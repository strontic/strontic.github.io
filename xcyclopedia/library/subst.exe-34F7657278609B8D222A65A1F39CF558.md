---
title: subst.exe | Subst Utility
excerpt: What is subst.exe?
---

# subst.exe 

* File Path: `C:\windows\SysWOW64\subst.exe`
* Description: Subst Utility

## Hashes

Type | Hash
-- | --
MD5 | `34F7657278609B8D222A65A1F39CF558`
SHA1 | `E19309EC638FEBC036931BB5DAFDD62E08B26E68`
SHA256 | `51CD26A60D77B16D7BF4458FB5E54BA7C4D1F3B0DF3DE51BB95391B54DA33C21`
SHA384 | `394A32F69EB024C75FD294D3A81C232A62B9EB52B083966088F7D09D90662DF074DD294C9505AA5912CC6E794AF6FC07`
SHA512 | `E536DA509AE164CA38988C3F6C00C31A247601ACDBBE11FE0766E348A6D5CAFFC2B4A22A2897CD91D8FB3366A668177AAE5B261E1A1C1F8E5715D9BA1D000185`
SSDEEP | `192:Wb31kuD4DXqBWoktCTgOWmBC6yGZdfp3oQkpWxGWkyMh2aH:oKuD0XqEWgRmRyGnfEpWxGWkHh`

## Signature

* Status: The file C:\windows\SysWOW64\subst.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: Subst.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## subst

Associates a path with a drive letter. If used without parameters, **subst** displays the names of the virtual drives in effect.

### Syntax

```
subst [<drive1>: [<drive2>:]<path>]
subst <drive1>: /d
```

#### Parameters

| Parameter | Description |
|--|--|
| `<drive1>:` | Specifies the virtual drive to which you want to assign a path. |
| `[<drive2>:]<path>` | Specifies the physical drive and path that you want to assign to a virtual drive. |
| /d | Deletes a substituted (virtual) drive. |
| /? | Displays help at the command prompt. |

### Remarks

- The following commands don't work and must not be used on drives specified in the **subst** command:

  - [chkdsk command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/chkdsk.md)

    [diskcomp command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/diskcomp.md)

    [diskcopy command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/diskcopy.md)

    [format command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/format.md)

    [label command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/label.md)

    [recover command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/recover.md)

- The `<drive1>` parameter must be within the range that is specified by the **lastdrive** command. If not, **subst** displays the following error message: `Invalid parameter - drive1:`

### Examples

To create a virtual drive z for the path b:\user\betty\forms, type:

```
subst z: b:\user\betty\forms
```

Instead of typing the full path, you can reach this directory by typing the letter of the virtual drive followed by a colon as follows:

```
z:
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


