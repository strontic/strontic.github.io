---
title: autoconv.exe | Auto File System Conversion Utility
---

# autoconv.exe 

* File Path: `C:\Windows\SysWOW64\autoconv.exe`
* Description: Auto File System Conversion Utility

## Hashes

Type | Hash
-- | --
MD5 | `FDFFB4E11FF3B75EDBE1CCF557707F16`
SHA1 | `9897681EF1BAD08D3A6D6508406FDB54FFD9DEED`
SHA256 | `9AEF49E3087CD8E5557AFFDFA0E92E1A58E78ADC95D94579CBC91E40CEE88356`
SHA384 | `ADF6022CF2CDDFBF9D36CE71337546D47A3CF47A98643AE7439702F622EA4BBA1F5BD32D91E387CF68FE6C38E10907AE`
SHA512 | `B057B1742E4FC59D074219E6B47C81CCF2EB4EFBF3300B3B6C23E1A00F7C2B0F5FE1B2C25352EA60F0931DA1724CFFA43BB994A1FC445EE3302958BC6713D370`
SSDEEP | `12288:aPQDnJn3BRJ4sKmqxb9RwMBOjHeCs7lizBgE6XkdRFipUA3zBzW+1X9:aMnJRRJ4FnxxUBgE6ERFiV391`

### Loaded Modules:

Path |
-- |
C:\Windows\system32\AuthHost.exe |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\SYSTEM32\wintypes.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUTOCONV.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.1532 (rs1_release_d.170711-1840)
* Product Version: 10.0.14393.1532
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


