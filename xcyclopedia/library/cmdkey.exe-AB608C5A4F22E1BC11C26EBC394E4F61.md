﻿---
title: cmdkey.exe | Credential Manager Command Line Utility
excerpt: What is cmdkey.exe?
---

# cmdkey.exe 

* File Path: `C:\Windows\SysWOW64\cmdkey.exe`
* Description: Credential Manager Command Line Utility

## Hashes

Type | Hash
-- | --
MD5 | `AB608C5A4F22E1BC11C26EBC394E4F61`
SHA1 | `16814597D6BB2F18CB36A2630A281DE4936068E1`
SHA256 | `EA468EF7815F4E628C295BD05ED247DCD942CD71AFA991B9EC4B94D963110AA4`
SHA384 | `265D05507870697C523FC9E7C9521403C597418F8338B8FDBD5C8F1DA67292242B8352227D3E098D670BF776DF6E72AE`
SHA512 | `E00DEC46B6770AA160B9048156B6F69751F08F00312326318AAAC3EFF4268A568FEF2AA43DE800EB9F98DCCDA51755D6EB06F28C51D20425E475178C1E88C580`
SSDEEP | `384:UDhVrF3i5shjB0uOZdR7sx34zd/qcGDlWswW:UDhOYPOZdI4hbGDF`
IMP | `19CAF11535B9CA1BEB2EF45EB8724422`
PESHA1 | `00FC36920CC363B42CD365619C468B87175E6E20`
PE256 | `E93B14868CC994C770EBFB915307902B3CF2BBEB04FD14EAE41547C2E0EB0A40`

## Runtime Data

### Usage (stdout):
```cmhg

Creates, displays, and deletes stored user names and passwords.

The syntax of this command is:

CMDKEY [{/add | /generic}:targetname {/smartcard | /user:username {/pass{:password} }} | /delete{:targetname | /ras} | /list{:targetname}]

Examples:

  To list available credentials:
     cmdkey /list
     cmdkey /list:targetname

  To create domain credentials:
     cmdkey /add:targetname /user:username /pass:password
     cmdkey /add:targetname /user:username /pass
     cmdkey /add:targetname /user:username
     cmdkey /add:targetname /smartcard
     
  To create generic credentials:
     The /add switch may be replaced by /generic to create generic credentials

  To delete existing credentials:
     cmdkey /delete:targetname

  To delete RAS credentials:
     cmdkey /delete /ras
     

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cmdkey.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/ea468ef7815f4e628c295bd05ed247dcd942cd71afa991b9ec4b94d963110aa4/detection/


## Possible Misuse

*The following table contains possible examples of `cmdkey.exe` being misused. While `cmdkey.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_cmdkey_recon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmdkey_recon.yml) | `title: Cmdkey Cached Credentials Recon`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cmdkey_recon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmdkey_recon.yml) | `description: Detects usage of cmdkey to look for cached credentials`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cmdkey_recon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmdkey_recon.yml) | `- https://www.peew.pw/blog/2017/11/26/exploring-cmdkey-an-edge-case-for-privilege-escalation`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cmdkey_recon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmdkey_recon.yml) | `Image\|endswith: '\cmdkey.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_local_system_owner_account_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_local_system_owner_account_discovery.yml) | `- Image\|endswith: '\cmdkey.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdkey.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdkey.yml) | `Name: Cmdkey.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdkey.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdkey.yml) | `- Command: cmdkey /list`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdkey.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdkey.yml) | `- Path: C:\Windows\System32\cmdkey.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdkey.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdkey.yml) | `- Path: C:\Windows\SysWOW64\cmdkey.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdkey.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdkey.yml) | `- Link: https://www.peew.pw/blog/2017/11/26/exploring-cmdkey-an-edge-case-for-privilege-escalation`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdkey.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdkey.yml) | `- Link: https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/cmdkey`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.001/T1021.001.md) | cmdkey /generic:TERMSRV/$Server /user:$User /pass:$Password | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1087.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1087.001/T1087.001.md) | cmdkey.exe /list | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## cmdkey

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Creates, lists, and deletes stored user names and passwords or credentials.

### Syntax

```
cmdkey [{/add:<targetname>|/generic:<targetname>}] {/smartcard | /user:<username> [/pass:<password>]} [/delete{:<targetname> | /ras}] /list:<targetname>
```

#### Parameters

| Parameters | Description |
| ---------- | ----------- |
| /add:`<targetname>` | Adds a user name and password to the list.<p>Requires the parameter of `<targetname>` which identifies the computer or domain name that this entry will be associated with. |
| /generic:`<targetname>` | Adds generic credentials to the list.<p>Requires the parameter of `<targetname>` which identifies the computer or domain name that this entry will be associated with. |
| /smartcard | Retrieves the credential from a smart card. If more than one smart card is found on the system when this option is used, **cmdkey** displays information about all available smart cards, and then prompts the user to specify which one to use. |
| /user:`<username>` | Specifies the user or account name to store with this entry. If `<username>` isn't supplied, it will be requested. |
|/pass:`<password>` | Specifies the password to store with this entry. If `<password>` isn't supplied, it will be requested. Passwords are not displayed after they're stored. |
| /delete:`{<targetname> \| /ras}` | Deletes a user name and password from the list. If `<targetname>` is specified, that entry is deleted. If `/ras` is specified, the stored remote access entry is deleted. |
| /list:`<targetname>` | Displays the list of stored user names and credentials. If `<targetname>` isn't specified, all stored user names and credentials are listed. |
| /? | Displays help at the command prompt. |

### Examples

To display a list of all user names and credentials that are stored, type:

```
cmdkey /list
```

To add a user name and password for user *Mikedan* to access computer *Server01* with the password *Kleo*, type:

```
cmdkey /add:server01 /user:mikedan /pass:Kleo
```

To add a user name and password for user *Mikedan* to access computer *Server01* and prompt for the password whenever Server01 is accessed, type:

```
cmdkey /add:server01 /user:mikedan
```

To delete a credential stored by remote access, type:

```
cmdkey /delete /ras
```

To delete a credential stored for *Server01*, type:

```
cmdkey /delete:server01
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


