---
title: takeown.exe | Takes ownership of a file
---

# takeown.exe 

* File Path: `C:\windows\SysWOW64\takeown.exe`
* Description: Takes ownership of a file
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `71F454FDDC36732FA5E0AC6B518DF41F`
SHA1 | `53826412BE30AC056784BD41F8B0622C040FA251`
SHA256 | `F844A4A3E020FE064218D65A0F26B2DB28A3D92FF10077FDE023454D3ADC8510`
SHA384 | `5E92D6ECCF81E4EE1F059A75F5B20FA2AD1A1FCFCBEE088CA7260075D466F22BEF490497F3FE5A432E1703D2C0E8845E`
SHA512 | `0B62796D9B3B79FD14AF96372CCDBBB7A1D95AD8833B42444E8DA49EABF564C47CDA1BF8489872190BC4C7DDC5EDF0022B414DB105E09FCB218FB593B499A668`
SSDEEP | `768:b3WdLtIMgAR8rJoxkqHsZIZS7l7I70WijBGE/YGmWf0hZ05TNm6GlyQXsxJLD6PZ:b3WMZNJhH7I7wb/YQM0VQLyQXsxJn6x`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\takeown.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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

*The following table contains possible examples of `takeown.exe` being misused. While `takeown.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_file_permission_modifications.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_file_permission_modifications.yml) | `          - '\takeown.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-macOS.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-macOS.misp.event.json) | `						"https:\/\/docs.microsoft.com\/windows-server\/administration\/windows-commands\/takeown",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #1: Take ownership using takeown utility [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #1: Take ownership using takeown utility [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | Adversaries can interact with the DACLs using built-in Windows commands, such as `icacls`, `takeown`, and `attrib`, which can grant adversaries higher permissions on specific files and folders. Further, [PowerShell](https://attack.mitre.org/techniques/T1059/001) provides cmdlets that can be used to retrieve or modify file and directory DACLs. Specific file and directory modifications may be a required step for many techniques, such as establishing Persistence via [Accessibility Features](https://attack.mitre.org/techniques/T1546/008), [Boot or Logon Initialization Scripts](https://attack.mitre.org/techniques/T1037), or tainting/hijacking other instrumental binary/configuration files via [Hijack Execution Flow](https://attack.mitre.org/techniques/T1574).</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | - [Atomic Test #1 - Take ownership using takeown utility](#atomic-test-1---take-ownership-using-takeown-utility) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | ## Atomic Test #1 - Take ownership using takeown utility | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | \| file_folder_to_own \| Path of the file or folder for takeown to take ownership. \| path \| %temp%&#92;T1222.001_takeown_folder\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | takeown.exe /f #{file_folder_to_own} /r | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## takeown

Enables an administrator to recover access to a file that previously was denied, by making the administrator the owner of the file.



### Syntax

```
takeown [/s <Computer> [/u [<Domain>\]<User name> [/p [<Password>]]]] /f <File name> [/a] [/r [/d {Y|N}]]
```

##### Parameters

|Parameter|Description|
|---------|-----------|
|/s \<Computer>|Specifies the name or IP address of a remote computer (do not use backslashes). The default value is the local computer. This parameter applies to all of the files and folders specified in the command.|
|/u [\<Domain>\]<User name>|Runs the script with the permissions of the specified user account. The default value is system permissions.|
|/p [\<Password>]|Specifies the password of the user account that is specified in the **/u** parameter.|
|/f \<File name>|Specifies the file name or directory name pattern. You can use the wildcard character * when specifying the pattern. You can also use the syntax *ShareName*\*FileName*.|
|/a|Gives ownership to the Administrators group instead of the current user.|
|/r|Performs a recursive operation on all files in the specified directory and subdirectories.|
|/d {Y \| N}|Suppresses the confirmation prompt that is displayed when the current user does not have the "List Folder" permission on a specified directory, and instead uses the specified default value. Valid values for the **/d** option are as follows:</br>-   Y: Take ownership of the directory.</br>-   N: Skip the directory.</br>Note that you must use this option in conjunction with the **/r** option.|
|/?|Displays help at the command prompt.|

### Remarks

-   This command is typically used in batch files.
-   If the **/a** parameter is not specified, file ownership is given to the user who is currently logged on to the computer.
-   Mixed patterns using (**?** and **&#42;**) are not supported by **takeown** command.
-   After deleting the lock with **takeown**, you might have to use Windows Explorer or the **cacls** command to give yourself full permissions to the files and directories before you can delete them. For more information about **cacls**, see "Additional References" at the end of this topic.

### <a name="BKMK_examples"></a>Examples

To take ownership of a file named Lostfile, type:
```
takeown /f lostfile
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


