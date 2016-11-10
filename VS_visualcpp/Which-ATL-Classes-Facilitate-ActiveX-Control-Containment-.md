---
title: "Which ATL Classes Facilitate ActiveX Control Containment?"
ms.custom: na
ms.date: 10/03/2016
ms.devlang: 
  - C++
ms.prod: visual-studio-dev14
ms.reviewer: na
ms.suite: na
ms.technology: 
  - devlang-cpp
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 803a4605-7f4c-4139-8638-49d8783d31b0
caps.latest.revision: 9
manager: ghogen
translation.priority.ht: 
  - de-de
  - es-es
  - fr-fr
  - it-it
  - ja-jp
  - ko-kr
  - ru-ru
  - zh-cn
  - zh-tw
translation.priority.mt: 
  - cs-cz
  - pl-pl
  - pt-br
  - tr-tr
---
# Which ATL Classes Facilitate ActiveX Control Containment?
ATL's control-hosting code doesn't require you to use any ATL classes; you can simply create an **"AtlAxWin80"** window and use the control-hosting API if necessary (for more information, see [What Is the ATL Control-Hosting API?](../VS_visualcpp/What-Is-the-ATL-Control-Hosting-API-.md)). However, the following classes make the containment features easier to use.  
  
|Class|Description|  
|-----------|-----------------|  
|[CAxWindow](../VS_visualcpp/CAxWindow-Class.md)|Wraps an **"AtlAxWin80"** window, providing methods for creating the window, creating a control and/or attaching a control to the window, and retrieving interface pointers on the host object.|  
|[CAxWindow2T](../VS_visualcpp/CAxWindow2T-Class.md)|Wraps an **"AtlAxWinLic80"** window, providing methods for creating the window, creating a control and/or attaching a licensed control to the window, and retrieving interface pointers on the host object.|  
|[CComCompositeControl](../VS_visualcpp/CComCompositeControl-Class.md)|Acts as a base class for ActiveX control classes based on a dialog resource. Such controls can contain other ActiveX controls.|  
|[CAxDialogImpl](../VS_visualcpp/CAxDialogImpl-Class.md)|Acts as a base class for dialog classes based on a dialog resource. Such dialogs can contain ActiveX controls.|  
|[CWindow](../VS_visualcpp/CWindow-Class.md)|Provides a method, [GetDlgControl](../Topic/CWindow::GetDlgControl.md), that will return an interface pointer on a control, given the ID of its host window. In addition, the Windows API wrappers exposed by `CWindow` generally make window management easier.|  
  
## See Also  
 [Control Containment FAQ](../VS_visualcpp/ATL-Control-Containment-FAQ.md)