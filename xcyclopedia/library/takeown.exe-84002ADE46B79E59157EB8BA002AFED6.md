---
title: takeown.exe | Takes ownership of a file
excerpt: What is takeown.exe?
---

# takeown.exe 

* File Path: `C:\Windows\SysWOW64\takeown.exe`
* Description: Takes ownership of a file

## Hashes

Type | Hash
-- | --
MD5 | `84002ADE46B79E59157EB8BA002AFED6`
SHA1 | `293352BE936E3BFAA18DD9D5BFA779C8B1DC19EE`
SHA256 | `5C865D2D1012EBF9F2503F06F2C4B8AFCCAE063D1E79421E0244E0CF627E5FF1`
SHA384 | `D31413305D3411F81F062A9CCBC448AAF8ADE72BA6F0EA67A12F6F9BAA68495E4E15B0436B47072F87880D67ACD2CC2C`
SHA512 | `21774ED290C644EE988F30BA65CDDC9CCF43905698519CFB6E991F7DB3E52F7DC77424A47292F402916BEB619F9958EE204469BE9A850F72774F2DB229083B24`
SSDEEP | `1536:W3W7Cpl/5zR3jkNT1Gf4jViqfPpWfJZaFf6:HUjm0YVi4PpOJZal`
IMP | `3EFF225872A4BFF594AF402A5BBCC6F4`
PESHA1 | `6AB04561E19BA177F0EA23D3BAD23FCEA2E86DCB`
PE256 | `699C07704014D7115430F5FF347C719266113B08336E8CCD72704EE881A63B95`

## Runtime Data

### Usage (stdout):
```cmhg

TAKEOWN [/S system [/U username [/P [password]]]]
        /F filename [/A] [/R [/D prompt]]

Description:
    This tool allows an administrator to recover access to a file that
    was denied by re-assigning file ownership.

Parameter List: 
    /S           system          Specifies the remote system to
                                 connect to.

    /U           [domain\]user   Specifies the user context under
                                 which the command should execute.

    /P           [password]      Specifies the password for the
                                 given user context.
                                 Prompts for input if omitted.

    /F           filename        Specifies the filename or directory
                                 name pattern. Wildcard "*" can be used
                                 to specify the pattern. Allows
                                 sharename\filename.

    /A                           Gives ownership to the administrators
                                 group instead of the current user.

    /R                           Recurse: instructs tool to operate on
                                 files in specified directory and all 
                                 subdirectories.

    /D           prompt          Default answer used when the current user
                                 does not have the "list folder" permission
                                 on a directory.  This occurs while operating
                                 recursively (/R) on sub-directories. Valid 
                                 values "Y" to take ownership or "N" to skip.

    /SKIPSL                      Do not follow symbolic links.
                                 Only applicable with /R.

    /?                           Displays this help message.

    NOTE: 1) If /A is not specified, file ownership will be given to the
             current logged on user.

          2) Mixed patterns using "?" and "*" are not supported.

          3) /D is used to suppress the confirmation prompt.

Examples: 
    TAKEOWN /?
    TAKEOWN /F lostfile
    TAKEOWN /F \\system\share\lostfile /A
    TAKEOWN /F directory /R /D N
    TAKEOWN /F directory /R /A
    TAKEOWN /F *
    TAKEOWN /F C:\Windows\System32\acme.exe
    TAKEOWN /F %windir%\*.txt
    TAKEOWN /S system /F MyShare\Acme*.doc
    TAKEOWN /S system /U user /F MyShare\MyBinary.dll
    TAKEOWN /S system /U domain\user /P password /F share\filename
    TAKEOWN /S system /U user /P password /F Doc\Report.doc /A
    TAKEOWN /S system /U user /P password /F Myshare\* 
    TAKEOWN /S system /U user /P password /F Home\Logon /R
    TAKEOWN /S system /U user /P password /F Myshare\directory /R /A

```

### Usage (stderr):
```cmhg
ERROR: Invalid argument/option - '--help'.
Type "TAKEOWN /?" for usage.

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: takeown.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/5c865d2d1012ebf9f2503f06f2c4b8afccae063d1e79421e0244e0cf627e5ff1/detection/


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
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | \| file_folder_to_own \| Path of the file or folder for takeown to take ownership. \| path \| %temp%&#92;T1222.001_takeown_folder\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
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


