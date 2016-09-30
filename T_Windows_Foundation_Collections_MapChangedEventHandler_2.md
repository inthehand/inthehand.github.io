# MapChangedEventHandler(*K*, *V*) Delegate
 _**\[This is preliminary documentation and is subject to change.\]**_

Represents the method that handles the changed event of an observable map.

**Namespace:**&nbsp;<a href="N_Windows_Foundation_Collections">Windows.Foundation.Collections</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public delegate void MapChangedEventHandler<K, V>(
	IObservableMap<K, V> sender,
	IMapChangedEventArgs<K> eventArgs
)

```

**VB**<br />
``` VB
Public Delegate Sub MapChangedEventHandler(Of K, V) ( 
	sender As IObservableMap(Of K, V),
	eventArgs As IMapChangedEventArgs(Of K)
)
```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: <a href="T_Windows_Foundation_Collections_IObservableMap_2">Windows.Foundation.Collections.IObservableMap</a>(*K*, *V*)<br /></dd><dt>eventArgs</dt><dd>Type: <a href="T_Windows_Foundation_Collections_IMapChangedEventArgs_1">Windows.Foundation.Collections.IMapChangedEventArgs</a>(*K*)<br /></dd></dl>

#### Type Parameters
&nbsp;<dl><dt>K</dt><dd>The type of the keys in the map.</dd><dt>V</dt><dd>The type of the values in the map.</dd></dl>

## See Also


#### Reference
<a href="N_Windows_Foundation_Collections">Windows.Foundation.Collections Namespace</a><br />