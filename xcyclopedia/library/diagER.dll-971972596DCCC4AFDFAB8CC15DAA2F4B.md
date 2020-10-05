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

Function Name | Ordinal | Type
-- | -- | --
`public: virtual __cdecl CWfpER::~CWfpER(void) __ptr64` | 8 | Exported Function
`public: virtual __cdecl CDwWinER::~CDwWinER(void) __ptr64` | 7 | Exported Function
`public: virtual __cdecl IDiagER::~IDiagER(void) __ptr64` | 9 | Exported Function
`public: virtual unsigned long __cdecl CDwWinER::AddFiles(unsigned short const * __ptr64 * __ptr64,unsigned int) __ptr64` | 21 | Exported Function
`public: virtual unsigned long __cdecl CDwWinER::AddBucketingParameters(unsigned short const * __ptr64 * __ptr64,unsigned int) __ptr64` | 18 | Exported Function
`public: static void __cdecl CDiagERFactory::ReleaseInstance(void)` | 35 | Exported Function
`public: class CWfpER & __ptr64 __cdecl CWfpER::operator=(class CWfpER const & __ptr64) __ptr64` | 13 | Exported Function
`public: class CDwWinER & __ptr64 __cdecl CDwWinER::operator=(class CDwWinER const & __ptr64) __ptr64` | 12 | Exported Function
`public: class IDiagER & __ptr64 __cdecl IDiagER::operator=(class IDiagER const & __ptr64) __ptr64` | 14 | Exported Function
`public: static unsigned long __cdecl CDiagERFactory::CreateInstance(unsigned short const * __ptr64,enum _DIAG_REPORT_TYPE,int,class IDiagER * __ptr64 * __ptr64)` | 24 | Exported Function
`public: static class IDiagER * __ptr64 __cdecl CDiagERFactory::GetErrorReporter(void)` | 32 | Exported Function
`public: virtual unsigned long __cdecl CWfpER::Submit(unsigned long) __ptr64` | 40 | Exported Function
`public: virtual unsigned long __cdecl CWfpER::SetHeader(unsigned short const * __ptr64) __ptr64` | 37 | Exported Function
`public: virtual unsigned long __cdecl IDiagER::AddBucketingParameters(unsigned short const * __ptr64 * __ptr64,unsigned int) __ptr64` | 20 | Exported Function
`public: virtual unsigned long __cdecl IDiagER::SetHeader(unsigned short const * __ptr64) __ptr64` | 38 | Exported Function
`public: virtual unsigned long __cdecl IDiagER::AddFiles(unsigned short const * __ptr64 * __ptr64,unsigned int) __ptr64` | 23 | Exported Function
`public: virtual unsigned long __cdecl CWfpER::Initialize(void) __ptr64` | 34 | Exported Function
`public: virtual unsigned long __cdecl CDwWinER::SetHeader(unsigned short const * __ptr64) __ptr64` | 36 | Exported Function
`public: virtual unsigned long __cdecl CDwWinER::Initialize(void) __ptr64` | 33 | Exported Function
`public: virtual unsigned long __cdecl CDwWinER::Submit(unsigned long) __ptr64` | 39 | Exported Function
`public: virtual unsigned long __cdecl CWfpER::AddFiles(unsigned short const * __ptr64 * __ptr64,unsigned int) __ptr64` | 22 | Exported Function
`public: virtual unsigned long __cdecl CWfpER::AddBucketingParameters(unsigned short const * __ptr64 * __ptr64,unsigned int) __ptr64` | 19 | Exported Function
`DiagERSubmit` | 29 | Exported Function
`DiagERSetHeader` | 28 | Exported Function
`DiagERSubmitEx` | 30 | Exported Function
`g_Kernel32` | 41 | Exported Function
`DiagERTerminate` | 31 | Exported Function
`DiagERInitialize` | 27 | Exported Function
`const CWfpER::``vftable'` | 16 | Exported Function
`const CDwWinER::``vftable'` | 15 | Exported Function
`const IDiagER::``vftable'` | 17 | Exported Function
`DiagERAddFiles` | 26 | Exported Function
`DiagERAddBucketingParameters` | 25 | Exported Function
`public: __cdecl IDiagER::IDiagER(class IDiagER const & __ptr64) __ptr64` | 5 | Exported Function
`public: __cdecl CWfpER::CWfpER(unsigned short const * __ptr64,enum _DIAG_REPORT_TYPE,int) __ptr64` | 4 | Exported Function
`public: __cdecl IDiagER::IDiagER(unsigned short const * __ptr64,int) __ptr64` | 6 | Exported Function
`public: class CDiagERFactory & __ptr64 __cdecl CDiagERFactory::operator=(class CDiagERFactory const & __ptr64) __ptr64` | 11 | Exported Function
`public: class CDiagERFactory & __ptr64 __cdecl CDiagERFactory::operator=(class CDiagERFactory && __ptr64) __ptr64` | 10 | Exported Function
`public: __cdecl CWfpER::CWfpER(class CWfpER const & __ptr64) __ptr64` | 3 | Exported Function
`g_WerApi` | 43 | Exported Function
`g_Shell32` | 42 | Exported Function
`private: static class IDiagER * __ptr64 __ptr64 CDiagERFactory::m_diagER` | 44 | Exported Function
`public: __cdecl CDwWinER::CDwWinER(unsigned short const * __ptr64,int) __ptr64` | 2 | Exported Function
`public: __cdecl CDwWinER::CDwWinER(class CDwWinER const & __ptr64) __ptr64` | 1 | Exported Function


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


