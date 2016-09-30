# DataTransferManager.DataRequested Event
 _**\[This is preliminary documentation and is subject to change.\]**_

Occurs when a share operation starts.

**Namespace:**&nbsp;<a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public event EventHandler<DataRequestedEventArgs> DataRequested
```

**VB**<br />
``` VB
Public Event DataRequested As EventHandler(Of DataRequestedEventArgs)
```


#### Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/db0etb8x" target="_blank">System.EventHandler</a>(<a href="T_Windows_ApplicationModel_DataTransfer_DataRequestedEventArgs">DataRequestedEventArgs</a>)

## Remarks
This event is fired when a sharing operation starts. To handle this event, you need to add an event listener to the <a href="T_Windows_ApplicationModel_DataTransfer_DataTransferManager">DataTransferManager</a> object for the active window. You can get this object through the <a href="M_Windows_ApplicationModel_DataTransfer_DataTransferManager_GetForCurrentView">GetForCurrentView()</a> method. 
When handling a datarequested event, the most important property you need to be aware of is its request property. This property contains a <a href="T_Windows_ApplicationModel_DataTransfer_DataRequest">DataRequest</a> object. Your app uses this object to provide the data that the user wants to share with a selected target app.


## See Also


#### Reference
<a href="T_Windows_ApplicationModel_DataTransfer_DataTransferManager">DataTransferManager Class</a><br /><a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer Namespace</a><br />