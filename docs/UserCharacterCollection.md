# UserCharacterCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**name** | **str** |  | 
**type** | [**CharacterType**](CharacterType.md) | 角色，机体，舰船，组织... | 
**images** | [**PersonImages**](PersonImages.md) | object with some size of images, this object maybe &#x60;null&#x60; | [optional] 
**created_at** | **datetime** |  | 

## Example

```python
from openapi_client.models.user_character_collection import UserCharacterCollection

# TODO update the JSON string below
json = "{}"
# create an instance of UserCharacterCollection from a JSON string
user_character_collection_instance = UserCharacterCollection.from_json(json)
# print the JSON string representation of the object
print(UserCharacterCollection.to_json())

# convert the object into a dict
user_character_collection_dict = user_character_collection_instance.to_dict()
# create an instance of UserCharacterCollection from a dict
user_character_collection_from_dict = UserCharacterCollection.from_dict(user_character_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


