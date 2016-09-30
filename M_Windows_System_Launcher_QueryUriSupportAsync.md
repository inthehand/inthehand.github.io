# Launcher.QueryUriSupportAsync Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Asynchronously query whether an app can be activated for the specified URI and launch type.

**Namespace:**&nbsp;<a href="N_Windows_System">Windows.System</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static IAsyncOperation<LaunchQuerySupportStatus> QueryUriSupportAsync(
	Uri uri,
	LaunchQuerySupportType launchQuerySupportType
)
```

**VB**<br />
``` VB
Public Shared Function QueryUriSupportAsync ( 
	uri As Uri,
	launchQuerySupportType As LaunchQuerySupportType
) As IAsyncOperation(Of LaunchQuerySupportStatus)
```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/txt7706a" target="_blank">System.Uri</a><br />The URI.</dd><dt>launchQuerySupportType</dt><dd>Type: <a href="T_Windows_System_LaunchQuerySupportType">Windows.System.LaunchQuerySupportType</a><br />\[Missing <param name="launchQuerySupportType"/> documentation for "M:Windows.System.Launcher.QueryUriSupportAsync(System.Uri,Windows.System.LaunchQuerySupportType)"\]</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="T_Windows_System_LaunchQuerySupportStatus">LaunchQuerySupportStatus</a>)<br />Returns true if the default app for the URI scheme was launched; false otherwise.

## See Also


#### Reference
<a href="T_Windows_System_Launcher">Launcher Class</a><br /><a href="N_Windows_System">Windows.System Namespace</a><br />