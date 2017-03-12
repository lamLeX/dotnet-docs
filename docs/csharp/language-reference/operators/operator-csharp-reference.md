---
title: "- Operator (C# Reference)1 | Microsoft Docs"
ms.custom: ""
ms.date: "2015-07-20"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-csharp"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "/_CSharpKeyword"
dev_langs: 
  - "CSharp"
helpviewer_keywords: 
  - "/ operator [C#]"
  - "division operator [C#]"
ms.assetid: d155e496-678f-4efa-bebe-2bd08da2c5af
caps.latest.revision: 21
author: "BillWagner"
ms.author: "wiwagn"
manager: "wpickett"
---
# / Operator (C# Reference)
[!INCLUDE[csharpbanner](../../../csharp/includes/csharpbanner.md)]

The division operator (`/`) divides its first operand by its second operand. All numeric types have predefined division operators.  
  
## Remarks  
 User-defined types can overload the `/` operator (see [operator](../../../csharp/language-reference/keywords/operator-csharp-reference.md)). An overload of the `/` operator implicitly overloads the [/= operator](../../../csharp/language-reference/operators/operator-csharp-reference.md).  
  
 When you divide two integers, the result is always an integer. For example, the result of 7 / 3 is 2. To determine the remainder of 7 / 3, use the remainder operator ([%](../../../csharp/language-reference/operators/modulus-operator.md)). To obtain a quotient as a rational number or fraction, give the dividend or divisor type `float` or type `double`. You can assign the type implicitly if you express the dividend or divisor as a decimal by putting a digit to the right side of the decimal point, as the following example shows.  
  
## Example  
 [!code-cs[csRefOperators#42](../../../csharp/language-reference/operators/codesnippet/csharp/csrefOperators/csrefOperators.cs#42)]  
  
## See Also  
 [C# Reference](../../../csharp/language-reference/index.md)   
 [C# Programming Guide](../../../csharp/programming-guide/index.md)   
 [C# Operators](../../../csharp/language-reference/operators/index.md)