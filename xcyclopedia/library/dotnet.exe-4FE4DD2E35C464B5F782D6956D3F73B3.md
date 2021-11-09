---
title: dotnet.exe | .NET Host
excerpt: What is dotnet.exe?
---

# dotnet.exe 

* File Path: `C:\Program Files (x86)\dotnet\dotnet.exe`
* Description: .NET Host

## Hashes

Type | Hash
-- | --
MD5 | `4FE4DD2E35C464B5F782D6956D3F73B3`
SHA1 | `2A1FFC99421B72E60E3FB05D929D02113897E39F`
SHA256 | `FC799367F5DDB02755D3938C92A56262474FD9CA65BA53E5EFDD5021A2584DEB`
SHA384 | `94E7D92E907766005204BA5D94C4907FE44E32241F195CF29408B95504065543419375CD7FD0BC6CBE88B9013A8C3018`
SHA512 | `884BD4C536B8CD9A94A58E53C58841D80DBA0516E715E851289573D79C8A5C7DF1D3C6483DABAA01BF82C5124B2F41E5DCE6EC38C4EB091E551C429875F469C6`
SSDEEP | `1536:UbLCZr5dWxsi5LYTnfO8EDWWTQ/LgVSvxOqJJv6:s0lda5LYz2SWTQDUSvxOqJs`
IMP | `EE48FA1B7817CEDC1F4A0F042EAF60DC`
PESHA1 | `DFD01ADBB28CE1DC08A0E13155D51D99704EE903`
PE256 | `AA81198F121A0F79E262FF5D76C6DC7A8F144B2B4AEEC609827618810FB535B6`

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
C:\Program Files (x86)\dotnet\dotnet.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/fc799367f5ddb02755d3938c92a56262474fd9ca65ba53e5efdd5021a2584deb/detection


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


