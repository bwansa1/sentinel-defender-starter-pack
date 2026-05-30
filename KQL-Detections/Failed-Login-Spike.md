SigninLogs
| where ResultType != 0
| summarize FailedAttempts=count() by UserPrincipalName, IPAddress, bin(TimeGenerated, 15m)
| where FailedAttempts >= 10
| order by FailedAttempts desc