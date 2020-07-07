﻿---
title: rasdial.exe | Remote Access Command Line Dial UI
---

# rasdial.exe 

* File Path: `C:\Windows\SysWOW64\rasdial.exe`
* Description: Remote Access Command Line Dial UI
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `799A2572818B770C12B9B02B89E38FEB`
SHA1 | `454C0132295D76E8FAF8EEA39B12CCC7D9B0921E`
SHA256 | `56572B71F9E7E3151FAD06EE724A1CC11C6D56B27981AD2E6FEEF0A0D759F12C`
SHA384 | `87A018ECD8816C763C7D77EC5DA16A570CEF5B5D323817CD1F54BE6CCC9E0B46D975FA1E9D28A682ADF106226F8BF194`
SHA512 | `1A232FDE52F3654F84AF5D7410EC8C7165CB753A02795D4821C5AB092994ABDF7A39C05FD5E0582567D86BE388AC8AD7E23239D0748F853C541C79E1AEE476AE`
SSDEEP | `384:7Hp44TPy7bcf4Q0jAvsrkkEsQ7yzNmqWrVW:lXy5FQ2zNmn`

## Runtime Data

### Usage (stdout):
```Batchfile
USAGE:
	C:\Windows\SysWOW64\rasdial.exe entryname [username [password|*]] [/DOMAIN:domain]
		[/PHONE:phonenumber] [/CALLBACK:callbacknumber]
		[/PHONEBOOK:phonebookfile] [/PREFIXSUFFIX]

	C:\Windows\SysWOW64\rasdial.exe [entryname] /DISCONNECT

	C:\Windows\SysWOW64\rasdial.exe

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

* Original Filename: RASDIAL.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
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

