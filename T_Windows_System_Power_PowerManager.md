# PowerManager Class
 _**\[This is preliminary documentation and is subject to change.\]**_

Provides information about the status of the device's battery. 
Only supported for Windows 8.1 apps when deployed to Windows 10 machines.



## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Windows.System.Power.PowerManager<br />
**Namespace:**&nbsp;<a href="N_Windows_System_Power">Windows.System.Power</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static class PowerManager
```

**VB**<br />
``` VB
Public NotInheritable Class PowerManager
```

The PowerManager type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_Windows_System_Power_PowerManager_BatteryStatus">BatteryStatus</a></td><td>
Gets the device's battery status.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_Windows_System_Power_PowerManager_EnergySaverStatus">EnergySaverStatus</a></td><td>
Gets battery saver status, indicating when to save energy.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_Windows_System_Power_PowerManager_RemainingChargePercent">RemainingChargePercent</a></td><td>
Gets the total percentage of charge remaining from all batteries connected to the device. 
Not supported for Windows 8.1 apps deployed via the public Windows Store.</td></tr></table>&nbsp;
<a href="#powermanager-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")![Static member](media/static.gif "Static member")</td><td><a href="E_Windows_System_Power_PowerManager_RemainingChargePercentChanged">RemainingChargePercentChanged</a></td><td>
Occurs when <a href="P_Windows_System_Power_PowerManager_RemainingChargePercent">RemainingChargePercent</a>changes.</td></tr></table>&nbsp;
<a href="#powermanager-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Windows_System_Power">Windows.System.Power Namespace</a><br />