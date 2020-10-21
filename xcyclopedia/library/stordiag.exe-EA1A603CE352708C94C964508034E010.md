---
title: stordiag.exe |  
excerpt: What is stordiag.exe?
---

# stordiag.exe 

* File Path: `C:\Windows\system32\stordiag.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `EA1A603CE352708C94C964508034E010`
SHA1 | `2E8AA7B1EBDFDD6DDB487D69B8C0B46699F7C9B2`
SHA256 | `DDC1C81667A942F91F25E18EAF3AFC453F7FE3A4CC4140CBA82FB49732011536`
SHA384 | `310263FC7606CF4954127D403EAD35A0995A3E2E9C10FB2E09E84B4A85EE4592285631E509E958111A5AC06988F362CF`
SHA512 | `A573335D8AE94B842E45E0913A81806B658E78D57E426D428A97A6918FEB7CEE4F2D2BF1EA3F5829464F3425524B036A69A548ED0BEACA92836FBB01A567DC87`
SSDEEP | `1536:dSXiToaguRN2LT0SA6Tny2esoOCd+LbJWE4KWh+fbN0:QXBagGA0SAGy8jbJWE4t2bN0`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `5FAE9F9EEFAA1FE1963A2A84CC7E231592508108`
PE256 | `85FED5D0C95C7A5823CC1610DCEEC0D9D9411CCFA15B69E90B921C45DFF883C1`

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
\BaseNamedObjects\Cor_Private_IPCBlock_v4_2904 | Section
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
C:\Windows\system32\CRYPTBASE.dll |
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
C:\Windows\system32\stordiag.exe |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\VERSION.dll |
C:\Windows\System32\win32u.dll |


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

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/ddc1c81667a942f91f25e18eaf3afc453f7fe3a4cc4140cba82fb49732011536/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\stordiag.exe](stordiag.exe-1F08AA1B4FB6EF5EFC219CC25A27C2E7.md) | 90




MIT License. Copyright (c) 2020 Strontic.


