# IStorageFolder Interface
 _**\[This is preliminary documentation and is subject to change.\]**_

Manipulates folders and their contents, and provides information about them.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public interface IStorageFolder : IStorageItem
```

**VB**<br />
``` VB
Public Interface IStorageFolder
	Inherits IStorageItem
```

The IStorageFolder type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_IStorageItem_Attributes">Attributes</a></td><td>
Gets the attributes of a storage item.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_IStorageItem_DateCreated">DateCreated</a></td><td>
Gets the date and time when the current item was created.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_IStorageItem_Name">Name</a></td><td>
Gets the name of the item including the file name extension if there is one.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_IStorageItem_Path">Path</a></td><td>
Gets the full file-system path of the item, if the item has a path.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr></table>&nbsp;
<a href="#istoragefolder-interface">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageFolder_CreateFileAsync">CreateFileAsync(String)</a></td><td>
Creates a new file in the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageFolder_CreateFileAsync_1">CreateFileAsync(String, CreationCollisionOption)</a></td><td>
Creates a new file in the current folder, and specifies what to do if a file with the same name already exists in the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageFolder_CreateFolderAsync">CreateFolderAsync(String)</a></td><td>
Creates a new folder in the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageFolder_CreateFolderAsync_1">CreateFolderAsync(String, CreationCollisionOption)</a></td><td>
Creates a new folder in the current folder, and specifies what to do if a folder with the same name already exists in the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageItem_DeleteAsync">DeleteAsync()</a></td><td>
Deletes the current item.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageItem_DeleteAsync_1">DeleteAsync(StorageDeleteOption)</a></td><td>
Deletes the current item, optionally deleting it permanently.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageFolder_GetFileAsync">GetFileAsync</a></td><td>
Gets the specified file from the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageFolder_GetFilesAsync">GetFilesAsync</a></td><td>
Gets the files from the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageFolder_GetFolderAsync">GetFolderAsync</a></td><td>
Gets the specified folder from the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageFolder_GetFoldersAsync">GetFoldersAsync</a></td><td>
Gets the folders in the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageItem_IsOfType">IsOfType</a></td><td>
Determines whether the current IStorageItem matches the specified StorageItemTypes value.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr></table>&nbsp;
<a href="#istoragefolder-interface">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_System_IO_WindowsRuntimeStorageExtensions_OpenStreamForReadAsync_1">OpenStreamForReadAsync</a></td><td>
Retrieves a stream for reading from a file in the specified parent folder.
 (Defined by <a href="T_System_IO_WindowsRuntimeStorageExtensions">WindowsRuntimeStorageExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_System_IO_WindowsRuntimeStorageExtensions_OpenStreamForWriteAsync_1">OpenStreamForWriteAsync</a></td><td>
Retrieves a stream for writing from a file in the specified parent folder.
 (Defined by <a href="T_System_IO_WindowsRuntimeStorageExtensions">WindowsRuntimeStorageExtensions</a>.)</td></tr></table>&nbsp;
<a href="#istoragefolder-interface">Back to Top</a>

## See Also


#### Reference
<a href="N_Windows_Storage">Windows.Storage Namespace</a><br />