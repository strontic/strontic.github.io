---
title: prntvpt.dll | Print Ticket Services Module
excerpt: What is prntvpt.dll?
---

# prntvpt.dll 

* File Path: `C:\Windows\system32\prntvpt.dll`
* Description: Print Ticket Services Module

## Hashes

Type | Hash
-- | --
MD5 | `9CCCD3091B94711B1A0C8746B5E43F56`
SHA1 | `BF73EC81982F5A9ECC963775F58022BC6A0A35CE`
SHA256 | `9FFE292FA03C14FB30E9F7B59B03882E3B8377E42AF2675AD6430B59B01EC598`
SHA384 | `38D279363A721A4B2265CF80CF379302275128CCBF4A1B9F55FDF7E3E17E02AE28DEEAEB981E868FAFCA4E822F483A3A`
SHA512 | `37A2A21A180632D06AD9CD5CE9FF44059F6C393C02ADCC71A35AD37FBE45FDF16C18F52A6A94D57A7E8C4D09BA9135511C7EFE523D7E54FF5398BEF5A43F127C`
SSDEEP | `3072:1XOjHEWV6rUfKf8WIcq/4hVrmc0YyFGuuwNiNq5mYekR:1XOjHEC6YfKfnPqQhOYy7aN`
IMP | `13ED99C01641467696E13DBF42FC6EDF`
PESHA1 | `9F4C94C6005BA448073D44BDBA6BF91C20FABC2D`
PE256 | `97EAAAF8514685D484AB72428F5B7BDEDBDBC6757FD155FB4BDED950CA7E44E0`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`BindPTProviderThunk` | 5 (0x5) | Exported Function | 0x000000018000fa10 | 0x0000fa10
`PTQuerySchemaVersionSupport` | 1 (0x1) | Exported Function | 0x000000018000f650 | 0x0000f650
`PTOpenProviderEx` | 3 (0x3) | Exported Function | 0x0000000180006a70 | 0x00006a70
`PTOpenProvider` | 2 (0x2) | Exported Function | 0x000000018000f490 | 0x0000f490
`PTMergeAndValidatePrintTicket` | 7 (0x7) | Exported Function | 0x000000018000f370 | 0x0000f370
`PTGetPrintDeviceResources` | 12 (0xc) | Exported Function | 0x000000018000f220 | 0x0000f220
`PTGetPrintDeviceCapabilities` | 11 (0xb) | Exported Function | 0x000000018000f0e0 | 0x0000f0e0
`PTGetPrintCapabilities` | 6 (0x6) | Exported Function | 0x0000000180007dc0 | 0x00007dc0
`PTConvertPrintTicketToDevMode` | 8 (0x8) | Exported Function | 0x000000018000ef40 | 0x0000ef40
`PTConvertDevModeToPrintTicket` | 9 (0x9) | Exported Function | 0x0000000180007e80 | 0x00007e80
`PTCloseProvider` | 4 (0x4) | Exported Function | 0x0000000180007f30 | 0x00007f30
`MergeAndValidatePrintTicketThunk2` | 32 (0x20) | Exported Function | 0x0000000180010130 | 0x00010130
`MergeAndValidatePrintTicketThunk` | 31 (0x1f) | Exported Function | 0x00000001800100e0 | 0x000100e0
`GetSchemaVersionThunk` | 30 (0x1e) | Exported Function | 0x0000000180001170 | 0x00001170
`GetPrintDeviceResourcesThunk2` | 29 (0x1d) | Exported Function | 0x000000018000ffe0 | 0x0000ffe0
`PTReleaseMemory` | 10 (0xa) | Exported Function | 0x000000018000f750 | 0x0000f750
`GetPrintDeviceResourcesThunk` | 28 (0x1c) | Exported Function | 0x000000018000ffa0 | 0x0000ffa0
`GetPrintDeviceCapabilitiesThunk` | 26 (0x1a) | Exported Function | 0x000000018000fe70 | 0x0000fe70
`GetPrintCapabilitiesThunk2` | 25 (0x19) | Exported Function | 0x000000018000fda0 | 0x0000fda0
`GetPrintCapabilitiesThunk` | 24 (0x18) | Exported Function | 0x000000018000fd70 | 0x0000fd70
`GetDeviceNamespacesThunk` | 23 (0x17) | Exported Function | 0x000000018000fd60 | 0x0000fd60
`GetDeviceDefaultPrintTicketThunk` | 22 (0x16) | Exported Function | 0x000000018000fd60 | 0x0000fd60
`DllUnregisterServer` | 21 (0x15) | Exported Function | 0x000000018000ec50 | 0x0000ec50
`DllRegisterServer` | 20 (0x14) | Exported Function | 0x000000018000ebd0 | 0x0000ebd0
`DllMain` | 19 (0x13) | Exported Function | 0x0000000180009520 | 0x00009520
`DllGetClassObject` | 18 (0x12) | Exported Function | 0x000000018000eb20 | 0x0000eb20
`DllCanUnloadNow` | 17 (0x11) | Exported Function | 0x000000018000eab0 | 0x0000eab0
`ConvertPrintTicketToDevModeThunk2` | 16 (0x10) | Exported Function | 0x000000018000fc30 | 0x0000fc30
`ConvertPrintTicketToDevModeThunk` | 15 (0xf) | Exported Function | 0x000000018000fbe0 | 0x0000fbe0
`ConvertDevModeToPrintTicketThunk2` | 14 (0xe) | Exported Function | 0x000000018000fb30 | 0x0000fb30
`ConvertDevModeToPrintTicketThunk` | 13 (0xd) | Exported Function | 0x000000018000faf0 | 0x0000faf0
`GetPrintDeviceCapabilitiesThunk2` | 27 (0x1b) | Exported Function | 0x000000018000fea0 | 0x0000fea0
`UnbindPTProviderThunk` | 33 (0x21) | Exported Function | 0x0000000180010240 | 0x00010240


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: prntvpt.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/9ffe292fa03c14fb30e9f7b59b03882e3b8377e42af2675ad6430b59b01ec598/detection/





MIT License. Copyright (c) 2020 Strontic.


