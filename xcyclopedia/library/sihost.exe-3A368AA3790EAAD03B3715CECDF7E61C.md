---
title: sihost.exe | Shell Infrastructure Host
excerpt: What is sihost.exe?
---

# sihost.exe 

* File Path: `C:\WINDOWS\system32\sihost.exe`
* Description: Shell Infrastructure Host

## Hashes

Type | Hash
-- | --
MD5 | `3A368AA3790EAAD03B3715CECDF7E61C`
SHA1 | `C9E01523C3F22493D54A711E602DC002E1D91B3E`
SHA256 | `6B7ED70E0728D01C277ED90A1B4F538E17B009054B435792DC589022838E72F9`
SHA384 | `0D4580E70AF38ECEB57B176DA9DDBEAEB8166185AC5A3E39607AA6F75C17DF0D605D7E07CD9D0C96B3F6A873DE8926A9`
SHA512 | `D6680AE76D9963423F9EC2A4AF7A64DF4FF31DBB4E6BB682CCD57904D4CC34EEA761572C62E6768010BA6B098D6326B681747BA83A11BA272F8934698955443D`
SSDEEP | `3072:iDJsNbbiWxQwp9GSSdKY8V3lNtqQ1PXTlbZd+Ai:EJWfiWxQw/vpY8V3lNtnJbZd9`
IMP | `416EE26CB8C768F6662AC36C7D016457`
PESHA1 | `9DCE0A5AE6EA0474A21CCB3346E017E109D4E642`
PE256 | `CD5B9DB4D8D301AC387D5EEA8060AF8DED361DD0681C9459DF1A61A223FA6AC5`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(RW-)   C:\Windows\System32 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\advapi32.dll |
C:\WINDOWS\System32\bcryptPrimitives.dll |
C:\WINDOWS\System32\clbcatq.dll |
C:\WINDOWS\System32\combase.dll |
C:\WINDOWS\system32\CoreMessaging.dll |
C:\WINDOWS\system32\desktopshellext.dll |
C:\WINDOWS\System32\GDI32.dll |
C:\WINDOWS\System32\gdi32full.dll |
C:\WINDOWS\System32\IMM32.DLL |
C:\WINDOWS\SYSTEM32\kernel.appcore.dll |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcp_win.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\SYSTEM32\ntmarta.dll |
C:\WINDOWS\System32\RPCRT4.dll |
C:\WINDOWS\System32\sechost.dll |
C:\WINDOWS\System32\shcore.dll |
C:\WINDOWS\System32\shlwapi.dll |
C:\WINDOWS\system32\sihost.exe |
C:\WINDOWS\System32\ucrtbase.dll |
C:\WINDOWS\System32\user32.dll |
C:\WINDOWS\System32\win32u.dll |
C:\WINDOWS\SYSTEM32\WINSTA.dll |
C:\WINDOWS\SYSTEM32\wtsapi32.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sihost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/6b7ed70e0728d01c277ed90a1b4f538e17b009054b435792dc589022838e72f9/detection


## Possible Misuse

*The following table contains possible examples of `sihost.exe` being misused. While `sihost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\sihost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\sihost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


