---
title: "regex_error Class"
ms.custom: na
ms.date: 10/05/2016
ms.devlang: 
  - C++
ms.prod: visual-studio-dev14
ms.reviewer: na
ms.suite: na
ms.technology: 
  - devlang-cpp
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 3333a1a3-ca6f-4612-84b2-1b4c7e3db5a4
caps.latest.revision: 16
manager: ghogen
translation.priority.mt: 
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
# regex_error Class
Reports a bad basic_regex object.  
  
## Syntax  
  
```  
class regex_error  
    : public std::runtime_error {  
public:  
    explicit regex_error(regex_constants::error_code error);  
    regex_constants::error_code code() const;  
    };  
```  
  
## Remarks  
 The class describes an exception object thrown to report an error in the construction or use of a `basic_regex` object.  
  
## Requirements  
 **Header:** <regex\>  
  
 **Namespace:** std  
  
##  <a name="regex_error__code"></a>  regex_error::code  
 Returns the error code.  
  
```  
regex_constants::error_code code() const;  
```  
  
### Remarks  
 The member function returns the value that was passed to the object's constructor.  
  
### Example  
  
```  
// std_tr1__regex__regex_error_code.cpp   
// compile with: /EHsc   
#include <regex>   
#include <iostream>   
  
int main()   
    {   
    std::regex_error paren(std::regex_constants::error_paren);   
  
    try   
        {   
        std::regex rx("(a");   
        }   
    catch (const std::regex_error& rerr)   
        {   
        std::cout << "regex error: "   
            << (rerr.code() == paren.code()   
                ? "unbalanced parentheses" : "?")   
            << std::endl;   
        }   
    catch (...)   
        {   
        std::cout << "unknown exception" << std::endl;   
        }   
  
    return (0);   
    }  
  
```  
  
  **regex error: unbalanced parentheses**    
##  <a name="regex_error__regex_error"></a>  regex_error::regex_error  
 Constructs the object.  
  
```  
regex_error(regex_constants::error_code error);  
```  
  
### Parameters  
 `error`  
 The error code.  
  
### Remarks  
 The constructor constructs an object that holds the value `error`.  
  
### Example  
  
```  
// std_tr1__regex__regex_error_construct.cpp   
// compile with: /EHsc   
#include <regex>   
#include <iostream>   
  
int main()   
    {   
    std::regex_error paren(std::regex_constants::error_paren);   
  
    try   
        {   
        std::regex rx("(a");   
        }   
    catch (const std::regex_error& rerr)   
        {   
        std::cout << "regex error: "   
            << (rerr.code() == paren.code()   
                ? "unbalanced parentheses" : "?")   
            << std::endl;   
        }   
    catch (...)   
        {   
        std::cout << "unknown exception" << std::endl;   
        }   
  
    return (0);   
    }  
  
```  
  
  **regex error: unbalanced parentheses**    
## See Also  
 [<regex\>](../VS_visualcpp/-regex-.md)   
 [regex_error](../VS_visualcpp/regex_error-Class.md)