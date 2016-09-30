# DataPackageView.GetDataAsync Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Gets the data contained in the <a href="T_Windows_ApplicationModel_DataTransfer_DataPackageView">DataPackageView</a>.

**Namespace:**&nbsp;<a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public IAsyncOperation<Object> GetDataAsync(
	string formatId
)
```

**VB**<br />
``` VB
Public Function GetDataAsync ( 
	formatId As String
) As IAsyncOperation(Of Object)
```


#### Parameters
&nbsp;<dl><dt>formatId</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The format of the data.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>)<br />The data.

## See Also


#### Reference
<a href="T_Windows_ApplicationModel_DataTransfer_DataPackageView">DataPackageView Class</a><br /><a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer Namespace</a><br />