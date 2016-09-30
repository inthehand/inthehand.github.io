# PopupMenu.ShowForSelectionAsync Method (Rect)
 _**\[This is preliminary documentation and is subject to change.\]**_

Shows the context menu by the specified selection.

**Namespace:**&nbsp;<a href="N_Windows_UI_Popups">Windows.UI.Popups</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public IAsyncOperation<IUICommand> ShowForSelectionAsync(
	Rect selection
)
```

**VB**<br />
``` VB
Public Function ShowForSelectionAsync ( 
	selection As Rect
) As IAsyncOperation(Of IUICommand)
```


#### Parameters
&nbsp;<dl><dt>selection</dt><dd>Type: <a href="T_Windows_Foundation_Rect">Windows.Foundation.Rect</a><br />The coordinates (in DIPs) of the selected rectangle, relative to the window.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="T_Windows_UI_Popups_IUICommand">IUICommand</a>)<br />\[Missing <returns> documentation for "M:Windows.UI.Popups.PopupMenu.ShowForSelectionAsync(Windows.Foundation.Rect)"\]

## See Also


#### Reference
<a href="T_Windows_UI_Popups_PopupMenu">PopupMenu Class</a><br /><a href="Overload_Windows_UI_Popups_PopupMenu_ShowForSelectionAsync">ShowForSelectionAsync Overload</a><br /><a href="N_Windows_UI_Popups">Windows.UI.Popups Namespace</a><br />