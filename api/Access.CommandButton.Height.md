---
title: CommandButton.Height Property (Access)
keywords: vbaac10.chm10470
f1_keywords:
- vbaac10.chm10470
ms.prod: access
api_name:
- Access.CommandButton.Height
ms.assetid: 40b8e9fb-8573-7bb2-9467-12ca5b593a04
ms.date: 06/08/2017
---


# CommandButton.Height Property (Access)

Gets or sets the height of the specified object in twips. Read/write  **Integer**.


## Syntax

 _expression_. `Height`

 _expression_ A variable that represents a [CommandButton](Access.CommandButton.md) object.


## Remarks

For report controls, you can set the  **Height** property when you print or preview a report only by using a macro or an event procedure specified in a section's **OnFormat** event property setting.

Microsoft Access automatically sets the  **Height** property when you create or size a control or when you size a window in form Design View or report Design view.

The height of controls is measured from the center of their borders so controls with different border widths align correctly. 


## See also


[CommandButton Object](Access.CommandButton.md)

