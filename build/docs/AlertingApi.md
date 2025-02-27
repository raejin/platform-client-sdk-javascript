---
title: AlertingApi
---
# platformClient.AlertingApi

All URIs are relative to *https://api.mypurecloud.com*

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
[**deleteAlertingInteractionstatsAlert**](AlertingApi.html#deleteAlertingInteractionstatsAlert) | **DELETE** /api/v2/alerting/interactionstats/alerts/{alertId} | Delete an interaction stats alert
[**deleteAlertingInteractionstatsRule**](AlertingApi.html#deleteAlertingInteractionstatsRule) | **DELETE** /api/v2/alerting/interactionstats/rules/{ruleId} | Delete an interaction stats rule.
[**getAlertingAlertsActive**](AlertingApi.html#getAlertingAlertsActive) | **GET** /api/v2/alerting/alerts/active | Gets active alert count for a user.
[**getAlertingInteractionstatsAlert**](AlertingApi.html#getAlertingInteractionstatsAlert) | **GET** /api/v2/alerting/interactionstats/alerts/{alertId} | Get an interaction stats alert
[**getAlertingInteractionstatsAlerts**](AlertingApi.html#getAlertingInteractionstatsAlerts) | **GET** /api/v2/alerting/interactionstats/alerts | Get interaction stats alert list.
[**getAlertingInteractionstatsAlertsUnread**](AlertingApi.html#getAlertingInteractionstatsAlertsUnread) | **GET** /api/v2/alerting/interactionstats/alerts/unread | Gets user unread count of interaction stats alerts.
[**getAlertingInteractionstatsRule**](AlertingApi.html#getAlertingInteractionstatsRule) | **GET** /api/v2/alerting/interactionstats/rules/{ruleId} | Get an interaction stats rule.
[**getAlertingInteractionstatsRules**](AlertingApi.html#getAlertingInteractionstatsRules) | **GET** /api/v2/alerting/interactionstats/rules | Get an interaction stats rule list.
[**postAlertingInteractionstatsRules**](AlertingApi.html#postAlertingInteractionstatsRules) | **POST** /api/v2/alerting/interactionstats/rules | Create an interaction stats rule.
[**putAlertingInteractionstatsAlert**](AlertingApi.html#putAlertingInteractionstatsAlert) | **PUT** /api/v2/alerting/interactionstats/alerts/{alertId} | Update an interaction stats alert read status
[**putAlertingInteractionstatsRule**](AlertingApi.html#putAlertingInteractionstatsRule) | **PUT** /api/v2/alerting/interactionstats/rules/{ruleId} | Update an interaction stats rule
{: class="table table-striped"}

<a name="deleteAlertingInteractionstatsAlert"></a>

# void deleteAlertingInteractionstatsAlert(alertId)



DELETE /api/v2/alerting/interactionstats/alerts/{alertId}

Delete an interaction stats alert



Requires ALL permissions: 

* alerting:alert:delete

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.AlertingApi();

let alertId = "alertId_example"; // String | Alert ID

apiInstance.deleteAlertingInteractionstatsAlert(alertId)
  .then(() => {
    console.log('deleteAlertingInteractionstatsAlert returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling deleteAlertingInteractionstatsAlert');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **alertId** | **String** | Alert ID |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="deleteAlertingInteractionstatsRule"></a>

# void deleteAlertingInteractionstatsRule(ruleId)



DELETE /api/v2/alerting/interactionstats/rules/{ruleId}

Delete an interaction stats rule.



Requires ALL permissions: 

* alerting:rule:delete

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.AlertingApi();

let ruleId = "ruleId_example"; // String | Rule ID

apiInstance.deleteAlertingInteractionstatsRule(ruleId)
  .then(() => {
    console.log('deleteAlertingInteractionstatsRule returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling deleteAlertingInteractionstatsRule');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **ruleId** | **String** | Rule ID |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="getAlertingAlertsActive"></a>

# ActiveAlertCount getAlertingAlertsActive()



GET /api/v2/alerting/alerts/active

Gets active alert count for a user.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.AlertingApi();

apiInstance.getAlertingAlertsActive()
  .then((data) => {
    console.log(`getAlertingAlertsActive success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getAlertingAlertsActive');
    console.error(err);
  });
```

### Parameters

This endpoint does not need any parameter.


### Return type

**ActiveAlertCount**

<a name="getAlertingInteractionstatsAlert"></a>

# InteractionStatsAlert getAlertingInteractionstatsAlert(alertId, opts)



GET /api/v2/alerting/interactionstats/alerts/{alertId}

Get an interaction stats alert



Requires ALL permissions: 

* alerting:alert:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.AlertingApi();

let alertId = "alertId_example"; // String | Alert ID
let opts = { 
  'expand': ["expand_example"] // [String] | Which fields, if any, to expand
};

apiInstance.getAlertingInteractionstatsAlert(alertId, opts)
  .then((data) => {
    console.log(`getAlertingInteractionstatsAlert success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getAlertingInteractionstatsAlert');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **alertId** | **String** | Alert ID |  |
 **expand** | **[String]** | Which fields, if any, to expand | [optional] <br />**Values**: notificationUsers |
{: class="table table-striped"}

### Return type

**InteractionStatsAlert**

<a name="getAlertingInteractionstatsAlerts"></a>

# InteractionStatsAlertContainer getAlertingInteractionstatsAlerts(opts)



GET /api/v2/alerting/interactionstats/alerts

Get interaction stats alert list.



Requires ALL permissions: 

* alerting:alert:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.AlertingApi();

let opts = { 
  'expand': ["expand_example"] // [String] | Which fields, if any, to expand
};

apiInstance.getAlertingInteractionstatsAlerts(opts)
  .then((data) => {
    console.log(`getAlertingInteractionstatsAlerts success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getAlertingInteractionstatsAlerts');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **expand** | **[String]** | Which fields, if any, to expand | [optional] <br />**Values**: notificationUsers |
{: class="table table-striped"}

### Return type

**InteractionStatsAlertContainer**

<a name="getAlertingInteractionstatsAlertsUnread"></a>

# UnreadMetric getAlertingInteractionstatsAlertsUnread()



GET /api/v2/alerting/interactionstats/alerts/unread

Gets user unread count of interaction stats alerts.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.AlertingApi();

apiInstance.getAlertingInteractionstatsAlertsUnread()
  .then((data) => {
    console.log(`getAlertingInteractionstatsAlertsUnread success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getAlertingInteractionstatsAlertsUnread');
    console.error(err);
  });
```

### Parameters

This endpoint does not need any parameter.


### Return type

**UnreadMetric**

<a name="getAlertingInteractionstatsRule"></a>

# InteractionStatsRule getAlertingInteractionstatsRule(ruleId, opts)



GET /api/v2/alerting/interactionstats/rules/{ruleId}

Get an interaction stats rule.



Requires ALL permissions: 

* alerting:rule:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.AlertingApi();

let ruleId = "ruleId_example"; // String | Rule ID
let opts = { 
  'expand': ["expand_example"] // [String] | Which fields, if any, to expand
};

apiInstance.getAlertingInteractionstatsRule(ruleId, opts)
  .then((data) => {
    console.log(`getAlertingInteractionstatsRule success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getAlertingInteractionstatsRule');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **ruleId** | **String** | Rule ID |  |
 **expand** | **[String]** | Which fields, if any, to expand | [optional] <br />**Values**: notificationUsers |
{: class="table table-striped"}

### Return type

**InteractionStatsRule**

<a name="getAlertingInteractionstatsRules"></a>

# InteractionStatsRuleContainer getAlertingInteractionstatsRules(opts)



GET /api/v2/alerting/interactionstats/rules

Get an interaction stats rule list.



Requires ALL permissions: 

* alerting:rule:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.AlertingApi();

let opts = { 
  'expand': ["expand_example"] // [String] | Which fields, if any, to expand
};

apiInstance.getAlertingInteractionstatsRules(opts)
  .then((data) => {
    console.log(`getAlertingInteractionstatsRules success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getAlertingInteractionstatsRules');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **expand** | **[String]** | Which fields, if any, to expand | [optional] <br />**Values**: notificationUsers |
{: class="table table-striped"}

### Return type

**InteractionStatsRuleContainer**

<a name="postAlertingInteractionstatsRules"></a>

# InteractionStatsRule postAlertingInteractionstatsRules(body, opts)



POST /api/v2/alerting/interactionstats/rules

Create an interaction stats rule.



Requires ALL permissions: 

* alerting:rule:add

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.AlertingApi();

let body = {}; // Object | AlertingRule
let opts = { 
  'expand': ["expand_example"] // [String] | Which fields, if any, to expand
};

apiInstance.postAlertingInteractionstatsRules(body, opts)
  .then((data) => {
    console.log(`postAlertingInteractionstatsRules success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postAlertingInteractionstatsRules');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | AlertingRule |  |
 **expand** | **[String]** | Which fields, if any, to expand | [optional] <br />**Values**: notificationUsers |
{: class="table table-striped"}

### Return type

**InteractionStatsRule**

<a name="putAlertingInteractionstatsAlert"></a>

# UnreadStatus putAlertingInteractionstatsAlert(alertId, body, opts)



PUT /api/v2/alerting/interactionstats/alerts/{alertId}

Update an interaction stats alert read status



Requires ALL permissions: 

* alerting:alert:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.AlertingApi();

let alertId = "alertId_example"; // String | Alert ID
let body = {}; // Object | InteractionStatsAlert
let opts = { 
  'expand': ["expand_example"] // [String] | Which fields, if any, to expand
};

apiInstance.putAlertingInteractionstatsAlert(alertId, body, opts)
  .then((data) => {
    console.log(`putAlertingInteractionstatsAlert success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling putAlertingInteractionstatsAlert');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **alertId** | **String** | Alert ID |  |
 **body** | **Object** | InteractionStatsAlert |  |
 **expand** | **[String]** | Which fields, if any, to expand | [optional] <br />**Values**: notificationUsers |
{: class="table table-striped"}

### Return type

**UnreadStatus**

<a name="putAlertingInteractionstatsRule"></a>

# InteractionStatsRule putAlertingInteractionstatsRule(ruleId, body, opts)



PUT /api/v2/alerting/interactionstats/rules/{ruleId}

Update an interaction stats rule



Requires ALL permissions: 

* alerting:rule:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.AlertingApi();

let ruleId = "ruleId_example"; // String | Rule ID
let body = {}; // Object | AlertingRule
let opts = { 
  'expand': ["expand_example"] // [String] | Which fields, if any, to expand
};

apiInstance.putAlertingInteractionstatsRule(ruleId, body, opts)
  .then((data) => {
    console.log(`putAlertingInteractionstatsRule success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling putAlertingInteractionstatsRule');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **ruleId** | **String** | Rule ID |  |
 **body** | **Object** | AlertingRule |  |
 **expand** | **[String]** | Which fields, if any, to expand | [optional] <br />**Values**: notificationUsers |
{: class="table table-striped"}

### Return type

**InteractionStatsRule**

