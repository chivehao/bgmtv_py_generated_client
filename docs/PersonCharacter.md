# PersonCharacter


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
from openapi_client.models.person_character import PersonCharacter

# TODO update the JSON string below
json = "{}"
# create an instance of PersonCharacter from a JSON string
person_character_instance = PersonCharacter.from_json(json)
# print the JSON string representation of the object
print(PersonCharacter.to_json())

# convert the object into a dict
person_character_dict = person_character_instance.to_dict()
# create an instance of PersonCharacter from a dict
person_character_from_dict = PersonCharacter.from_dict(person_character_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


