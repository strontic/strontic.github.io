---
title: ttdrecordcpu.dll | Time Travel Debugging CPU Recorder Runtime
excerpt: What is ttdrecordcpu.dll?
---

# ttdrecordcpu.dll 

* File Path: `C:\Windows\system32\ttdrecordcpu.dll`
* Description: Time Travel Debugging CPU Recorder Runtime

## Hashes

Type | Hash
-- | --
MD5 | `BAB1003072214E86E26E3E0DBD0E1FF5`
SHA1 | `2C4608D0E0EB202F1A009076449EDAD69B80ECB4`
SHA256 | `05A337953DCC15069D1F3B0879E15A350AC763FA98458217347A49D7DFB79B32`
SHA384 | `FB5DC6673FD44CBB698CE59A6B5172D444434BD37A2CD4C4154A21C5CF609256874290BCA9A071CC4786679AE1738E95`
SHA512 | `C82977A737F67C013CE6A07C4400BDC197D8D7EF169AC6F8D3395B7892CC7102B8EB0DE9BAA49C9F218A09F3E66FCF7088CB6235CC28498FD440029FB951CDE5`
SSDEEP | `24576:Z3/sWlQBqMos/LNkaKJQCAgtfxtnm4nl+50:Z3coltaLgtfx04nlC0`
IMP | `595633B20722D427F0691D88339E50F3`
PESHA1 | `D3B4DF6460698B041D393749C106A069AF99D35D`
PE256 | `F806DE0AF77E9235C80AD00331F8B2782EA5D39F72E3789E7D6954921C176DD5`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`ClearClientTlsValueForThreadId` | 1 (0x1) | Exported Function | 0x00000001800417d0 | 0x000417d0
`SetRuntimeOptions` | 22 (0x16) | Exported Function | 0x0000000180041ce0 | 0x00041ce0
`SetThreadNative` | 23 (0x17) | Exported Function | 0x0000000180041680 | 0x00041680
`StartEmulatingCurrentThread` | 24 (0x18) | Exported Function | 0x00000001800419c0 | 0x000419c0
`StopEmulatingCurrentThread` | 25 (0x19) | Exported Function | 0x0000000180041a00 | 0x00041a00
`StubDllEntry` | 26 (0x1a) | Exported Function | 0x00000001800a1820 | 0x000a1820
`TryPauseSimulation` | 27 (0x1b) | Exported Function | 0x00000001800a0e80 | 0x000a0e80
`TtdWriterAddCustomEvent` | 28 (0x1c) | Exported Function | 0x0000000180092b30 | 0x00092b30
`TtdWriterDumpHeaps` | 29 (0x1d) | Exported Function | 0x0000000180092b20 | 0x00092b20
`TtdWriterDumpModuleData` | 30 (0x1e) | Exported Function | 0x0000000180092b10 | 0x00092b10
`TtdWriterDumpSnapshot` | 31 (0x1f) | Exported Function | 0x0000000180092b00 | 0x00092b00
`TtdWriterGetFileName` | 32 (0x20) | Exported Function | 0x0000000180092af0 | 0x00092af0
`TtdWriterGetState` | 33 (0x21) | Exported Function | 0x0000000180092b80 | 0x00092b80
`TtdWriterGetThrottleState` | 34 (0x22) | Exported Function | 0x0000000180092b50 | 0x00092b50
`TtdWriterRelease` | 35 (0x23) | Exported Function | 0x0000000180092ae0 | 0x00092ae0
`TtdWriterResetThrottle` | 36 (0x24) | Exported Function | 0x0000000180092750 | 0x00092750
`TtdWriterResumeRecording` | 37 (0x25) | Exported Function | 0x0000000180092770 | 0x00092770
`TtdWriterStartRecordingCurrentThread` | 38 (0x26) | Exported Function | 0x0000000180092b40 | 0x00092b40
`RunCallbackWithSmartContextForCurrentThread` | 21 (0x15) | Exported Function | 0x0000000180041760 | 0x00041760
`ResumeSimulation` | 20 (0x14) | Exported Function | 0x0000000180041b80 | 0x00041b80
`ResetMaxInstructionsToEmulate` | 19 (0x13) | Exported Function | 0x0000000180041b10 | 0x00041b10
`RequestUnhookedFunctions` | 18 (0x12) | Exported Function | 0x0000000180042560 | 0x00042560
`FlushCodeCaches` | 2 (0x2) | Exported Function | 0x0000000180041d40 | 0x00041d40
`g_ttdConstants` | 41 (0x29) | Exported Function | 0x0000000180154720 | 0x00154720
`GetClientTlsValueForCurrentThread` | 3 (0x3) | Exported Function | 0x0000000180041800 | 0x00041800
`GetInstructionCounts` | 4 (0x4) | Exported Function | 0x0000000180041a90 | 0x00041a90
`GetRegisterOffsets` | 5 (0x5) | Exported Function | 0x0000000180041d60 | 0x00041d60
`InitializeEmulateOnlyClient` | 6 (0x6) | Exported Function | 0x0000000180041da0 | 0x00041da0
`InitializeGlobalState` | 7 (0x7) | Exported Function | 0x0000000180041630 | 0x00041630
`InitializeNirvanaClient` | 8 (0x8) | Exported Function | 0x000000018008f430 | 0x0008f430
`TtdWriterStopRecordingCurrentThread` | 39 (0x27) | Exported Function | 0x00000001800926f0 | 0x000926f0
`InitializeRecorder` | 9 (0x9) | Exported Function | 0x0000000180092990 | 0x00092990
`InjectThread` | 11 (0xb) | Exported Function | 0x00000001800a17d0 | 0x000a17d0
`IsEmulatingCurrentThread` | 12 (0xc) | Exported Function | 0x0000000180041a40 | 0x00041a40
`IsSimulating` | 13 (0xd) | Exported Function | 0x00000001800a0e85 | 0x000a0e85
`ntdllLdrInitializeThunk` | 42 (0x2a) | Exported Function | 0x0000000180174e30 | 0x00174e30
`OpenWriter` | 14 (0xe) | Exported Function | 0x00000001800927d0 | 0x000927d0
`ParametersBlock` | 15 (0xf) | Exported Function | 0x0000000180174e38 | 0x00174e38
`RegisterInstrumentationCallbacks` | 16 (0x10) | Exported Function | 0x0000000180042000 | 0x00042000
`RegisterRecordCallbacks` | 17 (0x11) | Exported Function | 0x0000000180042130 | 0x00042130
`InitializeSmartCpuClient` | 10 (0xa) | Exported Function | 0x00000001800415d0 | 0x000415d0
`TtdWriterTryPauseRecording` | 40 (0x28) | Exported Function | 0x0000000180092760 | 0x00092760


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TTDRecordCPU.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/05a337953dcc15069d1f3b0879e15a350ac763fa98458217347a49d7dfb79b32/detection/





MIT License. Copyright (c) 2020 Strontic.


