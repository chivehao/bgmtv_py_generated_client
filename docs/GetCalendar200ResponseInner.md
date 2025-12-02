# GetCalendar200ResponseInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**weekday** | [**GetCalendar200ResponseInnerWeekday**](GetCalendar200ResponseInnerWeekday.md) |  | [optional] 
**items** | [**List[LegacySubjectSmall]**](LegacySubjectSmall.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_calendar200_response_inner import GetCalendar200ResponseInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendar200ResponseInner from a JSON string
get_calendar200_response_inner_instance = GetCalendar200ResponseInner.from_json(json)
# print the JSON string representation of the object
print(GetCalendar200ResponseInner.to_json())

# convert the object into a dict
get_calendar200_response_inner_dict = get_calendar200_response_inner_instance.to_dict()
# create an instance of GetCalendar200ResponseInner from a dict
get_calendar200_response_inner_from_dict = GetCalendar200ResponseInner.from_dict(get_calendar200_response_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


