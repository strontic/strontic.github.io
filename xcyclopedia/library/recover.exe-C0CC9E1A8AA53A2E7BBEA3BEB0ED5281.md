﻿---
title: recover.exe | Recover Files Utility
---

# recover.exe 

* File Path: `C:\windows\system32\recover.exe`
* Description: Recover Files Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C0CC9E1A8AA53A2E7BBEA3BEB0ED5281`
SHA1 | `188421022518C3B21350C98042F897AA45929DCC`
SHA256 | `525BC408B5DA791F7EB751BA5FA34343AD3719D6F8EE64A90F122C069E4C9F47`
SHA384 | `18CA9AE1480521A4DC104D7DBF96834C602DE6FEEC9070F15E5C80B8CAD794FF22D103358F94440FCDC20660EA1B91F8`
SHA512 | `7CEDF76D10DDFD34959582A932A64D8BEABD8334F5909A04C7D0171D7CC6019F15F719E841A9B287539EA160C50B22D7D638D9737F67343F8BD41437493E1553`
SSDEEP | `192:bsseIpJBGdP/2YhEvxepqkK/IT38Rny8MeAGkzCOFum2TWCnWa:bssdpJBSTUxfC3+ype8zz2TWCnWa`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\recover.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: Recover.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\SysWOW64\recover.exe](recover.exe-70DC5E90F88E476FA769BB7D12F936F5.md) | 41

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

