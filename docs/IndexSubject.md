# IndexSubject

同名字段意义同<a href=\"#model-Subject\">Subject</a>

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**type** | **int** |  | 
**name** | **str** |  | 
**images** | [**Images**](Images.md) |  | [optional] 
**infobox** | [**List[Item]**](Item.md) |  | [optional] 
**var_date** | **str** |  | [optional] 
**comment** | **str** |  | 
**added_at** | **datetime** |  | 

## Example

```python
from openapi_client.models.index_subject import IndexSubject

# TODO update the JSON string below
json = "{}"
# create an instance of IndexSubject from a JSON string
index_subject_instance = IndexSubject.from_json(json)
# print the JSON string representation of the object
print(IndexSubject.to_json())

# convert the object into a dict
index_subject_dict = index_subject_instance.to_dict()
# create an instance of IndexSubject from a dict
index_subject_from_dict = IndexSubject.from_dict(index_subject_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


