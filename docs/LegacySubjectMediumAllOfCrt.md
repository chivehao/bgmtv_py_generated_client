# LegacySubjectMediumAllOfCrt


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | 人物 ID | [optional] 
**url** | **str** | 人物地址 | [optional] 
**name** | **str** | 姓名 | [optional] 
**images** | [**LegacyMonoBaseImages**](LegacyMonoBaseImages.md) |  | [optional] 
**name_cn** | **str** | 简体中文名 | [optional] 
**comment** | **int** | 回复数量 | [optional] 
**collects** | **int** | 收藏人数 | [optional] 
**info** | [**LegacyMonoInfo**](LegacyMonoInfo.md) |  | [optional] 
**actors** | [**List[LegacyMonoBase]**](LegacyMonoBase.md) | 声优列表 | [optional] 
**role_name** | **str** | 角色类型 | [optional] 

## Example

```python
from openapi_client.models.legacy_subject_medium_all_of_crt import LegacySubjectMediumAllOfCrt

# TODO update the JSON string below
json = "{}"
# create an instance of LegacySubjectMediumAllOfCrt from a JSON string
legacy_subject_medium_all_of_crt_instance = LegacySubjectMediumAllOfCrt.from_json(json)
# print the JSON string representation of the object
print(LegacySubjectMediumAllOfCrt.to_json())

# convert the object into a dict
legacy_subject_medium_all_of_crt_dict = legacy_subject_medium_all_of_crt_instance.to_dict()
# create an instance of LegacySubjectMediumAllOfCrt from a dict
legacy_subject_medium_all_of_crt_from_dict = LegacySubjectMediumAllOfCrt.from_dict(legacy_subject_medium_all_of_crt_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


