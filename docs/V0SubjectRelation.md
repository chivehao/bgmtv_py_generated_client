# V0SubjectRelation


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**type** | **int** |  | 
**name** | **str** |  | 
**name_cn** | **str** |  | 
**images** | [**Images**](Images.md) |  | [optional] 
**relation** | **str** |  | 

## Example

```python
from openapi_client.models.v0_subject_relation import V0SubjectRelation

# TODO update the JSON string below
json = "{}"
# create an instance of V0SubjectRelation from a JSON string
v0_subject_relation_instance = V0SubjectRelation.from_json(json)
# print the JSON string representation of the object
print(V0SubjectRelation.to_json())

# convert the object into a dict
v0_subject_relation_dict = v0_subject_relation_instance.to_dict()
# create an instance of V0SubjectRelation from a dict
v0_subject_relation_from_dict = V0SubjectRelation.from_dict(v0_subject_relation_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


