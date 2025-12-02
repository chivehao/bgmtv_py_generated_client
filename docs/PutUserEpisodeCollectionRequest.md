# PutUserEpisodeCollectionRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | [**EpisodeCollectionType**](EpisodeCollectionType.md) |  | 

## Example

```python
from openapi_client.models.put_user_episode_collection_request import PutUserEpisodeCollectionRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PutUserEpisodeCollectionRequest from a JSON string
put_user_episode_collection_request_instance = PutUserEpisodeCollectionRequest.from_json(json)
# print the JSON string representation of the object
print(PutUserEpisodeCollectionRequest.to_json())

# convert the object into a dict
put_user_episode_collection_request_dict = put_user_episode_collection_request_instance.to_dict()
# create an instance of PutUserEpisodeCollectionRequest from a dict
put_user_episode_collection_request_from_dict = PutUserEpisodeCollectionRequest.from_dict(put_user_episode_collection_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


