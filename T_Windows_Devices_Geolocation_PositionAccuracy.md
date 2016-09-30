# PositionAccuracy Enumeration
 _**\[This is preliminary documentation and is subject to change.\]**_

Indicates the requested accuracy level for the location data that the application uses.

**Namespace:**&nbsp;<a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public enum PositionAccuracy
```

**VB**<br />
``` VB
Public Enumeration PositionAccuracy
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:Windows.Devices.Geolocation.PositionAccuracy.Default">**Default**</td><td>0</td><td>Optimize for power, performance, and other cost considerations.</td></tr><tr><td /><td target="F:Windows.Devices.Geolocation.PositionAccuracy.High">**High**</td><td>1</td><td>Deliver the most accurate report possible. This includes using services that might charge money, or consuming higher levels of battery power or connection bandwidth. An accuracy level of High may degrade system performance and should be used only when necessary.</td></tr></table>

## See Also


#### Reference
<a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation Namespace</a><br />