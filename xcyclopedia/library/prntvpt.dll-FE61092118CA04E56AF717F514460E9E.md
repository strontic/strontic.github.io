---
title: prntvpt.dll | Print Ticket Services Module
excerpt: What is prntvpt.dll?
---

# prntvpt.dll 

* File Path: `C:\Windows\SysWOW64\prntvpt.dll`
* Description: Print Ticket Services Module

## Hashes

Type | Hash
-- | --
MD5 | `FE61092118CA04E56AF717F514460E9E`
SHA1 | `070C9A3F5E8E98BFAEC2AA0550CD94DEF3EC25FC`
SHA256 | `6A1FA85419C36BEB5787FE721110271057F56E20329FB3E77A353892D95D8EE4`
SHA384 | `ECA68CAD1C66CC476966E22BCE0718E9275BEB1B6011FBA2860D2A06AC9FB566CBEF0B1D5D8788325211360DC3DBA3E2`
SHA512 | `418B8798E16C29688B48BEDE795C5B4EAA92AF1BAEBADE2A76B6990854A619EF995009D1496B708926A897F71E3141193CDF07730A9071E09AE4455A431CE3D7`
SSDEEP | `3072:AsYy+legwiEUs/PDkOBmklzPHRwOf5Zw2C4Y0CVpq6bxTToXlyaFgueaxBHFI7ht:zYy0eDUcPDkEmklzPHRjf5ZwOY0CVpt7`
IMP | `E53ED2D1288240EED8FDB03401A7834F`
PESHA1 | `963156DD9D97AFB5085F1E6CBF1DD0CA6AF3AE0B`
PE256 | `DD81DAC881290A06F86D4E0E7EFE19B022EA82B6ABA9B4B60FFE8B1B73434E56`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`BindPTProviderThunk` | 5 (0x5) | Exported Function | 0x1000d7a0 | 0x0000d7a0
`PTQuerySchemaVersionSupport` | 1 (0x1) | Exported Function | 0x1000d4a0 | 0x0000d4a0
`PTOpenProviderEx` | 3 (0x3) | Exported Function | 0x1000d320 | 0x0000d320
`PTOpenProvider` | 2 (0x2) | Exported Function | 0x1000d1b0 | 0x0000d1b0
`PTMergeAndValidatePrintTicket` | 7 (0x7) | Exported Function | 0x1000d0c0 | 0x0000d0c0
`PTGetPrintDeviceResources` | 12 (0xc) | Exported Function | 0x1000cf80 | 0x0000cf80
`PTGetPrintDeviceCapabilities` | 11 (0xb) | Exported Function | 0x1000ce50 | 0x0000ce50
`PTGetPrintCapabilities` | 6 (0x6) | Exported Function | 0x1000cd70 | 0x0000cd70
`PTConvertPrintTicketToDevMode` | 8 (0x8) | Exported Function | 0x1000cc10 | 0x0000cc10
`PTConvertDevModeToPrintTicket` | 9 (0x9) | Exported Function | 0x1000cb60 | 0x0000cb60
`PTCloseProvider` | 4 (0x4) | Exported Function | 0x1000cab0 | 0x0000cab0
`MergeAndValidatePrintTicketThunk2` | 31 (0x1f) | Exported Function | 0x1000dd70 | 0x0000dd70
`MergeAndValidatePrintTicketThunk` | 32 (0x20) | Exported Function | 0x1000de60 | 0x0000de60
`GetSchemaVersionThunk` | 30 (0x1e) | Exported Function | 0x10007ef0 | 0x00007ef0
`GetPrintDeviceResourcesThunk2` | 28 (0x1c) | Exported Function | 0x1000dc50 | 0x0000dc50
`PTReleaseMemory` | 10 (0xa) | Exported Function | 0x1000d550 | 0x0000d550
`GetPrintDeviceResourcesThunk` | 29 (0x1d) | Exported Function | 0x1000dd30 | 0x0000dd30
`GetPrintDeviceCapabilitiesThunk` | 27 (0x1b) | Exported Function | 0x1000dc10 | 0x0000dc10
`GetPrintCapabilitiesThunk2` | 24 (0x18) | Exported Function | 0x1000da30 | 0x0000da30
`GetPrintCapabilitiesThunk` | 25 (0x19) | Exported Function | 0x1000daf0 | 0x0000daf0
`GetDeviceNamespacesThunk` | 23 (0x17) | Exported Function | 0x1000da20 | 0x0000da20
`GetDeviceDefaultPrintTicketThunk` | 22 (0x16) | Exported Function | 0x1000da20 | 0x0000da20
`DllUnregisterServer` | 21 (0x15) | Exported Function | 0x1000c660 | 0x0000c660
`DllRegisterServer` | 20 (0x14) | Exported Function | 0x1000c620 | 0x0000c620
`DllMain` | 19 (0x13) | Exported Function | 0x100091c0 | 0x000091c0
`DllGetClassObject` | 18 (0x12) | Exported Function | 0x1000c5e0 | 0x0000c5e0
`DllCanUnloadNow` | 17 (0x11) | Exported Function | 0x1000c5a0 | 0x0000c5a0
`ConvertPrintTicketToDevModeThunk2` | 15 (0xf) | Exported Function | 0x1000d900 | 0x0000d900
`ConvertPrintTicketToDevModeThunk` | 16 (0x10) | Exported Function | 0x1000d9e0 | 0x0000d9e0
`ConvertDevModeToPrintTicketThunk2` | 13 (0xd) | Exported Function | 0x1000d840 | 0x0000d840
`ConvertDevModeToPrintTicketThunk` | 14 (0xe) | Exported Function | 0x1000d8c0 | 0x0000d8c0
`GetPrintDeviceCapabilitiesThunk2` | 26 (0x1a) | Exported Function | 0x1000db30 | 0x0000db30
`UnbindPTProviderThunk` | 33 (0x21) | Exported Function | 0x1000dea0 | 0x0000dea0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: prntvpt.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/6a1fa85419c36beb5787fe721110271057f56e20329fb3e77a353892d95d8ee4/detection/





MIT License. Copyright (c) 2020 Strontic.


