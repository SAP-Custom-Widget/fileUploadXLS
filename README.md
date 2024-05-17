

<img src="https://raw.githubusercontent.com/SAP-Custom-Widget/fileUploadXLS/main/icon.png" width="100">

## SAC-P Custom Widget: fileUploadXLS
A custom widget designed to work with Excel or XLS files, helping you retrieve file data in JSON, raw, and multiple other formats

## Installation
To use this widget in your SAP application, follow these steps:

<a target="_blank" href="https://sap-custom-widget.github.io/?dl=fileUploadXLS"><img width="150" src="https://raw.githubusercontent.com/SAP-Custom-Widget/sap-custom-widget.github.io/main/download.png"/></a>
- Download the `fileUploadXLS.json` file from the URLs specified in the webcomponents property of the JSON.
- Go to your SAC Portal, select Analytic Application from the left side bar, and then go to the Custom Widget tab.
- Click on the + icon on the right side and select the `fileUploadXLS.json` file that you downloaded.
- You're done! You can now use it in your app.

## Methods
The widget has the following methods:

### Set Methods

|  Method | Parameter Type  | Description  |
| ------------ | ------------ | ------------ |
| setHierarchyStructure(hierarchy) | Selection/Object `array` |  Sets the hierarchical structure for the data. |
| setFilterByValue(filterByValue) | Selection/Object `array`|  Applies a filter to records based on a constant value. |
|setFilterByContains(filterByContains)| Selection/Object `array` |Applies a filter to records based on a value that contains a specific character.|

### get Methods

|  Method | Return Type | Description  |
| ------------ | ------------ | ------------ |
| getDataAsJson()  | Selection/Object `array` |  Retrieves uploaded data in JSON/Selection/Object format. |
| getDataAsRaw()  | string |  Retrieves uploaded data in raw string format |
|getTotalRecordsCount()| integer|Gets the total count of records|
|getHeaders()| string[] `array` |Gets the headers of uploaded data as an array.|

## About
This sac-p custom widget is developed by [Rohit Chouhan](http://linkedin.com/in/itsrohitchouhan "Rohit Chouhan")

