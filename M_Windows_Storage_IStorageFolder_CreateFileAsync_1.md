# IStorageFolder.CreateFileAsync Method (String, CreationCollisionOption)
 _**\[This is preliminary documentation and is subject to change.\]**_

Creates a new file in the current folder, and specifies what to do if a file with the same name already exists in the current folder.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
IAsyncOperation<StorageFile> CreateFileAsync(
	string desiredName,
	CreationCollisionOption options
)
```

**VB**<br />
``` VB
Function CreateFileAsync ( 
	desiredName As String,
	options As CreationCollisionOption
) As IAsyncOperation(Of StorageFile)
```


#### Parameters
&nbsp;<dl><dt>desiredName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The desired name of the file to create. If there is an existing file in the current folder that already has the specified desiredName, the specified CreationCollisionOption determines how Windows responds to the conflict.</dd><dt>options</dt><dd>Type: <a href="T_Windows_Storage_CreationCollisionOption">Windows.Storage.CreationCollisionOption</a><br />The enum value that determines how Windows responds if the desiredName is the same as the name of an existing file in the current folder.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="T_Windows_Storage_StorageFile">StorageFile</a>)<br />When this method completes, it returns the new file as a StorageFile.

## See Also


#### Reference
<a href="T_Windows_Storage_IStorageFolder">IStorageFolder Interface</a><br /><a href="Overload_Windows_Storage_IStorageFolder_CreateFileAsync">CreateFileAsync Overload</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />