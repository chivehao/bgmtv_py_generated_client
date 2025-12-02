# LegacyMonoInfoAlias

别名（另外添加出来的 key 为 0 开始的数字）

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**jp** | **str** | 日文名 | [optional] 
**kana** | **str** | 纯假名 | [optional] 
**nick** | **str** | 昵称 | [optional] 
**romaji** | **str** | 罗马字 | [optional] 
**zh** | **str** | 第二中文名 | [optional] 

## Example

```python
from openapi_client.models.legacy_mono_info_alias import LegacyMonoInfoAlias

# TODO update the JSON string below
json = "{}"
# create an instance of LegacyMonoInfoAlias from a JSON string
legacy_mono_info_alias_instance = LegacyMonoInfoAlias.from_json(json)
# print the JSON string representation of the object
print(LegacyMonoInfoAlias.to_json())

# convert the object into a dict
legacy_mono_info_alias_dict = legacy_mono_info_alias_instance.to_dict()
# create an instance of LegacyMonoInfoAlias from a dict
legacy_mono_info_alias_from_dict = LegacyMonoInfoAlias.from_dict(legacy_mono_info_alias_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


