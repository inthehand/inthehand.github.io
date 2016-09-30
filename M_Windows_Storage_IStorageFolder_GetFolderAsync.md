# IStorageFolder.GetFolderAsync Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Gets the specified folder from the current folder.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
IAsyncOperation<StorageFolder> GetFolderAsync(
	string name
)
```

**VB**<br />
``` VB
Function GetFolderAsync ( 
	name As String
) As IAsyncOperation(Of StorageFolder)
```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The name of the child folder to retrieve.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="T_Windows_Storage_StorageFolder">StorageFolder</a>)<br />When this method completes successfully, it returns a StorageFolder that represents the child folder.

## See Also


#### Reference
<a href="T_Windows_Storage_IStorageFolder">IStorageFolder Interface</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />