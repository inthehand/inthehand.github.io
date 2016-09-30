# GeofenceMonitor Class
 _**\[This is preliminary documentation and is subject to change.\]**_

Contains the information about the monitored Geofence objects.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Windows.Devices.Geolocation.Geofencing.GeofenceMonitor<br />
**Namespace:**&nbsp;<a href="N_Windows_Devices_Geolocation_Geofencing">Windows.Devices.Geolocation.Geofencing</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public sealed class GeofenceMonitor
```

**VB**<br />
``` VB
Public NotInheritable Class GeofenceMonitor
```

The GeofenceMonitor type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_Windows_Devices_Geolocation_Geofencing_GeofenceMonitor_Current">Current</a></td><td>
Gets the GeofenceMonitor object which contains all of an app's <a href="T_Windows_Devices_Geolocation_Geofencing_Geofence">Geofence</a> information.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Devices_Geolocation_Geofencing_GeofenceMonitor_Geofences">Geofences</a></td><td>
Returns a vector of the app's <a href="T_Windows_Devices_Geolocation_Geofencing_Geofence">Geofence</a> objects currently registered with the system wide GeofenceMonitor.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Devices_Geolocation_Geofencing_GeofenceMonitor_LastKnownGeoposition">LastKnownGeoposition</a></td><td>
Last reading of the device's location.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Windows_Devices_Geolocation_Geofencing_GeofenceMonitor_Status">Status</a></td><td>
Indicates the current state of the GeofenceMonitor.</td></tr></table>&nbsp;
<a href="#geofencemonitor-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Devices_Geolocation_Geofencing_GeofenceMonitor_ReadReports">ReadReports</a></td><td>
Gets a collection of status changes to the <a href="T_Windows_Devices_Geolocation_Geofencing_Geofence">Geofence</a> objects in the Geofences collection of the GeofenceMonitor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr></table>&nbsp;
<a href="#geofencemonitor-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Windows_Devices_Geolocation_Geofencing_GeofenceMonitor_GeofenceStateChanged">GeofenceStateChanged</a></td><td>
Raised when the state of one or more <a href="T_Windows_Devices_Geolocation_Geofencing_Geofence">Geofence</a> objects in the Geofences collection of the GeofenceMonitor has changed.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_Windows_Devices_Geolocation_Geofencing_GeofenceMonitor_StatusChanged">StatusChanged</a></td><td>
Raised when the status of the GeofenceMonitor has changed.</td></tr></table>&nbsp;
<a href="#geofencemonitor-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Windows_Devices_Geolocation_Geofencing">Windows.Devices.Geolocation.Geofencing Namespace</a><br />