# IndexSubjectAddInfo

新增某条目到目录的请求信息

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**subject_id** | **int** |  | [optional] 
**sort** | **int** | 排序条件，越小越靠前 | [optional] 
**comment** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.index_subject_add_info import IndexSubjectAddInfo

# TODO update the JSON string below
json = "{}"
# create an instance of IndexSubjectAddInfo from a JSON string
index_subject_add_info_instance = IndexSubjectAddInfo.from_json(json)
# print the JSON string representation of the object
print(IndexSubjectAddInfo.to_json())

# convert the object into a dict
index_subject_add_info_dict = index_subject_add_info_instance.to_dict()
# create an instance of IndexSubjectAddInfo from a dict
index_subject_add_info_from_dict = IndexSubjectAddInfo.from_dict(index_subject_add_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


