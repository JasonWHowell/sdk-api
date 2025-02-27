---
UID: NN:objidl.IPipeByte
title: IPipeByte (objidl.h)
description: Transfers data of the byte type (which is 8 bits wide).
helpviewer_keywords: ["IPipeByte","IPipeByte interface [COM]","IPipeByte interface [COM]","described","_com_ipipebyte","com.ipipebyte","objidlbase/IPipeByte"]
old-location: com\ipipebyte.htm
tech.root: com
ms.assetid: e3e01280-c015-488a-8be4-9740c44c0041
ms.date: 12/05/2018
ms.keywords: IPipeByte, IPipeByte interface [COM], IPipeByte interface [COM],described, _com_ipipebyte, com.ipipebyte, objidlbase/IPipeByte
req.header: objidl.h
req.include-header: ObjIdl.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: ObjIdl.idl
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
 - IPipeByte
 - objidl/IPipeByte
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - objidlbase.h
api_name:
 - IPipeByte
---

# IPipeByte interface


## -description

Transfers data of the byte type (which is 8 bits wide).

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IPipeByte</b> interface inherits from the <a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IPipeByte</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>IPipeByte</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/objidl/nf-objidl-ipipebyte-pull">Pull</a>
</td>
<td align="left" width="63%">
Retrieves data of the byte type from the pipe source.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/objidl/nf-objidl-ipipebyte-push">Push</a>
</td>
<td align="left" width="63%">
Sends data of the byte type to the pipe source.

</td>
</tr>
</table>

## -remarks

The <b>IPipeByte</b>, <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nn-objidl-ipipedouble">IPipeDouble</a>, and <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nn-objidl-ipipelong">IPipeLong</a> interfaces are similar to the standard DCE/RPC pipes. However, the COM implementation of pipes offers more flexibility. With the COM implementation, the basic idea is that the pipe is simply another interface with two methods: <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nf-objidl-ipipebyte-pull">Pull</a> and <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nf-objidl-ipipebyte-push">Push</a>. This results in three main benefits:

<ul>
<li>A COM pipe is another interface, so it can be received as an out parameter from a method call and then either <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nf-objidl-ipipebyte-pull">Pull</a> or <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nf-objidl-ipipebyte-push">Push</a> can be called. </li>
<li>There are no restrictions on when to call the <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nf-objidl-ipipebyte-pull">Pull</a> and <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nf-objidl-ipipebyte-push">Push</a> methods, so a pipe is in reality bidirectional.</li>
<li>Pipes are interfaces, so the method calls can be asynchronous and follow those rules.</li>
</ul>
For more information, see <a href="https://docs.microsoft.com/windows/desktop/Rpc/pipes">Pipes</a> in the RPC documentation.

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/api/objidl/nn-objidl-ipipedouble">IPipeDouble</a>



<a href="https://docs.microsoft.com/windows/desktop/api/objidl/nn-objidl-ipipelong">IPipeLong</a>

