# PagedPerson


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total** | **int** |  | [optional] [default to 0]
**limit** | **int** |  | [optional] [default to 0]
**offset** | **int** |  | [optional] [default to 0]
**data** | [**List[Person]**](Person.md) |  | [optional] [default to []]

## Example

```python
from openapi_client.models.paged_person import PagedPerson

# TODO update the JSON string below
json = "{}"
# create an instance of PagedPerson from a JSON string
paged_person_instance = PagedPerson.from_json(json)
# print the JSON string representation of the object
print(PagedPerson.to_json())

# convert the object into a dict
paged_person_dict = paged_person_instance.to_dict()
# create an instance of PagedPerson from a dict
paged_person_from_dict = PagedPerson.from_dict(paged_person_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


