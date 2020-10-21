---
title: chgusr.exe | Change INI File Mapping Utility
excerpt: What is chgusr.exe?
---

# chgusr.exe 

* File Path: `C:\Windows\system32\chgusr.exe`
* Description: Change INI File Mapping Utility

## Hashes

Type | Hash
-- | --
MD5 | `8DAF58E7E05F72467DE0FAFDED21BA1A`
SHA1 | `4FDAD69A0DEAAA7E223E9329F7C6BEBA5E5F6721`
SHA256 | `4DA3797B3AAB0BDC53A2B923C43A84E16269C4683A556FAE0F491B827BAEE1C8`
SHA384 | `B8FF53262730CC2E1E0A8695FDC00056E1275FADE3A281FB6ABA9A73C3B24A3DFDCF7ABB11B98A9287E4A0828AC9238F`
SHA512 | `6A175AED80E18AD9F847F0D3E9D8A956B1CEC273521A0AE6408FBD8567F6AD1D6EFB98A545022BE599372B495458FCEF45D83F1F73E6E9292BFCBC1026D70E33`
SSDEEP | `384:GX2Y08rYQ/8x7nVmEoz5XukK8vW5kLS43eYH2TwHKXTSWoVW:W08rYQ/G7n8AkK8u5klJIT8`
IMP | `EA17270B67FAE16B05714FD14BE68EA3`
PESHA1 | `22C334C65F3530A56A47CA1D779A97EA4CF411FC`
PE256 | `A085DAC2EC0B104F49BE9186C95DC2C7BB75DC4C632AFDA63E3D03A64663EF10`

## Runtime Data

### Usage (stdout):
```cmhg
Change Install Mode.

CHANGE USER {/EXECUTE | /INSTALL | /QUERY}

  /EXECUTE  Enable execute mode (default).
  /INSTALL  Enable install mode.
  /QUERY    Display current settings.


```

### Usage (stderr):
```cmhg
Invalid parameter(s)
Change Install Mode.

CHANGE USER {/EXECUTE | /INSTALL | /QUERY}

  /EXECUTE  Enable execute mode (default).
  /INSTALL  Enable install mode.
  /QUERY    Display current settings.


```

### Child Processes:
csrss.exe wininit.exe

### Loaded Modules:

Path |
-- |
C:\Windows\system32\chgusr.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: chgusr.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/4da3797b3aab0bdc53a2b923c43a84e16269c4683a556fae0f491b827baee1c8/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\chgusr.exe](chgusr.exe-DF4F3F4B59FC7198AC410920B5332E71.md) | 82


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## chgusr

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Changes the install mode for the Remote Desktop Session Host server.

> [!NOTE]
> This command has been replaced by the **change user command**. For more information, including the syntax and parameter details, see [change user command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-user.md).

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [change user command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/change-user.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020 Strontic.


