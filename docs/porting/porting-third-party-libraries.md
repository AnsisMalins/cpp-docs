---
title: "Porting Third-Party Libraries | Microsoft Docs"
ms.custom: ""
ms.date: "01/10/2017"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "3rd-party libraries"
  - "vspkg"
ms.assetid: b055ed20-8a9e-45b2-ac2a-e3d94271c009
caps.latest.revision: 0
author: "mikeblome"
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

# Porting third-party libraries

When you upgrade a project to the current version of Visual C++, you also have to upgrade any libraries that the project uses, so that the library and your project are built with the same version and flavor of the compiler. (For more information, see [Overview of potential upgrade issues](overview-of-potential-upgrade-issues-visual-cpp.md)). 

## Introducing vcpkg
In the past, finding and upgrading 3rd party libraries was sometimes a non-trivial task. To make it easier to acquire and rebuild C++ 3rd party open source libraries, the Visual C++ team has created a command-line tool called the **VC++ Packaging Tool** or **vcpkg**. Vcpkg has a searchable catalog of many popular C++ open-source libraries. You can install any library in the catalog directly from the vcpkg command line. When you install a library, Vcpkg creates a directory tree on your machine and adds the .h, the .lib and binaries in this folder. You can use this folder in your compilation command line, or integrate it into Visual Studio 2015 or later by using the vcpkg integrate install command. After you integrate a library location, Visual Studio can find it and add it to any new project that you create. To use a library, just #include it, and Visual Studio will automatically add the .lib path to your project settings and copy the dll to your solution folder.

## Acquisition and usage

You can download vcpkg from the [vcpkg GitHub repo][vcpkg](https://github.com/Microsoft/vcpkg/).

 - To search a library in the catalog: vcpkg search <LibName>
 - To acquire a library (for example Boost): vcpkg install boost
 - To list the libs that are currently installed: vcpkg list

The blog post [Vcpkg: a tool to acquire and build C++ open source libraries on Windows](https://blogs.msdn.microsoft.com/vcblog/2016/09/19/vcpkg-a-tool-to-acquire-and-build-c-open-source-libraries-on-windows/) explains how vcpkg works and gives a list of supported libraries. The list is updated every week.

## Reporting issues
If your library is not present in vcpkg catalog, you can open an issue on the [GitHub repo](https://github.com/Microsoft/vcpkg/issues) where the community and the Visual C++ team can see it and potentially create the port file for this library.

For proprietary 3rd party libraries (non-open source) we recommend that you contact the library provider. However, we are interested to know of any proprietary libs you are using and block you, let us know which one you depend on (you can contact us at vcupgrade@microsoft.com).

  
## See Also  
 [Visual C++ Porting and Upgrading Guide](visual-cpp-porting-and-upgrading-guide.md)
