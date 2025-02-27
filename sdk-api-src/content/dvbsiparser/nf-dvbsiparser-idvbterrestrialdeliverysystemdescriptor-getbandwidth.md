---
UID: NF:dvbsiparser.IDvbTerrestrialDeliverySystemDescriptor.GetBandwidth
title: IDvbTerrestrialDeliverySystemDescriptor::GetBandwidth (dvbsiparser.h)
description: This topic applies to Update Rollup 2 for Microsoft Windows XP Media Center Edition 2005 and later.
helpviewer_keywords: ["GetBandwidth","GetBandwidth method [Microsoft TV Technologies]","GetBandwidth method [Microsoft TV Technologies]","IDvbTerrestrialDeliverySystemDescriptor interface","IDvbTerrestrialDeliverySystemDescriptor interface [Microsoft TV Technologies]","GetBandwidth method","IDvbTerrestrialDeliverySystemDescriptor.GetBandwidth","IDvbTerrestrialDeliverySystemDescriptor::GetBandwidth","IDvbTerrestrialDeliverySystemDescriptorGetBandwidth","dvbsiparser/IDvbTerrestrialDeliverySystemDescriptor::GetBandwidth","mstv.idvbterrestrialdeliverysystemdescriptor_getbandwidth"]
old-location: mstv\idvbterrestrialdeliverysystemdescriptor_getbandwidth.htm
tech.root: mstv
ms.assetid: 60efabb7-82bd-4b1f-991e-854c1a8b75ce
ms.date: 12/05/2018
ms.keywords: GetBandwidth, GetBandwidth method [Microsoft TV Technologies], GetBandwidth method [Microsoft TV Technologies],IDvbTerrestrialDeliverySystemDescriptor interface, IDvbTerrestrialDeliverySystemDescriptor interface [Microsoft TV Technologies],GetBandwidth method, IDvbTerrestrialDeliverySystemDescriptor.GetBandwidth, IDvbTerrestrialDeliverySystemDescriptor::GetBandwidth, IDvbTerrestrialDeliverySystemDescriptorGetBandwidth, dvbsiparser/IDvbTerrestrialDeliverySystemDescriptor::GetBandwidth, mstv.idvbterrestrialdeliverysystemdescriptor_getbandwidth
req.header: dvbsiparser.h
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
 - IDvbTerrestrialDeliverySystemDescriptor::GetBandwidth
 - dvbsiparser/IDvbTerrestrialDeliverySystemDescriptor::GetBandwidth
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - dvbsiparser.h
api_name:
 - IDvbTerrestrialDeliverySystemDescriptor.GetBandwidth
---

# IDvbTerrestrialDeliverySystemDescriptor::GetBandwidth


## -description

This topic applies to Update Rollup 2 for Microsoft Windows XP Media Center Edition 2005 and later.
        



The <b>GetBandwidth</b> method returns the bandwidth in use.

## -parameters

### -param pbVal [out]

Receives the bandwidth field.

## -returns

The method returns an <b>HRESULT</b>. Possible values include, but are not limited to, those in the following table.

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
</table>

## -see-also

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/dvbsiparser/nn-dvbsiparser-idvbterrestrialdeliverysystemdescriptor">IDvbTerrestrialDeliverySystemDescriptor Interface</a>

