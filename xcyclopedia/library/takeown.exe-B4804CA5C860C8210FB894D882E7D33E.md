---
title: takeown.exe | Takes ownership of a file
excerpt: What is takeown.exe?
---

# takeown.exe 

* File Path: `C:\windows\system32\takeown.exe`
* Description: Takes ownership of a file

## Hashes

Type | Hash
-- | --
MD5 | `B4804CA5C860C8210FB894D882E7D33E`
SHA1 | `9DFD43D1F1FA46553C32419567B4BF5017C43258`
SHA256 | `26B3DD8E0FD18190144EF1DDB2ED08AFFEAB2BCD1A218E091DB5671010AF4AF7`
SHA384 | `23DB5E621872322BC4A291D9B4D42B10617D7A680E203D61B5B6A6F4CDE8D513A60501E1C6ADA9B318EA72FDF275314F`
SHA512 | `10DF193F2D0113E217C80965FE149BEFFA128DF513CF68C69FCC428371CA40A652CFBCB39B02B2319BC39D6B185015F2F1B17E197C24054C3A802ACB459148CA`
SSDEEP | `1536:/nGSpfE65t75MbF8o4cbxnzuttd/Gbrj3VKMV7bvVQX4xQq:zR395MbFZzuB83VjQX4xL`

## Signature

* Status: The file C:\windows\system32\takeown.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: takeown.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `takeown.exe` being misused. While `takeown.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_file_permission_modifications.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_file_permission_modifications.yml) | `- '\takeown.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-macOS.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-macOS.misp.event.json) | `"https:\/\/docs.microsoft.com\/windows-server\/administration\/windows-commands\/takeown",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Take ownership using takeown utility [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Take ownership using takeown utility [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | Adversaries can interact with the DACLs using built-in Windows commands, such as `icacls`, `cacls`, `takeown`, and `attrib`, which can grant adversaries higher permissions on specific files and folders. Further, [PowerShell](https://attack.mitre.org/techniques/T1059/001) provides cmdlets that can be used to retrieve or modify file and directory DACLs. Specific file and directory modifications may be a required step for many techniques, such as establishing Persistence via [Accessibility Features](https://attack.mitre.org/techniques/T1546/008), [Boot or Logon Initialization Scripts](https://attack.mitre.org/techniques/T1037), or tainting/hijacking other instrumental binary/configuration files via [Hijack Execution Flow](https://attack.mitre.org/techniques/T1574).</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | - [Atomic Test #1 - Take ownership using takeown utility](#atomic-test-1---take-ownership-using-takeown-utility) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | ## Atomic Test #1 - Take ownership using takeown utility | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | \| file_folder_to_own \| Path of the file or folder for takeown to take ownership. \| Path \| %temp%&#92;T1222.001_takeown_folder\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | takeown.exe /f #{file_folder_to_own} /r | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | takeown /F C:\Windows\System32\sethc.exe /A | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_scripts.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_scripts.yar) | $s1 = "success = obj.run(\"cmd /c takeown /f %SystemRoot%\\system32\\sethc.exe&echo y\| " ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## takeown

Enables an administrator to recover access to a file that previously was denied, by making the administrator the owner of the file. This command is typically used on batch files.

### Syntax

```
takeown [/s <computer> [/u [<domain>\]<username> [/p [<password>]]]] /f <filename> [/a] [/r [/d {Y|N}]]
```

#### Parameters

| Parameter | Description |
|--|--|
| /s `<computer>` | Specifies the name or IP address of a remote computer (do not use backslashes). The default value is the local computer. This parameter applies to all of the files and folders specified in the command. |
| /u `[<domain>\]<username>` | Runs the script with the permissions of the specified user account. The default value is system permissions. |
| /p `[<[password>]` | Specifies the password of the user account that is specified in the **/u** parameter. |
| /f `<filename>` | Specifies the file name or directory name pattern. You can use the wildcard character `*` when specifying the pattern. You can also use the syntax `<sharename>\<filename>`. |
| /a | Gives ownership to the Administrators group instead of the current user. If you don't specify this option, file ownership is given to the user who is currently logged on to the computer. |
| /r | Performs a recursive operation on all files in the specified directory and subdirectories. |
| /d `{Y | N}` | Suppresses the confirmation prompt that is displayed when the current user does not have the **List Folder** permission on a specified directory, and instead uses the specified default value. Valid values for the **/d** option are:<ul><li>**Y** - Take ownership of the directory.</li><li>**N** - Skip the directory.<p>**NOTE**<br>You must use this option in conjunction with the **/r** option.</li></ul> |
| /? | Displays help at the command prompt. |

### Remarks

- Mixed patterns using (**?** and **&#42;**) aren't supported by **takeown** command.

- After deleting the lock with **takeown**, you might have to use Windows Explorer to give yourself full permissions to the files and directories before you can delete them.

### Examples

To take ownership of a file named *Lostfile*, type:

```
takeown /f lostfile
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


