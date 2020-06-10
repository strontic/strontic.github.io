
# Register-CimProvider.exe 
* File Path: `C:\WINDOWS\SysWOW64\Register-CimProvider.exe`
* Description: WMI
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `5B521425FEB037753F3AA9479A8A53A3`
SHA1 | `4C693398388184D9FE98083D68BF14F95C314B49`
SHA256 | `E971BB623A908F47E54AE84BD8C16FFA8D43C0A8CB1EEEC104FCEFA3119AE32F`
SHA384 | `5FF8820CB595AB4627B2414F24A4B8229E1823CD501609CDFAF05078A0100646EC569D14F2E626322B382498A3D609F1`
SHA415 | `74A40A6A4C217064AAFA0E35A620FF49ECDD937D1855DF504D9A1620748873EAE8D33849FD01EF5EC59F96CCD3899D66244C8CD1A12223742EE0281B0662D7CF`
SSDEEP | `384:R+4H6sKmxpfH5Uk/WQw43NaLfBmvBHVzrkgMOesekp4K7xAWv1WV:R+TlUx5Zp0LfAvBH0Sekp48xhs`

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
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
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


