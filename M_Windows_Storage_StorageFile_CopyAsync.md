# StorageFile.CopyAsync Method (IStorageFolder)
 _**\[This is preliminary documentation and is subject to change.\]**_

Creates a copy of the file in the specified folder.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public IAsyncOperation<StorageFile> CopyAsync(
	IStorageFolder destinationFolder
)
```

**VB**<br />
``` VB
Public Function CopyAsync ( 
	destinationFolder As IStorageFolder
) As IAsyncOperation(Of StorageFile)
```


#### Parameters
&nbsp;<dl><dt>destinationFolder</dt><dd>Type: <a href="T_Windows_Storage_IStorageFolder">Windows.Storage.IStorageFolder</a><br />The destination folder where the copy of the file is created.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="T_Windows_Storage_StorageFile">StorageFile</a>)<br />\[Missing <returns> documentation for "M:Windows.Storage.StorageFile.CopyAsync(Windows.Storage.IStorageFolder)"\]

#### Implements
<a href="M_Windows_Storage_IStorageFile_CopyAsync">IStorageFile.CopyAsync(IStorageFolder)</a><br />

## See Also


#### Reference
<a href="T_Windows_Storage_StorageFile">StorageFile Class</a><br /><a href="Overload_Windows_Storage_StorageFile_CopyAsync">CopyAsync Overload</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />