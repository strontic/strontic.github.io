---
title: mmcbase.dll | MMC Base DLL
excerpt: What is mmcbase.dll?
---

# mmcbase.dll 

* File Path: `C:\Windows\SysWOW64\mmcbase.dll`
* Description: MMC Base DLL

## Hashes

Type | Hash
-- | --
MD5 | `886F675E0C5017E33E86371A0C8A168F`
SHA1 | `2395D1ED6335CB471B549ED0BA0242581BD93AA3`
SHA256 | `A43016B92E7A76F8529C420F6E2158ED5A1F5014260BBFA214DB7939F8FAC2FD`
SHA384 | `81986C83705F5268155224264F786316F681E091CF40573A1158398976E876B1726C298A81F1BEA8CA719BD3BEB43EE4`
SHA512 | `DC777BC203716F1794CBA7C40E9BF0277FFC6A3835563CB935606479BCF6BC47FEBB7E62CF0ABF6E476B2B5A59ED3C98EBEE113325F517BBD6A595DDB18E0E79`
SSDEEP | `3072:b+IdFVHkovJJ7jHULuNyW399GBhcAaU8ZF8er+GvRHaSdv:bNZBJ7jHULoyW3n4cw8bPZHaa`
IMP | `D1FC868CBA996F87D1BBC0906C815B2B`
PESHA1 | `2F659683FA32B9237FCAEEF3E7B00DE3B842034D`
PE256 | `ACDE59CAC5CDA24A9F13E5020219F24389E01B390D28D78F923B51EA73CEA0E5`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: static struct HWND__ * __stdcall mmcerror::SC::SetModalHWND(struct HWND__ *)` | 111 | Exported Function
`public: static struct HWND__ * __stdcall mmcerror::SC::GetModalHWND(void)` | 58 | Exported Function
`public: static unsigned long __stdcall CMMCStrongReferences::Release(void)` | 98 | Exported Function
`public: static unsigned long __stdcall CMMCStrongReferences::AddRef(void)` | 24 | Exported Function
`public: static long __stdcall CMMCWatsonAPI::ExceptionFilter(struct _EXCEPTION_POINTERS *,int)` | 31 | Exported Function
`public: static long __stdcall BookKeeping::UnregisterThread(int,unsigned long)` | 122 | Exported Function
`public: static struct HWND__ * __stdcall mmcerror::SC::GetHWnd(void)` | 53 | Exported Function
`public: static struct HINSTANCE__ * __stdcall mmcerror::SC::GetHinst(void)` | 56 | Exported Function
`public: static void __stdcall BookKeeping::InterfaceMethodActivationContextException(int,unsigned short const *,unsigned short const *,unsigned long,struct _EXCEPTION_POINTERS *)` | 68 | Exported Function
`public: static void __stdcall BookKeeping::InterfaceFailure(int,unsigned short const *,unsigned short const *)` | 67 | Exported Function
`public: static void __stdcall BookKeeping::InterfaceNotFound(int,unsigned short const *)` | 70 | Exported Function
`public: static void __stdcall BookKeeping::InterfaceMethodException(int,unsigned short const *,unsigned short const *,unsigned long,struct _EXCEPTION_POINTERS *)` | 69 | Exported Function
`public: static unsigned short const * __stdcall BookKeeping::GetSnapinModuleName(int)` | 61 | Exported Function
`public: static unsigned long __stdcall mmcerror::SC::GetMainThreadID(void)` | 57 | Exported Function
`public: static unsigned short const * __stdcall mmcerror::SC::GetHelpFile(void)` | 54 | Exported Function
`public: static unsigned short const * __stdcall BookKeeping::GetSnapinName(int)` | 62 | Exported Function
`public: static long __stdcall BookKeeping::UnregisterAllSnapinInstanceThreads(int)` | 121 | Exported Function
`public: static int __stdcall BookKeeping::GetNewSnapinInstanceId(void)` | 59 | Exported Function
`public: static class SnapinBookkeepingInfo const & __stdcall BookKeeping::FindSnapin(unsigned short const *)` | 38 | Exported Function
`public: static long __stdcall BookKeeping::AddSnapin(unsigned short const *,int &)` | 25 | Exported Function
`public: static long __stdcall BookKeeping::AddItem(class ItemHandle &)` | 23 | Exported Function
`public: static class mmcerror::SC __stdcall CConsoleEventDispatcherProvider::ScSetConsoleEventDispatcher(class CConsoleEventDispatcher *)` | 106 | Exported Function
`public: static class mmcerror::SC __stdcall CConsoleEventDispatcherProvider::ScGetConsoleEventDispatcher(class CConsoleEventDispatcher * &)` | 105 | Exported Function
`public: static class SnapinBookkeepingInfo const & __stdcall BookKeeping::FindSnapin(struct IUnknown *)` | 37 | Exported Function
`public: static class SnapinBookkeepingInfo const & __stdcall BookKeeping::FindSnapin(int)` | 36 | Exported Function
`public: static long __stdcall BookKeeping::RegisterThread(int,int,unsigned long,enum BookKeeping::SnapinThreadFlags)` | 97 | Exported Function
`public: static long __stdcall BookKeeping::LKResult2HRESULT(long)` | 80 | Exported Function
`public: static long __stdcall BookKeeping::RemoveItem(void *)` | 100 | Exported Function
`public: static long __stdcall BookKeeping::ReleaseSnapinInterface(struct IUnknown *,int)` | 99 | Exported Function
`public: static long __stdcall BookKeeping::FindAllSnapinUIThreads(int,unsigned long * *,unsigned long *)` | 33 | Exported Function
`public: static long __stdcall BookKeeping::DumpWatsonTables(void *,unsigned short const *,int)` | 29 | Exported Function
`public: static long __stdcall BookKeeping::InitInstance(void)` | 66 | Exported Function
`public: static long __stdcall BookKeeping::FindAllSnapinUIThreads(unsigned long * *,unsigned long *)` | 34 | Exported Function
`public: void __thiscall mmcerror::SC::SetSnapinName(unsigned short const *)` | 112 | Exported Function
`public: void __thiscall mmcerror::SC::SetFunctionName(unsigned short const *)` | 107 | Exported Function
`public: void __thiscall mmcerror::SC::Throw(void)` | 114 | Exported Function
`public: void __thiscall mmcerror::SC::Throw(long)` | 113 | Exported Function
`public: void __thiscall mmcerror::SC::Clear(void)` | 28 | Exported Function
`public: void __thiscall mmcerror::SC::CheckCallingThreadID(void)` | 27 | Exported Function
`public: void __thiscall mmcerror::SC::GetErrorMessage(unsigned int,unsigned short *)const ` | 49 | Exported Function
`public: void __thiscall mmcerror::SC::FatalError(void)const ` | 32 | Exported Function
`void __stdcall FormatErrorString(unsigned short const *,class mmcerror::SC,unsigned int,unsigned short *,int)` | 42 | Exported Function
`void __stdcall FormatErrorShort(class mmcerror::SC,unsigned int,unsigned short *)` | 41 | Exported Function
`void __stdcall TraceSnapinError(unsigned short const *,class mmcerror::SC const &)` | 118 | Exported Function
`void __stdcall TraceError(unsigned short const *,class mmcerror::SC const &)` | 117 | Exported Function
`public: void __thiscall mmcerror::SC::TraceAndClear(void)` | 116 | Exported Function
`public: void __thiscall mmcerror::SC::Trace_(void)const ` | 119 | Exported Function
`void __stdcall FormatErrorIds(unsigned int,class mmcerror::SC,unsigned int,unsigned short *)` | 40 | Exported Function
`ReportFxSnapinException` | 132 | Exported Function
`public: void __thiscall mmcerror::SC::``default constructor closure'(void)` | 22 | Exported Function
`public: static void __stdcall BookKeeping::MMCInterfaceMethodException(int,unsigned short const *,unsigned short const *,unsigned long,struct _EXCEPTION_POINTERS *,enum BookKeeping::_SnapinError)` | 91 | Exported Function
`public: static void __stdcall BookKeeping::MMCInterfaceLeak(int,unsigned short const *)` | 90 | Exported Function
`public: static void __stdcall CMMCWatsonAPI::ForceException(int)` | 39 | Exported Function
`public: static void __stdcall BookKeeping::MMCNullInterface(int,unsigned short const *,unsigned short const *)` | 92 | Exported Function
`public: static void __stdcall BookKeeping::InvalidMMCInterface(int,unsigned short const *,unsigned short const *)` | 75 | Exported Function
`public: static void __stdcall BookKeeping::InvalidInterface(int,unsigned short const *,unsigned short const *)` | 74 | Exported Function
`public: static void __stdcall BookKeeping::MMCInterfaceError(int,unsigned short const *,unsigned short const *)` | 89 | Exported Function
`public: static void __stdcall BookKeeping::InvalidMMCInterfaceRelease(int,unsigned short const *,unsigned short const *)` | 76 | Exported Function
`public: unsigned short const * __thiscall mmcerror::SC::GetSnapinName(void)const ` | 63 | Exported Function
`public: unsigned short const * __thiscall mmcerror::SC::GetFunctionName(void)const ` | 52 | Exported Function
`public: void __thiscall CEventBuffer::Unlock(void)` | 120 | Exported Function
`public: void __thiscall CEventBuffer::Lock(void)` | 83 | Exported Function
`public: static void __stdcall mmcerror::SC::SetHWnd(struct HWND__ *)` | 108 | Exported Function
`public: static void __stdcall mmcerror::SC::SetHinst(struct HINSTANCE__ *)` | 109 | Exported Function
`public: unsigned long __thiscall mmcerror::SC::GetHelpID(void)` | 55 | Exported Function
`public: static void __stdcall mmcerror::SC::SetMainThreadID(unsigned long)` | 110 | Exported Function
`private: static class CMMCStrongReferences & __stdcall CMMCStrongReferences::GetSingletonObject(void)` | 60 | Exported Function
`private: static class CConsoleEventDispatcher * CConsoleEventDispatcherProvider::s_pDispatcher` | 128 | Exported Function
`private: static struct HWND__ * mmcerror::SC::s_hWnd` | 126 | Exported Function
`private: static struct HINSTANCE__ * mmcerror::SC::s_hInst` | 125 | Exported Function
`private: bool __thiscall CMMCStrongReferences::InternalLastRefReleased(void)` | 72 | Exported Function
`private: __thiscall CMMCStrongReferences::CMMCStrongReferences(void)` | 4 | Exported Function
`private: enum mmcerror::SC::facility_type __thiscall mmcerror::SC::GetFacility(void)const ` | 51 | Exported Function
`private: class mmcerror::SC __thiscall CEventBuffer::ScFlushPostponed(void)` | 103 | Exported Function
`private: void __thiscall mmcerror::SC::MakeSc(enum mmcerror::SC::facility_type,long)` | 95 | Exported Function
`private: unsigned long __thiscall CMMCStrongReferences::InternalRelease(void)` | 73 | Exported Function
`public: __thiscall CEventBuffer::CEventBuffer(void)` | 3 | Exported Function
`public: __thiscall CEventBuffer::CEventBuffer(class CEventBuffer const &)` | 2 | Exported Function
`private: static unsigned int mmcerror::SC::s_CallDepth` | 123 | Exported Function
`private: static struct HWND__ * mmcerror::SC::s_hWndModal` | 127 | Exported Function
`private: unsigned long __thiscall CMMCStrongReferences::InternalAddRef(void)` | 71 | Exported Function
`private: static unsigned long mmcerror::SC::s_dwMainThreadID` | 124 | Exported Function
`MMCUpdateRegistry` | 93 | Exported Function
`InsideModalLoop` | 130 | Exported Function
`GetStringModule` | 64 | Exported Function
`int __stdcall MMCErrorBox(unsigned int,class mmcerror::SC,unsigned int)` | 85 | Exported Function
`int __stdcall MMCErrorBox(class mmcerror::SC,unsigned int)` | 88 | Exported Function
`EnterModalLoop` | 129 | Exported Function
`class mmcerror::SC __stdcall ScFromMMC(long)` | 104 | Exported Function
`GetEventBuffer` | 50 | Exported Function
`GetComObjectEventSource` | 48 | Exported Function
`long __stdcall HrFromSc(class mmcerror::SC const &)` | 65 | Exported Function
`LoadStandardOverlays` | 82 | Exported Function
`MMC_PickIconDlg` | 94 | Exported Function
`long __stdcall SCODEFromSc(class mmcerror::SC const &)` | 101 | Exported Function
`int __stdcall MMCErrorBox(unsigned short const *,class mmcerror::SC,unsigned int)` | 87 | Exported Function
`int __stdcall MMCErrorBox(unsigned int,unsigned int)` | 84 | Exported Function
`LeaveModalLoop` | 131 | Exported Function
`int __stdcall MMCErrorBox(unsigned short const *,unsigned int)` | 86 | Exported Function
`public: class mmcerror::SC __thiscall CEventBuffer::ScEmitOrPostpone(struct IDispatch *,long,class ATL::CComVariant *,int)` | 102 | Exported Function
`public: class mmcerror::SC & __thiscall mmcerror::SC::operator=(long)` | 15 | Exported Function
`public: long __thiscall mmcerror::SC::GetCode(void)const ` | 47 | Exported Function
`public: int __thiscall mmcerror::SC::operator!(void)const ` | 16 | Exported Function
`public: class mmcerror::SC & __thiscall mmcerror::SC::FromMMC(long)` | 44 | Exported Function
`public: class mmcerror::SC & __thiscall mmcerror::SC::FromLastError(void)` | 43 | Exported Function
`public: class mmcerror::SC & __thiscall mmcerror::SC::operator=(class mmcerror::SC const &)` | 14 | Exported Function
`public: class mmcerror::SC & __thiscall mmcerror::SC::FromWin32(long)` | 45 | Exported Function
`public: static bool __stdcall CMMCStrongReferences::LastRefReleased(void)` | 81 | Exported Function
`public: static bool __stdcall BookKeeping::FxSnapinException(int,unsigned short const *,unsigned short const *,unsigned short const *,unsigned short const *,int,struct HWND__ *)` | 46 | Exported Function
`public: static class ItemHandle * __stdcall BookKeeping::FindItem(void *)` | 35 | Exported Function
`public: static bool __stdcall ItemHandle::IsValid(class ItemHandle const *)` | 79 | Exported Function
`public: static bool (__stdcall*__stdcall BookKeeping::RegisterSnapinInterfaceErrorHandler(bool (__stdcall*)(class SnapinBookkeepingInfo &,enum BookKeeping::_SnapinError,unsigned short const *,unsigned short const *,unsigned short const *,unsigned short const *,unsigned long,struct _EXCEPTION_POINTERS *)))(class SnapinBookkeepingInfo &,enum BookKeeping::_SnapinError,unsigned short const *,unsigned short const *,unsigned short const *,unsigned short const *,unsigned long,struct _EXCEPTION_POINTERS *)` | 96 | Exported Function
`public: long __thiscall mmcerror::SC::ToHr(void)const ` | 115 | Exported Function
`public: static bool __stdcall BookKeeping::EnableDiagnosticMessageBox(bool)` | 30 | Exported Function
`public: static bool __stdcall BookKeeping::AddSnapinInterface(struct IUnknown *,unsigned short const *,int &)` | 26 | Exported Function
`public: class CMMCStrongReferences & __thiscall CMMCStrongReferences::operator=(class CMMCStrongReferences const &)` | 13 | Exported Function
`public: __thiscall mmcerror::SC::SC(long)` | 6 | Exported Function
`public: __thiscall mmcerror::SC::SC(class mmcerror::SC const &)` | 5 | Exported Function
`public: bool __thiscall CEventBuffer::IsLocked(void)` | 78 | Exported Function
`public: __thiscall mmcerror::SC::~SC(void)` | 9 | Exported Function
`public: __thiscall CEventLock<struct AppEvents>::CEventLock<struct AppEvents>(void)` | 1 | Exported Function
`public: __thiscall CEventBuffer::~CEventBuffer(void)` | 8 | Exported Function
`public: __thiscall mmcerror::SC::operator bool(void)const ` | 21 | Exported Function
`public: __thiscall CEventLock<struct AppEvents>::~CEventLock<struct AppEvents>(void)` | 7 | Exported Function
`public: class CEventBuffer & __thiscall CEventBuffer::operator=(class CEventBuffer const &)` | 11 | Exported Function
`public: bool __thiscall mmcerror::SC::operator==(long)const ` | 18 | Exported Function
`public: class CMMCStrongReferences & __thiscall CMMCStrongReferences::operator=(class CMMCStrongReferences &&)` | 12 | Exported Function
`public: class CEventLock<struct AppEvents> & __thiscall CEventLock<struct AppEvents>::operator=(class CEventLock<struct AppEvents> const &)` | 10 | Exported Function
`public: bool __thiscall mmcerror::SC::operator!=(class mmcerror::SC const &)const ` | 19 | Exported Function
`public: bool __thiscall mmcerror::SC::IsError(void)const ` | 77 | Exported Function
`public: bool __thiscall mmcerror::SC::operator==(class mmcerror::SC const &)const ` | 17 | Exported Function
`public: bool __thiscall mmcerror::SC::operator!=(long)const ` | 20 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mmcbase.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/a43016b92e7a76f8529c420f6e2158ed5a1f5014260bbfa214db7939f8fac2fd/detection/





MIT License. Copyright (c) 2020 Strontic.


