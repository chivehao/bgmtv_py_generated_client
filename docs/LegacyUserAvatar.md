# LegacyUserAvatar

头像地址

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**large** | **str** |  | [optional] 
**medium** | **str** |  | [optional] 
**small** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.legacy_user_avatar import LegacyUserAvatar

# TODO update the JSON string below
json = "{}"
# create an instance of LegacyUserAvatar from a JSON string
legacy_user_avatar_instance = LegacyUserAvatar.from_json(json)
# print the JSON string representation of the object
print(LegacyUserAvatar.to_json())

# convert the object into a dict
legacy_user_avatar_dict = legacy_user_avatar_instance.to_dict()
# create an instance of LegacyUserAvatar from a dict
legacy_user_avatar_from_dict = LegacyUserAvatar.from_dict(legacy_user_avatar_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


