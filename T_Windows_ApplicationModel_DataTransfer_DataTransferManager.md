# DataTransferManager Class
 _**\[This is preliminary documentation and is subject to change.\]**_

Programmatically initiates an exchange of content with other apps.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Windows.ApplicationModel.DataTransfer.DataTransferManager<br />
**Namespace:**&nbsp;<a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public class DataTransferManager
```

**VB**<br />
``` VB
Public Class DataTransferManager
```

The DataTransferManager type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7" target="_blank">Finalize</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Windows_ApplicationModel_DataTransfer_DataTransferManager_GetForCurrentView">GetForCurrentView</a></td><td>
Returns the DataTransferManager object associated with the current window.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a" target="_blank">MemberwiseClone</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Windows_ApplicationModel_DataTransfer_DataTransferManager_ShowShareUI">ShowShareUI</a></td><td>
Programmatically initiates the user interface for sharing content with another app.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#datatransfermanager-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Windows_ApplicationModel_DataTransfer_DataTransferManager_DataRequested">DataRequested</a></td><td>
Occurs when a share operation starts.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Windows_ApplicationModel_DataTransfer_DataTransferManager_TargetApplicationChosen">TargetApplicationChosen</a></td><td>
Occurs when the user chooses a target app in a Share operation.</td></tr></table>&nbsp;
<a href="#datatransfermanager-class">Back to Top</a>

## Remarks
The DataTransferManager class is a static class that you use to initiate sharing operations. To use the class, first call the <a href="M_Windows_ApplicationModel_DataTransfer_DataTransferManager_GetForCurrentView">GetForCurrentView()</a> method. This method returns the DataTransferManager object that is specific to the active window. Next, you need to add an event listener for the datarequested event to the object. This event is fired when your app starts a share operation programmatically. 
The DataTransferManager class includes a <a href="M_Windows_ApplicationModel_DataTransfer_DataTransferManager_ShowShareUI">ShowShareUI()</a> method, which you can use to programmatically start a share operation. In general, we recommend against using this method. Users expect to initiate share operations by using the Share charm—when you launch the operation programmatically, you can create an inconsistent user experience. We include the method because there are a few scenarios in which the user might not recognize opportunities to share. A good example is when the user achieves a high score in a game.

The DataTransferManager class also has a <a href="E_Windows_ApplicationModel_DataTransfer_DataTransferManager_TargetApplicationChosen">TargetApplicationChosen</a> event. Use this event when you want to capture what applications a user selects when sharing content from your app.


## See Also


#### Reference
<a href="N_Windows_ApplicationModel_DataTransfer">Windows.ApplicationModel.DataTransfer Namespace</a><br />