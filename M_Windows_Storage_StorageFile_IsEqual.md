# StorageFile.IsEqual Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Indicates whether the current file is equal to the specified file.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public bool IsEqual(
	IStorageItem item
)
```

**VB**<br />
``` VB
Public Function IsEqual ( 
	item As IStorageItem
) As Boolean
```


#### Parameters
&nbsp;<dl><dt>item</dt><dd>Type: <a href="T_Windows_Storage_IStorageItem">Windows.Storage.IStorageItem</a><br />The <a href="T_Windows_Storage_IStorageItem">IStorageItem</a> object that represents a file to compare against.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />Returns true if the current file is equal to the specified file; otherwise false.

#### Implements
<a href="M_Windows_Storage_IStorageItem2_IsEqual">IStorageItem2.IsEqual(IStorageItem)</a><br />

## See Also


#### Reference
<a href="T_Windows_Storage_StorageFile">StorageFile Class</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />