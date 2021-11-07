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
MD5 | `0718AA4C9BD4A64231A92672B36BCDA9`
SHA1 | `EDBC95E7D5A3F93F851950AB75C5EC182757824A`
SHA256 | `CFCF444DDB908A89DC7C0C279D320F960FAC3BA5D64E631370CD7357D4003880`
SHA384 | `D2B744813FA5DAF6063306560BA4A2DBA85C91437DCE4F11FB861C0CEB3CD78A5CE2C67BEE1D9F5AF80585C9064334D4`
SHA512 | `A2664413B5B12090D94F472317764DA9D983359222770C78AE6905CCB45276C4D786FC34A3B12FF8904F1376597CAEE582111B36463771581A7D24ADFE988621`
SSDEEP | `192:j2sL84qxeU25tRTOzRDnEtzMPUOYA0svGS0qTYRWlofWi:MeU29TO9Et0UOB3kRWlofW`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `020E641B1E1FD6B0639CEFF3BE973363B29D2DC4`
PE256 | `DD0B154805FC7A56587EBF6F067C76F94AC34CEC30255AE0AAFAE3CF6D0F152F`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\RemoteFXvGPUDisablement.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |


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
* File Version: 10.0.19041.388
* Product Version: 10.0.19041.388
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/cfcf444ddb908a89dc7c0c279d320f960fac3ba5d64e631370cd7357d4003880/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\RemoteFXvGPUDisablement.exe](RemoteFXvGPUDisablement.exe-DA10AD97CE891EE6C483BF2FDE66877E.md) | 82

## Possible Misuse

*The following table contains possible examples of `RemoteFXvGPUDisablement.exe` being misused. While `RemoteFXvGPUDisablement.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\WINDOWS\System32\RemoteFXvGPUDisablement.exe'  # on win10`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_classic_susp_athremotefxvgpudisablementcommand.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_classic/powershell_classic_susp_athremotefxvgpudisablementcommand.yml) | `description: RemoteFXvGPUDisablement.exe is an abusable, signed PowerShell host executable that was introduced in Windows 10 and Server 2019 (OS Build 17763.1339).`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_susp_athremotefxvgpudisablementcommand.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_susp_athremotefxvgpudisablementcommand.yml) | `description: RemoteFXvGPUDisablement.exe is an abusable, signed PowerShell host executable that was introduced in Windows 10 and Server 2019 (OS Build 17763.1339).`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_susp_athremotefxvgpudisablementcommand.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_susp_athremotefxvgpudisablementcommand.yml) | `description: RemoteFXvGPUDisablement.exe is an abusable, signed PowerShell host executable that was introduced in Windows 10 and Server 2019 (OS Build 17763.1339).`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | RemoteFXvGPUDisablement.exe is an abusable, signed PowerShell host executable that was introduced in Windows 10 and Server 2019 (OS Build 17763.1339). | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | One of the PowerShell functions called by RemoteFXvGPUDisablement.exe is Get-VMRemoteFXPhysicalVideoAdapter, a part of the Hyper-V module. This atomic test influences RemoteFXvGPUDisablement.exe to execute custom PowerShell code by using a technique referred to as "PowerShell module load-order hijacking" where a module containing, in this case, an implementation of the Get-VMRemoteFXPhysicalVideoAdapter is loaded first by way of introducing a temporary module into the first directory listed in the %PSModulePath% environment variable or within a user-specified module directory outside of %PSModulePath%. Upon execution the temporary module is deleted. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | Invoke-ATHRemoteFXvGPUDisablementCommand is used in this test to demonstrate how a PowerShell host executable can be directed to user-supplied PowerShell code without needing to supply anything at the command-line. PowerShell code execution is triggered when supplying the "Disable" argument to RemoteFXvGPUDisablement.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | \| module_path \| Specifies an alternate, non-default PowerShell module path for RemoteFXvGPUDisablement.exe. If -ModulePath is not specified, the first entry in %PSModulePath% will be used. Typically, this is %USERPROFILE%&#92;Documents&#92;WindowsPowerShell&#92;Modules. \| String \| $PWD\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


