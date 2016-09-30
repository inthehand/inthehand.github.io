# StorageFile.MoveAsync Method (IStorageFolder, String)
 _**\[This is preliminary documentation and is subject to change.\]**_

Moves the current file to the specified folder and renames the file according to the desired name.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public IAsyncAction MoveAsync(
	IStorageFolder destinationFolder,
	string desiredNewName
)
```

**VB**<br />
``` VB
Public Function MoveAsync ( 
	destinationFolder As IStorageFolder,
	desiredNewName As String
) As IAsyncAction
```


#### Parameters
&nbsp;<dl><dt>destinationFolder</dt><dd>Type: <a href="T_Windows_Storage_IStorageFolder">Windows.Storage.IStorageFolder</a><br />The destination folder where the file is moved.</dd><dt>desiredNewName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The desired name of the file after it is moved.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncAction">IAsyncAction</a><br />\[Missing <returns> documentation for "M:Windows.Storage.StorageFile.MoveAsync(Windows.Storage.IStorageFolder,System.String)"\]

#### Implements
<a href="M_Windows_Storage_IStorageFile_MoveAsync_1">IStorageFile.MoveAsync(IStorageFolder, String)</a><br />

## See Also


#### Reference
<a href="T_Windows_Storage_StorageFile">StorageFile Class</a><br /><a href="Overload_Windows_Storage_StorageFile_MoveAsync">MoveAsync Overload</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />