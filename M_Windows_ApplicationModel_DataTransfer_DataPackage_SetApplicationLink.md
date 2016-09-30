# DataPackage.SetApplicationLink Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Sets the application link that a <a href="T_Windows_ApplicationModel_DataTransfer_DataPackage">DataPackage</a> contains.

**Namespace:**&nbsp;<a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public void SetApplicationLink(
	Uri value
)
```

**VB**<br />
``` VB
Public Sub SetApplicationLink ( 
	value As Uri
)
```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/txt7706a" target="_blank">System.Uri</a><br />A URI with a scheme that isn't http or https that's handled by the source app.</dd></dl>

## Remarks
Whenever possible, you should set this property. This URI represents a deep link that takes the user back to the currently displayed content. A source app provides a value for this property, and a target app reads the value. Use this property to indicate the source of the shared content. 
The scheme of this URI must not be http or https. The app sharing this URI must be capable of being the default handler, although it may not be set as the default handler.


## See Also


#### Reference
<a href="T_Windows_ApplicationModel_DataTransfer_DataPackage">DataPackage Class</a><br /><a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer Namespace</a><br />