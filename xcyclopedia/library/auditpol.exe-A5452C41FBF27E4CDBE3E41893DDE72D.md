---
title: auditpol.exe | Audit Policy Program
excerpt: What is auditpol.exe?
---

# auditpol.exe 

* File Path: `C:\Windows\SysWOW64\auditpol.exe`
* Description: Audit Policy Program

## Hashes

Type | Hash
-- | --
MD5 | `A5452C41FBF27E4CDBE3E41893DDE72D`
SHA1 | `2C7AC7FF170567BC2EB4578BA2242220F5BC997A`
SHA256 | `CE7C5BBC024F803E35D1486585941F7BA6338543CCDE606FC04138A22AC763BC`
SHA384 | `C2A7D715A0C82057BA0FB09CB73956635CDCFEB6217ABE9058591DA774BCACBD9188486B620AA0D973F54E421788D165`
SHA512 | `7EA07E08BD8FC5AAEB5103BCBB16ACE0110B1E3AF206A4E0B867E3F53E1CD354D89FB3ADE37415D749A7F2DC689B64969059F2F713AB4E97A45FCB8FF83A7CFD`
SSDEEP | `768:kF76lUgRsRF057jvykFalDtqQ4pd5w2Nmsy:Ke+FRi7W+ADtqQ4X5w2Nmsy`
IMP | `0C4B99BEEA5B3B9367B087A10A48BD92`
PESHA1 | `39595778D01766F77F796AC96EA228E01438D320`
PE256 | `188FE10D1BE092310A9A8091A2F91E7576B3DB2720854352023EBF5AE64BD86A`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\auditpol.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUDITPOL.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/ce7c5bbc024f803e35d1486585941f7ba6338543ccde606fc04138a22ac763bc/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\auditpol.exe](auditpol.exe-70DF7973F8D4AAA2EE3B28391239397B.md) | 86


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



MIT License. Copyright (c) 2020 Strontic.


