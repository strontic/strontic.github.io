---
title: cacls.exe | Control ACLs Program
excerpt: What is cacls.exe?
---

# cacls.exe 

* File Path: `C:\Windows\system32\cacls.exe`
* Description: Control ACLs Program

## Hashes

Type | Hash
-- | --
MD5 | `A353590E06C976809F14906746109758`
SHA1 | `3E38480E52434F1E193D9C84B8BDC133C4BD10C2`
SHA256 | `D6E40B4ED7C0BC8AC18B15D265ED2EDAB9EFC260332EF0A98623F943BE3A43FA`
SHA384 | `75A1879BF22E076C12BC6EDB4EBF40604B78EC6C8D347CD1DE957B327187E61D9943BC18C2D9E36CA6D938D387DA3A5C`
SHA512 | `54A884652032040ACDA5C3A78D258BBE50362F77F2A3A364A8819CF8263282FCB21E35D7293EB62202EA82E96B5994FD072356D310DF3037BEC6A61C221796A6`
SSDEEP | `768:gOkLr2hyZByocltC8L90CoWbR+B9/d9gWh4i/6rWaDbGXlF:gBLr2hOkzL90CoK+BRd95hmDbGXlF`
IMP | `30254A514CD61AB9D483307AA5A195E8`
PESHA1 | `FE772B355E1733B1F8E1954C44BDBCC10DAC6621`
PE256 | `A6EC74EDD825EC6EE28F6A74A8CBFCA102A994AABF560EA2F4D578E04A251641`

## Runtime Data

### Usage (stdout):
```cmhg

 NOTE: Cacls is now deprecated, please use Icacls.

 Displays or modifies access control lists (ACLs) of files

 CACLS filename [/T] [/M] [/L] [/S[:SDDL]] [/E] [/C] [/G user:perm]
        [/R user [...]] [/P user:perm [...]] [/D user [...]]
    filename      Displays ACLs.
    /T            Changes ACLs of specified files in
                  the current directory and all subdirectories.
    /L            Work on the Symbolic Link itself versus the target
    /M            Changes ACLs of volumes mounted to a directory
    /S            Displays the SDDL string for the DACL.
    /S:SDDL       Replaces the ACLs with those specified in the SDDL string
                  (not valid with /E, /G, /R, /P, or /D).
    /E            Edit ACL instead of replacing it.
    /C            Continue on access denied errors.
    /G user:perm  Grant specified user access rights.
                  Perm can be: R  Read
                               W  Write
                               C  Change (write)
                               F  Full control
    /R user       Revoke specified user's access rights (only valid with /E).
    /P user:perm  Replace specified user's access rights.
                  Perm can be: N  None
                               R  Read
                               W  Write
                               C  Change (write)
                               F  Full control
    /D user       Deny specified user access.
 Wildcards can be used to specify more than one file in a command.
 You can specify more than one user in a command.

 Abbreviations:
    CI - Container Inherit.
         The ACE will be inherited by directories.
    OI - Object Inherit.
         The ACE will be inherited by files.
    IO - Inherit Only.
         The ACE does not apply to the current file/directory.
    ID - Inherited.
         The ACE was inherited from the parent directory's ACL.

```

### Usage (stderr):
```cmhg
The system cannot find the file specified.

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\cacls.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CACLS.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/d6e40b4ed7c0bc8ac18b15d265ed2edab9efc260332ef0a98623f943be3a43fa/detection


## Possible Misuse

*The following table contains possible examples of `cacls.exe` being misused. While `cacls.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_file_permission_modifications.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_file_permission_modifications.yml) | `- '\cacls.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_hiding_malware_in_fonts_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_hiding_malware_in_fonts_folder.yml) | `CommandLine\|re: '(?i).*(echo\|copy\|type\|file createnew\|cacls).*C:\\\\Windows\\\\Fonts\\\\.*(.sh\|.exe\|.dll\|.bin\|.bat\|.cmd\|.js\|.msh\|.reg\|.scr\|.ps\|.vb\|.jar\|.pl\|.inf\|.cpl\|.hta\|.msi\|.vbs).*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: cacls - Grant permission to specified user or group recursively [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: cacls - Grant permission to specified user or group recursively [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | Adversaries can interact with the DACLs using built-in Windows commands, such as `icacls`, `cacls`, `takeown`, and `attrib`, which can grant adversaries higher permissions on specific files and folders. Further, [PowerShell](https://attack.mitre.org/techniques/T1059/001) provides cmdlets that can be used to retrieve or modify file and directory DACLs. Specific file and directory modifications may be a required step for many techniques, such as establishing Persistence via [Accessibility Features](https://attack.mitre.org/techniques/T1546/008), [Boot or Logon Initialization Scripts](https://attack.mitre.org/techniques/T1037), or tainting/hijacking other instrumental binary/configuration files via [Hijack Execution Flow](https://attack.mitre.org/techniques/T1574).</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | - [Atomic Test #2 - cacls - Grant permission to specified user or group recursively](#atomic-test-2---cacls---grant-permission-to-specified-user-or-group-recursively) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | ## Atomic Test #2 - cacls - Grant permission to specified user or group recursively | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s1 = "cacls %s /t /c /e /r administrators" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

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



MIT License. Copyright (c) 2020-2021 Strontic.


