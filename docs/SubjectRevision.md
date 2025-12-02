# SubjectRevision


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**type** | **int** |  | 
**creator** | [**Creator**](Creator.md) |  | [optional] 
**summary** | **str** |  | 
**created_at** | **datetime** |  | 
**data** | [**SubjectRevisionData**](SubjectRevisionData.md) |  | [optional] 

## Example

```python
from openapi_client.models.subject_revision import SubjectRevision

# TODO update the JSON string below
json = "{}"
# create an instance of SubjectRevision from a JSON string
subject_revision_instance = SubjectRevision.from_json(json)
# print the JSON string representation of the object
print(SubjectRevision.to_json())

# convert the object into a dict
subject_revision_dict = subject_revision_instance.to_dict()
# create an instance of SubjectRevision from a dict
subject_revision_from_dict = SubjectRevision.from_dict(subject_revision_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


