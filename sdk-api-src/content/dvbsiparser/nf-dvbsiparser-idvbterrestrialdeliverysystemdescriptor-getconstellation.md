---
UID: NF:dvbsiparser.IDvbTerrestrialDeliverySystemDescriptor.GetConstellation
title: IDvbTerrestrialDeliverySystemDescriptor::GetConstellation (dvbsiparser.h)
description: This topic applies to Update Rollup 2 for Microsoft Windows XP Media Center Edition 2005 and later.
helpviewer_keywords: ["GetConstellation","GetConstellation method [Microsoft TV Technologies]","GetConstellation method [Microsoft TV Technologies]","IDvbTerrestrialDeliverySystemDescriptor interface","IDvbTerrestrialDeliverySystemDescriptor interface [Microsoft TV Technologies]","GetConstellation method","IDvbTerrestrialDeliverySystemDescriptor.GetConstellation","IDvbTerrestrialDeliverySystemDescriptor::GetConstellation","IDvbTerrestrialDeliverySystemDescriptorGetConstellation","dvbsiparser/IDvbTerrestrialDeliverySystemDescriptor::GetConstellation","mstv.idvbterrestrialdeliverysystemdescriptor_getconstellation"]
old-location: mstv\idvbterrestrialdeliverysystemdescriptor_getconstellation.htm
tech.root: mstv
ms.assetid: 1a34de19-c684-4778-a164-5ddde87443b0
ms.date: 12/05/2018
ms.keywords: GetConstellation, GetConstellation method [Microsoft TV Technologies], GetConstellation method [Microsoft TV Technologies],IDvbTerrestrialDeliverySystemDescriptor interface, IDvbTerrestrialDeliverySystemDescriptor interface [Microsoft TV Technologies],GetConstellation method, IDvbTerrestrialDeliverySystemDescriptor.GetConstellation, IDvbTerrestrialDeliverySystemDescriptor::GetConstellation, IDvbTerrestrialDeliverySystemDescriptorGetConstellation, dvbsiparser/IDvbTerrestrialDeliverySystemDescriptor::GetConstellation, mstv.idvbterrestrialdeliverysystemdescriptor_getconstellation
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
 - IDvbTerrestrialDeliverySystemDescriptor::GetConstellation
 - dvbsiparser/IDvbTerrestrialDeliverySystemDescriptor::GetConstellation
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
 - IDvbTerrestrialDeliverySystemDescriptor.GetConstellation
---

# IDvbTerrestrialDeliverySystemDescriptor::GetConstellation


## -description

This topic applies to Update Rollup 2 for Microsoft Windows XP Media Center Edition 2005 and later.
        



The <b>GetConstellation</b> method returns the constellation pattern.

## -parameters

### -param pbVal [out]

Receives the constellation field.

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

