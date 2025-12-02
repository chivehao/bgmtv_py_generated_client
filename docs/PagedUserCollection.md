# PagedUserCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total** | **int** |  | [optional] [default to 0]
**limit** | **int** |  | [optional] [default to 0]
**offset** | **int** |  | [optional] [default to 0]
**data** | [**List[UserSubjectCollection]**](UserSubjectCollection.md) |  | [optional] [default to []]

## Example

```python
from openapi_client.models.paged_user_collection import PagedUserCollection

# TODO update the JSON string below
json = "{}"
# create an instance of PagedUserCollection from a JSON string
paged_user_collection_instance = PagedUserCollection.from_json(json)
# print the JSON string representation of the object
print(PagedUserCollection.to_json())

# convert the object into a dict
paged_user_collection_dict = paged_user_collection_instance.to_dict()
# create an instance of PagedUserCollection from a dict
paged_user_collection_from_dict = PagedUserCollection.from_dict(paged_user_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


