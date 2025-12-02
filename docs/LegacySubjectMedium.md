# LegacySubjectMedium


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | 条目 ID | [optional] 
**url** | **str** | 条目地址 | [optional] 
**type** | **int** | 条目类型 - &#x60;1&#x60; 为 书籍 - &#x60;2&#x60; 为 动画 - &#x60;3&#x60; 为 音乐 - &#x60;4&#x60; 为 游戏 - &#x60;6&#x60; 为 三次元  没有 &#x60;5&#x60; | [optional] 
**name** | **str** | 条目名称 | [optional] 
**name_cn** | **str** | 条目中文名称 | [optional] 
**summary** | **str** | 剧情简介 | [optional] 
**air_date** | **str** | 放送开始日期 | [optional] 
**air_weekday** | **int** | 放送星期 | [optional] 
**images** | [**LegacySubjectSmallImages**](LegacySubjectSmallImages.md) |  | [optional] 
**eps** | **int** | 话数 | [optional] 
**eps_count** | **int** | 话数 | [optional] 
**rating** | [**LegacySubjectSmallRating**](LegacySubjectSmallRating.md) |  | [optional] 
**rank** | **int** | 排名 | [optional] 
**collection** | [**LegacySubjectSmallCollection**](LegacySubjectSmallCollection.md) |  | [optional] 
**crt** | [**List[LegacySubjectMediumAllOfCrt]**](LegacySubjectMediumAllOfCrt.md) | 角色信息 | [optional] 
**staff** | [**List[LegacySubjectMediumAllOfStaff]**](LegacySubjectMediumAllOfStaff.md) | 制作人员信息 | [optional] 

## Example

```python
from openapi_client.models.legacy_subject_medium import LegacySubjectMedium

# TODO update the JSON string below
json = "{}"
# create an instance of LegacySubjectMedium from a JSON string
legacy_subject_medium_instance = LegacySubjectMedium.from_json(json)
# print the JSON string representation of the object
print(LegacySubjectMedium.to_json())

# convert the object into a dict
legacy_subject_medium_dict = legacy_subject_medium_instance.to_dict()
# create an instance of LegacySubjectMedium from a dict
legacy_subject_medium_from_dict = LegacySubjectMedium.from_dict(legacy_subject_medium_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


