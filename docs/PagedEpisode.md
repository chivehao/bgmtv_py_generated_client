# PagedEpisode


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total** | **int** |  | [optional] [default to 0]
**limit** | **int** |  | [optional] [default to 0]
**offset** | **int** |  | [optional] [default to 0]
**data** | [**List[Episode]**](Episode.md) |  | [optional] [default to []]

## Example

```python
from openapi_client.models.paged_episode import PagedEpisode

# TODO update the JSON string below
json = "{}"
# create an instance of PagedEpisode from a JSON string
paged_episode_instance = PagedEpisode.from_json(json)
# print the JSON string representation of the object
print(PagedEpisode.to_json())

# convert the object into a dict
paged_episode_dict = paged_episode_instance.to_dict()
# create an instance of PagedEpisode from a dict
paged_episode_from_dict = PagedEpisode.from_dict(paged_episode_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


