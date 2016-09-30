# BasicGeoposition Structure
 _**\[This is preliminary documentation and is subject to change.\]**_

The basic information to describe a geographic position.

**Namespace:**&nbsp;<a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public struct BasicGeoposition
```

**VB**<br />
``` VB
Public Structure BasicGeoposition
```

The BasicGeoposition type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/2dts52z7" target="_blank">Equals</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/aey3s293" target="_blank">ValueType</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/y3509fc2" target="_blank">GetHashCode</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/aey3s293" target="_blank">ValueType</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/wb77sz3h" target="_blank">ToString</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/aey3s293" target="_blank">ValueType</a>.)</td></tr></table>&nbsp;
<a href="#basicgeoposition-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_Windows_Devices_Geolocation_BasicGeoposition_Altitude">Altitude</a></td><td>
The altitude of the geographic position in meters.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_Windows_Devices_Geolocation_BasicGeoposition_Latitude">Latitude</a></td><td>
The latitude of the geographic position. The valid range of latitude values is from -90.0 to 90.0 degrees.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_Windows_Devices_Geolocation_BasicGeoposition_Longitude">Longitude</a></td><td>
The longitude of the geographic position. This can be any value. For values less than or equal to-180.0 or values greater than 180.0, the value may be wrapped and stored appropriately before it is used. For example, a longitude of 183.0 degrees would become -177.0 degrees.</td></tr></table>&nbsp;
<a href="#basicgeoposition-structure">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_InTheHand_Devices_Geolocation_BasicGeopositionExtensions_GetDistanceTo">GetDistanceTo</a></td><td>
Returns the distance between the latitude and longitude coordinates that are specified by this BasicGeoposition and another specified BasicGeoposition.
 (Defined by <a href="T_InTheHand_Devices_Geolocation_BasicGeopositionExtensions">BasicGeopositionExtensions</a>.)</td></tr></table>&nbsp;
<a href="#basicgeoposition-structure">Back to Top</a>

## See Also


#### Reference
<a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation Namespace</a><br />