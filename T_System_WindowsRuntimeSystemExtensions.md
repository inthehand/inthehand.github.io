# WindowsRuntimeSystemExtensions Class
 _**\[This is preliminary documentation and is subject to change.\]**_

Provides extension methods for converting between tasks and Windows Runtime asynchronous actions and operations.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;System.WindowsRuntimeSystemExtensions<br />
**Namespace:**&nbsp;<a href="N_System">System</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static class WindowsRuntimeSystemExtensions
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public NotInheritable Class WindowsRuntimeSystemExtensions
```

The WindowsRuntimeSystemExtensions type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_System_WindowsRuntimeSystemExtensions_AsAsyncAction">AsAsyncAction</a></td><td>
Returns a Windows Runtime asynchronous action that represents a started task.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_System_WindowsRuntimeSystemExtensions_AsAsyncOperation__1">AsAsyncOperation(TResult)</a></td><td>
Returns a Windows Runtime asynchronous operation that represents a started task that returns a result.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_System_WindowsRuntimeSystemExtensions_AsTask">AsTask(IAsyncAction)</a></td><td>
Returns a task that represents a Windows Runtime asynchronous action.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_System_WindowsRuntimeSystemExtensions_AsTask__1">AsTask(TResult)(IAsyncOperation(TResult))</a></td><td>
Returns a task that represents a Windows Runtime asynchronous operation returns a result.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_System_WindowsRuntimeSystemExtensions_GetAwaiter">GetAwaiter(IAsyncAction)</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_System_WindowsRuntimeSystemExtensions_GetAwaiter__1">GetAwaiter(TResult)(IAsyncOperation(TResult))</a></td><td /></tr></table>&nbsp;
<a href="#windowsruntimesystemextensions-class">Back to Top</a>

## See Also


#### Reference
<a href="N_System">System Namespace</a><br />