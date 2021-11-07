---
title: help.exe | GNU Image Manipulation Program Plug-In
excerpt: What is help.exe?
---

# help.exe 

* File Path: `C:\program files\GIMP 2\lib\gimp\2.0\plug-ins\help\help.exe`
* Description: GNU Image Manipulation Program Plug-In

## Hashes

Type | Hash
-- | --
MD5 | `A2655899AC3239006F5BEC0E3F4CF540`
SHA1 | `ECC4C730AF265FBF81207155F438954462B9741F`
SHA256 | `A0749BF24AFC684F41A3CEAF99CC13ED0CDB183F8B660ACE18ADA9E794763ABA`
SHA384 | `3CCB634F322EAE15DF7FAE0C75F9036F1221A3D279526E81B2264FDC217353136CE891F0DEBA1FE6DBDB77E232473FE0`
SHA512 | `DC0F4CC259B3893C46C7A43D6AF6BF9A5A4736ACF66441B72667402AF688E905AE1E1DA277C5ACA7A1DCB7E8403A01F63E0579F09C3D130A612B4F35B021F4F9`
SSDEEP | `1536:mddbJ3eNXZVbJ7tG0gvIGIh/jJgaipiPWxaiocPWXi1:mHbJuNX/97t7GIh/9gfmO6cPgQ`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user\Documents | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\program files\GIMP 2\lib\gimp\2.0\plug-ins\help\help.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `00E7E6FE263192D15EAC485B4198E64488`
* Thumbprint: `3A427356A24983C1C8211C07CF766D4726A33E4F`
* Issuer: CN=COMODO RSA Code Signing CA, O=COMODO CA Limited, L=Salford, S=Greater Manchester, C=GB
* Subject: CN=Jernej Simoni, O=Jernej Simoni, STREET=Herbersteinova 29, L=Ljubljana, S=-, PostalCode=1000, C=SI

## File Metadata

* Original Filename: help.exe
* Product Name: GNU Image Manipulation Program
* Company Name: Spencer Kimball, Peter Mattis and the GIMP Development Team
* File Version: 2.10.20.0
* Product Version: 2.10.20
* Language: English (United States)
* Legal Copyright: Copyright  1995-2020


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\GIMP 2\lib\gimp\2.0\plug-ins\file-html-table\file-html-table.exe](file-html-table.exe-E87646D24FEF13BE6F8027CAEA7D8C8C.md) | 49


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## help

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays a list of the available commands or detailed help information on a specified command. If used without parameters, **help** lists and briefly describes every system command.

### Syntax

```
help [<command>]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<command>` | Specifies the command for which to display detailed help information. |

#### Examples

To view information about the **robocopy** command, type:

```
help robocopy
```

To display a list of all commands available in DiskPart, type:

```
help
```

To display detailed help information about how to use the **create partition primary** command in DiskPart, type:

```
help create partition primary
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


