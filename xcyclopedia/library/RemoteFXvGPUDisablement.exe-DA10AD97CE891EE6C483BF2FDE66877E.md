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
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `078044F770D8C33CD62E9976649783EAF0F4CD7A`
PE256 | `13FA78246B167A0714DE6EC87FADE1AEAD8D2006E33A6707E701C3605DA9F6FF`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\clr.dll |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscoreei.dll |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\MSVCR120_CLR0400.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\RemoteFXvGPUDisablement.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\VERSION.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/a42b55bf02179c8676f260ec9fd89ec8aed9fb5117c914d928ec711d96771424/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\RemoteFXvGPUDisablement.exe](RemoteFXvGPUDisablement.exe-0718AA4C9BD4A64231A92672B36BCDA9.md) | 82

## Possible Misuse

*The following table contains possible examples of `RemoteFXvGPUDisablement.exe` being misused. While `RemoteFXvGPUDisablement.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\WINDOWS\System32\RemoteFXvGPUDisablement.exe'  # on win10` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | RemoteFXvGPUDisablement.exe is an abusable, signed PowerShell host executable that was introduced in Windows 10 and Server 2019 (OS Build 17763.1339). | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | One of the PowerShell functions called by RemoteFXvGPUDisablement.exe is Get-VMRemoteFXPhysicalVideoAdapter, a part of the Hyper-V module. This atomic test influences RemoteFXvGPUDisablement.exe to execute custom PowerShell code by using a technique referred to as "PowerShell module load-order hijacking" where a module containing, in this case, an implementation of the Get-VMRemoteFXPhysicalVideoAdapter is loaded first by way of introducing a temporary module into the first directory listed in the %PSModulePath% environment variable or within a user-specified module directory outside of %PSModulePath%. Upon execution the temporary module is deleted. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | Invoke-ATHRemoteFXvGPUDisablementCommand is used in this test to demonstrate how a PowerShell host executable can be directed to user-supplied PowerShell code without needing to supply anything at the command-line. PowerShell code execution is triggered when supplying the "Disable" argument to RemoteFXvGPUDisablement.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | \| module_path \| Specifies an alternate, non-default PowerShell module path for RemoteFXvGPUDisablement.exe. If -ModulePath is not specified, the first entry in %PSModulePath% will be used. Typically, this is %USERPROFILE%&#92;Documents&#92;WindowsPowerShell&#92;Modules. \| string \| $PWD\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


