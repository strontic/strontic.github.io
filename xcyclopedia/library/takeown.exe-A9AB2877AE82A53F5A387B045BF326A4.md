---
title: takeown.exe | Takes ownership of a file
---

# takeown.exe 

* File Path: `C:\Windows\SysWOW64\takeown.exe`
* Description: Takes ownership of a file

## Hashes

Type | Hash
-- | --
MD5 | `A9AB2877AE82A53F5A387B045BF326A4`
SHA1 | `4FA3F15D369947026DC7BC6BA5283159B761F568`
SHA256 | `C7159144C6403C38AAF3DEF4C2FC5759B6DF824AF003B304D4B77C6D72353B3E`
SHA384 | `9ABE3D2C7B452D76F54DF32FCE67F39D4D25C3F67EF68AF107582F74DEC5964EB7A60D342FBF5BA3390B7B35C43AB378`
SHA512 | `4674B650BFF29D90758D1964620C7FD5889B489C515362C236D91C05DAF4BC4A5BDCEF9F9C0C011E51350DA3A74D394CA98BAD06D18FDB937DA76F8A87EF3214`
SSDEEP | `1536:U3WcvOYMd57IAB/R0CO9derpMkT2MVd17ihh4SpWfbZay0d:SOYM/7hRVmc20liLVpObZaTd`

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

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\takeown.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: takeown.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
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
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_scripts.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_scripts.yar) |         $s1 = "success = obj.run(\"cmd /c takeown /f %SystemRoot%\\system32\\sethc.exe&echo y\| " ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

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


