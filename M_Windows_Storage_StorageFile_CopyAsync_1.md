# StorageFile.CopyAsync Method (IStorageFolder, String)
 _**\[This is preliminary documentation and is subject to change.\]**_

Creates a copy of the file in the specified folder and renames the copy.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public IAsyncOperation<StorageFile> CopyAsync(
	IStorageFolder destinationFolder,
	string desiredNewName
)
```

**VB**<br />
``` VB
Public Function CopyAsync ( 
	destinationFolder As IStorageFolder,
	desiredNewName As String
) As IAsyncOperation(Of StorageFile)
```


#### Parameters
&nbsp;<dl><dt>destinationFolder</dt><dd>Type: <a href="T_Windows_Storage_IStorageFolder">Windows.Storage.IStorageFolder</a><br />The destination folder where the copy of the file is created.</dd><dt>desiredNewName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The new name for the copy of the file created in the destinationFolder.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="T_Windows_Storage_StorageFile">StorageFile</a>)<br />\[Missing <returns> documentation for "M:Windows.Storage.StorageFile.CopyAsync(Windows.Storage.IStorageFolder,System.String)"\]

#### Implements
<a href="M_Windows_Storage_IStorageFile_CopyAsync_1">IStorageFile.CopyAsync(IStorageFolder, String)</a><br />

## See Also


#### Reference
<a href="T_Windows_Storage_StorageFile">StorageFile Class</a><br /><a href="Overload_Windows_Storage_StorageFile_CopyAsync">CopyAsync Overload</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />