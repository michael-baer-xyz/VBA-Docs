---
title: Rectangle.EventProcPrefix property (Access)
keywords: vbaac10.chm10278
f1_keywords:
- vbaac10.chm10278
ms.prod: access
api_name:
- Access.Rectangle.EventProcPrefix
ms.assetid: 7a7781fb-e715-b44c-39ac-6763114ab848
ms.date: 02/21/2019
ms.localizationpriority: medium
---


# Rectangle.EventProcPrefix property (Access)

Gets or sets the prefix portion of an event procedure name. Read/write **String**.


## Syntax

_expression_.**EventProcPrefix**

_expression_ A variable that represents a **[Rectangle](Access.Rectangle.md)** object.


## Remarks

For example, if you have a command button with an event procedure named **Details_Click**, the **EventProcPrefix** property returns the string **Details**.

Microsoft Access adds the prefix portion of an event procedure name to the event name with an underscore character ( _ ).




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]