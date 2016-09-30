# IStorageFile Interface
 _**\[This is preliminary documentation and is subject to change.\]**_

Represents a file. Provides information about the file and its contents, and ways to manipulate them.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public interface IStorageFile : IStorageItem
```

**VB**<br />
``` VB
Public Interface IStorageFile
	Inherits IStorageItem
```

The IStorageFile type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_IStorageItem_Attributes">Attributes</a></td><td>
Gets the attributes of a storage item.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_IStorageFile_ContentType">ContentType</a></td><td>
Gets the MIME type of the contents of the file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_IStorageItem_DateCreated">DateCreated</a></td><td>
Gets the date and time when the current item was created.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_IStorageFile_FileType">FileType</a></td><td>
Gets the type (file name extension) of the file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_IStorageItem_Name">Name</a></td><td>
Gets the name of the item including the file name extension if there is one.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_IStorageItem_Path">Path</a></td><td>
Gets the full file-system path of the item, if the item has a path.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr></table>&nbsp;
<a href="#istoragefile-interface">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageFile_CopyAndReplaceAsync">CopyAndReplaceAsync</a></td><td>
Replaces the specified file with a copy of the current file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageFile_CopyAsync">CopyAsync(IStorageFolder)</a></td><td>
Creates a copy of the file in the specified folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageFile_CopyAsync_1">CopyAsync(IStorageFolder, String)</a></td><td>
Creates a copy of the file in the specified folder, using the desired name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageItem_DeleteAsync">DeleteAsync()</a></td><td>
Deletes the current item.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageItem_DeleteAsync_1">DeleteAsync(StorageDeleteOption)</a></td><td>
Deletes the current item, optionally deleting it permanently.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageItem_IsOfType">IsOfType</a></td><td>
Determines whether the current IStorageItem matches the specified StorageItemTypes value.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageFile_MoveAndReplaceAsync">MoveAndReplaceAsync</a></td><td>
Moves the current file to the location of the specified file and replaces the specified file in that location.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageFile_MoveAsync">MoveAsync(IStorageFolder)</a></td><td>
Moves the current file to the specified folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageFile_MoveAsync_1">MoveAsync(IStorageFolder, String)</a></td><td>
Moves the current file to the specified folder and renames the file according to the desired name.</td></tr></table>&nbsp;
<a href="#istoragefile-interface">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_System_IO_WindowsRuntimeStorageExtensions_OpenStreamForReadAsync">OpenStreamForReadAsync</a></td><td>
Retrieves a stream for reading from a specified file.
 (Defined by <a href="T_System_IO_WindowsRuntimeStorageExtensions">WindowsRuntimeStorageExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_System_IO_WindowsRuntimeStorageExtensions_OpenStreamForWriteAsync">OpenStreamForWriteAsync</a></td><td>
Retrieves a stream for writing to a specified file.
 (Defined by <a href="T_System_IO_WindowsRuntimeStorageExtensions">WindowsRuntimeStorageExtensions</a>.)</td></tr></table>&nbsp;
<a href="#istoragefile-interface">Back to Top</a>

## See Also


#### Reference
<a href="N_Windows_Storage">Windows.Storage Namespace</a><br />