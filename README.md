# K2 for Adobe Experience Manager

There are two swagger definitions available:
1. Adobe.AEM-Assets.v1.0.0.json
1. Adobe.AEM-Workflow.v1.0.0.json

## AEM Assets
The Swagger can be used with the K2 REST broker, enabling one to work with AEM Assets and Folders in K2 Classic and K2 Cloud. The following actions have been exposed:
### Assets
- Create an Asset 
- Add Comment to an Asset
- Create an Asset Rendition
- Update an Asset's Metadata

### Folders
- Create a Folder
- Retrieve a Folder's Listing

## AEM Workflow
This Swagger file can be used with the K2 REST broker, enabling one to work with AEM Workflows and Tasks in K2 Classic and K2 Cloud. The following actions have been exposed:
### Workflows
- Get list of all active workflow instances
- Start a new Workflow Instance
- Get a Workflow Instance by ID

### Tasks
- Get a list of Tasks
- Get a workflow instance's routes by ID
- Complete or Advance an Item

