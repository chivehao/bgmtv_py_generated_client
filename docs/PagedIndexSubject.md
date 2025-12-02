# PagedIndexSubject


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total** | **int** |  | [optional] [default to 0]
**limit** | **int** |  | [optional] [default to 0]
**offset** | **int** |  | [optional] [default to 0]
**data** | [**List[IndexSubject]**](IndexSubject.md) |  | [optional] [default to []]

## Example

```python
from openapi_client.models.paged_index_subject import PagedIndexSubject

# TODO update the JSON string below
json = "{}"
# create an instance of PagedIndexSubject from a JSON string
paged_index_subject_instance = PagedIndexSubject.from_json(json)
# print the JSON string representation of the object
print(PagedIndexSubject.to_json())

# convert the object into a dict
paged_index_subject_dict = paged_index_subject_instance.to_dict()
# create an instance of PagedIndexSubject from a dict
paged_index_subject_from_dict = PagedIndexSubject.from_dict(paged_index_subject_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


