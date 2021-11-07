---
title: stordiag.exe |  
excerpt: What is stordiag.exe?
---

# stordiag.exe 

* File Path: `C:\Windows\SysWOW64\stordiag.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `1F08AA1B4FB6EF5EFC219CC25A27C2E7`
SHA1 | `C049D4B5AAC6C736ADEFB1FC243E7F9538D923A0`
SHA256 | `D706DC037C51B48E412E6CA00129FC34F06830C27260A5D84F7D30D61237E980`
SHA384 | `EEC1A09610AAF32BB8E2A5EA47294B9AD14F1723B912D125DED85FD4F5E65D9CA5814A185DD1CC4DCB891A849230494A`
SHA512 | `47514CFDC13281FFE3FFBF3C53EC55BC53F3DACD96DEC6AFA58AC8B064FC2D144BBE4B744161E172A102FAD2C44CDB3B58962C0DAF7CF6F1A417F1B28660D05F`
SSDEEP | `1536:LSXiToaguRN2LT0SA6Tny2esoOCrcLbJWE4KWh+fbyJ:OXBagGA0SAGy8/bJWE4t2byJ`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `EF32A573149F3BFF31FA622A8D1771C250B4CA3F`
PE256 | `EFB192C80026823F3FE2A59C2BD9E3319CF03F68034FAEAC10816E6473940A6C`

## Runtime Data

### Usage (stdout):
```cmhg

Collects storage and filesystem diagnostic logs and outputs them to a folder.

StorDiag [-collectEtw] [-out <PATH>]
-collectEtw           Collect a 30-second long ETW trace if run from an elevated session
-collectPerf          Collect disk performance counters
-checkFSConsistency   Checks for the consistency of the NTFS file system
-diagnostic           outputs a storage diagnostic report
-bootdiag             output boot sectors of the disk
-driverdiag           output avaliable storport and storahci logs
-out <PATH>           Specify the output path. If not specified, logs are saved to %TEMP%\StorDiag



```

### Child Processes:
conhost.exe systeminfo.exe

### Open Handles:

Path | Type
-- | --
(R--)   C:\Users\user\AppData\Local\Temp\2\StorDiag\PSLogs.txt | File
(RW-)   C:\Users\user | File
\...\Cor_SxSPublic_IPCBlock | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\Cor_Private_IPCBlock_v4_2300 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\assembly\NativeImages_v4.0.30319_64\mscorlib\5543cca0df435801e2303ff46a482ed5\mscorlib.ni.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Management\35d31e1630335aeb7e7cb2ed836e7230\System.Management.ni.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\System\6885802f40fd803e49150d8a2b43a09b\System.ni.dll |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\clr.dll |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\clrjit.dll |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscoreei.dll |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\SYSTEM32\CRYPTBASE.dll |
C:\Windows\System32\CRYPTSP.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\MSVCR120_CLR0400.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\rsaenh.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\SYSTEM32\VERSION.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\SysWOW64\stordiag.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: stordiag.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1
* Product Version: 10.0.17763.1
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/d706dc037c51b48e412e6ca00129fc34f06830c27260a5d84f7d30d61237e980/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\stordiag.exe](stordiag.exe-EA1A603CE352708C94C964508034E010.md) | 90

## Possible Misuse

*The following table contains possible examples of `stordiag.exe` being misused. While `stordiag.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_stordiag_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_stordiag_execution.yml) | `title: Execution via stordiag.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_stordiag_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_stordiag_execution.yml) | `description: Detects the use of stordiag.exe to execute schtasks.exe systeminfo.exe and fltmc.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_stordiag_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_stordiag_execution.yml) | `- https://strontic.github.io/xcyclopedia/library/stordiag.exe-1F08FC87C373673944F6A7E8B18CD845.html`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_stordiag_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_stordiag_execution.yml) | `ParentImage\|endswith: '\stordiag.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_stordiag_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_stordiag_execution.yml) | `ParentImage\|startswith: # as first is "Copy c:\windows\system32\stordiag.exe to a folder"`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_stordiag_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_stordiag_execution.yml) | `- Legitimate usage of stordiag.exe.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Stordiag.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Stordiag.yml) | `Name: Stordiag.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Stordiag.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Stordiag.yml) | `- Command: stordiag.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Stordiag.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Stordiag.yml) | `Description: Once executed, Stordiag.exe will execute schtasks.exe systeminfo.exe and fltmc.exe - if stordiag.exe is copied to a folder and an arbitrary executable is renamed to one of these names, stordiag.exe will execute it.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Stordiag.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Stordiag.yml) | `- Path: c:\windows\system32\stordiag.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Stordiag.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Stordiag.yml) | `- Path: c:\windows\syswow64\stordiag.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


