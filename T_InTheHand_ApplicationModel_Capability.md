# Capability Enumeration
 _**\[This is preliminary documentation and is subject to change.\]**_

Application Capabilities

**Namespace:**&nbsp;<a href="N_InTheHand_ApplicationModel">InTheHand.ApplicationModel</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum Capability
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration Capability
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:InTheHand.ApplicationModel.Capability.Appointments">**Appointments**</td><td>0</td><td>The Appointments capability provides access to the user’s appointment store. This capability allows read access to appointments obtained from the synced network accounts and to other apps that write to the appointment store With this capability, your app can create new calendars and write appointments to calendars that it creates.</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.Capability.Contacts">**Contacts**</td><td>1</td><td>The Contacts capability provides access to the aggregated view of the contacts from various contacts stores. This capability gives the app limited access (network permitting rules apply) to contacts that were synced from various networks and the local contact store.</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.Capability.Music">**Music**</td><td>2</td><td>The MusicLibrary capability provides programmatic access to the user's Music, allowing the app to enumerate and access all files in the library without user interaction This capability is typically used in jukebox apps that need to access the entire Music library.</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.Capability.Pictures">**Pictures**</td><td>3</td><td>The PicturesLibrary capability provides programmatic access to the user's Pictures, allowing the app to enumerate and access all files in the library without user interaction. This capability is typically used in photo playback apps that need to access the entire Pictures library.</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.Capability.Videos">**Videos**</td><td>4</td><td>The VideosLibrary capability provides programmatic access to the user's Videos, allowing the app to enumerate and access all files in the library without user interaction. This capability is typically used in movie playback apps that need access to the entire Videos library.</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.Capability.Internet">**Internet**</td><td>5</td><td>Application requires network access.</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.Capability.PhoneDialer">**PhoneDialer**</td><td>6</td><td>Application requires the ability to make phone calls. 
Silverlight Only</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.Capability.PushNotification">**PushNotification**</td><td>7</td><td>Application requires access to push notifications. 
Silverlight Only</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.Capability.RemovableStorage">**RemovableStorage**</td><td>8</td><td>The RemovableStorage capability provides programmatic access to files on removable storage, such as USB keys and external hard drives, filtered to the file type associations declared in the package manifest. For example, if a DOC reader app declared a .doc file type association, it can open .doc files on the removable storage device, but not other types of files. Be careful when declaring this capability, because users may include a variety of info in their removable storage devices, and will expect the app to provide a valid justification for programmatic access to the removable storage for the entire file type.</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.Capability.SpeechRecognition">**SpeechRecognition**</td><td>9</td><td>
Silverlight Only</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.Capability.Voip">**Voip**</td><td>10</td><td>
Silverlight Only</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.Capability.Wallet">**Wallet**</td><td>11</td><td>
Silverlight Only</td></tr><tr><td /><td target="F:InTheHand.ApplicationModel.Capability.EnterpriseAuthentication">**EnterpriseAuthentication**</td><td>12</td><td /></tr><tr><td /><td target="F:InTheHand.ApplicationModel.Capability.SharedUserCertificates">**SharedUserCertificates**</td><td>13</td><td /></tr><tr><td /><td target="F:InTheHand.ApplicationModel.Capability.DocumentsLibrary">**DocumentsLibrary**</td><td>14</td><td>The DocumentsLibrary capability provides programmatic access to the user's Documents, filtered to the file type associations declared in the package manifest, to support offline access to OneDrive. For example, if a DOC reader app declared a .doc file type association, it can open .doc files in Documents, but not other types of files.</td></tr></table>

## See Also


#### Reference
<a href="N_InTheHand_ApplicationModel">InTheHand.ApplicationModel Namespace</a><br />