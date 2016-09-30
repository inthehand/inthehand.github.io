# DataPackage.SetDataProvider Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Sets a delegate to handle requests from the target app.

**Namespace:**&nbsp;<a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public void SetDataProvider(
	string formatId,
	DataProviderHandler delayRenderer
)
```

**VB**<br />
``` VB
Public Sub SetDataProvider ( 
	formatId As String,
	delayRenderer As DataProviderHandler
)
```


#### Parameters
&nbsp;<dl><dt>formatId</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Specifies the format of the data. We recommend that you set this value by using the StandardDataFormats class.</dd><dt>delayRenderer</dt><dd>Type: <a href="T_Windows_ApplicationModel_DataTransfer_DataProviderHandler">Windows.ApplicationModel.DataTransfer.DataProviderHandler</a><br />A delegate that is responsible for processing requests from a target app.</dd></dl>

## See Also


#### Reference
<a href="T_Windows_ApplicationModel_DataTransfer_DataPackage">DataPackage Class</a><br /><a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer Namespace</a><br />