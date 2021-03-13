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
MD5 | `6E92C10F5EEC17D4D67A23609D340679`
SHA1 | `161F416B98D569B87B933EC78A705B8587ED4381`
SHA256 | `6F52D81DBBB6D07C033299B9B64A0011B59089401327CDF494611649E392372E`
SHA384 | `72242F68F4A71BF70E0E19FE73EE853BC59B97B846B78777E7172AED50D16323F0368FAF1D5AA971CFB0A7F3A5069983`
SHA512 | `BF1AEF9C79B7B5504501864C0FA1C25629CF7EA198A0A347A0970FFB927AE64913BDFDD3853EF8DDA51B79FAEB568053F68075AC62102801BC16A4745B3AABD5`
SSDEEP | `384:7r2BMwcGKpSs1YEhu+L/4VyerOKZtZ1w+20rgkbOcokosnJSWEVW:fyJbgeEhu+Lsrn+wrg9coj8Jw`

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

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RASDIAL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `rasdial.exe` being misused. While `rasdial.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `title: Suspicious RASdial Activity`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `description: Detects suspicious process related to rasdial.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rasdial_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rasdial_activity.yml) | `- rasdial.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


