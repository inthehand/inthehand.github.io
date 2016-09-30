# WindowsRuntimeSystemExtensions.AsAsyncOperation(*TResult*) Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Returns a Windows Runtime asynchronous operation that represents a started task that returns a result.

**Namespace:**&nbsp;<a href="N_System">System</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static IAsyncOperation<TResult> AsAsyncOperation<TResult>(
	this Task<TResult> source
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function AsAsyncOperation(Of TResult) ( 
	source As Task(Of TResult)
) As IAsyncOperation(Of TResult)
```


#### Parameters
&nbsp;<dl><dt>source</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/dd321424" target="_blank">System.Threading.Tasks.Task</a>(*TResult*)<br />The started task.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>TResult</dt><dd>The type that returns the result.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(*TResult*)<br />\[Missing <returns> documentation for "M:System.WindowsRuntimeSystemExtensions.AsAsyncOperation``1(System.Threading.Tasks.Task{``0})"\]

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="http://msdn2.microsoft.com/en-us/library/dd321424" target="_blank">Task</a>(*TResult*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="http://msdn.microsoft.com/en-us/library/bb384936.aspx">Extension Methods (Visual Basic)</a> or <a href="http://msdn.microsoft.com/en-us/library/bb383977.aspx">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_System_WindowsRuntimeSystemExtensions">WindowsRuntimeSystemExtensions Class</a><br /><a href="N_System">System Namespace</a><br />