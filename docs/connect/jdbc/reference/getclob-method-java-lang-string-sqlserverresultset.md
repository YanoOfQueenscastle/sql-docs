---
title: "getClob Method (java.lang.String) (SQLServerResultSet)"
description: "getClob Method (java.lang.String) (SQLServerResultSet)"
author: David-Engel
ms.author: davidengel
ms.date: "01/19/2017"
ms.service: sql
ms.subservice: connectivity
ms.topic: reference
apilocation: "sqljdbc.jar"
apiname: "SQLServerResultSet.getClob (java.lang.String)"
apitype: "Assembly"
---
# getClob Method (java.lang.String) (SQLServerResultSet)
[!INCLUDE[Driver_JDBC_Download](../../../includes/driver_jdbc_download.md)]

  Retrieves the value of the designated column name in the current row of this [SQLServerResultSet](../../../connect/jdbc/reference/sqlserverresultset-class.md) object as a Clob object in the Java programming language.  
  
## Syntax  
  
```  
  
public java.sql.Clob getClob(java.lang.String colName)  
```  
  
#### Parameters  
 *colName*  
  
 A **String** that contains the column name.  
  
## Return Value  
 A Clob object.  
  
## Exceptions  
 [SQLServerException](../../../connect/jdbc/reference/sqlserverexception-class.md)  
  
## Remarks  
 This getClob method is specified by the getClob method in the java.sql.ResultSet interface.  
  
## See Also  
 [getClob Method &#40;SQLServerResultSet&#41;](../../../connect/jdbc/reference/getclob-method-sqlserverresultset.md)   
 [SQLServerResultSet Members](../../../connect/jdbc/reference/sqlserverresultset-members.md)   
 [SQLServerResultSet Class](../../../connect/jdbc/reference/sqlserverresultset-class.md)  
  
  
