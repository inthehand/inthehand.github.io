# LaunchQuerySupportStatus Enumeration
 _**\[This is preliminary documentation and is subject to change.\]**_

Specifies whether an app is available that supports activation

**Namespace:**&nbsp;<a href="N_Windows_System">Windows.System</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public enum LaunchQuerySupportStatus
```

**VB**<br />
``` VB
Public Enumeration LaunchQuerySupportStatus
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:Windows.System.LaunchQuerySupportStatus.Available">**Available**</td><td>0</td><td>An app that handles the activation is available and may be activated.</td></tr><tr><td /><td target="F:Windows.System.LaunchQuerySupportStatus.AppNotInstalled">**AppNotInstalled**</td><td>1</td><td>No app is installed to handle the activation.</td></tr><tr><td /><td target="F:Windows.System.LaunchQuerySupportStatus.AppUnavailable">**AppUnavailable**</td><td>2</td><td>An app that handles the activation is installed but not available because it is being updated by the store or it was installed on a removable device that is not available.</td></tr><tr><td /><td target="F:Windows.System.LaunchQuerySupportStatus.NotSupported">**NotSupported**</td><td>3</td><td>The app does not handle the activation.</td></tr><tr><td /><td target="F:Windows.System.LaunchQuerySupportStatus.Unknown">**Unknown**</td><td>4</td><td>An unknown error was encountered while determining whether an app supports the activation.</td></tr></table>

## See Also


#### Reference
<a href="N_Windows_System">Windows.System Namespace</a><br />