---
UID: NS:vmr9._VMR9DeinterlaceCaps
title: VMR9DeinterlaceCaps (vmr9.h)
description: The VMR9DeinterlaceCaps structure describes the capabilities of a deinterlacing mode.
helpviewer_keywords: ["VMR9DeinterlaceCaps","VMR9DeinterlaceCaps structure [DirectShow]","VMR9DeinterlaceCapsStructure","dshow.vmr9deinterlacecaps","vmr9/VMR9DeinterlaceCaps"]
old-location: dshow\vmr9deinterlacecaps.htm
tech.root: dshow
ms.assetid: ae71c9d6-2540-4679-927c-e1d759df7009
ms.date: 12/05/2018
ms.keywords: VMR9DeinterlaceCaps, VMR9DeinterlaceCaps structure [DirectShow], VMR9DeinterlaceCapsStructure, dshow.vmr9deinterlacecaps, vmr9/VMR9DeinterlaceCaps
req.header: vmr9.h
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
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: VMR9DeinterlaceCaps
req.redist: 
ms.custom: 19H1
f1_keywords:
 - _VMR9DeinterlaceCaps
 - vmr9/_VMR9DeinterlaceCaps
 - VMR9DeinterlaceCaps
 - vmr9/VMR9DeinterlaceCaps
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - Vmr9.h
api_name:
 - VMR9DeinterlaceCaps
---

# VMR9DeinterlaceCaps structure


## -description

The <code>VMR9DeinterlaceCaps</code> structure describes the capabilities of a deinterlacing mode.

## -struct-fields

### -field dwSize

Size of the structure, in bytes.

### -field dwNumPreviousOutputFrames

Number of previously de-interlaced frames that must be fed back to the hardware to deinterlace the next field. (Used by recursive deinterlacing algorithms.)

### -field dwNumForwardRefSamples

Number of future samples needed to deinterlace the current field.

### -field dwNumBackwardRefSamples

Number of past samples needed to deinterlace the current field.

### -field DeinterlaceTechnology

Bitwise combination of flags from the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/vmr9/ne-vmr9-vmr9deinterlacetech">VMR9DeinterlaceTech</a> enumeration type. These flags are used to describe the deinterlacing algorithm.

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/DirectShow/directshow-structures">DirectShow Structures</a>

