---
title: ConversationsApi
---
# platformClient.ConversationsApi

All URIs are relative to *https://api.mypurecloud.com*

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
[**deleteAnalyticsConversationsDetailsJob**](ConversationsApi.html#deleteAnalyticsConversationsDetailsJob) | **DELETE** /api/v2/analytics/conversations/details/jobs/{jobId} | Delete/cancel an async request
[**deleteConversationParticipantCode**](ConversationsApi.html#deleteConversationParticipantCode) | **DELETE** /api/v2/conversations/{conversationId}/participants/{participantId}/codes/{addCommunicationCode} | Delete a code used to add a communication to this participant
[**deleteConversationParticipantFlaggedreason**](ConversationsApi.html#deleteConversationParticipantFlaggedreason) | **DELETE** /api/v2/conversations/{conversationId}/participants/{participantId}/flaggedreason | Remove flagged reason from conversation participant.
[**deleteConversationsCallParticipantConsult**](ConversationsApi.html#deleteConversationsCallParticipantConsult) | **DELETE** /api/v2/conversations/calls/{conversationId}/participants/{participantId}/consult | Cancel the transfer
[**deleteConversationsEmailMessagesDraftAttachment**](ConversationsApi.html#deleteConversationsEmailMessagesDraftAttachment) | **DELETE** /api/v2/conversations/emails/{conversationId}/messages/draft/attachments/{attachmentId} | Delete attachment from draft
[**deleteConversationsMessagingIntegrationsFacebookIntegrationId**](ConversationsApi.html#deleteConversationsMessagingIntegrationsFacebookIntegrationId) | **DELETE** /api/v2/conversations/messaging/integrations/facebook/{integrationId} | Delete a Facebook messaging integration
[**deleteConversationsMessagingIntegrationsLineIntegrationId**](ConversationsApi.html#deleteConversationsMessagingIntegrationsLineIntegrationId) | **DELETE** /api/v2/conversations/messaging/integrations/line/{integrationId} | Delete a LINE messenger integration
[**deleteConversationsMessagingIntegrationsOpenIntegrationId**](ConversationsApi.html#deleteConversationsMessagingIntegrationsOpenIntegrationId) | **DELETE** /api/v2/conversations/messaging/integrations/open/{integrationId} | Delete an Open messaging integration
[**deleteConversationsMessagingIntegrationsTwitterIntegrationId**](ConversationsApi.html#deleteConversationsMessagingIntegrationsTwitterIntegrationId) | **DELETE** /api/v2/conversations/messaging/integrations/twitter/{integrationId} | Delete a Twitter messaging integration
[**deleteConversationsMessagingIntegrationsWhatsappIntegrationId**](ConversationsApi.html#deleteConversationsMessagingIntegrationsWhatsappIntegrationId) | **DELETE** /api/v2/conversations/messaging/integrations/whatsapp/{integrationId} | Delete a WhatsApp messaging integration
[**getAnalyticsConversationDetails**](ConversationsApi.html#getAnalyticsConversationDetails) | **GET** /api/v2/analytics/conversations/{conversationId}/details | Get a conversation by id
[**getAnalyticsConversationsDetails**](ConversationsApi.html#getAnalyticsConversationsDetails) | **GET** /api/v2/analytics/conversations/details | Gets multiple conversations by id
[**getAnalyticsConversationsDetailsJob**](ConversationsApi.html#getAnalyticsConversationsDetailsJob) | **GET** /api/v2/analytics/conversations/details/jobs/{jobId} | Get status for async query for conversation details
[**getAnalyticsConversationsDetailsJobResults**](ConversationsApi.html#getAnalyticsConversationsDetailsJobResults) | **GET** /api/v2/analytics/conversations/details/jobs/{jobId}/results | Fetch a page of results for an async query
[**getAnalyticsConversationsDetailsJobsAvailability**](ConversationsApi.html#getAnalyticsConversationsDetailsJobsAvailability) | **GET** /api/v2/analytics/conversations/details/jobs/availability | Lookup the datalake availability date and time
[**getConversation**](ConversationsApi.html#getConversation) | **GET** /api/v2/conversations/{conversationId} | Get conversation
[**getConversationParticipantSecureivrsession**](ConversationsApi.html#getConversationParticipantSecureivrsession) | **GET** /api/v2/conversations/{conversationId}/participants/{participantId}/secureivrsessions/{secureSessionId} | Fetch info on a secure session
[**getConversationParticipantSecureivrsessions**](ConversationsApi.html#getConversationParticipantSecureivrsessions) | **GET** /api/v2/conversations/{conversationId}/participants/{participantId}/secureivrsessions | Get a list of secure sessions for this participant.
[**getConversationParticipantWrapup**](ConversationsApi.html#getConversationParticipantWrapup) | **GET** /api/v2/conversations/{conversationId}/participants/{participantId}/wrapup | Get the wrap-up for this conversation participant. 
[**getConversationParticipantWrapupcodes**](ConversationsApi.html#getConversationParticipantWrapupcodes) | **GET** /api/v2/conversations/{conversationId}/participants/{participantId}/wrapupcodes | Get list of wrapup codes for this conversation participant
[**getConversations**](ConversationsApi.html#getConversations) | **GET** /api/v2/conversations | Get active conversations for the logged in user
[**getConversationsCall**](ConversationsApi.html#getConversationsCall) | **GET** /api/v2/conversations/calls/{conversationId} | Get call conversation
[**getConversationsCallParticipantWrapup**](ConversationsApi.html#getConversationsCallParticipantWrapup) | **GET** /api/v2/conversations/calls/{conversationId}/participants/{participantId}/wrapup | Get the wrap-up for this conversation participant. 
[**getConversationsCallParticipantWrapupcodes**](ConversationsApi.html#getConversationsCallParticipantWrapupcodes) | **GET** /api/v2/conversations/calls/{conversationId}/participants/{participantId}/wrapupcodes | Get list of wrapup codes for this conversation participant
[**getConversationsCallback**](ConversationsApi.html#getConversationsCallback) | **GET** /api/v2/conversations/callbacks/{conversationId} | Get callback conversation
[**getConversationsCallbackParticipantWrapup**](ConversationsApi.html#getConversationsCallbackParticipantWrapup) | **GET** /api/v2/conversations/callbacks/{conversationId}/participants/{participantId}/wrapup | Get the wrap-up for this conversation participant. 
[**getConversationsCallbackParticipantWrapupcodes**](ConversationsApi.html#getConversationsCallbackParticipantWrapupcodes) | **GET** /api/v2/conversations/callbacks/{conversationId}/participants/{participantId}/wrapupcodes | Get list of wrapup codes for this conversation participant
[**getConversationsCallbacks**](ConversationsApi.html#getConversationsCallbacks) | **GET** /api/v2/conversations/callbacks | Get active callback conversations for the logged in user
[**getConversationsCalls**](ConversationsApi.html#getConversationsCalls) | **GET** /api/v2/conversations/calls | Get active call conversations for the logged in user
[**getConversationsCallsHistory**](ConversationsApi.html#getConversationsCallsHistory) | **GET** /api/v2/conversations/calls/history | Get call history
[**getConversationsCallsMaximumconferenceparties**](ConversationsApi.html#getConversationsCallsMaximumconferenceparties) | **GET** /api/v2/conversations/calls/maximumconferenceparties | Get the maximum number of participants that this user can have on a conference
[**getConversationsChat**](ConversationsApi.html#getConversationsChat) | **GET** /api/v2/conversations/chats/{conversationId} | Get chat conversation
[**getConversationsChatMessage**](ConversationsApi.html#getConversationsChatMessage) | **GET** /api/v2/conversations/chats/{conversationId}/messages/{messageId} | Get a web chat conversation message
[**getConversationsChatMessages**](ConversationsApi.html#getConversationsChatMessages) | **GET** /api/v2/conversations/chats/{conversationId}/messages | Get the messages of a chat conversation.
[**getConversationsChatParticipantWrapup**](ConversationsApi.html#getConversationsChatParticipantWrapup) | **GET** /api/v2/conversations/chats/{conversationId}/participants/{participantId}/wrapup | Get the wrap-up for this conversation participant. 
[**getConversationsChatParticipantWrapupcodes**](ConversationsApi.html#getConversationsChatParticipantWrapupcodes) | **GET** /api/v2/conversations/chats/{conversationId}/participants/{participantId}/wrapupcodes | Get list of wrapup codes for this conversation participant
[**getConversationsChats**](ConversationsApi.html#getConversationsChats) | **GET** /api/v2/conversations/chats | Get active chat conversations for the logged in user
[**getConversationsCobrowsesession**](ConversationsApi.html#getConversationsCobrowsesession) | **GET** /api/v2/conversations/cobrowsesessions/{conversationId} | Get cobrowse conversation
[**getConversationsCobrowsesessionParticipantWrapup**](ConversationsApi.html#getConversationsCobrowsesessionParticipantWrapup) | **GET** /api/v2/conversations/cobrowsesessions/{conversationId}/participants/{participantId}/wrapup | Get the wrap-up for this conversation participant. 
[**getConversationsCobrowsesessionParticipantWrapupcodes**](ConversationsApi.html#getConversationsCobrowsesessionParticipantWrapupcodes) | **GET** /api/v2/conversations/cobrowsesessions/{conversationId}/participants/{participantId}/wrapupcodes | Get list of wrapup codes for this conversation participant
[**getConversationsCobrowsesessions**](ConversationsApi.html#getConversationsCobrowsesessions) | **GET** /api/v2/conversations/cobrowsesessions | Get active cobrowse conversations for the logged in user
[**getConversationsEmail**](ConversationsApi.html#getConversationsEmail) | **GET** /api/v2/conversations/emails/{conversationId} | Get email conversation
[**getConversationsEmailMessage**](ConversationsApi.html#getConversationsEmailMessage) | **GET** /api/v2/conversations/emails/{conversationId}/messages/{messageId} | Get conversation message
[**getConversationsEmailMessages**](ConversationsApi.html#getConversationsEmailMessages) | **GET** /api/v2/conversations/emails/{conversationId}/messages | Get conversation messages
[**getConversationsEmailMessagesDraft**](ConversationsApi.html#getConversationsEmailMessagesDraft) | **GET** /api/v2/conversations/emails/{conversationId}/messages/draft | Get conversation draft reply
[**getConversationsEmailParticipantWrapup**](ConversationsApi.html#getConversationsEmailParticipantWrapup) | **GET** /api/v2/conversations/emails/{conversationId}/participants/{participantId}/wrapup | Get the wrap-up for this conversation participant. 
[**getConversationsEmailParticipantWrapupcodes**](ConversationsApi.html#getConversationsEmailParticipantWrapupcodes) | **GET** /api/v2/conversations/emails/{conversationId}/participants/{participantId}/wrapupcodes | Get list of wrapup codes for this conversation participant
[**getConversationsEmails**](ConversationsApi.html#getConversationsEmails) | **GET** /api/v2/conversations/emails | Get active email conversations for the logged in user
[**getConversationsMessage**](ConversationsApi.html#getConversationsMessage) | **GET** /api/v2/conversations/messages/{conversationId} | Get message conversation
[**getConversationsMessageCommunicationMessagesMediaMediaId**](ConversationsApi.html#getConversationsMessageCommunicationMessagesMediaMediaId) | **GET** /api/v2/conversations/messages/{conversationId}/communications/{communicationId}/messages/media/{mediaId} | Get media
[**getConversationsMessageDetails**](ConversationsApi.html#getConversationsMessageDetails) | **GET** /api/v2/conversations/messages/{messageId}/details | Get message
[**getConversationsMessageMessage**](ConversationsApi.html#getConversationsMessageMessage) | **GET** /api/v2/conversations/messages/{conversationId}/messages/{messageId} | Get conversation message
[**getConversationsMessageParticipantWrapup**](ConversationsApi.html#getConversationsMessageParticipantWrapup) | **GET** /api/v2/conversations/messages/{conversationId}/participants/{participantId}/wrapup | Get the wrap-up for this conversation participant. 
[**getConversationsMessageParticipantWrapupcodes**](ConversationsApi.html#getConversationsMessageParticipantWrapupcodes) | **GET** /api/v2/conversations/messages/{conversationId}/participants/{participantId}/wrapupcodes | Get list of wrapup codes for this conversation participant
[**getConversationsMessages**](ConversationsApi.html#getConversationsMessages) | **GET** /api/v2/conversations/messages | Get active message conversations for the logged in user
[**getConversationsMessagingFacebookApp**](ConversationsApi.html#getConversationsMessagingFacebookApp) | **GET** /api/v2/conversations/messaging/facebook/app | Get Genesys Facebook App Id
[**getConversationsMessagingIntegrations**](ConversationsApi.html#getConversationsMessagingIntegrations) | **GET** /api/v2/conversations/messaging/integrations | Get a list of Integrations
[**getConversationsMessagingIntegrationsFacebook**](ConversationsApi.html#getConversationsMessagingIntegrationsFacebook) | **GET** /api/v2/conversations/messaging/integrations/facebook | Get a list of Facebook Integrations
[**getConversationsMessagingIntegrationsFacebookIntegrationId**](ConversationsApi.html#getConversationsMessagingIntegrationsFacebookIntegrationId) | **GET** /api/v2/conversations/messaging/integrations/facebook/{integrationId} | Get a Facebook messaging integration
[**getConversationsMessagingIntegrationsLine**](ConversationsApi.html#getConversationsMessagingIntegrationsLine) | **GET** /api/v2/conversations/messaging/integrations/line | Get a list of LINE messenger Integrations
[**getConversationsMessagingIntegrationsLineIntegrationId**](ConversationsApi.html#getConversationsMessagingIntegrationsLineIntegrationId) | **GET** /api/v2/conversations/messaging/integrations/line/{integrationId} | Get a LINE messenger integration
[**getConversationsMessagingIntegrationsOpen**](ConversationsApi.html#getConversationsMessagingIntegrationsOpen) | **GET** /api/v2/conversations/messaging/integrations/open | Get a list of Open messaging integrations
[**getConversationsMessagingIntegrationsOpenIntegrationId**](ConversationsApi.html#getConversationsMessagingIntegrationsOpenIntegrationId) | **GET** /api/v2/conversations/messaging/integrations/open/{integrationId} | Get an Open messaging integration
[**getConversationsMessagingIntegrationsTwitter**](ConversationsApi.html#getConversationsMessagingIntegrationsTwitter) | **GET** /api/v2/conversations/messaging/integrations/twitter | Get a list of Twitter Integrations
[**getConversationsMessagingIntegrationsTwitterIntegrationId**](ConversationsApi.html#getConversationsMessagingIntegrationsTwitterIntegrationId) | **GET** /api/v2/conversations/messaging/integrations/twitter/{integrationId} | Get a Twitter messaging integration
[**getConversationsMessagingIntegrationsWhatsapp**](ConversationsApi.html#getConversationsMessagingIntegrationsWhatsapp) | **GET** /api/v2/conversations/messaging/integrations/whatsapp | Get a list of WhatsApp Integrations
[**getConversationsMessagingIntegrationsWhatsappIntegrationId**](ConversationsApi.html#getConversationsMessagingIntegrationsWhatsappIntegrationId) | **GET** /api/v2/conversations/messaging/integrations/whatsapp/{integrationId} | Get a WhatsApp messaging integration
[**getConversationsMessagingSticker**](ConversationsApi.html#getConversationsMessagingSticker) | **GET** /api/v2/conversations/messaging/stickers/{messengerType} | Get a list of Messaging Stickers
[**getConversationsMessagingThreadingtimeline**](ConversationsApi.html#getConversationsMessagingThreadingtimeline) | **GET** /api/v2/conversations/messaging/threadingtimeline | Get conversation threading window timeline for each messaging type
[**patchConversationParticipant**](ConversationsApi.html#patchConversationParticipant) | **PATCH** /api/v2/conversations/{conversationId}/participants/{participantId} | Update a participant.
[**patchConversationParticipantAttributes**](ConversationsApi.html#patchConversationParticipantAttributes) | **PATCH** /api/v2/conversations/{conversationId}/participants/{participantId}/attributes | Update the attributes on a conversation participant.
[**patchConversationsCall**](ConversationsApi.html#patchConversationsCall) | **PATCH** /api/v2/conversations/calls/{conversationId} | Update a conversation by setting it&#39;s recording state, merging in other conversations to create a conference, or disconnecting all of the participants
[**patchConversationsCallParticipant**](ConversationsApi.html#patchConversationsCallParticipant) | **PATCH** /api/v2/conversations/calls/{conversationId}/participants/{participantId} | Update conversation participant
[**patchConversationsCallParticipantAttributes**](ConversationsApi.html#patchConversationsCallParticipantAttributes) | **PATCH** /api/v2/conversations/calls/{conversationId}/participants/{participantId}/attributes | Update the attributes on a conversation participant.
[**patchConversationsCallParticipantCommunication**](ConversationsApi.html#patchConversationsCallParticipantCommunication) | **PATCH** /api/v2/conversations/calls/{conversationId}/participants/{participantId}/communications/{communicationId} | Update conversation participant&#39;s communication by disconnecting it.
[**patchConversationsCallParticipantConsult**](ConversationsApi.html#patchConversationsCallParticipantConsult) | **PATCH** /api/v2/conversations/calls/{conversationId}/participants/{participantId}/consult | Change who can speak
[**patchConversationsCallback**](ConversationsApi.html#patchConversationsCallback) | **PATCH** /api/v2/conversations/callbacks/{conversationId} | Update a conversation by disconnecting all of the participants
[**patchConversationsCallbackParticipant**](ConversationsApi.html#patchConversationsCallbackParticipant) | **PATCH** /api/v2/conversations/callbacks/{conversationId}/participants/{participantId} | Update conversation participant
[**patchConversationsCallbackParticipantAttributes**](ConversationsApi.html#patchConversationsCallbackParticipantAttributes) | **PATCH** /api/v2/conversations/callbacks/{conversationId}/participants/{participantId}/attributes | Update the attributes on a conversation participant.
[**patchConversationsCallbackParticipantCommunication**](ConversationsApi.html#patchConversationsCallbackParticipantCommunication) | **PATCH** /api/v2/conversations/callbacks/{conversationId}/participants/{participantId}/communications/{communicationId} | Update conversation participant&#39;s communication by disconnecting it.
[**patchConversationsChat**](ConversationsApi.html#patchConversationsChat) | **PATCH** /api/v2/conversations/chats/{conversationId} | Update a conversation by disconnecting all of the participants
[**patchConversationsChatParticipant**](ConversationsApi.html#patchConversationsChatParticipant) | **PATCH** /api/v2/conversations/chats/{conversationId}/participants/{participantId} | Update conversation participant
[**patchConversationsChatParticipantAttributes**](ConversationsApi.html#patchConversationsChatParticipantAttributes) | **PATCH** /api/v2/conversations/chats/{conversationId}/participants/{participantId}/attributes | Update the attributes on a conversation participant.
[**patchConversationsChatParticipantCommunication**](ConversationsApi.html#patchConversationsChatParticipantCommunication) | **PATCH** /api/v2/conversations/chats/{conversationId}/participants/{participantId}/communications/{communicationId} | Update conversation participant&#39;s communication by disconnecting it.
[**patchConversationsCobrowsesession**](ConversationsApi.html#patchConversationsCobrowsesession) | **PATCH** /api/v2/conversations/cobrowsesessions/{conversationId} | Update a conversation by disconnecting all of the participants
[**patchConversationsCobrowsesessionParticipant**](ConversationsApi.html#patchConversationsCobrowsesessionParticipant) | **PATCH** /api/v2/conversations/cobrowsesessions/{conversationId}/participants/{participantId} | Update conversation participant
[**patchConversationsCobrowsesessionParticipantAttributes**](ConversationsApi.html#patchConversationsCobrowsesessionParticipantAttributes) | **PATCH** /api/v2/conversations/cobrowsesessions/{conversationId}/participants/{participantId}/attributes | Update the attributes on a conversation participant.
[**patchConversationsCobrowsesessionParticipantCommunication**](ConversationsApi.html#patchConversationsCobrowsesessionParticipantCommunication) | **PATCH** /api/v2/conversations/cobrowsesessions/{conversationId}/participants/{participantId}/communications/{communicationId} | Update conversation participant&#39;s communication by disconnecting it.
[**patchConversationsEmail**](ConversationsApi.html#patchConversationsEmail) | **PATCH** /api/v2/conversations/emails/{conversationId} | Update a conversation by disconnecting all of the participants
[**patchConversationsEmailParticipant**](ConversationsApi.html#patchConversationsEmailParticipant) | **PATCH** /api/v2/conversations/emails/{conversationId}/participants/{participantId} | Update conversation participant
[**patchConversationsEmailParticipantAttributes**](ConversationsApi.html#patchConversationsEmailParticipantAttributes) | **PATCH** /api/v2/conversations/emails/{conversationId}/participants/{participantId}/attributes | Update the attributes on a conversation participant.
[**patchConversationsEmailParticipantCommunication**](ConversationsApi.html#patchConversationsEmailParticipantCommunication) | **PATCH** /api/v2/conversations/emails/{conversationId}/participants/{participantId}/communications/{communicationId} | Update conversation participant&#39;s communication by disconnecting it.
[**patchConversationsMessage**](ConversationsApi.html#patchConversationsMessage) | **PATCH** /api/v2/conversations/messages/{conversationId} | Update a conversation by disconnecting all of the participants
[**patchConversationsMessageParticipant**](ConversationsApi.html#patchConversationsMessageParticipant) | **PATCH** /api/v2/conversations/messages/{conversationId}/participants/{participantId} | Update conversation participant
[**patchConversationsMessageParticipantAttributes**](ConversationsApi.html#patchConversationsMessageParticipantAttributes) | **PATCH** /api/v2/conversations/messages/{conversationId}/participants/{participantId}/attributes | Update the attributes on a conversation participant.
[**patchConversationsMessageParticipantCommunication**](ConversationsApi.html#patchConversationsMessageParticipantCommunication) | **PATCH** /api/v2/conversations/messages/{conversationId}/participants/{participantId}/communications/{communicationId} | Update conversation participant&#39;s communication by disconnecting it.
[**patchConversationsMessagingIntegrationsFacebookIntegrationId**](ConversationsApi.html#patchConversationsMessagingIntegrationsFacebookIntegrationId) | **PATCH** /api/v2/conversations/messaging/integrations/facebook/{integrationId} | Update Facebook messaging integration
[**patchConversationsMessagingIntegrationsOpenIntegrationId**](ConversationsApi.html#patchConversationsMessagingIntegrationsOpenIntegrationId) | **PATCH** /api/v2/conversations/messaging/integrations/open/{integrationId} | Update an Open messaging integration
[**patchConversationsMessagingIntegrationsTwitterIntegrationId**](ConversationsApi.html#patchConversationsMessagingIntegrationsTwitterIntegrationId) | **PATCH** /api/v2/conversations/messaging/integrations/twitter/{integrationId} | Update Twitter messaging integration
[**patchConversationsMessagingIntegrationsWhatsappIntegrationId**](ConversationsApi.html#patchConversationsMessagingIntegrationsWhatsappIntegrationId) | **PATCH** /api/v2/conversations/messaging/integrations/whatsapp/{integrationId} | Update or activate a WhatsApp messaging integration.
[**postAnalyticsConversationDetailsProperties**](ConversationsApi.html#postAnalyticsConversationDetailsProperties) | **POST** /api/v2/analytics/conversations/{conversationId}/details/properties | Index conversation properties
[**postAnalyticsConversationsAggregatesQuery**](ConversationsApi.html#postAnalyticsConversationsAggregatesQuery) | **POST** /api/v2/analytics/conversations/aggregates/query | Query for conversation aggregates
[**postAnalyticsConversationsDetailsJobs**](ConversationsApi.html#postAnalyticsConversationsDetailsJobs) | **POST** /api/v2/analytics/conversations/details/jobs | Query for conversation details asynchronously
[**postAnalyticsConversationsDetailsQuery**](ConversationsApi.html#postAnalyticsConversationsDetailsQuery) | **POST** /api/v2/analytics/conversations/details/query | Query for conversation details
[**postConversationAssign**](ConversationsApi.html#postConversationAssign) | **POST** /api/v2/conversations/{conversationId}/assign | Attempts to manually assign a specified conversation to a specified user.  Ignores bullseye ring, PAR score, skills, and languages.
[**postConversationDisconnect**](ConversationsApi.html#postConversationDisconnect) | **POST** /api/v2/conversations/{conversationId}/disconnect | Performs a full conversation teardown. Issues disconnect requests for any connected media. Applies a system wrap-up code to any participants that are pending wrap-up. This is not intended to be the normal way of ending interactions but is available in the event of problems with the application to allow a resynchronization of state across all components. It is recommended that users submit a support case if they are relying on this endpoint systematically as there is likely something that needs investigation.
[**postConversationParticipantCallbacks**](ConversationsApi.html#postConversationParticipantCallbacks) | **POST** /api/v2/conversations/{conversationId}/participants/{participantId}/callbacks | Create a new callback for the specified participant on the conversation.
[**postConversationParticipantDigits**](ConversationsApi.html#postConversationParticipantDigits) | **POST** /api/v2/conversations/{conversationId}/participants/{participantId}/digits | Sends DTMF to the participant
[**postConversationParticipantReplace**](ConversationsApi.html#postConversationParticipantReplace) | **POST** /api/v2/conversations/{conversationId}/participants/{participantId}/replace | Replace this participant with the specified user and/or address
[**postConversationParticipantSecureivrsessions**](ConversationsApi.html#postConversationParticipantSecureivrsessions) | **POST** /api/v2/conversations/{conversationId}/participants/{participantId}/secureivrsessions | Create secure IVR session. Only a participant in the conversation can invoke a secure IVR.
[**postConversationsCall**](ConversationsApi.html#postConversationsCall) | **POST** /api/v2/conversations/calls/{conversationId} | Place a new call as part of a callback conversation.
[**postConversationsCallParticipantCoach**](ConversationsApi.html#postConversationsCallParticipantCoach) | **POST** /api/v2/conversations/calls/{conversationId}/participants/{participantId}/coach | Listen in on the conversation from the point of view of a given participant while speaking to just the given participant.
[**postConversationsCallParticipantConsult**](ConversationsApi.html#postConversationsCallParticipantConsult) | **POST** /api/v2/conversations/calls/{conversationId}/participants/{participantId}/consult | Initiate and update consult transfer
[**postConversationsCallParticipantMonitor**](ConversationsApi.html#postConversationsCallParticipantMonitor) | **POST** /api/v2/conversations/calls/{conversationId}/participants/{participantId}/monitor | Listen in on the conversation from the point of view of a given participant.
[**postConversationsCallParticipantReplace**](ConversationsApi.html#postConversationsCallParticipantReplace) | **POST** /api/v2/conversations/calls/{conversationId}/participants/{participantId}/replace | Replace this participant with the specified user and/or address
[**postConversationsCallParticipants**](ConversationsApi.html#postConversationsCallParticipants) | **POST** /api/v2/conversations/calls/{conversationId}/participants | Add participants to a conversation
[**postConversationsCallbackParticipantReplace**](ConversationsApi.html#postConversationsCallbackParticipantReplace) | **POST** /api/v2/conversations/callbacks/{conversationId}/participants/{participantId}/replace | Replace this participant with the specified user and/or address
[**postConversationsCallbacks**](ConversationsApi.html#postConversationsCallbacks) | **POST** /api/v2/conversations/callbacks | Create a Callback
[**postConversationsCalls**](ConversationsApi.html#postConversationsCalls) | **POST** /api/v2/conversations/calls | Create a call conversation
[**postConversationsChatCommunicationMessages**](ConversationsApi.html#postConversationsChatCommunicationMessages) | **POST** /api/v2/conversations/chats/{conversationId}/communications/{communicationId}/messages | Send a message on behalf of a communication in a chat conversation.
[**postConversationsChatCommunicationTyping**](ConversationsApi.html#postConversationsChatCommunicationTyping) | **POST** /api/v2/conversations/chats/{conversationId}/communications/{communicationId}/typing | Send a typing-indicator on behalf of a communication in a chat conversation.
[**postConversationsChatParticipantReplace**](ConversationsApi.html#postConversationsChatParticipantReplace) | **POST** /api/v2/conversations/chats/{conversationId}/participants/{participantId}/replace | Replace this participant with the specified user and/or address
[**postConversationsChats**](ConversationsApi.html#postConversationsChats) | **POST** /api/v2/conversations/chats | Create a web chat conversation
[**postConversationsCobrowsesessionParticipantReplace**](ConversationsApi.html#postConversationsCobrowsesessionParticipantReplace) | **POST** /api/v2/conversations/cobrowsesessions/{conversationId}/participants/{participantId}/replace | Replace this participant with the specified user and/or address
[**postConversationsEmailInboundmessages**](ConversationsApi.html#postConversationsEmailInboundmessages) | **POST** /api/v2/conversations/emails/{conversationId}/inboundmessages | Send an email to an external conversation. An external conversation is one where the provider is not PureCloud based. This endpoint allows the sender of the external email to reply or send a new message to the existing conversation. The new message will be treated as part of the existing conversation and chained to it.
[**postConversationsEmailMessages**](ConversationsApi.html#postConversationsEmailMessages) | **POST** /api/v2/conversations/emails/{conversationId}/messages | Send an email reply
[**postConversationsEmailMessagesDraftAttachmentsCopy**](ConversationsApi.html#postConversationsEmailMessagesDraftAttachmentsCopy) | **POST** /api/v2/conversations/emails/{conversationId}/messages/draft/attachments/copy | Copy attachments from an email message to the current draft.
[**postConversationsEmailParticipantReplace**](ConversationsApi.html#postConversationsEmailParticipantReplace) | **POST** /api/v2/conversations/emails/{conversationId}/participants/{participantId}/replace | Replace this participant with the specified user and/or address
[**postConversationsEmails**](ConversationsApi.html#postConversationsEmails) | **POST** /api/v2/conversations/emails | Create an email conversation
[**postConversationsFaxes**](ConversationsApi.html#postConversationsFaxes) | **POST** /api/v2/conversations/faxes | Create Fax Conversation
[**postConversationsMessageCommunicationMessages**](ConversationsApi.html#postConversationsMessageCommunicationMessages) | **POST** /api/v2/conversations/messages/{conversationId}/communications/{communicationId}/messages | Send message
[**postConversationsMessageCommunicationMessagesMedia**](ConversationsApi.html#postConversationsMessageCommunicationMessagesMedia) | **POST** /api/v2/conversations/messages/{conversationId}/communications/{communicationId}/messages/media | Create media
[**postConversationsMessageMessagesBulk**](ConversationsApi.html#postConversationsMessageMessagesBulk) | **POST** /api/v2/conversations/messages/{conversationId}/messages/bulk | Get messages in batch
[**postConversationsMessageParticipantReplace**](ConversationsApi.html#postConversationsMessageParticipantReplace) | **POST** /api/v2/conversations/messages/{conversationId}/participants/{participantId}/replace | Replace this participant with the specified user and/or address
[**postConversationsMessages**](ConversationsApi.html#postConversationsMessages) | **POST** /api/v2/conversations/messages | Create an outbound messaging conversation.
[**postConversationsMessagesAgentless**](ConversationsApi.html#postConversationsMessagesAgentless) | **POST** /api/v2/conversations/messages/agentless | Send an agentless outbound message
[**postConversationsMessagesInboundOpen**](ConversationsApi.html#postConversationsMessagesInboundOpen) | **POST** /api/v2/conversations/messages/inbound/open | Send an inbound Open Message
[**postConversationsMessagingIntegrationsFacebook**](ConversationsApi.html#postConversationsMessagingIntegrationsFacebook) | **POST** /api/v2/conversations/messaging/integrations/facebook | Create a Facebook Integration
[**postConversationsMessagingIntegrationsLine**](ConversationsApi.html#postConversationsMessagingIntegrationsLine) | **POST** /api/v2/conversations/messaging/integrations/line | Create a LINE messenger Integration
[**postConversationsMessagingIntegrationsOpen**](ConversationsApi.html#postConversationsMessagingIntegrationsOpen) | **POST** /api/v2/conversations/messaging/integrations/open | Create an Open messaging integration
[**postConversationsMessagingIntegrationsTwitter**](ConversationsApi.html#postConversationsMessagingIntegrationsTwitter) | **POST** /api/v2/conversations/messaging/integrations/twitter | Create a Twitter Integration
[**postConversationsMessagingIntegrationsWhatsapp**](ConversationsApi.html#postConversationsMessagingIntegrationsWhatsapp) | **POST** /api/v2/conversations/messaging/integrations/whatsapp | Create a WhatsApp Integration
[**putConversationParticipantFlaggedreason**](ConversationsApi.html#putConversationParticipantFlaggedreason) | **PUT** /api/v2/conversations/{conversationId}/participants/{participantId}/flaggedreason | Set flagged reason on conversation participant to indicate bad conversation quality.
[**putConversationTags**](ConversationsApi.html#putConversationTags) | **PUT** /api/v2/conversations/{conversationId}/tags | Update the tags on a conversation.
[**putConversationsCallParticipantCommunicationUuidata**](ConversationsApi.html#putConversationsCallParticipantCommunicationUuidata) | **PUT** /api/v2/conversations/calls/{conversationId}/participants/{participantId}/communications/{communicationId}/uuidata | Set uuiData to be sent on future commands.
[**putConversationsEmailMessagesDraft**](ConversationsApi.html#putConversationsEmailMessagesDraft) | **PUT** /api/v2/conversations/emails/{conversationId}/messages/draft | Update conversation draft reply
[**putConversationsMessagingIntegrationsLineIntegrationId**](ConversationsApi.html#putConversationsMessagingIntegrationsLineIntegrationId) | **PUT** /api/v2/conversations/messaging/integrations/line/{integrationId} | Update a LINE messenger integration
[**putConversationsMessagingThreadingtimeline**](ConversationsApi.html#putConversationsMessagingThreadingtimeline) | **PUT** /api/v2/conversations/messaging/threadingtimeline | Update conversation threading window timeline for each messaging type
{: class="table table-striped"}

<a name="deleteAnalyticsConversationsDetailsJob"></a>

# void deleteAnalyticsConversationsDetailsJob(jobId)



DELETE /api/v2/analytics/conversations/details/jobs/{jobId}

Delete/cancel an async request



Requires ANY permissions: 

* analytics:conversationDetail:view
* analytics:agentConversationDetail:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let jobId = "jobId_example"; // String | jobId

apiInstance.deleteAnalyticsConversationsDetailsJob(jobId)
  .then(() => {
    console.log('deleteAnalyticsConversationsDetailsJob returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling deleteAnalyticsConversationsDetailsJob');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **jobId** | **String** | jobId |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="deleteConversationParticipantCode"></a>

# void deleteConversationParticipantCode(conversationId, participantId, addCommunicationCode)



DELETE /api/v2/conversations/{conversationId}/participants/{participantId}/codes/{addCommunicationCode}

Delete a code used to add a communication to this participant



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID
let participantId = "participantId_example"; // String | participant ID
let addCommunicationCode = "addCommunicationCode_example"; // String | addCommunicationCode

apiInstance.deleteConversationParticipantCode(conversationId, participantId, addCommunicationCode)
  .then(() => {
    console.log('deleteConversationParticipantCode returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling deleteConversationParticipantCode');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
 **participantId** | **String** | participant ID |  |
 **addCommunicationCode** | **String** | addCommunicationCode |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="deleteConversationParticipantFlaggedreason"></a>

# void deleteConversationParticipantFlaggedreason(conversationId, participantId)



DELETE /api/v2/conversations/{conversationId}/participants/{participantId}/flaggedreason

Remove flagged reason from conversation participant.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID
let participantId = "participantId_example"; // String | participant ID

apiInstance.deleteConversationParticipantFlaggedreason(conversationId, participantId)
  .then(() => {
    console.log('deleteConversationParticipantFlaggedreason returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling deleteConversationParticipantFlaggedreason');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
 **participantId** | **String** | participant ID |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="deleteConversationsCallParticipantConsult"></a>

# void deleteConversationsCallParticipantConsult(conversationId, participantId)



DELETE /api/v2/conversations/calls/{conversationId}/participants/{participantId}/consult

Cancel the transfer



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId

apiInstance.deleteConversationsCallParticipantConsult(conversationId, participantId)
  .then(() => {
    console.log('deleteConversationsCallParticipantConsult returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling deleteConversationsCallParticipantConsult');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="deleteConversationsEmailMessagesDraftAttachment"></a>

# void deleteConversationsEmailMessagesDraftAttachment(conversationId, attachmentId)



DELETE /api/v2/conversations/emails/{conversationId}/messages/draft/attachments/{attachmentId}

Delete attachment from draft



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let attachmentId = "attachmentId_example"; // String | attachmentId

apiInstance.deleteConversationsEmailMessagesDraftAttachment(conversationId, attachmentId)
  .then(() => {
    console.log('deleteConversationsEmailMessagesDraftAttachment returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling deleteConversationsEmailMessagesDraftAttachment');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **attachmentId** | **String** | attachmentId |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="deleteConversationsMessagingIntegrationsFacebookIntegrationId"></a>

# void deleteConversationsMessagingIntegrationsFacebookIntegrationId(integrationId)



DELETE /api/v2/conversations/messaging/integrations/facebook/{integrationId}

Delete a Facebook messaging integration



Requires ALL permissions: 

* messaging:integration:delete

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let integrationId = "integrationId_example"; // String | Integration ID

apiInstance.deleteConversationsMessagingIntegrationsFacebookIntegrationId(integrationId)
  .then(() => {
    console.log('deleteConversationsMessagingIntegrationsFacebookIntegrationId returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling deleteConversationsMessagingIntegrationsFacebookIntegrationId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **integrationId** | **String** | Integration ID |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="deleteConversationsMessagingIntegrationsLineIntegrationId"></a>

# void deleteConversationsMessagingIntegrationsLineIntegrationId(integrationId)



DELETE /api/v2/conversations/messaging/integrations/line/{integrationId}

Delete a LINE messenger integration



Requires ALL permissions: 

* messaging:integration:delete

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let integrationId = "integrationId_example"; // String | Integration ID

apiInstance.deleteConversationsMessagingIntegrationsLineIntegrationId(integrationId)
  .then(() => {
    console.log('deleteConversationsMessagingIntegrationsLineIntegrationId returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling deleteConversationsMessagingIntegrationsLineIntegrationId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **integrationId** | **String** | Integration ID |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="deleteConversationsMessagingIntegrationsOpenIntegrationId"></a>

# void deleteConversationsMessagingIntegrationsOpenIntegrationId(integrationId)



DELETE /api/v2/conversations/messaging/integrations/open/{integrationId}

Delete an Open messaging integration

See https://developer.genesys.cloud/api/digital/openmessaging/ for more information.

Requires ALL permissions: 

* messaging:integration:delete

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let integrationId = "integrationId_example"; // String | Integration ID

apiInstance.deleteConversationsMessagingIntegrationsOpenIntegrationId(integrationId)
  .then(() => {
    console.log('deleteConversationsMessagingIntegrationsOpenIntegrationId returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling deleteConversationsMessagingIntegrationsOpenIntegrationId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **integrationId** | **String** | Integration ID |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="deleteConversationsMessagingIntegrationsTwitterIntegrationId"></a>

# void deleteConversationsMessagingIntegrationsTwitterIntegrationId(integrationId)



DELETE /api/v2/conversations/messaging/integrations/twitter/{integrationId}

Delete a Twitter messaging integration



Requires ALL permissions: 

* messaging:integration:delete

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let integrationId = "integrationId_example"; // String | Integration ID

apiInstance.deleteConversationsMessagingIntegrationsTwitterIntegrationId(integrationId)
  .then(() => {
    console.log('deleteConversationsMessagingIntegrationsTwitterIntegrationId returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling deleteConversationsMessagingIntegrationsTwitterIntegrationId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **integrationId** | **String** | Integration ID |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="deleteConversationsMessagingIntegrationsWhatsappIntegrationId"></a>

# WhatsAppIntegration deleteConversationsMessagingIntegrationsWhatsappIntegrationId(integrationId)



DELETE /api/v2/conversations/messaging/integrations/whatsapp/{integrationId}

Delete a WhatsApp messaging integration



Requires ALL permissions: 

* messaging:integration:delete

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let integrationId = "integrationId_example"; // String | Integration ID

apiInstance.deleteConversationsMessagingIntegrationsWhatsappIntegrationId(integrationId)
  .then((data) => {
    console.log(`deleteConversationsMessagingIntegrationsWhatsappIntegrationId success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling deleteConversationsMessagingIntegrationsWhatsappIntegrationId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **integrationId** | **String** | Integration ID |  |
{: class="table table-striped"}

### Return type

**WhatsAppIntegration**

<a name="getAnalyticsConversationDetails"></a>

# AnalyticsConversationWithoutAttributes getAnalyticsConversationDetails(conversationId)



GET /api/v2/analytics/conversations/{conversationId}/details

Get a conversation by id



Requires ANY permissions: 

* analytics:conversationDetail:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId

apiInstance.getAnalyticsConversationDetails(conversationId)
  .then((data) => {
    console.log(`getAnalyticsConversationDetails success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getAnalyticsConversationDetails');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
{: class="table table-striped"}

### Return type

**AnalyticsConversationWithoutAttributes**

<a name="getAnalyticsConversationsDetails"></a>

# AnalyticsConversationWithoutAttributesMultiGetResponse getAnalyticsConversationsDetails(opts)



GET /api/v2/analytics/conversations/details

Gets multiple conversations by id



Requires ANY permissions: 

* analytics:conversationDetail:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let opts = { 
  'id': ["id_example"] // [String] | Comma-separated conversation ids
};

apiInstance.getAnalyticsConversationsDetails(opts)
  .then((data) => {
    console.log(`getAnalyticsConversationsDetails success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getAnalyticsConversationsDetails');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **id** | **[String]** | Comma-separated conversation ids | [optional]  |
{: class="table table-striped"}

### Return type

**AnalyticsConversationWithoutAttributesMultiGetResponse**

<a name="getAnalyticsConversationsDetailsJob"></a>

# AsyncQueryStatus getAnalyticsConversationsDetailsJob(jobId)



GET /api/v2/analytics/conversations/details/jobs/{jobId}

Get status for async query for conversation details



Requires ANY permissions: 

* analytics:conversationDetail:view
* analytics:agentConversationDetail:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let jobId = "jobId_example"; // String | jobId

apiInstance.getAnalyticsConversationsDetailsJob(jobId)
  .then((data) => {
    console.log(`getAnalyticsConversationsDetailsJob success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getAnalyticsConversationsDetailsJob');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **jobId** | **String** | jobId |  |
{: class="table table-striped"}

### Return type

**AsyncQueryStatus**

<a name="getAnalyticsConversationsDetailsJobResults"></a>

# AnalyticsConversationAsyncQueryResponse getAnalyticsConversationsDetailsJobResults(jobId, opts)



GET /api/v2/analytics/conversations/details/jobs/{jobId}/results

Fetch a page of results for an async query



Requires ANY permissions: 

* analytics:conversationDetail:view
* analytics:agentConversationDetail:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let jobId = "jobId_example"; // String | jobId
let opts = { 
  'cursor': "cursor_example", // String | Indicates where to resume query results (not required for first page)
  'pageSize': 56 // Number | The desired maximum number of results
};

apiInstance.getAnalyticsConversationsDetailsJobResults(jobId, opts)
  .then((data) => {
    console.log(`getAnalyticsConversationsDetailsJobResults success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getAnalyticsConversationsDetailsJobResults');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **jobId** | **String** | jobId |  |
 **cursor** | **String** | Indicates where to resume query results (not required for first page) | [optional]  |
 **pageSize** | **Number** | The desired maximum number of results | [optional]  |
{: class="table table-striped"}

### Return type

**AnalyticsConversationAsyncQueryResponse**

<a name="getAnalyticsConversationsDetailsJobsAvailability"></a>

# DataAvailabilityResponse getAnalyticsConversationsDetailsJobsAvailability()



GET /api/v2/analytics/conversations/details/jobs/availability

Lookup the datalake availability date and time



Requires ANY permissions: 

* analytics:conversationDetail:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

apiInstance.getAnalyticsConversationsDetailsJobsAvailability()
  .then((data) => {
    console.log(`getAnalyticsConversationsDetailsJobsAvailability success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getAnalyticsConversationsDetailsJobsAvailability');
    console.error(err);
  });
```

### Parameters

This endpoint does not need any parameter.


### Return type

**DataAvailabilityResponse**

<a name="getConversation"></a>

# Conversation getConversation(conversationId)



GET /api/v2/conversations/{conversationId}

Get conversation



Requires ANY permissions: 

* conversation:communication:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID

apiInstance.getConversation(conversationId)
  .then((data) => {
    console.log(`getConversation success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversation');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
{: class="table table-striped"}

### Return type

**Conversation**

<a name="getConversationParticipantSecureivrsession"></a>

# SecureSession getConversationParticipantSecureivrsession(conversationId, participantId, secureSessionId)



GET /api/v2/conversations/{conversationId}/participants/{participantId}/secureivrsessions/{secureSessionId}

Fetch info on a secure session



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID
let participantId = "participantId_example"; // String | participant ID
let secureSessionId = "secureSessionId_example"; // String | secure IVR session ID

apiInstance.getConversationParticipantSecureivrsession(conversationId, participantId, secureSessionId)
  .then((data) => {
    console.log(`getConversationParticipantSecureivrsession success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationParticipantSecureivrsession');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
 **participantId** | **String** | participant ID |  |
 **secureSessionId** | **String** | secure IVR session ID |  |
{: class="table table-striped"}

### Return type

**SecureSession**

<a name="getConversationParticipantSecureivrsessions"></a>

# SecureSessionEntityListing getConversationParticipantSecureivrsessions(conversationId, participantId)



GET /api/v2/conversations/{conversationId}/participants/{participantId}/secureivrsessions

Get a list of secure sessions for this participant.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID
let participantId = "participantId_example"; // String | participant ID

apiInstance.getConversationParticipantSecureivrsessions(conversationId, participantId)
  .then((data) => {
    console.log(`getConversationParticipantSecureivrsessions success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationParticipantSecureivrsessions');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
 **participantId** | **String** | participant ID |  |
{: class="table table-striped"}

### Return type

**SecureSessionEntityListing**

<a name="getConversationParticipantWrapup"></a>

# AssignedWrapupCode getConversationParticipantWrapup(conversationId, participantId, opts)



GET /api/v2/conversations/{conversationId}/participants/{participantId}/wrapup

Get the wrap-up for this conversation participant. 



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID
let participantId = "participantId_example"; // String | participant ID
let opts = { 
  'provisional': false // Boolean | Indicates if the wrap-up code is provisional.
};

apiInstance.getConversationParticipantWrapup(conversationId, participantId, opts)
  .then((data) => {
    console.log(`getConversationParticipantWrapup success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationParticipantWrapup');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
 **participantId** | **String** | participant ID |  |
 **provisional** | **Boolean** | Indicates if the wrap-up code is provisional. | [optional] [default to false] |
{: class="table table-striped"}

### Return type

**AssignedWrapupCode**

<a name="getConversationParticipantWrapupcodes"></a>

# [WrapupCode] getConversationParticipantWrapupcodes(conversationId, participantId)



GET /api/v2/conversations/{conversationId}/participants/{participantId}/wrapupcodes

Get list of wrapup codes for this conversation participant



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID
let participantId = "participantId_example"; // String | participant ID

apiInstance.getConversationParticipantWrapupcodes(conversationId, participantId)
  .then((data) => {
    console.log(`getConversationParticipantWrapupcodes success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationParticipantWrapupcodes');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
 **participantId** | **String** | participant ID |  |
{: class="table table-striped"}

### Return type

**[WrapupCode]**

<a name="getConversations"></a>

# ConversationEntityListing getConversations(opts)



GET /api/v2/conversations

Get active conversations for the logged in user



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let opts = { 
  'communicationType': "communicationType_example" // String | Call or Chat communication filtering
};

apiInstance.getConversations(opts)
  .then((data) => {
    console.log(`getConversations success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversations');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **communicationType** | **String** | Call or Chat communication filtering | [optional]  |
{: class="table table-striped"}

### Return type

**ConversationEntityListing**

<a name="getConversationsCall"></a>

# CallConversation getConversationsCall(conversationId)



GET /api/v2/conversations/calls/{conversationId}

Get call conversation



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId

apiInstance.getConversationsCall(conversationId)
  .then((data) => {
    console.log(`getConversationsCall success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsCall');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
{: class="table table-striped"}

### Return type

**CallConversation**

<a name="getConversationsCallParticipantWrapup"></a>

# AssignedWrapupCode getConversationsCallParticipantWrapup(conversationId, participantId, opts)



GET /api/v2/conversations/calls/{conversationId}/participants/{participantId}/wrapup

Get the wrap-up for this conversation participant. 



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let opts = { 
  'provisional': false // Boolean | Indicates if the wrap-up code is provisional.
};

apiInstance.getConversationsCallParticipantWrapup(conversationId, participantId, opts)
  .then((data) => {
    console.log(`getConversationsCallParticipantWrapup success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsCallParticipantWrapup');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **provisional** | **Boolean** | Indicates if the wrap-up code is provisional. | [optional] [default to false] |
{: class="table table-striped"}

### Return type

**AssignedWrapupCode**

<a name="getConversationsCallParticipantWrapupcodes"></a>

# [WrapupCode] getConversationsCallParticipantWrapupcodes(conversationId, participantId)



GET /api/v2/conversations/calls/{conversationId}/participants/{participantId}/wrapupcodes

Get list of wrapup codes for this conversation participant



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId

apiInstance.getConversationsCallParticipantWrapupcodes(conversationId, participantId)
  .then((data) => {
    console.log(`getConversationsCallParticipantWrapupcodes success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsCallParticipantWrapupcodes');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
{: class="table table-striped"}

### Return type

**[WrapupCode]**

<a name="getConversationsCallback"></a>

# CallbackConversation getConversationsCallback(conversationId)



GET /api/v2/conversations/callbacks/{conversationId}

Get callback conversation



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId

apiInstance.getConversationsCallback(conversationId)
  .then((data) => {
    console.log(`getConversationsCallback success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsCallback');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
{: class="table table-striped"}

### Return type

**CallbackConversation**

<a name="getConversationsCallbackParticipantWrapup"></a>

# AssignedWrapupCode getConversationsCallbackParticipantWrapup(conversationId, participantId, opts)



GET /api/v2/conversations/callbacks/{conversationId}/participants/{participantId}/wrapup

Get the wrap-up for this conversation participant. 



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let opts = { 
  'provisional': false // Boolean | Indicates if the wrap-up code is provisional.
};

apiInstance.getConversationsCallbackParticipantWrapup(conversationId, participantId, opts)
  .then((data) => {
    console.log(`getConversationsCallbackParticipantWrapup success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsCallbackParticipantWrapup');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **provisional** | **Boolean** | Indicates if the wrap-up code is provisional. | [optional] [default to false] |
{: class="table table-striped"}

### Return type

**AssignedWrapupCode**

<a name="getConversationsCallbackParticipantWrapupcodes"></a>

# [WrapupCode] getConversationsCallbackParticipantWrapupcodes(conversationId, participantId)



GET /api/v2/conversations/callbacks/{conversationId}/participants/{participantId}/wrapupcodes

Get list of wrapup codes for this conversation participant



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId

apiInstance.getConversationsCallbackParticipantWrapupcodes(conversationId, participantId)
  .then((data) => {
    console.log(`getConversationsCallbackParticipantWrapupcodes success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsCallbackParticipantWrapupcodes');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
{: class="table table-striped"}

### Return type

**[WrapupCode]**

<a name="getConversationsCallbacks"></a>

# CallbackConversationEntityListing getConversationsCallbacks()



GET /api/v2/conversations/callbacks

Get active callback conversations for the logged in user



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

apiInstance.getConversationsCallbacks()
  .then((data) => {
    console.log(`getConversationsCallbacks success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsCallbacks');
    console.error(err);
  });
```

### Parameters

This endpoint does not need any parameter.


### Return type

**CallbackConversationEntityListing**

<a name="getConversationsCalls"></a>

# CallConversationEntityListing getConversationsCalls()



GET /api/v2/conversations/calls

Get active call conversations for the logged in user



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

apiInstance.getConversationsCalls()
  .then((data) => {
    console.log(`getConversationsCalls success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsCalls');
    console.error(err);
  });
```

### Parameters

This endpoint does not need any parameter.


### Return type

**CallConversationEntityListing**

<a name="getConversationsCallsHistory"></a>

# CallHistoryConversationEntityListing getConversationsCallsHistory(opts)



GET /api/v2/conversations/calls/history

Get call history



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let opts = { 
  'pageSize': 25, // Number | Page size, maximum 50
  'pageNumber': 1, // Number | Page number
  'interval': "interval_example", // String | Interval string; format is ISO-8601. Separate start and end times with forward slash '/'
  'expand': ["expand_example"] // [String] | Which fields, if any, to expand.
};

apiInstance.getConversationsCallsHistory(opts)
  .then((data) => {
    console.log(`getConversationsCallsHistory success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsCallsHistory');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **pageSize** | **Number** | Page size, maximum 50 | [optional] [default to 25] |
 **pageNumber** | **Number** | Page number | [optional] [default to 1] |
 **interval** | **String** | Interval string; format is ISO-8601. Separate start and end times with forward slash &#39;/&#39; | [optional]  |
 **expand** | **[String]** | Which fields, if any, to expand. | [optional] <br />**Values**: externalorganization, externalcontact, user, queue, group |
{: class="table table-striped"}

### Return type

**CallHistoryConversationEntityListing**

<a name="getConversationsCallsMaximumconferenceparties"></a>

# MaxParticipants getConversationsCallsMaximumconferenceparties()



GET /api/v2/conversations/calls/maximumconferenceparties

Get the maximum number of participants that this user can have on a conference



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

apiInstance.getConversationsCallsMaximumconferenceparties()
  .then((data) => {
    console.log(`getConversationsCallsMaximumconferenceparties success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsCallsMaximumconferenceparties');
    console.error(err);
  });
```

### Parameters

This endpoint does not need any parameter.


### Return type

**MaxParticipants**

<a name="getConversationsChat"></a>

# ChatConversation getConversationsChat(conversationId)



GET /api/v2/conversations/chats/{conversationId}

Get chat conversation



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId

apiInstance.getConversationsChat(conversationId)
  .then((data) => {
    console.log(`getConversationsChat success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsChat');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
{: class="table table-striped"}

### Return type

**ChatConversation**

<a name="getConversationsChatMessage"></a>

# WebChatMessage getConversationsChatMessage(conversationId, messageId)



GET /api/v2/conversations/chats/{conversationId}/messages/{messageId}

Get a web chat conversation message

The current user must be involved with the conversation to get its messages.

Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let messageId = "messageId_example"; // String | messageId

apiInstance.getConversationsChatMessage(conversationId, messageId)
  .then((data) => {
    console.log(`getConversationsChatMessage success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsChatMessage');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **messageId** | **String** | messageId |  |
{: class="table table-striped"}

### Return type

**WebChatMessage**

<a name="getConversationsChatMessages"></a>

# WebChatMessageEntityList getConversationsChatMessages(conversationId, opts)



GET /api/v2/conversations/chats/{conversationId}/messages

Get the messages of a chat conversation.

The current user must be involved with the conversation to get its messages.

Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let opts = { 
  'after': "after_example", // String | If specified, get the messages chronologically after the id of this message
  'before': "before_example", // String | If specified, get the messages chronologically before the id of this message
  'sortOrder': "ascending", // String | Sort order
  'maxResults': 100 // Number | Limit the returned number of messages, up to a maximum of 100
};

apiInstance.getConversationsChatMessages(conversationId, opts)
  .then((data) => {
    console.log(`getConversationsChatMessages success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsChatMessages');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **after** | **String** | If specified, get the messages chronologically after the id of this message | [optional]  |
 **before** | **String** | If specified, get the messages chronologically before the id of this message | [optional]  |
 **sortOrder** | **String** | Sort order | [optional] [default to ascending]<br />**Values**: ascending, descending |
 **maxResults** | **Number** | Limit the returned number of messages, up to a maximum of 100 | [optional] [default to 100] |
{: class="table table-striped"}

### Return type

**WebChatMessageEntityList**

<a name="getConversationsChatParticipantWrapup"></a>

# AssignedWrapupCode getConversationsChatParticipantWrapup(conversationId, participantId, opts)



GET /api/v2/conversations/chats/{conversationId}/participants/{participantId}/wrapup

Get the wrap-up for this conversation participant. 



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let opts = { 
  'provisional': false // Boolean | Indicates if the wrap-up code is provisional.
};

apiInstance.getConversationsChatParticipantWrapup(conversationId, participantId, opts)
  .then((data) => {
    console.log(`getConversationsChatParticipantWrapup success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsChatParticipantWrapup');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **provisional** | **Boolean** | Indicates if the wrap-up code is provisional. | [optional] [default to false] |
{: class="table table-striped"}

### Return type

**AssignedWrapupCode**

<a name="getConversationsChatParticipantWrapupcodes"></a>

# [WrapupCode] getConversationsChatParticipantWrapupcodes(conversationId, participantId)



GET /api/v2/conversations/chats/{conversationId}/participants/{participantId}/wrapupcodes

Get list of wrapup codes for this conversation participant



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId

apiInstance.getConversationsChatParticipantWrapupcodes(conversationId, participantId)
  .then((data) => {
    console.log(`getConversationsChatParticipantWrapupcodes success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsChatParticipantWrapupcodes');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
{: class="table table-striped"}

### Return type

**[WrapupCode]**

<a name="getConversationsChats"></a>

# ChatConversationEntityListing getConversationsChats()



GET /api/v2/conversations/chats

Get active chat conversations for the logged in user



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

apiInstance.getConversationsChats()
  .then((data) => {
    console.log(`getConversationsChats success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsChats');
    console.error(err);
  });
```

### Parameters

This endpoint does not need any parameter.


### Return type

**ChatConversationEntityListing**

<a name="getConversationsCobrowsesession"></a>

# CobrowseConversation getConversationsCobrowsesession(conversationId)



GET /api/v2/conversations/cobrowsesessions/{conversationId}

Get cobrowse conversation



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId

apiInstance.getConversationsCobrowsesession(conversationId)
  .then((data) => {
    console.log(`getConversationsCobrowsesession success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsCobrowsesession');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
{: class="table table-striped"}

### Return type

**CobrowseConversation**

<a name="getConversationsCobrowsesessionParticipantWrapup"></a>

# AssignedWrapupCode getConversationsCobrowsesessionParticipantWrapup(conversationId, participantId, opts)



GET /api/v2/conversations/cobrowsesessions/{conversationId}/participants/{participantId}/wrapup

Get the wrap-up for this conversation participant. 



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let opts = { 
  'provisional': false // Boolean | Indicates if the wrap-up code is provisional.
};

apiInstance.getConversationsCobrowsesessionParticipantWrapup(conversationId, participantId, opts)
  .then((data) => {
    console.log(`getConversationsCobrowsesessionParticipantWrapup success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsCobrowsesessionParticipantWrapup');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **provisional** | **Boolean** | Indicates if the wrap-up code is provisional. | [optional] [default to false] |
{: class="table table-striped"}

### Return type

**AssignedWrapupCode**

<a name="getConversationsCobrowsesessionParticipantWrapupcodes"></a>

# [WrapupCode] getConversationsCobrowsesessionParticipantWrapupcodes(conversationId, participantId)



GET /api/v2/conversations/cobrowsesessions/{conversationId}/participants/{participantId}/wrapupcodes

Get list of wrapup codes for this conversation participant



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId

apiInstance.getConversationsCobrowsesessionParticipantWrapupcodes(conversationId, participantId)
  .then((data) => {
    console.log(`getConversationsCobrowsesessionParticipantWrapupcodes success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsCobrowsesessionParticipantWrapupcodes');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
{: class="table table-striped"}

### Return type

**[WrapupCode]**

<a name="getConversationsCobrowsesessions"></a>

# CobrowseConversationEntityListing getConversationsCobrowsesessions()



GET /api/v2/conversations/cobrowsesessions

Get active cobrowse conversations for the logged in user



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

apiInstance.getConversationsCobrowsesessions()
  .then((data) => {
    console.log(`getConversationsCobrowsesessions success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsCobrowsesessions');
    console.error(err);
  });
```

### Parameters

This endpoint does not need any parameter.


### Return type

**CobrowseConversationEntityListing**

<a name="getConversationsEmail"></a>

# EmailConversation getConversationsEmail(conversationId)



GET /api/v2/conversations/emails/{conversationId}

Get email conversation



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId

apiInstance.getConversationsEmail(conversationId)
  .then((data) => {
    console.log(`getConversationsEmail success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsEmail');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
{: class="table table-striped"}

### Return type

**EmailConversation**

<a name="getConversationsEmailMessage"></a>

# EmailMessage getConversationsEmailMessage(conversationId, messageId)



GET /api/v2/conversations/emails/{conversationId}/messages/{messageId}

Get conversation message



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let messageId = "messageId_example"; // String | messageId

apiInstance.getConversationsEmailMessage(conversationId, messageId)
  .then((data) => {
    console.log(`getConversationsEmailMessage success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsEmailMessage');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **messageId** | **String** | messageId |  |
{: class="table table-striped"}

### Return type

**EmailMessage**

<a name="getConversationsEmailMessages"></a>

# EmailMessageListing getConversationsEmailMessages(conversationId)



GET /api/v2/conversations/emails/{conversationId}/messages

Get conversation messages



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId

apiInstance.getConversationsEmailMessages(conversationId)
  .then((data) => {
    console.log(`getConversationsEmailMessages success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsEmailMessages');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
{: class="table table-striped"}

### Return type

**EmailMessageListing**

<a name="getConversationsEmailMessagesDraft"></a>

# EmailMessage getConversationsEmailMessagesDraft(conversationId)



GET /api/v2/conversations/emails/{conversationId}/messages/draft

Get conversation draft reply



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId

apiInstance.getConversationsEmailMessagesDraft(conversationId)
  .then((data) => {
    console.log(`getConversationsEmailMessagesDraft success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsEmailMessagesDraft');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
{: class="table table-striped"}

### Return type

**EmailMessage**

<a name="getConversationsEmailParticipantWrapup"></a>

# AssignedWrapupCode getConversationsEmailParticipantWrapup(conversationId, participantId, opts)



GET /api/v2/conversations/emails/{conversationId}/participants/{participantId}/wrapup

Get the wrap-up for this conversation participant. 



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let opts = { 
  'provisional': false // Boolean | Indicates if the wrap-up code is provisional.
};

apiInstance.getConversationsEmailParticipantWrapup(conversationId, participantId, opts)
  .then((data) => {
    console.log(`getConversationsEmailParticipantWrapup success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsEmailParticipantWrapup');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **provisional** | **Boolean** | Indicates if the wrap-up code is provisional. | [optional] [default to false] |
{: class="table table-striped"}

### Return type

**AssignedWrapupCode**

<a name="getConversationsEmailParticipantWrapupcodes"></a>

# [WrapupCode] getConversationsEmailParticipantWrapupcodes(conversationId, participantId)



GET /api/v2/conversations/emails/{conversationId}/participants/{participantId}/wrapupcodes

Get list of wrapup codes for this conversation participant



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId

apiInstance.getConversationsEmailParticipantWrapupcodes(conversationId, participantId)
  .then((data) => {
    console.log(`getConversationsEmailParticipantWrapupcodes success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsEmailParticipantWrapupcodes');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
{: class="table table-striped"}

### Return type

**[WrapupCode]**

<a name="getConversationsEmails"></a>

# EmailConversationEntityListing getConversationsEmails()



GET /api/v2/conversations/emails

Get active email conversations for the logged in user



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

apiInstance.getConversationsEmails()
  .then((data) => {
    console.log(`getConversationsEmails success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsEmails');
    console.error(err);
  });
```

### Parameters

This endpoint does not need any parameter.


### Return type

**EmailConversationEntityListing**

<a name="getConversationsMessage"></a>

# MessageConversation getConversationsMessage(conversationId)



GET /api/v2/conversations/messages/{conversationId}

Get message conversation



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId

apiInstance.getConversationsMessage(conversationId)
  .then((data) => {
    console.log(`getConversationsMessage success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessage');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
{: class="table table-striped"}

### Return type

**MessageConversation**

<a name="getConversationsMessageCommunicationMessagesMediaMediaId"></a>

# MessageMediaData getConversationsMessageCommunicationMessagesMediaMediaId(conversationId, communicationId, mediaId)



GET /api/v2/conversations/messages/{conversationId}/communications/{communicationId}/messages/media/{mediaId}

Get media

See https://developer.genesys.cloud/api/rest/v2/conversations/messaging-media-upload for example usage.

Requires ANY permissions: 

* conversation:message:view
* conversation:webmessaging:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let communicationId = "communicationId_example"; // String | communicationId
let mediaId = "mediaId_example"; // String | mediaId

apiInstance.getConversationsMessageCommunicationMessagesMediaMediaId(conversationId, communicationId, mediaId)
  .then((data) => {
    console.log(`getConversationsMessageCommunicationMessagesMediaMediaId success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessageCommunicationMessagesMediaMediaId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **communicationId** | **String** | communicationId |  |
 **mediaId** | **String** | mediaId |  |
{: class="table table-striped"}

### Return type

**MessageMediaData**

<a name="getConversationsMessageDetails"></a>

# MessageData getConversationsMessageDetails(messageId)



GET /api/v2/conversations/messages/{messageId}/details

Get message



Requires ANY permissions: 

* conversation:message:view
* conversation:webmessaging:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let messageId = "messageId_example"; // String | messageId

apiInstance.getConversationsMessageDetails(messageId)
  .then((data) => {
    console.log(`getConversationsMessageDetails success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessageDetails');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **messageId** | **String** | messageId |  |
{: class="table table-striped"}

### Return type

**MessageData**

<a name="getConversationsMessageMessage"></a>

# MessageData getConversationsMessageMessage(conversationId, messageId)



GET /api/v2/conversations/messages/{conversationId}/messages/{messageId}

Get conversation message



Requires ANY permissions: 

* conversation:message:view
* conversation:webmessaging:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let messageId = "messageId_example"; // String | messageId

apiInstance.getConversationsMessageMessage(conversationId, messageId)
  .then((data) => {
    console.log(`getConversationsMessageMessage success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessageMessage');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **messageId** | **String** | messageId |  |
{: class="table table-striped"}

### Return type

**MessageData**

<a name="getConversationsMessageParticipantWrapup"></a>

# AssignedWrapupCode getConversationsMessageParticipantWrapup(conversationId, participantId, opts)



GET /api/v2/conversations/messages/{conversationId}/participants/{participantId}/wrapup

Get the wrap-up for this conversation participant. 



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let opts = { 
  'provisional': false // Boolean | Indicates if the wrap-up code is provisional.
};

apiInstance.getConversationsMessageParticipantWrapup(conversationId, participantId, opts)
  .then((data) => {
    console.log(`getConversationsMessageParticipantWrapup success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessageParticipantWrapup');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **provisional** | **Boolean** | Indicates if the wrap-up code is provisional. | [optional] [default to false] |
{: class="table table-striped"}

### Return type

**AssignedWrapupCode**

<a name="getConversationsMessageParticipantWrapupcodes"></a>

# [WrapupCode] getConversationsMessageParticipantWrapupcodes(conversationId, participantId)



GET /api/v2/conversations/messages/{conversationId}/participants/{participantId}/wrapupcodes

Get list of wrapup codes for this conversation participant



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String |  conversationId
let participantId = "participantId_example"; // String | participantId

apiInstance.getConversationsMessageParticipantWrapupcodes(conversationId, participantId)
  .then((data) => {
    console.log(`getConversationsMessageParticipantWrapupcodes success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessageParticipantWrapupcodes');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** |  conversationId |  |
 **participantId** | **String** | participantId |  |
{: class="table table-striped"}

### Return type

**[WrapupCode]**

<a name="getConversationsMessages"></a>

# MessageConversationEntityListing getConversationsMessages()



GET /api/v2/conversations/messages

Get active message conversations for the logged in user



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

apiInstance.getConversationsMessages()
  .then((data) => {
    console.log(`getConversationsMessages success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessages');
    console.error(err);
  });
```

### Parameters

This endpoint does not need any parameter.


### Return type

**MessageConversationEntityListing**

<a name="getConversationsMessagingFacebookApp"></a>

# FacebookAppCredentials getConversationsMessagingFacebookApp()



GET /api/v2/conversations/messaging/facebook/app

Get Genesys Facebook App Id



Requires ALL permissions: 

* messaging:integration:add

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

apiInstance.getConversationsMessagingFacebookApp()
  .then((data) => {
    console.log(`getConversationsMessagingFacebookApp success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessagingFacebookApp');
    console.error(err);
  });
```

### Parameters

This endpoint does not need any parameter.


### Return type

**FacebookAppCredentials**

<a name="getConversationsMessagingIntegrations"></a>

# MessagingIntegrationEntityListing getConversationsMessagingIntegrations(opts)



GET /api/v2/conversations/messaging/integrations

Get a list of Integrations



Requires ALL permissions: 

* messaging:integration:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let opts = { 
  'pageSize': 25, // Number | Page size
  'pageNumber': 1, // Number | Page number
  'expand': "expand_example", // String | Expand instructions for the return value.
  'supportedContentId': "supportedContentId_example" // String | Filter integrations returned based on the supported content ID
};

apiInstance.getConversationsMessagingIntegrations(opts)
  .then((data) => {
    console.log(`getConversationsMessagingIntegrations success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessagingIntegrations');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **pageSize** | **Number** | Page size | [optional] [default to 25] |
 **pageNumber** | **Number** | Page number | [optional] [default to 1] |
 **expand** | **String** | Expand instructions for the return value. | [optional] <br />**Values**: supportedContent |
 **supportedContentId** | **String** | Filter integrations returned based on the supported content ID | [optional]  |
{: class="table table-striped"}

### Return type

**MessagingIntegrationEntityListing**

<a name="getConversationsMessagingIntegrationsFacebook"></a>

# FacebookIntegrationEntityListing getConversationsMessagingIntegrationsFacebook(opts)



GET /api/v2/conversations/messaging/integrations/facebook

Get a list of Facebook Integrations



Requires ALL permissions: 

* messaging:integration:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let opts = { 
  'pageSize': 25, // Number | Page size
  'pageNumber': 1, // Number | Page number
  'expand': "expand_example", // String | Expand instructions for the return value.
  'supportedContentId': "supportedContentId_example" // String | Filter integrations returned based on the supported content ID
};

apiInstance.getConversationsMessagingIntegrationsFacebook(opts)
  .then((data) => {
    console.log(`getConversationsMessagingIntegrationsFacebook success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessagingIntegrationsFacebook');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **pageSize** | **Number** | Page size | [optional] [default to 25] |
 **pageNumber** | **Number** | Page number | [optional] [default to 1] |
 **expand** | **String** | Expand instructions for the return value. | [optional] <br />**Values**: supportedContent |
 **supportedContentId** | **String** | Filter integrations returned based on the supported content ID | [optional]  |
{: class="table table-striped"}

### Return type

**FacebookIntegrationEntityListing**

<a name="getConversationsMessagingIntegrationsFacebookIntegrationId"></a>

# FacebookIntegration getConversationsMessagingIntegrationsFacebookIntegrationId(integrationId, opts)



GET /api/v2/conversations/messaging/integrations/facebook/{integrationId}

Get a Facebook messaging integration



Requires ALL permissions: 

* messaging:integration:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let integrationId = "integrationId_example"; // String | Integration ID
let opts = { 
  'expand': "expand_example" // String | Expand instructions for the return value.
};

apiInstance.getConversationsMessagingIntegrationsFacebookIntegrationId(integrationId, opts)
  .then((data) => {
    console.log(`getConversationsMessagingIntegrationsFacebookIntegrationId success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessagingIntegrationsFacebookIntegrationId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **integrationId** | **String** | Integration ID |  |
 **expand** | **String** | Expand instructions for the return value. | [optional] <br />**Values**: supportedContent |
{: class="table table-striped"}

### Return type

**FacebookIntegration**

<a name="getConversationsMessagingIntegrationsLine"></a>

# LineIntegrationEntityListing getConversationsMessagingIntegrationsLine(opts)



GET /api/v2/conversations/messaging/integrations/line

Get a list of LINE messenger Integrations



Requires ALL permissions: 

* messaging:integration:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let opts = { 
  'pageSize': 25, // Number | Page size
  'pageNumber': 1, // Number | Page number
  'expand': "expand_example", // String | Expand instructions for the return value.
  'supportedContentId': "supportedContentId_example" // String | Filter integrations returned based on the supported content ID
};

apiInstance.getConversationsMessagingIntegrationsLine(opts)
  .then((data) => {
    console.log(`getConversationsMessagingIntegrationsLine success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessagingIntegrationsLine');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **pageSize** | **Number** | Page size | [optional] [default to 25] |
 **pageNumber** | **Number** | Page number | [optional] [default to 1] |
 **expand** | **String** | Expand instructions for the return value. | [optional] <br />**Values**: supportedContent |
 **supportedContentId** | **String** | Filter integrations returned based on the supported content ID | [optional]  |
{: class="table table-striped"}

### Return type

**LineIntegrationEntityListing**

<a name="getConversationsMessagingIntegrationsLineIntegrationId"></a>

# LineIntegration getConversationsMessagingIntegrationsLineIntegrationId(integrationId, opts)



GET /api/v2/conversations/messaging/integrations/line/{integrationId}

Get a LINE messenger integration



Requires ALL permissions: 

* messaging:integration:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let integrationId = "integrationId_example"; // String | Integration ID
let opts = { 
  'expand': "expand_example" // String | Expand instructions for the return value.
};

apiInstance.getConversationsMessagingIntegrationsLineIntegrationId(integrationId, opts)
  .then((data) => {
    console.log(`getConversationsMessagingIntegrationsLineIntegrationId success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessagingIntegrationsLineIntegrationId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **integrationId** | **String** | Integration ID |  |
 **expand** | **String** | Expand instructions for the return value. | [optional] <br />**Values**: supportedContent |
{: class="table table-striped"}

### Return type

**LineIntegration**

<a name="getConversationsMessagingIntegrationsOpen"></a>

# OpenIntegrationEntityListing getConversationsMessagingIntegrationsOpen(opts)



GET /api/v2/conversations/messaging/integrations/open

Get a list of Open messaging integrations

See https://developer.genesys.cloud/api/digital/openmessaging/ for more information.

Requires ALL permissions: 

* messaging:integration:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let opts = { 
  'pageSize': 25, // Number | Page size
  'pageNumber': 1, // Number | Page number
  'expand': "expand_example", // String | Expand instructions for the return value.
  'supportedContentId': "supportedContentId_example" // String | Filter integrations returned based on the supported content ID
};

apiInstance.getConversationsMessagingIntegrationsOpen(opts)
  .then((data) => {
    console.log(`getConversationsMessagingIntegrationsOpen success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessagingIntegrationsOpen');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **pageSize** | **Number** | Page size | [optional] [default to 25] |
 **pageNumber** | **Number** | Page number | [optional] [default to 1] |
 **expand** | **String** | Expand instructions for the return value. | [optional] <br />**Values**: supportedContent |
 **supportedContentId** | **String** | Filter integrations returned based on the supported content ID | [optional]  |
{: class="table table-striped"}

### Return type

**OpenIntegrationEntityListing**

<a name="getConversationsMessagingIntegrationsOpenIntegrationId"></a>

# OpenIntegration getConversationsMessagingIntegrationsOpenIntegrationId(integrationId, opts)



GET /api/v2/conversations/messaging/integrations/open/{integrationId}

Get an Open messaging integration

See https://developer.genesys.cloud/api/digital/openmessaging/ for more information.

Requires ALL permissions: 

* messaging:integration:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let integrationId = "integrationId_example"; // String | Integration ID
let opts = { 
  'expand': "expand_example" // String | Expand instructions for the return value.
};

apiInstance.getConversationsMessagingIntegrationsOpenIntegrationId(integrationId, opts)
  .then((data) => {
    console.log(`getConversationsMessagingIntegrationsOpenIntegrationId success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessagingIntegrationsOpenIntegrationId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **integrationId** | **String** | Integration ID |  |
 **expand** | **String** | Expand instructions for the return value. | [optional] <br />**Values**: supportedContent |
{: class="table table-striped"}

### Return type

**OpenIntegration**

<a name="getConversationsMessagingIntegrationsTwitter"></a>

# TwitterIntegrationEntityListing getConversationsMessagingIntegrationsTwitter(opts)



GET /api/v2/conversations/messaging/integrations/twitter

Get a list of Twitter Integrations



Requires ALL permissions: 

* messaging:integration:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let opts = { 
  'pageSize': 25, // Number | Page size
  'pageNumber': 1, // Number | Page number
  'expand': "expand_example", // String | Expand instructions for the return value.
  'supportedContentId': "supportedContentId_example" // String | Filter integrations returned based on the supported content ID
};

apiInstance.getConversationsMessagingIntegrationsTwitter(opts)
  .then((data) => {
    console.log(`getConversationsMessagingIntegrationsTwitter success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessagingIntegrationsTwitter');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **pageSize** | **Number** | Page size | [optional] [default to 25] |
 **pageNumber** | **Number** | Page number | [optional] [default to 1] |
 **expand** | **String** | Expand instructions for the return value. | [optional] <br />**Values**: supportedContent |
 **supportedContentId** | **String** | Filter integrations returned based on the supported content ID | [optional]  |
{: class="table table-striped"}

### Return type

**TwitterIntegrationEntityListing**

<a name="getConversationsMessagingIntegrationsTwitterIntegrationId"></a>

# TwitterIntegration getConversationsMessagingIntegrationsTwitterIntegrationId(integrationId, opts)



GET /api/v2/conversations/messaging/integrations/twitter/{integrationId}

Get a Twitter messaging integration



Requires ALL permissions: 

* messaging:integration:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let integrationId = "integrationId_example"; // String | Integration ID
let opts = { 
  'expand': "expand_example" // String | Expand instructions for the return value.
};

apiInstance.getConversationsMessagingIntegrationsTwitterIntegrationId(integrationId, opts)
  .then((data) => {
    console.log(`getConversationsMessagingIntegrationsTwitterIntegrationId success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessagingIntegrationsTwitterIntegrationId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **integrationId** | **String** | Integration ID |  |
 **expand** | **String** | Expand instructions for the return value. | [optional] <br />**Values**: supportedContent |
{: class="table table-striped"}

### Return type

**TwitterIntegration**

<a name="getConversationsMessagingIntegrationsWhatsapp"></a>

# WhatsAppIntegrationEntityListing getConversationsMessagingIntegrationsWhatsapp(opts)



GET /api/v2/conversations/messaging/integrations/whatsapp

Get a list of WhatsApp Integrations



Requires ALL permissions: 

* messaging:integration:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let opts = { 
  'pageSize': 25, // Number | Page size
  'pageNumber': 1, // Number | Page number
  'expand': "expand_example", // String | Expand instructions for the return value.
  'supportedContentId': "supportedContentId_example" // String | Filter integrations returned based on the supported content ID
};

apiInstance.getConversationsMessagingIntegrationsWhatsapp(opts)
  .then((data) => {
    console.log(`getConversationsMessagingIntegrationsWhatsapp success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessagingIntegrationsWhatsapp');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **pageSize** | **Number** | Page size | [optional] [default to 25] |
 **pageNumber** | **Number** | Page number | [optional] [default to 1] |
 **expand** | **String** | Expand instructions for the return value. | [optional] <br />**Values**: supportedContent |
 **supportedContentId** | **String** | Filter integrations returned based on the supported content ID | [optional]  |
{: class="table table-striped"}

### Return type

**WhatsAppIntegrationEntityListing**

<a name="getConversationsMessagingIntegrationsWhatsappIntegrationId"></a>

# WhatsAppIntegration getConversationsMessagingIntegrationsWhatsappIntegrationId(integrationId, opts)



GET /api/v2/conversations/messaging/integrations/whatsapp/{integrationId}

Get a WhatsApp messaging integration



Requires ALL permissions: 

* messaging:integration:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let integrationId = "integrationId_example"; // String | Integration ID
let opts = { 
  'expand': "expand_example" // String | Expand instructions for the return value.
};

apiInstance.getConversationsMessagingIntegrationsWhatsappIntegrationId(integrationId, opts)
  .then((data) => {
    console.log(`getConversationsMessagingIntegrationsWhatsappIntegrationId success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessagingIntegrationsWhatsappIntegrationId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **integrationId** | **String** | Integration ID |  |
 **expand** | **String** | Expand instructions for the return value. | [optional] <br />**Values**: supportedContent |
{: class="table table-striped"}

### Return type

**WhatsAppIntegration**

<a name="getConversationsMessagingSticker"></a>

# MessagingStickerEntityListing getConversationsMessagingSticker(messengerType, opts)



GET /api/v2/conversations/messaging/stickers/{messengerType}

Get a list of Messaging Stickers



Requires ALL permissions: 

* conversation:message:create

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let messengerType = "messengerType_example"; // String | Messenger Type
let opts = { 
  'pageSize': 25, // Number | Page size
  'pageNumber': 1 // Number | Page number
};

apiInstance.getConversationsMessagingSticker(messengerType, opts)
  .then((data) => {
    console.log(`getConversationsMessagingSticker success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessagingSticker');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **messengerType** | **String** | Messenger Type |  |
 **pageSize** | **Number** | Page size | [optional] [default to 25] |
 **pageNumber** | **Number** | Page number | [optional] [default to 1] |
{: class="table table-striped"}

### Return type

**MessagingStickerEntityListing**

<a name="getConversationsMessagingThreadingtimeline"></a>

# ConversationThreadingWindow getConversationsMessagingThreadingtimeline()



GET /api/v2/conversations/messaging/threadingtimeline

Get conversation threading window timeline for each messaging type

Conversation messaging threading timeline is a setting defined for each messenger type in your organization. This setting will dictate whether a new message is added to the most recent existing conversation, or creates a new Conversation. If the existing Conversation is still in a connected state the threading timeline setting will never play a role. After the conversation is disconnected, if an inbound message is received or an outbound message is sent after the setting for threading timeline expires, a new conversation is created.

Requires ALL permissions: 

* conversation:threadingTimeline:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

apiInstance.getConversationsMessagingThreadingtimeline()
  .then((data) => {
    console.log(`getConversationsMessagingThreadingtimeline success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling getConversationsMessagingThreadingtimeline');
    console.error(err);
  });
```

### Parameters

This endpoint does not need any parameter.


### Return type

**ConversationThreadingWindow**

<a name="patchConversationParticipant"></a>

# void patchConversationParticipant(conversationId, participantId, body)



PATCH /api/v2/conversations/{conversationId}/participants/{participantId}

Update a participant.

Update conversation participant.

Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID
let participantId = "participantId_example"; // String | participant ID
let body = {}; // Object | Update request

apiInstance.patchConversationParticipant(conversationId, participantId, body)
  .then(() => {
    console.log('patchConversationParticipant returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationParticipant');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
 **participantId** | **String** | participant ID |  |
 **body** | **Object** | Update request |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="patchConversationParticipantAttributes"></a>

# void patchConversationParticipantAttributes(conversationId, participantId, body)



PATCH /api/v2/conversations/{conversationId}/participants/{participantId}/attributes

Update the attributes on a conversation participant.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID
let participantId = "participantId_example"; // String | participant ID
let body = {}; // Object | Participant attributes

apiInstance.patchConversationParticipantAttributes(conversationId, participantId, body)
  .then(() => {
    console.log('patchConversationParticipantAttributes returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationParticipantAttributes');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
 **participantId** | **String** | participant ID |  |
 **body** | **Object** | Participant attributes |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="patchConversationsCall"></a>

# Conversation patchConversationsCall(conversationId, body)



PATCH /api/v2/conversations/calls/{conversationId}

Update a conversation by setting it&#39;s recording state, merging in other conversations to create a conference, or disconnecting all of the participants



Requires ANY permissions: 

* conversation:communication:disconnect

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let body = {}; // Object | Conversation

apiInstance.patchConversationsCall(conversationId, body)
  .then((data) => {
    console.log(`patchConversationsCall success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsCall');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **body** | **Object** | Conversation |  |
{: class="table table-striped"}

### Return type

**Conversation**

<a name="patchConversationsCallParticipant"></a>

# void patchConversationsCallParticipant(conversationId, participantId, body)



PATCH /api/v2/conversations/calls/{conversationId}/participants/{participantId}

Update conversation participant



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let body = {}; // Object | Participant request

apiInstance.patchConversationsCallParticipant(conversationId, participantId, body)
  .then(() => {
    console.log('patchConversationsCallParticipant returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsCallParticipant');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** | Participant request |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="patchConversationsCallParticipantAttributes"></a>

# void patchConversationsCallParticipantAttributes(conversationId, participantId, body)



PATCH /api/v2/conversations/calls/{conversationId}/participants/{participantId}/attributes

Update the attributes on a conversation participant.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let body = {}; // Object | Participant attributes

apiInstance.patchConversationsCallParticipantAttributes(conversationId, participantId, body)
  .then(() => {
    console.log('patchConversationsCallParticipantAttributes returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsCallParticipantAttributes');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** | Participant attributes |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="patchConversationsCallParticipantCommunication"></a>

# Empty patchConversationsCallParticipantCommunication(conversationId, participantId, communicationId, body)



PATCH /api/v2/conversations/calls/{conversationId}/participants/{participantId}/communications/{communicationId}

Update conversation participant&#39;s communication by disconnecting it.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let communicationId = "communicationId_example"; // String | communicationId
let body = {}; // Object | Participant

apiInstance.patchConversationsCallParticipantCommunication(conversationId, participantId, communicationId, body)
  .then((data) => {
    console.log(`patchConversationsCallParticipantCommunication success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsCallParticipantCommunication');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **communicationId** | **String** | communicationId |  |
 **body** | **Object** | Participant |  |
{: class="table table-striped"}

### Return type

**Empty**

<a name="patchConversationsCallParticipantConsult"></a>

# ConsultTransferResponse patchConversationsCallParticipantConsult(conversationId, participantId, body)



PATCH /api/v2/conversations/calls/{conversationId}/participants/{participantId}/consult

Change who can speak



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let body = {}; // Object | new speak to

apiInstance.patchConversationsCallParticipantConsult(conversationId, participantId, body)
  .then((data) => {
    console.log(`patchConversationsCallParticipantConsult success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsCallParticipantConsult');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** | new speak to |  |
{: class="table table-striped"}

### Return type

**ConsultTransferResponse**

<a name="patchConversationsCallback"></a>

# Conversation patchConversationsCallback(conversationId, body)



PATCH /api/v2/conversations/callbacks/{conversationId}

Update a conversation by disconnecting all of the participants



Requires ANY permissions: 

* conversation:communication:disconnect

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let body = {}; // Object | Conversation

apiInstance.patchConversationsCallback(conversationId, body)
  .then((data) => {
    console.log(`patchConversationsCallback success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsCallback');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **body** | **Object** | Conversation |  |
{: class="table table-striped"}

### Return type

**Conversation**

<a name="patchConversationsCallbackParticipant"></a>

# void patchConversationsCallbackParticipant(conversationId, participantId, body)



PATCH /api/v2/conversations/callbacks/{conversationId}/participants/{participantId}

Update conversation participant



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let body = {}; // Object | Participant

apiInstance.patchConversationsCallbackParticipant(conversationId, participantId, body)
  .then(() => {
    console.log('patchConversationsCallbackParticipant returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsCallbackParticipant');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** | Participant |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="patchConversationsCallbackParticipantAttributes"></a>

# void patchConversationsCallbackParticipantAttributes(conversationId, participantId, body)



PATCH /api/v2/conversations/callbacks/{conversationId}/participants/{participantId}/attributes

Update the attributes on a conversation participant.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let body = {}; // Object | Attributes

apiInstance.patchConversationsCallbackParticipantAttributes(conversationId, participantId, body)
  .then(() => {
    console.log('patchConversationsCallbackParticipantAttributes returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsCallbackParticipantAttributes');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** | Attributes |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="patchConversationsCallbackParticipantCommunication"></a>

# Empty patchConversationsCallbackParticipantCommunication(conversationId, participantId, communicationId, body)



PATCH /api/v2/conversations/callbacks/{conversationId}/participants/{participantId}/communications/{communicationId}

Update conversation participant&#39;s communication by disconnecting it.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let communicationId = "communicationId_example"; // String | communicationId
let body = {}; // Object | Participant

apiInstance.patchConversationsCallbackParticipantCommunication(conversationId, participantId, communicationId, body)
  .then((data) => {
    console.log(`patchConversationsCallbackParticipantCommunication success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsCallbackParticipantCommunication');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **communicationId** | **String** | communicationId |  |
 **body** | **Object** | Participant |  |
{: class="table table-striped"}

### Return type

**Empty**

<a name="patchConversationsChat"></a>

# Conversation patchConversationsChat(conversationId, body)



PATCH /api/v2/conversations/chats/{conversationId}

Update a conversation by disconnecting all of the participants



Requires ANY permissions: 

* conversation:communication:disconnect

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let body = {}; // Object | Conversation

apiInstance.patchConversationsChat(conversationId, body)
  .then((data) => {
    console.log(`patchConversationsChat success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsChat');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **body** | **Object** | Conversation |  |
{: class="table table-striped"}

### Return type

**Conversation**

<a name="patchConversationsChatParticipant"></a>

# void patchConversationsChatParticipant(conversationId, participantId, body)



PATCH /api/v2/conversations/chats/{conversationId}/participants/{participantId}

Update conversation participant



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let body = {}; // Object | Update request

apiInstance.patchConversationsChatParticipant(conversationId, participantId, body)
  .then(() => {
    console.log('patchConversationsChatParticipant returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsChatParticipant');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** | Update request |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="patchConversationsChatParticipantAttributes"></a>

# void patchConversationsChatParticipantAttributes(conversationId, participantId, body)



PATCH /api/v2/conversations/chats/{conversationId}/participants/{participantId}/attributes

Update the attributes on a conversation participant.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let body = {}; // Object | Participant attributes

apiInstance.patchConversationsChatParticipantAttributes(conversationId, participantId, body)
  .then(() => {
    console.log('patchConversationsChatParticipantAttributes returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsChatParticipantAttributes');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** | Participant attributes |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="patchConversationsChatParticipantCommunication"></a>

# Empty patchConversationsChatParticipantCommunication(conversationId, participantId, communicationId, body)



PATCH /api/v2/conversations/chats/{conversationId}/participants/{participantId}/communications/{communicationId}

Update conversation participant&#39;s communication by disconnecting it.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let communicationId = "communicationId_example"; // String | communicationId
let body = {}; // Object | Participant

apiInstance.patchConversationsChatParticipantCommunication(conversationId, participantId, communicationId, body)
  .then((data) => {
    console.log(`patchConversationsChatParticipantCommunication success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsChatParticipantCommunication');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **communicationId** | **String** | communicationId |  |
 **body** | **Object** | Participant |  |
{: class="table table-striped"}

### Return type

**Empty**

<a name="patchConversationsCobrowsesession"></a>

# Conversation patchConversationsCobrowsesession(conversationId, body)



PATCH /api/v2/conversations/cobrowsesessions/{conversationId}

Update a conversation by disconnecting all of the participants



Requires ANY permissions: 

* conversation:communication:disconnect

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let body = {}; // Object | Conversation

apiInstance.patchConversationsCobrowsesession(conversationId, body)
  .then((data) => {
    console.log(`patchConversationsCobrowsesession success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsCobrowsesession');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **body** | **Object** | Conversation |  |
{: class="table table-striped"}

### Return type

**Conversation**

<a name="patchConversationsCobrowsesessionParticipant"></a>

# void patchConversationsCobrowsesessionParticipant(conversationId, participantId, opts)



PATCH /api/v2/conversations/cobrowsesessions/{conversationId}/participants/{participantId}

Update conversation participant



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let opts = { 
  'body': {} // Object | 
};

apiInstance.patchConversationsCobrowsesessionParticipant(conversationId, participantId, opts)
  .then(() => {
    console.log('patchConversationsCobrowsesessionParticipant returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsCobrowsesessionParticipant');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** |  | [optional]  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="patchConversationsCobrowsesessionParticipantAttributes"></a>

# void patchConversationsCobrowsesessionParticipantAttributes(conversationId, participantId, opts)



PATCH /api/v2/conversations/cobrowsesessions/{conversationId}/participants/{participantId}/attributes

Update the attributes on a conversation participant.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let opts = { 
  'body': {} // Object | 
};

apiInstance.patchConversationsCobrowsesessionParticipantAttributes(conversationId, participantId, opts)
  .then(() => {
    console.log('patchConversationsCobrowsesessionParticipantAttributes returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsCobrowsesessionParticipantAttributes');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** |  | [optional]  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="patchConversationsCobrowsesessionParticipantCommunication"></a>

# Empty patchConversationsCobrowsesessionParticipantCommunication(conversationId, participantId, communicationId, body)



PATCH /api/v2/conversations/cobrowsesessions/{conversationId}/participants/{participantId}/communications/{communicationId}

Update conversation participant&#39;s communication by disconnecting it.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let communicationId = "communicationId_example"; // String | communicationId
let body = {}; // Object | Participant

apiInstance.patchConversationsCobrowsesessionParticipantCommunication(conversationId, participantId, communicationId, body)
  .then((data) => {
    console.log(`patchConversationsCobrowsesessionParticipantCommunication success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsCobrowsesessionParticipantCommunication');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **communicationId** | **String** | communicationId |  |
 **body** | **Object** | Participant |  |
{: class="table table-striped"}

### Return type

**Empty**

<a name="patchConversationsEmail"></a>

# Conversation patchConversationsEmail(conversationId, body)



PATCH /api/v2/conversations/emails/{conversationId}

Update a conversation by disconnecting all of the participants



Requires ANY permissions: 

* conversation:communication:disconnect

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let body = {}; // Object | Conversation

apiInstance.patchConversationsEmail(conversationId, body)
  .then((data) => {
    console.log(`patchConversationsEmail success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsEmail');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **body** | **Object** | Conversation |  |
{: class="table table-striped"}

### Return type

**Conversation**

<a name="patchConversationsEmailParticipant"></a>

# void patchConversationsEmailParticipant(conversationId, participantId, body)



PATCH /api/v2/conversations/emails/{conversationId}/participants/{participantId}

Update conversation participant



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let body = {}; // Object | Update request

apiInstance.patchConversationsEmailParticipant(conversationId, participantId, body)
  .then(() => {
    console.log('patchConversationsEmailParticipant returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsEmailParticipant');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** | Update request |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="patchConversationsEmailParticipantAttributes"></a>

# void patchConversationsEmailParticipantAttributes(conversationId, participantId, body)



PATCH /api/v2/conversations/emails/{conversationId}/participants/{participantId}/attributes

Update the attributes on a conversation participant.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let body = {}; // Object | Participant attributes

apiInstance.patchConversationsEmailParticipantAttributes(conversationId, participantId, body)
  .then(() => {
    console.log('patchConversationsEmailParticipantAttributes returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsEmailParticipantAttributes');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** | Participant attributes |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="patchConversationsEmailParticipantCommunication"></a>

# Empty patchConversationsEmailParticipantCommunication(conversationId, participantId, communicationId, body)



PATCH /api/v2/conversations/emails/{conversationId}/participants/{participantId}/communications/{communicationId}

Update conversation participant&#39;s communication by disconnecting it.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let communicationId = "communicationId_example"; // String | communicationId
let body = {}; // Object | Participant

apiInstance.patchConversationsEmailParticipantCommunication(conversationId, participantId, communicationId, body)
  .then((data) => {
    console.log(`patchConversationsEmailParticipantCommunication success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsEmailParticipantCommunication');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **communicationId** | **String** | communicationId |  |
 **body** | **Object** | Participant |  |
{: class="table table-striped"}

### Return type

**Empty**

<a name="patchConversationsMessage"></a>

# Conversation patchConversationsMessage(conversationId, body)



PATCH /api/v2/conversations/messages/{conversationId}

Update a conversation by disconnecting all of the participants



Requires ANY permissions: 

* conversation:communication:disconnect

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let body = {}; // Object | Conversation

apiInstance.patchConversationsMessage(conversationId, body)
  .then((data) => {
    console.log(`patchConversationsMessage success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsMessage');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **body** | **Object** | Conversation |  |
{: class="table table-striped"}

### Return type

**Conversation**

<a name="patchConversationsMessageParticipant"></a>

# void patchConversationsMessageParticipant(conversationId, participantId, opts)



PATCH /api/v2/conversations/messages/{conversationId}/participants/{participantId}

Update conversation participant



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String |  conversationId
let participantId = "participantId_example"; // String | participantId
let opts = { 
  'body': {} // Object | 
};

apiInstance.patchConversationsMessageParticipant(conversationId, participantId, opts)
  .then(() => {
    console.log('patchConversationsMessageParticipant returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsMessageParticipant');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** |  conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** |  | [optional]  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="patchConversationsMessageParticipantAttributes"></a>

# void patchConversationsMessageParticipantAttributes(conversationId, participantId, opts)



PATCH /api/v2/conversations/messages/{conversationId}/participants/{participantId}/attributes

Update the attributes on a conversation participant.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String |  conversationId
let participantId = "participantId_example"; // String | participantId
let opts = { 
  'body': {} // Object | 
};

apiInstance.patchConversationsMessageParticipantAttributes(conversationId, participantId, opts)
  .then(() => {
    console.log('patchConversationsMessageParticipantAttributes returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsMessageParticipantAttributes');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** |  conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** |  | [optional]  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="patchConversationsMessageParticipantCommunication"></a>

# Empty patchConversationsMessageParticipantCommunication(conversationId, participantId, communicationId, body)



PATCH /api/v2/conversations/messages/{conversationId}/participants/{participantId}/communications/{communicationId}

Update conversation participant&#39;s communication by disconnecting it.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String |  conversationId
let participantId = "participantId_example"; // String | participantId
let communicationId = "communicationId_example"; // String | communicationId
let body = {}; // Object | Participant

apiInstance.patchConversationsMessageParticipantCommunication(conversationId, participantId, communicationId, body)
  .then((data) => {
    console.log(`patchConversationsMessageParticipantCommunication success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsMessageParticipantCommunication');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** |  conversationId |  |
 **participantId** | **String** | participantId |  |
 **communicationId** | **String** | communicationId |  |
 **body** | **Object** | Participant |  |
{: class="table table-striped"}

### Return type

**Empty**

<a name="patchConversationsMessagingIntegrationsFacebookIntegrationId"></a>

# FacebookIntegration patchConversationsMessagingIntegrationsFacebookIntegrationId(integrationId, body)



PATCH /api/v2/conversations/messaging/integrations/facebook/{integrationId}

Update Facebook messaging integration



Requires ALL permissions: 

* messaging:integration:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let integrationId = "integrationId_example"; // String | Integration ID
let body = {}; // Object | FacebookIntegrationUpdateRequest

apiInstance.patchConversationsMessagingIntegrationsFacebookIntegrationId(integrationId, body)
  .then((data) => {
    console.log(`patchConversationsMessagingIntegrationsFacebookIntegrationId success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsMessagingIntegrationsFacebookIntegrationId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **integrationId** | **String** | Integration ID |  |
 **body** | **Object** | FacebookIntegrationUpdateRequest |  |
{: class="table table-striped"}

### Return type

**FacebookIntegration**

<a name="patchConversationsMessagingIntegrationsOpenIntegrationId"></a>

# OpenIntegration patchConversationsMessagingIntegrationsOpenIntegrationId(integrationId, body)



PATCH /api/v2/conversations/messaging/integrations/open/{integrationId}

Update an Open messaging integration

See https://developer.genesys.cloud/api/digital/openmessaging/ for more information.

Requires ALL permissions: 

* messaging:integration:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let integrationId = "integrationId_example"; // String | Integration ID
let body = {}; // Object | OpenIntegrationUpdateRequest

apiInstance.patchConversationsMessagingIntegrationsOpenIntegrationId(integrationId, body)
  .then((data) => {
    console.log(`patchConversationsMessagingIntegrationsOpenIntegrationId success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsMessagingIntegrationsOpenIntegrationId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **integrationId** | **String** | Integration ID |  |
 **body** | **Object** | OpenIntegrationUpdateRequest |  |
{: class="table table-striped"}

### Return type

**OpenIntegration**

<a name="patchConversationsMessagingIntegrationsTwitterIntegrationId"></a>

# TwitterIntegration patchConversationsMessagingIntegrationsTwitterIntegrationId(integrationId, body)



PATCH /api/v2/conversations/messaging/integrations/twitter/{integrationId}

Update Twitter messaging integration



Requires ALL permissions: 

* messaging:integration:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let integrationId = "integrationId_example"; // String | Integration ID
let body = {}; // Object | TwitterIntegrationRequest

apiInstance.patchConversationsMessagingIntegrationsTwitterIntegrationId(integrationId, body)
  .then((data) => {
    console.log(`patchConversationsMessagingIntegrationsTwitterIntegrationId success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsMessagingIntegrationsTwitterIntegrationId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **integrationId** | **String** | Integration ID |  |
 **body** | **Object** | TwitterIntegrationRequest |  |
{: class="table table-striped"}

### Return type

**TwitterIntegration**

<a name="patchConversationsMessagingIntegrationsWhatsappIntegrationId"></a>

# WhatsAppIntegration patchConversationsMessagingIntegrationsWhatsappIntegrationId(integrationId, body)



PATCH /api/v2/conversations/messaging/integrations/whatsapp/{integrationId}

Update or activate a WhatsApp messaging integration.

The following steps are required in order to fully activate a Whatsapp Integration: Initially, you will need to get an activation code by sending: an action set to Activate, and an authenticationMethod choosing from Sms or Voice. Finally, once you have been informed of an activation code on selected authenticationMethod, you will need to confirm the code by sending: an action set to Confirm, and the confirmationCode you have received from Whatsapp.

Requires ALL permissions: 

* messaging:integration:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let integrationId = "integrationId_example"; // String | Integration ID
let body = {}; // Object | WhatsAppIntegrationUpdateRequest

apiInstance.patchConversationsMessagingIntegrationsWhatsappIntegrationId(integrationId, body)
  .then((data) => {
    console.log(`patchConversationsMessagingIntegrationsWhatsappIntegrationId success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling patchConversationsMessagingIntegrationsWhatsappIntegrationId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **integrationId** | **String** | Integration ID |  |
 **body** | **Object** | WhatsAppIntegrationUpdateRequest |  |
{: class="table table-striped"}

### Return type

**WhatsAppIntegration**

<a name="postAnalyticsConversationDetailsProperties"></a>

# PropertyIndexRequest postAnalyticsConversationDetailsProperties(conversationId, body)



POST /api/v2/analytics/conversations/{conversationId}/details/properties

Index conversation properties



Requires ANY permissions: 

* analytics:conversationProperties:index

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let body = {}; // Object | request

apiInstance.postAnalyticsConversationDetailsProperties(conversationId, body)
  .then((data) => {
    console.log(`postAnalyticsConversationDetailsProperties success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postAnalyticsConversationDetailsProperties');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **body** | **Object** | request |  |
{: class="table table-striped"}

### Return type

**PropertyIndexRequest**

<a name="postAnalyticsConversationsAggregatesQuery"></a>

# ConversationAggregateQueryResponse postAnalyticsConversationsAggregatesQuery(body)



POST /api/v2/analytics/conversations/aggregates/query

Query for conversation aggregates



Requires ANY permissions: 

* analytics:conversationAggregate:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | query

apiInstance.postAnalyticsConversationsAggregatesQuery(body)
  .then((data) => {
    console.log(`postAnalyticsConversationsAggregatesQuery success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postAnalyticsConversationsAggregatesQuery');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | query |  |
{: class="table table-striped"}

### Return type

**ConversationAggregateQueryResponse**

<a name="postAnalyticsConversationsDetailsJobs"></a>

# AsyncQueryResponse postAnalyticsConversationsDetailsJobs(body)



POST /api/v2/analytics/conversations/details/jobs

Query for conversation details asynchronously



Requires ANY permissions: 

* analytics:conversationDetail:view
* analytics:agentConversationDetail:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | query

apiInstance.postAnalyticsConversationsDetailsJobs(body)
  .then((data) => {
    console.log(`postAnalyticsConversationsDetailsJobs success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postAnalyticsConversationsDetailsJobs');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | query |  |
{: class="table table-striped"}

### Return type

**AsyncQueryResponse**

<a name="postAnalyticsConversationsDetailsQuery"></a>

# AnalyticsConversationQueryResponse postAnalyticsConversationsDetailsQuery(body)



POST /api/v2/analytics/conversations/details/query

Query for conversation details



Requires ANY permissions: 

* analytics:conversationDetail:view
* analytics:agentConversationDetail:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | query

apiInstance.postAnalyticsConversationsDetailsQuery(body)
  .then((data) => {
    console.log(`postAnalyticsConversationsDetailsQuery success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postAnalyticsConversationsDetailsQuery');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | query |  |
{: class="table table-striped"}

### Return type

**AnalyticsConversationQueryResponse**

<a name="postConversationAssign"></a>

# **&#39;String&#39;** postConversationAssign(conversationId, body)



POST /api/v2/conversations/{conversationId}/assign

Attempts to manually assign a specified conversation to a specified user.  Ignores bullseye ring, PAR score, skills, and languages.



Requires ANY permissions: 

* conversation:call:pull
* conversation:call:assign
* conversation:callback:pull
* conversation:callback:assign
* conversation:webchat:pull
* conversation:webchat:assign
* conversation:email:pull
* conversation:email:assign
* conversation:message:pull
* conversation:message:assign

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID
let body = {}; // Object | Targeted user

apiInstance.postConversationAssign(conversationId, body)
  .then((data) => {
    console.log(`postConversationAssign success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationAssign');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
 **body** | **Object** | Targeted user |  |
{: class="table table-striped"}

### Return type

**&#39;String&#39;**

<a name="postConversationDisconnect"></a>

# **&#39;String&#39;** postConversationDisconnect(conversationId)



POST /api/v2/conversations/{conversationId}/disconnect

Performs a full conversation teardown. Issues disconnect requests for any connected media. Applies a system wrap-up code to any participants that are pending wrap-up. This is not intended to be the normal way of ending interactions but is available in the event of problems with the application to allow a resynchronization of state across all components. It is recommended that users submit a support case if they are relying on this endpoint systematically as there is likely something that needs investigation.



Requires ANY permissions: 

* conversation:communication:disconnect

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID

apiInstance.postConversationDisconnect(conversationId)
  .then((data) => {
    console.log(`postConversationDisconnect success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationDisconnect');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
{: class="table table-striped"}

### Return type

**&#39;String&#39;**

<a name="postConversationParticipantCallbacks"></a>

# void postConversationParticipantCallbacks(conversationId, participantId, opts)



POST /api/v2/conversations/{conversationId}/participants/{participantId}/callbacks

Create a new callback for the specified participant on the conversation.



Requires ALL permissions: 

* conversation:callback:create

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID
let participantId = "participantId_example"; // String | participant ID
let opts = { 
  'body': {} // Object | 
};

apiInstance.postConversationParticipantCallbacks(conversationId, participantId, opts)
  .then(() => {
    console.log('postConversationParticipantCallbacks returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationParticipantCallbacks');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
 **participantId** | **String** | participant ID |  |
 **body** | **Object** |  | [optional]  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="postConversationParticipantDigits"></a>

# void postConversationParticipantDigits(conversationId, participantId, opts)



POST /api/v2/conversations/{conversationId}/participants/{participantId}/digits

Sends DTMF to the participant



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID
let participantId = "participantId_example"; // String | participant ID
let opts = { 
  'body': {} // Object | Digits
};

apiInstance.postConversationParticipantDigits(conversationId, participantId, opts)
  .then(() => {
    console.log('postConversationParticipantDigits returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationParticipantDigits');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
 **participantId** | **String** | participant ID |  |
 **body** | **Object** | Digits | [optional]  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="postConversationParticipantReplace"></a>

# void postConversationParticipantReplace(conversationId, participantId, body)



POST /api/v2/conversations/{conversationId}/participants/{participantId}/replace

Replace this participant with the specified user and/or address



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID
let participantId = "participantId_example"; // String | participant ID
let body = {}; // Object | Transfer request

apiInstance.postConversationParticipantReplace(conversationId, participantId, body)
  .then(() => {
    console.log('postConversationParticipantReplace returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationParticipantReplace');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
 **participantId** | **String** | participant ID |  |
 **body** | **Object** | Transfer request |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="postConversationParticipantSecureivrsessions"></a>

# SecureSession postConversationParticipantSecureivrsessions(conversationId, participantId, opts)



POST /api/v2/conversations/{conversationId}/participants/{participantId}/secureivrsessions

Create secure IVR session. Only a participant in the conversation can invoke a secure IVR.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID
let participantId = "participantId_example"; // String | participant ID
let opts = { 
  'body': {} // Object | 
};

apiInstance.postConversationParticipantSecureivrsessions(conversationId, participantId, opts)
  .then((data) => {
    console.log(`postConversationParticipantSecureivrsessions success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationParticipantSecureivrsessions');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
 **participantId** | **String** | participant ID |  |
 **body** | **Object** |  | [optional]  |
{: class="table table-striped"}

### Return type

**SecureSession**

<a name="postConversationsCall"></a>

# Conversation postConversationsCall(conversationId, body)



POST /api/v2/conversations/calls/{conversationId}

Place a new call as part of a callback conversation.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let body = {}; // Object | Conversation

apiInstance.postConversationsCall(conversationId, body)
  .then((data) => {
    console.log(`postConversationsCall success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsCall');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **body** | **Object** | Conversation |  |
{: class="table table-striped"}

### Return type

**Conversation**

<a name="postConversationsCallParticipantCoach"></a>

# void postConversationsCallParticipantCoach(conversationId, participantId)



POST /api/v2/conversations/calls/{conversationId}/participants/{participantId}/coach

Listen in on the conversation from the point of view of a given participant while speaking to just the given participant.



Requires ANY permissions: 

* conversation:call:coach

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId

apiInstance.postConversationsCallParticipantCoach(conversationId, participantId)
  .then(() => {
    console.log('postConversationsCallParticipantCoach returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsCallParticipantCoach');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="postConversationsCallParticipantConsult"></a>

# ConsultTransferResponse postConversationsCallParticipantConsult(conversationId, participantId, body)



POST /api/v2/conversations/calls/{conversationId}/participants/{participantId}/consult

Initiate and update consult transfer



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let body = {}; // Object | Destination address & initial speak to

apiInstance.postConversationsCallParticipantConsult(conversationId, participantId, body)
  .then((data) => {
    console.log(`postConversationsCallParticipantConsult success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsCallParticipantConsult');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** | Destination address &amp; initial speak to |  |
{: class="table table-striped"}

### Return type

**ConsultTransferResponse**

<a name="postConversationsCallParticipantMonitor"></a>

# void postConversationsCallParticipantMonitor(conversationId, participantId)



POST /api/v2/conversations/calls/{conversationId}/participants/{participantId}/monitor

Listen in on the conversation from the point of view of a given participant.



Requires ANY permissions: 

* conversation:call:monitor

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId

apiInstance.postConversationsCallParticipantMonitor(conversationId, participantId)
  .then(() => {
    console.log('postConversationsCallParticipantMonitor returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsCallParticipantMonitor');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="postConversationsCallParticipantReplace"></a>

# void postConversationsCallParticipantReplace(conversationId, participantId, body)



POST /api/v2/conversations/calls/{conversationId}/participants/{participantId}/replace

Replace this participant with the specified user and/or address



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let body = {}; // Object | Transfer request

apiInstance.postConversationsCallParticipantReplace(conversationId, participantId, body)
  .then(() => {
    console.log('postConversationsCallParticipantReplace returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsCallParticipantReplace');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** | Transfer request |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="postConversationsCallParticipants"></a>

# Conversation postConversationsCallParticipants(conversationId, body)



POST /api/v2/conversations/calls/{conversationId}/participants

Add participants to a conversation



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let body = {}; // Object | Conversation

apiInstance.postConversationsCallParticipants(conversationId, body)
  .then((data) => {
    console.log(`postConversationsCallParticipants success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsCallParticipants');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **body** | **Object** | Conversation |  |
{: class="table table-striped"}

### Return type

**Conversation**

<a name="postConversationsCallbackParticipantReplace"></a>

# void postConversationsCallbackParticipantReplace(conversationId, participantId, body)



POST /api/v2/conversations/callbacks/{conversationId}/participants/{participantId}/replace

Replace this participant with the specified user and/or address



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let body = {}; // Object | Transfer request

apiInstance.postConversationsCallbackParticipantReplace(conversationId, participantId, body)
  .then(() => {
    console.log('postConversationsCallbackParticipantReplace returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsCallbackParticipantReplace');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** | Transfer request |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="postConversationsCallbacks"></a>

# CreateCallbackResponse postConversationsCallbacks(body)



POST /api/v2/conversations/callbacks

Create a Callback



Requires ALL permissions: 

* conversation:callback:create

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | Callback

apiInstance.postConversationsCallbacks(body)
  .then((data) => {
    console.log(`postConversationsCallbacks success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsCallbacks');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | Callback |  |
{: class="table table-striped"}

### Return type

**CreateCallbackResponse**

<a name="postConversationsCalls"></a>

# CreateCallResponse postConversationsCalls(body)



POST /api/v2/conversations/calls

Create a call conversation



Requires ANY permissions: 

* conversation:conference:add

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | Call request

apiInstance.postConversationsCalls(body)
  .then((data) => {
    console.log(`postConversationsCalls success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsCalls');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | Call request |  |
{: class="table table-striped"}

### Return type

**CreateCallResponse**

<a name="postConversationsChatCommunicationMessages"></a>

# WebChatMessage postConversationsChatCommunicationMessages(conversationId, communicationId, body)



POST /api/v2/conversations/chats/{conversationId}/communications/{communicationId}/messages

Send a message on behalf of a communication in a chat conversation.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let communicationId = "communicationId_example"; // String | communicationId
let body = {}; // Object | Message

apiInstance.postConversationsChatCommunicationMessages(conversationId, communicationId, body)
  .then((data) => {
    console.log(`postConversationsChatCommunicationMessages success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsChatCommunicationMessages');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **communicationId** | **String** | communicationId |  |
 **body** | **Object** | Message |  |
{: class="table table-striped"}

### Return type

**WebChatMessage**

<a name="postConversationsChatCommunicationTyping"></a>

# WebChatTyping postConversationsChatCommunicationTyping(conversationId, communicationId)



POST /api/v2/conversations/chats/{conversationId}/communications/{communicationId}/typing

Send a typing-indicator on behalf of a communication in a chat conversation.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let communicationId = "communicationId_example"; // String | communicationId

apiInstance.postConversationsChatCommunicationTyping(conversationId, communicationId)
  .then((data) => {
    console.log(`postConversationsChatCommunicationTyping success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsChatCommunicationTyping');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **communicationId** | **String** | communicationId |  |
{: class="table table-striped"}

### Return type

**WebChatTyping**

<a name="postConversationsChatParticipantReplace"></a>

# void postConversationsChatParticipantReplace(conversationId, participantId, body)



POST /api/v2/conversations/chats/{conversationId}/participants/{participantId}/replace

Replace this participant with the specified user and/or address



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let body = {}; // Object | Transfer request

apiInstance.postConversationsChatParticipantReplace(conversationId, participantId, body)
  .then(() => {
    console.log('postConversationsChatParticipantReplace returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsChatParticipantReplace');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** | Transfer request |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="postConversationsChats"></a>

# ChatConversation postConversationsChats(body)



POST /api/v2/conversations/chats

Create a web chat conversation



Requires ALL permissions: 

* conversation:webchat:create

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | Create web chat request

apiInstance.postConversationsChats(body)
  .then((data) => {
    console.log(`postConversationsChats success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsChats');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | Create web chat request |  |
{: class="table table-striped"}

### Return type

**ChatConversation**

<a name="postConversationsCobrowsesessionParticipantReplace"></a>

# void postConversationsCobrowsesessionParticipantReplace(conversationId, participantId, opts)



POST /api/v2/conversations/cobrowsesessions/{conversationId}/participants/{participantId}/replace

Replace this participant with the specified user and/or address



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let opts = { 
  'body': {} // Object | 
};

apiInstance.postConversationsCobrowsesessionParticipantReplace(conversationId, participantId, opts)
  .then(() => {
    console.log('postConversationsCobrowsesessionParticipantReplace returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsCobrowsesessionParticipantReplace');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** |  | [optional]  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="postConversationsEmailInboundmessages"></a>

# EmailConversation postConversationsEmailInboundmessages(conversationId, body)



POST /api/v2/conversations/emails/{conversationId}/inboundmessages

Send an email to an external conversation. An external conversation is one where the provider is not PureCloud based. This endpoint allows the sender of the external email to reply or send a new message to the existing conversation. The new message will be treated as part of the existing conversation and chained to it.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let body = {}; // Object | Send external email reply

apiInstance.postConversationsEmailInboundmessages(conversationId, body)
  .then((data) => {
    console.log(`postConversationsEmailInboundmessages success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsEmailInboundmessages');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **body** | **Object** | Send external email reply |  |
{: class="table table-striped"}

### Return type

**EmailConversation**

<a name="postConversationsEmailMessages"></a>

# EmailMessage postConversationsEmailMessages(conversationId, body)



POST /api/v2/conversations/emails/{conversationId}/messages

Send an email reply



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let body = {}; // Object | Reply

apiInstance.postConversationsEmailMessages(conversationId, body)
  .then((data) => {
    console.log(`postConversationsEmailMessages success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsEmailMessages');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **body** | **Object** | Reply |  |
{: class="table table-striped"}

### Return type

**EmailMessage**

<a name="postConversationsEmailMessagesDraftAttachmentsCopy"></a>

# EmailMessage postConversationsEmailMessagesDraftAttachmentsCopy(conversationId, body)



POST /api/v2/conversations/emails/{conversationId}/messages/draft/attachments/copy

Copy attachments from an email message to the current draft.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let body = {}; // Object | Copy Attachment Request

apiInstance.postConversationsEmailMessagesDraftAttachmentsCopy(conversationId, body)
  .then((data) => {
    console.log(`postConversationsEmailMessagesDraftAttachmentsCopy success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsEmailMessagesDraftAttachmentsCopy');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **body** | **Object** | Copy Attachment Request |  |
{: class="table table-striped"}

### Return type

**EmailMessage**

<a name="postConversationsEmailParticipantReplace"></a>

# void postConversationsEmailParticipantReplace(conversationId, participantId, body)



POST /api/v2/conversations/emails/{conversationId}/participants/{participantId}/replace

Replace this participant with the specified user and/or address



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let body = {}; // Object | Transfer request

apiInstance.postConversationsEmailParticipantReplace(conversationId, participantId, body)
  .then(() => {
    console.log('postConversationsEmailParticipantReplace returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsEmailParticipantReplace');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** | Transfer request |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="postConversationsEmails"></a>

# EmailConversation postConversationsEmails(body)



POST /api/v2/conversations/emails

Create an email conversation

If the direction of the request is INBOUND, this will create an external conversation with a third party provider. If the direction of the the request is OUTBOUND, this will create a conversation to send outbound emails on behalf of a queue.

Requires ANY permissions: 

* conversation:email:create

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | Create email request

apiInstance.postConversationsEmails(body)
  .then((data) => {
    console.log(`postConversationsEmails success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsEmails');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | Create email request |  |
{: class="table table-striped"}

### Return type

**EmailConversation**

<a name="postConversationsFaxes"></a>

# FaxSendResponse postConversationsFaxes(body)



POST /api/v2/conversations/faxes

Create Fax Conversation



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | Fax

apiInstance.postConversationsFaxes(body)
  .then((data) => {
    console.log(`postConversationsFaxes success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsFaxes');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | Fax |  |
{: class="table table-striped"}

### Return type

**FaxSendResponse**

<a name="postConversationsMessageCommunicationMessages"></a>

# MessageData postConversationsMessageCommunicationMessages(conversationId, communicationId, body)



POST /api/v2/conversations/messages/{conversationId}/communications/{communicationId}/messages

Send message

Send message on existing conversation/communication. Only one message body field can be accepted, per request. Example: 1 textBody, 1 mediaId, 1 stickerId, or 1 messageTemplate.

Requires ANY permissions: 

* conversation:message:create
* conversation:webmessaging:create

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let communicationId = "communicationId_example"; // String | communicationId
let body = {}; // Object | Message

apiInstance.postConversationsMessageCommunicationMessages(conversationId, communicationId, body)
  .then((data) => {
    console.log(`postConversationsMessageCommunicationMessages success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsMessageCommunicationMessages');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **communicationId** | **String** | communicationId |  |
 **body** | **Object** | Message |  |
{: class="table table-striped"}

### Return type

**MessageData**

<a name="postConversationsMessageCommunicationMessagesMedia"></a>

# MessageMediaData postConversationsMessageCommunicationMessagesMedia(conversationId, communicationId)



POST /api/v2/conversations/messages/{conversationId}/communications/{communicationId}/messages/media

Create media

See https://developer.genesys.cloud/api/rest/v2/conversations/messaging-media-upload for example usage.

Requires ANY permissions: 

* conversation:message:create
* conversation:webmessaging:create

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let communicationId = "communicationId_example"; // String | communicationId

apiInstance.postConversationsMessageCommunicationMessagesMedia(conversationId, communicationId)
  .then((data) => {
    console.log(`postConversationsMessageCommunicationMessagesMedia success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsMessageCommunicationMessagesMedia');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **communicationId** | **String** | communicationId |  |
{: class="table table-striped"}

### Return type

**MessageMediaData**

<a name="postConversationsMessageMessagesBulk"></a>

# TextMessageListing postConversationsMessageMessagesBulk(conversationId, opts)



POST /api/v2/conversations/messages/{conversationId}/messages/bulk

Get messages in batch

The path parameter [conversationId] should contain the conversationId of the conversation being filtered. The body should contain the messageId(s) of messages being requested. For example: [\&quot;a3069a33b-bbb1-4703-9d68-061d9e9db96e\&quot;, \&quot;55bc6be3-078c-4a49-a4e6-1e05776ed7e8\&quot;]

Requires ANY permissions: 

* conversation:message:view
* conversation:webmessaging:view

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | 
let opts = { 
  'body': [{}] // Object | messageIds
};

apiInstance.postConversationsMessageMessagesBulk(conversationId, opts)
  .then((data) => {
    console.log(`postConversationsMessageMessagesBulk success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsMessageMessagesBulk');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** |  |  |
 **body** | **Object** | messageIds | [optional]  |
{: class="table table-striped"}

### Return type

**TextMessageListing**

<a name="postConversationsMessageParticipantReplace"></a>

# void postConversationsMessageParticipantReplace(conversationId, participantId, body)



POST /api/v2/conversations/messages/{conversationId}/participants/{participantId}/replace

Replace this participant with the specified user and/or address



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let body = {}; // Object | Transfer request

apiInstance.postConversationsMessageParticipantReplace(conversationId, participantId, body)
  .then(() => {
    console.log('postConversationsMessageParticipantReplace returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsMessageParticipantReplace');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **body** | **Object** | Transfer request |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="postConversationsMessages"></a>

# MessageConversation postConversationsMessages(body)



POST /api/v2/conversations/messages

Create an outbound messaging conversation.

If there is an existing conversation between the remote address and the address associated with the queue specified in createOutboundRequest then the result of this request depends on the state of that conversation and the useExistingConversation field of createOutboundRequest. If the existing conversation is in alerting or connected state, then the request will fail. If the existing conversation is disconnected but still within the conversation window then the request will fail unless useExistingConversation is set to true.

Requires ALL permissions: 

* conversation:message:create

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | Create outbound messaging conversation

apiInstance.postConversationsMessages(body)
  .then((data) => {
    console.log(`postConversationsMessages success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsMessages');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | Create outbound messaging conversation |  |
{: class="table table-striped"}

### Return type

**MessageConversation**

<a name="postConversationsMessagesAgentless"></a>

# SendAgentlessOutboundMessageResponse postConversationsMessagesAgentless(body)



POST /api/v2/conversations/messages/agentless

Send an agentless outbound message

Send an agentlesss (api participant) outbound message using a client credential grant. In order to call this endpoint you will need OAuth token generated using OAuth client credentials authorized with at least messaging scope. This will generate a new Conversation, if there is an existing active Conversation between the fromAddress and toAddress already, then this POST will fail.

Requires ALL permissions: 

* conversation:message:create

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | Create agentless outbound messaging request

apiInstance.postConversationsMessagesAgentless(body)
  .then((data) => {
    console.log(`postConversationsMessagesAgentless success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsMessagesAgentless');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | Create agentless outbound messaging request |  |
{: class="table table-striped"}

### Return type

**SendAgentlessOutboundMessageResponse**

<a name="postConversationsMessagesInboundOpen"></a>

# OpenNormalizedMessage postConversationsMessagesInboundOpen(body)



POST /api/v2/conversations/messages/inbound/open

Send an inbound Open Message

Send an inbound message to an Open Messaging integration. In order to call this endpoint you will need OAuth token generated using OAuth client credentials authorized with at least messaging scope. This will either generate a new Conversation, or be a part of an existing conversation. See https://developer.genesys.cloud/api/digital/openmessaging/ for example usage.

Requires ALL permissions: 

* conversation:message:receive

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | NormalizedMessage

apiInstance.postConversationsMessagesInboundOpen(body)
  .then((data) => {
    console.log(`postConversationsMessagesInboundOpen success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsMessagesInboundOpen');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | NormalizedMessage |  |
{: class="table table-striped"}

### Return type

**OpenNormalizedMessage**

<a name="postConversationsMessagingIntegrationsFacebook"></a>

# FacebookIntegration postConversationsMessagingIntegrationsFacebook(body)



POST /api/v2/conversations/messaging/integrations/facebook

Create a Facebook Integration



Requires ALL permissions: 

* messaging:integration:add

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | FacebookIntegrationRequest

apiInstance.postConversationsMessagingIntegrationsFacebook(body)
  .then((data) => {
    console.log(`postConversationsMessagingIntegrationsFacebook success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsMessagingIntegrationsFacebook');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | FacebookIntegrationRequest |  |
{: class="table table-striped"}

### Return type

**FacebookIntegration**

<a name="postConversationsMessagingIntegrationsLine"></a>

# LineIntegration postConversationsMessagingIntegrationsLine(body)



POST /api/v2/conversations/messaging/integrations/line

Create a LINE messenger Integration



Requires ALL permissions: 

* messaging:integration:add

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | LineIntegrationRequest

apiInstance.postConversationsMessagingIntegrationsLine(body)
  .then((data) => {
    console.log(`postConversationsMessagingIntegrationsLine success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsMessagingIntegrationsLine');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | LineIntegrationRequest |  |
{: class="table table-striped"}

### Return type

**LineIntegration**

<a name="postConversationsMessagingIntegrationsOpen"></a>

# OpenIntegration postConversationsMessagingIntegrationsOpen(body)



POST /api/v2/conversations/messaging/integrations/open

Create an Open messaging integration

See https://developer.genesys.cloud/api/digital/openmessaging/ for more information.

Requires ALL permissions: 

* messaging:integration:add

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | OpenIntegrationRequest

apiInstance.postConversationsMessagingIntegrationsOpen(body)
  .then((data) => {
    console.log(`postConversationsMessagingIntegrationsOpen success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsMessagingIntegrationsOpen');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | OpenIntegrationRequest |  |
{: class="table table-striped"}

### Return type

**OpenIntegration**

<a name="postConversationsMessagingIntegrationsTwitter"></a>

# TwitterIntegration postConversationsMessagingIntegrationsTwitter(body)



POST /api/v2/conversations/messaging/integrations/twitter

Create a Twitter Integration



Requires ALL permissions: 

* messaging:integration:add

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | TwitterIntegrationRequest

apiInstance.postConversationsMessagingIntegrationsTwitter(body)
  .then((data) => {
    console.log(`postConversationsMessagingIntegrationsTwitter success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsMessagingIntegrationsTwitter');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | TwitterIntegrationRequest |  |
{: class="table table-striped"}

### Return type

**TwitterIntegration**

<a name="postConversationsMessagingIntegrationsWhatsapp"></a>

# WhatsAppIntegration postConversationsMessagingIntegrationsWhatsapp(body)



POST /api/v2/conversations/messaging/integrations/whatsapp

Create a WhatsApp Integration

You must be approved by WhatsApp to use this feature. Your approved e164-formatted phone number and valid WhatsApp certificate for your number are required. Your WhatsApp certificate must have valid base64 encoding. Please paste carefully and do not add any leading or trailing spaces. Do not alter any characters. An integration must be activated within 7 days of certificate generation. If you cannot complete the addition and activation of the number within 7 days, please obtain a new certificate before creating the integration. Integrations created with an invalid number or certificate may immediately incur additional integration fees. Please carefully enter your number and certificate as described.

Requires ALL permissions: 

* messaging:whatsappIntegration:add

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | WhatsAppIntegrationRequest

apiInstance.postConversationsMessagingIntegrationsWhatsapp(body)
  .then((data) => {
    console.log(`postConversationsMessagingIntegrationsWhatsapp success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling postConversationsMessagingIntegrationsWhatsapp');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | WhatsAppIntegrationRequest |  |
{: class="table table-striped"}

### Return type

**WhatsAppIntegration**

<a name="putConversationParticipantFlaggedreason"></a>

# void putConversationParticipantFlaggedreason(conversationId, participantId)



PUT /api/v2/conversations/{conversationId}/participants/{participantId}/flaggedreason

Set flagged reason on conversation participant to indicate bad conversation quality.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID
let participantId = "participantId_example"; // String | participant ID

apiInstance.putConversationParticipantFlaggedreason(conversationId, participantId)
  .then(() => {
    console.log('putConversationParticipantFlaggedreason returned successfully.');
  })
  .catch((err) => {
    console.log('There was a failure calling putConversationParticipantFlaggedreason');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
 **participantId** | **String** | participant ID |  |
{: class="table table-striped"}

### Return type

void (no response body)

<a name="putConversationTags"></a>

# **&#39;String&#39;** putConversationTags(conversationId, body)



PUT /api/v2/conversations/{conversationId}/tags

Update the tags on a conversation.



Requires ANY permissions: 

* conversation:externalTag:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversation ID
let body = {}; // Object | Conversation Tags

apiInstance.putConversationTags(conversationId, body)
  .then((data) => {
    console.log(`putConversationTags success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling putConversationTags');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversation ID |  |
 **body** | **Object** | Conversation Tags |  |
{: class="table table-striped"}

### Return type

**&#39;String&#39;**

<a name="putConversationsCallParticipantCommunicationUuidata"></a>

# Empty putConversationsCallParticipantCommunicationUuidata(conversationId, participantId, communicationId, body)



PUT /api/v2/conversations/calls/{conversationId}/participants/{participantId}/communications/{communicationId}/uuidata

Set uuiData to be sent on future commands.



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let participantId = "participantId_example"; // String | participantId
let communicationId = "communicationId_example"; // String | communicationId
let body = {}; // Object | UUIData Request

apiInstance.putConversationsCallParticipantCommunicationUuidata(conversationId, participantId, communicationId, body)
  .then((data) => {
    console.log(`putConversationsCallParticipantCommunicationUuidata success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling putConversationsCallParticipantCommunicationUuidata');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **participantId** | **String** | participantId |  |
 **communicationId** | **String** | communicationId |  |
 **body** | **Object** | UUIData Request |  |
{: class="table table-striped"}

### Return type

**Empty**

<a name="putConversationsEmailMessagesDraft"></a>

# EmailMessage putConversationsEmailMessagesDraft(conversationId, body)



PUT /api/v2/conversations/emails/{conversationId}/messages/draft

Update conversation draft reply



Requires NO permissions: 


### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let conversationId = "conversationId_example"; // String | conversationId
let body = {}; // Object | Draft

apiInstance.putConversationsEmailMessagesDraft(conversationId, body)
  .then((data) => {
    console.log(`putConversationsEmailMessagesDraft success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling putConversationsEmailMessagesDraft');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **conversationId** | **String** | conversationId |  |
 **body** | **Object** | Draft |  |
{: class="table table-striped"}

### Return type

**EmailMessage**

<a name="putConversationsMessagingIntegrationsLineIntegrationId"></a>

# LineIntegration putConversationsMessagingIntegrationsLineIntegrationId(integrationId, body)



PUT /api/v2/conversations/messaging/integrations/line/{integrationId}

Update a LINE messenger integration



Requires ALL permissions: 

* messaging:integration:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let integrationId = "integrationId_example"; // String | Integration ID
let body = {}; // Object | LineIntegrationRequest

apiInstance.putConversationsMessagingIntegrationsLineIntegrationId(integrationId, body)
  .then((data) => {
    console.log(`putConversationsMessagingIntegrationsLineIntegrationId success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling putConversationsMessagingIntegrationsLineIntegrationId');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **integrationId** | **String** | Integration ID |  |
 **body** | **Object** | LineIntegrationRequest |  |
{: class="table table-striped"}

### Return type

**LineIntegration**

<a name="putConversationsMessagingThreadingtimeline"></a>

# ConversationThreadingWindow putConversationsMessagingThreadingtimeline(body)



PUT /api/v2/conversations/messaging/threadingtimeline

Update conversation threading window timeline for each messaging type

PUT Conversation messaging threading timeline is intended to set the conversation threading settings for ALL messengerTypes. If you omit a messengerType in the request body then the setting for that messengerType will use the platform default value. The PUT replaces the existing setting(s) that were previously set for each messengerType.

Requires ALL permissions: 

* conversation:threadingTimeline:edit

### Example Usage

```{"language":"javascript"}
// Browser
const platformClient = require('platformClient');
// Node
const platformClient = require('purecloud-platform-client-v2');

// Manually set auth token or use loginImplicitGrant(...) or loginClientCredentialsGrant(...)
platformClient.ApiClient.instance.setAccessToken(yourAccessToken);

let apiInstance = new platformClient.ConversationsApi();

let body = {}; // Object | ConversationThreadingWindowRequest

apiInstance.putConversationsMessagingThreadingtimeline(body)
  .then((data) => {
    console.log(`putConversationsMessagingThreadingtimeline success! data: ${JSON.stringify(data, null, 2)}`);
  })
  .catch((err) => {
    console.log('There was a failure calling putConversationsMessagingThreadingtimeline');
    console.error(err);
  });
```

### Parameters


| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
 **body** | **Object** | ConversationThreadingWindowRequest |  |
{: class="table table-striped"}

### Return type

**ConversationThreadingWindow**

