# DataTransferManager.TargetApplicationChosen Event
 _**\[This is preliminary documentation and is subject to change.\]**_

Occurs when the user chooses a target app in a Share operation.

**Namespace:**&nbsp;<a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public event EventHandler<TargetApplicationChosenEventArgs> TargetApplicationChosen
```

**VB**<br />
``` VB
Public Event TargetApplicationChosen As EventHandler(Of TargetApplicationChosenEventArgs)
```


#### Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/db0etb8x" target="_blank">System.EventHandler</a>(<a href="T_Windows_ApplicationModel_DataTransfer_TargetApplicationChosenEventArgs">TargetApplicationChosenEventArgs</a>)

## Remarks
When the user chooses a target app to share content with, the system fires a TargetApplicationChosen event. The app receiving the event can use this event to record information about the target app for business intelligence. A common use of this event is to record which applications are used to complete different sharing actions, which in turn can help the source app create better experiences for the user.

## See Also


#### Reference
<a href="T_Windows_ApplicationModel_DataTransfer_DataTransferManager">DataTransferManager Class</a><br /><a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer Namespace</a><br />