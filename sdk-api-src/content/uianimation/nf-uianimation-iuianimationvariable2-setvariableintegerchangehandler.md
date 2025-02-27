---
UID: NF:uianimation.IUIAnimationVariable2.SetVariableIntegerChangeHandler
title: IUIAnimationVariable2::SetVariableIntegerChangeHandler (uianimation.h)
description: Specifies a handler for changes to the integer value of the animation variable.
helpviewer_keywords: ["IUIAnimationVariable2 interface [Windows Animation]","SetVariableIntegerChangeHandler method","IUIAnimationVariable2.SetVariableIntegerChangeHandler","IUIAnimationVariable2::SetVariableIntegerChangeHandler","SetVariableIntegerChangeHandler","SetVariableIntegerChangeHandler method [Windows Animation]","SetVariableIntegerChangeHandler method [Windows Animation]","IUIAnimationVariable2 interface","uianimation.iuianimationvariable2_setvariableintegerchangehandler","uianimation/IUIAnimationVariable2::SetVariableIntegerChangeHandler"]
old-location: uianimation\iuianimationvariable2_setvariableintegerchangehandler.htm
tech.root: UIAnimation
ms.assetid: 4327AC4A-2C2C-4C1A-AFCD-D2BA8ECEBA12
ms.date: 12/05/2018
ms.keywords: IUIAnimationVariable2 interface [Windows Animation],SetVariableIntegerChangeHandler method, IUIAnimationVariable2.SetVariableIntegerChangeHandler, IUIAnimationVariable2::SetVariableIntegerChangeHandler, SetVariableIntegerChangeHandler, SetVariableIntegerChangeHandler method [Windows Animation], SetVariableIntegerChangeHandler method [Windows Animation],IUIAnimationVariable2 interface, uianimation.iuianimationvariable2_setvariableintegerchangehandler, uianimation/IUIAnimationVariable2::SetVariableIntegerChangeHandler
req.header: uianimation.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8, Windows 7 and Platform Update for Windows 7 [desktop apps \| UWP apps]
req.target-min-winversvr: None supported
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: UIAnimation.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: UIAnimation.dll
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IUIAnimationVariable2::SetVariableIntegerChangeHandler
 - uianimation/IUIAnimationVariable2::SetVariableIntegerChangeHandler
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - UIAnimation.dll
api_name:
 - IUIAnimationVariable2.SetVariableIntegerChangeHandler
---

# IUIAnimationVariable2::SetVariableIntegerChangeHandler


## -description

Specifies a handler for changes to the integer value of the animation variable.

## -parameters

### -param handler [in, optional]

A pointer to the handler for changes to the integer value of the animation variable. This parameter can be <b>NULL</b>.

### -param fRegisterForNextAnimationEvent [in]

If <b>TRUE</b>, specifies that the <a href="https://docs.microsoft.com/windows/desktop/api/uianimation/nf-uianimation-iuianimationmanager2-estimatenexteventtime">EstimateNextEventTime</a> method will incorporate <i>handler</i> into its estimate of the time interval until the next animation event. No default value.

## -returns

Returns <b>S_OK</b> if successful; otherwise an <b>HRESULT</b> error code. See <a href="https://docs.microsoft.com/windows/desktop/UIAnimation/uianimation-error-codes">Windows Animation Error Codes</a> for a list of error codes.

## -remarks

Passing <b>NULL</b> for the <i>handler</i> parameter causes Windows Animation to release its reference to any handler object that you passed in earlier. This technique can be essential for breaking reference cycles without having to call the <a href="https://docs.microsoft.com/windows/desktop/api/uianimation/nf-uianimation-iuianimationmanager2-shutdown">Shutdown</a> method.


<a href="https://docs.microsoft.com/windows/desktop/api/uianimation/nf-uianimation-iuianimationvariableintegerchangehandler2-onintegervaluechanged">IUIAnimationVariableIntegerChangeHandler2::OnIntegerValueChanged</a> is called only if the rounded value has changed since the last update.

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/api/uianimation/nn-uianimation-iuianimationvariable2">IUIAnimationVariable2</a>



<a href="https://docs.microsoft.com/windows/desktop/api/uianimation/nn-uianimation-iuianimationvariablechangehandler2">IUIAnimationVariableChangeHandler2</a>

