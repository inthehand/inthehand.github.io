# IStorageItem2 Interface
 _**\[This is preliminary documentation and is subject to change.\]**_

Manipulates storage items (files and folders) and their contents, and provides information about them.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public interface IStorageItem2 : IStorageItem
```

**VB**<br />
``` VB
Public Interface IStorageItem2
	Inherits IStorageItem
```

The IStorageItem2 type exposes the following members.


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
<a href="#istorageitem2-interface">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageItem_DeleteAsync">DeleteAsync()</a></td><td>
Deletes the current item.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageItem_DeleteAsync_1">DeleteAsync(StorageDeleteOption)</a></td><td>
Deletes the current item, optionally deleting it permanently.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageItem2_GetParentAsync">GetParentAsync</a></td><td>
Gets the parent folder of the current storage item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageItem2_IsEqual">IsEqual</a></td><td>
Indicates whether the current item is the same as the specified item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_IStorageItem_IsOfType">IsOfType</a></td><td>
Determines whether the current IStorageItem matches the specified StorageItemTypes value.
 (Inherited from <a href="T_Windows_Storage_IStorageItem">IStorageItem</a>.)</td></tr></table>&nbsp;
<a href="#istorageitem2-interface">Back to Top</a>

## See Also


#### Reference
<a href="N_Windows_Storage">Windows.Storage Namespace</a><br />