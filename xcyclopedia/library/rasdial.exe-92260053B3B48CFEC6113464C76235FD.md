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
MD5 | `92260053B3B48CFEC6113464C76235FD`
SHA1 | `D6CD743EC4F3910DF0E59977E5E68EA110EC33B4`
SHA256 | `7427FE46C5A8B9A8E2A85FFE4AF8706473CE02ECD4168517C3FF81E6802302E1`
SHA384 | `ACEEA98F8AC2311D25EF9428906EDF25D43BD7067ED3054F100D7C843C7A227C34B1D328BA74D621AD628790BB80AFD2`
SHA512 | `E5016E501D7D5276D08DA3735260FE7C5F29FD3DEDD4C3F9B2DECECD9C3EBB6CC87AE4EA18A5E4746A054D28EAA9177DFD0A6B35A91D97452ADE2E7A71E9E9A7`
SSDEEP | `384:qMrNEf9uohXdznu+hyUje+GRmLjM2OOAIf+bxVY9t0yNwKWQVW:qMrN2uohXQ60NRa4DRbLytNNws`
IMP | `D893FB6DD140FF7107D0E41FFBAAAEC9`
PESHA1 | `57B804D50266E680C52C58286255F12394CE1B88`
PE256 | `CEFEB555BDE7FE1DC9B0D6C8ADF0759590D0170D7611239192C1C5C07509ADA9`

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
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\cryptsp.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\system32\RASAPI32.dll |
C:\Windows\system32\rasdial.exe |
C:\Windows\system32\rasman.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\rtutils.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\windows.storage.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RASDIAL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/7427fe46c5a8b9a8e2a85ffe4af8706473ce02ecd4168517c3ff81e6802302e1/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\rasdial.exe](rasdial.exe-E9EC77CEB1E941AA51CBBEE8C4328334.md) | 47

## Possible Misuse

*The following table contains possible examples of `rasdial.exe` being misused. While `rasdial.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `title: Suspicious RASdial Activity`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `description: Detects suspicious process related to rasdial.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `- rasdial.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


