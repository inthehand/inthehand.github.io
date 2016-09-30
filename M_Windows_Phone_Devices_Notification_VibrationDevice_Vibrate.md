# VibrationDevice.Vibrate Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Vibrates the phone for the specified duration (from 0 to 5 seconds).

**Namespace:**&nbsp;<a href="N_Windows_Phone_Devices_Notification">Windows.Phone.Devices.Notification</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public void Vibrate(
	TimeSpan duration
)
```

**VB**<br />
``` VB
Public Sub Vibrate ( 
	duration As TimeSpan
)
```


#### Parameters
&nbsp;<dl><dt>duration</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/269ew577" target="_blank">System.TimeSpan</a><br />The duration (from 0 to 5 seconds) for which the phone vibrates. A value that is less than 0 or greater than 5 raises an exception. Ignored on iOS.</dd></dl>

## See Also


#### Reference
<a href="T_Windows_Phone_Devices_Notification_VibrationDevice">VibrationDevice Class</a><br /><a href="N_Windows_Phone_Devices_Notification">Windows.Phone.Devices.Notification Namespace</a><br />