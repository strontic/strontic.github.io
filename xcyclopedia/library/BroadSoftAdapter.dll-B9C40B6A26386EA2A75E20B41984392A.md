---
title: BroadSoftAdapter.dll | BroadSoftAdapter dll file
excerpt: What is BroadSoftAdapter.dll?
---

# BroadSoftAdapter.dll 

* File Path: `C:\Program Files (x86)\Sennheiser\SenncomSDK\BroadSoftAdapter.dll`
* Description: BroadSoftAdapter dll file

## Hashes

Type | Hash
-- | --
MD5 | `B9C40B6A26386EA2A75E20B41984392A`
SHA1 | `50F1248574ABBA9F75AEEB3835228ED6153D2152`
SHA256 | `0B81294E50606E1E038906FC0059B1D22FBF3745FD2BA7EC04775F690E6F3A18`
SHA384 | `63457E9B2FACA1DDB0A5EF5EBD478617A5FF05B6BEC6BB8386DED6B40A24E48D9DA017EBF0AE79167DF5409F353B2909`
SHA512 | `0B242D2375EAC1C69D19C09C9CE8BB4E2A9B560DD545A44721ED28D32B4D3BC62B0DA5B7696DD3B8012F2C04D24F186E7B7D2D8B3871F3A5099E3519E280A211`
SSDEEP | `12288:BtkYghOxU3RE/XOuwP6kQIRrvGRidmbNzAqR4tWIu:Bij53RE/XoQIRriidmpzAqR4Ju`
IMP | `023E26FE4997208E15AF10AD847080C0`
PESHA1 | `EA8D9B1BA5F2AB9E5AACADD23601BE52D96E5390`
PE256 | `7E221689DF83B18FB07DA6944AE3A79A78E17E852EC035716A3915049A8E3291`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: virtual __thiscall HSAdapterInterface::IHSInterface::~IHSInterface(void)` | 16 | Exported Function
`public: virtual __thiscall SeComBroadSoftAdapter::BroadSoftEventListener::~BroadSoftEventListener(void)` | 13 | Exported Function
`public: static void __cdecl SeComBroadSoftAdapter::BroadSoftImpl::DestroyBroadSoftInstance(void)` | 37 | Exported Function
`public: static class ProcessTracker * __cdecl ProcessTracker::_GetInstance(void)` | 57 | Exported Function
`public: static class std::shared_ptr<class SeComBroadSoftAdapter::BroadSoftImpl> __cdecl SeComBroadSoftAdapter::BroadSoftImpl::GetBroadSoftInstance(class ISFEventListener *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 39 | Exported Function
`public: virtual bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::activeDeviceChangedFromSDK(void)` | 70 | Exported Function
`public: virtual bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::connect(void)` | 71 | Exported Function
`public: virtual __thiscall SFAdapterInterface::ISFInterface::~ISFInterface(void)` | 17 | Exported Function
`public: virtual __thiscall SeComBroadSoftAdapter::BroadSoftImpl::~BroadSoftImpl(void)` | 14 | Exported Function
`public: virtual __thiscall SeComCall::ICall::~ICall(void)` | 15 | Exported Function
`public: static bool __cdecl SeComBroadSoftAdapter::BroadSoftImpl::IsBroadSoftInstalled(void)` | 40 | Exported Function
`public: class HSAdapterInterface::IHSInterface & __thiscall HSAdapterInterface::IHSInterface::operator=(class HSAdapterInterface::IHSInterface const &)` | 22 | Exported Function
`public: class ISFEventListener & __thiscall ISFEventListener::operator=(class ISFEventListener const &)` | 23 | Exported Function
`public: bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::isSupportedSoftphone(void)` | 82 | Exported Function
`public: bool __thiscall SeComBroadSoftAdapter::BroadSoftEventListener::CanSendRequest(void)` | 36 | Exported Function
`public: bool __thiscall SeComBroadSoftAdapter::BroadSoftEventListener::IsWaitingForResponse(void)const ` | 41 | Exported Function
`public: class SeComCall::ICall & __thiscall SeComCall::ICall::operator=(class SeComCall::ICall const &)` | 21 | Exported Function
`public: class SFAdapterInterface::ISFInterface & __thiscall SFAdapterInterface::ISFInterface::operator=(class SFAdapterInterface::ISFInterface const &)` | 24 | Exported Function
`public: class SeComBroadSoftAdapter::BroadSoftImpl & __thiscall SeComBroadSoftAdapter::BroadSoftImpl::operator=(class SeComBroadSoftAdapter::BroadSoftImpl const &)` | 20 | Exported Function
`public: class ProcessTracker & __thiscall ProcessTracker::operator=(class ProcessTracker const &)` | 25 | Exported Function
`public: class SeComBroadSoftAdapter::BroadSoftEventListener & __thiscall SeComBroadSoftAdapter::BroadSoftEventListener::operator=(class SeComBroadSoftAdapter::BroadSoftEventListener const &)` | 19 | Exported Function
`public: virtual bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::disconnect(void)` | 73 | Exported Function
`public: virtual void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::MessageReceived(class SeComBroadSoftAdapter::BroadSoftMessage const *)` | 42 | Exported Function
`public: virtual void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::OnConnectionChange(bool)` | 43 | Exported Function
`public: virtual void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::informHeadsetDisconnected(class SecomHeadset::CHeadsetInfo *)` | 79 | Exported Function
`public: virtual void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::informConnectedHsListToAdapters(class std::list<class std::shared_ptr<class SecomHeadset::CHeadsetInfo>,class std::allocator<class std::shared_ptr<class SecomHeadset::CHeadsetInfo> > > *)` | 77 | Exported Function
`public: virtual void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::informHeadsetConnected(class std::shared_ptr<class SecomHeadset::CHeadsetInfo>)` | 78 | Exported Function
`public: void __thiscall SeComBroadSoftAdapter::BroadSoftEventListener::SetWaitForResponse(bool)` | 51 | Exported Function
`public: void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::writeToLog(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 87 | Exported Function
`public: void __thiscall ProcessTracker::_DestroyInstance(void)` | 55 | Exported Function
`public: virtual void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::ProcessEnded(void)` | 45 | Exported Function
`public: virtual void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::ProcessStarted(void)` | 46 | Exported Function
`public: virtual void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::destroy(void)` | 72 | Exported Function
`public: virtual bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::muteCall(bool)` | 83 | Exported Function
`public: virtual bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::offHook(void)` | 84 | Exported Function
`public: virtual bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::isRedialNotSupported(void)` | 81 | Exported Function
`public: virtual bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::getMuteStatus(void)` | 76 | Exported Function
`public: virtual bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::isOffHookNotSupported(void)` | 80 | Exported Function
`public: virtual enum SeComAppDefs::CONNECTION_TYPE __thiscall SeComBroadSoftAdapter::BroadSoftImpl::getConnectionType(void)` | 74 | Exported Function
`public: virtual void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::CallEnded(class SeComBroadSoftAdapter::CBroadSoftCallImpl *)` | 35 | Exported Function
`public: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall SeComBroadSoftAdapter::BroadSoftImpl::getID(void)` | 75 | Exported Function
`public: virtual bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::onHook(void)` | 85 | Exported Function
`public: virtual bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::redial(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 86 | Exported Function
`public: bool __thiscall ProcessTracker::RemoveProcessObserver(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class ProcessObserver *)` | 47 | Exported Function
`private: bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::PerformRegistration(void)` | 44 | Exported Function
`private: bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::SendMuteEvent(bool)` | 48 | Exported Function
`private: bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::_RemoveCallFromList(class SeComBroadSoftAdapter::CBroadSoftCallImpl *,bool)` | 66 | Exported Function
`private: bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::_AddCallToCallList(class SeComBroadSoftAdapter::CBroadSoftCallImpl *)` | 53 | Exported Function
`private: bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::_DeleteAllCalls(void)` | 54 | Exported Function
`private: int __thiscall SeComBroadSoftAdapter::BroadSoftImpl::GetActiveCallID(void)` | 38 | Exported Function
`private: static class ProcessTracker * ProcessTracker::_pProcessTrackInstance` | 69 | Exported Function
`private: class SeComBroadSoftAdapter::CBroadSoftCallImpl * __thiscall SeComBroadSoftAdapter::BroadSoftImpl::_GetCallWithID(int)` | 56 | Exported Function
`private: bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::SendOffhook(void)` | 49 | Exported Function
`private: bool __thiscall SeComBroadSoftAdapter::BroadSoftImpl::SendRedialEvent(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 50 | Exported Function
`private: __thiscall SeComBroadSoftAdapter::BroadSoftImpl::BroadSoftImpl(class ISFEventListener *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 3 | Exported Function
`const SeComBroadSoftAdapter::BroadSoftImpl::``vftable'{for ``ProcessObserver'}` | 29 | Exported Function
`const SeComBroadSoftAdapter::BroadSoftImpl::``vftable'{for ``SeComBroadSoftAdapter::BroadSoftEventListener'}` | 27 | Exported Function
`const SeComBroadSoftAdapter::BroadSoftEventListener::``vftable'` | 26 | Exported Function
`const HSAdapterInterface::IHSInterface::``vftable'` | 31 | Exported Function
`const ISFEventListener::``vftable'` | 32 | Exported Function
`private: __thiscall ProcessTracker::ProcessTracker(void)` | 12 | Exported Function
`private: __thiscall ProcessTracker::~ProcessTracker(void)` | 18 | Exported Function
`const SFAdapterInterface::ISFInterface::``vftable'` | 33 | Exported Function
`const SeComBroadSoftAdapter::BroadSoftImpl::``vftable'{for ``SFAdapterInterface::ISFInterface'}` | 28 | Exported Function
`const SeComCall::ICall::``vftable'` | 30 | Exported Function
`private: static class std::shared_ptr<class SeComBroadSoftAdapter::BroadSoftImpl> SeComBroadSoftAdapter::BroadSoftImpl::_pBroadSoftInstance` | 68 | Exported Function
`public: __thiscall SeComBroadSoftAdapter::BroadSoftEventListener::BroadSoftEventListener(class SeComBroadSoftAdapter::BroadSoftEventListener const &)` | 1 | Exported Function
`public: __thiscall SeComBroadSoftAdapter::BroadSoftEventListener::BroadSoftEventListener(void)` | 2 | Exported Function
`public: __thiscall ISFEventListener::ISFEventListener(void)` | 9 | Exported Function
`public: __thiscall HSAdapterInterface::IHSInterface::IHSInterface(void)` | 7 | Exported Function
`public: __thiscall ISFEventListener::ISFEventListener(class ISFEventListener const &)` | 8 | Exported Function
`public: __thiscall SFAdapterInterface::ISFInterface::ISFInterface(void)` | 11 | Exported Function
`public: bool __thiscall ProcessTracker::AddProcessObserver(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class ProcessObserver *)` | 34 | Exported Function
`public: __thiscall SFAdapterInterface::ISFInterface::ISFInterface(class SFAdapterInterface::ISFInterface const &)` | 10 | Exported Function
`public: __thiscall SeComCall::ICall::ICall(class SeComCall::ICall const &)` | 4 | Exported Function
`public: __thiscall SeComCall::ICall::ICall(void)` | 5 | Exported Function
`public: __thiscall HSAdapterInterface::IHSInterface::IHSInterface(class HSAdapterInterface::IHSInterface const &)` | 6 | Exported Function
`private: void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::_OnCallCreated(class SeComBroadSoftAdapter::BroadSoftMessage const *)` | 59 | Exported Function
`private: void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::_OnCallHold(class SeComBroadSoftAdapter::BroadSoftMessage const *)` | 60 | Exported Function
`private: void __thiscall ProcessTracker::_UnInitialize(void)` | 67 | Exported Function
`private: void __thiscall ProcessTracker::_Initialize(void)` | 58 | Exported Function
`private: void __thiscall ProcessTracker::_ProcessTrackerServiceProcedure(void)` | 65 | Exported Function
`private: void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::_OnRingingCall(class SeComBroadSoftAdapter::BroadSoftMessage const *)` | 64 | Exported Function
`private: void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::SubscribeforEvents(void)` | 52 | Exported Function
`private: void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::_OnCallTerminated(class SeComBroadSoftAdapter::BroadSoftMessage const *)` | 63 | Exported Function
`private: void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::_OnCallOpen(class SeComBroadSoftAdapter::BroadSoftMessage const *)` | 61 | Exported Function
`private: void __thiscall SeComBroadSoftAdapter::BroadSoftImpl::_OnCallRejected(class SeComBroadSoftAdapter::BroadSoftMessage const *)` | 62 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `5422C64EF952DE89AE41B042558FFC41`
* Thumbprint: `735C91FA1DB4FFB0CA7FFF980C75AF29F8703050`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Sennheiser Communications A/S, OU=Cloud and Desktop applications, O=Sennheiser Communications A/S, L=Ballerup, S=DK, C=DK

## File Metadata

* Original Filename: BroadSoftAdapter.dll
* Product Name: SenncomSDK
* Company Name: Sennheiser Communications A/S 2016
* File Version: 1.0.0.0
* Product Version: 9.0.1.285
* Language: English (United States)
* Legal Copyright: Sennheiser Communications A/S 2016
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/0b81294e50606e1e038906fc0059b1d22fbf3745fd2ba7ec04775f690e6f3a18/detection/




MIT License. Copyright (c) 2020 Strontic.


