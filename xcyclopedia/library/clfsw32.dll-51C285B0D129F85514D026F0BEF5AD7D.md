---
title: clfsw32.dll | Common Log Marshalling Win32 DLL
excerpt: What is clfsw32.dll?
---

# clfsw32.dll 

* File Path: `C:\Windows\system32\clfsw32.dll`
* Description: Common Log Marshalling Win32 DLL

## Hashes

Type | Hash
-- | --
MD5 | `51C285B0D129F85514D026F0BEF5AD7D`
SHA1 | `19AEBFD5789D13FD20EC9ED8FFB1234E15212197`
SHA256 | `3BF88DF082D8316B7448D577520C1712932F080EE4CBC2AAD8DDCB5CCD38803B`
SHA384 | `FE645C722D9B9554C9D59766B0FF8CF35F78A0118574CBD9A6A0AA3579DC90A0B83FF8DDFE5AA9F28D60452BE49595EC`
SHA512 | `1B6A3C7E19319E2C368D6304D5C9D655E998825290B01ABEC098A27A07A6EAC6AE285CEFA9F17F7233BE4B389B50B060303A091A1480147EF5F43E34D189FA3F`
SSDEEP | `1536:+RWf5XIO+as99YeRhhDc1mKOMCarX+8u7yXC8/TaW:+RTas9SeVDnKTz+8KH8/z`
IMP | `5EA1C24D8426558496CDCC67AE06F642`
PESHA1 | `5E7A7647C4666EC88CD684A1CABD173D3D05E858`
PE256 | `1C7135A8AC1170528A17692B4966257C898DDCABB243057EC35B9F840ACB22AD`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AddLogContainer` | 2 (0x2) | Exported Function | 0x0000000180002420 | 0x00002420
`LsnIncrement` | 34 (0x22) | Exported Function | 0x0000000180007e70 | 0x00007e70
`LsnInvalid` | 35 (0x23) | Exported Function | 0x0000000180006b50 | 0x00006b50
`LsnLess` | 36 (0x24) | Exported Function | 0x0000000180001090 | 0x00001090
`LsnNull` | 37 (0x25) | Exported Function | 0x0000000180006a90 | 0x00006a90
`LsnRecordSequence` | 38 (0x26) | Exported Function | 0x0000000180006b30 | 0x00006b30
`PrepareLogArchive` | 39 (0x27) | Exported Function | 0x0000000180004100 | 0x00004100
`QueryLogPolicy` | 40 (0x28) | Exported Function | 0x00000001800067c0 | 0x000067c0
`ReadLogArchiveMetadata` | 41 (0x29) | Exported Function | 0x0000000180004540 | 0x00004540
`ReadLogNotification` | 42 (0x2a) | Exported Function | 0x0000000180006750 | 0x00006750
`ReadLogRecord` | 43 (0x2b) | Exported Function | 0x0000000180004e90 | 0x00004e90
`ReadLogRestartArea` | 44 (0x2c) | Exported Function | 0x0000000180003a00 | 0x00003a00
`ReadNextLogRecord` | 45 (0x2d) | Exported Function | 0x0000000180004ff0 | 0x00004ff0
`ReadPreviousLogRestartArea` | 46 (0x2e) | Exported Function | 0x0000000180003ab0 | 0x00003ab0
`LsnGreater` | 33 (0x21) | Exported Function | 0x00000001800010c0 | 0x000010c0
`RegisterForLogWriteNotification` | 47 (0x2f) | Exported Function | 0x00000001800069e0 | 0x000069e0
`RemoveLogContainer` | 49 (0x31) | Exported Function | 0x0000000180002900 | 0x00002900
`RemoveLogContainerSet` | 50 (0x32) | Exported Function | 0x0000000180002950 | 0x00002950
`RemoveLogPolicy` | 51 (0x33) | Exported Function | 0x00000001800064d0 | 0x000064d0
`ReserveAndAppendLog` | 52 (0x34) | Exported Function | 0x0000000180003de0 | 0x00003de0
`ReserveAndAppendLogAligned` | 53 (0x35) | Exported Function | 0x0000000180003f70 | 0x00003f70
`ScanLogContainers` | 54 (0x36) | Exported Function | 0x0000000180003270 | 0x00003270
`SetEndOfLog` | 55 (0x37) | Exported Function | 0x0000000180002e50 | 0x00002e50
`SetLogArchiveMode` | 56 (0x38) | Exported Function | 0x00000001800036e0 | 0x000036e0
`SetLogArchiveTail` | 57 (0x39) | Exported Function | 0x0000000180002de0 | 0x00002de0
`SetLogFileSizeWithPolicy` | 58 (0x3a) | Exported Function | 0x00000001800065a0 | 0x000065a0
`TerminateLogArchive` | 59 (0x3b) | Exported Function | 0x00000001800045e0 | 0x000045e0
`TerminateReadLog` | 60 (0x3c) | Exported Function | 0x0000000180005720 | 0x00005720
`TruncateLog` | 61 (0x3d) | Exported Function | 0x0000000180002f80 | 0x00002f80
`RegisterManageableLogClient` | 48 (0x30) | Exported Function | 0x00000001800063b0 | 0x000063b0
`ValidateLog` | 62 (0x3e) | Exported Function | 0x00000001800046d0 | 0x000046d0
`LsnEqual` | 32 (0x20) | Exported Function | 0x0000000180001070 | 0x00001070
`LsnCreate` | 31 (0x1f) | Exported Function | 0x0000000180006ad0 | 0x00006ad0
`AddLogContainerSet` | 3 (0x3) | Exported Function | 0x0000000180002470 | 0x00002470
`AdvanceLogBase` | 4 (0x4) | Exported Function | 0x0000000180003d50 | 0x00003d50
`AlignReservedLog` | 5 (0x5) | Exported Function | 0x0000000180003470 | 0x00003470
`AllocReservedLog` | 6 (0x6) | Exported Function | 0x0000000180003560 | 0x00003560
`CLFS_LSN_INVALID` | 7 (0x7) | Exported Function | 0x0000000180011e70 | 0x00011e70
`CLFS_LSN_NULL` | 8 (0x8) | Exported Function | 0x0000000180011e88 | 0x00011e88
`CloseAndResetLogFile` | 9 (0x9) | Exported Function | 0x00000001800057c0 | 0x000057c0
`CreateLogContainerScanContext` | 10 (0xa) | Exported Function | 0x0000000180003000 | 0x00003000
`CreateLogFile` | 11 (0xb) | Exported Function | 0x0000000180001b20 | 0x00001b20
`CreateLogMarshallingArea` | 12 (0xc) | Exported Function | 0x0000000180003810 | 0x00003810
`DeleteLogByHandle` | 13 (0xd) | Exported Function | 0x00000001800023a0 | 0x000023a0
`DeleteLogFile` | 14 (0xe) | Exported Function | 0x00000001800022c0 | 0x000022c0
`DeleteLogMarshallingArea` | 15 (0xf) | Exported Function | 0x0000000180003990 | 0x00003990
`LsnDecrement` | 1 (0x1) | Exported Function | 0x0000000180007ec0 | 0x00007ec0
`DeregisterManageableLogClient` | 16 (0x10) | Exported Function | 0x0000000180006540 | 0x00006540
`FlushLogBuffers` | 18 (0x12) | Exported Function | 0x00000001800055e0 | 0x000055e0
`FlushLogToLsn` | 19 (0x13) | Exported Function | 0x0000000180005680 | 0x00005680
`FreeReservedLog` | 20 (0x14) | Exported Function | 0x00000001800035e0 | 0x000035e0
`GetLogContainerName` | 21 (0x15) | Exported Function | 0x0000000180006030 | 0x00006030
`GetLogFileInformation` | 22 (0x16) | Exported Function | 0x0000000180003650 | 0x00003650
`GetLogIoStatistics` | 23 (0x17) | Exported Function | 0x00000001800061a0 | 0x000061a0
`GetLogReservationInfo` | 24 (0x18) | Exported Function | 0x0000000180003ce0 | 0x00003ce0
`GetNextLogArchiveExtent` | 25 (0x19) | Exported Function | 0x00000001800044c0 | 0x000044c0
`HandleLogFull` | 26 (0x1a) | Exported Function | 0x0000000180006620 | 0x00006620
`InstallLogPolicy` | 27 (0x1b) | Exported Function | 0x0000000180006450 | 0x00006450
`LogTailAdvanceFailure` | 28 (0x1c) | Exported Function | 0x00000001800066b0 | 0x000066b0
`LsnBlockOffset` | 29 (0x1d) | Exported Function | 0x0000000180006b10 | 0x00006b10
`LsnContainer` | 30 (0x1e) | Exported Function | 0x0000000180006ab0 | 0x00006ab0
`DumpLogRecords` | 17 (0x11) | Exported Function | 0x0000000180005910 | 0x00005910
`WriteLogRestartArea` | 63 (0x3f) | Exported Function | 0x0000000180003bb0 | 0x00003bb0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: clfsw32.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.21 (WinBuild.160101.0800)
* Product Version: 10.0.19041.21
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/3bf88df082d8316b7448d577520c1712932f080ee4cbc2aad8ddcb5ccd38803b/detection/





MIT License. Copyright (c) 2020 Strontic.


