---
title: Legend Object (Word)
keywords: vbawd10.chm2246
f1_keywords:
- vbawd10.chm2246
ms.prod: word
api_name:
- Word.Legend
ms.assetid: f0122074-87b7-0225-3c6c-406103fa4c29
ms.date: 06/08/2017
---


# Legend Object (Word)

Represents the legend in a chart. Each chart can have only one legend.


## Remarks

 The **Legend** object contains one or more **[LegendEntry](Word.LegendEntry.md)** objects; each **LegendEntry** object contains a **[LegendKey](Word.LegendKey.md)** object.

The chart legend is not visible unless the  **[HasLegend](Word.Chart.HasLegend.md)** property is **True** . If this property is **False** , properties and methods of the **Legend** object will fail.


## Example

Use the  **[Legend](Word.Chart.Legend.md)** property to return the **Legend** object. The following example sets the font style for the legend of the first chart in the active document to bold.


```vb
With ActiveDocument.InlineShapes(1) 
 If .HasChart Then 
 .Chart.Legend.Font.Bold = True 
 End If 
End With
```


## See also


#### Other resources


[Word Object Model Reference](http://msdn.microsoft.com/library/be452561-b436-bb9b-6f94-3faa9a74a6fd%28Office.15%29.aspx)


