---
UID: NS:d3d11.CD3D11_TEXTURE1D_DESC
title: CD3D11_TEXTURE1D_DESC (d3d11.h)
description: Represents a 1D texture and provides convenience methods for creating 1D textures.
helpviewer_keywords: ["CD3D11_TEXTURE1D_DESC","CD3D11_TEXTURE1D_DESC structure [Direct3D 11]","d3d11/CD3D11_TEXTURE1D_DESC","direct3d11.cd3d11_texture1d_desc"]
old-location: direct3d11\cd3d11_texture1d_desc.htm
tech.root: direct3d11
ms.assetid: 71ED0CD5-6EDC-474C-B131-62C42EF0D261
ms.date: 12/05/2018
ms.keywords: CD3D11_TEXTURE1D_DESC, CD3D11_TEXTURE1D_DESC structure [Direct3D 11], d3d11/CD3D11_TEXTURE1D_DESC, direct3d11.cd3d11_texture1d_desc
req.header: d3d11.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 7 [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2008 R2 [desktop apps \| UWP apps]
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
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - CD3D11_TEXTURE1D_DESC
 - d3d11/CD3D11_TEXTURE1D_DESC
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - D3D11.h
api_name:
 - CD3D11_TEXTURE1D_DESC
---

# CD3D11_TEXTURE1D_DESC structure


## -description

Represents a 1D texture and provides convenience methods for creating 1D textures.

## -struct-fields

## -remarks

Here is how D3D11.h defines <b>CD3D11_TEXTURE1D_DESC</b>:

<div class="code"><span codelanguage=""><table>
<tr>
<th></th>
</tr>
<tr>
<td>
<pre>
struct CD3D11_TEXTURE1D_DESC : public D3D11_TEXTURE1D_DESC
{
    CD3D11_TEXTURE1D_DESC()
    {}
    explicit CD3D11_TEXTURE1D_DESC( const D3D11_TEXTURE1D_DESC&amp; o ) :
        D3D11_TEXTURE1D_DESC( o )
    {}
    explicit CD3D11_TEXTURE1D_DESC(
        DXGI_FORMAT format,
        UINT width,
        UINT arraySize = 1,
        UINT mipLevels = 0,
        UINT bindFlags = D3D11_BIND_SHADER_RESOURCE,
        D3D11_USAGE usage = D3D11_USAGE_DEFAULT,
        UINT cpuaccessFlags= 0,
        UINT miscFlags = 0 )
    {
        Width = width;
        MipLevels = mipLevels;
        ArraySize = arraySize;
        Format = format;
        Usage = usage;
        BindFlags = bindFlags;
        CPUAccessFlags = cpuaccessFlags;
        MiscFlags = miscFlags;
    }
    ~CD3D11_TEXTURE1D_DESC() {}
    operator const D3D11_TEXTURE1D_DESC&amp;() const { return *this; }
};
</pre>
</td>
</tr>
</table></span></div>

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/direct3d11/cd3d11-helper-classes">CD3D11 Helper Structures</a>

