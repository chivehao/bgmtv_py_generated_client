# PersonRevision


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**type** | **int** |  | 
**creator** | [**Creator**](Creator.md) |  | [optional] 
**summary** | **str** |  | 
**created_at** | **datetime** |  | 
**data** | [**Dict[str, PersonRevisionDataItem]**](PersonRevisionDataItem.md) |  | [optional] 

## Example

```python
from openapi_client.models.person_revision import PersonRevision

# TODO update the JSON string below
json = "{}"
# create an instance of PersonRevision from a JSON string
person_revision_instance = PersonRevision.from_json(json)
# print the JSON string representation of the object
print(PersonRevision.to_json())

# convert the object into a dict
person_revision_dict = person_revision_instance.to_dict()
# create an instance of PersonRevision from a dict
person_revision_from_dict = PersonRevision.from_dict(person_revision_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


