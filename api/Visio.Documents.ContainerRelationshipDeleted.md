---
title: Documents.ContainerRelationshipDeleted Event (Visio)
keywords: vis_sdr.chm10662070
f1_keywords:
- vis_sdr.chm10662070
ms.prod: visio
api_name:
- Visio.Documents.ContainerRelationshipDeleted
ms.assetid: 1804110e-091f-f864-461a-8545338c4883
ms.date: 06/08/2017
---


# Documents.ContainerRelationshipDeleted Event (Visio)

Occurs when a container relationship is deleted from the document.


## Syntax

Private Sub  _expression_ _**ContainerRelationshipDeleted**( **_By Val ShapePair As RelatedShapePairEvent_** )

 _expression_ A variable that represents a **[Documents](Visio.Documents.md)** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _ShapePair_|Required| **[RelatedShapePairEvent](relatedshapepairVisio.Event.md)**|An object that represents the container shape-pair relationship.|

## Remarks

The  **RelatedShapePairEvent** object that this event returns contains two shapes: the container and the member, represented by the **[RelatedShapePairEvent.FromShapeID](Visio.RelatedShapePairEvent.FromShapeID.md)** and the **[RelatedShapePairEvent.ToShapeID](Visio.RelatedShapePairEvent.ToShapeID.md)** properties respectively. When Microsoft Visio deletes both shapes in the container relationship simultaneously, for example when both shapes are deleted from a drawing as part of a selection, the event does not fire.

If you are using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own  **[Event](Visio.Event.md)** objects, use the **[EventList.Add](Visio.EventList.Add.md)** or **[EventList.AddAdvise](Visio.EventList.AddAdvise.md)** method. To create an **Event** object that runs an add-on, use the **EventList.Add** method. To create an **Event** object that receives notification, use the **EventList.AddAdvise** method. To find an event code for the event you want to create, see[Event Codes](http://msdn.microsoft.com/library/de8f5c7a-421d-ebcf-22b6-4310a202ef64%28Office.15%29.aspx).


