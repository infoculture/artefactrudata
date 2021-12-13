# Artefact.app dataset and source code
## Source code

All data collected using APIBackuper tool (https://github.com/ruarxive/apibackuper) using apibackuper.cfg 
for each dataset.

To download/update any of datasets go to dataset dir "artefact-orgs" and use command **run**
`apibackuper run full` to extract full dataset from source. Original JSON files will be stored to the "storage/storage.zip" file.

Use command **export** to get dataset from stored data `apibackuper export jsonl data.jsonl` file data will 
be stored as **data.jsonl**

To download files from original source use command **getfiles** with apibackuper tool 
`apibackuper getfiles`. It will store all files to the "storage/files" directory.


## Datasets
Data from Artefact.app project of the Ministry of Culture of Russian federation.
Collected for educational and scientific purposes by Infoculture (https://infoculture.ru) team.

All data collected as JSON lines files (*.jsonl) extension.

Source API: https://artefact.app/public_api/

List of datasets ("data/" dir):
* collections - collections of art
* projects - art projects
* subjects - art
* orgs - organizations (museums)
* tags - tags
* places - places, locations

For all "subjects" and "orgs" images downloaded from "topImage" attribute with ".jpg" file extension added.

Not yet processed:
- labels
- persons
- images

[pushkin-artefact-objects-MA.xlsx](https://github.com/infoculture/artefactrudata/blob/main/data/subjects/pushkin-artefact-objects-MA.xlsx) — dataset with the preliminary results of image recognition using Microsoft Azure. The images belong to the Pushkin Museum objects from the Artefact.app database.

## Licenses

Source code and packaged data licensed under CC0-1.0 License. 
Original content licensed under following terms https://artefact.app/terms.html
All IP rights on images belongs to museums published these images on Artefact.app.
