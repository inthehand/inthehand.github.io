# Geocoordinate Class
 _**\[This is preliminary documentation and is subject to change.\]**_

Contains the information for identifying a geographic location.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Windows.Devices.Geolocation.Geocoordinate<br />
**Namespace:**&nbsp;<a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public sealed class Geocoordinate
```

**VB**<br />
``` VB
Public NotInheritable Class Geocoordinate
```

The Geocoordinate type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Devices_Geolocation_Geocoordinate__ctor">Geocoordinate</a></td><td>
Initializes a new instance of the Geocoordinate class</td></tr></table>&nbsp;
<a href="#geocoordinate-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Devices_Geolocation_Geocoordinate_Accuracy">Accuracy</a></td><td>
The accuracy of the location in meters.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Devices_Geolocation_Geocoordinate_AltitudeAccuracy">AltitudeAccuracy</a></td><td>
The accuracy of the altitude, in meters.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Devices_Geolocation_Geocoordinate_Heading">Heading</a></td><td>
The current heading in degrees relative to true north.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Devices_Geolocation_Geocoordinate_Point">Point</a></td><td>
The location of the Geocoordinate.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Devices_Geolocation_Geocoordinate_PositionSource">PositionSource</a></td><td>
Gets the source used to obtain a Geocoordinate.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Devices_Geolocation_Geocoordinate_PositionSourceTimestamp">PositionSourceTimestamp</a></td><td>
Gets the time at which the associated Geocoordinate position was calculated.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Devices_Geolocation_Geocoordinate_Speed">Speed</a></td><td>
The speed in meters per second.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Devices_Geolocation_Geocoordinate_Timestamp">Timestamp</a></td><td>
The system time at which the location was determined.</td></tr></table>&nbsp;
<a href="#geocoordinate-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#geocoordinate-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_InTheHand_Devices_Geolocation_GeocoordinateExtensions_GetDistanceTo">GetDistanceTo</a></td><td>
Returns the distance between the latitude and longitude coordinates that are specified by this Geocoordinate and another specified Geocoordinate.
 (Defined by <a href="T_InTheHand_Devices_Geolocation_GeocoordinateExtensions">GeocoordinateExtensions</a>.)</td></tr></table>&nbsp;
<a href="#geocoordinate-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation Namespace</a><br />