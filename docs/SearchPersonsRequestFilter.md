# SearchPersonsRequestFilter

不同条件之间是 `且` 的关系

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**career** | **List[str]** | 职业，可以多次出现。多值之间为 &#x60;且&#x60; 关系。 | [optional] 

## Example

```python
from openapi_client.models.search_persons_request_filter import SearchPersonsRequestFilter

# TODO update the JSON string below
json = "{}"
# create an instance of SearchPersonsRequestFilter from a JSON string
search_persons_request_filter_instance = SearchPersonsRequestFilter.from_json(json)
# print the JSON string representation of the object
print(SearchPersonsRequestFilter.to_json())

# convert the object into a dict
search_persons_request_filter_dict = search_persons_request_filter_instance.to_dict()
# create an instance of SearchPersonsRequestFilter from a dict
search_persons_request_filter_from_dict = SearchPersonsRequestFilter.from_dict(search_persons_request_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


