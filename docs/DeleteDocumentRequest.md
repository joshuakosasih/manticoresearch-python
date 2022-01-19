# DeleteDocumentRequest

Payload for delete request. Documents can be deleted either one by one by specifying the document id or by providing a query object. For more information see  [Delete API](https://docs.manticoresearch.com/latest/html/http_reference/json_delete.html) 
## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**index** | **str** | Index name | 
**cluster** | **str** | cluster name | [optional] 
**id** | **int** | Document ID | [optional] 
**query** | [**{str: (bool, date, datetime, dict, float, int, list, str, none_type)}**](.md) | Query tree object | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


