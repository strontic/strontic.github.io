---
title: OneDrive.exe | Microsoft OneDrive
excerpt: What is OneDrive.exe?
---

# OneDrive.exe 

* File Path: `C:\Users\user\AppData\Local\Microsoft\OneDrive\OneDrive.exe`
* Description: Microsoft OneDrive

## Hashes

Type | Hash
-- | --
MD5 | `76C312F2EAC5CA8FED3434C7741187E8`
SHA1 | `80972F1A2C36963F7CB7FD6D49C6801ABD8C595D`
SHA256 | `5CA3A8D19432E882F03216DA60462BA0E7B5B9CC360508C591CCDA96915AC887`
SHA384 | `D708B18E85034597D586EC28E5BC2D3BC045935038D3FD2E392862B62E069C022BA1823B1B2480A1F8DB77D44BDD0D9B`
SHA512 | `542DBD4D9DDAB4FE11D639E4693CCB9BBAD32423E907CD66D4A4C6128AE7A1B8BF9A725C077BD21A09ECD2EA47D0A3F88550B13B6600E859C8AD5F684FDF5B89`
SSDEEP | `49152:sxjDAnzG5TNXyTtsBP/OlsLzFmNfW6FJKxxfZA4Xq:UkzCBXzBP/OlsLzFmNfW6FJKxxfZA4Xq`
IMP | `1C21EE48684E8D17AF2F6DF6DB3842F4`
PESHA1 | `C903A70B045E21F0A785C70C4E42A8E9AD105B97`
PE256 | `77B100B80F20B5A6DE98D09D9FCD4036C20191BCABE25A601B9ED841545A0D79`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\Microsoft\OneDrive\OneDrive.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000003F16206E3E7EFDA8ABE0000000003F1`
* Thumbprint: `5362FAEB842C236D05A729B7FAC85BAA1B68BDCA`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: OneDrive.exe
* Product Name: Microsoft OneDrive
* Company Name: Microsoft Corporation
* File Version: 21.220.1024.0001
* Product Version: 21.220.1024.0001
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/5ca3a8d19432e882f03216da60462ba0e7b5b9cc360508c591ccda96915ac887/detection


## Possible Misuse

*The following table contains possible examples of `OneDrive.exe` being misused. While `OneDrive.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [microsoft365_suspicious_oauth_app_file_download_activities.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/m365/microsoft365_suspicious_oauth_app_file_download_activities.yml) | `description: Detects when a Microsoft Cloud App Security reported when an app downloads multiple files from Microsoft SharePoint or Microsoft OneDrive in a manner that is unusual for the user.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_cobalt_onedrive.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_cobalt_onedrive.yml) | `title: CobaltStrike Malleable OneDrive Browsing Traffic Profile`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_cobalt_onedrive.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_cobalt_onedrive.yml) | `description: Detects Malleable OneDrive Profile`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_cobalt_onedrive.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_cobalt_onedrive.yml) | `cs-host: 'onedrive.live.com'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_cobalt_onedrive.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_cobalt_onedrive.yml) | `c-uri\|contains: '://onedrive.live.com/'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_detection_lsass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/sysmon_mimikatz_detection_lsass.yml) | `- https://onedrive.live.com/view.aspx?resid=D026B4699190F1E6!2843&ithint=file%2cpptx&app=PowerPoint&authkey=!AMvCRTKB_V1J5ow`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cred_dump_lsass_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_cred_dump_lsass_access.yml) | `- https://onedrive.live.com/view.aspx?resid=D026B4699190F1E6!2843&ithint=file%2cpptx&app=PowerPoint&authkey=!AMvCRTKB_V1J5ow`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_local_system_owner_account_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_local_system_owner_account_discovery.yml) | `- ' rmdir '       # don't match on 'dir'   "C:\Windows\System32\cmd.exe" /q /c rmdir /s /q "C:\Users\XX\AppData\Local\Microsoft\OneDrive\19.232.1124.0005"`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_registry_persistence_search_order.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_registry_persistence_search_order.yml) | `Details\|contains: '\AppData\Local\Microsoft\OneDrive\'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_registry_persistence_search_order.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_registry_persistence_search_order.yml) | `- Some installed utilities (i.e. OneDrive) may serve new COM objects at user-level`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [OneDriveStandaloneUpdater.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/OneDriveStandaloneUpdater.yml) | `Description: OneDrive Standalone Updater`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [OneDriveStandaloneUpdater.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/OneDriveStandaloneUpdater.yml) | `Description: Download a file from the web address specified in HKCU\Software\Microsoft\OneDrive\UpdateOfficeConfig\UpdateRingSettingURLFromOC. ODSUUpdateXMLUrlFromOC and UpdateXMLUrlFromOC must be equal to non-empty string values in that same registry key. UpdateOfficeConfigTimestamp is a UNIX epoch time which must be set to a large QWORD such as 99999999999 (in decimal) to indicate the URL cache is good. The downloaded file will be in %localappdata%\OneDrive\StandaloneUpdater\PreSignInSettingsConfig.json`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [OneDriveStandaloneUpdater.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/OneDriveStandaloneUpdater.yml) | `- Path: '%localappdata%\Microsoft\OneDrive\OneDriveStandaloneUpdater.exe'`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [OneDriveStandaloneUpdater.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/OneDriveStandaloneUpdater.yml) | `- IOC: HKCU\Software\Microsoft\OneDrive\UpdateOfficeConfig\UpdateRingSettingURLFromOC being set to a suspicious non-Microsoft controlled URL`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [OneDriveStandaloneUpdater.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/OneDriveStandaloneUpdater.yml) | `- IOC: Reports of downloading from suspicious URLs in %localappdata%\OneDrive\setup\logs\StandaloneUpdate_*.log files`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [casbaneiro](https://github.com/eset/malware-ioc/blob/master/casbaneiro/README.adoc) | `- `%APPDATA%\OneDrive\OneDrive.exe``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [casbaneiro](https://github.com/eset/malware-ioc/blob/master/casbaneiro/README.adoc) | `** `OneDrive = %APPDATA%\OneDrive\OneDrive.exe``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [interception](https://github.com/eset/malware-ioc/blob/master/interception/README.adoc) | `C:\Users\<USER>\AppData\Local\Microsoft\OneDrive\OneDrive.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [interception](https://github.com/eset/malware-ioc/blob/master/interception/README.adoc) | `C:\Users\<USER>\AppData\Local\Microsoft\oneDrive\oneDriveSync.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [2020_Q2](https://github.com/eset/malware-ioc/blob/master/quarterly_reports/2020_Q2/README.adoc) | `C:\OneDrive\OneDriveSync.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [2020_Q4](https://github.com/eset/malware-ioc/blob/master/quarterly_reports/2020_Q4/README.adoc) | `C:\ProgramData\OneDrive\OneDriveService.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-crutch-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-crutch-event.json) | `"value": "%LOCALAPPDATA%\\Microsoft\\OneDrive\\dwmapi.dll",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | `* `++%LOCALAPPDATA%\Microsoft\OneDrive\dwmapi.dll++``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt37_bluelight.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt37_bluelight.yar) | description = "The BLUELIGHT malware family. Leverages Microsoft OneDrive for network communications." | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


