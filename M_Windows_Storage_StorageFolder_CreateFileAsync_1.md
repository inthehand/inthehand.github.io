# StorageFolder.CreateFileAsync Method (String, CreationCollisionOption)
 _**\[This is preliminary documentation and is subject to change.\]**_

Creates a new file with the specified name in the current folder.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public IAsyncOperation<StorageFile> CreateFileAsync(
	string desiredName,
	CreationCollisionOption options
)
```

**VB**<br />
``` VB
Public Function CreateFileAsync ( 
	desiredName As String,
	options As CreationCollisionOption
) As IAsyncOperation(Of StorageFile)
```


#### Parameters
&nbsp;<dl><dt>desiredName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The name of the new file to create in the current folder.</dd><dt>options</dt><dd>Type: <a href="T_Windows_Storage_CreationCollisionOption">Windows.Storage.CreationCollisionOption</a><br />One of the enumeration values that determines how to handle the collision if a file with the specified desiredName already exists in the current folder.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="T_Windows_Storage_StorageFile">StorageFile</a>)<br />When this method completes, it returns a StorageFile that represents the new file.

#### Implements
<a href="M_Windows_Storage_IStorageFolder_CreateFileAsync_1">IStorageFolder.CreateFileAsync(String, CreationCollisionOption)</a><br />

## See Also


#### Reference
<a href="T_Windows_Storage_StorageFolder">StorageFolder Class</a><br /><a href="Overload_Windows_Storage_StorageFolder_CreateFileAsync">CreateFileAsync Overload</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />