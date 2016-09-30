# MessageDialog.Title Property 
 _**\[This is preliminary documentation and is subject to change.\]**_

Gets or sets the title to display on the dialog box, if any.

**Namespace:**&nbsp;<a href="N_Windows_UI_Popups">Windows.UI.Popups</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public string Title { get; set; }
```

**VB**<br />
``` VB
Public Property Title As String
	Get
	Set
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a><br />The title you want to display on the dialog. If the title is not set, this will return an empty string.

## Remarks
Use the title as a concise main instruction to convey the objective of the dialog. 
Long titles do not wrap and will be truncated.

If you're using the dialog to deliver a simple message, error or question, omit the title. Rely on the <a href="P_Windows_UI_Popups_MessageDialog_Content">Content</a> to deliver that core information.


## See Also


#### Reference
<a href="T_Windows_UI_Popups_MessageDialog">MessageDialog Class</a><br /><a href="N_Windows_UI_Popups">Windows.UI.Popups Namespace</a><br />