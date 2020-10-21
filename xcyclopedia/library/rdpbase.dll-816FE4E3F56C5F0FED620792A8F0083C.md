---
title: rdpbase.dll | Rdp OneCore Base Services
excerpt: What is rdpbase.dll?
---

# rdpbase.dll 

* File Path: `C:\Windows\system32\rdpbase.dll`
* Description: Rdp OneCore Base Services

## Hashes

Type | Hash
-- | --
MD5 | `816FE4E3F56C5F0FED620792A8F0083C`
SHA1 | `B2655391A7FD38269E3EE7B7B72741FE1A46A4D5`
SHA256 | `14FECA12AA85F3CE773C74CD54FF0E2F5A6895E321D51FF684D7EBC9700708EB`
SHA384 | `34841DFA82A261FA9ABF4179E4AA27DEC4462D7E978884C82121BB3CEAB0978235803E5100F08D20832976E34A05D355`
SHA512 | `87266B2C3A1A8A4D1595F25E162D18099E432DCBC14AA3754121AD583658357C0156520CDED41FBE696C6833DF82FDD4F41629BAA314AE3F590F7FC313725A1A`
SSDEEP | `24576:o3BIocQPyVY/y+N61EUjbJNrJJBBFL2eA5HpxuTz+kfKiiplQ6R3mOK7Rsh+f4Iw:o3OQPyV/+N6aqVNrJJBBkVHnun+kyii5`
IMP | `7A4A681FF8A3C60DED811F3C51230C15`
PESHA1 | `0919A347592E5D98B3654B976801C4F1A7457E2A`
PE256 | `846E489DD7BB51E5F7BC9412C1B237CE44486C596A89416400DB68A4690CA393`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`RDP_HMACMD5Update` | 200 | Exported Function
`RDP_HMACMD5Init` | 199 | Exported Function
`RDP_HMACMD5Final` | 198 | Exported Function
`RDP_MD5Final` | 201 | Exported Function
`RDP_RC4` | 204 | Exported Function
`RDP_MD5Update` | 203 | Exported Function
`RDP_MD5Init` | 202 | Exported Function
`FakeSleep` | 29 | Exported Function
`Initialize` | 41 | Exported Function
`Enable` | 27 | Exported Function
`XMLSerialize` | 71 | Exported Function
`InsertEntry` | 43 | Exported Function
`UnevictEntry` | 68 | Exported Function
`PromoteEntry` | 53 | Exported Function
`ParkEntry` | 48 | Exported Function
`RDP_SHAFinal` | 215 | Exported Function
`RDP_RsaGetPublicKeyLength` | 214 | Exported Function
`RDP_RsaGetPublicKeyDataLength` | 213 | Exported Function
`RDP_SHAInit` | 216 | Exported Function
`RDPAPI_GetGlobalObject` | 168 | Exported Function
`RDPAPI_GetGenericCounter` | 167 | Exported Function
`RDP_SHAUpdate` | 217 | Exported Function
`RDP_RsaBSafeEncPublic` | 212 | Exported Function
`RDP_RC4SetKey` | 207 | Exported Function
`RDP_RC4FreeKey` | 206 | Exported Function
`RDP_RC4AllocKey` | 205 | Exported Function
`RDP_RC4ZeroKey` | 208 | Exported Function
`RDP_RsaBCryptPubKeyToBSafePubKey` | 211 | Exported Function
`RDP_RsaBCryptGenerateRsaKeyPair` | 210 | Exported Function
`RDP_RsaBCryptDecryptPrivate` | 209 | Exported Function
`SetSessionId` | 62 | Exported Function
`CreateInstance` | 19 | Exported Function
`CreateInstance` | 18 | Exported Function
`IsSupportedVersion` | 44 | Exported Function
`CreateInstance` | 20 | Exported Function
`CreateInstance` | 24 | Exported Function
`CreateInstance` | 23 | Exported Function
`CreateInstance` | 21 | Exported Function
`GetInstance` | 31 | Exported Function
`Initialize` | 40 | Exported Function
`XMLDeserialize` | 70 | Exported Function
`GetPortMapping` | 36 | Exported Function
`Terminate` | 67 | Exported Function
`CreateInstance` | 22 | Exported Function
`SortAddresses` | 63 | Exported Function
`AddConnection` | 12 | Exported Function
`SearchCache` | 58 | Exported Function
`Reset` | 57 | Exported Function
`ClearCache` | 15 | Exported Function
`SetCacheEntry` | 59 | Exported Function
`SetConnectorId` | 60 | Exported Function
`InitializeInstance` | 42 | Exported Function
`AddPortMapping` | 13 | Exported Function
`public: virtual __cdecl CRDPCache::~CRDPCache(void) __ptr64` | 8 | Exported Function
`GetNext` | 34 | Exported Function
`GetFreeEntry` | 30 | Exported Function
`EvictEntry` | 28 | Exported Function
`GetMillisecondCount64` | 32 | Exported Function
`GetTickCount` | 37 | Exported Function
`GetMillisecondCount` | 33 | Exported Function
`StartEnum` | 65 | Exported Function
`RDPAPI_GetLongCounter` | 169 | Exported Function
`TsAddRectsToRegion` | 237 | Exported Function
`TRC_TraceBufferW` | 230 | Exported Function
`SubtractRects` | 229 | Exported Function
`TSAlloc` | 231 | Exported Function
`TSCreatePlatform` | 234 | Exported Function
`TSCreateCoreEvents` | 233 | Exported Function
`TSCreateBaseServices` | 232 | Exported Function
`SaveImageToFile` | 228 | Exported Function
`RdpX_DateTime_GetHighResolutionTimeSinceReboot` | 223 | Exported Function
`RdpX_AtomicIncrement32` | 222 | Exported Function
`RdpX_AtomicDecrement32` | 221 | Exported Function
`RdpX_DebugBreak` | 224 | Exported Function
`RgnlibBA_CreateInstance` | 227 | Exported Function
`RdpX_Threading_CreateCriticalSection` | 226 | Exported Function
`RdpX_GetActivityIdPrefix` | 225 | Exported Function
`unsigned long __cdecl NSRunLengthDecode(unsigned char const * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long)` | 46 | Exported Function
`UnpackServerCert` | 244 | Exported Function
`TsSetRegionFromRects` | 243 | Exported Function
`UpdateSessionKey` | 245 | Exported Function
`void __cdecl RdpPerfLoggerStaticTerminate(void)` | 56 | Exported Function
`void __cdecl RdpPerfLoggerStaticInitialize(void)` | 55 | Exported Function
`ValidateServerCert` | 246 | Exported Function
`TSRNG_GenerateRandomBits` | 236 | Exported Function
`TsDestroyRegion` | 239 | Exported Function
`TSDbgAssertThread` | 235 | Exported Function
`TsCreateRegion` | 238 | Exported Function
`TSFree` | 66 | Exported Function
`TsGetRegionRects` | 242 | Exported Function
`TsGetRegionRectCount` | 241 | Exported Function
`TsGetRegionBoundingBox` | 240 | Exported Function
`RDPWSStreamConnector_CreateInstance` | 197 | Exported Function
`RDPENCGDIHLP_FlipBitmapBitsInPlace` | 180 | Exported Function
`RDPENCGDIHLP_FlipBitmapBits` | 179 | Exported Function
`RDPENCDirectConnector_CreateInstance` | 178 | Exported Function
`RDPENCGDIHLP_ValidatePointerParams` | 181 | Exported Function
`RDPENCHLP_IsSessionActive` | 188 | Exported Function
`RDPENCHLP_IsGreaterThanOrEqWin8` | 187 | Exported Function
`RDPENCHLP_GetInputDesktopName` | 186 | Exported Function
`RDPDeCompress_GetContextSize` | 176 | Exported Function
`RDPCompress_GetContextSize` | 173 | Exported Function
`RDPCompress` | 171 | Exported Function
`RDPBASE_CreateInstance` | 170 | Exported Function
`RDPCompress_InitRecvContext` | 174 | Exported Function
`RDPDecompress` | 177 | Exported Function
`RDPCompressEx` | 172 | Exported Function
`RDPCompress_InitSendContext` | 175 | Exported Function
`RDPServerStackDiagnostics_LogFailure` | 194 | Exported Function
`RDPServerStackDiagnostics_LogDisconnect` | 193 | Exported Function
`RDPServerStackDiagnostics_LogCheckpoint` | 192 | Exported Function
`RDPServerStackDiagnostics_Register` | 195 | Exported Function
`RdpUnionRect` | 220 | Exported Function
`RdpTiledSurface_CreateInstance` | 219 | Exported Function
`RDPServerStackDiagnostics_Unregister` | 196 | Exported Function
`RdpIntersectRect` | 218 | Exported Function
`RDPENCHLPREG_ReadValueDWORD` | 182 | Exported Function
`RDPENCHLP_TraceWindowInfo` | 190 | Exported Function
`RDPENCHLP_IsSessionRemote` | 189 | Exported Function
`RDPENCHLPWS_GetIPFromAddr` | 184 | Exported Function
`RDPENCORE_AddGlobalObject` | 191 | Exported Function
`RDPENCHLPWSErr2Hr` | 183 | Exported Function
`RDPENCHLPWS_GetPortFromAddr` | 185 | Exported Function
`PAL_System_AtomicCompareAndExchange` | 107 | Exported Function
`MemMoveReverseAligned_SSE` | 106 | Exported Function
`MemEqual` | 105 | Exported Function
`PAL_System_AtomicCompareAndExchangePointer` | 108 | Exported Function
`PAL_System_AtomicExchangeAdd` | 111 | Exported Function
`PAL_System_AtomicExchange` | 110 | Exported Function
`PAL_System_AtomicDecrement` | 109 | Exported Function
`MemCopyAligned_SSE` | 104 | Exported Function
`long __cdecl CompressRdp8__CreateInstance(class IRdpPipeCompress * __ptr64 * __ptr64,unsigned int)` | 17 | Exported Function
`long __cdecl AlphaCompressor__CreateInstance(struct IRdpImageCompressor * __ptr64 * __ptr64)` | 14 | Exported Function
`int __cdecl PAL_System_Win32_IsRunningInAppContainer(void)` | 47 | Exported Function
`long __cdecl DecompressRdp8__CreateInstance(class IRdpPipeDecompress * __ptr64 * __ptr64)` | 26 | Exported Function
`MakeSessionKeys` | 103 | Exported Function
`long __cdecl RdpGfxProtocolServerEncoder_CreateInstance(class IRdpEncoderIO * __ptr64,class IRdpPipeProtocolEncoderEx * __ptr64 * __ptr64)` | 54 | Exported Function
`long __cdecl HintCoconet__CreateInstance(class IRdpPipeCompressHintProvider * __ptr64 * __ptr64)` | 39 | Exported Function
`PAL_System_CredUnprotect` | 122 | Exported Function
`PAL_System_CredProtect` | 121 | Exported Function
`PAL_System_CreateGuid` | 120 | Exported Function
`PAL_System_CritSecEnter` | 123 | Exported Function
`PAL_System_CritSecLeave` | 126 | Exported Function
`PAL_System_CritSecIsLockedByCurrentThread` | 125 | Exported Function
`PAL_System_CritSecInit` | 124 | Exported Function
`PAL_System_ConvertToAndFromWideChar` | 119 | Exported Function
`PAL_System_Beep` | 114 | Exported Function
`PAL_System_AtomicIncrement` | 113 | Exported Function
`PAL_System_AtomicExchangePointer` | 112 | Exported Function
`PAL_System_CondAlloc` | 115 | Exported Function
`PAL_System_CondWait` | 118 | Exported Function
`PAL_System_CondSignal` | 117 | Exported Function
`PAL_System_CondReset` | 116 | Exported Function
`GridBA_CreateInstance` | 102 | Exported Function
`CRDPCacVideoCodec_CreateInstance` | 86 | Exported Function
`CRDPCacCodecEncoder_CreateInstance` | 83 | Exported Function
`CRDPCacCodec_CreateInstance` | 84 | Exported Function
`CRDPCacVideoCodecForHardwareClient_CreateInstance` | 85 | Exported Function
`CRdpFIPSEncryption_CreateInstance` | 91 | Exported Function
`CRDPENCGfxEncoder_CreateInstance` | 88 | Exported Function
`CRDPCaps_CreateInstance` | 87 | Exported Function
`CRDPBitmapRecorder_CreateInstance` | 82 | Exported Function
`BitmapCombinePlanes` | 77 | Exported Function
`ApplySobelFilterOnLum` | 76 | Exported Function
`ApplyLuminanceFilter` | 75 | Exported Function
`CAPAPI_AddCapSet` | 78 | Exported Function
`CAPAPI_MergeCombinedCaps` | 81 | Exported Function
`CAPAPI_InitializeCombinedCaps` | 80 | Exported Function
`CAPAPI_GetCapSet` | 79 | Exported Function
`enum _XResult32 __cdecl XObjectId_RdpXHttpSession_CreateObject(struct RdpXInterface * __ptr64,unsigned int,enum _XInterfaceId32,void * __ptr64 * __ptr64)` | 72 | Exported Function
`EncryptData` | 99 | Exported Function
`EncryptClientRandom` | 98 | Exported Function
`enum _XResult32 __cdecl XObjectId_RdpXInterfaceUriComponents_CreateObject(struct RdpXInterface * __ptr64,unsigned int,enum _XInterfaceId32,void * __ptr64 * __ptr64)` | 73 | Exported Function
`GetSupportedSSELevel_SSE` | 101 | Exported Function
`ExpandRectForSSE` | 100 | Exported Function
`enum _XResult32 __cdecl XObjectId_RdpXSecFilterServer_CreateObject(struct RdpXInterface * __ptr64,unsigned int,enum _XInterfaceId32,void * __ptr64 * __ptr64)` | 74 | Exported Function
`DrawVLine` | 97 | Exported Function
`DecryptData` | 92 | Exported Function
`CRDPPlanarCompressor_CreateInstance` | 90 | Exported Function
`CRDPNsCodec_CreateInstance` | 89 | Exported Function
`DecryptDataEx` | 93 | Exported Function
`DrawIconToPixelMap` | 96 | Exported Function
`DrawHLine` | 95 | Exported Function
`DrawBox` | 94 | Exported Function
`PAL_System_CritSecTerminate` | 127 | Exported Function
`ProcessAlignedData_SSE41` | 51 | Exported Function
`ProcessAlignedData_SSE2` | 50 | Exported Function
`ProcessAlignedData_AVX` | 49 | Exported Function
`ProcessUnalignedData_REG` | 52 | Exported Function
`protected: __cdecl RdpGfxProtocolBaseDecoder::~RdpGfxProtocolBaseDecoder(void) __ptr64` | 11 | Exported Function
`RdpGfxProtocolBaseDecoder` | 6 | Exported Function
`UpdateKeys` | 69 | Exported Function
`PAL_System_WideCharToUnicode16` | 166 | Exported Function
`PAL_System_TimerCancel` | 161 | Exported Function
`PAL_System_TimeGetTimeZoneInformation` | 160 | Exported Function
`PAL_System_TimeGetTickCount64` | 159 | Exported Function
`PAL_System_TimerDelete` | 162 | Exported Function
`PAL_System_TimerSet` | 165 | Exported Function
`PAL_System_TimerIsSet` | 164 | Exported Function
`PAL_System_TimerInit` | 163 | Exported Function
`Compress` | 16 | Exported Function
`GetTimeHNS` | 38 | Exported Function
`SSECBCHash2` | 7 | Exported Function
`Decompress` | 25 | Exported Function
`GetNext` | 35 | Exported Function
`StartEnum` | 64 | Exported Function
`IsTestMode` | 45 | Exported Function
`RdpEncodeBuffer` | 5 | Exported Function
`CRDPENCONResolver` | 2 | Exported Function
`CRDPCache` | 1 | Exported Function
`SetDecodeBuffer` | 61 | Exported Function
`public: __cdecl CRDPENCONResolver::~CRDPENCONResolver(void) __ptr64` | 9 | Exported Function
`PipeETWEvents` | 4 | Exported Function
`NSCodecDecompressor` | 3 | Exported Function
`public: __cdecl Evict::~Evict(void) __ptr64` | 10 | Exported Function
`PAL_System_TimeGetTickCount` | 158 | Exported Function
`PAL_System_GetModuleFilename` | 138 | Exported Function
`PAL_System_GetLocalSessionId` | 137 | Exported Function
`PAL_System_GetFIPSAlgorithmEnabled` | 136 | Exported Function
`PAL_System_GetNetworkStatus` | 139 | Exported Function
`PAL_System_HandleFree` | 142 | Exported Function
`PAL_System_GetWindowsProductId` | 141 | Exported Function
`PAL_System_GetNumberOfProcessors` | 140 | Exported Function
`PAL_System_GetComputerName` | 135 | Exported Function
`PAL_System_CryptEncrypt` | 130 | Exported Function
`PAL_System_CryptDecryptLegacy` | 129 | Exported Function
`PAL_System_CritSecTryEnter` | 128 | Exported Function
`PAL_System_CryptFree` | 131 | Exported Function
`PAL_System_DebugOutput` | 134 | Exported Function
`PAL_System_DebugBreak` | 133 | Exported Function
`PAL_System_CryptZeroMemory` | 132 | Exported Function
`PAL_System_Sleep` | 153 | Exported Function
`PAL_System_SingleCondWait` | 152 | Exported Function
`PAL_System_SemaphoreRelease` | 151 | Exported Function
`PAL_System_SwitchToThread` | 154 | Exported Function
`PAL_System_TimeGetDynamicTimeZoneInformation` | 157 | Exported Function
`PAL_System_TimeGetCurrent` | 156 | Exported Function
`PAL_System_ThreadGetId` | 155 | Exported Function
`PAL_System_SemaphoreAlloc` | 150 | Exported Function
`PAL_System_NetworkMonitorInit` | 145 | Exported Function
`PAL_System_MemFree` | 144 | Exported Function
`PAL_System_MemAlloc` | 143 | Exported Function
`PAL_System_NetworkMonitorNotification` | 146 | Exported Function
`PAL_System_SemaphoreAcquire` | 149 | Exported Function
`PAL_System_SecureZeroMemory` | 148 | Exported Function
`PAL_System_NetworkMonitorTerminate` | 147 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rdpbase.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.84 (WinBuild.160101.0800)
* Product Version: 10.0.19041.84
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/14feca12aa85f3ce773c74cd54ff0e2f5a6895e321d51ff684d7ebc9700708eb/detection/





MIT License. Copyright (c) 2020 Strontic.


