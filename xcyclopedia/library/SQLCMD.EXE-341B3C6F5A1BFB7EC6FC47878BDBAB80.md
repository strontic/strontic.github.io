---
title: SQLCMD.EXE | T-SQL execution command line utility
excerpt: What is SQLCMD.EXE?
---

# SQLCMD.EXE 

* File Path: `C:\Program Files\Microsoft SQL Server\Client SDK\ODBC\170\Tools\Binn\SQLCMD.EXE`
* Description: T-SQL execution command line utility
* Comments: SQL


## Hashes

Type | Hash
-- | --
MD5 | `341B3C6F5A1BFB7EC6FC47878BDBAB80`
SHA1 | `8423D5A8E47430A29D0E91A066E3B429CE7BE9A0`
SHA256 | `5803521CD1A53B4DE33E7BB782651548C22D1D81C0C1C6B26B1EB9CF773BB724`
SHA384 | `BFE021A7592499D905D70E2D456CF78BB73D232B9DF2D6AAF37E837BD00A11C61163653C88EABDBB6CAC44BEA3293F51`
SHA512 | `31AC3DAFFCD052E027D7FE2A320720E9482D05FCB90B2690F2BDD8A29893500FD5C1FF9353DE44C802C0EF099CC15E991895260A26897DA8615DFB01466F3010`
SSDEEP | `3072:QPkOTjjmDpuQtR8NMtmjcrM4NCjKtirp5DqNUseGvMNTcyqnqFmCQiEd:4/edtvBoxjUir7DqNU7GkNTMqFcd`
IMP | `3D3B6D9E8906FC45B35D79B6B2BFDC28`
PESHA1 | `84EB0C9C0EE1F3D5DEA419522D26FA23310DAFE1`
PE256 | `9FDE8E7801064FBA173C73992EE617FF02C6A59979AC2D947DBB42A2AD897ACA`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) SQL Server Command Line Tool
Version 15.0.2000.5 NT
Copyright (C) 2019 Microsoft Corporation. All rights reserved.

usage: Sqlcmd            [-U login id]          [-P password]
  [-S server]            [-H hostname]          [-E trusted connection]
  [-N Encrypt Connection][-C Trust Server Certificate]
  [-d use database name] [-l login timeout]     [-t query timeout]
  [-h headers]           [-s colseparator]      [-w screen width]
  [-a packetsize]        [-e echo input]        [-I Enable Quoted Identifiers]
  [-c cmdend]            [-L[c] list servers[clean output]]
  [-q "cmdline query"]   [-Q "cmdline query" and exit]
  [-m errorlevel]        [-V severitylevel]     [-W remove trailing spaces]
  [-u unicode output]    [-r[0|1] msgs to stderr]
  [-i inputfile]         [-o outputfile]        [-z new password]
  [-f <codepage> | i:<codepage>[,o:<codepage>]] [-Z new password and exit]
  [-k[1|2] remove[replace] control characters]
  [-y variable length type display width]
  [-Y fixed length type display width]
  [-p[1] print statistics[colon format]]
  [-R use client regional setting]
  [-K application intent]
  [-M multisubnet failover]
  [-b On error batch abort]
  [-v var = "value"...]  [-A dedicated admin connection]
  [-X[1] disable commands, startup script, environment variables [and exit]]
  [-x disable variable substitution]
  [-j Print raw error messages]
  [-g enable column encryption]
  [-G use Azure Active Directory for authentication]
  [-? show syntax summary]

```

### Usage (stderr):
```cmhg
Sqlcmd: '-h elp': header value must be either -1 or a value between -1 and 2147483647

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Microsoft SQL Server\Client SDK\ODBC\170\Tools\Binn\SQLCMD.EXE |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001E47CFC029560FF84FB0002000001E4`
* Thumbprint: `E942D27A35DCBBE072872AD9E9E0AC4C948A7864`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SQLCMD.exe
* Product Name: Microsoft SQL Server
* Company Name: Microsoft Corporation
* File Version: 2019.0150.2000.05 ((SQLServer).190924-2033)
* Product Version: 15.0.2000.5
* Language: English (United States)
* Legal Copyright: Microsoft. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/5803521cd1a53b4de33e7bb782651548c22d1d81c0c1c6b26b1eb9cf773bb724/detection


## Possible Misuse

*The following table contains possible examples of `SQLCMD.EXE` being misused. While `SQLCMD.EXE` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_webshells.yar) | $s2 = "String sql = request.getParameter(\"sqlcmd\");" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | description = "Chinese Hacktool Set - file Sqlcmd.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s6 = "=======================Sqlcmd v0.21 For HScan v1.20=======================" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s11 = "Sqlcmd>" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | description = "Chinese Hacktool Set - file sqlcmd.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Disclosed hacktool set (old stuff) - file sqlcmd.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


