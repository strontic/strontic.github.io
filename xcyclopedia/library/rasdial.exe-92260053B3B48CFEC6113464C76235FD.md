---
title: rasdial.exe | Remote Access Command Line Dial UI
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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\rasdial.exe |


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

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\rasdial.exe](rasdial.exe-E9EC77CEB1E941AA51CBBEE8C4328334.md) | 47

## Possible Misuse

*The following table contains possible examples of `rasdial.exe` being misused. While `rasdial.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `title: Suspicious RASdial Activity` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `description: Detects suspicious process related to rasdial.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `            - rasdial.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


