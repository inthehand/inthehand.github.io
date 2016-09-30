# VibrationDevice Class
 _**\[This is preliminary documentation and is subject to change.\]**_

Vibrates the phone.


## Inheritance Hierarchy
<a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">System.Object</a><br />&nbsp;&nbsp;Windows.Phone.Devices.Notification.VibrationDevice<br />
**Namespace:**&nbsp;<a href="N_Windows_Phone_Devices_Notification">Windows.Phone.Devices.Notification</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public sealed class VibrationDevice
```

**VB**<br />
``` VB
Public NotInheritable Class VibrationDevice
```

The VibrationDevice type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Phone_Devices_Notification_VibrationDevice_Cancel">Cancel</a></td><td>
Stops the vibration of the phone.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47" target="_blank">Equals</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_Windows_Phone_Devices_Notification_VibrationDevice_GetDefault">GetDefault</a></td><td>
Gets an instance of the VibrationDevice class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y" target="_blank">GetHashCode</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9" target="_blank">GetType</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2" target="_blank">ToString</a></td><td> (Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Windows_Phone_Devices_Notification_VibrationDevice_Vibrate">Vibrate</a></td><td>
Vibrates the phone for the specified duration (from 0 to 5 seconds).</td></tr></table>&nbsp;
<a href="#vibrationdevice-class">Back to Top</a>

## Remarks
Phone devices include a vibration controller. Your app can vibrate the phone for up to 5 seconds to notify the user of an important event. Use the vibration feature in moderation. Do not rely on the vibration feature for critical notifications, because the user can disable vibration 
To test an app that uses the vibration controller effectively, you have to test it on a physical device. The emulator cannot simulate vibration and does not provide any audible or visual feedback that vibration is occurring. 
An app that is running in the background cannot vibrate the phone.
 If your code tries to use vibration while the app is running in the background, nothing happens, but no exception is raised. If you want to vibrate the phone while your app is running in the background, you have to implement a toast notification.


## See Also


#### Reference
<a href="N_Windows_Phone_Devices_Notification">Windows.Phone.Devices.Notification Namespace</a><br />