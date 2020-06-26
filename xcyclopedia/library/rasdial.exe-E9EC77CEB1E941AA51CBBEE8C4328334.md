---
title: rasdial.exe | Remote Access Command Line Dial UI
---

# rasdial.exe 

* File Path: `C:\WINDOWS\system32\rasdial.exe`
* Description: Remote Access Command Line Dial UI
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E9EC77CEB1E941AA51CBBEE8C4328334`
SHA1 | `C1F2B09275AC95C0837EE87BBD3477F2E1795023`
SHA256 | `FBAF36C2FC8C597DACBDC7976C6C541D3E8ECF2D6E8C0B302E4A95A742824169`
SHA384 | `6BDAB5815FC1538D38ACC00635BD459737DC5B50D2D1F9347EEDA70AAC866A007B4CD928B109465411940D88955A4A34`
SHA512 | `ED917ADEE31200FB5E9D202CA931C787D060C2AC211F625B84A3A41209429BDDBD5593EC9D6E5238616C775B0F75FA07CBBBD99802B924ED9C6DE0309D56EF22`
SSDEEP | `384:WSII9NhWmOm5XPuYb9ASn++hyUje+lRmLjR6LO9Kf+txVP9h96WWVW:WSrkmpuYbKF60ORaILUtLFh9i`

## Runtime Data

### Usage (stdout):
```Batchfile
USAGE:
	C:\WINDOWS\system32\rasdial.exe entryname [username [password|*]] [/DOMAIN:domain]
		[/PHONE:phonenumber] [/CALLBACK:callbacknumber]
		[/PHONEBOOK:phonebookfile] [/PREFIXSUFFIX]

	C:\WINDOWS\system32\rasdial.exe [entryname] /DISCONNECT

	C:\WINDOWS\system32\rasdial.exe

	Please refer to our privacy statement at 
	'https://go.microsoft.com/fwlink/?LinkId=521839'


```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RASDIAL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `rasdial.exe` being misused. While `rasdial.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `title: Suspicious RASdial Activity` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `description: Detects suspicious process related to rasdial.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `            - rasdial` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


