# StorageFolder Class
 _**\[This is preliminary documentation and is subject to change.\]**_

Manages folders and their contents and provides information about them.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Windows.Storage.StorageFolder<br />
**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public sealed class StorageFolder : IStorageFolder, 
	IStorageItem
```

**VB**<br />
``` VB
Public NotInheritable Class StorageFolder
	Implements IStorageFolder, IStorageItem
```

The StorageFolder type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_StorageFolder_Attributes">Attributes</a></td><td>
Gets the attributes of the current folder.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_StorageFolder_DateCreated">DateCreated</a></td><td>
Gets the date and time that the current folder was created.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_StorageFolder_Name">Name</a></td><td>
Gets the name of the current folder.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_StorageFolder_Path">Path</a></td><td>
Gets the full path of the current folder in the file system, if the path is available.</td></tr></table>&nbsp;
<a href="#storagefolder-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFolder_CreateFileAsync">CreateFileAsync(String)</a></td><td>
Creates a new file with the specified name in the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFolder_CreateFileAsync_1">CreateFileAsync(String, CreationCollisionOption)</a></td><td>
Creates a new file with the specified name in the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFolder_CreateFolderAsync">CreateFolderAsync(String)</a></td><td>
Creates a new subfolder with the specified name in the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFolder_CreateFolderAsync_1">CreateFolderAsync(String, CreationCollisionOption)</a></td><td>
Creates a new subfolder with the specified name in the current folder. This method also specifies what to do if a subfolder with the same name already exists in the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFolder_DeleteAsync">DeleteAsync()</a></td><td>
Deletes the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFolder_DeleteAsync_1">DeleteAsync(StorageDeleteOption)</a></td><td>
Deletes the current folder. This method also specifies whether to delete the folder permanently.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFolder_GetFileAsync">GetFileAsync</a></td><td>
Gets the file with the specified name from the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFolder_GetFilesAsync">GetFilesAsync</a></td><td>
Gets the files in the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFolder_GetFolderAsync">GetFolderAsync</a></td><td>
Gets the specified folder from the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Windows_Storage_StorageFolder_GetFolderFromPathAsync">GetFolderFromPathAsync</a></td><td>
Gets a StorageFile object to represent the file at the specified path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFolder_GetFoldersAsync">GetFoldersAsync</a></td><td>
Gets the folders in the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFolder_GetParentAsync">GetParentAsync</a></td><td>
Gets the parent folder of the current folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFolder_IsOfType">IsOfType</a></td><td>
Indicates whether the current StorageFolder matches the specified StorageItemTypes value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFolder_TryGetItemAsync">TryGetItemAsync</a></td><td>
Try to get a single file or sub-folder from the current folder by using the name of the item.</td></tr></table>&nbsp;
<a href="#storagefolder-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_System_IO_WindowsRuntimeStorageExtensions_OpenStreamForReadAsync_1">OpenStreamForReadAsync</a></td><td>
Retrieves a stream for reading from a file in the specified parent folder.
 (Defined by <a href="T_System_IO_WindowsRuntimeStorageExtensions">WindowsRuntimeStorageExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_System_IO_WindowsRuntimeStorageExtensions_OpenStreamForWriteAsync_1">OpenStreamForWriteAsync</a></td><td>
Retrieves a stream for writing from a file in the specified parent folder.
 (Defined by <a href="T_System_IO_WindowsRuntimeStorageExtensions">WindowsRuntimeStorageExtensions</a>.)</td></tr></table>&nbsp;
<a href="#storagefolder-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Windows_Storage">Windows.Storage Namespace</a><br />