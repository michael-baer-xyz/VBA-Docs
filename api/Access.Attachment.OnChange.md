---
title: Attachment.OnChange property (Access)
keywords: vbaac10.chm13942
f1_keywords:
- vbaac10.chm13942
ms.prod: access
api_name:
- Access.Attachment.OnChange
ms.assetid: c2c12032-463a-2e3e-f434-defce71c8138
ms.date: 02/07/2019
ms.localizationpriority: medium
---


# Attachment.OnChange property (Access)

Sets or returns the value of the **On Change** box in the Properties window of one of the objects in the **Applies To** list. Read/write **String**.


## Syntax

_expression_.**OnChange**

_expression_ A variable that represents an **[Attachment](Access.Attachment.md)** object.


## Remarks

This property is helpful for programmatically changing the action that Microsoft Access takes when an event is triggered. For example, between event calls you may want to change an expression's parameters, or switch from an event procedure to an expression or macro, depending on the circumstances under which the event was triggered.

The **[Change](access.attachment.change.md)** event occurs when the contents of a text box or the text portion of a combo box changes. It also occurs when you move from one page to another page in a tab control.

The **OnChange** value will be one of the following, depending on the selection chosen in the Choose Builder window (accessed by choosing the **Build** button next to the **On Change** box in the object's Properties window):

- If you choose Expression Builder, the value will be =_expression_, where _expression_ is the expression from the Expression Builder window.
    
- If you choose Macro Builder, the value is the name of the macro. 
    
- If you choose Code Builder, the value will be [Event Procedure]. 
    
If the **On Change** box is blank, the property value is an empty string.




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]