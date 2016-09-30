# Geocoordinate.PositionSourceTimestamp Property 
 _**\[This is preliminary documentation and is subject to change.\]**_

Gets the time at which the associated Geocoordinate position was calculated.

**Namespace:**&nbsp;<a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public Nullable<DateTimeOffset> PositionSourceTimestamp { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property PositionSourceTimestamp As Nullable(Of DateTimeOffset)
	Get
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/b3h38hb0" target="_blank">Nullable</a>(<a href="http://msdn2.microsoft.com/en-us/library/bb341783" target="_blank">DateTimeOffset</a>)<br />The time at which the associated Geocoordinate position was calculated.

## Remarks
When this property is not available, the value will be null. 
The timestamp returned by this property depends on how the location was obtained and may be completely unrelated to the system time on the device. For example, if the position is obtained from the Global Navigation Satellite System (GNSS) the timestamp would be obtained from the satellites. If the position was is obtained from Secure User Plane Location (SUPL), the timestamp would be obtained from SUPL servers. This means that the timestamps obtained from these services will be precise and, most importantly, consistent across all devices regardless of whether the system time on the devices is set correctly.


## See Also


#### Reference
<a href="T_Windows_Devices_Geolocation_Geocoordinate">Geocoordinate Class</a><br /><a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation Namespace</a><br />