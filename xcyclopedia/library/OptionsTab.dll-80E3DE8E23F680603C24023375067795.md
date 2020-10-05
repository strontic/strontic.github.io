---
title: OptionsTab.dll | OptionsTab Dynamic Link Library
excerpt: What is OptionsTab.dll?
---

# OptionsTab.dll 

* File Path: `C:\Program Files (x86)\Cisco Systems\Cisco Jabber\OptionsTab.dll`
* Description: OptionsTab Dynamic Link Library

## Hashes

Type | Hash
-- | --
MD5 | `80E3DE8E23F680603C24023375067795`
SHA1 | `7FD1A510440280AF1FDF75F1C183A7CDAEB07A2F`
SHA256 | `BEB94718DD3E87CAB01018A8C79B909021B60D0AD4B4049AA5303A8E29B1BC98`
SHA384 | `E850BA1E808B3625048622405302C11B9F285D8191F9008614009EA2272CB1DE6656B931412FBD38D417110D730ECFC7`
SHA512 | `A1A037535E9911E9DA2D8E5CB1E046C6F6F3BA4B76279D8EF63A6F5024E38D4EBAD7383747D75E5D15692ED1377563D06E4F526F9A872F61AB90F08B93E9EE2F`
SSDEEP | `1536:+Um6yfS3AEV6PqpDCUt/f48KM7FUa7njb/Qb2j5Kxte9t6U:+X6yfS33sPYho8vua7gbI5Ku9tR`
IMP | `A62CDABCAAB5C457B86CA29363FDEB99`
PESHA1 | `E1C800E28A04F5F2421129431EDAF04A541538FE`
PE256 | `B4433685A3BC2F23EF1700F3307DFB65358C6CF0DC048A77D0D5A6D99BB81D29`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: virtual long __stdcall OptionsTabPlugin::onDefaultActionRequested(class std::shared_ptr<class JabberSelectionContextStruct>,wchar_t *,bool &)` | 39 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::onCreateTabs(void)` | 38 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::onClosing(void)` | 37 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::onTabDisabled(wchar_t *)` | 42 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::onRegistered(wchar_t *,unsigned int,unsigned int)` | 41 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::onOKPressed(void)` | 40 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::onApplyPressed(void)` | 33 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::onApplicationStateChanged(enum ApplicationState)` | 32 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::logoutRequested(bool *)` | 31 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::onClosed(void)` | 36 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::onCancelPressed(void)` | 35 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::onBroadcastMessageReceived(wchar_t *)` | 34 | Exported Function
`public: virtual unsigned long __stdcall OptionsTabPlugin::Release(void)` | 24 | Exported Function
`public: virtual unsigned long __stdcall OptionsTabPlugin::AddRef(void)` | 20 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::startPlugin(void)` | 48 | Exported Function
`public: virtual void __thiscall ConfigOverride::Set(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> >,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)` | 26 | Exported Function
`public: virtual void __thiscall ConfigOverride::Save(void)` | 25 | Exported Function
`public: virtual void __thiscall ConfigOverride::Init(class CSFUnified::ServiceFactory *)` | 22 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::onTabSelected(wchar_t *)` | 45 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::onTabFocus(wchar_t *)` | 44 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::onTabEnabled(wchar_t *)` | 43 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::QueryInterface(struct _GUID const &,void * *)` | 23 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::processLocalEvent(wchar_t *,unsigned int,long)` | 47 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::onUnRegistered(wchar_t *)` | 46 | Exported Function
`public: __thiscall IOptionsTab::IOptionsTab(class IOptionsTab const &)` | 5 | Exported Function
`public: __thiscall IOptionsTab::IOptionsTab(class IOptionsTab &&)` | 4 | Exported Function
`public: __thiscall ConfigOverride::ConfigOverride(void)` | 3 | Exported Function
`public: __thiscall OptionsTabPlugin::OptionsTabPlugin(long &,wchar_t const *)` | 7 | Exported Function
`public: __thiscall OptionsTabPlugin::OptionsTabPlugin(class OptionsTabPlugin const &)` | 8 | Exported Function
`public: __thiscall IOptionsTab::IOptionsTab(void)` | 6 | Exported Function
`const OptionsTabPlugin::``vftable'{for ``IJabberOptionsWindowTab'}` | 18 | Exported Function
`const IOptionsTab::``vftable'` | 17 | Exported Function
`const ConfigOverride::``vftable'` | 16 | Exported Function
`public: __thiscall ConfigOverride::ConfigOverride(class CSFUnified::ServiceFactory *)` | 2 | Exported Function
`public: __thiscall ConfigOverride::ConfigOverride(class ConfigOverride const &)` | 1 | Exported Function
`const OptionsTabPlugin::``vftable'{for ``IJabberPlugin'}` | 19 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::destroy(bool &)` | 27 | Exported Function
`public: virtual class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __thiscall ConfigOverride::Get(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> >)` | 21 | Exported Function
`public: virtual class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > & __thiscall ConfigOverride::operator[](class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> >)` | 15 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::loggedOut(void)` | 30 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::loggedIn(void)` | 29 | Exported Function
`public: virtual long __stdcall OptionsTabPlugin::initPlugin(struct IPluginRuntime *,class IJabberContext *)` | 28 | Exported Function
`public: class IOptionsTab & __thiscall IOptionsTab::operator=(class IOptionsTab const &)` | 13 | Exported Function
`public: class IOptionsTab & __thiscall IOptionsTab::operator=(class IOptionsTab &&)` | 12 | Exported Function
`public: class ConfigOverride & __thiscall ConfigOverride::operator=(class ConfigOverride const &)` | 11 | Exported Function
`public: virtual __thiscall OptionsTabPlugin::~OptionsTabPlugin(void)` | 10 | Exported Function
`public: virtual __thiscall ConfigOverride::~ConfigOverride(void)` | 9 | Exported Function
`public: class OptionsTabPlugin & __thiscall OptionsTabPlugin::operator=(class OptionsTabPlugin const &)` | 14 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `59C5C9F46EA82C4C743981566B64BD6C`
* Thumbprint: `475DAEE5A6CC149389EFDE176DEA526C627D203A`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA - G2, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Cisco Systems Inc., O=Cisco Systems Inc., L=San Jose, S=California, C=US

## File Metadata

* Original Filename: OptionsTab.dll
* Product Name: 
* Company Name: Cisco Systems, Inc
* File Version: 12.9.2.54247
* Product Version: 12.9.2.54247
* Language: English (United Kingdom)
* Legal Copyright: Copyright (C) 2012-2015 Cisco Systems Inc.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/beb94718dd3e87cab01018a8c79b909021b60d0ad4b4049aa5303a8e29b1bc98/detection/




MIT License. Copyright (c) 2020 Strontic.


