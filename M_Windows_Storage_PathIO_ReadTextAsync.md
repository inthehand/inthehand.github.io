# PathIO.ReadTextAsync Method (String)
 _**\[This is preliminary documentation and is subject to change.\]**_

Reads the contents of the file at the specified path or URI and returns text.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static IAsyncOperation<string> ReadTextAsync(
	string absolutePath
)
```

**VB**<br />
``` VB
Public Shared Function ReadTextAsync ( 
	absolutePath As String
) As IAsyncOperation(Of String)
```


#### Parameters
&nbsp;<dl><dt>absolutePath</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The path of the file to read.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>)<br />When this method completes successfully, it returns the contents of the file as a text string.

## See Also


#### Reference
<a href="T_Windows_Storage_PathIO">PathIO Class</a><br /><a href="Overload_Windows_Storage_PathIO_ReadTextAsync">ReadTextAsync Overload</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />