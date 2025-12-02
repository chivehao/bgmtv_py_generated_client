# SearchSubjectsRequestFilter

不同条件之间是 `且` 的关系

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | [**List[SubjectType]**](SubjectType.md) | 条目类型，参照 &#x60;SubjectType&#x60; enum，多值之间为 &#x60;或&#x60; 的关系。 | [optional] 
**meta_tags** | **List[str]** | 公共标签。多个值之间为 &#x60;且&#x60; 关系。可以用 &#x60;-&#x60; 排除标签。比如 &#x60;-科幻&#x60; 可以排除科幻标签。 | [optional] 
**tag** | **List[str]** | 标签，可以多次出现。多值之间为 &#x60;且&#x60; 关系。 | [optional] 
**air_date** | **List[str]** | 播出日期/发售日期，日期必需为 &#x60;YYYY-MM-DD&#x60; 格式。多值之间为 &#x60;且&#x60; 关系。 | [optional] 
**rating** | **List[str]** | 用于搜索指定评分的条目，多值之间为 &#x60;且&#x60; 关系。 | [optional] 
**rating_count** | **List[str]** | 用于按照评分人数筛选条目，多值之间为 &#x60;且&#x60; 关系，格式与 &#x60;rating&#x60; 相同。 | [optional] 
**rank** | **List[str]** | 用于搜索指定排名的条目，多值之间为 &#x60;且&#x60; 关系。 | [optional] 
**nsfw** | **bool** | 无权限的用户会直接忽略此字段，不会返回R18条目。  默认或者 &#x60;null&#x60; 会返回包含 R18 的所有搜索结果。  &#x60;true&#x60; 只会返回 R18 条目。  &#x60;false&#x60; 只会返回非 R18 条目。  | [optional] 

## Example

```python
from openapi_client.models.search_subjects_request_filter import SearchSubjectsRequestFilter

# TODO update the JSON string below
json = "{}"
# create an instance of SearchSubjectsRequestFilter from a JSON string
search_subjects_request_filter_instance = SearchSubjectsRequestFilter.from_json(json)
# print the JSON string representation of the object
print(SearchSubjectsRequestFilter.to_json())

# convert the object into a dict
search_subjects_request_filter_dict = search_subjects_request_filter_instance.to_dict()
# create an instance of SearchSubjectsRequestFilter from a dict
search_subjects_request_filter_from_dict = SearchSubjectsRequestFilter.from_dict(search_subjects_request_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


