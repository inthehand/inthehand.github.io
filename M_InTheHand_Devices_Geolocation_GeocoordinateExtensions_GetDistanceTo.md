# GeocoordinateExtensions.GetDistanceTo Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Returns the distance between the latitude and longitude coordinates that are specified by this <a href="T_Windows_Devices_Geolocation_Geocoordinate">Geocoordinate</a> and another specified <a href="T_Windows_Devices_Geolocation_Geocoordinate">Geocoordinate</a>.

**Namespace:**&nbsp;<a href="N_InTheHand_Devices_Geolocation">InTheHand.Devices.Geolocation</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static double GetDistanceTo(
	this Geocoordinate g,
	Geocoordinate other
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function GetDistanceTo ( 
	g As Geocoordinate,
	other As Geocoordinate
) As Double
```


#### Parameters
&nbsp;<dl><dt>g</dt><dd>Type: <a href="T_Windows_Devices_Geolocation_Geocoordinate">Windows.Devices.Geolocation.Geocoordinate</a><br /></dd><dt>other</dt><dd>Type: <a href="T_Windows_Devices_Geolocation_Geocoordinate">Windows.Devices.Geolocation.Geocoordinate</a><br />The <a href="T_Windows_Devices_Geolocation_Geocoordinate">Geocoordinate</a> for the location to calculate the distance to.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/643eft0t" target="_blank">Double</a><br />The distance between the two coordinates, in meters.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="T_Windows_Devices_Geolocation_Geocoordinate">Geocoordinate</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="http://msdn.microsoft.com/en-us/library/bb384936.aspx">Extension Methods (Visual Basic)</a> or <a href="http://msdn.microsoft.com/en-us/library/bb383977.aspx">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_InTheHand_Devices_Geolocation_GeocoordinateExtensions">GeocoordinateExtensions Class</a><br /><a href="N_InTheHand_Devices_Geolocation">InTheHand.Devices.Geolocation Namespace</a><br />