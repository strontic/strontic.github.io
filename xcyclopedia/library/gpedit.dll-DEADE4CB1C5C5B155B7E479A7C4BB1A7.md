---
title: gpedit.dll | GPEdit
excerpt: What is gpedit.dll?
---

# gpedit.dll 

* File Path: `C:\Windows\system32\gpedit.dll`
* Description: GPEdit

## Hashes

Type | Hash
-- | --
MD5 | `DEADE4CB1C5C5B155B7E479A7C4BB1A7`
SHA1 | `0B8BDBC8A78EDCD565784772B0EFFF185BACD1FA`
SHA256 | `8C87003B0FDD9EC226966C60384D90DFD0129529A451954C8257FA2C1FE84887`
SHA384 | `B6366EDF05F4ADEC4A4CEE709B10955CDF02A14D6AB0CF3D0873E5C6E88BE50B8137ED12A95DF5F21529E3970F28A909`
SHA512 | `68339516989D2ED42FEA6644ED8D56B60CCEA38EB66BCCFD0F1DE4D7A33F22345A08D37705D6049C662A114828F52B413A1C3469ED7785311D0647DE4C21DD46`
SSDEEP | `6144:aL6kfasBtMyIJQ/WePgh7x76jjIJwN49blqm2uf3DcaPMH499AwWR6I6kYcsL:vByIqujb2Y8k79EH7RXYcsL`
IMP | `B37ED561FA2926FEAD4C0D85DC48EF3D`
PESHA1 | `C424827580FAFE392FAD8A1CC2B351BA39C9BA82`
PE256 | `E950BFE772DBC770C5F84C19BCC7135646525013029085462B70796B84E41647`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllGetClassObject` | 109 | Exported Function
`DllCanUnloadNow` | 108 | Exported Function
`ImportRSoPData` | 111 | Exported Function
`ExportRSoPData` | 110 | Exported Function
`CreateGPOLink` | 105 | Exported Function
`BrowseForGPO` | 104 | Exported Function
`DeleteGPOLink` | 107 | Exported Function
`DeleteAllGPOLinks` | 106 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: gpedit.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/8c87003b0fdd9ec226966c60384d90dfd0129529a451954c8257fa2c1fe84887/detection/


## Possible Misuse

*The following table contains possible examples of `gpedit.dll` being misused. While `gpedit.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_disable_event_logging.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_disable_event_logging.yml) | `description: 'Detects scenarios where system auditing (ie: windows event log auditing) is disabled. This may be used in a scenario where an entity would want to bypass local logging to evade detection when windows event logging is enabled and reviewed. Also, it is recommended to turn off "Local Group Policy Object Processing" via GPO, which will make sure that Active Directory GPOs take precedence over local/edited computer policies via something such as "gpedit.msc". Please note, that disabling "Local Group Policy Object Processing" may cause an issue in scenarios of one off specific GPO modifications -- however it is recommended to perform these modifications in Active Directory anyways.'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


