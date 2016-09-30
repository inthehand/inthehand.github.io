# MessageDialog.Commands Property 
 _**\[This is preliminary documentation and is subject to change.\]**_

Gets the set of commands that appear in the command bar of the message dialog.

**Namespace:**&nbsp;<a href="N_Windows_UI_Popups">Windows.UI.Popups</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public IList<IUICommand> Commands { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Commands As IList(Of IUICommand)
	Get
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/5y536ey6" target="_blank">IList</a>(<a href="T_Windows_UI_Popups_IUICommand">IUICommand</a>)<br />The commands.

## Remarks
This is the array of commands that makes the dialog actionable. Get this array and add your dialog commands to it.

## See Also


#### Reference
<a href="T_Windows_UI_Popups_MessageDialog">MessageDialog Class</a><br /><a href="N_Windows_UI_Popups">Windows.UI.Popups Namespace</a><br />