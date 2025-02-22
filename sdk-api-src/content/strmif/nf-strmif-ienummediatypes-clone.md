---
UID: NF:strmif.IEnumMediaTypes.Clone
title: IEnumMediaTypes::Clone (strmif.h)
description: The Clone method makes a copy of the enumerator. The returned object starts with the same enumeration state as the original.
helpviewer_keywords: ["Clone","Clone method [DirectShow]","Clone method [DirectShow]","IEnumMediaTypes interface","IEnumMediaTypes interface [DirectShow]","Clone method","IEnumMediaTypes.Clone","IEnumMediaTypes::Clone","IEnumMediaTypesClone","dshow.ienummediatypes_clone","strmif/IEnumMediaTypes::Clone"]
old-location: dshow\ienummediatypes_clone.htm
tech.root: dshow
ms.assetid: 7a81496d-34e5-43d2-aad9-510ab515adc2
ms.date: 4/26/2023
ms.keywords: Clone, Clone method [DirectShow], Clone method [DirectShow],IEnumMediaTypes interface, IEnumMediaTypes interface [DirectShow],Clone method, IEnumMediaTypes.Clone, IEnumMediaTypes::Clone, IEnumMediaTypesClone, dshow.ienummediatypes_clone, strmif/IEnumMediaTypes::Clone
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
 - IEnumMediaTypes::Clone
 - strmif/IEnumMediaTypes::Clone
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
 - IEnumMediaTypes.Clone
---

# IEnumMediaTypes::Clone


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>Clone</code> method makes a copy of the enumerator. The returned object starts with the same enumeration state as the original.

## -parameters

### -param ppEnum [out]

Receives a pointer to the <a href="/windows/desktop/api/strmif/nn-strmif-ienummediatypes">IEnumMediaTypes</a> interface of the new enumerator. The caller must release the interface.

## -returns

Returns one of the following <b>HRESULT</b> values.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
Success.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_OUTOFMEMORY</b></dt>
</dl>
</td>
<td width="60%">
Insufficient memory.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_POINTER</b></dt>
</dl>
</td>
<td width="60%">
<b>NULL</b> pointer argument.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>VFW_E_ENUM_OUT_OF_SYNC</b></dt>
</dl>
</td>
<td width="60%">
The pin's state has changed and is now inconsistent with the enumerator.

</td>
</tr>
</table>

## -remarks

If the set of media types changes, the enumerator is no longer consistent with the pin, and the method returns VFW_E_ENUM_OUT_OF_SYNC. Discard any data obtained from previous calls to the enumerator, because it might be invalid. Update the enumerator by calling the <a href="/windows/desktop/api/strmif/nf-strmif-ienummediatypes-reset">Reset</a> method. You can then call the <code>Clone</code> method safely.

## -see-also

<a href="/windows/desktop/DirectShow/enumerating-media-types">Enumerating Media Types</a>



<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/strmif/nn-strmif-ienummediatypes">IEnumMediaTypes Interface</a>