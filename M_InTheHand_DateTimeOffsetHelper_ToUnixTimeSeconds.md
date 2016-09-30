# DateTimeOffsetHelper.ToUnixTimeSeconds Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Returns the number of seconds that have elapsed since 1970-01-01T00:00:00Z.

**Namespace:**&nbsp;<a href="N_InTheHand">InTheHand</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static long ToUnixTimeSeconds(
	this DateTimeOffset date
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
Public Shared Function ToUnixTimeSeconds ( 
	date As DateTimeOffset
) As Long
```


#### Parameters
&nbsp;<dl><dt>date</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/bb341783" target="_blank">System.DateTimeOffset</a><br />The DateTimeOffset value.</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/6yy583ek" target="_blank">Int64</a><br />The number of seconds that have elapsed since 1970-01-01T00:00:00Z.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type <a href="http://msdn2.microsoft.com/en-us/library/bb341783" target="_blank">DateTimeOffset</a>. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="http://msdn.microsoft.com/en-us/library/bb384936.aspx">Extension Methods (Visual Basic)</a> or <a href="http://msdn.microsoft.com/en-us/library/bb383977.aspx">Extension Methods (C# Programming Guide)</a>.

## Remarks
Unix time represents the number of seconds that have elapsed since 1970-01-01T00:00:00Z (January 1, 1970, at 12:00 AM UTC). It does not take leap seconds into account. 
This method first converts the current instance to UTC before returning its Unix time. For date and time values before 1970-01-01T00:00:00Z, this method returns a negative value.


## See Also


#### Reference
<a href="T_InTheHand_DateTimeOffsetHelper">DateTimeOffsetHelper Class</a><br /><a href="N_InTheHand">InTheHand Namespace</a><br />