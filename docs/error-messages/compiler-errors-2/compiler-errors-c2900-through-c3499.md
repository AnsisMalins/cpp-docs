---
title: "Compiler Errors C2900 Through C2999 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: ""
ms.topic: "error-reference"
f1_keywords: 
  - "C2900"
  - "C2901"
  - "C2905"
  - "C2907"
  - "C2915"
  - "C2916"
  - "C2922"
  - "C2924"
  - "C2925"
  - "C2926"
  - "C2938"
  - "C2949"
  - "C2950"
  - "C2954"
  - "C2956"
  - "C2960"
  - "C2961"
  - "C2963"
  - "C2964"
  - "C2965"
  - "C2966"
  - "C2967"
  - "C2968"
  - "C2972"
  - "C2980"
  - "C2981"
  - "C2982"
  - "C2983"
  - "C2984"
  - "C2985"
  - "C2986"
  - "C2987"
  - "C2997"
  - "C2999"
helpviewer_keywords: 
  - "C2900"
  - "C2901"
  - "C2905"
  - "C2907"
  - "C2915"
  - "C2916"
  - "C2922"
  - "C2924"
  - "C2925"
  - "C2926"
  - "C2938"
  - "C2949"
  - "C2950"
  - "C2954"
  - "C2956"
  - "C2960"
  - "C2961"
  - "C2963"
  - "C2964"
  - "C2965"
  - "C2966"
  - "C2967"
  - "C2968"
  - "C2972"
  - "C2980"
  - "C2981"
  - "C2982"
  - "C2983"
  - "C2984"
  - "C2985"
  - "C2986"
  - "C2987"
  - "C2997"
  - "C2999"
dev_langs: 
  - "C++"
ms.assetid: e3440738-e11b-4878-9ae3-6bc6c53ba461
caps.latest.revision: 16
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
# Compiler Errors C2900 Through C2999
The articles in this part of the documentation contain information about a subsection of the Visual C++ compiler errors. You can access the information here or, in the **Output** window in Visual Studio, you can select an error number and then choose the F1 key.  
  
> [!NOTE]
>  Not every [!INCLUDE[vcprvc](../../build/includes/vcprvc_md.md)] error is documented in MSDN. In many cases, the diagnostic message provides all of the information that's available. If you think an error message needs additional explanation, you can let us know. You can use the feedback form on this page, or go to the menu bar in Visual Studio and choose **Help**, **Report a Bug**, or you can submit a suggestion or bug report on [Microsoft Connect](http://connect.microsoft.com/VisualStudio).  
  
 You may find additional assistance for errors and warnings on the MSDN public forums. The [Visual C++ Language](http://go.microsoft.com/fwlink/?LinkId=158195) forum is for questions and discussions about the [!INCLUDE[vcprvc](../../build/includes/vcprvc_md.md)] language syntax and compiler. The [Visual C++ General](http://go.microsoft.com/fwlink/?LinkId=158194) forum is for questions about [!INCLUDE[vcprvc](../../build/includes/vcprvc_md.md)] that are not discussed in other forums. You may also find help about errors and warnings on [Stack Overflow](http://stackoverflow.com/).  
  
|Error|Message|  
|-----------|-------------|  
|Compiler Error C2900|'*declarator*': member function templates in WinRT classes must be 'private', 'internal' or 'protected private'|  
|Compiler Error C2901|'*identifier*': A generic interface or delegate cannot be public|  
|[Compiler Error C2902](compiler-error-c2902.md)|'*token*': unexpected token following 'template/generic', identifier expected|  
|[Compiler Error C2903](compiler-error-c2903.md)|'*identifier*': symbol is neither a class template/generic nor a function template/generic|  
|[Compiler Error C2904](compiler-error-c2904.md)|'*identifier*': name already used for a template in the current scope|  
|Compiler Error C2905|Obsolete.|  
|[Compiler Error C2906](compiler-error-c2906.md)|'*template*': explicit specialization requires 'template <>'|  
|Compiler Error C2907|register argument '*number*' does not specify a valid register number|  
|[Compiler Error C2908](compiler-error-c2908.md)|explicit specialization; '*template*' has already been instantiated|  
|[Compiler Error C2909](compiler-error-c2909.md)|'*identifier*': explicit instantiation of function template requires return type|  
|[Compiler Error C2910](compiler-error-c2910.md)|'*function*': cannot be explicitly specialized|  
|[Compiler Error C2911](compiler-error-c2911.md)|'*member*': cannot be declared or defined in the current scope|  
|[Compiler Error C2912](compiler-error-c2912.md)|explicit specialization '*declaration*' is not a specialization of a function template|  
|[Compiler Error C2913](compiler-error-c2913.md)|explicit specialization; '*declaration*' is not a specialization of a class template|  
|[Compiler Error C2914](compiler-error-c2914.md)|'*identifier*': cannot deduce template/generic argument as function argument is ambiguous|  
|Compiler Error C2915|'*identifier*': '*type*' cannot be directly used on the published surface of a WinRT type. Use 'Platform::Object^' instead to pass this type|  
|Compiler Error C2916|'*identifier*': [FlagsAttribute] must (only) be specified on a public enum with an 'unsigned int' underlying type|  
|[Compiler Error C2917](compiler-error-c2917.md)|'*identifier*': invalid template-parameter|  
|[Compiler Error C2918](compiler-error-c2918.md)|'*identifier*': Indexed properties cannot be used on the published surface of a WinRT type|  
|[Compiler Error C2919](compiler-error-c2919.md)|'*type*': Operators cannot be used on the published surface of a WinRT type|  
|[Compiler Error C2920](compiler-error-c2920.md)|redefinition: '*type*': class template/generic has already been declared as '*declaration*'|  
|[Compiler Error C2921](compiler-error-c2921.md)|redefinition: '*type*': class template/generic is being redeclared as '*declaration*'|  
|Compiler Error C2922|'*interface*': A WinRT interface cannot contain static members|  
|[Compiler Error C2923](compiler-error-c2923.md)|'*type*': '*identifier*' is not a valid template/generic type argument for parameter '*parameter*'|  
|Compiler Error C2924|__declspec(interrupt) routine argument not in R2|  
|Compiler Error C2925|__declspec(interrupt) routine cannot use floating-point|  
|Compiler Error C2926|'*identifier*': a default member initializer is not allowed for a member of an anonymous struct within a union|  
|[Compiler Error C2927](compiler-error-c2927.md)|'*identifier*': a function template must be called with at least one argument|  
|[Compiler Error C2928](compiler-error-c2928.md)|explicit instantiation; '*identifier*' is not a function or static data member of template-class '*class*'|  
|[Compiler Error C2929](compiler-error-c2929.md)|'*declarator*': explicit instantiation; cannot explicitly force and suppress instantiation of template-class member|  
|[Compiler Error C2930](compiler-error-c2930.md)|'*class*': template-id/generic-id redefined as an enumerator of 'enum *identifier*'|  
|[Compiler Error C2931](compiler-error-c2931.md)|'*class1*': template-id/generic-id redefined as a member function of '*class2*'|  
|[Compiler Error C2932](compiler-error-c2932.md)|'*type*': template-id/generic-id redefined as a data member of '*identifier*'|  
|[Compiler Error C2933](compiler-error-c2933.md)|'*type*': template-id/generic-id redefined as a typedef member of '*identifier*'|  
|[Compiler Error C2934](compiler-error-c2934.md)|'*type*': template-id/generic-id redefined as a nested '*item*' of '*identifier*'|  
|[Compiler Error C2935](compiler-error-c2935.md)|'*type*': template-id/generic-id redefined as a global function|  
|[Compiler Error C2936](compiler-error-c2936.md)|'*type*': template-id/generic-id redefined as a global data variable|  
|[Compiler Error C2937](compiler-error-c2937.md)|'*type*': template-id/generic-id redefined as a global typedef|  
|Compiler Error C2938|'*identifier*' : Failed to specialize alias template|  
|[Compiler Error C2939](compiler-error-c2939.md)|'*type*': template-id/generic-id redefined as a local data variable|  
|[Compiler Error C2940](compiler-error-c2940.md)|'*type*': template-id/generic-id redefined as a local typedef|  
|[Compiler Error C2941](compiler-error-c2941.md)|'*type*': template-id/generic-id redefined as a local '*item*'|  
|[Compiler Error C2942](compiler-error-c2942.md)|'*type*': template-id/generic-id redefined as a formal argument of a function|  
|[Compiler Error C2943](compiler-error-c2943.md)|'*type*': template-id/generic-id redefined as a type argument of a template|  
|[Compiler Error C2944](compiler-error-c2944.md)|'*type*': template-id/generic-id redefined as a value argument of a template|  
|[Compiler Error C2945](compiler-error-c2945.md)|explicit instantiation does not refer to a template-class specialization|  
|[Compiler Error C2946](compiler-error-c2946.md)|explicit instantiation; '*type*' is not a template-class specialization|  
|[Compiler Error C2947](compiler-error-c2947.md)|expecting '>' to terminate template arguments, found '*token*'|  
|[Compiler Error C2948](compiler-error-c2948.md)|explicit instantiation; storage class specifier '*specifier*' not permitted on specialization|  
|Compiler Error C2949|thread_local is not supported with /kernel|  
|Compiler Error C2950|Obsolete.|  
|[Compiler Error C2951](compiler-error-c2951.md)|template/generic declarations are only permitted at global, namespace, or class scope|  
|[Compiler Error C2952](compiler-error-c2952.md)|'*declaration*': template/generic declaration missing template/generic parameter list|  
|[Compiler Error C2953](compiler-error-c2953.md)|'*type*': class template has already been defined|  
|Compiler Error C2954|instruction word argument not in range|  
|[Compiler Error C2955](compiler-error-c2955.md)|'*type*': use of class template/generic requires template/generic argument list|  
|Compiler Error C2956|sized deallocation function 'operator delete(void*, size_t)' would be chosen as placement deallocation function.|  
|[Compiler Error C2957](compiler-error-c2957.md)|'*token*': invalid left delimiter: expected '<'|  
|[Compiler Error C2958](compiler-error-c2958.md)|the left *delimiter* found at '*file*(*line_number*)' was not matched correctly|  
|[Compiler Error C2959](compiler-error-c2959.md)|a generic class or function may not be a member of a template|  
|Compiler Error C2960|Obsolete.|  
|Compiler Error C2961|'*function*': inconsistent explicit instantiations, a previous explicit instantiation did not specify '*argument*'|  
|[Compiler Error C2962](compiler-error-c2962.md)|syntax error: '*token*': expected template-class member function definition to end with '}'|  
|Compiler Error C2963|Obsolete.|  
|Compiler Error C2964|Obsolete.|  
|Compiler Error C2965|__declspec(*specifier*) is not supported with /kernel|  
|Compiler Error C2966|'*identifier1*': must have the same __declspec(code_seg(...)) as its base class '*identifier2*'|  
|Compiler Error C2967|'*identifier*': an overriding virtual function must have the same __declspec(code_seg(...)) as an overridden virtual function|  
|Compiler Error C2968|'*identifier*': recursive alias declaration|  
|[Compiler Error C2969](compiler-error-c2969.md)|syntax error: '*token*': expected member function definition to end with '}'|  
|[Compiler Error C2970](compiler-error-c2970.md)|'*type*': template parameter '*parameter*': '*argument*': an expression involving objects with internal linkage cannot be used as a non-type argument|  
|[Compiler Error C2971](compiler-error-c2971.md)|'*type*': template parameter '*parameter*': '*argument*': a variable with non-static storage duration cannot be used as a non-type argument|  
|Compiler Error C2972|'*type*': template parameter '*parameter*': the type of non-type argument is invalid|  
|[Compiler Error C2973](compiler-error-c2973.md)|'*template*': invalid template argument '*number*'|  
|[Compiler Error C2974](compiler-error-c2974.md)|'*type*': invalid template/generic argument for '*parameter*', type expected|  
|[Compiler Error C2975](compiler-error-c2975.md)|'*type*': invalid template argument for '*parameter*', expected compile-time constant expression|  
|[Compiler Error C2976](compiler-error-c2976.md)|'*type*': too few template/generic arguments|  
|[Compiler Error C2977](compiler-error-c2977.md)|'*type*': too many template/generic arguments|  
|[Compiler Error C2978](compiler-error-c2978.md)|syntax error: expected '*keyword1*' or '*keyword2*'; found type '*type*'; non-type parameters are not supported in generics|  
|[Compiler Error C2979](compiler-error-c2979.md)|explicit specializations are not supported in generics|  
|Compiler Error C2980|C++ exception handling is not supported with /kernel|  
|Compiler Error C2981|the dynamic form of '*keyword*' is not supported with /kernel|  
|Compiler Error C2982|'*declaration*': different __declspec(code_seg(...)) used: was '*identifier1*' now '*identifier2*'|  
|Compiler Error C2983|'*declaration*': all declarations must have an identical __declspec(code_seg(...))|  
|Compiler Error C2984|Obsolete.|  
|Compiler Error C2985|'*argument*': the argument to __declspec(code_seg(...)) must be a text section|  
|Compiler Error C2986|'*identifier*': __declspec(code_seg(...)) can only be applied to a class or a function|  
|Compiler Error C2987|a declaration cannot have both __declspec(code_seg('*identifier*')) and __declspec(code_seg('*value*'))|  
|[Compiler Error C2988](compiler-error-c2988.md)|unrecognizable template declaration/definition|  
|[Compiler Error C2989](compiler-error-c2989.md)|'*class*': class template/generic has already been declared as a non-class template/generic|  
|[Compiler Error C2990](compiler-error-c2990.md)|'*class*': non-class template/generic has already been declared as a class template/generic|  
|[Compiler Error C2991](compiler-error-c2991.md)|redefinition of template/generic parameter '*parameter*'|  
|[Compiler Error C2992](compiler-error-c2992.md)|'*class*': invalid or missing template/generic parameter list|  
|[Compiler Error C2993](compiler-error-c2993.md)|'*type*': illegal type for non-type template parameter '*identifier*'|  
|[Compiler Error C2994](compiler-error-c2994.md)|unnamed class in template parameter list|  
|[Compiler Error C2995](compiler-error-c2995.md)|'*declaration*': function template has already been defined|  
|[Compiler Error C2996](compiler-error-c2996.md)|'*function*': recursive function template definition|  
|Compiler Error C2997|'*function*': array bound cannot be deduced from a default member initializer|  
|[Compiler Error C2998](compiler-error-c2998.md)|'*declarator*': cannot be a template definition|  
|Compiler Error C2999|UNKNOWN ERROR  Please choose the Technical Support command on the Visual C++ Help menu, or open the Technical Support help file for more information|  
