---
title: rdpserverbase.dll | Rdp Server OneCore Base Services
excerpt: What is rdpserverbase.dll?
---

# rdpserverbase.dll 

* File Path: `C:\Windows\system32\rdpserverbase.dll`
* Description: Rdp Server OneCore Base Services

## Hashes

Type | Hash
-- | --
MD5 | `9C9458D940A037E29C003DDFFCC72A3C`
SHA1 | `FB98B49F09A73D94AB23B9F2B95E4DC5B7F2D621`
SHA256 | `1BF71F7E503378779F755FD480D4E338A186FC77F16BB7FC16A12566155BBB40`
SHA384 | `01FDF04A129FC223DCB6B162A9A2AE6EC33F9394B79CE0DEA1B7AF946C801005BD403CAAB7FB8FC14EC7064803F5C173`
SHA512 | `BD3643362A27BACB0606B23FCEB16D2ABE96730A03A9DD8C00BD19A49F83F0265B7045F60D6ADAC10E57E20474A4EFAEAF1BABB1DCFD6ECABA9D610446DFE844`
SSDEEP | `49152:UmY1barRZaroZebWmrAqVvAh5tdNw375tknSV9QWGfO04r1UC6ou9l8nTqiTY/hl:U51baZaMoWmrAqVv85tdNw375tknSV9G`
IMP | `58B3B48206570C67EEE1FD796484475C`
PESHA1 | `09B250DEE58F448834FB69308291F2D6EF1054EE`
PE256 | `9F0C5599C49F5EC61DC4DED142FFC901B94CBC1D4B5524E04B155AE603647FE2`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CCompressedUpdateContext_CreateInstance` | 18 (0x12) | Exported Function | 0x00000001800c0d80 | 0x000c0d80
`void __cdecl RDPGraphicsTraceLogging::LogRDPGraphicsVOBRHint(unsigned int,unsigned __int64,unsigned int,unsigned int)` | 13 (0xd) | Exported Function | 0x0000000180100d80 | 0x00100d80
`void __cdecl RDPGraphicsTraceLogging::LogRDPGraphicsSubsampleFailure(long,unsigned int)` | 12 (0xc) | Exported Function | 0x0000000180100b70 | 0x00100b70
`void __cdecl RDPGraphicsTraceLogging::LogRDPGraphicsSubsampleAdapter(unsigned short const * __ptr64,unsigned int,unsigned int)` | 11 (0xb) | Exported Function | 0x0000000180100a90 | 0x00100a90
`void __cdecl RDPGraphicsTraceLogging::LogRDPGraphicsFirstNonBlackFramePostLogon(unsigned int)` | 10 (0xa) | Exported Function | 0x00000001801002f0 | 0x001002f0
`void __cdecl RDPGraphicsTraceLogging::LogRDPGraphicsFirstNonBlackFrame(unsigned __int64)` | 9 (0x9) | Exported Function | 0x0000000180100210 | 0x00100210
`void __cdecl RDPGraphicsTraceLogging::LogRDPGraphicsError(struct _GUID,unsigned int,unsigned int,long)` | 8 (0x8) | Exported Function | 0x000000018003b590 | 0x0003b590
`RDPSERVERBASE_CreateInstance` | 23 (0x17) | Exported Function | 0x0000000180030480 | 0x00030480
`RDPEncryptionTraceLogging_Unregister` | 22 (0x16) | Exported Function | 0x00000001800ffbd0 | 0x000ffbd0
`RDPEncryptionTraceLogging_Register` | 21 (0x15) | Exported Function | 0x00000001800ffbb0 | 0x000ffbb0
`void __cdecl RDPGraphicsTraceLogging::RDPGraphicsTraceLogging_Unregister(void)` | 15 (0xf) | Exported Function | 0x0000000180100e90 | 0x00100e90
`public: long __cdecl Tiler::Initialize(struct RdpRect const * __ptr64,struct RdpRect const * __ptr64) __ptr64` | 7 (0x7) | Exported Function | 0x0000000180051f60 | 0x00051f60
`public: long __cdecl Tiler::GetTileFirst(struct RdpRect const * __ptr64,struct RdpRect * __ptr64) __ptr64` | 5 (0x5) | Exported Function | 0x000000018001ee80 | 0x0001ee80
`public: long __cdecl RdpSurface::GetGraphicsSourceContext(struct IRdpGFXSourceUpdateContext * __ptr64 * __ptr64) __ptr64` | 4 (0x4) | Exported Function | 0x000000018006bbf0 | 0x0006bbf0
`public: long __cdecl RdpSurface::GetEncodingPixelMap(class PixelMap * __ptr64 * __ptr64) __ptr64` | 1 (0x1) | Exported Function | 0x00000001800073d0 | 0x000073d0
`long __cdecl RDPServerStackQOE_Register(void)` | 16 (0x10) | Exported Function | 0x00000001800bd3e0 | 0x000bd3e0
`long __cdecl RDPGraphicsTraceLogging::RDPGraphicsTraceLogging_Register(void)` | 14 (0xe) | Exported Function | 0x0000000180100e70 | 0x00100e70
`long __cdecl GetGfxPipeSettingUINT(unsigned short * __ptr64,unsigned int,unsigned int * __ptr64)` | 3 (0x3) | Exported Function | 0x00000001800772f0 | 0x000772f0
`long __cdecl GetGfxPipeSettingBOOL(unsigned short * __ptr64,int,int * __ptr64)` | 2 (0x2) | Exported Function | 0x0000000180077240 | 0x00077240
`CUpdateDataAccumulator_CreateInstance` | 20 (0x14) | Exported Function | 0x00000001800c0e60 | 0x000c0e60
`CUpdateContext_CreateInstance` | 19 (0x13) | Exported Function | 0x00000001800c0df0 | 0x000c0df0
`public: long __cdecl Tiler::GetTileNext(struct RdpRect * __ptr64) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180051f00 | 0x00051f00
`void __cdecl RDPServerStackQOE_Unregister(void)` | 17 (0x11) | Exported Function | 0x00000001800bd420 | 0x000bd420


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rdpserverbase.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.84 (WinBuild.160101.0800)
* Product Version: 10.0.19041.84
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/1bf71f7e503378779f755fd480d4e338a186fc77f16bb7fc16a12566155bbb40/detection/





MIT License. Copyright (c) 2020 Strontic.


