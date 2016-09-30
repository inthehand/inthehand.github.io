# ApplicationDataContainerSettings.CopyTo Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Copies the elements of the collection to an array, starting at a particular array index.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public void CopyTo(
	KeyValuePair<string, Object>[] array,
	int arrayIndex
)
```

**VB**<br />
``` VB
Public Sub CopyTo ( 
	array As KeyValuePair(Of String, Object)(),
	arrayIndex As Integer
)
```


#### Parameters
&nbsp;<dl><dt>array</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/5tbh8a42" target="_blank">System.Collections.Generic.KeyValuePair</a>(<a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>, <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>)[]<br />The one-dimensional Array that is the destination of the elements copied from the collection. The Array must have zero-based indexing.</dd><dt>arrayIndex</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">System.Int32</a><br />The zero-based index in array at which copying begins.</dd></dl>

#### Implements
<a href="http://msdn2.microsoft.com/en-us/library/0efx51xw" target="_blank">ICollection(T).CopyTo(T[], Int32)</a><br />

## See Also


#### Reference
<a href="T_Windows_Storage_ApplicationDataContainerSettings">ApplicationDataContainerSettings Class</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />