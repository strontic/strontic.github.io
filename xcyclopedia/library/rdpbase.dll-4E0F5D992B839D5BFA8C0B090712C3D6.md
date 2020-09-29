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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`ApplyLuminanceFilter` | 72 (0x48) | Exported Function | 0x10086820 | 0x00086820
`public: virtual long __thiscall PipeETWEvents::Initialize(struct IUnknown *)` | 40 (0x28) | Exported Function | 0x1008fbc0 | 0x0008fbc0
`public: void __thiscall Evict::InsertEntry(struct _SCORE_ENTRY *,unsigned long)` | 42 (0x2a) | Exported Function | 0x10091b60 | 0x00091b60
`public: void __thiscall Evict::ParkEntry(struct _SCORE_ENTRY *)` | 46 (0x2e) | Exported Function | 0x10091c30 | 0x00091c30
`public: void __thiscall Evict::PromoteEntry(unsigned long,unsigned long)` | 51 (0x33) | Exported Function | 0x10091c60 | 0x00091c60
`public: void __thiscall Evict::UnevictEntry(struct _SCORE_ENTRY *)` | 66 (0x42) | Exported Function | 0x10091e80 | 0x00091e80
`RDP_HMACMD5Final` | 195 (0xc3) | Exported Function | 0x10100af0 | 0x00100af0
`RDP_HMACMD5Init` | 196 (0xc4) | Exported Function | 0x10100b30 | 0x00100b30
`RDP_HMACMD5Update` | 197 (0xc5) | Exported Function | 0x10100ba0 | 0x00100ba0
`RDP_MD5Final` | 198 (0xc6) | Exported Function | 0x10100be0 | 0x00100be0
`RDP_MD5Init` | 199 (0xc7) | Exported Function | 0x10100c20 | 0x00100c20
`RDP_MD5Update` | 200 (0xc8) | Exported Function | 0x10100ba0 | 0x00100ba0
`RDP_RC4` | 201 (0xc9) | Exported Function | 0x10100ca0 | 0x00100ca0
`public: virtual long __thiscall PipeETWEvents::Enable(unsigned long,unsigned long)` | 27 (0x1b) | Exported Function | 0x1008ed20 | 0x0008ed20
`RDP_RC4AllocKey` | 202 (0xca) | Exported Function | 0x10100ce0 | 0x00100ce0
`RDP_RC4SetKey` | 204 (0xcc) | Exported Function | 0x10100d50 | 0x00100d50
`RDP_RC4ZeroKey` | 205 (0xcd) | Exported Function | 0x10100dd0 | 0x00100dd0
`RDP_RsaBCryptDecryptPrivate` | 206 (0xce) | Exported Function | 0x10100df0 | 0x00100df0
`RDP_RsaBCryptGenerateRsaKeyPair` | 207 (0xcf) | Exported Function | 0x10100ed0 | 0x00100ed0
`RDP_RsaBCryptPubKeyToBSafePubKey` | 208 (0xd0) | Exported Function | 0x10101040 | 0x00101040
`RDP_RsaBSafeEncPublic` | 209 (0xd1) | Exported Function | 0x10101110 | 0x00101110
`RDP_RsaGetPublicKeyDataLength` | 210 (0xd2) | Exported Function | 0x10101290 | 0x00101290
`RDP_RsaGetPublicKeyLength` | 211 (0xd3) | Exported Function | 0x101012c0 | 0x001012c0
`RDP_SHAFinal` | 212 (0xd4) | Exported Function | 0x101012f0 | 0x001012f0
`RDP_SHAInit` | 213 (0xd5) | Exported Function | 0x10101330 | 0x00101330
`RDP_SHAUpdate` | 214 (0xd6) | Exported Function | 0x10100ba0 | 0x00100ba0
`RDPAPI_GetGenericCounter` | 164 (0xa4) | Exported Function | 0x10033300 | 0x00033300
`RDP_RC4FreeKey` | 203 (0xcb) | Exported Function | 0x10100d20 | 0x00100d20
`public: virtual long __stdcall CRDPENCConnectorStringSerializer::XMLSerialize(unsigned short * *)` | 69 (0x45) | Exported Function | 0x100b1f90 | 0x000b1f90
`public: virtual long __stdcall CRDPENCConnectorStringSerializer::SetSessionId(unsigned int)` | 60 (0x3c) | Exported Function | 0x100b1bc0 | 0x000b1bc0
`public: virtual long __stdcall CRDPENCConnectorStringSerializer::SetConnectorId(unsigned long)` | 58 (0x3a) | Exported Function | 0x100b1b50 | 0x000b1b50
`public: long __thiscall CRDPENCONIPHelper::Initialize(unsigned long,int,unsigned short *)` | 39 (0x27) | Exported Function | 0x100b2d90 | 0x000b2d90
`public: long __thiscall CRDPENCONIPHelper::Terminate(void)` | 65 (0x41) | Exported Function | 0x100b2fa0 | 0x000b2fa0
`public: long __thiscall CRDPENCONResolver::AddConnection(unsigned short *,unsigned long,int)` | 12 (0xc) | Exported Function | 0x100afc10 | 0x000afc10
`public: long __thiscall CRDPENCONResolver::SortAddresses(void)` | 61 (0x3d) | Exported Function | 0x100b1030 | 0x000b1030
`public: static bool __stdcall NSCodecCompressor::CreateInstance(bool,bool,bool,unsigned char,class TCntPtr<class NSCodecCompressor> &)` | 22 (0x16) | Exported Function | 0x10063130 | 0x00063130
`public: static class PipelineClock & __stdcall PipelineClock::GetInstance(void)` | 30 (0x1e) | Exported Function | 0x10040f20 | 0x00040f20
`public: static int __stdcall CRdpGfxCaps::IsSupportedVersion(unsigned long)` | 43 (0x2b) | Exported Function | 0x100554e0 | 0x000554e0
`public: static long __stdcall CRDPENCONPort::CreateInstance(struct addrinfo *,int,void *,class CRDPENCONPort * *)` | 18 (0x12) | Exported Function | 0x100b2180 | 0x000b2180
`public: static long __stdcall CRdpGfxCapsSet::CreateInstance(void *,unsigned long,struct IRdpGfxCapsSet * *)` | 19 (0x13) | Exported Function | 0x10054c20 | 0x00054c20
`public: static long __stdcall Evict::CreateInstance(unsigned long,unsigned long,unsigned long,unsigned long,unsigned long,class Evict * *)` | 20 (0x14) | Exported Function | 0x10091590 | 0x00091590
`public: static long __stdcall HashTable::CreateInstance(unsigned long,unsigned long,struct IHashBucket * *)` | 21 (0x15) | Exported Function | 0x10091f70 | 0x00091f70
`public: static long __stdcall PlanarCompressor::CreateInstance(unsigned short,unsigned short,unsigned char,int,int,int,struct IRdpImageCompressor * *)` | 23 (0x17) | Exported Function | 0x10064bf0 | 0x00064bf0
`public: static long __stdcall RdpEncodeBuffer::CreateInstance(class RdpEncodeBufferPool *,unsigned long,class RdpEncodeBuffer * *)` | 24 (0x18) | Exported Function | 0x10054490 | 0x00054490
`public: struct _SCORE_ENTRY * __thiscall Evict::EvictEntry(void)` | 28 (0x1c) | Exported Function | 0x10091680 | 0x00091680
`public: struct _SCORE_ENTRY * __thiscall Evict::GetFreeEntry(void)` | 29 (0x1d) | Exported Function | 0x10091740 | 0x00091740
`public: struct _SOCKET_ADDRESS * __thiscall CRDPENCONIPHelper::GetNext(void)` | 33 (0x21) | Exported Function | 0x100b2d40 | 0x000b2d40
`public: unsigned __int64 __thiscall PipelineClock::GetMillisecondCount64(void)` | 31 (0x1f) | Exported Function | 0x10092760 | 0x00092760
`public: unsigned int __thiscall CRDPENCONResolver::StartEnum(void)` | 63 (0x3f) | Exported Function | 0x100b1450 | 0x000b1450
`public: unsigned int __thiscall PipelineClock::GetMillisecondCount(void)` | 32 (0x20) | Exported Function | 0x10092790 | 0x00092790
`public: unsigned int __thiscall PipelineClock::GetTickCount(void)` | 36 (0x24) | Exported Function | 0x10042e40 | 0x00042e40
`public: virtual __thiscall CRDPCache::~CRDPCache(void)` | 8 (0x8) | Exported Function | 0x10095170 | 0x00095170
`public: virtual long __stdcall CRDPCache::ClearCache(void)` | 15 (0xf) | Exported Function | 0x10095240 | 0x00095240
`public: virtual long __stdcall CRDPCache::Reset(unsigned int)` | 55 (0x37) | Exported Function | 0x10095440 | 0x00095440
`public: virtual long __stdcall CRDPCache::SearchCache(unsigned int,unsigned int,struct IUnknown * *,unsigned int *)` | 56 (0x38) | Exported Function | 0x10095620 | 0x00095620
`public: virtual long __stdcall CRDPCache::SetCacheEntry(unsigned int,unsigned int,struct IUnknown *,unsigned int *)` | 57 (0x39) | Exported Function | 0x10095720 | 0x00095720
`public: virtual long __stdcall CRDPENCConnectorStringSerializer::AddPortMapping(unsigned short *,unsigned long)` | 13 (0xd) | Exported Function | 0x100b15c0 | 0x000b15c0
`public: virtual long __stdcall CRDPENCConnectorStringSerializer::InitializeInstance(void)` | 41 (0x29) | Exported Function | 0x100b1a20 | 0x000b1a20
`RDPAPI_GetGlobalObject` | 165 (0xa5) | Exported Function | 0x10038c30 | 0x00038c30
`public: long __thiscall CRDPENCConnectorStringDeserializer::XMLDeserialize(unsigned short *)` | 68 (0x44) | Exported Function | 0x100b1c30 | 0x000b1c30
`RDPAPI_GetLongCounter` | 166 (0xa6) | Exported Function | 0x100a4810 | 0x000a4810
`RDPCompress` | 168 (0xa8) | Exported Function | 0x1005df90 | 0x0005df90
`RdpX_DateTime_GetHighResolutionTimeSinceReboot` | 220 (0xdc) | Exported Function | 0x100541b0 | 0x000541b0
`RdpX_DebugBreak` | 221 (0xdd) | Exported Function | 0x10054220 | 0x00054220
`RdpX_GetActivityIdPrefix` | 222 (0xde) | Exported Function | 0x10054230 | 0x00054230
`RdpX_Threading_CreateCriticalSection` | 223 (0xdf) | Exported Function | 0x10048000 | 0x00048000
`RgnlibBA_CreateInstance` | 224 (0xe0) | Exported Function | 0x1008b380 | 0x0008b380
`SaveImageToFile` | 225 (0xe1) | Exported Function | 0x10087060 | 0x00087060
`SubtractRects` | 226 (0xe2) | Exported Function | 0x100874c0 | 0x000874c0
`TRC_TraceBufferW` | 227 (0xe3) | Exported Function | 0x10061bf0 | 0x00061bf0
`TsAddRectsToRegion` | 234 (0xea) | Exported Function | 0x1008dbb0 | 0x0008dbb0
`TSAlloc` | 228 (0xe4) | Exported Function | 0x10085f70 | 0x00085f70
`TSCreateBaseServices` | 229 (0xe5) | Exported Function | 0x1007f780 | 0x0007f780
`TSCreateCoreEvents` | 230 (0xe6) | Exported Function | 0x10082000 | 0x00082000
`RdpX_AtomicIncrement32` | 219 (0xdb) | Exported Function | 0x10043af0 | 0x00043af0
`TSCreatePlatform` | 231 (0xe7) | Exported Function | 0x100833a0 | 0x000833a0
`TSDbgAssertThread` | 232 (0xe8) | Exported Function | 0x10083430 | 0x00083430
`TsDestroyRegion` | 236 (0xec) | Exported Function | 0x1008dd80 | 0x0008dd80
`TSFree` | 64 (0x40) | Exported Function | 0x10047f30 | 0x00047f30
`TsGetRegionBoundingBox` | 237 (0xed) | Exported Function | 0x1008dea0 | 0x0008dea0
`TsGetRegionRectCount` | 238 (0xee) | Exported Function | 0x1008df10 | 0x0008df10
`TsGetRegionRects` | 239 (0xef) | Exported Function | 0x1008df60 | 0x0008df60
`TSRNG_GenerateRandomBits` | 233 (0xe9) | Exported Function | 0x10100a10 | 0x00100a10
`TsSetRegionFromRects` | 240 (0xf0) | Exported Function | 0x1008e010 | 0x0008e010
`UnpackServerCert` | 241 (0xf1) | Exported Function | 0x101003c0 | 0x001003c0
`unsigned long __stdcall NSRunLengthDecode(unsigned char const *,unsigned long,unsigned char *,unsigned long)` | 44 (0x2c) | Exported Function | 0x10063780 | 0x00063780
`UpdateSessionKey` | 242 (0xf2) | Exported Function | 0x101009a0 | 0x001009a0
`ValidateServerCert` | 243 (0xf3) | Exported Function | 0x10100480 | 0x00100480
`TsCreateRegion` | 235 (0xeb) | Exported Function | 0x1008dc80 | 0x0008dc80
`RdpX_AtomicDecrement32` | 218 (0xda) | Exported Function | 0x10047560 | 0x00047560
`RDPWSStreamConnector_CreateInstance` | 194 (0xc2) | Exported Function | 0x100d37c0 | 0x000d37c0
`RdpUnionRect` | 217 (0xd9) | Exported Function | 0x10087460 | 0x00087460
`RDPCompress_GetContextSize` | 170 (0xaa) | Exported Function | 0x1005e070 | 0x0005e070
`RDPCompress_InitRecvContext` | 171 (0xab) | Exported Function | 0x1005e0b0 | 0x0005e0b0
`RDPCompress_InitSendContext` | 172 (0xac) | Exported Function | 0x1005e110 | 0x0005e110
`RDPCompressEx` | 169 (0xa9) | Exported Function | 0x1005e000 | 0x0005e000
`RDPDecompress` | 174 (0xae) | Exported Function | 0x1005e1b0 | 0x0005e1b0
`RDPDeCompress_GetContextSize` | 173 (0xad) | Exported Function | 0x1005e160 | 0x0005e160
`RDPENCDirectConnector_CreateInstance` | 175 (0xaf) | Exported Function | 0x100b49a0 | 0x000b49a0
`RDPENCGDIHLP_FlipBitmapBits` | 176 (0xb0) | Exported Function | 0x100a4a80 | 0x000a4a80
`RDPENCGDIHLP_FlipBitmapBitsInPlace` | 177 (0xb1) | Exported Function | 0x100a4b20 | 0x000a4b20
`RDPENCGDIHLP_ValidatePointerParams` | 178 (0xb2) | Exported Function | 0x100a4d30 | 0x000a4d30
`RDPENCHLP_GetInputDesktopName` | 183 (0xb7) | Exported Function | 0x100a50f0 | 0x000a50f0
`RDPENCHLP_IsGreaterThanOrEqWin8` | 184 (0xb8) | Exported Function | 0x100a51e0 | 0x000a51e0
`RDPENCHLP_IsSessionActive` | 185 (0xb9) | Exported Function | 0x100a5290 | 0x000a5290
`RDPENCHLP_IsSessionRemote` | 186 (0xba) | Exported Function | 0x100a53a0 | 0x000a53a0
`RDPENCHLP_TraceWindowInfo` | 187 (0xbb) | Exported Function | 0x100a5470 | 0x000a5470
`RDPENCHLPREG_ReadValueDWORD` | 179 (0xb3) | Exported Function | 0x1003a3b0 | 0x0003a3b0
`RDPENCHLPWS_GetIPFromAddr` | 181 (0xb5) | Exported Function | 0x10047a30 | 0x00047a30
`RDPENCHLPWS_GetPortFromAddr` | 182 (0xb6) | Exported Function | 0x10041fd0 | 0x00041fd0
`RDPENCHLPWSErr2Hr` | 180 (0xb4) | Exported Function | 0x10029a60 | 0x00029a60
`RDPENCORE_AddGlobalObject` | 188 (0xbc) | Exported Function | 0x100a5d60 | 0x000a5d60
`RdpIntersectRect` | 215 (0xd7) | Exported Function | 0x10087410 | 0x00087410
`RDPServerStackDiagnostics_LogCheckpoint` | 189 (0xbd) | Exported Function | 0x100d41a0 | 0x000d41a0
`RDPServerStackDiagnostics_LogDisconnect` | 190 (0xbe) | Exported Function | 0x100d4210 | 0x000d4210
`RDPServerStackDiagnostics_LogFailure` | 191 (0xbf) | Exported Function | 0x100d42b0 | 0x000d42b0
`RDPServerStackDiagnostics_Register` | 192 (0xc0) | Exported Function | 0x100d4380 | 0x000d4380
`RDPServerStackDiagnostics_Unregister` | 193 (0xc1) | Exported Function | 0x100d43b0 | 0x000d43b0
`RdpTiledSurface_CreateInstance` | 216 (0xd8) | Exported Function | 0x100999b0 | 0x000999b0
`RDPBASE_CreateInstance` | 167 (0xa7) | Exported Function | 0x1002f6b0 | 0x0002f6b0
`void __stdcall RdpPerfLoggerStaticInitialize(void)` | 53 (0x35) | Exported Function | 0x100d3b90 | 0x000d3b90
`public: long __thiscall CRDPENCConnectorStringDeserializer::GetPortMapping(unsigned long,unsigned short * *,unsigned long *)` | 35 (0x23) | Exported Function | 0x100b1880 | 0x000b1880
`public: int __thiscall CRDPENCONIPHelper::StartEnum(void)` | 62 (0x3e) | Exported Function | 0x100b2f70 | 0x000b2f70
`long __stdcall CompressRdp8__CreateInstance(class IRdpPipeCompress * *,unsigned int)` | 17 (0x11) | Exported Function | 0x1007c690 | 0x0007c690
`long __stdcall DecompressRdp8__CreateInstance(class IRdpPipeDecompress * *)` | 26 (0x1a) | Exported Function | 0x1007cda0 | 0x0007cda0
`long __stdcall HintCoconet__CreateInstance(class IRdpPipeCompressHintProvider * *)` | 38 (0x26) | Exported Function | 0x1007d100 | 0x0007d100
`long __stdcall RdpGfxProtocolServerEncoder_CreateInstance(class IRdpEncoderIO *,class IRdpPipeProtocolEncoderEx * *)` | 52 (0x34) | Exported Function | 0x10094670 | 0x00094670
`MakeSessionKeys` | 100 (0x64) | Exported Function | 0x101007c0 | 0x001007c0
`MemCopyAligned_SSE` | 101 (0x65) | Exported Function | 0x100476a0 | 0x000476a0
`MemEqual` | 102 (0x66) | Exported Function | 0x10043500 | 0x00043500
`MemMoveReverseAligned_SSE` | 103 (0x67) | Exported Function | 0x10087650 | 0x00087650
`PAL_System_AtomicCompareAndExchange` | 104 (0x68) | Exported Function | 0x10034900 | 0x00034900
`PAL_System_AtomicCompareAndExchangePointer` | 105 (0x69) | Exported Function | 0x1008d2f0 | 0x0008d2f0
`PAL_System_AtomicDecrement` | 106 (0x6a) | Exported Function | 0x10033a20 | 0x00033a20
`PAL_System_AtomicExchange` | 107 (0x6b) | Exported Function | 0x1008d320 | 0x0008d320
`long __stdcall AlphaCompressor__CreateInstance(struct IRdpImageCompressor * *)` | 14 (0xe) | Exported Function | 0x10061d60 | 0x00061d60
`PAL_System_AtomicExchangeAdd` | 108 (0x6c) | Exported Function | 0x1008d340 | 0x0008d340
`PAL_System_AtomicIncrement` | 110 (0x6e) | Exported Function | 0x100280f0 | 0x000280f0
`PAL_System_Beep` | 111 (0x6f) | Exported Function | 0x100d6a50 | 0x000d6a50
`PAL_System_CondAlloc` | 112 (0x70) | Exported Function | 0x1008d390 | 0x0008d390
`PAL_System_CondReset` | 113 (0x71) | Exported Function | 0x1008d3d0 | 0x0008d3d0
`PAL_System_CondSignal` | 114 (0x72) | Exported Function | 0x10048380 | 0x00048380
`PAL_System_CondWait` | 115 (0x73) | Exported Function | 0x10039b80 | 0x00039b80
`PAL_System_ConvertToAndFromWideChar` | 116 (0x74) | Exported Function | 0x100d7cf0 | 0x000d7cf0
`PAL_System_CreateGuid` | 117 (0x75) | Exported Function | 0x100d7d40 | 0x000d7d40
`PAL_System_CredProtect` | 118 (0x76) | Exported Function | 0x100d6a70 | 0x000d6a70
`PAL_System_CredUnprotect` | 119 (0x77) | Exported Function | 0x100d6a90 | 0x000d6a90
`PAL_System_CritSecEnter` | 120 (0x78) | Exported Function | 0x10029a30 | 0x00029a30
`PAL_System_CritSecInit` | 121 (0x79) | Exported Function | 0x10030fb0 | 0x00030fb0
`PAL_System_AtomicExchangePointer` | 109 (0x6d) | Exported Function | 0x1008d370 | 0x0008d370
`int __stdcall PAL_System_Win32_IsRunningInAppContainer(void)` | 45 (0x2d) | Exported Function | 0x100d4e50 | 0x000d4e50
`GridBA_CreateInstance` | 99 (0x63) | Exported Function | 0x100896f0 | 0x000896f0
`GetSupportedSSELevel_SSE` | 98 (0x62) | Exported Function | 0x10087640 | 0x00087640
`ApplySobelFilterOnLum` | 73 (0x49) | Exported Function | 0x10086860 | 0x00086860
`BitmapCombinePlanes` | 74 (0x4a) | Exported Function | 0x100661f0 | 0x000661f0
`CAPAPI_AddCapSet` | 75 (0x4b) | Exported Function | 0x100783e0 | 0x000783e0
`CAPAPI_GetCapSet` | 76 (0x4c) | Exported Function | 0x10078410 | 0x00078410
`CAPAPI_InitializeCombinedCaps` | 77 (0x4d) | Exported Function | 0x100480d0 | 0x000480d0
`CAPAPI_MergeCombinedCaps` | 78 (0x4e) | Exported Function | 0x10078450 | 0x00078450
`CRDPBitmapRecorder_CreateInstance` | 79 (0x4f) | Exported Function | 0x100965d0 | 0x000965d0
`CRDPCacCodec_CreateInstance` | 81 (0x51) | Exported Function | 0x1004a740 | 0x0004a740
`CRDPCacCodecEncoder_CreateInstance` | 80 (0x50) | Exported Function | 0x1004a6b0 | 0x0004a6b0
`CRDPCacVideoCodec_CreateInstance` | 83 (0x53) | Exported Function | 0x1004a880 | 0x0004a880
`CRDPCacVideoCodecForHardwareClient_CreateInstance` | 82 (0x52) | Exported Function | 0x1004a820 | 0x0004a820
`CRDPCaps_CreateInstance` | 84 (0x54) | Exported Function | 0x10047580 | 0x00047580
`CRDPENCGfxEncoder_CreateInstance` | 85 (0x55) | Exported Function | 0x10098070 | 0x00098070
`CRdpFIPSEncryption_CreateInstance` | 88 (0x58) | Exported Function | 0x1008c160 | 0x0008c160
`CRDPNsCodec_CreateInstance` | 86 (0x56) | Exported Function | 0x10064640 | 0x00064640
`CRDPPlanarCompressor_CreateInstance` | 87 (0x57) | Exported Function | 0x10065480 | 0x00065480
`DecryptData` | 89 (0x59) | Exported Function | 0x10100180 | 0x00100180
`DecryptDataEx` | 90 (0x5a) | Exported Function | 0x101001f0 | 0x001001f0
`DrawBox` | 91 (0x5b) | Exported Function | 0x10086e70 | 0x00086e70
`DrawHLine` | 92 (0x5c) | Exported Function | 0x10086ed0 | 0x00086ed0
`DrawIconToPixelMap` | 93 (0x5d) | Exported Function | 0x10086f60 | 0x00086f60
`DrawVLine` | 94 (0x5e) | Exported Function | 0x10086fc0 | 0x00086fc0
`EncryptClientRandom` | 95 (0x5f) | Exported Function | 0x101002c0 | 0x001002c0
`EncryptData` | 96 (0x60) | Exported Function | 0x10100280 | 0x00100280
`enum _XResult32 __stdcall XObjectId_RdpXHttpSession_CreateObject(struct RdpXInterface *,unsigned int,enum _XInterfaceId32,void * *)` | 70 (0x46) | Exported Function | 0x1005cb00 | 0x0005cb00
`enum _XResult32 __stdcall XObjectId_RdpXInterfaceUriComponents_CreateObject(struct RdpXInterface *,unsigned int,enum _XInterfaceId32,void * *)` | 71 (0x47) | Exported Function | 0x1005cb90 | 0x0005cb90
`ExpandRectForSSE` | 97 (0x61) | Exported Function | 0x100873b0 | 0x000873b0
`PAL_System_CritSecIsLockedByCurrentThread` | 122 (0x7a) | Exported Function | 0x1008d400 | 0x0008d400
`public: int __thiscall CRDPENCONResolver::GetNext(struct sockaddr * *,unsigned int *)` | 34 (0x22) | Exported Function | 0x100b0620 | 0x000b0620
`PAL_System_CritSecLeave` | 123 (0x7b) | Exported Function | 0x1002be00 | 0x0002be00
`PAL_System_CritSecTryEnter` | 125 (0x7d) | Exported Function | 0x1008d430 | 0x0008d430
`PAL_System_TimeGetTimeZoneInformation` | 157 (0x9d) | Exported Function | 0x100d7de0 | 0x000d7de0
`PAL_System_TimerCancel` | 158 (0x9e) | Exported Function | 0x100d7610 | 0x000d7610
`PAL_System_TimerDelete` | 159 (0x9f) | Exported Function | 0x100d77d0 | 0x000d77d0
`PAL_System_TimerInit` | 160 (0xa0) | Exported Function | 0x100d7830 | 0x000d7830
`PAL_System_TimerIsSet` | 161 (0xa1) | Exported Function | 0x100d7950 | 0x000d7950
`PAL_System_TimerSet` | 162 (0xa2) | Exported Function | 0x100d79b0 | 0x000d79b0
`PAL_System_WideCharToUnicode16` | 163 (0xa3) | Exported Function | 0x100d7ef0 | 0x000d7ef0
`private: void __thiscall SSECBCHash2::ProcessAlignedData_AVX(unsigned int const *,unsigned int,unsigned int,unsigned int)` | 47 (0x2f) | Exported Function | 0x10085f90 | 0x00085f90
`private: void __thiscall SSECBCHash2::ProcessAlignedData_SSE2(unsigned int const *,unsigned int,unsigned int,unsigned int)` | 48 (0x30) | Exported Function | 0x10086470 | 0x00086470
`private: void __thiscall SSECBCHash2::ProcessAlignedData_SSE41(unsigned int const *,unsigned int,unsigned int,unsigned int)` | 49 (0x31) | Exported Function | 0x100425b0 | 0x000425b0
`private: void __thiscall SSECBCHash2::ProcessUnalignedData_REG(unsigned int const *,unsigned int,unsigned int,unsigned int)` | 50 (0x32) | Exported Function | 0x10086700 | 0x00086700
`private: void __thiscall SSECBCHash2::UpdateKeys(void)const ` | 67 (0x43) | Exported Function | 0x100867e0 | 0x000867e0
`PAL_System_TimeGetTickCount64` | 155 (0x9b) | Exported Function | 0x1008d7b0 | 0x0008d7b0
`protected: __thiscall RdpGfxProtocolBaseDecoder::RdpGfxProtocolBaseDecoder(void)` | 6 (0x6) | Exported Function | 0x100548c0 | 0x000548c0
`protected: void __thiscall RdpGfxProtocolBaseDecoder::SetDecodeBuffer(unsigned char const *,unsigned int)` | 59 (0x3b) | Exported Function | 0x10054900 | 0x00054900
`public: __int64 __thiscall PipelineClock::GetTimeHNS(void)` | 37 (0x25) | Exported Function | 0x100927c0 | 0x000927c0
`public: __thiscall CRDPCache::CRDPCache(void)` | 1 (0x1) | Exported Function | 0x10095100 | 0x00095100
`public: __thiscall CRDPENCONResolver::CRDPENCONResolver(void)` | 2 (0x2) | Exported Function | 0x100afa40 | 0x000afa40
`public: __thiscall CRDPENCONResolver::~CRDPENCONResolver(void)` | 9 (0x9) | Exported Function | 0x100afb20 | 0x000afb20
`public: __thiscall Evict::~Evict(void)` | 10 (0xa) | Exported Function | 0x10091460 | 0x00091460
`public: __thiscall NSCodecDecompressor::NSCodecDecompressor(bool)` | 3 (0x3) | Exported Function | 0x10062450 | 0x00062450
`public: __thiscall PipeETWEvents::PipeETWEvents(void)` | 4 (0x4) | Exported Function | 0x1008e780 | 0x0008e780
`public: __thiscall RdpEncodeBuffer::RdpEncodeBuffer(class ITSObjectPool *)` | 5 (0x5) | Exported Function | 0x10054390 | 0x00054390
`public: __thiscall SSECBCHash2::SSECBCHash2(void)` | 7 (0x7) | Exported Function | 0x10086200 | 0x00086200
`public: bool __thiscall NSCodecCompressor::Compress(class PixelMap const &,bool,unsigned char *,unsigned int,unsigned int &)` | 16 (0x10) | Exported Function | 0x10062990 | 0x00062990
`public: bool __thiscall NSCodecDecompressor::Decompress(unsigned char const *,unsigned int,class PixelMap &)` | 25 (0x19) | Exported Function | 0x10063180 | 0x00063180
`protected: __thiscall RdpGfxProtocolBaseDecoder::~RdpGfxProtocolBaseDecoder(void)` | 11 (0xb) | Exported Function | 0x100548e0 | 0x000548e0
`PAL_System_TimeGetTickCount` | 156 (0x9c) | Exported Function | 0x100487d0 | 0x000487d0
`PAL_System_TimeGetDynamicTimeZoneInformation` | 154 (0x9a) | Exported Function | 0x100d7450 | 0x000d7450
`PAL_System_TimeGetCurrent` | 153 (0x99) | Exported Function | 0x1008d750 | 0x0008d750
`PAL_System_CryptDecryptLegacy` | 126 (0x7e) | Exported Function | 0x100d6ab0 | 0x000d6ab0
`PAL_System_CryptEncrypt` | 127 (0x7f) | Exported Function | 0x100d6ad0 | 0x000d6ad0
`PAL_System_CryptFree` | 128 (0x80) | Exported Function | 0x100d6af0 | 0x000d6af0
`PAL_System_CryptZeroMemory` | 129 (0x81) | Exported Function | 0x100d7d60 | 0x000d7d60
`PAL_System_DebugBreak` | 130 (0x82) | Exported Function | 0x1008b790 | 0x0008b790
`PAL_System_DebugOutput` | 131 (0x83) | Exported Function | 0x1008b7a0 | 0x0008b7a0
`PAL_System_GetComputerName` | 132 (0x84) | Exported Function | 0x100d6b60 | 0x000d6b60
`PAL_System_GetFIPSAlgorithmEnabled` | 133 (0x85) | Exported Function | 0x1008b7d0 | 0x0008b7d0
`PAL_System_GetLocalSessionId` | 134 (0x86) | Exported Function | 0x100d6b80 | 0x000d6b80
`PAL_System_GetModuleFilename` | 135 (0x87) | Exported Function | 0x1008b8d0 | 0x0008b8d0
`PAL_System_GetNetworkStatus` | 136 (0x88) | Exported Function | 0x100d6bf0 | 0x000d6bf0
`PAL_System_GetNumberOfProcessors` | 137 (0x89) | Exported Function | 0x10048860 | 0x00048860
`PAL_System_GetWindowsProductId` | 138 (0x8a) | Exported Function | 0x100d7000 | 0x000d7000
`PAL_System_HandleFree` | 139 (0x8b) | Exported Function | 0x10042060 | 0x00042060
`PAL_System_MemAlloc` | 140 (0x8c) | Exported Function | 0x10048310 | 0x00048310
`PAL_System_MemFree` | 141 (0x8d) | Exported Function | 0x10047f30 | 0x00047f30
`PAL_System_NetworkMonitorInit` | 142 (0x8e) | Exported Function | 0x100d7070 | 0x000d7070
`PAL_System_NetworkMonitorNotification` | 143 (0x8f) | Exported Function | 0x100d7d90 | 0x000d7d90
`PAL_System_NetworkMonitorTerminate` | 144 (0x90) | Exported Function | 0x100d73e0 | 0x000d73e0
`PAL_System_SecureZeroMemory` | 145 (0x91) | Exported Function | 0x100d7db0 | 0x000d7db0
`PAL_System_SemaphoreAcquire` | 146 (0x92) | Exported Function | 0x1008d670 | 0x0008d670
`PAL_System_SemaphoreAlloc` | 147 (0x93) | Exported Function | 0x10040f80 | 0x00040f80
`PAL_System_SemaphoreRelease` | 148 (0x94) | Exported Function | 0x10028140 | 0x00028140
`PAL_System_SingleCondWait` | 149 (0x95) | Exported Function | 0x1008d700 | 0x0008d700
`PAL_System_Sleep` | 150 (0x96) | Exported Function | 0x1008b9d0 | 0x0008b9d0
`PAL_System_SwitchToThread` | 151 (0x97) | Exported Function | 0x1008b9e0 | 0x0008b9e0
`PAL_System_ThreadGetId` | 152 (0x98) | Exported Function | 0x1003f620 | 0x0003f620
`PAL_System_CritSecTerminate` | 124 (0x7c) | Exported Function | 0x1003ea40 | 0x0003ea40
`void __stdcall RdpPerfLoggerStaticTerminate(void)` | 54 (0x36) | Exported Function | 0x100d3ba0 | 0x000d3ba0


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


