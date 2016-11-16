---
title: "Troubleshooting Exceptions: System.Data.Odbc.OdbcException | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-csharp"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "EHOdbc"
dev_langs: 
  - "JScript"
  - "VB"
  - "CSharp"
  - "C++"
helpviewer_keywords: 
  - "exceptions, ODBC"
  - "ODBC, exceptions"
  - "OdbcException class"
ms.assetid: 5f2c2167-cf7b-4634-af86-44dc71eff02d
caps.latest.revision: 17
author: "mikeblome"
ms.author: "mblome"
manager: "douge"
translation.priority.ht: 
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "ru-ru"
  - "zh-cn"
  - "zh-tw"
translation.priority.mt: 
  - "cs-cz"
  - "pl-pl"
  - "pt-br"
  - "tr-tr"
---
# Troubleshooting Exceptions: System.Data.Odbc.OdbcException
An <xref:System.Data.Odbc.OdbcException> exception is generated when a warning or error is returned by an ODBC data source.  
  
## Associated Tips  
 **Verify that you are connecting with valid credentials.**  
 Check your credentials to make sure they are valid.  
  
 **Verify that the server name is correct and that the server is running.**  
 Make sure that you are using the correct server name, and that the server is reachable.  
  
## Remarks  
 This exception is thrown whenever the <xref:System.Data.Odbc.OdbcDataAdapter> encounters an error generated by the server.  
  
 If the severity of the error is too great, the server may close the <xref:System.Data.Odbc.OdbcConnection>. However, the user can reopen the connection and continue.  
  
## See Also  
 <xref:System.Data.Odbc.OdbcException>   
 [Use the Exception Assistant](../Topic/How%20to:%20Use%20the%20Exception%20Assistant.md)