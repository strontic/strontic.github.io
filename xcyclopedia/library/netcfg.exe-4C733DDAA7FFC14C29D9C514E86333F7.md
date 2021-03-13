---
title: netcfg.exe | WinPE network installer
excerpt: What is netcfg.exe?
---

# netcfg.exe 

* File Path: `C:\windows\system32\netcfg.exe`
* Description: WinPE network installer

## Hashes

Type | Hash
-- | --
MD5 | `4C733DDAA7FFC14C29D9C514E86333F7`
SHA1 | `6A99048BE2D7ABE5FE9C2598D9C456CC9979A36E`
SHA256 | `F4E138C85C5C50306CFD36457EDD549CA295BA3B2B60064A485116DCBA17F8B6`
SHA384 | `13F9BDA475A2DBD99515AA7546151195794701B5AC96F469809FDB2D7E46432E3D6051568049FFF5AAB637D745358295`
SHA512 | `1771A7814C6F44590700CFC5224E8801B2442B92CF484257AD06D3A42AB421794CDF5EC5E0C9044473E74A2E0C09D9F973A2AF702E38D83B0BBA7686F6EE981F`
SSDEEP | `768:4WXpoEpa/OC1w0EsJo1Eha0SNBlVtNQ9foKh/:LpoE8/hSjBBlVtNQ9Xh/`

## Signature

* Status: The file C:\windows\system32\netcfg.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: netcfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## netcfg

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Installs the Windows Preinstallation Environment (WinPE), a lightweight version of Windows used to deploy workstations.

### Syntax

```
netcfg [/v] [/e] [/winpe] [/l ] /c /i
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /v | Runs in verbose (detailed) mode. |
| /e | Uses servicing environment variables during install and uninstall. |
| /winpe | Installs TCP/IP, NetBIOS, and Microsoft Client for Windows preinstallation environment (WinPE). |
| /l | Provides the location of the INF file. |
| /c | Provides the class of the component to be installed; **protocol**, **service**, or **client**. |
| /i | Provides the component ID. |
| /s | Provides the type of components to show, including **\ta** for adapters or **n** for net components. |
| /b | Displays the binding paths, when followed by a string containing the name of the path. |
| /? | Displays help at the command prompt. |

#### Examples

To install the protocol *example* using c:\oemdir\example.inf, type:

```
netcfg /l c:\oemdir\example.inf /c p /i example
```

To install the *MS_Server* service, type:

```
netcfg /c s /i MS_Server
```

To install TCP/IP, NetBIOS and Microsoft Client for Windows preinstallation environment, type:

```
netcfg /v /winpe
```

To display if component *MS_IPX* is installed, type:

```
netcfg /q MS_IPX
```

To uninstall component *MS_IPX*, type:

```
netcfg /u MS_IPX
```

To show all installed net components, type:

```
netcfg /s n
```

To display binding paths containing *MS_TCPIP*, type:

```
netcfg /b ms_tcpip
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


