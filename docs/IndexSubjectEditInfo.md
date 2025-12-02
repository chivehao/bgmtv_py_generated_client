# IndexSubjectEditInfo

修改目录中条目的信息

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sort** | **int** | 排序条件，越小越靠前 | [optional] 
**comment** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.index_subject_edit_info import IndexSubjectEditInfo

# TODO update the JSON string below
json = "{}"
# create an instance of IndexSubjectEditInfo from a JSON string
index_subject_edit_info_instance = IndexSubjectEditInfo.from_json(json)
# print the JSON string representation of the object
print(IndexSubjectEditInfo.to_json())

# convert the object into a dict
index_subject_edit_info_dict = index_subject_edit_info_instance.to_dict()
# create an instance of IndexSubjectEditInfo from a dict
index_subject_edit_info_from_dict = IndexSubjectEditInfo.from_dict(index_subject_edit_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


