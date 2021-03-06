---
title: OlkTimeZoneControl.MouseDown Event (Outlook)
keywords: vbaol11.chm1000518
f1_keywords:
- vbaol11.chm1000518
ms.prod: outlook
api_name:
- Outlook.OlkTimeZoneControl.MouseDown
ms.assetid: 5c544113-46ef-ddb0-0926-ec0c089465c5
ms.date: 06/08/2017
---


# OlkTimeZoneControl.MouseDown Event (Outlook)

Occurs when the user presses a mouse button on the control.


## Syntax

 _expression_ . **MouseDown**( **_Button_** , **_Shift_** , **_X_** , **_Y_** )

 _expression_ A variable that represents an **OlkTimeZoneControl** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _Button_|Required| **OlMouseButton**|An  **[OlMouseButton](Outlook.OlMouseButton.md)** constant that specifies which button on the mouse has been pressed.|
| _Shift_|Required| **OlShiftState**|A bitwise-OR mask of constants in the  **[OlShiftState](Outlook.OlShiftState.md)** enumeration that specifies whether the **SHIFT**,  **CTRL**, or  **ALT** keys have been pressed.|
| _X_|Required| **[OLE_XPOS_CONTAINER]**|Identifies the location of the mouse cursor on the X-axis relative to the form.|
| _Y_|Required| **[OLE_YPOS_CONTAINER]**|Identifies the location of the mouse cursor on the Y-axis relative to the form.|

## See also


#### Concepts


[OlkTimeZoneControl Object](Outlook.OlkTimeZoneControl.md)

