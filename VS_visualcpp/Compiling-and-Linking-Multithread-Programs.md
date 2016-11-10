---
title: "Compiling and Linking Multithread Programs"
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
ms.assetid: 27589afc-daf2-4f26-b868-a99de5c9dfec
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
# Compiling and Linking Multithread Programs
The Bounce.c program is introduced in [Sample Multithread C Program](../VS_visualcpp/Sample-Multithread-C-Program.md).  
  
 Programs are compiled multithreaded by default.  
  
#### To compile and link the multithread program Bounce.c from within the development environment  
  
1.  On the **File** menu, click **New**, and then click **Project**.  
  
2.  In the **Project Types** pane, click **Win32**.  
  
3.  In the **Templates** pane, click **Win32 Console Application**, and then name the project.  
  
4.  Add the file containing the C source code to the project.  
  
5.  On the **Build** menu, build the project by clicking the **Build** command.  
  
#### To compile and link the multithread program Bounce.c from the command line  
  
1.  Compile and link the program:  
  
    ```  
    CL BOUNCE.C  
    ```  
  
## See Also  
 [Multithreading with C and Win32](../VS_visualcpp/Multithreading-with-C-and-Win32.md)