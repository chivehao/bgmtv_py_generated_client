# PagedSubject


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total** | **int** |  | [optional] [default to 0]
**limit** | **int** |  | [optional] [default to 0]
**offset** | **int** |  | [optional] [default to 0]
**data** | [**List[Subject]**](Subject.md) |  | [optional] [default to []]

## Example

```python
from openapi_client.models.paged_subject import PagedSubject

# TODO update the JSON string below
json = "{}"
# create an instance of PagedSubject from a JSON string
paged_subject_instance = PagedSubject.from_json(json)
# print the JSON string representation of the object
print(PagedSubject.to_json())

# convert the object into a dict
paged_subject_dict = paged_subject_instance.to_dict()
# create an instance of PagedSubject from a dict
paged_subject_from_dict = PagedSubject.from_dict(paged_subject_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


