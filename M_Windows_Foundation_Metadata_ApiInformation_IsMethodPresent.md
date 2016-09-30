# ApiInformation.IsMethodPresent Method (String, String)
 _**\[This is preliminary documentation and is subject to change.\]**_

Returns true or false to indicate whether a specified method is present for a specified type.

**Namespace:**&nbsp;<a href="N_Windows_Foundation_Metadata">Windows.Foundation.Metadata</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static bool IsMethodPresent(
	string typeName,
	string methodName
)
```

**VB**<br />
``` VB
Public Shared Function IsMethodPresent ( 
	typeName As String,
	methodName As String
) As Boolean
```


#### Parameters
&nbsp;<dl><dt>typeName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The namespace-qualified name of the type.</dd><dt>methodName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The name of the method.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />True if the specified method is present for the type; otherwise, false.

## See Also


#### Reference
<a href="T_Windows_Foundation_Metadata_ApiInformation">ApiInformation Class</a><br /><a href="Overload_Windows_Foundation_Metadata_ApiInformation_IsMethodPresent">IsMethodPresent Overload</a><br /><a href="N_Windows_Foundation_Metadata">Windows.Foundation.Metadata Namespace</a><br />