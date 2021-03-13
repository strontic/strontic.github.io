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
MD5 | `D686812456A76D1FD64334B1967E5051`
SHA1 | `4D3D670B1DF78A805A9601EC861F0B3B874F344C`
SHA256 | `074B4A36E0CC697E4146EA3873BFD25EBB067F2A937930E4D8393340F84F0D32`
SHA384 | `2AB5FCB6FA4CCEF294229A5C077F58EF8C1FBBAB27AF2497C326E0EDD8EFFCCE8CA65A83860E48BD15EB58E69B677587`
SHA512 | `D53FB3510C1A0F5411D1F8EF04456672D547BFABE02063B114B516162CAF99A59C06C8B1EFD721E0B4BE0E924038845FA55F28260C254AC67682CE97A5F3296F`
SSDEEP | `384:cGcZkm+OYbUHJjtm3tJT52DZZ8sSv6u2i89xP95ElC1H0aAKWDVW:cGcZkbJUHJjtmvkZZ8DfanPk/`
IMP | `EA17270B67FAE16B05714FD14BE68EA3`
PESHA1 | `EF6EAB602B0D4D930148026180156F37BCC03E8D`
PE256 | `E393174C4D5921D8C641985689C2DD361E959792AB0585FB35040FEE37A7D517`

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

### Loaded Modules:

Path |
-- |
C:\Windows\system32\chgusr.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: chgusr.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/074b4a36e0cc697e4146ea3873bfd25ebb067f2a937930e4d8393340f84f0d32/detection



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



MIT License. Copyright (c) 2020-2021 Strontic.


