---
title: ws2help.dll | Windows Socket 2.0 Helper for Windows NT
excerpt: What is ws2help.dll?
---

# ws2help.dll 

* File Path: `C:\Windows\SysWOW64\ws2help.dll`
* Description: Windows Socket 2.0 Helper for Windows NT

## Hashes

Type | Hash
-- | --
MD5 | `E32319E5947A76F8E50EC50C37906882`
SHA1 | `135A1ED2ADD1E8DDFF0920DF82E57078CA3CBD06`
SHA256 | `2A900AC21B85E6E32A502F24B804D8796A0D148B513D449AB4384323846D7DA9`
SHA384 | `9DB9A2E8D4A52070D3E6952FD00FC081A5DCE920614B856E4F8FCB7D392F8E1DE100D41C3441CAE84249F4B74D606586`
SHA512 | `5DEFF824DC784CDD44AE7C76B53EB9D212D1D9D2199F23D766325A2702180963BF52C40C6CC095C1F1584B2918DC9A7F4EEA7320904CAD147B48CD0A7F7584C0`
SSDEEP | `48:yZ/5Q4Ja0Y+0IeaRiCn5yXHUhQqSA6AqzrtEIZWXoXuV25WwHg:ohJr0IeQ5yXuQhrmEWYQmWw`
IMP | `n/a`
PESHA1 | `769E196BE031A4C83E8D15AA5EA16FE92D26C97A`
PE256 | `336B40EC36D6125BF9BA5C6EFD745EF6325D966843837EB3FACA91BC858BC056`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`WahCloseApcHelper` | 1 | Exported Function
`WahRemoveHandleContext` | 22 | Exported Function
`WahReferenceContextByHandle` | 21 | Exported Function
`WahQueueUserApc` | 20 | Exported Function
`WahOpenNotificationHandleHelper` | 19 | Exported Function
`WahOpenHandleHelper` | 18 | Exported Function
`WahOpenCurrentThread` | 17 | Exported Function
`WahOpenApcHelper` | 16 | Exported Function
`WahNotifyAllProcesses` | 15 | Exported Function
`WahInsertHandleContext` | 14 | Exported Function
`WahEnumerateHandleContexts` | 13 | Exported Function
`WahEnableNonIFSHandleSupport` | 12 | Exported Function
`WahDisableNonIFSHandleSupport` | 11 | Exported Function
`WahDestroyHandleContextTable` | 10 | Exported Function
`WahCreateSocketHandle` | 9 | Exported Function
`WahCreateNotificationHandle` | 8 | Exported Function
`WahCreateHandleContextTable` | 7 | Exported Function
`WahCompleteRequest` | 6 | Exported Function
`WahCloseThread` | 5 | Exported Function
`WahCloseSocketHandle` | 4 | Exported Function
`WahCloseNotificationHandleHelper` | 3 | Exported Function
`WahCloseHandleHelper` | 2 | Exported Function
`WahWaitForNotification` | 23 | Exported Function
`WahWriteLSPEvent` | 24 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ws2help.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/2a900ac21b85e6e32a502f24b804d8796a0d148b513d449ab4384323846d7da9/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ws2help.dll](ws2help.dll-1EB8F9A912715EA39EB85617FB12608A.md) | 86

## Possible Misuse

*The following table contains possible examples of `ws2help.dll` being misused. While `ws2help.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | description = "Sample from CN Honker Pentest Toolset - file ws2help.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s1 = "\\ws2help.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


