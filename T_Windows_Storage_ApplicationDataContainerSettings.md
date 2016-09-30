# ApplicationDataContainerSettings Class
 _**\[This is preliminary documentation and is subject to change.\]**_

Provides access to the settings in a settings container.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Windows.Storage.ApplicationDataContainerSettings<br />
**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public sealed class ApplicationDataContainerSettings : IPropertySet, 
	IObservableMap<string, Object>, IDictionary<string, Object>, 
	ICollection<KeyValuePair<string, Object>>, IEnumerable<KeyValuePair<string, Object>>, 
	IEnumerable
```

**VB**<br />
``` VB
Public NotInheritable Class ApplicationDataContainerSettings
	Implements IPropertySet, IObservableMap(Of String, Object), 
	IDictionary(Of String, Object), ICollection(Of KeyValuePair(Of String, Object)), 
	IEnumerable(Of KeyValuePair(Of String, Object)), IEnumerable
```

The ApplicationDataContainerSettings type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_ApplicationDataContainerSettings_Count">Count</a></td><td>
Gets the number of elements contained in the collection.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_ApplicationDataContainerSettings_IsReadOnly">IsReadOnly</a></td><td>
Gets a value indicating whether the dictionary is read-only.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_ApplicationDataContainerSettings_Item">Item</a></td><td>
Gets or sets the element value at the specified key index.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_ApplicationDataContainerSettings_Keys">Keys</a></td><td>
Gets an ICollection object containing the keys of the ApplicationDataContainerSettings.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Storage_ApplicationDataContainerSettings_Values">Values</a></td><td>
Gets an ICollection object containing the values of the ApplicationDataContainerSettings.</td></tr></table>&nbsp;
<a href="#applicationdatacontainersettings-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_ApplicationDataContainerSettings_Add">Add(KeyValuePair(String, Object))</a></td><td>
Adds a new key-value pair to the ApplicationDataContainerSettings.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_ApplicationDataContainerSettings_Add_1">Add(String, Object)</a></td><td>
Adds an item to the ApplicationDataContainerSettings.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_ApplicationDataContainerSettings_Clear">Clear</a></td><td>
Removes all related application settings.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_ApplicationDataContainerSettings_Contains">Contains</a></td><td>
Returns a value that indicates whether a specified key-value pair exists in the ApplicationDataContainerSettings.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_ApplicationDataContainerSettings_ContainsKey">ContainsKey</a></td><td>
Returns a value that indicates whether a specified key exists in the ApplicationDataContainerSettings.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_ApplicationDataContainerSettings_CopyTo">CopyTo</a></td><td>
Copies the elements of the collection to an array, starting at a particular array index.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_ApplicationDataContainerSettings_Remove">Remove(KeyValuePair(String, Object))</a></td><td>
Removes a specific key-value pair from the ApplicationDataContainerSettings.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_ApplicationDataContainerSettings_Remove_1">Remove(String)</a></td><td>
Removes a specific item from the ApplicationDataContainerSettings.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Storage_ApplicationDataContainerSettings_TryGetValue">TryGetValue</a></td><td>
Returns a value that indicates whether a specified key exists in the ApplicationDataContainerSettings. If an item with that key exists, the item is retrieved as an out parameter.</td></tr></table>&nbsp;
<a href="#applicationdatacontainersettings-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Windows_Storage_ApplicationDataContainerSettings_MapChanged">MapChanged</a></td><td>
Occurs when the map changes.</td></tr></table>&nbsp;
<a href="#applicationdatacontainersettings-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Windows_Storage">Windows.Storage Namespace</a><br />