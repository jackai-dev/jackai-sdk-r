# JackAI Platform OS Hub API (public subset) R API

<!-- omniwrap-api-reference eyJjb250cmFjdF9maW5nZXJwcmludCI6ImM3Y2E1ZTVlYmI0YzA5MjkxMGVjNzJiMzcxZTE4ODMwMzM1OGM1ZTM0ZDI5MDhjMGE4OGY3ODJhMjQxMTYyY2YiLCJvcGVyYXRpb25fY291bnQiOjgsInJlbmRlcmVyIjoiciIsInZlcnNpb24iOiIxLjUuMCJ9 -->

This generated index is tied to Semantic IR `1.14.0` and contract fingerprint `c7ca5e5ebb4c092910ec72b371e188303358c5e34d2908c0a88f782a241162cf`. Every operation below is rendered from the same semantic contract and artifact-attested public member allocation as the SDK.

SDK maturity: **experimental**  
Artifact evidence: [`omniwrap-artifact.json`](omniwrap-artifact.json) binds this file by SHA-256 and is revalidated by the package gate.

## Resource `health`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRfaGVhbHRoIiwibWV0aG9kIjoiR0VUIiwib3BlcmF0aW9uX2lkIjoiZ2V0SGVhbHRoIiwicGF0aCI6Ii9oZWFsdGgiLCJyZXNvdXJjZSI6ImhlYWx0aCIsInNlY3Rpb25fc2hhMjU2IjoiMzYzOWYyM2M1ODNiOWQ0NmRjMDI3MjdiYWQxMDI1NDQxMGI0OWFiNWU2YmVkMDNkYmY5MjNlNDRjNTI2MjZlNyIsInNpZ25hdHVyZV9zaGEyNTYiOiJkODc2OWRmZTU0YzljYjUyZWRiYTRhYzAyZGNlYjA0YzA1NTIyZjI0NTI0Njg1MDRiMDgxY2RkZTU5ZWU4NTVjIn0 -->
### `client.get_health`

Operation ID: `getHealth`  
Route: `GET` `/health`  

#### Signature

```r
get_health <- function(client)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Hub liveness status | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRIZWFsdGgifQ -->

## Resource `kernel`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJmYWlsX3VzYWdlX3F1b3RhIiwibWV0aG9kIjoiUE9TVCIsIm9wZXJhdGlvbl9pZCI6ImZhaWxVc2FnZVF1b3RhIiwicGF0aCI6Ii92MS9rZXJuZWwvdXNhZ2UvZmFpbCIsInJlc291cmNlIjoia2VybmVsIiwic2VjdGlvbl9zaGEyNTYiOiI3Y2YzMmYyNzkxOTFmNGE1ZTVhOTA4ZDcyMTQzNjhhYjUyNmUxODRkNTM5ODYyOGYzNGJlNjM1ZjcxZjBmYjlhIiwic2lnbmF0dXJlX3NoYTI1NiI6IjQ2N2E1M2RjNzBmOGM0YjhiNzEwMWU2MjVmMzk2NTc0ODQ5ODNjZDhkMzJhNDViNjUwZDk0YjAwZjFlMjBmMDIifQ -->
### `client.fail_usage_quota`

Operation ID: `failUsageQuota`  
Route: `POST` `/v1/kernel/usage/fail`  

#### Signature

```r
fail_usage_quota <- function(client)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Reservation released | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJmYWlsVXNhZ2VRdW90YSJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJmaW5hbGl6ZV91c2FnZV9xdW90YSIsIm1ldGhvZCI6IlBPU1QiLCJvcGVyYXRpb25faWQiOiJmaW5hbGl6ZVVzYWdlUXVvdGEiLCJwYXRoIjoiL3YxL2tlcm5lbC91c2FnZS9maW5hbGl6ZSIsInJlc291cmNlIjoia2VybmVsIiwic2VjdGlvbl9zaGEyNTYiOiJhOWQ4OWEyZDJkYjE3MDMzNmJlNGFjZWQ5NTQ1ZDAyOTA3ZTY1OWMyYWY5ODlkMDI5MTA0NGQyMWEyMTUxNjRjIiwic2lnbmF0dXJlX3NoYTI1NiI6ImUzNGZkZjY4MGVmZGIzODgxNWRhYzliZDg5YjY1YzZjOTRjZjdiNzQ0ZmE0YWU1M2Q0MGJiMzAxZTliOTM2NWYifQ -->
### `client.finalize_usage_quota`

Operation ID: `finalizeUsageQuota`  
Route: `POST` `/v1/kernel/usage/finalize`  

#### Signature

```r
finalize_usage_quota <- function(client)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Reservation finalized | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJmaW5hbGl6ZVVzYWdlUXVvdGEifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJyZXNlcnZlX3VzYWdlX3F1b3RhIiwibWV0aG9kIjoiUE9TVCIsIm9wZXJhdGlvbl9pZCI6InJlc2VydmVVc2FnZVF1b3RhIiwicGF0aCI6Ii92MS9rZXJuZWwvdXNhZ2UvcmVzZXJ2ZSIsInJlc291cmNlIjoia2VybmVsIiwic2VjdGlvbl9zaGEyNTYiOiJkNTU3NTU5ZGRkZmMwZGVjODY1NDkxNDRmZjE4YWQ3YzQ4NjhhYjM3YmFmYjI5ODRlOWQ5MGE4NDU5OGFlNDA5Iiwic2lnbmF0dXJlX3NoYTI1NiI6ImU0M2Y2NmJhOTdiMzZjNzIxMzUxNDQxZGI5YjJkN2ExZGMzNDQ5YmE0MTI5YzgzOWE2NWM2ZGUxOTNhODQxMWYifQ -->
### `client.reserve_usage_quota`

Operation ID: `reserveUsageQuota`  
Route: `POST` `/v1/kernel/usage/reserve`  

#### Signature

```r
reserve_usage_quota <- function(client)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Reservation lease created | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJyZXNlcnZlVXNhZ2VRdW90YSJ9 -->

## Resource `user`

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRfY3VycmVudF91c2VyIiwibWV0aG9kIjoiR0VUIiwib3BlcmF0aW9uX2lkIjoiZ2V0Q3VycmVudFVzZXIiLCJwYXRoIjoiL3VzZXIvbWUiLCJyZXNvdXJjZSI6InVzZXIiLCJzZWN0aW9uX3NoYTI1NiI6IjQ2OTg3NWFkZDEwYzM0MTRjNTk4MWU2Mjc0ZmVkNzQ0NjNkM2NhYzBhYTQxMzVhOTRlMjQyODhhMDBjNzcwNzAiLCJzaWduYXR1cmVfc2hhMjU2IjoiOTQwZmViMmY0MTVmMTQ3NjY3NjM4NGFmZjQxY2I2Yzc4ZDlhZTQzZjFlZTIxZTI3NzJlZDIyZGYxYmQzOTRkMCJ9 -->
### `client.get_current_user`

Operation ID: `getCurrentUser`  
Route: `GET` `/user/me`  

#### Signature

```r
get_current_user <- function(client)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Current user context | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRDdXJyZW50VXNlciJ9 -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJnZXRfc2lnbnVwX3BvbGljeSIsIm1ldGhvZCI6IkdFVCIsIm9wZXJhdGlvbl9pZCI6ImdldFNpZ251cFBvbGljeSIsInBhdGgiOiIvdXNlci9hdXRoL3NpZ251cC1wb2xpY3kiLCJyZXNvdXJjZSI6InVzZXIiLCJzZWN0aW9uX3NoYTI1NiI6IjhiZmFjYjBjNDgxYTViYWExZTQ2NjMxOTI5MDBlMzI0NjU5MDE2N2VhZWQ4NjMyMDA0OGY2YTdmZWExMjdiYTEiLCJzaWduYXR1cmVfc2hhMjU2IjoiYWM2ODg4NTkxMTVhYTBiMmJjNzc5YThlY2IyMzU2NmQ1ZGE3YmY0MmVkZWMyZjA4N2RiZWM3MWQ2MDg1ZjcwYyJ9 -->
### `client.get_signup_policy`

Operation ID: `getSignupPolicy`  
Route: `GET` `/user/auth/signup-policy`  

#### Signature

```r
get_signup_policy <- function(client)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Current signup policy | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJnZXRTaWdudXBQb2xpY3kifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJsb2dpbl91c2VyIiwibWV0aG9kIjoiUE9TVCIsIm9wZXJhdGlvbl9pZCI6ImxvZ2luVXNlciIsInBhdGgiOiIvdXNlci9hdXRoL2xvZ2luIiwicmVzb3VyY2UiOiJ1c2VyIiwic2VjdGlvbl9zaGEyNTYiOiJlZmY0YWNjMGFjYjdlMGQ2YWYwNDIxYjU3ZWI5MTA5NTM1ZDc2MGYwMTA3MjI2ZTZjYjc1ODc1ZjFiMjkzZjM4Iiwic2lnbmF0dXJlX3NoYTI1NiI6IjBhOTA1NTEwZGQyNmY1NGFlZWRjMjhhNTQ5ZmVhYTI2NDQ3ZDFlNDhkZGUxOTQ5YWZmYjk0ZTc2ZmMxYTdlNTcifQ -->
### `client.login_user`

Operation ID: `loginUser`  
Route: `POST` `/user/auth/login`  

#### Signature

```r
login_user <- function(client)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `200` | Authenticated session or MFA challenge | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJsb2dpblVzZXIifQ -->

<!-- omniwrap-api-operation eyJleGFtcGxlX3JlYXNvbiI6Imxhbmd1YWdlLWV4YW1wbGUtbm90LWdlbmVyYXRlZCIsImV4YW1wbGVfc3RhdHVzIjoidW5zdXBwb3J0ZWQiLCJtZW1iZXIiOiJzdWJtaXRfd2FpdGxpc3RfcmVxdWVzdCIsIm1ldGhvZCI6IlBPU1QiLCJvcGVyYXRpb25faWQiOiJzdWJtaXRXYWl0bGlzdFJlcXVlc3QiLCJwYXRoIjoiL3VzZXIvYXV0aC93YWl0bGlzdCIsInJlc291cmNlIjoidXNlciIsInNlY3Rpb25fc2hhMjU2IjoiNTljYTgzMTRkMDdlODBjOTAzM2RjMmIxNDQ4OTY3NGM5NTVjZjMwNGFkZDI1ZDBmNGRhZmNkN2FhM2M1Y2Y1MCIsInNpZ25hdHVyZV9zaGEyNTYiOiI1MGQ1NzM3OGM1MmRiNmM2NTE0MTQ1Yzc3MDI1NTllYTg0MDk4ODBjZjExY2Q1ZGMwNjc3MzM3MjZmZmFlNWUwIn0 -->
### `client.submit_waitlist_request`

Operation ID: `submitWaitlistRequest`  
Route: `POST` `/user/auth/waitlist`  

#### Signature

```r
submit_waitlist_request <- function(client)
```

#### Parameters

| Name | In | Required | Contract type | Description |
| --- | --- | --- | --- | --- |
| _none_ | | | | |

#### Responses

| Status | Description | Content |
| --- | --- | --- |
| `202` | Waitlist request recorded with an opaque WL- reference | none |

#### Canonical required-input example

```json
{
  "parameters": []
}
```

#### SDK call example

Example status: `unsupported`  
Unsupported reason: `language-example-not-generated`

<!-- omniwrap-api-operation-end eyJvcGVyYXRpb25faWQiOiJzdWJtaXRXYWl0bGlzdFJlcXVlc3QifQ -->

