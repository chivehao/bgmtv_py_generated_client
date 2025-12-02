# PagedUserCharacterCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total** | **int** |  | [optional] [default to 0]
**limit** | **int** |  | [optional] [default to 0]
**offset** | **int** |  | [optional] [default to 0]
**data** | [**List[UserCharacterCollection]**](UserCharacterCollection.md) |  | [optional] [default to []]

## Example

```python
from openapi_client.models.paged_user_character_collection import PagedUserCharacterCollection

# TODO update the JSON string below
json = "{}"
# create an instance of PagedUserCharacterCollection from a JSON string
paged_user_character_collection_instance = PagedUserCharacterCollection.from_json(json)
# print the JSON string representation of the object
print(PagedUserCharacterCollection.to_json())

# convert the object into a dict
paged_user_character_collection_dict = paged_user_character_collection_instance.to_dict()
# create an instance of PagedUserCharacterCollection from a dict
paged_user_character_collection_from_dict = PagedUserCharacterCollection.from_dict(paged_user_character_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


