---
title: Project.CurrencyCode property (Project)
ms.prod: project-server
api_name:
- Project.Project.CurrencyCode
ms.assetid: 12085e58-5520-600e-1a00-2822474303fe
ms.date: 06/08/2017
ms.localizationpriority: medium
---


# Project.CurrencyCode property (Project)

Project property for the three-character ISO standard currency code of the project. Read/write **String**.


## Syntax

_expression_. `CurrencyCode`

_expression_ A variable that represents a **[Project](project.project.md)** object.


## Example

The following example sets **CurrencyCode** to the three-character ISO currency code "JPY".


```vb
Sub ChangeCurrencyAndValidate() 
 ActiveProject.CurrencyCode = "JPY" 
 MsgBox (ActiveProject.CurrencyCode) 
End Sub
```

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]