# DataPackage.SetData Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Sets the data contained in the DataPackage.

**Namespace:**&nbsp;<a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public void SetData(
	string formatId,
	Object value
)
```

**VB**<br />
``` VB
Public Sub SetData ( 
	formatId As String,
	value As Object
)
```


#### Parameters
&nbsp;<dl><dt>formatId</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Specifies the format of the data. We recommend that you set this value by using the StandardDataFormats class.</dd><dt>value</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />Specifies the content that the DataPackage contains.</dd></dl>

## See Also


#### Reference
<a href="T_Windows_ApplicationModel_DataTransfer_DataPackage">DataPackage Class</a><br /><a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer Namespace</a><br />