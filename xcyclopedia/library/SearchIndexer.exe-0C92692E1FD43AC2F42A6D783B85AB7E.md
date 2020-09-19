---
title: SearchIndexer.exe | Microsoft Windows Search Indexer
---

# SearchIndexer.exe 

* File Path: `C:\Windows\system32\SearchIndexer.exe`
* Description: Microsoft Windows Search Indexer

## Hashes

Type | Hash
-- | --
MD5 | `0C92692E1FD43AC2F42A6D783B85AB7E`
SHA1 | `FB856ABB3611537F2519AA37DB7BB0117A3AC375`
SHA256 | `6177CDD79D82143DE463486D22DE69416DB3DA99A91C0B65E8708A295BAEF2EA`
SHA384 | `17693032BFF1BC7D6920E1867B08F31B7537C11F42FCC1E641F18F2B729C8BD30C7FB7E89A1EE661F983C205BBE0A9D1`
SHA512 | `9ED16FD87E51086FE74099306407D13C108AF611CED8ED3F489A5FB34085880BBCA99403228401E26727A2A9F82819FE9A40F1F5B3DB479F3208989E9C2E524B`
SSDEEP | `24576:APjxG1T2jt3pbhvNpFZLZIeYPC1Cy1bthyD:APDZbPpzLKCcy1bthE`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\SearchIndexer.exe |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SearchIndexer.exe.mui
* Product Name: Windows Search
* Company Name: Microsoft Corporation
* File Version: 7.0.19041.1 (WinBuild.160101.0800)
* Product Version: 7.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\searchindexer.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


