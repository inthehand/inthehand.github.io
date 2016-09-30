# PositionStatus Enumeration
 _**\[This is preliminary documentation and is subject to change.\]**_

Indicates the ability of the Geolocator object to provide location data.

**Namespace:**&nbsp;<a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public enum PositionStatus
```

**VB**<br />
``` VB
Public Enumeration PositionStatus
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:Windows.Devices.Geolocation.PositionStatus.Ready">**Ready**</td><td>0</td><td>Location data is available.</td></tr><tr><td /><td target="F:Windows.Devices.Geolocation.PositionStatus.Initializing">**Initializing**</td><td>1</td><td>Location services is initializing. This is the status if a GPS is the source of location data and the GPS receiver does not yet have the required number of satellites in view to obtain an accurate position.</td></tr><tr><td /><td target="F:Windows.Devices.Geolocation.PositionStatus.NoData">**NoData**</td><td>2</td><td>No location data is available from any source.</td></tr><tr><td /><td target="F:Windows.Devices.Geolocation.PositionStatus.Disabled">**Disabled**</td><td>3</td><td>Location settings are turned off. This status indicates that the user has not granted the application permission to access location.</td></tr><tr><td /><td target="F:Windows.Devices.Geolocation.PositionStatus.NotInitialized">**NotInitialized**</td><td>4</td><td>An operation to retrieve location has not yet been initialized. LocationStatus will have this value if the application has not yet called GetGeopositionAsync or registered an event handler for the PositionChanged event. LocationStatus may also have this value if your app doesn’t have permission to access location.</td></tr><tr><td /><td target="F:Windows.Devices.Geolocation.PositionStatus.NotAvailable">**NotAvailable**</td><td>5</td><td>Location services is not available on this version of Windows.</td></tr></table>

## See Also


#### Reference
<a href="N_Windows_Devices_Geolocation">Windows.Devices.Geolocation Namespace</a><br />