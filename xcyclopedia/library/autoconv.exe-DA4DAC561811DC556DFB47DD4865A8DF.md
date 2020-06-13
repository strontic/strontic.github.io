
# autoconv.exe 

* File Path: `C:\WINDOWS\system32\autoconv.exe`
* Description: Auto File System Conversion Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `DA4DAC561811DC556DFB47DD4865A8DF`
SHA1 | `8CE3097FF9EF0BEBE9840F2837EC3DBCA87E5694`
SHA256 | `20F166D445E04B250A1B6A14B83381F4BC9E959E378213AAA7B73E4FF0248A77`
SHA384 | `E75DEEB985335E7E5B958BE705A3D39EB7204B4CA8F20BAD08A0238D031E5A255ACAD3C1BF62D87AF051B72C285CC6A0`
SHA512 | `96C467AB45F9A7198DF221B47E26E7270FDDF37F61737FDCC7612AD94AC0B1798EFECDD9DD35B5EECFE8F0F0A86EB4C56133EC73C5D646D943C5E122BB80BD3E`
SSDEEP | `12288:O1vnIHUlk/q2fUxX57JisWaJvgFme2cgaRSY0LK4MbVk2PCMOB4tr:OFnOd/q2fmQsWSYme2ckY54eq/2h`

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

* Original Filename: AUTOCONV.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# autoconv

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Converts file allocation table (Fat) and Fat32 volumes to the NTFS file system, leaving existing files and directories intact at startup after **autochk** runs. volumes converted to the NTFS file system cannot be converted back to Fat or Fat32.

> [!IMPORTANT]
> You can't run **autoconv** from the command-line. This can only run at startup, if set through **convert.exe**.

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [autochk command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/autochk.md)

- [convert command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert.md)

---


MIT License. Copyright (c) 2020 Strontic.


