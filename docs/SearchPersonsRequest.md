# SearchPersonsRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keyword** | **str** |  | 
**filter** | [**SearchPersonsRequestFilter**](SearchPersonsRequestFilter.md) |  | [optional] 

## Example

```python
from openapi_client.models.search_persons_request import SearchPersonsRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SearchPersonsRequest from a JSON string
search_persons_request_instance = SearchPersonsRequest.from_json(json)
# print the JSON string representation of the object
print(SearchPersonsRequest.to_json())

# convert the object into a dict
search_persons_request_dict = search_persons_request_instance.to_dict()
# create an instance of SearchPersonsRequest from a dict
search_persons_request_from_dict = SearchPersonsRequest.from_dict(search_persons_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


