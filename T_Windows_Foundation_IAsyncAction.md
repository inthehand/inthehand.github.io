# IAsyncAction Interface
 _**\[This is preliminary documentation and is subject to change.\]**_

Represents an asynchronous action. This is the return type for many Windows Runtime asynchronous methods that don't have a result object, and don't report ongoing progress.

**Namespace:**&nbsp;<a href="N_Windows_Foundation">Windows.Foundation</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public interface IAsyncAction
```

**VB**<br />
``` VB
Public Interface IAsyncAction
```

The IAsyncAction type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Foundation_IAsyncAction_Completed">Completed</a></td><td>
Gets or sets the method that handles the action completed notification.</td></tr></table>&nbsp;
<a href="#iasyncaction-interface">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Foundation_IAsyncAction_GetResults">GetResults</a></td><td>
Returns the results of the action.</td></tr></table>&nbsp;
<a href="#iasyncaction-interface">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_System_WindowsRuntimeSystemExtensions_AsTask">AsTask</a></td><td>
Returns a task that represents a Windows Runtime asynchronous action.
 (Defined by <a href="T_System_WindowsRuntimeSystemExtensions">WindowsRuntimeSystemExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_System_WindowsRuntimeSystemExtensions_GetAwaiter">GetAwaiter</a></td><td> (Defined by <a href="T_System_WindowsRuntimeSystemExtensions">WindowsRuntimeSystemExtensions</a>.)</td></tr></table>&nbsp;
<a href="#iasyncaction-interface">Back to Top</a>

## See Also


#### Reference
<a href="N_Windows_Foundation">Windows.Foundation Namespace</a><br />