# PersonRevisionDataItem


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prsn_infobox** | **str** |  | 
**prsn_summary** | **str** |  | 
**profession** | [**PersonRevisionProfession**](PersonRevisionProfession.md) |  | 
**extra** | [**RevisionExtra**](RevisionExtra.md) |  | 
**prsn_name** | **str** |  | 

## Example

```python
from openapi_client.models.person_revision_data_item import PersonRevisionDataItem

# TODO update the JSON string below
json = "{}"
# create an instance of PersonRevisionDataItem from a JSON string
person_revision_data_item_instance = PersonRevisionDataItem.from_json(json)
# print the JSON string representation of the object
print(PersonRevisionDataItem.to_json())

# convert the object into a dict
person_revision_data_item_dict = person_revision_data_item_instance.to_dict()
# create an instance of PersonRevisionDataItem from a dict
person_revision_data_item_from_dict = PersonRevisionDataItem.from_dict(person_revision_data_item_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


