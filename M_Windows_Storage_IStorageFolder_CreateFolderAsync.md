# IStorageFolder.CreateFolderAsync Method (String)
 _**\[This is preliminary documentation and is subject to change.\]**_

Creates a new folder in the current folder.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
IAsyncOperation<StorageFolder> CreateFolderAsync(
	string desiredName
)
```

**VB**<br />
``` VB
Function CreateFolderAsync ( 
	desiredName As String
) As IAsyncOperation(Of StorageFolder)
```


#### Parameters
&nbsp;<dl><dt>desiredName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The desired name of the folder to create.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="T_Windows_Storage_StorageFolder">StorageFolder</a>)<br />When this method completes, it returns the new folder as a StorageFolder.

## See Also


#### Reference
<a href="T_Windows_Storage_IStorageFolder">IStorageFolder Interface</a><br /><a href="Overload_Windows_Storage_IStorageFolder_CreateFolderAsync">CreateFolderAsync Overload</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />