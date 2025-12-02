# GetMyself200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**username** | **str** | 唯一用户名，初始与 UID 相同，可修改一次 | 
**nickname** | **str** |  | 
**user_group** | [**UserGroup**](UserGroup.md) |  | 
**avatar** | [**Avatar**](Avatar.md) |  | 
**sign** | **str** | 个人签名 | 
**email** | **str** | 用户绑定的邮箱地址 | [optional] 
**reg_time** | **datetime** | 用户注册时间。比如 2017-12-03T08:51:16+08:00 | [optional] 
**time_offset** | **int** | 用户设置的时区偏移，以小时为单位。比如 GMT+8（shanghai/beijing）为 8 | [optional] 

## Example

```python
from openapi_client.models.get_myself200_response import GetMyself200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetMyself200Response from a JSON string
get_myself200_response_instance = GetMyself200Response.from_json(json)
# print the JSON string representation of the object
print(GetMyself200Response.to_json())

# convert the object into a dict
get_myself200_response_dict = get_myself200_response_instance.to_dict()
# create an instance of GetMyself200Response from a dict
get_myself200_response_from_dict = GetMyself200Response.from_dict(get_myself200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


