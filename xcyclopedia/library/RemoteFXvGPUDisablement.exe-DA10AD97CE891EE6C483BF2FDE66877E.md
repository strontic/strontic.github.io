---
title: RemoteFXvGPUDisablement.exe |  
excerpt: What is RemoteFXvGPUDisablement.exe?
---

# RemoteFXvGPUDisablement.exe 

* File Path: `C:\Windows\system32\RemoteFXvGPUDisablement.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `DA10AD97CE891EE6C483BF2FDE66877E`
SHA1 | `CB724F848EB36257E725F4444B0B54DA2279DD3F`
SHA256 | `A42B55BF02179C8676F260EC9FD89EC8AED9FB5117C914D928EC711D96771424`
SHA384 | `BCE1800AF2CA295A93BC3FE2D5ABC7EBBE3898464389133E9BB19EF645C45447C7E878FE737CCDCC87051F16CE78970D`
SHA512 | `80ECD40762D80AAE98629A0FF7A1C412F8D567E7115D13FAB36C990B59B01A12CE247004B761DAF6CA6C9BC85CD65F39EBDC1718107849582D2F82D6D974AAFF`
SSDEEP | `192:+Y2sL84qxeU2VtRjOzRDnEtzMPUOY/0svGS0lTYwWTfWR:+VeU2hjO9Et0UOSokwWTfW`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\RemoteFXvGPUDisablement.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RemoteFXvGPUDisablement.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1339
* Product Version: 10.0.17763.1339
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\RemoteFXvGPUDisablement.exe](RemoteFXvGPUDisablement.exe-0718AA4C9BD4A64231A92672B36BCDA9.md) | 82

## Possible Misuse

*The following table contains possible examples of `RemoteFXvGPUDisablement.exe` being misused. While `RemoteFXvGPUDisablement.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\WINDOWS\System32\RemoteFXvGPUDisablement.exe'  # on win10` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


