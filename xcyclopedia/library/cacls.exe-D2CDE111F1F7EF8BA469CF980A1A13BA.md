---
title: cacls.exe | Control ACLs Program
---

# cacls.exe 

* File Path: `C:\windows\system32\cacls.exe`
* Description: Control ACLs Program

## Hashes

Type | Hash
-- | --
MD5 | `D2CDE111F1F7EF8BA469CF980A1A13BA`
SHA1 | `3201E01B40878FBBFFE5D330085154AD1BDF047B`
SHA256 | `4162FAF99C4FD924AC71151CE344F38EECD424CEFA1B6B9018A22B44A9532BAC`
SHA384 | `A71D6AAE1366FEDF266BA8892A10FDB69CA9E5D3D307E34DCFA1BB4747AA79C023A47BCA9FC7CB3ADB80A104987430CD`
SHA512 | `5DE1FD8C9DD222CB684AF49BCE3A60E79B9C1475AEBE31BD49174B5A07DA04BFFB3E267626818E05D8387C7871ACC2AC61A885ED7578939E9E4D5475810BC257`
SSDEEP | `768:X/+XpZXwy9nTbf4xjo4ZRGQnDR+rOk7HPNLjiauu3r2AQ2ov:XWTXwATsxs4LGvPN4AQ2ov`

## Signature

* Status: The file C:\windows\system32\cacls.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: CACLS.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `cacls.exe` being misused. While `cacls.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_file_permission_modifications.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_file_permission_modifications.yml) | `- '\cacls.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #2: cacls - Grant permission to specified user or group recursively [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #2: cacls - Grant permission to specified user or group recursively [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | - [Atomic Test #2 - cacls - Grant permission to specified user or group recursively](#atomic-test-2---cacls---grant-permission-to-specified-user-or-group-recursively) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | ## Atomic Test #2 - cacls - Grant permission to specified user or group recursively | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | 		$s1 = "cacls %s /t /c /e /r administrators" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## cacls

>[!IMPORTANT]
> This command has been deprecated. Please use [icacls](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/icacls.md) instead.

Displays or modifies discretionary access control lists (DACL) on specified files.

### Syntax

```
cacls <filename> [/t] [/m] [/l] [/s[:sddl]] [/e] [/c] [/g user:<perm>] [/r user [...]] [/p user:<perm> [...]] [/d user [...]]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<filename>` | Required. Displays ACLs of specified files. |
| /t | Changes ACLs of specified files in the current directory and all subdirectories. |
| /m | Changes ACLs of volumes mounted to a directory. |
| /l | Works on the Symbolic Link itself instead of the target. |
| /s:sddl | Replaces the ACLs with those specified in the SDDL string. This parameter is not valid for use with the **/e**, **/g**, **/r**, **/p**, or **/d** parameters. |
| /e | Edit an ACL instead of replacing it. |
| /c | Continue after access denied errors. |
| `/g user:<perm>` | Grants specified user access rights, including these valid values for permission:<ul><li>**n** - None</li><li>**r** - Read</li><li>**w** - Write</li><li>**c** - Change (write)</li><li>**f** - Full control</li></ul> |
| /r user [...] | Revoke specified user's access rights. Only valid when used with the **/e** parameter. |
| `[/p user:<perm> [...]` | Replace specified user's access rights, including these valid values for permission:<ul><li>**n** - None</li><li>**r** - Read</li><li>**w** - Write</li><li>**c** - Change (write)</li><li>**f** - Full control</li></ul> |
| [/d user [...] | Deny specified user access. |
| /? | Displays help at the command prompt. |

##### Sample output

| Output | Access control entry (ACE) applies to |
-------- | ------------------------------------- |
| OI | Object inherit. This folder and files. |
| CI | Container inherit. This folder and subfolders. |
| IO | Inherit only. The ACE does not apply to the current file/directory. |
| No output message | This folder only. |
| (OI)(CI) | This folder, subfolders, and files. |
| (OI)(CI)(IO) | Subfolders and files only. |
| (CI)(IO) | Subfolders only. |
| (OI)(IO) | Files only. |

##### Remarks

- You can use wildcards (**?** and **&#42;**) to specify multiple files.

- You can specify more than one user.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [icacls](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/icacls.md)

---



MIT License. Copyright (c) 2020 Strontic.


