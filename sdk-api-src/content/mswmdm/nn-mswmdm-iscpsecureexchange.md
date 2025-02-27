---
UID: NN:mswmdm.ISCPSecureExchange
title: ISCPSecureExchange (mswmdm.h)
description: The ISCPSecureExchange interface is used to exchange secured content and rights associated with content. The secure content provider implements this interface and secure Windows Media Device Manager implementations call its methods.
helpviewer_keywords: ["ISCPSecureExchange","ISCPSecureExchange interface [windows Media Device Manager]","ISCPSecureExchange interface [windows Media Device Manager]","described","ISCPSecureExchangeInterface","mswmdm/ISCPSecureExchange","wmdm.iscpsecureexchange"]
old-location: wmdm\iscpsecureexchange.htm
tech.root: WMDM
ms.assetid: 8c61e1a0-18fc-4ae9-881a-0362166012d9
ms.date: 12/05/2018
ms.keywords: ISCPSecureExchange, ISCPSecureExchange interface [windows Media Device Manager], ISCPSecureExchange interface [windows Media Device Manager],described, ISCPSecureExchangeInterface, mswmdm/ISCPSecureExchange, wmdm.iscpsecureexchange
req.header: mswmdm.h
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
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - ISCPSecureExchange
 - mswmdm/ISCPSecureExchange
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - mswmdm.h
api_name:
 - ISCPSecureExchange
---

# ISCPSecureExchange interface


## -description

The <b>ISCPSecureExchange</b> interface is used to exchange secured content and rights associated with content. The secure content provider implements this interface and secure Windows Media Device Manager implementations call its methods.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">ISCPSecureExchange</b> interface inherits from the <a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>ISCPSecureExchange</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>ISCPSecureExchange</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/mswmdm/nf-mswmdm-iscpsecureexchange-objectdata">ObjectData</a>
</td>
<td align="left" width="63%">
Transfers a block of object data to Windows Media Device Manager.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/mswmdm/nf-mswmdm-iscpsecureexchange-transfercomplete">TransferComplete</a>
</td>
<td align="left" width="63%">
Called by Windows Media Device Manager to signal the end of a secure transfer of data.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/mswmdm/nf-mswmdm-iscpsecureexchange-transfercontainerdata">TransferContainerData</a>
</td>
<td align="left" width="63%">
Transfers container file data to the secure content provider.

</td>
</tr>
</table>

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/api/mswmdm/nn-mswmdm-iscpsecureexchange2">ISCPSecureExchange2 Interface</a>



<a href="https://docs.microsoft.com/windows/desktop/api/mswmdm/nn-mswmdm-iscpsecureexchange3">ISCPSecureExchange3 Interface</a>



<a href="https://docs.microsoft.com/windows/desktop/WMDM/interfaces-for-secure-content-providers">Interfaces for Secure Content Providers</a>

