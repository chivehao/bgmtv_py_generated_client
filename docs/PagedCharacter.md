# PagedCharacter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total** | **int** |  | [optional] [default to 0]
**limit** | **int** |  | [optional] [default to 0]
**offset** | **int** |  | [optional] [default to 0]
**data** | [**List[Character]**](Character.md) |  | [optional] [default to []]

## Example

```python
from openapi_client.models.paged_character import PagedCharacter

# TODO update the JSON string below
json = "{}"
# create an instance of PagedCharacter from a JSON string
paged_character_instance = PagedCharacter.from_json(json)
# print the JSON string representation of the object
print(PagedCharacter.to_json())

# convert the object into a dict
paged_character_dict = paged_character_instance.to_dict()
# create an instance of PagedCharacter from a dict
paged_character_from_dict = PagedCharacter.from_dict(paged_character_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


