# SearchCharactersRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keyword** | **str** |  | 
**filter** | [**SearchCharactersRequestFilter**](SearchCharactersRequestFilter.md) |  | [optional] 

## Example

```python
from openapi_client.models.search_characters_request import SearchCharactersRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SearchCharactersRequest from a JSON string
search_characters_request_instance = SearchCharactersRequest.from_json(json)
# print the JSON string representation of the object
print(SearchCharactersRequest.to_json())

# convert the object into a dict
search_characters_request_dict = search_characters_request_instance.to_dict()
# create an instance of SearchCharactersRequest from a dict
search_characters_request_from_dict = SearchCharactersRequest.from_dict(search_characters_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


