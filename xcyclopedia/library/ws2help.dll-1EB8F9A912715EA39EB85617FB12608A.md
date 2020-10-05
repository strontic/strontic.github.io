---
title: ws2help.dll | Windows Socket 2.0 Helper for Windows NT
excerpt: What is ws2help.dll?
---

# ws2help.dll 

* File Path: `C:\Windows\system32\ws2help.dll`
* Description: Windows Socket 2.0 Helper for Windows NT

## Hashes

Type | Hash
-- | --
MD5 | `1EB8F9A912715EA39EB85617FB12608A`
SHA1 | `D9C9D615BE07DCCCEB37D6A5B723BA8354023494`
SHA256 | `B45001D6EAABD3C87EAA1038C3FC8E912258FA7896C2B65117ED7DE2E83683F9`
SHA384 | `043A0F1E4B373B8249846D5CEA2A4E6920D80A0D007DCBE02F2D6A98A3201C25B20DBDA72E7ED380ED23D82F2F992E5A`
SHA512 | `CCAD16E0E4209872B3EF03EC62394C5954D8FCB0AE0916C8F4D8A73DFF266AA5161F3095FF173AB2D58A1A9C087FA53E4E469A87662A5C61726289D41EF48632`
SSDEEP | `48:iKhR5Q4Ja0Y+0IeaRiCn5yXHUhQqSA6AQj41j2tEIZWXoXuV25WwHg:jhJr0IeQ5yXuQJjUj2mEWYQmWw`
IMP | `n/a`
PESHA1 | `A282DE8EAE950279946ED737D3531A7BD72A4228`
PE256 | `50994214DCF859F69ECD717C0124387C7717FDA8374630C0604662C5BC332BEC`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`WahOpenApcHelper` | 16 | Exported Function
`WahOpenCurrentThread` | 17 | Exported Function
`WahOpenHandleHelper` | 18 | Exported Function
`WahEnumerateHandleContexts` | 13 | Exported Function
`WahInsertHandleContext` | 14 | Exported Function
`WahNotifyAllProcesses` | 15 | Exported Function
`WahRemoveHandleContext` | 22 | Exported Function
`WahWaitForNotification` | 23 | Exported Function
`WahWriteLSPEvent` | 24 | Exported Function
`WahOpenNotificationHandleHelper` | 19 | Exported Function
`WahQueueUserApc` | 20 | Exported Function
`WahReferenceContextByHandle` | 21 | Exported Function
`WahCloseSocketHandle` | 4 | Exported Function
`WahCloseThread` | 5 | Exported Function
`WahCompleteRequest` | 6 | Exported Function
`WahCloseApcHelper` | 1 | Exported Function
`WahCloseHandleHelper` | 2 | Exported Function
`WahCloseNotificationHandleHelper` | 3 | Exported Function
`WahDestroyHandleContextTable` | 10 | Exported Function
`WahDisableNonIFSHandleSupport` | 11 | Exported Function
`WahEnableNonIFSHandleSupport` | 12 | Exported Function
`WahCreateHandleContextTable` | 7 | Exported Function
`WahCreateNotificationHandle` | 8 | Exported Function
`WahCreateSocketHandle` | 9 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/b45001d6eaabd3c87eaa1038c3fc8e912258fa7896c2b65117ed7de2e83683f9/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\ws2help.dll](ws2help.dll-E32319E5947A76F8E50EC50C37906882.md) | 86

## Possible Misuse

*The following table contains possible examples of `ws2help.dll` being misused. While `ws2help.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | description = "Sample from CN Honker Pentest Toolset - file ws2help.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s1 = "\\ws2help.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


