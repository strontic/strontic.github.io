﻿---
title: Register-CimProvider.exe | WMI
excerpt: What is Register-CimProvider.exe?
---

# Register-CimProvider.exe 

* File Path: `C:\Windows\SysWOW64\Register-CimProvider.exe`
* Description: WMI

## Hashes

Type | Hash
-- | --
MD5 | `04073FE74835F8FD8822E1568C98F42A`
SHA1 | `8FA520CF46BFAAAFEC909F2F979F098C4C281E83`
SHA256 | `11FC84778B6B88DDE720B4B84354A64F3256BE6149CD5F558350BB3F5CE8C204`
SHA384 | `C5A9466528D2F5CEEF1053B81FFCC220B3A89D166EA912DE68214C107A619ED5D416043FFAC8F382C45DA8CE0EA004F3`
SHA512 | `9DB6FAA3FDEF57E758EC8CB62193F855C9E12C355A95EC7B77783EC84C822A61B9711B7D0C3AA3A3F95C9D6DCD2307A65A91048475CC5FF778552D1A1086B53F`
SSDEEP | `384:s6xOg6dVw4VUQh8BOzxg4b1x5qQkwQcQGVjeeM4KbxQWV1WYRQp:sDiFQHx5VcGheeM4Mx7W`
IMP | `0FB0548A3D9D48194DC4FA7F08F5D988`
PESHA1 | `58A819B80A6B982B2B8CBB78AE60A135B470EF6B`
PE256 | `1873452BFAD347C5B08F0C9F9C8BDA6A45C044455D9C03E93392BD300F4AC592`

## Runtime Data

### Usage (stdout):
```cmhg

Registers CIM Provider into system

Usage:  Register-CimProvider.exe
		-Namespace <NamespaceName>
		-ProviderName <ProviderName>
		-Path <ProviderDllPath>
		[-ClassList <Space delimited list of white-listed classes>]
		[-Impersonation <True or False>]
		[-Decoupled <SDDL>]
		[-HostingModel <HostingModel>]
		[-Localize <locale>]
		[-NoAutorecover]
		[-SupportWQL]
		[-GenerateUnregistration]
		[-ForceUpdate]
		[-Verbose]

-Namespace <NamespaceName>
	Specifies the target namespace of the provider.

-ProviderName <ProviderName>
	Specifies the provider name.

-Path <ProviderDllPath>
	Specifies the provider binary path.

-Impersonation <True or False>
	Specifies foldidentity of decoupled provider, by default is True.

-Decoupled <SDDL>
	Registers provider as decoupled and specifies the security descriptor
	that determines the set of users that can successfully register
	the provider.

-HostingModel <HostingModel>
	Specifies the HostingModel of coupled provider.

-Localize <locale>
	Localizes the provider with resource of specified locale.

-NoAutorecover
	Doesn't autorecover the provider.

-SupportWQL
	Passes the query expression to the filter.

-GenerateUnregistration
	Generate the uninstall mof for the registration,
	which is disabled by default.

-ForceUpdate
	Force update the class if it exists in the system.

-ClassList <ProviderDllPath>
	Specifies space delimited list of white-listed classes that
	will be generated in the mof.

-Verbose
	Outputs registration log.


```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\Register-CimProvider.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Register-CimProvider2.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/11fc84778b6b88dde720b4b84354a64f3256be6149cd5f558350bb3f5ce8c204/detection/


## Possible Misuse

*The following table contains possible examples of `Register-CimProvider.exe` being misused. While `Register-CimProvider.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_register_cimprovider.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_register_cimprovider.yml) | `title: DLL Execution Via Register-cimprovider.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_register_cimprovider.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_register_cimprovider.yml) | `description: Detects using register-cimprovider.exe to execute arbitrary dll file.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_register_cimprovider.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_register_cimprovider.yml) | `- https://github.com/api0cradle/LOLBAS/blob/master/OSBinaries/Register-cimprovider.md`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_register_cimprovider.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_register_cimprovider.yml) | `Image\|endswith: '\register-cimprovider.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Register-cimprovider.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Register-cimprovider.yml) | `Name: Register-cimprovider.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Register-cimprovider.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Register-cimprovider.yml) | `- Command: Register-cimprovider -path "C:\folder\evil.dll"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Register-cimprovider.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Register-cimprovider.yml) | `- Path: C:\Windows\System32\Register-cimprovider.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Register-cimprovider.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Register-cimprovider.yml) | `- Path: C:\Windows\SysWOW64\Register-cimprovider.exe`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Register-CimProvider - Execute evil dll [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: Register-CimProvider - Execute evil dll [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | - [Atomic Test #3 - Register-CimProvider - Execute evil dll](#atomic-test-3---register-cimprovider---execute-evil-dll) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | ## Atomic Test #3 - Register-CimProvider - Execute evil dll | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | C:\Windows\SysWow64\Register-CimProvider.exe -Path #{dll_payload} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


