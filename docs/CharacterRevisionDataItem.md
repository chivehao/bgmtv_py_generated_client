# CharacterRevisionDataItem


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**infobox** | **str** |  | 
**summary** | **str** |  | 
**name** | **str** |  | 
**extra** | [**RevisionExtra**](RevisionExtra.md) |  | 

## Example

```python
from openapi_client.models.character_revision_data_item import CharacterRevisionDataItem

# TODO update the JSON string below
json = "{}"
# create an instance of CharacterRevisionDataItem from a JSON string
character_revision_data_item_instance = CharacterRevisionDataItem.from_json(json)
# print the JSON string representation of the object
print(CharacterRevisionDataItem.to_json())

# convert the object into a dict
character_revision_data_item_dict = character_revision_data_item_instance.to_dict()
# create an instance of CharacterRevisionDataItem from a dict
character_revision_data_item_from_dict = CharacterRevisionDataItem.from_dict(character_revision_data_item_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


