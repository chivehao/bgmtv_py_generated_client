# LegacyMonoBase

人物（基础模型）

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | 人物 ID | [optional] 
**url** | **str** | 人物地址 | [optional] 
**name** | **str** | 姓名 | [optional] 
**images** | [**LegacyMonoBaseImages**](LegacyMonoBaseImages.md) |  | [optional] 

## Example

```python
from openapi_client.models.legacy_mono_base import LegacyMonoBase

# TODO update the JSON string below
json = "{}"
# create an instance of LegacyMonoBase from a JSON string
legacy_mono_base_instance = LegacyMonoBase.from_json(json)
# print the JSON string representation of the object
print(LegacyMonoBase.to_json())

# convert the object into a dict
legacy_mono_base_dict = legacy_mono_base_instance.to_dict()
# create an instance of LegacyMonoBase from a dict
legacy_mono_base_from_dict = LegacyMonoBase.from_dict(legacy_mono_base_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


