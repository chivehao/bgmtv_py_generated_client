# SearchSubjectsRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keyword** | **str** |  | 
**sort** | **str** | 排序规则  - &#x60;match&#x60; meilisearch 的默认排序，按照匹配程度 - &#x60;heat&#x60; 收藏人数 - &#x60;rank&#x60; 排名由高到低 - &#x60;score&#x60; 评分  | [optional] [default to 'match']
**filter** | [**SearchSubjectsRequestFilter**](SearchSubjectsRequestFilter.md) |  | [optional] 

## Example

```python
from openapi_client.models.search_subjects_request import SearchSubjectsRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SearchSubjectsRequest from a JSON string
search_subjects_request_instance = SearchSubjectsRequest.from_json(json)
# print the JSON string representation of the object
print(SearchSubjectsRequest.to_json())

# convert the object into a dict
search_subjects_request_dict = search_subjects_request_instance.to_dict()
# create an instance of SearchSubjectsRequest from a dict
search_subjects_request_from_dict = SearchSubjectsRequest.from_dict(search_subjects_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


