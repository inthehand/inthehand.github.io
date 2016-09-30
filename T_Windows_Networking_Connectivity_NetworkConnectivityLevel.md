# NetworkConnectivityLevel Enumeration
 _**\[This is preliminary documentation and is subject to change.\]**_

Defines the level of connectivity currently available.

**Namespace:**&nbsp;<a href="N_Windows_Networking_Connectivity">Windows.Networking.Connectivity</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public enum NetworkConnectivityLevel
```

**VB**<br />
``` VB
Public Enumeration NetworkConnectivityLevel
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:Windows.Networking.Connectivity.NetworkConnectivityLevel.None">**None**</td><td>0</td><td>No connectivity.</td></tr><tr><td /><td target="F:Windows.Networking.Connectivity.NetworkConnectivityLevel.LocalAccess">**LocalAccess**</td><td>1</td><td>Local network access only.</td></tr><tr><td /><td target="F:Windows.Networking.Connectivity.NetworkConnectivityLevel.ConstrainedInternetAccess">**ConstrainedInternetAccess**</td><td>2</td><td>Limited internet access. 
This value indicates captive portal connectivity, where local access to a web portal is provided, but access to the Internet requires that specific credentials are provided via the portal. This level of connectivity is generally encountered when using connections hosted in public locations (e.g. coffee shops and book stores).
 Note This doesn't guarantee detection of a captive portal. Windows Store apps should also test if the captive portal can be reached using a URL for the captive portal, or by attempting access to a public web site which will then redirect to the captive portal when Windows reports LocalAccess as the current NetworkConnectivityLevel.</td></tr><tr><td /><td target="F:Windows.Networking.Connectivity.NetworkConnectivityLevel.InternetAccess">**InternetAccess**</td><td>3</td><td>Local and Internet access.</td></tr></table>

## See Also


#### Reference
<a href="N_Windows_Networking_Connectivity">Windows.Networking.Connectivity Namespace</a><br />