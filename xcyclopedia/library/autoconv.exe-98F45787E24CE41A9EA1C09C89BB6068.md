
# autoconv.exe 

* File Path: `C:\WINDOWS\SysWOW64\autoconv.exe`
* Description: Auto File System Conversion Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `98F45787E24CE41A9EA1C09C89BB6068`
SHA1 | `66AF179B8C4E25CBEA3E6752506B9AB8947C3987`
SHA256 | `5E2E3FFA5E2C761C2459696D0404232BE64944F338650A5701D6BCE300C8BF99`
SHA384 | `1F57504CF9833123454F460D9586DEBDF27B80F738AB8E71A9C6F536F57C7FD33AFE6F1721117F8413D05CAF83E0C367`
SHA512 | `29C8D05857F216C165AC35760C15AF3B5936C8D4AF3D126CF6624A02EF36112C126E7D588510FD129D5E9EF979371867F0191C76AF755C36D23D8FE5A15D12CB`
SSDEEP | `24576:0RlU+X8j/te59PcwNQYGgJfDeEXlYE/yDUA0V5O0R5Lh:+XM+9PcwNQYGgJxXlBA0VpR5Lh`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUTOCONV.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
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


