# MessageDialog.ShowAsync Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Begins an asynchronous operation showing a dialog.

**Namespace:**&nbsp;<a href="N_Windows_UI_Popups">Windows.UI.Popups</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public IAsyncOperation<IUICommand> ShowAsync()
```

**VB**<br />
``` VB
Public Function ShowAsync As IAsyncOperation(Of IUICommand)
```


#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="T_Windows_UI_Popups_IUICommand">IUICommand</a>)<br />An object that represents the asynchronous operation. For more on the async pattern, see Asynchronous programming in the Windows Runtime.

## Remarks
In some cases, such as when the dialog is closed by the system out of your control, your result can be an empty command. <a href="M_Windows_Foundation_IAsyncOperation_1_GetResults">GetResults()</a> returns either the command selected which destroyed the dialog, or an empty command. For example, a dialog hosted in a charms window will return an empty command if the charms window has been dismissed.

## See Also


#### Reference
<a href="T_Windows_UI_Popups_MessageDialog">MessageDialog Class</a><br /><a href="N_Windows_UI_Popups">Windows.UI.Popups Namespace</a><br />