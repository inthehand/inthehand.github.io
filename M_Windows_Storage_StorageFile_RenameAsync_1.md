# StorageFile.RenameAsync Method (String, NameCollisionOption)
 _**\[This is preliminary documentation and is subject to change.\]**_

Renames the current file. This method also specifies what to do if an existing item in the current file's location has the same name.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public IAsyncAction RenameAsync(
	string desiredName,
	NameCollisionOption option
)
```

**VB**<br />
``` VB
Public Function RenameAsync ( 
	desiredName As String,
	option As NameCollisionOption
) As IAsyncAction
```


#### Parameters
&nbsp;<dl><dt>desiredName</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The desired, new name of the current file. 
If there is an existing item in the current file's location that already has the specified desiredName, the specified <a href="T_Windows_Storage_NameCollisionOption">NameCollisionOption</a> determines how the system responds to the conflict.</dd><dt>option</dt><dd>Type: <a href="T_Windows_Storage_NameCollisionOption">Windows.Storage.NameCollisionOption</a><br />The enum value that determines how the system responds if the desiredName is the same as the name of an existing item in the current file's location.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncAction">IAsyncAction</a><br />No object or value is returned by this method when it completes.

## See Also


#### Reference
<a href="T_Windows_Storage_StorageFile">StorageFile Class</a><br /><a href="Overload_Windows_Storage_StorageFile_RenameAsync">RenameAsync Overload</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />