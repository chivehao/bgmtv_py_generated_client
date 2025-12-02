# LegacySubjectSmallCollection

收藏人数

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**wish** | **int** | 想做 | [optional] 
**collect** | **int** | 做过 | [optional] 
**doing** | **int** | 在做 | [optional] 
**on_hold** | **int** | 搁置 | [optional] 
**dropped** | **int** | 抛弃 | [optional] 

## Example

```python
from openapi_client.models.legacy_subject_small_collection import LegacySubjectSmallCollection

# TODO update the JSON string below
json = "{}"
# create an instance of LegacySubjectSmallCollection from a JSON string
legacy_subject_small_collection_instance = LegacySubjectSmallCollection.from_json(json)
# print the JSON string representation of the object
print(LegacySubjectSmallCollection.to_json())

# convert the object into a dict
legacy_subject_small_collection_dict = legacy_subject_small_collection_instance.to_dict()
# create an instance of LegacySubjectSmallCollection from a dict
legacy_subject_small_collection_from_dict = LegacySubjectSmallCollection.from_dict(legacy_subject_small_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


