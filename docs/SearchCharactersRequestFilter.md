# SearchCharactersRequestFilter

不同条件之间是 `且` 的关系

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**nsfw** | **bool** | 无权限的用户会直接忽略此字段，不会返回 R18 角色。  默认或者 &#x60;null&#x60; 会返回包含 R18 的所有搜索结果。  &#x60;true&#x60; 只会返回 R18 角色。  &#x60;false&#x60; 只会返回非 R18 角色。  | [optional] 

## Example

```python
from openapi_client.models.search_characters_request_filter import SearchCharactersRequestFilter

# TODO update the JSON string below
json = "{}"
# create an instance of SearchCharactersRequestFilter from a JSON string
search_characters_request_filter_instance = SearchCharactersRequestFilter.from_json(json)
# print the JSON string representation of the object
print(SearchCharactersRequestFilter.to_json())

# convert the object into a dict
search_characters_request_filter_dict = search_characters_request_filter_instance.to_dict()
# create an instance of SearchCharactersRequestFilter from a dict
search_characters_request_filter_from_dict = SearchCharactersRequestFilter.from_dict(search_characters_request_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


