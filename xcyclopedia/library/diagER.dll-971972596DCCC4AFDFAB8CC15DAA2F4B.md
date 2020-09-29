---
title: diagER.dll | Diagnostic ER Module
excerpt: What is diagER.dll?
---

# diagER.dll 

* File Path: `C:\Windows\system32\oobe\diagER.dll`
* Description: Diagnostic ER Module

## Hashes

Type | Hash
-- | --
MD5 | `971972596DCCC4AFDFAB8CC15DAA2F4B`
SHA1 | `C27EC45506E7FBF9B92ADDBE54232343F7D23239`
SHA256 | `1A4508D2EB062B744AE7CDF0B24D998FAE93756E0BBF1286765A75B5E6930439`
SHA384 | `5813E3DB936A9140483DF5F921C82C18F737C2C8FD8C0A9B2E3E87B6B628B2F45255FD1771ED12545344ED128FB745DF`
SHA512 | `4C5796B0B4738946BBC029F8D4C4C0A2AC5ACCE7D33DBB3679633E9C6846401CF61E44BB7D4FFEC055D37D66414DB47656A87B5B39153E3D81455A8BE9598B05`
SSDEEP | `768:IBqkR284bz5Su33E3nbox26S8tAnGg4rYuV/Xxt7upIyTr6wD1PFkM:3z5Su33E3nbh6ynG5EuV/Xxt7CjPFV`
IMP | `A6DFAB2F841183F78D7BA325D5888C10`
PESHA1 | `2501ACC05AF2330884B8D7AAB39B0616D25B04EB`
PE256 | `568909558878C29CB936B177C30A540EC355F325EFD58467B00CA5E0CD96F353`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`const CDwWinER::``vftable'` | 15 (0xf) | Exported Function | 0x0000000180007198 | 0x00007198
`public: class IDiagER & __ptr64 __cdecl IDiagER::operator=(class IDiagER const & __ptr64) __ptr64` | 14 (0xe) | Exported Function | 0x00000001800010b0 | 0x000010b0
`public: static class IDiagER * __ptr64 __cdecl CDiagERFactory::GetErrorReporter(void)` | 32 (0x20) | Exported Function | 0x0000000180004a60 | 0x00004a60
`public: static unsigned long __cdecl CDiagERFactory::CreateInstance(unsigned short const * __ptr64,enum _DIAG_REPORT_TYPE,int,class IDiagER * __ptr64 * __ptr64)` | 24 (0x18) | Exported Function | 0x0000000180004a70 | 0x00004a70
`public: static void __cdecl CDiagERFactory::ReleaseInstance(void)` | 35 (0x23) | Exported Function | 0x0000000180004c60 | 0x00004c60
`public: virtual __cdecl CDwWinER::~CDwWinER(void) __ptr64` | 7 (0x7) | Exported Function | 0x00000001800029f0 | 0x000029f0
`public: virtual __cdecl CWfpER::~CWfpER(void) __ptr64` | 8 (0x8) | Exported Function | 0x0000000180001a20 | 0x00001a20
`public: virtual __cdecl IDiagER::~IDiagER(void) __ptr64` | 9 (0x9) | Exported Function | 0x00000001800047b0 | 0x000047b0
`public: virtual unsigned long __cdecl CDwWinER::AddBucketingParameters(unsigned short const * __ptr64 * __ptr64,unsigned int) __ptr64` | 18 (0x12) | Exported Function | 0x0000000180002b90 | 0x00002b90
`public: class CWfpER & __ptr64 __cdecl CWfpER::operator=(class CWfpER const & __ptr64) __ptr64` | 13 (0xd) | Exported Function | 0x0000000180001150 | 0x00001150
`public: virtual unsigned long __cdecl CDwWinER::AddFiles(unsigned short const * __ptr64 * __ptr64,unsigned int) __ptr64` | 21 (0x15) | Exported Function | 0x0000000180002e80 | 0x00002e80
`public: virtual unsigned long __cdecl CDwWinER::SetHeader(unsigned short const * __ptr64) __ptr64` | 36 (0x24) | Exported Function | 0x0000000180002a30 | 0x00002a30
`public: virtual unsigned long __cdecl CDwWinER::Submit(unsigned long) __ptr64` | 39 (0x27) | Exported Function | 0x0000000180003160 | 0x00003160
`public: virtual unsigned long __cdecl CWfpER::AddBucketingParameters(unsigned short const * __ptr64 * __ptr64,unsigned int) __ptr64` | 19 (0x13) | Exported Function | 0x0000000180001db0 | 0x00001db0
`public: virtual unsigned long __cdecl CWfpER::AddFiles(unsigned short const * __ptr64 * __ptr64,unsigned int) __ptr64` | 22 (0x16) | Exported Function | 0x0000000180001f60 | 0x00001f60
`public: virtual unsigned long __cdecl CWfpER::Initialize(void) __ptr64` | 34 (0x22) | Exported Function | 0x00000001800016d0 | 0x000016d0
`public: virtual unsigned long __cdecl CWfpER::SetHeader(unsigned short const * __ptr64) __ptr64` | 37 (0x25) | Exported Function | 0x0000000180001c40 | 0x00001c40
`public: virtual unsigned long __cdecl CWfpER::Submit(unsigned long) __ptr64` | 40 (0x28) | Exported Function | 0x00000001800021b0 | 0x000021b0
`public: virtual unsigned long __cdecl IDiagER::AddBucketingParameters(unsigned short const * __ptr64 * __ptr64,unsigned int) __ptr64` | 20 (0x14) | Exported Function | 0x0000000180004370 | 0x00004370
`public: virtual unsigned long __cdecl CDwWinER::Initialize(void) __ptr64` | 33 (0x21) | Exported Function | 0x00000001800025d0 | 0x000025d0
`public: class CDwWinER & __ptr64 __cdecl CDwWinER::operator=(class CDwWinER const & __ptr64) __ptr64` | 12 (0xc) | Exported Function | 0x00000001800013b0 | 0x000013b0
`public: class CDiagERFactory & __ptr64 __cdecl CDiagERFactory::operator=(class CDiagERFactory const & __ptr64) __ptr64` | 11 (0xb) | Exported Function | 0x00000001800014f0 | 0x000014f0
`public: class CDiagERFactory & __ptr64 __cdecl CDiagERFactory::operator=(class CDiagERFactory && __ptr64) __ptr64` | 10 (0xa) | Exported Function | 0x00000001800014f0 | 0x000014f0
`const CWfpER::``vftable'` | 16 (0x10) | Exported Function | 0x0000000180007168 | 0x00007168
`const IDiagER::``vftable'` | 17 (0x11) | Exported Function | 0x00000001800071c8 | 0x000071c8
`DiagERAddBucketingParameters` | 25 (0x19) | Exported Function | 0x0000000180004ea0 | 0x00004ea0
`DiagERAddFiles` | 26 (0x1a) | Exported Function | 0x0000000180005010 | 0x00005010
`DiagERInitialize` | 27 (0x1b) | Exported Function | 0x0000000180004ca0 | 0x00004ca0
`DiagERSetHeader` | 28 (0x1c) | Exported Function | 0x0000000180004dc0 | 0x00004dc0
`DiagERSubmit` | 29 (0x1d) | Exported Function | 0x0000000180005100 | 0x00005100
`DiagERSubmitEx` | 30 (0x1e) | Exported Function | 0x00000001800051b0 | 0x000051b0
`DiagERTerminate` | 31 (0x1f) | Exported Function | 0x0000000180005280 | 0x00005280
`g_Kernel32` | 41 (0x29) | Exported Function | 0x000000018000b010 | 0x0000b010
`g_Shell32` | 42 (0x2a) | Exported Function | 0x000000018000b008 | 0x0000b008
`g_WerApi` | 43 (0x2b) | Exported Function | 0x000000018000b000 | 0x0000b000
`private: static class IDiagER * __ptr64 __ptr64 CDiagERFactory::m_diagER` | 44 (0x2c) | Exported Function | 0x000000018000b608 | 0x0000b608
`public: __cdecl CDwWinER::CDwWinER(class CDwWinER const & __ptr64) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180001220 | 0x00001220
`public: __cdecl CDwWinER::CDwWinER(unsigned short const * __ptr64,int) __ptr64` | 2 (0x2) | Exported Function | 0x00000001800024f0 | 0x000024f0
`public: __cdecl CWfpER::CWfpER(class CWfpER const & __ptr64) __ptr64` | 3 (0x3) | Exported Function | 0x00000001800010f0 | 0x000010f0
`public: __cdecl CWfpER::CWfpER(unsigned short const * __ptr64,enum _DIAG_REPORT_TYPE,int) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180001600 | 0x00001600
`public: __cdecl IDiagER::IDiagER(class IDiagER const & __ptr64) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180001060 | 0x00001060
`public: __cdecl IDiagER::IDiagER(unsigned short const * __ptr64,int) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180004180 | 0x00004180
`public: virtual unsigned long __cdecl IDiagER::AddFiles(unsigned short const * __ptr64 * __ptr64,unsigned int) __ptr64` | 23 (0x17) | Exported Function | 0x0000000180004540 | 0x00004540
`public: virtual unsigned long __cdecl IDiagER::SetHeader(unsigned short const * __ptr64) __ptr64` | 38 (0x26) | Exported Function | 0x00000001800042a0 | 0x000042a0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DIAGER.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.450 (WinBuild.160101.0800)
* Product Version: 10.0.19041.450
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/1a4508d2eb062b744ae7cdf0b24d998fae93756e0bbf1286765a75b5e6930439/detection/





MIT License. Copyright (c) 2020 Strontic.


