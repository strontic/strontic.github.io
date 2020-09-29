---
title: miutils.dll | Management Infrastructure
excerpt: What is miutils.dll?
---

# miutils.dll 

* File Path: `C:\Windows\SysWOW64\miutils.dll`
* Description: Management Infrastructure

## Hashes

Type | Hash
-- | --
MD5 | `7F92FDB901C840CA331B3FB71C53A92B`
SHA1 | `EAE35E17862A95F3D9A8A749FDBFD4887724ABE7`
SHA256 | `95DE3E4C96998A9819488BDBD208CEA9CB145DA2A0373ABCDA8127BBF9E4E5C2`
SHA384 | `5B1E042EB83F9C13A38F8C0AA0236A859B8340930ABF3115E2E8038BECC7F998617D36265833F405420A3C78405D2D19`
SHA512 | `433C2FFFCD8B7CFC565E2F9BDB36693CE6781940030BEBD07356D3B605C8BCC082C880EB12B182999093C5F108857047C45322220F56DA6E00006B24D778E09C`
SSDEEP | `3072:7a+LQdRzoN9zMZZjKARxM3ZriSnLfVWloMgdqo7xYW2axt:7aBdR8NiZeR1nLYrLo7iW9`
IMP | `6A01BDB4F986CA85E321051FC8B67365`
PESHA1 | `C2B675DD0FFD6BB1962A8455F155413537E681F1`
PE256 | `0065F7986556F47DC5FDD5169ED57E3BC4E6B1D01752DB0005C215B8B1EDB5F2`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`_CimTypeToType@8` | 30 (0x1e) | Exported Function | 0x1001bd20 | 0x0001bd20
`PublishDebugMessage` | 82 (0x52) | Exported Function | 0x100089e0 | 0x000089e0
`PublishProviderResult` | 83 (0x53) | Exported Function | 0x10024b50 | 0x00024b50
`PublishProviderWriteError` | 84 (0x54) | Exported Function | 0x10024b60 | 0x00024b60
`PublishProviderWriteMessage` | 85 (0x55) | Exported Function | 0x10024b70 | 0x00024b70
`RCClass_AddClassQualifier` | 87 (0x57) | Exported Function | 0x10010240 | 0x00010240
`RCClass_AddClassQualifierArray` | 88 (0x58) | Exported Function | 0x10010280 | 0x00010280
`PublishDebugInfo` | 81 (0x51) | Exported Function | 0x10024b00 | 0x00024b00
`RCClass_AddClassQualifierArrayItem` | 89 (0x59) | Exported Function | 0x10010300 | 0x00010300
`RCClass_AddElementArray` | 91 (0x5b) | Exported Function | 0x100103d0 | 0x000103d0
`RCClass_AddElementArrayItem` | 92 (0x5c) | Exported Function | 0x10010460 | 0x00010460
`RCClass_AddElementQualifier` | 93 (0x5d) | Exported Function | 0x100104e0 | 0x000104e0
`RCClass_AddElementQualifierArray` | 94 (0x5e) | Exported Function | 0x10010520 | 0x00010520
`RCClass_AddElementQualifierArrayItem` | 95 (0x5f) | Exported Function | 0x100105a0 | 0x000105a0
`RCClass_AddMethod` | 96 (0x60) | Exported Function | 0x10010620 | 0x00010620
`RCClass_AddElement` | 90 (0x5a) | Exported Function | 0x10010380 | 0x00010380
`PublishClientOperationInfo` | 80 (0x50) | Exported Function | 0x10024ac0 | 0x00024ac0
`public: void __thiscall WMISchema::Initialize(bool)` | 25 (0x19) | Exported Function | 0x10020580 | 0x00020580
`public: virtual long __stdcall WMISchema::GetWmiIWbemServices(unsigned short const *,class ATL::CComPtr<struct IWbemServices> &)` | 23 (0x17) | Exported Function | 0x100203d0 | 0x000203d0
`public: __thiscall WMISchema::WMISchema(void)` | 6 (0x6) | Exported Function | 0x100084e0 | 0x000084e0
`public: class CAutoSetActivityId & __thiscall CAutoSetActivityId::operator=(class CAutoSetActivityId const &)` | 11 (0xb) | Exported Function | 0x10014780 | 0x00014780
`public: class CCritSec & __thiscall CCritSec::operator=(class CCritSec const &)` | 12 (0xc) | Exported Function | 0x100147e0 | 0x000147e0
`public: long __stdcall StaticSchema::Initialize(struct _MI_Module const *)` | 24 (0x18) | Exported Function | 0x10020560 | 0x00020560
`public: long __stdcall WMISchema::DeInitialize(void)` | 16 (0x10) | Exported Function | 0x1001fc80 | 0x0001fc80
`public: virtual __thiscall WMISchema::~WMISchema(void)` | 10 (0xa) | Exported Function | 0x1001f140 | 0x0001f140
`public: virtual long __stdcall DynamicSchema::CreateInstance(unsigned short const *,struct IWbemClassObject *,unsigned long,struct _MI_PropertySet const *,bool,struct _MI_Instance * &,struct IConversionContext *)` | 13 (0xd) | Exported Function | 0x1001f860 | 0x0001f860
`public: virtual long __stdcall DynamicSchema::GetMiClass(unsigned short const *,unsigned short const *,unsigned short const *,struct _MI_Class const * *)` | 18 (0x12) | Exported Function | 0x1001ff20 | 0x0001ff20
`public: virtual long __stdcall IndicationSchema::CreateInstance(unsigned short const *,struct IWbemClassObject *,unsigned long,struct _MI_PropertySet const *,bool,struct _MI_Instance * &,struct IConversionContext *)` | 14 (0xe) | Exported Function | 0x1001fa20 | 0x0001fa20
`public: virtual long __stdcall IndicationSchema::GetMiClass(unsigned short const *,unsigned short const *,unsigned short const *,struct _MI_Class const * *)` | 19 (0x13) | Exported Function | 0x1001ff30 | 0x0001ff30
`public: virtual long __stdcall MiSchema::GetFlags(void)const ` | 17 (0x11) | Exported Function | 0x1001fe60 | 0x0001fe60
`public: virtual long __stdcall StaticSchema::CreateInstance(unsigned short const *,struct IWbemClassObject *,unsigned long,struct _MI_PropertySet const *,bool,struct _MI_Instance * &,struct IConversionContext *)` | 15 (0xf) | Exported Function | 0x1001fae0 | 0x0001fae0
`public: virtual long __stdcall StaticSchema::GetMiClass(unsigned short const *,unsigned short const *,unsigned short const *,struct _MI_Class const * *)` | 20 (0x14) | Exported Function | 0x1001ffb0 | 0x0001ffb0
`public: virtual long __stdcall WMISchema::GetNoneCachedWmiClass(unsigned short const *,struct IWbemServices *,class ATL::CComPtr<struct IWbemClassObject> &,struct IConversionContext *)` | 21 (0x15) | Exported Function | 0x10020000 | 0x00020000
`public: virtual long __stdcall WMISchema::GetWmiClass(unsigned short const *,unsigned short const *,class ATL::CComPtr<struct IWbemClassObject> &,struct IConversionContext *)` | 22 (0x16) | Exported Function | 0x100201c0 | 0x000201c0
`RCClass_AddMethodParameter` | 97 (0x61) | Exported Function | 0x10010800 | 0x00010800
`public: __thiscall WMISchema::WMISchema(bool)` | 7 (0x7) | Exported Function | 0x1001efa0 | 0x0001efa0
`RCClass_AddMethodParameterQualifier` | 98 (0x62) | Exported Function | 0x100109b0 | 0x000109b0
`RCClass_AddMethodParameterQualifierArrayItem` | 100 (0x64) | Exported Function | 0x10010a80 | 0x00010a80
`RtlReleaseFastLockShared` | 118 (0x76) | Exported Function | 0x1000c480 | 0x0000c480
`RtlTryAcquireCachedFastLockShared` | 119 (0x77) | Exported Function | 0x10008f60 | 0x00008f60
`RtlTryAcquireFastLockExclusive` | 120 (0x78) | Exported Function | 0x10009fb0 | 0x00009fb0
`RtlTryAcquireFastLockShared` | 121 (0x79) | Exported Function | 0x1000c4b0 | 0x0000c4b0
`SetCorrelationIdToWbemContext` | 124 (0x7c) | Exported Function | 0x10024b80 | 0x00024b80
`SetModifiedPropertyNamesToContext` | 125 (0x7d) | Exported Function | 0x10027240 | 0x00027240
`RtlReleaseFastLockExclusive` | 117 (0x75) | Exported Function | 0x1000c450 | 0x0000c450
`WriteWBEM_MC_CLIENT_REQUEST_FAILURE` | 139 (0x8b) | Exported Function | 0x10024b90 | 0x00024b90
`XML_Init` | 143 (0x8f) | Exported Function | 0x10012230 | 0x00012230
`XML_Next` | 144 (0x90) | Exported Function | 0x10012260 | 0x00012260
`XML_PutError` | 145 (0x91) | Exported Function | 0x10012400 | 0x00012400
`XML_RegisterNameSpace` | 146 (0x92) | Exported Function | 0x100124c0 | 0x000124c0
`XML_SetText` | 147 (0x93) | Exported Function | 0x10012550 | 0x00012550
`XML_StripWhitespace` | 148 (0x94) | Exported Function | 0x10012580 | 0x00012580
`XML_FormatError` | 142 (0x8e) | Exported Function | 0x100121f0 | 0x000121f0
`RtlReleaseCachedFastLockShared` | 116 (0x74) | Exported Function | 0x10009030 | 0x00009030
`RtlReleaseCachedFastLockExclusive` | 115 (0x73) | Exported Function | 0x10008f30 | 0x00008f30
`RtlQueueAcquireFastLockShared` | 114 (0x72) | Exported Function | 0x1000c230 | 0x0000c230
`RCClass_AddMethodQualifier` | 101 (0x65) | Exported Function | 0x10010b10 | 0x00010b10
`RCClass_AddMethodQualifierArray` | 102 (0x66) | Exported Function | 0x10010b50 | 0x00010b50
`RCClass_AddMethodQualifierArrayItem` | 103 (0x67) | Exported Function | 0x10010bd0 | 0x00010bd0
`RCClass_New` | 104 (0x68) | Exported Function | 0x10010c50 | 0x00010c50
`ResultFromHRESULT` | 105 (0x69) | Exported Function | 0x10026260 | 0x00026260
`ResultToHRESULT` | 106 (0x6a) | Exported Function | 0x10009070 | 0x00009070
`RtlDeleteCachedFastLock` | 107 (0x6b) | Exported Function | 0x1000be80 | 0x0000be80
`RtlInitializeCachedFastLock` | 108 (0x6c) | Exported Function | 0x10008560 | 0x00008560
`RtlInterlockedCompareWait` | 109 (0x6d) | Exported Function | 0x1000bee0 | 0x0000bee0
`RtlInterlockedWakeAll` | 110 (0x6e) | Exported Function | 0x1000bff0 | 0x0000bff0
`RtlpInitFastLock` | 122 (0x7a) | Exported Function | 0x10008ea0 | 0x00008ea0
`RtlpReleaseIdleSlots` | 123 (0x7b) | Exported Function | 0x1000c6d0 | 0x0000c6d0
`RtlQueueAcquireCachedFastLockExclusive` | 111 (0x6f) | Exported Function | 0x10008a60 | 0x00008a60
`RtlQueueAcquireCachedFastLockShared` | 112 (0x70) | Exported Function | 0x10009f90 | 0x00009f90
`RtlQueueAcquireFastLockExclusive` | 113 (0x71) | Exported Function | 0x1000c070 | 0x0000c070
`RCClass_AddMethodParameterQualifierArray` | 99 (0x63) | Exported Function | 0x100109f0 | 0x000109f0
`public: __thiscall StaticSchema::StaticSchema(void)` | 5 (0x5) | Exported Function | 0x1001ef80 | 0x0001ef80
`public: __thiscall IndicationSchema::IndicationSchema(void)` | 4 (0x4) | Exported Function | 0x1001ef60 | 0x0001ef60
`public: __thiscall DynamicSchema::DynamicSchema(void)` | 3 (0x3) | Exported Function | 0x1001ef40 | 0x0001ef40
`_ParametersToWMIObject@40` | 77 (0x4d) | Exported Function | 0x1001d1e0 | 0x0001d1e0
`_PropertyToVariant@20` | 79 (0x4f) | Exported Function | 0x1001d630 | 0x0001d630
`_QualifierFlavorToWMI@4` | 86 (0x56) | Exported Function | 0x1001ddf0 | 0x0001ddf0
`_SetProperties@24` | 126 (0x7e) | Exported Function | 0x1001de20 | 0x0001de20
`_SubscriptionDeliveryOptions_Create@12` | 127 (0x7f) | Exported Function | 0x10023f10 | 0x00023f10
`_SubscriptionDeliveryOptions_MigrateOptions@8` | 128 (0x80) | Exported Function | 0x10023f60 | 0x00023f60
`_OptionsValueToContextValue@24` | 75 (0x4b) | Exported Function | 0x10023e10 | 0x00023e10
`_TypeToCimType@4` | 129 (0x81) | Exported Function | 0x1001de50 | 0x0001de50
`_ValueToVariant@24` | 131 (0x83) | Exported Function | 0x1000a050 | 0x0000a050
`_VariantArrayToSafeArray@12` | 132 (0x84) | Exported Function | 0x1001e190 | 0x0001e190
`_VariantToValue@28` | 133 (0x85) | Exported Function | 0x1001e410 | 0x0001e410
`_WMIEventToCIMIndication@12` | 134 (0x86) | Exported Function | 0x10022040 | 0x00022040
`_WMIExtendedObjectToInstance@20` | 135 (0x87) | Exported Function | 0x1001e440 | 0x0001e440
`_WMIObjectToClass@20` | 136 (0x88) | Exported Function | 0x1001e6f0 | 0x0001e6f0
`_ValueClear@8` | 130 (0x82) | Exported Function | 0x1001dfd0 | 0x0001dfd0
`_Options_FindValue@8` | 76 (0x4c) | Exported Function | 0x10023eb0 | 0x00023eb0
`_OperationOptions_MigrateOptions@8` | 74 (0x4a) | Exported Function | 0x10023cc0 | 0x00023cc0
`_OperationOptions_Create@12` | 73 (0x49) | Exported Function | 0x10023ca0 | 0x00023ca0
`_CompareInstance@12` | 36 (0x24) | Exported Function | 0x1001bfc0 | 0x0001bfc0
`_CompareValue@12` | 37 (0x25) | Exported Function | 0x1001c170 | 0x0001c170
`_DestinationOptions_Create@8` | 41 (0x29) | Exported Function | 0x10008660 | 0x00008660
`_DestinationOptions_Duplicate@8` | 42 (0x2a) | Exported Function | 0x10008fc0 | 0x00008fc0
`_DestinationOptions_MigrateOptions@16` | 43 (0x2b) | Exported Function | 0x10008d10 | 0x00008d10
`_FindClassDecl@8` | 44 (0x2c) | Exported Function | 0x1001c490 | 0x0001c490
`_FindMethodDecl@8` | 45 (0x2d) | Exported Function | 0x1001c4f0 | 0x0001c4f0
`_FindQualifierInWMIObject@16` | 46 (0x2e) | Exported Function | 0x1001c530 | 0x0001c530
`_GetMethodParameters@32` | 48 (0x30) | Exported Function | 0x1001c5c0 | 0x0001c5c0
`_GetReferenceFromWMIObjectPath@16` | 49 (0x31) | Exported Function | 0x1001c6c0 | 0x0001c6c0
`_InstanceToWMIEvent@16` | 50 (0x32) | Exported Function | 0x1001cd10 | 0x0001cd10
`_InstanceToWMIExtendedStatus@16` | 51 (0x33) | Exported Function | 0x1001cda0 | 0x0001cda0
`_InstanceToWMIObject@24` | 52 (0x34) | Exported Function | 0x1001d1b0 | 0x0001d1b0
`_IsLifeCycleIndicationQuery@12` | 64 (0x40) | Exported Function | 0x10021cf0 | 0x00021cf0
`_OperationOptions_CopyOptions@8` | 72 (0x48) | Exported Function | 0x10023bf0 | 0x00023bf0
`_WMIObjectToInstance@28` | 137 (0x89) | Exported Function | 0x1001e770 | 0x0001e770
`_WMIQualifierFlavorToMI@8` | 138 (0x8a) | Exported Function | 0x1001e8f0 | 0x0001e8f0
`CimError_Construct` | 28 (0x1c) | Exported Function | 0x1000c730 | 0x0000c730
`CimErrorFromErrorCode` | 27 (0x1b) | Exported Function | 0x10026110 | 0x00026110
`Instance_SetResourceURI` | 62 (0x3e) | Exported Function | 0x1000cad0 | 0x0000cad0
`Instance_SetServerName` | 63 (0x3f) | Exported Function | 0x1000cba0 | 0x0000cba0
`MI_Hash` | 65 (0x41) | Exported Function | 0x1000cc60 | 0x0000cc60
`MiErrorCategoryFromWindowsError` | 66 (0x42) | Exported Function | 0x100261e0 | 0x000261e0
`OSC_Batch_Destroy` | 67 (0x43) | Exported Function | 0x1000ccc0 | 0x0000ccc0
`OSC_Batch_Get` | 68 (0x44) | Exported Function | 0x1000cd30 | 0x0000cd30
`OSC_Batch_Strdup` | 69 (0x45) | Exported Function | 0x1000ce80 | 0x0000ce80
`OSC_StringToMiValue` | 70 (0x46) | Exported Function | 0x1000d760 | 0x0000d760
`OSC_Type_GetSize` | 71 (0x47) | Exported Function | 0x1000d920 | 0x0000d920
`PropertySet_New` | 78 (0x4e) | Exported Function | 0x10012180 | 0x00012180
`protected: virtual long __stdcall MiSchema::SetFlags(long)` | 26 (0x1a) | Exported Function | 0x10020a40 | 0x00020a40
`public: __thiscall CAutoSetActivityId::CAutoSetActivityId(void)` | 1 (0x1) | Exported Function | 0x100240d0 | 0x000240d0
`public: __thiscall CAutoSetActivityId::~CAutoSetActivityId(void)` | 8 (0x8) | Exported Function | 0x100241b0 | 0x000241b0
`public: __thiscall CCritSec::CCritSec(void)` | 2 (0x2) | Exported Function | 0x10014330 | 0x00014330
`public: __thiscall CCritSec::~CCritSec(void)` | 9 (0x9) | Exported Function | 0x100146a0 | 0x000146a0
`Instance_SetElementArrayItem` | 61 (0x3d) | Exported Function | 0x1000ca40 | 0x0000ca40
`XMLDOM_Free` | 140 (0x8c) | Exported Function | 0x10013800 | 0x00013800
`Instance_SetElementArray` | 60 (0x3c) | Exported Function | 0x1000c950 | 0x0000c950
`Instance_MatchKeys` | 58 (0x3a) | Exported Function | 0x1000c8e0 | 0x0000c8e0
`CimStatusCodeFromWindowsError` | 29 (0x1d) | Exported Function | 0x10026170 | 0x00026170
`Class_New` | 35 (0x23) | Exported Function | 0x1000fcc0 | 0x0000fcc0
`ClassCache_AddClass` | 31 (0x1f) | Exported Function | 0x10013c10 | 0x00013c10
`ClassCache_Delete` | 32 (0x20) | Exported Function | 0x10013dc0 | 0x00013dc0
`ClassCache_GetClass` | 33 (0x21) | Exported Function | 0x10013e30 | 0x00013e30
`ClassCache_New` | 34 (0x22) | Exported Function | 0x10008c40 | 0x00008c40
`Config_GetProtocolHandlerDetails` | 38 (0x26) | Exported Function | 0x10008150 | 0x00008150
`Config_GetRegString` | 39 (0x27) | Exported Function | 0x1000bda0 | 0x0000bda0
`CreateConversionContext` | 40 (0x28) | Exported Function | 0x10027220 | 0x00027220
`GetCorrelationId` | 47 (0x2f) | Exported Function | 0x10024a90 | 0x00024a90
`Instance_Clone` | 53 (0x35) | Exported Function | 0x1000c750 | 0x0000c750
`Instance_Construct` | 54 (0x36) | Exported Function | 0x1000c7b0 | 0x0000c7b0
`Instance_GetResourceURI` | 55 (0x37) | Exported Function | 0x1000c820 | 0x0000c820
`Instance_InitDynamic` | 56 (0x38) | Exported Function | 0x1000c870 | 0x0000c870
`Instance_IsDynamic` | 57 (0x39) | Exported Function | 0x1000c8c0 | 0x0000c8c0
`Instance_New` | 59 (0x3b) | Exported Function | 0x1000c900 | 0x0000c900
`XMLDOM_Parse` | 141 (0x8d) | Exported Function | 0x10013820 | 0x00013820


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: miutils.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/95de3e4c96998a9819488bdbd208cea9cb145da2a0373abcda8127bbf9e4e5c2/detection/





MIT License. Copyright (c) 2020 Strontic.


