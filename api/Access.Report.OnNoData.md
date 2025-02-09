---
title: Report.OnNoData property (Access)
keywords: vbaac10.chm13767,vbaac10.chm4135
f1_keywords:
- vbaac10.chm13767,vbaac10.chm4135
ms.prod: access
api_name:
- Access.Report.OnNoData
ms.assetid: 5d3cfec5-1b57-625c-c350-0d7e475be2d2
ms.date: 03/15/2019
ms.localizationpriority: medium
---


# Report.OnNoData property (Access)

Sets or returns the value of the **On No Data** box in the Properties window of a report. Read/write **String**.


## Syntax

_expression_.**OnNoData**

_expression_ A variable that represents a **[Report](Access.Report.md)** object.


## Remarks

This property is helpful for programmatically changing the action that Microsoft Access takes when an event is triggered. For example, between event calls you may want to change an expression's parameters, or switch from an event procedure to an expression or macro, depending on the circumstances under which the event was triggered. 

The **NoData** event occurs after Microsoft Access formats a report for printing that has no data (the report is bound to an empty recordset), but before the report is printed.

The **OnNoData** value will be one of the following, depending on the selection chosen in the Choose Builder window (accessed by choosing the **Build** button next to the **On No Data** box in the report's Properties window):

- If you choose Expression Builder, the value will be =_expression_, where _expression_ is the expression from the Expression Builder window.
    
- If you choose Macro Builder, the value is the name of the macro. 
    
- If you choose Code Builder, the value will be [Event Procedure]. 
    
If the **On No Data** box is blank, the property value is an empty string.


## Example

The following example prints the value of the **OnNoData** property in the Immediate window for the **Purchase Order** report.

```vb
Debug.Print Reports("Purchase Order").OnNoData
```



[!include[Support and feedback](~/includes/feedback-boilerplate.md)]