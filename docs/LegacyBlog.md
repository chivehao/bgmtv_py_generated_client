# LegacyBlog

日志

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID | [optional] 
**url** | **str** | 地址 | [optional] 
**title** | **str** | 标题 | [optional] 
**summary** | **str** | 概览 | [optional] 
**image** | **str** | 图片 | [optional] 
**replies** | **int** | 回复数 | [optional] 
**timestamp** | **int** | 发布时间 | [optional] 
**dateline** | **str** | 发布时间 | [optional] 
**user** | [**LegacyUser**](LegacyUser.md) |  | [optional] 

## Example

```python
from openapi_client.models.legacy_blog import LegacyBlog

# TODO update the JSON string below
json = "{}"
# create an instance of LegacyBlog from a JSON string
legacy_blog_instance = LegacyBlog.from_json(json)
# print the JSON string representation of the object
print(LegacyBlog.to_json())

# convert the object into a dict
legacy_blog_dict = legacy_blog_instance.to_dict()
# create an instance of LegacyBlog from a dict
legacy_blog_from_dict = LegacyBlog.from_dict(legacy_blog_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


