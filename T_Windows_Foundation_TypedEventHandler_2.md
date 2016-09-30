# TypedEventHandler(*TSender*, *TResult*) Delegate
 _**\[This is preliminary documentation and is subject to change.\]**_

Represents a method that handles general events.

**Namespace:**&nbsp;<a href="N_Windows_Foundation">Windows.Foundation</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public delegate void TypedEventHandler<TSender, TResult>(
	TSender sender,
	TResult args
)

```

**VB**<br />
``` VB
Public Delegate Sub TypedEventHandler(Of TSender, TResult) ( 
	sender As TSender,
	args As TResult
)
```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: *TSender*<br />The event source.</dd><dt>args</dt><dd>Type: *TResult*<br />The event data. If there is no event data, this parameter will be null.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>TSender</dt><dd>The event source.</dd><dt>TResult</dt><dd>The event data. If there is no event data, this parameter will be null.</dd></dl>

## See Also


#### Reference
<a href="N_Windows_Foundation">Windows.Foundation Namespace</a><br />