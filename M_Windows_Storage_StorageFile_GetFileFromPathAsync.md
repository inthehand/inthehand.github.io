# StorageFile.GetFileFromPathAsync Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Gets a StorageFile object to represent the file at the specified path.

**Namespace:**&nbsp;<a href="N_Windows_Storage">Windows.Storage</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static IAsyncOperation<StorageFile> GetFileFromPathAsync(
	string path
)
```

**VB**<br />
``` VB
Public Shared Function GetFileFromPathAsync ( 
	path As String
) As IAsyncOperation(Of StorageFile)
```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The path of the file to get a StorageFile to represent. If your path uses slashes, make sure you use backslashes(\). Forward slashes(/) are not accepted by this method.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="T_Windows_Storage_StorageFile">StorageFile</a>)<br />When this method completes, it returns the file as a StorageFile.

## See Also


#### Reference
<a href="T_Windows_Storage_StorageFile">StorageFile Class</a><br /><a href="N_Windows_Storage">Windows.Storage Namespace</a><br />