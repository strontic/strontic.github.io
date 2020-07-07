---
title: regini.exe | Registry Initializer
---

# regini.exe 

* File Path: `C:\windows\SysWOW64\regini.exe`
* Description: Registry Initializer
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `50752D2AEDF0E27FF7EFCA584755A203`
SHA1 | `8003285582FB19C7018242FB2CA2FE78D0521774`
SHA256 | `CED97AC768997B34FC37E4661E66EBF3D253CB068931BB4F2FAF1DDDED3016DC`
SHA384 | `1C885CE9E74CB85377736A455CE05315399BD8BC597C533FF1DE650351D19F6084BB881802D4F6BD3DDE5C12BDED0EA1`
SHA512 | `3F16540C12F416651D3D3BFA13D6B2825E2CB327AD73D993D1F756E565BB79CF03961F39C5BDC5017BBE2D021764D6ACC839D9B2C0FC6EFCFA7BF37C59B6D695`
SSDEEP | `768:HvGV2EIgkhyilb1143tN37BR2BTyOd78DNeo+ERHCQhBhT1dGt2:H5Ec43tN37ATy678ReojRHCQJHGt2`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\regini.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: REGINI.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\regini.exe](regini.exe-075434A31ACB3954337BE18A1B336B87.md) | 43
[C:\Windows\SysWOW64\regini.exe](regini.exe-8E9CB202467E209A7C4C5C15A7727DA2.md) | 35
[C:\WINDOWS\SysWOW64\regini.exe](regini.exe-92D7CDD79F53E56612F8252B1BCD562E.md) | 36
[C:\Windows\SysWOW64\regini.exe](regini.exe-C99C3BB423097FCF4990539FC1ED60E3.md) | 40

## Possible Misuse

*The following table contains possible examples of `regini.exe` being misused. While `regini.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regini.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regini.yml) | `Name: Regini.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regini.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regini.yml) | `  - Command: regini.exe newfile.txt:hidden.ini` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regini.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regini.yml) | `  - Path: C:\Windows\System32\regini.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regini.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regini.yml) | `  - Path: C:\Windows\SysWOW64\regini.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regini.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regini.yml) | ` - IOC: regini.exe reading from ADS` | 

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## regini

Modifies the registry from the command line or a script, and applies changes that were preset in one or more text files. You can create, modify, or delete registry keys, in addition to modifying the permissions on the registry keys.

For details on the format and content of the text script file that regini.exe uses to make changes to the registry, see [How to change registry values or permissions from a command line or a script](https://support.microsoft.com/help/264584/how-to-change-registry-values-or-permissions-from-a-command-line-or-a).

### Syntax

```
regini [-m \\machinename | -h hivefile hiveroot][-i n] [-o outputwidth][-b] textfiles...
```

#### Parameters

| Parameter | Description |
|--|--|
| -m `<\\computername>` | Specifies the remote computer name with a registry that is to be modified. Use the format **\\ComputerName**. |
| -h `<hivefile hiveroot>` | Specifies the local registry hive to modify. You must specify the name of the hive file and the root of the hive in the format **hivefile hiveroot**. |
| -i `<n>` | Specifies the level of indentation to use to indicate the tree structure of registry keys in the command output. The **regdmp.exe** tool (which gets a registry key's current permissions in binary format) uses indentation in multiples of four, so the default value is **4**. |
| -o `<outputwidth>` | Specifies the width of the command output, in characters. If the output will appear in the command window, the default value is the width of the window. If the output is directed to a file, the default value is **240** characters. |
| -b | Specifies that **regini.exe** output is backward compatible with previous versions of **regini.exe**. |
| textfiles | Specifies the name of one or more text files that contain registry data. Any number of ANSI or Unicode text files can be listed. |

##### Remarks

The following guidelines apply primarily to the content of the text files that contain registry data that you apply by using **regini.exe**.

- Use the semicolon as an end-of-line comment character. It must be the first non-blank character in a line.

- Use the backslash to indicate continuation of a line. The command will ignore all characters from the backslash up to (but not including) the first non-blank character of the next line. If you include more than one space before the backslash, it is replaced by a single space.

- Use hard-tab characters to control indentation. This indentation indicates the tree structure of the registry keys; however, these characters are converted to a single space regardless of their position.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


