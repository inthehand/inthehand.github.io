# ApiInformation.IsWriteablePropertyPresent Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Returns true or false to indicate whether a specified writeable property is present for a specified type.

**Namespace:**&nbsp;<a href="N_Windows_Foundation_Metadata">Windows.Foundation.Metadata</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static bool IsWriteablePropertyPresent(
	string typeName,
	string propertyName
)
```

**VB**<br />
``` VB
Public Shared Function IsWriteablePropertyPresent ( 
	typeName As String,
	propertyName As String
) As Boolean
```


#### Parameters
&nbsp;<dl><dt>typeName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The namespace-qualified name of the type.</dd><dt>propertyName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The name of the property.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />True if the specified property is present for the type; otherwise, false.

## See Also


#### Reference
<a href="T_Windows_Foundation_Metadata_ApiInformation">ApiInformation Class</a><br /><a href="N_Windows_Foundation_Metadata">Windows.Foundation.Metadata Namespace</a><br />