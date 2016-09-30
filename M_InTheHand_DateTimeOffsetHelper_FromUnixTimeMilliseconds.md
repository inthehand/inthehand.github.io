# DateTimeOffsetHelper.FromUnixTimeMilliseconds Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Converts a Unix time expressed as the number of milliseconds that have elapsed since 1970-01-01T00:00:00Z to a <a href="http://msdn2.microsoft.com/en-us/library/bb341783" target="_blank">DateTimeOffset</a> value.

**Namespace:**&nbsp;<a href="N_InTheHand">InTheHand</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static DateTimeOffset FromUnixTimeMilliseconds(
	long milliseconds
)
```

**VB**<br />
``` VB
Public Shared Function FromUnixTimeMilliseconds ( 
	milliseconds As Long
) As DateTimeOffset
```


#### Parameters
&nbsp;<dl><dt>milliseconds</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/6yy583ek" target="_blank">System.Int64</a><br />A Unix time, expressed as the number of milliseconds that have elapsed since 1970-01-01T00:00:00Z (January 1, 1970, at 12:00 AM UTC). For Unix times before this date, its value is negative.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/bb341783" target="_blank">DateTimeOffset</a><br />A date and time value that represents the same moment in time as the Unix time.

## See Also


#### Reference
<a href="T_InTheHand_DateTimeOffsetHelper">DateTimeOffsetHelper Class</a><br /><a href="N_InTheHand">InTheHand Namespace</a><br />