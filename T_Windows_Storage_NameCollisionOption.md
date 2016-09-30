# NameCollisionOption Enumeration
 _**\[This is preliminary documentation and is subject to change.\]**_

Specifies what to do if a file or folder with the specified name already exists in the current folder when you copy, move, or rename a file or folder.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public enum NameCollisionOption
```

**VB**<br />
``` VB
Public Enumeration NameCollisionOption
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:Windows.Storage.NameCollisionOption.GenerateUniqueName">**GenerateUniqueName**</td><td>0</td><td>Automatically append a number to the base of the specified name if the file or folder already exists. For example, if MyFile.txt already exists, then the new file is named MyFile(2).txt. If MyFolder already exists, then the new folder is named MyFolder(2).</td></tr><tr><td /><td target="F:Windows.Storage.NameCollisionOption.ReplaceExisting">**ReplaceExisting**</td><td>1</td><td>Replace the existing item if the file or folder already exists.</td></tr><tr><td /><td target="F:Windows.Storage.NameCollisionOption.FailIfExists">**FailIfExists**</td><td>2</td><td>Raise an exception of type System.Exception if the file or folder already exists. Methods that don't explicitly pass a value from the NameCollisionOption enumeration use the FailIfExists value as the default when you try to create, rename, copy, or move a file or folder.</td></tr></table>

## See Also


#### Reference
<a href="N_Windows_Storage">Windows.Storage Namespace</a><br />