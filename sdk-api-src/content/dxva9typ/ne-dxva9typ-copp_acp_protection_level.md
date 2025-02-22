---
UID: NE:dxva9typ._COPP_ACP_Protection_Level
title: COPP_ACP_Protection_Level (dxva9typ.h)
description: Specifies the ACP protection level.
helpviewer_keywords: ["COPP_ACP_ForceDWORD","COPP_ACP_Level0","COPP_ACP_Level1","COPP_ACP_Level2","COPP_ACP_Level3","COPP_ACP_LevelMax","COPP_ACP_LevelMin","COPP_ACP_Protection_Level","COPP_ACP_Protection_Level","COPP_ACP_Protection_Level enumeration [DirectShow]","COPP_ACP_Protection_LevelEnumeration","dshow.copp_acp_protection_level","dxva9typ/COPP_ACP_ForceDWORD","dxva9typ/COPP_ACP_Level0","dxva9typ/COPP_ACP_Level1","dxva9typ/COPP_ACP_Level2","dxva9typ/COPP_ACP_Level3","dxva9typ/COPP_ACP_LevelMax","dxva9typ/COPP_ACP_LevelMin","dxva9typ/COPP_ACP_Protection_Level"]
old-location: dshow\copp_acp_protection_level.htm
tech.root: dshow
ms.assetid: a3149eb6-e758-4b21-b574-32fb6c2ae3a2
ms.date: 4/26/2023
ms.keywords: COPP_ACP_ForceDWORD, COPP_ACP_Level0, COPP_ACP_Level1, COPP_ACP_Level2, COPP_ACP_Level3, COPP_ACP_LevelMax, COPP_ACP_LevelMin, COPP_ACP_Protection_Level, COPP_ACP_Protection_Level , COPP_ACP_Protection_Level enumeration [DirectShow], COPP_ACP_Protection_LevelEnumeration, dshow.copp_acp_protection_level, dxva9typ/COPP_ACP_ForceDWORD, dxva9typ/COPP_ACP_Level0, dxva9typ/COPP_ACP_Level1, dxva9typ/COPP_ACP_Level2, dxva9typ/COPP_ACP_Level3, dxva9typ/COPP_ACP_LevelMax, dxva9typ/COPP_ACP_LevelMin, dxva9typ/COPP_ACP_Protection_Level
req.header: dxva9typ.h
req.include-header: Dxva.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: COPP_ACP_Protection_Level
req.redist: 
ms.custom: 19H1
f1_keywords:
 - _COPP_ACP_Protection_Level
 - dxva9typ/_COPP_ACP_Protection_Level
 - COPP_ACP_Protection_Level
 - dxva9typ/COPP_ACP_Protection_Level
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - dxva9typ.h
api_name:
 - COPP_ACP_Protection_Level
---

# COPP_ACP_Protection_Level enumeration


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

Specifies the ACP protection level.

## -enum-fields

### -field COPP_ACP_Level0:0

Level 0.

### -field COPP_ACP_LevelMin

Minimum ACP level. Equivalent to <b>COPP_ACP_Level0</b>.

### -field COPP_ACP_Level1:1

Level 1.

### -field COPP_ACP_Level2:2

Level 2.

### -field COPP_ACP_Level3:3

Level 3.

### -field COPP_ACP_LevelMax

Maximum ACP level. Equivalent to <b>COPP_ACP_Level3</b>.

### -field COPP_ACP_ForceDWORD:0x7fffffff

Reserved.

## -see-also

<a href="/windows/desktop/DirectShow/directshow-enumerated-types">DirectShow Enumerated Types</a>



<a href="/windows/desktop/DirectShow/using-certified-output-protection-protocol--copp">Using Certified Output Protection Protocol (COPP)</a>
