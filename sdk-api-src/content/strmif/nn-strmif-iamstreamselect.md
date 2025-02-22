---
UID: NN:strmif.IAMStreamSelect
title: IAMStreamSelect (strmif.h)
description: The IAMStreamSelect interface selects from the available streams on a parser filter.
helpviewer_keywords: ["IAMStreamSelect","IAMStreamSelect interface [DirectShow]","IAMStreamSelect interface [DirectShow]","described","IAMStreamSelectInterface","dshow.iamstreamselect","strmif/IAMStreamSelect"]
old-location: dshow\iamstreamselect.htm
tech.root: dshow
ms.assetid: a305e91e-f506-4bd1-b4d4-7361df89e158
ms.date: 4/26/2023
ms.keywords: IAMStreamSelect, IAMStreamSelect interface [DirectShow], IAMStreamSelect interface [DirectShow],described, IAMStreamSelectInterface, dshow.iamstreamselect, strmif/IAMStreamSelect
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
 - IAMStreamSelect
 - strmif/IAMStreamSelect
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
 - IAMStreamSelect
---

# IAMStreamSelect interface


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>IAMStreamSelect</code> interface selects from the available streams on a parser filter. For example, a file might contain audio streams encoded in several languages, such as English, German, and French. The application could use this interface to select which language is played.

## -inheritance

The <b>IAMStreamSelect</b> interface inherits from the <a href="/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IAMStreamSelect</b> also has these types of members:

## -remarks

The following filters implement this interface:

<ul>
<li>
<a href="/windows/desktop/DirectShow/mpeg-1-stream-splitter-filter">MPEG-1 Stream Splitter</a> filter</li>
<li>
<a href="/windows/desktop/DirectShow/mpeg-2-splitter">MPEG-2 Splitter</a> filter</li>
<li>
<a href="/windows/desktop/DirectShow/sami--cc--parser-filter">SAMI (CC) Parser</a> filter</li>
</ul>
