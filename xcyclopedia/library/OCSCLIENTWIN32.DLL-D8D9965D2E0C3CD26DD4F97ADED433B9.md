---
title: OCSCLIENTWIN32.DLL | Microsoft Office component
excerpt: What is OCSCLIENTWIN32.DLL?
---

# OCSCLIENTWIN32.DLL 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\OCSCLIENTWIN32.DLL`
* Description: Microsoft Office component

## Hashes

Type | Hash
-- | --
MD5 | `D8D9965D2E0C3CD26DD4F97ADED433B9`
SHA1 | `BF3B447FF3D2F5559613FDEBEE5BEBBDE8439262`
SHA256 | `A79EA65E0F769CB085390E9F4FFB9F38B5EF90D94482D57CC2944917EAF621C5`
SHA384 | `D9B6830764DA32B6EB840B0B3EC9AF824876AB1DEE3CE4D1DEB47CCAD31584B4019CA774F11BD1A25FA8FC6434954046`
SHA512 | `2693302CCB017405051747AB7C136A6192BCC4F90262688649B0D91E1841673A93F9FDAD0B33C01B0E0F05CD664097D423E93C55FD6A121F50D27693F67A7AAD`
SSDEEP | `12288:dzsGRmufdi6/66d91/xQx5dNcdidUnsU34Qp:doodi6/R5xQxh1dUF3p`
IMP | `25BA7A32B517E95DE354240A51342386`
PESHA1 | `B9D163F6E51DEF3781D0DFCB77DECBA18069B02B`
PE256 | `6F12D0DFB4B9CAF4D7371195D11CF6A89CA945F005B5368DC930E09DE18CE7B0`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: bool __thiscall Bondi::JsonElementReader::ReadNext(void)` | 25 | Exported Function
`public: bool __thiscall Bondi::JsonReader::ReadNext(char const * *)` | 26 | Exported Function
`public: bool __thiscall MocsiSyncEndpoint::MocsiError::operator==(class MocsiSyncEndpoint::MocsiError const &)const ` | 4 | Exported Function
`public: __thiscall Bondi::JsonReader::~JsonReader(void)` | 3 | Exported Function
`private: void __thiscall Bondi::JsonWriter::WriteRawString(char const *,unsigned int)` | 30 | Exported Function
`private: void __thiscall MocsiSyncEndpoint::MocsiError::Report(void)` | 28 | Exported Function
`public: __thiscall Bondi::JsonReader::JsonReader(class std::basic_string_view<char,struct std::char_traits<char> >)` | 1 | Exported Function
`public: class Bondi::BlobPtr __thiscall Bondi::ContextBase::AllocBlob(class array_view<unsigned char>)` | 5 | Exported Function
`public: unsigned char * __thiscall Bondi::ContextBase::AllocBlock(unsigned int)` | 6 | Exported Function
`public: virtual __thiscall Bondi::Exception::~Exception(void)` | 2 | Exported Function
`void __stdcall MocsiSyncEndpoint::SetMocsiSyncEndpointMock(class Mso::Functor<class Mso::TCntPtr<struct SyncController::IDirectSyncEndpoint> __stdcall(struct MocsiSyncEndpoint::IMocsiEndpointLocator &,struct DocumentRevisionGraph::IRevisionGraph &,struct MocsiSyncEndpoint::KnownRevisionReferences,struct MocsiSyncEndpoint::IMocsiSyncEndpointUser2 &,class Mso::Functor<bool __stdcall(struct MocsiSyncEndpoint::MocsiEndpointHealth const &)> const &,class Mso::FunctorRef<class Mso::TCntPtr<struct SyncController::IDirectSyncEndpoint> __stdcall(class Mso::Async::IDispatchQueue &,struct MocsiSyncEndpoint::IMocsiEndpointLocator &,struct DocumentRevisionGraph::IRevisionGraph &,struct MocsiSyncEndpoint::KnownRevisionReferences,struct MocsiSyncEndpoint::IMocsiSyncEndpointUser2 &,class Mso::Functor<bool __stdcall(struct MocsiSyncEndpoint::MocsiEndpointHealth const &)> const &)> const &)>)` | 29 | Exported Function
`public: class Bondi::StringPtr __thiscall Bondi::ContextBase::AllocString(class std::basic_string_view<char,struct std::char_traits<char> >)` | 8 | Exported Function
`public: class Bondi::JsonReader __thiscall Bondi::JsonReader::ReadArray(void)` | 24 | Exported Function
`public: class Bondi::JsonReader __thiscall Bondi::JsonReader::ReadObject(void)` | 27 | Exported Function
`public: class Bondi::StringPtr __thiscall Bondi::ContextBase::AllocString(class Bondi::StringPtr)` | 7 | Exported Function
`class Mso::optional<struct MocsiSyncEndpoint::ParsedHostKnownVersionInfo> __stdcall MocsiSyncEndpoint::ParseHostKnownVersionInfo(class std::vector<unsigned char,class std::allocator<unsigned char> > const &)` | 22 | Exported Function
`class Mso::optional<struct MocsiSyncEndpoint::RemoteRevIdInfo> __stdcall MocsiSyncEndpoint::ParseRemoteRevId(class std::vector<unsigned char,class std::allocator<unsigned char> > const &)` | 23 | Exported Function
`class Mso::TCntPtr<struct Bondi::IServiceEndpointManager> __stdcall Bondi::CreateServiceEndpointManager(struct Bondi::IMessageListener &)` | 14 | Exported Function
`class array_view<unsigned char> __stdcall Bondi::DecodeBlob(class Bondi::ContextBase &,class std::basic_string_view<char,struct std::char_traits<char> >)` | 16 | Exported Function
`bool __stdcall MocsiSyncEndpoint::HasLocalChanges(struct DocumentRevisionGraph::IRevisionGraph &,struct MocsiSyncEndpoint::KnownRevisionReferences)` | 18 | Exported Function
`bool __stdcall MocsiSyncEndpoint::IsLeftRevisionSameOrParent(struct DocumentRevisionGraph::IRevisionGraph &,struct DocumentRevisionGraph::IRevision &,struct DocumentRevisionGraph::IRevision &)` | 20 | Exported Function
`bool __stdcall MocsiSyncEndpoint::IsMocsiGraphDirty(struct DocumentRevisionGraph::IRevisionGraph &,struct MocsiSyncEndpoint::KnownRevisionReferences)` | 21 | Exported Function
`class Mso::TCntPtr<struct HttpClient::IHttpClient> __stdcall HttpClient::CreateHttpClient(class std::shared_ptr<class Mso::Lockable<class Mso::AlwaysInit<class Mso::CritSecBase>,class Mso::ZeroOrOneThreaded> > const &,class Mso::Http::IRequestSettings *,class Mso::Functor<class Mso::TCntPtr<class Mso::Http::IRequest> __stdcall(void)>)` | 11 | Exported Function
`enum MocsiSyncEndpoint::CompareRemoteRevisionResult __stdcall MocsiSyncEndpoint::CompareRemoteRevision(struct DocumentRevisionGraph::IRevisionGraph &,struct DocumentRevisionGraph::IRevision &,struct DocumentRevisionGraph::IRevision &)` | 9 | Exported Function
`enum MocsiSyncEndpoint::CompareRemoteRevisionResult __stdcall MocsiSyncEndpoint::CompareRemoteRevisions(class Mso::optional<class std::vector<unsigned char,class std::allocator<unsigned char> > > const &,class Mso::optional<class std::vector<unsigned char,class std::allocator<unsigned char> > > const &)` | 10 | Exported Function
`private: class std::vector<char,class std::allocator<char> > __thiscall Bondi::ServiceClientBase::InvokeMethod(char const *,char const *,class std::basic_string_view<char,struct std::char_traits<char> >)` | 19 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __stdcall Bondi::EncodeBlob(class array_view<unsigned char>)` | 17 | Exported Function
`class Mso::TCntPtr<struct MocsiSyncEndpoint::IMocsiSyncEndpointUser2> __stdcall MocsiSyncEndpoint::CreateStateSyncEndpointUser(struct DocumentRevisionGraph::IRevisionGraph &)` | 15 | Exported Function
`class Mso::TCntPtr<struct SyncController::IDirectSyncEndpoint> __stdcall MocsiSyncEndpoint::CreateMocsiSyncEndpoint2(struct MocsiSyncEndpoint::IMocsiEndpointLocator &,struct DocumentRevisionGraph::IRevisionGraph &,struct MocsiSyncEndpoint::KnownRevisionReferences,struct MocsiSyncEndpoint::IMocsiSyncEndpointUser2 &,class Mso::Functor<void __stdcall(class Mso::Async::IDispatchQueue &,class std::shared_ptr<class Mso::Lockable<class Mso::AlwaysInit<class Mso::CritSecBase>,class Mso::ZeroOrOneThreaded> > const &,struct MocsiSyncEndpoint::IMocsiFrameChannel * *)> const &,struct MocsiSyncEndpoint::IMocsiStateMachineMonitor *,class Mso::Functor<enum MocsiSyncEndpoint::CompareHostKnowledgeResult __stdcall(class array_view<unsigned char> const &,struct MocsiSyncEndpoint::ParsedHostKnownVersionInfo const &)> const &,class Mso::Functor<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __stdcall(struct MocsiSyncEndpoint::ParsedHostKnownVersionInfo const &)> const &,char ` | 12 | Exported Function
`class Mso::TCntPtr<struct SyncController::ISignal> __stdcall MocsiSyncEndpoint::CreateRevisionGraphPushPullSignal(struct DocumentRevisionGraph::IRevisionGraph &,unsigned __int64)` | 13 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: OcsClientWin32.dll
* Product Name: Microsoft Office
* Company Name: Microsoft Corporation
* File Version: 16.0.12527.20122
* Product Version: 16.0.12527.20122
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/a79ea65e0f769cb085390e9f4ffb9f38b5ef90d94482d57cc2944917eaf621c5/detection/




MIT License. Copyright (c) 2020 Strontic.


