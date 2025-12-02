# UserEpisodeCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**episode** | [**Episode**](Episode.md) |  | 
**type** | [**EpisodeCollectionType**](EpisodeCollectionType.md) |  | 
**updated_at** | **int** | A int64 unix timestamp, &#x60;0&#x60; as unknown or un-recorded. | 

## Example

```python
from openapi_client.models.user_episode_collection import UserEpisodeCollection

# TODO update the JSON string below
json = "{}"
# create an instance of UserEpisodeCollection from a JSON string
user_episode_collection_instance = UserEpisodeCollection.from_json(json)
# print the JSON string representation of the object
print(UserEpisodeCollection.to_json())

# convert the object into a dict
user_episode_collection_dict = user_episode_collection_instance.to_dict()
# create an instance of UserEpisodeCollection from a dict
user_episode_collection_from_dict = UserEpisodeCollection.from_dict(user_episode_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


