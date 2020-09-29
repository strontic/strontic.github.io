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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`class mmcerror::SC __cdecl ScFromMMC(long)` | 104 (0x68) | Exported Function | 0x000000018000fb60 | 0x0000fb60
`public: static void __cdecl BookKeeping::InterfaceMethodActivationContextException(int,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,struct _EXCEPTION_POINTERS * __ptr64)` | 68 (0x44) | Exported Function | 0x0000000180012500 | 0x00012500
`public: static void __cdecl BookKeeping::InterfaceFailure(int,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 67 (0x43) | Exported Function | 0x00000001800124c0 | 0x000124c0
`public: static unsigned short const * __ptr64 __cdecl mmcerror::SC::GetHelpFile(void)` | 54 (0x36) | Exported Function | 0x0000000180018d90 | 0x00018d90
`public: static unsigned short const * __ptr64 __cdecl BookKeeping::GetSnapinName(int)` | 62 (0x3e) | Exported Function | 0x0000000180007a70 | 0x00007a70
`public: static unsigned short const * __ptr64 __cdecl BookKeeping::GetSnapinModuleName(int)` | 61 (0x3d) | Exported Function | 0x0000000180012440 | 0x00012440
`public: static unsigned long __cdecl mmcerror::SC::GetMainThreadID(void)` | 57 (0x39) | Exported Function | 0x000000018000fb30 | 0x0000fb30
`public: static unsigned long __cdecl CMMCStrongReferences::Release(void)` | 98 (0x62) | Exported Function | 0x00000001800163d0 | 0x000163d0
`public: static unsigned long __cdecl CMMCStrongReferences::AddRef(void)` | 24 (0x18) | Exported Function | 0x0000000180016350 | 0x00016350
`public: static struct HWND__ * __ptr64 __cdecl mmcerror::SC::SetModalHWND(struct HWND__ * __ptr64)` | 111 (0x6f) | Exported Function | 0x0000000180019280 | 0x00019280
`public: static struct HWND__ * __ptr64 __cdecl mmcerror::SC::GetModalHWND(void)` | 58 (0x3a) | Exported Function | 0x0000000180018de0 | 0x00018de0
`public: static struct HWND__ * __ptr64 __cdecl mmcerror::SC::GetHWnd(void)` | 53 (0x35) | Exported Function | 0x0000000180008d20 | 0x00008d20
`public: static struct HINSTANCE__ * __ptr64 __cdecl mmcerror::SC::GetHinst(void)` | 56 (0x38) | Exported Function | 0x0000000180008760 | 0x00008760
`public: static long __cdecl CMMCWatsonAPI::ExceptionFilter(struct _EXCEPTION_POINTERS * __ptr64,int)` | 31 (0x1f) | Exported Function | 0x0000000180015880 | 0x00015880
`public: static long __cdecl BookKeeping::UnregisterThread(int,unsigned long)` | 122 (0x7a) | Exported Function | 0x0000000180012f40 | 0x00012f40
`public: static long __cdecl BookKeeping::UnregisterAllSnapinInstanceThreads(int)` | 121 (0x79) | Exported Function | 0x0000000180001350 | 0x00001350
`public: static long __cdecl BookKeeping::RemoveItem(void * __ptr64)` | 100 (0x64) | Exported Function | 0x00000001800039b0 | 0x000039b0
`public: static long __cdecl BookKeeping::ReleaseSnapinInterface(struct IUnknown * __ptr64,int)` | 99 (0x63) | Exported Function | 0x0000000180003a50 | 0x00003a50
`public: static long __cdecl BookKeeping::RegisterThread(int,int,unsigned long,enum BookKeeping::SnapinThreadFlags)` | 97 (0x61) | Exported Function | 0x00000001800012d0 | 0x000012d0
`public: static long __cdecl BookKeeping::LKResult2HRESULT(__int64)` | 80 (0x50) | Exported Function | 0x0000000180003ed0 | 0x00003ed0
`public: static long __cdecl BookKeeping::InitInstance(void)` | 66 (0x42) | Exported Function | 0x0000000180003f40 | 0x00003f40
`public: static long __cdecl BookKeeping::FindAllSnapinUIThreads(unsigned long * __ptr64 * __ptr64,unsigned long * __ptr64)` | 34 (0x22) | Exported Function | 0x0000000180001390 | 0x00001390
`public: static long __cdecl BookKeeping::FindAllSnapinUIThreads(int,unsigned long * __ptr64 * __ptr64,unsigned long * __ptr64)` | 33 (0x21) | Exported Function | 0x00000001800121c0 | 0x000121c0
`public: static long __cdecl BookKeeping::DumpWatsonTables(void * __ptr64,unsigned short const * __ptr64,int)` | 29 (0x1d) | Exported Function | 0x0000000180011fd0 | 0x00011fd0
`public: static long __cdecl BookKeeping::AddSnapin(unsigned short const * __ptr64,int & __ptr64)` | 25 (0x19) | Exported Function | 0x0000000180003330 | 0x00003330
`public: static long __cdecl BookKeeping::AddItem(class ItemHandle & __ptr64)` | 23 (0x17) | Exported Function | 0x00000001800038c0 | 0x000038c0
`public: static int __cdecl BookKeeping::GetNewSnapinInstanceId(void)` | 59 (0x3b) | Exported Function | 0x0000000180008d00 | 0x00008d00
`public: static class SnapinBookkeepingInfo const & __ptr64 __cdecl BookKeeping::FindSnapin(unsigned short const * __ptr64)` | 38 (0x26) | Exported Function | 0x00000001800122a0 | 0x000122a0
`public: static class SnapinBookkeepingInfo const & __ptr64 __cdecl BookKeeping::FindSnapin(struct IUnknown * __ptr64)` | 37 (0x25) | Exported Function | 0x0000000180012290 | 0x00012290
`public: static class SnapinBookkeepingInfo const & __ptr64 __cdecl BookKeeping::FindSnapin(int)` | 36 (0x24) | Exported Function | 0x0000000180012280 | 0x00012280
`public: static void __cdecl BookKeeping::InterfaceMethodException(int,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,struct _EXCEPTION_POINTERS * __ptr64)` | 69 (0x45) | Exported Function | 0x00000001800125e0 | 0x000125e0
`public: static class mmcerror::SC __cdecl CConsoleEventDispatcherProvider::ScSetConsoleEventDispatcher(class CConsoleEventDispatcher * __ptr64)` | 106 (0x6a) | Exported Function | 0x0000000180001430 | 0x00001430
`public: static void __cdecl BookKeeping::InterfaceNotFound(int,unsigned short const * __ptr64)` | 70 (0x46) | Exported Function | 0x00000001800126c0 | 0x000126c0
`public: static void __cdecl BookKeeping::InvalidMMCInterface(int,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 75 (0x4b) | Exported Function | 0x0000000180012740 | 0x00012740
`void __cdecl FormatErrorString(unsigned short const * __ptr64,class mmcerror::SC,unsigned int,unsigned short * __ptr64,int)` | 42 (0x2a) | Exported Function | 0x0000000180018b30 | 0x00018b30
`void __cdecl FormatErrorShort(class mmcerror::SC,unsigned int,unsigned short * __ptr64)` | 41 (0x29) | Exported Function | 0x0000000180018ad0 | 0x00018ad0
`void __cdecl FormatErrorIds(unsigned int,class mmcerror::SC,unsigned int,unsigned short * __ptr64)` | 40 (0x28) | Exported Function | 0x0000000180018a20 | 0x00018a20
`ReportFxSnapinException` | 132 (0x84) | Exported Function | 0x0000000180013020 | 0x00013020
`public: void __cdecl mmcerror::SC::TraceAndClear(void) __ptr64` | 116 (0x74) | Exported Function | 0x0000000180001d80 | 0x00001d80
`public: void __cdecl mmcerror::SC::Trace_(void)const __ptr64` | 119 (0x77) | Exported Function | 0x0000000180001d30 | 0x00001d30
`public: void __cdecl mmcerror::SC::Throw(void) __ptr64` | 114 (0x72) | Exported Function | 0x00000001800192c0 | 0x000192c0
`public: void __cdecl mmcerror::SC::Throw(long) __ptr64` | 113 (0x71) | Exported Function | 0x00000001800192a0 | 0x000192a0
`public: void __cdecl mmcerror::SC::SetSnapinName(unsigned short const * __ptr64) __ptr64` | 112 (0x70) | Exported Function | 0x0000000180008550 | 0x00008550
`public: void __cdecl mmcerror::SC::SetFunctionName(unsigned short const * __ptr64) __ptr64` | 107 (0x6b) | Exported Function | 0x0000000180001dd0 | 0x00001dd0
`public: void __cdecl mmcerror::SC::GetErrorMessage(unsigned int,unsigned short * __ptr64)const __ptr64` | 49 (0x31) | Exported Function | 0x0000000180018bc0 | 0x00018bc0
`public: void __cdecl mmcerror::SC::FatalError(void)const __ptr64` | 32 (0x20) | Exported Function | 0x00000001800189d0 | 0x000189d0
`public: void __cdecl mmcerror::SC::Clear(void) __ptr64` | 28 (0x1c) | Exported Function | 0x0000000180007e90 | 0x00007e90
`public: void __cdecl mmcerror::SC::CheckCallingThreadID(void) __ptr64` | 27 (0x1b) | Exported Function | 0x0000000180007e50 | 0x00007e50
`public: void __cdecl mmcerror::SC::``default constructor closure'(void) __ptr64` | 22 (0x16) | Exported Function | 0x000000018000fa80 | 0x0000fa80
`public: void __cdecl CEventBuffer::Unlock(void) __ptr64` | 120 (0x78) | Exported Function | 0x0000000180001490 | 0x00001490
`public: void __cdecl CEventBuffer::Lock(void) __ptr64` | 83 (0x53) | Exported Function | 0x0000000180017fb0 | 0x00017fb0
`public: unsigned short const * __ptr64 __cdecl mmcerror::SC::GetSnapinName(void)const __ptr64` | 63 (0x3f) | Exported Function | 0x000000018000fb40 | 0x0000fb40
`public: unsigned short const * __ptr64 __cdecl mmcerror::SC::GetFunctionName(void)const __ptr64` | 52 (0x34) | Exported Function | 0x000000018000fb20 | 0x0000fb20
`public: unsigned long __cdecl mmcerror::SC::GetHelpID(void) __ptr64` | 55 (0x37) | Exported Function | 0x0000000180008eb0 | 0x00008eb0
`public: static void __cdecl mmcerror::SC::SetMainThreadID(unsigned long)` | 110 (0x6e) | Exported Function | 0x0000000180008d30 | 0x00008d30
`public: static void __cdecl mmcerror::SC::SetHWnd(struct HWND__ * __ptr64)` | 108 (0x6c) | Exported Function | 0x0000000180008d40 | 0x00008d40
`public: static void __cdecl mmcerror::SC::SetHinst(struct HINSTANCE__ * __ptr64)` | 109 (0x6d) | Exported Function | 0x0000000180019270 | 0x00019270
`public: static void __cdecl CMMCWatsonAPI::ForceException(int)` | 39 (0x27) | Exported Function | 0x0000000180015a40 | 0x00015a40
`public: static void __cdecl BookKeeping::MMCNullInterface(int,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 92 (0x5c) | Exported Function | 0x0000000180012910 | 0x00012910
`public: static void __cdecl BookKeeping::MMCInterfaceMethodException(int,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,struct _EXCEPTION_POINTERS * __ptr64,enum BookKeeping::_SnapinError)` | 91 (0x5b) | Exported Function | 0x0000000180012840 | 0x00012840
`public: static void __cdecl BookKeeping::MMCInterfaceLeak(int,unsigned short const * __ptr64)` | 90 (0x5a) | Exported Function | 0x0000000180012800 | 0x00012800
`public: static void __cdecl BookKeeping::MMCInterfaceError(int,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 89 (0x59) | Exported Function | 0x00000001800127c0 | 0x000127c0
`public: static void __cdecl BookKeeping::InvalidMMCInterfaceRelease(int,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 76 (0x4c) | Exported Function | 0x0000000180012780 | 0x00012780
`public: static void __cdecl BookKeeping::InvalidInterface(int,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 74 (0x4a) | Exported Function | 0x0000000180012700 | 0x00012700
`public: static class mmcerror::SC __cdecl CConsoleEventDispatcherProvider::ScGetConsoleEventDispatcher(class CConsoleEventDispatcher * __ptr64 & __ptr64)` | 105 (0x69) | Exported Function | 0x0000000180016400 | 0x00016400
`public: static class ItemHandle * __ptr64 __cdecl BookKeeping::FindItem(void * __ptr64)` | 35 (0x23) | Exported Function | 0x00000001800041e0 | 0x000041e0
`public: static bool __cdecl ItemHandle::IsValid(class ItemHandle const * __ptr64)` | 79 (0x4f) | Exported Function | 0x0000000180014390 | 0x00014390
`private: unsigned long __cdecl CMMCStrongReferences::InternalRelease(void) __ptr64` | 73 (0x49) | Exported Function | 0x00000001800163a0 | 0x000163a0
`private: unsigned long __cdecl CMMCStrongReferences::InternalAddRef(void) __ptr64` | 71 (0x47) | Exported Function | 0x0000000180016380 | 0x00016380
`private: static unsigned long mmcerror::SC::s_dwMainThreadID` | 124 (0x7c) | Exported Function | 0x000000018002c990 | 0x0002c990
`private: static unsigned int mmcerror::SC::s_CallDepth` | 123 (0x7b) | Exported Function | 0x000000018002d258 | 0x0002d258
`private: static struct HWND__ * __ptr64 __ptr64 mmcerror::SC::s_hWndModal` | 127 (0x7f) | Exported Function | 0x0000000180030880 | 0x00030880
`private: static struct HWND__ * __ptr64 __ptr64 mmcerror::SC::s_hWnd` | 126 (0x7e) | Exported Function | 0x000000018002d250 | 0x0002d250
`private: static struct HINSTANCE__ * __ptr64 __ptr64 mmcerror::SC::s_hInst` | 125 (0x7d) | Exported Function | 0x0000000180030878 | 0x00030878
`private: static class CMMCStrongReferences & __ptr64 __cdecl CMMCStrongReferences::GetSingletonObject(void)` | 60 (0x3c) | Exported Function | 0x0000000180016370 | 0x00016370
`private: static class CConsoleEventDispatcher * __ptr64 __ptr64 CConsoleEventDispatcherProvider::s_pDispatcher` | 128 (0x80) | Exported Function | 0x000000018002d240 | 0x0002d240
`private: enum mmcerror::SC::facility_type __cdecl mmcerror::SC::GetFacility(void)const __ptr64` | 51 (0x33) | Exported Function | 0x000000018000fb10 | 0x0000fb10
`private: class mmcerror::SC __cdecl CEventBuffer::ScFlushPostponed(void) __ptr64` | 103 (0x67) | Exported Function | 0x0000000180001580 | 0x00001580
`private: bool __cdecl CMMCStrongReferences::InternalLastRefReleased(void) __ptr64` | 72 (0x48) | Exported Function | 0x0000000180016390 | 0x00016390
`private: __cdecl CMMCStrongReferences::CMMCStrongReferences(void) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180016270 | 0x00016270
`MMCUpdateRegistry` | 93 (0x5d) | Exported Function | 0x000000018001a430 | 0x0001a430
`MMC_PickIconDlg` | 94 (0x5e) | Exported Function | 0x000000018001c6f0 | 0x0001c6f0
`long __cdecl SCODEFromSc(class mmcerror::SC const & __ptr64)` | 101 (0x65) | Exported Function | 0x0000000180007ba0 | 0x00007ba0
`long __cdecl HrFromSc(class mmcerror::SC const & __ptr64)` | 65 (0x41) | Exported Function | 0x0000000180007ba0 | 0x00007ba0
`LoadStandardOverlays` | 82 (0x52) | Exported Function | 0x0000000180007c20 | 0x00007c20
`LeaveModalLoop` | 131 (0x83) | Exported Function | 0x000000018001d520 | 0x0001d520
`int __cdecl MMCErrorBox(unsigned short const * __ptr64,unsigned int)` | 86 (0x56) | Exported Function | 0x0000000180018fd0 | 0x00018fd0
`int __cdecl MMCErrorBox(unsigned short const * __ptr64,class mmcerror::SC,unsigned int)` | 87 (0x57) | Exported Function | 0x00000001800190e0 | 0x000190e0
`int __cdecl MMCErrorBox(unsigned int,unsigned int)` | 84 (0x54) | Exported Function | 0x0000000180018df0 | 0x00018df0
`int __cdecl MMCErrorBox(unsigned int,class mmcerror::SC,unsigned int)` | 85 (0x55) | Exported Function | 0x0000000180018ec0 | 0x00018ec0
`int __cdecl MMCErrorBox(class mmcerror::SC,unsigned int)` | 88 (0x58) | Exported Function | 0x00000001800191b0 | 0x000191b0
`InsideModalLoop` | 130 (0x82) | Exported Function | 0x000000018001d430 | 0x0001d430
`GetStringModule` | 64 (0x40) | Exported Function | 0x0000000180008760 | 0x00008760
`GetEventBuffer` | 50 (0x32) | Exported Function | 0x00000001800014f0 | 0x000014f0
`GetComObjectEventSource` | 48 (0x30) | Exported Function | 0x0000000180007ef0 | 0x00007ef0
`EnterModalLoop` | 129 (0x81) | Exported Function | 0x000000018001d360 | 0x0001d360
`private: void __cdecl mmcerror::SC::MakeSc(enum mmcerror::SC::facility_type,long) __ptr64` | 95 (0x5f) | Exported Function | 0x000000018000fb50 | 0x0000fb50
`public: __cdecl CEventBuffer::CEventBuffer(class CEventBuffer const & __ptr64) __ptr64` | 2 (0x2) | Exported Function | 0x0000000180017810 | 0x00017810
`public: __cdecl CEventBuffer::CEventBuffer(void) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180017840 | 0x00017840
`public: __cdecl CEventBuffer::~CEventBuffer(void) __ptr64` | 8 (0x8) | Exported Function | 0x0000000180009030 | 0x00009030
`public: static bool __cdecl CMMCStrongReferences::LastRefReleased(void)` | 81 (0x51) | Exported Function | 0x00000001800163c0 | 0x000163c0
`public: static bool __cdecl BookKeeping::FxSnapinException(int,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,int,struct HWND__ * __ptr64)` | 46 (0x2e) | Exported Function | 0x00000001800122b0 | 0x000122b0
`public: static bool __cdecl BookKeeping::EnableDiagnosticMessageBox(bool)` | 30 (0x1e) | Exported Function | 0x00000001800121a0 | 0x000121a0
`public: static bool __cdecl BookKeeping::AddSnapinInterface(struct IUnknown * __ptr64,unsigned short const * __ptr64,int & __ptr64)` | 26 (0x1a) | Exported Function | 0x0000000180003b70 | 0x00003b70
`public: static bool (__cdecl*__cdecl BookKeeping::RegisterSnapinInterfaceErrorHandler(bool (__cdecl*)(class SnapinBookkeepingInfo & __ptr64,enum BookKeeping::_SnapinError,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,struct _EXCEPTION_POINTERS * __ptr64)))(class SnapinBookkeepingInfo & __ptr64,enum BookKeeping::_SnapinError,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,struct _EXCEPTION_POINTERS * __ptr64)` | 96 (0x60) | Exported Function | 0x0000000180012950 | 0x00012950
`public: long __cdecl mmcerror::SC::ToHr(void)const __ptr64` | 115 (0x73) | Exported Function | 0x0000000180007bb0 | 0x00007bb0
`public: long __cdecl mmcerror::SC::GetCode(void)const __ptr64` | 47 (0x2f) | Exported Function | 0x000000018000fb00 | 0x0000fb00
`public: int __cdecl mmcerror::SC::operator!(void)const __ptr64` | 16 (0x10) | Exported Function | 0x0000000180001d60 | 0x00001d60
`public: class mmcerror::SC __cdecl CEventBuffer::ScEmitOrPostpone(struct IDispatch * __ptr64,long,class ATL::CComVariant * __ptr64,int) __ptr64` | 102 (0x66) | Exported Function | 0x0000000180017fc0 | 0x00017fc0
`public: class mmcerror::SC & __ptr64 __cdecl mmcerror::SC::operator=(long) __ptr64` | 15 (0xf) | Exported Function | 0x0000000180007be0 | 0x00007be0
`public: class mmcerror::SC & __ptr64 __cdecl mmcerror::SC::operator=(class mmcerror::SC const & __ptr64) __ptr64` | 14 (0xe) | Exported Function | 0x0000000180007b10 | 0x00007b10
`public: class mmcerror::SC & __ptr64 __cdecl mmcerror::SC::FromWin32(long) __ptr64` | 45 (0x2d) | Exported Function | 0x0000000180007e30 | 0x00007e30
`public: class mmcerror::SC & __ptr64 __cdecl mmcerror::SC::FromMMC(long) __ptr64` | 44 (0x2c) | Exported Function | 0x000000018000fae0 | 0x0000fae0
`public: class mmcerror::SC & __ptr64 __cdecl mmcerror::SC::FromLastError(void) __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180018b70 | 0x00018b70
`void __cdecl TraceError(unsigned short const * __ptr64,class mmcerror::SC const & __ptr64)` | 117 (0x75) | Exported Function | 0x0000000180007a00 | 0x00007a00
`public: class CMMCStrongReferences & __ptr64 __cdecl CMMCStrongReferences::operator=(class CMMCStrongReferences const & __ptr64) __ptr64` | 13 (0xd) | Exported Function | 0x00000001800162b0 | 0x000162b0
`public: class CEventLock<struct AppEvents> & __ptr64 __cdecl CEventLock<struct AppEvents>::operator=(class CEventLock<struct AppEvents> const & __ptr64) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180017980 | 0x00017980
`public: class CEventBuffer & __ptr64 __cdecl CEventBuffer::operator=(class CEventBuffer const & __ptr64) __ptr64` | 11 (0xb) | Exported Function | 0x0000000180017e20 | 0x00017e20
`public: bool __cdecl mmcerror::SC::operator==(long)const __ptr64` | 18 (0x12) | Exported Function | 0x0000000180008150 | 0x00008150
`public: bool __cdecl mmcerror::SC::operator==(class mmcerror::SC const & __ptr64)const __ptr64` | 17 (0x11) | Exported Function | 0x0000000180007ed0 | 0x00007ed0
`public: bool __cdecl mmcerror::SC::operator!=(long)const __ptr64` | 20 (0x14) | Exported Function | 0x0000000180008130 | 0x00008130
`public: bool __cdecl mmcerror::SC::operator!=(class mmcerror::SC const & __ptr64)const __ptr64` | 19 (0x13) | Exported Function | 0x000000018000fa60 | 0x0000fa60
`public: bool __cdecl mmcerror::SC::IsError(void)const __ptr64` | 77 (0x4d) | Exported Function | 0x0000000180007e10 | 0x00007e10
`public: bool __cdecl CEventBuffer::IsLocked(void) __ptr64` | 78 (0x4e) | Exported Function | 0x0000000180017fa0 | 0x00017fa0
`public: __cdecl mmcerror::SC::~SC(void) __ptr64` | 9 (0x9) | Exported Function | 0x00000001800079b0 | 0x000079b0
`public: __cdecl mmcerror::SC::SC(long) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180001650 | 0x00001650
`public: __cdecl mmcerror::SC::SC(class mmcerror::SC const & __ptr64) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180007c00 | 0x00007c00
`public: __cdecl mmcerror::SC::operator bool(void)const __ptr64` | 21 (0x15) | Exported Function | 0x0000000180001db0 | 0x00001db0
`public: __cdecl CEventLock<struct AppEvents>::~CEventLock<struct AppEvents>(void) __ptr64` | 7 (0x7) | Exported Function | 0x0000000180001460 | 0x00001460
`public: __cdecl CEventLock<struct AppEvents>::CEventLock<struct AppEvents>(void) __ptr64` | 1 (0x1) | Exported Function | 0x00000001800014c0 | 0x000014c0
`public: class CMMCStrongReferences & __ptr64 __cdecl CMMCStrongReferences::operator=(class CMMCStrongReferences && __ptr64) __ptr64` | 12 (0xc) | Exported Function | 0x0000000180016290 | 0x00016290
`void __cdecl TraceSnapinError(unsigned short const * __ptr64,class mmcerror::SC const & __ptr64)` | 118 (0x76) | Exported Function | 0x0000000180019330 | 0x00019330


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


