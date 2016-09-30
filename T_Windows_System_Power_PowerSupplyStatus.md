# PowerSupplyStatus Enumeration
 _**\[This is preliminary documentation and is subject to change.\]**_

Represents the device's power supply status.

**Namespace:**&nbsp;<a href="N_Windows_System_Power">Windows.System.Power</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public enum PowerSupplyStatus
```

**VB**<br />
``` VB
Public Enumeration PowerSupplyStatus
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:Windows.System.Power.PowerSupplyStatus.NotPresent">**NotPresent**</td><td>0</td><td>The device has no power supply.</td></tr><tr><td /><td target="F:Windows.System.Power.PowerSupplyStatus.Inadequate">**Inadequate**</td><td>1</td><td>The device has an inadequate power supply.</td></tr><tr><td /><td target="F:Windows.System.Power.PowerSupplyStatus.Adequate">**Adequate**</td><td>2</td><td>The device has an adequate power supply.</td></tr></table>

## Remarks
An Inadequate status occurs when the power supply is present, but the charge rate is negative. For example, the device is plugged in, but it’s losing charge.

## See Also


#### Reference
<a href="N_Windows_System_Power">Windows.System.Power Namespace</a><br />