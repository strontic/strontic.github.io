---
title: SearchIndexer.exe | Microsoft Windows Search Indexer
excerpt: What is SearchIndexer.exe?
---

# SearchIndexer.exe 

* File Path: `C:\Windows\system32\SearchIndexer.exe`
* Description: Microsoft Windows Search Indexer

## Hashes

Type | Hash
-- | --
MD5 | `8E4177C1E7E7571CDD9E2BC1495A7C01`
SHA1 | `58CFA0FB57EFD966309B5290BFE158990C76A2BD`
SHA256 | `55B4B3510BCFAF831389B14A27F67417E1C4AB8D4C33C7C62BC7C4927A2C02BB`
SHA384 | `E82229D5942B43F1DEEA8B9B85E1E60C4518A132BC4DCDB8EB39FF987BCEC3CE0C36AB09AF0F6B27D9ACDABF7F7D185B`
SHA512 | `0E5713B5F151F7DF1FFCC265FE43C3E511A206D5C0D6513EBAC8A128DC1B84EA28E58BB0808CC2D49E83226FD99A450709C5ED95BFC332D5CFE4887C4673EBD8`
SSDEEP | `24576:jWhBZcG/nA/V+0NRE+gXisnc46z/Houh5eQ:KhBgw0NRAX9c46z/HouhMQ`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\cryptdll.dll |
C:\Windows\system32\ESENT.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MSSRCH.DLL |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\SearchIndexer.exe |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\system32\TQUERY.DLL |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\windows.storage.dll |


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
* File Version: 7.0.17763.1 (WinBuild.160101.0800)
* Product Version: 7.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


