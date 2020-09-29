---
title: ReAgent.dll | Microsoft Windows Recovery Agent DLL
excerpt: What is ReAgent.dll?
---

# ReAgent.dll 

* File Path: `C:\Windows\SysWOW64\ReAgent.dll`
* Description: Microsoft Windows Recovery Agent DLL

## Hashes

Type | Hash
-- | --
MD5 | `6FBEC878D0221C71E82265A571FC333C`
SHA1 | `67784BC13759FF7B61ED542A9C24B45AE31E4F12`
SHA256 | `2D346CC1B7C92AB93E9FF6ADD455E8E0F1FAEF85A139A8BB014D63AA99E4A253`
SHA384 | `939DEEB2B03287E8B1B61023DD6EAD0B9B0ADCBC662C00974ECD48F923EC7CDEACAC244C86D4221FC31093441E712BD8`
SHA512 | `380A8352AB48BCBFEB9C59FB238D2CE8F3FDB398F456E4A964AA88F299C93C0FC7BDE97BB6CF4B711F08DBEE73431341B0C1C6FA1859D03E033C8C13B0BCF27B`
SSDEEP | `24576:splkJI0cii0nO3X7Wdj3E3b23NF+UgVKUHvY4s:snFHXB7WRs23V4XHJs`
IMP | `72ABD3C448609C7ACF7D6DB9EFF5EADD`
PESHA1 | `34B1EC16149BC5AB83461E27BA71CBA0EE33CA93`
PE256 | `8C5ADD5055CB1275D00525EE52A17D634B91B40459686B51791A6109C48FAF98`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`WinRE_Generalize` | 7 (0x7) | Exported Function | 0x1004fbd0 | 0x0004fbd0
`WinReOpenLogInstance` | 32 (0x20) | Exported Function | 0x10056090 | 0x00056090
`WinRePostBCDRepair` | 33 (0x21) | Exported Function | 0x10051380 | 0x00051380
`WinReQueueRecoveryBoot` | 34 (0x22) | Exported Function | 0x10051710 | 0x00051710
`WinReReinstall` | 35 (0x23) | Exported Function | 0x1004c220 | 0x0004c220
`WinReRemoveTrustedBootApp` | 36 (0x24) | Exported Function | 0x10051860 | 0x00051860
`WinReRepair` | 37 (0x25) | Exported Function | 0x100518e0 | 0x000518e0
`WinReRestoreConfigAfterPBR` | 4 (0x4) | Exported Function | 0x10054700 | 0x00054700
`WinReRestoreLogFiles` | 38 (0x26) | Exported Function | 0x100562a0 | 0x000562a0
`WinReSetBootApp` | 39 (0x27) | Exported Function | 0x10051da0 | 0x00051da0
`WinReSetConfig` | 40 (0x28) | Exported Function | 0x10051e30 | 0x00051e30
`WinReSetCustomization` | 41 (0x29) | Exported Function | 0x10052430 | 0x00052430
`WinReSetError` | 42 (0x2a) | Exported Function | 0x10046c70 | 0x00046c70
`WinReSetNarratorScheduled` | 43 (0x2b) | Exported Function | 0x10052720 | 0x00052720
`WinReSetRecoveryAction` | 44 (0x2c) | Exported Function | 0x100528a0 | 0x000528a0
`WinReSetTriggerFile` | 45 (0x2d) | Exported Function | 0x10056320 | 0x00056320
`WinReSetupBackupWinRE` | 46 (0x2e) | Exported Function | 0x10056fc0 | 0x00056fc0
`WinReSetupCheckWinRE` | 47 (0x2f) | Exported Function | 0x10058000 | 0x00058000
`WinReSetupInstall` | 48 (0x30) | Exported Function | 0x1003d000 | 0x0003d000
`WinReSetupMigrateData` | 49 (0x31) | Exported Function | 0x10058140 | 0x00058140
`WinReSetupRemoveWinRE` | 50 (0x32) | Exported Function | 0x1003def0 | 0x0003def0
`WinReSetupRestoreWinREEx` | 51 (0x33) | Exported Function | 0x10058550 | 0x00058550
`WinReSetupSetImage` | 52 (0x34) | Exported Function | 0x10058640 | 0x00058640
`WinReUnInstall` | 53 (0x35) | Exported Function | 0x10052be0 | 0x00052be0
`WinReUpdateLogInstance` | 54 (0x36) | Exported Function | 0x10056520 | 0x00056520
`WinREUseNewPBRImage` | 6 (0x6) | Exported Function | 0x1004f8e0 | 0x0004f8e0
`WinReOobeInstall` | 31 (0x1f) | Exported Function | 0x10051160 | 0x00051160
`WinReIsWinPE` | 30 (0x1e) | Exported Function | 0x10046c60 | 0x00046c60
`WinReIsWimBootEnabled` | 29 (0x1d) | Exported Function | 0x100510e0 | 0x000510e0
`WinReIsInstalledOnSystemPartition` | 28 (0x1c) | Exported Function | 0x10050c80 | 0x00050c80
`WinRE_Specialize` | 1 (0x1) | Exported Function | 0x1004bcc0 | 0x0004bcc0
`WinRE_Specialize_Offline` | 2 (0x2) | Exported Function | 0x1004bd40 | 0x0004bd40
`WinReAddTrustedBootApp` | 8 (0x8) | Exported Function | 0x1004fc10 | 0x0004fc10
`WinRECheckGuid` | 5 (0x5) | Exported Function | 0x1004f7f0 | 0x0004f7f0
`WinReClearBootApp` | 9 (0x9) | Exported Function | 0x1004fc90 | 0x0004fc90
`WinReClearError` | 10 (0xa) | Exported Function | 0x10046690 | 0x00046690
`WinReClearOemImagePath` | 3 (0x3) | Exported Function | 0x1004e320 | 0x0004e320
`WinReConfigureTask` | 11 (0xb) | Exported Function | 0x1004fd20 | 0x0004fd20
`WinReCopyDiagnosticFiles` | 12 (0xc) | Exported Function | 0x10050220 | 0x00050220
`WinReCopyLogFilesToRamdisk` | 13 (0xd) | Exported Function | 0x10055b90 | 0x00055b90
`WinReCreateLogInstance` | 14 (0xe) | Exported Function | 0x10055c10 | 0x00055c10
`WinReCreateLogInstanceEx` | 15 (0xf) | Exported Function | 0x10055c40 | 0x00055c40
`WinReValidateRecoveryWim` | 55 (0x37) | Exported Function | 0x10052c60 | 0x00052c60
`WinReDeleteLogFiles` | 16 (0x10) | Exported Function | 0x10055d40 | 0x00055d40
`winreGetBinaryArch` | 58 (0x3a) | Exported Function | 0x10059e70 | 0x00059e70
`WinReGetConfig` | 17 (0x11) | Exported Function | 0x100466a0 | 0x000466a0
`WinReGetCustomization` | 18 (0x12) | Exported Function | 0x100502b0 | 0x000502b0
`WinReGetError` | 19 (0x13) | Exported Function | 0x10046c50 | 0x00046c50
`WinReGetLogDirPath` | 20 (0x14) | Exported Function | 0x10055e00 | 0x00055e00
`WinReGetTrustedBootApps` | 21 (0x15) | Exported Function | 0x100505d0 | 0x000505d0
`WinReGetWIMInfo` | 22 (0x16) | Exported Function | 0x10050650 | 0x00050650
`WinReHashBootApp` | 23 (0x17) | Exported Function | 0x10050810 | 0x00050810
`WinReHashWimFile` | 24 (0x18) | Exported Function | 0x100508a0 | 0x000508a0
`WinReInitiateOfflineScanning` | 25 (0x19) | Exported Function | 0x10050910 | 0x00050910
`WinReInstall` | 26 (0x1a) | Exported Function | 0x1004c100 | 0x0004c100
`WinReInstallOnTargetOS` | 27 (0x1b) | Exported Function | 0x1004c180 | 0x0004c180
`winreFindInstallMedia` | 57 (0x39) | Exported Function | 0x100591c0 | 0x000591c0
`WinReValidateWimFile` | 56 (0x38) | Exported Function | 0x100530b0 | 0x000530b0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reagent.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.84 (WinBuild.160101.0800)
* Product Version: 10.0.19041.84
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/2d346cc1b7c92ab93e9ff6add455e8e0f1faef85a139a8bb014d63aa99e4a253/detection/





MIT License. Copyright (c) 2020 Strontic.


