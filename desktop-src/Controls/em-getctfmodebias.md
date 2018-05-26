---
title: EM\_GETCTFMODEBIAS message
description: Gets the Text Services Framework mode bias values for a Microsoft Rich Edit control.
ms.assetid: 2421d37d-169d-480f-a5f7-4c6033ca6c1a
keywords:
- EM_GETCTFMODEBIAS message Windows Controls
topic_type:
- apiref
api_name:
- EM_GETCTFMODEBIAS
api_location:
- Richedit.h
api_type:
- HeaderDef
ms.date: 05/31/2018
ms.topic: article
ms.author: windowssdkdev
ms.prod: windows
ms.technology: desktop
---

# EM\_GETCTFMODEBIAS message

Gets the Text Services Framework mode bias values for a Microsoft Rich Edit control.

## Parameters

<dl> <dt>

*wParam* 
</dt> <dd>

Not used; must be zero.

</dd> <dt>

*lParam* 
</dt> <dd>

Not used; must be zero.

</dd> </dl>

## Return value

The current Text Services Framework mode bias value.

## Remarks

To get the IME mode bias, call [**EM\_GETIMEMODEBIAS**](em-getimemodebias.md).

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows XP with SP1 \[desktop apps only\]<br/>                                  |
| Minimum supported server<br/> | Windows Server 2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Richedit.h</dt> </dl> |



## See also

<dl> <dt>

**Reference**
</dt> <dt>

[**EM\_SETCTFMODEBIAS**](em-setctfmodebias.md)
</dt> <dt>

[**EM\_GETIMEMODEBIAS**](em-getimemodebias.md)
</dt> </dl>

 

 




