---
title: dotnet.exe | .NET Host
excerpt: What is dotnet.exe?
---

# dotnet.exe 

* File Path: `C:\Program Files\dotnet\dotnet.exe`
* Description: .NET Host

## Hashes

Type | Hash
-- | --
MD5 | `272CDDFC6B97F1DDC063F74A14E5DEB2`
SHA1 | `C591CEE8FA791C7E274B963076E24571E1BCC62B`
SHA256 | `0BBB5E1FA31AC3ABB683248029253473208164B6316690B7CF49D50998413315`
SHA384 | `244E7F9EDA331FB6F1B2AB7ED89B64AF391FA64ADC8F76CD9A68110DBE0C67B3BD72B6622A2D651BE765413E3CD3170A`
SHA512 | `3515E7B03F2126F6B193B8EE246E58053BEF1D5B1D953BCE226A575FC12342A85C3228298C07733C91F47149FA58F465A7D744E63ED9C8AC5C8F7F763E68EF34`
SSDEEP | `1536:x5VA8oZ1/J0dFnN3Apba/oKtE/TCqeuZyZQY0SNxlnOWBbTeYPd9q8vC:x/AXZ1/J0dFnNjBuZm7lOWVTeYbq3`
IMP | `D4302BD193807917EC02AF210C811651`
PESHA1 | `A3DB24F0C40A015CD3567769B2ACD434D884AC90`
PE256 | `E26AFF5611A6714CB64C9E2111457F940747A182E945FA874D72568E503D0586`

## Runtime Data

### Usage (stdout):
```cmhg

Usage: dotnet [host-options] [path-to-application]

path-to-application:
  The path to an application .dll file to execute.

host-options:
  --additionalprobingpath <path>  Path containing probing policy and assemblies to probe for.
  --depsfile <path>               Path to <application>.deps.json file.
  --runtimeconfig <path>          Path to <application>.runtimeconfig.json file.
  --fx-version <version>          Version of the installed Shared Framework to use to run the application.
  --roll-forward <value>          Roll forward to framework version (LatestPatch, Minor, LatestMinor, Major, LatestMajor, Disable)
  --additional-deps <path>        Path to additional deps.json file.
  --list-runtimes                 Display the installed runtimes
  --list-sdks                     Display the installed SDKs

Common Options:
  -h|--help                           Displays this help.
  --info                              Display .NET information.

```

### Usage (stderr):
```cmhg
Could not execute because the application was not found or a compatible .NET SDK is not installed.
Possible reasons for this include:
  * You intended to execute a .NET program:
      The application '-help' does not exist.
  * You intended to execute a .NET SDK command:
      It was not possible to find any installed .NET SDKs.
      Install a .NET SDK from:
        https://aka.ms/dotnet-download

```

### Loaded Modules:

Path |
-- |
C:\Program Files\dotnet\dotnet.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001DF6BF02E92A74AB4D00000000001DF`
* Thumbprint: `ABDCA79AF9DD48A0EA702AD45260B3C03093FB4B`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: .NET Host
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 5,0,1121,47308 @Commit: f431858f8b1f1510723ace6343786c9194dbd7fc
* Product Version: 5.0.11 @Commit: f431858f8b1f1510723ace6343786c9194dbd7fc
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/0bbb5e1fa31ac3abb683248029253473208164b6316690b7cf49d50998413315/detection


## Possible Misuse

*The following table contains possible examples of `dotnet.exe` being misused. While `dotnet.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_etw_modification.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_etw_modification.yml) | `- https://github.com/dotnet/runtime/blob/ee2355c801d892f2894b0f7b14a20e6cc50e0e54/docs/design/coreclr/jit/viewing-jit-dumps.md#setting-configuration-variables`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_etw_modification.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_etw_modification.yml) | `- https://github.com/dotnet/runtime/blob/f62e93416a1799aecc6b0947adad55a0d9870732/src/coreclr/src/inc/clrconfigvalues.h#L35-L38`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_etw_modification.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_etw_modification.yml) | `- https://github.com/dotnet/runtime/blob/7abe42dc1123722ed385218268bb9fe04556e3d3/src/coreclr/src/inc/clrconfig.h#L33-L39`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_etw_modification.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_etw_modification.yml) | `- https://github.com/dotnet/runtime/search?p=1&q=COMPlus_&unscoped_q=COMPlus_`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_etw_modification.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_etw_modification.yml) | `- https://github.com/dotnet/runtime/blob/4f9ae42d861fcb4be2fcd5d3d55d5f227d30e723/docs/coding-guidelines/clr-jit-coding-conventions.md#1412-disabling-code`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_mshta_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_mshta_execution.yml) | `- https://docs.microsoft.com/en-us/dotnet/standard/data/xml/xslt-stylesheet-scripting-using-msxsl-script`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_office_dotnet_assembly_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_office_dotnet_assembly_dll_load.yml) | `title: dotNET DLL Loaded Via Office Applications`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_dotnet.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_dotnet.yml) | `title: Dotnet.exe Exec Dll and Execute Unsigned Code LOLBIN`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_dotnet.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_dotnet.yml) | `description: dotnet.exe will execute any DLL and execute unsigned code`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_dotnet.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_dotnet.yml) | `- https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_dotnet.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_dotnet.yml) | `- https://bohops.com/2019/08/19/dotnet-core-a-vector-for-awl-bypass-defense-evasion/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_dotnet.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_dotnet.yml) | `- '\dotnet.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml) | `- https://docs.microsoft.com/en-us/dotnet/framework/data/wcf/wcf-data-service-client-utility-datasvcutil-exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml) | `- https://docs.microsoft.com/en-us/dotnet/framework/data/wcf/generating-the-data-service-client-library-wcf-data-services`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml) | `- https://docs.microsoft.com/en-us/dotnet/framework/data/wcf/how-to-add-a-data-service-reference-wcf-data-services`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_bad_opsec_sacrificial_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bad_opsec_sacrificial_processes.yml) | `- https://docs.microsoft.com/en-us/dotnet/framework/tools/regasm-exe-assembly-registration-tool`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_bad_opsec_sacrificial_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bad_opsec_sacrificial_processes.yml) | `- https://docs.microsoft.com/en-us/dotnet/framework/tools/regsvcs-exe-net-services-installation-tool#feedback`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_etw_modification_cmdline.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_etw_modification_cmdline.yml) | `- https://github.com/dotnet/runtime/blob/ee2355c801d892f2894b0f7b14a20e6cc50e0e54/docs/design/coreclr/jit/viewing-jit-dumps.md#setting-configuration-variables`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_etw_modification_cmdline.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_etw_modification_cmdline.yml) | `- https://github.com/dotnet/runtime/blob/f62e93416a1799aecc6b0947adad55a0d9870732/src/coreclr/src/inc/clrconfigvalues.h#L35-L38`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_etw_modification_cmdline.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_etw_modification_cmdline.yml) | `- https://github.com/dotnet/runtime/blob/7abe42dc1123722ed385218268bb9fe04556e3d3/src/coreclr/src/inc/clrconfig.h#L33-L39`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_etw_modification_cmdline.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_etw_modification_cmdline.yml) | `- https://github.com/dotnet/runtime/search?p=1&q=COMPlus_&unscoped_q=COMPlus_`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_etw_modification_cmdline.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_etw_modification_cmdline.yml) | `- https://github.com/dotnet/runtime/blob/4f9ae42d861fcb4be2fcd5d3d55d5f227d30e723/docs/coding-guidelines/clr-jit-coding-conventions.md#1412-disabling-code`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_etw_disabled.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_etw_disabled.yml) | `- https://github.com/dotnet/runtime/blob/ee2355c801d892f2894b0f7b14a20e6cc50e0e54/docs/design/coreclr/jit/viewing-jit-dumps.md#setting-configuration-variables`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_etw_disabled.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_etw_disabled.yml) | `- https://github.com/dotnet/runtime/blob/f62e93416a1799aecc6b0947adad55a0d9870732/src/coreclr/src/inc/clrconfigvalues.h#L35-L38`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_etw_disabled.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_etw_disabled.yml) | `- https://github.com/dotnet/runtime/blob/7abe42dc1123722ed385218268bb9fe04556e3d3/src/coreclr/src/inc/clrconfig.h#L33-L39`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_etw_disabled.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_etw_disabled.yml) | `- https://github.com/dotnet/runtime/search?p=1&q=COMPlus_&unscoped_q=COMPlus_`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_etw_disabled.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_etw_disabled.yml) | `- https://github.com/dotnet/runtime/blob/4f9ae42d861fcb4be2fcd5d3d55d5f227d30e723/docs/coding-guidelines/clr-jit-coding-conventions.md#1412-disabling-code`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Aspnet_Compiler.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Aspnet_Compiler.yml) | `- Link: https://docs.microsoft.com/en-us/dotnet/api/system.web.compilation.buildprovider.generatecode?view=netframework-4.8`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Csc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Csc.yml) | `- Link: https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/compiler-options/command-line-building-with-csc-exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [DataSvcUtil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/DataSvcUtil.yml) | `- Link: https://docs.microsoft.com/en-us/dotnet/framework/data/wcf/wcf-data-service-client-utility-datasvcutil-exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [DataSvcUtil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/DataSvcUtil.yml) | `- Link: https://docs.microsoft.com/en-us/dotnet/framework/data/wcf/generating-the-data-service-client-library-wcf-data-services`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [DataSvcUtil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/DataSvcUtil.yml) | `- Link: https://docs.microsoft.com/en-us/dotnet/framework/data/wcf/how-to-add-a-data-service-reference-wcf-data-services`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `- Link: https://docs.microsoft.com/en-us/dotnet/framework/tools/installutil-exe-installer-tool`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `Name: Dotnet.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `Description: dotnet.exe comes with .NET Framework`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `- Command: dotnet.exe [PATH_TO_DLL]`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `Description: dotnet.exe will execute any dll even if applocker is enabled.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `Description: dotnet.exe will execute any DLL.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `- Command: dotnet.exe msbuild [Path_TO_XML_CSPROJ]`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `Description: dotnet.exe with msbuild (SDK Version) will execute unsigned code`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `- Path: 'C:\Program Files\dotnet\dotnet.exe'`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `- IOC: dotnet.exe spawned an unknown process`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `- Link: https://bohops.com/2019/08/19/dotnet-core-a-vector-for-awl-bypass-defense-evasion/`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Fsi.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Fsi.yml) | `Description: 64-bit FSharp (F#) Interpreter included with Visual Studio and DotNet Core SDK.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Fsi.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Fsi.yml) | `- Path: C:\Program Files\dotnet\sdk\[sdk version]\FSharp\fsi.exe`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | \| output_file \| Path where resulting dump should be placed \| Path \| C:&#92;Windows&#92;Temp&#92;dotnet-lsass.dmp\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | \| createdump_exe \| Path of createdump.exe executable \| Path \| C:&#92;Program Files&#92;dotnet&#92;shared&#92;Microsoft.NETCore.App&#92;5.*.*&#92;createdump.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1006.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1006/T1006.md) | This test uses PowerShell to open a handle on the drive volume via the `\\.\` [DOS device path specifier](https://docs.microsoft.com/en-us/dotnet/standard/io/file-path-formats#dos-device-paths) and perform direct access read of the first few bytes of the volume. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | [Graphics.CopyFromScreen]: https://docs.microsoft.com/en-us/dotnet/api/system.drawing.graphics.copyfromscreen | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) | $DOTNET = "mscorlib" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) | (uint16(0) == 0x5A4D) and ($DOTNET) and ($REF_URL) and | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) | $DOTNET= "mscorlib" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_github_net_redteam_tools_guids.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_github_net_redteam_tools_guids.yar) | // Could also be done with https://yara.readthedocs.io/en/stable/modules/dotnet.html#c.typelib but that needs an extra module. | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_github_net_redteam_tools_guids.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_github_net_redteam_tools_guids.yar) | reference = "https://github.com/countercept/dotnet-gargoyle" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


