# EmailManager.ShowComposeNewEmailAsync Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Launches the email application with a new message displayed.

**Namespace:**&nbsp;<a href="N_Windows_ApplicationModel_Email">Windows.ApplicationModel.Email</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static IAsyncAction ShowComposeNewEmailAsync(
	EmailMessage message
)
```

**VB**<br />
``` VB
Public Shared Function ShowComposeNewEmailAsync ( 
	message As EmailMessage
) As IAsyncAction
```


#### Parameters
&nbsp;<dl><dt>message</dt><dd>Type: <a href="T_Windows_ApplicationModel_Email_EmailMessage">Windows.ApplicationModel.Email.EmailMessage</a><br />The email message that is displayed when the email application is launched.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncAction">IAsyncAction</a><br />An asynchronous action used to indicate when the operation has completed.

## See Also


#### Reference
<a href="T_Windows_ApplicationModel_Email_EmailManager">EmailManager Class</a><br /><a href="N_Windows_ApplicationModel_Email">Windows.ApplicationModel.Email Namespace</a><br />