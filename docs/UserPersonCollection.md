# UserPersonCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**name** | **str** |  | 
**type** | [**PersonType**](PersonType.md) | &#x60;1&#x60;, &#x60;2&#x60;, &#x60;3&#x60; 表示 &#x60;个人&#x60;, &#x60;公司&#x60;, &#x60;组合&#x60; | 
**career** | [**List[PersonCareer]**](PersonCareer.md) |  | 
**images** | [**PersonImages**](PersonImages.md) | object with some size of images, this object maybe &#x60;null&#x60; | [optional] 
**created_at** | **datetime** |  | 

## Example

```python
from openapi_client.models.user_person_collection import UserPersonCollection

# TODO update the JSON string below
json = "{}"
# create an instance of UserPersonCollection from a JSON string
user_person_collection_instance = UserPersonCollection.from_json(json)
# print the JSON string representation of the object
print(UserPersonCollection.to_json())

# convert the object into a dict
user_person_collection_dict = user_person_collection_instance.to_dict()
# create an instance of UserPersonCollection from a dict
user_person_collection_from_dict = UserPersonCollection.from_dict(user_person_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


