# AsyncActionCompletedHandler Delegate
 _**\[This is preliminary documentation and is subject to change.\]**_

Represents a method that handles the completed event of an asynchronous action.

**Namespace:**&nbsp;<a href="N_Windows_Foundation">Windows.Foundation</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public delegate void AsyncActionCompletedHandler(
	IAsyncAction asyncInfo,
	AsyncStatus asyncStatus
)
```

**VB**<br />
``` VB
Public Delegate Sub AsyncActionCompletedHandler ( 
	asyncInfo As IAsyncAction,
	asyncStatus As AsyncStatus
)
```


#### Parameters
&nbsp;<dl><dt>asyncInfo</dt><dd>Type: <a href="T_Windows_Foundation_IAsyncAction">Windows.Foundation.IAsyncAction</a><br />The asynchronous action.</dd><dt>asyncStatus</dt><dd>Type: <a href="T_Windows_Foundation_AsyncStatus">Windows.Foundation.AsyncStatus</a><br />One of the enumeration values.</dd></dl>

## See Also


#### Reference
<a href="N_Windows_Foundation">Windows.Foundation Namespace</a><br />