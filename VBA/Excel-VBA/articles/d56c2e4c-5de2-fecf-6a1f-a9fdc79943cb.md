
# Workbook.DeleteNumberFormat Method (Excel)

Deletes a custom number format from the workbook.


## Syntax

 _expression_ . **DeleteNumberFormat**( **_NumberFormat_** )

 _expression_ A variable that represents a **Workbook** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _NumberFormat_|Required| **String**|Names the number format to be deleted.|

## Example

This example deletes the number format "000-00-0000" from the active workbook.


```vb
ActiveWorkbook.DeleteNumberFormat("000-00-0000")
```


## See also


#### Concepts


[Workbook Object](8c00aa60-c974-eed3-0812-3c9625eb0d4c.md)
