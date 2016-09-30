# DataPackageView Class
 _**\[This is preliminary documentation and is subject to change.\]**_

A read-only version of a <a href="T_Windows_ApplicationModel_DataTransfer_DataPackage">DataPackage</a>. Apps that receive shared content get this object when acquiring content.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Windows.ApplicationModel.DataTransfer.DataPackageView<br />
**Namespace:**&nbsp;<a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public sealed class DataPackageView
```

**VB**<br />
``` VB
Public NotInheritable Class DataPackageView
```

The DataPackageView type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_ApplicationModel_DataTransfer_DataPackageView_AvailableFormats">AvailableFormats</a></td><td>
Returns the formats the DataPackageView contains.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_ApplicationModel_DataTransfer_DataPackageView_Properties">Properties</a></td><td>
Gets a <a href="T_Windows_ApplicationModel_DataTransfer_DataPackagePropertySetView">DataPackagePropertySetView</a> object, which contains a read-only set of properties for the data in the DataPackageView object.</td></tr></table>&nbsp;
<a href="#datapackageview-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_ApplicationModel_DataTransfer_DataPackageView_Contains">Contains</a></td><td>
Checks to see if the DataPackageView contains a specific data format.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_ApplicationModel_DataTransfer_DataPackageView_GetApplicationLinkAsync">GetApplicationLinkAsync</a></td><td>
Gets the application link in the DataPackageView object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_ApplicationModel_DataTransfer_DataPackageView_GetDataAsync">GetDataAsync</a></td><td>
Gets the data contained in the DataPackageView.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_ApplicationModel_DataTransfer_DataPackageView_GetTextAsync">GetTextAsync</a></td><td>
Gets the text in the DataPackageView object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_ApplicationModel_DataTransfer_DataPackageView_GetWebLinkAsync">GetWebLinkAsync</a></td><td>
Gets the web link in the DataPackageView object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#datapackageview-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer Namespace</a><br />