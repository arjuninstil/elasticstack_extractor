# ElasticSearchExporter.export

A simple object constructor with a method which combines attributes of elasticsearch package to extract data from elasticstack with some parameters added by the client

![](https://github.com/arjuninstil/elasticstack_extractor/tree/master/Images)

### Parameters :
* host – node to be connected to
* UserName , Password- username and password to access the es node through http_auth
* indexDbName – name of the index to scope the operation
* queryJson – body of the search() api
* form – data type of the data to be extracted (dataframe, json)
* fields – extracts only specific fields within the data (Topic/Payload/all)
* size – size of the batch send at each iteration
* timeout – operation timeout
* start – start date
* end – end date
