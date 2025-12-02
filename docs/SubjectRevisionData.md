# SubjectRevisionData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**field_eps** | **int** |  | 
**field_infobox** | **str** |  | 
**field_summary** | **str** |  | 
**name** | **str** |  | 
**name_cn** | **str** |  | 
**platform** | **int** |  | 
**subject_id** | **int** |  | 
**type** | **int** |  | 
**type_id** | **int** |  | 
**vote_field** | **str** |  | 

## Example

```python
from openapi_client.models.subject_revision_data import SubjectRevisionData

# TODO update the JSON string below
json = "{}"
# create an instance of SubjectRevisionData from a JSON string
subject_revision_data_instance = SubjectRevisionData.from_json(json)
# print the JSON string representation of the object
print(SubjectRevisionData.to_json())

# convert the object into a dict
subject_revision_data_dict = subject_revision_data_instance.to_dict()
# create an instance of SubjectRevisionData from a dict
subject_revision_data_from_dict = SubjectRevisionData.from_dict(subject_revision_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


