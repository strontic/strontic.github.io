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
MD5 | `F9F77EB472F58EDEBCFEA7B51FFC6EEA`
SHA1 | `087B259400C4E523144A4A829610BF589BDE125B`
SHA256 | `5311C4B92BDA7852580C8DF50922F8328EB5A238012F10DED7B38DC3B9D00D8E`
SHA384 | `E3BBE473967D2EE8387AA90656F9AB4554AAE5BF8AD9A3C81652C4C8015D2A96DCA6E6FF3F25580051B0AEBA0FA5DEA2`
SHA512 | `0C6D1BDCEEA5FD5E7DE2B47B4961E596E45FCB9237EE8B42CC9BBD93AB8F627CA919F3FCA744B701BAFB269E45C7BF4955268CA408926F10AD3DF200495F7BFA`
SSDEEP | `384:VNV1h6Bch1F9FajPameTrsv4LfDnexElF4dkEZfp1NJZ7ysl2RZPGPWrHo34Wxwq:/96BcEoYdx44FXlJl0gsHo34WxA`
IMP | `657445DD05A7049E92510D26B786C072`
PESHA1 | `91802BF3383560B9892C7CFD77F60AE5BEF79DE8`
PE256 | `D8C41016DF1B7860E483981419B13DECCE7F62FED3FBB9A18CB07E2F13BDAB51`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\Register-CimProvider.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Register-CimProvider2.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/5311c4b92bda7852580c8df50922f8328eb5a238012f10ded7b38dc3b9d00d8e/detection


## Possible Misuse

*The following table contains possible examples of `Register-CimProvider.exe` being misused. While `Register-CimProvider.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Register-cimprovider.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Register-cimprovider.yml) | `Name: Register-cimprovider.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Register-cimprovider.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Register-cimprovider.yml) | `- Command: Register-cimprovider -path "C:\folder\evil.dll"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Register-cimprovider.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Register-cimprovider.yml) | `- Path: C:\Windows\System32\Register-cimprovider.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Register-cimprovider.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Register-cimprovider.yml) | `- Path: C:\Windows\SysWOW64\Register-cimprovider.exe` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Register-CimProvider - Execute evil dll [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: Register-CimProvider - Execute evil dll [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | - [Atomic Test #3 - Register-CimProvider - Execute evil dll](#atomic-test-3---register-cimprovider---execute-evil-dll) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | ## Atomic Test #3 - Register-CimProvider - Execute evil dll | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | C:\Windows\SysWow64\Register-CimProvider.exe -Path #{dll_payload} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


