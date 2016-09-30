# Clipboard.SetContent Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Sets the current content that is stored in the clipboard object.

**Namespace:**&nbsp;<a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static void SetContent(
	DataPackage content
)
```

**VB**<br />
``` VB
Public Shared Sub SetContent ( 
	content As DataPackage
)
```


#### Parameters
&nbsp;<dl><dt>content</dt><dd>Type: <a href="T_Windows_ApplicationModel_DataTransfer_DataPackage">Windows.ApplicationModel.DataTransfer.DataPackage</a><br />Contains the content of the clipboard. If NULL, the clipboard is emptied.</dd></dl>

## See Also


#### Reference
<a href="T_Windows_ApplicationModel_DataTransfer_Clipboard">Clipboard Class</a><br /><a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer Namespace</a><br />