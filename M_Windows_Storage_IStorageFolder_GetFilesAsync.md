# IStorageFolder.GetFilesAsync Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Gets the files from the current folder.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
IAsyncOperation<IReadOnlyList<StorageFile>> GetFilesAsync()
```

**VB**<br />
``` VB
Function GetFilesAsync As IAsyncOperation(Of IReadOnlyList(Of StorageFile))
```


#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="http://msdn2.microsoft.com/en-us/library/hh192385" target="_blank">IReadOnlyList</a>(<a href="T_Windows_Storage_StorageFile">StorageFile</a>))<br />When this method completes successfully, it returns a list of the files (type IVectorView) in the folder. Each file in the list is represented by a StorageFile object.

## See Also


#### Reference
<a href="T_Windows_Storage_IStorageFolder">IStorageFolder Interface</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />