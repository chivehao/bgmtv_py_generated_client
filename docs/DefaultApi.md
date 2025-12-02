# openapi_client.DefaultApi

All URIs are relative to *https://api.bgm.tv*

Method | HTTP request | Description
------------- | ------------- | -------------
[**add_subject_to_index_by_index_id**](DefaultApi.md#add_subject_to_index_by_index_id) | **POST** /v0/indices/{index_id}/subjects | Add a subject to Index
[**collect_character_by_character_id_and_user_id**](DefaultApi.md#collect_character_by_character_id_and_user_id) | **POST** /v0/characters/{character_id}/collect | Collect character for current user
[**collect_index_by_index_id_and_user_id**](DefaultApi.md#collect_index_by_index_id_and_user_id) | **POST** /v0/indices/{index_id}/collect | Collect index for current user
[**collect_person_by_person_id_and_user_id**](DefaultApi.md#collect_person_by_person_id_and_user_id) | **POST** /v0/persons/{person_id}/collect | Collect person for current user
[**delelte_subject_from_index_by_index_id_and_subject_id**](DefaultApi.md#delelte_subject_from_index_by_index_id_and_subject_id) | **DELETE** /v0/indices/{index_id}/subjects/{subject_id} | Delete a subject from a Index
[**edit_index_by_id**](DefaultApi.md#edit_index_by_id) | **PUT** /v0/indices/{index_id} | Edit index&#39;s information
[**edit_index_subjects_by_index_id_and_subject_id**](DefaultApi.md#edit_index_subjects_by_index_id_and_subject_id) | **PUT** /v0/indices/{index_id}/subjects/{subject_id} | Edit subject information in a index
[**get_calendar**](DefaultApi.md#get_calendar) | **GET** /calendar | 每日放送
[**get_character_by_id**](DefaultApi.md#get_character_by_id) | **GET** /v0/characters/{character_id} | Get Character Detail
[**get_character_image_by_id**](DefaultApi.md#get_character_image_by_id) | **GET** /v0/characters/{character_id}/image | Get Character Image
[**get_character_revision_by_revision_id**](DefaultApi.md#get_character_revision_by_revision_id) | **GET** /v0/revisions/characters/{revision_id} | Get Character Revision
[**get_character_revisions**](DefaultApi.md#get_character_revisions) | **GET** /v0/revisions/characters | Get Character Revisions
[**get_episode_by_id**](DefaultApi.md#get_episode_by_id) | **GET** /v0/episodes/{episode_id} | Get Episode
[**get_episode_revision_by_revision_id**](DefaultApi.md#get_episode_revision_by_revision_id) | **GET** /v0/revisions/episodes/{revision_id} | Get Episode Revision
[**get_episode_revisions**](DefaultApi.md#get_episode_revisions) | **GET** /v0/revisions/episodes | Get Episode Revisions
[**get_episodes**](DefaultApi.md#get_episodes) | **GET** /v0/episodes | Get Episodes
[**get_index_by_id**](DefaultApi.md#get_index_by_id) | **GET** /v0/indices/{index_id} | Get Index By ID
[**get_index_subjects_by_index_id**](DefaultApi.md#get_index_subjects_by_index_id) | **GET** /v0/indices/{index_id}/subjects | Get Index Subjects
[**get_myself**](DefaultApi.md#get_myself) | **GET** /v0/me | Get User
[**get_person_by_id**](DefaultApi.md#get_person_by_id) | **GET** /v0/persons/{person_id} | Get Person
[**get_person_image_by_id**](DefaultApi.md#get_person_image_by_id) | **GET** /v0/persons/{person_id}/image | Get Person Image
[**get_person_revision_by_revision_id**](DefaultApi.md#get_person_revision_by_revision_id) | **GET** /v0/revisions/persons/{revision_id} | Get Person Revision
[**get_person_revisions**](DefaultApi.md#get_person_revisions) | **GET** /v0/revisions/persons | Get Person Revisions
[**get_related_characters_by_person_id**](DefaultApi.md#get_related_characters_by_person_id) | **GET** /v0/persons/{person_id}/characters | get person related characters
[**get_related_characters_by_subject_id**](DefaultApi.md#get_related_characters_by_subject_id) | **GET** /v0/subjects/{subject_id}/characters | Get Subject Characters
[**get_related_persons_by_character_id**](DefaultApi.md#get_related_persons_by_character_id) | **GET** /v0/characters/{character_id}/persons | get character related persons
[**get_related_persons_by_subject_id**](DefaultApi.md#get_related_persons_by_subject_id) | **GET** /v0/subjects/{subject_id}/persons | Get Subject Persons
[**get_related_subjects_by_character_id**](DefaultApi.md#get_related_subjects_by_character_id) | **GET** /v0/characters/{character_id}/subjects | get character related subjects
[**get_related_subjects_by_person_id**](DefaultApi.md#get_related_subjects_by_person_id) | **GET** /v0/persons/{person_id}/subjects | get person related subjects
[**get_related_subjects_by_subject_id**](DefaultApi.md#get_related_subjects_by_subject_id) | **GET** /v0/subjects/{subject_id}/subjects | Get Subject Relations
[**get_subject_by_id**](DefaultApi.md#get_subject_by_id) | **GET** /v0/subjects/{subject_id} | 获取条目
[**get_subject_image_by_id**](DefaultApi.md#get_subject_image_by_id) | **GET** /v0/subjects/{subject_id}/image | Get Subject Image
[**get_subject_revision_by_revision_id**](DefaultApi.md#get_subject_revision_by_revision_id) | **GET** /v0/revisions/subjects/{revision_id} | Get Subject Revision
[**get_subject_revisions**](DefaultApi.md#get_subject_revisions) | **GET** /v0/revisions/subjects | Get Subject Revisions
[**get_subjects**](DefaultApi.md#get_subjects) | **GET** /v0/subjects | 浏览条目
[**get_user_avatar_by_name**](DefaultApi.md#get_user_avatar_by_name) | **GET** /v0/users/{username}/avatar | Get User Avatar by name
[**get_user_by_name**](DefaultApi.md#get_user_by_name) | **GET** /v0/users/{username} | Get User by name
[**get_user_character_collection**](DefaultApi.md#get_user_character_collection) | **GET** /v0/users/{username}/collections/-/characters/{character_id} | 获取用户单个角色收藏信息
[**get_user_character_collections**](DefaultApi.md#get_user_character_collections) | **GET** /v0/users/{username}/collections/-/characters | 获取用户角色收藏列表
[**get_user_collection**](DefaultApi.md#get_user_collection) | **GET** /v0/users/{username}/collections/{subject_id} | 获取用户单个条目收藏
[**get_user_collections_by_username**](DefaultApi.md#get_user_collections_by_username) | **GET** /v0/users/{username}/collections | 获取用户收藏
[**get_user_episode_collection**](DefaultApi.md#get_user_episode_collection) | **GET** /v0/users/-/collections/-/episodes/{episode_id} | 章节收藏信息
[**get_user_person_collection**](DefaultApi.md#get_user_person_collection) | **GET** /v0/users/{username}/collections/-/persons/{person_id} | 获取用户单个人物收藏信息
[**get_user_person_collections**](DefaultApi.md#get_user_person_collections) | **GET** /v0/users/{username}/collections/-/persons | 获取用户人物收藏列表
[**get_user_subject_episode_collection**](DefaultApi.md#get_user_subject_episode_collection) | **GET** /v0/users/-/collections/{subject_id}/episodes | 章节收藏信息
[**new_index**](DefaultApi.md#new_index) | **POST** /v0/indices | Create a new index
[**patch_user_collection**](DefaultApi.md#patch_user_collection) | **PATCH** /v0/users/-/collections/{subject_id} | 修改用户单个收藏
[**patch_user_subject_episode_collection**](DefaultApi.md#patch_user_subject_episode_collection) | **PATCH** /v0/users/-/collections/{subject_id}/episodes | 章节收藏信息
[**post_user_collection**](DefaultApi.md#post_user_collection) | **POST** /v0/users/-/collections/{subject_id} | 新增或修改用户单个条目收藏
[**put_user_episode_collection**](DefaultApi.md#put_user_episode_collection) | **PUT** /v0/users/-/collections/-/episodes/{episode_id} | 更新章节收藏信息
[**search_characters**](DefaultApi.md#search_characters) | **POST** /v0/search/characters | 角色搜索
[**search_persons**](DefaultApi.md#search_persons) | **POST** /v0/search/persons | 人物搜索
[**search_subjects**](DefaultApi.md#search_subjects) | **POST** /v0/search/subjects | 条目搜索
[**uncollect_character_by_character_id_and_user_id**](DefaultApi.md#uncollect_character_by_character_id_and_user_id) | **DELETE** /v0/characters/{character_id}/collect | Uncollect character for current user
[**uncollect_index_by_index_id_and_user_id**](DefaultApi.md#uncollect_index_by_index_id_and_user_id) | **DELETE** /v0/indices/{index_id}/collect | Uncollect index for current user
[**uncollect_person_by_person_id_and_user_id**](DefaultApi.md#uncollect_person_by_person_id_and_user_id) | **DELETE** /v0/persons/{person_id}/collect | Uncollect person for current user


# **add_subject_to_index_by_index_id**
> add_subject_to_index_by_index_id(index_id, index_subject_add_info=index_subject_add_info)

Add a subject to Index

### Example

* Bearer Authentication (HTTPBearer):

```python
import openapi_client
from openapi_client.models.index_subject_add_info import IndexSubjectAddInfo
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: HTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    index_id = 56 # int | 目录 ID
    index_subject_add_info = openapi_client.IndexSubjectAddInfo() # IndexSubjectAddInfo |  (optional)

    try:
        # Add a subject to Index
        api_instance.add_subject_to_index_by_index_id(index_id, index_subject_add_info=index_subject_add_info)
    except Exception as e:
        print("Exception when calling DefaultApi->add_subject_to_index_by_index_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **index_id** | **int**| 目录 ID | 
 **index_subject_add_info** | [**IndexSubjectAddInfo**](IndexSubjectAddInfo.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Unauthorized |  -  |
**401** | Bad Request |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **collect_character_by_character_id_and_user_id**
> collect_character_by_character_id_and_user_id(character_id)

Collect character for current user

为当前用户收藏角色

### Example

* Bearer Authentication (HTTPBearer):

```python
import openapi_client
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: HTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    character_id = 56 # int | 角色 ID

    try:
        # Collect character for current user
        api_instance.collect_character_by_character_id_and_user_id(character_id)
    except Exception as e:
        print("Exception when calling DefaultApi->collect_character_by_character_id_and_user_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **character_id** | **int**| 角色 ID | 

### Return type

void (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Successful Response |  -  |
**400** | character ID not valid |  -  |
**401** | not authorized |  -  |
**404** | 角色不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **collect_index_by_index_id_and_user_id**
> collect_index_by_index_id_and_user_id(index_id)

Collect index for current user

为当前用户收藏一条目录

### Example

* Bearer Authentication (HTTPBearer):

```python
import openapi_client
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: HTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    index_id = 56 # int | 目录 ID

    try:
        # Collect index for current user
        api_instance.collect_index_by_index_id_and_user_id(index_id)
    except Exception as e:
        print("Exception when calling DefaultApi->collect_index_by_index_id_and_user_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **index_id** | **int**| 目录 ID | 

### Return type

void (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**401** | Unauthorized |  -  |
**404** | Not Found |  -  |
**500** | Internal Server Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **collect_person_by_person_id_and_user_id**
> collect_person_by_person_id_and_user_id(person_id)

Collect person for current user

为当前用户收藏人物

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    person_id = 56 # int | 人物 ID

    try:
        # Collect person for current user
        api_instance.collect_person_by_person_id_and_user_id(person_id)
    except Exception as e:
        print("Exception when calling DefaultApi->collect_person_by_person_id_and_user_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **person_id** | **int**| 人物 ID | 

### Return type

void (empty response body)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Successful Response |  -  |
**400** | person ID not valid |  -  |
**401** | not authorized |  -  |
**404** | 人物不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delelte_subject_from_index_by_index_id_and_subject_id**
> delelte_subject_from_index_by_index_id_and_subject_id(index_id, subject_id)

Delete a subject from a Index

### Example

* Bearer Authentication (HTTPBearer):

```python
import openapi_client
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: HTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    index_id = 56 # int | 目录 ID
    subject_id = 56 # int | 条目 ID

    try:
        # Delete a subject from a Index
        api_instance.delelte_subject_from_index_by_index_id_and_subject_id(index_id, subject_id)
    except Exception as e:
        print("Exception when calling DefaultApi->delelte_subject_from_index_by_index_id_and_subject_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **index_id** | **int**| 目录 ID | 
 **subject_id** | **int**| 条目 ID | 

### Return type

void (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**401** | Unauthorized |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **edit_index_by_id**
> Index edit_index_by_id(index_id, index_basic_info=index_basic_info)

Edit index's information

### Example

* Bearer Authentication (HTTPBearer):

```python
import openapi_client
from openapi_client.models.index import Index
from openapi_client.models.index_basic_info import IndexBasicInfo
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: HTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    index_id = 56 # int | 目录 ID
    index_basic_info = openapi_client.IndexBasicInfo() # IndexBasicInfo |  (optional)

    try:
        # Edit index's information
        api_response = api_instance.edit_index_by_id(index_id, index_basic_info=index_basic_info)
        print("The response of DefaultApi->edit_index_by_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->edit_index_by_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **index_id** | **int**| 目录 ID | 
 **index_basic_info** | [**IndexBasicInfo**](IndexBasicInfo.md)|  | [optional] 

### Return type

[**Index**](Index.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Bad Request |  -  |
**401** | Unauthorized |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **edit_index_subjects_by_index_id_and_subject_id**
> edit_index_subjects_by_index_id_and_subject_id(index_id, subject_id, index_subject_edit_info=index_subject_edit_info)

Edit subject information in a index

如果条目不存在于目录，会创建该条目

### Example

* Bearer Authentication (HTTPBearer):

```python
import openapi_client
from openapi_client.models.index_subject_edit_info import IndexSubjectEditInfo
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: HTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    index_id = 56 # int | 目录 ID
    subject_id = 56 # int | 条目 ID
    index_subject_edit_info = openapi_client.IndexSubjectEditInfo() # IndexSubjectEditInfo |  (optional)

    try:
        # Edit subject information in a index
        api_instance.edit_index_subjects_by_index_id_and_subject_id(index_id, subject_id, index_subject_edit_info=index_subject_edit_info)
    except Exception as e:
        print("Exception when calling DefaultApi->edit_index_subjects_by_index_id_and_subject_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **index_id** | **int**| 目录 ID | 
 **subject_id** | **int**| 条目 ID | 
 **index_subject_edit_info** | [**IndexSubjectEditInfo**](IndexSubjectEditInfo.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Bad Request |  -  |
**401** | Unauthorized |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_calendar**
> List[GetCalendar200ResponseInner] get_calendar()

每日放送

### Example


```python
import openapi_client
from openapi_client.models.get_calendar200_response_inner import GetCalendar200ResponseInner
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)

    try:
        # 每日放送
        api_response = api_instance.get_calendar()
        print("The response of DefaultApi->get_calendar:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_calendar: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**List[GetCalendar200ResponseInner]**](GetCalendar200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | 每日放送 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_character_by_id**
> Character get_character_by_id(character_id)

Get Character Detail

cache with 60s

### Example


```python
import openapi_client
from openapi_client.models.character import Character
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    character_id = 56 # int | 角色 ID

    try:
        # Get Character Detail
        api_response = api_instance.get_character_by_id(character_id)
        print("The response of DefaultApi->get_character_by_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_character_by_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **character_id** | **int**| 角色 ID | 

### Return type

[**Character**](Character.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_character_image_by_id**
> get_character_image_by_id(character_id, type)

Get Character Image

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    character_id = 56 # int | 角色 ID
    type = 'type_example' # str | 枚举值 {small|grid|large|medium}

    try:
        # Get Character Image
        api_instance.get_character_image_by_id(character_id, type)
    except Exception as e:
        print("Exception when calling DefaultApi->get_character_image_by_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **character_id** | **int**| 角色 ID | 
 **type** | **str**| 枚举值 {small|grid|large|medium} | 

### Return type

void (empty response body)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**302** | Successful Response |  * Location - 用户头像链接 无头像时返回默认头像 https://lain.bgm.tv/pic/user/m/icon.jpg <br>  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_character_revision_by_revision_id**
> CharacterRevision get_character_revision_by_revision_id(revision_id)

Get Character Revision

### Example


```python
import openapi_client
from openapi_client.models.character_revision import CharacterRevision
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    revision_id = 56 # int | 版本 ID

    try:
        # Get Character Revision
        api_response = api_instance.get_character_revision_by_revision_id(revision_id)
        print("The response of DefaultApi->get_character_revision_by_revision_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_character_revision_by_revision_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **revision_id** | **int**| 版本 ID | 

### Return type

[**CharacterRevision**](CharacterRevision.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_character_revisions**
> PagedRevision get_character_revisions(character_id, limit=limit, offset=offset)

Get Character Revisions

### Example


```python
import openapi_client
from openapi_client.models.paged_revision import PagedRevision
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    character_id = 56 # int | 角色 ID
    limit = 30 # int | 分页参数 (optional) (default to 30)
    offset = 0 # int | 分页参数 (optional) (default to 0)

    try:
        # Get Character Revisions
        api_response = api_instance.get_character_revisions(character_id, limit=limit, offset=offset)
        print("The response of DefaultApi->get_character_revisions:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_character_revisions: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **character_id** | **int**| 角色 ID | 
 **limit** | **int**| 分页参数 | [optional] [default to 30]
 **offset** | **int**| 分页参数 | [optional] [default to 0]

### Return type

[**PagedRevision**](PagedRevision.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_episode_by_id**
> EpisodeDetail get_episode_by_id(episode_id)

Get Episode

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.models.episode_detail import EpisodeDetail
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    episode_id = 56 # int | 章节 ID

    try:
        # Get Episode
        api_response = api_instance.get_episode_by_id(episode_id)
        print("The response of DefaultApi->get_episode_by_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_episode_by_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **episode_id** | **int**| 章节 ID | 

### Return type

[**EpisodeDetail**](EpisodeDetail.md)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_episode_revision_by_revision_id**
> DetailedRevision get_episode_revision_by_revision_id(revision_id)

Get Episode Revision

### Example


```python
import openapi_client
from openapi_client.models.detailed_revision import DetailedRevision
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    revision_id = 56 # int | 版本 ID

    try:
        # Get Episode Revision
        api_response = api_instance.get_episode_revision_by_revision_id(revision_id)
        print("The response of DefaultApi->get_episode_revision_by_revision_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_episode_revision_by_revision_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **revision_id** | **int**| 版本 ID | 

### Return type

[**DetailedRevision**](DetailedRevision.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_episode_revisions**
> PagedRevision get_episode_revisions(episode_id, limit=limit, offset=offset)

Get Episode Revisions

### Example


```python
import openapi_client
from openapi_client.models.paged_revision import PagedRevision
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    episode_id = 56 # int | 章节 ID
    limit = 30 # int | 分页参数 (optional) (default to 30)
    offset = 0 # int | 分页参数 (optional) (default to 0)

    try:
        # Get Episode Revisions
        api_response = api_instance.get_episode_revisions(episode_id, limit=limit, offset=offset)
        print("The response of DefaultApi->get_episode_revisions:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_episode_revisions: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **episode_id** | **int**| 章节 ID | 
 **limit** | **int**| 分页参数 | [optional] [default to 30]
 **offset** | **int**| 分页参数 | [optional] [default to 0]

### Return type

[**PagedRevision**](PagedRevision.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_episodes**
> PagedEpisode get_episodes(subject_id, type=type, limit=limit, offset=offset)

Get Episodes

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.models.paged_episode import PagedEpisode
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    subject_id = 56 # int | 条目 ID
    type = openapi_client.EpType() # EpType | 参照章节的`type` (optional)
    limit = 100 # int | 分页参数 (optional) (default to 100)
    offset = 0 # int | 分页参数 (optional) (default to 0)

    try:
        # Get Episodes
        api_response = api_instance.get_episodes(subject_id, type=type, limit=limit, offset=offset)
        print("The response of DefaultApi->get_episodes:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_episodes: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subject_id** | **int**| 条目 ID | 
 **type** | [**EpType**](.md)| 参照章节的&#x60;type&#x60; | [optional] 
 **limit** | **int**| 分页参数 | [optional] [default to 100]
 **offset** | **int**| 分页参数 | [optional] [default to 0]

### Return type

[**PagedEpisode**](PagedEpisode.md)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_index_by_id**
> Index get_index_by_id(index_id)

Get Index By ID

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.models.index import Index
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    index_id = 56 # int | 目录 ID

    try:
        # Get Index By ID
        api_response = api_instance.get_index_by_id(index_id)
        print("The response of DefaultApi->get_index_by_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_index_by_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **index_id** | **int**| 目录 ID | 

### Return type

[**Index**](Index.md)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_index_subjects_by_index_id**
> get_index_subjects_by_index_id(index_id, type=type, limit=limit, offset=offset)

Get Index Subjects

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.models.subject_type import SubjectType
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    index_id = 56 # int | 目录 ID
    type = openapi_client.SubjectType() # SubjectType | 条目类型 (optional)
    limit = 30 # int | 分页参数 (optional) (default to 30)
    offset = 0 # int | 分页参数 (optional) (default to 0)

    try:
        # Get Index Subjects
        api_instance.get_index_subjects_by_index_id(index_id, type=type, limit=limit, offset=offset)
    except Exception as e:
        print("Exception when calling DefaultApi->get_index_subjects_by_index_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **index_id** | **int**| 目录 ID | 
 **type** | [**SubjectType**](.md)| 条目类型 | [optional] 
 **limit** | **int**| 分页参数 | [optional] [default to 30]
 **offset** | **int**| 分页参数 | [optional] [default to 0]

### Return type

void (empty response body)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Bad Request |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_myself**
> GetMyself200Response get_myself()

Get User

返回当前 Access Token 对应的用户信息

### Example

* Bearer Authentication (HTTPBearer):

```python
import openapi_client
from openapi_client.models.get_myself200_response import GetMyself200Response
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: HTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)

    try:
        # Get User
        api_response = api_instance.get_myself()
        print("The response of DefaultApi->get_myself:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_myself: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**GetMyself200Response**](GetMyself200Response.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**401** | unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_person_by_id**
> PersonDetail get_person_by_id(person_id)

Get Person

cache with 60s

### Example


```python
import openapi_client
from openapi_client.models.person_detail import PersonDetail
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    person_id = 56 # int | 人物 ID

    try:
        # Get Person
        api_response = api_instance.get_person_by_id(person_id)
        print("The response of DefaultApi->get_person_by_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_person_by_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **person_id** | **int**| 人物 ID | 

### Return type

[**PersonDetail**](PersonDetail.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_person_image_by_id**
> get_person_image_by_id(person_id, type)

Get Person Image

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    person_id = 56 # int | 人物 ID
    type = 'type_example' # str | 枚举值 {small|grid|large|medium}

    try:
        # Get Person Image
        api_instance.get_person_image_by_id(person_id, type)
    except Exception as e:
        print("Exception when calling DefaultApi->get_person_image_by_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **person_id** | **int**| 人物 ID | 
 **type** | **str**| 枚举值 {small|grid|large|medium} | 

### Return type

void (empty response body)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**302** | Successful Response |  * Location - 用户头像链接 无头像时返回默认头像 https://lain.bgm.tv/pic/user/m/icon.jpg <br>  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_person_revision_by_revision_id**
> PersonRevision get_person_revision_by_revision_id(revision_id)

Get Person Revision

### Example


```python
import openapi_client
from openapi_client.models.person_revision import PersonRevision
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    revision_id = 56 # int | 历史版本 ID

    try:
        # Get Person Revision
        api_response = api_instance.get_person_revision_by_revision_id(revision_id)
        print("The response of DefaultApi->get_person_revision_by_revision_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_person_revision_by_revision_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **revision_id** | **int**| 历史版本 ID | 

### Return type

[**PersonRevision**](PersonRevision.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_person_revisions**
> PagedRevision get_person_revisions(person_id, limit=limit, offset=offset)

Get Person Revisions

### Example


```python
import openapi_client
from openapi_client.models.paged_revision import PagedRevision
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    person_id = 56 # int | 角色 ID
    limit = 30 # int | 分页参数 (optional) (default to 30)
    offset = 0 # int | 分页参数 (optional) (default to 0)

    try:
        # Get Person Revisions
        api_response = api_instance.get_person_revisions(person_id, limit=limit, offset=offset)
        print("The response of DefaultApi->get_person_revisions:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_person_revisions: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **person_id** | **int**| 角色 ID | 
 **limit** | **int**| 分页参数 | [optional] [default to 30]
 **offset** | **int**| 分页参数 | [optional] [default to 0]

### Return type

[**PagedRevision**](PagedRevision.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_related_characters_by_person_id**
> List[PersonCharacter] get_related_characters_by_person_id(person_id)

get person related characters

### Example


```python
import openapi_client
from openapi_client.models.person_character import PersonCharacter
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    person_id = 56 # int | 人物 ID

    try:
        # get person related characters
        api_response = api_instance.get_related_characters_by_person_id(person_id)
        print("The response of DefaultApi->get_related_characters_by_person_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_related_characters_by_person_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **person_id** | **int**| 人物 ID | 

### Return type

[**List[PersonCharacter]**](PersonCharacter.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_related_characters_by_subject_id**
> List[RelatedCharacter] get_related_characters_by_subject_id(subject_id)

Get Subject Characters

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.models.related_character import RelatedCharacter
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    subject_id = 56 # int | 条目 ID

    try:
        # Get Subject Characters
        api_response = api_instance.get_related_characters_by_subject_id(subject_id)
        print("The response of DefaultApi->get_related_characters_by_subject_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_related_characters_by_subject_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subject_id** | **int**| 条目 ID | 

### Return type

[**List[RelatedCharacter]**](RelatedCharacter.md)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_related_persons_by_character_id**
> List[CharacterPerson] get_related_persons_by_character_id(character_id)

get character related persons

### Example


```python
import openapi_client
from openapi_client.models.character_person import CharacterPerson
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    character_id = 56 # int | 角色 ID

    try:
        # get character related persons
        api_response = api_instance.get_related_persons_by_character_id(character_id)
        print("The response of DefaultApi->get_related_persons_by_character_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_related_persons_by_character_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **character_id** | **int**| 角色 ID | 

### Return type

[**List[CharacterPerson]**](CharacterPerson.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_related_persons_by_subject_id**
> List[RelatedPerson] get_related_persons_by_subject_id(subject_id)

Get Subject Persons

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.models.related_person import RelatedPerson
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    subject_id = 56 # int | 条目 ID

    try:
        # Get Subject Persons
        api_response = api_instance.get_related_persons_by_subject_id(subject_id)
        print("The response of DefaultApi->get_related_persons_by_subject_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_related_persons_by_subject_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subject_id** | **int**| 条目 ID | 

### Return type

[**List[RelatedPerson]**](RelatedPerson.md)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_related_subjects_by_character_id**
> List[V0RelatedSubject] get_related_subjects_by_character_id(character_id)

get character related subjects

### Example


```python
import openapi_client
from openapi_client.models.v0_related_subject import V0RelatedSubject
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    character_id = 56 # int | 角色 ID

    try:
        # get character related subjects
        api_response = api_instance.get_related_subjects_by_character_id(character_id)
        print("The response of DefaultApi->get_related_subjects_by_character_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_related_subjects_by_character_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **character_id** | **int**| 角色 ID | 

### Return type

[**List[V0RelatedSubject]**](V0RelatedSubject.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_related_subjects_by_person_id**
> List[V0RelatedSubject] get_related_subjects_by_person_id(person_id)

get person related subjects

### Example


```python
import openapi_client
from openapi_client.models.v0_related_subject import V0RelatedSubject
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    person_id = 56 # int | 人物 ID

    try:
        # get person related subjects
        api_response = api_instance.get_related_subjects_by_person_id(person_id)
        print("The response of DefaultApi->get_related_subjects_by_person_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_related_subjects_by_person_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **person_id** | **int**| 人物 ID | 

### Return type

[**List[V0RelatedSubject]**](V0RelatedSubject.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_related_subjects_by_subject_id**
> List[V0SubjectRelation] get_related_subjects_by_subject_id(subject_id)

Get Subject Relations

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.models.v0_subject_relation import V0SubjectRelation
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    subject_id = 56 # int | 条目 ID

    try:
        # Get Subject Relations
        api_response = api_instance.get_related_subjects_by_subject_id(subject_id)
        print("The response of DefaultApi->get_related_subjects_by_subject_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_related_subjects_by_subject_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subject_id** | **int**| 条目 ID | 

### Return type

[**List[V0SubjectRelation]**](V0SubjectRelation.md)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_subject_by_id**
> Subject get_subject_by_id(subject_id)

获取条目

cache with 300s

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.models.subject import Subject
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    subject_id = 56 # int | 条目 ID

    try:
        # 获取条目
        api_response = api_instance.get_subject_by_id(subject_id)
        print("The response of DefaultApi->get_subject_by_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_subject_by_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subject_id** | **int**| 条目 ID | 

### Return type

[**Subject**](Subject.md)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_subject_image_by_id**
> get_subject_image_by_id(subject_id, type)

Get Subject Image

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    subject_id = 56 # int | 条目 ID
    type = 'type_example' # str | 枚举值 {small|grid|large|medium|common}

    try:
        # Get Subject Image
        api_instance.get_subject_image_by_id(subject_id, type)
    except Exception as e:
        print("Exception when calling DefaultApi->get_subject_image_by_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subject_id** | **int**| 条目 ID | 
 **type** | **str**| 枚举值 {small|grid|large|medium|common} | 

### Return type

void (empty response body)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**302** | Successful Response |  * Location - 用户头像链接 无头像时返回默认头像 https://lain.bgm.tv/pic/user/m/icon.jpg <br>  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_subject_revision_by_revision_id**
> SubjectRevision get_subject_revision_by_revision_id(revision_id)

Get Subject Revision

### Example


```python
import openapi_client
from openapi_client.models.subject_revision import SubjectRevision
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    revision_id = 56 # int | 版本 ID

    try:
        # Get Subject Revision
        api_response = api_instance.get_subject_revision_by_revision_id(revision_id)
        print("The response of DefaultApi->get_subject_revision_by_revision_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_subject_revision_by_revision_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **revision_id** | **int**| 版本 ID | 

### Return type

[**SubjectRevision**](SubjectRevision.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_subject_revisions**
> PagedRevision get_subject_revisions(subject_id, limit=limit, offset=offset)

Get Subject Revisions

### Example


```python
import openapi_client
from openapi_client.models.paged_revision import PagedRevision
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    subject_id = 56 # int | 条目 ID
    limit = 30 # int | 分页参数 (optional) (default to 30)
    offset = 0 # int | 分页参数 (optional) (default to 0)

    try:
        # Get Subject Revisions
        api_response = api_instance.get_subject_revisions(subject_id, limit=limit, offset=offset)
        print("The response of DefaultApi->get_subject_revisions:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_subject_revisions: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subject_id** | **int**| 条目 ID | 
 **limit** | **int**| 分页参数 | [optional] [default to 30]
 **offset** | **int**| 分页参数 | [optional] [default to 0]

### Return type

[**PagedRevision**](PagedRevision.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_subjects**
> PagedSubject get_subjects(type, cat=cat, series=series, platform=platform, sort=sort, year=year, month=month, limit=limit, offset=offset)

浏览条目

第一页会 cache 24h，之后会 cache 1h

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.models.paged_subject import PagedSubject
from openapi_client.models.subject_category import SubjectCategory
from openapi_client.models.subject_type import SubjectType
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    type = openapi_client.SubjectType() # SubjectType | 条目类型
    cat = openapi_client.SubjectCategory() # SubjectCategory | 条目分类，参照 `SubjectCategory` enum (optional)
    series = True # bool | 是否系列，仅对书籍类型的条目有效 (optional)
    platform = 'platform_example' # str | 平台，仅对游戏类型的条目有效 (optional)
    sort = 'sort_example' # str | 排序，枚举值 {date|rank} (optional)
    year = 56 # int | 年份 (optional)
    month = 56 # int | 月份 (optional)
    limit = 30 # int | 分页参数 (optional) (default to 30)
    offset = 0 # int | 分页参数 (optional) (default to 0)

    try:
        # 浏览条目
        api_response = api_instance.get_subjects(type, cat=cat, series=series, platform=platform, sort=sort, year=year, month=month, limit=limit, offset=offset)
        print("The response of DefaultApi->get_subjects:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_subjects: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **type** | [**SubjectType**](.md)| 条目类型 | 
 **cat** | [**SubjectCategory**](.md)| 条目分类，参照 &#x60;SubjectCategory&#x60; enum | [optional] 
 **series** | **bool**| 是否系列，仅对书籍类型的条目有效 | [optional] 
 **platform** | **str**| 平台，仅对游戏类型的条目有效 | [optional] 
 **sort** | **str**| 排序，枚举值 {date|rank} | [optional] 
 **year** | **int**| 年份 | [optional] 
 **month** | **int**| 月份 | [optional] 
 **limit** | **int**| 分页参数 | [optional] [default to 30]
 **offset** | **int**| 分页参数 | [optional] [default to 0]

### Return type

[**PagedSubject**](PagedSubject.md)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_user_avatar_by_name**
> get_user_avatar_by_name(username, type)

Get User Avatar by name

获取用户头像，302 重定向至头像地址，设置了 username 之后无法使用 UID 查询。

### Example


```python
import openapi_client
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    username = 'username_example' # str | 设置了用户名之后无法使用 UID。
    type = 'type_example' # str | 枚举值 {small|large|medium}

    try:
        # Get User Avatar by name
        api_instance.get_user_avatar_by_name(username, type)
    except Exception as e:
        print("Exception when calling DefaultApi->get_user_avatar_by_name: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **str**| 设置了用户名之后无法使用 UID。 | 
 **type** | **str**| 枚举值 {small|large|medium} | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**302** | Successful Response |  * Location - 用户头像链接 无头像时返回默认头像 https://lain.bgm.tv/pic/user/m/icon.jpg <br>  |
**400** | username 太长 |  -  |
**404** | 对应用户不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_user_by_name**
> User get_user_by_name(username)

Get User by name

获取用户信息

### Example


```python
import openapi_client
from openapi_client.models.user import User
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    username = 'username_example' # str | 设置了用户名之后无法使用 UID。

    try:
        # Get User by name
        api_response = api_instance.get_user_by_name(username)
        print("The response of DefaultApi->get_user_by_name:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_user_by_name: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **str**| 设置了用户名之后无法使用 UID。 | 

### Return type

[**User**](User.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | username 太长 |  -  |
**404** | 对应用户不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_user_character_collection**
> UserCharacterCollection get_user_character_collection(username, character_id)

获取用户单个角色收藏信息

### Example


```python
import openapi_client
from openapi_client.models.user_character_collection import UserCharacterCollection
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    username = 'username_example' # str | 设置了用户名之后无法使用 UID。
    character_id = 56 # int | 角色 ID

    try:
        # 获取用户单个角色收藏信息
        api_response = api_instance.get_user_character_collection(username, character_id)
        print("The response of DefaultApi->get_user_character_collection:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_user_character_collection: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **str**| 设置了用户名之后无法使用 UID。 | 
 **character_id** | **int**| 角色 ID | 

### Return type

[**UserCharacterCollection**](UserCharacterCollection.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | character ID not valid |  -  |
**404** | 用户或角色不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_user_character_collections**
> PagedUserCharacterCollection get_user_character_collections(username)

获取用户角色收藏列表

### Example


```python
import openapi_client
from openapi_client.models.paged_user_character_collection import PagedUserCharacterCollection
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    username = 'username_example' # str | 设置了用户名之后无法使用 UID。

    try:
        # 获取用户角色收藏列表
        api_response = api_instance.get_user_character_collections(username)
        print("The response of DefaultApi->get_user_character_collections:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_user_character_collections: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **str**| 设置了用户名之后无法使用 UID。 | 

### Return type

[**PagedUserCharacterCollection**](PagedUserCharacterCollection.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**404** | 用户不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_user_collection**
> UserSubjectCollection get_user_collection(username, subject_id)

获取用户单个条目收藏

获取对应用户的收藏，查看私有收藏需要 access token

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.models.user_subject_collection import UserSubjectCollection
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    username = 'username_example' # str | 设置了用户名之后无法使用 UID。
    subject_id = 56 # int | 条目 ID

    try:
        # 获取用户单个条目收藏
        api_response = api_instance.get_user_collection(username, subject_id)
        print("The response of DefaultApi->get_user_collection:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_user_collection: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **str**| 设置了用户名之后无法使用 UID。 | 
 **subject_id** | **int**| 条目 ID | 

### Return type

[**UserSubjectCollection**](UserSubjectCollection.md)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | 用户不存在或者条目未收藏，或者条目为私有收藏 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_user_collections_by_username**
> PagedUserCollection get_user_collections_by_username(username, subject_type=subject_type, type=type, limit=limit, offset=offset)

获取用户收藏

获取对应用户的收藏，查看私有收藏需要access token。

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.models.paged_user_collection import PagedUserCollection
from openapi_client.models.subject_type import SubjectType
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    username = 'username_example' # str | 设置了用户名之后无法使用 UID。
    subject_type = openapi_client.SubjectType() # SubjectType | 条目类型，默认为全部  具体含义见 [SubjectType](#model-SubjectType) (optional)
    type = openapi_client.SubjectCollectionType() # SubjectCollectionType | 收藏类型，默认为全部  具体含义见 [CollectionType](#model-CollectionType) (optional)
    limit = 30 # int | 分页参数 (optional) (default to 30)
    offset = 0 # int | 分页参数 (optional) (default to 0)

    try:
        # 获取用户收藏
        api_response = api_instance.get_user_collections_by_username(username, subject_type=subject_type, type=type, limit=limit, offset=offset)
        print("The response of DefaultApi->get_user_collections_by_username:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_user_collections_by_username: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **str**| 设置了用户名之后无法使用 UID。 | 
 **subject_type** | [**SubjectType**](.md)| 条目类型，默认为全部  具体含义见 [SubjectType](#model-SubjectType) | [optional] 
 **type** | [**SubjectCollectionType**](.md)| 收藏类型，默认为全部  具体含义见 [CollectionType](#model-CollectionType) | [optional] 
 **limit** | **int**| 分页参数 | [optional] [default to 30]
 **offset** | **int**| 分页参数 | [optional] [default to 0]

### Return type

[**PagedUserCollection**](PagedUserCollection.md)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Validation Error |  -  |
**404** | 用户不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_user_episode_collection**
> UserEpisodeCollection get_user_episode_collection(episode_id)

章节收藏信息

### Example

* Bearer Authentication (HTTPBearer):

```python
import openapi_client
from openapi_client.models.user_episode_collection import UserEpisodeCollection
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: HTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    episode_id = 56 # int | 章节 ID

    try:
        # 章节收藏信息
        api_response = api_instance.get_user_episode_collection(episode_id)
        print("The response of DefaultApi->get_user_episode_collection:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_user_episode_collection: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **episode_id** | **int**| 章节 ID | 

### Return type

[**UserEpisodeCollection**](UserEpisodeCollection.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | episode ID not valid |  -  |
**401** | not authorized |  -  |
**404** | 条目或者章节不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_user_person_collection**
> UserPersonCollection get_user_person_collection(username, person_id)

获取用户单个人物收藏信息

### Example


```python
import openapi_client
from openapi_client.models.user_person_collection import UserPersonCollection
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    username = 'username_example' # str | 设置了用户名之后无法使用 UID。
    person_id = 56 # int | 人物 ID

    try:
        # 获取用户单个人物收藏信息
        api_response = api_instance.get_user_person_collection(username, person_id)
        print("The response of DefaultApi->get_user_person_collection:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_user_person_collection: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **str**| 设置了用户名之后无法使用 UID。 | 
 **person_id** | **int**| 人物 ID | 

### Return type

[**UserPersonCollection**](UserPersonCollection.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | person ID not valid |  -  |
**404** | 用户或人物不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_user_person_collections**
> PagedUserPersonCollection get_user_person_collections(username)

获取用户人物收藏列表

### Example


```python
import openapi_client
from openapi_client.models.paged_user_person_collection import PagedUserPersonCollection
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    username = 'username_example' # str | 设置了用户名之后无法使用 UID。

    try:
        # 获取用户人物收藏列表
        api_response = api_instance.get_user_person_collections(username)
        print("The response of DefaultApi->get_user_person_collections:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_user_person_collections: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **username** | **str**| 设置了用户名之后无法使用 UID。 | 

### Return type

[**PagedUserPersonCollection**](PagedUserPersonCollection.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**404** | 用户不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_user_subject_episode_collection**
> GetUserSubjectEpisodeCollection200Response get_user_subject_episode_collection(subject_id, offset=offset, limit=limit, episode_type=episode_type)

章节收藏信息

### Example

* Bearer Authentication (HTTPBearer):

```python
import openapi_client
from openapi_client.models.ep_type import EpType
from openapi_client.models.get_user_subject_episode_collection200_response import GetUserSubjectEpisodeCollection200Response
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: HTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    subject_id = 56 # int | 条目 ID
    offset = 0 # int | 分页参数 (optional) (default to 0)
    limit = 100 # int | 分页参数 (optional) (default to 100)
    episode_type = openapi_client.EpType() # EpType | 章节类型，不传则不按照章节进行筛选 (optional)

    try:
        # 章节收藏信息
        api_response = api_instance.get_user_subject_episode_collection(subject_id, offset=offset, limit=limit, episode_type=episode_type)
        print("The response of DefaultApi->get_user_subject_episode_collection:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->get_user_subject_episode_collection: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subject_id** | **int**| 条目 ID | 
 **offset** | **int**| 分页参数 | [optional] [default to 0]
 **limit** | **int**| 分页参数 | [optional] [default to 100]
 **episode_type** | [**EpType**](.md)| 章节类型，不传则不按照章节进行筛选 | [optional] 

### Return type

[**GetUserSubjectEpisodeCollection200Response**](GetUserSubjectEpisodeCollection200Response.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**400** | Bad Request |  -  |
**401** | not authorized |  -  |
**404** | 条目不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **new_index**
> Index new_index()

Create a new index

### Example

* Bearer Authentication (HTTPBearer):

```python
import openapi_client
from openapi_client.models.index import Index
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: HTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)

    try:
        # Create a new index
        api_response = api_instance.new_index()
        print("The response of DefaultApi->new_index:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->new_index: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**Index**](Index.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**401** | Unauthorized |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **patch_user_collection**
> patch_user_collection(subject_id, user_subject_collection_modify_payload=user_subject_collection_modify_payload)

修改用户单个收藏

修改条目收藏状态

由于直接修改剧集条目的完成度可能会引起意料之外效果，只能用于修改书籍类条目的完成度。

PATCH 方法的所有请求体字段均可选


### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.models.user_subject_collection_modify_payload import UserSubjectCollectionModifyPayload
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    subject_id = 56 # int | 条目 ID
    user_subject_collection_modify_payload = openapi_client.UserSubjectCollectionModifyPayload() # UserSubjectCollectionModifyPayload |  (optional)

    try:
        # 修改用户单个收藏
        api_instance.patch_user_collection(subject_id, user_subject_collection_modify_payload=user_subject_collection_modify_payload)
    except Exception as e:
        print("Exception when calling DefaultApi->patch_user_collection: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subject_id** | **int**| 条目 ID | 
 **user_subject_collection_modify_payload** | [**UserSubjectCollectionModifyPayload**](UserSubjectCollectionModifyPayload.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Successful Response |  -  |
**400** | Validation Error |  -  |
**401** | Unauthorized |  -  |
**404** | 用户不存在或者条目未收藏 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **patch_user_subject_episode_collection**
> patch_user_subject_episode_collection(subject_id, patch_user_subject_episode_collection_request=patch_user_subject_episode_collection_request)

章节收藏信息

同时会重新计算条目的完成度


### Example

* Bearer Authentication (HTTPBearer):

```python
import openapi_client
from openapi_client.models.patch_user_subject_episode_collection_request import PatchUserSubjectEpisodeCollectionRequest
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: HTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    subject_id = 56 # int | 条目 ID
    patch_user_subject_episode_collection_request = openapi_client.PatchUserSubjectEpisodeCollectionRequest() # PatchUserSubjectEpisodeCollectionRequest |  (optional)

    try:
        # 章节收藏信息
        api_instance.patch_user_subject_episode_collection(subject_id, patch_user_subject_episode_collection_request=patch_user_subject_episode_collection_request)
    except Exception as e:
        print("Exception when calling DefaultApi->patch_user_subject_episode_collection: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subject_id** | **int**| 条目 ID | 
 **patch_user_subject_episode_collection_request** | [**PatchUserSubjectEpisodeCollectionRequest**](PatchUserSubjectEpisodeCollectionRequest.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Successful Response |  -  |
**400** | Bad Request |  -  |
**401** | not authorized |  -  |
**404** | 条目不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **post_user_collection**
> post_user_collection(subject_id, user_subject_collection_modify_payload=user_subject_collection_modify_payload)

新增或修改用户单个条目收藏

修改条目收藏状态, 如果不存在则创建，如果存在则修改

由于直接修改剧集条目的完成度可能会引起意料之外效果，只能用于修改书籍类条目的完成度。

方法的所有请求体字段均可选


### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.models.user_subject_collection_modify_payload import UserSubjectCollectionModifyPayload
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    subject_id = 56 # int | 条目 ID
    user_subject_collection_modify_payload = openapi_client.UserSubjectCollectionModifyPayload() # UserSubjectCollectionModifyPayload |  (optional)

    try:
        # 新增或修改用户单个条目收藏
        api_instance.post_user_collection(subject_id, user_subject_collection_modify_payload=user_subject_collection_modify_payload)
    except Exception as e:
        print("Exception when calling DefaultApi->post_user_collection: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subject_id** | **int**| 条目 ID | 
 **user_subject_collection_modify_payload** | [**UserSubjectCollectionModifyPayload**](UserSubjectCollectionModifyPayload.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Successful Response |  -  |
**400** | Validation Error |  -  |
**401** | Unauthorized |  -  |
**404** | 用户不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **put_user_episode_collection**
> put_user_episode_collection(episode_id, put_user_episode_collection_request=put_user_episode_collection_request)

更新章节收藏信息

### Example

* Bearer Authentication (HTTPBearer):

```python
import openapi_client
from openapi_client.models.put_user_episode_collection_request import PutUserEpisodeCollectionRequest
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: HTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    episode_id = 56 # int | 章节 ID
    put_user_episode_collection_request = openapi_client.PutUserEpisodeCollectionRequest() # PutUserEpisodeCollectionRequest |  (optional)

    try:
        # 更新章节收藏信息
        api_instance.put_user_episode_collection(episode_id, put_user_episode_collection_request=put_user_episode_collection_request)
    except Exception as e:
        print("Exception when calling DefaultApi->put_user_episode_collection: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **episode_id** | **int**| 章节 ID | 
 **put_user_episode_collection_request** | [**PutUserEpisodeCollectionRequest**](PutUserEpisodeCollectionRequest.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Successful Response |  -  |
**400** | episode ID not valid or subject not collected |  -  |
**401** | not authorized |  -  |
**404** | 条目或者章节不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **search_characters**
> PagedCharacter search_characters(limit=limit, offset=offset, search_characters_request=search_characters_request)

角色搜索

## 实验性 API， 本 schema 和实际的 API 行为都可能随时发生改动

目前支持的筛选条件包括:
- `nsfw`: 使用 `include` 包含NSFW搜索结果。默认排除搜索NSFW条目。无权限情况下忽略此选项，不会返回NSFW条目。


### Example


```python
import openapi_client
from openapi_client.models.paged_character import PagedCharacter
from openapi_client.models.search_characters_request import SearchCharactersRequest
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    limit = 56 # int | 分页参数 (optional)
    offset = 56 # int | 分页参数 (optional)
    search_characters_request = openapi_client.SearchCharactersRequest() # SearchCharactersRequest |  (optional)

    try:
        # 角色搜索
        api_response = api_instance.search_characters(limit=limit, offset=offset, search_characters_request=search_characters_request)
        print("The response of DefaultApi->search_characters:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->search_characters: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int**| 分页参数 | [optional] 
 **offset** | **int**| 分页参数 | [optional] 
 **search_characters_request** | [**SearchCharactersRequest**](SearchCharactersRequest.md)|  | [optional] 

### Return type

[**PagedCharacter**](PagedCharacter.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | 返回搜索结果 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **search_persons**
> PagedPerson search_persons(limit=limit, offset=offset, search_persons_request=search_persons_request)

人物搜索

## 实验性 API， 本 schema 和实际的 API 行为都可能随时发生改动

目前支持的筛选条件包括:
- `career`: 职业，可以多次出现。`且` 关系。

不同筛选条件之间为 `且`


### Example


```python
import openapi_client
from openapi_client.models.paged_person import PagedPerson
from openapi_client.models.search_persons_request import SearchPersonsRequest
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    limit = 56 # int | 分页参数 (optional)
    offset = 56 # int | 分页参数 (optional)
    search_persons_request = openapi_client.SearchPersonsRequest() # SearchPersonsRequest |  (optional)

    try:
        # 人物搜索
        api_response = api_instance.search_persons(limit=limit, offset=offset, search_persons_request=search_persons_request)
        print("The response of DefaultApi->search_persons:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->search_persons: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int**| 分页参数 | [optional] 
 **offset** | **int**| 分页参数 | [optional] 
 **search_persons_request** | [**SearchPersonsRequest**](SearchPersonsRequest.md)|  | [optional] 

### Return type

[**PagedPerson**](PagedPerson.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | 返回搜索结果 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **search_subjects**
> PagedSubject search_subjects(limit=limit, offset=offset, search_subjects_request=search_subjects_request)

条目搜索

## 实验性 API， 本 schema 和实际的 API 行为都可能随时发生改动

目前支持的筛选条件包括:
- `type`: 条目类型，参照 `SubjectType` enum， `或`。
- `tag`: 标签，可以多次出现。`且` 关系。
- `air_date`: 播出日期/发售日期。`且` 关系。
- `rating`: 用于搜索指定评分的条目。`且` 关系。
- `rating_count`: 用于按照评分人数筛选条目。`且` 关系。
- `rank`: 用于搜索指定排名的条目。`且` 关系。
- `nsfw`: 使用 `include` 包含NSFW搜索结果。默认排除搜索NSFW条目。无权限情况下忽略此选项，不会返回NSFW条目。

不同筛选条件之间为 `且`


### Example


```python
import openapi_client
from openapi_client.models.paged_subject import PagedSubject
from openapi_client.models.search_subjects_request import SearchSubjectsRequest
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)


# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    limit = 56 # int | 分页参数 (optional)
    offset = 56 # int | 分页参数 (optional)
    search_subjects_request = openapi_client.SearchSubjectsRequest() # SearchSubjectsRequest |  (optional)

    try:
        # 条目搜索
        api_response = api_instance.search_subjects(limit=limit, offset=offset, search_subjects_request=search_subjects_request)
        print("The response of DefaultApi->search_subjects:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DefaultApi->search_subjects: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int**| 分页参数 | [optional] 
 **offset** | **int**| 分页参数 | [optional] 
 **search_subjects_request** | [**SearchSubjectsRequest**](SearchSubjectsRequest.md)|  | [optional] 

### Return type

[**PagedSubject**](PagedSubject.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | 返回搜索结果 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **uncollect_character_by_character_id_and_user_id**
> uncollect_character_by_character_id_and_user_id(character_id)

Uncollect character for current user

为当前用户取消收藏角色

### Example

* Bearer Authentication (HTTPBearer):

```python
import openapi_client
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: HTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    character_id = 56 # int | 角色 ID

    try:
        # Uncollect character for current user
        api_instance.uncollect_character_by_character_id_and_user_id(character_id)
    except Exception as e:
        print("Exception when calling DefaultApi->uncollect_character_by_character_id_and_user_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **character_id** | **int**| 角色 ID | 

### Return type

void (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Successful Response |  -  |
**400** | character ID not valid |  -  |
**401** | not authorized |  -  |
**404** | 角色不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **uncollect_index_by_index_id_and_user_id**
> uncollect_index_by_index_id_and_user_id(index_id)

Uncollect index for current user

为当前用户取消收藏一条目录

### Example

* Bearer Authentication (HTTPBearer):

```python
import openapi_client
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: HTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    index_id = 56 # int | 目录 ID

    try:
        # Uncollect index for current user
        api_instance.uncollect_index_by_index_id_and_user_id(index_id)
    except Exception as e:
        print("Exception when calling DefaultApi->uncollect_index_by_index_id_and_user_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **index_id** | **int**| 目录 ID | 

### Return type

void (empty response body)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successful Response |  -  |
**401** | Unauthorized |  -  |
**404** | Not Found |  -  |
**500** | Internal Server Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **uncollect_person_by_person_id_and_user_id**
> uncollect_person_by_person_id_and_user_id(person_id)

Uncollect person for current user

为当前用户取消收藏人物

### Example

* Bearer Authentication (OptionalHTTPBearer):

```python
import openapi_client
from openapi_client.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.bgm.tv
# See configuration.py for a list of all supported configuration parameters.
configuration = openapi_client.Configuration(
    host = "https://api.bgm.tv"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure Bearer authorization: OptionalHTTPBearer
configuration = openapi_client.Configuration(
    access_token = os.environ["BEARER_TOKEN"]
)

# Enter a context with an instance of the API client
with openapi_client.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = openapi_client.DefaultApi(api_client)
    person_id = 56 # int | 人物 ID

    try:
        # Uncollect person for current user
        api_instance.uncollect_person_by_person_id_and_user_id(person_id)
    except Exception as e:
        print("Exception when calling DefaultApi->uncollect_person_by_person_id_and_user_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **person_id** | **int**| 人物 ID | 

### Return type

void (empty response body)

### Authorization

[OptionalHTTPBearer](../README.md#OptionalHTTPBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Successful Response |  -  |
**400** | person ID not valid |  -  |
**401** | not authorized |  -  |
**404** | 人物不存在 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

