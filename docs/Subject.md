# Subject


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**type** | [**SubjectType**](SubjectType.md) |  | 
**name** | **str** |  | 
**name_cn** | **str** |  | 
**summary** | **str** |  | 
**series** | **bool** | 是否为书籍系列的主条目 | 
**nsfw** | **bool** |  | 
**locked** | **bool** |  | 
**var_date** | **str** | air date in &#x60;YYYY-MM-DD&#x60; format | [optional] 
**platform** | **str** | TV, Web, 欧美剧, DLC... | 
**images** | [**Images**](Images.md) |  | 
**infobox** | [**List[Item]**](Item.md) |  | [optional] 
**volumes** | **int** | 书籍条目的册数，由旧服务端从wiki中解析 | 
**eps** | **int** | 由旧服务端从wiki中解析，对于书籍条目为&#x60;话数&#x60; | 
**total_episodes** | **int** | 数据库中的章节数量 | 
**rating** | [**Rating**](Rating.md) |  | 
**collection** | [**Collection**](Collection.md) |  | 
**meta_tags** | **List[str]** | 由维基人维护的 tag | 
**tags** | [**List[Tag]**](Tag.md) |  | 

## Example

```python
from openapi_client.models.subject import Subject

# TODO update the JSON string below
json = "{}"
# create an instance of Subject from a JSON string
subject_instance = Subject.from_json(json)
# print the JSON string representation of the object
print(Subject.to_json())

# convert the object into a dict
subject_dict = subject_instance.to_dict()
# create an instance of Subject from a dict
subject_from_dict = Subject.from_dict(subject_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


