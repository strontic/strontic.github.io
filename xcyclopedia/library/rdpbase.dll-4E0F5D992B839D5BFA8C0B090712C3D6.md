---
title: rdpbase.dll | Rdp OneCore Base Services
excerpt: What is rdpbase.dll?
---

# rdpbase.dll 

* File Path: `C:\Windows\SysWOW64\rdpbase.dll`
* Description: Rdp OneCore Base Services

## Hashes

Type | Hash
-- | --
MD5 | `4E0F5D992B839D5BFA8C0B090712C3D6`
SHA1 | `B30757CF19DB1C77D66E307EC15B937C77A34C75`
SHA256 | `AD2C60A5DF748C2410242B8165E726598FFF4B105AA8320F1A35194C3A6C8AE6`
SHA384 | `1CC715A98BBB38089BA9C771EB4C914EA173FB186CEE295881148E8A6E93794B7CD35AC9324A538661EBC7DCE3F98FF3`
SHA512 | `B31B3F5B1E61AEAEBC871A8DBA5B8F3C3FA730465C086C8AED01B5807759DACDC32D04F046DA7AE41540527AE2369F211B40BFCD7C3F6511BE9F55A1AB751F88`
SSDEEP | `24576:46MoImHSPMgjvWmUoJExreoQb59+qu3vTB3F3mMV+f8HlPa68:46kmHqjvW+Exq15jsmMofsa68`
IMP | `1C7F5DEC01A5DE854F88E6FCFD5860C9`
PESHA1 | `DDC8951C17BE7C7FD2BFB70FB693DA5EC2F3D5AD`
PE256 | `E025F5E7A2309B188173F2A79452264D72E099CB615A3893C0BB5B4DEF330CCB`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`RDP_MD5Final` | 198 | Exported Function
`RDP_HMACMD5Update` | 197 | Exported Function
`RDP_HMACMD5Init` | 196 | Exported Function
`RDP_MD5Init` | 199 | Exported Function
`RDP_RC4AllocKey` | 202 | Exported Function
`RDP_RC4` | 201 | Exported Function
`RDP_MD5Update` | 200 | Exported Function
`RDP_HMACMD5Final` | 195 | Exported Function
`public: virtual long __thiscall PipeETWEvents::Initialize(struct IUnknown *)` | 40 | Exported Function
`public: virtual long __thiscall PipeETWEvents::Enable(unsigned long,unsigned long)` | 27 | Exported Function
`public: virtual long __stdcall CRDPENCConnectorStringSerializer::XMLSerialize(unsigned short * *)` | 69 | Exported Function
`public: void __thiscall Evict::InsertEntry(struct _SCORE_ENTRY *,unsigned long)` | 42 | Exported Function
`public: void __thiscall Evict::UnevictEntry(struct _SCORE_ENTRY *)` | 66 | Exported Function
`public: void __thiscall Evict::PromoteEntry(unsigned long,unsigned long)` | 51 | Exported Function
`public: void __thiscall Evict::ParkEntry(struct _SCORE_ENTRY *)` | 46 | Exported Function
`RDP_SHAInit` | 213 | Exported Function
`RDP_SHAFinal` | 212 | Exported Function
`RDP_RsaGetPublicKeyLength` | 211 | Exported Function
`RDP_SHAUpdate` | 214 | Exported Function
`RDPAPI_GetLongCounter` | 166 | Exported Function
`RDPAPI_GetGlobalObject` | 165 | Exported Function
`RDPAPI_GetGenericCounter` | 164 | Exported Function
`RDP_RsaGetPublicKeyDataLength` | 210 | Exported Function
`RDP_RC4ZeroKey` | 205 | Exported Function
`RDP_RC4SetKey` | 204 | Exported Function
`RDP_RC4FreeKey` | 203 | Exported Function
`RDP_RsaBCryptDecryptPrivate` | 206 | Exported Function
`RDP_RsaBSafeEncPublic` | 209 | Exported Function
`RDP_RsaBCryptPubKeyToBSafePubKey` | 208 | Exported Function
`RDP_RsaBCryptGenerateRsaKeyPair` | 207 | Exported Function
`public: static long __stdcall Evict::CreateInstance(unsigned long,unsigned long,unsigned long,unsigned long,unsigned long,class Evict * *)` | 20 | Exported Function
`public: static long __stdcall CRdpGfxCapsSet::CreateInstance(void *,unsigned long,struct IRdpGfxCapsSet * *)` | 19 | Exported Function
`public: static long __stdcall CRDPENCONPort::CreateInstance(struct addrinfo *,int,void *,class CRDPENCONPort * *)` | 18 | Exported Function
`public: static long __stdcall HashTable::CreateInstance(unsigned long,unsigned long,struct IHashBucket * *)` | 21 | Exported Function
`public: struct _SCORE_ENTRY * __thiscall Evict::EvictEntry(void)` | 28 | Exported Function
`public: static long __stdcall RdpEncodeBuffer::CreateInstance(class RdpEncodeBufferPool *,unsigned long,class RdpEncodeBuffer * *)` | 24 | Exported Function
`public: static long __stdcall PlanarCompressor::CreateInstance(unsigned short,unsigned short,unsigned char,int,int,int,struct IRdpImageCompressor * *)` | 23 | Exported Function
`public: static int __stdcall CRdpGfxCaps::IsSupportedVersion(unsigned long)` | 43 | Exported Function
`public: long __thiscall CRDPENCONIPHelper::Terminate(void)` | 65 | Exported Function
`public: long __thiscall CRDPENCONIPHelper::Initialize(unsigned long,int,unsigned short *)` | 39 | Exported Function
`public: long __thiscall CRDPENCConnectorStringDeserializer::XMLDeserialize(unsigned short *)` | 68 | Exported Function
`public: long __thiscall CRDPENCONResolver::AddConnection(unsigned short *,unsigned long,int)` | 12 | Exported Function
`public: static class PipelineClock & __stdcall PipelineClock::GetInstance(void)` | 30 | Exported Function
`public: static bool __stdcall NSCodecCompressor::CreateInstance(bool,bool,bool,unsigned char,class TCntPtr<class NSCodecCompressor> &)` | 22 | Exported Function
`public: long __thiscall CRDPENCONResolver::SortAddresses(void)` | 61 | Exported Function
`public: virtual long __stdcall CRDPCache::SetCacheEntry(unsigned int,unsigned int,struct IUnknown *,unsigned int *)` | 57 | Exported Function
`public: virtual long __stdcall CRDPCache::SearchCache(unsigned int,unsigned int,struct IUnknown * *,unsigned int *)` | 56 | Exported Function
`public: virtual long __stdcall CRDPCache::Reset(unsigned int)` | 55 | Exported Function
`public: virtual long __stdcall CRDPENCConnectorStringSerializer::AddPortMapping(unsigned short *,unsigned long)` | 13 | Exported Function
`public: virtual long __stdcall CRDPENCConnectorStringSerializer::SetSessionId(unsigned int)` | 60 | Exported Function
`public: virtual long __stdcall CRDPENCConnectorStringSerializer::SetConnectorId(unsigned long)` | 58 | Exported Function
`public: virtual long __stdcall CRDPENCConnectorStringSerializer::InitializeInstance(void)` | 41 | Exported Function
`public: virtual long __stdcall CRDPCache::ClearCache(void)` | 15 | Exported Function
`public: unsigned __int64 __thiscall PipelineClock::GetMillisecondCount64(void)` | 31 | Exported Function
`public: struct _SOCKET_ADDRESS * __thiscall CRDPENCONIPHelper::GetNext(void)` | 33 | Exported Function
`public: struct _SCORE_ENTRY * __thiscall Evict::GetFreeEntry(void)` | 29 | Exported Function
`public: unsigned int __thiscall CRDPENCONResolver::StartEnum(void)` | 63 | Exported Function
`public: virtual __thiscall CRDPCache::~CRDPCache(void)` | 8 | Exported Function
`public: unsigned int __thiscall PipelineClock::GetTickCount(void)` | 36 | Exported Function
`public: unsigned int __thiscall PipelineClock::GetMillisecondCount(void)` | 32 | Exported Function
`RDPBASE_CreateInstance` | 167 | Exported Function
`TsAddRectsToRegion` | 234 | Exported Function
`TRC_TraceBufferW` | 227 | Exported Function
`SubtractRects` | 226 | Exported Function
`TSAlloc` | 228 | Exported Function
`TSCreatePlatform` | 231 | Exported Function
`TSCreateCoreEvents` | 230 | Exported Function
`TSCreateBaseServices` | 229 | Exported Function
`SaveImageToFile` | 225 | Exported Function
`RdpX_DateTime_GetHighResolutionTimeSinceReboot` | 220 | Exported Function
`RdpX_AtomicIncrement32` | 219 | Exported Function
`RdpX_AtomicDecrement32` | 218 | Exported Function
`RdpX_DebugBreak` | 221 | Exported Function
`RgnlibBA_CreateInstance` | 224 | Exported Function
`RdpX_Threading_CreateCriticalSection` | 223 | Exported Function
`RdpX_GetActivityIdPrefix` | 222 | Exported Function
`unsigned long __stdcall NSRunLengthDecode(unsigned char const *,unsigned long,unsigned char *,unsigned long)` | 44 | Exported Function
`UnpackServerCert` | 241 | Exported Function
`TsSetRegionFromRects` | 240 | Exported Function
`UpdateSessionKey` | 242 | Exported Function
`void __stdcall RdpPerfLoggerStaticTerminate(void)` | 54 | Exported Function
`void __stdcall RdpPerfLoggerStaticInitialize(void)` | 53 | Exported Function
`ValidateServerCert` | 243 | Exported Function
`TSRNG_GenerateRandomBits` | 233 | Exported Function
`TsDestroyRegion` | 236 | Exported Function
`TSDbgAssertThread` | 232 | Exported Function
`TsCreateRegion` | 235 | Exported Function
`TSFree` | 64 | Exported Function
`TsGetRegionRects` | 239 | Exported Function
`TsGetRegionRectCount` | 238 | Exported Function
`TsGetRegionBoundingBox` | 237 | Exported Function
`RDPENCGDIHLP_ValidatePointerParams` | 178 | Exported Function
`RDPENCGDIHLP_FlipBitmapBitsInPlace` | 177 | Exported Function
`RDPENCGDIHLP_FlipBitmapBits` | 176 | Exported Function
`RDPENCHLP_GetInputDesktopName` | 183 | Exported Function
`RDPENCHLP_IsSessionRemote` | 186 | Exported Function
`RDPENCHLP_IsSessionActive` | 185 | Exported Function
`RDPENCHLP_IsGreaterThanOrEqWin8` | 184 | Exported Function
`RDPENCDirectConnector_CreateInstance` | 175 | Exported Function
`RDPCompress_InitRecvContext` | 171 | Exported Function
`RDPCompress_GetContextSize` | 170 | Exported Function
`RDPCompress` | 168 | Exported Function
`RDPCompress_InitSendContext` | 172 | Exported Function
`RDPDeCompress_GetContextSize` | 173 | Exported Function
`RDPDecompress` | 174 | Exported Function
`RDPCompressEx` | 169 | Exported Function
`RDPServerStackDiagnostics_Register` | 192 | Exported Function
`RDPServerStackDiagnostics_LogFailure` | 191 | Exported Function
`RDPServerStackDiagnostics_LogDisconnect` | 190 | Exported Function
`RDPServerStackDiagnostics_Unregister` | 193 | Exported Function
`RDPWSStreamConnector_CreateInstance` | 194 | Exported Function
`RdpUnionRect` | 217 | Exported Function
`RdpTiledSurface_CreateInstance` | 216 | Exported Function
`RDPServerStackDiagnostics_LogCheckpoint` | 189 | Exported Function
`RDPENCHLPWS_GetIPFromAddr` | 181 | Exported Function
`RDPENCHLPREG_ReadValueDWORD` | 179 | Exported Function
`RDPENCHLP_TraceWindowInfo` | 187 | Exported Function
`RDPENCHLPWS_GetPortFromAddr` | 182 | Exported Function
`RdpIntersectRect` | 215 | Exported Function
`RDPENCORE_AddGlobalObject` | 188 | Exported Function
`RDPENCHLPWSErr2Hr` | 180 | Exported Function
`public: long __thiscall CRDPENCConnectorStringDeserializer::GetPortMapping(unsigned long,unsigned short * *,unsigned long *)` | 35 | Exported Function
`PAL_System_AtomicCompareAndExchange` | 104 | Exported Function
`MemMoveReverseAligned_SSE` | 103 | Exported Function
`MemEqual` | 102 | Exported Function
`PAL_System_AtomicCompareAndExchangePointer` | 105 | Exported Function
`PAL_System_AtomicExchangeAdd` | 108 | Exported Function
`PAL_System_AtomicExchange` | 107 | Exported Function
`PAL_System_AtomicDecrement` | 106 | Exported Function
`MemCopyAligned_SSE` | 101 | Exported Function
`long __stdcall CompressRdp8__CreateInstance(class IRdpPipeCompress * *,unsigned int)` | 17 | Exported Function
`long __stdcall AlphaCompressor__CreateInstance(struct IRdpImageCompressor * *)` | 14 | Exported Function
`int __stdcall PAL_System_Win32_IsRunningInAppContainer(void)` | 45 | Exported Function
`long __stdcall DecompressRdp8__CreateInstance(class IRdpPipeDecompress * *)` | 26 | Exported Function
`MakeSessionKeys` | 100 | Exported Function
`long __stdcall RdpGfxProtocolServerEncoder_CreateInstance(class IRdpEncoderIO *,class IRdpPipeProtocolEncoderEx * *)` | 52 | Exported Function
`long __stdcall HintCoconet__CreateInstance(class IRdpPipeCompressHintProvider * *)` | 38 | Exported Function
`PAL_System_CredUnprotect` | 119 | Exported Function
`PAL_System_CredProtect` | 118 | Exported Function
`PAL_System_CreateGuid` | 117 | Exported Function
`PAL_System_CritSecEnter` | 120 | Exported Function
`PAL_System_CritSecLeave` | 123 | Exported Function
`PAL_System_CritSecIsLockedByCurrentThread` | 122 | Exported Function
`PAL_System_CritSecInit` | 121 | Exported Function
`PAL_System_ConvertToAndFromWideChar` | 116 | Exported Function
`PAL_System_Beep` | 111 | Exported Function
`PAL_System_AtomicIncrement` | 110 | Exported Function
`PAL_System_AtomicExchangePointer` | 109 | Exported Function
`PAL_System_CondAlloc` | 112 | Exported Function
`PAL_System_CondWait` | 115 | Exported Function
`PAL_System_CondSignal` | 114 | Exported Function
`PAL_System_CondReset` | 113 | Exported Function
`CRDPCacVideoCodec_CreateInstance` | 83 | Exported Function
`CRDPCacCodecEncoder_CreateInstance` | 80 | Exported Function
`CRDPCacCodec_CreateInstance` | 81 | Exported Function
`CRDPCacVideoCodecForHardwareClient_CreateInstance` | 82 | Exported Function
`CRdpFIPSEncryption_CreateInstance` | 88 | Exported Function
`CRDPENCGfxEncoder_CreateInstance` | 85 | Exported Function
`CRDPCaps_CreateInstance` | 84 | Exported Function
`CRDPBitmapRecorder_CreateInstance` | 79 | Exported Function
`BitmapCombinePlanes` | 74 | Exported Function
`ApplySobelFilterOnLum` | 73 | Exported Function
`ApplyLuminanceFilter` | 72 | Exported Function
`CAPAPI_AddCapSet` | 75 | Exported Function
`CAPAPI_MergeCombinedCaps` | 78 | Exported Function
`CAPAPI_InitializeCombinedCaps` | 77 | Exported Function
`CAPAPI_GetCapSet` | 76 | Exported Function
`enum _XResult32 __stdcall XObjectId_RdpXHttpSession_CreateObject(struct RdpXInterface *,unsigned int,enum _XInterfaceId32,void * *)` | 70 | Exported Function
`EncryptData` | 96 | Exported Function
`EncryptClientRandom` | 95 | Exported Function
`enum _XResult32 __stdcall XObjectId_RdpXInterfaceUriComponents_CreateObject(struct RdpXInterface *,unsigned int,enum _XInterfaceId32,void * *)` | 71 | Exported Function
`GridBA_CreateInstance` | 99 | Exported Function
`GetSupportedSSELevel_SSE` | 98 | Exported Function
`ExpandRectForSSE` | 97 | Exported Function
`DrawVLine` | 94 | Exported Function
`DecryptData` | 89 | Exported Function
`CRDPPlanarCompressor_CreateInstance` | 87 | Exported Function
`CRDPNsCodec_CreateInstance` | 86 | Exported Function
`DecryptDataEx` | 90 | Exported Function
`DrawIconToPixelMap` | 93 | Exported Function
`DrawHLine` | 92 | Exported Function
`DrawBox` | 91 | Exported Function
`PAL_System_CritSecTerminate` | 124 | Exported Function
`private: void __thiscall SSECBCHash2::ProcessAlignedData_SSE2(unsigned int const *,unsigned int,unsigned int,unsigned int)` | 48 | Exported Function
`private: void __thiscall SSECBCHash2::ProcessAlignedData_AVX(unsigned int const *,unsigned int,unsigned int,unsigned int)` | 47 | Exported Function
`PAL_System_WideCharToUnicode16` | 163 | Exported Function
`private: void __thiscall SSECBCHash2::ProcessAlignedData_SSE41(unsigned int const *,unsigned int,unsigned int,unsigned int)` | 49 | Exported Function
`protected: __thiscall RdpGfxProtocolBaseDecoder::RdpGfxProtocolBaseDecoder(void)` | 6 | Exported Function
`private: void __thiscall SSECBCHash2::UpdateKeys(void)const ` | 67 | Exported Function
`private: void __thiscall SSECBCHash2::ProcessUnalignedData_REG(unsigned int const *,unsigned int,unsigned int,unsigned int)` | 50 | Exported Function
`PAL_System_TimerSet` | 162 | Exported Function
`PAL_System_TimeGetTimeZoneInformation` | 157 | Exported Function
`PAL_System_TimeGetTickCount64` | 155 | Exported Function
`PAL_System_TimeGetTickCount` | 156 | Exported Function
`PAL_System_TimerCancel` | 158 | Exported Function
`PAL_System_TimerIsSet` | 161 | Exported Function
`PAL_System_TimerInit` | 160 | Exported Function
`PAL_System_TimerDelete` | 159 | Exported Function
`public: __thiscall SSECBCHash2::SSECBCHash2(void)` | 7 | Exported Function
`public: __thiscall RdpEncodeBuffer::RdpEncodeBuffer(class ITSObjectPool *)` | 5 | Exported Function
`public: __thiscall PipeETWEvents::PipeETWEvents(void)` | 4 | Exported Function
`public: bool __thiscall NSCodecCompressor::Compress(class PixelMap const &,bool,unsigned char *,unsigned int,unsigned int &)` | 16 | Exported Function
`public: int __thiscall CRDPENCONResolver::GetNext(struct sockaddr * *,unsigned int *)` | 34 | Exported Function
`public: int __thiscall CRDPENCONIPHelper::StartEnum(void)` | 62 | Exported Function
`public: bool __thiscall NSCodecDecompressor::Decompress(unsigned char const *,unsigned int,class PixelMap &)` | 25 | Exported Function
`public: __thiscall NSCodecDecompressor::NSCodecDecompressor(bool)` | 3 | Exported Function
`public: __int64 __thiscall PipelineClock::GetTimeHNS(void)` | 37 | Exported Function
`protected: void __thiscall RdpGfxProtocolBaseDecoder::SetDecodeBuffer(unsigned char const *,unsigned int)` | 59 | Exported Function
`protected: __thiscall RdpGfxProtocolBaseDecoder::~RdpGfxProtocolBaseDecoder(void)` | 11 | Exported Function
`public: __thiscall CRDPCache::CRDPCache(void)` | 1 | Exported Function
`public: __thiscall Evict::~Evict(void)` | 10 | Exported Function
`public: __thiscall CRDPENCONResolver::~CRDPENCONResolver(void)` | 9 | Exported Function
`public: __thiscall CRDPENCONResolver::CRDPENCONResolver(void)` | 2 | Exported Function
`PAL_System_GetModuleFilename` | 135 | Exported Function
`PAL_System_GetLocalSessionId` | 134 | Exported Function
`PAL_System_GetFIPSAlgorithmEnabled` | 133 | Exported Function
`PAL_System_GetNetworkStatus` | 136 | Exported Function
`PAL_System_HandleFree` | 139 | Exported Function
`PAL_System_GetWindowsProductId` | 138 | Exported Function
`PAL_System_GetNumberOfProcessors` | 137 | Exported Function
`PAL_System_GetComputerName` | 132 | Exported Function
`PAL_System_CryptEncrypt` | 127 | Exported Function
`PAL_System_CryptDecryptLegacy` | 126 | Exported Function
`PAL_System_CritSecTryEnter` | 125 | Exported Function
`PAL_System_CryptFree` | 128 | Exported Function
`PAL_System_DebugOutput` | 131 | Exported Function
`PAL_System_DebugBreak` | 130 | Exported Function
`PAL_System_CryptZeroMemory` | 129 | Exported Function
`PAL_System_Sleep` | 150 | Exported Function
`PAL_System_SingleCondWait` | 149 | Exported Function
`PAL_System_SemaphoreRelease` | 148 | Exported Function
`PAL_System_SwitchToThread` | 151 | Exported Function
`PAL_System_TimeGetDynamicTimeZoneInformation` | 154 | Exported Function
`PAL_System_TimeGetCurrent` | 153 | Exported Function
`PAL_System_ThreadGetId` | 152 | Exported Function
`PAL_System_SemaphoreAlloc` | 147 | Exported Function
`PAL_System_NetworkMonitorInit` | 142 | Exported Function
`PAL_System_MemFree` | 141 | Exported Function
`PAL_System_MemAlloc` | 140 | Exported Function
`PAL_System_NetworkMonitorNotification` | 143 | Exported Function
`PAL_System_SemaphoreAcquire` | 146 | Exported Function
`PAL_System_SecureZeroMemory` | 145 | Exported Function
`PAL_System_NetworkMonitorTerminate` | 144 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/ad2c60a5df748c2410242b8165e726598fff4b105aa8320f1a35194c3a6c8ae6/detection/





MIT License. Copyright (c) 2020 Strontic.


