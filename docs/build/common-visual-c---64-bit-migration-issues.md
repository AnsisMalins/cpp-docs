---
title: "Common Visual C++ 64-bit Migration Issues"
ms.custom: na
ms.date: "10/14/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: na
ms.suite: na
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: na
ms.topic: "article"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "64-bit programming [C++], migration"
  - "64-bit compiler [C++], migration"
  - "porting 32-bit code to 64-bit code"
  - "upgrading Visual C++ applications, 32-bit code"
  - "migration [C++], 64-bit code issues"
  - "32-bit code porting [C++]"
  - "64-bit applications [C++]"
  - "64-bit compiler [C++], porting 32-bit code"
  - "Win64 [C++]"
ms.assetid: d17fb838-7513-4e2d-8b27-a1666f17ad76
caps.latest.revision: 19
ms.author: "corob"
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
# Common Visual C++ 64-bit Migration Issues
When you use Visual C++ to create applications to run on a 64-bit Windows operating system, you should be aware of the following issues:  
  
-   An `int` and a `long` are 32-bit values on 64-bit Windows operating systems. For programs that you plan to compile for 64-bit platforms, you should be careful not to assign pointers to 32-bit variables. Pointers are 64-bit on 64-bit platforms, and you will truncate the pointer value if you assign it to a 32-bit variable.  
  
-   `size_t`, `time_t`, and `ptrdiff_t` are 64-bit values on 64-bit Windows operating systems.  
  
-   `time_t` is a 32-bit value on 32-bit Windows operating systems in Visual C++ versions before Visual C++ 2005. `time_t` is now a 64-bit integer by default. For more information, see [Time Management](../crt/time-management.md).  
  
     You should be aware of where your code takes an `int` value and processes it as a `size_t` or `time_t` value. It is possible that the number could grow to be larger than a 32-bit number and data will be truncated when it is passed back to the `int` storage.  
  
 The %x (hex `int` format) `printf` modifier will not work as expected on a 64-bit Windows operating system. It will only operate on the first 32 bits of the value that is passed to it.  
  
-   Use %I32x to display a 32-bit integral type in hex format.  
  
-   Use %I64x to display a 64-bit integral type in hex format.  
  
-   The %p (hex format for a pointer) will work as expected on a 64-bit Windows operating system.  
  
 For more information, see:  
  
-   [Compiler Options](../buildref/compiler-options.md)  
  
-   [Migration Tips](http://msdn.microsoft.com/library/windows/desktop/aa384214)  
  
## See Also  
 [Configuring Programs for 64-Bit](../build/configuring-programs-for-64-bit--visual-c---.md)   
 [Visual C++ Porting and Upgrading Guide](../porting/visual-c---porting-and-upgrading-guide.md)