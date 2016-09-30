# PathIO.ReadLinesAsync Method (String, UnicodeEncoding)
 _**\[This is preliminary documentation and is subject to change.\]**_

Reads the contents of the file at the specified path or URI using the specified character encoding and returns lines of text.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static IAsyncOperation<IList> ReadLinesAsync(
	string absolutePath,
	UnicodeEncoding encoding
)
```

**VB**<br />
``` VB
Public Shared Function ReadLinesAsync ( 
	absolutePath As String,
	encoding As UnicodeEncoding
) As IAsyncOperation(Of IList)
```


#### Parameters
&nbsp;<dl><dt>absolutePath</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The path of the file to read.</dd><dt>encoding</dt><dd>Type: <a href="T_Windows_Storage_Streams_UnicodeEncoding">Windows.Storage.Streams.UnicodeEncoding</a><br />The character encoding of the file.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="http://msdn2.microsoft.com/en-us/library/30ft6hw7" target="_blank">IList</a>)<br />When this method completes successfully, it returns the contents of the file as a list (type IVector) of lines of text. Each line of text in the list is represented by a String object.

## See Also


#### Reference
<a href="T_Windows_Storage_PathIO">PathIO Class</a><br /><a href="Overload_Windows_Storage_PathIO_ReadLinesAsync">ReadLinesAsync Overload</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />