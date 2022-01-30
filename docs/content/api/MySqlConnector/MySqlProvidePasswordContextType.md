---
title: MySqlProvidePasswordContext
---

# MySqlProvidePasswordContext class

Provides context for the [`ProvidePasswordCallback`](../MySqlConnection/ProvidePasswordCallback/) delegate.

```csharp
public sealed class MySqlProvidePasswordContext
```

## Public Members

| name | description |
| --- | --- |
| [Database](../MySqlProvidePasswordContext/Database/) { get; } | The optional initial database; this value may be the empty string. This corresponds to [`Database`](../MySqlConnectionStringBuilder/Database/). |
| [Port](../MySqlProvidePasswordContext/Port/) { get; } | The server port. This corresponds to [`Port`](../MySqlConnectionStringBuilder/Port/). |
| [Server](../MySqlProvidePasswordContext/Server/) { get; } | The server to which MySqlConnector is connecting. This is a host name from the [`Server`](../MySqlConnectionStringBuilder/Server/) option. |
| [UserId](../MySqlProvidePasswordContext/UserId/) { get; } | The user ID being used for authentication. This corresponds to [`UserID`](../MySqlConnectionStringBuilder/UserID/). |

## See Also

* namespace [MySqlConnector](../../MySqlConnectorNamespace/)
* assembly [MySqlConnector](../../MySqlConnectorAssembly/)

<!-- DO NOT EDIT: generated by xmldocmd for MySqlConnector.dll -->