# CharacterRevision


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**type** | **int** |  | 
**creator** | [**Creator**](Creator.md) |  | [optional] 
**summary** | **str** |  | 
**created_at** | **datetime** |  | 
**data** | [**Dict[str, CharacterRevisionDataItem]**](CharacterRevisionDataItem.md) |  | [optional] 

## Example

```python
from openapi_client.models.character_revision import CharacterRevision

# TODO update the JSON string below
json = "{}"
# create an instance of CharacterRevision from a JSON string
character_revision_instance = CharacterRevision.from_json(json)
# print the JSON string representation of the object
print(CharacterRevision.to_json())

# convert the object into a dict
character_revision_dict = character_revision_instance.to_dict()
# create an instance of CharacterRevision from a dict
character_revision_from_dict = CharacterRevision.from_dict(character_revision_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


