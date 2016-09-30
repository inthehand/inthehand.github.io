# Geocoordinate.Accuracy Property 
 _**\[This is preliminary documentation and is subject to change.\]**_

The accuracy of the location in meters.

**Namespace:**&nbsp;<a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public double Accuracy { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Accuracy As Double
	Get
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/643eft0t" target="_blank">Double</a><br />The accuracy in meters.

## Remarks
The Windows Location Provider and the Windows Phone Location Services accuracy depends on the location data available. For example,iIf Wifi is available, data is accurate to within 50 meters. If Wifi is not available, the data could be accurate to within 10 miles or larger. A GNSS device can provide data accurate to within a few meters. However, its accuracy can vary if the GNSS sensor is obscured by buildings, trees, or cloud cover. GNSS data may not be available at all within a building.

## See Also


#### Reference
<a href="T_Windows_Devices_Geolocation_Geocoordinate">Geocoordinate Class</a><br /><a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation Namespace</a><br />