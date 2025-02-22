---
UID: NF:iwstdec.IAMWstDecoder.GetBackgroundColor
title: IAMWstDecoder::GetBackgroundColor (iwstdec.h)
description: Downstream filters use the GetBackgroundColor method to retrieve the current physical color used in color keying the background for overlay mixing.
helpviewer_keywords: ["GetBackgroundColor","GetBackgroundColor method [DirectShow]","GetBackgroundColor method [DirectShow]","IAMWstDecoder interface","IAMWstDecoder interface [DirectShow]","GetBackgroundColor method","IAMWstDecoder.GetBackgroundColor","IAMWstDecoder::GetBackgroundColor","IAMWstDecoderGetBackgroundColor","dshow.iamwstdecoder_getbackgroundcolor","iwstdec/IAMWstDecoder::GetBackgroundColor"]
old-location: dshow\iamwstdecoder_getbackgroundcolor.htm
tech.root: dshow
ms.assetid: 1661f2cd-8e6c-4e55-b5fd-995ef2962cb7
ms.date: 4/26/2023
ms.keywords: GetBackgroundColor, GetBackgroundColor method [DirectShow], GetBackgroundColor method [DirectShow],IAMWstDecoder interface, IAMWstDecoder interface [DirectShow],GetBackgroundColor method, IAMWstDecoder.GetBackgroundColor, IAMWstDecoder::GetBackgroundColor, IAMWstDecoderGetBackgroundColor, dshow.iamwstdecoder_getbackgroundcolor, iwstdec/IAMWstDecoder::GetBackgroundColor
req.header: iwstdec.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
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
 - IAMWstDecoder::GetBackgroundColor
 - iwstdec/IAMWstDecoder::GetBackgroundColor
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
 - IAMWstDecoder.GetBackgroundColor
---

# IAMWstDecoder::GetBackgroundColor


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

Downstream filters use the <code>GetBackgroundColor</code> method to retrieve the current physical color used in color keying the background for overlay mixing.

## -parameters

### -param pdwPhysColor [out]

Receives the physical color as an RGB value.

## -returns

When the method succeeds, it returns S_OK. Otherwise, it returns an <b>HRESULT</b> error code.

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/iwstdec/nn-iwstdec-iamwstdecoder">IAMWstDecoder Interface</a>