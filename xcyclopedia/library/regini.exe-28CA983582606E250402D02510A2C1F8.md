﻿---
title: regini.exe | Registry Initializer
excerpt: What is regini.exe?
---

# regini.exe 

* File Path: `C:\Windows\system32\regini.exe`
* Description: Registry Initializer

## Hashes

Type | Hash
-- | --
MD5 | `28CA983582606E250402D02510A2C1F8`
SHA1 | `BABD9AD165050EBA11269E40DFB251473D7CE40D`
SHA256 | `CE02C12CFF31E588EE786462599F38528F899EAB8690EDA74744D04215107DFF`
SHA384 | `46129E47A56245F7A7E036FDA610EE78B36DEB8BDEFFB35A2ADCC5922BE92A8A4B6B8E33878CA83A71EFCBA7E2CF3C50`
SHA512 | `4CFD9DFC2F2F122DED375E494A374632699C51902D14C1C20424B97DD94BEE9579344329421E5905023A3C1D4AEF40A9F6DBB3DE6DF5F102C8C03A308F16BE17`
SSDEEP | `768:my2UkLBpkMEkutacvTKWU5X1Py+cP7MHliYw82i/PGlVogExyylwIcgSz:mJUWlEkz5Wmy+cMERi/pUu/Sz`
IMP | `59EADF2E64B87E9C2B8F545B5E2B4A03`
PESHA1 | `8D40760C3E2D5F42983B914544D2A943224EA9C5`
PE256 | `34D0E1F681813A46DA43B1E02F69D3006E754DDE8B083F7A2A8F780920DEB060`

## Runtime Data

### Usage (stderr):
```cmhg
usage: REGINI [-m \\machinename | -h hivefile hiveroot]
              [-i n] [-o outputWidth]
              [-b] textFiles...

where: -m specifies a remote Windows NT machine whose registry is to be manipulated.
       -h specifies a specify local hive to manipulate.
       -i n specifies the display indentation multiple.  Default is 4
       -o outputWidth specifies how wide the output is to be.  By default the
          outputWidth is set to the width of the console window if standard
          output has not been redirected to a file.  In the latter case, an
          outputWidth of 240 is used.

       -b specifies that REGINI should be backward compatible with older
           versions of REGINI that did not strictly enforce line continuations
           and quoted strings Specifically, REG_BINARY, REG_RESOURCE_LIST and
           REG_RESOURCE_REQUIREMENTS_LIST data types did not need line
           continuations after the first number that gave the size of the data.
           It just kept looking on following lines until it found enough data
           values to equal the data length or hit invalid input.  Quoted
           strings were only allowed in REG_MULTI_SZ.  They could not be
           specified around key or value names, or around values for REG_SZ or
           REG_EXPAND_SZ  Finally, the old REGINI did not support the semicolon
           as an end of line comment character.
       
       textFiles is one or more ANSI or Unicode text files with registry data.
       
       Some general rules are:
           Semicolon character is an end-of-line comment character, provided it
           is the first non-blank character on a line
       
           Backslash character is a line continuation character.  All
           characters from the backslash up to but not including the first
           non-blank character of the next line are ignored.  If there is more
           than one space before the line continuation character, it is
           replaced by a single space.
       
           Indentation is used to indicate the tree structure of registry keys
           The REGDMP program uses indentation in multiples of 4.  You may use
           hard tab characters for indentation, but embedded hard tab
           characters are converted to a single space regardless of their
           position
           
           Values should come before child keys, as they are associated with
           the previous key at or above the value's indentation level.
       
           For key names, leading and trailing space characters are ignored and
           not included in the key name, unless the key name is surrounded by
           quotes.  Imbedded spaces are part of a key name.
       
           Key names can be followed by an Access Control List (ACL) which is a
           series of decimal numbers, separated by spaces, bracketed by a
           square brackets (e.g.  [8 4 17]).  The valid numbers and their
           meanings are:
       
              1  - Administrators Full Access
              2  - Administrators Read Access
              3  - Administrators Read and Write Access
              4  - Administrators Read, Write and Delete Access
              5  - Creator Full Access
              6  - Creator Read and Write Access
              7  - World Full Access
              8  - World Read Access
              9  - World Read and Write Access
              10 - World Read, Write and Delete Access
              11 - Power Users Full Access
              12 - Power Users Read and Write Access
              13 - Power Users Read, Write and Delete Access
              14 - System Operators Full Access
              15 - System Operators Read and Write Access
              16 - System Operators Read, Write and Delete Access
              17 - System Full Access
              18 - System Read and Write Access
              19 - System Read Access
              20 - Administrators Read, Write and Execute Access
              21 - Interactive User Full Access
              22 - Interactive User Read and Write Access
              23 - Interactive User Read, Write and Delete Access
       
           If there is an equal sign on the same line as a left square bracket
           then the equal sign takes precedence, and the line is treated as a
           registry value.  If the text between the square brackets is the
           string DELETE with no spaces, then REGINI will delete the key and
           any values and keys under it.
       
           For registry values, the syntax is:
       
              value Name = type data
       
           Leading spaces, spaces on either side of the equal sign and spaces
           between the type keyword and data are ignored, unless the value name
           is surrounded by quotes.  If the text to the right of the equal sign
           is the string DELETE, then REGINI will delete the value.
       
           The value name may be left off or be specified by an at-sign
           character which is the same thing, namely the empty value name.  So
           the following two lines are identical:
       
              = type data
              @ = type data
       
           This syntax means that you can't create a value with leading or
           trailing spaces, an equal sign or an at-sign in the value name,
           unless you put the name in quotes.
       
           Valid value types and format of data that follows are:
       
              REG_SZ text
              REG_EXPAND_SZ text
              REG_MULTI_SZ "string1" "str""ing2" ...
              REG_DATE mm/dd/yyyy HH:MM DayOfWeek
              REG_DWORD numberDWORD
              REG_BINARY numberOfBytes numberDWORD(s)...
              REG_NONE (same format as REG_BINARY)
              REG_RESOURCE_LIST (same format as REG_BINARY)
              REG_RESOURCE_REQUIREMENTS (same format as REG_BINARY)
              REG_RESOURCE_REQUIREMENTS_LIST (same format as REG_BINARY)
              REG_FULL_RESOURCE_DESCRIPTOR (same format as REG_BINARY)
              REG_QWORD numberQWORD
              REG_MULTISZ_FILE fileName
              REG_BINARYFILE fileName
       
           If no value type is specified, default is REG_SZ
       
           For REG_SZ and REG_EXPAND_SZ, if you want leading or trailing spaces
           in the value text, surround the text with quotes.  The value text
           can contain any number of imbedded quotes, and REGINI will ignore
           them, as it only looks at the first and last character for quote
           characters.
       
           For REG_MULTI_SZ, each component string is surrounded by quotes.  If
           you want an imbedded quote character, then double quote it, as in
           string2 above.
       
           For REG_BINARY, the value data consists of one or more numbers The
           default base for numbers is decimal.  Hexidecimal may be specified
           by using 0x prefix.  The first number is the number of data bytes,
           excluding the first number.  After the first number must come enough
           numbers to fill the value.  Each number represents one DWORD or 4
           bytes.  So if the first number was 0x5 you would need two more
           numbers after that to fill the 5 bytes.  The high order 3 bytes
           of the second DWORD would be ignored.
       
       Whenever specifying a registry path, either on the command line
       or in an input file, the following prefix strings can be used:
       
            HKEY_LOCAL_MACHINE
            HKEY_USERS
            HKEY_CURRENT_USER
            USER:
       
          Each of these strings can stand alone as the key name or be followed
          a backslash and a subkey path.


REGINI: Missing parameter(s) for -h switch

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\regini.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: REGINI.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/ce02c12cff31e588ee786462599f38528f899eab8690eda74744d04215107dff/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\regini.exe](regini.exe-395075C20E663FC622981C9EE3DD5AC4.md) | 25
[C:\Windows\system32\regini.exe](regini.exe-3C91C37CE39EF6C3E6776B286EF7C295.md) | 32
[C:\WINDOWS\system32\regini.exe](regini.exe-5FB1FD7CBF411D45F2BE175941307995.md) | 55
[C:\Windows\system32\regini.exe](regini.exe-EAF2E449CAEC0FF310376373C5B993C9.md) | 35

## Possible Misuse

*The following table contains possible examples of `regini.exe` being misused. While `regini.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_regini.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_regini.yml) | `description: Detects the execution of regini.exe which can be used to modify registry keys, the changes are imported from one or more text files.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_regini.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_regini.yml) | `- https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regini.yml`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_regini.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_regini.yml) | `- https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/regini`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_regini.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_regini.yml) | `Image\|endswith: '\regini.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_regini_ads.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_regini_ads.yml) | `description: Detects the import of an alternate data stream with regini.exe, regini.exe can be used to modify registry keys.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_regini_ads.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_regini_ads.yml) | `- https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regini.yml`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_regini_ads.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_regini_ads.yml) | `- https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/regini`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_regini_ads.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_regini_ads.yml) | `Image\|endswith: '\regini.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regini.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regini.yml) | `Name: Regini.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regini.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regini.yml) | `- Command: regini.exe newfile.txt:hidden.ini`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regini.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regini.yml) | `- Path: C:\Windows\System32\regini.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regini.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regini.yml) | `- Path: C:\Windows\SysWOW64\regini.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regini.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regini.yml) | `- IOC: regini.exe reading from ADS`{:.highlight .language-yaml} | 

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



MIT License. Copyright (c) 2020-2021 Strontic.


