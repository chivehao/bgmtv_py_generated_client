# SlimSubject


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**type** | [**SubjectType**](SubjectType.md) |  | 
**name** | **str** |  | 
**name_cn** | **str** |  | 
**short_summary** | **str** | 截短后的条目描述。 | 
**var_date** | **str** | air date in &#x60;YYYY-MM-DD&#x60; format | [optional] 
**images** | [**Images**](Images.md) |  | 
**volumes** | **int** | 书籍条目的册数，由旧服务端从wiki中解析 | 
**eps** | **int** | 由旧服务端从wiki中解析，对于书籍条目为&#x60;话数&#x60; | 
**collection_total** | **int** | 收藏人数 | 
**score** | **float** | 分数 | 
**rank** | **int** | 排名 | 
**tags** | [**List[Tag]**](Tag.md) | 前 10 个 tag | 

## Example

```python
from openapi_client.models.slim_subject import SlimSubject

# TODO update the JSON string below
json = "{}"
# create an instance of SlimSubject from a JSON string
slim_subject_instance = SlimSubject.from_json(json)
# print the JSON string representation of the object
print(SlimSubject.to_json())

# convert the object into a dict
slim_subject_dict = slim_subject_instance.to_dict()
# create an instance of SlimSubject from a dict
slim_subject_from_dict = SlimSubject.from_dict(slim_subject_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


