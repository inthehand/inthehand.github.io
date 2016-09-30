# FileAttributes Enumeration
 _**\[This is preliminary documentation and is subject to change.\]**_

Describes the attributes of a file or folder.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum FileAttributes
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration FileAttributes
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:Windows.Storage.FileAttributes.Normal">**Normal**</td><td>0</td><td>The item is normal. That is, the item doesn't have any of the other values in the enumeration.</td></tr><tr><td /><td target="F:Windows.Storage.FileAttributes.ReadOnly">**ReadOnly**</td><td>1</td><td>The item is read-only.</td></tr><tr><td /><td target="F:Windows.Storage.FileAttributes.Directory">**Directory**</td><td>16</td><td>The item is a directory.</td></tr><tr><td /><td target="F:Windows.Storage.FileAttributes.Archive">**Archive**</td><td>32</td><td>The item is archived.</td></tr><tr><td /><td target="F:Windows.Storage.FileAttributes.Temporary">**Temporary**</td><td>256</td><td>The item is a temporary file.</td></tr></table>

## See Also


#### Reference
<a href="N_Windows_Storage">Windows.Storage Namespace</a><br />