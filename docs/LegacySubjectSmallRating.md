# LegacySubjectSmallRating

评分

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total** | **int** | 总评分人数 | [optional] 
**count** | [**LegacySubjectSmallRatingCount**](LegacySubjectSmallRatingCount.md) |  | [optional] 
**score** | **float** | 评分 | [optional] 

## Example

```python
from openapi_client.models.legacy_subject_small_rating import LegacySubjectSmallRating

# TODO update the JSON string below
json = "{}"
# create an instance of LegacySubjectSmallRating from a JSON string
legacy_subject_small_rating_instance = LegacySubjectSmallRating.from_json(json)
# print the JSON string representation of the object
print(LegacySubjectSmallRating.to_json())

# convert the object into a dict
legacy_subject_small_rating_dict = legacy_subject_small_rating_instance.to_dict()
# create an instance of LegacySubjectSmallRating from a dict
legacy_subject_small_rating_from_dict = LegacySubjectSmallRating.from_dict(legacy_subject_small_rating_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


