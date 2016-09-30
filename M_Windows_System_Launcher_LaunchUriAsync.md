# Launcher.LaunchUriAsync Method (Uri)
 _**\[This is preliminary documentation and is subject to change.\]**_

Starts the default app associated with the URI scheme name for the specified URI.

**Namespace:**&nbsp;<a href="N_Windows_System">Windows.System</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static IAsyncOperation<bool> LaunchUriAsync(
	Uri uri
)
```

**VB**<br />
``` VB
Public Shared Function LaunchUriAsync ( 
	uri As Uri
) As IAsyncOperation(Of Boolean)
```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/txt7706a" target="_blank">System.Uri</a><br />The URI.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a>)<br />The launch operation.

## See Also


#### Reference
<a href="T_Windows_System_Launcher">Launcher Class</a><br /><a href="Overload_Windows_System_Launcher_LaunchUriAsync">LaunchUriAsync Overload</a><br /><a href="N_Windows_System">Windows.System Namespace</a><br />