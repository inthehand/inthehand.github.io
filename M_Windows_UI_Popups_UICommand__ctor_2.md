# UICommand Constructor (String, UICommandInvokedHandler, Object)
 _**\[This is preliminary documentation and is subject to change.\]**_

Initializes a new instance of the UICommand class, using the specified label, event handler, and command identifier.

**Namespace:**&nbsp;<a href="N_Windows_UI_Popups">Windows.UI.Popups</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public UICommand(
	string label,
	UICommandInvokedHandler action,
	Object commandId
)
```

**VB**<br />
``` VB
Public Sub New ( 
	label As String,
	action As UICommandInvokedHandler,
	commandId As Object
)
```


#### Parameters
&nbsp;<dl><dt>label</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The label for the new command.</dd><dt>action</dt><dd>Type: <a href="T_Windows_UI_Popups_UICommandInvokedHandler">Windows.UI.Popups.UICommandInvokedHandler</a><br />The event handler for the new command.</dd><dt>commandId</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />The command identifier for the new command.</dd></dl>

## See Also


#### Reference
<a href="T_Windows_UI_Popups_UICommand">UICommand Class</a><br /><a href="Overload_Windows_UI_Popups_UICommand__ctor">UICommand Overload</a><br /><a href="N_Windows_UI_Popups">Windows.UI.Popups Namespace</a><br />