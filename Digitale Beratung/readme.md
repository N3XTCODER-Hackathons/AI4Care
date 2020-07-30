# About the 'Digitale Beratung' dataset

## Overview

|METADATA||
|:-----|------|
|**topic**|A set of data for digital care consulting|
|**publisher**|mitunsleben GmbH|
|**soure**|generic in-house generated|
|**type**|synthetic|
|**format**|sql (mySQL export), db (LiteDB), docx (MS Word)|
|**licence**|[Open Data Commons Attribution Licence (ODC-By)](https://opendatacommons.org/licenses/by/summary/)|
|**publishing date/period**|TBA|

## Short description

## Fallbeispiele.docx
... contains a set of 10 typical request cases for care consultation

### wp_posts.sql
... contains the SQL export (mySQL) of the **wp-posts** table of a typical Wordpress installation. Beside some additional (meta-)data, the **post_content** column contains the HTML code describing typical pains, issues and challenges in the care sector

### Anbieter.db
... is a [LiteDB](https://github.com/mbdavid/LiteDB) database, containing synthetic data from offers and UPSs from care organizations and departments. [LiteDB.Studio](https://github.com/mbdavid/LiteDB.Studio) is the respective editor. 

The **department** collection contains items with **Type**, **Categories** and **USPs** properties, that might be helpful to match the organisation with the requests.
 
### A typical workflow...
... might consist of finding requirements in the request cases, based on the Wordpress posts, cluster all that into logical groups and matching it with the data from the LiteDB. 

## Inspiration: Optimised search experience

https://mitpflegeleben.de/informationsportal/ We can see various searches which need improvement...

1. import wp_posts.sql into your db
2. extract the wp_content field and strip HTML 
3. index in your favourite search engine (solr, elasticsearch, https://www.algolia.com/) and store the content for later retreiveal
4. define synonyms and stemming rules (e.g. German language plural matching, domain-specific synonyms like "demenz" -> "althzeimers")
5. qualitatively evaluate search results using the stored content

Deliverable: configuration for search engine, such that the same can be adapted for the production website.
