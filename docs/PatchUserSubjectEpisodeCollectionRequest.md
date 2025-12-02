# PatchUserSubjectEpisodeCollectionRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**episode_id** | **List[int]** |  | 
**type** | [**EpisodeCollectionType**](EpisodeCollectionType.md) |  | 

## Example

```python
from openapi_client.models.patch_user_subject_episode_collection_request import PatchUserSubjectEpisodeCollectionRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PatchUserSubjectEpisodeCollectionRequest from a JSON string
patch_user_subject_episode_collection_request_instance = PatchUserSubjectEpisodeCollectionRequest.from_json(json)
# print the JSON string representation of the object
print(PatchUserSubjectEpisodeCollectionRequest.to_json())

# convert the object into a dict
patch_user_subject_episode_collection_request_dict = patch_user_subject_episode_collection_request_instance.to_dict()
# create an instance of PatchUserSubjectEpisodeCollectionRequest from a dict
patch_user_subject_episode_collection_request_from_dict = PatchUserSubjectEpisodeCollectionRequest.from_dict(patch_user_subject_episode_collection_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


