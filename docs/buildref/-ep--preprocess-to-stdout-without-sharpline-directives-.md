---
title: "-EP (Preprocess to stdout Without #line Directives)"
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
  - "/ep"
  - "VC.Project.VCCLCompilerTool.GeneratePreprocessedFileNoLines"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "copy preprocessor output to stdout"
  - "preprocessor output, copy to stdout"
  - "-EP compiler option [C++]"
  - "EP compiler option [C++]"
  - "/EP compiler option [C++]"
ms.assetid: 6ec411ae-e33d-4ef5-956e-0054635eabea
caps.latest.revision: 10
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
# /EP (Preprocess to stdout Without #line Directives)
Preprocesses C and C++ source files and copies the preprocessed files to the standard output device.  
  
## Syntax  
  
```  
/EP  
```  
  
## Remarks  
 In the process, all preprocessor directives are carried out, macro expansions are performed, and comments are removed. To preserve comments in the preprocessed output, use the [/C (Preserve Comments During Preprocessing)](../buildref/-c--preserve-comments-during-preprocessing-.md) option with **/EP**.  
  
 The **/EP** option suppresses compilation. You must resubmit the preprocessed file for compilation. **/EP** also suppresses the output files from the **/FA**, **/Fa**, and **/Fm** options. For more information, see [/FA, /Fa (Listing File)](../buildref/-fa---fa--listing-file-.md) and [/Fm (Name Mapfile)](../buildref/-fm--name-mapfile-.md).  
  
 Errors generated during later stages of processing refer to the line numbers of the preprocessed file rather than the original source file. If you want line numbers to refer to the original source file, use [/E (Preprocess to stdout)](../buildref/-e--preprocess-to-stdout-.md) instead. The **/E** option adds `#line` directives to the output for this purpose.  
  
 To send the preprocessed output, with `#line` directives, to a file, use the [/P (Preprocess to a File)](../buildref/-p--preprocess-to-a-file-.md) option instead.  
  
 To send the preprocessed output to stdout, with `#line` directives, use **/P** and **/EP** together.  
  
 You cannot use precompiled headers with the **/EP** option.  
  
### To set this compiler option in the Visual Studio development environment  
  
1.  Open the project's **Property Pages** dialog box. For details, see [How to: Open Project Property Pages](../notintoc/how-to--open-project-property-pages.md).  
  
2.  Click the **C/C++** folder.  
  
3.  Click the **Preprocessor** property page.  
  
4.  Modify the **Generate Preprocessed File** property.  
  
### To set this compiler option programmatically  
  
-   See \<xref:Microsoft.VisualStudio.VCProjectEngine.VCCLCompilerTool.GeneratePreprocessedFile*>.  
  
## Example  
 The following command line preprocesses file `ADD.C`, preserves comments, and displays the result on the standard output device:  
  
```  
CL /EP /C ADD.C  
```  
  
## See Also  
 [Compiler Options](../buildref/compiler-options.md)   
 [Setting Compiler Options](../buildref/setting-compiler-options.md)