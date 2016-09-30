# StorageFolder.TryGetItemAsync Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Try to get a single file or sub-folder from the current folder by using the name of the item.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public IAsyncOperation<IStorageItem> TryGetItemAsync(
	string name
)
```

**VB**<br />
``` VB
Public Function TryGetItemAsync ( 
	name As String
) As IAsyncOperation(Of IStorageItem)
```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The name (or path relative to the current folder) of the file or sub-folder to try to retrieve.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="T_Windows_Storage_IStorageItem">IStorageItem</a>)<br />When this method completes successfully, it returns the file or folder (type IStorageItem).

## See Also


#### Reference
<a href="T_Windows_Storage_StorageFolder">StorageFolder Class</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />