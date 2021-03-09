# Document-Understanding-Overview
Contains the default Document Understanding workflow

# Important notes
  - This workflow is just for overview purposes, which means it doesn't work immediately
  - If you want to run it properly, follow the steps below, but bear in my mind that we will provide more detailed videos about the below subjects in the future
  
# What to do
## In the Variables panel
  - Write the path of the directory that contains the documents to be processed on the default value of the "DirectoryPath" variable
  - Write the path where the extracted data worksheet should be written on the default value of the "WorkbookPath" variable
  - Write your Document Understanding API Key on the default value of the "ApiKey" variable
  - Write the path of the directory to which the processed documents should be moved to on the default value of the "MovePath" variable
  - Write the path of the directory to which the unknown documents should be moved to on the default value of the "UnknownPath" variable

## In the Taxonomy Manager
  - The taxonomy must be created, with the types of documents and the fields desired

## In the Digitization step
  - An OCR engine must be selected, and its API Key, credentials or other fields must be provided

## In the Classification step
  - One or more Classifiers must be selected and trained in the "Manage Learning" option 
  - After the training, the configuration must be made in the "Configure Classifiers" option

## In the Extraction Step
  - One or more Extractors must be selected, and trained in the "Manage Templates" option
  - After the training, the configuration must be made in the "Configure Extractors" option

## In the Train Classifier step
  - The training must be configured in the "Configure Classifiers" option
