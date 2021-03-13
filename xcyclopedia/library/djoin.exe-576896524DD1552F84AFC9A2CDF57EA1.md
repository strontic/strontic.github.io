---
title: djoin.exe | Unattended Setup Generic Command For Domain Join
excerpt: What is djoin.exe?
---

# djoin.exe 

* File Path: `C:\Windows\system32\djoin.exe`
* Description: Unattended Setup Generic Command For Domain Join

## Hashes

Type | Hash
-- | --
MD5 | `576896524DD1552F84AFC9A2CDF57EA1`
SHA1 | `20D8FB1FD3A09AD9CA810A0E37C5286DAB83F49B`
SHA256 | `A7B6AC2649E6398CEC55A349929FE1DE8DA137B9F77ECD7D9036F4BACB29BB59`
SHA384 | `9F5A5EAE10A2875C09B45EACE67CB1B1F01726A152100A69D55492C32BBEB830180BFF37F30FF130172F1862D3D01C40`
SHA512 | `A620669FB886FB2F5D4154F23E4A076ED70247B7DA3F230B4E40707A227A4537D729A57E892D6155B642396B74F7E3AA42EF110C546C45CF492EB8093D6B6A5F`
SSDEEP | `768:wTEh5BWZ33NBsU9fFiLe/DmUJJMT9NUnPW1vLpppWIj8FT82zpp0vh9rrb0vQYaU:4kk3NR9xtoMW1vVpbGTpW7rXd3EQJ`
IMP | `67ED2180B06686FECAA36DBFD2D9C7A6`
PESHA1 | `B09D43ABA968A1B7908CD87815D8566C8729417C`
PE256 | `8B7C3585B2AFB949D09663DC654E920C325F8C8850013C2440353B38BF8924A9`

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
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\dbgcore.DLL |
C:\Windows\system32\dbghelp.dll |
C:\Windows\system32\djoin.exe |
C:\Windows\system32\JOINUTIL.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\logoncli.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\system32\netprovfw.dll |
C:\Windows\system32\netutils.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\wdscore.dll |
C:\Windows\system32\wkscli.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: djoin.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/a7b6ac2649e6398cec55a349929fe1de8da137b9f77ecd7d9036f4bacb29bb59/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


