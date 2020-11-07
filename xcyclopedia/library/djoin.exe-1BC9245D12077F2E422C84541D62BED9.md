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
MD5 | `1BC9245D12077F2E422C84541D62BED9`
SHA1 | `01C877005E353A5202B2250B0277BB900D71753F`
SHA256 | `F5EE00BF7CFD7BF7504597D0106D1FA2C8CEBFC7B693DC18E6E10F2864FAD690`
SHA384 | `BBD52D571A209D42DEA28C24E7DBFE4BD5FC0647EFE2101D50F8FCD43DB5E230D87F2C28EF19355ABA9922B75EC60BB4`
SHA512 | `23D6D5217D2113909D69C769A41A39BF824101EBF4424F52F8ADF19E807D9FF392B5B2E29607D3659E22C513A024EB6D46E85DC73E89B443BBA74E497626E987`
SSDEEP | `1536:uzk0GRwMJ2Ut668+tFI2GwKEQeXsOmQJ:uA0GQUt668+U2GrEjL`
IMP | `A97339DE0E1A0EBC1C5F5B0FA9A1EF2E`
PESHA1 | `E4EFB9A52B09140ED04075752DB7E0E4FED12E07`
PE256 | `C1B118BC2F06892D825C160C782723CA7239832CDC3784AEBEDBE8D87721A978`

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
C:\Windows\system32\djoin.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: djoin.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/f5ee00bf7cfd7bf7504597d0106d1fa2c8cebfc7b693dc18e6e10f2864fad690/detection





MIT License. Copyright (c) 2020 Strontic.


