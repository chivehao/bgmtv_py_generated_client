# LegacyTopic

讨论版

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID | [optional] 
**url** | **str** | 地址 | [optional] 
**title** | **str** | 标题 | [optional] 
**main_id** | **int** | 所属对象（条目） ID | [optional] 
**timestamp** | **int** | 发布时间 | [optional] 
**lastpost** | **int** | 最后回复时间 | [optional] 
**replies** | **int** | 回复数 | [optional] 
**user** | [**LegacyUser**](LegacyUser.md) |  | [optional] 

## Example

```python
from openapi_client.models.legacy_topic import LegacyTopic

# TODO update the JSON string below
json = "{}"
# create an instance of LegacyTopic from a JSON string
legacy_topic_instance = LegacyTopic.from_json(json)
# print the JSON string representation of the object
print(LegacyTopic.to_json())

# convert the object into a dict
legacy_topic_dict = legacy_topic_instance.to_dict()
# create an instance of LegacyTopic from a dict
legacy_topic_from_dict = LegacyTopic.from_dict(legacy_topic_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


