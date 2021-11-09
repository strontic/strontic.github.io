---
title: rasdial.exe | Remote Access Command Line Dial UI
excerpt: What is rasdial.exe?
---

# rasdial.exe 

* File Path: `C:\WINDOWS\system32\rasdial.exe`
* Description: Remote Access Command Line Dial UI

## Hashes

Type | Hash
-- | --
MD5 | `40582C09634742DF2ED402CC5180772C`
SHA1 | `FAB0DAB20732A27A19F0448D9896B226FE617C00`
SHA256 | `AE8ABD0DC927E9E75AB796EF251E6DB5D19EBCA37B8CA04EC11C6D5170A46609`
SHA384 | `72AA7A33FF02180A086C5DB99F5C8AC9C48E8F1900917FF7FC368302C38F5573A2ED4E1130F1433AC3D340F1271F5D48`
SHA512 | `87A888D6DCA3F9566EA40E69F3E1C542A1B5329595AF8D05D997C6DCC01DAF31A0C3FA78725143A5D65AA80FF36222B3E5DA06F24D7C6E9D7CEEA9D3697082F0`
SSDEEP | `768:rCKJuS4WN2GrY+4+QdN09AyiQU6aRm8o:rV4Q2G0+4+2N09AyiQU6yo`
IMP | `D893FB6DD140FF7107D0E41FFBAAAEC9`
PESHA1 | `F68DC1E9AB62589A91A4C26FF30727776C240DF1`
PE256 | `F062DB788063F9697B602C576D666330AACF261A1E7C0ECE32A8BD06721C28F0`

## Runtime Data

### Usage (stdout):
```cmhg
USAGE:
	C:\WINDOWS\system32\rasdial.exe entryname [username [password|*]] [/DOMAIN:domain]
		[/PHONE:phonenumber] [/CALLBACK:callbacknumber]
		[/PHONEBOOK:phonebookfile] [/PREFIXSUFFIX]

	C:\WINDOWS\system32\rasdial.exe [entryname] /DISCONNECT

	C:\WINDOWS\system32\rasdial.exe

	Please refer to our privacy statement at 
	'https://go.microsoft.com/fwlink/?LinkId=521839'


```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\rasdial.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RASDIAL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/ae8abd0dc927e9e75ab796ef251e6db5d19ebca37b8ca04ec11c6d5170a46609/detection


## Possible Misuse

*The following table contains possible examples of `rasdial.exe` being misused. While `rasdial.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `title: Suspicious RASdial Activity`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `description: Detects suspicious process related to rasdial.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `- rasdial.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


