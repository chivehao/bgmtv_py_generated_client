# User

实际的返回值可能包括文档未声明的 `url` 字段，此字段主要用于开发者从 api 响应直接转跳到网页。 客户端开发者请不用依赖于此特性，此字段的值随时可能会改变。 

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**username** | **str** | 唯一用户名，初始与 UID 相同，可修改一次 | 
**nickname** | **str** |  | 
**user_group** | [**UserGroup**](UserGroup.md) |  | 
**avatar** | [**Avatar**](Avatar.md) |  | 
**sign** | **str** | 个人签名 | 

## Example

```python
from openapi_client.models.user import User

# TODO update the JSON string below
json = "{}"
# create an instance of User from a JSON string
user_instance = User.from_json(json)
# print the JSON string representation of the object
print(User.to_json())

# convert the object into a dict
user_dict = user_instance.to_dict()
# create an instance of User from a dict
user_from_dict = User.from_dict(user_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


