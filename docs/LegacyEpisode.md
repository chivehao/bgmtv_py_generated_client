# LegacyEpisode

章节信息

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | 章节 ID | [optional] 
**url** | **str** | 章节地址 | [optional] 
**type** | [**LegacyEpisodeType**](LegacyEpisodeType.md) |  | [optional] 
**sort** | **int** | 集数 | [optional] 
**name** | **str** | 标题 | [optional] 
**name_cn** | **str** | 简体中文标题 | [optional] 
**duration** | **str** | 时长 | [optional] 
**airdate** | **str** | 放送日期 | [optional] 
**comment** | **int** | 回复数量 | [optional] 
**desc** | **str** | 简介 | [optional] 
**status** | **str** | 放送状态 &lt;br&gt; Air &#x3D; 已放送 &lt;br&gt; Today &#x3D; 正在放送 &lt;br&gt; NA &#x3D; 未放送 | [optional] 

## Example

```python
from openapi_client.models.legacy_episode import LegacyEpisode

# TODO update the JSON string below
json = "{}"
# create an instance of LegacyEpisode from a JSON string
legacy_episode_instance = LegacyEpisode.from_json(json)
# print the JSON string representation of the object
print(LegacyEpisode.to_json())

# convert the object into a dict
legacy_episode_dict = legacy_episode_instance.to_dict()
# create an instance of LegacyEpisode from a dict
legacy_episode_from_dict = LegacyEpisode.from_dict(legacy_episode_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


