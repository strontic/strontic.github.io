---
title: AUDIOSEARCHMAIN.DLL | Microsoft OneNote Audio Search
excerpt: What is AUDIOSEARCHMAIN.DLL?
---

# AUDIOSEARCHMAIN.DLL 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\AUDIOSEARCHMAIN.DLL`
* Description: Microsoft OneNote Audio Search

## Hashes

Type | Hash
-- | --
MD5 | `1B221420ED83F69ED292E24B9B0ED3FB`
SHA1 | `EAF0E05AA941236DFE6822E50FC1B58E54895AEA`
SHA256 | `0676EF96A7927BCB5C11BC8467670FBA7168FB14F9E1096377042C4E3AC94977`
SHA384 | `DCE6D56120F0618AF6B515B3E1D943837ED73379C0BD588BE04D51C278947669A4B9B9C2E0D5F424C2364CB7212D3D1F`
SHA512 | `A6AFC4704B7C2971413ED6B3396ED2EA96FD53510B94C29155E9885E4233D6792416C73613CEB6EB1545ADBD4EBDFB82D8790EB28DA5D38912B2E7111D223C97`
SSDEEP | `24576:5NR/e0HoUdfWPPjE02zrlFpZN1m+TcfXDp:5NRWOEPNcL1m+iDp`
IMP | `ED3ACAE56F91587C8E81C1719F3F3F51`
PESHA1 | `760027ECB145F8535E6670DEE459D1C9690DB484`
PE256 | `EA93891A45EB8DF86DAF92D2C6BE14C2E44C5DAEC33901991312F26256DF2DB4`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: virtual void __thiscall MSRA::AudioSearchAPI::CIndexingSession::registerAudioFile(wchar_t const * const,wchar_t const *,wchar_t const *)` | 45 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CIndexingSession::getStatistics(int &,float &)` | 42 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CIndexingSession::getIndexedAudioFile(wchar_t const *,wchar_t const *,wchar_t *,int)const ` | 38 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CIndexingSession::remove(wchar_t const *)` | 46 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CRetrievalSession::cancel(void)` | 31 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CQuery::set(wchar_t const *)` | 48 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CQuery::set(wchar_t const * *,int,enum MSRA::AudioSearchAPI::QUERY_OPERATOR)` | 47 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CIndexingSession::cancel(void)` | 30 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CIndexingSession::buildIndexedAudioFile(wchar_t const *,wchar_t const *)` | 29 | Exported Function
`public: virtual struct MSRA::AudioSearchAPI::LIMITS __thiscall MSRA::AudioSearchAPI::CRetrievalSession::setLimits(struct MSRA::AudioSearchAPI::LIMITS const &)` | 50 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CIndexingSession::clearIndex(void)` | 32 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CIndexingSession::getDocumentSet(struct MSRA::AudioSearchAPI::DOCUMENT_IN_INDEX const * &,int &)` | 37 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CIndexingSession::freeDocumentSet(struct MSRA::AudioSearchAPI::DOCUMENT_IN_INDEX const *)` | 35 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CIndexingSession::deleteIndex(void)` | 33 | Exported Function
`struct MSRA::AudioSearchAPI::IRetrievalSession * __stdcall MSRA::AudioSearchAPI::CreateRetrievalSessionImpl(class MSRA::AudioSearchAPI::CIndexManager const &,struct MSRA::AudioSearchAPI::IRetrievalSessionNotify &)` | 22 | Exported Function
`struct MSRA::AudioSearchAPI::IQuery * __stdcall MSRA::AudioSearchAPI::CreateQueryImpl(class MSRA::AudioSearchAPI::CIndexManager const &)` | 21 | Exported Function
`struct MSRA::AudioSearchAPI::IIndexingSession * __stdcall MSRA::AudioSearchAPI::CreateIndexingSessionImpl(class MSRA::AudioSearchAPI::CIndexManager &,struct MSRA::AudioSearchAPI::IIndexingSessionNotify &)` | 20 | Exported Function
`void __stdcall MSRA::AudioSearchAPI::CopyQuery(struct MSRA::AudioSearchAPI::IQuery const &,struct MSRA::AudioSearchAPI::IQuery &)` | 18 | Exported Function
`void __stdcall MSRA::AudioSearchAPI::ReleaseRetrievalSessionImpl(struct MSRA::AudioSearchAPI::IRetrievalSession *)` | 26 | Exported Function
`void __stdcall MSRA::AudioSearchAPI::ReleaseQueryImpl(struct MSRA::AudioSearchAPI::IQuery *)` | 25 | Exported Function
`void __stdcall MSRA::AudioSearchAPI::ReleaseIndexingSessionImpl(struct MSRA::AudioSearchAPI::IIndexingSession *)` | 24 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CRetrievalSession::setQuery(class MSRA::AudioSearchAPI::CQuery const &)` | 51 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CRetrievalSession::goAndWait(void)` | 44 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CRetrievalSession::go(void)` | 43 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CRetrievalSession::setScope(struct MSRA::AudioSearchAPI::SCOPE_DOCUMENT const *,int,wchar_t const * const *,int)` | 54 | Exported Function
`public: void __thiscall MSRA::AudioSearchAPI::CRetrievalSessionImpl::FILELISTENTRY::setError(struct MSRA::AudioSearchAPI::EXCEPTION &)` | 49 | Exported Function
`public: virtual wchar_t const * __thiscall MSRA::AudioSearchAPI::CQuery::get(int)const ` | 36 | Exported Function
`public: virtual void __thiscall MSRA::AudioSearchAPI::CRetrievalSessionImpl::setQuery(class MSRA::AudioSearchAPI::CQuery const &)` | 52 | Exported Function
`public: __thiscall MSRA::AudioSearchAPI::CQuery::~CQuery(void)` | 12 | Exported Function
`public: __thiscall MSRA::AudioSearchAPI::CQuery::CQuery(class MSRA::AudioSearchAPI::CIndexManager const &)` | 5 | Exported Function
`public: __thiscall MSRA::AudioSearchAPI::CIndexManagerImpl::CIndexManagerImpl(struct MSRA::AudioSearchAPI::CIndexManager::CONFIG const &)` | 2 | Exported Function
`public: __thiscall MSRA::AudioSearchAPI::CQueryImpl::CQueryImpl(class MSRA::AudioSearchAPI::CIndexManager const &)` | 6 | Exported Function
`public: __thiscall MSRA::AudioSearchAPI::CRetrievalSessionImpl::CRetrievalSessionImpl(class MSRA::AudioSearchAPI::CIndexManager const &,struct MSRA::AudioSearchAPI::IRetrievalSessionNotify &)` | 8 | Exported Function
`public: __thiscall MSRA::AudioSearchAPI::CRetrievalSession::~CRetrievalSession(void)` | 13 | Exported Function
`public: __thiscall MSRA::AudioSearchAPI::CRetrievalSession::CRetrievalSession(class MSRA::AudioSearchAPI::CIndexManager const &,struct MSRA::AudioSearchAPI::IRetrievalSessionNotify &)` | 7 | Exported Function
`public: __thiscall MSRA::AudioSearchAPI::CIndexingSession::CIndexingSession(class MSRA::AudioSearchAPI::CIndexManager &,struct MSRA::AudioSearchAPI::IIndexingSessionNotify &)` | 3 | Exported Function
`class MSRA::AudioSearchAPI::CIndexManagerImpl * __stdcall MSRA::AudioSearchAPI::CreateIndexManagerImpl(struct MSRA::AudioSearchAPI::CIndexManager::CONFIG const &)` | 19 | Exported Function
`bool __stdcall MSRA::AudioSearchAPI::IsQueryEqual(struct MSRA::AudioSearchAPI::IQuery const &,struct MSRA::AudioSearchAPI::IQuery const &)` | 23 | Exported Function
`public: __thiscall MSRA::AudioSearchAPI::CIndexingSession::~CIndexingSession(void)` | 11 | Exported Function
`public: __thiscall MSRA::AudioSearchAPI::CIndexManager::~CIndexManager(void)` | 10 | Exported Function
`public: __thiscall MSRA::AudioSearchAPI::CIndexManager::CIndexManager(struct MSRA::AudioSearchAPI::CIndexManager::CONFIG const &)` | 1 | Exported Function
`public: __thiscall MSRA::AudioSearchAPI::CIndexingSessionImpl::CIndexingSessionImpl(class MSRA::AudioSearchAPI::CIndexManager &,struct MSRA::AudioSearchAPI::IIndexingSessionNotify &)` | 4 | Exported Function
`public: virtual enum MSRA::AudioSearchAPI::QUERY_OPERATOR __thiscall MSRA::AudioSearchAPI::CQuery::getOperator(void)const ` | 40 | Exported Function
`public: virtual bool __thiscall MSRA::AudioSearchAPI::CRetrievalSession::wait(int)` | 56 | Exported Function
`public: virtual bool __thiscall MSRA::AudioSearchAPI::CIndexingSession::wait(int)` | 55 | Exported Function
`public: virtual enum MSRA::AudioSearchAPI::RESOLUTION __thiscall MSRA::AudioSearchAPI::CRetrievalSession::setResolution(enum MSRA::AudioSearchAPI::RESOLUTION)` | 53 | Exported Function
`public: virtual int __thiscall MSRA::AudioSearchAPI::CQuery::getPhonetic(int,wchar_t *,int)const ` | 41 | Exported Function
`public: virtual int __thiscall MSRA::AudioSearchAPI::CQuery::getNumTerms(void)const ` | 39 | Exported Function
`public: virtual int __thiscall MSRA::AudioSearchAPI::CIndexingSession::documentExists(wchar_t const * const)` | 34 | Exported Function
`public: bool __thiscall MSRA::AudioSearchAPI::CQueryImpl::operator==(struct MSRA::AudioSearchAPI::IQuery const &)const ` | 17 | Exported Function
`public: bool __thiscall MSRA::AudioSearchAPI::CQuery::operator==(class MSRA::AudioSearchAPI::CQuery const &)const ` | 16 | Exported Function
`public: __thiscall MSRA::AudioSearchAPI::EXCEPTION::EXCEPTION(char const *,long,wchar_t const *,char const *)` | 9 | Exported Function
`public: class MSRA::AudioSearchAPI::CQuery & __thiscall MSRA::AudioSearchAPI::CQuery::operator=(class MSRA::AudioSearchAPI::CQuery const &)` | 14 | Exported Function
`public: virtual bool __thiscall MSRA::AudioSearchAPI::CIndexingSession::addIndexedAudioFile(wchar_t const * const,wchar_t const *,wchar_t const *)` | 28 | Exported Function
`public: virtual bool __thiscall MSRA::AudioSearchAPI::CIndexingSession::addAudioFile(wchar_t const * const,wchar_t const *,wchar_t const *)` | 27 | Exported Function
`public: struct MSRA::AudioSearchAPI::IQuery & __thiscall MSRA::AudioSearchAPI::CQueryImpl::operator=(struct MSRA::AudioSearchAPI::IQuery const &)` | 15 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002CE7C9ACE7D905ED2B70000000002CE`
* Thumbprint: `B10607FB914700B40F794610850C1DE0A21566C1`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AudioSearchMain.dll
* Product Name: Microsoft OneNote
* Company Name: Microsoft Corporation
* File Version: 16.0.12325.20144
* Product Version: 16.0.12325.20144
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/0676ef96a7927bcb5c11bc8467670fba7168fb14f9e1096377042c4e3ac94977/detection/




MIT License. Copyright (c) 2020 Strontic.


