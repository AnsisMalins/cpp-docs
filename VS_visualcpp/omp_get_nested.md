---
title: "omp_get_nested"
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
ms.assetid: e9784847-516e-40d3-89f7-b8b6898d8667
caps.latest.revision: 8
manager: ghogen
translation.priority.ht: 
  - cs-cz
  - de-de
  - es-es
  - fr-fr
  - it-it
  - ja-jp
  - ko-kr
  - pl-pl
  - pt-br
  - ru-ru
  - tr-tr
  - zh-cn
  - zh-tw
---
# omp_get_nested
Returns a value that indicates if nested parallelism is enabled.  
  
## Syntax  
  
```  
int omp_get_nested( );  
```  
  
## Return Value  
 If nonzero, nested parallelism is enabled.  
  
## Remarks  
 Nested parallelism is specified with [omp_set_nested](../VS_visualcpp/omp_set_nested.md) and [OMP_NESTED](../VS_visualcpp/OMP_NESTED.md).  
  
 For more information, see [3.1.10 omp_get_nested Function](../VS_visualcpp/3.1.10-omp_get_nested-Function.md).  
  
## Example  
 See [omp_set_nested](../VS_visualcpp/omp_set_nested.md) for an example of using `omp_get_nested`.  
  
## See Also  
 [Functions](../VS_visualcpp/OpenMP-Functions.md)