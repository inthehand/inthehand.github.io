# WindowsRuntimeStorageExtensions.OpenStreamForWriteAsync Method (IStorageFolder, String)
 _**\[This is preliminary documentation and is subject to change.\]**_

Retrieves a stream for writing from a file in the specified parent folder.

**Namespace:**&nbsp;<a href="N_System_IO">System.IO</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static Task<Stream> OpenStreamForWriteAsync(
	this IStorageFolder rootDirectory,
	string relativePath
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function OpenStreamForWriteAsync ( 
	rootDirectory As IStorageFolder,
	relativePath As String
) As Task(Of Stream)
```


#### Parameters
&nbsp;<dl><dt>rootDirectory</dt><dd>Type: <a href="T_Windows_Storage_IStorageFolder">Windows.Storage.IStorageFolder</a><br />The Windows Runtime IStorageFolder object that contains the file to write to.</dd><dt>relativePath</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The path, relative to the root folder, to the file to write to.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/dd321424" target="_blank">Task</a>(<a href="http://msdn2.microsoft.com/en-us/library/8f86tw9e" target="_blank">Stream</a>)<br />\[Missing <returns> documentation for "M:System.IO.WindowsRuntimeStorageExtensions.OpenStreamForWriteAsync(Windows.Storage.IStorageFolder,System.String)"\]

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="T_Windows_Storage_IStorageFolder">IStorageFolder</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="http://msdn.microsoft.com/en-us/library/bb384936.aspx">Extension Methods (Visual Basic)</a> or <a href="http://msdn.microsoft.com/en-us/library/bb383977.aspx">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_System_IO_WindowsRuntimeStorageExtensions">WindowsRuntimeStorageExtensions Class</a><br /><a href="Overload_System_IO_WindowsRuntimeStorageExtensions_OpenStreamForWriteAsync">OpenStreamForWriteAsync Overload</a><br /><a href="N_System_IO">System.IO Namespace</a><br />