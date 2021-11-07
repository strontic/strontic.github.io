---
title: rasdial.exe | Remote Access Command Line Dial UI
excerpt: What is rasdial.exe?
---

# rasdial.exe 

* File Path: `C:\Windows\SysWOW64\rasdial.exe`
* Description: Remote Access Command Line Dial UI

## Hashes

Type | Hash
-- | --
MD5 | `A280B0F42A83064C41CFFDC1CD35136E`
SHA1 | `8A2BF434E8EF7951AEFCDCA73CB18934D0EA8CD2`
SHA256 | `A33F829DD3FBBA909FA13ABB902FAD29A12E1519F295DB39FDD10A28094B9942`
SHA384 | `809A4537C9AC4C73FBE9024F2C1EFB56D9E78EBDBD807A7D6B109D0D7105F3D0173E4576D805D0D43569045FBFDFEC84`
SHA512 | `07323BCDD107213E575FFAE9F876F0E8D05E5B6DC6A09EBD430C8FEDF9017EE41167939380E15E28BCC4F8F1A7FA078898CC63E2BFB688EF1A91BDEE4911FE22`
SSDEEP | `384:fPp44TPy7bcf4Q0jAvsrkkEsQCLTWW6VW:5Xy5FQmTC`
IMP | `5C49C69DC9F9E8B85CB908313C7FCFF4`
PESHA1 | `9FFA25EF8DA5CE7B0773E5D49C331A29B21DE0DD`
PE256 | `10B7826D8A443E87C7E5247C811246C3831DDE4C1A5455598E70DC6EAB281596`

## Runtime Data

### Usage (stdout):
```cmhg
USAGE:
	C:\Windows\SysWOW64\rasdial.exe entryname [username [password|*]] [/DOMAIN:domain]
		[/PHONE:phonenumber] [/CALLBACK:callbacknumber]
		[/PHONEBOOK:phonebookfile] [/PREFIXSUFFIX]

	C:\Windows\SysWOW64\rasdial.exe [entryname] /DISCONNECT

	C:\Windows\SysWOW64\rasdial.exe

	Please refer to our privacy statement at 
	'https://go.microsoft.com/fwlink/?LinkId=521839'


```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\rasdial.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RASDIAL.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1266 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1266
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/a33f829dd3fbba909fa13abb902fad29a12e1519f295db39fdd10a28094b9942/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\rasdial.exe](rasdial.exe-799A2572818B770C12B9B02B89E38FEB.md) | 77

## Possible Misuse

*The following table contains possible examples of `rasdial.exe` being misused. While `rasdial.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `title: Suspicious RASdial Activity`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `description: Detects suspicious process related to rasdial.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `- rasdial.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


