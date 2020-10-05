---
title: Interceptor.dll | Microsoft Office Just-In-Time Virtualization Interceptor
excerpt: What is Interceptor.dll?
---

# Interceptor.dll 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\vfs\ProgramFilesX64\Microsoft Office\Office16\Interceptor.dll`
* Description: Microsoft Office Just-In-Time Virtualization Interceptor

## Hashes

Type | Hash
-- | --
MD5 | `C26921704F16CE5340205F5577661025`
SHA1 | `F8B4BB27874125C4CC4B30B4BE9F22AA0AF75A89`
SHA256 | `4169894938741C8E37B41B89A6FD14D38E4FF6E06F82D34BB74BE7570E4ACC90`
SHA384 | `C530ECEB46DB1EB9763E977D58B425BA7A68C27A21968A380DD2889C7E39FD46F1583314A5E24417D7BECF04BB20CBF1`
SHA512 | `F0FE78CDB3F1D55CC2C156824F87689B2072E86352809137CE785D8BFC4AE9D7991262A87BF2EC2E9AFDD67E511A6F46DEEC5DC542E7FADF9A9D6408706946DF`
SSDEEP | `24576:k/2zd8BQbmFf7MK7YyMCEokhLqLAhDFzQhScBZXJZ2JHX8fj6Fm9c6/r:0T2BkWw9c6T`
IMP | `E5D8D5CE78C1E96D4E65464D1BEEC149`
PESHA1 | `AE9167AFE0FE2CF2EF825D45285EF68827DDE2D4`
PE256 | `C6AC4EC76D6D141AD1C120940F682FD7F210FCDCFCA741CC06CA17C0019F3EEB`

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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/4169894938741c8e37b41b89a6fd14d38e4ff6e06f82d34bb74be7570e4acc90/detection/

## Possible Misuse

*The following table contains possible examples of `Interceptor.dll` being misused. While `Interceptor.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [powershell_nishang_malicious_commandlets.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_nishang_malicious_commandlets.yml) | `- Invoke-Interceptor` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [threat_lenovo_superfish.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/threat_lenovo_superfish.yar) | description = "Lenovo Superfish SSL Interceptor - file VisualDiscovery.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


