# CreationCollisionOption Enumeration
 _**\[This is preliminary documentation and is subject to change.\]**_

Represents a file. Provides information about the file and its content, and ways to manipulate them.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public enum CreationCollisionOption
```

**VB**<br />
``` VB
Public Enumeration CreationCollisionOption
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:Windows.Storage.CreationCollisionOption.GenerateUniqueName">**GenerateUniqueName**</td><td>0</td><td>Automatically append a number to the base of the specified name if the file or folder already exists. For example, if MyFile.txt already exists, then the new file is named MyFile(2).txt.If MyFolder already exists, then the new folder is named MyFolder(2).</td></tr><tr><td /><td target="F:Windows.Storage.CreationCollisionOption.ReplaceExisting">**ReplaceExisting**</td><td>1</td><td>Replace the existing item if the file or folder already exists.</td></tr><tr><td /><td target="F:Windows.Storage.CreationCollisionOption.FailIfExists">**FailIfExists**</td><td>2</td><td>Raise an exception of type System.Exception if the file or folder already exists. Methods that don't explicitly pass a value from the CreationCollisionOption enumeration use the FailIfExists value as the default when you try to create, rename, copy, or move a file or folder.</td></tr><tr><td /><td target="F:Windows.Storage.CreationCollisionOption.OpenIfExists">**OpenIfExists**</td><td>3</td><td>Return the existing item if the file or folder already exists.</td></tr></table>

## See Also


#### Reference
<a href="N_Windows_Storage">Windows.Storage Namespace</a><br />