# PopupMenu.ShowAsync Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Shows the context menu at the specified client coordinates.

**Namespace:**&nbsp;<a href="N_Windows_UI_Popups">Windows.UI.Popups</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public IAsyncOperation<IUICommand> ShowAsync(
	Point invocationPoint
)
```

**VB**<br />
``` VB
Public Function ShowAsync ( 
	invocationPoint As Point
) As IAsyncOperation(Of IUICommand)
```


#### Parameters
&nbsp;<dl><dt>invocationPoint</dt><dd>Type: <a href="T_Windows_Foundation_Point">Windows.Foundation.Point</a><br />The coordinates (in DIPs), relative to the window, of the user's finger or mouse pointer when the oncontextmenu event fired. The menu is placed above and centered on this point.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="T_Windows_UI_Popups_IUICommand">IUICommand</a>)<br />An object that represents the asynchronous operation. For more on the async pattern, see Asynchronous programming in the Windows Runtime.

## See Also


#### Reference
<a href="T_Windows_UI_Popups_PopupMenu">PopupMenu Class</a><br /><a href="N_Windows_UI_Popups">Windows.UI.Popups Namespace</a><br />