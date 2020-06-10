
# Register-CimProvider.exe 
* File Path: `C:\WINDOWS\system32\Register-CimProvider.exe`
* Description: WMI
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `6429F87E5D22AC53B78346CB5DD9D089`
SHA1 | `21E047F09E63B687EB5BCC53CBD97BF97C1EB3A0`
SHA256 | `D9395667AB0ECB3E2FF40E2E9098ECB0A431DB782D70AE222827EE13B9AFAA15`
SHA384 | `97D510FD175E33766A4D510BDE166C44B3D39621D6B3EF39979D5F34DB9596AE33E5F357593233144E45625AB3394804`
SHA415 | `E6559BBD2BDEC517081D747F906B0FC628E1804C20CD5008595D7D7630B8977A23227156C65871B4BCE779C7C70274D66D4F12D93E6BB8950D3D3050F3789ED2`
SSDEEP | `384:3/fT3YrsguHvsI8EhE7meO2rtkyFnX91uwB19ml2RZPu5rHr04QKl4xIWv1Wcs0:3rYr0E55V1Ul0QtHr04QKexJ`

## Runtime Data
### Usage (stdout):
```Batchfile

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

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Register-CimProvider2.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


