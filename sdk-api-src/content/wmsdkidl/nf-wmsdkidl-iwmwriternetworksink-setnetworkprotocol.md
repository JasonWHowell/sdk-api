---
UID: NF:wmsdkidl.IWMWriterNetworkSink.SetNetworkProtocol
title: IWMWriterNetworkSink::SetNetworkProtocol (wmsdkidl.h)
description: The SetNetworkProtocol method sets the network protocol that the network sink uses. Currently, HTTP is the only protocol supported by the network sink.
helpviewer_keywords: ["IWMWriterNetworkSink interface [windows Media Format]","SetNetworkProtocol method","IWMWriterNetworkSink.SetNetworkProtocol","IWMWriterNetworkSink::SetNetworkProtocol","IWMWriterNetworkSinkSetNetworkProtocol","SetNetworkProtocol","SetNetworkProtocol method [windows Media Format]","SetNetworkProtocol method [windows Media Format]","IWMWriterNetworkSink interface","wmformat.iwmwriternetworksink_setnetworkprotocol","wmsdkidl/IWMWriterNetworkSink::SetNetworkProtocol"]
old-location: wmformat\iwmwriternetworksink_setnetworkprotocol.htm
tech.root: wmformat
ms.assetid: 8ad6b2a4-b50b-45a0-8aa0-cabfc1e59bb7
ms.date: 12/05/2018
ms.keywords: IWMWriterNetworkSink interface [windows Media Format],SetNetworkProtocol method, IWMWriterNetworkSink.SetNetworkProtocol, IWMWriterNetworkSink::SetNetworkProtocol, IWMWriterNetworkSinkSetNetworkProtocol, SetNetworkProtocol, SetNetworkProtocol method [windows Media Format], SetNetworkProtocol method [windows Media Format],IWMWriterNetworkSink interface, wmformat.iwmwriternetworksink_setnetworkprotocol, wmsdkidl/IWMWriterNetworkSink::SetNetworkProtocol
req.header: wmsdkidl.h
req.include-header: Wmsdk.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only],Windows Media Format 7 SDK, or later versions of the SDK
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
req.lib: Wmvcore.lib; WMStubDRM.lib (if you use DRM)
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IWMWriterNetworkSink::SetNetworkProtocol
 - wmsdkidl/IWMWriterNetworkSink::SetNetworkProtocol
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Wmvcore.lib
 - Wmvcore.dll
 - WMStubDRM.lib
 - WMStubDRM.dll
api_name:
 - IWMWriterNetworkSink.SetNetworkProtocol
---

# IWMWriterNetworkSink::SetNetworkProtocol


## -description

The <b>SetNetworkProtocol</b> method sets the network protocol that the network sink uses. Currently, HTTP is the only protocol supported by the network sink.

## -parameters

### -param protocol [in]

Specifies the procotcol, as a value from the <a href="https://docs.microsoft.com/windows/desktop/api/wmsdkidl/ne-wmsdkidl-wmt_net_protocol">WMT_NET_PROTOCOL</a> enumeration type.

## -returns

The method returns an <b>HRESULT</b>. Possible values include, but are not limited to, the values shown in the following table.

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
The method succeeded.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_INVALIDARG</b></dt>
</dl>
</td>
<td width="60%">
Invalid argument.

</td>
</tr>
</table>

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/api/wmsdkidl/nn-wmsdkidl-iwmwriternetworksink">IWMWriterNetworkSink Interface</a>



<a href="https://docs.microsoft.com/windows/desktop/api/wmsdkidl/nf-wmsdkidl-iwmwriternetworksink-getnetworkprotocol">IWMWriterNetworkSink::GetNetworkProtocol</a>

