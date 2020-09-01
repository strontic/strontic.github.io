---
title: bootmgr.exe | Boot Manager
---

# bootmgr.exe 

* File Path: `C:\Windows\system32\RemInst\boot\x64\bootmgr.exe`
* Description: Boot Manager

## Hashes

Type | Hash
-- | --
MD5 | `E0E5DD54D1BA219D2A80DDC6E680C0D6`
SHA1 | `B4BB09293B9857822B2189729B15FA45183DE408`
SHA256 | `FE3FD097421ABD49C41E92880EE3628EC2C0300A70D20FB2F570F85A3F14CD00`
SHA384 | `84712DB78DEF1F23C0681420EDE31E43137C4E478B3F2076977E0B22429F49D050F80ACAA25A5BF718B9174BC8BF6ACB`
SHA512 | `E49FEAFF24DB0395FA044DAE645C4A376B03513D575F1A2D371335375D7C60A88C0859B1B06C757DA5C1472113DBE81DB3B920B917343F4904B3CE6F5F94911C`
SSDEEP | `12288:Q6JqcsiNFsRW0fTapDrbCxymAI7X9rjs9welQPUpVGMplIm9dmj1WwK9W9Qvw6Jo:Q6JgiNeR7TaExymAI7X9rQwGpAtWQmK`

### Loaded Modules:

Path |
-- |
C:\Windows\system32\bootim.exe |
C:\Windows\system32\BOOTUX.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\DUI70.dll |
C:\Windows\system32\DUser.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\PROPSYS.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\UIAutomationCore.DLL |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\UxTheme.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bootmgr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\RemInst\boot\x86\bootmgr.exe](bootmgr.exe-E0E5DD54D1BA219D2A80DDC6E680C0D6.md) | 100

## Possible Misuse

*The following table contains possible examples of `bootmgr.exe` being misused. While `bootmgr.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `bootmgr` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_ransom_ragna_locker.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_ransom_ragna_locker.yar) |       $f2 = "bootmgr.efi" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


