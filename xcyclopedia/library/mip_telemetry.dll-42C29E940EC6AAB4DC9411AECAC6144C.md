---
title: mip_telemetry.dll | MIP SDK
excerpt: What is mip_telemetry.dll?
---

# mip_telemetry.dll 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\mip_telemetry.dll`
* Description: MIP SDK

## Hashes

Type | Hash
-- | --
MD5 | `42C29E940EC6AAB4DC9411AECAC6144C`
SHA1 | `633FBA4D9D223C8BC37AF0451E3464F536CF1B9F`
SHA256 | `F03BE04C4ABF1BBAB5BE58273F3EDAF307C0426F425F0521A6AC92F04E5E5DE2`
SHA384 | `0AA341BBE27E7DE1A67DFC463CBDA5812DCC3EC44EB58F36CEDBF04D5AAF34C89B6D9B67282137CA8FBE10856EA2BA96`
SHA512 | `E2402D69B87F98F7C3C5B6E379EB4AEF78DFE4B4305837B328AEDA85AC59EB4977296D4EAC0F1ABB78149D39BCB46A56C48BA51610A5DD0D414AA7050AF896E0`
SSDEEP | `1536:DeuBOWgdSjunFKezbl05mz8GCZhkzOyh9YhRblmf9EbODq:Deu4WaAunn3l0ceqOyXEpmf9EbOD`
IMP | `86D715A39AE774EEE2D52E5AC48E7495`
PESHA1 | `358C704D7C6D675B417C83CCB735B0CE87229FC2`
PE256 | `5F6A0C7EC0D1123DB5F5C85A062E9A14B1A7196DC6E00EF9EBD7BA535F3D4407`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: enum mip::telemetry::Event::PiiKind __thiscall mip::telemetry::Event::EventProperty<__int64>::GetPiiKind(void)const ` | 46 | Exported Function
`public: enum mip::telemetry::Event::PiiKind __thiscall mip::telemetry::Event::EventProperty<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >::GetPiiKind(void)const ` | 45 | Exported Function
`public: class std::shared_ptr<class mip::telemetry::Event> __thiscall mip::telemetry::AutoEvent::Detach(void)` | 15 | Exported Function
`public: double const & __thiscall mip::telemetry::Event::EventProperty<double>::GetValue(bool)const ` | 51 | Exported Function
`public: enum mip::telemetry::Event::PiiKind __thiscall mip::telemetry::Event::EventProperty<double>::GetPiiKind(void)const ` | 44 | Exported Function
`public: virtual void __thiscall mip::telemetry::Event::AddProperty(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,bool,enum mip::telemetry::Event::PiiKind)` | 14 | Exported Function
`public: virtual void __thiscall mip::telemetry::Event::AddProperty(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum mip::telemetry::Event::PiiKind,bool)` | 11 | Exported Function
`public: virtual __thiscall mip::telemetry::Event::~Event(void)` | 8 | Exported Function
`public: virtual void __thiscall mip::telemetry::Event::AddProperty(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,__int64,enum mip::telemetry::Event::PiiKind)` | 13 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall mip::telemetry::Event::EventProperty<double>::GetName(void)const ` | 41 | Exported Function
`public: __thiscall mip::telemetry::Event::EventProperty<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >::EventProperty<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum mip::telemetry::Event::PiiKind,bool)` | 3 | Exported Function
`public: __thiscall mip::telemetry::Event::EventProperty<double>::EventProperty<double>(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,double const &,enum mip::telemetry::Event::PiiKind,bool)` | 2 | Exported Function
`public: __thiscall mip::telemetry::Event::Event(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 6 | Exported Function
`public: __thiscall mip::telemetry::Event::EventProperty<__int64>::EventProperty<__int64>(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,__int64 const &,enum mip::telemetry::Event::PiiKind,bool)` | 4 | Exported Function
`public: bool __thiscall mip::telemetry::Event::IsNecessaryData(void)const ` | 56 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall mip::telemetry::Event::EventProperty<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >::GetName(void)const ` | 42 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall mip::telemetry::Event::EventProperty<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >::GetValue(bool)const ` | 52 | Exported Function
`public: class mip::telemetry::Event & __thiscall mip::telemetry::Event::operator=(class mip::telemetry::Event const &)` | 9 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall mip::telemetry::Event::EventProperty<__int64>::GetName(void)const ` | 43 | Exported Function
`void __cdecl mip::telemetry::SetEventProperty(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,__int64,enum mip::telemetry::Event::PiiKind)` | 71 | Exported Function
`void __cdecl mip::telemetry::SetEventProperty(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,bool,enum mip::telemetry::Event::PiiKind)` | 72 | Exported Function
`void __cdecl mip::telemetry::ReleaseThreadResources(void)` | 63 | Exported Function
`void __cdecl mip::telemetry::SetEventErrorProperties(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::exception const *)` | 68 | Exported Function
`void __cdecl mip::telemetry::SetEventProperty(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum mip::telemetry::Event::PiiKind)` | 69 | Exported Function
`void __cdecl mip::telemetry::SetUseNoop(void)` | 74 | Exported Function
`void __cdecl mip::telemetry::Uninit(void)` | 75 | Exported Function
`void __cdecl mip::telemetry::SetEventProperty(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,double,enum mip::telemetry::Event::PiiKind)` | 70 | Exported Function
`void __cdecl mip::telemetry::SetTelemetryOverride(class std::shared_ptr<class mip::telemetry::TelemetryOverride> const &)` | 73 | Exported Function
`void __cdecl mip::telemetry::LogEvent(class mip::telemetry::Event &)` | 58 | Exported Function
`public: void __thiscall mip::telemetry::AutoEvent::SetErrorProperties(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::exception const *)` | 66 | Exported Function
`public: void __thiscall mip::telemetry::Event::``default constructor closure'(void)` | 10 | Exported Function
`public: virtual void __thiscall mip::telemetry::Event::AddProperty(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,double,enum mip::telemetry::Event::PiiKind)` | 12 | Exported Function
`public: virtual void __thiscall mip::telemetry::Event::SetErrorProperties(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::exception const *)` | 67 | Exported Function
`public: void __thiscall mip::telemetry::Event::SetAsNecessaryData(void)` | 65 | Exported Function
`void __cdecl mip::telemetry::Init(bool,struct mip::TelemetryConfiguration const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum mip::LogLevel)` | 54 | Exported Function
`void __cdecl mip::telemetry::LogAuditEvent(class mip::telemetry::Event const &)` | 57 | Exported Function
`void __cdecl mip::ReleaseAllResources(void)` | 62 | Exported Function
`void __cdecl mip::telemetry::Flush(void)` | 16 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetEngineTenantIdKey(void)` | 28 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetEngineUserObjectIdKey(void)` | 29 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetEnginePolicyDataSourceKey(void)` | 26 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetEngineSessionIdKey(void)` | 27 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetEventDurationKey(void)` | 31 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetHttpIsCancelledKey(void)` | 34 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetHttpIsRedirectedKey(void)` | 35 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetHttpCorrelationIdKey(void)` | 32 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetHttpIsAsynchronousKey(void)` | 33 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetEngineLocaleKey(void)` | 25 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetApplicationNameKey(void)` | 18 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetApplicationSessionIdKey(void)` | 19 | Exported Function
`bool __cdecl mip::telemetry::IsInitialized(void)` | 55 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetApplicationIdKey(void)` | 17 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetApplicationVersionKey(void)` | 20 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetEngineFileIdKey(void)` | 23 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetEngineIdKey(void)` | 24 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetDefaultLabelIdKey(void)` | 21 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetEngineEntryTimeKey(void)` | 22 | Exported Function
`class std::shared_ptr<class mip::telemetry::Event> __cdecl mip::telemetry::RemoveEvent(void)` | 64 | Exported Function
`class std::unique_ptr<class mip::telemetry::AutoEvent,struct std::default_delete<class mip::telemetry::AutoEvent> > __cdecl mip::telemetry::NewAutoEvent(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 59 | Exported Function
`class std::shared_ptr<class mip::telemetry::Event> __cdecl mip::telemetry::GetEvent(void)` | 30 | Exported Function
`class std::shared_ptr<class mip::telemetry::Event> __cdecl mip::telemetry::NewEvent(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 61 | Exported Function
`class std::unique_ptr<class mip::telemetry::AutoEvent,struct std::default_delete<class mip::telemetry::AutoEvent> > __cdecl mip::telemetry::NewAutoEvent(class std::shared_ptr<class mip::telemetry::Event> const &)` | 60 | Exported Function
`public: __thiscall mip::telemetry::AutoEvent::~AutoEvent(void)` | 7 | Exported Function
`public: __thiscall mip::telemetry::Event::Event(class mip::telemetry::Event const &)` | 5 | Exported Function
`int ``public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall mip::telemetry::Event::EventProperty<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >::GetValue(bool)const '::``5'::$TSS0` | 1 | Exported Function
`public: __int64 const & __thiscall mip::telemetry::Event::EventProperty<__int64>::GetValue(bool)const ` | 53 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const ``public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __thiscall mip::telemetry::Event::EventProperty<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >::GetValue(bool)const '::``5'::kSensitiveDataCensoredValue` | 76 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetLabelIdKey(void)` | 38 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetMipVersionKey(void)` | 39 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetHttpStatusCodeKey(void)` | 36 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetHttpUrlKey(void)` | 37 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetMipVersionValue(void)` | 40 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetUseInStorageMemoryIdKey(void)` | 49 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetUserObjectIdKey(void)` | 50 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetTelemetryHostNameOverrideKey(void)` | 47 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __cdecl mip::telemetry::GetTenantIdKey(void)` | 48 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: MIP SDK
* Company Name: Microsoft Corporation
* File Version: 1.2.185
* Product Version: 1.2.185
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/f03be04c4abf1bbab5be58273f3edaf307c0426f425f0521a6ac92f04e5e5de2/detection/




MIT License. Copyright (c) 2020 Strontic.


