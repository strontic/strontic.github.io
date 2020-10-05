---
title: MicrosoftAccountTokenProvider.dll | Microsoft Account Token Provider
excerpt: What is MicrosoftAccountTokenProvider.dll?
---

# MicrosoftAccountTokenProvider.dll 

* File Path: `C:\Windows\system32\MicrosoftAccountTokenProvider.dll`
* Description: Microsoft Account Token Provider

## Hashes

Type | Hash
-- | --
MD5 | `2151CB4BDACC68F74E52BFAD57D7572F`
SHA1 | `DB474619F6F3D3D806BE21B44238E68FBDC37FC9`
SHA256 | `E6088D0BA8CF80348C29FF019D0FC488CCC4585F13BA93ABFCE513B0A98C1D05`
SHA384 | `387F3ABCED2FC257363975D89C8938BF792F88CAEC67D9537F045ADE218A96B3E71AAE494C7BD94E968232306E995A8D`
SHA512 | `5880690DDA759AF5CE99D81E4EC9FCF94D53F154F2FAB35DE3B6311E5E11FCA38DF046FE33237FD5E0313F4327E011C676D6AD8D8E205430B99F49026899443C`
SSDEEP | `6144:M93Sl099EuLVFWTjj8uMQV1WliBe45pYDz1eOI:ll04ifEH1MQTkP1/I`
IMP | `98AC6D4CB512E110FCD8C0A53C1EEE3C`
PESHA1 | `C7F612DB80743A76AEFCCEDD57EB05713E19A190`
PE256 | `178B63B5C311ECF5408B7FB7BCC0D32FE2284FC119D85FCE43F8B5E02AE5E0FD`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MicrosoftAccountTokenProvider.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/e6088d0ba8cf80348c29ff019d0fc488ccc4585f13ba93abfce513b0a98c1d05/detection/


## Possible Misuse

*The following table contains possible examples of `MicrosoftAccountTokenProvider.dll` being misused. While `MicrosoftAccountTokenProvider.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_abusing_azure_browser_sso.yml) | `ImageLoaded\|endswith: MicrosoftAccountTokenProvider.dll` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


