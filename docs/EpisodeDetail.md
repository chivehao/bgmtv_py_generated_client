# EpisodeDetail


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**type** | [**EpType**](EpType.md) |  | 
**name** | **str** |  | 
**name_cn** | **str** |  | 
**sort** | **float** | 同类条目的排序和集数 | 
**ep** | **float** | 条目内的集数, 从&#x60;1&#x60;开始。非本篇剧集的此字段无意义 | [optional] 
**airdate** | **str** |  | 
**comment** | **int** |  | 
**duration** | **str** |  | 
**desc** | **str** | 简介 | 
**disc** | **int** | 音乐曲目的碟片数 | 
**subject_id** | **int** |  | 

## Example

```python
from openapi_client.models.episode_detail import EpisodeDetail

# TODO update the JSON string below
json = "{}"
# create an instance of EpisodeDetail from a JSON string
episode_detail_instance = EpisodeDetail.from_json(json)
# print the JSON string representation of the object
print(EpisodeDetail.to_json())

# convert the object into a dict
episode_detail_dict = episode_detail_instance.to_dict()
# create an instance of EpisodeDetail from a dict
episode_detail_from_dict = EpisodeDetail.from_dict(episode_detail_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


