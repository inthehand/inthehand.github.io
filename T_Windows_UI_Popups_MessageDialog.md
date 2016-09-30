# MessageDialog Class
 _**\[This is preliminary documentation and is subject to change.\]**_

Represents a dialog.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Windows.UI.Popups.MessageDialog<br />
**Namespace:**&nbsp;<a href="N_Windows_UI_Popups">Windows.UI.Popups</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public sealed class MessageDialog
```

**VB**<br />
``` VB
Public NotInheritable Class MessageDialog
```

The MessageDialog type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_UI_Popups_MessageDialog__ctor">MessageDialog(String)</a></td><td>
Initializes a new instance of the MessageDialog class to display an untitled message dialog box that can be used to ask your user simple questions.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_UI_Popups_MessageDialog__ctor_1">MessageDialog(String, String)</a></td><td>
Initializes a new instance of the MessageDialog class to display a titled message dialog box that can be used to ask your user simple questions.</td></tr></table>&nbsp;
<a href="#messagedialog-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_UI_Popups_MessageDialog_Commands">Commands</a></td><td>
Gets the set of commands that appear in the command bar of the message dialog.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_UI_Popups_MessageDialog_Content">Content</a></td><td>
Gets or sets the message to be displayed to the user.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_UI_Popups_MessageDialog_DefaultCommandIndex">DefaultCommandIndex</a></td><td>
Gets or sets the index of the command you want to use as the default. This is the command that fires by default when users press the ENTER key instead of a specific command, for example.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_UI_Popups_MessageDialog_Title">Title</a></td><td>
Gets or sets the title to display on the dialog box, if any.</td></tr></table>&nbsp;
<a href="#messagedialog-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_UI_Popups_MessageDialog_ShowAsync">ShowAsync</a></td><td>
Begins an asynchronous operation showing a dialog.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#messagedialog-class">Back to Top</a>

## Remarks
The dialog has a command bar that can support up to three commands. If you don't specify any commands, then a default command is added to close the dialog. 
The dialog dims the screen behind it and blocks touch events from passing to the app's canvas until the user responds.

Message dialogs should be used sparingly, and only for critical messages or simple questions that must block the user's flow.


## See Also


#### Reference
<a href="N_Windows_UI_Popups">Windows.UI.Popups Namespace</a><br />