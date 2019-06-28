### MSAR
Metadata search and retrieval wrapper project

- see doc/draft_overview.png doc/backend_draft.png and doc/frontend-draft.png

## Short Description
MSAR is an application where images and corresponding json-based metadata can be stored and retrieved based on the additional data. The data will be generated using frameworks like detectron, yolo9000, facerecognition, etc. It is then indexed by the application using elasticsearch and can be retrieved using a free text search and conditional filtering. The application is generic regarding the structure of the indexed metadata.

![overview](https://raw.githubusercontent.com/tomkretzschmar/msar/master/doc/draft_overview.png)
