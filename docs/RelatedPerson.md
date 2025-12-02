# RelatedPerson


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**name** | **str** |  | 
**type** | [**PersonType**](PersonType.md) | &#x60;1&#x60;, &#x60;2&#x60;, &#x60;3&#x60; 表示 &#x60;个人&#x60;, &#x60;公司&#x60;, &#x60;组合&#x60; | 
**career** | [**List[PersonCareer]**](PersonCareer.md) |  | 
**images** | [**PersonImages**](PersonImages.md) | object with some size of images, this object maybe &#x60;null&#x60; | [optional] 
**relation** | **str** |  | 
**eps** | **str** | 参与章节/曲目 | 

## Example

```python
from openapi_client.models.related_person import RelatedPerson

# TODO update the JSON string below
json = "{}"
# create an instance of RelatedPerson from a JSON string
related_person_instance = RelatedPerson.from_json(json)
# print the JSON string representation of the object
print(RelatedPerson.to_json())

# convert the object into a dict
related_person_dict = related_person_instance.to_dict()
# create an instance of RelatedPerson from a dict
related_person_from_dict = RelatedPerson.from_dict(related_person_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


