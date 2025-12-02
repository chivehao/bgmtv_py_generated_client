# Person


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**name** | **str** |  | 
**type** | [**PersonType**](PersonType.md) | &#x60;1&#x60;, &#x60;2&#x60;, &#x60;3&#x60; 表示 &#x60;个人&#x60;, &#x60;公司&#x60;, &#x60;组合&#x60; | 
**career** | [**List[PersonCareer]**](PersonCareer.md) |  | 
**images** | [**PersonImages**](PersonImages.md) | object with some size of images, this object maybe &#x60;null&#x60; | [optional] 
**short_summary** | **str** |  | 
**locked** | **bool** |  | 

## Example

```python
from openapi_client.models.person import Person

# TODO update the JSON string below
json = "{}"
# create an instance of Person from a JSON string
person_instance = Person.from_json(json)
# print the JSON string representation of the object
print(Person.to_json())

# convert the object into a dict
person_dict = person_instance.to_dict()
# create an instance of Person from a dict
person_from_dict = Person.from_dict(person_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


