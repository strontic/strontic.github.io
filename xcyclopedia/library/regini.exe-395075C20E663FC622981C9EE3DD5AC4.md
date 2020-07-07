---
title: regini.exe | Registry Initializer
---

# regini.exe 

* File Path: `C:\windows\system32\regini.exe`
* Description: Registry Initializer
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `395075C20E663FC622981C9EE3DD5AC4`
SHA1 | `10CECDFC4159487546BC64CED37BAA84E653B482`
SHA256 | `A5D8218A742A01F72799F89D12A7CDD55FECA4C01853CA4EF0B55D5C2DBB569F`
SHA384 | `A2B90427F932BF1FB7D7DC78D4EB6A62743D09E77EAF049BE8446DB144764FB80EB98718A13B98FF158562F6D388B943`
SHA512 | `49FA77E0547B028A0F27F4B4AEDC97E1732B4E2CBA66199D793D2968E5464948E2902BF1FB2791E7591AAFA070A3617D41553C724F27D724D20EFCFEFE234F22`
SSDEEP | `768:SPGlVogExyylLJs04JcSfnWB3I6I/4cMo2dJ3gf1HmSjNJTHLPT4unrunr7FSjTm:SpUl0JkWl6/4tdKDLTFUHI3m`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\regini.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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
[C:\Windows\system32\regini.exe](regini.exe-28CA983582606E250402D02510A2C1F8.md) | 25
[C:\Windows\system32\regini.exe](regini.exe-3C91C37CE39EF6C3E6776B286EF7C295.md) | 24
[C:\WINDOWS\system32\regini.exe](regini.exe-5FB1FD7CBF411D45F2BE175941307995.md) | 25
[C:\Windows\system32\regini.exe](regini.exe-EAF2E449CAEC0FF310376373C5B993C9.md) | 21

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


