# PersonDetail


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**name** | **str** |  | 
**type** | [**PersonType**](PersonType.md) | &#x60;1&#x60;, &#x60;2&#x60;, &#x60;3&#x60; 表示 &#x60;个人&#x60;, &#x60;公司&#x60;, &#x60;组合&#x60; | 
**career** | [**List[PersonCareer]**](PersonCareer.md) |  | 
**images** | [**PersonImages**](PersonImages.md) | object with some size of images, this object maybe &#x60;null&#x60; | [optional] 
**summary** | **str** |  | 
**locked** | **bool** |  | 
**last_modified** | **datetime** | currently it&#39;s latest user comment time, it will be replaced by wiki modified date in the future | 
**infobox** | **List[object]** | server parsed infobox, a map from key to string or tuple null if server infobox is not valid | [optional] 
**gender** | **str** | parsed from wiki, maybe null | [optional] 
**blood_type** | [**BloodType**](BloodType.md) | parsed from wiki, maybe null, &#x60;1, 2, 3, 4&#x60; for &#x60;A, B, AB, O&#x60; | [optional] 
**birth_year** | **int** | parsed from wiki, maybe &#x60;null&#x60; | [optional] 
**birth_mon** | **int** | parsed from wiki, maybe &#x60;null&#x60; | [optional] 
**birth_day** | **int** | parsed from wiki, maybe &#x60;null&#x60; | [optional] 
**stat** | [**Stat**](Stat.md) |  | 

## Example

```python
from openapi_client.models.person_detail import PersonDetail

# TODO update the JSON string below
json = "{}"
# create an instance of PersonDetail from a JSON string
person_detail_instance = PersonDetail.from_json(json)
# print the JSON string representation of the object
print(PersonDetail.to_json())

# convert the object into a dict
person_detail_dict = person_detail_instance.to_dict()
# create an instance of PersonDetail from a dict
person_detail_from_dict = PersonDetail.from_dict(person_detail_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


