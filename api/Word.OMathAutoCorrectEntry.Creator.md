---
title: OMathAutoCorrectEntry.Creator property (Word)
keywords: vbawd10.chm251723877
f1_keywords:
- vbawd10.chm251723877
ms.prod: word
api_name:
- Word.OMathAutoCorrectEntry.Creator
ms.assetid: ad83f97e-26fb-673d-1185-f6d745305c91
ms.date: 06/08/2017
ms.localizationpriority: medium
---


# OMathAutoCorrectEntry.Creator property (Word)

Returns a 32-bit integer that indicates the application in which the add-in was created. Read-only **Long**.


## Syntax

_expression_.**Creator**

 _expression_ An expression that returns an '[OMathAutoCorrectEntry](Word.OMathAutoCorrectEntry.md)' object.


## Remarks

If the object was created in Microsoft Word, the **Creator** property returns the hexadecimal number 4D535744, which represents the string "MSWD." This property was primarily designed to be used on the Macintosh, where each application has a four-character creator code. For example, Microsoft Word has the creator code MSWD. For additional information about this property, consult the language reference Help included with Microsoft Office Macintosh Edition.


> [!NOTE] 
> This value can also be represented by the constant **wdCreatorCode**.


## See also


[OMathAutoCorrectEntry Object](Word.OMathAutoCorrectEntry.md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]