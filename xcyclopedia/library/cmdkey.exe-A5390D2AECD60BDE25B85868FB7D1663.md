---
title: cmdkey.exe | Credential Manager Command Line Utility
---

# cmdkey.exe 

* File Path: `C:\WINDOWS\system32\cmdkey.exe`
* Description: Credential Manager Command Line Utility

## Hashes

Type | Hash
-- | --
MD5 | `A5390D2AECD60BDE25B85868FB7D1663`
SHA1 | `728D70C3ACF5179F6DD7F1A774C615F8326063EF`
SHA256 | `E6AD20EB41B82EB4211211522E3FA1E2ACF434766000A09B3F2BADE7A120411B`
SHA384 | `50055338A04B8DE28F5B1D50657E428BD9F83E32CD68BC042B54E29A2C0BAF7A68B766BBDC984EF14C2AECCFD4E3E567`
SHA512 | `3022BBB91384F1A66C0B48F60DCE0DA64B11C814975D94E03C75E8066EA1343A2A881B275E99868FC0095F274B5C437E5D74AC52ADC0F9F75CCA39ACF458FD87`
SSDEEP | `384:E3K4N9/4sTPWtvuKltPiEM5OUDdTXTlJ31Gp9WiwW:JoQrt6VtD3zGp3`

## Runtime Data

### Usage (stdout):
```cmhg

Creates, displays, and deletes stored user names and passwords.

The syntax of this command is:

CMDKEY [{/add | /generic}:targetname {/smartcard | /user:username {/pass{:password}}} | /delete{:targetname | /ras} | /list{:targetname}]

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cmdkey.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\cmdkey.exe](cmdkey.exe-2C6DFF18B542601CC6EF0B64AEC48A95.md) | 66

## Possible Misuse

*The following table contains possible examples of `cmdkey.exe` being misused. While `cmdkey.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_cmdkey_recon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmdkey_recon.yml) | `title: Cmdkey Cached Credentials Recon` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cmdkey_recon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmdkey_recon.yml) | `description: Detects usage of cmdkey to look for cached credentials` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cmdkey_recon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmdkey_recon.yml) | `- https://www.peew.pw/blog/2017/11/26/exploring-cmdkey-an-edge-case-for-privilege-escalation` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cmdkey_recon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmdkey_recon.yml) | `Image: '*\cmdkey.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_local_system_owner_account_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_local_system_owner_account_discovery.yml) | `- Image\|endswith: '\cmdkey.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdkey.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdkey.yml) | `Name: Cmdkey.exe ` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdkey.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdkey.yml) | `- Command: cmdkey /list` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdkey.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdkey.yml) | `- Path: C:\Windows\System32\cmdkey.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdkey.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdkey.yml) | `- Path: C:\Windows\SysWOW64\cmdkey.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdkey.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdkey.yml) | `- Link: https://www.peew.pw/blog/2017/11/26/exploring-cmdkey-an-edge-case-for-privilege-escalation` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmdkey.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmdkey.yml) | `- Link: https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/cmdkey` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.001/T1021.001.md) | cmdkey /generic:TERMSRV/$Server /user:$User /pass:$Password | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1087.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1087.001/T1087.001.md) | cmdkey.exe /list | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## cmdkey

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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
| /delete{:`<targetname>` | /ras} | Deletes a user name and password from the list. If `<targetname>` is specified, that entry is deleted. If `/ras` is specified, the stored remote access entry is deleted. |
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



MIT License. Copyright (c) 2020 Strontic.


