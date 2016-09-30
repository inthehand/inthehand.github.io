# ChatMessageManager.ShowComposeSmsMessageAsync Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Shows the compose SMS dialog, pre-populated with data from the supplied ChatMessage object, allowing the user to send an SMS message.

**Namespace:**&nbsp;<a href="N_Windows_ApplicationModel_Chat">Windows.ApplicationModel.Chat</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public static IAsyncAction ShowComposeSmsMessageAsync(
	ChatMessage message
)
```

**VB**<br />
``` VB
Public Shared Function ShowComposeSmsMessageAsync ( 
	message As ChatMessage
) As IAsyncAction
```


#### Parameters
&nbsp;<dl><dt>message</dt><dd>Type: <a href="T_Windows_ApplicationModel_Chat_ChatMessage">Windows.ApplicationModel.Chat.ChatMessage</a><br />The chat message.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncAction">IAsyncAction</a><br />An asynchronous action.

## See Also


#### Reference
<a href="T_Windows_ApplicationModel_Chat_ChatMessageManager">ChatMessageManager Class</a><br /><a href="N_Windows_ApplicationModel_Chat">Windows.ApplicationModel.Chat Namespace</a><br />