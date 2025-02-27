---
UID: NN:sbe.IStreamBufferMediaSeeking2
title: IStreamBufferMediaSeeking2 (sbe.h)
description: The IStreamBufferMediaSeeking2 interface is exposed by the Stream Buffer Source filter. It provides a method to control the frame rate during fast-forward play (&#0034;trick mode&#0034;).
helpviewer_keywords: ["IStreamBufferMediaSeeking2","IStreamBufferMediaSeeking2 interface [Microsoft TV Technologies]","IStreamBufferMediaSeeking2 interface [Microsoft TV Technologies]","described","IStreamBufferMediaSeeking2Interface","mstv.istreambuffermediaseeking2","sbe/IStreamBufferMediaSeeking2"]
old-location: mstv\istreambuffermediaseeking2.htm
tech.root: mstv
ms.assetid: 3029868e-0b27-4ce9-90b2-22d8e1961a1f
ms.date: 12/05/2018
ms.keywords: IStreamBufferMediaSeeking2, IStreamBufferMediaSeeking2 interface [Microsoft TV Technologies], IStreamBufferMediaSeeking2 interface [Microsoft TV Technologies],described, IStreamBufferMediaSeeking2Interface, mstv.istreambuffermediaseeking2, sbe/IStreamBufferMediaSeeking2
req.header: sbe.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP2 [desktop apps only]
req.target-min-winversvr: None supported
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
 - IStreamBufferMediaSeeking2
 - sbe/IStreamBufferMediaSeeking2
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Sbe.h
api_name:
 - IStreamBufferMediaSeeking2
---

# IStreamBufferMediaSeeking2 interface


## -description

The <b>IStreamBufferMediaSeeking2</b> interface is exposed by the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/mstv/stream-buffer-source-filter">Stream Buffer Source</a> filter. It provides a method to control the frame rate during fast-forward play ("trick mode").

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IStreamBufferMediaSeeking2</b> interface inherits from <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/sbe/nn-sbe-istreambuffermediaseeking">IStreamBufferMediaSeeking</a>. <b>IStreamBufferMediaSeeking2</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>IStreamBufferMediaSeeking2</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/sbe/nf-sbe-istreambuffermediaseeking2-setrateex">SetRateEx</a>
</td>
<td align="left" width="63%">
Sets playback rate, and sets the frame rate for trick mode.

</td>
</tr>
</table>

## -remarks

To declare the interface identifier (IID) for this interface, use the <b>__uuidof</b> operator: <code>__uuidof(IStreamBufferMediaSeeking2)</code>.

## -see-also

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/sbe/nn-sbe-istreambuffermediaseeking">IStreamBufferMediaSeeking</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/mstv/stream-buffer-engine-interfaces">Stream Buffer Engine Interfaces</a>

