---
title: recover.exe | Recover Files Utility
---

# recover.exe 

* File Path: `C:\windows\system32\recover.exe`
* Description: Recover Files Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B86B2EABEDC1FC6980C802F75FB9C408`
SHA1 | `F906C8F84C5E9C96766B9F02A17B7312ED658D66`
SHA256 | `B6EC80D55C7BA99165767D74E219D9393E81CA0B7CC1B65E6A697E84E62B9DFD`
SHA384 | `AEE2FE41FAAF2A2457FC9DC1F4BDB1E87361631FCC608C20D3320890615E058C5611FC334ADCBAD0A878EDBBE3916A9A`
SHA512 | `C0566422314622CF27D761765CA16AA404686B226496885F5691DDCF3F57D057F01FF8D78347F13B563FDE188AD4B090ED8FE3AF9AF02B3DE3A958B035E6CCF5`
SSDEEP | `192:E8nsoUysmXLBrQQ/Ao1mzY1RDfN09BpUZTj6qZ2G08lTSm2TWPnWnh:xn5XL51oo1mEPDm9XUZv12jW2TWPnW`

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
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Recover.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\recover.exe](recover.exe-2B90F99E5723A85A1E2F4E321500C451.md) | 35

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


