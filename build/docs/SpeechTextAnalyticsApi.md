---
title: SpeechTextAnalyticsApi
---
# platformClient.SpeechTextAnalyticsApi

All URIs are relative to *https://api.mypurecloud.com*

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
[**deleteSpeechandtextanalyticsProgram**](SpeechTextAnalyticsApi.html#deleteSpeechandtextanalyticsProgram) | **DELETE** /api/v2/speechandtextanalytics/programs/{programId} | Delete a Speech &amp; Text Analytics program by id
[**deleteSpeechandtextanalyticsTopic**](SpeechTextAnalyticsApi.html#deleteSpeechandtextanalyticsTopic) | **DELETE** /api/v2/speechandtextanalytics/topics/{topicId} | Delete a Speech &amp; Text Analytics topic by id
[**getSpeechandtextanalyticsConversation**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsConversation) | **GET** /api/v2/speechandtextanalytics/conversations/{conversationId} | Get Speech and Text Analytics for a specific conversation
[**getSpeechandtextanalyticsConversationCommunicationTranscripturl**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsConversationCommunicationTranscripturl) | **GET** /api/v2/speechandtextanalytics/conversations/{conversationId}/communications/{communicationId}/transcripturl | Get the pre-signed S3 URL for the transcript of a specific communication of a conversation
[**getSpeechandtextanalyticsDialects**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsDialects) | **GET** /api/v2/speechandtextanalytics/dialects | Get list of supported Speech &amp; Text Analytics dialects
[**getSpeechandtextanalyticsProgram**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsProgram) | **GET** /api/v2/speechandtextanalytics/programs/{programId} | Get a Speech &amp; Text Analytics program by id
[**getSpeechandtextanalyticsProgramMappings**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsProgramMappings) | **GET** /api/v2/speechandtextanalytics/programs/{programId}/mappings | Get Speech &amp; Text Analytics program mappings to queues and flows by id
[**getSpeechandtextanalyticsPrograms**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsPrograms) | **GET** /api/v2/speechandtextanalytics/programs | Get the list of Speech &amp; Text Analytics programs
[**getSpeechandtextanalyticsProgramsGeneralJob**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsProgramsGeneralJob) | **GET** /api/v2/speechandtextanalytics/programs/general/jobs/{jobId} | Get a Speech &amp; Text Analytics general program job by id
[**getSpeechandtextanalyticsProgramsMappings**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsProgramsMappings) | **GET** /api/v2/speechandtextanalytics/programs/mappings | Get the list of Speech &amp; Text Analytics programs mappings to queues and flows
[**getSpeechandtextanalyticsProgramsPublishjob**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsProgramsPublishjob) | **GET** /api/v2/speechandtextanalytics/programs/publishjobs/{jobId} | Get a Speech &amp; Text Analytics publish programs job by id
[**getSpeechandtextanalyticsProgramsUnpublished**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsProgramsUnpublished) | **GET** /api/v2/speechandtextanalytics/programs/unpublished | Get the list of Speech &amp; Text Analytics unpublished programs
[**getSpeechandtextanalyticsSettings**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsSettings) | **GET** /api/v2/speechandtextanalytics/settings | Get Speech And Text Analytics Settings
[**getSpeechandtextanalyticsTopic**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsTopic) | **GET** /api/v2/speechandtextanalytics/topics/{topicId} | Get a Speech &amp; Text Analytics topic by id
[**getSpeechandtextanalyticsTopics**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsTopics) | **GET** /api/v2/speechandtextanalytics/topics | Get the list of Speech &amp; Text Analytics topics
[**getSpeechandtextanalyticsTopicsDialects**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsTopicsDialects) | **GET** /api/v2/speechandtextanalytics/topics/dialects | Get list of supported Speech &amp; Text Analytics topics dialects
[**getSpeechandtextanalyticsTopicsGeneral**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsTopicsGeneral) | **GET** /api/v2/speechandtextanalytics/topics/general | Get the Speech &amp; Text Analytics general topics for a given dialect
[**getSpeechandtextanalyticsTopicsPublishjob**](SpeechTextAnalyticsApi.html#getSpeechandtextanalyticsTopicsPublishjob) | **GET** /api/v2/speechandtextanalytics/topics/publishjobs/{jobId} | Get a Speech &amp; Text Analytics publish topics job by id
[**patchSpeechandtextanalyticsSettings**](SpeechTextAnalyticsApi.html#patchSpeechandtextanalyticsSettings) | **PATCH** /api/v2/speechandtextanalytics/settings | Patch Speech And Text Analytics Settings
[**postSpeechandtextanalyticsPrograms**](SpeechTextAnalyticsApi.html#postSpeechandtextanalyticsPrograms) | **POST** /api/v2/speechandtextanalytics/programs | Create new Speech &amp; Text Analytics program
[**postSpeechandtextanalyticsProgramsGeneralJobs**](SpeechTextAnalyticsApi.html#postSpeechandtextanalyticsProgramsGeneralJobs) | **POST** /api/v2/speechandtextanalytics/programs/general/jobs | Create new Speech &amp; Text Analytics general program job
[**postSpeechandtextanalyticsProgramsPublishjobs**](SpeechTextAnalyticsApi.html#postSpeechandtextanalyticsProgramsPublishjobs) | **POST** /api/v2/speechandtextanalytics/programs/publishjobs | Create new Speech &amp; Text Analytics publish programs job
[**postSpeechandtextanalyticsTopics**](SpeechTextAnalyticsApi.html#postSpeechandtextanalyticsTopics) | **POST** /api/v2/speechandtextanalytics/topics | Create new Speech &amp; Text Analytics topic
[**postSpeechandtextanalyticsTopicsPublishjobs**](SpeechTextAnalyticsApi.html#postSpeechandtextanalyticsTopicsPublishjobs) | **POST** /api/v2/speechandtextanalytics/topics/publishjobs | Create new Speech &amp; Text Analytics publish topics job
[**postSpeechandtextanalyticsTranscriptsSearch**](SpeechTextAnalyticsApi.html#postSpeechandtextanalyticsTranscriptsSearch) | **POST** /api/v2/speechandtextanalytics/transcripts/search | Search resources.
[**putSpeechandtextanalyticsProgram**](SpeechTextAnalyticsApi.html#putSpeechandtextanalyticsProgram) | **PUT** /api/v2/speechandtextanalytics/programs/{programId} | Update existing Speech &amp; Text Analytics program
[**putSpeechandtextanalyticsProgramMappings**](SpeechTextAnalyticsApi.html#putSpeechandtextanalyticsProgramMappings) | **PUT** /api/v2/speechandtextanalytics/programs/{programId}/mappings | Set Speech &amp; Text Analytics program mappings to queues and flows
[**putSpeechandtextanalyticsSettings**](SpeechTextAnalyticsApi.html#putSpeechandtextanalyticsSettings) | **PUT** /api/v2/speechandtextanalytics/settings | Update Speech And Text Analytics Settings
[**putSpeechandtextanalyticsTopic**](SpeechTextAnalyticsApi.html#putSpeechandtextanalyticsTopic) | **PUT** /api/v2/speechandtextanalytics/topics/{topicId} | Update existing Speech &amp; Text Analytics topic
{: class="table table-striped"}

<a name="deleteSpeechandtextanalyticsProgram"></a>

# void deleteSpeechandtextanalyticsProgram(programId, opts)



DELETE /api/v2/speechandtextanalytics/programs/{programId}

Delete a Speech &amp; Text Analytics program by id



Requires ALL permissions: 

* speechAndTextAnalytics:program:delete

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let programId = "programId_example"; // String | The id of the program
let opts = { 
  'forceDelete': false // Boolean | Indicates whether the program is forced to be deleted or not. Required when the program to delete is the default program.
};

apiInstance.deleteSpeechandtextanalyticsProgram(programId, opts)
  .then(() => {
    console.log('deleteSpeechandtextanalyticsProgram returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling deleteSpeechandtextanalyticsProgram');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **programId** | **String** | The id of the program |  |
 **forceDelete** | **Boolean** | Indicates whether the program is forced to be deleted or not. Required when the program to delete is the default program. | [optional] [default to false] |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="deleteSpeechandtextanalyticsTopic"></a>

# void deleteSpeechandtextanalyticsTopic(topicId)



DELETE /api/v2/speechandtextanalytics/topics/{topicId}

Delete a Speech &amp; Text Analytics topic by id



Requires ALL permissions: 

* speechAndTextAnalytics:topic:delete

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let topicId = "topicId_example"; // String | The id of the topic

apiInstance.deleteSpeechandtextanalyticsTopic(topicId)
  .then(() => {
    console.log('deleteSpeechandtextanalyticsTopic returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling deleteSpeechandtextanalyticsTopic');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **topicId** | **String** | The id of the topic |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="getSpeechandtextanalyticsConversation"></a>

# ConversationMetrics getSpeechandtextanalyticsConversation(conversationId)



GET /api/v2/speechandtextanalytics/conversations/{conversationId}

Get Speech and Text Analytics for a specific conversation



Requires ANY permissions: 

* recording:recording:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let conversationId = "conversationId_example"; // String | Conversation Id

apiInstance.getSpeechandtextanalyticsConversation(conversationId)
  .then((data) => {
    console.log(`getSpeechandtextanalyticsConversation success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsConversation');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | Conversation Id |  |
{: class="table table-striped"}

### Return type

**ConversationMetrics**

<a name="getSpeechandtextanalyticsConversationCommunicationTranscripturl"></a>

# TranscriptUrl getSpeechandtextanalyticsConversationCommunicationTranscripturl(conversationId, communicationId)



GET /api/v2/speechandtextanalytics/conversations/{conversationId}/communications/{communicationId}/transcripturl

Get the pre-signed S3 URL for the transcript of a specific communication of a conversation



Requires ANY permissions: 

* recording:recording:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let conversationId = "conversationId_example"; // String | Conversation ID
let communicationId = "communicationId_example"; // String | Communication ID

apiInstance.getSpeechandtextanalyticsConversationCommunicationTranscripturl(conversationId, communicationId)
  .then((data) => {
    console.log(`getSpeechandtextanalyticsConversationCommunicationTranscripturl success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsConversationCommunicationTranscripturl');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | Conversation ID |  |
 **communicationId** | **String** | Communication ID |  |
{: class="table table-striped"}

### Return type

**TranscriptUrl**

<a name="getSpeechandtextanalyticsDialects"></a>

# **[Object]** getSpeechandtextanalyticsDialects()



GET /api/v2/speechandtextanalytics/dialects

Get list of supported Speech &amp; Text Analytics dialects



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

apiInstance.getSpeechandtextanalyticsDialects()
  .then((data) => {
    console.log(`getSpeechandtextanalyticsDialects success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsDialects');
    console.error(err);
  });
```

### Parameters

This endpoint does not need any parameter.


### Return type

**[Object]**

<a name="getSpeechandtextanalyticsProgram"></a>

# Program getSpeechandtextanalyticsProgram(programId)



GET /api/v2/speechandtextanalytics/programs/{programId}

Get a Speech &amp; Text Analytics program by id



Requires ALL permissions: 

* speechAndTextAnalytics:program:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let programId = "programId_example"; // String | The id of the program

apiInstance.getSpeechandtextanalyticsProgram(programId)
  .then((data) => {
    console.log(`getSpeechandtextanalyticsProgram success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsProgram');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **programId** | **String** | The id of the program |  |
{: class="table table-striped"}

### Return type

**Program**

<a name="getSpeechandtextanalyticsProgramMappings"></a>

# ProgramMappings getSpeechandtextanalyticsProgramMappings(programId)



GET /api/v2/speechandtextanalytics/programs/{programId}/mappings

Get Speech &amp; Text Analytics program mappings to queues and flows by id



Requires ALL permissions: 

* speechAndTextAnalytics:program:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let programId = "programId_example"; // String | The id of the program

apiInstance.getSpeechandtextanalyticsProgramMappings(programId)
  .then((data) => {
    console.log(`getSpeechandtextanalyticsProgramMappings success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsProgramMappings');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **programId** | **String** | The id of the program |  |
{: class="table table-striped"}

### Return type

**ProgramMappings**

<a name="getSpeechandtextanalyticsPrograms"></a>

# ProgramsEntityListing getSpeechandtextanalyticsPrograms(opts)



GET /api/v2/speechandtextanalytics/programs

Get the list of Speech &amp; Text Analytics programs



Requires ALL permissions: 

* speechAndTextAnalytics:program:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let opts = { 
  'nextPage': "nextPage_example", // String | The key for listing the next page
  'pageSize': 20 // Number | The page size for the listing
};

apiInstance.getSpeechandtextanalyticsPrograms(opts)
  .then((data) => {
    console.log(`getSpeechandtextanalyticsPrograms success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsPrograms');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **nextPage** | **String** | The key for listing the next page | [optional]  |
 **pageSize** | **Number** | The page size for the listing | [optional] [default to 20] |
{: class="table table-striped"}

### Return type

**ProgramsEntityListing**

<a name="getSpeechandtextanalyticsProgramsGeneralJob"></a>

# GeneralProgramJob getSpeechandtextanalyticsProgramsGeneralJob(jobId)



GET /api/v2/speechandtextanalytics/programs/general/jobs/{jobId}

Get a Speech &amp; Text Analytics general program job by id



Requires ALL permissions: 

* speechAndTextAnalytics:program:add
* speechAndTextAnalytics:program:edit
* speechAndTextAnalytics:topic:add
* speechAndTextAnalytics:topic:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let jobId = "jobId_example"; // String | The id of the publish programs job

apiInstance.getSpeechandtextanalyticsProgramsGeneralJob(jobId)
  .then((data) => {
    console.log(`getSpeechandtextanalyticsProgramsGeneralJob success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsProgramsGeneralJob');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **jobId** | **String** | The id of the publish programs job |  |
{: class="table table-striped"}

### Return type

**GeneralProgramJob**

<a name="getSpeechandtextanalyticsProgramsMappings"></a>

# ProgramsMappingsEntityListing getSpeechandtextanalyticsProgramsMappings(opts)



GET /api/v2/speechandtextanalytics/programs/mappings

Get the list of Speech &amp; Text Analytics programs mappings to queues and flows



Requires ALL permissions: 

* speechAndTextAnalytics:program:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let opts = { 
  'nextPage': "nextPage_example", // String | The key for listing the next page
  'pageSize': 20 // Number | The page size for the listing
};

apiInstance.getSpeechandtextanalyticsProgramsMappings(opts)
  .then((data) => {
    console.log(`getSpeechandtextanalyticsProgramsMappings success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsProgramsMappings');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **nextPage** | **String** | The key for listing the next page | [optional]  |
 **pageSize** | **Number** | The page size for the listing | [optional] [default to 20] |
{: class="table table-striped"}

### Return type

**ProgramsMappingsEntityListing**

<a name="getSpeechandtextanalyticsProgramsPublishjob"></a>

# ProgramJob getSpeechandtextanalyticsProgramsPublishjob(jobId)



GET /api/v2/speechandtextanalytics/programs/publishjobs/{jobId}

Get a Speech &amp; Text Analytics publish programs job by id



Requires ALL permissions: 

* speechAndTextAnalytics:program:publish

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let jobId = "jobId_example"; // String | The id of the publish programs job

apiInstance.getSpeechandtextanalyticsProgramsPublishjob(jobId)
  .then((data) => {
    console.log(`getSpeechandtextanalyticsProgramsPublishjob success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsProgramsPublishjob');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **jobId** | **String** | The id of the publish programs job |  |
{: class="table table-striped"}

### Return type

**ProgramJob**

<a name="getSpeechandtextanalyticsProgramsUnpublished"></a>

# UnpublishedProgramsEntityListing getSpeechandtextanalyticsProgramsUnpublished(opts)



GET /api/v2/speechandtextanalytics/programs/unpublished

Get the list of Speech &amp; Text Analytics unpublished programs



Requires ALL permissions: 

* speechAndTextAnalytics:program:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let opts = { 
  'nextPage': "nextPage_example", // String | The key for listing the next page
  'pageSize': 20 // Number | The page size for the listing
};

apiInstance.getSpeechandtextanalyticsProgramsUnpublished(opts)
  .then((data) => {
    console.log(`getSpeechandtextanalyticsProgramsUnpublished success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsProgramsUnpublished');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **nextPage** | **String** | The key for listing the next page | [optional]  |
 **pageSize** | **Number** | The page size for the listing | [optional] [default to 20] |
{: class="table table-striped"}

### Return type

**UnpublishedProgramsEntityListing**

<a name="getSpeechandtextanalyticsSettings"></a>

# SpeechTextAnalyticsSettingsResponse getSpeechandtextanalyticsSettings()



GET /api/v2/speechandtextanalytics/settings

Get Speech And Text Analytics Settings



Requires ALL permissions: 

* speechAndTextAnalytics:settings:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

apiInstance.getSpeechandtextanalyticsSettings()
  .then((data) => {
    console.log(`getSpeechandtextanalyticsSettings success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsSettings');
    console.error(err);
  });
```

### Parameters

This endpoint does not need any parameter.


### Return type

**SpeechTextAnalyticsSettingsResponse**

<a name="getSpeechandtextanalyticsTopic"></a>

# Topic getSpeechandtextanalyticsTopic(topicId)



GET /api/v2/speechandtextanalytics/topics/{topicId}

Get a Speech &amp; Text Analytics topic by id



Requires ALL permissions: 

* speechAndTextAnalytics:topic:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let topicId = "topicId_example"; // String | The id of the topic

apiInstance.getSpeechandtextanalyticsTopic(topicId)
  .then((data) => {
    console.log(`getSpeechandtextanalyticsTopic success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsTopic');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **topicId** | **String** | The id of the topic |  |
{: class="table table-striped"}

### Return type

**Topic**

<a name="getSpeechandtextanalyticsTopics"></a>

# TopicsEntityListing getSpeechandtextanalyticsTopics(opts)



GET /api/v2/speechandtextanalytics/topics

Get the list of Speech &amp; Text Analytics topics



Requires ALL permissions: 

* speechAndTextAnalytics:topic:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let opts = { 
  'nextPage': "nextPage_example", // String | The key for listing the next page
  'pageSize': 20, // Number | The page size for the listing
  'state': "state_example", // String | Topic state. Defaults to latest
  'name': "name_example", // String | Case insensitive partial name to filter by
  'ids': ["ids_example"], // [String] | Comma separated Topic IDs to filter by. Cannot be used with other filters. Maximum of 50 IDs allowed.
  'sortBy': "sortBy_example", // String | Sort results by. Defaults to name
  'sortOrder': "sortOrder_example" // String | Sort order. Defaults to asc
};

apiInstance.getSpeechandtextanalyticsTopics(opts)
  .then((data) => {
    console.log(`getSpeechandtextanalyticsTopics success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsTopics');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **nextPage** | **String** | The key for listing the next page | [optional]  |
 **pageSize** | **Number** | The page size for the listing | [optional] [default to 20] |
 **state** | **String** | Topic state. Defaults to latest | [optional] <br />**Values**: latest, published |
 **name** | **String** | Case insensitive partial name to filter by | [optional]  |
 **ids** | **[String]** | Comma separated Topic IDs to filter by. Cannot be used with other filters. Maximum of 50 IDs allowed. | [optional]  |
 **sortBy** | **String** | Sort results by. Defaults to name | [optional] <br />**Values**: name |
 **sortOrder** | **String** | Sort order. Defaults to asc | [optional] <br />**Values**: asc, desc |
{: class="table table-striped"}

### Return type

**TopicsEntityListing**

<a name="getSpeechandtextanalyticsTopicsDialects"></a>

# EntityListing getSpeechandtextanalyticsTopicsDialects()



GET /api/v2/speechandtextanalytics/topics/dialects

Get list of supported Speech &amp; Text Analytics topics dialects



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

apiInstance.getSpeechandtextanalyticsTopicsDialects()
  .then((data) => {
    console.log(`getSpeechandtextanalyticsTopicsDialects success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsTopicsDialects');
    console.error(err);
  });
```

### Parameters

This endpoint does not need any parameter.


### Return type

**EntityListing**

<a name="getSpeechandtextanalyticsTopicsGeneral"></a>

# GeneralTopicsEntityListing getSpeechandtextanalyticsTopicsGeneral(opts)



GET /api/v2/speechandtextanalytics/topics/general

Get the Speech &amp; Text Analytics general topics for a given dialect



Requires ALL permissions: 

* speechAndTextAnalytics:topic:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let opts = { 
  'dialect': "dialect_example" // String | The dialect of the general topics, dialect format is {language}-{country} where language follows ISO 639-1 standard and country follows ISO 3166-1 alpha 2 standard
};

apiInstance.getSpeechandtextanalyticsTopicsGeneral(opts)
  .then((data) => {
    console.log(`getSpeechandtextanalyticsTopicsGeneral success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsTopicsGeneral');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **dialect** | **String** | The dialect of the general topics, dialect format is {language}-{country} where language follows ISO 639-1 standard and country follows ISO 3166-1 alpha 2 standard | [optional] <br />**Values**: en-US, es-US, en-AU, en-GB, en-ZA, es-ES, en-IN, fr-FR, fr-CA, it-IT, de-DE, pt-BR |
{: class="table table-striped"}

### Return type

**GeneralTopicsEntityListing**

<a name="getSpeechandtextanalyticsTopicsPublishjob"></a>

# TopicJob getSpeechandtextanalyticsTopicsPublishjob(jobId)



GET /api/v2/speechandtextanalytics/topics/publishjobs/{jobId}

Get a Speech &amp; Text Analytics publish topics job by id



Requires ALL permissions: 

* speechAndTextAnalytics:topic:publish

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let jobId = "jobId_example"; // String | The id of the publish topics job

apiInstance.getSpeechandtextanalyticsTopicsPublishjob(jobId)
  .then((data) => {
    console.log(`getSpeechandtextanalyticsTopicsPublishjob success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getSpeechandtextanalyticsTopicsPublishjob');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **jobId** | **String** | The id of the publish topics job |  |
{: class="table table-striped"}

### Return type

**TopicJob**

<a name="patchSpeechandtextanalyticsSettings"></a>

# SpeechTextAnalyticsSettingsResponse patchSpeechandtextanalyticsSettings(body)



PATCH /api/v2/speechandtextanalytics/settings

Patch Speech And Text Analytics Settings



Requires ALL permissions: 

* speechAndTextAnalytics:settings:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let body = {}; // Object | Speech And Text Analytics Settings

apiInstance.patchSpeechandtextanalyticsSettings(body)
  .then((data) => {
    console.log(`patchSpeechandtextanalyticsSettings success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchSpeechandtextanalyticsSettings');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | Speech And Text Analytics Settings |  |
{: class="table table-striped"}

### Return type

**SpeechTextAnalyticsSettingsResponse**

<a name="postSpeechandtextanalyticsPrograms"></a>

# Program postSpeechandtextanalyticsPrograms(body)



POST /api/v2/speechandtextanalytics/programs

Create new Speech &amp; Text Analytics program



Requires ALL permissions: 

* speechAndTextAnalytics:program:add

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let body = {}; // Object | The program to create

apiInstance.postSpeechandtextanalyticsPrograms(body)
  .then((data) => {
    console.log(`postSpeechandtextanalyticsPrograms success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postSpeechandtextanalyticsPrograms');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | The program to create |  |
{: class="table table-striped"}

### Return type

**Program**

<a name="postSpeechandtextanalyticsProgramsGeneralJobs"></a>

# GeneralProgramJob postSpeechandtextanalyticsProgramsGeneralJobs(body)



POST /api/v2/speechandtextanalytics/programs/general/jobs

Create new Speech &amp; Text Analytics general program job



Requires ALL permissions: 

* speechAndTextAnalytics:program:add
* speechAndTextAnalytics:program:edit
* speechAndTextAnalytics:topic:add
* speechAndTextAnalytics:topic:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let body = {}; // Object | The general programs job to create

apiInstance.postSpeechandtextanalyticsProgramsGeneralJobs(body)
  .then((data) => {
    console.log(`postSpeechandtextanalyticsProgramsGeneralJobs success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postSpeechandtextanalyticsProgramsGeneralJobs');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | The general programs job to create |  |
{: class="table table-striped"}

### Return type

**GeneralProgramJob**

<a name="postSpeechandtextanalyticsProgramsPublishjobs"></a>

# ProgramJob postSpeechandtextanalyticsProgramsPublishjobs(body)



POST /api/v2/speechandtextanalytics/programs/publishjobs

Create new Speech &amp; Text Analytics publish programs job



Requires ALL permissions: 

* speechAndTextAnalytics:program:publish

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let body = {}; // Object | The publish programs job to create

apiInstance.postSpeechandtextanalyticsProgramsPublishjobs(body)
  .then((data) => {
    console.log(`postSpeechandtextanalyticsProgramsPublishjobs success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postSpeechandtextanalyticsProgramsPublishjobs');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | The publish programs job to create |  |
{: class="table table-striped"}

### Return type

**ProgramJob**

<a name="postSpeechandtextanalyticsTopics"></a>

# Topic postSpeechandtextanalyticsTopics(body)



POST /api/v2/speechandtextanalytics/topics

Create new Speech &amp; Text Analytics topic



Requires ALL permissions: 

* speechAndTextAnalytics:topic:add

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let body = {}; // Object | The topic to create

apiInstance.postSpeechandtextanalyticsTopics(body)
  .then((data) => {
    console.log(`postSpeechandtextanalyticsTopics success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postSpeechandtextanalyticsTopics');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | The topic to create |  |
{: class="table table-striped"}

### Return type

**Topic**

<a name="postSpeechandtextanalyticsTopicsPublishjobs"></a>

# TopicJob postSpeechandtextanalyticsTopicsPublishjobs(body)



POST /api/v2/speechandtextanalytics/topics/publishjobs

Create new Speech &amp; Text Analytics publish topics job



Requires ALL permissions: 

* speechAndTextAnalytics:topic:publish

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let body = {}; // Object | The publish topics job to create

apiInstance.postSpeechandtextanalyticsTopicsPublishjobs(body)
  .then((data) => {
    console.log(`postSpeechandtextanalyticsTopicsPublishjobs success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postSpeechandtextanalyticsTopicsPublishjobs');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | The publish topics job to create |  |
{: class="table table-striped"}

### Return type

**TopicJob**

<a name="postSpeechandtextanalyticsTranscriptsSearch"></a>

# JsonSearchResponse postSpeechandtextanalyticsTranscriptsSearch(body)



POST /api/v2/speechandtextanalytics/transcripts/search

Search resources.



Requires ANY permissions: 

* analytics:conversationDetail:view
* recording:recording:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let body = {}; // Object | Search request options

apiInstance.postSpeechandtextanalyticsTranscriptsSearch(body)
  .then((data) => {
    console.log(`postSpeechandtextanalyticsTranscriptsSearch success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postSpeechandtextanalyticsTranscriptsSearch');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | Search request options |  |
{: class="table table-striped"}

### Return type

**JsonSearchResponse**

<a name="putSpeechandtextanalyticsProgram"></a>

# Program putSpeechandtextanalyticsProgram(programId, body)



PUT /api/v2/speechandtextanalytics/programs/{programId}

Update existing Speech &amp; Text Analytics program



Requires ALL permissions: 

* speechAndTextAnalytics:program:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let programId = "programId_example"; // String | The id of the program
let body = {}; // Object | The program to update

apiInstance.putSpeechandtextanalyticsProgram(programId, body)
  .then((data) => {
    console.log(`putSpeechandtextanalyticsProgram success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling putSpeechandtextanalyticsProgram');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **programId** | **String** | The id of the program |  |
 **body** | **Object** | The program to update |  |
{: class="table table-striped"}

### Return type

**Program**

<a name="putSpeechandtextanalyticsProgramMappings"></a>

# ProgramMappings putSpeechandtextanalyticsProgramMappings(programId, body)



PUT /api/v2/speechandtextanalytics/programs/{programId}/mappings

Set Speech &amp; Text Analytics program mappings to queues and flows



Requires ALL permissions: 

* speechAndTextAnalytics:program:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let programId = "programId_example"; // String | The id of the program
let body = {}; // Object | The program to set mappings for

apiInstance.putSpeechandtextanalyticsProgramMappings(programId, body)
  .then((data) => {
    console.log(`putSpeechandtextanalyticsProgramMappings success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling putSpeechandtextanalyticsProgramMappings');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **programId** | **String** | The id of the program |  |
 **body** | **Object** | The program to set mappings for |  |
{: class="table table-striped"}

### Return type

**ProgramMappings**

<a name="putSpeechandtextanalyticsSettings"></a>

# SpeechTextAnalyticsSettingsResponse putSpeechandtextanalyticsSettings(body)



PUT /api/v2/speechandtextanalytics/settings

Update Speech And Text Analytics Settings



Requires ALL permissions: 

* speechAndTextAnalytics:settings:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let body = {}; // Object | Speech And Text Analytics Settings

apiInstance.putSpeechandtextanalyticsSettings(body)
  .then((data) => {
    console.log(`putSpeechandtextanalyticsSettings success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling putSpeechandtextanalyticsSettings');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | Speech And Text Analytics Settings |  |
{: class="table table-striped"}

### Return type

**SpeechTextAnalyticsSettingsResponse**

<a name="putSpeechandtextanalyticsTopic"></a>

# Topic putSpeechandtextanalyticsTopic(topicId, body)



PUT /api/v2/speechandtextanalytics/topics/{topicId}

Update existing Speech &amp; Text Analytics topic



Requires ALL permissions: 

* speechAndTextAnalytics:topic:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.SpeechTextAnalyticsApi();

let topicId = "topicId_example"; // String | The id of the topic
let body = {}; // Object | The topic to update

apiInstance.putSpeechandtextanalyticsTopic(topicId, body)
  .then((data) => {
    console.log(`putSpeechandtextanalyticsTopic success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling putSpeechandtextanalyticsTopic');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **topicId** | **String** | The id of the topic |  |
 **body** | **Object** | The topic to update |  |
{: class="table table-striped"}

### Return type

**Topic**

