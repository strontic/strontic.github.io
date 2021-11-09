---
title: netcfg.exe | WinPE network installer
excerpt: What is netcfg.exe?
---

# netcfg.exe 

* File Path: `C:\WINDOWS\system32\netcfg.exe`
* Description: WinPE network installer

## Hashes

Type | Hash
-- | --
MD5 | `5797194515F389D1EB62828E8D45C0E4`
SHA1 | `A6B81F8B67E36B6D8D97BCB8129C35EAA1AF06DC`
SHA256 | `F0FDECF9B716A96078A4DB4DE5A1B7DEEA3B40B84D492A7AEE320E9EAA60991A`
SHA384 | `F1880B3DC29E58D3B35306BA52F639C508C2D6962CC0B0504ACFC659908A2B0919E4F2B11948756CE76F59E9A1A50584`
SHA512 | `ED6CEB19CDA18A83A7332E01C61064913DB7F67CC943B90A45EBF69F445B424A51834A620F331B73AA386C0D8BD03794F3E032EBAEEF252A2CDB2A88E43E0779`
SSDEEP | `1536:v/rqTTCvM8er+em5Udn8NpWWSk6r+53+wM+:veWvMpr+eDd6pWWhi+5uwj`
IMP | `F4666ACBF024767FFF0861A8EC8E8908`
PESHA1 | `CF168A54D9197BA0C1F3968726F1AAFE4C7C3CA5`
PE256 | `807CFF9537FB18E75FEB96506E61646057EFAB68CA9672828648C1FBC47C4199`

## Runtime Data

### Usage (stdout):
```cmhg
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
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\netcfg.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: netcfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/f0fdecf9b716a96078a4db4de5a1b7deea3b40b84d492a7aee320e9eaa60991a/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## netcfg

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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


