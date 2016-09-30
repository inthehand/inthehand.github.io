# ApplicationDataContainerSettings.TryGetValue Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Returns a value that indicates whether a specified key exists in the <a href="T_Windows_Storage_ApplicationDataContainerSettings">ApplicationDataContainerSettings</a>. If an item with that key exists, the item is retrieved as an out parameter.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public bool TryGetValue(
	string key,
	out Object value
)
```

**VB**<br />
``` VB
Public Function TryGetValue ( 
	key As String,
	<OutAttribute> ByRef value As Object
) As Boolean
```


#### Parameters
&nbsp;<dl><dt>key</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The key to check for in the <a href="T_Windows_Storage_ApplicationDataContainerSettings">ApplicationDataContainerSettings</a>.</dd><dt>value</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />The item, if it exists. Contains null if the item does not exist in the <a href="T_Windows_Storage_ApplicationDataContainerSettings">ApplicationDataContainerSettings</a>.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />true if an item with that key exists in the <a href="T_Windows_Storage_ApplicationDataContainerSettings">ApplicationDataContainerSettings</a>; otherwise, false.

#### Implements
<a href="http://msdn2.microsoft.com/en-us/library/bb299639" target="_blank">IDictionary(TKey, TValue).TryGetValue(TKey, TValue)</a><br />

## See Also


#### Reference
<a href="T_Windows_Storage_ApplicationDataContainerSettings">ApplicationDataContainerSettings Class</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />