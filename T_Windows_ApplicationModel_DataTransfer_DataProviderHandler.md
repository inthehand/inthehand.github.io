# DataProviderHandler Delegate
 _**\[This is preliminary documentation and is subject to change.\]**_

Provides data when the target app requests it, instead of including the data in the DataPackage ahead of time. DataProviderHandler is used when the source app wants to avoid unnecessary work that is resource intensive, such as performing format conversions.

**Namespace:**&nbsp;<a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public delegate void DataProviderHandler(
	DataProviderRequest request
)
```

**VB**<br />
``` VB
Public Delegate Sub DataProviderHandler ( 
	request As DataProviderRequest
)
```


#### Parameters
&nbsp;<dl><dt>request</dt><dd>Type: <a href="T_Windows_ApplicationModel_DataTransfer_DataProviderRequest">Windows.ApplicationModel.DataTransfer.DataProviderRequest</a><br />Contains the data that the user wants to share.</dd></dl>

## See Also


#### Reference
<a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer Namespace</a><br />