# AsyncOperationCompletedHandler(*TResult*) Delegate
 _**\[This is preliminary documentation and is subject to change.\]**_

Represents a method that handles the completed event of an asynchronous operation.

**Namespace:**&nbsp;<a href="N_Windows_Foundation">Windows.Foundation</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public delegate void AsyncOperationCompletedHandler<TResult>(
	IAsyncOperation<TResult> asyncInfo,
	AsyncStatus asyncStatus
)

```

**VB**<br />
``` VB
Public Delegate Sub AsyncOperationCompletedHandler(Of TResult) ( 
	asyncInfo As IAsyncOperation(Of TResult),
	asyncStatus As AsyncStatus
)
```


#### Parameters
&nbsp;<dl><dt>asyncInfo</dt><dd>Type: <a href="T_Windows_Foundation_IAsyncOperation_1">Windows.Foundation.IAsyncOperation</a>(*TResult*)<br />The asynchronous operation.</dd><dt>asyncStatus</dt><dd>Type: <a href="T_Windows_Foundation_AsyncStatus">Windows.Foundation.AsyncStatus</a><br />One of the enumeration values.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>TResult</dt><dd>\[Missing <typeparam name="TResult"/> documentation for "T:Windows.Foundation.AsyncOperationCompletedHandler`1"\]</dd></dl>

## See Also


#### Reference
<a href="N_Windows_Foundation">Windows.Foundation Namespace</a><br />