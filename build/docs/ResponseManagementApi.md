---
title: ResponseManagementApi
---
# platformClient.ResponseManagementApi

All URIs are relative to *https://api.mypurecloud.com*

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
[**deleteResponsemanagementLibrary**](ResponseManagementApi.html#deleteResponsemanagementLibrary) | **DELETE** /api/v2/responsemanagement/libraries/{libraryId} | Delete an existing response library.
[**deleteResponsemanagementResponse**](ResponseManagementApi.html#deleteResponsemanagementResponse) | **DELETE** /api/v2/responsemanagement/responses/{responseId} | Delete an existing response.
[**getResponsemanagementLibraries**](ResponseManagementApi.html#getResponsemanagementLibraries) | **GET** /api/v2/responsemanagement/libraries | Gets a list of existing response libraries.
[**getResponsemanagementLibrary**](ResponseManagementApi.html#getResponsemanagementLibrary) | **GET** /api/v2/responsemanagement/libraries/{libraryId} | Get details about an existing response library.
[**getResponsemanagementResponse**](ResponseManagementApi.html#getResponsemanagementResponse) | **GET** /api/v2/responsemanagement/responses/{responseId} | Get details about an existing response.
[**getResponsemanagementResponses**](ResponseManagementApi.html#getResponsemanagementResponses) | **GET** /api/v2/responsemanagement/responses | Gets a list of existing responses.
[**postResponsemanagementLibraries**](ResponseManagementApi.html#postResponsemanagementLibraries) | **POST** /api/v2/responsemanagement/libraries | Create a response library.
[**postResponsemanagementResponses**](ResponseManagementApi.html#postResponsemanagementResponses) | **POST** /api/v2/responsemanagement/responses | Create a response.
[**postResponsemanagementResponsesQuery**](ResponseManagementApi.html#postResponsemanagementResponsesQuery) | **POST** /api/v2/responsemanagement/responses/query | Query responses
[**putResponsemanagementLibrary**](ResponseManagementApi.html#putResponsemanagementLibrary) | **PUT** /api/v2/responsemanagement/libraries/{libraryId} | Update an existing response library.
[**putResponsemanagementResponse**](ResponseManagementApi.html#putResponsemanagementResponse) | **PUT** /api/v2/responsemanagement/responses/{responseId} | Update an existing response.
{: class="table table-striped"}

<a name="deleteResponsemanagementLibrary"></a>

# void deleteResponsemanagementLibrary(libraryId)



DELETE /api/v2/responsemanagement/libraries/{libraryId}

Delete an existing response library.

This will remove any responses associated with the library.

Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ResponseManagementApi();

let libraryId = "libraryId_example"; // String | Library ID

apiInstance.deleteResponsemanagementLibrary(libraryId)
  .then(() => {
    console.log('deleteResponsemanagementLibrary returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling deleteResponsemanagementLibrary');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **libraryId** | **String** | Library ID |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="deleteResponsemanagementResponse"></a>

# void deleteResponsemanagementResponse(responseId)



DELETE /api/v2/responsemanagement/responses/{responseId}

Delete an existing response.

This will remove the response from any libraries associated with it.

Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ResponseManagementApi();

let responseId = "responseId_example"; // String | Response ID

apiInstance.deleteResponsemanagementResponse(responseId)
  .then(() => {
    console.log('deleteResponsemanagementResponse returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling deleteResponsemanagementResponse');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **responseId** | **String** | Response ID |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="getResponsemanagementLibraries"></a>

# LibraryEntityListing getResponsemanagementLibraries(opts)



GET /api/v2/responsemanagement/libraries

Gets a list of existing response libraries.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ResponseManagementApi();

let opts = { 
  'pageNumber': 1, // Number | Page number
  'pageSize': 25, // Number | Page size
  'messagingTemplateFilter': "messagingTemplateFilter_example" // String | Returns a list of libraries that contain responses with at least one messaging template defined for a specific message channel
};

apiInstance.getResponsemanagementLibraries(opts)
  .then((data) => {
    console.log(`getResponsemanagementLibraries success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getResponsemanagementLibraries');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **pageNumber** | **Number** | Page number | [optional] [default to 1] |
 **pageSize** | **Number** | Page size | [optional] [default to 25] |
 **messagingTemplateFilter** | **String** | Returns a list of libraries that contain responses with at least one messaging template defined for a specific message channel | [optional] <br />**Values**: whatsapp |
{: class="table table-striped"}

### Return type

**LibraryEntityListing**

<a name="getResponsemanagementLibrary"></a>

# Library getResponsemanagementLibrary(libraryId)



GET /api/v2/responsemanagement/libraries/{libraryId}

Get details about an existing response library.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ResponseManagementApi();

let libraryId = "libraryId_example"; // String | Library ID

apiInstance.getResponsemanagementLibrary(libraryId)
  .then((data) => {
    console.log(`getResponsemanagementLibrary success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getResponsemanagementLibrary');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **libraryId** | **String** | Library ID |  |
{: class="table table-striped"}

### Return type

**Library**

<a name="getResponsemanagementResponse"></a>

# Response getResponsemanagementResponse(responseId, opts)



GET /api/v2/responsemanagement/responses/{responseId}

Get details about an existing response.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ResponseManagementApi();

let responseId = "responseId_example"; // String | Response ID
let opts = { 
  'expand': "expand_example" // String | Expand instructions for the return value.
};

apiInstance.getResponsemanagementResponse(responseId, opts)
  .then((data) => {
    console.log(`getResponsemanagementResponse success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getResponsemanagementResponse');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **responseId** | **String** | Response ID |  |
 **expand** | **String** | Expand instructions for the return value. | [optional] <br />**Values**: substitutionsSchema |
{: class="table table-striped"}

### Return type

**Response**

<a name="getResponsemanagementResponses"></a>

# ResponseEntityListing getResponsemanagementResponses(libraryId, opts)



GET /api/v2/responsemanagement/responses

Gets a list of existing responses.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ResponseManagementApi();

let libraryId = "libraryId_example"; // String | Library ID
let opts = { 
  'pageNumber': 1, // Number | Page number
  'pageSize': 25, // Number | Page size
  'expand': "expand_example" // String | Expand instructions for the return value.
};

apiInstance.getResponsemanagementResponses(libraryId, opts)
  .then((data) => {
    console.log(`getResponsemanagementResponses success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getResponsemanagementResponses');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **libraryId** | **String** | Library ID |  |
 **pageNumber** | **Number** | Page number | [optional] [default to 1] |
 **pageSize** | **Number** | Page size | [optional] [default to 25] |
 **expand** | **String** | Expand instructions for the return value. | [optional] <br />**Values**: substitutionsSchema |
{: class="table table-striped"}

### Return type

**ResponseEntityListing**

<a name="postResponsemanagementLibraries"></a>

# Library postResponsemanagementLibraries(body)



POST /api/v2/responsemanagement/libraries

Create a response library.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ResponseManagementApi();

let body = {}; // Object | Library

apiInstance.postResponsemanagementLibraries(body)
  .then((data) => {
    console.log(`postResponsemanagementLibraries success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postResponsemanagementLibraries');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | Library |  |
{: class="table table-striped"}

### Return type

**Library**

<a name="postResponsemanagementResponses"></a>

# Response postResponsemanagementResponses(body, opts)



POST /api/v2/responsemanagement/responses

Create a response.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ResponseManagementApi();

let body = {}; // Object | Response
let opts = { 
  'expand': "expand_example" // String | Expand instructions for the return value.
};

apiInstance.postResponsemanagementResponses(body, opts)
  .then((data) => {
    console.log(`postResponsemanagementResponses success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postResponsemanagementResponses');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | Response |  |
 **expand** | **String** | Expand instructions for the return value. | [optional] <br />**Values**: substitutionsSchema |
{: class="table table-striped"}

### Return type

**Response**

<a name="postResponsemanagementResponsesQuery"></a>

# ResponseQueryResults postResponsemanagementResponsesQuery(body)



POST /api/v2/responsemanagement/responses/query

Query responses



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ResponseManagementApi();

let body = {}; // Object | Response

apiInstance.postResponsemanagementResponsesQuery(body)
  .then((data) => {
    console.log(`postResponsemanagementResponsesQuery success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postResponsemanagementResponsesQuery');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | Response |  |
{: class="table table-striped"}

### Return type

**ResponseQueryResults**

<a name="putResponsemanagementLibrary"></a>

# Library putResponsemanagementLibrary(libraryId, body)



PUT /api/v2/responsemanagement/libraries/{libraryId}

Update an existing response library.

Fields that can be updated: name. The most recent version is required for updates.

Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ResponseManagementApi();

let libraryId = "libraryId_example"; // String | Library ID
let body = {}; // Object | Library

apiInstance.putResponsemanagementLibrary(libraryId, body)
  .then((data) => {
    console.log(`putResponsemanagementLibrary success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling putResponsemanagementLibrary');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **libraryId** | **String** | Library ID |  |
 **body** | **Object** | Library |  |
{: class="table table-striped"}

### Return type

**Library**

<a name="putResponsemanagementResponse"></a>

# Response putResponsemanagementResponse(responseId, body, opts)



PUT /api/v2/responsemanagement/responses/{responseId}

Update an existing response.

Fields that can be updated: name, libraries, and texts. The most recent version is required for updates.

Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ResponseManagementApi();

let responseId = "responseId_example"; // String | Response ID
let body = {}; // Object | Response
let opts = { 
  'expand': "expand_example" // String | Expand instructions for the return value.
};

apiInstance.putResponsemanagementResponse(responseId, body, opts)
  .then((data) => {
    console.log(`putResponsemanagementResponse success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling putResponsemanagementResponse');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **responseId** | **String** | Response ID |  |
 **body** | **Object** | Response |  |
 **expand** | **String** | Expand instructions for the return value. | [optional] <br />**Values**: substitutionsSchema |
{: class="table table-striped"}

### Return type

**Response**

