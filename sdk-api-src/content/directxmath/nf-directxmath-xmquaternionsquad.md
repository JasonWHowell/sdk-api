---
UID: NF:directxmath.XMQuaternionSquad
title: XMQuaternionSquad function (directxmath.h)
description: Interpolates between four unit quaternions, using spherical quadrangle interpolation.
helpviewer_keywords: ["Use DirectX..XMQuaternionSquad","XMQuaternionSquad","XMQuaternionSquad method [DirectX Math Support APIs]","dxmath.xmquaternionsquad"]
old-location: dxmath\xmquaternionsquad.htm
tech.root: dxmath
ms.assetid: M:Microsoft.directx_sdk.quaternion.XMQuaternionSquad(XMVECTOR,XMVECTOR,XMVECTOR,XMVECTOR,float)
ms.date: 12/05/2018
ms.keywords: Use DirectX..XMQuaternionSquad, XMQuaternionSquad, XMQuaternionSquad method [DirectX Math Support APIs], dxmath.xmquaternionsquad
req.header: directxmath.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: Use DirectX.
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - XMQuaternionSquad
 - directxmath/XMQuaternionSquad
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - DirectXMath.h
api_name:
 - XMQuaternionSquad
---

# XMQuaternionSquad function


## -description

Interpolates between four unit quaternions, using spherical quadrangle interpolation.

## -parameters

### -param Q0 [in]

First unit quaternion.

### -param Q1 [in]

Second unit quaternion.

### -param Q2 [in]

Third unit quaternion.

### -param Q3 [in]

Fourth unit quaternion.

### -param t [in]

Interpolation control factor.

## -returns

Returns the interpolated quaternion. If <i>Q0</i>, <i>Q1</i>, <i>Q2</i>, and <i>Q3</i> are not all unit
       quaternions, the returned quaternion is undefined.

## -remarks

The DirectXMath quaternion functions use an XMVECTOR 4-vector to represent quaternions, 
    where the X, Y, and Z components are the vector part and the W component is the scalar part.

The use of this method requires some setup before its use. See
   <a href="https://docs.microsoft.com/windows/desktop/api/directxmath/nf-directxmath-xmquaternionsquadsetup">XMQuaternionSquadSetup</a> for details.

<h3><a id="Platform_Requirements"></a><a id="platform_requirements"></a><a id="PLATFORM_REQUIREMENTS"></a>Platform Requirements</h3>
Microsoft Visual Studio 2010 or Microsoft Visual Studio 2012 with the Windows SDK for Windows 8. Supported for Win32 desktop apps, Windows Store apps, and Windows Phone 8 apps.

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/dxmath/ovw-xnamath-reference-functions-quaternion">DirectXMath Library Quaternion Functions</a>



<a href="https://docs.microsoft.com/windows/desktop/api/directxmath/nf-directxmath-xmquaternionsquadsetup">XMQuaternionSquadSetup</a>



<a href="https://docs.microsoft.com/windows/desktop/api/directxmath/nf-directxmath-xmquaternionsquadv">XMQuaternionSquadV</a>

