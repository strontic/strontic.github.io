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
MD5 | `6CDC8E5DF04752235D5B4432EACC81A8`
SHA1 | `858A6A5A56C473F3DDD0BC2CC6DFE30856442103`
SHA256 | `DA8059F55EC94DFCB0E75FA43FA6BBC794070E50DEFC00216FC42710CFA58825`
SHA384 | `726DB38E17D1538D2AA8CAC43E2E7C295AAE8DDB9CE4DDD05E63B423E72D73CB41B0F48AB467B8A90BEB31810F27B195`
SHA512 | `85662F9A7E8820DE2CAB4FDACA1DCC9D3503F9A401EB83A4022B2F94090EE73133B453574FEA33117CC247134F0BE24F9D562C4B2F76C18C899D66759DB3C628`
SSDEEP | `384:h/HDVrL5yZsXfPPeN5qu7/btczd/xbGV9W3wW:VDCgmHLVchhGVC`
IMP | `19CAF11535B9CA1BEB2EF45EB8724422`
PESHA1 | `3436CC79A0721F888C51F837315862DC33CB57E6`
PE256 | `9B0B6BA719A07051820857918A3312313429B7941B9C382B61285FD09C14F16D`

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

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\cmdkey.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cmdkey.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/da8059f55ec94dfcb0e75fa43fa6bbc794070e50defc00216fc42710cfa58825/detection


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


