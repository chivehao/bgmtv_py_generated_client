# LegacyPerson

现实人物

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

## Example

```python
from openapi_client.models.legacy_person import LegacyPerson

# TODO update the JSON string below
json = "{}"
# create an instance of LegacyPerson from a JSON string
legacy_person_instance = LegacyPerson.from_json(json)
# print the JSON string representation of the object
print(LegacyPerson.to_json())

# convert the object into a dict
legacy_person_dict = legacy_person_instance.to_dict()
# create an instance of LegacyPerson from a dict
legacy_person_from_dict = LegacyPerson.from_dict(legacy_person_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


