---
title: rgb9rast.dll | 
excerpt: What is rgb9rast.dll?
---

# rgb9rast.dll 

* File Path: `C:\Windows\system32\rgb9rast.dll`

## Hashes

Type | Hash
-- | --
MD5 | `5C1227594207775ABD0FC654E913FAE1`
SHA1 | `3AF0D6B681E9426D2E95E5B75EF4468EC36EA5FA`
SHA256 | `3B45CAD4A0048596DB1AE3C958341F7C8688609F5CA34BE6C11DE589C00364C3`
SHA384 | `DCE8B8B3A8B6B54CF2DA3AE5AC159D6E2311DEC6A4C12D771B93B49EB851035141FA6790FC12529A8CF6697CE014B18B`
SHA512 | `EBB9B2F06D7F662F32856B110433C4EE90F94BD9E24DEFDA076A2AD5AF4A32F01AAB0A602EA945709B82BDDBC6143E33CE0357CB2111E2F294C0957A5014622C`
SSDEEP | `3072:XBRSUBLwRwxQNP7IjUwtn8MncNDUA05xGaSqz0IE2NJIOKxIGRK:XBfwztancOao0WNI`
IMP | `81482ECCE19350DFA33FD8825A05E1CF`
PESHA1 | `155878832167B5FCA76E0136A0EF26415E6AFCCD`
PE256 | `CA9A37C6CB4F186F6EBC80AC8736530132789B8D036970ACC30F83DA115F0F28`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`D3D9GetSWInfo` | 30 (0x1e) | Exported Function | 0x0000000180001630 | 0x00001630
`public: void __cdecl PrimProcessor::SetCtx(struct tagD3DI_RASTCTX * __ptr64) __ptr64` | 24 (0x18) | Exported Function | 0x0000000180007bd0 | 0x00007bd0
`public: void __cdecl PrimProcessor::FreeSpans(unsigned int) __ptr64` | 13 (0xd) | Exported Function | 0x0000000180007ca0 | 0x00007ca0
`public: void __cdecl PrimProcessor::ClrFlags(unsigned int) __ptr64` | 8 (0x8) | Exported Function | 0x0000000180001610 | 0x00001610
`public: void __cdecl PrimProcessor::BeginPrimSet(enum _D3DPRIMITIVETYPE,enum _RAST_VERTEX_TYPE) __ptr64` | 7 (0x7) | Exported Function | 0x0000000180007cc0 | 0x00007cc0
`public: void __cdecl PrimProcessor::Begin(void) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180007b60 | 0x00007b60
`public: unsigned int __cdecl PrimProcessor::GetFlags(void) __ptr64` | 14 (0xe) | Exported Function | 0x00000001800015f0 | 0x000015f0
`public: long __cdecl PrimProcessor::Tri(struct _D3DTLVERTEX * __ptr64,struct _D3DTLVERTEX * __ptr64,struct _D3DTLVERTEX * __ptr64) __ptr64` | 28 (0x1c) | Exported Function | 0x0000000180009fb0 | 0x00009fb0
`public: long __cdecl PrimProcessor::Point(struct _D3DTLVERTEX * __ptr64,struct _D3DTLVERTEX * __ptr64) __ptr64` | 21 (0x15) | Exported Function | 0x00000001800082f0 | 0x000082f0
`public: long __cdecl PrimProcessor::Line(struct _D3DTLVERTEX * __ptr64,struct _D3DTLVERTEX * __ptr64,struct _D3DTLVERTEX * __ptr64) __ptr64` | 16 (0x10) | Exported Function | 0x0000000180008700 | 0x00008700
`public: long __cdecl PrimProcessor::Initialize(void) __ptr64` | 15 (0xf) | Exported Function | 0x0000000180007850 | 0x00007850
`public: long __cdecl PrimProcessor::End(void) __ptr64` | 9 (0x9) | Exported Function | 0x0000000180007b90 | 0x00007b90
`public: long __cdecl PrimProcessor::AllocSpans(unsigned int * __ptr64,struct tagD3DI_RASTSPAN * __ptr64 * __ptr64) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180007be0 | 0x00007be0
`public: class PrimProcessor & __ptr64 __cdecl PrimProcessor::operator=(class PrimProcessor const & __ptr64) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180001540 | 0x00001540
`public: __cdecl PrimProcessor::~PrimProcessor(void) __ptr64` | 2 (0x2) | Exported Function | 0x00000001800078b0 | 0x000078b0
`public: __cdecl PrimProcessor::PrimProcessor(void) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180007800 | 0x00007800
`private: void __cdecl PrimProcessor::SetTriFunctions(void) __ptr64` | 26 (0x1a) | Exported Function | 0x0000000180009f10 | 0x00009f10
`private: void __cdecl PrimProcessor::ResetBuffer(void) __ptr64` | 23 (0x17) | Exported Function | 0x00000001800078e0 | 0x000078e0
`private: void __cdecl PrimProcessor::NormalizeTriRHW(struct _D3DTLVERTEX * __ptr64,struct _D3DTLVERTEX * __ptr64,struct _D3DTLVERTEX * __ptr64) __ptr64` | 20 (0x14) | Exported Function | 0x0000000180009660 | 0x00009660
`private: void __cdecl PrimProcessor::NormalizePointRHW(struct _D3DTLVERTEX * __ptr64) __ptr64` | 19 (0x13) | Exported Function | 0x00000001800082b0 | 0x000082b0
`private: void __cdecl PrimProcessor::NormalizeLineRHW(struct _D3DTLVERTEX * __ptr64,struct _D3DTLVERTEX * __ptr64) __ptr64` | 18 (0x12) | Exported Function | 0x0000000180009010 | 0x00009010
`private: void __cdecl PrimProcessor::FillPointSpan(struct _D3DTLVERTEX * __ptr64,struct tagD3DI_RASTSPAN * __ptr64) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180007ff0 | 0x00007ff0
`private: long __cdecl PrimProcessor::FlushPartial(void) __ptr64` | 12 (0xc) | Exported Function | 0x0000000180007970 | 0x00007970
`private: long __cdecl PrimProcessor::Flush(void) __ptr64` | 11 (0xb) | Exported Function | 0x0000000180007900 | 0x00007900
`private: long __cdecl PrimProcessor::AppendPrim(void) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180007ae0 | 0x00007ae0
`private: int __cdecl PrimProcessor::TriSetup(struct _D3DTLVERTEX * __ptr64,struct _D3DTLVERTEX * __ptr64,struct _D3DTLVERTEX * __ptr64) __ptr64` | 29 (0x1d) | Exported Function | 0x00000001800096f0 | 0x000096f0
`private: int __cdecl PrimProcessor::PointDiamondCheck(int,int,int,int) __ptr64` | 22 (0x16) | Exported Function | 0x0000000180009060 | 0x00009060
`private: int __cdecl PrimProcessor::LineSetup(struct _D3DTLVERTEX * __ptr64,struct _D3DTLVERTEX * __ptr64) __ptr64` | 17 (0x11) | Exported Function | 0x00000001800090e0 | 0x000090e0
`public: void __cdecl PrimProcessor::SetFlags(unsigned int) __ptr64` | 25 (0x19) | Exported Function | 0x0000000180001600 | 0x00001600
`public: void __cdecl PrimProcessor::StateChanged(void) __ptr64` | 27 (0x1b) | Exported Function | 0x0000000180001620 | 0x00001620


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RGBRASTD.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/3b45cad4a0048596db1ae3c958341f7c8688609f5ca34be6c11de589c00364c3/detection/





MIT License. Copyright (c) 2020 Strontic.


