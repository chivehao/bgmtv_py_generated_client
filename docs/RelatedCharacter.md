# RelatedCharacter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**name** | **str** |  | 
**type** | [**CharacterType**](CharacterType.md) | 角色，机体，舰船，组织... | 
**images** | [**PersonImages**](PersonImages.md) | object with some size of images, this object maybe &#x60;null&#x60; | [optional] 
**relation** | **str** |  | 
**actors** | [**List[Person]**](Person.md) | 演员列表 | [optional] [default to []]

## Example

```python
from openapi_client.models.related_character import RelatedCharacter

# TODO update the JSON string below
json = "{}"
# create an instance of RelatedCharacter from a JSON string
related_character_instance = RelatedCharacter.from_json(json)
# print the JSON string representation of the object
print(RelatedCharacter.to_json())

# convert the object into a dict
related_character_dict = related_character_instance.to_dict()
# create an instance of RelatedCharacter from a dict
related_character_from_dict = RelatedCharacter.from_dict(related_character_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


