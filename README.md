# The Royal Armoury, Skokloster Castle and the Hallwyl Museum Collection 

Welcome to The Royal Armoury, Skokloster Castle and the Hallwyl Museum (In Swedish: *Livrustkammaren och Skoklosters slott med Stiftelsen Hallwylska museet* ([LSH] (http://www.lsh.se)).

Here you will find datasets with metadata of about 91,000 museum objects from the collection management system used by the three Swedish museums. The purpose with these datasets is to provide as much free open museum data as possible – all licensed with [CC0] (https://creativecommons.org/publicdomain/zero/1.0/). There is data about the museum objects, names and usage of the objects in historical events (please see the detailed description for each CSV-file).

### Dataset Description
You will find a detailed description of each CSV-file (where each column is described) either in our [wiki] (https://github.com/lshSWE/collection/wiki) or in the *LSH on GitHub - CSV Descriptions.csv*-file inside the repository.

### File format
The metadata is stored in CSV-files (UTF-16 - vertical bar as column separator). The CSV-files are exported from the SQL-based collection management system used by the three museums. In every CSV-file you will find primary and foreign keys to other tables, which means that it is possible to rebuild an relational database with the datasets. Each CSV-file represent an SQL-table, and each CSV-file is stored within an TAR archive file (gzip). 

### Images are not included
Images are not included in the datasets. You can however find all of our high resolution images on [Wikimedia Commons] (https://commons.wikimedia.org/wiki/Commons:Livrustkammaren_och_Skoklosters_slott_med_Stiftelsen_Hallwylska_museet/sv). 

### Language
At the moment most of the data is in Swedish, but future uploads may contain translations in English.

### Data In Progress
This data is provided “as is” and you use this data at your own risk. Much of the information included in this dataset is not complete and has not been curatorially approved. Much of the information in the datasets have been added during a very long historical time and within the datasets it is possible that old museum catalogue texts exist that may not have been recently edited - information that we would today consider discriminating. However, the collection management system used by the three museums is continuously being updated and edited, and new dataset exports will be uploaded to GitHub on a regular basis. It is also possible that further tables may be added to the datasets. Please notice that LSH offers the datasets as-is and makes no representations or warranties of any kind.

### Pull Requests
Because these datasets are generated from our internal collection management system, we do not accept pull requests. If you have identified errors or have extra information to share, please [contact us] (http://lsh.se/en/contact-us).

### Usage and modifications
* Please do not use the metadata in a way that suggests you have any official status or that LSH endorses you or your use of the metadata, unless you have prior permission to do so.
* Please do not mislead others or misrepresent the metadata or its sources.
* Please make the metadata and any improvements thereto freely available under the same terms as LSH, i.e., without claiming any legal right to, or imposing any legally binding conditions on access to the metadata or your improvements.

*The writers of these guidelines wish to thank [Europeana] (http://www.europeana.eu), [Museum of Modern Art] (http://www.moma.org), [Tate] (http://www.tate.org.uk) and [Cooper Hewitt, Smithsonian Design Museum] (http://cooperhewitt.org).*
