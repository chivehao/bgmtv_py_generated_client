# UserSubjectCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**subject_id** | **int** |  | 
**subject_type** | [**SubjectType**](SubjectType.md) |  | 
**rate** | **int** |  | 
**type** | [**SubjectCollectionType**](SubjectCollectionType.md) |  | 
**comment** | **str** |  | [optional] 
**tags** | **List[str]** |  | 
**ep_status** | **int** |  | 
**vol_status** | **int** |  | 
**updated_at** | **datetime** | 本时间并不代表条目的收藏时间。修改评分，评价，章节观看状态等收藏信息时未更新此时间是一个 bug。请不要依赖此特性 | 
**private** | **bool** |  | 
**subject** | [**SlimSubject**](SlimSubject.md) |  | [optional] 

## Example

```python
from openapi_client.models.user_subject_collection import UserSubjectCollection

# TODO update the JSON string below
json = "{}"
# create an instance of UserSubjectCollection from a JSON string
user_subject_collection_instance = UserSubjectCollection.from_json(json)
# print the JSON string representation of the object
print(UserSubjectCollection.to_json())

# convert the object into a dict
user_subject_collection_dict = user_subject_collection_instance.to_dict()
# create an instance of UserSubjectCollection from a dict
user_subject_collection_from_dict = UserSubjectCollection.from_dict(user_subject_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


