---
title: Page.CalloutRelationshipAdded Event (Visio)
keywords: vis_sdr.chm10962075
f1_keywords:
- vis_sdr.chm10962075
ms.prod: visio
api_name:
- Visio.Page.CalloutRelationshipAdded
ms.assetid: b5181cd5-e763-a25c-abdc-3b32d2c902a0
ms.date: 06/08/2017
---


# Page.CalloutRelationshipAdded Event (Visio)

Occurs when a new callout relationship is added to the page.


## Syntax

Private Sub  _expression_ _**CalloutRelationshipAdded**( **_By Val ShapePair As RelatedShapePairEvent_** )

 _expression_ A variable that represents a **[Page](Visio.Page.md)** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _ShapePair_|Required| **[RelatedShapePairEvent](relatedshapepairVisio.Event.md)**|An object that represents the new callout shape-pair relationship.|

## Remarks

The  **RelatedShapePairEvent** object returned by this event contains two shapes: the callout, represented by the **[FromShapeID](Visio.RelatedShapePairEvent.FromShapeID.md)** property of the **RelatedShapePairEvent** object; and the target shape, represented by the **[ToShapeID](Visio.RelatedShapePairEvent.ToShapeID.md)** property.

If you are using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own  **[Event](Visio.Event.md)** objects, use the **[EventList.Add](Visio.EventList.Add.md)** or **[EventList.AddAdvise](Visio.EventList.AddAdvise.md)** method. To create an **Event** object that runs an add-on, use the **EventList.Add** method. To create an **Event** object that receives notification, use the **EventList.AddAdvise** method. To find an event code for the event you want to create, see[Event Codes](http://msdn.microsoft.com/library/de8f5c7a-421d-ebcf-22b6-4310a202ef64%28Office.15%29.aspx).


