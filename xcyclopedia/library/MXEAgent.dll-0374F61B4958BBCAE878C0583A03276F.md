---
title: MXEAgent.dll | MXE Agent
excerpt: What is MXEAgent.dll?
---

# MXEAgent.dll 

* File Path: `C:\Windows\system32\migwiz\MXEAgent.dll`
* Description: MXE Agent

## Hashes

Type | Hash
-- | --
MD5 | `0374F61B4958BBCAE878C0583A03276F`
SHA1 | `56EE61F69A60C44A0514F8200283F9E5B4475056`
SHA256 | `A070C3355BCEA053A66EB593F614A6A2993927595E73DDEBD9EACDC73B1879CA`
SHA384 | `4BAE906B708427A22259DA04A3A820DB8F437548F5F19A532E1CF8B8756B2815B35422A2C5F36D56A93A92C211033803`
SHA512 | `C45B81FB1FDBDB7466B2BC48BE59CEA86928BD948753602E1245A18DF1C7D0D0836B035DAE3359555B02F12115BAD83EFCFC5B77DC1F13F400A6C11C5474FB81`
SSDEEP | `3072:HjL9T8zujhN48954mrws5JCx/mCTpc5EKZ5:Hn9T8zuha8vrwstCTpcOy`
IMP | `7A160D69C317511B6BFFF695463A804A`
PESHA1 | `A15C703E51F3A9D7FDFA8CB852489155B7D701BD`
PE256 | `1653AA88DAF72E2D8AE0BCA50DCE483802B0B6B43B0C13A3D5BB18CD62FA95AD`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`const Mig::CMXEAgent::``vbtable'` | 9 (0x9) | Exported Function | 0x00000001800334f8 | 0x000334f8
`public: virtual void __cdecl Mig::CMXEAgent::Init(class Mig::CPlatform * __ptr64,class UnBCL::String * __ptr64,class UnBCL::ArrayList<class UnBCL::String * __ptr64> * __ptr64) __ptr64` | 18 (0x12) | Exported Function | 0x0000000180001a80 | 0x00001a80
`public: virtual void __cdecl Mig::CMXEAgent::Init(class Mig::CPlatform * __ptr64,class UnBCL::String * __ptr64) __ptr64` | 17 (0x11) | Exported Function | 0x0000000180001e20 | 0x00001e20
`public: virtual void __cdecl Mig::CMXEAgent::Done(int) __ptr64` | 16 (0x10) | Exported Function | 0x00000001800025b0 | 0x000025b0
`public: virtual void __cdecl Mig::CMXEAgent::AdjustRules(class Mig::CMigUnit * __ptr64,class Mig::CMigUnit * __ptr64) __ptr64` | 14 (0xe) | Exported Function | 0x0000000180003080 | 0x00003080
`public: virtual void __cdecl Mig::CMXEAgent::AddGatherInfo(class Mig::CMigUnit * __ptr64,struct ICancelable * __ptr64) __ptr64` | 12 (0xc) | Exported Function | 0x0000000180002bf0 | 0x00002bf0
`public: virtual void __cdecl Mig::CMXEAgent::AddApplyInfo(class Mig::CMigUnit * __ptr64) __ptr64` | 11 (0xb) | Exported Function | 0x0000000180002f30 | 0x00002f30
`public: virtual class Mig::CMigUnitList * __ptr64 __cdecl Mig::CMXEAgent::Detect(class Mig::CUserContext * __ptr64,struct ICancelable * __ptr64) __ptr64` | 15 (0xf) | Exported Function | 0x0000000180002610 | 0x00002610
`public: virtual __cdecl Mig::CMXEAgent::~CMXEAgent(void) __ptr64` | 4 (0x4) | Exported Function | 0x00000001800016f0 | 0x000016f0
`public: class Mig::CMXEAgent & __ptr64 __cdecl Mig::CMXEAgent::operator=(class Mig::CMXEAgent const & __ptr64) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180001820 | 0x00001820
`public: class Mig::CMXEAgent & __ptr64 __cdecl Mig::CMXEAgent::operator=(class Mig::CMXEAgent && __ptr64) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180001820 | 0x00001820
`public: __cdecl Mig::CMXEAgent::CMXEAgent(class UnBCL::String * __ptr64) __ptr64` | 3 (0x3) | Exported Function | 0x00000001800019b0 | 0x000019b0
`public: __cdecl Mig::CMXEAgent::CMXEAgent(class Mig::CMXEAgent const & __ptr64) __ptr64` | 2 (0x2) | Exported Function | 0x0000000180001700 | 0x00001700
`public: __cdecl Mig::CMXEAgent::CMXEAgent(class Mig::CMXEAgent && __ptr64) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180001790 | 0x00001790
`protected: void __cdecl Mig::CMXEAgent::AddXmlFile(class UnBCL::String * __ptr64) __ptr64` | 13 (0xd) | Exported Function | 0x0000000180003200 | 0x00003200
`LoadAgent` | 20 (0x14) | Exported Function | 0x0000000180001930 | 0x00001930
`const Mig::CMXEAgent::``vftable'{for ``Mig::CMXEAgent'}` | 7 (0x7) | Exported Function | 0x0000000180026be8 | 0x00026be8
`const Mig::CMXEAgent::``vftable'{for ``Mig::CAgent'}` | 8 (0x8) | Exported Function | 0x0000000180025d80 | 0x00025d80
`public: virtual void __cdecl Mig::CMXEAgent::InitApply(class Mig::CPlatform * __ptr64,class Mig::CPlatform * __ptr64,class UnBCL::String * __ptr64) __ptr64` | 19 (0x13) | Exported Function | 0x0000000180002cf0 | 0x00002cf0
`public: void __cdecl Mig::CMXEAgent::``vbase destructor'(void) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180001910 | 0x00001910


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MXEAgent.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/a070c3355bcea053a66eb593f614a6a2993927595e73ddebd9eacdc73b1879ca/detection/





MIT License. Copyright (c) 2020 Strontic.


