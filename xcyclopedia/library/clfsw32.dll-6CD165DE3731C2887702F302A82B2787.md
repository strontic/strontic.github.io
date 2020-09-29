---
title: clfsw32.dll | Common Log Marshalling Win32 DLL
excerpt: What is clfsw32.dll?
---

# clfsw32.dll 

* File Path: `C:\Windows\SysWOW64\clfsw32.dll`
* Description: Common Log Marshalling Win32 DLL

## Hashes

Type | Hash
-- | --
MD5 | `6CD165DE3731C2887702F302A82B2787`
SHA1 | `5E2F0824FC027E32BE2D8D30117CE854F0A18299`
SHA256 | `2348F0489F1B537B2FFCBEB83CB79C3A8016D78C1F2BCAD4B2A04BCA2DE4A747`
SHA384 | `563BC6FE48C081E6FDF9C3BAFD80657F868B5BC6ED8E6BFE0ED5DA5DD8596FE1924BDB1C8F6CACD1DC41C66E290B725D`
SHA512 | `CB0A74060CCEB204D5CCF4A1B9F823A3FBF077EC4516C5F6FF52E4DEFE01F1E4EF830D6F4B50108F6B353DDA07741D04D7FBCAA7DD647D4A656F71282B4FFEED`
SSDEEP | `1536:lo+DjglOk19RErILfeSNsrAgjv+MGyOF4M:u+wlOS9RErIKSNsrAgjvfGR4M`
IMP | `AB68F7978DA9D552520F1C31BF449794`
PESHA1 | `8915917A2BB399C7623DDD73A6B2019163764C25`
PE256 | `74F3AF48E1A778F9F8AFB414449F8C9CB00E592A24B0A1416D5E3025A45C8FEB`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AddLogContainer` | 2 (0x2) | Exported Function | 0x10003c50 | 0x00003c50
`LsnIncrement` | 34 (0x22) | Exported Function | 0x100085f0 | 0x000085f0
`LsnInvalid` | 35 (0x23) | Exported Function | 0x10007450 | 0x00007450
`LsnLess` | 36 (0x24) | Exported Function | 0x10002d00 | 0x00002d00
`LsnNull` | 37 (0x25) | Exported Function | 0x10007380 | 0x00007380
`LsnRecordSequence` | 38 (0x26) | Exported Function | 0x10007430 | 0x00007430
`PrepareLogArchive` | 39 (0x27) | Exported Function | 0x10005100 | 0x00005100
`QueryLogPolicy` | 40 (0x28) | Exported Function | 0x100070c0 | 0x000070c0
`ReadLogArchiveMetadata` | 41 (0x29) | Exported Function | 0x10005590 | 0x00005590
`ReadLogNotification` | 42 (0x2a) | Exported Function | 0x10007070 | 0x00007070
`ReadLogRecord` | 43 (0x2b) | Exported Function | 0x10005cd0 | 0x00005cd0
`ReadLogRestartArea` | 44 (0x2c) | Exported Function | 0x10004c10 | 0x00004c10
`ReadNextLogRecord` | 45 (0x2d) | Exported Function | 0x10005df0 | 0x00005df0
`ReadPreviousLogRestartArea` | 46 (0x2e) | Exported Function | 0x10004ca0 | 0x00004ca0
`LsnGreater` | 33 (0x21) | Exported Function | 0x10002d40 | 0x00002d40
`RegisterForLogWriteNotification` | 47 (0x2f) | Exported Function | 0x10007230 | 0x00007230
`RemoveLogContainer` | 49 (0x31) | Exported Function | 0x10003fd0 | 0x00003fd0
`RemoveLogContainerSet` | 50 (0x32) | Exported Function | 0x10004010 | 0x00004010
`RemoveLogPolicy` | 51 (0x33) | Exported Function | 0x10006eb0 | 0x00006eb0
`ReserveAndAppendLog` | 52 (0x34) | Exported Function | 0x10004f80 | 0x00004f80
`ReserveAndAppendLogAligned` | 53 (0x35) | Exported Function | 0x10004fc0 | 0x00004fc0
`ScanLogContainers` | 54 (0x36) | Exported Function | 0x100046a0 | 0x000046a0
`SetEndOfLog` | 55 (0x37) | Exported Function | 0x100043a0 | 0x000043a0
`SetLogArchiveMode` | 56 (0x38) | Exported Function | 0x100049e0 | 0x000049e0
`SetLogArchiveTail` | 57 (0x39) | Exported Function | 0x10004340 | 0x00004340
`SetLogFileSizeWithPolicy` | 58 (0x3a) | Exported Function | 0x10006f40 | 0x00006f40
`TerminateLogArchive` | 59 (0x3b) | Exported Function | 0x10005610 | 0x00005610
`TerminateReadLog` | 60 (0x3c) | Exported Function | 0x100063f0 | 0x000063f0
`TruncateLog` | 61 (0x3d) | Exported Function | 0x10004460 | 0x00004460
`RegisterManageableLogClient` | 48 (0x30) | Exported Function | 0x10006df0 | 0x00006df0
`ValidateLog` | 62 (0x3e) | Exported Function | 0x10005660 | 0x00005660
`LsnEqual` | 32 (0x20) | Exported Function | 0x10002cd0 | 0x00002cd0
`LsnCreate` | 31 (0x1f) | Exported Function | 0x100073d0 | 0x000073d0
`AddLogContainerSet` | 3 (0x3) | Exported Function | 0x10003c90 | 0x00003c90
`AdvanceLogBase` | 4 (0x4) | Exported Function | 0x10004ef0 | 0x00004ef0
`AlignReservedLog` | 5 (0x5) | Exported Function | 0x10004830 | 0x00004830
`AllocReservedLog` | 6 (0x6) | Exported Function | 0x100048a0 | 0x000048a0
`CLFS_LSN_INVALID` | 7 (0x7) | Exported Function | 0x10002460 | 0x00002460
`CLFS_LSN_NULL` | 8 (0x8) | Exported Function | 0x10002478 | 0x00002478
`CloseAndResetLogFile` | 9 (0x9) | Exported Function | 0x10006450 | 0x00006450
`CreateLogContainerScanContext` | 10 (0xa) | Exported Function | 0x100044d0 | 0x000044d0
`CreateLogFile` | 11 (0xb) | Exported Function | 0x10003620 | 0x00003620
`CreateLogMarshallingArea` | 12 (0xc) | Exported Function | 0x10004ad0 | 0x00004ad0
`DeleteLogByHandle` | 13 (0xd) | Exported Function | 0x10003c00 | 0x00003c00
`DeleteLogFile` | 14 (0xe) | Exported Function | 0x10003b70 | 0x00003b70
`DeleteLogMarshallingArea` | 15 (0xf) | Exported Function | 0x10004bc0 | 0x00004bc0
`LsnDecrement` | 1 (0x1) | Exported Function | 0x10008640 | 0x00008640
`DeregisterManageableLogClient` | 16 (0x10) | Exported Function | 0x10006f00 | 0x00006f00
`FlushLogBuffers` | 18 (0x12) | Exported Function | 0x100062a0 | 0x000062a0
`FlushLogToLsn` | 19 (0x13) | Exported Function | 0x10006340 | 0x00006340
`FreeReservedLog` | 20 (0x14) | Exported Function | 0x10004910 | 0x00004910
`GetLogContainerName` | 21 (0x15) | Exported Function | 0x10006bb0 | 0x00006bb0
`GetLogFileInformation` | 22 (0x16) | Exported Function | 0x10004970 | 0x00004970
`GetLogIoStatistics` | 23 (0x17) | Exported Function | 0x10006ca0 | 0x00006ca0
`GetLogReservationInfo` | 24 (0x18) | Exported Function | 0x10004e70 | 0x00004e70
`GetNextLogArchiveExtent` | 25 (0x19) | Exported Function | 0x10005520 | 0x00005520
`HandleLogFull` | 26 (0x1a) | Exported Function | 0x10006fa0 | 0x00006fa0
`InstallLogPolicy` | 27 (0x1b) | Exported Function | 0x10006e60 | 0x00006e60
`LogTailAdvanceFailure` | 28 (0x1c) | Exported Function | 0x10007000 | 0x00007000
`LsnBlockOffset` | 29 (0x1d) | Exported Function | 0x10007410 | 0x00007410
`LsnContainer` | 30 (0x1e) | Exported Function | 0x100073b0 | 0x000073b0
`DumpLogRecords` | 17 (0x11) | Exported Function | 0x10006520 | 0x00006520
`WriteLogRestartArea` | 63 (0x3f) | Exported Function | 0x10004d50 | 0x00004d50


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/2348f0489f1b537b2ffcbeb83cb79c3a8016d78c1f2bcad4b2a04bca2de4a747/detection/





MIT License. Copyright (c) 2020 Strontic.


