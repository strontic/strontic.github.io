---
title: winrshost.exe | Host Process for WinRM's Remote Shell plugin
excerpt: What is winrshost.exe?
---

# winrshost.exe 

* File Path: `C:\Windows\system32\winrshost.exe`
* Description: Host Process for WinRM's Remote Shell plugin

## Hashes

Type | Hash
-- | --
MD5 | `BF647BDF510B2504A3503E075A0E5ECF`
SHA1 | `FC80CB4CE262D2FB249ABD4C6D53B8BF6E335194`
SHA256 | `401441DB1DBE8189EB5CF230714D8271F10F1023E893901C6DB95E6325B46884`
SHA384 | `786020887707D8FF972151B17A6477C2CC30562E3CB8C00AC20DC5B6F8100F40455613369A722BDBA7ADE7A1C169C151`
SHA512 | `7A3992FBD2C889EFE34875157BF302F2CAF90F9EFD37CC18DE22B1DAFE79B7B5EAC6BEDDC21105647BE62C2D8441596EE3C311DB7ED0E6852C2D027C8CF1983E`
SSDEEP | `384:bSI3EN4QWUXQ5RUaoerG0e3ZVSGhEngiWvwGkpIVCmv+7c3AECAWUwv5W00a8/gP:7LZ2a0bXhEngDoGkp6Cmm7c3N8x8/If`
IMP | `94B88BB1A488481A09FB94AE3B531ED2`
PESHA1 | `665DF2BCD2EFB8562DD92D0900952CA102370C95`
PE256 | `5AAC2D34F7FCC86FCA8863996C4ED4204648763721D6080BD5529721D6C59A76`

## Runtime Data

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\user32.dll.mui | File
(RW-)   C:\Users\user | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\RPC Control\DSEC12C8 | Section
\Sessions\2\Windows\Theme2131664586 | Section
\Windows\Theme966197582 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\clbcatq.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\CRYPTSP.dll |
C:\Windows\system32\dwmapi.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\MSASN1.dll |
C:\Windows\System32\MSCTF.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\user32.dll |
C:\Windows\system32\uxtheme.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\system32\winrshost.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: winrshost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/63
* VirusTotal Link: https://www.virustotal.com/gui/file/401441db1dbe8189eb5cf230714d8271f10f1023e893901c6db95e6325b46884/detection/


## Possible Misuse

*The following table contains possible examples of `winrshost.exe` being misused. While `winrshost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\winrshost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


