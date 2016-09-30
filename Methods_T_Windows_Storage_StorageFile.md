# StorageFile Methods
 _**\[This is preliminary documentation and is subject to change.\]**_

The <a href="T_Windows_Storage_StorageFile">StorageFile</a> type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFile_CopyAndReplaceAsync">CopyAndReplaceAsync</a></td><td>
Replaces the specified file with a copy of the current file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFile_CopyAsync">CopyAsync(IStorageFolder)</a></td><td>
Creates a copy of the file in the specified folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFile_CopyAsync_1">CopyAsync(IStorageFolder, String)</a></td><td>
Creates a copy of the file in the specified folder and renames the copy.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFile_DeleteAsync">DeleteAsync()</a></td><td>
Deletes the current file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFile_DeleteAsync_1">DeleteAsync(StorageDeleteOption)</a></td><td>
Deletes the current file, optionally deleting the item permanently.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Windows_Storage_StorageFile_GetFileFromPathAsync">GetFileFromPathAsync</a></td><td>
Gets a StorageFile object to represent the file at the specified path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFile_GetParentAsync">GetParentAsync</a></td><td>
Gets the parent folder of the current file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFile_IsEqual">IsEqual</a></td><td>
Indicates whether the current file is equal to the specified file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFile_IsOfType">IsOfType</a></td><td>
Determines whether the current <a href="T_Windows_Storage_StorageFile">StorageFile</a> matches the specified <a href="T_Windows_Storage_StorageItemTypes">StorageItemTypes</a> value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFile_MoveAndReplaceAsync">MoveAndReplaceAsync</a></td><td>
Moves the current file to the location of the specified file and replaces the specified file in that location.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFile_MoveAsync">MoveAsync(IStorageFolder)</a></td><td>
Moves the current file to the specified folder and renames the file according to the desired name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFile_MoveAsync_1">MoveAsync(IStorageFolder, String)</a></td><td>
Moves the current file to the specified folder and renames the file according to the desired name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFile_RenameAsync">RenameAsync(String)</a></td><td>
Renames the current file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_StorageFile_RenameAsync_1">RenameAsync(String, NameCollisionOption)</a></td><td>
Renames the current file. This method also specifies what to do if an existing item in the current file's location has the same name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#storagefile-methods">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_System_IO_WindowsRuntimeStorageExtensions_OpenStreamForReadAsync">OpenStreamForReadAsync</a></td><td>
Retrieves a stream for reading from a specified file.
 (Defined by <a href="T_System_IO_WindowsRuntimeStorageExtensions">WindowsRuntimeStorageExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_System_IO_WindowsRuntimeStorageExtensions_OpenStreamForWriteAsync">OpenStreamForWriteAsync</a></td><td>
Retrieves a stream for writing to a specified file.
 (Defined by <a href="T_System_IO_WindowsRuntimeStorageExtensions">WindowsRuntimeStorageExtensions</a>.)</td></tr></table>&nbsp;
<a href="#storagefile-methods">Back to Top</a>

## See Also


#### Reference
<a href="T_Windows_Storage_StorageFile">StorageFile Class</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />