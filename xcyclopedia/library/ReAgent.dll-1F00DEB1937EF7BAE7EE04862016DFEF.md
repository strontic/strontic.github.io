---
title: ReAgent.dll | Microsoft Windows Recovery Agent DLL
excerpt: What is ReAgent.dll?
---

# ReAgent.dll 

* File Path: `C:\Windows\system32\ReAgent.dll`
* Description: Microsoft Windows Recovery Agent DLL

## Hashes

Type | Hash
-- | --
MD5 | `1F00DEB1937EF7BAE7EE04862016DFEF`
SHA1 | `7D20E9428A54AE76C03546C9B3AF2D12B24668B8`
SHA256 | `CE63360B378C46A318AFA6BDDE13D0DD3942F6FDC761BA7E712725B470757E10`
SHA384 | `CA0E3F07D925CD32D6673C3273D73AA47D4CC2E09D53AB33968C56B6537954E329AB4A363ACB136796D98C9A973CDD45`
SHA512 | `33A7CA68316115D58C77AA54160AA273257A37B17B14CE2D5BDB06F94FA2E048BD41CB47AD3AECA600322CB20EDA9BF9EFFB0FB68C9ABD29321573DE12E9E640`
SSDEEP | `12288:IY1VeBzytVWK+MuEszVQl9jx6Kfo39009VM+boauAtGvHb8bJkh5Txd/hu:bamtVfdsugbGUVJoauAO73hFxu`
IMP | `45C05CF60EB55AA41050E0F77AD50D40`
PESHA1 | `CD55990C908379F176508C0BAB193B89531A13F6`
PE256 | `C97172E211018980BE8AC5745DDEFD25F3ACB04FA0D05598F25BF60FCCB9CDA4`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`WinRE_Generalize` | 7 (0x7) | Exported Function | 0x0000000180011630 | 0x00011630
`WinReOpenLogInstance` | 32 (0x20) | Exported Function | 0x0000000180019060 | 0x00019060
`WinRePostBCDRepair` | 33 (0x21) | Exported Function | 0x0000000180013180 | 0x00013180
`WinReQueueRecoveryBoot` | 34 (0x22) | Exported Function | 0x0000000180013550 | 0x00013550
`WinReReinstall` | 35 (0x23) | Exported Function | 0x000000018000cb10 | 0x0000cb10
`WinReRemoveTrustedBootApp` | 36 (0x24) | Exported Function | 0x00000001800136d0 | 0x000136d0
`WinReRepair` | 37 (0x25) | Exported Function | 0x0000000180013780 | 0x00013780
`WinReRestoreConfigAfterPBR` | 4 (0x4) | Exported Function | 0x00000001800171e0 | 0x000171e0
`WinReRestoreLogFiles` | 38 (0x26) | Exported Function | 0x0000000180019300 | 0x00019300
`WinReSetBootApp` | 39 (0x27) | Exported Function | 0x0000000180013cc0 | 0x00013cc0
`WinReSetConfig` | 40 (0x28) | Exported Function | 0x0000000180013d70 | 0x00013d70
`WinReSetCustomization` | 41 (0x29) | Exported Function | 0x0000000180014460 | 0x00014460
`WinReSetError` | 42 (0x2a) | Exported Function | 0x00000001800054b0 | 0x000054b0
`WinReSetNarratorScheduled` | 43 (0x2b) | Exported Function | 0x0000000180014800 | 0x00014800
`WinReSetRecoveryAction` | 44 (0x2c) | Exported Function | 0x0000000180014a00 | 0x00014a00
`WinReSetTriggerFile` | 45 (0x2d) | Exported Function | 0x00000001800193a0 | 0x000193a0
`WinReSetupBackupWinRE` | 46 (0x2e) | Exported Function | 0x000000018001ae20 | 0x0001ae20
`WinReSetupCheckWinRE` | 47 (0x2f) | Exported Function | 0x000000018001bd80 | 0x0001bd80
`WinReSetupInstall` | 48 (0x30) | Exported Function | 0x000000018000cc40 | 0x0000cc40
`WinReSetupMigrateData` | 49 (0x31) | Exported Function | 0x000000018001bf10 | 0x0001bf10
`WinReSetupRemoveWinRE` | 50 (0x32) | Exported Function | 0x000000018001c3b0 | 0x0001c3b0
`WinReSetupRestoreWinREEx` | 51 (0x33) | Exported Function | 0x000000018001c590 | 0x0001c590
`WinReSetupSetImage` | 52 (0x34) | Exported Function | 0x000000018001c6c0 | 0x0001c6c0
`WinReUnInstall` | 53 (0x35) | Exported Function | 0x0000000180014df0 | 0x00014df0
`WinReUpdateLogInstance` | 54 (0x36) | Exported Function | 0x0000000180019650 | 0x00019650
`WinREUseNewPBRImage` | 6 (0x6) | Exported Function | 0x00000001800112b0 | 0x000112b0
`WinReOobeInstall` | 31 (0x1f) | Exported Function | 0x0000000180012f80 | 0x00012f80
`WinReIsWinPE` | 30 (0x1e) | Exported Function | 0x00000001800054a0 | 0x000054a0
`WinReIsWimBootEnabled` | 29 (0x1d) | Exported Function | 0x0000000180012ee0 | 0x00012ee0
`WinReIsInstalledOnSystemPartition` | 28 (0x1c) | Exported Function | 0x0000000180012980 | 0x00012980
`WinRE_Specialize` | 1 (0x1) | Exported Function | 0x000000018000bd00 | 0x0000bd00
`WinRE_Specialize_Offline` | 2 (0x2) | Exported Function | 0x000000018000bda0 | 0x0000bda0
`WinReAddTrustedBootApp` | 8 (0x8) | Exported Function | 0x0000000180011680 | 0x00011680
`WinRECheckGuid` | 5 (0x5) | Exported Function | 0x00000001800111a0 | 0x000111a0
`WinReClearBootApp` | 9 (0x9) | Exported Function | 0x0000000180011740 | 0x00011740
`WinReClearError` | 10 (0xa) | Exported Function | 0x0000000180004d70 | 0x00004d70
`WinReClearOemImagePath` | 3 (0x3) | Exported Function | 0x000000018000f690 | 0x0000f690
`WinReConfigureTask` | 11 (0xb) | Exported Function | 0x00000001800117e0 | 0x000117e0
`WinReCopyDiagnosticFiles` | 12 (0xc) | Exported Function | 0x0000000180011ce0 | 0x00011ce0
`WinReCopyLogFilesToRamdisk` | 13 (0xd) | Exported Function | 0x00000001800189f0 | 0x000189f0
`WinReCreateLogInstance` | 14 (0xe) | Exported Function | 0x0000000180018a90 | 0x00018a90
`WinReCreateLogInstanceEx` | 15 (0xf) | Exported Function | 0x0000000180018ad0 | 0x00018ad0
`WinReValidateRecoveryWim` | 55 (0x37) | Exported Function | 0x0000000180014ea0 | 0x00014ea0
`WinReDeleteLogFiles` | 16 (0x10) | Exported Function | 0x0000000180018c20 | 0x00018c20
`winreGetBinaryArch` | 58 (0x3a) | Exported Function | 0x000000018001e6e0 | 0x0001e6e0
`WinReGetConfig` | 17 (0x11) | Exported Function | 0x0000000180004d80 | 0x00004d80
`WinReGetCustomization` | 18 (0x12) | Exported Function | 0x0000000180011d90 | 0x00011d90
`WinReGetError` | 19 (0x13) | Exported Function | 0x0000000180005490 | 0x00005490
`WinReGetLogDirPath` | 20 (0x14) | Exported Function | 0x0000000180018d30 | 0x00018d30
`WinReGetTrustedBootApps` | 21 (0x15) | Exported Function | 0x0000000180012190 | 0x00012190
`WinReGetWIMInfo` | 22 (0x16) | Exported Function | 0x0000000180012240 | 0x00012240
`WinReHashBootApp` | 23 (0x17) | Exported Function | 0x0000000180012480 | 0x00012480
`WinReHashWimFile` | 24 (0x18) | Exported Function | 0x0000000180012530 | 0x00012530
`WinReInitiateOfflineScanning` | 25 (0x19) | Exported Function | 0x00000001800125c0 | 0x000125c0
`WinReInstall` | 26 (0x1a) | Exported Function | 0x000000018000c940 | 0x0000c940
`WinReInstallOnTargetOS` | 27 (0x1b) | Exported Function | 0x000000018000c9f0 | 0x0000c9f0
`winreFindInstallMedia` | 57 (0x39) | Exported Function | 0x000000018001d480 | 0x0001d480
`WinReValidateWimFile` | 56 (0x38) | Exported Function | 0x00000001800153e0 | 0x000153e0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reagent.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/ce63360b378c46a318afa6bdde13d0dd3942f6fdc761ba7e712725b470757e10/detection/





MIT License. Copyright (c) 2020 Strontic.


