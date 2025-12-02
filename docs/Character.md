# Character


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**name** | **str** |  | 
**type** | [**CharacterType**](CharacterType.md) | 角色，机体，舰船，组织... | 
**images** | [**PersonImages**](PersonImages.md) | object with some size of images, this object maybe &#x60;null&#x60; | [optional] 
**summary** | **str** |  | 
**locked** | **bool** |  | 
**infobox** | **List[object]** | server parsed infobox, a map from key to string or tuple null if server infobox is not valid | [optional] 
**gender** | **str** | parsed from wiki, maybe null | [optional] 
**blood_type** | [**BloodType**](BloodType.md) | parsed from wiki, maybe null, &#x60;1, 2, 3, 4&#x60; for &#x60;A, B, AB, O&#x60; | [optional] 
**birth_year** | **int** | parsed from wiki, maybe &#x60;null&#x60; | [optional] 
**birth_mon** | **int** | parsed from wiki, maybe &#x60;null&#x60; | [optional] 
**birth_day** | **int** | parsed from wiki, maybe &#x60;null&#x60; | [optional] 
**stat** | [**Stat**](Stat.md) |  | 

## Example

```python
from openapi_client.models.character import Character

# TODO update the JSON string below
json = "{}"
# create an instance of Character from a JSON string
character_instance = Character.from_json(json)
# print the JSON string representation of the object
print(Character.to_json())

# convert the object into a dict
character_dict = character_instance.to_dict()
# create an instance of Character from a dict
character_from_dict = Character.from_dict(character_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


