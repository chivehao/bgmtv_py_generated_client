# Index


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | 
**title** | **str** |  | 
**desc** | **str** |  | 
**total** | **int** | 收录条目总数 | [optional] [default to 0]
**stat** | [**Stat**](Stat.md) | 目录评论及收藏数 | 
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | 
**creator** | [**Creator**](Creator.md) |  | 
**ban** | **bool** | deprecated, always false. | 
**nsfw** | **bool** |  | 

## Example

```python
from openapi_client.models.index import Index

# TODO update the JSON string below
json = "{}"
# create an instance of Index from a JSON string
index_instance = Index.from_json(json)
# print the JSON string representation of the object
print(Index.to_json())

# convert the object into a dict
index_dict = index_instance.to_dict()
# create an instance of Index from a dict
index_from_dict = Index.from_dict(index_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


