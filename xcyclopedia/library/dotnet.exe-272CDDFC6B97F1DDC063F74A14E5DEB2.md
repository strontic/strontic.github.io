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
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_dotnet.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_dotnet.yml) | `title: Dotnet.exe Exec Dll and Execute Unsigned Code LOLBIN`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_dotnet.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_dotnet.yml) | `description: dotnet.exe will execute any DLL and execute unsigned code`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_dotnet.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_dotnet.yml) | `- '\dotnet.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `Name: Dotnet.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `Description: dotnet.exe comes with .NET Framework`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `- Command: dotnet.exe [PATH_TO_DLL]`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `Description: dotnet.exe will execute any dll even if applocker is enabled.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `Description: dotnet.exe will execute any DLL.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `- Command: dotnet.exe msbuild [Path_TO_XML_CSPROJ]`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `Description: dotnet.exe with msbuild (SDK Version) will execute unsigned code`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `- Path: 'C:\Program Files\dotnet\dotnet.exe'`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `- IOC: dotnet.exe spawned an unknown process`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


