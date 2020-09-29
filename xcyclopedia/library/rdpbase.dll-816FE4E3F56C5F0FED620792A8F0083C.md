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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`ApplyLuminanceFilter` | 75 (0x4b) | Exported Function | 0x0000000180012af0 | 0x00012af0
`public: virtual long __cdecl PipeETWEvents::Initialize(struct IUnknown * __ptr64) __ptr64` | 41 (0x29) | Exported Function | 0x0000000180086650 | 0x00086650
`public: void __cdecl Evict::InsertEntry(struct _SCORE_ENTRY * __ptr64,unsigned long) __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180032260 | 0x00032260
`public: void __cdecl Evict::ParkEntry(struct _SCORE_ENTRY * __ptr64) __ptr64` | 48 (0x30) | Exported Function | 0x0000000180088bf0 | 0x00088bf0
`public: void __cdecl Evict::PromoteEntry(unsigned long,unsigned long) __ptr64` | 53 (0x35) | Exported Function | 0x00000001800295b0 | 0x000295b0
`public: void __cdecl Evict::UnevictEntry(struct _SCORE_ENTRY * __ptr64) __ptr64` | 68 (0x44) | Exported Function | 0x0000000180088c70 | 0x00088c70
`public: void __cdecl PipelineClock::FakeSleep(unsigned __int64) __ptr64` | 29 (0x1d) | Exported Function | 0x00000001800893a0 | 0x000893a0
`RDP_HMACMD5Final` | 198 (0xc6) | Exported Function | 0x000000018010b750 | 0x0010b750
`RDP_HMACMD5Init` | 199 (0xc7) | Exported Function | 0x000000018010b7a0 | 0x0010b7a0
`RDP_HMACMD5Update` | 200 (0xc8) | Exported Function | 0x000000018010b860 | 0x0010b860
`RDP_MD5Final` | 201 (0xc9) | Exported Function | 0x000000018010b8b0 | 0x0010b8b0
`RDP_MD5Init` | 202 (0xca) | Exported Function | 0x000000018010b900 | 0x0010b900
`RDP_MD5Update` | 203 (0xcb) | Exported Function | 0x000000018010b860 | 0x0010b860
`public: virtual long __cdecl PipeETWEvents::Enable(unsigned long,unsigned long) __ptr64` | 27 (0x1b) | Exported Function | 0x0000000180085520 | 0x00085520
`RDP_RC4` | 204 (0xcc) | Exported Function | 0x000000018010b9b0 | 0x0010b9b0
`RDP_RC4FreeKey` | 206 (0xce) | Exported Function | 0x000000018010ba60 | 0x0010ba60
`RDP_RC4SetKey` | 207 (0xcf) | Exported Function | 0x000000018010baa0 | 0x0010baa0
`RDP_RC4ZeroKey` | 208 (0xd0) | Exported Function | 0x000000018010bb70 | 0x0010bb70
`RDP_RsaBCryptDecryptPrivate` | 209 (0xd1) | Exported Function | 0x000000018010bb90 | 0x0010bb90
`RDP_RsaBCryptGenerateRsaKeyPair` | 210 (0xd2) | Exported Function | 0x000000018010bcf0 | 0x0010bcf0
`RDP_RsaBCryptPubKeyToBSafePubKey` | 211 (0xd3) | Exported Function | 0x000000018010bf10 | 0x0010bf10
`RDP_RsaBSafeEncPublic` | 212 (0xd4) | Exported Function | 0x000000018010c030 | 0x0010c030
`RDP_RsaGetPublicKeyDataLength` | 213 (0xd5) | Exported Function | 0x000000018010c1f0 | 0x0010c1f0
`RDP_RsaGetPublicKeyLength` | 214 (0xd6) | Exported Function | 0x000000018010c210 | 0x0010c210
`RDP_SHAFinal` | 215 (0xd7) | Exported Function | 0x000000018010c230 | 0x0010c230
`RDP_SHAInit` | 216 (0xd8) | Exported Function | 0x000000018010c280 | 0x0010c280
`RDP_SHAUpdate` | 217 (0xd9) | Exported Function | 0x000000018010b860 | 0x0010b860
`RDP_RC4AllocKey` | 205 (0xcd) | Exported Function | 0x000000018010ba00 | 0x0010ba00
`public: virtual long __cdecl CRDPENCConnectorStringSerializer::XMLSerialize(unsigned short * __ptr64 * __ptr64) __ptr64` | 71 (0x47) | Exported Function | 0x00000001800ad3b0 | 0x000ad3b0
`public: virtual long __cdecl CRDPENCConnectorStringSerializer::SetSessionId(unsigned int) __ptr64` | 62 (0x3e) | Exported Function | 0x00000001800acf70 | 0x000acf70
`public: virtual long __cdecl CRDPENCConnectorStringSerializer::SetConnectorId(unsigned long) __ptr64` | 60 (0x3c) | Exported Function | 0x00000001800acee0 | 0x000acee0
`public: long __cdecl CRDPENCONIPHelper::Initialize(unsigned long,int,unsigned short * __ptr64) __ptr64` | 40 (0x28) | Exported Function | 0x00000001800ae5e0 | 0x000ae5e0
`public: long __cdecl CRDPENCONIPHelper::Terminate(void) __ptr64` | 67 (0x43) | Exported Function | 0x00000001800ae840 | 0x000ae840
`public: long __cdecl CRDPENCONResolver::AddConnection(unsigned short * __ptr64,unsigned long,int) __ptr64` | 12 (0xc) | Exported Function | 0x00000001800aa720 | 0x000aa720
`public: long __cdecl CRDPENCONResolver::SortAddresses(void) __ptr64` | 63 (0x3f) | Exported Function | 0x00000001800ac080 | 0x000ac080
`public: static bool __cdecl NSCodecCompressor::CreateInstance(bool,bool,bool,unsigned char,class TCntPtr<class NSCodecCompressor> & __ptr64)` | 22 (0x16) | Exported Function | 0x0000000180055c80 | 0x00055c80
`public: static class PipelineClock & __ptr64 __cdecl PipelineClock::GetInstance(void)` | 31 (0x1f) | Exported Function | 0x0000000180002390 | 0x00002390
`public: static int __cdecl CRdpGfxCaps::IsSupportedVersion(unsigned long)` | 44 (0x2c) | Exported Function | 0x0000000180046c40 | 0x00046c40
`public: static long __cdecl CRDPENCONPort::CreateInstance(struct addrinfo * __ptr64,int,void * __ptr64,class CRDPENCONPort * __ptr64 * __ptr64)` | 18 (0x12) | Exported Function | 0x00000001800ad630 | 0x000ad630
`public: static long __cdecl CRdpGfxCapsSet::CreateInstance(void * __ptr64,unsigned long,struct IRdpGfxCapsSet * __ptr64 * __ptr64)` | 19 (0x13) | Exported Function | 0x0000000180046180 | 0x00046180
`public: static long __cdecl Evict::CreateInstance(unsigned long,unsigned long,unsigned long,unsigned long,unsigned long,class Evict * __ptr64 * __ptr64)` | 20 (0x14) | Exported Function | 0x00000001800885f0 | 0x000885f0
`public: static long __cdecl HashTable::CreateInstance(unsigned long,unsigned long,struct IHashBucket * __ptr64 * __ptr64)` | 21 (0x15) | Exported Function | 0x0000000180088d70 | 0x00088d70
`public: static long __cdecl PlanarCompressor::CreateInstance(unsigned short,unsigned short,unsigned char,int,int,int,struct IRdpImageCompressor * __ptr64 * __ptr64)` | 23 (0x17) | Exported Function | 0x0000000180057870 | 0x00057870
`public: static long __cdecl RdpEncodeBuffer::CreateInstance(class RdpEncodeBufferPool * __ptr64,unsigned long,class RdpEncodeBuffer * __ptr64 * __ptr64)` | 24 (0x18) | Exported Function | 0x0000000180045870 | 0x00045870
`public: struct _SCORE_ENTRY * __ptr64 __cdecl Evict::EvictEntry(void) __ptr64` | 28 (0x1c) | Exported Function | 0x000000018002ed10 | 0x0002ed10
`public: struct _SCORE_ENTRY * __ptr64 __cdecl Evict::GetFreeEntry(void) __ptr64` | 30 (0x1e) | Exported Function | 0x0000000180088780 | 0x00088780
`public: struct _SOCKET_ADDRESS * __ptr64 __cdecl CRDPENCONIPHelper::GetNext(void) __ptr64` | 34 (0x22) | Exported Function | 0x00000001800ae570 | 0x000ae570
`public: unsigned __int64 __cdecl PipelineClock::GetMillisecondCount64(void) __ptr64` | 32 (0x20) | Exported Function | 0x00000001800893f0 | 0x000893f0
`public: unsigned int __cdecl CRDPENCONResolver::StartEnum(void) __ptr64` | 65 (0x41) | Exported Function | 0x00000001800ac5e0 | 0x000ac5e0
`public: unsigned int __cdecl PipelineClock::GetMillisecondCount(void) __ptr64` | 33 (0x21) | Exported Function | 0x0000000180027940 | 0x00027940
`public: unsigned int __cdecl PipelineClock::GetTickCount(void) __ptr64` | 37 (0x25) | Exported Function | 0x0000000180002110 | 0x00002110
`public: virtual __cdecl CRDPCache::~CRDPCache(void) __ptr64` | 8 (0x8) | Exported Function | 0x000000018008b210 | 0x0008b210
`public: virtual long __cdecl CRDPCache::ClearCache(void) __ptr64` | 15 (0xf) | Exported Function | 0x000000018008b2f0 | 0x0008b2f0
`public: virtual long __cdecl CRDPCache::Reset(unsigned int) __ptr64` | 57 (0x39) | Exported Function | 0x000000018008b5e0 | 0x0008b5e0
`public: virtual long __cdecl CRDPCache::SearchCache(unsigned int,unsigned int,struct IUnknown * __ptr64 * __ptr64,unsigned int * __ptr64) __ptr64` | 58 (0x3a) | Exported Function | 0x000000018008b820 | 0x0008b820
`public: virtual long __cdecl CRDPCache::SetCacheEntry(unsigned int,unsigned int,struct IUnknown * __ptr64,unsigned int * __ptr64) __ptr64` | 59 (0x3b) | Exported Function | 0x000000018008b9a0 | 0x0008b9a0
`public: virtual long __cdecl CRDPENCConnectorStringSerializer::AddPortMapping(unsigned short * __ptr64,unsigned long) __ptr64` | 13 (0xd) | Exported Function | 0x00000001800ac800 | 0x000ac800
`public: virtual long __cdecl CRDPENCConnectorStringSerializer::InitializeInstance(void) __ptr64` | 42 (0x2a) | Exported Function | 0x00000001800acd40 | 0x000acd40
`RDPAPI_GetGenericCounter` | 167 (0xa7) | Exported Function | 0x00000001800251d0 | 0x000251d0
`RDPAPI_GetGlobalObject` | 168 (0xa8) | Exported Function | 0x0000000180028dd0 | 0x00028dd0
`RDPAPI_GetLongCounter` | 169 (0xa9) | Exported Function | 0x000000018009c460 | 0x0009c460
`RDPBASE_CreateInstance` | 170 (0xaa) | Exported Function | 0x00000001800376e0 | 0x000376e0
`RdpX_AtomicIncrement32` | 222 (0xde) | Exported Function | 0x0000000180035d30 | 0x00035d30
`RdpX_DateTime_GetHighResolutionTimeSinceReboot` | 223 (0xdf) | Exported Function | 0x0000000180033b80 | 0x00033b80
`RdpX_DebugBreak` | 224 (0xe0) | Exported Function | 0x00000001800455c0 | 0x000455c0
`RdpX_GetActivityIdPrefix` | 225 (0xe1) | Exported Function | 0x000000018000d980 | 0x0000d980
`RdpX_Threading_CreateCriticalSection` | 226 (0xe2) | Exported Function | 0x0000000180038200 | 0x00038200
`RgnlibBA_CreateInstance` | 227 (0xe3) | Exported Function | 0x000000018002d850 | 0x0002d850
`SaveImageToFile` | 228 (0xe4) | Exported Function | 0x000000018007e140 | 0x0007e140
`SubtractRects` | 229 (0xe5) | Exported Function | 0x000000018007e580 | 0x0007e580
`TRC_TraceBufferW` | 230 (0xe6) | Exported Function | 0x0000000180054720 | 0x00054720
`TsAddRectsToRegion` | 237 (0xed) | Exported Function | 0x000000018000c650 | 0x0000c650
`TSAlloc` | 231 (0xe7) | Exported Function | 0x000000018007d4a0 | 0x0007d4a0
`TSCreateBaseServices` | 232 (0xe8) | Exported Function | 0x0000000180074c80 | 0x00074c80
`TSCreateCoreEvents` | 233 (0xe9) | Exported Function | 0x00000001800782b0 | 0x000782b0
`TSCreatePlatform` | 234 (0xea) | Exported Function | 0x0000000180079d00 | 0x00079d00
`TsCreateRegion` | 238 (0xee) | Exported Function | 0x000000018002db90 | 0x0002db90
`TSDbgAssertThread` | 235 (0xeb) | Exported Function | 0x0000000180038000 | 0x00038000
`TsDestroyRegion` | 239 (0xef) | Exported Function | 0x0000000180032ae0 | 0x00032ae0
`TSFree` | 66 (0x42) | Exported Function | 0x00000001800351c0 | 0x000351c0
`TsGetRegionBoundingBox` | 240 (0xf0) | Exported Function | 0x0000000180035610 | 0x00035610
`TsGetRegionRectCount` | 241 (0xf1) | Exported Function | 0x00000001800278d0 | 0x000278d0
`TsGetRegionRects` | 242 (0xf2) | Exported Function | 0x000000018000bfa0 | 0x0000bfa0
`TSRNG_GenerateRandomBits` | 236 (0xec) | Exported Function | 0x000000018010b630 | 0x0010b630
`TsSetRegionFromRects` | 243 (0xf3) | Exported Function | 0x000000018002ee80 | 0x0002ee80
`UnpackServerCert` | 244 (0xf4) | Exported Function | 0x000000018010aef0 | 0x0010aef0
`unsigned long __cdecl NSRunLengthDecode(unsigned char const * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long)` | 46 (0x2e) | Exported Function | 0x0000000180056340 | 0x00056340
`UpdateSessionKey` | 245 (0xf5) | Exported Function | 0x000000018010b5a0 | 0x0010b5a0
`ValidateServerCert` | 246 (0xf6) | Exported Function | 0x000000018010afb0 | 0x0010afb0
`RdpX_AtomicDecrement32` | 221 (0xdd) | Exported Function | 0x0000000180036200 | 0x00036200
`public: long __cdecl CRDPENCConnectorStringDeserializer::XMLDeserialize(unsigned short * __ptr64) __ptr64` | 70 (0x46) | Exported Function | 0x00000001800ad000 | 0x000ad000
`RDPWSStreamConnector_CreateInstance` | 197 (0xc5) | Exported Function | 0x00000001800d4190 | 0x000d4190
`RdpTiledSurface_CreateInstance` | 219 (0xdb) | Exported Function | 0x0000000180091330 | 0x00091330
`RDPCompress` | 171 (0xab) | Exported Function | 0x0000000180051750 | 0x00051750
`RDPCompress_GetContextSize` | 173 (0xad) | Exported Function | 0x0000000180051850 | 0x00051850
`RDPCompress_InitRecvContext` | 174 (0xae) | Exported Function | 0x0000000180051880 | 0x00051880
`RDPCompress_InitSendContext` | 175 (0xaf) | Exported Function | 0x00000001800518d0 | 0x000518d0
`RDPCompressEx` | 172 (0xac) | Exported Function | 0x00000001800517b0 | 0x000517b0
`RDPDecompress` | 177 (0xb1) | Exported Function | 0x0000000180051960 | 0x00051960
`RDPDeCompress_GetContextSize` | 176 (0xb0) | Exported Function | 0x0000000180051920 | 0x00051920
`RDPENCDirectConnector_CreateInstance` | 178 (0xb2) | Exported Function | 0x00000001800b08b0 | 0x000b08b0
`RDPENCGDIHLP_FlipBitmapBits` | 179 (0xb3) | Exported Function | 0x000000018009c8b0 | 0x0009c8b0
`RDPENCGDIHLP_FlipBitmapBitsInPlace` | 180 (0xb4) | Exported Function | 0x000000018009c980 | 0x0009c980
`RDPENCGDIHLP_ValidatePointerParams` | 181 (0xb5) | Exported Function | 0x000000018009cbe0 | 0x0009cbe0
`RDPENCHLP_GetInputDesktopName` | 186 (0xba) | Exported Function | 0x000000018009cfe0 | 0x0009cfe0
`RDPENCHLP_IsGreaterThanOrEqWin8` | 187 (0xbb) | Exported Function | 0x000000018009d140 | 0x0009d140
`RDPENCHLP_IsSessionActive` | 188 (0xbc) | Exported Function | 0x000000018009d220 | 0x0009d220
`RDPENCHLP_IsSessionRemote` | 189 (0xbd) | Exported Function | 0x000000018009d380 | 0x0009d380
`RDPENCHLP_TraceWindowInfo` | 190 (0xbe) | Exported Function | 0x000000018009d490 | 0x0009d490
`RDPENCHLPREG_ReadValueDWORD` | 182 (0xb6) | Exported Function | 0x0000000180028ca0 | 0x00028ca0
`RDPENCHLPWS_GetIPFromAddr` | 184 (0xb8) | Exported Function | 0x000000018001c790 | 0x0001c790
`RDPENCHLPWS_GetPortFromAddr` | 185 (0xb9) | Exported Function | 0x00000001800351e0 | 0x000351e0
`RDPENCHLPWSErr2Hr` | 183 (0xb7) | Exported Function | 0x000000018009ce80 | 0x0009ce80
`RDPENCORE_AddGlobalObject` | 191 (0xbf) | Exported Function | 0x000000018009e0a0 | 0x0009e0a0
`RdpIntersectRect` | 218 (0xda) | Exported Function | 0x000000018007e4c0 | 0x0007e4c0
`RDPServerStackDiagnostics_LogCheckpoint` | 192 (0xc0) | Exported Function | 0x00000001800d4ce0 | 0x000d4ce0
`RDPServerStackDiagnostics_LogDisconnect` | 193 (0xc1) | Exported Function | 0x00000001800d4d60 | 0x000d4d60
`RDPServerStackDiagnostics_LogFailure` | 194 (0xc2) | Exported Function | 0x0000000180037ba0 | 0x00037ba0
`RDPServerStackDiagnostics_Register` | 195 (0xc3) | Exported Function | 0x00000001800d4e10 | 0x000d4e10
`RDPServerStackDiagnostics_Unregister` | 196 (0xc4) | Exported Function | 0x00000001800d4e50 | 0x000d4e50
`RdpUnionRect` | 220 (0xdc) | Exported Function | 0x000000018007e520 | 0x0007e520
`public: long __cdecl CRDPENCConnectorStringDeserializer::GetPortMapping(unsigned long,unsigned short * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 36 (0x24) | Exported Function | 0x00000001800acb70 | 0x000acb70
`public: int __cdecl CRDPENCONResolver::GetNext(struct sockaddr * __ptr64 * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 35 (0x23) | Exported Function | 0x00000001800ab370 | 0x000ab370
`public: int __cdecl CRDPENCONIPHelper::StartEnum(void) __ptr64` | 64 (0x40) | Exported Function | 0x00000001800ae810 | 0x000ae810
`long __cdecl AlphaCompressor__CreateInstance(struct IRdpImageCompressor * __ptr64 * __ptr64)` | 14 (0xe) | Exported Function | 0x0000000180054930 | 0x00054930
`long __cdecl CompressRdp8__CreateInstance(class IRdpPipeCompress * __ptr64 * __ptr64,unsigned int)` | 17 (0x11) | Exported Function | 0x0000000180071cd0 | 0x00071cd0
`long __cdecl DecompressRdp8__CreateInstance(class IRdpPipeDecompress * __ptr64 * __ptr64)` | 26 (0x1a) | Exported Function | 0x00000001800724c0 | 0x000724c0
`long __cdecl HintCoconet__CreateInstance(class IRdpPipeCompressHintProvider * __ptr64 * __ptr64)` | 39 (0x27) | Exported Function | 0x0000000180072870 | 0x00072870
`long __cdecl RdpGfxProtocolServerEncoder_CreateInstance(class IRdpEncoderIO * __ptr64,class IRdpPipeProtocolEncoderEx * __ptr64 * __ptr64)` | 54 (0x36) | Exported Function | 0x000000018008ad30 | 0x0008ad30
`MakeSessionKeys` | 103 (0x67) | Exported Function | 0x000000018010b3d0 | 0x0010b3d0
`MemCopyAligned_SSE` | 104 (0x68) | Exported Function | 0x000000018000da70 | 0x0000da70
`MemEqual` | 105 (0x69) | Exported Function | 0x0000000180001e10 | 0x00001e10
`MemMoveReverseAligned_SSE` | 106 (0x6a) | Exported Function | 0x000000018007e710 | 0x0007e710
`PAL_System_AtomicCompareAndExchange` | 107 (0x6b) | Exported Function | 0x0000000180028160 | 0x00028160
`PAL_System_AtomicCompareAndExchangePointer` | 108 (0x6c) | Exported Function | 0x0000000180084090 | 0x00084090
`PAL_System_AtomicDecrement` | 109 (0x6d) | Exported Function | 0x000000018001f2d0 | 0x0001f2d0
`PAL_System_AtomicExchange` | 110 (0x6e) | Exported Function | 0x00000001800840b0 | 0x000840b0
`PAL_System_AtomicExchangeAdd` | 111 (0x6f) | Exported Function | 0x00000001800840d0 | 0x000840d0
`PAL_System_AtomicExchangePointer` | 112 (0x70) | Exported Function | 0x00000001800840f0 | 0x000840f0
`PAL_System_AtomicIncrement` | 113 (0x71) | Exported Function | 0x00000001800098c0 | 0x000098c0
`PAL_System_Beep` | 114 (0x72) | Exported Function | 0x00000001800d7e50 | 0x000d7e50
`PAL_System_CondAlloc` | 115 (0x73) | Exported Function | 0x0000000180084110 | 0x00084110
`PAL_System_CondReset` | 116 (0x74) | Exported Function | 0x0000000180084170 | 0x00084170
`PAL_System_CondSignal` | 117 (0x75) | Exported Function | 0x00000001800071c0 | 0x000071c0
`PAL_System_CondWait` | 118 (0x76) | Exported Function | 0x00000001800286c0 | 0x000286c0
`PAL_System_ConvertToAndFromWideChar` | 119 (0x77) | Exported Function | 0x00000001800d9570 | 0x000d9570
`PAL_System_CreateGuid` | 120 (0x78) | Exported Function | 0x00000001800d95e0 | 0x000d95e0
`PAL_System_CredProtect` | 121 (0x79) | Exported Function | 0x00000001800d7e70 | 0x000d7e70
`PAL_System_CredUnprotect` | 122 (0x7a) | Exported Function | 0x00000001800d7e80 | 0x000d7e80
`PAL_System_CritSecEnter` | 123 (0x7b) | Exported Function | 0x0000000180006320 | 0x00006320
`PAL_System_CritSecInit` | 124 (0x7c) | Exported Function | 0x00000001800090a0 | 0x000090a0
`int __cdecl PAL_System_Win32_IsRunningInAppContainer(void)` | 47 (0x2f) | Exported Function | 0x00000001800d5ba0 | 0x000d5ba0
`PAL_System_CritSecIsLockedByCurrentThread` | 125 (0x7d) | Exported Function | 0x0000000180036120 | 0x00036120
`GridBA_CreateInstance` | 102 (0x66) | Exported Function | 0x00000001800809d0 | 0x000809d0
`ExpandRectForSSE` | 100 (0x64) | Exported Function | 0x00000001800329e0 | 0x000329e0
`ApplySobelFilterOnLum` | 76 (0x4c) | Exported Function | 0x000000018007db20 | 0x0007db20
`BitmapCombinePlanes` | 77 (0x4d) | Exported Function | 0x0000000180059410 | 0x00059410
`CAPAPI_AddCapSet` | 78 (0x4e) | Exported Function | 0x000000018006d370 | 0x0006d370
`CAPAPI_GetCapSet` | 79 (0x4f) | Exported Function | 0x000000018006d390 | 0x0006d390
`CAPAPI_InitializeCombinedCaps` | 80 (0x50) | Exported Function | 0x0000000180037e10 | 0x00037e10
`CAPAPI_MergeCombinedCaps` | 81 (0x51) | Exported Function | 0x000000018006d3e0 | 0x0006d3e0
`CRDPBitmapRecorder_CreateInstance` | 82 (0x52) | Exported Function | 0x000000018008ce10 | 0x0008ce10
`CRDPCacCodec_CreateInstance` | 84 (0x54) | Exported Function | 0x000000018003a7d0 | 0x0003a7d0
`CRDPCacCodecEncoder_CreateInstance` | 83 (0x53) | Exported Function | 0x000000018003a6e0 | 0x0003a6e0
`CRDPCacVideoCodec_CreateInstance` | 86 (0x56) | Exported Function | 0x00000001800376f0 | 0x000376f0
`CRDPCacVideoCodecForHardwareClient_CreateInstance` | 85 (0x55) | Exported Function | 0x000000018003a8f0 | 0x0003a8f0
`CRDPCaps_CreateInstance` | 87 (0x57) | Exported Function | 0x00000001800381c0 | 0x000381c0
`CRDPENCGfxEncoder_CreateInstance` | 88 (0x58) | Exported Function | 0x000000018008f270 | 0x0008f270
`CRdpFIPSEncryption_CreateInstance` | 91 (0x5b) | Exported Function | 0x00000001800829b0 | 0x000829b0
`CRDPNsCodec_CreateInstance` | 89 (0x59) | Exported Function | 0x0000000180057040 | 0x00057040
`CRDPPlanarCompressor_CreateInstance` | 90 (0x5a) | Exported Function | 0x00000001800583b0 | 0x000583b0
`DecryptData` | 92 (0x5c) | Exported Function | 0x000000018010abe0 | 0x0010abe0
`DecryptDataEx` | 93 (0x5d) | Exported Function | 0x000000018010aca0 | 0x0010aca0
`DrawBox` | 94 (0x5e) | Exported Function | 0x000000018007df40 | 0x0007df40
`DrawHLine` | 95 (0x5f) | Exported Function | 0x000000018007dfd0 | 0x0007dfd0
`DrawIconToPixelMap` | 96 (0x60) | Exported Function | 0x000000018001c8b0 | 0x0001c8b0
`DrawVLine` | 97 (0x61) | Exported Function | 0x000000018007e080 | 0x0007e080
`EncryptClientRandom` | 98 (0x62) | Exported Function | 0x000000018010ade0 | 0x0010ade0
`EncryptData` | 99 (0x63) | Exported Function | 0x000000018010ad70 | 0x0010ad70
`enum _XResult32 __cdecl XObjectId_RdpXHttpSession_CreateObject(struct RdpXInterface * __ptr64,unsigned int,enum _XInterfaceId32,void * __ptr64 * __ptr64)` | 72 (0x48) | Exported Function | 0x000000018004fef0 | 0x0004fef0
`enum _XResult32 __cdecl XObjectId_RdpXInterfaceUriComponents_CreateObject(struct RdpXInterface * __ptr64,unsigned int,enum _XInterfaceId32,void * __ptr64 * __ptr64)` | 73 (0x49) | Exported Function | 0x000000018004ffa0 | 0x0004ffa0
`enum _XResult32 __cdecl XObjectId_RdpXSecFilterServer_CreateObject(struct RdpXInterface * __ptr64,unsigned int,enum _XInterfaceId32,void * __ptr64 * __ptr64)` | 74 (0x4a) | Exported Function | 0x0000000180021c20 | 0x00021c20
`GetSupportedSSELevel_SSE` | 101 (0x65) | Exported Function | 0x000000018001f210 | 0x0001f210
`void __cdecl RdpPerfLoggerStaticInitialize(void)` | 55 (0x37) | Exported Function | 0x00000001800d46a0 | 0x000d46a0
`PAL_System_CritSecLeave` | 126 (0x7e) | Exported Function | 0x00000001800062e0 | 0x000062e0
`PAL_System_CritSecTryEnter` | 128 (0x80) | Exported Function | 0x00000001800841a0 | 0x000841a0
`PAL_System_TimeGetTimeZoneInformation` | 160 (0xa0) | Exported Function | 0x00000001800d9680 | 0x000d9680
`PAL_System_TimerCancel` | 161 (0xa1) | Exported Function | 0x00000001800d8d20 | 0x000d8d20
`PAL_System_TimerDelete` | 162 (0xa2) | Exported Function | 0x00000001800d8f20 | 0x000d8f20
`PAL_System_TimerInit` | 163 (0xa3) | Exported Function | 0x00000001800d8fa0 | 0x000d8fa0
`PAL_System_TimerIsSet` | 164 (0xa4) | Exported Function | 0x00000001800d9110 | 0x000d9110
`PAL_System_TimerSet` | 165 (0xa5) | Exported Function | 0x00000001800d9180 | 0x000d9180
`PAL_System_WideCharToUnicode16` | 166 (0xa6) | Exported Function | 0x00000001800d97e0 | 0x000d97e0
`private: void __cdecl SSECBCHash2::ProcessAlignedData_AVX(unsigned int const * __ptr64,unsigned int,unsigned int,unsigned int) __ptr64` | 49 (0x31) | Exported Function | 0x000000018000adc0 | 0x0000adc0
`private: void __cdecl SSECBCHash2::ProcessAlignedData_SSE2(unsigned int const * __ptr64,unsigned int,unsigned int,unsigned int) __ptr64` | 50 (0x32) | Exported Function | 0x000000018007d4b0 | 0x0007d4b0
`private: void __cdecl SSECBCHash2::ProcessAlignedData_SSE41(unsigned int const * __ptr64,unsigned int,unsigned int,unsigned int) __ptr64` | 51 (0x33) | Exported Function | 0x000000018007d7f0 | 0x0007d7f0
`private: void __cdecl SSECBCHash2::ProcessUnalignedData_REG(unsigned int const * __ptr64,unsigned int,unsigned int,unsigned int) __ptr64` | 52 (0x34) | Exported Function | 0x00000001800246c0 | 0x000246c0
`private: void __cdecl SSECBCHash2::UpdateKeys(void)const __ptr64` | 69 (0x45) | Exported Function | 0x0000000180023ee0 | 0x00023ee0
`protected: __cdecl RdpGfxProtocolBaseDecoder::RdpGfxProtocolBaseDecoder(void) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180045cf0 | 0x00045cf0
`protected: __cdecl RdpGfxProtocolBaseDecoder::~RdpGfxProtocolBaseDecoder(void) __ptr64` | 11 (0xb) | Exported Function | 0x0000000180045d20 | 0x00045d20
`protected: void __cdecl RdpGfxProtocolBaseDecoder::SetDecodeBuffer(unsigned char const * __ptr64,unsigned int) __ptr64` | 61 (0x3d) | Exported Function | 0x0000000180036c60 | 0x00036c60
`public: __cdecl CRDPCache::CRDPCache(void) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180036540 | 0x00036540
`public: __cdecl CRDPENCONResolver::CRDPENCONResolver(void) __ptr64` | 2 (0x2) | Exported Function | 0x00000001800aa4b0 | 0x000aa4b0
`public: __cdecl CRDPENCONResolver::~CRDPENCONResolver(void) __ptr64` | 9 (0x9) | Exported Function | 0x00000001800aa5e0 | 0x000aa5e0
`public: __cdecl Evict::~Evict(void) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180088450 | 0x00088450
`public: __cdecl NSCodecDecompressor::NSCodecDecompressor(bool) __ptr64` | 3 (0x3) | Exported Function | 0x00000001800551b0 | 0x000551b0
`public: __cdecl PipeETWEvents::PipeETWEvents(void) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180084e50 | 0x00084e50
`public: __cdecl RdpEncodeBuffer::RdpEncodeBuffer(class ITSObjectPool * __ptr64) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180045730 | 0x00045730
`public: __cdecl SSECBCHash2::SSECBCHash2(void) __ptr64` | 7 (0x7) | Exported Function | 0x0000000180029300 | 0x00029300
`public: __int64 __cdecl PipelineClock::GetTimeHNS(void) __ptr64` | 38 (0x26) | Exported Function | 0x00000001800340b0 | 0x000340b0
`public: bool __cdecl NSCodecCompressor::Compress(class PixelMap const & __ptr64,bool,unsigned char * __ptr64,unsigned int,unsigned int & __ptr64) __ptr64` | 16 (0x10) | Exported Function | 0x0000000180011520 | 0x00011520
`public: bool __cdecl NSCodecDecompressor::Decompress(unsigned char const * __ptr64,unsigned int,class PixelMap & __ptr64) __ptr64` | 25 (0x19) | Exported Function | 0x0000000180055d00 | 0x00055d00
`public: bool __cdecl PipelineClock::IsTestMode(void) __ptr64` | 45 (0x2d) | Exported Function | 0x00000001800381e0 | 0x000381e0
`PAL_System_TimeGetTickCount64` | 159 (0x9f) | Exported Function | 0x00000001800845c0 | 0x000845c0
`PAL_System_CritSecTerminate` | 127 (0x7f) | Exported Function | 0x0000000180028240 | 0x00028240
`PAL_System_TimeGetTickCount` | 158 (0x9e) | Exported Function | 0x0000000180034020 | 0x00034020
`PAL_System_TimeGetCurrent` | 156 (0x9c) | Exported Function | 0x0000000180084550 | 0x00084550
`PAL_System_CryptDecryptLegacy` | 129 (0x81) | Exported Function | 0x00000001800d7e90 | 0x000d7e90
`PAL_System_CryptEncrypt` | 130 (0x82) | Exported Function | 0x00000001800d7eb0 | 0x000d7eb0
`PAL_System_CryptFree` | 131 (0x83) | Exported Function | 0x00000001800d7ed0 | 0x000d7ed0
`PAL_System_CryptZeroMemory` | 132 (0x84) | Exported Function | 0x00000001800d9600 | 0x000d9600
`PAL_System_DebugBreak` | 133 (0x85) | Exported Function | 0x0000000180081c90 | 0x00081c90
`PAL_System_DebugOutput` | 134 (0x86) | Exported Function | 0x0000000180081cb0 | 0x00081cb0
`PAL_System_GetComputerName` | 135 (0x87) | Exported Function | 0x00000001800d7f50 | 0x000d7f50
`PAL_System_GetFIPSAlgorithmEnabled` | 136 (0x88) | Exported Function | 0x0000000180081cf0 | 0x00081cf0
`PAL_System_GetLocalSessionId` | 137 (0x89) | Exported Function | 0x00000001800d7f80 | 0x000d7f80
`PAL_System_GetModuleFilename` | 138 (0x8a) | Exported Function | 0x0000000180081e70 | 0x00081e70
`PAL_System_GetNetworkStatus` | 139 (0x8b) | Exported Function | 0x00000001800d8040 | 0x000d8040
`PAL_System_GetNumberOfProcessors` | 140 (0x8c) | Exported Function | 0x0000000180033890 | 0x00033890
`PAL_System_GetWindowsProductId` | 141 (0x8d) | Exported Function | 0x00000001800d8520 | 0x000d8520
`PAL_System_HandleFree` | 142 (0x8e) | Exported Function | 0x0000000180028280 | 0x00028280
`PAL_System_MemAlloc` | 143 (0x8f) | Exported Function | 0x00000001800311c0 | 0x000311c0
`PAL_System_MemFree` | 144 (0x90) | Exported Function | 0x00000001800351c0 | 0x000351c0
`PAL_System_NetworkMonitorInit` | 145 (0x91) | Exported Function | 0x00000001800d85d0 | 0x000d85d0
`PAL_System_NetworkMonitorNotification` | 146 (0x92) | Exported Function | 0x00000001800d9630 | 0x000d9630
`PAL_System_NetworkMonitorTerminate` | 147 (0x93) | Exported Function | 0x00000001800d89f0 | 0x000d89f0
`PAL_System_SecureZeroMemory` | 148 (0x94) | Exported Function | 0x00000001800d9660 | 0x000d9660
`PAL_System_SemaphoreAcquire` | 149 (0x95) | Exported Function | 0x0000000180084450 | 0x00084450
`PAL_System_SemaphoreAlloc` | 150 (0x96) | Exported Function | 0x0000000180031740 | 0x00031740
`PAL_System_SemaphoreRelease` | 151 (0x97) | Exported Function | 0x0000000180023b60 | 0x00023b60
`PAL_System_SingleCondWait` | 152 (0x98) | Exported Function | 0x0000000180084500 | 0x00084500
`PAL_System_Sleep` | 153 (0x99) | Exported Function | 0x0000000180081fc0 | 0x00081fc0
`PAL_System_SwitchToThread` | 154 (0x9a) | Exported Function | 0x0000000180081fe0 | 0x00081fe0
`PAL_System_ThreadGetId` | 155 (0x9b) | Exported Function | 0x000000018002ecd0 | 0x0002ecd0
`PAL_System_TimeGetDynamicTimeZoneInformation` | 157 (0x9d) | Exported Function | 0x00000001800d8ab0 | 0x000d8ab0
`void __cdecl RdpPerfLoggerStaticTerminate(void)` | 56 (0x38) | Exported Function | 0x00000001800d46c0 | 0x000d46c0


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


