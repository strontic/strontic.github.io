---
title: MRT.exe | Microsoft Windows Malicious Software Removal Tool
excerpt: What is MRT.exe?
---

# MRT.exe 

* File Path: `C:\Windows\system32\MRT.exe`
* Description: Microsoft Windows Malicious Software Removal Tool

## Screenshot

![MRT.exe](screenshots/MRT.exe-792A4FC72C80CA97C00196B4D8B27A0E.png)

## Hashes

Type | Hash
-- | --
MD5 | `66CFF638C4886C3ADFD7F4A8C4E5305C`
SHA1 | `7590E18B8BD55B77326797D2DBBF57E992FECEFC`
SHA256 | `A96F8928BEC28857706E01FFFD043DD88D863B23105937F8A83D763025254684`
SHA384 | `A9C46FE6D8A8BBACFDCC0C223CC36A6BEF50DBDCBD2F561164D87A7087F3950C3BDDACE52DAC8F314D8E635D7EF0B549`
SHA512 | `7CD46208E4519EDC30E1411B37AD1ED3008BD8AE9549CEFC09A287BA10A4EFC9F40C27E8735901B791CA91A5E5E8B24EFE06123EF56E145B5AC8E349E2D4151D`
SSDEEP | `3145728:1Su+FSpLoVlpM/6/w/65xV/jE5xf5xd5xX/h5x55xN5xg5xA5x85xK5xA5xkItJg:UFd3iItJPo`
IMP | `B280AA6D77CEF1859E15BCD2A3D67751`
PESHA1 | `1564C2F08C3F7DB0A48BC2B8398D918F83A9CEDC`
PE256 | `0B11FDF901039EB4CAC508CC4DF4CC7E8CE187F78CC925735C0BDE47ECB82A13`

## Runtime Data

### Window Title:
Malicious Software Removal Tool

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\imageres.dll.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.17763.1518_none_de6e2bd0534e2567 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\2\Windows\Theme2131664586 | Section
\Windows\Theme966197582 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\cryptsp.dll |
C:\Windows\system32\dwmapi.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MRT.exe |
C:\Windows\System32\MSASN1.dll |
C:\Windows\System32\MSCTF.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SETUPAPI.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\USERENV.dll |
C:\Windows\system32\uxtheme.dll |
C:\Windows\system32\version.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\windows.storage.dll |
C:\Windows\system32\WindowsCodecs.dll |
C:\Windows\System32\WINTRUST.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.17763.1518_none_de6e2bd0534e2567\COMCTL32.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002689ACC74C3B73DBA47000000000268`
* Thumbprint: `26E1ECEDA18F82CCE5EE18F25C98F1AC9C02DA16`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mrt.exe
* Product Name: Microsoft Windows Malicious Software Removal Tool
* Company Name: Microsoft Corporation
* File Version: 5.83.17439.1
* Product Version: 5.83.17439.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/a96f8928bec28857706e01fffd043dd88d863b23105937f8a83d763025254684/detection/


## Possible Misuse

*The following table contains possible examples of `MRT.exe` being misused. While `MRT.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_svchost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_svchost.yml) | `- '*\Mrt.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_fireball.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_fireball.yar) | $x1 = "SOFTWARE\\Microsoft\\Windows NT\\CurrentVersion\\Image File Execution Options\\MRT.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


