﻿---
title: auditpol.exe | Audit Policy Program
excerpt: What is auditpol.exe?
---

# auditpol.exe 

* File Path: `C:\Windows\system32\auditpol.exe`
* Description: Audit Policy Program

## Hashes

Type | Hash
-- | --
MD5 | `F97C0041886519CEAE336B06AEBFC9E1`
SHA1 | `0A81854C79D49EF3241A962EBFBAEE438CEF1160`
SHA256 | `969306E33A469096EFA20BEE264FB37AC4DA86899F2659007D6BE0D1EB666B1C`
SHA384 | `F4B90A40FA4E52D82DE8F7375E5D2E898DD5E9BA776CB0F272A58086B5242EB44CF84AD5324C443A2D1570B8AA03DD52`
SHA512 | `CE8A1A2D13D9CB8503F7AD2B03F331275F2361F9F3004C19EEC0EDE24928BD84795202E8FBB3BCE9BCF8B68A390CAB127525B9B4D6797F0B36796B2A82C9F5CC`
SSDEEP | `768:nVWCDXCmFOv7yG8Ts+m7BwVRRde98Hom3NCWE6gn:1DgeXPm6om3NVgn`
IMP | `D401223A63DBFDCD11C945B9EEE0BD7E`
PESHA1 | `30537E917CAC4C56B59C7B640D595F1CBF781CCF`
PE256 | `CC067F540B96A893DDC9DC8184E5A7DAFBD869751864BB4590DEBB74C966E99D`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: AuditPol command [<sub-command><options>]


Commands (only one command permitted per execution)
  /?               Help (context-sensitive)
  /get             Displays the current audit policy.
  /set             Sets the audit policy.
  /list            Displays selectable policy elements.
  /backup          Saves the audit policy to a file.
  /restore         Restores the audit policy from a file.
  /clear           Clears the audit policy.
  /remove          Removes the per-user audit policy for a user account.
  /resourceSACL    Configure global resource SACLs


Use AuditPol <command> /? for details on each command

```

### Usage (stderr):
```cmhg
Error 0x00000057 occurred:
The parameter is incorrect.


```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\system32\auditpol.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUDITPOL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/969306e33a469096efa20bee264fb37ac4da86899f2659007d6be0d1eb666b1c/detection/


## Possible Misuse

*The following table contains possible examples of `auditpol.exe` being misused. While `auditpol.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_sus_auditpol_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sus_auditpol_usage.yml) | `title: Suspicious Auditpol Usage `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sus_auditpol_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sus_auditpol_usage.yml) | `description: Threat actors can use auditpol binary to change audit policy configuration to impair detection capability. This can be carried out by selectively disabling/removing certain audit policies as well as restoring a custom policy owned by the threat actor. `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sus_auditpol_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sus_auditpol_usage.yml) | `Image\|endswith: '\auditpol.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | Use the cleanup commands to restore some default auditpol settings (your original settings will be lost) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | auditpol /set /category:"Account Logon" /success:disable /failure:disable | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | auditpol /set /category:"Logon/Logoff" /success:disable /failure:disable | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | auditpol /set /category:"Detailed Tracking" /success:disable | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | auditpol /set /category:"Account Logon" /success:enable /failure:enable | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | auditpol /set /category:"Detailed Tracking" /success:enable | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | auditpol /set /category:"Logon/Logoff" /success:enable /failure:enable | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | Clear the Windows audit policy using auditpol utility. This action would stop certain audit events from being recorded in the security log. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | auditpol /clear /y | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | auditpol /remove /allusers | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## auditpol

Displays information about and performs functions to manipulate audit policies, including:

- Setting and querying a system audit policy.

- Setting and querying a per-user audit policy.

- Setting and querying auditing options.

- Setting and querying the security descriptor used to delegate access to an audit policy.

- Reporting or backing up an audit policy to a comma-separated value (CSV) text file.

- Loading an audit policy from a CSV text file.

- Configuring global resource SACLs.

### Syntax

```
auditpol command [<sub-command><options>]
```

#### Parameters

| Sub-command | Description |
| ----------- | ----------- |
| /get | Displays the current audit policy. For more information, see [auditpol get](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/auditpol-get.md) for syntax and options. |
| /set | Sets the audit policy. For more information, see [auditpol set](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/auditpol-set.md) for syntax and options. |
| /list | Displays selectable policy elements. For more information, see [auditpol list](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/auditpol-list.md) for syntax and options. |
| /backup | Saves the audit policy to a file. For more information, see [auditpol backup](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/auditpol-backup.md) for syntax and options. |
| /restore | Restores the audit policy from a file that was previously created by using auditpol /backup. For more information, see [auditpol restore](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/auditpol-restore.md) for syntax and options. |
| /clear | Clears the audit policy. For more information, see [auditpol clear](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/auditpol-clear.md) for syntax and options. |
| /remove | Removes all per-user audit policy settings and disables all system audit policy settings. For more information, see [auditpol remove](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/auditpol-remove.md) for syntax and options. |
| /resourceSACL | Configures global resource system access control lists (SACLs). **Note:** Applies only to Windows 7 and Windows Server 2008 R2. For more information, see [auditpol resourceSACL](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/auditpol-resourcesacl.md). |
| /?| Displays help at the command prompt. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


