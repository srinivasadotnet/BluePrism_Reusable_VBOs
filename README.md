# BluePrism_Reusable_VBOs
Reusable Components for BluePrism

* BPA Object - CollectionDateFormater.xml
  VBO can be used to update existing date format to required date format. Operation can be performed on Collection.
  
* BPA Object - AzureStorageUtility.xml
  VBO responsible for doing operations on Azure Blob Storage.
  
    Contains 4 actions
     * ListBlobItems
     * DownloadBlobItem
     * UploadBlobItem
     * DeleteBlobItem

* BPA Process - Oledb Query - Multiple Joins
  With the help of this process one can understand how to create multiple joins. 
  Video link can be found [here](https://youtu.be/KsoxpXumioM)
* BPA Object - SQL Bulk Update -
  Read bulk data from excel using oledb and insert them to Sql Server using SqlBulkInsert class.
  Video link can be found [here](https://youtu.be/rF2fw42LWl8)
* BPA Object - Extract Password Zip
  Extract password proted zip file using Blue Prism code stage. 
  We have used thrid party open source library named [DotNetZip.dll](https://github.com/haf/DotNetZip.Semverd). Library can be downloaded from gitrepo or nuget, for your usability have added it in [ExampleFile](/ExampleFile) folder. Demo Video can be found [here](https://youtu.be/cSxYyS8EmdE)
* BPA Object - Table Scrapper.bpobject
  Scrape data from HTML table and select required columns using code stage LINQ.
