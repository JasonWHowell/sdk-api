---
UID: NF:netfw.INetFwServices.get__NewEnum
title: INetFwServices::get__NewEnum (netfw.h)
description: Returns an object supporting IEnumVARIANT that can be used to iterate through all the services in the collection.
helpviewer_keywords: ["INetFwServices interface [ICS/ICF]","_NewEnum property","INetFwServices._NewEnum","INetFwServices.get__NewEnum","INetFwServices::_NewEnum","INetFwServices::get__NewEnum","_NewEnum property [ICS/ICF]","_NewEnum property [ICS/ICF]","INetFwServices interface","get__NewEnum","ics.inetfwservices_newenum","netfw/INetFwServices::_NewEnum","netfw/INetFwServices::get__NewEnum"]
old-location: ics\inetfwservices_newenum.htm
tech.root: ics
ms.assetid: 2da6560f-2eca-4391-88c1-a86948d19d58
ms.date: 12/05/2018
ms.keywords: INetFwServices interface [ICS/ICF],_NewEnum property, INetFwServices._NewEnum, INetFwServices.get__NewEnum, INetFwServices::_NewEnum, INetFwServices::get__NewEnum, _NewEnum property [ICS/ICF], _NewEnum property [ICS/ICF],INetFwServices interface, get__NewEnum, ics.inetfwservices_newenum, netfw/INetFwServices::_NewEnum, netfw/INetFwServices::get__NewEnum
req.header: netfw.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista, Windows XP with SP2 [desktop apps only]
req.target-min-winversvr: Windows Server 2003 with SP1 [desktop apps only]
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
req.dll: FirewallAPI.dll; Hnetcfg.dll on Windows XP with SP2
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - INetFwServices::get__NewEnum
 - netfw/INetFwServices::get__NewEnum
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - FirewallAPI.dll
 - Hnetcfg.dll
api_name:
 - INetFwServices._NewEnum
 - INetFwServices.get__NewEnum
---

# INetFwServices::get__NewEnum


## -description

<p class="CCE_Message">[The Windows Firewall API is available for use in the operating systems specified in the Requirements section. It may be altered or unavailable in subsequent versions. For Windows Vista and later, use of the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/ics/windows-firewall-advanced-security-start-page">Windows Firewall with Advanced Security</a> API is recommended.]

Returns an object supporting <b>IEnumVARIANT</b> that can be used to iterate through all the services in the collection.

Iteration through a collection is done using the <b>for each</b> construct in VBScript. See <a href="https://docs.microsoft.com/previous-versions/windows/desktop/ics/iterating-a-collection">Iterating a Collection</a> for an example.

This property is read-only.

## -parameters

## -see-also

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/netfw/nn-netfw-inetfwservices">INetFwServices</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/ics/iterating-a-collection">Iterating a Collection</a>

