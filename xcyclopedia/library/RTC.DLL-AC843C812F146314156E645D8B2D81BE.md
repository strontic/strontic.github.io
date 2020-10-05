---
title: RTC.DLL | Microsoft Realtime Collaboration Dll
excerpt: What is RTC.DLL?
---

# RTC.DLL 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\RTC.DLL`
* Description: Microsoft Realtime Collaboration Dll

## Hashes

Type | Hash
-- | --
MD5 | `AC843C812F146314156E645D8B2D81BE`
SHA1 | `693F4B348BAD6A192A9FDB2B98BE629DE259D102`
SHA256 | `B8E4FFB7B25F74AD0914A1080F9039FF3F6DFD5BBCC33BD766AF36B1FA36C6F6`
SHA384 | `D3BE1BE270525D17E9BFEC5518FD8B273A02433EB47F13F8557AED06E07E0DFF97C17B24F6AF3166AA01559B27CDCB78`
SHA512 | `CE6BEFEF09E2751D796F2FB873C59172A06B09297FFD9202F9DF3E62E7DDB6464E7FDE04BC63BB511240E2BF647021A8F9F717B2E3D720FF0C8DF9AA5B187176`
SSDEEP | `49152:kn/uuK3p0b5bf2uvlEvKeVQXZ5qGNzRvXJ6eXbuLgFP6ismXcUUdl:ktEJSe0ZBNzRvZ+WQ`
IMP | `28051B6F551CB1BDCA618130B859F2EB`
PESHA1 | `DD5EDF09FD22EA942C316A04E2A800211DDAC887`
PE256 | `4C76FCCE87EA0B98D5C819AF0329FB74ABF8711F56E62C9305B63F496B644EDA`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: virtual unsigned int __thiscall Rtc::RealtimeChannelConnection::RegisterPersistentStateUpdateHandler(class std::function<void __stdcall(struct Rtc::FullPersistentState const &)> &&)` | 58 | Exported Function
`public: virtual unsigned int __thiscall Rtc::RealtimeChannelConnection::RegisterPresenceUpdateHandler(class std::function<void __stdcall(struct Rtc::FullPresenceData const &)> &&)` | 59 | Exported Function
`public: virtual unsigned int __thiscall Rtc::RealtimeChannelConnection::RegisterPersistentStateClearedUpdateHandler(class std::function<void __stdcall(struct Rtc::PersistentStateClearedData const &)> &&)` | 57 | Exported Function
`public: virtual unsigned int __thiscall Rtc::RealtimeChannelConnection::RegisterLabelUpdateHandler(class std::function<void __stdcall(void)> &&)` | 55 | Exported Function
`public: virtual unsigned int __thiscall Rtc::RealtimeChannelConnection::RegisterPersistedContentUpdateHandler(class std::function<void __stdcall(struct Rtc::PersistedContentNotificationData const &)> &&)` | 56 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::Close(bool)` | 14 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::Disconnect(void)` | 28 | Exported Function
`public: virtual unsigned int __thiscall Rtc::RealtimeChannelConnection::RegisterWetContentUpdateHandler(class std::function<void __stdcall(struct Rtc::WetContentData const &)> &&)` | 62 | Exported Function
`public: virtual unsigned int __thiscall Rtc::RealtimeChannelConnection::RegisterReconnectRequestHandler(class std::function<void __stdcall(void)> &&)` | 61 | Exported Function
`public: virtual unsigned int __thiscall Rtc::RealtimeChannelConnection::RegisterRTTStatusChangedHandler(class std::function<void __stdcall(void)> &&)` | 60 | Exported Function
`public: virtual class Mso::TCntPtr<class Rtc::Task<void> > __thiscall Rtc::RealtimeChannelConnection::BroadcastWetContentUpdateAsync(struct Rtc::WetContentData const &&)` | 12 | Exported Function
`public: virtual class std::map<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,struct std::less<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >,class std::allocator<struct std::pair<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const ,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > > __thiscall Rtc::RealtimeChannelConnection::GetMessageLatencyHistograms(void)` | 32 | Exported Function
`public: virtual class Mso::TCntPtr<class Rtc::Task<void> > __thiscall Rtc::RealtimeChannelConnection::BroadcastPresenceUpdateAsync(struct Rtc::ClientPresenceData const &&)` | 11 | Exported Function
`public: virtual class Mso::TCntPtr<class Rtc::Task<void> > __thiscall Rtc::RealtimeChannelConnection::BroadcastPersistedContentUpdateAsync(struct Rtc::PersistedContentNotificationData const &&)` | 9 | Exported Function
`public: virtual class Mso::TCntPtr<class Rtc::Task<void> > __thiscall Rtc::RealtimeChannelConnection::BroadcastPersistentStateUpdateAsync(enum PersistentStateType,struct Rtc::ClientPersistentState const &&)` | 10 | Exported Function
`public: virtual unsigned int __thiscall Rtc::RealtimeChannelConnection::RegisterEditorsTableUpdateHandler(class std::function<void __stdcall(struct Rtc::EditorsTableUpdateData const &)> &&)` | 51 | Exported Function
`public: virtual unsigned int __thiscall Rtc::RealtimeChannelConnection::RegisterFileNameUpdateHandler(class std::function<void __stdcall(void)> &&)` | 53 | Exported Function
`public: virtual unsigned int __thiscall Rtc::RealtimeChannelConnection::RegisterConnectionStateChangeHandler(class std::function<void __stdcall(enum Rtc::ConnectionState)> &&)` | 50 | Exported Function
`public: virtual enum Rtc::ConnectionState __thiscall Rtc::RealtimeChannelConnection::GetConnectionState(void)` | 31 | Exported Function
`public: virtual unsigned int __thiscall Rtc::RealtimeChannelConnection::RegisterCollabContentUpdateHandler(class std::function<void __stdcall(struct Rtc::CollabContentUpdateData const &)> &&)` | 49 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::ForceNextReconnectToTimeout(void)` | 29 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::UnregisterRTTStatusChangedHandler(unsigned int &)` | 78 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::UnregisterWetContentUpdateHandler(unsigned int &)` | 80 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::UnregisterReconnectRequestHandler(unsigned int &)` | 79 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::UnregisterPersistentStateUpdateHandler(unsigned int &)` | 76 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::UnregisterPresenceUpdateHandler(unsigned int &)` | 77 | Exported Function
`public: void __thiscall Rtc::Throttler::UpdateThrottlingParameters(unsigned int,unsigned int,unsigned int)` | 81 | Exported Function
`struct Rtc::RealtimeChannelSettings __stdcall Rtc::CreateRealtimeChannelSettings(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)` | 21 | Exported Function
`public: void __thiscall Rtc::Throttler::ThrowIfThrottled(void)` | 68 | Exported Function
`public: void __thiscall Rtc::Throttler::CancelAllRegisteredTasks(void)` | 13 | Exported Function
`public: void __thiscall Rtc::Throttler::RegisterExecutingTask(class Mso::TCntPtr<class Rtc::Task<void> >,class Mso::TCntPtr<class Rtc::CancellationTokenSource>)` | 52 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::UnregisterCollabContentUpdateHandler(unsigned int &)` | 69 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::UnregisterConnectionStateChangeHandler(unsigned int &)` | 70 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::SetThrottling(int,int,int,int)` | 64 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::ForceReconnect(void)` | 30 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::SetExpirationTime(class std::chrono::time_point<struct std::chrono::system_clock,class std::chrono::duration<__int64,struct std::ratio<1,10000000> > > const &)` | 63 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::UnregisterPersistedContentUpdateHandler(unsigned int &)` | 74 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::UnregisterPersistentStateClearedUpdateHandler(unsigned int &)` | 75 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::UnregisterLabelUpdateHandler(unsigned int &)` | 73 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::UnregisterEditorsTableUpdateHandler(unsigned int &)` | 71 | Exported Function
`public: virtual void __thiscall Rtc::RealtimeChannelConnection::UnregisterFileNameUpdateHandler(unsigned int &)` | 72 | Exported Function
`protected: void __thiscall Rtc::RealtimeChannelConnection::CloseHub(void)` | 15 | Exported Function
`protected: void __thiscall Rtc::RealtimeChannelConnection::CreateProxy(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)` | 17 | Exported Function
`protected: class Mso::TCntPtr<class Rtc::Task<void> > __thiscall Rtc::RealtimeChannelConnection::OnUpdateNotification(class Mso::Json::value const &)` | 45 | Exported Function
`protected: class Mso::TCntPtr<class Rtc::Task<void> > __thiscall Rtc::RealtimeChannelConnection::OnPersistentStateUpdated(class Mso::Json::value const &)` | 43 | Exported Function
`protected: class Mso::TCntPtr<class Rtc::Task<void> > __thiscall Rtc::RealtimeChannelConnection::OnPresenceUpdated(class Mso::Json::value const &)` | 44 | Exported Function
`protected: void __thiscall Rtc::RealtimeChannelConnection::WaitOnRemainingCallbackTasks(void)` | 82 | Exported Function
`public: __thiscall Rtc::RealtimeChannelConnection::RealtimeChannelConnection(struct Rtc::RealtimeChannelSettings &,class std::shared_ptr<class Rtc::IHubConnectionFactory>)` | 1 | Exported Function
`protected: void __thiscall Rtc::RealtimeChannelConnection::StartHub(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,bool)` | 66 | Exported Function
`protected: void __thiscall Rtc::RealtimeChannelConnection::RegisterCallbackTask(class Mso::TCntPtr<class Rtc::Task<void> >)` | 48 | Exported Function
`protected: void __thiscall Rtc::RealtimeChannelConnection::RegisterHandlersWithSignalRProxy(void)` | 54 | Exported Function
`class Mso::TCntPtr<class Rtc::IRealtimeChannelConnectionAccess> __stdcall Rtc::CreateRealtimeChannelConnectionAccess(struct Rtc::RealtimeChannelSettings &&)` | 19 | Exported Function
`class Mso::TCntPtr<struct Rtc::IRealtimeChannel> __stdcall Rtc::CreateRealtimeChannel(class Mso::TCntPtr<class Rtc::IRealtimeChannelConnectionAccess> const &,struct _GUID const &,class Mso::TCntPtr<struct Mso::DocumentId::IDocumentId> const &,enum MSOAPP,class Mso::Functor<class Mso::Future<class Mso::Maybe<class std::unordered_map<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> >,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> >,struct std::hash<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > >,struct std::equal_to<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > >,class std::allocator<struct std::pair<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const ,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > > > > > > __stdca` | 18 | Exported Function
`class Mso::TCntPtr<class Rtc::IRealtimeChannelConnectionAccess> __stdcall Rtc::CreateRealtimeChannelConnectionAccess(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)` | 20 | Exported Function
`bool __stdcall Rtc::IsFindSessionEndpointSupported(void)` | 37 | Exported Function
`class Mso::ErrorProvider<enum Rtc::RtcError,class Rtc::RtcErrorGuid> const & __stdcall Rtc::GetRtcErrorProvider(void)` | 33 | Exported Function
`protected: class Mso::TCntPtr<class Rtc::Task<void> > __thiscall Rtc::RealtimeChannelConnection::InvokeConnectionStateChangeHandlers(enum Rtc::ConnectionState)` | 36 | Exported Function
`protected: class Mso::TCntPtr<class Rtc::Task<void> > __thiscall Rtc::RealtimeChannelConnection::OnPersistentStateCleared(class Mso::Json::value const &)` | 42 | Exported Function
`private: void __thiscall Rtc::RealtimeChannelConnection::SetThrottlingInternal(int,int,int,int)` | 65 | Exported Function
`private: bool __thiscall Rtc::RealtimeChannelConnection::IsHubInitialized(void)` | 40 | Exported Function
`private: struct Rtc::OperationResult __thiscall Rtc::RealtimeChannelConnection::OpenConnectionInternal(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,bool)` | 47 | Exported Function
`public: __thiscall Rtc::Throttler::Throttler(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,enum UpdateNotificationType,unsigned int,unsigned int,unsigned int)` | 2 | Exported Function
`public: virtual class Mso::TCntPtr<class Rtc::Task<class std::shared_ptr<struct Rtc::ServicePersistentState> > > __thiscall Rtc::RealtimeChannelConnection::GetServicePersistentStateAsync(enum PersistentStateType)` | 34 | Exported Function
`public: virtual class Mso::TCntPtr<class Rtc::Task<class std::shared_ptr<struct Rtc::ServicePresenceData> > > __thiscall Rtc::RealtimeChannelConnection::GetServicePresenceAsync(void)` | 35 | Exported Function
`public: virtual bool __thiscall Rtc::RealtimeChannelConnection::SupportsWetContent(void)` | 67 | Exported Function
`public: virtual bool __thiscall Rtc::RealtimeChannelConnection::IsHubExplicitlyDisconnected(void)` | 39 | Exported Function
`public: virtual bool __thiscall Rtc::RealtimeChannelConnection::IsTokenExpired(void)` | 41 | Exported Function
`public: virtual class Mso::TCntPtr<class Rtc::Task<void> > __thiscall Rtc::RealtimeChannelConnection::BroadcastFileNameUpdateAsync(void)` | 7 | Exported Function
`public: virtual class Mso::TCntPtr<class Rtc::Task<void> > __thiscall Rtc::RealtimeChannelConnection::BroadcastLabelUpdateAsync(void)` | 8 | Exported Function
`public: virtual class Mso::TCntPtr<class Rtc::Task<void> > __thiscall Rtc::RealtimeChannelConnection::BroadcastEditorsTableUpdateAsync(struct Rtc::EditorsTableUpdateData const &&)` | 6 | Exported Function
`public: virtual class Mso::TCntPtr<class Rtc::Task<struct Rtc::OperationResult> > __thiscall Rtc::RealtimeChannelConnection::OpenConnection(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,bool,bool)` | 46 | Exported Function
`public: virtual class Mso::TCntPtr<class Rtc::Task<void> > __thiscall Rtc::RealtimeChannelConnection::BroadcastCollabContentUpdateAsync(struct Rtc::CollabContentUpdateData const &&)` | 5 | Exported Function
`public: static void __stdcall Rtc::RealtimeChannelConnection::DeserializeFullPresenceData(class Mso::Json::value const &,struct Rtc::FullPresenceData *)` | 23 | Exported Function
`public: static void __stdcall Rtc::RealtimeChannelConnection::DeserializePersistentStateClearedData(class Mso::Json::value const &,struct Rtc::PersistentStateClearedData *)` | 24 | Exported Function
`public: static void __stdcall Rtc::RealtimeChannelConnection::DeserializeFullPersistentState(class Mso::Json::value const &,struct Rtc::FullPersistentState *)` | 22 | Exported Function
`public: __thiscall Rtc::Throttler::~Throttler(void)` | 4 | Exported Function
`public: static class std::unique_ptr<class Rtc::IHubConnection,struct std::default_delete<class Rtc::IHubConnection> > __stdcall Rtc::IHubConnection::Create(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,bool,class std::function<void __cdecl(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)> &&)` | 16 | Exported Function
`public: virtual __thiscall Rtc::RealtimeChannelConnection::~RealtimeChannelConnection(void)` | 3 | Exported Function
`public: virtual bool __thiscall Rtc::RealtimeChannelConnection::IsHubConnecting(void)` | 38 | Exported Function
`public: static void __stdcall Rtc::RealtimeChannelConnection::DeserializeUpdateData(class Mso::Json::value const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> >,int &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > &)` | 27 | Exported Function
`public: static void __stdcall Rtc::RealtimeChannelConnection::DeserializeServicePersistentState(class Mso::Json::value const &,struct Rtc::ServicePersistentState *)` | 25 | Exported Function
`public: static void __stdcall Rtc::RealtimeChannelConnection::DeserializeServicePresenceData(class Mso::Json::value const &,struct Rtc::ServicePresenceData *)` | 26 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002CE7C9ACE7D905ED2B70000000002CE`
* Thumbprint: `B10607FB914700B40F794610850C1DE0A21566C1`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Rtc.dll
* Product Name: Microsoft Office
* Company Name: Microsoft Corporation
* File Version: 16.0.12527.20122
* Product Version: 16.0.12527.20122
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/b8e4ffb7b25f74ad0914a1080f9039ff3f6dfd5bbcc33bd766af36b1fa36c6f6/detection/




MIT License. Copyright (c) 2020 Strontic.


