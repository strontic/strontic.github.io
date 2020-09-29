---
title: rdpserverbase.dll | Rdp Server OneCore Base Services
excerpt: What is rdpserverbase.dll?
---

# rdpserverbase.dll 

* File Path: `C:\Windows\SysWOW64\rdpserverbase.dll`
* Description: Rdp Server OneCore Base Services

## Hashes

Type | Hash
-- | --
MD5 | `9CC2EDB288EA454B1AEB7D93856CEDE4`
SHA1 | `4DE403FB3BFB7C1C33EC25BB83B5CDCE68E8D35F`
SHA256 | `8D3269C608E47489BAD96B1B278BC7C2B284C1744276DD1D418307754DE514FB`
SHA384 | `B27412BBB6357EA4D21CF882080BF67EFD4360D3063F2150A5A61AF7A46A9779FDD29FA789B3C01F287559E6D6E743D8`
SHA512 | `3B6BE43B2F00605CD2B93C654CF33DC68B9221E40BDE5FF3DD1942B79CB2BD80A0B462AC2FD3ABD0813D3C589EDBF5B82526C01A84B001287BF51826961AB1E0`
SSDEEP | `24576:1SVBxJsQZiTkpIwn83zx5DpMpAUNdsm9x613FFeo2H4IYEneNIlWar:YVKqarwnCV5UITeplWqlH`
IMP | `2BEFFA499CA91BD8001147D9688A872B`
PESHA1 | `0B068C5DD4C0786D544EBC731B753410C7243499`
PE256 | `355DEF8C17F534D4FB42E49365DDA6DB6365D33814EA93630F54C9F214A12144`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CCompressedUpdateContext_CreateInstance` | 18 (0x12) | Exported Function | 0x10103eb0 | 0x00103eb0
`void __stdcall RDPGraphicsTraceLogging::LogRDPGraphicsVOBRHint(unsigned int,unsigned __int64,unsigned int,unsigned int)` | 13 (0xd) | Exported Function | 0x1013b730 | 0x0013b730
`void __stdcall RDPGraphicsTraceLogging::LogRDPGraphicsSubsampleFailure(long,unsigned int)` | 12 (0xc) | Exported Function | 0x1013b5c0 | 0x0013b5c0
`void __stdcall RDPGraphicsTraceLogging::LogRDPGraphicsSubsampleAdapter(unsigned short const *,unsigned int,unsigned int)` | 11 (0xb) | Exported Function | 0x1013b530 | 0x0013b530
`void __stdcall RDPGraphicsTraceLogging::LogRDPGraphicsFirstNonBlackFramePostLogon(unsigned int)` | 10 (0xa) | Exported Function | 0x1013b030 | 0x0013b030
`void __stdcall RDPGraphicsTraceLogging::LogRDPGraphicsFirstNonBlackFrame(unsigned __int64)` | 9 (0x9) | Exported Function | 0x1013afa0 | 0x0013afa0
`void __stdcall RDPGraphicsTraceLogging::LogRDPGraphicsError(struct _GUID,unsigned int,unsigned int,long)` | 8 (0x8) | Exported Function | 0x1013aee0 | 0x0013aee0
`RDPSERVERBASE_CreateInstance` | 23 (0x17) | Exported Function | 0x1007aab0 | 0x0007aab0
`RDPEncryptionTraceLogging_Unregister` | 22 (0x16) | Exported Function | 0x1013aaa0 | 0x0013aaa0
`RDPEncryptionTraceLogging_Register` | 21 (0x15) | Exported Function | 0x1013aa80 | 0x0013aa80
`void __stdcall RDPGraphicsTraceLogging::RDPGraphicsTraceLogging_Unregister(void)` | 15 (0xf) | Exported Function | 0x1013b7f0 | 0x0013b7f0
`public: long __thiscall Tiler::Initialize(struct RdpRect const *,struct RdpRect const *)` | 7 (0x7) | Exported Function | 0x100a48a0 | 0x000a48a0
`public: long __thiscall Tiler::GetTileFirst(struct RdpRect const *,struct RdpRect *)` | 5 (0x5) | Exported Function | 0x100a43e0 | 0x000a43e0
`public: long __thiscall RdpSurface::GetGraphicsSourceContext(struct IRdpGFXSourceUpdateContext * *)` | 4 (0x4) | Exported Function | 0x100a1750 | 0x000a1750
`public: long __thiscall RdpSurface::GetEncodingPixelMap(class PixelMap * *)` | 1 (0x1) | Exported Function | 0x100a16e0 | 0x000a16e0
`long __stdcall RDPServerStackQOE_Register(void)` | 16 (0x10) | Exported Function | 0x10100890 | 0x00100890
`long __stdcall RDPGraphicsTraceLogging::RDPGraphicsTraceLogging_Register(void)` | 14 (0xe) | Exported Function | 0x1013b7d0 | 0x0013b7d0
`long __stdcall GetGfxPipeSettingUINT(unsigned short *,unsigned int,unsigned int *)` | 3 (0x3) | Exported Function | 0x100a4080 | 0x000a4080
`long __stdcall GetGfxPipeSettingBOOL(unsigned short *,int,int *)` | 2 (0x2) | Exported Function | 0x100a3ff0 | 0x000a3ff0
`CUpdateDataAccumulator_CreateInstance` | 20 (0x14) | Exported Function | 0x10103f70 | 0x00103f70
`CUpdateContext_CreateInstance` | 19 (0x13) | Exported Function | 0x10103f10 | 0x00103f10
`public: long __thiscall Tiler::GetTileNext(struct RdpRect *)` | 6 (0x6) | Exported Function | 0x100a45d0 | 0x000a45d0
`void __stdcall RDPServerStackQOE_Unregister(void)` | 17 (0x11) | Exported Function | 0x101008c0 | 0x001008c0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/8d3269c608e47489bad96b1b278bc7c2b284c1744276dd1d418307754de514fb/detection/





MIT License. Copyright (c) 2020 Strontic.


