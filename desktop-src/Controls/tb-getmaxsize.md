---
title: TB\_GETMAXSIZE message
description: Retrieves the total size of all of the visible buttons and separators in the toolbar.
ms.assetid: '560e6ce2-00ef-46c3-b1d8-fbe0ac79c888'
keywords: ["TB_GETMAXSIZE message Windows Controls"]
topic_type:
- apiref
api_name:
- TB_GETMAXSIZE
api_location:
- Commctrl.h
api_type:
- HeaderDef
---

# TB\_GETMAXSIZE message

Retrieves the total size of all of the visible buttons and separators in the toolbar.

## Parameters

<dl> <dt>

*wParam* 
</dt> <dd>Must be zero.</dd> <dt>

*lParam* 
</dt> <dd>

Pointer to a [**SIZE**](https://msdn.microsoft.com/library/windows/desktop/dd145106) structure that receives the size of the items.

</dd> </dl>

## Return value

Returns nonzero if successful, or zero otherwise.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server�2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Commctrl.h</dt> </dl> |



�

�




