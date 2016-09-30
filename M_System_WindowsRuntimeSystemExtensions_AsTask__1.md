# WindowsRuntimeSystemExtensions.AsTask(*TResult*) Method (IAsyncOperation(*TResult*))
 _**\[This is preliminary documentation and is subject to change.\]**_

Returns a task that represents a Windows Runtime asynchronous operation returns a result.

**Namespace:**&nbsp;<a href="N_System">System</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static Task<TResult> AsTask<TResult>(
	this IAsyncOperation<TResult> source
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function AsTask(Of TResult) ( 
	source As IAsyncOperation(Of TResult)
) As Task(Of TResult)
```


#### Parameters
&nbsp;<dl><dt>source</dt><dd>Type: <a href="T_Windows_Foundation_IAsyncOperation_1">Windows.Foundation.IAsyncOperation</a>(*TResult*)<br />The asynchronous operation.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>TResult</dt><dd>The type of object that returns the result of the asynchronous operation.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/dd321424" target="_blank">Task</a>(*TResult*)<br />\[Missing <returns> documentation for "M:System.WindowsRuntimeSystemExtensions.AsTask``1(Windows.Foundation.IAsyncOperation{``0})"\]

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(*TResult*). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="http://msdn.microsoft.com/en-us/library/bb384936.aspx">Extension Methods (Visual Basic)</a> or <a href="http://msdn.microsoft.com/en-us/library/bb383977.aspx">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_System_WindowsRuntimeSystemExtensions">WindowsRuntimeSystemExtensions Class</a><br /><a href="Overload_System_WindowsRuntimeSystemExtensions_AsTask">AsTask Overload</a><br /><a href="N_System">System Namespace</a><br />