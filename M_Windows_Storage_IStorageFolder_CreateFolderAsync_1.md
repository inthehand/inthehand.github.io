# IStorageFolder.CreateFolderAsync Method (String, CreationCollisionOption)
 _**\[This is preliminary documentation and is subject to change.\]**_

Creates a new folder in the current folder, and specifies what to do if a folder with the same name already exists in the current folder.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
IAsyncOperation<StorageFolder> CreateFolderAsync(
	string desiredName,
	CreationCollisionOption options
)
```

**VB**<br />
``` VB
Function CreateFolderAsync ( 
	desiredName As String,
	options As CreationCollisionOption
) As IAsyncOperation(Of StorageFolder)
```


#### Parameters
&nbsp;<dl><dt>desiredName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The desired name of the folder to create. If there is an existing folder in the current folder that already has the specified desiredName, the specified CreationCollisionOption determines how Windows responds to the conflict.</dd><dt>options</dt><dd>Type: <a href="T_Windows_Storage_CreationCollisionOption">Windows.Storage.CreationCollisionOption</a><br />The enum value that determines how Windows responds if the desiredName is the same as the name of an existing folder in the current folder.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="T_Windows_Storage_StorageFolder">StorageFolder</a>)<br />When this method completes, it returns the new folder as a StorageFolder.

## See Also


#### Reference
<a href="T_Windows_Storage_IStorageFolder">IStorageFolder Interface</a><br /><a href="Overload_Windows_Storage_IStorageFolder_CreateFolderAsync">CreateFolderAsync Overload</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />