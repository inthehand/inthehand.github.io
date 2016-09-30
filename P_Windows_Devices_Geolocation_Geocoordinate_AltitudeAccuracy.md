# Geocoordinate.AltitudeAccuracy Property 
 _**\[This is preliminary documentation and is subject to change.\]**_

The accuracy of the altitude, in meters.

**Namespace:**&nbsp;<a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public Nullable<double> AltitudeAccuracy { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property AltitudeAccuracy As Nullable(Of Double)
	Get
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/b3h38hb0" target="_blank">Nullable</a>(<a href="http://msdn2.microsoft.com/en-us/library/643eft0t" target="_blank">Double</a>)<br />The accuracy of the altitude.

## Remarks
It is optional for a location provider to set this property. If the property is not provided, the value will be NULL. The Windows Location Provider and the Windows Phone Location Services do not set this property.

## See Also


#### Reference
<a href="T_Windows_Devices_Geolocation_Geocoordinate">Geocoordinate Class</a><br /><a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation Namespace</a><br />