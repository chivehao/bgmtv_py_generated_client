# UserSubjectCollectionModifyPayload

所有的字段均可选

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | [**SubjectCollectionType**](SubjectCollectionType.md) | 修改条目收藏类型 | [optional] 
**rate** | **int** | 评分，&#x60;0&#x60; 表示删除评分 | [optional] 
**ep_status** | **int** | 只能用于修改书籍条目进度 | [optional] 
**vol_status** | **int** | 只能用于修改书籍条目进度 | [optional] 
**comment** | **str** | 评价 | [optional] 
**private** | **bool** | 仅自己可见 | [optional] 
**tags** | **List[str]** | 不传或者 &#x60;null&#x60; 都会被忽略，传 &#x60;[]&#x60; 则会删除所有 tag。 | [optional] 

## Example

```python
from openapi_client.models.user_subject_collection_modify_payload import UserSubjectCollectionModifyPayload

# TODO update the JSON string below
json = "{}"
# create an instance of UserSubjectCollectionModifyPayload from a JSON string
user_subject_collection_modify_payload_instance = UserSubjectCollectionModifyPayload.from_json(json)
# print the JSON string representation of the object
print(UserSubjectCollectionModifyPayload.to_json())

# convert the object into a dict
user_subject_collection_modify_payload_dict = user_subject_collection_modify_payload_instance.to_dict()
# create an instance of UserSubjectCollectionModifyPayload from a dict
user_subject_collection_modify_payload_from_dict = UserSubjectCollectionModifyPayload.from_dict(user_subject_collection_modify_payload_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


