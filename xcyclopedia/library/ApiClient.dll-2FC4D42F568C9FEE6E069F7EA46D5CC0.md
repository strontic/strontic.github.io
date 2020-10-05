---
title: ApiClient.dll | Microsoft Office API Client Library
excerpt: What is ApiClient.dll?
---

# ApiClient.dll 

* File Path: `C:\Program Files\Common Files\microsoft shared\ClickToRun\ApiClient.dll`
* Description: Microsoft Office API Client Library

## Hashes

Type | Hash
-- | --
MD5 | `2FC4D42F568C9FEE6E069F7EA46D5CC0`
SHA1 | `318429F05909B5D4097C2840D64029BC76D08D0F`
SHA256 | `F0D4D5993E3E236C288AB8534583DA7A624B340C0F6160F61FF4E2DF4A82D390`
SHA384 | `D1225836F1AB6FA8F9FECE236AAF5830F2A0FA92CE4AA820E05E821F59B1E144E6623EEE9DDC8C28F272351BB8B26005`
SHA512 | `8E419505B40F55486AAA25DDCA9E19C575986FFCD606168DCA0FFDA25E3AFFC5E5104185647F5CC277C5F647A6358F0FD35F53CA20BCC208728659EAF43DAEE9`
SSDEEP | `3072:B4CpiIobMeDFLH4fBKqEy6GWmVdppWfBfgdkoY46Qx+YmqOFieOq9Olf:hj/iFL8BKDP+diJohxGqOFn6l`
IMP | `49C5AB07947E05E4E37CA0F74AD81297`
PESHA1 | `5C0E9FF70F72B864DD4F72FDE0708DDD3A1EDB0B`
PE256 | `7508AE6704C4C6AFA2C5B7178671E0B4F30AB1077E6456380BE5A8E0C94F93D1`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`long __cdecl QueueTaskItem(class std::shared_ptr<class ORpcClient>,struct _GUID)` | 34 | Exported Function
`long __cdecl QueueUpdate(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64)` | 35 | Exported Function
`long __cdecl PublishRSOD(class std::shared_ptr<class ORpcClient>,int * __ptr64)` | 33 | Exported Function
`long __cdecl ModifyOfficeProducts(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,unsigned long,int)` | 31 | Exported Function
`long __cdecl PromptUser(class std::shared_ptr<class ORpcClient>,unsigned long,unsigned long * __ptr64,wchar_t const * __ptr64)` | 32 | Exported Function
`long __cdecl RaiseTaskErrorEvent(class std::shared_ptr<class ORpcClient>,unsigned long,unsigned long,unsigned long)` | 41 | Exported Function
`long __cdecl RaiseTaskErrorEvent2(class std::shared_ptr<class ORpcClient>,unsigned long,unsigned long,unsigned long,wchar_t const * __ptr64)` | 39 | Exported Function
`long __cdecl RaiseTaskDialogEvent(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64,wchar_t const * __ptr64)` | 38 | Exported Function
`long __cdecl QueueUpdateEx(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64,unsigned long)` | 36 | Exported Function
`long __cdecl QueueUpdateOnlyApply(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64)` | 37 | Exported Function
`long __cdecl KillQueuedProcesses(class std::shared_ptr<class ORpcClient>)` | 30 | Exported Function
`long __cdecl HandleMigrateOSPPToSPP(class std::shared_ptr<class ORpcClient>)` | 22 | Exported Function
`long __cdecl HrStartUpdatesDiscoveryPeriod(class std::shared_ptr<class ORpcClient>)` | 23 | Exported Function
`long __cdecl HandleHeartbeatScheduledTaskEx(class std::shared_ptr<class ORpcClient>,int,unsigned long)` | 21 | Exported Function
`long __cdecl GetServiceVersion(class std::shared_ptr<class ORpcClient>,wchar_t * __ptr64,unsigned long)` | 19 | Exported Function
`long __cdecl HandleHeartbeatScheduledTask(class std::shared_ptr<class ORpcClient>,int)` | 20 | Exported Function
`long __cdecl InvokeProcessKiller(class std::shared_ptr<class ORpcClient>,int,int,int,wchar_t const * __ptr64,unsigned long * __ptr64)` | 27 | Exported Function
`long __cdecl InvokeProcessKillerEx(class std::shared_ptr<class ORpcClient>,int,int,int,wchar_t const * __ptr64,wchar_t const * __ptr64,unsigned long * __ptr64)` | 28 | Exported Function
`long __cdecl InstallPOPEx(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64,int,int,wchar_t * __ptr64,int,int,unsigned long)` | 26 | Exported Function
`long __cdecl HrStartUpdatesDiscoveryPeriodEx(class std::shared_ptr<class ORpcClient>,unsigned long)` | 24 | Exported Function
`long __cdecl InstallPOP(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64,int,int,wchar_t * __ptr64,int,int)` | 25 | Exported Function
`long __cdecl RaiseTaskErrorEvent3(class std::shared_ptr<class ORpcClient>,unsigned long,unsigned long,unsigned long,unsigned long,wchar_t const * __ptr64)` | 40 | Exported Function
`RaiseTaskErrorEvent` | 80 | Exported Function
`RaiseTaskErrorEvent2` | 81 | Exported Function
`RaiseTaskDialogEvent` | 79 | Exported Function
`QueueUpdateEx` | 77 | Exported Function
`QueueUpdateOnlyApply` | 78 | Exported Function
`RestartKilledProcesses` | 85 | Exported Function
`SetPolicyOverride` | 86 | Exported Function
`RaiseTaskToastEvent` | 84 | Exported Function
`RaiseTaskErrorEvent3` | 82 | Exported Function
`RaiseTaskProgressEvent` | 83 | Exported Function
`QueueUpdate` | 76 | Exported Function
`long __cdecl SetPrivacySettings(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64,unsigned long,unsigned long,unsigned long,wchar_t const * __ptr64,unsigned long,unsigned long,wchar_t const * __ptr64,unsigned long,unsigned long,wchar_t const * __ptr64,unsigned long,unsigned long,wchar_t const * __ptr64,unsigned long,unsigned long,wchar_t const * __ptr64)` | 47 | Exported Function
`long __cdecl UninstallPOP(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64)` | 48 | Exported Function
`long __cdecl RestartKilledProcesses(class std::shared_ptr<class ORpcClient>)` | 44 | Exported Function
`long __cdecl RaiseTaskProgressEvent(class std::shared_ptr<class ORpcClient>,struct _GUID,unsigned long)` | 42 | Exported Function
`long __cdecl RaiseTaskToastEvent(class std::shared_ptr<class ORpcClient>,int)` | 43 | Exported Function
`PublishRSOD` | 74 | Exported Function
`QueueTaskItem` | 75 | Exported Function
`PromptUser` | 73 | Exported Function
`long __cdecl UninstallPOPEx(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64,unsigned long)` | 49 | Exported Function
`ModifyOfficeProducts` | 72 | Exported Function
`DoRepairForApp` | 58 | Exported Function
`DoRepairForAppEx` | 59 | Exported Function
`DiffRSOD` | 57 | Exported Function
`DetermineIsRepairRequired` | 55 | Exported Function
`DetermineIsRepairRequiredEx` | 56 | Exported Function
`GetPipelineTotalMegabytes` | 63 | Exported Function
`GetProcessPoolProcessId` | 64 | Exported Function
`GetPipelineStreamedMegabytes` | 62 | Exported Function
`GetClickToRunData` | 60 | Exported Function
`GetClickToRunDataEx` | 61 | Exported Function
`DeleteAFOTask` | 7 | Exported Function
`bool __cdecl ApplyPolicy(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,int)` | 3 | Exported Function
`bool __cdecl CollectFileDiagnostics(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64,wchar_t * __ptr64,unsigned long,unsigned long * __ptr64)` | 6 | Exported Function
`ApplyPolicy` | 52 | Exported Function
`Activate` | 50 | Exported Function
`ActivateEx` | 51 | Exported Function
`CancelUpdate` | 53 | Exported Function
`CollectFileDiagnostics` | 54 | Exported Function
`bool __cdecl SetPolicyOverride(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64)` | 46 | Exported Function
`bool __cdecl IsFileInVirtualFolder(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64)` | 29 | Exported Function
`bool __cdecl SetC2RProperty(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64,unsigned long,wchar_t const * __ptr64,unsigned long,unsigned long)` | 45 | Exported Function
`GetServiceVersion` | 65 | Exported Function
`long __cdecl DoRepairForAppEx(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64,unsigned long)` | 12 | Exported Function
`long __cdecl FetchDBSLicense(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64)` | 13 | Exported Function
`long __cdecl DoRepairForApp(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64)` | 11 | Exported Function
`long __cdecl DetermineIsRepairRequiredEx(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64,int & __ptr64,unsigned long)` | 9 | Exported Function
`long __cdecl DiffRSOD(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64,int * __ptr64)` | 10 | Exported Function
`long __cdecl GetPipelineTotalMegabytes(class std::shared_ptr<class ORpcClient>,unsigned long * __ptr64)` | 17 | Exported Function
`long __cdecl GetProcessPoolProcessId(class std::shared_ptr<class ORpcClient>,unsigned long * __ptr64)` | 18 | Exported Function
`long __cdecl GetPipelineStreamedMegabytes(class std::shared_ptr<class ORpcClient>,unsigned long * __ptr64)` | 16 | Exported Function
`long __cdecl GetClickToRunData(class std::shared_ptr<class ORpcClient>,int,wchar_t const * __ptr64,wchar_t * __ptr64,unsigned long)` | 14 | Exported Function
`long __cdecl GetClickToRunDataEx(class std::shared_ptr<class ORpcClient>,int,wchar_t const * __ptr64,wchar_t * __ptr64,unsigned long,unsigned long)` | 15 | Exported Function
`long __cdecl DetermineIsRepairRequired(class std::shared_ptr<class ORpcClient>,wchar_t const * __ptr64,int & __ptr64)` | 8 | Exported Function
`InvokeProcessKillerEx` | 69 | Exported Function
`IsFileInVirtualFolder` | 70 | Exported Function
`InvokeProcessKiller` | 68 | Exported Function
`HrStartUpdatesDiscoveryPeriod` | 66 | Exported Function
`HrStartUpdatesDiscoveryPeriodEx` | 67 | Exported Function
`long __cdecl CallReArm(class std::shared_ptr<class ORpcClient>,struct _GUID const * __ptr64)` | 4 | Exported Function
`long __cdecl CancelUpdate(class std::shared_ptr<class ORpcClient>)` | 5 | Exported Function
`long __cdecl ActivateEx(class std::shared_ptr<class ORpcClient>,struct _GUID const * __ptr64,unsigned long)` | 2 | Exported Function
`KillQueuedProcesses` | 71 | Exported Function
`long __cdecl Activate(class std::shared_ptr<class ORpcClient>,struct _GUID const * __ptr64)` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002CE7C9ACE7D905ED2B70000000002CE`
* Thumbprint: `B10607FB914700B40F794610850C1DE0A21566C1`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ApiClient.dll
* Product Name: Microsoft Office
* Company Name: Microsoft Corporation
* File Version: 16.0.12527.20470
* Product Version: 16.0.12527.20470
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/f0d4d5993e3e236c288ab8534583da7a624b340c0f6160f61ff4e2df4a82d390/detection/




MIT License. Copyright (c) 2020 Strontic.


