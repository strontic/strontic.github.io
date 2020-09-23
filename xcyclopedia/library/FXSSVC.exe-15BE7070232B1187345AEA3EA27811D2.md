---
title: FXSSVC.exe | Fax Service
excerpt: What is FXSSVC.exe?
---

# FXSSVC.exe 

* File Path: `C:\Windows\system32\FXSSVC.exe`
* Description: Fax Service

## Hashes

Type | Hash
-- | --
MD5 | `15BE7070232B1187345AEA3EA27811D2`
SHA1 | `9D3D9CEE17D7571C2CCCE921D8D682307CC1C91A`
SHA256 | `02550C0AAD3F86F5C6EFB1F5043C358D78C6D847539755D95672935D974D5AE8`
SHA384 | `DDE70383486C33B2B515EE99C190DDB79255AA690268271FF29BFED518AF54EB8AEB93C60F87B357BBBA568B873CBB1B`
SHA512 | `BD978853B217333228989AEF36B8EB0503887743C294769969124009046735C176B147A8939C60679B6FD60A852939BD94F6D2DE53761A669C7DC00B9CD7624A`
SSDEEP | `12288:+LiNviwpK2qFoKa0+wVZhqwWnorQrRkyNAkv4B7s2qhut3ZSg8j/3:QYv5pcF3PZRrQrRkydv83Fc/3`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FXSSVC.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `FXSSVC.exe` being misused. While `FXSSVC.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_fax_dll.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_fax_dll.yml) | `- fxssvc.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.003/T1543.003.md) | sc config Fax binPath= "C:\WINDOWS\system32\fxssvc.exe" >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


