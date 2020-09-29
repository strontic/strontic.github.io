---
title: PSHED.DLL | Platform Specific Hardware Error Driver
excerpt: What is PSHED.DLL?
---

# PSHED.DLL 

* File Path: `C:\Windows\system32\PSHED.DLL`
* Description: Platform Specific Hardware Error Driver

## Hashes

Type | Hash
-- | --
MD5 | `DC61643CD353AA826F2B8DF06422B266`
SHA1 | `7EC8F511717A71F692A79A27E348C6654D0D6F40`
SHA256 | `27858972C18AFCCD944453B72FEEEBA66B1587F2075087780AA4FC54202D8221`
SHA384 | `8DEBE54174216AE604A7DB2C1881AF118AF937718BDC93A3C8EEDCD3890576653E7BDCC6825579BEF678E2F768D10227`
SHA512 | `9220040F5F97DA34B68FD20E59081BEB410627EF8F4C3DC15CE0CDDA56EC523682A31FCBEE5F11A266EB81C1897A8825FD96440D98DA57A51EC7AD9C29CC1B1A`
SSDEEP | `1536:UcwAIzNHSyh6OQuOt9btte+sXKukPQ+psI0Ly2PwV5ugT:4NV3Q/4+sXKukPQ+psI0Ly24bpT`
IMP | `89347D290990998D3F6FB20FEC58B1D9`
PESHA1 | `37B9D8BA88BDB2F2B1693A0CCEFCFA8C5875ADDC`
PE256 | `A425409A4886699584E82933E5C89E1F3DC48163493EFA10786266D3A0DDD09A`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`PshedAllocateMemory` | 1 (0x1) | Exported Function | 0x00000001c000ca90 | 0x0000ca90
`PshedSynchronizeExecution` | 28 (0x1c) | Exported Function | 0x00000001c00027e0 | 0x000027e0
`PshedSetHalEnlightenments` | 27 (0x1b) | Exported Function | 0x00000001c00027a0 | 0x000027a0
`PshedSetErrorSourceInfo` | 26 (0x1a) | Exported Function | 0x00000001c0001680 | 0x00001680
`PshedRetrieveErrorInfo` | 25 (0x19) | Exported Function | 0x00000001c0001010 | 0x00001010
`PshedRegisterPlugin` | 24 (0x18) | Exported Function | 0x00000001c000c4b0 | 0x0000c4b0
`PshedReadErrorRecord` | 23 (0x17) | Exported Function | 0x00000001c0001320 | 0x00001320
`PshedMarkHiberPhase` | 22 (0x16) | Exported Function | 0x00000001c0001b70 | 0x00001b70
`PshedIsSystemWheaEnabled` | 21 (0x15) | Exported Function | 0x00000001c0002300 | 0x00002300
`PshedInjectError` | 20 (0x14) | Exported Function | 0x00000001c0001a00 | 0x00001a00
`PshedInitProc` | 18 (0x12) | Exported Function | 0x00000001c0002710 | 0x00002710
`PshedInitialize` | 19 (0x13) | Exported Function | 0x00000001c000f4b0 | 0x0000f4b0
`PshedInitGlobal` | 17 (0x11) | Exported Function | 0x00000001c00026d0 | 0x000026d0
`PshedInitAvailable` | 16 (0x10) | Exported Function | 0x00000001c00026b0 | 0x000026b0
`PshedGetInjectionCapabilities` | 15 (0xf) | Exported Function | 0x00000001c00018e0 | 0x000018e0
`PshedGetHalEnlightenments` | 14 (0xe) | Exported Function | 0x00000001c00027c0 | 0x000027c0
`PshedGetErrorSourceInfo` | 13 (0xd) | Exported Function | 0x00000001c00015c0 | 0x000015c0
`PshedGetBootErrorPacket` | 12 (0xc) | Exported Function | 0x00000001c0002000 | 0x00002000
`PshedGetAllErrorSources` | 11 (0xb) | Exported Function | 0x00000001c000c2f0 | 0x0000c2f0
`PshedFreeMemory` | 10 (0xa) | Exported Function | 0x00000001c000cac0 | 0x0000cac0
`PshedFinalizeErrorRecord` | 9 (0x9) | Exported Function | 0x00000001c0001420 | 0x00001420
`PshedEnableErrorSource` | 8 (0x8) | Exported Function | 0x00000001c0001750 | 0x00001750
`PshedDoPfa` | 7 (0x7) | Exported Function | 0x00000001c0002750 | 0x00002750
`PshedDisableErrorSource` | 6 (0x6) | Exported Function | 0x00000001c0001810 | 0x00001810
`PshedClearErrorRecord` | 5 (0x5) | Exported Function | 0x00000001c00013f0 | 0x000013f0
`PshedBugCheckSystem` | 4 (0x4) | Exported Function | 0x00000001c00015a0 | 0x000015a0
`PshedAttemptErrorRecovery` | 3 (0x3) | Exported Function | 0x00000001c00014e0 | 0x000014e0
`PshedArePluginsPresent` | 2 (0x2) | Exported Function | 0x00000001c0001be0 | 0x00001be0
`PshedUnregisterPlugin` | 29 (0x1d) | Exported Function | 0x00000001c000c9e0 | 0x0000c9e0
`PshedWriteErrorRecord` | 30 (0x1e) | Exported Function | 0x00000001c00011c0 | 0x000011c0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pshed.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/27858972c18afccd944453b72feeeba66b1587f2075087780aa4fc54202d8221/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\PSHED.DLL](PSHED.DLL-A5F9427E2FDF505CA22511B58B4D1651.md) | 63




MIT License. Copyright (c) 2020 Strontic.


