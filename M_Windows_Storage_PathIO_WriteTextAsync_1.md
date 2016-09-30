# PathIO.WriteTextAsync Method (String, String, UnicodeEncoding)
 _**\[This is preliminary documentation and is subject to change.\]**_

Writes text to the file at the specified path or URI using the specified character encoding.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static IAsyncAction WriteTextAsync(
	string absolutePath,
	string contents,
	UnicodeEncoding encoding
)
```

**VB**<br />
``` VB
Public Shared Function WriteTextAsync ( 
	absolutePath As String,
	contents As String,
	encoding As UnicodeEncoding
) As IAsyncAction
```


#### Parameters
&nbsp;<dl><dt>absolutePath</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The path of the file that the text is written to.</dd><dt>contents</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The text to write.</dd><dt>encoding</dt><dd>Type: <a href="T_Windows_Storage_Streams_UnicodeEncoding">Windows.Storage.Streams.UnicodeEncoding</a><br />The character encoding of the file.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncAction">IAsyncAction</a><br />No object or value is returned when this method completes.

## See Also


#### Reference
<a href="T_Windows_Storage_PathIO">PathIO Class</a><br /><a href="Overload_Windows_Storage_PathIO_WriteTextAsync">WriteTextAsync Overload</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />