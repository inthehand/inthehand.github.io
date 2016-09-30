# PathIO.WriteLinesAsync Method (String, IEnumerable(String))
 _**\[This is preliminary documentation and is subject to change.\]**_

Writes lines of text to the file at the specified path or URI.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static IAsyncAction WriteLinesAsync(
	string absolutePath,
	IEnumerable<string> lines
)
```

**VB**<br />
``` VB
Public Shared Function WriteLinesAsync ( 
	absolutePath As String,
	lines As IEnumerable(Of String)
) As IAsyncAction
```


#### Parameters
&nbsp;<dl><dt>absolutePath</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The path of the file that the lines are written to.</dd><dt>lines</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/9eekhta0" target="_blank">System.Collections.Generic.IEnumerable</a>(<a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>)<br />The list of text strings to append as lines.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncAction">IAsyncAction</a><br />No object or value is returned when this method completes.

## See Also


#### Reference
<a href="T_Windows_Storage_PathIO">PathIO Class</a><br /><a href="Overload_Windows_Storage_PathIO_WriteLinesAsync">WriteLinesAsync Overload</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />