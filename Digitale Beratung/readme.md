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