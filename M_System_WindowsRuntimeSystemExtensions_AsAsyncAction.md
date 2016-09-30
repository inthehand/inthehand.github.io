# WindowsRuntimeSystemExtensions.AsAsyncAction Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Returns a Windows Runtime asynchronous action that represents a started task.

**Namespace:**&nbsp;<a href="N_System">System</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static IAsyncAction AsAsyncAction(
	this Task source
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function AsAsyncAction ( 
	source As Task
) As IAsyncAction
```


#### Parameters
&nbsp;<dl><dt>source</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/dd235678" target="_blank">System.Threading.Tasks.Task</a><br />\[Missing <param name="source"/> documentation for "M:System.WindowsRuntimeSystemExtensions.AsAsyncAction(System.Threading.Tasks.Task)"\]</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncAction">IAsyncAction</a><br />\[Missing <returns> documentation for "M:System.WindowsRuntimeSystemExtensions.AsAsyncAction(System.Threading.Tasks.Task)"\]

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="http://msdn2.microsoft.com/en-us/library/dd235678" target="_blank">Task</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="http://msdn.microsoft.com/en-us/library/bb384936.aspx">Extension Methods (Visual Basic)</a> or <a href="http://msdn.microsoft.com/en-us/library/bb383977.aspx">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_System_WindowsRuntimeSystemExtensions">WindowsRuntimeSystemExtensions Class</a><br /><a href="N_System">System Namespace</a><br />