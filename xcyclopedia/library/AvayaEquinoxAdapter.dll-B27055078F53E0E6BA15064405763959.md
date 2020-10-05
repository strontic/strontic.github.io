---
title: AvayaEquinoxAdapter.dll | AvayaEquinoxAdapter dll file
excerpt: What is AvayaEquinoxAdapter.dll?
---

# AvayaEquinoxAdapter.dll 

* File Path: `C:\Program Files (x86)\Sennheiser\SenncomSDK\AvayaEquinoxAdapter.dll`
* Description: AvayaEquinoxAdapter dll file

## Hashes

Type | Hash
-- | --
MD5 | `B27055078F53E0E6BA15064405763959`
SHA1 | `3CDFAF22A0581E32406A1679B84E91ABCFB1FF36`
SHA256 | `2A6B3A23D554AC90C29DC53133E860421F596F862BB220D491446D1D102AA565`
SHA384 | `BF19CB8CAF5EEEF084A3F628DF783F40FFBFB23829FDDEB3F162E1811E3D420978423AFB2D88036DB9A9646BE9A3D68E`
SHA512 | `19F059FF8CD268974D34FDECDAFC3748C998B01368A5022BD744CFD1DE3C299C35CEFB34F30694EAA3EEDC3250CC17D3F0BAC8398DE54A52FA100A9BDA410DA4`
SSDEEP | `6144:V0tZM/hCHWIACGCMUaul6lQEAXZWc5tSqJcsRGTT:V4MMWUTaIAQLXZV1iT`
IMP | `0895CFF81B6C9A590F27CE3AA5BE643F`
PESHA1 | `6569F34E9EDEC53325E23B1847D98332CB12D166`
PE256 | `E1695836C8D5CE4CB5BCB9F3AA4D5005D25CEF946C41D1C1532FB8C6930B1D7D`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: __thiscall HSAdapterInterface::IHSInterface::IHSInterface(void)` | 6 | Exported Function
`public: __thiscall HSAdapterInterface::IHSInterface::IHSInterface(class HSAdapterInterface::IHSInterface const &)` | 5 | Exported Function
`protected: virtual void __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::MessageReceived(char const *)` | 30 | Exported Function
`public: __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::AvayaEquinox(class SecomAvayaEquinoxAdapter::AvayaEquinox const &)` | 2 | Exported Function
`public: __thiscall ISFEventListener::ISFEventListener(void)` | 8 | Exported Function
`public: __thiscall ISFEventListener::ISFEventListener(class ISFEventListener const &)` | 7 | Exported Function
`protected: virtual void __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::informHeadsetDisconnected(class SecomHeadset::CHeadsetInfo *)` | 47 | Exported Function
`protected: virtual void __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::ConnectionChanged(bool)` | 28 | Exported Function
`protected: virtual void __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::CallEnded(class SecomAvayaEquinoxAdapter::AvayaEquinoxCall *,bool)` | 27 | Exported Function
`protected: virtual enum SeComAppDefs::CONNECTION_TYPE __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::getConnectionType(void)` | 42 | Exported Function
`protected: virtual void __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::informHeadsetConnected(class std::shared_ptr<class SecomHeadset::CHeadsetInfo>)` | 46 | Exported Function
`protected: virtual void __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::informConnectedHsListToAdapters(class std::list<class std::shared_ptr<class SecomHeadset::CHeadsetInfo>,class std::allocator<class std::shared_ptr<class SecomHeadset::CHeadsetInfo> > > *)` | 45 | Exported Function
`protected: virtual void __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::destroy(void)` | 40 | Exported Function
`public: __thiscall SeComCall::ICall::ICall(class SeComCall::ICall const &)` | 3 | Exported Function
`public: virtual __thiscall HSAdapterInterface::IHSInterface::~IHSInterface(void)` | 13 | Exported Function
`public: static class std::shared_ptr<class SecomAvayaEquinoxAdapter::AvayaEquinox> __cdecl SecomAvayaEquinoxAdapter::AvayaEquinox::GetInstance(class ISFEventListener *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 29 | Exported Function
`public: class SFAdapterInterface::ISFInterface & __thiscall SFAdapterInterface::ISFInterface::operator=(class SFAdapterInterface::ISFInterface const &)` | 19 | Exported Function
`public: virtual __thiscall SFAdapterInterface::ISFInterface::~ISFInterface(void)` | 14 | Exported Function
`public: virtual __thiscall SeComCall::ICall::~ICall(void)` | 12 | Exported Function
`public: virtual __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::~AvayaEquinox(void)` | 11 | Exported Function
`public: class SeComCall::ICall & __thiscall SeComCall::ICall::operator=(class SeComCall::ICall const &)` | 16 | Exported Function
`public: __thiscall SFAdapterInterface::ISFInterface::ISFInterface(void)` | 10 | Exported Function
`public: __thiscall SFAdapterInterface::ISFInterface::ISFInterface(class SFAdapterInterface::ISFInterface const &)` | 9 | Exported Function
`public: __thiscall SeComCall::ICall::ICall(void)` | 4 | Exported Function
`public: class SecomAvayaEquinoxAdapter::AvayaEquinox & __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::operator=(class SecomAvayaEquinoxAdapter::AvayaEquinox const &)` | 15 | Exported Function
`public: class ISFEventListener & __thiscall ISFEventListener::operator=(class ISFEventListener const &)` | 18 | Exported Function
`public: class HSAdapterInterface::IHSInterface & __thiscall HSAdapterInterface::IHSInterface::operator=(class HSAdapterInterface::IHSInterface const &)` | 17 | Exported Function
`private: class SecomAvayaEquinoxAdapter::AvayaEquinoxCall * __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::_GetCallWithID(int)` | 31 | Exported Function
`private: bool __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::_RemoveCallFromList(class SecomAvayaEquinoxAdapter::AvayaEquinoxCall *,bool)` | 35 | Exported Function
`private: __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::AvayaEquinox(class ISFEventListener *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 1 | Exported Function
`private: void __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::_HandleCallEventMsg(struct SecomAvayaEquinoxAdapter::EquinoxMessage const &)` | 32 | Exported Function
`private: static class std::shared_ptr<class SecomAvayaEquinoxAdapter::AvayaEquinox> SecomAvayaEquinoxAdapter::AvayaEquinox::_pEquinoxInstance` | 36 | Exported Function
`private: static class ISFEventListener * SecomAvayaEquinoxAdapter::AvayaEquinox::_pEvtlistener` | 37 | Exported Function
`const SFAdapterInterface::ISFInterface::``vftable'` | 26 | Exported Function
`const SecomAvayaEquinoxAdapter::AvayaEquinox::``vftable'{for ``SecomAvayaEquinoxAdapter::EquinoxCallEventHandler'}` | 20 | Exported Function
`const ISFEventListener::``vftable'` | 25 | Exported Function
`const HSAdapterInterface::IHSInterface::``vftable'` | 24 | Exported Function
`const SeComCall::ICall::``vftable'` | 23 | Exported Function
`const SecomAvayaEquinoxAdapter::AvayaEquinox::``vftable'{for ``SFAdapterInterface::ISFInterface'}` | 22 | Exported Function
`const SecomAvayaEquinoxAdapter::AvayaEquinox::``vftable'{for ``SecomAvayaEquinoxAdapter::EquinoxClientObserver'}` | 21 | Exported Function
`private: void __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::_HandleEquinoxMsg(struct SecomAvayaEquinoxAdapter::EquinoxMessage const &)` | 33 | Exported Function
`protected: virtual bool __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::offHook(void)` | 51 | Exported Function
`protected: virtual bool __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::muteCall(bool)` | 50 | Exported Function
`protected: virtual bool __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::isRedialNotSupported(void)` | 49 | Exported Function
`protected: virtual class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::getID(void)` | 43 | Exported Function
`protected: virtual bool __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::redial(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 53 | Exported Function
`protected: virtual bool __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::onHook(void)` | 52 | Exported Function
`protected: virtual bool __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::isOffHookNotSupported(void)` | 48 | Exported Function
`protected: virtual bool __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::activeDeviceChangedFromSDK(void)` | 38 | Exported Function
`private: void __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::writeToLog(enum SecomLogManager::LogTypes,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 54 | Exported Function
`private: void __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::_HandleRegistrationMsg(struct SecomAvayaEquinoxAdapter::EquinoxMessage const &)` | 34 | Exported Function
`protected: virtual bool __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::getMuteStatus(void)` | 44 | Exported Function
`protected: virtual bool __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::disconnect(void)` | 41 | Exported Function
`protected: virtual bool __thiscall SecomAvayaEquinoxAdapter::AvayaEquinox::connect(void)` | 39 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `5422C64EF952DE89AE41B042558FFC41`
* Thumbprint: `735C91FA1DB4FFB0CA7FFF980C75AF29F8703050`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Sennheiser Communications A/S, OU=Cloud and Desktop applications, O=Sennheiser Communications A/S, L=Ballerup, S=DK, C=DK

## File Metadata

* Original Filename: AvayaEquinoxAdapter.dll
* Product Name: SenncomSDK
* Company Name: Sennheiser Communications A/S 2016
* File Version: 1.0.0.0
* Product Version: 9.0.1.285
* Language: English (United States)
* Legal Copyright: Sennheiser Communications A/S 2016
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/2a6b3a23d554ac90c29dc53133e860421f596f862bb220d491446d1d102aa565/detection/




MIT License. Copyright (c) 2020 Strontic.


