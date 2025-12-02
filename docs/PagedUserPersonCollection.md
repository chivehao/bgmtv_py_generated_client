# PagedUserPersonCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total** | **int** |  | [optional] [default to 0]
**limit** | **int** |  | [optional] [default to 0]
**offset** | **int** |  | [optional] [default to 0]
**data** | [**List[UserPersonCollection]**](UserPersonCollection.md) |  | [optional] [default to []]

## Example

```python
from openapi_client.models.paged_user_person_collection import PagedUserPersonCollection

# TODO update the JSON string below
json = "{}"
# create an instance of PagedUserPersonCollection from a JSON string
paged_user_person_collection_instance = PagedUserPersonCollection.from_json(json)
# print the JSON string representation of the object
print(PagedUserPersonCollection.to_json())

# convert the object into a dict
paged_user_person_collection_dict = paged_user_person_collection_instance.to_dict()
# create an instance of PagedUserPersonCollection from a dict
paged_user_person_collection_from_dict = PagedUserPersonCollection.from_dict(paged_user_person_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


