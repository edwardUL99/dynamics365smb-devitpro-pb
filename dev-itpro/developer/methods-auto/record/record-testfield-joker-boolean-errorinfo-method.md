---
title: "Record.TestField(Any, Boolean, ErrorInfo) Method"
description: "Tests whether the contents of a field match a given value."
ms.author: solsen
ms.date: 05/14/2024
ms.topic: reference
author: SusanneWindfeldPedersen
ms.reviewer: solsen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# Record.TestField(Any, Boolean, ErrorInfo) Method
> **Version**: _Available or changed with runtime version 8.1._

Tests whether the contents of a field match a given value.


## Syntax
```AL
 Record.TestField(Field: Any, Value: Boolean, ErrorInfo: ErrorInfo)
```
## Parameters
*Record*  
&emsp;Type: [Record](record-data-type.md)  
An instance of the [Record](record-data-type.md) data type.  

*Field*  
&emsp;Type: [Any](../any/any-data-type.md)  
The field that you want to test.  

*Value*  
&emsp;Type: [Boolean](../boolean/boolean-data-type.md)  
The value that you want to compare to Field. The data type of this parameter must match the data type of Field. If you include this optional parameter and the contents of Field do not match, then an error message is displayed. If you omit this parameter and the contents of Field is zero or blank (empty string), then an error message is displayed.  

*ErrorInfo*  
&emsp;Type: [ErrorInfo](../errorinfo/errorinfo-data-type.md)  
Additional information to include in the error if the test fails.  



[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## See Also
[Record Data Type](record-data-type.md)
[Get Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)  