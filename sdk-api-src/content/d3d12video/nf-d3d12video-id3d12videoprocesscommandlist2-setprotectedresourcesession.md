---
UID: NF:d3d12video.ID3D12VideoProcessCommandList2.SetProtectedResourceSession
title: ID3D12VideoProcessCommandList2::SetProtectedResourceSession
description: Specifies whether or not protected resources can be accessed by subsequent commands in the video process command list.
tech.root: mf
ms.date: 11/4/2019
ms.topic: language-reference
targetos: Windows
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: d3d12video.h
req.idl: 
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: Windows 10, version 2004 (10.0; Build 19041)
req.target-min-winversvr: Windows Server, version 2004 (10.0; Build 19041)
req.target-type: 
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - COM
api_location:
 - d3d12video.h
api_name:
 - ID3D12VideoProcessCommandList2::SetProtectedResourceSession
f1_keywords:
 - ID3D12VideoProcessCommandList2::SetProtectedResourceSession
 - d3d12video/ID3D12VideoProcessCommandList2::SetProtectedResourceSession
dev_langs:
 - c++
---

## -description

Specifies whether or not protected resources can be accessed by subsequent commands in the video process command list. By default, no protected resources are enabled. After calling **SetProtectedResourceSession** with a valid session, protected resources of the same type can refer to that session. After calling **SetProtectedResourceSession** with **NULL**, no protected resources can be accessed.

## -parameters

### -param pProtectedResourceSession

An optional pointer to an [ID3D12ProtectedResourceSession](/windows/win32/api/d3d12/nn-d3d12-id3d12protectedresourcesession). You can obtain an **ID3D12ProtectedResourceSession** by calling [ID3D12Device4::CreateProtectedResourceSession](/windows/win32/api/d3d12/nf-d3d12-id3d12device4-createprotectedresourcesession).

## -remarks

## -see-also

