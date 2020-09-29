---
title: ttdrecordcpu.dll | Time Travel Debugging CPU Recorder Runtime
excerpt: What is ttdrecordcpu.dll?
---

# ttdrecordcpu.dll 

* File Path: `C:\Windows\SysWOW64\ttdrecordcpu.dll`
* Description: Time Travel Debugging CPU Recorder Runtime

## Hashes

Type | Hash
-- | --
MD5 | `65BB229850440881A8ADB2657E36244E`
SHA1 | `4EF64DD67A2136045368611B4C08A3DBC8691BE5`
SHA256 | `C3D38CF445B19D28ECE194CE1B81A0F20C7EE71499868C53643766596F7272E7`
SHA384 | `28924F81732D9D1AF7921FC5D507C08DF02FFEC695B52D503E9082A9B6CE2F95B233A173BC4912AE913E9508900921D7`
SHA512 | `098A5241925A2ECE3D36277C2ED3A832276106A15148E06071CD8AC160E349736245D7D108F63C20A17C305F08A70555EE5564DB9ACFE728193E0DC1C7A362A6`
SSDEEP | `24576:VuXn5OfKp8tLsUxiidaQxZPFZTK6XuWh9u+7J76YSZiSCyH5xhoeh:a59p8ensbZDTK6XuG7J76YSZiSCyH5x9`
IMP | `9AA107E69590B3970D354491ED894B0A`
PESHA1 | `C0580A4A61ADBCADB362F9A4E2D5571EDFF0236C`
PE256 | `C83683A51AFABD2E98CC0AD370A67B339027E773E5687F20A43FAE64A7B3C1E5`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`ClearClientTlsValueForThreadId` | 1 (0x1) | Exported Function | 0x100215a0 | 0x000215a0
`SetThreadNative` | 23 (0x17) | Exported Function | 0x100213d0 | 0x000213d0
`StartEmulatingCurrentThread` | 24 (0x18) | Exported Function | 0x100217a0 | 0x000217a0
`StopEmulatingCurrentThread` | 25 (0x19) | Exported Function | 0x100217f0 | 0x000217f0
`StubDllEntry` | 26 (0x1a) | Exported Function | 0x10081860 | 0x00081860
`StubDllEntryWow64` | 27 (0x1b) | Exported Function | 0x10081890 | 0x00081890
`TriggerOSNotification` | 28 (0x1c) | Exported Function | 0x1001a420 | 0x0001a420
`TryPauseSimulation` | 29 (0x1d) | Exported Function | 0x10081070 | 0x00081070
`TtdWriterAddCustomEvent` | 30 (0x1e) | Exported Function | 0x10076ef0 | 0x00076ef0
`SetRuntimeOptions` | 22 (0x16) | Exported Function | 0x10021d30 | 0x00021d30
`TtdWriterDumpHeaps` | 31 (0x1f) | Exported Function | 0x10076ed0 | 0x00076ed0
`TtdWriterDumpSnapshot` | 33 (0x21) | Exported Function | 0x10076e90 | 0x00076e90
`TtdWriterGetFileName` | 34 (0x22) | Exported Function | 0x10076e70 | 0x00076e70
`TtdWriterGetState` | 35 (0x23) | Exported Function | 0x10076f90 | 0x00076f90
`TtdWriterGetThrottleState` | 36 (0x24) | Exported Function | 0x10076f40 | 0x00076f40
`TtdWriterRelease` | 37 (0x25) | Exported Function | 0x10076e50 | 0x00076e50
`TtdWriterResetThrottle` | 38 (0x26) | Exported Function | 0x10076f70 | 0x00076f70
`TtdWriterResumeRecording` | 39 (0x27) | Exported Function | 0x10076bc0 | 0x00076bc0
`TtdWriterStartRecordingCurrentThread` | 40 (0x28) | Exported Function | 0x10076f10 | 0x00076f10
`TtdWriterDumpModuleData` | 32 (0x20) | Exported Function | 0x10076eb0 | 0x00076eb0
`TtdWriterStopRecordingCurrentThread` | 41 (0x29) | Exported Function | 0x10076b20 | 0x00076b20
`RunCallbackWithSmartContextForCurrentThread` | 21 (0x15) | Exported Function | 0x10021540 | 0x00021540
`ResetMaxInstructionsToEmulate` | 19 (0x13) | Exported Function | 0x10021970 | 0x00021970
`FlushCodeCaches` | 2 (0x2) | Exported Function | 0x10021de0 | 0x00021de0
`g_ttdConstants` | 43 (0x2b) | Exported Function | 0x101075c0 | 0x001075c0
`GetClientTlsValueForCurrentThread` | 3 (0x3) | Exported Function | 0x10021600 | 0x00021600
`GetInstructionCounts` | 4 (0x4) | Exported Function | 0x100218b0 | 0x000218b0
`GetRegisterOffsets` | 5 (0x5) | Exported Function | 0x10021e00 | 0x00021e00
`InitializeEmulateOnlyClient` | 6 (0x6) | Exported Function | 0x10021e40 | 0x00021e40
`InitializeGlobalState` | 7 (0x7) | Exported Function | 0x10021370 | 0x00021370
`InitializeNirvanaClient` | 8 (0x8) | Exported Function | 0x100736e0 | 0x000736e0
`ResumeSimulation` | 20 (0x14) | Exported Function | 0x10021a00 | 0x00021a00
`InitializeRecorder` | 9 (0x9) | Exported Function | 0x10076d50 | 0x00076d50
`InjectThread` | 11 (0xb) | Exported Function | 0x10081810 | 0x00081810
`IsEmulatingCurrentThread` | 12 (0xc) | Exported Function | 0x10021850 | 0x00021850
`IsSimulating` | 13 (0xd) | Exported Function | 0x10081075 | 0x00081075
`OpenWriter` | 14 (0xe) | Exported Function | 0x10076c50 | 0x00076c50
`ParametersBlock` | 15 (0xf) | Exported Function | 0x10127a5c | 0x00127a5c
`RegisterInstrumentationCallbacks` | 16 (0x10) | Exported Function | 0x10021f20 | 0x00021f20
`RegisterRecordCallbacks` | 17 (0x11) | Exported Function | 0x10022050 | 0x00022050
`RequestUnhookedFunctions` | 18 (0x12) | Exported Function | 0x10022580 | 0x00022580
`InitializeSmartCpuClient` | 10 (0xa) | Exported Function | 0x10021330 | 0x00021330
`TtdWriterTryPauseRecording` | 42 (0x2a) | Exported Function | 0x10076bb0 | 0x00076bb0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/c3d38cf445b19d28ece194ce1b81a0f20c7ee71499868c53643766596f7272e7/detection/





MIT License. Copyright (c) 2020 Strontic.


