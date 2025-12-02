# PagedRevision


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total** | **int** |  | [optional] [default to 0]
**limit** | **int** |  | [optional] [default to 0]
**offset** | **int** |  | [optional] [default to 0]
**data** | [**List[Revision]**](Revision.md) |  | [optional] [default to []]

## Example

```python
from openapi_client.models.paged_revision import PagedRevision

# TODO update the JSON string below
json = "{}"
# create an instance of PagedRevision from a JSON string
paged_revision_instance = PagedRevision.from_json(json)
# print the JSON string representation of the object
print(PagedRevision.to_json())

# convert the object into a dict
paged_revision_dict = paged_revision_instance.to_dict()
# create an instance of PagedRevision from a dict
paged_revision_from_dict = PagedRevision.from_dict(paged_revision_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


