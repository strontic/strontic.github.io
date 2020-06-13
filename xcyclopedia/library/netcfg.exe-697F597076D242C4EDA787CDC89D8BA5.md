
# netcfg.exe 

* File Path: `C:\WINDOWS\system32\netcfg.exe`
* Description: WinPE network installer
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `697F597076D242C4EDA787CDC89D8BA5`
SHA1 | `3F6FCD86A6EBA7D6487A459F561D14C3EA261F88`
SHA256 | `CF6E6B447304B3CAC8E24962D2ED9EE025B2218EB147F4C64FC6BB1837B3EE78`
SHA384 | `A74D9200FE3339884F18A6413615EC30F1A261BA52805030B67A3C8EC62BA724D95AAF32003BFAE4E058D4FE6B90A991`
SHA512 | `528684CCA0C19644E811142A46393ED68AD855C76C42F1495C4BE9244EFE32950C0BCCF7CFD5CB3D80C7A744D2F0E5B95663AD4C1406D96D3DD04544092FC3EE`
SSDEEP | `768:dl6Vl8RZhOObzltEb0CvZllVW+JNt8iQ0M0Rqc:q8L5bxtEg8jDW+iiQ094c`

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

* Original Filename: netcfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# netcfg

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Installs the Windows Preinstallation Environment (WinPE), a lightweight version of Windows used to deploy workstations.

## Syntax

```
netcfg [/v] [/e] [/winpe] [/l ] /c /i
```

### Parameters

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

### Examples

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

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


