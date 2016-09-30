# ResourceLoader Class
 _**\[This is preliminary documentation and is subject to change.\]**_

Provides simplified access to app resources such as app UI strings.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Windows.ApplicationModel.Resources.ResourceLoader<br />
**Namespace:**&nbsp;<a href="N_Windows_ApplicationModel_Resources">Windows.ApplicationModel.Resources</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public sealed class ResourceLoader
```

**VB**<br />
``` VB
Public NotInheritable Class ResourceLoader
```

The ResourceLoader type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Windows_ApplicationModel_Resources_ResourceLoader_GetForCurrentView">GetForCurrentView</a></td><td>
Gets a ResourceLoader object for the Resources subtree of the currently running app's main ResourceMap. This ResourceLoader uses a default context associated with the current view.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Windows_ApplicationModel_Resources_ResourceLoader_GetForViewIndependentUse">GetForViewIndependentUse</a></td><td>
Gets a ResourceLoader object for the Resources subtree of the currently running app's main ResourceMap. This ResourceLoader uses a default context that's not associated with any view.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_ApplicationModel_Resources_ResourceLoader_GetString">GetString</a></td><td>
Returns the most appropriate string value of a resource, specified by resource identifier, for the default ResourceContext of the view in which the ResourceLoader was obtained using ResourceLoader.GetForCurrentView.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#resourceloader-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Windows_ApplicationModel_Resources">Windows.ApplicationModel.Resources Namespace</a><br />