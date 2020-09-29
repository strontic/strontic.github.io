---
title: netshell.dll | Network Connections Shell
excerpt: What is netshell.dll?
---

# netshell.dll 

* File Path: `C:\Windows\system32\netshell.dll`
* Description: Network Connections Shell

## Hashes

Type | Hash
-- | --
MD5 | `F6FF45CE958AD44794B8952C889CF268`
SHA1 | `BCC1BB8B2EB913B7024D8C528FCDBE0FEA1E739D`
SHA256 | `04057FB88394F87B34333D3D64CFF20A726A4564073E9862513721B6A2E917FA`
SHA384 | `BE761B6F581D7F9AC5DB1F5E6E0A03A0B4465B62C36A856629C16FD805F9FD3E0B7A82762A2C1718BD91866F5E2E308E`
SHA512 | `2D0546B578AEBA96884344350050FFCF0E38E1329FDBEAD4F7E4329E09CFF42F1145B8D97AEF061DEDE4C3BFE8DE2F3575F7DFAAAE203AA93E53444B1CD4B11C`
SSDEEP | `12288:ZHI+g3O/XMCBfohZrJ4ZQ52vtVSSDp2P7iwE:ZH3zProhZrJGP3qWw`
IMP | `91D7C52FF7AFD37A74F332C17F93C43B`
PESHA1 | `85348D4F0AA22AE8B9AC962FD0FCFD4852A3C758`
PE256 | `6A65CE7CBBD3D9104BA1C2E4E50271ADF4059C85179F78243442B7366002B931`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x000000018000f260 | 0x0000f260
`DllGetClassObject` | 2 (0x2) | Exported Function | 0x000000018000f2a0 | 0x0000f2a0
`DllRegisterServer` | 3 (0x3) | Exported Function | 0x00000001800020a0 | 0x000020a0
`DllUnregisterServer` | 4 (0x4) | Exported Function | 0x00000001800020a0 | 0x000020a0
`HrCreateDesktopIcon` | 5 (0x5) | Exported Function | 0x000000018000f350 | 0x0000f350
`HrGetIconFromMediaType` | 6 (0x6) | Exported Function | 0x000000018000f460 | 0x0000f460
`HrGetIconFromMediaTypeEx` | 7 (0x7) | Exported Function | 0x000000018000f4d0 | 0x0000f4d0
`HrLaunchConnection` | 8 (0x8) | Exported Function | 0x000000018000f530 | 0x0000f530
`HrLaunchConnectionEx` | 9 (0x9) | Exported Function | 0x000000018000f620 | 0x0000f620
`HrRenameConnection` | 10 (0xa) | Exported Function | 0x000000018000f7c0 | 0x0000f7c0
`NcFreeNetconProperties` | 11 (0xb) | Exported Function | 0x000000018000f9e0 | 0x0000f9e0
`NcIsValidConnectionName` | 12 (0xc) | Exported Function | 0x000000018000f9f0 | 0x0000f9f0
`StartNCW` | 13 (0xd) | Exported Function | 0x0000000180002140 | 0x00002140


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: netshell.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/04057fb88394f87b34333d3d64cff20a726a4564073e9862513721b6a2e917fa/detection/


## Possible Misuse

*The following table contains possible examples of `netshell.dll` being misused. While `netshell.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `- Link: https://htmlpreview.github.io/?https://github.com/MatthewDemaske/blogbackup/blob/master/netshell.html` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | <blockquote>Adversaries may establish persistence by executing malicious content triggered by Netsh Helper DLLs. Netsh.exe (also referred to as Netshell) is a command-line scripting utility used to interact with the network configuration of a system. It contains functionality to add helper DLLs for extending functionality of the utility. (Citation: TechNet Netsh) The paths to registered netsh.exe helper DLLs are entered into the Windows Registry at <code>HKLM\SOFTWARE\Microsoft\Netsh</code>. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


