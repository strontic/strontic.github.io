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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`class mmcerror::SC __stdcall ScFromMMC(long)` | 104 (0x68) | Exported Function | 0x100123a0 | 0x000123a0
`public: static void __stdcall BookKeeping::InterfaceMethodActivationContextException(int,unsigned short const *,unsigned short const *,unsigned long,struct _EXCEPTION_POINTERS *)` | 68 (0x44) | Exported Function | 0x10013eb0 | 0x00013eb0
`public: static void __stdcall BookKeeping::InterfaceFailure(int,unsigned short const *,unsigned short const *)` | 67 (0x43) | Exported Function | 0x10013e80 | 0x00013e80
`public: static unsigned short const * __stdcall mmcerror::SC::GetHelpFile(void)` | 54 (0x36) | Exported Function | 0x10017e10 | 0x00017e10
`public: static unsigned short const * __stdcall BookKeeping::GetSnapinName(int)` | 62 (0x3e) | Exported Function | 0x10009dd0 | 0x00009dd0
`public: static unsigned short const * __stdcall BookKeeping::GetSnapinModuleName(int)` | 61 (0x3d) | Exported Function | 0x10013e00 | 0x00013e00
`public: static unsigned long __stdcall mmcerror::SC::GetMainThreadID(void)` | 57 (0x39) | Exported Function | 0x10012360 | 0x00012360
`public: static unsigned long __stdcall CMMCStrongReferences::Release(void)` | 98 (0x62) | Exported Function | 0x10017140 | 0x00017140
`public: static unsigned long __stdcall CMMCStrongReferences::AddRef(void)` | 24 (0x18) | Exported Function | 0x100170c0 | 0x000170c0
`public: static struct HWND__ * __stdcall mmcerror::SC::SetModalHWND(struct HWND__ *)` | 111 (0x6f) | Exported Function | 0x10018180 | 0x00018180
`public: static struct HWND__ * __stdcall mmcerror::SC::GetModalHWND(void)` | 58 (0x3a) | Exported Function | 0x10017e40 | 0x00017e40
`public: static struct HWND__ * __stdcall mmcerror::SC::GetHWnd(void)` | 53 (0x35) | Exported Function | 0x1000b3e0 | 0x0000b3e0
`public: static struct HINSTANCE__ * __stdcall mmcerror::SC::GetHinst(void)` | 56 (0x38) | Exported Function | 0x1000b0f0 | 0x0000b0f0
`public: static long __stdcall CMMCWatsonAPI::ExceptionFilter(struct _EXCEPTION_POINTERS *,int)` | 31 (0x1f) | Exported Function | 0x100167e0 | 0x000167e0
`public: static long __stdcall BookKeeping::UnregisterThread(int,unsigned long)` | 122 (0x7a) | Exported Function | 0x10014620 | 0x00014620
`public: static long __stdcall BookKeeping::UnregisterAllSnapinInstanceThreads(int)` | 121 (0x79) | Exported Function | 0x10005d90 | 0x00005d90
`public: static long __stdcall BookKeeping::RemoveItem(void *)` | 100 (0x64) | Exported Function | 0x10007cb0 | 0x00007cb0
`public: static long __stdcall BookKeeping::ReleaseSnapinInterface(struct IUnknown *,int)` | 99 (0x63) | Exported Function | 0x10007d10 | 0x00007d10
`public: static long __stdcall BookKeeping::RegisterThread(int,int,unsigned long,enum BookKeeping::SnapinThreadFlags)` | 97 (0x61) | Exported Function | 0x10005d50 | 0x00005d50
`public: static long __stdcall BookKeeping::LKResult2HRESULT(long)` | 80 (0x50) | Exported Function | 0x100081e0 | 0x000081e0
`public: static long __stdcall BookKeeping::InitInstance(void)` | 66 (0x42) | Exported Function | 0x10008220 | 0x00008220
`public: static long __stdcall BookKeeping::FindAllSnapinUIThreads(unsigned long * *,unsigned long *)` | 34 (0x22) | Exported Function | 0x100070d0 | 0x000070d0
`public: static long __stdcall BookKeeping::FindAllSnapinUIThreads(int,unsigned long * *,unsigned long *)` | 33 (0x21) | Exported Function | 0x10013c50 | 0x00013c50
`public: static long __stdcall BookKeeping::DumpWatsonTables(void *,unsigned short const *,int)` | 29 (0x1d) | Exported Function | 0x10013a70 | 0x00013a70
`public: static long __stdcall BookKeeping::AddSnapin(unsigned short const *,int &)` | 25 (0x19) | Exported Function | 0x10007830 | 0x00007830
`public: static long __stdcall BookKeeping::AddItem(class ItemHandle &)` | 23 (0x17) | Exported Function | 0x10007bd0 | 0x00007bd0
`public: static int __stdcall BookKeeping::GetNewSnapinInstanceId(void)` | 59 (0x3b) | Exported Function | 0x1000b340 | 0x0000b340
`public: static class SnapinBookkeepingInfo const & __stdcall BookKeeping::FindSnapin(unsigned short const *)` | 38 (0x26) | Exported Function | 0x10013d10 | 0x00013d10
`public: static class SnapinBookkeepingInfo const & __stdcall BookKeeping::FindSnapin(struct IUnknown *)` | 37 (0x25) | Exported Function | 0x10013cf0 | 0x00013cf0
`public: static class SnapinBookkeepingInfo const & __stdcall BookKeeping::FindSnapin(int)` | 36 (0x24) | Exported Function | 0x10013cd0 | 0x00013cd0
`public: static void __stdcall BookKeeping::InterfaceMethodException(int,unsigned short const *,unsigned short const *,unsigned long,struct _EXCEPTION_POINTERS *)` | 69 (0x45) | Exported Function | 0x10013f20 | 0x00013f20
`public: static class mmcerror::SC __stdcall CConsoleEventDispatcherProvider::ScSetConsoleEventDispatcher(class CConsoleEventDispatcher *)` | 106 (0x6a) | Exported Function | 0x1000b0c0 | 0x0000b0c0
`public: static void __stdcall BookKeeping::InterfaceNotFound(int,unsigned short const *)` | 70 (0x46) | Exported Function | 0x10013f90 | 0x00013f90
`public: static void __stdcall BookKeeping::InvalidMMCInterface(int,unsigned short const *,unsigned short const *)` | 75 (0x4b) | Exported Function | 0x10013ff0 | 0x00013ff0
`void __stdcall FormatErrorString(unsigned short const *,class mmcerror::SC,unsigned int,unsigned short *,int)` | 42 (0x2a) | Exported Function | 0x10017c90 | 0x00017c90
`void __stdcall FormatErrorShort(class mmcerror::SC,unsigned int,unsigned short *)` | 41 (0x29) | Exported Function | 0x10017c40 | 0x00017c40
`void __stdcall FormatErrorIds(unsigned int,class mmcerror::SC,unsigned int,unsigned short *)` | 40 (0x28) | Exported Function | 0x10017ba0 | 0x00017ba0
`ReportFxSnapinException` | 132 (0x84) | Exported Function | 0x100146f0 | 0x000146f0
`public: void __thiscall mmcerror::SC::TraceAndClear(void)` | 116 (0x74) | Exported Function | 0x1000a200 | 0x0000a200
`public: void __thiscall mmcerror::SC::Trace_(void)const ` | 119 (0x77) | Exported Function | 0x1000a220 | 0x0000a220
`public: void __thiscall mmcerror::SC::Throw(void)` | 114 (0x72) | Exported Function | 0x100181c0 | 0x000181c0
`public: void __thiscall mmcerror::SC::Throw(long)` | 113 (0x71) | Exported Function | 0x100181a0 | 0x000181a0
`public: void __thiscall mmcerror::SC::SetSnapinName(unsigned short const *)` | 112 (0x70) | Exported Function | 0x1000a880 | 0x0000a880
`public: void __thiscall mmcerror::SC::SetFunctionName(unsigned short const *)` | 107 (0x6b) | Exported Function | 0x1000a270 | 0x0000a270
`public: void __thiscall mmcerror::SC::GetErrorMessage(unsigned int,unsigned short *)const ` | 49 (0x31) | Exported Function | 0x10017d00 | 0x00017d00
`public: void __thiscall mmcerror::SC::FatalError(void)const ` | 32 (0x20) | Exported Function | 0x10017b70 | 0x00017b70
`public: void __thiscall mmcerror::SC::Clear(void)` | 28 (0x1c) | Exported Function | 0x1000a850 | 0x0000a850
`public: void __thiscall mmcerror::SC::CheckCallingThreadID(void)` | 27 (0x1b) | Exported Function | 0x1000a7f0 | 0x0000a7f0
`public: void __thiscall mmcerror::SC::``default constructor closure'(void)` | 22 (0x16) | Exported Function | 0x100122f0 | 0x000122f0
`public: void __thiscall CEventBuffer::Unlock(void)` | 120 (0x78) | Exported Function | 0x1000d820 | 0x0000d820
`public: void __thiscall CEventBuffer::Lock(void)` | 83 (0x53) | Exported Function | 0x10017730 | 0x00017730
`public: unsigned short const * __thiscall mmcerror::SC::GetSnapinName(void)const ` | 63 (0x3f) | Exported Function | 0x10012370 | 0x00012370
`public: unsigned short const * __thiscall mmcerror::SC::GetFunctionName(void)const ` | 52 (0x34) | Exported Function | 0x10012350 | 0x00012350
`public: unsigned long __thiscall mmcerror::SC::GetHelpID(void)` | 55 (0x37) | Exported Function | 0x1000b550 | 0x0000b550
`public: static void __stdcall mmcerror::SC::SetMainThreadID(unsigned long)` | 110 (0x6e) | Exported Function | 0x1000b380 | 0x0000b380
`public: static void __stdcall mmcerror::SC::SetHWnd(struct HWND__ *)` | 108 (0x6c) | Exported Function | 0x1000b3a0 | 0x0000b3a0
`public: static void __stdcall mmcerror::SC::SetHinst(struct HINSTANCE__ *)` | 109 (0x6d) | Exported Function | 0x1000b3c0 | 0x0000b3c0
`public: static void __stdcall CMMCWatsonAPI::ForceException(int)` | 39 (0x27) | Exported Function | 0x10016920 | 0x00016920
`public: static void __stdcall BookKeeping::MMCNullInterface(int,unsigned short const *,unsigned short const *)` | 92 (0x5c) | Exported Function | 0x10014120 | 0x00014120
`public: static void __stdcall BookKeeping::MMCInterfaceMethodException(int,unsigned short const *,unsigned short const *,unsigned long,struct _EXCEPTION_POINTERS *,enum BookKeeping::_SnapinError)` | 91 (0x5b) | Exported Function | 0x100140b0 | 0x000140b0
`public: static void __stdcall BookKeeping::MMCInterfaceLeak(int,unsigned short const *)` | 90 (0x5a) | Exported Function | 0x10014080 | 0x00014080
`public: static void __stdcall BookKeeping::MMCInterfaceError(int,unsigned short const *,unsigned short const *)` | 89 (0x59) | Exported Function | 0x10014050 | 0x00014050
`public: static void __stdcall BookKeeping::InvalidMMCInterfaceRelease(int,unsigned short const *,unsigned short const *)` | 76 (0x4c) | Exported Function | 0x10014020 | 0x00014020
`public: static void __stdcall BookKeeping::InvalidInterface(int,unsigned short const *,unsigned short const *)` | 74 (0x4a) | Exported Function | 0x10013fc0 | 0x00013fc0
`public: static class mmcerror::SC __stdcall CConsoleEventDispatcherProvider::ScGetConsoleEventDispatcher(class CConsoleEventDispatcher * &)` | 105 (0x69) | Exported Function | 0x10017160 | 0x00017160
`public: static class ItemHandle * __stdcall BookKeeping::FindItem(void *)` | 35 (0x23) | Exported Function | 0x1000a2f0 | 0x0000a2f0
`public: static bool __stdcall ItemHandle::IsValid(class ItemHandle const *)` | 79 (0x4f) | Exported Function | 0x10015550 | 0x00015550
`private: unsigned long __thiscall CMMCStrongReferences::InternalRelease(void)` | 73 (0x49) | Exported Function | 0x10017110 | 0x00017110
`private: unsigned long __thiscall CMMCStrongReferences::InternalAddRef(void)` | 71 (0x47) | Exported Function | 0x100170f0 | 0x000170f0
`private: static unsigned long mmcerror::SC::s_dwMainThreadID` | 124 (0x7c) | Exported Function | 0x1001f700 | 0x0001f700
`private: static unsigned int mmcerror::SC::s_CallDepth` | 123 (0x7b) | Exported Function | 0x100227fc | 0x000227fc
`private: static struct HWND__ * mmcerror::SC::s_hWndModal` | 127 (0x7f) | Exported Function | 0x10022880 | 0x00022880
`private: static struct HWND__ * mmcerror::SC::s_hWnd` | 126 (0x7e) | Exported Function | 0x100227f8 | 0x000227f8
`private: static struct HINSTANCE__ * mmcerror::SC::s_hInst` | 125 (0x7d) | Exported Function | 0x100227f4 | 0x000227f4
`private: static class CMMCStrongReferences & __stdcall CMMCStrongReferences::GetSingletonObject(void)` | 60 (0x3c) | Exported Function | 0x100170e0 | 0x000170e0
`private: static class CConsoleEventDispatcher * CConsoleEventDispatcherProvider::s_pDispatcher` | 128 (0x80) | Exported Function | 0x1001fb84 | 0x0001fb84
`private: enum mmcerror::SC::facility_type __thiscall mmcerror::SC::GetFacility(void)const ` | 51 (0x33) | Exported Function | 0x10012340 | 0x00012340
`private: class mmcerror::SC __thiscall CEventBuffer::ScFlushPostponed(void)` | 103 (0x67) | Exported Function | 0x1000a000 | 0x0000a000
`private: bool __thiscall CMMCStrongReferences::InternalLastRefReleased(void)` | 72 (0x48) | Exported Function | 0x10017100 | 0x00017100
`private: __thiscall CMMCStrongReferences::CMMCStrongReferences(void)` | 4 (0x4) | Exported Function | 0x10017030 | 0x00017030
`MMCUpdateRegistry` | 93 (0x5d) | Exported Function | 0x10018d20 | 0x00018d20
`MMC_PickIconDlg` | 94 (0x5e) | Exported Function | 0x1001a320 | 0x0001a320
`long __stdcall SCODEFromSc(class mmcerror::SC const &)` | 101 (0x65) | Exported Function | 0x1000a5b0 | 0x0000a5b0
`long __stdcall HrFromSc(class mmcerror::SC const &)` | 65 (0x41) | Exported Function | 0x1000a5b0 | 0x0000a5b0
`LoadStandardOverlays` | 82 (0x52) | Exported Function | 0x1000a640 | 0x0000a640
`LeaveModalLoop` | 131 (0x83) | Exported Function | 0x1001ad50 | 0x0001ad50
`int __stdcall MMCErrorBox(unsigned short const *,unsigned int)` | 86 (0x56) | Exported Function | 0x10017fa0 | 0x00017fa0
`int __stdcall MMCErrorBox(unsigned short const *,class mmcerror::SC,unsigned int)` | 87 (0x57) | Exported Function | 0x10018060 | 0x00018060
`int __stdcall MMCErrorBox(unsigned int,unsigned int)` | 84 (0x54) | Exported Function | 0x10017e50 | 0x00017e50
`int __stdcall MMCErrorBox(unsigned int,class mmcerror::SC,unsigned int)` | 85 (0x55) | Exported Function | 0x10017ee0 | 0x00017ee0
`int __stdcall MMCErrorBox(class mmcerror::SC,unsigned int)` | 88 (0x58) | Exported Function | 0x100180f0 | 0x000180f0
`InsideModalLoop` | 130 (0x82) | Exported Function | 0x1001ac90 | 0x0001ac90
`GetStringModule` | 64 (0x40) | Exported Function | 0x1000b0f0 | 0x0000b0f0
`GetEventBuffer` | 50 (0x32) | Exported Function | 0x10009f80 | 0x00009f80
`GetComObjectEventSource` | 48 (0x30) | Exported Function | 0x1000ae60 | 0x0000ae60
`EnterModalLoop` | 129 (0x81) | Exported Function | 0x1001abf0 | 0x0001abf0
`private: void __thiscall mmcerror::SC::MakeSc(enum mmcerror::SC::facility_type,long)` | 95 (0x5f) | Exported Function | 0x10012380 | 0x00012380
`public: __thiscall CEventBuffer::CEventBuffer(class CEventBuffer const &)` | 2 (0x2) | Exported Function | 0x10017320 | 0x00017320
`public: __thiscall CEventBuffer::CEventBuffer(void)` | 3 (0x3) | Exported Function | 0x10017350 | 0x00017350
`public: __thiscall CEventBuffer::~CEventBuffer(void)` | 8 (0x8) | Exported Function | 0x1000b360 | 0x0000b360
`public: static bool __stdcall CMMCStrongReferences::LastRefReleased(void)` | 81 (0x51) | Exported Function | 0x10017130 | 0x00017130
`public: static bool __stdcall BookKeeping::FxSnapinException(int,unsigned short const *,unsigned short const *,unsigned short const *,unsigned short const *,int,struct HWND__ *)` | 46 (0x2e) | Exported Function | 0x10013d30 | 0x00013d30
`public: static bool __stdcall BookKeeping::EnableDiagnosticMessageBox(bool)` | 30 (0x1e) | Exported Function | 0x10013c30 | 0x00013c30
`public: static bool __stdcall BookKeeping::AddSnapinInterface(struct IUnknown *,unsigned short const *,int &)` | 26 (0x1a) | Exported Function | 0x10007e10 | 0x00007e10
`public: static bool (__stdcall*__stdcall BookKeeping::RegisterSnapinInterfaceErrorHandler(bool (__stdcall*)(class SnapinBookkeepingInfo &,enum BookKeeping::_SnapinError,unsigned short const *,unsigned short const *,unsigned short const *,unsigned short const *,unsigned long,struct _EXCEPTION_POINTERS *)))(class SnapinBookkeepingInfo &,enum BookKeeping::_SnapinError,unsigned short const *,unsigned short const *,unsigned short const *,unsigned short const *,unsigned long,struct _EXCEPTION_POINTERS *)` | 96 (0x60) | Exported Function | 0x10014150 | 0x00014150
`public: long __thiscall mmcerror::SC::ToHr(void)const ` | 115 (0x73) | Exported Function | 0x1000a5d0 | 0x0000a5d0
`public: long __thiscall mmcerror::SC::GetCode(void)const ` | 47 (0x2f) | Exported Function | 0x10012330 | 0x00012330
`public: int __thiscall mmcerror::SC::operator!(void)const ` | 16 (0x10) | Exported Function | 0x1000a1e0 | 0x0000a1e0
`public: class mmcerror::SC __thiscall CEventBuffer::ScEmitOrPostpone(struct IDispatch *,long,class ATL::CComVariant *,int)` | 102 (0x66) | Exported Function | 0x10017740 | 0x00017740
`public: class mmcerror::SC & __thiscall mmcerror::SC::operator=(long)` | 15 (0xf) | Exported Function | 0x1000a5f0 | 0x0000a5f0
`public: class mmcerror::SC & __thiscall mmcerror::SC::operator=(class mmcerror::SC const &)` | 14 (0xe) | Exported Function | 0x1000a550 | 0x0000a550
`public: class mmcerror::SC & __thiscall mmcerror::SC::FromWin32(long)` | 45 (0x2d) | Exported Function | 0x1000a7d0 | 0x0000a7d0
`public: class mmcerror::SC & __thiscall mmcerror::SC::FromMMC(long)` | 44 (0x2c) | Exported Function | 0x10012310 | 0x00012310
`public: class mmcerror::SC & __thiscall mmcerror::SC::FromLastError(void)` | 43 (0x2b) | Exported Function | 0x10017cc0 | 0x00017cc0
`void __stdcall TraceError(unsigned short const *,class mmcerror::SC const &)` | 117 (0x75) | Exported Function | 0x10009da0 | 0x00009da0
`public: class CMMCStrongReferences & __thiscall CMMCStrongReferences::operator=(class CMMCStrongReferences const &)` | 13 (0xd) | Exported Function | 0x1000a550 | 0x0000a550
`public: class CEventLock<struct AppEvents> & __thiscall CEventLock<struct AppEvents>::operator=(class CEventLock<struct AppEvents> const &)` | 10 (0xa) | Exported Function | 0x10017440 | 0x00017440
`public: class CEventBuffer & __thiscall CEventBuffer::operator=(class CEventBuffer const &)` | 11 (0xb) | Exported Function | 0x100176b0 | 0x000176b0
`public: bool __thiscall mmcerror::SC::operator==(long)const ` | 18 (0x12) | Exported Function | 0x1000a8c0 | 0x0000a8c0
`public: bool __thiscall mmcerror::SC::operator==(class mmcerror::SC const &)const ` | 17 (0x11) | Exported Function | 0x1000a820 | 0x0000a820
`public: bool __thiscall mmcerror::SC::operator!=(long)const ` | 20 (0x14) | Exported Function | 0x1000a8a0 | 0x0000a8a0
`public: bool __thiscall mmcerror::SC::operator!=(class mmcerror::SC const &)const ` | 19 (0x13) | Exported Function | 0x100122d0 | 0x000122d0
`public: bool __thiscall mmcerror::SC::IsError(void)const ` | 77 (0x4d) | Exported Function | 0x1000a240 | 0x0000a240
`public: bool __thiscall CEventBuffer::IsLocked(void)` | 78 (0x4e) | Exported Function | 0x10017720 | 0x00017720
`public: __thiscall mmcerror::SC::~SC(void)` | 9 (0x9) | Exported Function | 0x10009d60 | 0x00009d60
`public: __thiscall mmcerror::SC::SC(long)` | 6 (0x6) | Exported Function | 0x1000a2c0 | 0x0000a2c0
`public: __thiscall mmcerror::SC::SC(class mmcerror::SC const &)` | 5 (0x5) | Exported Function | 0x1000a610 | 0x0000a610
`public: __thiscall mmcerror::SC::operator bool(void)const ` | 21 (0x15) | Exported Function | 0x1000a250 | 0x0000a250
`public: __thiscall CEventLock<struct AppEvents>::~CEventLock<struct AppEvents>(void)` | 7 (0x7) | Exported Function | 0x10009f10 | 0x00009f10
`public: __thiscall CEventLock<struct AppEvents>::CEventLock<struct AppEvents>(void)` | 1 (0x1) | Exported Function | 0x10009f60 | 0x00009f60
`public: class CMMCStrongReferences & __thiscall CMMCStrongReferences::operator=(class CMMCStrongReferences &&)` | 12 (0xc) | Exported Function | 0x10017040 | 0x00017040
`void __stdcall TraceSnapinError(unsigned short const *,class mmcerror::SC const &)` | 118 (0x76) | Exported Function | 0x10018210 | 0x00018210


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


