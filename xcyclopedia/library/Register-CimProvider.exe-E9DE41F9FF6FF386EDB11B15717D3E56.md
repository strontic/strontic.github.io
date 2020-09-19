---
title: Register-CimProvider.exe | WMI
---

# Register-CimProvider.exe 

* File Path: `C:\Windows\SysWOW64\Register-CimProvider.exe`
* Description: WMI

## Hashes

Type | Hash
-- | --
MD5 | `E9DE41F9FF6FF386EDB11B15717D3E56`
SHA1 | `1B85E53521F7D6361CF5FF124AB8F3A6138F2815`
SHA256 | `7946DD01FD7A3C2B9F33ECEDF6CE04F04D6F494830900338F4469DE6464CAA0E`
SHA384 | `1F7984D97E1E59F2BE71C9C99A0BA7D637FB3776A0529C46859B0B949FD3DBE9156A46E42877CBCA3C1236A01394A3A8`
SHA512 | `8700C2C48507559D963123688A78C4B8368BCAD073F5F4676E440C745C4519215F8DFDC084B712591E573814DE53108963DE4D3CB709B5DA6A2A9CED7234B6E3`
SSDEEP | `384:m4HBsKmxpfjX564NvHWrEnN2LfQGOzzrkgMcCsenu4K7xIWK1Wk:mMlUt5XzYLfQGOykenu48x4x`

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


## Possible Misuse

*The following table contains possible examples of `Register-CimProvider.exe` being misused. While `Register-CimProvider.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Register-cimprovider.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Register-cimprovider.yml) | `Name: Register-cimprovider.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Register-cimprovider.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Register-cimprovider.yml) | `- Command: Register-cimprovider -path "C:\folder\evil.dll"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Register-cimprovider.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Register-cimprovider.yml) | `- Path: C:\Windows\System32\Register-cimprovider.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Register-cimprovider.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Register-cimprovider.yml) | `- Path: C:\Windows\SysWOW64\Register-cimprovider.exe` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #3: Register-CimProvider - Execute evil dll [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #3: Register-CimProvider - Execute evil dll [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | - [Atomic Test #3 - Register-CimProvider - Execute evil dll](#atomic-test-3---register-cimprovider---execute-evil-dll) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | ## Atomic Test #3 - Register-CimProvider - Execute evil dll | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | C:\Windows\SysWow64\Register-CimProvider.exe -Path #{dll_payload} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


