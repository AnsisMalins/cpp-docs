---
title: "Compiler Errors C2300 Through C2399 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: ""
ms.topic: "error-reference"
f1_keywords: 
  - "C2303"
  - "C2304"
  - "C2305"
  - "C2306"
  - "C2314"
  - "C2321"
  - "C2323"
  - "C2328"
  - "C2329"
  - "C2330"
  - "C2331"
  - "C2335"
  - "C2336"
  - "C2339"
  - "C2340"
  - "C2342"
  - "C2343"
  - "C2347"
  - "C2354"
  - "C2358"
  - "C2359"
  - "C2363"
  - "C2366"
  - "C2367"
  - "C2398"
  - "C2399"
helpviewer_keywords: 
  - "C2303"
  - "C2304"
  - "C2305"
  - "C2306"
  - "C2314"
  - "C2321"
  - "C2323"
  - "C2328"
  - "C2329"
  - "C2330"
  - "C2331"
  - "C2335"
  - "C2336"
  - "C2339"
  - "C2340"
  - "C2342"
  - "C2343"
  - "C2347"
  - "C2354"
  - "C2358"
  - "C2359"
  - "C2363"
  - "C2366"
  - "C2367"
  - "C2398"
  - "C2399"
dev_langs: 
  - "C++"
ms.assetid: 07ca45b5-b2f0-4049-837b-40a7a3caed88
caps.latest.revision: 14
author: "corob-msft"
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
# Compiler Errors C2300 Through C2399
The articles in this part of the documentation contain information about a subsection of the Visual C++ compiler errors. You can access the information here or, in the **Output** window in Visual Studio, you can select an error number and then choose the F1 key.  
  
> [!NOTE]
>  Not every [!INCLUDE[vcprvc](../../build/includes/vcprvc_md.md)] error is documented in MSDN. In many cases, the diagnostic message provides all of the information that's available. If you think an error message needs additional explanation, you can let us know. You can use the feedback form on this page, or go to the menu bar in Visual Studio and choose **Help**, **Report a Bug**, or you can submit a suggestion or bug report on [Microsoft Connect](http://connect.microsoft.com/VisualStudio).  
  
 You may find additional assistance for errors and warnings on the MSDN public forums. The [Visual C++ Language](http://go.microsoft.com/fwlink/?LinkId=158195) forum is for questions and discussions about the [!INCLUDE[vcprvc](../../build/includes/vcprvc_md.md)] language syntax and compiler. The [Visual C++ General](http://go.microsoft.com/fwlink/?LinkId=158194) forum is for questions about [!INCLUDE[vcprvc](../../build/includes/vcprvc_md.md)] that are not discussed in other forums. You may also find help about errors and warnings on [Stack Overflow](http://stackoverflow.com/).  
  
|Error|Message|  
|-----------|-------------|  
|[Compiler Error C2300](compiler-error-c2300.md)|'*class*': class does not have a destructor called '~*class*'|  
|[Compiler Error C2301](compiler-error-c2301.md)|left of '->~*identifier*' must point to class/struct/union|  
|[Compiler Error C2302](compiler-error-c2302.md)|left of '.~*identifier*' must have class/struct/union type|  
|Compiler Error C2303|Structured exception handling cannot be used in a coroutine|  
|Compiler Error C2304|'*keyword*' cannot be used inside of a catch block|  
|Compiler Error C2305|'*file*' does not contain debugging information for this module|  
|Compiler Error C2306|'*file*' does not contain the most recent debugging information for this module|  
|[Compiler Error C2307](compiler-error-c2307.md)|pragma *directive* must be moved outside of the function if incremental compilation is enabled|  
|[Compiler Error C2308](compiler-error-c2308.md)|concatenating mismatched strings|  
|[Compiler Error C2309](compiler-error-c2309.md)|catch handler expected a parenthesized exception declaration|  
|[Compiler Error C2310](compiler-error-c2310.md)|catch handlers must specify one type|  
|[Compiler Error C2311](compiler-error-c2311.md)|'*type*': is caught by '...' on line *number*|  
|[Compiler Error C2312](compiler-error-c2312.md)|'*type1*': is caught by '*type2*' on line *number*|  
|[Compiler Error C2313](compiler-error-c2313.md)|'*type1*': is caught by reference ('*type2*') on line *number*|  
|Compiler Error C2314|keyword '*keyword1*' is deprecated: use '*keyword2*' instead|  
|[Compiler Error C2315](compiler-error-c2315.md)|'*type1*': reference is caught by '*type2*' on line *number*|  
|[Compiler Error C2316](compiler-error-c2316.md)|'*type*': cannot be caught as the destructor and/or copy constructor are inaccessible or deleted|  
|[Compiler Error C2317](compiler-error-c2317.md)|'try' block starting on line '*number*' has no catch handlers|  
|[Compiler Error C2318](compiler-error-c2318.md)|no try block associated with this catch handler|  
|[Compiler Error C2319](compiler-error-c2319.md)|'try/catch' must be followed by a compound statement. Missing '{'|  
|[Compiler Error C2320](compiler-error-c2320.md)|expected ':' to follow access specifier '*specifier*'|  
|Compiler Error C2321|'*identifier*' is a keyword, and cannot be used in this context|  
|[Compiler Error C2322](compiler-error-c2322.md)|'*identifier*': address of dllimport '*identifier*' is not static|  
|Compiler Error C2323|'*identifier*': non-member operator new or delete functions may not be declared static or in a namespace other than the global namespace|  
|[Compiler Error C2324](compiler-error-c2324.md)|'*identifier*': unexpected to the right of '::~'|  
|[Compiler Error C2325](compiler-error-c2325.md)|'*type1*': unexpected type to the right of '->~': expected '*type2*'|  
|[Compiler Error C2326](compiler-error-c2326.md)|'*declarator*': function cannot access '*identifier*'|  
|[Compiler Error C2327](compiler-error-c2327.md)|'*identifier*': is not a type name, static, or enumerator|  
|Compiler Error C2328|'*keyword*': keyword is not yet supported|  
|Compiler Error C2329|'*identifier*': __ptr64 not available for pointers to functions|  
|Compiler Error C2330|'implementation_key( )' is only valid in a region bounded by #pragma start_map_region/stop_map_region|  
|Compiler Error C2331|access to '*identifier*' now defined to be '*accessibility1*', previously it was defined to be '*accessibility2*'|  
|[Compiler Error C2332](compiler-error-c2332.md)|'*typedef*': missing tag name|  
|[Compiler Error C2333](compiler-error-c2333.md)|'*function*': error in function declaration; skipping function body|  
|[Compiler Error C2334](compiler-error-c2334.md)|unexpected token(s) preceding '*token*'; skipping apparent function body|  
|Compiler Error C2335|'*identifier*': a type cannot be introduced in a function parameter list|  
|Compiler Error C2336|'*type*': illegal type|  
|[Compiler Error C2337](compiler-error-c2337.md)|'*attribute*': attribute not found|  
|[Compiler Error C2338](compiler-error-c2338.md)|*(error message from external provider)*|  
|Compiler Error C2339|'*identifier*': illegal type in embedded-IDL|  
|Compiler Error C2340|'*identifier*': 'static' can only be used within a class definition|  
|[Compiler Error C2341](compiler-error-c2341.md)|'*section*': segment must be defined using #pragma data_seg, code_seg or section prior to use|  
|Compiler Error C2342|syntax error: conflicting type qualifiers|  
|Compiler Error C2343|'*section*': conflicting section attributes|  
|[Compiler Error C2344](compiler-error-c2344.md)|align(*number*): alignment must be power of two|  
|[Compiler Error C2345](compiler-error-c2345.md)|align(*number*): illegal alignment value|  
|[Compiler Error C2346](compiler-error-c2346.md)|'*function*' cannot be compiled as native: '*explanation*'|  
|Compiler Error C2347|Obsolete.|  
|[Compiler Error C2348](compiler-error-c2348.md)|'*type*': is not a C-style aggregate, cannot be exported in embedded-IDL|  
|[Compiler Error C2349](compiler-error-c2349.md)|'*function*' cannot be compiled as managed: '*explanation*'; use #pragma unmanaged|  
|[Compiler Error C2350](compiler-error-c2350.md)|'*identifier*' is not a static member|  
|[Compiler Error C2351](compiler-error-c2351.md)|obsolete C++ constructor initialization syntax|  
|[Compiler Error C2352](compiler-error-c2352.md)|'*identifier*': illegal call of non-static member function|  
|[Compiler Error C2353](compiler-error-c2353.md)|exception specification is not allowed|  
|Compiler Error C2354|Obsolete.|  
|[Compiler Error C2355](compiler-error-c2355.md)|'this': can only be referenced inside non-static member functions or non-static data member initializers|  
|[Compiler Error C2356](compiler-error-c2356.md)|initialization segment must not change during translation unit|  
|[Compiler Error C2357](compiler-error-c2357.md)|'*identifier*': must be a function of type '*type*'|  
|Compiler Error C2358|'*identifier*': a static property cannot be defined outside of a class definition|  
|Compiler Error C2359|Obsolete.|  
|[Compiler Error C2360](compiler-error-c2360.md)|initialization of '*identifier*' is skipped by 'case' label|  
|[Compiler Error C2361](compiler-error-c2361.md)|initialization of '*identifier*' is skipped by 'default' label|  
|[Compiler Error C2362](compiler-error-c2362.md)|initialization of '*identifier*' is skipped by 'goto *label*'|  
|Compiler Error C2363|compiler intrinsic numeric limit function requires a string literal argument|  
|[Compiler Error C2364](compiler-error-c2364.md)|'*type*': illegal type for custom attribute|  
|[Compiler Error C2365](compiler-error-c2365.md)|'*member1*': redefinition; previous definition was '*member2*'|  
|Compiler Error C2366|'*identifier*': redefinition; different implementation_key specifiers|  
|Compiler Error C2367|Obsolete.|  
|[Compiler Error C2368](compiler-error-c2368.md)|'*identifier*': redefinition; different allocation specifiers|  
|[Compiler Error C2369](compiler-error-c2369.md)|'*identifier*': redefinition; different subscripts|  
|[Compiler Error C2370](compiler-error-c2370.md)|'*identifier*': redefinition; different storage class|  
|[Compiler Error C2371](compiler-error-c2371.md)|'*identifier*': redefinition; different basic types|  
|[Compiler Error C2372](compiler-error-c2372.md)|'*identifier*': redefinition; different types of indirection|  
|[Compiler Error C2373](compiler-error-c2373.md)|'*identifier*': redefinition; different type modifiers|  
|[Compiler Error C2374](compiler-error-c2374.md)|'*identifier*': redefinition; multiple initialization|  
|[Compiler Error C2375](compiler-error-c2375.md)|'*identifier*': redefinition; different linkage|  
|[Compiler Error C2376](compiler-error-c2376.md)|'*identifier*': redefinition; different based allocation|  
|[Compiler Error C2377](compiler-error-c2377.md)|'*identifier*': redefinition; typedef cannot be overloaded with any other symbol|  
|[Compiler Error C2378](compiler-error-c2378.md)|'*identifier*': redefinition; symbol cannot be overloaded with a typedef|  
|[Compiler Error C2379](compiler-error-c2379.md)|formal parameter *number* has different type when promoted|  
|[Compiler Error C2380](compiler-error-c2380.md)|type(s) preceding '*identifier*' (constructor with return type, or illegal redefinition of current class-name?)|  
|[Compiler Error C2381](compiler-error-c2381.md)|'*identifier*': redefinition; '__declspec(noreturn)' or '[[noreturn]]' differs|  
|[Compiler Error C2382](compiler-error-c2382.md)|'*identifier*': redefinition; different exception specifications|  
|[Compiler Error C2383](compiler-error-c2383.md)|'*identifier*': default-arguments are not allowed on this symbol|  
|[Compiler Error C2384](compiler-error-c2384.md)|'*member*': cannot apply thread_local or __declspec(thread) to a member of a managed/WinRT class|  
|[Compiler Error C2385](compiler-error-c2385.md)|ambiguous access of '*member*'|  
|[Compiler Error C2386](compiler-error-c2386.md)|'*identifier*': a symbol with this name already exists in the current scope|  
|[Compiler Error C2387](compiler-error-c2387.md)|'*identifier*': ambiguous base class|  
|[Compiler Error C2388](compiler-error-c2388.md)|'*identifier*': a symbol cannot be declared with both __declspec(appdomain) and __declspec(process)|  
|[Compiler Error C2389](compiler-error-c2389.md)|'*operator*': illegal operand 'nullptr'|  
|[Compiler Error C2390](compiler-error-c2390.md)|'*identifier*': incorrect storage class '*specifier*'|  
|[Compiler Error C2391](compiler-error-c2391.md)|'*identifier*': 'friend' cannot be used during type definition|  
|[Compiler Error C2392](compiler-error-c2392.md)|'*member1*': covariant returns types are not supported in managed/WinRT types, otherwise '*member2*' would be overridden|  
|[Compiler Error C2393](compiler-error-c2393.md)|'*symbol*': per-appdomain symbol cannot be allocated in segment '*segment*'|  
|[Compiler Error C2394](compiler-error-c2394.md)|'*type*::operator *operator*': CLR/WinRT operator not valid. At least one parameter must be of the following types:  'T^', 'T^%', 'T^&', where T = '*type*'|  
|[Compiler Error C2395](compiler-error-c2395.md)|'*type*::operator *operator*': CLR/WinRT operator not valid. At least one parameter must be of the following types: 'T', 'T%', 'T&', 'T^', 'T^%', 'T^&', where T = '*type*'|  
|[Compiler Error C2396](compiler-error-c2396.md)|'*type1*::operator *type2*': CLR/WinRT user-defined conversion function not valid. Must either convert from or convert to: 'T^', 'T^%', 'T^&', where T = '*type1*'|  
|[Compiler Error C2397](compiler-error-c2397.md)|conversion from '*type1*' to '*type2*' requires a narrowing conversion|  
|Compiler Error C2398|Element '*number*': conversion from '*type1*' to '*type2*' requires a narrowing conversion|  
|Compiler Error C2399|Obsolete.|  
