---
title: MySqlServerRedirectionMode
---

# MySqlServerRedirectionMode enumeration

Server redirection configuration.

```csharp
public enum MySqlServerRedirectionMode
```

## Values

| name | value | description |
| --- | --- | --- |
| Disabled | `0` | Server redirection will not be performed. |
| Preferred | `1` | Server redirection will occur if possible, otherwise the original connection will be used. |
| Required | `2` | Server redirection must occur, otherwise connecting fails. |

## See Also

* namespace [MySqlConnector](../../MySqlConnectorNamespace/)
* assembly [MySqlConnector](../../MySqlConnectorAssembly/)

<!-- DO NOT EDIT: generated by xmldocmd for MySqlConnector.dll -->