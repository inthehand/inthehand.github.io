# DeviceCapability Enumeration
 _**\[This is preliminary documentation and is subject to change.\]**_

Device capabilities allow your app to access peripheral and internal devices. Device capabilities are specified with the DeviceCapability element in your app package manifest. This element may require additional child elements and some device capabilities need to be added to the package manifest manually

**Namespace:**&nbsp;<a href="N_InTheHand_ApplicationModel">InTheHand.ApplicationModel</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum DeviceCapability
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration DeviceCapability
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:InTheHand.ApplicationModel.DeviceCapability.Location">**Location**</td><td>0</td><td>The Location capability provides access to location functionality, which you get from dedicated hardware like a GPS sensor in the PC or is derived from available network info. Apps must handle the case where the user has disabled location services from settings.</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.DeviceCapability.Microphone">**Microphone**</td><td>1</td><td>The Microphone capability provides access to the microphone’s audio feed, which allows the app to record audio from connected microphones.</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.DeviceCapability.Proximity">**Proximity**</td><td>2</td><td>The Proximity capability enables multiple devices in close proximity to communicate with one another. This capability is typically used in casual multi-player games and in apps that exchange information. Devices attempt to use the communication technology that provides the best possible connection, including Bluetooth, WiFi, and the internet. This capability is used only to initiate communication between the devices.</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.DeviceCapability.Camera">**Camera**</td><td>3</td><td>The Camera capability provides access to the video feed of a built-in camera or external webcam, which allows the app to capture photos and videos. On Windows, apps must handle the case where the user has disabled the camera from the Settings charm.</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.DeviceCapability.Usb">**Usb**</td><td>4</td><td>The Usb device capability enables access to APIs in the Windows.Devices.Usb namespace. By using the namespace, you can write an app that talks to a custom USB device. "Custom" in this context means, a peripheral device for which Microsoft does not provide an in-box class driver.</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.DeviceCapability.HumanInterfaceDevice">**HumanInterfaceDevice**</td><td>5</td><td>The HumanInterfaceDevice device capability enables access to APIs in the Windows.Devices.HumanInterfaceDevice namespace. This namespace lets your app access devices that support the Human Interface Device (HID) protocol.</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.DeviceCapability.Bluetooth">**Bluetooth**</td><td>6</td><td>The bluetooth device capability enables access to APIs in the Windows.Devices.Bluetooth.GenericAttributeProfile and Windows.Devices.Bluetooth.Rfcomm namespaces.</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.DeviceCapability.PointOfService">**PointOfService**</td><td>7</td><td>The PointOfService device capability enables access to APIs in the Windows.Devices.PointOfService namespace. This namespace lets your Windows Store app access Point of Service (POS) barcode scanners and magnetic stripe readers. The namespace provides a vendor-neutral interface for accessing POS devices from various manufacturers from a Windows Store app.</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.DeviceCapability.Sensors">**Sensors**</td><td>8</td><td>Application requires access to the accelerometer. 
Silverlight Only</td></tr></table>

## See Also


#### Reference
<a href="N_InTheHand_ApplicationModel">InTheHand.ApplicationModel Namespace</a><br />