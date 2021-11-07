---
title: rasdial.exe | Remote Access Command Line Dial UI
excerpt: What is rasdial.exe?
---

# rasdial.exe 

* File Path: `C:\Windows\system32\rasdial.exe`
* Description: Remote Access Command Line Dial UI

## Hashes

Type | Hash
-- | --
MD5 | `63E72A854C787371CB26590269C1E93E`
SHA1 | `D3F856EE0D592295456E1A6756E3E7962B2F16BB`
SHA256 | `A5D1F1C9A53F285D027CD1D57326FB323C4B90FBFEF9B9806A46328A09B7BF08`
SHA384 | `51151F4315B04106FA18B854060CFC43F446760BF491B95E910904FD8A8F8ED0579AA19C8F2B3ED5975A4BDCC9FB49B2`
SHA512 | `015D18FA787EF949FA1B3FAD7A81B0438A24735C304177A70F0A3701DB74058A18897D03888EA6E55BF4C2D218E2E5C62ECDEB8E32846FE5994EA62250B65CC0`
SSDEEP | `384:nKoqPyZTRhuIONkeFrk9I45HFO+0+DKOobMCgGW6VW:nKXiuzNkeFo9Iush5PoTS`
IMP | `D893FB6DD140FF7107D0E41FFBAAAEC9`
PESHA1 | `0238F27EA374507223270B0AFA8EF66BCA17200A`
PE256 | `56FA3DE44D5068749F00EB09174C654A8D57B598E28E3A75AE283B3471C1003F`

## Runtime Data

### Usage (stdout):
```cmhg
USAGE:
	C:\Windows\system32\rasdial.exe entryname [username [password|*]] [/DOMAIN:domain]
		[/PHONE:phonenumber] [/CALLBACK:callbacknumber]
		[/PHONEBOOK:phonebookfile] [/PREFIXSUFFIX]

	C:\Windows\system32\rasdial.exe [entryname] /DISCONNECT

	C:\Windows\system32\rasdial.exe

	Please refer to our privacy statement at 
	'https://go.microsoft.com/fwlink/?LinkId=521839'


```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\rasdial.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RASDIAL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/a5d1f1c9a53f285d027cd1d57326fb323c4b90fbfef9b9806a46328a09b7bf08/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\rasdial.exe](rasdial.exe-6AEB82B4CA13B5FBD316F3247049DB0F.md) | 74

## Possible Misuse

*The following table contains possible examples of `rasdial.exe` being misused. While `rasdial.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `title: Suspicious RASdial Activity`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `description: Detects suspicious process related to rasdial.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `- rasdial.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


