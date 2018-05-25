---
Description: 'Retrieves the IInkAnalysisRecognizer at the specified index.'
ms.assetid: 'e4db56c6-7c15-4336-bc0a-f50222c3520e'
title: 'IInkAnalysisRecognizers::GetInkAnalysisRecognizer method'
---

# IInkAnalysisRecognizers::GetInkAnalysisRecognizer method

Retrieves the [**IInkAnalysisRecognizer**](iinkanalysisrecognizer.md) at the specified index.

## Syntax


```C++
HRESULT GetInkAnalysisRecognizer(
  [in]��ULONG �����������������ulIndex,
  [out]�IInkAnalysisRecognizer **ppInkAnalysisRecognizer
);
```



## Parameters

<dl> <dt>

*ulIndex* \[in\]
</dt> <dd>

The zero-based index of the [**IInkAnalysisRecognizer**](iinkanalysisrecognizer.md) object to get.

</dd> <dt>

*ppInkAnalysisRecognizer* \[out\]
</dt> <dd>

A pointer to the [**IInkAnalysisRecognizer**](iinkanalysisrecognizer.md) at the specified index.

</dd> </dl>

## Return value

For a description of the return values, see [Classes and Interfaces - Ink Analysis](classes-and-interfaces---ink-analysis.md).

## Remarks

> \[!Caution\]  
> To avoid a memory leak, call [**IUnknown::Release**](https://msdn.microsoft.com/library/windows/desktop/ms682317) on \**ppInkAnalysisRecognizer* when you no longer need to use the ink analysis recognizer.

�

## Requirements



|                                     |                                                                                                               |
|-------------------------------------|---------------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�XP Tablet PC Edition \[desktop apps only\]<br/>                                                 |
| Minimum supported server<br/> | None supported<br/>                                                                                     |
| Header<br/>                   | <dl> <dt>IACom.h (also requires IACom\_i.c)</dt> </dl> |
| DLL<br/>                      | <dl> <dt>IACom.dll</dt> </dl>                          |



## See also

<dl> <dt>

[**InkAnalysisRecognizers**](iinkanalysisrecognizers.md)
</dt> <dt>

[Ink Analysis Reference](ink-analysis-reference.md)
</dt> </dl>

�

�



