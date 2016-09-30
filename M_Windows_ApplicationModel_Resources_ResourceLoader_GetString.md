# ResourceLoader.GetString Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Returns the most appropriate string value of a resource, specified by resource identifier, for the default ResourceContext of the view in which the ResourceLoader was obtained using ResourceLoader.GetForCurrentView.

**Namespace:**&nbsp;<a href="N_Windows_ApplicationModel_Resources">Windows.ApplicationModel.Resources</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public string GetString(
	string resource
)
```

**VB**<br />
``` VB
Public Function GetString ( 
	resource As String
) As String
```


#### Parameters
&nbsp;<dl><dt>resource</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The resource identifier of the resource to be resolved.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a><br />The most appropriate string value of the specified resource for the default ResourceContext.

## See Also


#### Reference
<a href="T_Windows_ApplicationModel_Resources_ResourceLoader">ResourceLoader Class</a><br /><a href="N_Windows_ApplicationModel_Resources">Windows.ApplicationModel.Resources Namespace</a><br />