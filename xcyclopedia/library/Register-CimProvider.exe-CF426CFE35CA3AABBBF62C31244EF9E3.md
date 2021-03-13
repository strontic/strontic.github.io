---
title: Register-CimProvider.exe | WMI
excerpt: What is Register-CimProvider.exe?
---

# Register-CimProvider.exe 

* File Path: `C:\Windows\system32\Register-CimProvider.exe`
* Description: WMI

## Hashes

Type | Hash
-- | --
MD5 | `CF426CFE35CA3AABBBF62C31244EF9E3`
SHA1 | `4957F28C6C18B2D14D9C4879C5A6769FB0D9618E`
SHA256 | `088DE004B2ABC256739060C61B89A4B3EAA892907B0A61EA30C2EB4533ADD373`
SHA384 | `F2D9A734C93F39A344C11319B0C244E74D924A941BBD4A8D27AB0B071287121D97D7279252E20A99ECFF52870221B3B3`
SHA512 | `13874C7A150CF1DFFD1FA5211A738F73FDDBA9F2A55E60A281EF1276D7F1E7B4CE897789BAEBB922CEF639FDA2099B8B70D5BC1E43C6628E80EC7BE13C9F4027`
SSDEEP | `384:gbeG/bazHusjK0sZT9hm5ACy0io4Sq9JFadXZceP5P23tHj14KVGGx4WV1W:gr4OHk2XS4Fg2AqHj14E5xT`
IMP | `4AC40E439D637601F5F9F12A23F83148`
PESHA1 | `5230D677A82A1389E268D06E498462B8C1596CCB`
PE256 | `B49BDB97F6C0B31F54F209649FD4656D2F774E7D738DAE60B85871A772A81E37`

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

### Child Processes:
RdpSa.exe

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\Register-CimProvider.exe |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/088de004b2abc256739060c61b89a4b3eaa892907b0a61ea30c2eb4533add373/detection/


## Possible Misuse

*The following table contains possible examples of `Register-CimProvider.exe` being misused. While `Register-CimProvider.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
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


