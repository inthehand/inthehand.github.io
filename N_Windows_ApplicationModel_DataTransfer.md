# Windows.ApplicationModel.DataTransfer Namespace
 _**\[This is preliminary documentation and is subject to change.\]**_

\[Missing <summary> documentation for "N:Windows.ApplicationModel.DataTransfer"\]


## Classes
&nbsp;<table><tr><th></th><th>Class</th><th>Description</th></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_Windows_ApplicationModel_DataTransfer_Clipboard">Clipboard</a></td><td>
Gets and sets information from the clipboard object.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_Windows_ApplicationModel_DataTransfer_DataPackage">DataPackage</a></td><td>
Contains the data that a user wants to exchange with another app.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_Windows_ApplicationModel_DataTransfer_DataPackagePropertySet">DataPackagePropertySet</a></td><td>
Defines a set of properties to use with a <a href="T_Windows_ApplicationModel_DataTransfer_DataPackage">DataPackage</a> object.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_Windows_ApplicationModel_DataTransfer_DataPackagePropertySetView">DataPackagePropertySetView</a></td><td>
Gets the set of properties of a <a href="T_Windows_ApplicationModel_DataTransfer_DataPackageView">DataPackageView</a> object.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_Windows_ApplicationModel_DataTransfer_DataPackageView">DataPackageView</a></td><td>
A read-only version of a <a href="T_Windows_ApplicationModel_DataTransfer_DataPackage">DataPackage</a>. Apps that receive shared content get this object when acquiring content.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_Windows_ApplicationModel_DataTransfer_DataProviderRequest">DataProviderRequest</a></td><td>
An object of this type is passed to the <a href="T_Windows_ApplicationModel_DataTransfer_DataProviderHandler">DataProviderHandler</a> delegate.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_Windows_ApplicationModel_DataTransfer_DataRequest">DataRequest</a></td><td>
Lets your app supply the content the user wants to share or specify a message, if an error occurs.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_Windows_ApplicationModel_DataTransfer_DataRequestedEventArgs">DataRequestedEventArgs</a></td><td>
Contains information about the DataRequested event. The system fires this event when the user invokes the Share UI.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_Windows_ApplicationModel_DataTransfer_DataTransferManager">DataTransferManager</a></td><td>
Programmatically initiates an exchange of content with other apps.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_Windows_ApplicationModel_DataTransfer_StandardDataFormats">StandardDataFormats</a></td><td>
Contains static properties that return string values. Each string corresponds to a known format ID. Use this class to avoid errors in using string constants to specify data formats.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_Windows_ApplicationModel_DataTransfer_TargetApplicationChosenEventArgs">TargetApplicationChosenEventArgs</a></td><td>
Contains information about the target app the user chose to share content with. To get this object, you must handle the TargetApplicationChosen event.</td></tr></table>

## Delegates
&nbsp;<table><tr><th></th><th>Delegate</th><th>Description</th></tr><tr><td>![Public delegate](media/pubdelegate.gif "Public delegate")</td><td><a href="T_Windows_ApplicationModel_DataTransfer_DataProviderHandler">DataProviderHandler</a></td><td>
Provides data when the target app requests it, instead of including the data in the DataPackage ahead of time. DataProviderHandler is used when the source app wants to avoid unnecessary work that is resource intensive, such as performing format conversions.</td></tr></table>&nbsp;
