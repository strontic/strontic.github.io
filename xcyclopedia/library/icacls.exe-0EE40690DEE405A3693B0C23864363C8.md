---
title: icacls.exe | 
---

# icacls.exe 

* File Path: `C:\Windows\system32\icacls.exe`

## Hashes

Type | Hash
-- | --
MD5 | `0EE40690DEE405A3693B0C23864363C8`
SHA1 | `350BC92A74D022CE0EC7C613ED3F66040CD61DBC`
SHA256 | `8DFC26EEFC94BD4FA35736444D8D9703AA2D3802D17896835F9EA9DE136A68C8`
SHA384 | `CF6F4A40C1C6566DB8DD9AA4DD6FE30E2D393B69CB195769A983DA16FB13DB1CF368FD3BCED574DCF13EFB48E8086051`
SHA512 | `6D1559AAF57C2D706DCFFA0D9BA5B646D089225ACB2963D00281731B1FBDEE01A3FB5CB9093F741FC6323605554EF893B54F4DFBC7DE9646AF59C10CD812446D`
SSDEEP | `768:ZKohWnN0KvXGp55EaT6b0HCKp1KnrUEg84TWMsrk:woU/ZKp1KrUEgHTWMEk`

## Runtime Data

### Usage (stdout):
```cmhg

ICACLS name /save aclfile [/T] [/C] [/L] [/Q]
    stores the DACLs for the files and folders that match the name
    into aclfile for later use with /restore. Note that SACLs,
    owner, or integrity labels are not saved.

ICACLS directory [/substitute SidOld SidNew [...]] /restore aclfile
                 [/C] [/L] [/Q]
    applies the stored DACLs to files in directory.

ICACLS name /setowner user [/T] [/C] [/L] [/Q]
    changes the owner of all matching names. This option does not
    force a change of ownership; use the takeown.exe utility for
    that purpose.

ICACLS name /findsid Sid [/T] [/C] [/L] [/Q]
    finds all matching names that contain an ACL
    explicitly mentioning Sid.

ICACLS name /verify [/T] [/C] [/L] [/Q]
    finds all files whose ACL is not in canonical form or whose
    lengths are inconsistent with ACE counts.

ICACLS name /reset [/T] [/C] [/L] [/Q]
    replaces ACLs with default inherited ACLs for all matching files.

ICACLS name [/grant[:r] Sid:perm[...]]
       [/deny Sid:perm [...]]
       [/remove[:g|:d]] Sid[...]] [/T] [/C] [/L] [/Q]
       [/setintegritylevel Level:policy[...]]

    /grant[:r] Sid:perm grants the specified user access rights. With :r,
        the permissions replace any previously granted explicit permissions.
        Without :r, the permissions are added to any previously granted
        explicit permissions.

    /deny Sid:perm explicitly denies the specified user access rights.
        An explicit deny ACE is added for the stated permissions and
        the same permissions in any explicit grant are removed.

    /remove[:[g|d]] Sid removes all occurrences of Sid in the ACL. With
        :g, it removes all occurrences of granted rights to that Sid. With
        :d, it removes all occurrences of denied rights to that Sid.

    /setintegritylevel [(CI)(OI)]Level explicitly adds an integrity
        ACE to all matching files.  The level is to be specified as one
        of:
            L[ow]
            M[edium]
            H[igh]
        Inheritance options for the integrity ACE may precede the level
        and are applied only to directories.

    /inheritance:e|d|r
        e - enables inheritance
        d - disables inheritance and copy the ACEs
        r - remove all inherited ACEs


Note:
    Sids may be in either numerical or friendly name form. If a numerical
    form is given, affix a * to the start of the SID.

    /T indicates that this operation is performed on all matching
        files/directories below the directories specified in the name.

    /C indicates that this operation will continue on all file errors.
        Error messages will still be displayed.

    /L indicates that this operation is performed on a symbolic link
       itself versus its target.

    /Q indicates that icacls should suppress success messages.

    ICACLS preserves the canonical ordering of ACE entries:
            Explicit denials
            Explicit grants
            Inherited denials
            Inherited grants

    perm is a permission mask and can be specified in one of two forms:
        a sequence of simple rights:
                N - no access
                F - full access
                M - modify access
                RX - read and execute access
                R - read-only access
                W - write-only access
                D - delete access
        a comma-separated list in parentheses of specific rights:
                DE - delete
                RC - read control
                WDAC - write DAC
                WO - write owner
                S - synchronize
                AS - access system security
                MA - maximum allowed
                GR - generic read
                GW - generic write
                GE - generic execute
                GA - generic all
                RD - read data/list directory
                WD - write data/add file
                AD - append data/add subdirectory
                REA - read extended attributes
                WEA - write extended attributes
                X - execute/traverse
                DC - delete child
                RA - read attributes
                WA - write attributes
        inheritance rights may precede either form and are applied
        only to directories:
                (OI) - object inherit
                (CI) - container inherit
                (IO) - inherit only
                (NP) - don't propagate inherit
                (I) - permission inherited from parent container

Examples:

        icacls c:\windows\* /save AclFile /T
        - Will save the ACLs for all files under c:\windows
          and its subdirectories to AclFile.

        icacls c:\windows\ /restore AclFile
        - Will restore the Acls for every file within
          AclFile that exists in c:\windows and its subdirectories.

        icacls file /grant Administrator:(D,WDAC)
        - Will grant the user Administrator Delete and Write DAC
          permissions to file.

        icacls file /grant *S-1-1-0:(D,WDAC)
        - Will grant the user defined by sid S-1-1-0 Delete and
          Write DAC permissions to file.

```

### Usage (stderr):
```cmhg
First parameter must be a file name pattern or "/?"

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\icacls.exe |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: iCACLS.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `icacls.exe` being misused. While `icacls.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_file_permission_modifications.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_file_permission_modifications.yml) | `- '\icacls.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_wannacry.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_wannacry.yml) | `- '*icacls * /grant Everyone:F /T /C /Q*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- icacls.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_process_creations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_process_creations.yml) | `- icacls * /grant Everyone:F /T /C /Q` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-macOS.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-macOS.misp.event.json) | `"https:\/\/docs.microsoft.com\/windows-server\/administration\/windows-commands\/icacls",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
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


