# PackageVersionExtensions.ToString Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Converts the value of the current Version object to its equivalent String representation. A specified count indicates the number of components to return.

**Namespace:**&nbsp;<a href="N_InTheHand_ApplicationModel">InTheHand.ApplicationModel</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static string ToString(
	this PackageVersion packageVersion,
	int fieldCount
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function ToString ( 
	packageVersion As PackageVersion,
	fieldCount As Integer
) As String
```


#### Parameters
&nbsp;<dl><dt>packageVersion</dt><dd>Type: <a href="T_Windows_ApplicationModel_PackageVersion">Windows.ApplicationModel.PackageVersion</a><br /></dd><dt>fieldCount</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />The number of components to return. The fieldCount ranges from 0 to 4.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a><br />The String representation of the values of the major, minor, build, and revision components of the current Version object, each separated by a period character ('.'). The fieldCount parameter determines how many components are returned.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="T_Windows_ApplicationModel_PackageVersion">PackageVersion</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="http://msdn.microsoft.com/en-us/library/bb384936.aspx">Extension Methods (Visual Basic)</a> or <a href="http://msdn.microsoft.com/en-us/library/bb383977.aspx">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_InTheHand_ApplicationModel_PackageVersionExtensions">PackageVersionExtensions Class</a><br /><a href="N_InTheHand_ApplicationModel">InTheHand.ApplicationModel Namespace</a><br />