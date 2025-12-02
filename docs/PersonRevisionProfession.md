# PersonRevisionProfession


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**producer** | **str** |  | [optional] 
**mangaka** | **str** |  | [optional] 
**artist** | **str** |  | [optional] 
**seiyu** | **str** |  | [optional] 
**writer** | **str** |  | [optional] 
**illustrator** | **str** |  | [optional] 
**actor** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.person_revision_profession import PersonRevisionProfession

# TODO update the JSON string below
json = "{}"
# create an instance of PersonRevisionProfession from a JSON string
person_revision_profession_instance = PersonRevisionProfession.from_json(json)
# print the JSON string representation of the object
print(PersonRevisionProfession.to_json())

# convert the object into a dict
person_revision_profession_dict = person_revision_profession_instance.to_dict()
# create an instance of PersonRevisionProfession from a dict
person_revision_profession_from_dict = PersonRevisionProfession.from_dict(person_revision_profession_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


