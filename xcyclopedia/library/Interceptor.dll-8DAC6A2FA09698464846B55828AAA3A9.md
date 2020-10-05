---
title: Interceptor.dll | Microsoft Office Just-In-Time Virtualization Interceptor
excerpt: What is Interceptor.dll?
---

# Interceptor.dll 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\Interceptor.dll`
* Description: Microsoft Office Just-In-Time Virtualization Interceptor

## Hashes

Type | Hash
-- | --
MD5 | `8DAC6A2FA09698464846B55828AAA3A9`
SHA1 | `D033A20D6E1CA9C98A5127451941877FEA533F44`
SHA256 | `D582C51CF8744BE6A4F7F4C3740F28F5B2E109A94A36C6B05322D2B873666ACA`
SHA384 | `423B7FC8AC1F799175941668D42113236D347A15F6327E79E1F550B3C9B38FCD02FF94BEEF3AB30EFCD1277AD2BEA0D7`
SHA512 | `19D021A1627034ECA15884714E80CDC3FAE903FBF60B07F05885B50C6B319457DB6CF50EFFA534408E9977959245538272A27063346D76DE238759A8DFDB88DD`
SSDEEP | `12288:Afs08KnHVDOwreC1/eDFtmbLKZbWf+r+U8pg0Munmd:oz8OVDOme1DQLKtWQ8pg7D`
IMP | `960AC0E3D89E10F09CAEA97F2BFF36E2`
PESHA1 | `5E5A2783988F18002850B5358716DE5C4F18D516`
PE256 | `B144BD95A475E52D93B5742CD5F4C1E7B5D516BA1855121691956F5A5E3AD074`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Interceptor.dll
* Product Name: Microsoft Office
* Company Name: Microsoft Corporation
* File Version: 16.0.12527.20122
* Product Version: 16.0.12527.20122
* Language: Language Neutral
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/d582c51cf8744be6a4f7f4c3740f28f5b2e109a94a36c6b05322d2b873666aca/detection/

## Possible Misuse

*The following table contains possible examples of `Interceptor.dll` being misused. While `Interceptor.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [powershell_nishang_malicious_commandlets.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_nishang_malicious_commandlets.yml) | `- Invoke-Interceptor` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [threat_lenovo_superfish.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/threat_lenovo_superfish.yar) | description = "Lenovo Superfish SSL Interceptor - file VisualDiscovery.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


