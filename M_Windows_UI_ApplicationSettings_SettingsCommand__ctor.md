# SettingsCommand Constructor 
 _**\[This is preliminary documentation and is subject to change.\]**_

Creates a new settings command.

**Namespace:**&nbsp;<a href="N_Windows_UI_ApplicationSettings">Windows.UI.ApplicationSettings</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public SettingsCommand(
	Object settingsCommandId,
	string label,
	UICommandInvokedHandler handler
)
```

**VB**<br />
``` VB
Public Sub New ( 
	settingsCommandId As Object,
	label As String,
	handler As UICommandInvokedHandler
)
```


#### Parameters
&nbsp;<dl><dt>settingsCommandId</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />The ID of the command.</dd><dt>label</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The label for the command, which is displayed in the settings pane.</dd><dt>handler</dt><dd>Type: <a href="T_Windows_UI_Popups_UICommandInvokedHandler">Windows.UI.Popups.UICommandInvokedHandler</a><br />The event handler that is called when the user selects this command in the settings pane.</dd></dl>

## See Also


#### Reference
<a href="T_Windows_UI_ApplicationSettings_SettingsCommand">SettingsCommand Class</a><br /><a href="N_Windows_UI_ApplicationSettings">Windows.UI.ApplicationSettings Namespace</a><br />