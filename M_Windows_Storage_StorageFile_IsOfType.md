# StorageFile.IsOfType Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Determines whether the current <a href="T_Windows_Storage_StorageFile">StorageFile</a> matches the specified <a href="T_Windows_Storage_StorageItemTypes">StorageItemTypes</a> value.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public bool IsOfType(
	StorageItemTypes type
)
```

**VB**<br />
``` VB
Public Function IsOfType ( 
	type As StorageItemTypes
) As Boolean
```


#### Parameters
&nbsp;<dl><dt>type</dt><dd>Type: <a href="T_Windows_Storage_StorageItemTypes">Windows.Storage.StorageItemTypes</a><br />The value to match against.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />True if the <a href="T_Windows_Storage_StorageFile">StorageFile</a> matches the specified value; otherwise false.

#### Implements
<a href="M_Windows_Storage_IStorageItem_IsOfType">IStorageItem.IsOfType(StorageItemTypes)</a><br />

## See Also


#### Reference
<a href="T_Windows_Storage_StorageFile">StorageFile Class</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />