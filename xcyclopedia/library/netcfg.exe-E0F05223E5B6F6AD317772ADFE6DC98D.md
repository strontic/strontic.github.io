---
title: netcfg.exe | WinPE network installer
---

# netcfg.exe 

* File Path: `C:\Windows\system32\netcfg.exe`
* Description: WinPE network installer

## Hashes

Type | Hash
-- | --
MD5 | `E0F05223E5B6F6AD317772ADFE6DC98D`
SHA1 | `FBA117CF6F936DDCA974A5F6B041075F9736F053`
SHA256 | `6820988B6804A05C7FC2F674961275861163395C2D73F6AD4A450F49282CC735`
SHA384 | `FD4DB9544A3F1B62F8D6EDBCF98B9A1FCE551B470F61E8C2034FFF73CF000284DB0BE6F0E45A6117BAE7DA1C7B2D06D6`
SHA512 | `97663EF126AFC48B4196045DBDAA6E2F9C744C8263E4BC2B6BAB5121312CDC872DB65758A70AF3BF6C6F9840A9D52CE198999D9D8792F9606659CB45393F16DE`
SSDEEP | `768:98aXLV7adQObHc9kP4eVjI/SyVufQicMu/0M0FKS:TRudXHYkP7VjrEuYM009gS`

## Runtime Data

### Usage (stdout):
```Batchfile
netcfg [-v] [-winpe] [-l <full-path-to-component-INF>] -c <p|s|c> 
       -i <comp-id>
    
    -winpe installs TCP/IP, NetBIOS and Microsoft Client for Windows 
           preinstallation environment
    -l	   provides the location of INF
    -c	   provides the class of the component to be installed (p == Protocol, 
           s == Service, c == Client)
    -i	   provides the component ID

    The arguments must be passed in the order shown.

    Examples:
    
    netcfg -l c:\oemdir\myprot.inf -c p -i myprot
    
        Installs protocol 'myprot' using c:\oemdir\myprot.inf

    netcfg -c s -i MS_Server
     
        Installs service 'MS_Server'
 
OR

netcfg [-v] -winpe

    Example:
    
    netcfg -v -winpe

        Installs TCP/IP, NetBIOS, and Microsoft Client for Windows 
        preinstallation environment

OR

netcfg [-v] -q <comp-id>

    Example:
    
    netcfg -q MS_IPX
    
        Displays if component 'MS_IPX' is installed

OR

netcfg [-v] -u <comp-id>

    Example:

    netcfg -u MS_IPX

        Uninstalls component 'MS_IPX'

OR

netcfg [-v] -s <a|n>

    -s  provides the type of components to show (a == adapters, 
        n == net components)

    Example:
    
    netcfg -s n

        Shows all installed net components

OR

netcfg [-v] -b <comp-id>

    Example:

    netcfg -b ms_tcpip

        Shows binding paths containing 'MS_TCPIP'

OR

netcfg [-v] -m

    Example:

    netcfg -m 

        Outputs the binding map to NetworkBindingMap.txt in the current directory.
        -v will also display the binding map to the console.

OR

netcfg -d

    Example:

    netcfg -d

        Performs a cleanup on all networking devices.
		This will require a reboot.

OR

netcfg -x

    Example:

    netcfg -x

        Performs a cleanup on networking devices, skipping those without physical
        object names.
		This will require a reboot.

General Notes:
  -v	Run in verbose (detailed) mode
  -?	Displays this help information


```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\netcfg.exe |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: netcfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
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



MIT License. Copyright (c) 2020 Strontic.


