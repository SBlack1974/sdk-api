---
UID: NF:strmif.IAMTVAudio.UnRegisterNotificationCallBack
title: IAMTVAudio::UnRegisterNotificationCallBack (strmif.h)
description: The UnRegisterNotificationCallBack method unregisters an object for event notifications. (IAMTVAudio.UnRegisterNotificationCallBack)
helpviewer_keywords: ["IAMTVAudio interface [DirectShow]","UnRegisterNotificationCallBack method","IAMTVAudio.UnRegisterNotificationCallBack","IAMTVAudio::UnRegisterNotificationCallBack","IAMTVAudioUnRegisterNotificationCallBack","UnRegisterNotificationCallBack","UnRegisterNotificationCallBack method [DirectShow]","UnRegisterNotificationCallBack method [DirectShow]","IAMTVAudio interface","dshow.iamtvaudio_unregisternotificationcallback","strmif/IAMTVAudio::UnRegisterNotificationCallBack"]
old-location: dshow\iamtvaudio_unregisternotificationcallback.htm
tech.root: dshow
ms.assetid: 17a2f882-f6a8-467d-a6f9-eb8e6309e878
ms.date: 4/26/2023
ms.keywords: IAMTVAudio interface [DirectShow],UnRegisterNotificationCallBack method, IAMTVAudio.UnRegisterNotificationCallBack, IAMTVAudio::UnRegisterNotificationCallBack, IAMTVAudioUnRegisterNotificationCallBack, UnRegisterNotificationCallBack, UnRegisterNotificationCallBack method [DirectShow], UnRegisterNotificationCallBack method [DirectShow],IAMTVAudio interface, dshow.iamtvaudio_unregisternotificationcallback, strmif/IAMTVAudio::UnRegisterNotificationCallBack
req.header: strmif.h
req.include-header: Dshow.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Strmiids.lib
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IAMTVAudio::UnRegisterNotificationCallBack
 - strmif/IAMTVAudio::UnRegisterNotificationCallBack
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Strmiids.lib
 - Strmiids.dll
api_name:
 - IAMTVAudio.UnRegisterNotificationCallBack
---

# IAMTVAudio::UnRegisterNotificationCallBack


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>UnRegisterNotificationCallBack</code> method unregisters an object for event notifications.



This method is not implemented.

## -parameters

### -param pNotify [in]

Pointer to the <a href="/windows/desktop/api/strmif/nn-strmif-iamtunernotification">IAMTunerNotification</a> interface that was specified in a previous call to <b>RegisterNotificationCallBack</b>.

## -returns

Returns E_NOTIMPL.

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/strmif/nn-strmif-iamtvaudio">IAMTVAudio Interface</a>
