# LegacyCharacter

虚拟角色

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

## Example

```python
from openapi_client.models.legacy_character import LegacyCharacter

# TODO update the JSON string below
json = "{}"
# create an instance of LegacyCharacter from a JSON string
legacy_character_instance = LegacyCharacter.from_json(json)
# print the JSON string representation of the object
print(LegacyCharacter.to_json())

# convert the object into a dict
legacy_character_dict = legacy_character_instance.to_dict()
# create an instance of LegacyCharacter from a dict
legacy_character_from_dict = LegacyCharacter.from_dict(legacy_character_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


