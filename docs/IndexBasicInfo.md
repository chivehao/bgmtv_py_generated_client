# IndexBasicInfo

新增或修改条目的内容，同名字段意义同<a href=\"#model-Subject\">Subject</a>

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **str** |  | [optional] 
**description** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.index_basic_info import IndexBasicInfo

# TODO update the JSON string below
json = "{}"
# create an instance of IndexBasicInfo from a JSON string
index_basic_info_instance = IndexBasicInfo.from_json(json)
# print the JSON string representation of the object
print(IndexBasicInfo.to_json())

# convert the object into a dict
index_basic_info_dict = index_basic_info_instance.to_dict()
# create an instance of IndexBasicInfo from a dict
index_basic_info_from_dict = IndexBasicInfo.from_dict(index_basic_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


