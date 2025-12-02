# LegacyUser

用户信息

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | 用户 id | [optional] 
**url** | **str** | 用户主页地址 | [optional] 
**username** | **str** | 用户名 | [optional] 
**nickname** | **str** | 昵称 | [optional] 
**avatar** | [**LegacyUserAvatar**](LegacyUserAvatar.md) |  | [optional] 
**sign** | **str** | 签名 | [optional] 
**usergroup** | [**LegacyUserGroup**](LegacyUserGroup.md) |  | [optional] 

## Example

```python
from openapi_client.models.legacy_user import LegacyUser

# TODO update the JSON string below
json = "{}"
# create an instance of LegacyUser from a JSON string
legacy_user_instance = LegacyUser.from_json(json)
# print the JSON string representation of the object
print(LegacyUser.to_json())

# convert the object into a dict
legacy_user_dict = legacy_user_instance.to_dict()
# create an instance of LegacyUser from a dict
legacy_user_from_dict = LegacyUser.from_dict(legacy_user_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


