---
description: "FormattedValue Property (ADO MD)"
title: "FormattedValue Property (ADO MD) | Microsoft Docs"
ms.prod: sql
ms.prod_service: connectivity
ms.technology: ado
ms.custom: ""
ms.date: "01/19/2017"
ms.reviewer: ""
ms.topic: reference
apitype: "COM"
f1_keywords: 
  - "Cell::FormattedValue"
  - "FormattedValue"
helpviewer_keywords: 
  - "FormattedValue property [ADO MD]"
ms.assetid: 5c06451e-06ec-4da6-9a87-2d043469248a
author: rothja
ms.author: jroth
---
# FormattedValue Property (ADO MD)
Indicates the formatted display of a [cell](./cell-object-ado-md.md) value.  
  
## Return Values  
 Returns a **String** and is read-only.  
  
## Remarks  
 Use the **FormattedValue** property to obtain the formatted display value of the [Value](./value-property-ado-md.md) property of a [Cell](./cell-object-ado-md.md) object. For example, if the value of a cell was 1056.87, and this value represented a dollar amount, **FormattedValue** would be $1,056.87.  
  
## Applies To  
 [Cell Object (ADO MD)](./cell-object-ado-md.md)  
  
## See Also  
 [Cellset Example (VB)](./cellset-example-vb.md)   
 [Value Property (ADO MD)](./value-property-ado-md.md)