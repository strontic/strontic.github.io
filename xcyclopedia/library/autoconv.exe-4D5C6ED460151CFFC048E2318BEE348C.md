---
title: autoconv.exe | Auto File System Conversion Utility
---

# autoconv.exe 

* File Path: `C:\windows\SysWOW64\autoconv.exe`
* Description: Auto File System Conversion Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4D5C6ED460151CFFC048E2318BEE348C`
SHA1 | `0028C998DDE5DA42D16DA9AF04861EE129B23CCF`
SHA256 | `3DA90503C57C57C198904EAB618AB5ED4942E8FA225643F4705328CDF4C69EC4`
SHA384 | `C172A9355DB6877F82FACBE547425BCF10F48BECA518B17EB66B7F0A4D7FC73F496A470E335141ABED64B57AEC7A0C4D`
SHA512 | `96DC44C19A0427D565CA41A172AF47B070F3247370D29E6E343BC09CBF4382C2FA8459282507AA5800F1370C6CE56D57307FED9AEE5400C44651D341C4573483`
SSDEEP | `24576:9ujBgFjvGB8BNfAdKmtBh0eiiQuggvGjCEs4xh:8gFiANfAdKmh0eQwGj3s4xh`

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

* Original Filename: AUTOCONV.EXE
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


