---
title: sihost.exe | Shell Infrastructure Host
excerpt: What is sihost.exe?
---

# sihost.exe 

* File Path: `C:\Windows\system32\sihost.exe`
* Description: Shell Infrastructure Host

## Hashes

Type | Hash
-- | --
MD5 | `F6A576DCC3EA8F62B8818434B163D25B`
SHA1 | `A72247134CA39DA0B1F706F6B339DC912C0EE0D3`
SHA256 | `FDF2362A69C542996A8AC84B938DE62CA97AC209762171D2F8B6B543D3A966D0`
SHA384 | `0E53778852D51252DD3E83D2641C6C5C0358FEDA818487FB159F04E0937796EE6225B5BE80DC0DDCD70EDAF1B2F01792`
SHA512 | `92159635D475DC21BE9C543142C79370F3A80F9C1D8ECCBCF6D959517165FF40FE0DB59215C105406D0E0F7F8B060B3B0A67C4E3260DAAA2E0B34C13F38415E0`
SSDEEP | `3072:HoGHHEEU+WYAKG+DizpogS+qWe9AN5rytOU/:HoekV+PA/PpVSGb5rytOU`
IMP | `D79FA753A3003DE97EDFC038DF32C136`
PESHA1 | `114DFFE1E84E1B996F246FD3F1FB17F40985E6CF`
PE256 | `F9CCDD6AD8FE167C0810354427225C90239F985B6692F11CCE05747E8ED9590F`

## Runtime Data

### Child Processes:
explorer.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\RPC Control\DSEC3F8 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\clbcatq.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\CoreMessaging.dll |
C:\Windows\system32\desktopshellext.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SYSTEM32\ntmarta.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\system32\sihost.exe |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\SYSTEM32\WINSTA.dll |
C:\Windows\SYSTEM32\wtsapi32.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sihost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1075 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1075
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/fdf2362a69c542996a8ac84b938de62ca97ac209762171d2f8b6b543d3a966d0/detection/


## Possible Misuse

*The following table contains possible examples of `sihost.exe` being misused. While `sihost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\sihost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\sihost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


