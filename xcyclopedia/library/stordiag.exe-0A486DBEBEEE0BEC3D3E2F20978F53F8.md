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
MD5 | `0A486DBEBEEE0BEC3D3E2F20978F53F8`
SHA1 | `7BBC1977DE11EE9324C5A4C3ACF4724882B38279`
SHA256 | `6A13DAC8BD42767DAD55D4C1ED4640F4E7F01ABB08CA05DDCDC2C348FCD6F8B3`
SHA384 | `FFBD945C22C16E612BE83BA3EDB2ABB74E69491256F8C0F529AC92A5098F0A430E1B5D6E8108BE7240A732CD3C256CFB`
SHA512 | `400ACADC345D946EF481C974856C9E3101B59D47E559790D0B161CDF05BC01E0498A45159392223240BF49EE0EA7D68189BDC24D929E7FC6532F24B496326E5B`
SSDEEP | `1536:hwYYQyn8M801RXnItvNCl/iB8KwZfbOZE4RS8JRFahdqb9BuN:6Y28M8068xfbOZE4I8JRFEYb9BuN`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `9F1243EDB08EC84BC245EF048FFE441CBEBEC1C1`
PE256 | `8D2BF9896D5B7051DB9AB0EA9EC13CA01FBA6700831B651A925785311270F9AB`

## Runtime Data

### Usage (stdout):
```cmhg

Collects storage and filesystem diagnostic logs and outputs them to a folder.

StorDiag [-collectEtw] [-out <PATH>]
-collectEtw                  Collect a 30-second long ETW trace if run from an elevated session
-collectPerf                 Collect disk performance counters
-collectStorageBreakdown     Collect system volume used space breakdown
-checkFSConsistency          Checks for the consistency of the NTFS file system
-diagnostic                  outputs a storage diagnostic report
-bootdiag                    output boot sectors of the disk
-driverdiag                  output avaliable storport and storahci logs
-out <PATH>                  Specify the output path. If not specified, logs are saved to %TEMP%\StorDiag



```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R--)   C:\Users\user\AppData\Local\Temp\StorDiag\PSLogs.txt | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_64\mscorlib\v4.0_4.0.0.0__b77a5c561934e089\mscorlib.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\Microsoft.PowerShell.Commands.Diagnostics\v4.0_3.0.0.0__31bf3856ad364e35\Microsoft.PowerShell.Commands.Diagnostics.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Configuration.Install\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.Configuration.Install.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Core\v4.0_4.0.0.0__b77a5c561934e089\System.Core.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Management.Automation\v4.0_3.0.0.0__31bf3856ad364e35\System.Management.Automation.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Management\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.Management.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Xml\v4.0_4.0.0.0__b77a5c561934e089\System.XML.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System\v4.0_4.0.0.0__b77a5c561934e089\System.dll | File
(R-D)   C:\Windows\System32\en-US\winnlsres.dll.mui | File
(RW-)   C:\Users\user | File
\...\Cor_SxSPublic_IPCBlock | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\Cor_Private_IPCBlock_v4_3352 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\stordiag.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: stordiag.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1
* Product Version: 10.0.19041.1
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/6a13dac8bd42767dad55d4c1ed4640f4e7f01abb08ca05ddcdc2c348fcd6f8b3/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\stordiag.exe](stordiag.exe-1F08FC87C373673944F6A7E8B18CD845.md) | 91




MIT License. Copyright (c) 2020 Strontic.


