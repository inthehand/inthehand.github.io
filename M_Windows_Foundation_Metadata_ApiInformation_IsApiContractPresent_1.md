# ApiInformation.IsApiContractPresent Method (String, UInt16, UInt16)
 _**\[This is preliminary documentation and is subject to change.\]**_

Returns true or false to indicate whether the API contract with the specified name and major and minor version number is present.

**Namespace:**&nbsp;<a href="N_Windows_Foundation_Metadata">Windows.Foundation.Metadata</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static bool IsApiContractPresent(
	string contractName,
	ushort majorVersion,
	ushort minorVersion
)
```

**VB**<br />
``` VB
Public Shared Function IsApiContractPresent ( 
	contractName As String,
	majorVersion As UShort,
	minorVersion As UShort
) As Boolean
```


#### Parameters
&nbsp;<dl><dt>contractName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The name of the API contract.</dd><dt>majorVersion</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s6eyk10z" target="_blank">System.UInt16</a><br />The major version number of the API contract.</dd><dt>minorVersion</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s6eyk10z" target="_blank">System.UInt16</a><br />The minor version number of the API contract.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />True if the specified API contract is present; otherwise, false.

## See Also


#### Reference
<a href="T_Windows_Foundation_Metadata_ApiInformation">ApiInformation Class</a><br /><a href="Overload_Windows_Foundation_Metadata_ApiInformation_IsApiContractPresent">IsApiContractPresent Overload</a><br /><a href="N_Windows_Foundation_Metadata">Windows.Foundation.Metadata Namespace</a><br />