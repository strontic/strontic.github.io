---
title: OneDriveStandaloneUpdater.exe | Standalone Updater
excerpt: What is OneDriveStandaloneUpdater.exe?
---

# OneDriveStandaloneUpdater.exe 

* File Path: `C:\Users\user\AppData\Local\Microsoft\OneDrive\OneDriveStandaloneUpdater.exe`
* Description: Standalone Updater

## Hashes

Type | Hash
-- | --
MD5 | `3E9BBDB6B4BDFF8AB365688EE5538F65`
SHA1 | `154291B75A918F8443A43E5A81C5A8BFEEA903FA`
SHA256 | `B3E79D55CEFB172BB10A42A0965422A1AA3EDA052E414D0561E2A0361F0DEE3B`
SHA384 | `990C7A0EC4A9728ABE6239766741ED4C26CCAE5A45C684020C5FC2396C9225FA3FF4465FFE28FAED80F901C3338FBAB0`
SHA512 | `4C9BAEF913E9A010949A9D812890F4A3A21FAE30EC5041F580F83530922A9574E12D20EFCB1D10353050B64DB28A9890C572CA856A6C8E0C6065B3065FE23620`
SSDEEP | `49152:9uDkBnfDiZknewBWeCijjNloN1lNlcBjbXLgXfoTqjJU:x9sjI3XLgJU`
IMP | `6FEB6DF89E46CB6B8E32DD08909821C9`
PESHA1 | `A6E1ACC6423427D686CE5F5754458CA0B30EA664`
PE256 | `35EC84CBDD6AB57097121072D343629906B3082CC25FA9A0E352741576472207`

## Runtime Data

### Child Processes:
Microsoft.SharePoint.exe

### Open Handles:

Path | Type
-- | --
(---)   \FileSystem\Filters\FltMgrMsg | File
(R--)   C:\Users\user\AppData\Local\Microsoft\OneDrive\logs\Common\StandaloneUpdater-2021-11-07.2317.4628.1.aodl | File
(R--)   C:\Users\user\AppData\Local\Microsoft\OneDrive\setup\logs\StandaloneUpdate_2021-11-07_231737_4628-6316.log | File
(R-D)   C:\Users\user\AppData\Local\Temp\wctBF58.tmp | File
(R-D)   C:\Users\user\AppData\Local\Temp\wctC034.tmp | File
(R-D)   C:\Windows\System32\en-US\crypt32.dll.mui | File
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(R-D)   C:\Windows\System32\en-US\mswsock.dll.mui | File
(R-D)   C:\Windows\System32\en-US\propsys.dll.mui | File
(RW-)   C:\Users\user\AppData\Local\Microsoft\OneDrive\logs\Common\standaloneUpdaterTelemetryCache.otc | File
(RW-)   C:\Users\user\AppData\Local\Microsoft\OneDrive\logs\Common\standaloneUpdaterTelemetryCache.otc-shm | File
(RW-)   C:\Users\user\AppData\Local\Microsoft\OneDrive\logs\Common\standaloneUpdaterTelemetryCache.otc-wal | File
(RW-)   C:\Windows\System32 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\F932B6C7-3A20-46A0-B8A0-8894AA421973 | Section
\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\UrlZonesSM_TI-ADMIN | Section
\Sessions\2\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\2\BaseNamedObjects\windows_webcache_counters_{9B6AB5B3-91BC-4097-835C-EA2DEC95E9CC}_S-1-5-21-1128764013-3361508229-3049782613-1001 | Section


### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\Microsoft\OneDrive\OneDriveStandaloneUpdater.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\USER32.dll |
C:\WINDOWS\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000003F16206E3E7EFDA8ABE0000000003F1`
* Thumbprint: `5362FAEB842C236D05A729B7FAC85BAA1B68BDCA`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: OneDriveStandaloneUpdater.exe
* Product Name: Microsoft OneDrive
* Company Name: Microsoft Corporation
* File Version: 21.220.1024.0001
* Product Version: 21.220.1024.0001
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/b3e79d55cefb172bb10a42a0965422a1aa3eda052e414d0561e2a0361f0dee3b/detection


## Possible Misuse

*The following table contains possible examples of `OneDriveStandaloneUpdater.exe` being misused. While `OneDriveStandaloneUpdater.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [OneDriveStandaloneUpdater.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/OneDriveStandaloneUpdater.yml) | `Name: OneDriveStandaloneUpdater.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [OneDriveStandaloneUpdater.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/OneDriveStandaloneUpdater.yml) | `- Command: OneDriveStandaloneUpdater`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [OneDriveStandaloneUpdater.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/OneDriveStandaloneUpdater.yml) | `- Path: '%localappdata%\Microsoft\OneDrive\OneDriveStandaloneUpdater.exe'`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


