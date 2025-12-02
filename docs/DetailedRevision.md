# DetailedRevision


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**type** | **int** |  | 
**creator** | [**Creator**](Creator.md) |  | [optional] 
**summary** | **str** |  | 
**created_at** | **datetime** |  | 
**data** | **object** | 编辑修改内容，响应类型不固定 | [optional] 

## Example

```python
from openapi_client.models.detailed_revision import DetailedRevision

# TODO update the JSON string below
json = "{}"
# create an instance of DetailedRevision from a JSON string
detailed_revision_instance = DetailedRevision.from_json(json)
# print the JSON string representation of the object
print(DetailedRevision.to_json())

# convert the object into a dict
detailed_revision_dict = detailed_revision_instance.to_dict()
# create an instance of DetailedRevision from a dict
detailed_revision_from_dict = DetailedRevision.from_dict(detailed_revision_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


