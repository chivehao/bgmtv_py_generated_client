# LegacySubjectMediumAllOfStaff


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
**role_name** | **str** | 人物类型 | [optional] 
**jobs** | **List[str]** | 职位 | [optional] 

## Example

```python
from openapi_client.models.legacy_subject_medium_all_of_staff import LegacySubjectMediumAllOfStaff

# TODO update the JSON string below
json = "{}"
# create an instance of LegacySubjectMediumAllOfStaff from a JSON string
legacy_subject_medium_all_of_staff_instance = LegacySubjectMediumAllOfStaff.from_json(json)
# print the JSON string representation of the object
print(LegacySubjectMediumAllOfStaff.to_json())

# convert the object into a dict
legacy_subject_medium_all_of_staff_dict = legacy_subject_medium_all_of_staff_instance.to_dict()
# create an instance of LegacySubjectMediumAllOfStaff from a dict
legacy_subject_medium_all_of_staff_from_dict = LegacySubjectMediumAllOfStaff.from_dict(legacy_subject_medium_all_of_staff_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


