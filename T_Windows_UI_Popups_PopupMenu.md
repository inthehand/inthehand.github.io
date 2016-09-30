# PopupMenu Class
 _**\[This is preliminary documentation and is subject to change.\]**_

Represents a context menu.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Windows.UI.Popups.PopupMenu<br />
**Namespace:**&nbsp;<a href="N_Windows_UI_Popups">Windows.UI.Popups</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public sealed class PopupMenu
```

**VB**<br />
``` VB
Public NotInheritable Class PopupMenu
```

The PopupMenu type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_UI_Popups_PopupMenu__ctor">PopupMenu</a></td><td>
Creates a new instance of the PopupMenu class.</td></tr></table>&nbsp;
<a href="#popupmenu-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_UI_Popups_PopupMenu_Commands">Commands</a></td><td>
Gets the set of commands that appear in the command bar of the message dialog.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_UI_Popups_PopupMenu_Content">Content</a></td><td>
Gets or sets the message to be displayed to the user.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_UI_Popups_PopupMenu_DefaultCommandIndex">DefaultCommandIndex</a></td><td>
Gets or sets the index of the command you want to use as the default. This is the command that fires by default when users press the ENTER key instead of a specific command, for example.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_UI_Popups_PopupMenu_Title">Title</a></td><td>
Gets or sets the title to display on the dialog box, if any.</td></tr></table>&nbsp;
<a href="#popupmenu-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_UI_Popups_PopupMenu_ShowAsync">ShowAsync</a></td><td>
Shows the context menu at the specified client coordinates.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_UI_Popups_PopupMenu_ShowForSelectionAsync">ShowForSelectionAsync(Rect)</a></td><td>
Shows the context menu by the specified selection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_UI_Popups_PopupMenu_ShowForSelectionAsync_1">ShowForSelectionAsync(Rect, Placement)</a></td><td>
Shows the context menu in the preferred placement relative to the specified selection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#popupmenu-class">Back to Top</a>

## Remarks
Context menus can show a maximum of six commands. This limit helps to ensure that the context menu remains uncluttered, usable, and directly relevant to users.

## See Also


#### Reference
<a href="N_Windows_UI_Popups">Windows.UI.Popups Namespace</a><br />