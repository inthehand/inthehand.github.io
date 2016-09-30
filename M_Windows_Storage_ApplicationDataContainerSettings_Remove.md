# ApplicationDataContainerSettings.Remove Method (KeyValuePair(String, Object))
 _**\[This is preliminary documentation and is subject to change.\]**_

Removes a specific key-value pair from the <a href="T_Windows_Storage_ApplicationDataContainerSettings">ApplicationDataContainerSettings</a>.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public bool Remove(
	KeyValuePair<string, Object> item
)
```

**VB**<br />
``` VB
Public Function Remove ( 
	item As KeyValuePair(Of String, Object)
) As Boolean
```


#### Parameters
&nbsp;<dl><dt>item</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/5tbh8a42" target="_blank">System.Collections.Generic.KeyValuePair</a>(<a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>, <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>)<br />The key-value pair to remove.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/a28wyd50" target="_blank">Boolean</a><br />true if the item was removed, otherwise false.

#### Implements
<a href="http://msdn2.microsoft.com/en-us/library/bye7h94w" target="_blank">ICollection(T).Remove(T)</a><br />

## See Also


#### Reference
<a href="T_Windows_Storage_ApplicationDataContainerSettings">ApplicationDataContainerSettings Class</a><br /><a href="Overload_Windows_Storage_ApplicationDataContainerSettings_Remove">Remove Overload</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />