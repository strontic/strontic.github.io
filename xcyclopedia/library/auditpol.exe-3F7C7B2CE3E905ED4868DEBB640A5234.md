
# auditpol.exe 

* File Path: `C:\Windows\system32\auditpol.exe`
* Description: Audit Policy Program
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `3F7C7B2CE3E905ED4868DEBB640A5234`
SHA1 | `9D0F2C4224F780847E0D1AC6C21C11A0CDCE7EEF`
SHA256 | `91278DA04F3A40DA84CD151D3E69A4F39EEF82BD7F7F3A238DD5E3C224CAA33A`
SHA384 | `36460CFBDB2ECCF1691C54A95DAD1222F028FB901C7FE55E39815275E3DDBA12BD3DF23468AC10AFAC51886FE5D446A2`
SHA512 | `8755396F0E01859C938D5D6E2B0155F0A86E52BE1B14742DA97C71B1A0C002FCCABD3C3628BC55E96E07E9B1320FE3465E7115F3B1295456B831C012954DD0E6`
SSDEEP | `768:k/5zR9nJTTUb0HRh03+pIh7zokpKLBSlLv0U0pv5ar:8RkQzy7zzpKLUlLcU0pv5ar`

## Runtime Data

### Usage (stdout):
```Batchfile
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
```Batchfile
Error 0x00000057 occurred:
The parameter is incorrect.


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUDITPOL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# auditpol

Displays information about and performs functions to manipulate audit policies, including:

- Setting and querying a system audit policy.

- Setting and querying a per-user audit policy.

- Setting and querying auditing options.

- Setting and querying the security descriptor used to delegate access to an audit policy.

- Reporting or backing up an audit policy to a comma-separated value (CSV) text file.

- Loading an audit policy from a CSV text file.

- Configuring global resource SACLs.

## Syntax

```
auditpol command [<sub-command><options>]
```

### Parameters

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

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


