---
title: djoin.exe | Unattended Setup Generic Command For Domain Join
excerpt: What is djoin.exe?
---

# djoin.exe 

* File Path: `C:\WINDOWS\system32\djoin.exe`
* Description: Unattended Setup Generic Command For Domain Join

## Hashes

Type | Hash
-- | --
MD5 | `7896062C2E121201E11D4124A09F73B2`
SHA1 | `F654E5C1F4AE6BCAE433A429C65FE8838B4C88CE`
SHA256 | `013775598914BC8DFB240392F0977F62A984D2FC7DDCC9C2540F4C7366A26DAE`
SHA384 | `1DF0042E4CBFF536506D03056552E3FB93784FD2A11D375402295A0A051F42AF5D7770A801ABB6D0DE556641DDD18570`
SHA512 | `C1371B64DD61DB56F16A1A5C5E87F45E9D2F5D6D73F1425438EC56EE863CC4BAD282D82AD26F7F4B27EEC3A4BD490A7371BD6D77492DD818371E00857D43DF3E`
SSDEEP | `1536:gmOYWHEzTsyoRxjFYzuabXGdwHF3aXPC5YQJ:gFYsy4yoRxZYKoXGAdGK5`
IMP | `A0D2C238122B7ACE2F6A5B53A13B9E40`
PESHA1 | `95A47304AF9E3D42E4789FD9C760CED27819D74C`
PE256 | `2A5B220435510BC2DA109878E83A9604C8D5A810B1F3BF8CC6EAAF2350A746E2`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: djoin.exe [/OPTIONS]

  /PROVISION  - Provision a computer account in the domain
      /DOMAIN <Name> - <Name> of the domain to join
      /MACHINE <Name> - Host <Name> of the computer joining the domain
      /MACHINEOU <OU> - Optional <OU> where the account is created
      /DCNAME <DC> - Optional <DC> to target for account creation
      /REUSE - Reuse any existing account (password will be reset)
      /SAVEFILE <FilePath> - Save provisioning data to a file at <FilePath>
      /NOSEARCH - Skip account conflict detection, requires DCNAME (faster)
      /DOWNLEVEL - Support using a Windows Server 2008 DC or earlier
      /PRINTBLOB - Return base64 encoded metadata blob for an answer file
      /DEFPWD - Use default machine account password (not recommended)
      /ROOTCACERTS - Opt. include root Certificate Authority certificates.
      /CERTTEMPLATE <Name> - Optional <Name> of machine certificate template.
                             Includes root Certificate Authority certificates.
      /POLICYNAMES <Name(s)> - Opt. semicolon-separated list of policy names.
                               Each name is the displayName of the GPO in AD.
      /POLICYPATHS <Path(s)> - Opt. semicolon-separated list of policy paths.
                               Each path is a path to a registry policy file.
      /NETBIOS <Name> - Opt. Netbios <Name> of the computer joining the domain.
      /PSITE <Name> - Opt. <Name> of persistent site to put the computer joining
                      the domain in.
      /DSITE <Name> - Opt. <Name> of dynamic site to initially put the computer 
                      joining the domain in.
      /PRIMARYDNS <Name> - Opt. <Name> of primary DNS domain of the computer
                           joining the domain.

  /REQUESTODJ  - Request offline domain join at next boot
      /LOADFILE <FilePath> - <FilePath> specified previously via /SAVEFILE
      /WINDOWSPATH <Path> - <Path> to the Windows directory in an offline image
      /LOCALOS - Allows /WINDOWSPATH to specify the locally running OS.
                 This command must be run as a local Administrator.
                 This option requires a reboot for changes to be applied.
      
Examples:

To provision a computer account in the domain:
djoin.exe /PROVISION /DOMAIN <DomainName> /MACHINE <MachineName>
          /SAVEFILE <FilePath>
          Note: Other parameters are optional
          
To request the local machine to perform an offline domain join:
djoin.exe /REQUESTODJ /LOADFILE <FilePath> /WINDOWSPATH <Path>
          Note: Other parameters are optional
The parameter is incorrect.

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\djoin.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: djoin.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/013775598914bc8dfb240392f0977f62a984d2fc7ddcc9c2540f4c7366a26dae/detection





MIT License. Copyright (c) 2020-2021 Strontic.


