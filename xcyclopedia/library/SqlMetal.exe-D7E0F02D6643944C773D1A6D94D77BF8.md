---
title: SqlMetal.exe | SqlMetal.exe
excerpt: What is SqlMetal.exe?
---

# SqlMetal.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\SqlMetal.exe`
* Description: SqlMetal.exe
* Comments: SqlMetal.exe


## Hashes

Type | Hash
-- | --
MD5 | `D7E0F02D6643944C773D1A6D94D77BF8`
SHA1 | `136B3C28372B312BEF2072AD2C6E4F4BF5E66668`
SHA256 | `B0974E15DED88CA5A0342CC1E2E3D97FCCC596B75A39C6D31F8D9BFAAD10F8B5`
SHA384 | `FEB70C75E82A12D3A1107F9E6D96C2B7986F85CA687F8E80E6C323A269DA6C4B88FAE33A048012581B3989B8765DA19E`
SHA512 | `354708C6FE28BD516F85CAC4175A17874C7C8241C6526743875201B17ABC41AE38FF647F3DE6BA4E50F497E0EA657E2003B75555AA5CF0B004C1F4F22E06D420`
SSDEEP | `6144:ByuefGT5rk1z/Q0BQMUQY28b30A7ur0WpG:OfG9rECZQY70AGY`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `2F236548A13548A7E7963B3EECF7C187347B930B`
PE256 | `2383839B3C5DC94E2EF482F25EDE2405613E26E0A1A139BEE92539F76E843578`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Database Mapping Generator version 4.8.4084.0
for Microsoft (R) .NET Framework version 4.8
Copyright (C) Microsoft Corporation. All rights reserved.

SqlMetal [options] [<input file>]

  Generates code and mapping for the LINQ to SQL component of the .NET framework. SqlMetal can:
  - Generate source code and mapping attributes or a mapping file from a database.
  - Generate an intermediate dbml file for customization from the database.
  - Generate code and mapping attributes or mapping file from a dbml file.

Options:
  /server:<name>             Database server name.
  /database:<name>           Database catalog on server.
  /user:<name>               Login user ID (default: use Windows Authentication).
  /password:<password>       Login password (default: use Windows Authentication).
  /conn:<connection string>  Database connection string. Cannot be used with /server, /database, /user or /password options.
  /timeout:<seconds>         Timeout value to use when SqlMetal accesses the database (default: 0 which means infinite).

  /views                     Extract database views.
  /functions                 Extract database functions.
  /sprocs                    Extract stored procedures.

  /dbml[:file]               Output as dbml. Cannot be used with /map option.
  /code[:file]               Output as source code. Cannot be used with /dbml option.
  /map[:file]                Generate mapping file, not attributes. Cannot be used with /dbml option.

  /language:<language>       Language for source code: VB or C# (default: derived from extension on code file name).
  /namespace:<name>          Namespace of generated code (default: no namespace).
  /context:<type>            Name of data context class (default: derived from database name).
  /entitybase:<type>         Base class of entity classes in the generated code (default: entities have no base class).
  /pluralize                 Automatically pluralize or singularize class and member names using English language rules.
  /serialization:<option>    Generate serializable classes: None or Unidirectional (default: None).
  /provider:<type>           Provider type: SQLCompact, SQL2000, SQL2005, or SQL2008. (default: provider is determined at run time).

  <input file>               May be a SqlExpress mdf file, a SqlCE sdf file, or a dbml intermediate file.

Create code from SqlServer:
  SqlMetal /server:myserver /database:northwind /code:nwind.cs /namespace:nwind 

Generate intermediate dbml file from SqlServer:
  SqlMetal /server:myserver /database:northwind /dbml:northwind.dbml /namespace:nwind

Generate code with external mapping from dbml:
  SqlMetal /code:nwind.cs /map:nwind.map northwind.dbml

Generate dbml from a SqlCE sdf file:
  SqlMetal /dbml:northwind.dbml northwind.sdf

Generate dbml from SqlExpress local server:
  SqlMetal /server:.\sqlexpress /database:northwind /dbml:northwind.dbml

Generate dbml by using a connection string in the command line:
  SqlMetal /conn:"server='myserver'; database='northwind'" /dbml:northwind.dbml


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\SqlMetal.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SqlMetal.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0
* Product Version: 4.8.4084.0
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/b0974e15ded88ca5a0342cc1e2e3d97fccc596b75a39c6d31f8d9bfaad10f8b5/detection





MIT License. Copyright (c) 2020-2021 Strontic.


