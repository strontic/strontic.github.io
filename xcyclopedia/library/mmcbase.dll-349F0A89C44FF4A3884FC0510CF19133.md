---
title: mmcbase.dll | MMC Base DLL
excerpt: What is mmcbase.dll?
---

# mmcbase.dll 

* File Path: `C:\Windows\system32\mmcbase.dll`
* Description: MMC Base DLL

## Hashes

Type | Hash
-- | --
MD5 | `349F0A89C44FF4A3884FC0510CF19133`
SHA1 | `A494A988A6BC8D1BE67FED0FB128DC73B1D00A7F`
SHA256 | `4104F925C926006C31955FE88509519CC735B01022648E00A2AC8D6849DDBBCB`
SHA384 | `A4851E5BFFF5100AC404BA459D4B6D4E3D468E814BAFE5655D402EB9BD5805EE558E6B843C91D30B73E41DFF575EF7E1`
SHA512 | `D4D624C2F72720A05D24DB8497F4850569E1C76DE6B5CA0012F2788F6504724F4A74A7CFEB5BAF6B69D50785E6D492004FFD53380ED7BD91118C058886D55607`
SSDEEP | `3072:kBaJiY/v0jpGQ2QXdGG2dFtskSRt+ef64yolajJsFLrCMm0hWacnZg:kk7/v0jYbQtGG2ts5KolajebmMWac`
IMP | `CA39EF89F91DE96094EA4386DEB612F6`
PESHA1 | `5D08601536BD4DC9C2B6E30B073D28F5B824626C`
PE256 | `C81260020C2B91565D5695FF6ECB404291398FAEA0B24F84F59BBADD44EE5B88`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: static struct HWND__ * __ptr64 __cdecl mmcerror::SC::SetModalHWND(struct HWND__ * __ptr64)` | 111 | Exported Function
`public: static struct HWND__ * __ptr64 __cdecl mmcerror::SC::GetModalHWND(void)` | 58 | Exported Function
`public: static unsigned long __cdecl CMMCStrongReferences::Release(void)` | 98 | Exported Function
`public: static unsigned long __cdecl CMMCStrongReferences::AddRef(void)` | 24 | Exported Function
`public: static long __cdecl CMMCWatsonAPI::ExceptionFilter(struct _EXCEPTION_POINTERS * __ptr64,int)` | 31 | Exported Function
`public: static long __cdecl BookKeeping::UnregisterThread(int,unsigned long)` | 122 | Exported Function
`public: static struct HWND__ * __ptr64 __cdecl mmcerror::SC::GetHWnd(void)` | 53 | Exported Function
`public: static struct HINSTANCE__ * __ptr64 __cdecl mmcerror::SC::GetHinst(void)` | 56 | Exported Function
`public: static void __cdecl BookKeeping::InterfaceMethodActivationContextException(int,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,struct _EXCEPTION_POINTERS * __ptr64)` | 68 | Exported Function
`public: static void __cdecl BookKeeping::InterfaceFailure(int,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 67 | Exported Function
`public: static void __cdecl BookKeeping::InterfaceNotFound(int,unsigned short const * __ptr64)` | 70 | Exported Function
`public: static void __cdecl BookKeeping::InterfaceMethodException(int,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,struct _EXCEPTION_POINTERS * __ptr64)` | 69 | Exported Function
`public: static unsigned short const * __ptr64 __cdecl BookKeeping::GetSnapinModuleName(int)` | 61 | Exported Function
`public: static unsigned long __cdecl mmcerror::SC::GetMainThreadID(void)` | 57 | Exported Function
`public: static unsigned short const * __ptr64 __cdecl mmcerror::SC::GetHelpFile(void)` | 54 | Exported Function
`public: static unsigned short const * __ptr64 __cdecl BookKeeping::GetSnapinName(int)` | 62 | Exported Function
`public: static long __cdecl BookKeeping::UnregisterAllSnapinInstanceThreads(int)` | 121 | Exported Function
`public: static int __cdecl BookKeeping::GetNewSnapinInstanceId(void)` | 59 | Exported Function
`public: static class SnapinBookkeepingInfo const & __ptr64 __cdecl BookKeeping::FindSnapin(unsigned short const * __ptr64)` | 38 | Exported Function
`public: static long __cdecl BookKeeping::AddSnapin(unsigned short const * __ptr64,int & __ptr64)` | 25 | Exported Function
`public: static long __cdecl BookKeeping::AddItem(class ItemHandle & __ptr64)` | 23 | Exported Function
`public: static class mmcerror::SC __cdecl CConsoleEventDispatcherProvider::ScSetConsoleEventDispatcher(class CConsoleEventDispatcher * __ptr64)` | 106 | Exported Function
`public: static class mmcerror::SC __cdecl CConsoleEventDispatcherProvider::ScGetConsoleEventDispatcher(class CConsoleEventDispatcher * __ptr64 & __ptr64)` | 105 | Exported Function
`public: static class SnapinBookkeepingInfo const & __ptr64 __cdecl BookKeeping::FindSnapin(struct IUnknown * __ptr64)` | 37 | Exported Function
`public: static class SnapinBookkeepingInfo const & __ptr64 __cdecl BookKeeping::FindSnapin(int)` | 36 | Exported Function
`public: static long __cdecl BookKeeping::RegisterThread(int,int,unsigned long,enum BookKeeping::SnapinThreadFlags)` | 97 | Exported Function
`public: static long __cdecl BookKeeping::LKResult2HRESULT(__int64)` | 80 | Exported Function
`public: static long __cdecl BookKeeping::RemoveItem(void * __ptr64)` | 100 | Exported Function
`public: static long __cdecl BookKeeping::ReleaseSnapinInterface(struct IUnknown * __ptr64,int)` | 99 | Exported Function
`public: static long __cdecl BookKeeping::FindAllSnapinUIThreads(int,unsigned long * __ptr64 * __ptr64,unsigned long * __ptr64)` | 33 | Exported Function
`public: static long __cdecl BookKeeping::DumpWatsonTables(void * __ptr64,unsigned short const * __ptr64,int)` | 29 | Exported Function
`public: static long __cdecl BookKeeping::InitInstance(void)` | 66 | Exported Function
`public: static long __cdecl BookKeeping::FindAllSnapinUIThreads(unsigned long * __ptr64 * __ptr64,unsigned long * __ptr64)` | 34 | Exported Function
`public: void __cdecl mmcerror::SC::SetSnapinName(unsigned short const * __ptr64) __ptr64` | 112 | Exported Function
`public: void __cdecl mmcerror::SC::SetFunctionName(unsigned short const * __ptr64) __ptr64` | 107 | Exported Function
`public: void __cdecl mmcerror::SC::Throw(void) __ptr64` | 114 | Exported Function
`public: void __cdecl mmcerror::SC::Throw(long) __ptr64` | 113 | Exported Function
`public: void __cdecl mmcerror::SC::Clear(void) __ptr64` | 28 | Exported Function
`public: void __cdecl mmcerror::SC::CheckCallingThreadID(void) __ptr64` | 27 | Exported Function
`public: void __cdecl mmcerror::SC::GetErrorMessage(unsigned int,unsigned short * __ptr64)const __ptr64` | 49 | Exported Function
`public: void __cdecl mmcerror::SC::FatalError(void)const __ptr64` | 32 | Exported Function
`void __cdecl FormatErrorString(unsigned short const * __ptr64,class mmcerror::SC,unsigned int,unsigned short * __ptr64,int)` | 42 | Exported Function
`void __cdecl FormatErrorShort(class mmcerror::SC,unsigned int,unsigned short * __ptr64)` | 41 | Exported Function
`void __cdecl TraceSnapinError(unsigned short const * __ptr64,class mmcerror::SC const & __ptr64)` | 118 | Exported Function
`void __cdecl TraceError(unsigned short const * __ptr64,class mmcerror::SC const & __ptr64)` | 117 | Exported Function
`public: void __cdecl mmcerror::SC::TraceAndClear(void) __ptr64` | 116 | Exported Function
`public: void __cdecl mmcerror::SC::Trace_(void)const __ptr64` | 119 | Exported Function
`void __cdecl FormatErrorIds(unsigned int,class mmcerror::SC,unsigned int,unsigned short * __ptr64)` | 40 | Exported Function
`ReportFxSnapinException` | 132 | Exported Function
`public: void __cdecl mmcerror::SC::``default constructor closure'(void) __ptr64` | 22 | Exported Function
`public: static void __cdecl BookKeeping::MMCInterfaceMethodException(int,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,struct _EXCEPTION_POINTERS * __ptr64,enum BookKeeping::_SnapinError)` | 91 | Exported Function
`public: static void __cdecl BookKeeping::MMCInterfaceLeak(int,unsigned short const * __ptr64)` | 90 | Exported Function
`public: static void __cdecl CMMCWatsonAPI::ForceException(int)` | 39 | Exported Function
`public: static void __cdecl BookKeeping::MMCNullInterface(int,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 92 | Exported Function
`public: static void __cdecl BookKeeping::InvalidMMCInterface(int,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 75 | Exported Function
`public: static void __cdecl BookKeeping::InvalidInterface(int,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 74 | Exported Function
`public: static void __cdecl BookKeeping::MMCInterfaceError(int,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 89 | Exported Function
`public: static void __cdecl BookKeeping::InvalidMMCInterfaceRelease(int,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 76 | Exported Function
`public: unsigned short const * __ptr64 __cdecl mmcerror::SC::GetSnapinName(void)const __ptr64` | 63 | Exported Function
`public: unsigned short const * __ptr64 __cdecl mmcerror::SC::GetFunctionName(void)const __ptr64` | 52 | Exported Function
`public: void __cdecl CEventBuffer::Unlock(void) __ptr64` | 120 | Exported Function
`public: void __cdecl CEventBuffer::Lock(void) __ptr64` | 83 | Exported Function
`public: static void __cdecl mmcerror::SC::SetHWnd(struct HWND__ * __ptr64)` | 108 | Exported Function
`public: static void __cdecl mmcerror::SC::SetHinst(struct HINSTANCE__ * __ptr64)` | 109 | Exported Function
`public: unsigned long __cdecl mmcerror::SC::GetHelpID(void) __ptr64` | 55 | Exported Function
`public: static void __cdecl mmcerror::SC::SetMainThreadID(unsigned long)` | 110 | Exported Function
`private: static class CMMCStrongReferences & __ptr64 __cdecl CMMCStrongReferences::GetSingletonObject(void)` | 60 | Exported Function
`private: static class CConsoleEventDispatcher * __ptr64 __ptr64 CConsoleEventDispatcherProvider::s_pDispatcher` | 128 | Exported Function
`private: static struct HWND__ * __ptr64 __ptr64 mmcerror::SC::s_hWnd` | 126 | Exported Function
`private: static struct HINSTANCE__ * __ptr64 __ptr64 mmcerror::SC::s_hInst` | 125 | Exported Function
`private: bool __cdecl CMMCStrongReferences::InternalLastRefReleased(void) __ptr64` | 72 | Exported Function
`private: __cdecl CMMCStrongReferences::CMMCStrongReferences(void) __ptr64` | 4 | Exported Function
`private: enum mmcerror::SC::facility_type __cdecl mmcerror::SC::GetFacility(void)const __ptr64` | 51 | Exported Function
`private: class mmcerror::SC __cdecl CEventBuffer::ScFlushPostponed(void) __ptr64` | 103 | Exported Function
`private: void __cdecl mmcerror::SC::MakeSc(enum mmcerror::SC::facility_type,long) __ptr64` | 95 | Exported Function
`private: unsigned long __cdecl CMMCStrongReferences::InternalRelease(void) __ptr64` | 73 | Exported Function
`public: __cdecl CEventBuffer::CEventBuffer(void) __ptr64` | 3 | Exported Function
`public: __cdecl CEventBuffer::CEventBuffer(class CEventBuffer const & __ptr64) __ptr64` | 2 | Exported Function
`private: static unsigned int mmcerror::SC::s_CallDepth` | 123 | Exported Function
`private: static struct HWND__ * __ptr64 __ptr64 mmcerror::SC::s_hWndModal` | 127 | Exported Function
`private: unsigned long __cdecl CMMCStrongReferences::InternalAddRef(void) __ptr64` | 71 | Exported Function
`private: static unsigned long mmcerror::SC::s_dwMainThreadID` | 124 | Exported Function
`MMCUpdateRegistry` | 93 | Exported Function
`InsideModalLoop` | 130 | Exported Function
`GetStringModule` | 64 | Exported Function
`int __cdecl MMCErrorBox(unsigned int,class mmcerror::SC,unsigned int)` | 85 | Exported Function
`int __cdecl MMCErrorBox(class mmcerror::SC,unsigned int)` | 88 | Exported Function
`EnterModalLoop` | 129 | Exported Function
`class mmcerror::SC __cdecl ScFromMMC(long)` | 104 | Exported Function
`GetEventBuffer` | 50 | Exported Function
`GetComObjectEventSource` | 48 | Exported Function
`long __cdecl HrFromSc(class mmcerror::SC const & __ptr64)` | 65 | Exported Function
`LoadStandardOverlays` | 82 | Exported Function
`MMC_PickIconDlg` | 94 | Exported Function
`long __cdecl SCODEFromSc(class mmcerror::SC const & __ptr64)` | 101 | Exported Function
`int __cdecl MMCErrorBox(unsigned short const * __ptr64,class mmcerror::SC,unsigned int)` | 87 | Exported Function
`int __cdecl MMCErrorBox(unsigned int,unsigned int)` | 84 | Exported Function
`LeaveModalLoop` | 131 | Exported Function
`int __cdecl MMCErrorBox(unsigned short const * __ptr64,unsigned int)` | 86 | Exported Function
`public: class mmcerror::SC __cdecl CEventBuffer::ScEmitOrPostpone(struct IDispatch * __ptr64,long,class ATL::CComVariant * __ptr64,int) __ptr64` | 102 | Exported Function
`public: class mmcerror::SC & __ptr64 __cdecl mmcerror::SC::operator=(long) __ptr64` | 15 | Exported Function
`public: long __cdecl mmcerror::SC::GetCode(void)const __ptr64` | 47 | Exported Function
`public: int __cdecl mmcerror::SC::operator!(void)const __ptr64` | 16 | Exported Function
`public: class mmcerror::SC & __ptr64 __cdecl mmcerror::SC::FromMMC(long) __ptr64` | 44 | Exported Function
`public: class mmcerror::SC & __ptr64 __cdecl mmcerror::SC::FromLastError(void) __ptr64` | 43 | Exported Function
`public: class mmcerror::SC & __ptr64 __cdecl mmcerror::SC::operator=(class mmcerror::SC const & __ptr64) __ptr64` | 14 | Exported Function
`public: class mmcerror::SC & __ptr64 __cdecl mmcerror::SC::FromWin32(long) __ptr64` | 45 | Exported Function
`public: static bool __cdecl CMMCStrongReferences::LastRefReleased(void)` | 81 | Exported Function
`public: static bool __cdecl BookKeeping::FxSnapinException(int,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,int,struct HWND__ * __ptr64)` | 46 | Exported Function
`public: static class ItemHandle * __ptr64 __cdecl BookKeeping::FindItem(void * __ptr64)` | 35 | Exported Function
`public: static bool __cdecl ItemHandle::IsValid(class ItemHandle const * __ptr64)` | 79 | Exported Function
`public: static bool (__cdecl*__cdecl BookKeeping::RegisterSnapinInterfaceErrorHandler(bool (__cdecl*)(class SnapinBookkeepingInfo & __ptr64,enum BookKeeping::_SnapinError,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,struct _EXCEPTION_POINTERS * __ptr64)))(class SnapinBookkeepingInfo & __ptr64,enum BookKeeping::_SnapinError,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,struct _EXCEPTION_POINTERS * __ptr64)` | 96 | Exported Function
`public: long __cdecl mmcerror::SC::ToHr(void)const __ptr64` | 115 | Exported Function
`public: static bool __cdecl BookKeeping::EnableDiagnosticMessageBox(bool)` | 30 | Exported Function
`public: static bool __cdecl BookKeeping::AddSnapinInterface(struct IUnknown * __ptr64,unsigned short const * __ptr64,int & __ptr64)` | 26 | Exported Function
`public: class CMMCStrongReferences & __ptr64 __cdecl CMMCStrongReferences::operator=(class CMMCStrongReferences const & __ptr64) __ptr64` | 13 | Exported Function
`public: __cdecl mmcerror::SC::SC(long) __ptr64` | 6 | Exported Function
`public: __cdecl mmcerror::SC::SC(class mmcerror::SC const & __ptr64) __ptr64` | 5 | Exported Function
`public: bool __cdecl CEventBuffer::IsLocked(void) __ptr64` | 78 | Exported Function
`public: __cdecl mmcerror::SC::~SC(void) __ptr64` | 9 | Exported Function
`public: __cdecl CEventLock<struct AppEvents>::CEventLock<struct AppEvents>(void) __ptr64` | 1 | Exported Function
`public: __cdecl CEventBuffer::~CEventBuffer(void) __ptr64` | 8 | Exported Function
`public: __cdecl mmcerror::SC::operator bool(void)const __ptr64` | 21 | Exported Function
`public: __cdecl CEventLock<struct AppEvents>::~CEventLock<struct AppEvents>(void) __ptr64` | 7 | Exported Function
`public: class CEventBuffer & __ptr64 __cdecl CEventBuffer::operator=(class CEventBuffer const & __ptr64) __ptr64` | 11 | Exported Function
`public: bool __cdecl mmcerror::SC::operator==(long)const __ptr64` | 18 | Exported Function
`public: class CMMCStrongReferences & __ptr64 __cdecl CMMCStrongReferences::operator=(class CMMCStrongReferences && __ptr64) __ptr64` | 12 | Exported Function
`public: class CEventLock<struct AppEvents> & __ptr64 __cdecl CEventLock<struct AppEvents>::operator=(class CEventLock<struct AppEvents> const & __ptr64) __ptr64` | 10 | Exported Function
`public: bool __cdecl mmcerror::SC::operator!=(class mmcerror::SC const & __ptr64)const __ptr64` | 19 | Exported Function
`public: bool __cdecl mmcerror::SC::IsError(void)const __ptr64` | 77 | Exported Function
`public: bool __cdecl mmcerror::SC::operator==(class mmcerror::SC const & __ptr64)const __ptr64` | 17 | Exported Function
`public: bool __cdecl mmcerror::SC::operator!=(long)const __ptr64` | 20 | Exported Function


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/4104f925c926006c31955fe88509519cc735b01022648e00a2ac8d6849ddbbcb/detection/





MIT License. Copyright (c) 2020 Strontic.


