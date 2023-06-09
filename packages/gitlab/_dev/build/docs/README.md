# GitLab Integration

The GitLab integration collects audit events from the GitLab API, specifically reading from the GitLab Audit Events API.

## Logs

### System

The GitLab Audit Events records system events related to your organization in order to provide an audit trail that can be used to understand platform activity and to diagnose problems. This module is implemented using the httpjson input and is configured to paginate through the logs.

{{event "system"}}

{{fields "system"}}