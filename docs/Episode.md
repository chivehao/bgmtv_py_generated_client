# Episode


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**type** | **int** | &#x60;0&#x60; 本篇，&#x60;1&#x60; SP，&#x60;2&#x60; OP，&#x60;3&#x60; ED | 
**name** | **str** |  | 
**name_cn** | **str** |  | 
**sort** | **float** | 同类条目的排序和集数 | 
**ep** | **float** | 条目内的集数, 从&#x60;1&#x60;开始。非本篇剧集的此字段无意义 | [optional] 
**airdate** | **str** |  | 
**comment** | **int** |  | 
**duration** | **str** | 维基人填写的原始时长 | 
**desc** | **str** | 简介 | 
**disc** | **int** | 音乐曲目的碟片数 | 
**duration_seconds** | **int** | 服务器解析的时长，无法解析时为 &#x60;0&#x60; | [optional] 

## Example

```python
from openapi_client.models.episode import Episode

# TODO update the JSON string below
json = "{}"
# create an instance of Episode from a JSON string
episode_instance = Episode.from_json(json)
# print the JSON string representation of the object
print(Episode.to_json())

# convert the object into a dict
episode_dict = episode_instance.to_dict()
# create an instance of Episode from a dict
episode_from_dict = Episode.from_dict(episode_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


