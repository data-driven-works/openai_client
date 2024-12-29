# OpenAIClient::AuditLog

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **String** | The ID of this log. | 
**type** | [**AuditLogEventType**](AuditLogEventType.md) |  | 
**effective_at** | **Integer** | The Unix timestamp (in seconds) of the event. | 
**project** | [**AuditLogProject**](AuditLogProject.md) |  | [optional] 
**actor** | [**AuditLogActor**](AuditLogActor.md) |  | 
**api_key_created** | [**AuditLogApiKeyCreated**](AuditLogApiKeyCreated.md) |  | [optional] 
**api_key_updated** | [**AuditLogApiKeyUpdated**](AuditLogApiKeyUpdated.md) |  | [optional] 
**api_key_deleted** | [**AuditLogApiKeyDeleted**](AuditLogApiKeyDeleted.md) |  | [optional] 
**invite_sent** | [**AuditLogInviteSent**](AuditLogInviteSent.md) |  | [optional] 
**invite_accepted** | [**AuditLogInviteAccepted**](AuditLogInviteAccepted.md) |  | [optional] 
**invite_deleted** | [**AuditLogInviteAccepted**](AuditLogInviteAccepted.md) |  | [optional] 
**login_failed** | [**AuditLogLoginFailed**](AuditLogLoginFailed.md) |  | [optional] 
**logout_failed** | [**AuditLogLoginFailed**](AuditLogLoginFailed.md) |  | [optional] 
**organization_updated** | [**AuditLogOrganizationUpdated**](AuditLogOrganizationUpdated.md) |  | [optional] 
**project_created** | [**AuditLogProjectCreated**](AuditLogProjectCreated.md) |  | [optional] 
**project_updated** | [**AuditLogProjectUpdated**](AuditLogProjectUpdated.md) |  | [optional] 
**project_archived** | [**AuditLogProjectArchived**](AuditLogProjectArchived.md) |  | [optional] 
**rate_limit_updated** | [**AuditLogRateLimitUpdated**](AuditLogRateLimitUpdated.md) |  | [optional] 
**rate_limit_deleted** | [**AuditLogRateLimitDeleted**](AuditLogRateLimitDeleted.md) |  | [optional] 
**service_account_created** | [**AuditLogServiceAccountCreated**](AuditLogServiceAccountCreated.md) |  | [optional] 
**service_account_updated** | [**AuditLogServiceAccountUpdated**](AuditLogServiceAccountUpdated.md) |  | [optional] 
**service_account_deleted** | [**AuditLogServiceAccountDeleted**](AuditLogServiceAccountDeleted.md) |  | [optional] 
**user_added** | [**AuditLogUserAdded**](AuditLogUserAdded.md) |  | [optional] 
**user_updated** | [**AuditLogUserUpdated**](AuditLogUserUpdated.md) |  | [optional] 
**user_deleted** | [**AuditLogUserDeleted**](AuditLogUserDeleted.md) |  | [optional] 

