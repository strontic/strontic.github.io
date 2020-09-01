---
title: regedt32.exe | Registry Editor Utility
---

# regedt32.exe 

* File Path: `C:\Windows\SysWOW64\regedt32.exe`
* Description: Registry Editor Utility

## Hashes

Type | Hash
-- | --
MD5 | `49E9EA6F79338B350A8B23CEA47D1A86`
SHA1 | `B51311EEE2A58FDF80CD55616B5A15291A5EE951`
SHA256 | `B9A0659A5F8173629C2CC702F9D786F699BE2C1C1BD10EE354494DF75C618954`
SHA384 | `0B7D872C1AE2C053CECCB83BEA2A393105F573E60C5FD8BF6397627A2511151A91A474B7BE855FB09D66B6DA0244002B`
SHA512 | `A6F473794315E9A38C3D08F1777BA14D0DE3F98F560E8DB120F96ED6FB6EF2A14568F444783AE2520F958E872223A8D4CFAEB98718089E3BC5A3DA35539C85E0`
SSDEEP | `96:cT/8zwOtfZOWkcTLEp2TyIRoJIP3DGjsl3tTZFovnzeDJFMVWVEWlZhHWwB:cT8zwqrTaGRoTeTZFovnz0MWbxWG`

## Runtime Data

### Child Processes:
regedit.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\propsys.dll.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{F79646A6-8BE5-443B-A98F-AD03D667F646}.2.ver0x0000000000000001.db | Section
\Sessions\1\BaseNamedObjects\SessionImmersiveColorPreference | Section
\Sessions\1\BaseNamedObjects\UrlZonesSM_user | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\regedt32.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: regedt32.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\regedt32.exe](regedt32.exe-6E243D43D411D8C7384883376A1F54E3.md) | 66

## Possible Misuse

*The following table contains possible examples of `regedt32.exe` being misused. While `regedt32.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) |       $a3 = "regedt32.exe" wide nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


