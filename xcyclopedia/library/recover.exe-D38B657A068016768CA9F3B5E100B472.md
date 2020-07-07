﻿---
title: recover.exe | Recover Files Utility
---

# recover.exe 

* File Path: `C:\Windows\SysWOW64\recover.exe`
* Description: Recover Files Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `D38B657A068016768CA9F3B5E100B472`
SHA1 | `BEE11FDB9806B1527C46DF2F374B1716E13ACA20`
SHA256 | `D971D5F962E2188A429DE6AC6DD6FBA3FA97199CDC1A8182E753069AEC2FB93E`
SHA384 | `558A877D466D9D0B6BBD45AD9E797801DAD3456E2E5525A943274F7CE0E543C85CABF72D149A380081A00FF5D2B32FE5`
SHA512 | `3128B173A47CFF9F53F904ADC757D4340D574847B5F7E9997CACA88C003244BFE17FE8412A52EEFD5791CFC797FCF3482CCEAB923FBFE6A34E276A4279A1F3C5`
SSDEEP | `192:gfmv5WKYs/pCjwY19qpXD9tAYq7xk2jWEnWyaAb4V:1v5gCpWwi9qp3AnS2jWEnWHAkV`

## Runtime Data

### Usage (stdout):
```Batchfile
Recovers readable information from a bad or defective disk.

RECOVER [drive:][path]filename
Consult the online Command Reference in Windows Help
before using the RECOVER command.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Recover.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\recover.exe](recover.exe-FB2C06116CA9506829F08B8CAAE56561.md) | 30

## Possible Misuse

*The following table contains possible examples of `recover.exe` being misused. While `recover.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1048.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1048.003/T1048.003.md) | 3. Once the data is received, use the below command to recover the data. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [use-cases.md](https://github.com/redcanaryco/atomic-red-team/blob/master/docs/use-cases.md) | - How long does it take us to contain, remediate, recover? | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## recover



Recovers readable information from a bad or defective disk.



### Syntax

```
recover [<Drive>:][<Path>]<FileName>
```

#### Parameters

|           Parameter           |                                          Description                                          |
|-------------------------------|-----------------------------------------------------------------------------------------------|
| [\<Drive>:][<Path>]<FileName> | Specifies the location and name of the file that you want to recover. *FileName* is required. |
|              /?               |                             Displays help at the command prompt.                              |

### Remarks

-   The **recover** command reads a file, sector-by-sector, and recovers data from the good sectors. Data in bad sectors is lost.
-   Bad sectors reported by **chkdsk** were marked as bad when your disk was prepared for operation. They pose no danger, and **recover** does not affect them.
-   Because all data in bad sectors is lost when you recover a file, you should recover only one file at a time.
-   You cannot use wildcard characters (**&#42;** and **?**) with the **recover** command. You must specify a file (and the location of the file if it is not in the current directory).

### Examples

To recover the file Story.txt in the \Fiction directory on drive D, type:
```
recover d:\fiction\story.txt 
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.

