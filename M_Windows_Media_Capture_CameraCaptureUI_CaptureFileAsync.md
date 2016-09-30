# CameraCaptureUI.CaptureFileAsync Method 
 _**\[This is preliminary documentation and is subject to change.\]**_

Launches the CameraCaptureUI user interface.

**Namespace:**&nbsp;<a href="N_Windows_Media_Capture">Windows.Media.Capture</a><br />**Assembly:**&nbsp;InTheHand (in InTheHand.dll) Version: 9.0.0.0 (9.2016.9.22)

## Syntax

**C#**<br />
``` C#
public IAsyncOperation<StorageFile> CaptureFileAsync(
	CameraCaptureUIMode mode
)
```

**VB**<br />
``` VB
Public Function CaptureFileAsync ( 
	mode As CameraCaptureUIMode
) As IAsyncOperation(Of StorageFile)
```


#### Parameters
&nbsp;<dl><dt>mode</dt><dd>Type: <a href="T_Windows_Media_Capture_CameraCaptureUIMode">Windows.Media.Capture.CameraCaptureUIMode</a><br />Specifies whether the user interface that will be shown allows the user to capture a photo, capture a video, or capture both photos and videos.</dd></dl>

#### Return Value
Type: <a href="T_Windows_Foundation_IAsyncOperation_1">IAsyncOperation</a>(<a href="T_Windows_Storage_StorageFile">StorageFile</a>)<br />When this operation completes, a StorageFile object is returned.

## See Also


#### Reference
<a href="T_Windows_Media_Capture_CameraCaptureUI">CameraCaptureUI Class</a><br /><a href="N_Windows_Media_Capture">Windows.Media.Capture Namespace</a><br />