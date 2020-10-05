---
title: bcd.dll | BCD DLL
excerpt: What is bcd.dll?
---

# bcd.dll 

* File Path: `C:\Windows\system32\bcd.dll`
* Description: BCD DLL

## Hashes

Type | Hash
-- | --
MD5 | `B86FAA39AADD66D42DD5EC84B7BE7290`
SHA1 | `44AB674364F53A81C3A1B41C24A7470D170C920C`
SHA256 | `5B3C3C3C75093787E2433A4D27CA716D1D6A0BE9D74332A15CE663E5AD25C251`
SHA384 | `07E983B9197905C7E9583D1FA554607D200511F563617BB152CAC46EC615041EB05BD4F9EA1C2C256D074D259763650B`
SHA512 | `C3A6D77F2A9BC0C4DCE01C14F6655C802C5D9230575F9EFE0511A1A0D7B3C9D6FC5C2AE4E96F7A2C662C11854E8076B3C919A89EC6722BD6C0AF43CE71C10F12`
SSDEEP | `3072:xKVI87uPpuJxxY9G+6RxaRZds1dOdfk3CmOk/3M:xStuf9G+WardsvoNiM`
IMP | `4561307F8D53E046A9F112710810F6D8`
PESHA1 | `EAACBE95508B5DBFCD7F07D05075DCCD915B553E`
PE256 | `42DC76F4C08ABDB864A8BC8F25DDF9B39BB599D2905C5221E31FE7EA5BF3D58E`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`GUID_WINDOWS_MEMORY_TESTER` | 49 | Exported Function
`GUID_WINDOWS_OS_TARGET_TEMPLATE_EFI` | 50 | Exported Function
`GUID_WINDOWS_BOOTMGR` | 47 | Exported Function
`GUID_WINDOWS_LEGACY_NTLDR` | 48 | Exported Function
`GUID_WINDOWS_OS_TARGET_TEMPLATE_PCAT` | 51 | Exported Function
`GUID_WINDOWS_SETUP_EFI` | 54 | Exported Function
`GUID_WINDOWS_SETUP_PCAT` | 55 | Exported Function
`GUID_WINDOWS_RESUME_TARGET_TEMPLATE_EFI` | 52 | Exported Function
`GUID_WINDOWS_RESUME_TARGET_TEMPLATE_PCAT` | 53 | Exported Function
`GUID_DEFAULT_BOOT_ENTRY` | 40 | Exported Function
`GUID_EMS_SETTINGS_GROUP` | 41 | Exported Function
`GUID_CURRENT_BOOT_ENTRY` | 38 | Exported Function
`GUID_DEBUGGER_SETTINGS_GROUP` | 39 | Exported Function
`GUID_FIRMWARE_BOOTMGR` | 42 | Exported Function
`GUID_KERNEL_DEBUGGER_SETTINGS_GROUP` | 45 | Exported Function
`GUID_RESUME_LOADER_SETTINGS_GROUP` | 46 | Exported Function
`GUID_GLOBAL_SETTINGS_GROUP` | 43 | Exported Function
`GUID_HYPERVISOR_SETTINGS_GROUP` | 44 | Exported Function
`SyspartDirectGetSystemDisk` | 67 | Exported Function
`SyspartDirectGetSystemPartition` | 68 | Exported Function
`PARTITION_SPACES_GUID` | 65 | Exported Function
`PARTITION_SYSTEM_GUID` | 66 | Exported Function
`SyspartDirectSetSystemDevice` | 69 | Exported Function
`SyspartGetSystemPartition` | 72 | Exported Function
`SyspartIsSpace` | 73 | Exported Function
`SyspartGetPhysicalPartitions` | 70 | Exported Function
`SyspartGetSystemDisk` | 71 | Exported Function
`PARTITION_CLUSTER_GUID` | 58 | Exported Function
`PARTITION_ENTRY_UNUSED_GUID` | 59 | Exported Function
`GUID_WINDOWS_SETUP_RAMDISK_OPTIONS` | 56 | Exported Function
`PARTITION_BASIC_DATA_GUID` | 57 | Exported Function
`PARTITION_LDM_DATA_GUID` | 60 | Exported Function
`PARTITION_MSFT_RESERVED_GUID` | 63 | Exported Function
`PARTITION_MSFT_SNAPSHOT_GUID` | 64 | Exported Function
`PARTITION_LDM_METADATA_GUID` | 61 | Exported Function
`PARTITION_MSFT_RECOVERY_GUID` | 62 | Exported Function
`GUID_BOOT_LOADER_SETTINGS_GROUP` | 37 | Exported Function
`BcdEnumerateAndUnpackElements` | 12 | Exported Function
`BcdEnumerateElements` | 14 | Exported Function
`BcdDeleteObjectReferences` | 10 | Exported Function
`BcdDeleteSystemStore` | 11 | Exported Function
`BcdEnumerateElementsWithFlags` | 15 | Exported Function
`BcdExportStore` | 17 | Exported Function
`BcdFlushStore` | 18 | Exported Function
`BcdEnumerateElementTypes` | 13 | Exported Function
`BcdEnumerateObjects` | 16 | Exported Function
`BcdCopyObject` | 3 | Exported Function
`BcdCopyObjectEx` | 4 | Exported Function
`BcdCloseObject` | 1 | Exported Function
`BcdCloseStore` | 2 | Exported Function
`BcdCopyObjects` | 5 | Exported Function
`BcdDeleteElement` | 8 | Exported Function
`BcdDeleteObject` | 9 | Exported Function
`BcdCreateObject` | 6 | Exported Function
`BcdCreateStore` | 7 | Exported Function
`BcdOpenSystemStore` | 30 | Exported Function
`BcdQueryObject` | 31 | Exported Function
`BcdOpenStore` | 28 | Exported Function
`BcdOpenStoreFromFile` | 29 | Exported Function
`BcdSetElementData` | 32 | Exported Function
`BcdSetSystemStoreDevice` | 35 | Exported Function
`GUID_BAD_MEMORY_GROUP` | 36 | Exported Function
`BcdSetElementDataWithFlags` | 33 | Exported Function
`BcdSetLogging` | 34 | Exported Function
`BcdGetElementDataWithFlags` | 21 | Exported Function
`BcdGetSystemStorePath` | 22 | Exported Function
`BcdForciblyUnloadStore` | 19 | Exported Function
`BcdGetElementData` | 20 | Exported Function
`BcdImportStore` | 23 | Exported Function
`BcdMigrateObjectElementValues` | 26 | Exported Function
`BcdOpenObject` | 27 | Exported Function
`BcdImportStoreWithFlags` | 24 | Exported Function
`BcdMarkAsSystemStore` | 25 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bcd.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/5b3c3c3c75093787e2433a4d27ca716d1d6a0be9d74332a15ce663e5ad25c251/detection/





MIT License. Copyright (c) 2020 Strontic.


