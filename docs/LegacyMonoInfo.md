# LegacyMonoInfo

人物信息

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**birth** | **str** | 生日 | [optional] 
**height** | **str** | 身高 | [optional] 
**gender** | **str** | 性别 | [optional] 
**alias** | [**LegacyMonoInfoAlias**](LegacyMonoInfoAlias.md) |  | [optional] 
**source** | [**LegacyMonoInfoSource**](LegacyMonoInfoSource.md) |  | [optional] 
**name_cn** | **str** | 简体中文名 | [optional] 
**cv** | **str** | 声优 | [optional] 

## Example

```python
from openapi_client.models.legacy_mono_info import LegacyMonoInfo

# TODO update the JSON string below
json = "{}"
# create an instance of LegacyMonoInfo from a JSON string
legacy_mono_info_instance = LegacyMonoInfo.from_json(json)
# print the JSON string representation of the object
print(LegacyMonoInfo.to_json())

# convert the object into a dict
legacy_mono_info_dict = legacy_mono_info_instance.to_dict()
# create an instance of LegacyMonoInfo from a dict
legacy_mono_info_from_dict = LegacyMonoInfo.from_dict(legacy_mono_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


