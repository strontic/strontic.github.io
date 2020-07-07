---
title: recover.exe | Recover Files Utility
---

# recover.exe 

* File Path: `C:\Windows\system32\recover.exe`
* Description: Recover Files Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FB2C06116CA9506829F08B8CAAE56561`
SHA1 | `BB6745BDDE365BCF26FCA0727FF0541C3D173BDD`
SHA256 | `DD8BC56FFB5B471B94F101C385439159B289BB9255A48EDD1F0C247F5101FDD7`
SHA384 | `BC88FEF37801C34E43C59C8030068B4D947EDC790D2780451BD6FD46656B7A056ACF81A2422AF2F2C2C0F75B863BF11E`
SHA512 | `430F9B8CD1B89C50DC77CA137368B391534312A278881D297E201C72F96D7BB6DFF51D84CBFE783A2F000EDBF0A049279180B66136551119B1242AC7DD2F4A4D`
SSDEEP | `192:EMp1/zPqoxJg1VD87N9EKVar3qy08VchbWSGS5Ajum2jWEnWy:BTRM7879UuyBVoVB62jWEnW`

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

* Original Filename: Recover.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\recover.exe](recover.exe-D38B657A068016768CA9F3B5E100B472.md) | 30

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

Recovers readable information from a bad or defective disk. This command reads a file, sector-by-sector, and recovers data from the good sectors. Data in bad sectors is lost. Because all data in bad sectors is lost when you recover a file, you should recover only one file at a time.

Bad sectors reported by the **chkdsk** command were marked as bad when your disk was prepared for operation. They pose no danger, and **recover** does not affect them.

### Syntax

```
recover [<drive>:][<path>]<filename>
```

#### Parameters

| Parameter | Description |
|--|--|
| `[<drive>:][<path>]<filename>` | Specifies the file name (and the location of the file if it is not in the current directory) you want to recover. *Filename* is required and wildcards aren't supported. |
| /? | Displays help at the command prompt. |

#### Examples

To recover the file *story.txt* in the *\fiction* directory on drive D, type:

```
recover d:\fiction\story.txt
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


