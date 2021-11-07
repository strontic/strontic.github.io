---
title: GoogleUpdate.exe | Google Installer
excerpt: What is GoogleUpdate.exe?
---

# GoogleUpdate.exe 

* File Path: `C:\Program Files (x86)\Google\Update\GoogleUpdate.exe`
* Description: Google Installer

## Screenshot

![GoogleUpdate.exe](screenshots/GoogleUpdate.exe-0BCA3F16DD527B4150648EC1E36CB22A-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `6BF197B8C7DE4B004C5D6FA415FC7867`
SHA1 | `28F84C220BA321960687A80B79D7860B767A0960`
SHA256 | `61A92167587E540275B374890BE8FD0319FE03C4F19CC79A8C2FB6871CF21E73`
SHA384 | `74BC7707E01A27EC8DB51A1EF5AB26D9EBBFB0C1D37E81513DBD8B662961C5138E1EDFEDE8BDCC42696121B8B9656BD0`
SHA512 | `D7A3DD059DDAE20A09C00738F20720CAEEB026368DFCFDF4103D433121A236780C37EFD89CD6DCC15F6C3AEAE5A3D29178498435CC5A2506E1E674BA155986F6`
SSDEEP | `3072:MAt2So2m5oyiTOZQvfSERdX9Zk8AtB+flovvC/Y6V6z5jmVZklFYCFQCexxlG3/E:ExwjRsB+Rc0`
IMP | `7DF1816239C5BC855600D41210406C5B`
PESHA1 | `91215E06322F60B9887679F369298AE147F9137A`
PE256 | `9564F00DFD811AFC22CBD0C8214D5B949498AD1F1EAB7DC664EFABC47BA883C0`

## Runtime Data

### Child Processes:
explorer.exe

### Window Title:
Google Update Installer

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\SysWOW64\en-US\user32.dll.mui | File
(RW-)   C:\Program Files (x86)\Google\Update\1.3.36.112 | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1110_none_a8625c1886757984 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme449731986 | Section
\Windows\Theme1396518710 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Google\Update\GoogleUpdate.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `06AEA76BAC46A9E8CFE6D29E45AAF033`
* Thumbprint: `A3958AE522F3C54B878B20D7B0F63711E08666B2`
* Issuer: CN=DigiCert Assured ID Code Signing CA-1, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=Google LLC, O=Google LLC, L=Mountain View, S=California, C=US

## File Metadata

* Original Filename: GoogleUpdate.exe
* Product Name: Google Update
* Company Name: Google LLC
* File Version: 1.3.36.111
* Product Version: 1.3.36.111
* Language: English (United States)
* Legal Copyright: Copyright 2018 Google LLC
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/61a92167587e540275b374890be8fd0319fe03c4f19cc79a8c2fb6871cf21e73/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Google\Update\1.3.35.452\GoogleUpdate.exe](GoogleUpdate.exe-0BCA3F16DD527B4150648EC1E36CB22A.md) | 65
[C:\Program Files (x86)\Google\Update\1.3.36.112\GoogleUpdate.exe](GoogleUpdate.exe-6BF197B8C7DE4B004C5D6FA415FC7867.md) | 100
[C:\Program Files (x86)\Google\Update\GoogleUpdate.exe](GoogleUpdate.exe-0BCA3F16DD527B4150648EC1E36CB22A.md) | 65

## Possible Misuse

*The following table contains possible examples of `GoogleUpdate.exe` being misused. While `GoogleUpdate.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_alert_lsass_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_alert_lsass_access.yml) | `- Google Chrome GoogleUpdate.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_apt29_tor.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/win_apt_apt29_tor.yml) | `description: This method detects malicious services mentioned in APT29 report by FireEye. The legitimate path for the Google update service is C:\Program Files (x86)\Google\Update\GoogleUpdate.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_apt29_tor.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/win_apt_apt29_tor.yml) | `- 'C:\Program Files(x86)\Google\GoogleUpdate.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `- Command: wmic.exe /node:REMOTECOMPUTERNAME PROCESS call create "at 9:00PM c:\GoogleUpdate.exe ^> c:\notGoogleUpdateResults.txt"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `Description: Create a scheduled execution of C:\GoogleUpdate.exe to run at 9pm.`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-machete-event.json](https://github.com/eset/malware-ioc/blob/master/machete/misp-machete-event.json) | `"value": "GoogleUpdate.exe",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [machete](https://github.com/eset/malware-ioc/blob/master/machete/README.adoc) | `=== GoogleUpdate.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_google_anomaly.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_google_anomaly.yar) | description = "Detects suspicious unsigned GoogleUpdate.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_google_anomaly.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_google_anomaly.yar) | /* OriginalName GoogleUpdate.exe */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


