# V0RelatedSubject


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**type** | [**SubjectType**](SubjectType.md) |  | 
**staff** | **str** |  | 
**eps** | **str** | 参与章节/曲目 | 
**name** | **str** |  | 
**name_cn** | **str** |  | 
**image** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.v0_related_subject import V0RelatedSubject

# TODO update the JSON string below
json = "{}"
# create an instance of V0RelatedSubject from a JSON string
v0_related_subject_instance = V0RelatedSubject.from_json(json)
# print the JSON string representation of the object
print(V0RelatedSubject.to_json())

# convert the object into a dict
v0_related_subject_dict = v0_related_subject_instance.to_dict()
# create an instance of V0RelatedSubject from a dict
v0_related_subject_from_dict = V0RelatedSubject.from_dict(v0_related_subject_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


