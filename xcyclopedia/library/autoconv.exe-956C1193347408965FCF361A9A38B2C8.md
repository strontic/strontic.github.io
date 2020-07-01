---
title: autoconv.exe | Auto File System Conversion Utility
---

# autoconv.exe 

* File Path: `C:\windows\system32\autoconv.exe`
* Description: Auto File System Conversion Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `956C1193347408965FCF361A9A38B2C8`
SHA1 | `FAE05CCC1AF5711590B68344822FEBD90049C958`
SHA256 | `D9C70D9DB3512834DBA65648EDF305339D4FC3A023956E5DF12EE54023251F3D`
SHA384 | `AD47F84805FD8488A623B1B215A050F44F5FE2008B5877B0490F388AADD1D203848EE28B46CD848ED52BCAB3C5290818`
SHA512 | `2E1EDC17282B449EDA8100706BFDD79DA304170D2C8BF2ABC421834C0C1DF9ECFA9CC89EA70D3D521B9A3587CF1223ECAB5DA37EB5C99A54B4FC9B8B72025E97`
SSDEEP | `24576:+Hm3h/m/jwIi2WT//5aHI+rR+uCBFAduh:7EUIivhQI+tDCBFAduh`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUTOCONV.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## autoconv

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Converts file allocation table (Fat) and Fat32 volumes to the NTFS file system, leaving existing files and directories intact at startup after **autochk** runs. volumes converted to the NTFS file system cannot be converted back to Fat or Fat32.

> [!IMPORTANT]
> You can't run **autoconv** from the command-line. This can only run at startup, if set through **convert.exe**.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [autochk command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/autochk.md)

- [convert command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert.md)

---



MIT License. Copyright (c) 2020 Strontic.


