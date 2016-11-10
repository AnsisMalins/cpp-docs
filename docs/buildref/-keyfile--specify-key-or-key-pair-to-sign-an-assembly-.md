---
title: "-KEYFILE (Specify Key or Key Pair to Sign an Assembly)"
ms.custom: na
ms.date: "10/14/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: na
ms.suite: na
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: na
ms.topic: "article"
f1_keywords: 
  - "/keyfile"
  - "VC.Project.VCLinkerTool.KeyFile"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "/KEYFILE linker option"
  - "-KEYFILE linker option"
  - "KEYFILE linker option"
ms.assetid: 9b71f8c0-541c-4fe5-a0c7-9364f42ecb06
caps.latest.revision: 12
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
# /KEYFILE (Specify Key or Key Pair to Sign an Assembly)
```  
/KEYFILE:filename  
```  
  
## Remarks  
 where:  
  
 *filename*  
 File that contains the key. Place the string in double quotation marks (" ") if it contains a space.  
  
## Remarks  
 The linker inserts the public key into the assembly manifest and then signs the final assembly with the private key. To generate a key file, type [sn -k](../Topic/Sn.exe%20\(Strong%20Name%20Tool\).md) `file` at the command line. A signed assembly is said to have a strong name.  
  
 If you compile with [/LN](../buildref/-ln--create-msil-module-.md), the name of the key file is held in the module and incorporated into the assembly that is created when you compile an assembly that includes an explicit reference to the module, via [#using](../c/sharpusing-directive--c---.md), or when linking with [/ASSEMBLYMODULE](../buildref/-assemblymodule--add-a-msil-module-to-the-assembly-.md).  
  
 You can also pass your encryption information to the linker with [/KEYCONTAINER](../buildref/-keycontainer--specify-a-key-container-to-sign-an-assembly-.md). Use [/DELAYSIGN](../buildref/-delaysign--partially-sign-an-assembly-.md) if you want a partially signed assembly. See [Strong Name Assemblies (Assembly Signing) (C++/CLI)](../cli/strong-name-assemblies--assembly-signing---c---cli-.md) for more information on signing an assembly.  
  
 In case both **/KEYFILE** and **/KEYCONTAINER** are specified (either by command line option or by custom attribute), the linker will first try the key container. If that succeeds, then the assembly is signed with the information in the key container. If the linker does not find the key container, it will try the file specified with /KEYFILE. If that succeeds, the assembly is signed with the information in the key file and the key information will be installed in the key container (similar to sn -i) so that on the next compilation, the key container will be valid.  
  
 Note that a key file might contain only the public key.  
  
 See [Creating and Using Strong-Named Assemblies](../Topic/Creating%20and%20Using%20Strong-Named%20Assemblies.md) for more information on signing an assembly.  
  
 Other linker options that affect assembly generation are:  
  
-   [/ASSEMBLYDEBUG](../buildref/-assemblydebug--add-debuggableattribute-.md)  
  
-   [/ASSEMBLYLINKRESOURCE](../buildref/-assemblylinkresource--link-to-.net-framework-resource-.md)  
  
-   [/ASSEMBLYMODULE](../buildref/-assemblymodule--add-a-msil-module-to-the-assembly-.md)  
  
-   [/ASSEMBLYRESOURCE](../buildref/-assemblyresource--embed-a-managed-resource-.md)  
  
-   [/NOASSEMBLY](../buildref/-noassembly--create-a-msil-module-.md)  
  
### To set this linker option in the Visual Studio development environment  
  
1.  Open the project's **Property Pages** dialog box. For details, see [Setting Visual C++ Project Properties](../ide/working-with-project-properties.md).  
  
2.  Click the **Linker** folder.  
  
3.  Click the **Command Line** property page.  
  
4.  Type the option into the **Additional Options** box.  
  
### To set this linker option programmatically  
  
-   See \<xref:Microsoft.VisualStudio.VCProjectEngine.VCLinkerTool.AdditionalOptions*>.  
  
## See Also  
 [Setting Linker Options](../buildref/setting-linker-options.md)   
 [Linker Options](../buildref/linker-options.md)