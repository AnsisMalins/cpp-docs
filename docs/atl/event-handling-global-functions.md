---
title: "Event Handling Global Functions"
ms.custom: na
ms.date: "10/14/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: na
ms.suite: na
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: na
ms.topic: "reference"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "event handling, global functions"
  - "global functions, event handling"
ms.assetid: fd674470-3def-47c3-be1c-894fa85f13e8
caps.latest.revision: 15
ms.author: "mblome"
manager: "ghogen"
translation.priority.ht: 
  - "cs-cz"
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "pl-pl"
  - "pt-br"
  - "ru-ru"
  - "tr-tr"
  - "zh-cn"
  - "zh-tw"
---
# Event Handling Global Functions
This function provides an event handler.  
  
> [!IMPORTANT]
>  The function listed in the following table cannot be used in applications that execute in the [!INCLUDE[wrt](../atl/includes/wrt_md.md)].  
  
|||  
|-|-|  
|[AtlWaitWithMessageLoop](../Topic/AtlWaitWithMessageLoop.md)|Waits for an object to be signaled, meanwhile dispatching window messages as needed.|  
  
##  <a name="atlwaitwithmessageloop"></a>  AtlWaitWithMessageLoop  
 Waits for the object to be signaled, meanwhile dispatching window messages as needed.  
  
> [!IMPORTANT]
>  This function cannot be used in applications that execute in the [!INCLUDE[wrt](../atl/includes/wrt_md.md)].  
  
```
BOOL
    AtlWaitWithMessageLoop(HANDLE hEvent);
```  
  
### Parameters  
 `hEvent`  
 [in] The handle of the object to wait for.  
  
### Return Value  
 Returns **TRUE** if the object has been signaled.  
  
### Remarks  
 This is useful if you want to wait for an object's event to happen and be notified of it happening, but allow window messages to be dispatched while waiting.  
  
## See Also  
 [Functions](../atl/atl-functions.md)
