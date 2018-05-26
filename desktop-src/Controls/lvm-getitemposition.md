---
title: LVM\_GETITEMPOSITION message
description: Retrieves the position of a list-view item. You can send this message explicitly or by using the ListView\_GetItemPosition macro.
ms.assetid: e5841089-c34e-498e-b94c-45c845bfc747
keywords:
- LVM_GETITEMPOSITION message Windows Controls
topic_type:
- apiref
api_name:
- LVM_GETITEMPOSITION
api_location:
- Commctrl.h
api_type:
- HeaderDef
ms.date: 05/31/2018
ms.topic: article
ms.author: windowssdkdev
ms.prod: windows
ms.technology: desktop
---

# LVM\_GETITEMPOSITION message

Retrieves the position of a list-view item. You can send this message explicitly or by using the [**ListView\_GetItemPosition**](/windows/win32/Commctrl/nf-commctrl-listview_getitemposition?branch=master) macro.

## Parameters

<dl> <dt>

*wParam* 
</dt> <dd>

Index of the list-view item.

</dd> <dt>

*lParam* 
</dt> <dd>

Pointer to a [**POINT**](https://msdn.microsoft.com/library/windows/desktop/dd162805) structure that receives the position of the item's upper-left corner, in view coordinates.

</dd> </dl>

## Return value

Returns **TRUE** if successful, or **FALSE** otherwise.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server 2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Commctrl.h</dt> </dl> |



 

 




