# DataPackage.SetWebLink Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Sets the web link that a <a href="T_Windows_ApplicationModel_DataTransfer_DataPackage">DataPackage</a> contains.

**Namespace:**&nbsp;<a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public void SetWebLink(
	Uri value
)
```

**VB**<br />
``` VB
Public Sub SetWebLink ( 
	value As Uri
)
```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/txt7706a" target="_blank">System.Uri</a><br />A URI with an http or https scheme that corresponds to the content being displayed to the user.</dd></dl>

## Remarks
Whenever possible, you should set this property. A source app provides a value for this property, and a target app reads the value. Use this property to indicate the source of the shared content.

## See Also


#### Reference
<a href="T_Windows_ApplicationModel_DataTransfer_DataPackage">DataPackage Class</a><br /><a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer Namespace</a><br />