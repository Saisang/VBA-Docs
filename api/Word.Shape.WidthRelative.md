---
title: Shape.WidthRelative Property (Word)
keywords: vbawd10.chm161480906
f1_keywords:
- vbawd10.chm161480906
ms.prod: word
api_name:
- Word.Shape.WidthRelative
ms.assetid: db076311-7ecf-3564-9cf4-400663ae400b
ms.date: 06/08/2017
---


# Shape.WidthRelative Property (Word)

Returns or sets a  **Single** that represents the relative width of a shape. Read/write.


## Syntax

 _expression_ . **WidthRelative**

 _expression_ An expression that returns a **[Shape](Word.Shape.md)** object.


## Remarks

Use this property with the  **[RelativeVerticalSize](Word.Shape.RelativeVerticalSize.md)** property. When set to **wdShapeSizeRelativeNone** (-999999) (see the **[WdShapeSizeRelative](Word.WdShapeSizeRelative.md)** enumeration), this property should be ignored because the shape does not use percent sizing. The width is solely determined by the **[Width](Word.Shape.Width.md)** property.


## See also


#### Concepts


[Shape Object](Word.Shape.md)

