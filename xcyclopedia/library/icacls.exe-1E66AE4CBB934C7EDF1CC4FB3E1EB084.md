---
title: icacls.exe | 
---

# icacls.exe 

* File Path: `C:\windows\system32\icacls.exe`

## Hashes

Type | Hash
-- | --
MD5 | `1E66AE4CBB934C7EDF1CC4FB3E1EB084`
SHA1 | `1E9932F74BF0F6C0A68731CFD5D2B45432D0810E`
SHA256 | `0DBEE1F682DB7A4E279261A3E24ACBB5CFA789196B85CCDE54A32B04B0465F63`
SHA384 | `3F36CBCDD33B0AD7739C1830B3A8406B91B20AFC0E48416832A6983A9E78DA1E9132A0047FA82F47DAE4396FD748E0DC`
SHA512 | `C03E2C6970D2A9745C9F8DD8AE24353D7FA67F48B4069B2935E2D87D185E050D4C53BB0F2F7412A5DEFC4D69AECDAFC374D48525B005A111AC1A523A6407E82F`
SSDEEP | `768:o4vGKXcHYhSCIbfe4BE5NnyP+vNiUGzDpoTBB6ElbyqiR+126C71Eq4Ha82aEu4h:pvfX432NmDuuEZyqiRh1X/Ds4A1K9`

## Signature

* Status: The file C:\windows\system32\icacls.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: iCACLS.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `icacls.exe` being misused. While `icacls.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_file_permission_modifications.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_file_permission_modifications.yml) | `          - '\icacls.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_wannacry.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_wannacry.yml) | `            - '*icacls * /grant Everyone:F /T /C /Q*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `            - icacls.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_process_creations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_process_creations.yml) | `            - icacls * /grant Everyone:F /T /C /Q` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-macOS.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-macOS.misp.event.json) | `						"https:\/\/docs.microsoft.com\/windows-server\/administration\/windows-commands\/icacls",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | Adversaries can interact with the DACLs using built-in Windows commands, such as `icacls`, `takeown`, and `attrib`, which can grant adversaries higher permissions on specific files and folders. Further, [PowerShell](https://attack.mitre.org/techniques/T1059/001) provides cmdlets that can be used to retrieve or modify file and directory DACLs. Specific file and directory modifications may be a required step for many techniques, such as establishing Persistence via [Accessibility Features](https://attack.mitre.org/techniques/T1546/008), [Boot or Logon Initialization Scripts](https://attack.mitre.org/techniques/T1037), or tainting/hijacking other instrumental binary/configuration files via [Hijack Execution Flow](https://attack.mitre.org/techniques/T1574).</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | Icacls.exe #{file_or_folder} /grant #{user_or_group}:F | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_blackenergy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_blackenergy.yar) | 		$s1 = "system32\\icacls.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keyboys.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keyboys.yar) |       $s5 = "icacls %s /grant administrators:F" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_wannacry.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_wannacry.yar) |       $x1 = "icacls . /grant Everyone:F /T /C /Q" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_wannacry.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_wannacry.yar) |       $x9 = "icacls . /grant Everyone:F /T /C /Q" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## icacls

Displays or modifies discretionary access control lists (DACLs) on specified files, and applies stored DACLs to files in specified directories.

> [!NOTE]
> This command replaces the deprecated [cacls command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/cacls.md).

### Syntax

```
icacls <filename> [/grant[:r] <sid>:<perm>[...]] [/deny <sid>:<perm>[...]] [/remove[:g|:d]] <sid>[...]] [/t] [/c] [/l] [/q] [/setintegritylevel <Level>:<policy>[...]]
icacls <directory> [/substitute <sidold> <sidnew> [...]] [/restore <aclfile> [/c] [/l] [/q]]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<filename>` | Specifies the file for which to display DACLs. |
| `<directory>` | Specifies the directory for which to display DACLs. |
| /t | Performs the operation on all specified files in the current directory and its subdirectories. |
| /c | Continues the operation despite any file errors. Error messages will still be displayed. |
| /l | Performs the operation on a symbolic link instead of its destination. |
| /q | Suppresses success messages. |
| [/save `<ACLfile>` [/t] [/c] [/l] [/q]] | Stores DACLs for all matching files into *ACLfile* for later use with **/restore**. |
| [/setowner `<username>` [/t] [/c] [/l] [/q]] | Changes the owner of all matching files to the specified user. |
| [/findsid `<sid>` [/t] [/c] [/l] [/q]] | Finds all matching files that contain a DACL explicitly mentioning the specified security identifier (SID). |
| [/verify [/t] [/c] [/l] [/q]] | Finds all files with ACLs that are not canonical or have lengths inconsistent with ACE (access control entry) counts. |
| [/reset [/t] [/c] [/l] [/q]] | Replaces ACLs with default inherited ACLs for all matching files. |
| [/grant[:r] \<sid>:<perm>[...]] | Grants specified user access rights. Permissions replace previously granted explicit permissions.<p>Not adding the **:r**, means that permissions are added to any previously granted explicit permissions. |
| [/deny \<sid>:<perm>[...]] | Explicitly denies specified user access rights. An explicit deny ACE is added for the stated permissions and the same permissions in any explicit grant are removed. |
| [/remove`[:g | :d]]` `<sid>`[...] [/t] [/c] [/l] [/q] | Removes all occurrences of the specified SID from the DACL. This command can also use:<ul><li>**:g** - Removes all occurrences of granted rights to the specified SID.</li><li>**:d** - Removes all occurrences of denied rights to the specified SID. |
| [/setintegritylevel [(CI)(OI)] `<Level>:<Policy>`[...]] | Explicitly adds an integrity ACE to all matching files. The level can be specified as:<ul><li>**l** - Low</li><li>**m**- Medium</li><li>**h** - High</li></ul>Inheritance options for the integrity ACE may precede the level and are applied only to directories. |
| [/substitute `<sidold> <sidnew>` [...]] | Replaces an existing SID (*sidold*) with a new SID (*sidnew*). Requires using with the `<directory>` parameter. |
| /restore `<ACLfile>` [/c] [/l] [/q] | Applies stored DACLs from `<ACLfile>` to files in the specified directory. Requires using with the `<directory>` parameter. |
| /inheritancelevel:`[e | d | r]` | Sets the inheritance level, which can be:<ul><li>**e** - Enables inheritance</li><li>**d** - Disables inheritance and copies the ACEs</li><li>**r** - Removes all inherited ACEs</li></ul> |

### Remarks

- SIDs may be in either numerical or friendly name form. If you use a numerical form, affix the wildcard character **&#42;** to the beginning of the SID.

- This command preserves the canonical order of ACE entries as:

    - Explicit denials

    -  Explicit grants

    - Inherited denials

    - Inherited grants

- The `<perm>` option is a permission mask that can be specified in one of the following forms:

    - A sequence of simple rights:

      - **F** - Full access

      - **M**- Modify access

      - **RX** - Read and execute access

      - **R** - Read-only access

      - **W** - Write-only access

    - A comma-separated list in parenthesis of specific rights:

      - **D** - Delete

      - **RC** - Read control

      - **WDAC** - Write DAC

      - **WO** - Write owner

      - **S** - Synchronize

      - **AS** - Access system security

      - **MA** - Maximum allowed

      - **GR** - Generic read

      - **GW** - Generic write

      - **GE** - Generic execute

      - **GA** - Generic all

      - **RD** - Read data/list directory

      - **WD** - Write data/add file

      - **AD** - Append data/add subdirectory

      - **REA** - Read extended attributes

      - **WEA** - Write extended attributes

      - **X** - Execute/traverse

      - **DC** - Delete child

      - **RA** - Read attributes

      - **WA** - Write attributes

  - Inheritance rights may precede either `<perm>` form, and they are applied only to directories:

      - **(OI)** - Object inherit

      - **(CI)** - Container inherit

      - **(IO)** - Inherit only

      - **(NP)** - Do not propagate inherit

### Examples

To save the DACLs for all files in the C:\Windows directory and its subdirectories to the ACLFile file, type:

```
icacls c:\windows\* /save aclfile /t
```

To restore the DACLs for every file within ACLFile that exists in the C:\Windows directory and its subdirectories, type:

```
icacls c:\windows\ /restore aclfile
```

To grant the user User1 Delete and Write DAC permissions to a file named Test1, type:

```
icacls test1 /grant User1:(d,wdac)
```

To grant the user defined by SID S-1-1-0 Delete and Write DAC permissions to a file, named Test2, type:

```
icacls test2 /grant *S-1-1-0:(d,wdac)
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


