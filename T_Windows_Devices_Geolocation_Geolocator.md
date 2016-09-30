# Geolocator Class
 _**\[This is preliminary documentation and is subject to change.\]**_

Provides access to the current geographic location.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Windows.Devices.Geolocation.Geolocator<br />
**Namespace:**&nbsp;<a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public sealed class Geolocator
```

**VB**<br />
``` VB
Public NotInheritable Class Geolocator
```

The Geolocator type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Devices_Geolocation_Geolocator__ctor">Geolocator</a></td><td>
Initializes a new Geolocator object.</td></tr></table>&nbsp;
<a href="#geolocator-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Devices_Geolocation_Geolocator_DesiredAccuracy">DesiredAccuracy</a></td><td>
The accuracy level at which the Geolocator provides location updates.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Devices_Geolocation_Geolocator_LocationStatus">LocationStatus</a></td><td>
The status that indicates the ability of the Geolocator to provide location updates.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Devices_Geolocation_Geolocator_MovementThreshold">MovementThreshold</a></td><td>
Gets and sets the distance of movement, in meters, relative to the coordinate from the last PositionChanged event, that is required for the Geolocator to raise a PositionChanged event.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Devices_Geolocation_Geolocator_ReportInterval">ReportInterval</a></td><td>
The requested minimum time interval between location updates, in milliseconds. If your application requires updates infrequently, set this value so that you only receive location updates when needed.</td></tr></table>&nbsp;
<a href="#geolocator-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Devices_Geolocation_Geolocator_GetGeopositionAsync">GetGeopositionAsync</a></td><td>
Starts an asynchronous operation to retrieve the current location of the device.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#geolocator-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Windows_Devices_Geolocation_Geolocator_PositionChanged">PositionChanged</a></td><td>
Raised when the location is updated.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Windows_Devices_Geolocation_Geolocator_StatusChanged">StatusChanged</a></td><td>
Raised when the ability of the Geolocator to provide updated location changes.</td></tr></table>&nbsp;
<a href="#geolocator-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation Namespace</a><br />