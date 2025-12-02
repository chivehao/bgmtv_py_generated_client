# LegacyMono

人物

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

## Example

```python
from openapi_client.models.legacy_mono import LegacyMono

# TODO update the JSON string below
json = "{}"
# create an instance of LegacyMono from a JSON string
legacy_mono_instance = LegacyMono.from_json(json)
# print the JSON string representation of the object
print(LegacyMono.to_json())

# convert the object into a dict
legacy_mono_dict = legacy_mono_instance.to_dict()
# create an instance of LegacyMono from a dict
legacy_mono_from_dict = LegacyMono.from_dict(legacy_mono_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


