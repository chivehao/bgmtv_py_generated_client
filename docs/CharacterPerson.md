# CharacterPerson


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**name** | **str** |  | 
**type** | [**CharacterType**](CharacterType.md) | 角色，机体，舰船，组织... | 
**images** | [**PersonImages**](PersonImages.md) | object with some size of images, this object maybe &#x60;null&#x60; | [optional] 
**subject_id** | **int** |  | 
**subject_type** | [**SubjectType**](SubjectType.md) |  | 
**subject_name** | **str** |  | 
**subject_name_cn** | **str** |  | 
**staff** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.character_person import CharacterPerson

# TODO update the JSON string below
json = "{}"
# create an instance of CharacterPerson from a JSON string
character_person_instance = CharacterPerson.from_json(json)
# print the JSON string representation of the object
print(CharacterPerson.to_json())

# convert the object into a dict
character_person_dict = character_person_instance.to_dict()
# create an instance of CharacterPerson from a dict
character_person_from_dict = CharacterPerson.from_dict(character_person_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


