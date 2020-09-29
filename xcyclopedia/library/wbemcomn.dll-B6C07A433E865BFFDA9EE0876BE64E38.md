---
title: wbemcomn.dll | WMI
excerpt: What is wbemcomn.dll?
---

# wbemcomn.dll 

* File Path: `C:\Windows\system32\wbemcomn.dll`
* Description: WMI

## Hashes

Type | Hash
-- | --
MD5 | `B6C07A433E865BFFDA9EE0876BE64E38`
SHA1 | `7D3D9402FB0077B2ACE8464B444814936C295274`
SHA256 | `A4227272ED26C1CFEDC51785204F7A32F5AF3579556C5D9423DB1FBD82938A63`
SHA384 | `36FE44B42F886CA0757FD449055AAAF4A19F2DDD94B98EEA6C04E51B8D457173792CBAA6548A7866F8FF0C938B19DDAF`
SHA512 | `7BE56E91217164069AE325F766423BCF7E7C6DF9D9F6E79A8C372C540FAAEA5A7BB2505D5F56C07A7D513A05193764037D55D4DA1CFE367A03021C20DC85C903`
SSDEEP | `6144:HKj41+cGmt4i4GO5JTCodvZSxHt61ZWEMynIMtp/cF2Zc88c/rQF/3MQ/uoIxx:qjv2rRLoZZi9MjcMxIGoG`
IMP | `86CAC8F8890EA865EC728148A6336B92`
PESHA1 | `6EE8CE12BD1BE2D5C631FB945E56CB8B6B41928B`
PE256 | `6C9722745E734E4585932901F9076CDD88D4FCE428B76B54519B810FF1A53848`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`_DoTraceHRFailure_` | 1304 (0x518) | Exported Function | 0x0000000180039c90 | 0x00039c90
`public: static class CWbemCallSecurity * __ptr64 __cdecl CWbemCallSecurity::MakeInternalCopyOfThread(void)` | 976 (0x3d0) | Exported Function | 0x0000000180024620 | 0x00024620
`public: static class CSmallArrayBlob * __ptr64 __cdecl CSmallArrayBlob::CreateBlob(int)` | 558 (0x22e) | Exported Function | 0x0000000180014070 | 0x00014070
`public: static bool __cdecl CWbemInstallObject::IsOffline(void)` | 927 (0x39f) | Exported Function | 0x0000000180012a90 | 0x00012a90
`public: short __cdecl CVar::GetShort(void) __ptr64` | 815 (0x32f) | Exported Function | 0x0000000180012d30 | 0x00012d30
`public: short __cdecl CVar::GetBool(void) __ptr64` | 691 (0x2b3) | Exported Function | 0x0000000180012d30 | 0x00012d30
`public: short __cdecl CSafeArray::GetShortAt(int) __ptr64` | 816 (0x330) | Exported Function | 0x000000018002bee0 | 0x0002bee0
`public: short __cdecl CSafeArray::GetBoolAt(int) __ptr64` | 692 (0x2b4) | Exported Function | 0x000000018002bee0 | 0x0002bee0
`public: long __cdecl Registry::GetLastError(void) __ptr64` | 748 (0x2ec) | Exported Function | 0x0000000180023e70 | 0x00023e70
`public: long __cdecl CWbemCriticalSection::GetRecursionCount(void) __ptr64` | 797 (0x31d) | Exported Function | 0x0000000180023e80 | 0x00023e80
`public: long __cdecl CWbemCriticalSection::GetLockCount(void) __ptr64` | 752 (0x2f0) | Exported Function | 0x0000000180010290 | 0x00010290
`public: long __cdecl CVarVector::UnaccessRawArray(void) __ptr64` | 1254 (0x4e6) | Exported Function | 0x0000000180012b40 | 0x00012b40
`public: long __cdecl CVarVector::SetRawArrayData(void * __ptr64,int,int) __ptr64` | 1164 (0x48c) | Exported Function | 0x0000000180011e30 | 0x00011e30
`public: long __cdecl CVarVector::InternalRawArrayAccess(void) __ptr64` | 900 (0x384) | Exported Function | 0x0000000180012d80 | 0x00012d80
`public: long __cdecl CVarVector::GetRawArrayData(void * __ptr64,int) __ptr64` | 793 (0x319) | Exported Function | 0x00000001800384d0 | 0x000384d0
`public: long __cdecl CVarVector::AccessRawArray(void * __ptr64 * __ptr64) __ptr64` | 448 (0x1c0) | Exported Function | 0x0000000180012e60 | 0x00012e60
`public: long __cdecl CVar::GetLong(void) __ptr64` | 754 (0x2f2) | Exported Function | 0x0000000180011410 | 0x00011410
`public: long __cdecl CUnkInternal::InternalQueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 899 (0x383) | Exported Function | 0x000000018002c040 | 0x0002c040
`public: static class CWbemInterval __cdecl CBasicUnloadInstruction::staticRead(struct IWbemServices * __ptr64,struct IWbemContext * __ptr64,unsigned short const * __ptr64)` | 1389 (0x56d) | Exported Function | 0x00000001800436b0 | 0x000436b0
`public: static class CWbemInterval __cdecl CWbemInterval::GetInfinity(void)` | 736 (0x2e0) | Exported Function | 0x0000000180024e40 | 0x00024e40
`public: static class CWbemTime __cdecl CWbemTime::GetInfinity(void)` | 737 (0x2e1) | Exported Function | 0x0000000180024e50 | 0x00024e50
`public: static class CWbemTime __cdecl CWbemTime::GetTickCount(void)` | 845 (0x34d) | Exported Function | 0x000000018000f900 | 0x0000f900
`public: static long __cdecl CMUILocale::_GetSystemDefaultLocale(unsigned short * __ptr64 * __ptr64,unsigned long)` | 1306 (0x51a) | Exported Function | 0x000000018000e590 | 0x0000e590
`public: static int __cdecl CWin32DefaultArena::WbemSysReAllocStringLen(unsigned short * __ptr64 * __ptr64,unsigned short const * __ptr64,unsigned int)` | 1294 (0x50e) | Exported Function | 0x0000000180023fc0 | 0x00023fc0
`public: static int __cdecl CWin32DefaultArena::WbemSysReAllocString(unsigned short * __ptr64 * __ptr64,unsigned short const * __ptr64)` | 1293 (0x50d) | Exported Function | 0x0000000180023fa0 | 0x00023fa0
`public: static int __cdecl CWin32DefaultArena::WbemOutOfMemory(void)` | 1286 (0x506) | Exported Function | 0x0000000180023f30 | 0x00023f30
`public: static int __cdecl CWin32DefaultArena::WbemMemFree(void * __ptr64)` | 1283 (0x503) | Exported Function | 0x0000000180009390 | 0x00009390
`public: static int __cdecl CWin32DefaultArena::WbemHeapInitialize(void * __ptr64)` | 1281 (0x501) | Exported Function | 0x0000000180013000 | 0x00013000
`public: static int __cdecl CWin32DefaultArena::ValidateMemSize(int)` | 1273 (0x4f9) | Exported Function | 0x0000000180012dc0 | 0x00012dc0
`public: static int __cdecl CVarVector::IsValidVectorType(int)` | 954 (0x3ba) | Exported Function | 0x000000018000c830 | 0x0000c830
`public: long __cdecl CTimerGenerator::Set(class CTimerInstruction * __ptr64,class CWbemTime) __ptr64` | 1089 (0x441) | Exported Function | 0x000000018000fbc0 | 0x0000fbc0
`public: static int __cdecl CVarVector::IsValidVectorArray(int,struct tagSAFEARRAY * __ptr64)` | 953 (0x3b9) | Exported Function | 0x000000018000c7f0 | 0x0000c7f0
`public: static int __cdecl CNtSecurity::IsUserInGroup(void * __ptr64,class CNtSid & __ptr64,int * __ptr64)` | 936 (0x3a8) | Exported Function | 0x000000018000cd90 | 0x0000cd90
`public: static int __cdecl CMUILocale::_Free(void * __ptr64)` | 1305 (0x519) | Exported Function | 0x0000000180011cf0 | 0x00011cf0
`public: static int __cdecl CMRCICompression::GetCompressedFileInfo(unsigned short const * __ptr64,enum CMRCICompression::CompressionLevel & __ptr64,unsigned long & __ptr64,struct _FILETIME & __ptr64,__int64 & __ptr64)` | 699 (0x2bb) | Exported Function | 0x0000000180031e20 | 0x00031e20
`public: static int __cdecl CExecQueue::IsSTAThread(void)` | 932 (0x3a4) | Exported Function | 0x000000018002db40 | 0x0002db40
`public: static int __cdecl CDateTimeParser::CheckDMTFDateTimeInterval(unsigned short const * __ptr64)` | 521 (0x209) | Exported Function | 0x00000001800261d0 | 0x000261d0
`public: static int __cdecl CDateTimeParser::CheckDMTFDateTimeFormat(unsigned short const * __ptr64,int,int)` | 519 (0x207) | Exported Function | 0x0000000180011800 | 0x00011800
`public: static class IWbemCallSecurity * __ptr64 __cdecl CWbemCallSecurity::CreateInst(void)` | 559 (0x22f) | Exported Function | 0x00000001800083f0 | 0x000083f0
`public: static class CWbemTime __cdecl CWbemTime::GetZero(void)` | 870 (0x366) | Exported Function | 0x0000000180001490 | 0x00001490
`public: static int __cdecl CStaticCritSec::anyFailure(void)` | 1320 (0x528) | Exported Function | 0x0000000180013490 | 0x00013490
`public: long __cdecl CTimerGenerator::Remove(class CInstructionTest * __ptr64) __ptr64` | 1052 (0x41c) | Exported Function | 0x0000000180036560 | 0x00036560
`public: long __cdecl CSafeArray::Unaccess(void) __ptr64` | 1253 (0x4e5) | Exported Function | 0x000000018002d160 | 0x0002d160
`public: long __cdecl CSafeArray::GetLongAt(int) __ptr64` | 755 (0x2f3) | Exported Function | 0x000000018002bff0 | 0x0002bff0
`public: long __cdecl CDatePart::SetDate(unsigned short const * __ptr64) __ptr64` | 1119 (0x45f) | Exported Function | 0x0000000180025980 | 0x00025980
`public: long __cdecl CDatePart::SetDate(char const * __ptr64) __ptr64` | 1118 (0x45e) | Exported Function | 0x0000000180025800 | 0x00025800
`public: long __cdecl CDatePart::GetPart(int,int * __ptr64) __ptr64` | 776 (0x308) | Exported Function | 0x00000001800251a0 | 0x000251a0
`public: long __cdecl CBuffer::WriteLPWSTR(unsigned short const * __ptr64) __ptr64` | 1301 (0x515) | Exported Function | 0x00000001800239c0 | 0x000239c0
`public: long __cdecl CBuffer::SetSize(unsigned long) __ptr64` | 1177 (0x499) | Exported Function | 0x0000000180023810 | 0x00023810
`public: long __cdecl CBuffer::ReadLPWSTR(unsigned short const * __ptr64 & __ptr64) __ptr64` | 1032 (0x408) | Exported Function | 0x0000000180023620 | 0x00023620
`public: long __cdecl CBuffer::Advance(unsigned long) __ptr64` | 493 (0x1ed) | Exported Function | 0x0000000180023130 | 0x00023130
`public: int __cdecl WString::WildcardTest(unsigned short const * __ptr64)const __ptr64` | 1296 (0x510) | Exported Function | 0x0000000180041b10 | 0x00041b10
`public: long __cdecl CExecQueue::EnqueueAndWait(class CExecRequest * __ptr64) __ptr64` | 620 (0x26c) | Exported Function | 0x000000018002d730 | 0x0002d730
`public: int __cdecl WString::operator>=(unsigned short const * __ptr64)const __ptr64` | 397 (0x18d) | Exported Function | 0x000000018002bb60 | 0x0002bb60
`public: int __cdecl WString::operator<=(unsigned short const * __ptr64)const __ptr64` | 390 (0x186) | Exported Function | 0x000000018002bb00 | 0x0002bb00
`public: int __cdecl WString::operator<(unsigned short const * __ptr64)const __ptr64` | 387 (0x183) | Exported Function | 0x000000018002bad0 | 0x0002bad0
`public: int __cdecl WString::Length(void)const __ptr64` | 969 (0x3c9) | Exported Function | 0x0000000180012860 | 0x00012860
`public: int __cdecl WString::ExtractToken(unsigned short,class WString & __ptr64) __ptr64` | 648 (0x288) | Exported Function | 0x0000000180041280 | 0x00041280
`public: int __cdecl WString::ExtractToken(unsigned short const * __ptr64,class WString & __ptr64) __ptr64` | 649 (0x289) | Exported Function | 0x00000001800414a0 | 0x000414a0
`public: int __cdecl WString::EqualNoCase(unsigned short const * __ptr64)const __ptr64` | 636 (0x27c) | Exported Function | 0x000000018000a210 | 0x0000a210
`public: int __cdecl WString::Equal(unsigned short const * __ptr64)const __ptr64` | 634 (0x27a) | Exported Function | 0x000000018002beb0 | 0x0002beb0
`public: int __cdecl WString2::operator>=(unsigned short const * __ptr64)const __ptr64` | 396 (0x18c) | Exported Function | 0x000000018002bb60 | 0x0002bb60
`public: int __cdecl WString::operator>(unsigned short const * __ptr64)const __ptr64` | 394 (0x18a) | Exported Function | 0x000000018002bb30 | 0x0002bb30
`public: static long __cdecl CMUILocale::_GetSystemDefaultLocaleName(unsigned short * __ptr64 * __ptr64)` | 1307 (0x51b) | Exported Function | 0x000000018000e4c0 | 0x0000e4c0
`public: long __cdecl CExecQueue::EnqueueWithoutSleep(class CExecRequest * __ptr64,void * __ptr64 * __ptr64) __ptr64` | 621 (0x26d) | Exported Function | 0x000000018002d850 | 0x0002d850
`public: long __cdecl CHaltable::Halt(void) __ptr64` | 874 (0x36a) | Exported Function | 0x0000000180035d20 | 0x00035d20
`public: long __cdecl CSafeArray::Access(void * __ptr64 * __ptr64) __ptr64` | 446 (0x1be) | Exported Function | 0x000000018002bd10 | 0x0002bd10
`public: long __cdecl CRegistryMinMaxLimitControl::Reread(void) __ptr64` | 1065 (0x429) | Exported Function | 0x0000000180044520 | 0x00044520
`public: long __cdecl CPropertyName::GetNumElements(void)const __ptr64` | 770 (0x302) | Exported Function | 0x0000000180010290 | 0x00010290
`public: long __cdecl CNtSid::GetTextSid(unsigned short * __ptr64 * __ptr64) __ptr64` | 844 (0x34c) | Exported Function | 0x000000018003f370 | 0x0003f370
`public: long __cdecl CNtSecurityDescriptor::GetSacl(class CNtAcl * __ptr64 * __ptr64) __ptr64` | 804 (0x324) | Exported Function | 0x000000018003de20 | 0x0003de20
`public: long __cdecl CNtSecurityDescriptor::GetDacl(class CNtAcl * __ptr64 * __ptr64) __ptr64` | 707 (0x2c3) | Exported Function | 0x000000018003da00 | 0x0003da00
`public: long __cdecl CNtSecurityDescriptor::DeleteSacl(void) __ptr64` | 584 (0x248) | Exported Function | 0x000000018003cef0 | 0x0003cef0
`public: long __cdecl CMUILocaleList::Initialize(unsigned short * __ptr64,bool) __ptr64` | 888 (0x378) | Exported Function | 0x0000000180004140 | 0x00004140
`public: long __cdecl CExecRequest::GetPriority(void) __ptr64` | 783 (0x30f) | Exported Function | 0x0000000180023510 | 0x00023510
`public: long __cdecl CMUILocaleList::GetFirst_ms_XXX_Locale(unsigned short * __ptr64 * __ptr64) __ptr64` | 723 (0x2d3) | Exported Function | 0x00000001800084c0 | 0x000084c0
`public: long __cdecl CInstructionQueue::Remove(class CInstructionTest * __ptr64,class CTimerInstruction * __ptr64 * __ptr64) __ptr64` | 1050 (0x41a) | Exported Function | 0x000000018000f220 | 0x0000f220
`public: long __cdecl CInstructionQueue::GetNumInstructions(void) __ptr64` | 771 (0x303) | Exported Function | 0x0000000180036500 | 0x00036500
`public: long __cdecl CInstructionQueue::Enqueue(class CWbemTime,class CTimerInstruction * __ptr64) __ptr64` | 619 (0x26b) | Exported Function | 0x000000018000e5f0 | 0x0000e5f0
`public: long __cdecl CInstructionQueue::Dequeue(class CTimerInstruction * __ptr64 & __ptr64,class CWbemTime & __ptr64) __ptr64` | 590 (0x24e) | Exported Function | 0x0000000180036450 | 0x00036450
`public: long __cdecl CInstructionQueue::Change(class CTimerInstruction * __ptr64,class CWbemTime) __ptr64` | 515 (0x203) | Exported Function | 0x000000018000f420 | 0x0000f420
`public: long __cdecl CHaltable::WaitForResumption(void) __ptr64` | 1277 (0x4fd) | Exported Function | 0x000000018000f9b0 | 0x0000f9b0
`public: long __cdecl CHaltable::ResumeAll(void) __ptr64` | 1074 (0x432) | Exported Function | 0x0000000180035e00 | 0x00035e00
`public: long __cdecl CHaltable::Resume(void) __ptr64` | 1073 (0x431) | Exported Function | 0x0000000180035d90 | 0x00035d90
`public: long __cdecl CInstructionQueue::WaitAndPeek(class CTimerInstruction * __ptr64 & __ptr64,class CWbemTime & __ptr64) __ptr64` | 1276 (0x4fc) | Exported Function | 0x000000018000f740 | 0x0000f740
`public: int __cdecl WString2::operator>(unsigned short const * __ptr64)const __ptr64` | 393 (0x189) | Exported Function | 0x000000018002bb30 | 0x0002bb30
`public: static long __cdecl CMUILocale::_GetThreadPreferredUILanguages(unsigned long,unsigned long * __ptr64,unsigned short * __ptr64,unsigned long * __ptr64)` | 1308 (0x51c) | Exported Function | 0x000000018000a7b0 | 0x0000a7b0
`public: static long __cdecl CMUILocale::_LocaleNameToLCID(unsigned short * __ptr64,unsigned long,unsigned long * __ptr64)` | 1311 (0x51f) | Exported Function | 0x000000018000a8f0 | 0x0000a8f0
`public: static void __cdecl CWbemInstallObject::RegisterCMIFlushRepositoryCacheHook(long (__cdecl*)(int))` | 1038 (0x40e) | Exported Function | 0x0000000180045510 | 0x00045510
`public: static void __cdecl CWbemInstallObject::InitMap(void)` | 885 (0x375) | Exported Function | 0x0000000180012220 | 0x00012220
`public: static void __cdecl CWbemInstallObject::FreeMap(void)` | 659 (0x293) | Exported Function | 0x0000000180012110 | 0x00012110
`public: static void __cdecl CWbemInstallObject::CleanUp(void)` | 526 (0x20e) | Exported Function | 0x0000000180012170 | 0x00012170
`public: static void __cdecl CStaticCritSec::SetFailure(void)` | 1130 (0x46a) | Exported Function | 0x00000001800434c0 | 0x000434c0
`public: static void * __ptr64 __cdecl CWin32DefaultArena::WbemMemReAlloc(void * __ptr64,unsigned __int64)` | 1284 (0x504) | Exported Function | 0x000000018000cc90 | 0x0000cc90
`public: static void * __ptr64 __cdecl CWin32DefaultArena::WbemMemAlloc(unsigned __int64)` | 1282 (0x502) | Exported Function | 0x0000000180009420 | 0x00009420
`public: static void * __ptr64 __cdecl CWin32DefaultArena::GetArenaHeap(void)` | 671 (0x29f) | Exported Function | 0x0000000180011a00 | 0x00011a00
`public: static void * __ptr64 __cdecl CMUILocale::_Alloc(unsigned __int64)` | 1303 (0x517) | Exported Function | 0x0000000180022ef0 | 0x00022ef0
`public: static unsigned short const * __ptr64 __cdecl CWbemInstallObject::GetRepositoryFolder(void)` | 802 (0x322) | Exported Function | 0x00000001800454c0 | 0x000454c0
`public: static unsigned short const * __ptr64 __cdecl CWbemInstallObject::GetRegistryPathWbem(void)` | 801 (0x321) | Exported Function | 0x00000001800454b0 | 0x000454b0
`public: static unsigned short const * __ptr64 __cdecl CWbemInstallObject::GetRegistryPathCIMOM(void)` | 800 (0x320) | Exported Function | 0x00000001800454a0 | 0x000454a0
`public: static unsigned short const * __ptr64 __cdecl CWbemInstallObject::GetBinaryPath(void)` | 689 (0x2b1) | Exported Function | 0x0000000180045440 | 0x00045440
`public: static unsigned short const * __ptr64 __cdecl CWbemInstallObject::GetAutoRecoverFolder(void)` | 684 (0x2ac) | Exported Function | 0x0000000180045430 | 0x00045430
`public: static unsigned short * __ptr64 __cdecl QL1_Parser::ReplaceClassName(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,unsigned short const * __ptr64)` | 1062 (0x426) | Exported Function | 0x00000001800345a0 | 0x000345a0
`public: static unsigned short * __ptr64 __cdecl CWin32DefaultArena::WbemSysAllocStringLen(unsigned short const * __ptr64,unsigned int)` | 1291 (0x50b) | Exported Function | 0x0000000180023f80 | 0x00023f80
`public: static unsigned short * __ptr64 __cdecl CWin32DefaultArena::WbemSysAllocStringByteLen(char const * __ptr64,unsigned int)` | 1290 (0x50a) | Exported Function | 0x0000000180023f60 | 0x00023f60
`public: static void __cdecl CWbemInstallObject::SetAutoRecoverFolder(unsigned short const * __ptr64)` | 1097 (0x449) | Exported Function | 0x0000000180045520 | 0x00045520
`public: static void __cdecl CWbemInstallObject::SetBinaryPath(unsigned short const * __ptr64)` | 1102 (0x44e) | Exported Function | 0x0000000180045530 | 0x00045530
`public: static void __cdecl CWbemInstallObject::SetOffline(bool)` | 1155 (0x483) | Exported Function | 0x0000000180045540 | 0x00045540
`public: static void __cdecl CWbemInstallObject::SetRegistryPathCIMOM(unsigned short const * __ptr64)` | 1168 (0x490) | Exported Function | 0x0000000180045550 | 0x00045550
`public: struct IDispatch * __ptr64 __cdecl CVar::GetDispatch(void) __ptr64` | 710 (0x2c6) | Exported Function | 0x000000018002bf40 | 0x0002bf40
`public: struct IDispatch * __ptr64 __cdecl CSafeArray::GetDispatchAt(int) __ptr64` | 711 (0x2c7) | Exported Function | 0x00000001800354b0 | 0x000354b0
`public: struct _GUID * __ptr64 __cdecl CVar::GetClsId(void) __ptr64` | 698 (0x2ba) | Exported Function | 0x0000000180010d00 | 0x00010d00
`public: struct _FILETIME __cdecl CVar::GetFileTime(void) __ptr64` | 721 (0x2d1) | Exported Function | 0x000000018002ba80 | 0x0002ba80
`public: struct _EVENT_TRACE_PROPERTIES * __ptr64 __cdecl CWMITraceSettings::GetEventTraceProperties(void) __ptr64` | 717 (0x2cd) | Exported Function | 0x0000000180013340 | 0x00013340
`public: struct _ACL * __ptr64 __cdecl CNtAcl::GetPtr(void) __ptr64` | 786 (0x312) | Exported Function | 0x00000001800117b0 | 0x000117b0
`public: struct _ACCESS_ALLOWED_ACE * __ptr64 __cdecl CNtAce::GetPtr(void) __ptr64` | 785 (0x311) | Exported Function | 0x0000000180010d00 | 0x00010d00
`public: static void __cdecl SHA256::Transform(void * __ptr64,unsigned int,unsigned char * __ptr64 const)` | 1242 (0x4da) | Exported Function | 0x00000001800014a0 | 0x000014a0
`public: static unsigned short * __ptr64 __cdecl CWin32DefaultArena::WbemSysAllocString(unsigned short const * __ptr64)` | 1289 (0x509) | Exported Function | 0x0000000180023f40 | 0x00023f40
`public: static void __cdecl MD5::Transform(void * __ptr64,unsigned int,unsigned char * __ptr64 const)` | 1241 (0x4d9) | Exported Function | 0x00000001800318e0 | 0x000318e0
`public: static void __cdecl CWStringArray::Intersection(class CWStringArray & __ptr64,class CWStringArray & __ptr64,class CWStringArray & __ptr64)` | 902 (0x386) | Exported Function | 0x000000018002ee10 | 0x0002ee10
`public: static void __cdecl CWStringArray::Difference(class CWStringArray & __ptr64,class CWStringArray & __ptr64,class CWStringArray & __ptr64)` | 593 (0x251) | Exported Function | 0x000000018002eb70 | 0x0002eb70
`public: static void __cdecl CWin32DefaultArena::WbemSysFreeString(unsigned short * __ptr64)` | 1292 (0x50c) | Exported Function | 0x0000000180022f60 | 0x00022f60
`public: static void __cdecl CWin32DefaultArena::WbemHeapFree(void)` | 1280 (0x500) | Exported Function | 0x0000000180013280 | 0x00013280
`public: static void __cdecl CWbemInstallObject::UnregisterCMIFlushRepositoryCacheHook(void)` | 1270 (0x4f6) | Exported Function | 0x0000000180045620 | 0x00045620
`public: static void __cdecl CWbemInstallObject::Shutdown(void)` | 1200 (0x4b0) | Exported Function | 0x0000000180045580 | 0x00045580
`public: static void __cdecl CWbemInstallObject::SetRepositoryFolder(unsigned short const * __ptr64)` | 1170 (0x492) | Exported Function | 0x0000000180045570 | 0x00045570
`public: static void __cdecl CWbemInstallObject::SetRegistryPathWbem(unsigned short const * __ptr64)` | 1169 (0x491) | Exported Function | 0x0000000180045560 | 0x00045560
`public: static void __cdecl CWStringArray::Union(class CWStringArray & __ptr64,class CWStringArray & __ptr64,class CWStringArray & __ptr64)` | 1263 (0x4ef) | Exported Function | 0x000000018000bea0 | 0x0000bea0
`public: static unsigned short * __ptr64 __cdecl CVar::TypeToText(int)` | 1251 (0x4e3) | Exported Function | 0x0000000180038ec0 | 0x00038ec0
`public: static unsigned long __cdecl CWbemInstallObject::ExpandEnvironmentStringsW(unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long)` | 641 (0x281) | Exported Function | 0x0000000180045170 | 0x00045170
`public: static unsigned long __cdecl CTraceSessionControl::Start(struct _GUID const * __ptr64,class CWMITraceSettings * __ptr64)` | 1211 (0x4bb) | Exported Function | 0x00000001800462c0 | 0x000462c0
`public: static long __cdecl CPublishWMIOperationEvent::PublishEssToConsumer(unsigned short * __ptr64,unsigned short * __ptr64)` | 1010 (0x3f2) | Exported Function | 0x00000001800480f0 | 0x000480f0
`public: static long __cdecl CPublishWMIOperationEvent::PublishEssStarted(unsigned short * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long,unsigned short * __ptr64)` | 1009 (0x3f1) | Exported Function | 0x0000000180013ab0 | 0x00013ab0
`public: static long __cdecl CPublishWMIOperationEvent::PublishESSDrop(unsigned short * __ptr64,unsigned short * __ptr64)` | 1008 (0x3f0) | Exported Function | 0x0000000180047f40 | 0x00047f40
`public: static long __cdecl CPublishWMIOperationEvent::PublishClientRequestFailure(unsigned short const * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,unsigned long,unsigned short * __ptr64,unsigned short const * __ptr64,long,unsigned short const * __ptr64)` | 1007 (0x3ef) | Exported Function | 0x000000018000eb00 | 0x0000eb00
`public: static long __cdecl CPublishWMIOperationEvent::Publish(unsigned short * __ptr64,unsigned long,unsigned long,unsigned short * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,unsigned long,unsigned __int64,unsigned short * __ptr64,int)` | 1006 (0x3ee) | Exported Function | 0x000000018000eeb0 | 0x0000eeb0
`public: static long __cdecl CPublishWMIOperationEvent::IsEventEnabled(struct _EVENT_DESCRIPTOR const & __ptr64)` | 912 (0x390) | Exported Function | 0x000000018000f040 | 0x0000f040
`public: static long __cdecl CPublishWMIOperationEvent::Init(void)` | 883 (0x373) | Exported Function | 0x000000018000f390 | 0x0000f390
`public: static long __cdecl CPublishWMIOperationEvent::GetFunctionPointers(void)` | 729 (0x2d9) | Exported Function | 0x000000018000f090 | 0x0000f090
`public: static long __cdecl CPublishWMIOperationEvent::PublishEssToConsumerBinding(unsigned short * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64)` | 1011 (0x3f3) | Exported Function | 0x0000000180013cd0 | 0x00013cd0
`public: static long __cdecl CMUILocale::SetPreferredLanguages(unsigned long,unsigned short const * __ptr64,unsigned long * __ptr64)` | 1159 (0x487) | Exported Function | 0x000000018000b610 | 0x0000b610
`public: static long __cdecl CMUILocale::ms_XXX_Locale_From_LCID(unsigned long,unsigned short * __ptr64 * __ptr64)` | 1370 (0x55a) | Exported Function | 0x0000000180046900 | 0x00046900
`public: static long __cdecl CMUILocale::LocaleName_To_LCID(unsigned short const * __ptr64,bool * __ptr64,unsigned long * __ptr64)` | 970 (0x3ca) | Exported Function | 0x000000018000a860 | 0x0000a860
`public: static long __cdecl CMUILocale::LCID_To_ms_XXX_Format(unsigned long,unsigned short * __ptr64,unsigned __int64)` | 962 (0x3c2) | Exported Function | 0x00000001800028e0 | 0x000028e0
`public: static long __cdecl CMUILocale::LCID_To_Culture_Format(unsigned long,unsigned short * __ptr64,unsigned __int64)` | 961 (0x3c1) | Exported Function | 0x000000018000cc40 | 0x0000cc40
`public: static long __cdecl CMUILocale::GetPreferredLanguages(unsigned short * __ptr64 * __ptr64,unsigned long * __ptr64)` | 781 (0x30d) | Exported Function | 0x000000018000d3d0 | 0x0000d3d0
`public: static long __cdecl CMUILocale::GetPreferredLanguages(unsigned long,unsigned short * __ptr64 * __ptr64,unsigned long * __ptr64)` | 780 (0x30c) | Exported Function | 0x000000018000a550 | 0x0000a550
`public: static long __cdecl CMUILocale::CheckLangNeutral(unsigned short const * __ptr64,bool * __ptr64)` | 523 (0x20b) | Exported Function | 0x000000018000d3f0 | 0x0000d3f0
`public: static long __cdecl CMUILocale::_SetThreadPreferredUILanguages(unsigned long,unsigned short const * __ptr64,unsigned long * __ptr64)` | 1313 (0x521) | Exported Function | 0x000000018000b580 | 0x0000b580
`public: static long __cdecl CMUILocale::ms_XXX_Locale_To_LCID(unsigned short const * __ptr64,unsigned long * __ptr64)` | 1371 (0x55b) | Exported Function | 0x0000000180005150 | 0x00005150
`public: static long __cdecl CMUILocale::_LCIDToLocaleName(unsigned long,unsigned short * __ptr64,int,unsigned long)` | 1310 (0x51e) | Exported Function | 0x000000018000cba0 | 0x0000cba0
`public: static long __cdecl CPublishWMIOperationEvent::PublishMethodExec(unsigned short * __ptr64,unsigned long,unsigned long,unsigned short * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,unsigned long,unsigned __int64,unsigned short * __ptr64,int)` | 1012 (0x3f4) | Exported Function | 0x00000001800482a0 | 0x000482a0
`public: static long __cdecl CPublishWMIOperationEvent::PublishProviderStarted(unsigned short * __ptr64,long,unsigned short * __ptr64,unsigned long,unsigned short * __ptr64)` | 1014 (0x3f6) | Exported Function | 0x000000018000e950 | 0x0000e950
`public: static unsigned long __cdecl CTraceSessionControl::Query(unsigned __int64,unsigned short * __ptr64,class CWMITraceSettings * __ptr64 * __ptr64)` | 1021 (0x3fd) | Exported Function | 0x0000000180045d10 | 0x00045d10
`public: static unsigned long __cdecl CExecQueue::QueueWaitForSingleObject(void * __ptr64,unsigned long)` | 1028 (0x404) | Exported Function | 0x000000018002dc90 | 0x0002dc90
`public: static unsigned long __cdecl CExecQueue::QueueUnblockedWaitForSingleObject(void * __ptr64,unsigned long)` | 1027 (0x403) | Exported Function | 0x000000018002dc00 | 0x0002dc00
`public: static unsigned long __cdecl CExecQueue::GetTlsIndex(void)` | 846 (0x34e) | Exported Function | 0x000000018002daa0 | 0x0002daa0
`public: static unsigned long (__cdecl* __ptr64 CPublishWMIOperationEvent::m_fEventWriteTransfer)(unsigned __int64,struct _EVENT_DESCRIPTOR const * __ptr64,struct _GUID const * __ptr64,struct _GUID const * __ptr64,unsigned long,struct _EVENT_DATA_DESCRIPTOR * __ptr64)` | 1347 (0x543) | Exported Function | 0x000000018007b248 | 0x0007b248
`public: static unsigned long (__cdecl* __ptr64 CPublishWMIOperationEvent::m_fEventActivityIdControl)(unsigned long,struct _GUID * __ptr64)` | 1342 (0x53e) | Exported Function | 0x000000018007b250 | 0x0007b250
`public: static unsigned __int64 CPublishWMIOperationEvent::m_publisher` | 1358 (0x54e) | Exported Function | 0x000000018007b310 | 0x0007b310
`public: static unsigned __int64 __cdecl CWin32DefaultArena::WbemMemSize(void * __ptr64)` | 1285 (0x505) | Exported Function | 0x0000000180023f00 | 0x00023f00
`public: static long __cdecl CPublishWMIOperationEvent::PublishProviderInfo(unsigned long,unsigned short * __ptr64,unsigned long,unsigned short * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,struct IWbemContext * __ptr64)` | 1013 (0x3f5) | Exported Function | 0x000000018000ede0 | 0x0000ede0
`public: static long __cdecl CWbemTime::GetLocalOffsetForDate(struct _SYSTEMTIME const * __ptr64)` | 750 (0x2ee) | Exported Function | 0x0000000180024e70 | 0x00024e70
`public: static long __cdecl CWbemInstallObject::CoGetClassObject(struct _GUID const & __ptr64,unsigned long,struct _COSERVERINFO * __ptr64,struct _GUID const & __ptr64,void * __ptr64 * __ptr64)` | 536 (0x218) | Exported Function | 0x0000000180044eb0 | 0x00044eb0
`public: static long __cdecl CWbemInstallObject::CoCreateInstance(struct _GUID const & __ptr64,struct IUnknown * __ptr64,unsigned long,struct _GUID const & __ptr64,void * __ptr64 * __ptr64)` | 535 (0x217) | Exported Function | 0x0000000180012ac0 | 0x00012ac0
`public: static long __cdecl CWbemInstallObject::AddEnvironmentValue(unsigned short const * __ptr64,unsigned short const * __ptr64)` | 467 (0x1d3) | Exported Function | 0x0000000180044d50 | 0x00044d50
`public: static long __cdecl CPublishWMIOperationEvent::PublishWin32ProcessCreation(unsigned short * __ptr64,unsigned long,unsigned long,unsigned short * __ptr64,unsigned long,unsigned __int64,unsigned short * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,unsigned long,unsigned __int64,int)` | 1019 (0x3fb) | Exported Function | 0x0000000180048930 | 0x00048930
`public: static long __cdecl CPublishWMIOperationEvent::PublishTemporaryEssStarted(unsigned short * __ptr64,unsigned short * __ptr64,unsigned short * __ptr64,unsigned long,unsigned short * __ptr64,unsigned short * __ptr64)` | 1018 (0x3fa) | Exported Function | 0x000000018000e740 | 0x0000e740
`public: static long __cdecl CPublishWMIOperationEvent::PublishStop(unsigned long,long,unsigned short * __ptr64)` | 1017 (0x3f9) | Exported Function | 0x000000018000efa0 | 0x0000efa0
`public: static long __cdecl CPublishWMIOperationEvent::PublishRepUpdate(unsigned long,unsigned short * __ptr64,unsigned long,struct IWbemContext * __ptr64,unsigned long,unsigned short * __ptr64,unsigned __int64,int)` | 1016 (0x3f8) | Exported Function | 0x000000018000fa10 | 0x0000fa10
`public: static long __cdecl CPublishWMIOperationEvent::PublishRepDelete(unsigned long,unsigned short * __ptr64,struct IWbemContext * __ptr64,unsigned long,unsigned short * __ptr64,unsigned __int64,int)` | 1015 (0x3f7) | Exported Function | 0x000000018000fde0 | 0x0000fde0
`public: static long __cdecl CWbemInstallObject::FlushRepository(void)` | 657 (0x291) | Exported Function | 0x0000000180045410 | 0x00045410
`public: int __cdecl WString2::operator<=(unsigned short const * __ptr64)const __ptr64` | 389 (0x185) | Exported Function | 0x000000018002bb00 | 0x0002bb00
`public: int __cdecl WString2::operator<(unsigned short const * __ptr64)const __ptr64` | 386 (0x182) | Exported Function | 0x000000018002bad0 | 0x0002bad0
`public: int __cdecl WString2::Length(void)const __ptr64` | 968 (0x3c8) | Exported Function | 0x0000000180012a00 | 0x00012a00
`public: int __cdecl CSafeArray::AddDispatch(struct IDispatch * __ptr64) __ptr64` | 464 (0x1d0) | Exported Function | 0x0000000180035330 | 0x00035330
`public: int __cdecl CSafeArray::AddByte(unsigned char) __ptr64` | 461 (0x1cd) | Exported Function | 0x000000018002bd50 | 0x0002bd50
`public: int __cdecl CSafeArray::AddBSTR(unsigned short * __ptr64) __ptr64` | 459 (0x1cb) | Exported Function | 0x00000001800070d0 | 0x000070d0
`public: int __cdecl CSafeArray::AddBool(short) __ptr64` | 460 (0x1cc) | Exported Function | 0x000000018002bd30 | 0x0002bd30
`public: int __cdecl CPropertyName::operator==(struct _tag_WbemPropertyName const & __ptr64) __ptr64` | 349 (0x15d) | Exported Function | 0x00000001800339b0 | 0x000339b0
`public: int __cdecl CPersistentConfig::SetPersistentCfgValue(unsigned long,unsigned long) __ptr64` | 1158 (0x486) | Exported Function | 0x00000001800137e0 | 0x000137e0
`public: int __cdecl CPersistentConfig::GetPersistentCfgValue(unsigned long,unsigned long & __ptr64) __ptr64` | 777 (0x309) | Exported Function | 0x0000000180042810 | 0x00042810
`public: int __cdecl CNtSid::operator==(class CNtSid & __ptr64) __ptr64` | 348 (0x15c) | Exported Function | 0x00000001800093d0 | 0x000093d0
`public: int __cdecl CNtSid::IsValid(void) __ptr64` | 940 (0x3ac) | Exported Function | 0x0000000180009590 | 0x00009590
`public: int __cdecl CNtSid::GetTextSid(unsigned short * __ptr64,unsigned long * __ptr64) __ptr64` | 843 (0x34b) | Exported Function | 0x000000018003f2e0 | 0x0003f2e0
`public: int __cdecl CNtSid::GetInfo(unsigned short * __ptr64 * __ptr64,unsigned short * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 739 (0x2e3) | Exported Function | 0x000000018003dbd0 | 0x0003dbd0
`public: int __cdecl CNtSid::CopyTo(void * __ptr64) __ptr64` | 556 (0x22c) | Exported Function | 0x0000000180003710 | 0x00003710
`public: int __cdecl CNtSecurityDescriptor::SetSacl(class CNtAcl * __ptr64) __ptr64` | 1172 (0x494) | Exported Function | 0x0000000180040cb0 | 0x00040cb0
`public: int __cdecl CNtSecurityDescriptor::SetOwner(class CNtSid * __ptr64) __ptr64` | 1157 (0x485) | Exported Function | 0x0000000180040c20 | 0x00040c20
`public: int __cdecl CNtSecurityDescriptor::SetGroup(class CNtSid * __ptr64) __ptr64` | 1138 (0x472) | Exported Function | 0x00000001800408e0 | 0x000408e0
`public: int __cdecl CNtSecurityDescriptor::SetFromAbsoluteCopy(struct SNtAbsoluteSD * __ptr64) __ptr64` | 1137 (0x471) | Exported Function | 0x000000018000a400 | 0x0000a400
`public: int __cdecl CNtSecurityDescriptor::SetDacl(class CNtAcl * __ptr64) __ptr64` | 1117 (0x45d) | Exported Function | 0x000000018000af30 | 0x0000af30
`public: int __cdecl CSafeArray::AddDouble(double) __ptr64` | 465 (0x1d1) | Exported Function | 0x000000018002bd70 | 0x0002bd70
`public: int __cdecl CSafeArray::AddFloat(float) __ptr64` | 468 (0x1d4) | Exported Function | 0x000000018002bd90 | 0x0002bd90
`public: int __cdecl CSafeArray::AddLong(long) __ptr64` | 472 (0x1d8) | Exported Function | 0x000000018002bde0 | 0x0002bde0
`public: int __cdecl CSafeArray::AddShort(short) __ptr64` | 485 (0x1e5) | Exported Function | 0x000000018002bd30 | 0x0002bd30
`public: int __cdecl CSafeArray::SetVariantAt(int,struct tagVARIANT * __ptr64) __ptr64` | 1191 (0x4a7) | Exported Function | 0x00000001800358b0 | 0x000358b0
`public: int __cdecl CSafeArray::SetUnknownAt(int,struct IUnknown * __ptr64) __ptr64` | 1188 (0x4a4) | Exported Function | 0x00000001800358b0 | 0x000358b0
`public: int __cdecl CSafeArray::SetShortAt(int,short) __ptr64` | 1176 (0x498) | Exported Function | 0x000000018002cf60 | 0x0002cf60
`public: int __cdecl CSafeArray::SetRawData(void * __ptr64,int,int) __ptr64` | 1167 (0x48f) | Exported Function | 0x0000000180011e80 | 0x00011e80
`public: int __cdecl CSafeArray::SetLongAt(int,long) __ptr64` | 1148 (0x47c) | Exported Function | 0x000000018002d0d0 | 0x0002d0d0
`public: int __cdecl CSafeArray::SetFloatAt(int,float) __ptr64` | 1136 (0x470) | Exported Function | 0x000000018002d0a0 | 0x0002d0a0
`public: int __cdecl CSafeArray::SetDoubleAt(int,double) __ptr64` | 1126 (0x466) | Exported Function | 0x000000018002d030 | 0x0002d030
`public: int __cdecl CSafeArray::SetDispatchAt(int,struct IDispatch * __ptr64) __ptr64` | 1124 (0x464) | Exported Function | 0x00000001800358b0 | 0x000358b0
`public: int __cdecl CNtSecurityDescriptor::IsValid(void) __ptr64` | 939 (0x3ab) | Exported Function | 0x000000018000ac70 | 0x0000ac70
`public: int __cdecl CSafeArray::SetByteAt(int,unsigned char) __ptr64` | 1107 (0x453) | Exported Function | 0x000000018002cfa0 | 0x0002cfa0
`public: int __cdecl CSafeArray::SetBoolAt(int,short) __ptr64` | 1105 (0x451) | Exported Function | 0x000000018002cf60 | 0x0002cf60
`public: int __cdecl CSafeArray::RemoveAt(int) __ptr64` | 1054 (0x41e) | Exported Function | 0x00000001800355f0 | 0x000355f0
`public: int __cdecl CSafeArray::GetType(void) __ptr64` | 852 (0x354) | Exported Function | 0x0000000180012a00 | 0x00012a00
`public: int __cdecl CSafeArray::GetRawData(void * __ptr64,int) __ptr64` | 795 (0x31b) | Exported Function | 0x00000001800354f0 | 0x000354f0
`public: int __cdecl CSafeArray::GetActualVarType(unsigned short * __ptr64) __ptr64` | 669 (0x29d) | Exported Function | 0x0000000180035430 | 0x00035430
`public: int __cdecl CSafeArray::ElementSize(void) __ptr64` | 604 (0x25c) | Exported Function | 0x0000000180023e70 | 0x00023e70
`public: int __cdecl CSafeArray::AddVariant(struct tagVARIANT * __ptr64) __ptr64` | 489 (0x1e9) | Exported Function | 0x0000000180035330 | 0x00035330
`public: int __cdecl CSafeArray::AddUnknown(struct IUnknown * __ptr64) __ptr64` | 488 (0x1e8) | Exported Function | 0x0000000180035330 | 0x00035330
`public: int __cdecl CSafeArray::SetBSTRAt(int,unsigned short * __ptr64) __ptr64` | 1100 (0x44c) | Exported Function | 0x00000001800357f0 | 0x000357f0
`public: int __cdecl CNtSecurityDescriptor::HasOwner(void) __ptr64` | 877 (0x36d) | Exported Function | 0x000000018003f400 | 0x0003f400
`public: int __cdecl CNtSecurityDescriptor::GetDacl(class CNtAcl & __ptr64) __ptr64` | 706 (0x2c2) | Exported Function | 0x000000018003d9b0 | 0x0003d9b0
`public: int __cdecl CNtAcl::Resize(unsigned long) __ptr64` | 1072 (0x430) | Exported Function | 0x00000001800406d0 | 0x000406d0
`public: int __cdecl CEventLogRecord::operator==(class CEventLogRecord const & __ptr64) __ptr64` | 347 (0x15b) | Exported Function | 0x000000018002b9e0 | 0x0002b9e0
`public: int __cdecl CEventLog::Report(unsigned short,struct _EVENT_DESCRIPTOR const & __ptr64,class CInsertionString,class CInsertionString,class CInsertionString,class CInsertionString,class CInsertionString,class CInsertionString,class CInsertionString,class CInsertionString,class CInsertionString,class CInsertionString) __ptr64` | 1063 (0x427) | Exported Function | 0x000000018002c110 | 0x0002c110
`public: int __cdecl CEventLog::Open(void) __ptr64` | 994 (0x3e2) | Exported Function | 0x000000018002c0a0 | 0x0002c0a0
`public: int __cdecl CEventLog::Close(void) __ptr64` | 534 (0x216) | Exported Function | 0x000000018002be70 | 0x0002be70
`public: int __cdecl CEnterWbemCriticalSection::IsEntered(void) __ptr64` | 911 (0x38f) | Exported Function | 0x0000000180011410 | 0x00011410
`public: int __cdecl CDMTFParser::GetValue(int) __ptr64` | 862 (0x35e) | Exported Function | 0x0000000180025320 | 0x00025320
`public: int __cdecl CDateTimeParser::SetDateTime(unsigned short const * __ptr64) __ptr64` | 1120 (0x460) | Exported Function | 0x0000000180029410 | 0x00029410
`public: int __cdecl CDateTimeParser::IsValidDateTime(void) __ptr64` | 943 (0x3af) | Exported Function | 0x0000000180025390 | 0x00025390
`public: int __cdecl CFlexArray::Add(void * __ptr64) __ptr64` | 449 (0x1c1) | Exported Function | 0x000000018000caa0 | 0x0000caa0
`public: int __cdecl CDateTimeParser::GetUTC(void) __ptr64` | 857 (0x359) | Exported Function | 0x0000000180025310 | 0x00025310
`public: int __cdecl CCheckedInCritSec::IsEntered(void) __ptr64` | 910 (0x38e) | Exported Function | 0x0000000180011410 | 0x00011410
`public: int __cdecl CAbstractQl1Parser::Parse(class CQl1ParseSink * __ptr64,int) __ptr64` | 997 (0x3e5) | Exported Function | 0x0000000180034570 | 0x00034570
`public: int __cdecl CAbstractQl1Parser::CurrentLine(void) __ptr64` | 562 (0x232) | Exported Function | 0x0000000180023510 | 0x00023510
`public: float __cdecl CVar::GetFloat(void) __ptr64` | 726 (0x2d6) | Exported Function | 0x000000018002bab0 | 0x0002bab0
`public: float __cdecl CSafeArray::GetFloatAt(int) __ptr64` | 727 (0x2d7) | Exported Function | 0x000000018002bfc0 | 0x0002bfc0
`public: double __cdecl CVar::GetDouble(void) __ptr64` | 712 (0x2c8) | Exported Function | 0x000000018002bac0 | 0x0002bac0
`public: double __cdecl CSafeArray::GetDoubleAt(int) __ptr64` | 713 (0x2c9) | Exported Function | 0x000000018002bf80 | 0x0002bf80
`public: class WString2 __cdecl WString2::operator()(int,int)const __ptr64` | 400 (0x190) | Exported Function | 0x0000000180041fb0 | 0x00041fb0
`public: int __cdecl CDateTimeParser::FillDMTF(unsigned short * __ptr64,unsigned __int64) __ptr64` | 652 (0x28c) | Exported Function | 0x0000000180028530 | 0x00028530
`public: int __cdecl CSafeArray::Size(void) __ptr64` | 1204 (0x4b4) | Exported Function | 0x000000018002d130 | 0x0002d130
`public: int __cdecl CFlexArray::CopyDataFrom(class CFlexArray const & __ptr64) __ptr64` | 553 (0x229) | Exported Function | 0x000000018002e9b0 | 0x0002e9b0
`public: int __cdecl CFlexArray::InsertAt(int,void * __ptr64) __ptr64` | 894 (0x37e) | Exported Function | 0x0000000180007760 | 0x00007760
`public: int __cdecl CNtAcl::IsValid(void) __ptr64` | 938 (0x3aa) | Exported Function | 0x00000001800245f0 | 0x000245f0
`public: int __cdecl CNtAcl::GetNumAces(void) __ptr64` | 769 (0x301) | Exported Function | 0x000000018000b070 | 0x0000b070
`public: int __cdecl CNtAcl::GetAclSizeInfo(unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 667 (0x29b) | Exported Function | 0x000000018003d920 | 0x0003d920
`public: int __cdecl CNtAcl::GetAce(int,class CNtAce & __ptr64) __ptr64` | 665 (0x299) | Exported Function | 0x000000018003d270 | 0x0003d270
`public: int __cdecl CNtAcl::DeleteAce(int) __ptr64` | 582 (0x246) | Exported Function | 0x000000018003ced0 | 0x0003ced0
`public: int __cdecl CNtAcl::ContainsSid(class CNtSid & __ptr64,unsigned char & __ptr64) __ptr64` | 550 (0x226) | Exported Function | 0x0000000180008800 | 0x00008800
`public: int __cdecl CNtAcl::AddAce(class CNtAce * __ptr64) __ptr64` | 454 (0x1c6) | Exported Function | 0x000000018003b0f0 | 0x0003b0f0
`public: int __cdecl CNtAce::GetSid(class CNtSid & __ptr64) __ptr64` | 817 (0x331) | Exported Function | 0x000000018003ec80 | 0x0003ec80
`public: int __cdecl CFlexArray::EnsureExtent(int) __ptr64` | 623 (0x26f) | Exported Function | 0x000000018002ec50 | 0x0002ec50
`public: int __cdecl CMRCIControl::AbortRequested(void) __ptr64` | 445 (0x1bd) | Exported Function | 0x0000000180010290 | 0x00010290
`public: int __cdecl CMRCICompression::CompressFile(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,enum CMRCICompression::CompressionLevel,class CMRCIControl * __ptr64) __ptr64` | 546 (0x222) | Exported Function | 0x0000000180031aa0 | 0x00031aa0
`public: int __cdecl CInstructionQueue::IsEmpty(void) __ptr64` | 908 (0x38c) | Exported Function | 0x0000000180025010 | 0x00025010
`public: int __cdecl CInsertionString::IsEmpty(void) __ptr64` | 907 (0x38b) | Exported Function | 0x0000000180010290 | 0x00010290
`public: int __cdecl CIdentitySecurity::AccessCheck(void) __ptr64` | 447 (0x1bf) | Exported Function | 0x0000000180008fd0 | 0x00008fd0
`public: int __cdecl CHaltable::IsHalted(void) __ptr64` | 915 (0x393) | Exported Function | 0x000000018000fa00 | 0x0000fa00
`public: int __cdecl CFlexQueue::GetQueueSize(void)const __ptr64` | 792 (0x318) | Exported Function | 0x000000018000b860 | 0x0000b860
`public: int __cdecl CFlexArray::Size(void)const __ptr64` | 1203 (0x4b3) | Exported Function | 0x0000000180010290 | 0x00010290
`public: int __cdecl CFlexArray::RemoveAt(int) __ptr64` | 1053 (0x41d) | Exported Function | 0x00000001800067c0 | 0x000067c0
`public: int __cdecl CMRCICompression::UncompressFile(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 1260 (0x4ec) | Exported Function | 0x0000000180031f20 | 0x00031f20
`public: int __cdecl CSafeArray::Status(void) __ptr64` | 1213 (0x4bd) | Exported Function | 0x000000018002d140 | 0x0002d140
`public: int __cdecl CSafeArray::Trim(void) __ptr64` | 1245 (0x4dd) | Exported Function | 0x000000018000a010 | 0x0000a010
`public: int __cdecl CSmallArrayBlob::Size(void)const __ptr64` | 1205 (0x4b5) | Exported Function | 0x0000000180010290 | 0x00010290
`public: int __cdecl CWStringArray::Size(void)const __ptr64` | 1207 (0x4b7) | Exported Function | 0x0000000180010290 | 0x00010290
`public: int __cdecl CWStringArray::SetAt(int,unsigned short const * __ptr64) __ptr64` | 1096 (0x448) | Exported Function | 0x000000018002ef10 | 0x0002ef10
`public: int __cdecl CWStringArray::ReplaceAt(int,unsigned short * __ptr64) __ptr64` | 1061 (0x425) | Exported Function | 0x000000018002eef0 | 0x0002eef0
`public: int __cdecl CWStringArray::RemoveAt(int) __ptr64` | 1057 (0x421) | Exported Function | 0x00000001800023d0 | 0x000023d0
`public: int __cdecl CWStringArray::InsertAt(int,unsigned short const * __ptr64) __ptr64` | 897 (0x381) | Exported Function | 0x000000018002ed70 | 0x0002ed70
`public: int __cdecl CWStringArray::FindStr(unsigned short const * __ptr64,int) __ptr64` | 655 (0x28f) | Exported Function | 0x000000018000c0e0 | 0x0000c0e0
`public: int __cdecl CWStringArray::DeleteStr(int) __ptr64` | 585 (0x249) | Exported Function | 0x000000018002eb30 | 0x0002eb30
`public: int __cdecl CWStringArray::Add(unsigned short const * __ptr64) __ptr64` | 453 (0x1c5) | Exported Function | 0x000000018000bf50 | 0x0000bf50
`public: int __cdecl QL1_Parser::GetQueryClass(unsigned short * __ptr64,int) __ptr64` | 791 (0x317) | Exported Function | 0x0000000180034430 | 0x00034430
`public: int __cdecl CWQLScanner::Parse(void) __ptr64` | 998 (0x3e6) | Exported Function | 0x00000001800073a0 | 0x000073a0
`public: int __cdecl CWQLScanner::GetReferencedAliases(class CWStringArray & __ptr64) __ptr64` | 798 (0x31e) | Exported Function | 0x000000018000ded0 | 0x0000ded0
`public: int __cdecl CWQLScanner::CountQuery(void) __ptr64` | 557 (0x22d) | Exported Function | 0x0000000180013560 | 0x00013560
`public: int __cdecl CWbemTime::SetSystemTime(struct _SYSTEMTIME const & __ptr64) __ptr64` | 1182 (0x49e) | Exported Function | 0x000000018000f960 | 0x0000f960
`public: int __cdecl CWbemTime::SetFileTime(struct _FILETIME const & __ptr64) __ptr64` | 1132 (0x46c) | Exported Function | 0x0000000180025030 | 0x00025030
`public: int __cdecl CWbemTime::SetDMTF(unsigned short const * __ptr64) __ptr64` | 1113 (0x459) | Exported Function | 0x0000000180001330 | 0x00001330
`public: int __cdecl CWbemTime::operator>=(class CWbemTime const & __ptr64)const __ptr64` | 395 (0x18b) | Exported Function | 0x0000000180024c30 | 0x00024c30
`public: int __cdecl CWbemTime::operator>(class CWbemTime const & __ptr64)const __ptr64` | 392 (0x188) | Exported Function | 0x0000000180024c10 | 0x00024c10
`public: int __cdecl CWbemTime::operator<=(class CWbemTime const & __ptr64)const __ptr64` | 388 (0x184) | Exported Function | 0x0000000180024bf0 | 0x00024bf0
`public: int __cdecl CWQLScanner::GetReferencedTables(class CWStringArray & __ptr64) __ptr64` | 799 (0x31f) | Exported Function | 0x000000018000be30 | 0x0000be30
`public: int __cdecl CWbemTime::operator<(class CWbemTime const & __ptr64)const __ptr64` | 385 (0x181) | Exported Function | 0x0000000180024bd0 | 0x00024bd0
`public: int __cdecl QL1_Parser::Parse(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64 * __ptr64) __ptr64` | 999 (0x3e7) | Exported Function | 0x0000000180005af0 | 0x00005af0
`public: int __cdecl Registry::GetBinary(unsigned short const * __ptr64,unsigned char * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 688 (0x2b0) | Exported Function | 0x0000000180034e30 | 0x00034e30
`public: int __cdecl WString2::ExtractToken(unsigned short,class WString2 & __ptr64) __ptr64` | 646 (0x286) | Exported Function | 0x0000000180042270 | 0x00042270
`public: int __cdecl WString2::ExtractToken(unsigned short const * __ptr64,class WString2 & __ptr64) __ptr64` | 647 (0x287) | Exported Function | 0x00000001800423e0 | 0x000423e0
`public: int __cdecl WString2::EqualNoCase(unsigned short const * __ptr64)const __ptr64` | 635 (0x27b) | Exported Function | 0x000000018000a210 | 0x0000a210
`public: int __cdecl WString2::Equal(unsigned short const * __ptr64)const __ptr64` | 633 (0x279) | Exported Function | 0x000000018002beb0 | 0x0002beb0
`public: int __cdecl Registry::SetStr(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 1181 (0x49d) | Exported Function | 0x000000018000e6f0 | 0x0000e6f0
`public: int __cdecl Registry::SetQWORD(unsigned short const * __ptr64,unsigned __int64) __ptr64` | 1161 (0x489) | Exported Function | 0x00000001800351a0 | 0x000351a0
`public: int __cdecl Registry::SetMultiStr(unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long) __ptr64` | 1152 (0x480) | Exported Function | 0x0000000180035160 | 0x00035160
`public: int __cdecl Registry::SetExpandStr(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 1128 (0x468) | Exported Function | 0x00000001800350f0 | 0x000350f0
`public: int __cdecl Registry::DeleteValue(unsigned short const * __ptr64) __ptr64` | 588 (0x24c) | Exported Function | 0x0000000180034e10 | 0x00034e10
`public: int __cdecl Registry::SetDWORDStr(unsigned short const * __ptr64,unsigned long) __ptr64` | 1116 (0x45c) | Exported Function | 0x0000000180002420 | 0x00002420
`public: int __cdecl Registry::SetBinary(unsigned short const * __ptr64,unsigned char * __ptr64,unsigned long) __ptr64` | 1101 (0x44d) | Exported Function | 0x0000000180013860 | 0x00013860
`public: int __cdecl Registry::Open(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long) __ptr64` | 995 (0x3e3) | Exported Function | 0x000000018000dfa0 | 0x0000dfa0
`public: int __cdecl Registry::MoveToSubkey(unsigned short const * __ptr64) __ptr64` | 981 (0x3d5) | Exported Function | 0x0000000180035090 | 0x00035090
`public: int __cdecl Registry::GetType(unsigned short const * __ptr64,unsigned long * __ptr64) __ptr64` | 855 (0x357) | Exported Function | 0x0000000180035050 | 0x00035050
`public: int __cdecl Registry::GetStr(unsigned short const * __ptr64,unsigned short * __ptr64 * __ptr64) __ptr64` | 832 (0x340) | Exported Function | 0x000000018000d480 | 0x0000d480
`public: int __cdecl Registry::GetQWORD(unsigned short const * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 790 (0x316) | Exported Function | 0x0000000180034ff0 | 0x00034ff0
`public: int __cdecl Registry::GetDWORDStr(unsigned short const * __ptr64,unsigned long * __ptr64) __ptr64` | 705 (0x2c1) | Exported Function | 0x000000018000d720 | 0x0000d720
`public: int __cdecl Registry::GetDWORD(unsigned short const * __ptr64,unsigned long * __ptr64) __ptr64` | 704 (0x2c0) | Exported Function | 0x000000018000e100 | 0x0000e100
`public: int __cdecl Registry::SetDWORD(unsigned short const * __ptr64,unsigned long) __ptr64` | 1115 (0x45b) | Exported Function | 0x00000001800138b0 | 0x000138b0
`public: struct IUnknown * __ptr64 __cdecl CSafeArray::GetUnknownAt(int) __ptr64` | 861 (0x35d) | Exported Function | 0x00000001800354b0 | 0x000354b0
`public: int __cdecl CWbemTime::IsZero(void)const __ptr64` | 960 (0x3c0) | Exported Function | 0x0000000180025010 | 0x00025010
`public: int __cdecl CWbemTime::GetSYSTEMTIME(struct _SYSTEMTIME * __ptr64)const __ptr64` | 803 (0x323) | Exported Function | 0x0000000180024f80 | 0x00024f80
`public: int __cdecl CVar::ToUI4(void) __ptr64` | 1238 (0x4d6) | Exported Function | 0x0000000180038c80 | 0x00038c80
`public: int __cdecl CVar::ToSingleChar(void) __ptr64` | 1236 (0x4d4) | Exported Function | 0x0000000180038aa0 | 0x00038aa0
`public: int __cdecl CVar::Status(void) __ptr64` | 1214 (0x4be) | Exported Function | 0x0000000180023510 | 0x00023510
`public: int __cdecl CVar::SetVariant(struct tagVARIANT * __ptr64,int) __ptr64` | 1190 (0x4a6) | Exported Function | 0x000000018000c850 | 0x0000c850
`public: int __cdecl CVar::SetLPWSTR(unsigned short * __ptr64,int) __ptr64` | 1145 (0x479) | Exported Function | 0x0000000180011bb0 | 0x00011bb0
`public: int __cdecl CVar::SetLPSTR(char * __ptr64,int) __ptr64` | 1144 (0x478) | Exported Function | 0x00000001800387b0 | 0x000387b0
`public: int __cdecl CVar::SetBSTR(unsigned short * __ptr64) __ptr64` | 1098 (0x44a) | Exported Function | 0x0000000180012060 | 0x00012060
`public: int __cdecl CVar::SetBSTR(class auto_bstr) __ptr64` | 1099 (0x44b) | Exported Function | 0x0000000180010450 | 0x00010450
`public: int __cdecl CVarVector::Add(class CVar & __ptr64) __ptr64` | 451 (0x1c3) | Exported Function | 0x00000001800380c0 | 0x000380c0
`public: int __cdecl CVar::operator==(class CVar & __ptr64) __ptr64` | 350 (0x15e) | Exported Function | 0x0000000180012b80 | 0x00012b80
`public: int __cdecl CVar::IsDataNull(void) __ptr64` | 905 (0x389) | Exported Function | 0x00000001800102a0 | 0x000102a0
`public: int __cdecl CVar::GetType(void) __ptr64` | 853 (0x355) | Exported Function | 0x0000000180010290 | 0x00010290
`public: int __cdecl CVar::GetOleType(void) __ptr64` | 773 (0x305) | Exported Function | 0x00000001800104a0 | 0x000104a0
`public: int __cdecl CVar::DumpText(struct _iobuf * __ptr64) __ptr64` | 603 (0x25b) | Exported Function | 0x0000000180013480 | 0x00013480
`public: int __cdecl CVar::CompareTo(class CVar & __ptr64,int) __ptr64` | 540 (0x21c) | Exported Function | 0x0000000180012ba0 | 0x00012ba0
`public: int __cdecl CVar::ChangeTypeToEx(unsigned short,unsigned long) __ptr64` | 517 (0x205) | Exported Function | 0x0000000180038220 | 0x00038220
`public: int __cdecl CVar::ChangeTypeTo(unsigned short) __ptr64` | 516 (0x204) | Exported Function | 0x0000000180001160 | 0x00001160
`public: int __cdecl CVar::CanDelete(void) __ptr64` | 513 (0x201) | Exported Function | 0x0000000180013560 | 0x00013560
`public: int __cdecl CVar::IsNull(void) __ptr64` | 926 (0x39e) | Exported Function | 0x0000000180010440 | 0x00010440
`public: int __cdecl CWbemTime::IsFinite(void)const __ptr64` | 914 (0x392) | Exported Function | 0x000000018000f550 | 0x0000f550
`public: int __cdecl CVarVector::Add(class CVar * __ptr64) __ptr64` | 452 (0x1c4) | Exported Function | 0x0000000180011420 | 0x00011420
`public: int __cdecl CVarVector::DoesVectorTypeMatchArrayType(void) __ptr64` | 597 (0x255) | Exported Function | 0x0000000180038480 | 0x00038480
`public: int __cdecl CWbemTime::GetFILETIME(struct _FILETIME * __ptr64)const __ptr64` | 719 (0x2cf) | Exported Function | 0x0000000180024e10 | 0x00024e10
`public: int __cdecl CWbemInterval::operator>(class CWbemInterval) __ptr64` | 391 (0x187) | Exported Function | 0x0000000180014940 | 0x00014940
`public: int __cdecl CWbemInterval::operator<(class CWbemInterval) __ptr64` | 384 (0x180) | Exported Function | 0x0000000180024bc0 | 0x00024bc0
`public: int __cdecl CWbemInterval::IsZero(void)const __ptr64` | 959 (0x3bf) | Exported Function | 0x0000000180025000 | 0x00025000
`public: int __cdecl CWbemInterval::IsFinite(void)const __ptr64` | 913 (0x391) | Exported Function | 0x0000000180024ff0 | 0x00024ff0
`public: int __cdecl CWbemCriticalSection::Enter(unsigned long) __ptr64` | 632 (0x278) | Exported Function | 0x0000000180012a10 | 0x00012a10
`public: int __cdecl CVarVector::ToUI4(void) __ptr64` | 1239 (0x4d7) | Exported Function | 0x0000000180038d60 | 0x00038d60
`public: int __cdecl CVarVector::ToSingleChar(void) __ptr64` | 1237 (0x4d5) | Exported Function | 0x0000000180038b20 | 0x00038b20
`public: int __cdecl CVarVector::CompareTo(class CVarVector & __ptr64,int) __ptr64` | 541 (0x21d) | Exported Function | 0x0000000180038360 | 0x00038360
`public: int __cdecl CVarVector::Status(void) __ptr64` | 1215 (0x4bf) | Exported Function | 0x000000018002d150 | 0x0002d150
`public: int __cdecl CVarVector::SetRawArraySize(int) __ptr64` | 1166 (0x48e) | Exported Function | 0x0000000180012d60 | 0x00012d60
`public: int __cdecl CVarVector::RemoveAt(int) __ptr64` | 1056 (0x420) | Exported Function | 0x0000000180038610 | 0x00038610
`public: int __cdecl CVarVector::operator==(class CVarVector & __ptr64) __ptr64` | 351 (0x15f) | Exported Function | 0x0000000180037fa0 | 0x00037fa0
`public: int __cdecl CVarVector::MakeOptimized(int,int,int) __ptr64` | 977 (0x3d1) | Exported Function | 0x00000001800057b0 | 0x000057b0
`public: int __cdecl CVarVector::IsOptimized(void) __ptr64` | 929 (0x3a1) | Exported Function | 0x0000000180012ec0 | 0x00012ec0
`public: int __cdecl CVarVector::InsertAt(int,class CVar & __ptr64) __ptr64` | 896 (0x380) | Exported Function | 0x0000000180038570 | 0x00038570
`public: int __cdecl CVarVector::GetType(void) __ptr64` | 854 (0x356) | Exported Function | 0x0000000180010290 | 0x00010290
`public: int __cdecl CVarVector::GetElementSize(void) __ptr64` | 714 (0x2ca) | Exported Function | 0x0000000180012ce0 | 0x00012ce0
`public: int __cdecl CVarVector::Size(void) __ptr64` | 1206 (0x4b6) | Exported Function | 0x000000018000a0a0 | 0x0000a0a0
`public: struct IUnknown * __ptr64 __cdecl CUnk::GetInnerUnknown(void) __ptr64` | 740 (0x2e4) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: struct IUnknown * __ptr64 __cdecl CUnk::GetUnknown(void) __ptr64` | 858 (0x35a) | Exported Function | 0x0000000180011a70 | 0x00011a70
`public: struct IUnknown * __ptr64 __cdecl CUnkInternal::GetUnknown(void) __ptr64` | 859 (0x35b) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: void __cdecl CExecRequest::SetPriority(long) __ptr64` | 1160 (0x488) | Exported Function | 0x000000018002ddb0 | 0x0002ddb0
`public: void __cdecl CExecRequest::SetNext(class CExecRequest * __ptr64) __ptr64` | 1153 (0x481) | Exported Function | 0x000000018002dd90 | 0x0002dd90
`public: void __cdecl CExecQueue::Shutdown(void) __ptr64` | 1198 (0x4ae) | Exported Function | 0x000000018002df70 | 0x0002df70
`public: void __cdecl CExecQueue::SetThreadLimits(long,long,long) __ptr64` | 1184 (0x4a0) | Exported Function | 0x000000018002def0 | 0x0002def0
`public: void __cdecl CExecQueue::SetRequestLimits(long,long,long) __ptr64` | 1171 (0x493) | Exported Function | 0x000000018002ddc0 | 0x0002ddc0
`public: void __cdecl CExecQueue::SetOverflowIdleTimeout(unsigned long) __ptr64` | 1156 (0x484) | Exported Function | 0x000000018002dda0 | 0x0002dda0
`public: void __cdecl CExecQueue::SetIdleTimeout(unsigned long) __ptr64` | 1141 (0x475) | Exported Function | 0x000000018002dd80 | 0x0002dd80
`public: void __cdecl CExecQueue::Release(void) __ptr64` | 1044 (0x414) | Exported Function | 0x000000018002dd40 | 0x0002dd40
`public: void __cdecl CExecQueue::Leave(void) __ptr64` | 965 (0x3c5) | Exported Function | 0x000000018002db80 | 0x0002db80
`public: void __cdecl CExecQueue::Enter(void) __ptr64` | 630 (0x276) | Exported Function | 0x000000018002da70 | 0x0002da70
`public: void __cdecl CExecQueue::AddRef(void) __ptr64` | 479 (0x1df) | Exported Function | 0x0000000180013570 | 0x00013570
`public: void __cdecl CEventLog::``default constructor closure'(void) __ptr64` | 437 (0x1b5) | Exported Function | 0x000000018002bc90 | 0x0002bc90
`public: void __cdecl CCritSec::Leave(void) __ptr64` | 964 (0x3c4) | Exported Function | 0x0000000180012790 | 0x00012790
`public: void __cdecl CCritSec::Enter(void) __ptr64` | 629 (0x275) | Exported Function | 0x0000000180011210 | 0x00011210
`public: void __cdecl CClientOpsNode::Unlock(void) __ptr64` | 1265 (0x4f1) | Exported Function | 0x0000000180046410 | 0x00046410
`public: void __cdecl CClientOpsNode::SetInfo(void * __ptr64) __ptr64` | 1142 (0x476) | Exported Function | 0x0000000180013190 | 0x00013190
`public: void __cdecl CClientOpsNode::RemoveSelf(void) __ptr64` | 1060 (0x424) | Exported Function | 0x0000000180011090 | 0x00011090
`public: void __cdecl CExecRequest::SetWhenDoneHandle(void * __ptr64) __ptr64` | 1193 (0x4a9) | Exported Function | 0x000000018002df60 | 0x0002df60
`public: void __cdecl CFlexArray::``default constructor closure'(void) __ptr64` | 438 (0x1b6) | Exported Function | 0x0000000180023dd0 | 0x00023dd0
`public: void __cdecl CFlexArray::Bind(class CFlexArray & __ptr64) __ptr64` | 501 (0x1f5) | Exported Function | 0x000000018002e8b0 | 0x0002e8b0
`public: void __cdecl CFlexArray::Compress(void) __ptr64` | 543 (0x21f) | Exported Function | 0x0000000180011b00 | 0x00011b00
`public: void __cdecl CMinMaxLimitControl::SetSleepAtMax(unsigned long) __ptr64` | 1180 (0x49c) | Exported Function | 0x000000018002ddb0 | 0x0002ddb0
`public: void __cdecl CMinMaxLimitControl::SetMin(unsigned long) __ptr64` | 1151 (0x47f) | Exported Function | 0x00000001800446d0 | 0x000446d0
`public: void __cdecl CMinMaxLimitControl::SetMax(unsigned long) __ptr64` | 1149 (0x47d) | Exported Function | 0x00000001800446c0 | 0x000446c0
`public: void __cdecl CMemoryLog::Write(void * __ptr64,unsigned long) __ptr64` | 1300 (0x514) | Exported Function | 0x00000001800458e0 | 0x000458e0
`public: void __cdecl CMemoryLog::Write(long) __ptr64` | 1299 (0x513) | Exported Function | 0x0000000180011d90 | 0x00011d90
`public: void __cdecl CMemoryLog::SetLogingEnabled(bool) __ptr64` | 1146 (0x47a) | Exported Function | 0x00000001800458d0 | 0x000458d0
`public: void __cdecl CLockableFlexArray<class CStaticCritSec>::Unlock(void) __ptr64` | 1264 (0x4f0) | Exported Function | 0x0000000180011a10 | 0x00011a10
`public: void __cdecl CLockableFlexArray<class CStaticCritSec>::Lock(void) __ptr64` | 971 (0x3cb) | Exported Function | 0x0000000180011710 | 0x00011710
`public: void __cdecl CClientOpsNode::Lock(void) __ptr64` | 972 (0x3cc) | Exported Function | 0x0000000180045cf0 | 0x00045cf0
`public: void __cdecl CLike::SetExpression(unsigned short const * __ptr64,unsigned short) __ptr64` | 1129 (0x469) | Exported Function | 0x0000000180031710 | 0x00031710
`public: void __cdecl CFlexQueue::ResetQueue(void) __ptr64` | 1070 (0x42e) | Exported Function | 0x000000018002f2b0 | 0x0002f2b0
`public: void __cdecl CFlexQueue::``default constructor closure'(void) __ptr64` | 439 (0x1b7) | Exported Function | 0x0000000180023df0 | 0x00023df0
`public: void __cdecl CFlexArray::Trim(void) __ptr64` | 1244 (0x4dc) | Exported Function | 0x0000000180011b80 | 0x00011b80
`public: void __cdecl CFlexArray::Sort(void) __ptr64` | 1208 (0x4b8) | Exported Function | 0x000000018002f000 | 0x0002f000
`public: void __cdecl CFlexArray::SetSize(int) __ptr64` | 1179 (0x49b) | Exported Function | 0x0000000180012b20 | 0x00012b20
`public: void __cdecl CFlexArray::SetAt(int,void * __ptr64) __ptr64` | 1094 (0x446) | Exported Function | 0x00000001800115b0 | 0x000115b0
`public: void __cdecl CFlexArray::Empty(void) __ptr64` | 605 (0x25d) | Exported Function | 0x0000000180004c50 | 0x00004c50
`public: void __cdecl CFlexArray::DebugDump(void) __ptr64` | 579 (0x243) | Exported Function | 0x000000018002ea60 | 0x0002ea60
`public: void __cdecl CInstructionQueue::BreakWait(void) __ptr64` | 508 (0x1fc) | Exported Function | 0x0000000180036430 | 0x00036430
`public: void __cdecl CClientOpsNode::AddChild(class CClientOpsNode * __ptr64) __ptr64` | 462 (0x1ce) | Exported Function | 0x0000000180011100 | 0x00011100
`public: void __cdecl CCheckedInCritSec::Leave(void) __ptr64` | 963 (0x3c3) | Exported Function | 0x0000000180011780 | 0x00011780
`public: void __cdecl CCheckedInCritSec::Enter(void) __ptr64` | 628 (0x274) | Exported Function | 0x0000000180011060 | 0x00011060
`public: void * __ptr64 * __ptr64 __cdecl CFlexArray::GetArrayPtr(void) __ptr64` | 674 (0x2a2) | Exported Function | 0x0000000180013110 | 0x00013110
`public: void * __ptr64 & __ptr64 __cdecl CFlexArray::operator[](int) __ptr64` | 352 (0x160) | Exported Function | 0x0000000180008340 | 0x00008340
`public: virtual void __cdecl QL_LEVEL_1_RPN_EXPRESSION::SetTolerance(struct _tag_WbemQl1Tolerance const & __ptr64) __ptr64` | 1185 (0x4a1) | Exported Function | 0x0000000180012eb0 | 0x00012eb0
`public: virtual void __cdecl QL_LEVEL_1_RPN_EXPRESSION::SetCountQuery(void) __ptr64` | 1112 (0x458) | Exported Function | 0x0000000180034660 | 0x00034660
`public: virtual void __cdecl QL_LEVEL_1_RPN_EXPRESSION::SetClassName(unsigned short const * __ptr64) __ptr64` | 1110 (0x456) | Exported Function | 0x0000000180012880 | 0x00012880
`public: virtual void __cdecl QL_LEVEL_1_RPN_EXPRESSION::SetAggregationTolerance(struct _tag_WbemQl1Tolerance const & __ptr64) __ptr64` | 1091 (0x443) | Exported Function | 0x0000000180034650 | 0x00034650
`public: virtual void __cdecl QL_LEVEL_1_RPN_EXPRESSION::SetAggregated(void) __ptr64` | 1090 (0x442) | Exported Function | 0x0000000180034640 | 0x00034640
`public: virtual void __cdecl QL_LEVEL_1_RPN_EXPRESSION::AddToken(struct _tag_WbemQl1Token const & __ptr64) __ptr64` | 487 (0x1e7) | Exported Function | 0x0000000180010810 | 0x00010810
`public: void * __ptr64 * __ptr64 __cdecl CFlexArray::UnbindPtr(void) __ptr64` | 1255 (0x4e7) | Exported Function | 0x000000018002f150 | 0x0002f150
`public: virtual void __cdecl QL_LEVEL_1_RPN_EXPRESSION::AddProperty(class CPropertyName const & __ptr64) __ptr64` | 474 (0x1da) | Exported Function | 0x00000001800106d0 | 0x000106d0
`public: virtual void __cdecl QL_LEVEL_1_RPN_EXPRESSION::AddAllProperties(void) __ptr64` | 457 (0x1c9) | Exported Function | 0x00000001800131e0 | 0x000131e0
`public: virtual void __cdecl QL_LEVEL_1_RPN_EXPRESSION::AddAllAggregationProperties(void) __ptr64` | 456 (0x1c8) | Exported Function | 0x0000000180033d60 | 0x00033d60
`public: virtual void __cdecl QL_LEVEL_1_RPN_EXPRESSION::AddAggregationProperty(class CPropertyName const & __ptr64) __ptr64` | 455 (0x1c7) | Exported Function | 0x0000000180033bc0 | 0x00033bc0
`public: virtual void __cdecl CQl1ParseSink::InOrder(long) __ptr64` | 880 (0x370) | Exported Function | 0x000000018000a140 | 0x0000a140
`public: virtual void __cdecl CNtAce::SetFlags(long) __ptr64` | 1134 (0x46e) | Exported Function | 0x0000000180024a70 | 0x00024a70
`public: virtual void __cdecl CExecRequest::DumpError(void) __ptr64` | 602 (0x25a) | Exported Function | 0x000000018002d6e0 | 0x0002d6e0
`public: virtual void __cdecl CContainerControl::Release(struct IUnknown * __ptr64) __ptr64` | 1043 (0x413) | Exported Function | 0x000000018002c0f0 | 0x0002c0f0
`public: virtual void __cdecl CContainerControl::ObjectDestroyed(struct IUnknown * __ptr64) __ptr64` | 992 (0x3e0) | Exported Function | 0x000000018000a140 | 0x0000a140
`public: virtual void __cdecl QL_LEVEL_1_RPN_EXPRESSION::AddHavingToken(struct _tag_WbemQl1Token const & __ptr64) __ptr64` | 469 (0x1d5) | Exported Function | 0x0000000180033d70 | 0x00033d70
`public: void __cdecl CMRCIControl::AbortCompression(void) __ptr64` | 444 (0x1bc) | Exported Function | 0x0000000180031a60 | 0x00031a60
`public: void * __ptr64 * __ptr64 __cdecl CSmallArrayBlob::CloneData(void) __ptr64` | 531 (0x213) | Exported Function | 0x0000000180035990 | 0x00035990
`public: void * __ptr64 __cdecl CClientOpsNode::GetInfo(void) __ptr64` | 738 (0x2e2) | Exported Function | 0x0000000180013260 | 0x00013260
`public: void __cdecl CBuffer::Reset(void) __ptr64` | 1066 (0x42a) | Exported Function | 0x0000000180023720 | 0x00023720
`public: void __cdecl CBuffer::``default constructor closure'(void) __ptr64` | 436 (0x1b4) | Exported Function | 0x0000000180023100 | 0x00023100
`public: void __cdecl CBasicUnloadInstruction::Terminate(void) __ptr64` | 1222 (0x4c6) | Exported Function | 0x00000001800147c0 | 0x000147c0
`public: void __cdecl CBasicUnloadInstruction::SetInterval(class CWbemInterval & __ptr64) __ptr64` | 1143 (0x477) | Exported Function | 0x00000001800436a0 | 0x000436a0
`public: void * __ptr64 const * __ptr64 __cdecl CSmallArrayBlob::GetArrayPtr(void)const __ptr64` | 677 (0x2a5) | Exported Function | 0x0000000180013340 | 0x00013340
`public: void * __ptr64 const * __ptr64 __cdecl CFlexArray::GetArrayPtr(void)const __ptr64` | 675 (0x2a3) | Exported Function | 0x0000000180013110 | 0x00013110
`public: void * __ptr64 __cdecl CVar::GetRawData(void) __ptr64` | 796 (0x31c) | Exported Function | 0x0000000180013340 | 0x00013340
`public: void * __ptr64 __cdecl CSmallArrayBlob::operator[](int)const __ptr64` | 354 (0x162) | Exported Function | 0x00000001800149e0 | 0x000149e0
`public: void * __ptr64 * __ptr64 __cdecl CSmallArrayBlob::GetArrayPtr(void) __ptr64` | 676 (0x2a4) | Exported Function | 0x0000000180013340 | 0x00013340
`public: void * __ptr64 __cdecl CSmallArrayBlob::GetAt(int)const __ptr64` | 680 (0x2a8) | Exported Function | 0x00000001800149e0 | 0x000149e0
`public: void * __ptr64 __cdecl CNtSid::GetPtr(void) __ptr64` | 788 (0x314) | Exported Function | 0x00000001800117b0 | 0x000117b0
`public: void * __ptr64 __cdecl CNtSecurityDescriptor::GetPtr(void) __ptr64` | 787 (0x313) | Exported Function | 0x00000001800117b0 | 0x000117b0
`public: void * __ptr64 __cdecl CFlexQueue::Unqueue(void) __ptr64` | 1267 (0x4f3) | Exported Function | 0x0000000180023eb0 | 0x00023eb0
`public: void * __ptr64 __cdecl CFlexQueue::Peek(void) __ptr64` | 1004 (0x3ec) | Exported Function | 0x000000018002f220 | 0x0002f220
`public: void * __ptr64 __cdecl CFlexQueue::Dequeue(void) __ptr64` | 589 (0x24d) | Exported Function | 0x0000000180011900 | 0x00011900
`public: void * __ptr64 __cdecl CFlexArray::operator[](int)const __ptr64` | 353 (0x161) | Exported Function | 0x000000018000bf20 | 0x0000bf20
`public: void * __ptr64 __cdecl CFlexArray::GetAt(int)const __ptr64` | 679 (0x2a7) | Exported Function | 0x0000000180004c20 | 0x00004c20
`public: void * __ptr64 __cdecl CExecRequest::GetWhenDoneHandle(void) __ptr64` | 867 (0x363) | Exported Function | 0x0000000180010d00 | 0x00010d00
`public: void * __ptr64 __cdecl CPropertyName::GetHandle(void) __ptr64` | 732 (0x2dc) | Exported Function | 0x0000000180034420 | 0x00034420
`public: void __cdecl CMRCIControl::Reset(void) __ptr64` | 1067 (0x42b) | Exported Function | 0x0000000180031ee0 | 0x00031ee0
`public: void __cdecl CNtAcl::``default constructor closure'(void) __ptr64` | 440 (0x1b8) | Exported Function | 0x0000000180024440 | 0x00024440
`public: void __cdecl CPropertyName::AddElement(unsigned short const * __ptr64) __ptr64` | 466 (0x1d2) | Exported Function | 0x0000000180005530 | 0x00005530
`public: void __cdecl WString2::Unquote(void) __ptr64` | 1268 (0x4f4) | Exported Function | 0x00000001800427b0 | 0x000427b0
`public: void __cdecl WString2::Empty(void) __ptr64` | 611 (0x263) | Exported Function | 0x0000000180002a50 | 0x00002a50
`public: void __cdecl WString2::BindPtr(unsigned short * __ptr64) __ptr64` | 502 (0x1f6) | Exported Function | 0x0000000180042140 | 0x00042140
`public: void __cdecl QL_LEVEL_1_TOKEN::Dump(struct _iobuf * __ptr64) __ptr64` | 600 (0x258) | Exported Function | 0x0000000180034060 | 0x00034060
`public: void __cdecl QL_LEVEL_1_RPN_EXPRESSION::Release(void) __ptr64` | 1048 (0x418) | Exported Function | 0x000000018000c330 | 0x0000c330
`public: void __cdecl QL_LEVEL_1_RPN_EXPRESSION::Dump(char const * __ptr64) __ptr64` | 599 (0x257) | Exported Function | 0x0000000180033ef0 | 0x00033ef0
`public: void __cdecl QL_LEVEL_1_RPN_EXPRESSION::AddToken(struct QL_LEVEL_1_TOKEN const & __ptr64) __ptr64` | 486 (0x1e6) | Exported Function | 0x0000000180010500 | 0x00010500
`public: void __cdecl QL_LEVEL_1_RPN_EXPRESSION::AddRef(void) __ptr64` | 483 (0x1e3) | Exported Function | 0x0000000180013270 | 0x00013270
`public: void __cdecl WString::BindPtr(unsigned short * __ptr64) __ptr64` | 503 (0x1f7) | Exported Function | 0x0000000180012940 | 0x00012940
`public: void __cdecl CWStringArray::Sort(void) __ptr64` | 1210 (0x4ba) | Exported Function | 0x000000018002f040 | 0x0002f040
`public: void __cdecl CWStringArray::Compress(void) __ptr64` | 544 (0x220) | Exported Function | 0x0000000180023e40 | 0x00023e40
`public: void __cdecl CWStringArray::``default constructor closure'(void) __ptr64` | 443 (0x1bb) | Exported Function | 0x0000000180023e00 | 0x00023e00
`public: void __cdecl CWQLScanner::Dump(void) __ptr64` | 598 (0x256) | Exported Function | 0x0000000180042e10 | 0x00042e10
`public: void __cdecl CWMITraceSettings::SetTraceLevel(unsigned char) __ptr64` | 1186 (0x4a2) | Exported Function | 0x00000001800462a0 | 0x000462a0
`public: void __cdecl CWMITraceSettings::SetAreaFlags(unsigned long) __ptr64` | 1092 (0x444) | Exported Function | 0x000000018002d000 | 0x0002d000
`public: void __cdecl CWbemTime::Set100nss(__int64) __ptr64` | 1088 (0x440) | Exported Function | 0x0000000180025020 | 0x00025020
`public: void __cdecl CWbemTime::operator=(class CWbemTime const & __ptr64) __ptr64` | 330 (0x14a) | Exported Function | 0x0000000180013540 | 0x00013540
`public: void __cdecl CWbemInterval::SetMilliseconds(unsigned long) __ptr64` | 1150 (0x47e) | Exported Function | 0x0000000180012b20 | 0x00012b20
`public: void __cdecl CWStringArray::Empty(void) __ptr64` | 610 (0x262) | Exported Function | 0x0000000180007210 | 0x00007210
`public: void __cdecl CWbemInterval::operator+=(class CWbemInterval) __ptr64` | 402 (0x192) | Exported Function | 0x0000000180024c50 | 0x00024c50
`public: void __cdecl WString::Empty(void) __ptr64` | 612 (0x264) | Exported Function | 0x000000018000b730 | 0x0000b730
`ReadI64` | 1031 (0x407) | Exported Function | 0x00000001800101f0 | 0x000101f0
`WinPEKey` | 1297 (0x511) | Exported Function | 0x000000018000e470 | 0x0000e470
`WbemVariantChangeType` | 1295 (0x50f) | Exported Function | 0x0000000180012520 | 0x00012520
`WbemSetMachineShutdown` | 1288 (0x508) | Exported Function | 0x0000000180039c70 | 0x00039c70
`WbemSetDynamicCloaking` | 1287 (0x507) | Exported Function | 0x0000000180030f50 | 0x00030f50
`WbemGetMachineShutdown` | 1279 (0x4ff) | Exported Function | 0x0000000180039c60 | 0x00039c60
`UnregisterDllAppid` | 1271 (0x4f7) | Exported Function | 0x0000000180030c30 | 0x00030c30
`UnRegisterDLL` | 1252 (0x4e4) | Exported Function | 0x0000000180030990 | 0x00030990
`Throttle` | 1225 (0x4c9) | Exported Function | 0x000000018000d840 | 0x0000d840
`public: void __cdecl WString::Unquote(void) __ptr64` | 1269 (0x4f5) | Exported Function | 0x0000000180041ab0 | 0x00041ab0
`TestDirExistAndCreateWithSDIfNotThere` | 1223 (0x4c7) | Exported Function | 0x000000018000e360 | 0x0000e360
`SetObjectAccess2` | 1154 (0x482) | Exported Function | 0x00000001800409b0 | 0x000409b0
`Set_WPP_INIT_TRACING_Call_State` | 1195 (0x4ab) | Exported Function | 0x00000001800135b0 | 0x000135b0
`RetrieveSidFromToken` | 1076 (0x434) | Exported Function | 0x00000001800249a0 | 0x000249a0
`RetrieveSidFromCall` | 1075 (0x433) | Exported Function | 0x0000000180024790 | 0x00024790
`RemoveFileFromAutoRecoverFolder` | 1058 (0x422) | Exported Function | 0x0000000180047570 | 0x00047570
`RegisterDllAppid` | 1040 (0x410) | Exported Function | 0x000000018002fb50 | 0x0002fb50
`RegisterDLL` | 1039 (0x40f) | Exported Function | 0x000000018002f670 | 0x0002f670
`ReadUI64` | 1033 (0x409) | Exported Function | 0x0000000180010180 | 0x00010180
`SetWMITraceSession` | 1192 (0x4a8) | Exported Function | 0x00000001800462b0 | 0x000462b0
`public: virtual void __cdecl CContainerControl::AddRef(struct IUnknown * __ptr64) __ptr64` | 478 (0x1de) | Exported Function | 0x000000018002be50 | 0x0002be50
`public: void __cdecl CWbemCriticalSection::Leave(void) __ptr64` | 967 (0x3c7) | Exported Function | 0x0000000180012d00 | 0x00012d00
`public: void __cdecl CVarVector::FillCVarAt(int,class CVar & __ptr64) __ptr64` | 651 (0x28b) | Exported Function | 0x0000000180006ec0 | 0x00006ec0
`public: void __cdecl CVar::Empty(void) __ptr64` | 608 (0x260) | Exported Function | 0x0000000180006e30 | 0x00006e30
`public: void __cdecl CUnk::``default constructor closure'(void) __ptr64` | 442 (0x1ba) | Exported Function | 0x000000018002bcb0 | 0x0002bcb0
`public: void __cdecl CTimerGenerator::ScheduleFreeUnusedLibraries(void) __ptr64` | 1080 (0x438) | Exported Function | 0x0000000180036620 | 0x00036620
`public: void __cdecl CTextTemplate::SetTemplate(unsigned short const * __ptr64) __ptr64` | 1183 (0x49f) | Exported Function | 0x0000000180037c30 | 0x00037c30
`public: void __cdecl CTextTemplate::``default constructor closure'(void) __ptr64` | 441 (0x1b9) | Exported Function | 0x0000000180036880 | 0x00036880
`public: void __cdecl CStaticCritSec::Leave(void) __ptr64` | 966 (0x3c6) | Exported Function | 0x0000000180012790 | 0x00012790
`public: void __cdecl CStaticCritSec::Enter(void) __ptr64` | 631 (0x277) | Exported Function | 0x0000000180011210 | 0x00011210
`public: void __cdecl CSmallArrayBlob::Trim(void) __ptr64` | 1246 (0x4de) | Exported Function | 0x0000000180035b80 | 0x00035b80
`public: void __cdecl CVar::FillVariant(struct tagVARIANT * __ptr64,int) __ptr64` | 653 (0x28d) | Exported Function | 0x0000000180005920 | 0x00005920
`public: void __cdecl CSmallArrayBlob::Sort(void) __ptr64` | 1209 (0x4b9) | Exported Function | 0x0000000180035b50 | 0x00035b50
`public: void __cdecl CSafeArray::SetGrowGranularity(int) __ptr64` | 1139 (0x473) | Exported Function | 0x000000018002d0c0 | 0x0002d0c0
`public: void __cdecl CSafeArray::SetDestructorPolicy(int) __ptr64` | 1122 (0x462) | Exported Function | 0x000000018002d000 | 0x0002d000
`public: void __cdecl CSafeArray::Empty(void) __ptr64` | 607 (0x25f) | Exported Function | 0x00000001800353d0 | 0x000353d0
`public: void __cdecl CPropertyName::SetHandle(void * __ptr64) __ptr64` | 1140 (0x474) | Exported Function | 0x0000000180034670 | 0x00034670
`public: void __cdecl CPropertyName::operator=(struct _tag_WbemPropertyName const & __ptr64) __ptr64` | 301 (0x12d) | Exported Function | 0x0000000180010a90 | 0x00010a90
`public: void __cdecl CPropertyName::operator=(class CPropertyName const & __ptr64) __ptr64` | 302 (0x12e) | Exported Function | 0x0000000180010610 | 0x00010610
`public: void __cdecl CPropertyName::Init(void) __ptr64` | 882 (0x372) | Exported Function | 0x0000000180034550 | 0x00034550
`public: void __cdecl CPropertyName::Empty(void) __ptr64` | 606 (0x25e) | Exported Function | 0x0000000180005fd0 | 0x00005fd0
`public: void __cdecl CSafeArray::SetRawArrayMaxElement(int) __ptr64` | 1165 (0x48d) | Exported Function | 0x0000000180012b20 | 0x00012b20
`public: void __cdecl CVarVector::SetRawArrayBinding(int) __ptr64` | 1163 (0x48b) | Exported Function | 0x00000001800388e0 | 0x000388e0
`public: void __cdecl CVar::SetAsNull(void) __ptr64` | 1093 (0x445) | Exported Function | 0x0000000180011d40 | 0x00011d40
`public: void __cdecl CVar::SetBool(short) __ptr64` | 1104 (0x450) | Exported Function | 0x000000018002cf40 | 0x0002cf40
`public: void __cdecl CVarVector::Empty(void) __ptr64` | 609 (0x261) | Exported Function | 0x000000018000c370 | 0x0000c370
`public: void __cdecl CVar::SetWord(unsigned short) __ptr64` | 1194 (0x4aa) | Exported Function | 0x000000018002d110 | 0x0002d110
`public: void __cdecl CVar::SetVarVector(class CVarVector * __ptr64,int) __ptr64` | 1189 (0x4a5) | Exported Function | 0x0000000180011fb0 | 0x00011fb0
`public: void __cdecl CVar::SetUnknown(struct IUnknown * __ptr64) __ptr64` | 1187 (0x4a3) | Exported Function | 0x00000001800389f0 | 0x000389f0
`public: void __cdecl CVar::SetShort(short) __ptr64` | 1175 (0x497) | Exported Function | 0x000000018002d0f0 | 0x0002d0f0
`public: void __cdecl CVar::SetSafeArray(int,struct tagSAFEARRAY * __ptr64) __ptr64` | 1173 (0x495) | Exported Function | 0x0000000180038900 | 0x00038900
`public: void __cdecl CVar::SetRaw(int,void * __ptr64,int) __ptr64` | 1162 (0x48a) | Exported Function | 0x0000000180011950 | 0x00011950
`public: void __cdecl CVar::SetLong(long) __ptr64` | 1147 (0x47b) | Exported Function | 0x0000000180011720 | 0x00011720
`public: void __cdecl CVar::SetBlob(struct tagBLOB * __ptr64,int) __ptr64` | 1103 (0x44f) | Exported Function | 0x0000000180038680 | 0x00038680
`public: void __cdecl CVar::SetFloat(float) __ptr64` | 1135 (0x46f) | Exported Function | 0x000000018002d080 | 0x0002d080
`public: void __cdecl CVar::SetEmbeddedObject(struct IUnknown * __ptr64) __ptr64` | 1127 (0x467) | Exported Function | 0x000000018002d050 | 0x0002d050
`public: void __cdecl CVar::SetDWORD(unsigned long) __ptr64` | 1114 (0x45a) | Exported Function | 0x000000018002cfe0 | 0x0002cfe0
`public: void __cdecl CVar::SetDouble(double) __ptr64` | 1125 (0x465) | Exported Function | 0x000000018002d010 | 0x0002d010
`public: void __cdecl CVar::SetDispatch(struct IDispatch * __ptr64) __ptr64` | 1123 (0x463) | Exported Function | 0x0000000180038780 | 0x00038780
`public: void __cdecl CVar::SetClsId(struct _GUID * __ptr64,int) __ptr64` | 1111 (0x457) | Exported Function | 0x00000001800386d0 | 0x000386d0
`public: void __cdecl CVar::SetChar(char) __ptr64` | 1109 (0x455) | Exported Function | 0x000000018002cfc0 | 0x0002cfc0
`public: void __cdecl CVar::SetCanDelete(int) __ptr64` | 1108 (0x454) | Exported Function | 0x00000001800123f0 | 0x000123f0
`public: void __cdecl CVar::SetByte(unsigned char) __ptr64` | 1106 (0x452) | Exported Function | 0x000000018002cf80 | 0x0002cf80
`public: void __cdecl CVar::SetFileTime(struct _FILETIME * __ptr64) __ptr64` | 1131 (0x46b) | Exported Function | 0x000000018002d060 | 0x0002d060
`public: class WString2 __cdecl WString2::EscapeQuotes(void)const __ptr64` | 638 (0x27e) | Exported Function | 0x0000000180042190 | 0x00042190
`public: virtual void __cdecl CBasicUnloadInstruction::Release(void) __ptr64` | 1041 (0x411) | Exported Function | 0x0000000180013380 | 0x00013380
`public: virtual void __cdecl C9XAce::SetFlags(long) __ptr64` | 1133 (0x46d) | Exported Function | 0x0000000180024a60 | 0x00024a60
`public: unsigned short * __ptr64 __cdecl CTextTemplate::Apply(struct IWbemClassObject * __ptr64) __ptr64` | 500 (0x1f4) | Exported Function | 0x00000001800368c0 | 0x000368c0
`public: unsigned short * __ptr64 __cdecl CSafeArray::GetBSTRAtThrow(int) __ptr64` | 687 (0x2af) | Exported Function | 0x00000001800130c0 | 0x000130c0
`public: unsigned short * __ptr64 __cdecl CSafeArray::GetBSTRAt(int) __ptr64` | 686 (0x2ae) | Exported Function | 0x0000000180035460 | 0x00035460
`public: unsigned short * __ptr64 __cdecl CPropertyName::GetText(void) __ptr64` | 838 (0x346) | Exported Function | 0x0000000180002620 | 0x00002620
`public: unsigned short * __ptr64 __cdecl CAbstractQl1Parser::CurrentToken(void) __ptr64` | 563 (0x233) | Exported Function | 0x0000000180013260 | 0x00013260
`public: unsigned long __cdecl CWMITraceSettings::WriteToRegistry(unsigned short const * __ptr64) __ptr64` | 1302 (0x516) | Exported Function | 0x0000000180046630 | 0x00046630
`public: unsigned long __cdecl CWMITraceSettings::SetDefaultValues(void) __ptr64` | 1121 (0x461) | Exported Function | 0x0000000180046010 | 0x00046010
`public: unsigned long __cdecl CWMITraceSettings::ReadFromRegistry(unsigned short const * __ptr64) __ptr64` | 1030 (0x406) | Exported Function | 0x0000000180045e10 | 0x00045e10
`public: unsigned long __cdecl CWMITraceSettings::GetAreaFlags(void) __ptr64` | 670 (0x29e) | Exported Function | 0x0000000180023e80 | 0x00023e80
`public: unsigned long __cdecl CWbemInterval::GetSeconds(void)const __ptr64` | 809 (0x329) | Exported Function | 0x0000000180024fd0 | 0x00024fd0
`public: unsigned long __cdecl CWbemInterval::GetMilliseconds(void)const __ptr64` | 758 (0x2f6) | Exported Function | 0x0000000180010290 | 0x00010290
`public: unsigned long __cdecl CWbemCriticalSection::GetOwningThreadId(void) __ptr64` | 775 (0x307) | Exported Function | 0x0000000180011410 | 0x00011410
`public: unsigned long __cdecl CVar::GetDWORD(void) __ptr64` | 703 (0x2bf) | Exported Function | 0x0000000180011410 | 0x00011410
`public: unsigned long __cdecl CUnkInternal::InternalRelease(void) __ptr64` | 901 (0x385) | Exported Function | 0x0000000180012370 | 0x00012370
`public: unsigned long __cdecl CUnkInternal::InternalAddRef(void) __ptr64` | 898 (0x382) | Exported Function | 0x0000000180012770 | 0x00012770
`public: unsigned long __cdecl CTraceSessionControl::Initialize(unsigned short const * __ptr64) __ptr64` | 890 (0x37a) | Exported Function | 0x0000000180045c80 | 0x00045c80
`public: unsigned long __cdecl CTraceSessionControl::Enable(void) __ptr64` | 613 (0x265) | Exported Function | 0x0000000180045b10 | 0x00045b10
`public: unsigned short * __ptr64 __cdecl CVar::GetBSTR(void) __ptr64` | 685 (0x2ad) | Exported Function | 0x0000000180001310 | 0x00001310
`public: unsigned short * __ptr64 __cdecl CVar::GetLPWSTR(void) __ptr64` | 745 (0x2e9) | Exported Function | 0x0000000180010d00 | 0x00010d00
`public: unsigned short * __ptr64 __cdecl CVar::GetText(long,long,unsigned short const * __ptr64) __ptr64` | 839 (0x347) | Exported Function | 0x0000000180008970 | 0x00008970
`public: unsigned short * __ptr64 __cdecl CVar::GetTypeText(void) __ptr64` | 856 (0x358) | Exported Function | 0x0000000180038550 | 0x00038550
`public: unsigned short const * __ptr64 __cdecl CEventLogRecord::GetStringAt(int) __ptr64` | 834 (0x342) | Exported Function | 0x000000018002c020 | 0x0002c020
`public: unsigned short const * __ptr64 * __ptr64 __cdecl CWStringArray::GetArrayPtr(void) __ptr64` | 678 (0x2a6) | Exported Function | 0x0000000180013110 | 0x00013110
`public: unsigned short __cdecl WString::operator[](int)const __ptr64` | 358 (0x166) | Exported Function | 0x0000000180040fd0 | 0x00040fd0
`public: unsigned short __cdecl WString2::operator[](int)const __ptr64` | 357 (0x165) | Exported Function | 0x0000000180041f90 | 0x00041f90
`public: unsigned short __cdecl CVar::GetWord(void) __ptr64` | 868 (0x364) | Exported Function | 0x0000000180012d30 | 0x00012d30
`public: unsigned short __cdecl CEventLogRecord::GetNumStrings(void) __ptr64` | 772 (0x304) | Exported Function | 0x000000018002c010 | 0x0002c010
`public: unsigned short * __ptr64 __cdecl WString::UnbindPtr(void) __ptr64` | 1257 (0x4e9) | Exported Function | 0x00000001800128d0 | 0x000128d0
`public: unsigned short * __ptr64 __cdecl WString::GetLToken(unsigned short)const __ptr64` | 747 (0x2eb) | Exported Function | 0x0000000180041640 | 0x00041640
`public: unsigned long __cdecl CTraceSessionControl::Disable(void) __ptr64` | 594 (0x252) | Exported Function | 0x0000000180045a80 | 0x00045a80
`public: unsigned short * __ptr64 __cdecl WString2::UnbindPtr(void) __ptr64` | 1256 (0x4e8) | Exported Function | 0x0000000180003680 | 0x00003680
`public: unsigned short * __ptr64 __cdecl Registry::GetMultiStr(unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 761 (0x2f9) | Exported Function | 0x0000000180034f00 | 0x00034f00
`public: unsigned short * __ptr64 __cdecl QL_LEVEL_1_TOKEN::GetText(void) __ptr64` | 842 (0x34a) | Exported Function | 0x0000000180002fe0 | 0x00002fe0
`public: unsigned short * __ptr64 __cdecl QL_LEVEL_1_RPN_EXPRESSION::GetText(void) __ptr64` | 841 (0x349) | Exported Function | 0x0000000180002cd0 | 0x00002cd0
`public: unsigned short * __ptr64 __cdecl CWStringArray::operator[](int)const __ptr64` | 356 (0x164) | Exported Function | 0x00000001800104d0 | 0x000104d0
`public: unsigned short * __ptr64 __cdecl CWStringArray::GetAt(int)const __ptr64` | 682 (0x2aa) | Exported Function | 0x000000018000be90 | 0x0000be90
`public: unsigned short * __ptr64 __cdecl CWQLScanner::AliasToTable(unsigned short * __ptr64) __ptr64` | 494 (0x1ee) | Exported Function | 0x0000000180042bb0 | 0x00042bb0
`public: unsigned short * __ptr64 __cdecl CWMITraceSettings::GetSessionName(void) __ptr64` | 814 (0x32e) | Exported Function | 0x0000000180045ba0 | 0x00045ba0
`public: unsigned short * __ptr64 __cdecl CVarVector::GetText(long,long) __ptr64` | 840 (0x348) | Exported Function | 0x00000001800135e0 | 0x000135e0
`public: unsigned short * __ptr64 __cdecl WString2::GetLToken(unsigned short)const __ptr64` | 746 (0x2ea) | Exported Function | 0x0000000180041640 | 0x00041640
`public: unsigned long __cdecl CNtSid::GetStatus(void) __ptr64` | 831 (0x33f) | Exported Function | 0x0000000180011410 | 0x00011410
`public: unsigned long __cdecl CNtSid::GetSize(void) __ptr64` | 826 (0x33a) | Exported Function | 0x000000018000bb20 | 0x0000bb20
`public: unsigned long __cdecl CNtSecurityDescriptor::GetStatus(void) __ptr64` | 830 (0x33e) | Exported Function | 0x0000000180011410 | 0x00011410
`public: unsigned char __cdecl CDateTimeParser::GetHours(void) __ptr64` | 733 (0x2dd) | Exported Function | 0x0000000180025160 | 0x00025160
`public: unsigned char __cdecl CDateTimeParser::GetDay(void) __ptr64` | 709 (0x2c5) | Exported Function | 0x0000000180025150 | 0x00025150
`public: unsigned char * __ptr64 __cdecl CBuffer::GetRawData(void) __ptr64` | 794 (0x31a) | Exported Function | 0x0000000180013110 | 0x00013110
`public: struct tagVARIANT __cdecl CSafeArray::GetVariantAt(int) __ptr64` | 864 (0x360) | Exported Function | 0x0000000180035590 | 0x00035590
`public: struct tagVARIANT * __ptr64 __cdecl CVar::GetNewVariant(void) __ptr64` | 764 (0x2fc) | Exported Function | 0x0000000180005890 | 0x00005890
`public: struct tagSAFEARRAY * __ptr64 __cdecl CVarVector::GetSafeArray(int) __ptr64` | 806 (0x326) | Exported Function | 0x0000000180005730 | 0x00005730
`public: struct tagSAFEARRAY * __ptr64 __cdecl CVarVector::GetNewSafeArray(void) __ptr64` | 763 (0x2fb) | Exported Function | 0x0000000180006c30 | 0x00006c30
`public: struct tagSAFEARRAY * __ptr64 __cdecl CVar::GetNewSafeArray(void) __ptr64` | 762 (0x2fa) | Exported Function | 0x00000001800384c0 | 0x000384c0
`public: unsigned char __cdecl CDateTimeParser::GetMinutes(void) __ptr64` | 759 (0x2f7) | Exported Function | 0x0000000180025180 | 0x00025180
`public: struct tagSAFEARRAY * __ptr64 __cdecl CSafeArray::GetArrayCopy(void) __ptr64` | 673 (0x2a1) | Exported Function | 0x0000000180013030 | 0x00013030
`public: struct tagBLOB * __ptr64 __cdecl CVar::GetBlob(void) __ptr64` | 690 (0x2b2) | Exported Function | 0x0000000180013340 | 0x00013340
`public: struct SZLess<unsigned short const * __ptr64> & __ptr64 __cdecl SZLess<unsigned short const * __ptr64>::operator=(struct SZLess<unsigned short const * __ptr64> const & __ptr64) __ptr64` | 243 (0xf3) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: struct SNtAbsoluteSD * __ptr64 __cdecl CNtSecurityDescriptor::GetAbsoluteCopy(void) __ptr64` | 661 (0x295) | Exported Function | 0x0000000180008dc0 | 0x00008dc0
`public: struct QL_LEVEL_1_TOKEN & __ptr64 __cdecl QL_LEVEL_1_TOKEN::operator=(struct QL_LEVEL_1_TOKEN const & __ptr64) __ptr64` | 338 (0x152) | Exported Function | 0x00000001800109a0 | 0x000109a0
`public: struct QL_LEVEL_1_TOKEN & __ptr64 __cdecl QL_LEVEL_1_TOKEN::operator=(struct _tag_WbemQl1Token const & __ptr64) __ptr64` | 339 (0x153) | Exported Function | 0x0000000180010920 | 0x00010920
`public: struct QL_LEVEL_1_RPN_EXPRESSION & __ptr64 __cdecl QL_LEVEL_1_RPN_EXPRESSION::operator=(struct QL_LEVEL_1_RPN_EXPRESSION const & __ptr64) __ptr64` | 337 (0x151) | Exported Function | 0x0000000180033910 | 0x00033910
`public: struct IUnknown * __ptr64 __cdecl CVar::GetUnknown(void) __ptr64` | 860 (0x35c) | Exported Function | 0x000000018002bf40 | 0x0002bf40
`public: struct IUnknown * __ptr64 __cdecl CVar::GetEmbeddedObject(void) __ptr64` | 715 (0x2cb) | Exported Function | 0x000000018002bfb0 | 0x0002bfb0
`public: struct tagSAFEARRAY * __ptr64 __cdecl CSafeArray::GetArray(void) __ptr64` | 672 (0x2a0) | Exported Function | 0x0000000180013260 | 0x00013260
`public: unsigned short const * __ptr64 __cdecl CInsertionString::GetString(void) __ptr64` | 833 (0x341) | Exported Function | 0x0000000180010d00 | 0x00010d00
`public: unsigned char __cdecl CDateTimeParser::GetMonth(void) __ptr64` | 760 (0x2f8) | Exported Function | 0x0000000180025190 | 0x00025190
`public: unsigned char __cdecl CSafeArray::GetByteAt(int) __ptr64` | 694 (0x2b6) | Exported Function | 0x000000018002bf00 | 0x0002bf00
`public: unsigned long __cdecl CNtSecurityDescriptor::GetSize(void) __ptr64` | 825 (0x339) | Exported Function | 0x000000018003f2b0 | 0x0003f2b0
`public: unsigned long __cdecl CNtAcl::GetStatus(void) __ptr64` | 829 (0x33d) | Exported Function | 0x0000000180011410 | 0x00011410
`public: unsigned long __cdecl CNtAcl::GetSize(void) __ptr64` | 824 (0x338) | Exported Function | 0x000000018003f270 | 0x0003f270
`public: unsigned long __cdecl CNtAce::GetSize(void) __ptr64` | 823 (0x337) | Exported Function | 0x00000001800245c0 | 0x000245c0
`public: unsigned long __cdecl CExecQueue::GetSitoutPenalty(void) __ptr64` | 821 (0x335) | Exported Function | 0x000000018002da80 | 0x0002da80
`public: unsigned long __cdecl CCircularQueue::GetNextElement(struct LOG_ELEMENT * __ptr64 * __ptr64) __ptr64` | 767 (0x2ff) | Exported Function | 0x00000001800458a0 | 0x000458a0
`public: unsigned long __cdecl CBuffer::GetSize(void) __ptr64` | 822 (0x336) | Exported Function | 0x0000000180023510 | 0x00023510
`public: unsigned long __cdecl CBuffer::GetIndex(void) __ptr64` | 735 (0x2df) | Exported Function | 0x0000000180013560 | 0x00013560
`public: unsigned char __cdecl CDateTimeParser::GetSeconds(void) __ptr64` | 808 (0x328) | Exported Function | 0x0000000180025300 | 0x00025300
`public: unsigned int __cdecl CMRCICompression::UncompressBuffer(unsigned char * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long,enum CMRCICompression::CompressionLevel) __ptr64` | 1259 (0x4eb) | Exported Function | 0x0000000180031ef0 | 0x00031ef0
`public: unsigned int __cdecl CDateTimeParser::GetYear(void) __ptr64` | 869 (0x365) | Exported Function | 0x0000000180025340 | 0x00025340
`public: unsigned int __cdecl CDateTimeParser::GetMicroseconds(void) __ptr64` | 757 (0x2f5) | Exported Function | 0x0000000180025170 | 0x00025170
`public: unsigned int __cdecl CBaseMrciCompression::Mrci2MaxCompress(unsigned char * __ptr64,unsigned int,unsigned char * __ptr64,unsigned int) __ptr64` | 985 (0x3d9) | Exported Function | 0x0000000180032900 | 0x00032900
`public: unsigned int __cdecl CBaseMrciCompression::Mrci2Decompress(unsigned char * __ptr64,unsigned int,unsigned char * __ptr64,unsigned int) __ptr64` | 984 (0x3d8) | Exported Function | 0x0000000180032750 | 0x00032750
`public: unsigned int __cdecl CBaseMrciCompression::Mrci1MaxCompress(unsigned char * __ptr64,unsigned int,unsigned char * __ptr64,unsigned int) __ptr64` | 983 (0x3d7) | Exported Function | 0x0000000180032340 | 0x00032340
`public: unsigned int __cdecl CBaseMrciCompression::Mrci1Decompress(unsigned char * __ptr64,unsigned int,unsigned char * __ptr64,unsigned int) __ptr64` | 982 (0x3d6) | Exported Function | 0x00000001800321a0 | 0x000321a0
`public: unsigned char __cdecl CWMITraceSettings::GetTraceLevel(void) __ptr64` | 848 (0x350) | Exported Function | 0x0000000180025380 | 0x00025380
`public: unsigned char __cdecl CVar::GetByte(void) __ptr64` | 693 (0x2b5) | Exported Function | 0x000000018002baa0 | 0x0002baa0
`public: unsigned int __cdecl CMRCICompression::CompressBuffer(unsigned char * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long,enum CMRCICompression::CompressionLevel) __ptr64` | 545 (0x221) | Exported Function | 0x0000000180031a70 | 0x00031a70
`public: unsigned short const * __ptr64 __cdecl CLike::GetExpression(void) __ptr64` | 718 (0x2ce) | Exported Function | 0x00000001800117b0 | 0x000117b0
`public: unsigned short const * __ptr64 __cdecl CMUILocaleList::GetCultures(void) __ptr64` | 701 (0x2bd) | Exported Function | 0x00000001800117b0 | 0x000117b0
`public: unsigned short const * __ptr64 __cdecl CMUILocaleList::GetLocales(void) __ptr64` | 751 (0x2ef) | Exported Function | 0x0000000180013110 | 0x00013110
`public: virtual long __cdecl CWbemCallSecurity::ImpersonateClient(void) __ptr64` | 879 (0x36f) | Exported Function | 0x0000000180011a90 | 0x00011a90
`public: virtual long __cdecl CWbemCallSecurity::GetPotentialImpersonation(void) __ptr64` | 778 (0x30a) | Exported Function | 0x0000000180023510 | 0x00023510
`public: virtual long __cdecl CWbemCallSecurity::GetActiveImpersonation(void) __ptr64` | 668 (0x29c) | Exported Function | 0x0000000180013560 | 0x00013560
`public: virtual long __cdecl CWbemCallSecurity::CloneThreadContext(int) __ptr64` | 532 (0x214) | Exported Function | 0x00000001800038c0 | 0x000038c0
`public: virtual long __cdecl CUnkInternal::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 1025 (0x401) | Exported Function | 0x0000000180011310 | 0x00011310
`public: virtual long __cdecl CUnk::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 1024 (0x400) | Exported Function | 0x0000000180011990 | 0x00011990
`public: virtual long __cdecl CTimerInstruction::MarkForRemoval(void) __ptr64` | 978 (0x3d2) | Exported Function | 0x0000000180023f30 | 0x00023f30
`public: virtual long __cdecl CTimerGenerator::Shutdown(void) __ptr64` | 1199 (0x4af) | Exported Function | 0x0000000180036680 | 0x00036680
`public: virtual long __cdecl CWbemCallSecurity::QueryBlanket(unsigned long * __ptr64,unsigned long * __ptr64,unsigned short * __ptr64 * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,void * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 1022 (0x3fe) | Exported Function | 0x00000001800127b0 | 0x000127b0
`public: virtual long __cdecl CMinMaxLimitControl::Remove(unsigned long) __ptr64` | 1051 (0x41b) | Exported Function | 0x0000000180044440 | 0x00044440
`public: virtual long __cdecl CLimitControl::RemoveMember(void) __ptr64` | 1059 (0x423) | Exported Function | 0x0000000180013590 | 0x00013590
`public: virtual long __cdecl CLimitControl::AddMember(void) __ptr64` | 473 (0x1d9) | Exported Function | 0x0000000180013580 | 0x00013580
`public: virtual long __cdecl CExecQueue::Enqueue(class CExecRequest * __ptr64,void * __ptr64 * __ptr64) __ptr64` | 617 (0x269) | Exported Function | 0x0000000180014390 | 0x00014390
`public: virtual long __cdecl CBuffer::Write(void const * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 1298 (0x512) | Exported Function | 0x0000000180023900 | 0x00023900
`public: virtual long __cdecl CBuffer::UnlockRegion(union _ULARGE_INTEGER,union _ULARGE_INTEGER,unsigned long) __ptr64` | 1266 (0x4f2) | Exported Function | 0x00000001800232b0 | 0x000232b0
`public: virtual long __cdecl CBuffer::Stat(struct tagSTATSTG * __ptr64,unsigned long) __ptr64` | 1212 (0x4bc) | Exported Function | 0x00000001800238b0 | 0x000238b0
`public: virtual long __cdecl CBuffer::SetSize(union _ULARGE_INTEGER) __ptr64` | 1178 (0x49a) | Exported Function | 0x0000000180023840 | 0x00023840
`public: virtual long __cdecl CBuffer::Seek(union _LARGE_INTEGER,unsigned long,union _ULARGE_INTEGER * __ptr64) __ptr64` | 1084 (0x43c) | Exported Function | 0x0000000180023730 | 0x00023730
`public: virtual long __cdecl CMinMaxLimitControl::Add(unsigned long,unsigned long,unsigned long * __ptr64) __ptr64` | 450 (0x1c2) | Exported Function | 0x0000000180044160 | 0x00044160
`public: virtual long __cdecl CBuffer::Revert(void) __ptr64` | 1078 (0x436) | Exported Function | 0x00000001800232b0 | 0x000232b0
`public: virtual long __cdecl CWbemCallSecurity::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 1026 (0x402) | Exported Function | 0x0000000180003bd0 | 0x00003bd0
`public: virtual unsigned long __cdecl C9XAce::GetAccessMask(void) __ptr64` | 662 (0x296) | Exported Function | 0x0000000180012a00 | 0x00012a00
`public: virtual void * __ptr64 __cdecl CWin32DefaultArena::Realloc(void * __ptr64,unsigned __int64) __ptr64` | 1034 (0x40a) | Exported Function | 0x0000000180022f40 | 0x00022f40
`public: virtual void * __ptr64 __cdecl CWin32DefaultArena::Alloc(unsigned __int64) __ptr64` | 495 (0x1ef) | Exported Function | 0x0000000180022f20 | 0x00022f20
`public: virtual void * __ptr64 __cdecl CWbemCallSecurity::GetToken(void) __ptr64` | 847 (0x34f) | Exported Function | 0x0000000180013110 | 0x00013110
`public: virtual unsigned short const * __ptr64 __cdecl CExecQueue::GetType(void) __ptr64` | 850 (0x352) | Exported Function | 0x000000018002dab0 | 0x0002dab0
`public: virtual unsigned long __cdecl CWbemCallSecurity::Release(void) __ptr64` | 1047 (0x417) | Exported Function | 0x0000000180008370 | 0x00008370
`public: virtual unsigned long __cdecl CWbemCallSecurity::GetAuthenticationId(struct _LUID & __ptr64) __ptr64` | 683 (0x2ab) | Exported Function | 0x0000000180024530 | 0x00024530
`public: virtual unsigned long __cdecl CWbemCallSecurity::AddRef(void) __ptr64` | 482 (0x1e2) | Exported Function | 0x0000000180012770 | 0x00012770
`public: virtual unsigned long __cdecl CUnkInternal::Release(void) __ptr64` | 1046 (0x416) | Exported Function | 0x0000000180011860 | 0x00011860
`public: virtual long __cdecl CWbemCallSecurity::RevertToSelf(void) __ptr64` | 1079 (0x437) | Exported Function | 0x0000000180011c90 | 0x00011c90
`public: virtual unsigned long __cdecl CUnkInternal::AddRef(void) __ptr64` | 481 (0x1e1) | Exported Function | 0x0000000180011a30 | 0x00011a30
`public: virtual unsigned long __cdecl CUnk::AddRef(void) __ptr64` | 480 (0x1e0) | Exported Function | 0x0000000180012770 | 0x00012770
`public: virtual unsigned long __cdecl CNtAce::GetStatus(void) __ptr64` | 828 (0x33c) | Exported Function | 0x0000000180012a00 | 0x00012a00
`public: virtual unsigned long __cdecl CNtAce::GetSerializedSize(void) __ptr64` | 813 (0x32d) | Exported Function | 0x000000018003ec60 | 0x0003ec60
`public: virtual unsigned long __cdecl CNtAce::GetAccessMask(void) __ptr64` | 663 (0x297) | Exported Function | 0x000000018003d250 | 0x0003d250
`public: virtual unsigned long __cdecl CBuffer::Release(void) __ptr64` | 1042 (0x412) | Exported Function | 0x00000001800236e0 | 0x000236e0
`public: virtual unsigned long __cdecl CBuffer::AddRef(void) __ptr64` | 477 (0x1dd) | Exported Function | 0x0000000180012770 | 0x00012770
`public: virtual unsigned long __cdecl C9XAce::GetStatus(void) __ptr64` | 827 (0x33b) | Exported Function | 0x0000000180023f30 | 0x00023f30
`public: virtual unsigned long __cdecl C9XAce::GetSerializedSize(void) __ptr64` | 812 (0x32c) | Exported Function | 0x000000018003ec20 | 0x0003ec20
`public: virtual unsigned long __cdecl CUnk::Release(void) __ptr64` | 1045 (0x415) | Exported Function | 0x00000001800123b0 | 0x000123b0
`public: virtual void __cdecl CBasicUnloadInstruction::AddRef(void) __ptr64` | 476 (0x1dc) | Exported Function | 0x0000000180013570 | 0x00013570
`public: virtual long __cdecl CBuffer::Read(void * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 1029 (0x405) | Exported Function | 0x00000001800235b0 | 0x000235b0
`public: virtual long __cdecl CBuffer::LockRegion(union _ULARGE_INTEGER,union _ULARGE_INTEGER,unsigned long) __ptr64` | 973 (0x3cd) | Exported Function | 0x00000001800232b0 | 0x000232b0
`public: virtual __cdecl CUnkInternal::~CUnkInternal(void) __ptr64` | 226 (0xe2) | Exported Function | 0x0000000180012750 | 0x00012750
`public: virtual __cdecl CUnk::~CUnk(void) __ptr64` | 225 (0xe1) | Exported Function | 0x0000000180011c50 | 0x00011c50
`public: virtual __cdecl CTimerInstruction::~CTimerInstruction(void) __ptr64` | 224 (0xe0) | Exported Function | 0x0000000180036240 | 0x00036240
`public: virtual __cdecl CTimerGenerator::~CTimerGenerator(void) __ptr64` | 223 (0xdf) | Exported Function | 0x00000001800361c0 | 0x000361c0
`public: virtual __cdecl CRegistryMinMaxLimitControl::~CRegistryMinMaxLimitControl(void) __ptr64` | 219 (0xdb) | Exported Function | 0x0000000180043e10 | 0x00043e10
`public: virtual __cdecl CNtAce::~CNtAce(void) __ptr64` | 213 (0xd5) | Exported Function | 0x0000000180006340 | 0x00006340
`public: virtual __cdecl CMinMaxLimitControl::~CMinMaxLimitControl(void) __ptr64` | 212 (0xd4) | Exported Function | 0x0000000180043d90 | 0x00043d90
`public: virtual __cdecl CLimitControl::~CLimitControl(void) __ptr64` | 209 (0xd1) | Exported Function | 0x0000000180043d70 | 0x00043d70
`public: virtual __cdecl QL1_Parser::~QL1_Parser(void) __ptr64` | 235 (0xeb) | Exported Function | 0x0000000180005c90 | 0x00005c90
`public: virtual __cdecl CHaltable::~CHaltable(void) __ptr64` | 202 (0xca) | Exported Function | 0x0000000180035c80 | 0x00035c80
`public: virtual __cdecl CBasicUnloadInstruction::~CBasicUnloadInstruction(void) __ptr64` | 187 (0xbb) | Exported Function | 0x00000001800115e0 | 0x000115e0
`public: virtual __cdecl CBaseAce::~CBaseAce(void) __ptr64` | 186 (0xba) | Exported Function | 0x0000000180024200 | 0x00024200
`public: virtual __cdecl CAbstractQl1Parser::~CAbstractQl1Parser(void) __ptr64` | 185 (0xb9) | Exported Function | 0x0000000180005f40 | 0x00005f40
`public: virtual __cdecl C9XAce::~C9XAce(void) __ptr64` | 184 (0xb8) | Exported Function | 0x000000018003aec0 | 0x0003aec0
`public: unsigned short const * __ptr64 const & __ptr64 __cdecl WString::GetStringPointerByRef(void)const __ptr64` | 837 (0x345) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: unsigned short const * __ptr64 const & __ptr64 __cdecl WString2::GetStringPointerByRef(void)const __ptr64` | 836 (0x344) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: unsigned short const * __ptr64 __cdecl CWbemCallSecurity::GetCallerIdentity(void) __ptr64` | 695 (0x2b7) | Exported Function | 0x00000001800245b0 | 0x000245b0
`public: unsigned short const * __ptr64 __cdecl CPropertyName::GetStringAt(long)const __ptr64` | 835 (0x343) | Exported Function | 0x00000001800035c0 | 0x000035c0
`public: virtual __cdecl CExecRequest::~CExecRequest(void) __ptr64` | 199 (0xc7) | Exported Function | 0x0000000180014840 | 0x00014840
`public: virtual long __cdecl CBuffer::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 1023 (0x3ff) | Exported Function | 0x0000000180023520 | 0x00023520
`public: virtual __cdecl SZLess<unsigned short const * __ptr64>::~SZLess<unsigned short const * __ptr64>(void) __ptr64` | 183 (0xb7) | Exported Function | 0x0000000180034d70 | 0x00034d70
`public: virtual bool __cdecl C9XAce::Serialize(unsigned char * __ptr64,unsigned __int64) __ptr64` | 1086 (0x43e) | Exported Function | 0x0000000180040810 | 0x00040810
`public: virtual long __cdecl CBuffer::CopyTo(struct IStream * __ptr64,union _ULARGE_INTEGER,union _ULARGE_INTEGER * __ptr64,union _ULARGE_INTEGER * __ptr64) __ptr64` | 555 (0x22b) | Exported Function | 0x00000001800232c0 | 0x000232c0
`public: virtual long __cdecl CBuffer::Commit(unsigned long) __ptr64` | 537 (0x219) | Exported Function | 0x00000001800232b0 | 0x000232b0
`public: virtual long __cdecl CBuffer::Clone(struct IStream * __ptr64 * __ptr64) __ptr64` | 530 (0x212) | Exported Function | 0x0000000180023170 | 0x00023170
`public: virtual int __cdecl CWin32DefaultArena::Free(void * __ptr64) __ptr64` | 658 (0x292) | Exported Function | 0x0000000180022f30 | 0x00022f30
`public: virtual int __cdecl CWbemCallSecurity::IsImpersonating(void) __ptr64` | 917 (0x395) | Exported Function | 0x0000000180011740 | 0x00011740
`public: virtual int __cdecl CUnk::OnInitialize(void) __ptr64` | 993 (0x3e1) | Exported Function | 0x0000000180013480 | 0x00013480
`public: virtual int __cdecl CUnk::Initialize(void) __ptr64` | 891 (0x37b) | Exported Function | 0x0000000180012980 | 0x00012980
`public: virtual int __cdecl CNtAce::GetType(void) __ptr64` | 851 (0x353) | Exported Function | 0x000000018003f3e0 | 0x0003f3e0
`public: virtual bool __cdecl C9XAce::Deserialize(unsigned char * __ptr64) __ptr64` | 591 (0x24f) | Exported Function | 0x000000018003d0d0 | 0x0003d0d0
`public: virtual int __cdecl CNtAce::GetFlags(void) __ptr64` | 725 (0x2d5) | Exported Function | 0x000000018000b050 | 0x0000b050
`public: virtual int __cdecl CContainerControl::ObjectCreated(struct IUnknown * __ptr64) __ptr64` | 991 (0x3df) | Exported Function | 0x0000000180013480 | 0x00013480
`public: virtual int __cdecl CBasicUnloadInstruction::GetInstructionType(void) __ptr64` | 741 (0x2e5) | Exported Function | 0x0000000180043690 | 0x00043690
`public: virtual int __cdecl C9XAce::GetType(void) __ptr64` | 849 (0x351) | Exported Function | 0x0000000180023510 | 0x00023510
`public: virtual int __cdecl C9XAce::GetFlags(void) __ptr64` | 724 (0x2d4) | Exported Function | 0x0000000180023e70 | 0x00023e70
`public: virtual class CWbemTime __cdecl CBasicUnloadInstruction::GetNextFiringTime(class CWbemTime,long * __ptr64)const __ptr64` | 768 (0x300) | Exported Function | 0x000000018000fda0 | 0x0000fda0
`public: virtual class CWbemTime __cdecl CBasicUnloadInstruction::GetFirstFiringTime(void)const __ptr64` | 722 (0x2d2) | Exported Function | 0x000000018000fad0 | 0x0000fad0
`public: virtual bool __cdecl CNtAce::Serialize(unsigned char * __ptr64,unsigned __int64) __ptr64` | 1087 (0x43f) | Exported Function | 0x00000001800408a0 | 0x000408a0
`public: virtual bool __cdecl CNtAce::Deserialize(unsigned char * __ptr64) __ptr64` | 592 (0x250) | Exported Function | 0x000000018003d1d0 | 0x0003d1d0
`public: virtual int __cdecl CIdentityTest::operator()(class CTimerInstruction * __ptr64) __ptr64` | 399 (0x18f) | Exported Function | 0x0000000180013520 | 0x00013520
`WMIControlCallback` | 1274 (0x4fa) | Exported Function | 0x0000000180046480 | 0x00046480
`public: class WString2 & __ptr64 __cdecl WString2::TruncAtRToken(unsigned short) __ptr64` | 1249 (0x4e1) | Exported Function | 0x0000000180042760 | 0x00042760
`public: class WString2 & __ptr64 __cdecl WString2::StripWs(int) __ptr64` | 1219 (0x4c3) | Exported Function | 0x0000000180042600 | 0x00042600
`protected: int __cdecl CDateTimeParser::IsValidSecondNumber(unsigned short * __ptr64,unsigned short const * __ptr64) __ptr64` | 952 (0x3b8) | Exported Function | 0x0000000180028dc0 | 0x00028dc0
`protected: int __cdecl CDateTimeParser::IsValidMonthString(unsigned short * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64 * __ptr64 const,unsigned short * __ptr64 * __ptr64 const) __ptr64` | 951 (0x3b7) | Exported Function | 0x0000000180028cc0 | 0x00028cc0
`protected: int __cdecl CDateTimeParser::IsValidMonthNumber(unsigned short * __ptr64,unsigned short const * __ptr64) __ptr64` | 950 (0x3b6) | Exported Function | 0x0000000180028c00 | 0x00028c00
`protected: int __cdecl CDateTimeParser::IsValidMinuteNumber(unsigned short * __ptr64,unsigned short const * __ptr64) __ptr64` | 949 (0x3b5) | Exported Function | 0x0000000180028b60 | 0x00028b60
`protected: int __cdecl CDateTimeParser::IsValidHourNumber(unsigned short * __ptr64,unsigned short const * __ptr64) __ptr64` | 948 (0x3b4) | Exported Function | 0x0000000180028aa0 | 0x00028aa0
`protected: int __cdecl CDateTimeParser::IsValidDotMillisecond(unsigned short * __ptr64,unsigned short const * __ptr64) __ptr64` | 945 (0x3b1) | Exported Function | 0x00000001800289d0 | 0x000289d0
`protected: int __cdecl CDateTimeParser::IsValidDayNumber(unsigned short * __ptr64,unsigned short const * __ptr64) __ptr64` | 944 (0x3b0) | Exported Function | 0x0000000180028910 | 0x00028910
`protected: int __cdecl CDateTimeParser::IsValidColonMillisecond(unsigned short * __ptr64,unsigned short const * __ptr64) __ptr64` | 942 (0x3ae) | Exported Function | 0x0000000180028860 | 0x00028860
`protected: int __cdecl CDateTimeParser::IsValidAmPmString(unsigned short * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64 * __ptr64 const) __ptr64` | 941 (0x3ad) | Exported Function | 0x0000000180028770 | 0x00028770
`protected: int __cdecl CDateTimeParser::DateFormat9(unsigned short const * __ptr64,unsigned short const * __ptr64,int) __ptr64` | 578 (0x242) | Exported Function | 0x0000000180028330 | 0x00028330
`protected: int __cdecl CDateTimeParser::DateFormat8(unsigned short const * __ptr64,int) __ptr64` | 577 (0x241) | Exported Function | 0x00000001800280d0 | 0x000280d0
`protected: int __cdecl CDateTimeParser::DateFormat7(unsigned short const * __ptr64,int) __ptr64` | 576 (0x240) | Exported Function | 0x0000000180027f00 | 0x00027f00
`protected: int __cdecl CDateTimeParser::DateFormat6(unsigned short const * __ptr64,int) __ptr64` | 575 (0x23f) | Exported Function | 0x0000000180027c80 | 0x00027c80
`protected: int __cdecl CDateTimeParser::DateFormat5(unsigned short const * __ptr64,int) __ptr64` | 574 (0x23e) | Exported Function | 0x0000000180027a00 | 0x00027a00
`protected: int __cdecl CDateTimeParser::DateFormat4(unsigned short const * __ptr64,int) __ptr64` | 573 (0x23d) | Exported Function | 0x0000000180027780 | 0x00027780
`protected: int __cdecl CDateTimeParser::DateFormat3(unsigned short const * __ptr64,int) __ptr64` | 572 (0x23c) | Exported Function | 0x0000000180027500 | 0x00027500
`protected: int __cdecl CDateTimeParser::DateFormat2(unsigned short const * __ptr64,int) __ptr64` | 571 (0x23b) | Exported Function | 0x0000000180027330 | 0x00027330
`protected: int __cdecl CDateTimeParser::IsValidYearMonthDayNumber(unsigned short * __ptr64) __ptr64` | 955 (0x3bb) | Exported Function | 0x0000000180028e60 | 0x00028e60
`protected: int __cdecl CDateTimeParser::IsValidYearNumber(unsigned short * __ptr64,unsigned short const * __ptr64,int) __ptr64` | 956 (0x3bc) | Exported Function | 0x0000000180028fe0 | 0x00028fe0
`protected: int __cdecl CDateTimeParser::TimeFormat1(unsigned short const * __ptr64,int) __ptr64` | 1226 (0x4ca) | Exported Function | 0x00000001800294a0 | 0x000294a0
`protected: int __cdecl CDateTimeParser::TimeFormat2(unsigned short const * __ptr64,int) __ptr64` | 1227 (0x4cb) | Exported Function | 0x0000000180029610 | 0x00029610
`protected: static unsigned long __cdecl CExecQueue::_ThreadEntry(void * __ptr64)` | 1314 (0x522) | Exported Function | 0x00000001800148e0 | 0x000148e0
`protected: static unsigned long __cdecl CAbstractQl1Parser::TranslateIntrinsic(unsigned short const * __ptr64)` | 1243 (0x4db) | Exported Function | 0x0000000180034680 | 0x00034680
`protected: static long CExecQueue::mstatic_lNumInits` | 1373 (0x55d) | Exported Function | 0x0000000180075570 | 0x00075570
`protected: static int __cdecl CSmallArrayBlob::CompareEls(void const * __ptr64,void const * __ptr64)` | 539 (0x21b) | Exported Function | 0x000000018002e9a0 | 0x0002e9a0
`protected: static int __cdecl CFlexArray::CompareEls(void const * __ptr64,void const * __ptr64)` | 538 (0x21a) | Exported Function | 0x000000018002e9a0 | 0x0002e9a0
`protected: long __cdecl CMinMaxLimitControl::ComputePenalty(unsigned long,unsigned long,unsigned long * __ptr64,int * __ptr64) __ptr64` | 548 (0x224) | Exported Function | 0x0000000180044350 | 0x00044350
`protected: int __cdecl CMRCICompression::UncompressFileV1(int,int) __ptr64` | 1261 (0x4ed) | Exported Function | 0x0000000180032010 | 0x00032010
`protected: int __cdecl CMRCICompression::CompressFileV1(int,int,unsigned long,enum CMRCICompression::CompressionLevel,class CMRCIControl * __ptr64) __ptr64` | 547 (0x223) | Exported Function | 0x0000000180031ba0 | 0x00031ba0
`protected: int __cdecl CDateTimeParser::DateFormat15(unsigned short const * __ptr64,int) __ptr64` | 569 (0x239) | Exported Function | 0x0000000180026f90 | 0x00026f90
`protected: int __cdecl CEventLog::SearchForRecord(class CEventLogRecord * __ptr64) __ptr64` | 1082 (0x43a) | Exported Function | 0x000000018002ce50 | 0x0002ce50
`protected: int __cdecl CDMTFParser::ParsePart(unsigned short const * __ptr64,int,int,int * __ptr64,int,int) __ptr64` | 1003 (0x3eb) | Exported Function | 0x0000000180025740 | 0x00025740
`protected: int __cdecl CDateTimeParser::TimeFormat9(unsigned short const * __ptr64,int) __ptr64` | 1234 (0x4d2) | Exported Function | 0x000000018002a740 | 0x0002a740
`protected: int __cdecl CDateTimeParser::TimeFormat8(unsigned short const * __ptr64,int) __ptr64` | 1233 (0x4d1) | Exported Function | 0x000000018002a460 | 0x0002a460
`protected: int __cdecl CDateTimeParser::TimeFormat7(unsigned short const * __ptr64,int) __ptr64` | 1232 (0x4d0) | Exported Function | 0x000000018002a1e0 | 0x0002a1e0
`protected: int __cdecl CDateTimeParser::TimeFormat6(unsigned short const * __ptr64,int) __ptr64` | 1231 (0x4cf) | Exported Function | 0x0000000180029f00 | 0x00029f00
`protected: int __cdecl CDateTimeParser::TimeFormat5(unsigned short const * __ptr64,int) __ptr64` | 1230 (0x4ce) | Exported Function | 0x0000000180029c90 | 0x00029c90
`protected: int __cdecl CDateTimeParser::TimeFormat4(unsigned short const * __ptr64,int) __ptr64` | 1229 (0x4cd) | Exported Function | 0x0000000180029a20 | 0x00029a20
`protected: int __cdecl CDateTimeParser::TimeFormat3(unsigned short const * __ptr64,int) __ptr64` | 1228 (0x4cc) | Exported Function | 0x0000000180029810 | 0x00029810
`protected: int __cdecl CEventLog::AddRecord(class CEventLogRecord * __ptr64) __ptr64` | 475 (0x1db) | Exported Function | 0x000000018002be00 | 0x0002be00
`protected: int __cdecl CDateTimeParser::DateFormat14(unsigned short const * __ptr64,unsigned short const * __ptr64,int) __ptr64` | 568 (0x238) | Exported Function | 0x0000000180026db0 | 0x00026db0
`protected: int __cdecl CDateTimeParser::DateFormat13(unsigned short const * __ptr64,unsigned short const * __ptr64,int) __ptr64` | 567 (0x237) | Exported Function | 0x0000000180026bd0 | 0x00026bd0
`protected: int __cdecl CDateTimeParser::DateFormat12(unsigned short const * __ptr64,unsigned short const * __ptr64,int) __ptr64` | 566 (0x236) | Exported Function | 0x00000001800269f0 | 0x000269f0
`protected: int __cdecl CAbstractQl1Parser::opt_having(void) __ptr64` | 1375 (0x55f) | Exported Function | 0x0000000180034b90 | 0x00034b90
`protected: int __cdecl CAbstractQl1Parser::opt_aggregation(void) __ptr64` | 1374 (0x55e) | Exported Function | 0x0000000180009f20 | 0x00009f20
`protected: int __cdecl CAbstractQl1Parser::leading_ident_expr(void) __ptr64` | 1337 (0x539) | Exported Function | 0x0000000180004810 | 0x00004810
`protected: int __cdecl CAbstractQl1Parser::is_operator(void) __ptr64` | 1334 (0x536) | Exported Function | 0x0000000180034b20 | 0x00034b20
`protected: int __cdecl CAbstractQl1Parser::FlipOperator(int) __ptr64` | 656 (0x290) | Exported Function | 0x0000000180034380 | 0x00034380
`protected: int __cdecl CAbstractQl1Parser::finalize(void) __ptr64` | 1329 (0x531) | Exported Function | 0x0000000180005e30 | 0x00005e30
`protected: int __cdecl CAbstractQl1Parser::expr2(void) __ptr64` | 1327 (0x52f) | Exported Function | 0x00000001800047a0 | 0x000047a0
`protected: int __cdecl CAbstractQl1Parser::expr(void) __ptr64` | 1328 (0x530) | Exported Function | 0x0000000180004770 | 0x00004770
`protected: int __cdecl CAbstractQl1Parser::opt_where(void) __ptr64` | 1376 (0x560) | Exported Function | 0x0000000180009f50 | 0x00009f50
`protected: int __cdecl CAbstractQl1Parser::equiv_operator(void) __ptr64` | 1325 (0x52d) | Exported Function | 0x0000000180002590 | 0x00002590
`protected: int __cdecl CAbstractQl1Parser::class_name(void) __ptr64` | 1323 (0x52b) | Exported Function | 0x0000000180005bc0 | 0x00005bc0
`protected: int __cdecl CAbstractQl1Parser::aggregation_params(void) __ptr64` | 1318 (0x526) | Exported Function | 0x0000000180034a10 | 0x00034a10
`protected: int __cdecl CAbstractQl1Parser::aggregate_within(void) __ptr64` | 1317 (0x525) | Exported Function | 0x0000000180034950 | 0x00034950
`protected: int __cdecl CAbstractQl1Parser::aggregate_by(void) __ptr64` | 1316 (0x524) | Exported Function | 0x0000000180034920 | 0x00034920
`protected: class CWbemInterval __cdecl CInstructionQueue::TimeToWait(void) __ptr64` | 1235 (0x4d3) | Exported Function | 0x000000018000f850 | 0x0000f850
`protected: class CSmallArrayBlob * __ptr64 __cdecl CSmallArrayBlob::ShrinkIfNeeded(void) __ptr64` | 1197 (0x4ad) | Exported Function | 0x0000000180035b30 | 0x00035b30
`protected: class CSmallArrayBlob * __ptr64 __cdecl CSmallArrayBlob::Shrink(void) __ptr64` | 1196 (0x4ac) | Exported Function | 0x0000000180035ac0 | 0x00035ac0
`protected: class CSmallArrayBlob * __ptr64 __cdecl CSmallArrayBlob::Grow(void) __ptr64` | 873 (0x369) | Exported Function | 0x0000000180013fc0 | 0x00013fc0
`protected: int __cdecl CAbstractQl1Parser::comp_operator(void) __ptr64` | 1324 (0x52c) | Exported Function | 0x0000000180004860 | 0x00004860
`protected: static void __cdecl CAbstractQl1Parser::InitToken(struct _tag_WbemQl1Token * __ptr64)` | 887 (0x377) | Exported Function | 0x0000000180004ba0 | 0x00004ba0
`protected: int __cdecl CAbstractQl1Parser::parse(int) __ptr64` | 1378 (0x562) | Exported Function | 0x00000001800078b0 | 0x000078b0
`protected: int __cdecl CAbstractQl1Parser::prop_list(void) __ptr64` | 1380 (0x564) | Exported Function | 0x000000018000c560 | 0x0000c560
`protected: int __cdecl CDateTimeParser::DateFormat11(unsigned short const * __ptr64,unsigned short const * __ptr64,int) __ptr64` | 565 (0x235) | Exported Function | 0x0000000180026810 | 0x00026810
`protected: int __cdecl CDateTimeParser::DateFormat10(unsigned short const * __ptr64,unsigned short const * __ptr64,int) __ptr64` | 564 (0x234) | Exported Function | 0x0000000180026610 | 0x00026610
`protected: int __cdecl CDateTimeParser::DateFormat1(unsigned short const * __ptr64,int) __ptr64` | 570 (0x23a) | Exported Function | 0x00000001800270b0 | 0x000270b0
`protected: int __cdecl CDateTimeParser::CheckTimeFormat(unsigned short const * __ptr64,int) __ptr64` | 524 (0x20c) | Exported Function | 0x0000000180026530 | 0x00026530
`protected: int __cdecl CDateTimeParser::CheckDMTFDateTimeFormatInternal(unsigned short const * __ptr64) __ptr64` | 520 (0x208) | Exported Function | 0x0000000180025f60 | 0x00025f60
`protected: int __cdecl CDateTimeParser::CheckDateFormat(unsigned short const * __ptr64,int) __ptr64` | 522 (0x20a) | Exported Function | 0x0000000180026220 | 0x00026220
`protected: int __cdecl CAbstractQl1Parser::typed_constant(void) __ptr64` | 1397 (0x575) | Exported Function | 0x0000000180004a70 | 0x00004a70
`protected: int __cdecl CAbstractQl1Parser::trailing_prop_expr(void) __ptr64` | 1396 (0x574) | Exported Function | 0x0000000180034c50 | 0x00034c50
`protected: int __cdecl CAbstractQl1Parser::parse_property_name(class CPropertyName & __ptr64) __ptr64` | 1379 (0x563) | Exported Function | 0x0000000180005250 | 0x00005250
`protected: int __cdecl CAbstractQl1Parser::trailing_or_null(void) __ptr64` | 1395 (0x573) | Exported Function | 0x00000001800025e0 | 0x000025e0
`protected: int __cdecl CAbstractQl1Parser::trailing_const_expr(void) __ptr64` | 1393 (0x571) | Exported Function | 0x0000000180004a40 | 0x00004a40
`protected: int __cdecl CAbstractQl1Parser::tolerance(void) __ptr64` | 1392 (0x570) | Exported Function | 0x0000000180009fb0 | 0x00009fb0
`protected: int __cdecl CAbstractQl1Parser::term2(void) __ptr64` | 1390 (0x56e) | Exported Function | 0x0000000180004920 | 0x00004920
`protected: int __cdecl CAbstractQl1Parser::term(void) __ptr64` | 1391 (0x56f) | Exported Function | 0x00000001800048f0 | 0x000048f0
`protected: int __cdecl CAbstractQl1Parser::simple_expr(void) __ptr64` | 1388 (0x56c) | Exported Function | 0x0000000180004990 | 0x00004990
`protected: int __cdecl CAbstractQl1Parser::rel_operator(void) __ptr64` | 1384 (0x568) | Exported Function | 0x0000000180034be0 | 0x00034be0
`protected: int __cdecl CAbstractQl1Parser::property_name(void) __ptr64` | 1382 (0x566) | Exported Function | 0x0000000180009e50 | 0x00009e50
`protected: int __cdecl CAbstractQl1Parser::prop_list_2(void) __ptr64` | 1381 (0x565) | Exported Function | 0x0000000180009e10 | 0x00009e10
`protected: int __cdecl CAbstractQl1Parser::trailing_ident_expr(void) __ptr64` | 1394 (0x572) | Exported Function | 0x0000000180034c20 | 0x00034c20
`protected: class CSmallArrayBlob * __ptr64 __cdecl CSmallArrayBlob::EnsureExtent(int) __ptr64` | 624 (0x270) | Exported Function | 0x0000000180013fa0 | 0x00013fa0
`protected: static void __cdecl CExecQueue::InitTls(void)` | 886 (0x376) | Exported Function | 0x000000018002dac0 | 0x0002dac0
`protected: unsigned short * __ptr64 __cdecl CDateTimeParser::AllocAmPm(void) __ptr64` | 496 (0x1f0) | Exported Function | 0x0000000180025ef0 | 0x00025ef0
`public: __cdecl CClientOpsNode::~CClientOpsNode(void) __ptr64` | 190 (0xbe) | Exported Function | 0x0000000180011160 | 0x00011160
`public: __cdecl CClientOpsNode::CClientOpsNode(void) __ptr64` | 23 (0x17) | Exported Function | 0x0000000180012aa0 | 0x00012aa0
`public: __cdecl CCircularQueue::CCircularQueue(void) __ptr64` | 22 (0x16) | Exported Function | 0x0000000180013310 | 0x00013310
`public: __cdecl CCheckedInCritSec::~CCheckedInCritSec(void) __ptr64` | 189 (0xbd) | Exported Function | 0x00000001800117c0 | 0x000117c0
`public: __cdecl CCheckedInCritSec::CCheckedInCritSec(class CCritSec * __ptr64) __ptr64` | 21 (0x15) | Exported Function | 0x00000001800111e0 | 0x000111e0
`public: __cdecl CBuffer::~CBuffer(void) __ptr64` | 188 (0xbc) | Exported Function | 0x00000001800131f0 | 0x000131f0
`public: __cdecl CBuffer::CBuffer(unsigned char * __ptr64,unsigned long,int) __ptr64` | 20 (0x14) | Exported Function | 0x0000000180013230 | 0x00013230
`public: __cdecl CBuffer::CBuffer(class CBuffer const & __ptr64) __ptr64` | 19 (0x13) | Exported Function | 0x0000000180022f80 | 0x00022f80
`public: __cdecl CBasicUnloadInstruction::CBasicUnloadInstruction(class CWbemInterval) __ptr64` | 18 (0x12) | Exported Function | 0x0000000180011630 | 0x00011630
`public: __cdecl CBasicUnloadInstruction::CBasicUnloadInstruction(class CBasicUnloadInstruction const & __ptr64) __ptr64` | 17 (0x11) | Exported Function | 0x0000000180043550 | 0x00043550
`public: __cdecl CBaseAce::CBaseAce(void) __ptr64` | 15 (0xf) | Exported Function | 0x00000001800240a0 | 0x000240a0
`public: __cdecl CBaseAce::CBaseAce(class CBaseAce const & __ptr64) __ptr64` | 14 (0xe) | Exported Function | 0x00000001800240a0 | 0x000240a0
`public: __cdecl CArena::CArena(void) __ptr64` | 13 (0xd) | Exported Function | 0x0000000180022e90 | 0x00022e90
`public: __cdecl CArena::CArena(class CArena const & __ptr64) __ptr64` | 12 (0xc) | Exported Function | 0x0000000180022e90 | 0x00022e90
`public: __cdecl CArena::CArena(class CArena && __ptr64) __ptr64` | 11 (0xb) | Exported Function | 0x0000000180022e90 | 0x00022e90
`public: __cdecl CAbstractQl1Parser::CAbstractQl1Parser(class CGenLexSource * __ptr64) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180005cf0 | 0x00005cf0
`public: __cdecl CAbstractQl1Parser::CAbstractQl1Parser(class CAbstractQl1Parser const & __ptr64) __ptr64` | 9 (0x9) | Exported Function | 0x0000000180033250 | 0x00033250
`public: __cdecl CContainerControl::CContainerControl(class CContainerControl && __ptr64) __ptr64` | 24 (0x18) | Exported Function | 0x000000018002aa20 | 0x0002aa20
`public: __cdecl CContainerControl::CContainerControl(class CContainerControl const & __ptr64) __ptr64` | 25 (0x19) | Exported Function | 0x000000018002aa20 | 0x0002aa20
`public: __cdecl CContainerControl::CContainerControl(struct IUnknown * __ptr64) __ptr64` | 26 (0x1a) | Exported Function | 0x000000018002aa40 | 0x0002aa40
`public: __cdecl CCritSec::CCritSec(void) __ptr64` | 27 (0x1b) | Exported Function | 0x0000000180011680 | 0x00011680
`public: __cdecl CExecQueue::~CExecQueue(void) __ptr64` | 198 (0xc6) | Exported Function | 0x000000018002d470 | 0x0002d470
`public: __cdecl CExecQueue::CExecQueue(void) __ptr64` | 38 (0x26) | Exported Function | 0x000000018002d2e0 | 0x0002d2e0
`public: __cdecl CExecQueue::CExecQueue(class CExecQueue & __ptr64) __ptr64` | 37 (0x25) | Exported Function | 0x000000018002d180 | 0x0002d180
`public: __cdecl CEventLogRecord::~CEventLogRecord(void) __ptr64` | 197 (0xc5) | Exported Function | 0x000000018002b890 | 0x0002b890
`public: __cdecl CEventLogRecord::CEventLogRecord(unsigned short,struct _EVENT_DESCRIPTOR const & __ptr64,class CInsertionString,class CInsertionString,class CInsertionString,class CInsertionString,class CInsertionString,class CInsertionString,class CInsertionString,class CInsertionString,class CInsertionString,class CInsertionString) __ptr64` | 36 (0x24) | Exported Function | 0x000000018002aca0 | 0x0002aca0
`public: __cdecl CEventLogRecord::CEventLogRecord(class CEventLogRecord & __ptr64) __ptr64` | 35 (0x23) | Exported Function | 0x000000018002ac30 | 0x0002ac30
`public: __cdecl CEventLog::~CEventLog(void) __ptr64` | 196 (0xc4) | Exported Function | 0x000000018002b7e0 | 0x0002b7e0
`public: __cdecl CEventLog::CEventLog(unsigned short const * __ptr64,struct _GUID const & __ptr64,unsigned long) __ptr64` | 34 (0x22) | Exported Function | 0x000000018002ab00 | 0x0002ab00
`public: __cdecl C9XAce::C9XAce(void) __ptr64` | 8 (0x8) | Exported Function | 0x0000000180024050 | 0x00024050
`public: __cdecl CEventLog::CEventLog(class CEventLog const & __ptr64) __ptr64` | 33 (0x21) | Exported Function | 0x000000018002aa60 | 0x0002aa60
`public: __cdecl CEnterWbemCriticalSection::CEnterWbemCriticalSection(class CWbemCriticalSection * __ptr64,unsigned long) __ptr64` | 32 (0x20) | Exported Function | 0x0000000180023b80 | 0x00023b80
`public: __cdecl CDMTFParser::~CDMTFParser(void) __ptr64` | 192 (0xc0) | Exported Function | 0x000000018000a140 | 0x0000a140
`public: __cdecl CDMTFParser::CDMTFParser(unsigned short const * __ptr64) __ptr64` | 28 (0x1c) | Exported Function | 0x0000000180025050 | 0x00025050
`public: __cdecl CDateTimeParser::~CDateTimeParser(void) __ptr64` | 194 (0xc2) | Exported Function | 0x0000000180025d00 | 0x00025d00
`public: __cdecl CDateTimeParser::CDateTimeParser(unsigned short const * __ptr64) __ptr64` | 31 (0x1f) | Exported Function | 0x0000000180025ac0 | 0x00025ac0
`public: __cdecl CDatePart::~CDatePart(void) __ptr64` | 193 (0xc1) | Exported Function | 0x0000000180025070 | 0x00025070
`public: __cdecl CDatePart::CDatePart(void) __ptr64` | 29 (0x1d) | Exported Function | 0x0000000180001490 | 0x00001490
`public: __cdecl CCritSec::~CCritSec(void) __ptr64` | 191 (0xbf) | Exported Function | 0x0000000180011d60 | 0x00011d60
`public: __cdecl CEnterWbemCriticalSection::~CEnterWbemCriticalSection(void) __ptr64` | 195 (0xc3) | Exported Function | 0x0000000180023c30 | 0x00023c30
`public: __cdecl C9XAce::C9XAce(unsigned long,unsigned long,unsigned long,unsigned short * __ptr64) __ptr64` | 7 (0x7) | Exported Function | 0x000000018003a710 | 0x0003a710
`public: __cdecl C9XAce::C9XAce(class C9XAce const & __ptr64) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180023ff0 | 0x00023ff0
`protected: void __cdecl CSmallArrayBlob::Initialize(int) __ptr64` | 889 (0x379) | Exported Function | 0x00000001800359f0 | 0x000359f0
`protected: virtual void __cdecl CExecQueue::LogError(class CExecRequest * __ptr64,int) __ptr64` | 974 (0x3ce) | Exported Function | 0x000000018002dba0 | 0x0002dba0
`protected: virtual void __cdecl CExecQueue::AdjustPriorityForPassing(class CExecRequest * __ptr64) __ptr64` | 491 (0x1eb) | Exported Function | 0x000000018000a140 | 0x0000a140
`protected: virtual void __cdecl CExecQueue::AdjustInitialPriority(class CExecRequest * __ptr64) __ptr64` | 490 (0x1ea) | Exported Function | 0x000000018000a140 | 0x0000a140
`protected: virtual unsigned long __cdecl CExecQueue::WaitForSingleObjectWhileBusy(void * __ptr64,unsigned long,class CExecQueue::CThreadRecord * __ptr64) __ptr64` | 1278 (0x4fe) | Exported Function | 0x000000018002e230 | 0x0002e230
`protected: virtual unsigned long __cdecl CExecQueue::UnblockedWaitForSingleObject(void * __ptr64,unsigned long,class CExecQueue::CThreadRecord * __ptr64) __ptr64` | 1258 (0x4ea) | Exported Function | 0x000000018002e150 | 0x0002e150
`protected: virtual unsigned long __cdecl CExecQueue::GetIdleTimeout(class CExecQueue::CThreadRecord * __ptr64) __ptr64` | 734 (0x2de) | Exported Function | 0x0000000180014950 | 0x00014950
`protected: virtual unsigned long __cdecl CExecQueue::CalcSitOutPenalty(long) __ptr64` | 512 (0x200) | Exported Function | 0x0000000180014980 | 0x00014980
`protected: virtual long __cdecl CExecQueue::InitializeThread(void) __ptr64` | 892 (0x37c) | Exported Function | 0x00000001800149c0 | 0x000149c0
`protected: virtual void __cdecl CExecQueue::ShutdownThread(class CExecQueue::CThreadRecord * __ptr64) __ptr64` | 1201 (0x4b1) | Exported Function | 0x0000000180013970 | 0x00013970
`protected: virtual int __cdecl CExecQueue::IsSuitableThread(class CExecQueue::CThreadRecord * __ptr64,class CExecRequest * __ptr64) __ptr64` | 933 (0x3a5) | Exported Function | 0x00000001800149a0 | 0x000149a0
`protected: virtual int __cdecl CExecQueue::IsIdleTooLong(class CExecQueue::CThreadRecord * __ptr64,unsigned long) __ptr64` | 916 (0x394) | Exported Function | 0x0000000180013e60 | 0x00013e60
`protected: virtual int __cdecl CExecQueue::IsAppropriateThread(void) __ptr64` | 904 (0x388) | Exported Function | 0x000000018002daf0 | 0x0002daf0
`protected: virtual int __cdecl CExecQueue::Execute(class CExecQueue::CThreadRecord * __ptr64) __ptr64` | 640 (0x280) | Exported Function | 0x0000000180014720 | 0x00014720
`protected: virtual int __cdecl CExecQueue::DoesNeedNewThread(class CExecRequest * __ptr64) __ptr64` | 596 (0x254) | Exported Function | 0x00000001800148a0 | 0x000148a0
`protected: virtual int __cdecl CExecQueue::CreateNewThread(void) __ptr64` | 560 (0x230) | Exported Function | 0x0000000180014540 | 0x00014540
`protected: virtual int __cdecl CAbstractQl1Parser::Next(int) __ptr64` | 986 (0x3da) | Exported Function | 0x00000001800079c0 | 0x000079c0
`protected: virtual class CExecRequest * __ptr64 __cdecl CExecQueue::SearchForSuitableRequest(class CExecQueue::CThreadRecord * __ptr64) __ptr64` | 1083 (0x43b) | Exported Function | 0x0000000180014680 | 0x00014680
`protected: unsigned short const * __ptr64 __cdecl CAbstractQl1Parser::GetSinglePropertyName(void) __ptr64` | 820 (0x334) | Exported Function | 0x0000000180034530 | 0x00034530
`protected: virtual int __cdecl CExecQueue::IsSTA(void) __ptr64` | 931 (0x3a3) | Exported Function | 0x0000000180023f30 | 0x00023f30
`protected: static void __cdecl CExecQueue::Register(class CExecQueue::CThreadRecord * __ptr64)` | 1037 (0x40d) | Exported Function | 0x000000018002dd20 | 0x0002dd20
`protected: virtual void __cdecl CExecQueue::SitOutPenalty(long) __ptr64` | 1202 (0x4b2) | Exported Function | 0x0000000180014910 | 0x00014910
`protected: virtual void __cdecl CExecQueue::UninitializeThread(void) __ptr64` | 1262 (0x4ee) | Exported Function | 0x0000000180013f00 | 0x00013f00
`protected: void __cdecl CSmallArrayBlob::CopyData(class CSmallArrayBlob * __ptr64) __ptr64` | 552 (0x228) | Exported Function | 0x0000000180014020 | 0x00014020
`protected: void __cdecl CPropertyName::EnsureAllocated(long) __ptr64` | 622 (0x26e) | Exported Function | 0x00000001800056b0 | 0x000056b0
`protected: void __cdecl CInstructionQueue::TouchHead(void) __ptr64` | 1240 (0x4d8) | Exported Function | 0x0000000180036700 | 0x00036700
`protected: void __cdecl CFlexQueue::IncrementIndex(int & __ptr64) __ptr64` | 881 (0x371) | Exported Function | 0x0000000180023e90 | 0x00023e90
`protected: void __cdecl CFlexQueue::DecrementIndex(int & __ptr64) __ptr64` | 581 (0x245) | Exported Function | 0x0000000180023e50 | 0x00023e50
`protected: void __cdecl CEventLogRecord::AddInsertionString(class CInsertionString & __ptr64) __ptr64` | 470 (0x1d6) | Exported Function | 0x000000018002bdb0 | 0x0002bdb0
`protected: void __cdecl CDMTFParser::ParseInterval(unsigned short const * __ptr64) __ptr64` | 1002 (0x3ea) | Exported Function | 0x0000000180025630 | 0x00025630
`protected: void __cdecl CDMTFParser::ParseDate(unsigned short const * __ptr64) __ptr64` | 1001 (0x3e9) | Exported Function | 0x0000000180025570 | 0x00025570
`protected: virtual void __cdecl CExecQueue::ThreadMain(class CExecQueue::CThreadRecord * __ptr64) __ptr64` | 1224 (0x4c8) | Exported Function | 0x00000001800141e0 | 0x000141e0
`protected: void __cdecl CDMTFParser::ParseAbsolute(unsigned short const * __ptr64) __ptr64` | 1000 (0x3e8) | Exported Function | 0x00000001800253c0 | 0x000253c0
`protected: void __cdecl CDateTimeParser::ResetDateTime(int) __ptr64` | 1069 (0x42d) | Exported Function | 0x00000001800293a0 | 0x000293a0
`protected: void __cdecl CDateTimeParser::ResetDate(int) __ptr64` | 1068 (0x42c) | Exported Function | 0x0000000180029370 | 0x00029370
`protected: void __cdecl CDateTimeParser::GetPreferedDateFormat(void) __ptr64` | 779 (0x30b) | Exported Function | 0x0000000180028690 | 0x00028690
`protected: void __cdecl CDateTimeParser::GetLocalInfoAndAlloc(unsigned long,unsigned short * __ptr64 & __ptr64) __ptr64` | 749 (0x2ed) | Exported Function | 0x0000000180028600 | 0x00028600
`protected: void __cdecl CAbstractQl1Parser::DeletePropertyName(void) __ptr64` | 583 (0x247) | Exported Function | 0x0000000180006060 | 0x00006060
`protected: void __cdecl CAbstractQl1Parser::AddAppropriateToken(struct _tag_WbemQl1Token const & __ptr64) __ptr64` | 458 (0x1ca) | Exported Function | 0x0000000180004bf0 | 0x00004bf0
`protected: virtual void __cdecl CTimerGenerator::NotifyStoppingThread(void) __ptr64` | 990 (0x3de) | Exported Function | 0x000000018000a140 | 0x0000a140
`protected: virtual void __cdecl CTimerGenerator::NotifyStartingThread(void) __ptr64` | 989 (0x3dd) | Exported Function | 0x000000018000a140 | 0x0000a140
`protected: void __cdecl CDateTimeParser::ResetTime(int) __ptr64` | 1071 (0x42f) | Exported Function | 0x00000001800293e0 | 0x000293e0
`protected: bool __cdecl CLike::MatchSet(unsigned short const * __ptr64,unsigned short const * __ptr64,int & __ptr64) __ptr64` | 980 (0x3d4) | Exported Function | 0x0000000180031570 | 0x00031570
`protected: bool __cdecl CLike::DoLike(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short) __ptr64` | 595 (0x253) | Exported Function | 0x0000000180031150 | 0x00031150
`protected: bool __cdecl CFlexQueue::Grow(void) __ptr64` | 872 (0x368) | Exported Function | 0x000000018000b770 | 0x0000b770
`IsLocalService` | 922 (0x39a) | Exported Function | 0x000000018003f460 | 0x0003f460
`IsLocalConnection` | 921 (0x399) | Exported Function | 0x00000001800133b0 | 0x000133b0
`IsInAdminGroup` | 918 (0x396) | Exported Function | 0x000000018000d100 | 0x0000d100
`IsAdmin` | 903 (0x387) | Exported Function | 0x000000018000ccc0 | 0x0000ccc0
`GetWMITraceSession` | 866 (0x362) | Exported Function | 0x0000000180045bb0 | 0x00045bb0
`GetWMIADAPCmdLine` | 865 (0x361) | Exported Function | 0x0000000180002290 | 0x00002290
`GetSecurityDescriptorFromParameters` | 810 (0x32a) | Exported Function | 0x000000018003df90 | 0x0003df90
`GetQFDN_Ipv6` | 789 (0x315) | Exported Function | 0x00000001800394c0 | 0x000394c0
`GetMemLogObject` | 756 (0x2f4) | Exported Function | 0x0000000180012e50 | 0x00012e50
`GetLoggingLevelEnabled` | 753 (0x2f1) | Exported Function | 0x0000000180039470 | 0x00039470
`GetGlobalClientOps` | 730 (0x2da) | Exported Function | 0x0000000180013180 | 0x00013180
`GetFQDN_Ipv4` | 720 (0x2d0) | Exported Function | 0x00000001800392a0 | 0x000392a0
`GetAccessToken` | 664 (0x298) | Exported Function | 0x000000018000d1a0 | 0x0000d1a0
`Get_WPP_INIT_TRACING_Call_State` | 871 (0x367) | Exported Function | 0x0000000180045bc0 | 0x00045bc0
`ExtractMachineName` | 643 (0x283) | Exported Function | 0x000000018000cea0 | 0x0000cea0
`ErrorTrace` | 637 (0x27d) | Exported Function | 0x000000018000fcc0 | 0x0000fcc0
`EnablePrivilege` | 615 (0x267) | Exported Function | 0x000000018002f3b0 | 0x0002f3b0
`IsNetworkService` | 924 (0x39c) | Exported Function | 0x000000018003f500 | 0x0003f500
`IsNT` | 923 (0x39b) | Exported Function | 0x0000000180013e90 | 0x00013e90
`IsNtSetupRunning` | 925 (0x39d) | Exported Function | 0x000000018000dc80 | 0x0000dc80
`IsPrivilegePresent` | 930 (0x3a2) | Exported Function | 0x000000018002f520 | 0x0002f520
`private: int __cdecl CWQLScanner::BuildSWQLColRef(class CFlexArray & __ptr64,struct SWQLColRef & __ptr64) __ptr64` | 510 (0x1fe) | Exported Function | 0x0000000180006830 | 0x00006830
`private: int __cdecl CWbemTime::GetDMTF(int,unsigned long,unsigned short * __ptr64) __ptr64` | 702 (0x2be) | Exported Function | 0x0000000180024c60 | 0x00024c60
`private: int __cdecl CTextTemplate::IsEmbeddedObjectProperty(unsigned short * __ptr64) __ptr64` | 906 (0x38a) | Exported Function | 0x00000001800379f0 | 0x000379f0
`private: int __cdecl CSafeArray::SetScalarAt(int,union SA_ArrayScalar) __ptr64` | 1174 (0x496) | Exported Function | 0x0000000180035920 | 0x00035920
`private: int __cdecl CSafeArray::AddScalar(union SA_ArrayScalar) __ptr64` | 484 (0x1e4) | Exported Function | 0x0000000180001240 | 0x00001240
`private: class CWbemCallSecurity & __ptr64 __cdecl CWbemCallSecurity::operator=(class CWbemCallSecurity const & __ptr64) __ptr64` | 325 (0x145) | Exported Function | 0x000000018000b4c0 | 0x0000b4c0
`private: bool __cdecl CIdentitySecurity::EncryptedCall(void) __ptr64` | 616 (0x268) | Exported Function | 0x0000000180024490 | 0x00024490
`private: __cdecl CWbemCallSecurity::~CWbemCallSecurity(void) __ptr64` | 231 (0xe7) | Exported Function | 0x000000018000b320 | 0x0000b320
`EnableAllPrivileges` | 614 (0x266) | Exported Function | 0x0000000180023f30 | 0x00023f30
`private: __cdecl CWbemCallSecurity::CWbemCallSecurity(void) __ptr64` | 148 (0x94) | Exported Function | 0x0000000180009600 | 0x00009600
`NormalizeCimDateTime` | 988 (0x3dc) | Exported Function | 0x00000001800290e0 | 0x000290e0
`mstatic_dwTlsIndex` | 1372 (0x55c) | Exported Function | 0x0000000180075560 | 0x00075560
`LoggingLevelEnabled` | 975 (0x3cf) | Exported Function | 0x000000018000fcb0 | 0x0000fcb0
`IsW2KOrMore` | 957 (0x3bd) | Exported Function | 0x000000018002f600 | 0x0002f600
`IsValidElementName2` | 946 (0x3b2) | Exported Function | 0x0000000180010db0 | 0x00010db0
`IsValidElementName` | 947 (0x3b3) | Exported Function | 0x0000000180010f10 | 0x00010f10
`isunialphanum` | 1336 (0x538) | Exported Function | 0x0000000180010e70 | 0x00010e70
`isunialpha` | 1335 (0x537) | Exported Function | 0x0000000180011020 | 0x00011020
`private: __cdecl CWbemCallSecurity::CWbemCallSecurity(class CWbemCallSecurity const & __ptr64) __ptr64` | 147 (0x93) | Exported Function | 0x000000018000b370 | 0x0000b370
`DumpClientOps` | 601 (0x259) | Exported Function | 0x0000000180046840 | 0x00046840
`DebugTrace` | 580 (0x244) | Exported Function | 0x000000018000fd00 | 0x0000fd00
`CriticalFailADAPTrace` | 561 (0x231) | Exported Function | 0x0000000180039280 | 0x00039280
`const CBuffer::``vftable'` | 415 (0x19f) | Exported Function | 0x000000018004bda0 | 0x0004bda0
`const CBasicUnloadInstruction::``vftable'` | 414 (0x19e) | Exported Function | 0x000000018004bcb8 | 0x0004bcb8
`const CBaseAce::``vftable'` | 413 (0x19d) | Exported Function | 0x000000018004bb60 | 0x0004bb60
`const CArena::``vftable'` | 412 (0x19c) | Exported Function | 0x000000018004c918 | 0x0004c918
`const CAbstractQl1Parser::``vftable'` | 411 (0x19b) | Exported Function | 0x000000018004bb50 | 0x0004bb50
`const C9XAce::``vftable'` | 410 (0x19a) | Exported Function | 0x000000018004cb30 | 0x0004cb30
`ComposeName` | 542 (0x21e) | Exported Function | 0x0000000180046c50 | 0x00046c50
`ChangeVariantToCIMTYPE` | 518 (0x206) | Exported Function | 0x0000000180012400 | 0x00012400
`const CContainerControl::``vftable'` | 416 (0x1a0) | Exported Function | 0x000000018004cb78 | 0x0004cb78
`BuildSecurityDescriptorParameter` | 511 (0x1ff) | Exported Function | 0x000000018003bb70 | 0x0003bb70
`BreakOnDbgAndRenterLoop` | 507 (0x1fb) | Exported Function | 0x0000000180043490 | 0x00043490
`BlobCopy` | 506 (0x1fa) | Exported Function | 0x0000000180039190 | 0x00039190
`BlobClear` | 505 (0x1f9) | Exported Function | 0x0000000180039160 | 0x00039160
`BlobAssign` | 504 (0x1f8) | Exported Function | 0x00000001800390a0 | 0x000390a0
`bAreWeLocal` | 1321 (0x529) | Exported Function | 0x000000018000d010 | 0x0000d010
`AdjustPrivIfLocalSystem` | 492 (0x1ec) | Exported Function | 0x0000000180003de0 | 0x00003de0
`_ThrowMemoryException_` | 1315 (0x523) | Exported Function | 0x0000000180039df0 | 0x00039df0
`_IsValidElementName` | 1309 (0x51d) | Exported Function | 0x0000000180039d10 | 0x00039d10
`BuildOperationInfo` | 509 (0x1fd) | Exported Function | 0x0000000180004d20 | 0x00004d20
`private: int __cdecl CWQLScanner::ExtractSelectType(void) __ptr64` | 645 (0x285) | Exported Function | 0x000000018000b120 | 0x0000b120
`const CExecQueue::``vftable'` | 417 (0x1a1) | Exported Function | 0x000000018004cb98 | 0x0004cb98
`const CHaltable::``vftable'` | 419 (0x1a3) | Exported Function | 0x000000018004cb28 | 0x0004cb28
`CopyFileToAutorecover` | 554 (0x22a) | Exported Function | 0x0000000180046e50 | 0x00046e50
`const SZLess<unsigned short const * __ptr64>::``vftable'` | 409 (0x199) | Exported Function | 0x000000018004bd70 | 0x0004bd70
`const QL_LEVEL_1_RPN_EXPRESSION::``vftable'` | 435 (0x1b3) | Exported Function | 0x000000018004bc50 | 0x0004bc50
`const QL1_Parser::``vftable'` | 434 (0x1b2) | Exported Function | 0x000000018004bb40 | 0x0004bb40
`const CWin32DefaultArena::``vftable'` | 433 (0x1b1) | Exported Function | 0x000000018004cb10 | 0x0004cb10
`const CWbemCallSecurity::``vftable'` | 432 (0x1b0) | Exported Function | 0x000000018004bbf0 | 0x0004bbf0
`const CUnkInternal::``vftable'` | 431 (0x1af) | Exported Function | 0x000000018004bd78 | 0x0004bd78
`const CUnk::``vftable'` | 430 (0x1ae) | Exported Function | 0x000000018004bd38 | 0x0004bd38
`const CExecRequest::``vftable'` | 418 (0x1a2) | Exported Function | 0x000000018004be30 | 0x0004be30
`const CTimerInstruction::``vftable'` | 429 (0x1ad) | Exported Function | 0x000000018004bcf8 | 0x0004bcf8
`const CRegistryMinMaxLimitControl::``vftable'` | 427 (0x1ab) | Exported Function | 0x000000018004cc68 | 0x0004cc68
`const CQl1ParseSink::``vftable'` | 426 (0x1aa) | Exported Function | 0x000000018004c938 | 0x0004c938
`const CNtAce::``vftable'` | 425 (0x1a9) | Exported Function | 0x000000018004bba8 | 0x0004bba8
`const CMinMaxLimitControl::``vftable'` | 424 (0x1a8) | Exported Function | 0x000000018004cc90 | 0x0004cc90
`const CLimitControl::``vftable'` | 423 (0x1a7) | Exported Function | 0x000000018004c9a0 | 0x0004c9a0
`const CLifeControl::``vftable'` | 422 (0x1a6) | Exported Function | 0x000000018004be10 | 0x0004be10
`const CInstructionTest::``vftable'` | 421 (0x1a5) | Exported Function | 0x000000018004c998 | 0x0004c998
`const CIdentityTest::``vftable'` | 420 (0x1a4) | Exported Function | 0x000000018004bcb0 | 0x0004bcb0
`const CTimerGenerator::``vftable'` | 428 (0x1ac) | Exported Function | 0x000000018004cc48 | 0x0004cc48
`private: int __cdecl CWQLScanner::Next(void) __ptr64` | 987 (0x3db) | Exported Function | 0x000000018000bc50 | 0x0000bc50
`private: int __cdecl CWQLScanner::Pushback(struct WSLexToken * __ptr64) __ptr64` | 1020 (0x3fc) | Exported Function | 0x0000000180005500 | 0x00005500
`private: int __cdecl CWQLScanner::ReduceSql89Joins(void) __ptr64` | 1035 (0x40b) | Exported Function | 0x0000000180005330 | 0x00005330
`private: void __cdecl CBuffer::EnsureSize(unsigned long) __ptr64` | 627 (0x273) | Exported Function | 0x0000000180023430 | 0x00023430
`private: void __cdecl CBaseMrciCompression::putbits(unsigned int,unsigned int) __ptr64` | 1383 (0x567) | Exported Function | 0x00000001800331a0 | 0x000331a0
`private: void __cdecl CBaseMrciCompression::outlength(unsigned int) __ptr64` | 1377 (0x561) | Exported Function | 0x0000000180033080 | 0x00033080
`private: void __cdecl CBaseMrciCompression::mrci2outstring(unsigned int,unsigned int) __ptr64` | 1369 (0x559) | Exported Function | 0x0000000180033000 | 0x00033000
`private: void __cdecl CBaseMrciCompression::mrci2outsingle(unsigned int) __ptr64` | 1368 (0x558) | Exported Function | 0x0000000180032fd0 | 0x00032fd0
`private: void __cdecl CBaseMrciCompression::mrci1outstring(unsigned int,unsigned int) __ptr64` | 1367 (0x557) | Exported Function | 0x0000000180032f60 | 0x00032f60
`private: void __cdecl CBaseMrciCompression::mrci1outsingle(unsigned int) __ptr64` | 1366 (0x556) | Exported Function | 0x0000000180032f30 | 0x00032f30
`private: void __cdecl CBaseMrciCompression::inithash(void) __ptr64` | 1332 (0x534) | Exported Function | 0x0000000180032f00 | 0x00032f00
`private: void __cdecl CClientOpsNode::Insert(class CClientOpsNode * __ptr64) __ptr64` | 893 (0x37d) | Exported Function | 0x0000000180011230 | 0x00011230
`private: void __cdecl CBaseMrciCompression::expandstring(unsigned char * __ptr64 * __ptr64,unsigned int,unsigned int) __ptr64` | 1326 (0x52e) | Exported Function | 0x0000000180032d60 | 0x00032d60
`private: unsigned short * __ptr64 __cdecl CTextTemplate::ReturnEscapedReturns(unsigned short * __ptr64) __ptr64` | 1077 (0x435) | Exported Function | 0x0000000180037b20 | 0x00037b20
`private: unsigned short * __ptr64 __cdecl CTextTemplate::ProcessArray(struct tagVARIANT const & __ptr64,unsigned short * __ptr64) __ptr64` | 1005 (0x3ed) | Exported Function | 0x0000000180037a40 | 0x00037a40
`private: unsigned short * __ptr64 __cdecl CTextTemplate::HandleEmbeddedObjectProperties(unsigned short * __ptr64,struct IWbemClassObject * __ptr64) __ptr64` | 875 (0x36b) | Exported Function | 0x0000000180037590 | 0x00037590
`private: unsigned short * __ptr64 __cdecl CTextTemplate::GetPropertyFromIUnknown(unsigned short * __ptr64,struct IUnknown * __ptr64) __ptr64` | 784 (0x310) | Exported Function | 0x0000000180037160 | 0x00037160
`private: unsigned int __cdecl CBaseMrciCompression::getbits(unsigned int) __ptr64` | 1331 (0x533) | Exported Function | 0x0000000180032e20 | 0x00032e20
`private: unsigned int __cdecl CBaseMrciCompression::getbit(void) __ptr64` | 1330 (0x532) | Exported Function | 0x0000000180032da0 | 0x00032da0
`private: union SA_ArrayScalar __cdecl CSafeArray::GetScalarAt(int) __ptr64` | 807 (0x327) | Exported Function | 0x000000018000a1c0 | 0x0000a1c0
`private: struct WSLexToken * __ptr64 __cdecl CWQLScanner::ExtractNext(int) __ptr64` | 644 (0x284) | Exported Function | 0x0000000180005480 | 0x00005480
`private: void __cdecl CBaseMrciCompression::charbuf(unsigned int) __ptr64` | 1322 (0x52a) | Exported Function | 0x0000000180032d10 | 0x00032d10
`private: static void * __ptr64 __ptr64 CMUILocale::m_fSetThreadPreferredUILanguages` | 1353 (0x549) | Exported Function | 0x000000018007b228 | 0x0007b228
`private: void __cdecl CClientOpsNode::UpdateChildren(class CClientOpsNode * __ptr64) __ptr64` | 1272 (0x4f8) | Exported Function | 0x0000000180046890 | 0x00046890
`private: void __cdecl CLike::FinalizeMatchState(void) __ptr64` | 654 (0x28e) | Exported Function | 0x0000000180031510 | 0x00031510
`protected: __cdecl CWbemTime::CWbemTime(__int64) __ptr64` | 153 (0x99) | Exported Function | 0x0000000180024aa0 | 0x00024aa0
`protected: __cdecl CWbemInterval::CWbemInterval(unsigned long) __ptr64` | 151 (0x97) | Exported Function | 0x0000000180024a80 | 0x00024a80
`protected: __cdecl CDateTimeParser::CDateTimeParser(void) __ptr64` | 30 (0x1e) | Exported Function | 0x0000000180025a60 | 0x00025a60
`protected: __cdecl CBasicUnloadInstruction::CBasicUnloadInstruction(void) __ptr64` | 16 (0x10) | Exported Function | 0x00000001800434e0 | 0x000434e0
`private: void __cdecl WString::DeleteString(unsigned short * __ptr64) __ptr64` | 587 (0x24b) | Exported Function | 0x00000001800134d0 | 0x000134d0
`private: void __cdecl WString2::DeleteString(bool) __ptr64` | 586 (0x24a) | Exported Function | 0x00000001800035f0 | 0x000035f0
`private: void __cdecl WString2::CopyBuffer(unsigned short const * __ptr64,unsigned __int64) __ptr64` | 551 (0x227) | Exported Function | 0x0000000180002b60 | 0x00002b60
`private: void __cdecl WString2::AppendBuffer(unsigned short const * __ptr64,unsigned __int64) __ptr64` | 497 (0x1f1) | Exported Function | 0x00000001800033a0 | 0x000033a0
`private: void __cdecl CLike::EnsureMatchState(unsigned __int64) __ptr64` | 625 (0x271) | Exported Function | 0x0000000180031460 | 0x00031460
`private: void __cdecl CWQLScanner::ClearTokens(void) __ptr64` | 529 (0x211) | Exported Function | 0x00000001800087a0 | 0x000087a0
`private: void __cdecl CWQLScanner::ClearPropRefs(void) __ptr64` | 527 (0x20f) | Exported Function | 0x000000018000b1e0 | 0x0000b1e0
`private: void __cdecl CVar::Init(void) __ptr64` | 884 (0x374) | Exported Function | 0x00000001800120b0 | 0x000120b0
`private: void __cdecl CTimerGenerator::EnsureRunning(void) __ptr64` | 626 (0x272) | Exported Function | 0x000000018000fb30 | 0x0000fb30
`private: void __cdecl CTextTemplate::ConcatWithoutQuotes(class WString2 & __ptr64,unsigned short * __ptr64 & __ptr64) __ptr64` | 549 (0x225) | Exported Function | 0x00000001800370e0 | 0x000370e0
`private: void __cdecl CSafeArray::Fatal(char const * __ptr64) __ptr64` | 650 (0x28a) | Exported Function | 0x000000018000a140 | 0x0000a140
`private: void __cdecl CSafeArray::CheckType(int) __ptr64` | 525 (0x20d) | Exported Function | 0x000000018000a140 | 0x0000a140
`private: void __cdecl CMemoryLog::CaptureStackTrace(void * __ptr64 * __ptr64 const) __ptr64` | 514 (0x202) | Exported Function | 0x0000000180045860 | 0x00045860
`private: void __cdecl CLike::SwitchRow(unsigned __int64,unsigned char * __ptr64 & __ptr64,unsigned char * __ptr64 & __ptr64) __ptr64` | 1221 (0x4c5) | Exported Function | 0x0000000180031840 | 0x00031840
`private: void __cdecl CWQLScanner::ClearTableRefs(void) __ptr64` | 528 (0x210) | Exported Function | 0x000000018000a150 | 0x0000a150
`public: __cdecl CExecRequest::CExecRequest(class CExecRequest const & __ptr64) __ptr64` | 39 (0x27) | Exported Function | 0x000000018002d3e0 | 0x0002d3e0
`private: static void * __ptr64 __ptr64 CMUILocale::m_fLocaleNameToLCID` | 1352 (0x548) | Exported Function | 0x000000018007b220 | 0x0007b220
`private: static void * __ptr64 __ptr64 CMUILocale::m_fGetThreadPreferredUILanguages` | 1350 (0x546) | Exported Function | 0x000000018007b230 | 0x0007b230
`private: static long (__cdecl* __ptr64 CWbemInstallObject::m_pfFlushCache)(int)` | 1357 (0x54d) | Exported Function | 0x000000018007d350 | 0x0007d350
`private: static int CStaticCritSec::anyFailed_` | 1319 (0x527) | Exported Function | 0x000000018007b1f0 | 0x0007b1f0
`private: static class std::map<unsigned short const * __ptr64,unsigned short const * __ptr64,struct SZLess<unsigned short const * __ptr64>,class wbem_allocator<unsigned short const * __ptr64> > * __ptr64 __ptr64 CWbemInstallObject::m_pEnvironmentMap` | 1356 (0x54c) | Exported Function | 0x000000018007b1f8 | 0x0007b1f8
`private: static class CCritSec CPublishWMIOperationEvent::m_csFunctionPointers` | 1340 (0x53c) | Exported Function | 0x000000018007b430 | 0x0007b430
`private: static class CCritSec CMUILocale::m_csFunctionPointers` | 1339 (0x53b) | Exported Function | 0x000000018007b408 | 0x0007b408
`private: static class CCritSec CClientOpsNode::m_csGlobal` | 1341 (0x53d) | Exported Function | 0x000000018007b3b8 | 0x0007b3b8
`private: static bool CWbemInstallObject::m_bOffline` | 1338 (0x53a) | Exported Function | 0x000000018007b200 | 0x0007b200
`private: static bool __cdecl CWbemInstallObject::IsInitialized(void)` | 919 (0x397) | Exported Function | 0x00000001800454d0 | 0x000454d0
`private: static long __cdecl CMUILocale::GetFunctionPointers(void)` | 728 (0x2d8) | Exported Function | 0x000000018000a970 | 0x0000a970
`private: long __cdecl CWbemCallSecurity::CloneThreadToken(unsigned long) __ptr64` | 533 (0x215) | Exported Function | 0x0000000180003c50 | 0x00003c50
`private: long __cdecl CMUILocaleList::AppendCulture(unsigned short const * __ptr64) __ptr64` | 498 (0x1f2) | Exported Function | 0x00000001800044c0 | 0x000044c0
`private: long __cdecl CMUILocaleList::AddLocale(unsigned short const * __ptr64,enum CMUILocale::LocaleType,unsigned long) __ptr64` | 471 (0x1d7) | Exported Function | 0x0000000180004580 | 0x00004580
`private: long __cdecl CMUILocaleList::AddCulture(unsigned short const * __ptr64,enum CMUILocale::LocaleType,unsigned long) __ptr64` | 463 (0x1cf) | Exported Function | 0x0000000180004390 | 0x00004390
`private: long __cdecl CIdentitySecurity::GetSidFromThreadOrProcess(class CNtSid & __ptr64) __ptr64` | 819 (0x333) | Exported Function | 0x0000000180006490 | 0x00006490
`private: long __cdecl CIdentitySecurity::_RetrieveSidFromCall(class CNtSid & __ptr64) __ptr64` | 1312 (0x520) | Exported Function | 0x00000001800061a0 | 0x000061a0
`private: int __cdecl CWQLScanner::StripWhereClause(void) __ptr64` | 1218 (0x4c2) | Exported Function | 0x0000000180008260 | 0x00008260
`private: int __cdecl CWQLScanner::SelectList(void) __ptr64` | 1085 (0x43d) | Exported Function | 0x0000000180006560 | 0x00006560
`private: int __cdecl CWQLScanner::ReduceSql92Joins(void) __ptr64` | 1036 (0x40c) | Exported Function | 0x0000000180042f30 | 0x00042f30
`private: long __cdecl CMUILocaleList::AppendLocale(unsigned short const * __ptr64) __ptr64` | 499 (0x1f3) | Exported Function | 0x00000001800046b0 | 0x000046b0
`private: static void * __ptr64 __ptr64 CMUILocale::m_fLCIDToLocaleName` | 1351 (0x547) | Exported Function | 0x000000018007b210 | 0x0007b210
`private: static long __cdecl CWbemInstallObject::ExpandVariableValue(unsigned short const * __ptr64,unsigned short * __ptr64,unsigned __int64,unsigned __int64 * __ptr64)` | 642 (0x282) | Exported Function | 0x0000000180045380 | 0x00045380
`private: static struct ClsidDllMapping * CWbemInstallObject::m_rgClsidDllMap` | 1364 (0x554) | Exported Function | 0x0000000180075430 | 0x00075430
`private: static void * __ptr64 __ptr64 CMUILocale::m_fGetSystemDefaultLocaleName` | 1349 (0x545) | Exported Function | 0x000000018007b208 | 0x0007b208
`private: static void * __ptr64 __ptr64 CMUILocale::m_fGetLocaleInfoEx` | 1348 (0x544) | Exported Function | 0x000000018007b218 | 0x0007b218
`private: static unsigned short const * __ptr64 const __ptr64 CWbemInstallObject::m_pwszRepositoryPath` | 1363 (0x553) | Exported Function | 0x000000018007d358 | 0x0007d358
`private: static unsigned short const * __ptr64 const __ptr64 CWbemInstallObject::m_pwszRegistryPathWbem` | 1362 (0x552) | Exported Function | 0x000000018007d2b8 | 0x0007d2b8
`private: static unsigned short const * __ptr64 const __ptr64 CWbemInstallObject::m_pwszRegistryPathCIMOM` | 1361 (0x551) | Exported Function | 0x000000018007d2b0 | 0x0007d2b0
`private: static unsigned short const * __ptr64 const __ptr64 CWbemInstallObject::m_pwszBinaryPath` | 1360 (0x550) | Exported Function | 0x000000018007d360 | 0x0007d360
`private: static unsigned short const * __ptr64 const __ptr64 CWbemInstallObject::m_pwszAutoRecoverPath` | 1359 (0x54f) | Exported Function | 0x000000018007d2c0 | 0x0007d2c0
`private: static unsigned long __cdecl CTimerGenerator::SchedulerThread(void * __ptr64)` | 1081 (0x439) | Exported Function | 0x000000018000f5b0 | 0x0000f5b0
`private: static long __cdecl CWbemInstallObject::GetEnvironmentValue(unsigned short const * __ptr64,unsigned short const * __ptr64 * __ptr64)` | 716 (0x2cc) | Exported Function | 0x0000000180045450 | 0x00045450
`private: static unsigned long (__cdecl* __ptr64 CPublishWMIOperationEvent::m_fEventWrite)(unsigned __int64,struct _EVENT_DESCRIPTOR * __ptr64,unsigned long,struct _EVENT_DATA_DESCRIPTOR * __ptr64)` | 1346 (0x542) | Exported Function | 0x000000018007b258 | 0x0007b258
`private: static unsigned long (__cdecl* __ptr64 CPublishWMIOperationEvent::m_fEventRegister)(struct _GUID const * __ptr64,void (__cdecl*)(struct _GUID const * __ptr64,unsigned long,unsigned char,unsigned __int64,unsigned __int64,struct _EVENT_FILTER_DESCRIPTOR * __ptr64,void * __ptr64),void * __ptr64,unsigned __int64 * __ptr64)` | 1344 (0x540) | Exported Function | 0x000000018007b268 | 0x0007b268
`private: static unsigned char const CLike::sNoMatch` | 1387 (0x56b) | Exported Function | 0x0000000180055dc2 | 0x00055dc2
`private: static unsigned char const CLike::sMatachedWithWildcardChar` | 1386 (0x56a) | Exported Function | 0x0000000180055dc1 | 0x00055dc1
`private: static unsigned char const CLike::sMatachedWithOneChar` | 1385 (0x569) | Exported Function | 0x0000000180055dc0 | 0x00055dc0
`private: static unsigned char (__cdecl* __ptr64 CPublishWMIOperationEvent::m_fEventEnabled)(unsigned __int64,struct _EVENT_DESCRIPTOR const * __ptr64)` | 1343 (0x53f) | Exported Function | 0x000000018007b240 | 0x0007b240
`private: static struct HINSTANCE__ * __ptr64 __ptr64 CPublishWMIOperationEvent::m_hAdvAPI32` | 1354 (0x54a) | Exported Function | 0x000000018007b270 | 0x0007b270
`private: static struct HINSTANCE__ * __ptr64 __ptr64 CMUILocale::m_hKernel32` | 1355 (0x54b) | Exported Function | 0x000000018007b238 | 0x0007b238
`private: static struct DllModuleHandle * CWbemInstallObject::m_rgDllModules` | 1365 (0x555) | Exported Function | 0x00000001800754e0 | 0x000754e0
`private: static unsigned long (__cdecl* __ptr64 CPublishWMIOperationEvent::m_fEventUnregister)(unsigned __int64)` | 1345 (0x541) | Exported Function | 0x000000018007b260 | 0x0007b260
`public: __cdecl CExecRequest::CExecRequest(void) __ptr64` | 40 (0x28) | Exported Function | 0x0000000180014810 | 0x00014810
`public: __cdecl CFlexArray::CFlexArray(class CFlexArray & __ptr64) __ptr64` | 41 (0x29) | Exported Function | 0x000000018002e600 | 0x0002e600
`public: __cdecl CFlexArray::CFlexArray(int,int) __ptr64` | 42 (0x2a) | Exported Function | 0x000000018000b930 | 0x0000b930
`public: class CFlexArray & __ptr64 __cdecl CFlexArray::operator=(class CFlexArray & __ptr64) __ptr64` | 266 (0x10a) | Exported Function | 0x000000018002e780 | 0x0002e780
`public: class CExecRequest * __ptr64 __cdecl CExecRequest::GetNext(void) __ptr64` | 766 (0x2fe) | Exported Function | 0x0000000180013110 | 0x00013110
`public: class CExecRequest & __ptr64 __cdecl CExecRequest::operator=(class CExecRequest const & __ptr64) __ptr64` | 265 (0x109) | Exported Function | 0x000000018002d610 | 0x0002d610
`public: class CExecQueue & __ptr64 __cdecl CExecQueue::operator=(class CExecQueue & __ptr64) __ptr64` | 264 (0x108) | Exported Function | 0x000000018002d4f0 | 0x0002d4f0
`public: class CEnterWbemCriticalSection & __ptr64 __cdecl CEnterWbemCriticalSection::operator=(class CEnterWbemCriticalSection const & __ptr64) __ptr64` | 263 (0x107) | Exported Function | 0x0000000180023c60 | 0x00023c60
`public: class CDMTFParser & __ptr64 __cdecl CDMTFParser::operator=(class CDMTFParser const & __ptr64) __ptr64` | 260 (0x104) | Exported Function | 0x0000000180025090 | 0x00025090
`public: class CDateTimeParser & __ptr64 __cdecl CDateTimeParser::operator=(class CDateTimeParser const & __ptr64) __ptr64` | 262 (0x106) | Exported Function | 0x00000001800250c0 | 0x000250c0
`public: class CDatePart & __ptr64 __cdecl CDatePart::operator=(class CDatePart const & __ptr64) __ptr64` | 261 (0x105) | Exported Function | 0x0000000180023d10 | 0x00023d10
`public: class CCritSec & __ptr64 __cdecl CCritSec::operator=(class CCritSec const & __ptr64) __ptr64` | 259 (0x103) | Exported Function | 0x0000000180023c80 | 0x00023c80
`public: class CContainerControl & __ptr64 __cdecl CContainerControl::operator=(class CContainerControl const & __ptr64) __ptr64` | 258 (0x102) | Exported Function | 0x000000018002b940 | 0x0002b940
`public: class CContainerControl & __ptr64 __cdecl CContainerControl::operator=(class CContainerControl && __ptr64) __ptr64` | 257 (0x101) | Exported Function | 0x000000018002b940 | 0x0002b940
`public: class CClientOpsNode * __ptr64 __cdecl CClientOpsNode::GetPrevious(void) __ptr64` | 782 (0x30e) | Exported Function | 0x0000000180010d00 | 0x00010d00
`public: class CClientOpsNode * __ptr64 __cdecl CClientOpsNode::GetNext(void) __ptr64` | 765 (0x2fd) | Exported Function | 0x0000000180013110 | 0x00013110
`public: class CClientOpsNode * __ptr64 __cdecl CClientOpsNode::GetChildren(void) __ptr64` | 697 (0x2b9) | Exported Function | 0x0000000180034420 | 0x00034420
`public: class CClientOpsNode & __ptr64 __cdecl CClientOpsNode::operator=(class CClientOpsNode const & __ptr64) __ptr64` | 256 (0x100) | Exported Function | 0x0000000180023c80 | 0x00023c80
`public: class CCircularQueue & __ptr64 __cdecl CCircularQueue::operator=(class CCircularQueue const & __ptr64) __ptr64` | 255 (0xff) | Exported Function | 0x0000000180023060 | 0x00023060
`public: class CCircularQueue & __ptr64 __cdecl CCircularQueue::operator=(class CCircularQueue && __ptr64) __ptr64` | 254 (0xfe) | Exported Function | 0x0000000180023000 | 0x00023000
`public: class CFlexArray const * __ptr64 __cdecl CWQLScanner::GetSelectedColumns(void) __ptr64` | 811 (0x32b) | Exported Function | 0x0000000180013550 | 0x00013550
`public: class CFlexQueue & __ptr64 __cdecl CFlexQueue::operator=(class CFlexQueue const & __ptr64) __ptr64` | 267 (0x10b) | Exported Function | 0x0000000180023cb0 | 0x00023cb0
`public: class CHaltable & __ptr64 __cdecl CHaltable::operator=(class CHaltable const & __ptr64) __ptr64` | 268 (0x10c) | Exported Function | 0x0000000180023cd0 | 0x00023cd0
`public: class CHex & __ptr64 __cdecl CHex::operator=(class CHex && __ptr64) __ptr64` | 269 (0x10d) | Exported Function | 0x0000000180024b30 | 0x00024b30
`public: class CMinMaxLimitControl & __ptr64 __cdecl CMinMaxLimitControl::operator=(class CMinMaxLimitControl && __ptr64) __ptr64` | 291 (0x123) | Exported Function | 0x0000000180043f00 | 0x00043f00
`public: class CMemoryLog & __ptr64 __cdecl CMemoryLog::operator=(class CMemoryLog const & __ptr64) __ptr64` | 290 (0x122) | Exported Function | 0x00000001800230d0 | 0x000230d0
`public: class CMemoryLog & __ptr64 __cdecl CMemoryLog::operator=(class CMemoryLog && __ptr64) __ptr64` | 289 (0x121) | Exported Function | 0x0000000180023090 | 0x00023090
`public: class CLockableFlexArray<class CStaticCritSec> & __ptr64 __cdecl CLockableFlexArray<class CStaticCritSec>::operator=(class CLockableFlexArray<class CStaticCritSec> && __ptr64) __ptr64` | 241 (0xf1) | Exported Function | 0x000000018002e730 | 0x0002e730
`public: class CLockableFlexArray<class CStaticCritSec> & __ptr64 __cdecl CLockableFlexArray<class CStaticCritSec>::operator=(class CLockableFlexArray<class CStaticCritSec> & __ptr64) __ptr64` | 242 (0xf2) | Exported Function | 0x000000018002e730 | 0x0002e730
`public: class CLimitControl & __ptr64 __cdecl CLimitControl::operator=(class CLimitControl const & __ptr64) __ptr64` | 282 (0x11a) | Exported Function | 0x0000000180043ee0 | 0x00043ee0
`public: class CLike & __ptr64 __cdecl CLike::operator=(class CLike const & __ptr64) __ptr64` | 281 (0x119) | Exported Function | 0x0000000180031100 | 0x00031100
`public: class CLifeControl & __ptr64 __cdecl CLifeControl::operator=(class CLifeControl const & __ptr64) __ptr64` | 280 (0x118) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CCheckedInCritSec & __ptr64 __cdecl CCheckedInCritSec::operator=(class CCheckedInCritSec const & __ptr64) __ptr64` | 253 (0xfd) | Exported Function | 0x0000000180023c60 | 0x00023c60
`public: class CLifeControl & __ptr64 __cdecl CLifeControl::operator=(class CLifeControl && __ptr64) __ptr64` | 279 (0x117) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CInstructionTest & __ptr64 __cdecl CInstructionTest::operator=(class CInstructionTest && __ptr64) __ptr64` | 277 (0x115) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CInstructionQueue & __ptr64 __cdecl CInstructionQueue::operator=(class CInstructionQueue const & __ptr64) __ptr64` | 276 (0x114) | Exported Function | 0x0000000180036260 | 0x00036260
`public: class CInsertionString & __ptr64 __cdecl CInsertionString::operator=(class CInsertionString const & __ptr64) __ptr64` | 275 (0x113) | Exported Function | 0x000000018002b960 | 0x0002b960
`public: class CInsertionString & __ptr64 __cdecl CInsertionString::operator=(class CInsertionString && __ptr64) __ptr64` | 274 (0x112) | Exported Function | 0x000000018002b960 | 0x0002b960
`public: class CInCritSec & __ptr64 __cdecl CInCritSec::operator=(class CInCritSec const & __ptr64) __ptr64` | 273 (0x111) | Exported Function | 0x0000000180023d10 | 0x00023d10
`public: class CIdentityTest & __ptr64 __cdecl CIdentityTest::operator=(class CIdentityTest const & __ptr64) __ptr64` | 272 (0x110) | Exported Function | 0x000000018002b940 | 0x0002b940
`public: class CIdentitySecurity & __ptr64 __cdecl CIdentitySecurity::operator=(class CIdentitySecurity const & __ptr64) __ptr64` | 271 (0x10f) | Exported Function | 0x0000000180024280 | 0x00024280
`public: class CHex & __ptr64 __cdecl CHex::operator=(class CHex const & __ptr64) __ptr64` | 270 (0x10e) | Exported Function | 0x0000000180024b30 | 0x00024b30
`public: class CInstructionTest & __ptr64 __cdecl CInstructionTest::operator=(class CInstructionTest const & __ptr64) __ptr64` | 278 (0x116) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CBuffer & __ptr64 __cdecl CBuffer::operator=(class CBuffer const & __ptr64) __ptr64` | 252 (0xfc) | Exported Function | 0x0000000180022fc0 | 0x00022fc0
`public: class CBasicUnloadInstruction & __ptr64 __cdecl CBasicUnloadInstruction::operator=(class CBasicUnloadInstruction const & __ptr64) __ptr64` | 251 (0xfb) | Exported Function | 0x00000001800435d0 | 0x000435d0
`public: class CBaseMrciCompression & __ptr64 __cdecl CBaseMrciCompression::operator=(class CBaseMrciCompression const & __ptr64) __ptr64` | 250 (0xfa) | Exported Function | 0x0000000180031a30 | 0x00031a30
`public: bool __cdecl CDMTFParser::IsInterval(void) __ptr64` | 920 (0x398) | Exported Function | 0x0000000180025350 | 0x00025350
`public: bool __cdecl CClientOpsNode::HasChildren(void) __ptr64` | 876 (0x36c) | Exported Function | 0x0000000180045bd0 | 0x00045bd0
`public: __int64 __cdecl CWbemTime::Get100nss(void)const __ptr64` | 660 (0x294) | Exported Function | 0x00000001800117b0 | 0x000117b0
`public: __cdecl WString::~WString(void) __ptr64` | 240 (0xf0) | Exported Function | 0x0000000180010d10 | 0x00010d10
`public: __cdecl WString::WString(void) __ptr64` | 181 (0xb5) | Exported Function | 0x00000001800120d0 | 0x000120d0
`public: __cdecl WString::WString(unsigned short const * __ptr64) __ptr64` | 180 (0xb4) | Exported Function | 0x00000001800114a0 | 0x000114a0
`public: __cdecl WString::WString(unsigned short * __ptr64,int) __ptr64` | 178 (0xb2) | Exported Function | 0x0000000180011260 | 0x00011260
`public: __cdecl WString::WString(unsigned long,struct HINSTANCE__ * __ptr64) __ptr64` | 177 (0xb1) | Exported Function | 0x0000000180040de0 | 0x00040de0
`public: bool __cdecl CDMTFParser::IsUsed(int) __ptr64` | 934 (0x3a6) | Exported Function | 0x0000000180025360 | 0x00025360
`public: __cdecl WString::WString(class WString const & __ptr64) __ptr64` | 176 (0xb0) | Exported Function | 0x0000000180005ac0 | 0x00005ac0
`public: __cdecl WString::operator unsigned short const * __ptr64(void)const __ptr64` | 377 (0x179) | Exported Function | 0x00000001800117b0 | 0x000117b0
`public: __cdecl WString::operator unsigned short * __ptr64(void) __ptr64` | 376 (0x178) | Exported Function | 0x00000001800117b0 | 0x000117b0
`public: __cdecl WString2::~WString2(void) __ptr64` | 239 (0xef) | Exported Function | 0x0000000180011540 | 0x00011540
`public: __cdecl WString2::WString2(void) __ptr64` | 174 (0xae) | Exported Function | 0x0000000180003650 | 0x00003650
`public: __cdecl WString2::WString2(unsigned short const * __ptr64) __ptr64` | 173 (0xad) | Exported Function | 0x0000000180002b00 | 0x00002b00
`public: __cdecl WString2::WString2(unsigned short * __ptr64,int) __ptr64` | 171 (0xab) | Exported Function | 0x0000000180002a60 | 0x00002a60
`public: __cdecl WString2::WString2(unsigned long,struct HINSTANCE__ * __ptr64) __ptr64` | 170 (0xaa) | Exported Function | 0x0000000180041ce0 | 0x00041ce0
`public: __cdecl WString2::WString2(unsigned __int64) __ptr64` | 175 (0xaf) | Exported Function | 0x0000000180012910 | 0x00012910
`public: __cdecl WString::WString(char const * __ptr64) __ptr64` | 179 (0xb3) | Exported Function | 0x0000000180040ef0 | 0x00040ef0
`public: class CMinMaxLimitControl & __ptr64 __cdecl CMinMaxLimitControl::operator=(class CMinMaxLimitControl const & __ptr64) __ptr64` | 292 (0x124) | Exported Function | 0x0000000180043f00 | 0x00043f00
`public: bool __cdecl CDMTFParser::IsValid(void) __ptr64` | 937 (0x3a9) | Exported Function | 0x0000000180025380 | 0x00025380
`public: bool __cdecl CExecRequest::IsOk(void) __ptr64` | 928 (0x3a0) | Exported Function | 0x000000018002db30 | 0x0002db30
`public: class CBaseMrciCompression & __ptr64 __cdecl CBaseMrciCompression::operator=(class CBaseMrciCompression && __ptr64) __ptr64` | 249 (0xf9) | Exported Function | 0x00000001800319d0 | 0x000319d0
`public: class CBaseAce & __ptr64 __cdecl CBaseAce::operator=(class CBaseAce const & __ptr64) __ptr64` | 248 (0xf8) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CArena & __ptr64 __cdecl CArena::operator=(class CArena const & __ptr64) __ptr64` | 247 (0xf7) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CArena & __ptr64 __cdecl CArena::operator=(class CArena && __ptr64) __ptr64` | 246 (0xf6) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CAbstractQl1Parser & __ptr64 __cdecl CAbstractQl1Parser::operator=(class CAbstractQl1Parser const & __ptr64) __ptr64` | 245 (0xf5) | Exported Function | 0x00000001800337f0 | 0x000337f0
`public: class C9XAce & __ptr64 __cdecl C9XAce::operator=(class C9XAce const & __ptr64) __ptr64` | 244 (0xf4) | Exported Function | 0x0000000180024250 | 0x00024250
`public: char __cdecl CVar::GetChar(void) __ptr64` | 696 (0x2b8) | Exported Function | 0x000000018002baa0 | 0x0002baa0
`public: char * __ptr64 __cdecl WString::GetLPSTR(void)const __ptr64` | 744 (0x2e8) | Exported Function | 0x0000000180041560 | 0x00041560
`public: bool __cdecl CDMTFParser::IsWildcard(int) __ptr64` | 958 (0x3be) | Exported Function | 0x00000001800253a0 | 0x000253a0
`public: char * __ptr64 __cdecl WString2::GetLPSTR(void)const __ptr64` | 743 (0x2e7) | Exported Function | 0x0000000180042480 | 0x00042480
`public: bool __cdecl SZLess<unsigned short const * __ptr64>::operator()(unsigned short const * __ptr64 const & __ptr64,unsigned short const * __ptr64 const & __ptr64)const __ptr64` | 398 (0x18e) | Exported Function | 0x0000000180044d20 | 0x00044d20
`public: bool __cdecl CTraceSessionControl::IsEnabled(void) __ptr64` | 909 (0x38d) | Exported Function | 0x0000000180025380 | 0x00025380
`public: bool __cdecl CTraceSessionControl::HasToBeEnabled(void) __ptr64` | 878 (0x36e) | Exported Function | 0x0000000180045be0 | 0x00045be0
`public: bool __cdecl CNtSid::IsUser(void) __ptr64` | 935 (0x3a7) | Exported Function | 0x00000001800245e0 | 0x000245e0
`public: bool __cdecl CLike::Match(unsigned short const * __ptr64) __ptr64` | 979 (0x3d3) | Exported Function | 0x0000000180031540 | 0x00031540
`public: bool __cdecl CHaltable::isValid(void) __ptr64` | 1333 (0x535) | Exported Function | 0x0000000180023fe0 | 0x00023fe0
`public: bool __cdecl CFlexQueue::Requeue(void * __ptr64) __ptr64` | 1064 (0x428) | Exported Function | 0x000000018002f250 | 0x0002f250
`public: bool __cdecl CFlexQueue::Enqueue(void * __ptr64) __ptr64` | 618 (0x26a) | Exported Function | 0x000000018000ba90 | 0x0000ba90
`public: char * __ptr64 __cdecl CVar::GetLPSTR(void) __ptr64` | 742 (0x2e6) | Exported Function | 0x0000000180010d00 | 0x00010d00
`public: class CMRCICompression & __ptr64 __cdecl CMRCICompression::operator=(class CMRCICompression const & __ptr64) __ptr64` | 283 (0x11b) | Exported Function | 0x0000000180031a30 | 0x00031a30
`public: class CMRCIControl & __ptr64 __cdecl CMRCIControl::operator=(class CMRCIControl && __ptr64) __ptr64` | 284 (0x11c) | Exported Function | 0x0000000180024b30 | 0x00024b30
`public: class CMRCIControl & __ptr64 __cdecl CMRCIControl::operator=(class CMRCIControl const & __ptr64) __ptr64` | 285 (0x11d) | Exported Function | 0x0000000180024b30 | 0x00024b30
`public: class MD5 & __ptr64 __cdecl MD5::operator=(class MD5 && __ptr64) __ptr64` | 334 (0x14e) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CWStringArray & __ptr64 __cdecl CWStringArray::operator=(class CWStringArray & __ptr64) __ptr64` | 324 (0x144) | Exported Function | 0x0000000180007290 | 0x00007290
`public: class CWQLScanner & __ptr64 __cdecl CWQLScanner::operator=(class CWQLScanner & __ptr64) __ptr64` | 323 (0x143) | Exported Function | 0x0000000180042a50 | 0x00042a50
`public: class CWMITraceSettings & __ptr64 __cdecl CWMITraceSettings::operator=(class CWMITraceSettings const & __ptr64) __ptr64` | 322 (0x142) | Exported Function | 0x0000000180045a50 | 0x00045a50
`public: class CWMITraceSettings & __ptr64 __cdecl CWMITraceSettings::operator=(class CWMITraceSettings && __ptr64) __ptr64` | 321 (0x141) | Exported Function | 0x0000000180045a10 | 0x00045a10
`public: class CWin32DefaultArena & __ptr64 __cdecl CWin32DefaultArena::operator=(class CWin32DefaultArena const & __ptr64) __ptr64` | 333 (0x14d) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CWbemTimeSpan & __ptr64 __cdecl CWbemTimeSpan::operator=(class CWbemTimeSpan const & __ptr64) __ptr64` | 332 (0x14c) | Exported Function | 0x0000000180023d10 | 0x00023d10
`public: class CWbemTimeSpan & __ptr64 __cdecl CWbemTimeSpan::operator=(class CWbemTimeSpan && __ptr64) __ptr64` | 331 (0x14b) | Exported Function | 0x0000000180023d10 | 0x00023d10
`public: class MD5 & __ptr64 __cdecl MD5::operator=(class MD5 const & __ptr64) __ptr64` | 335 (0x14f) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CWbemTime __cdecl CWbemTime::operator-(class CWbemTimeSpan const & __ptr64)const __ptr64` | 379 (0x17b) | Exported Function | 0x0000000180024b60 | 0x00024b60
`public: class CWbemTime __cdecl CWbemTime::operator+(class CWbemInterval const & __ptr64)const __ptr64` | 382 (0x17e) | Exported Function | 0x000000018000fb10 | 0x0000fb10
`public: class CWbemTime __cdecl CEventLogRecord::GetCreationTime(void) __ptr64` | 700 (0x2bc) | Exported Function | 0x000000018002bf20 | 0x0002bf20
`public: class CWbemInterval __cdecl CWbemTime::RemainsUntil(class CWbemTime const & __ptr64)const __ptr64` | 1049 (0x419) | Exported Function | 0x000000018000f8c0 | 0x0000f8c0
`public: class CWbemInterval __cdecl CWbemTime::operator-(class CWbemTime const & __ptr64)const __ptr64` | 380 (0x17c) | Exported Function | 0x0000000180014860 | 0x00014860
`public: class CWbemInterval __cdecl CWbemInterval::operator+(class CWbemInterval)const __ptr64` | 381 (0x17d) | Exported Function | 0x0000000180024b80 | 0x00024b80
`public: class CWbemInterval __cdecl CWbemInterval::operator*(double)const __ptr64` | 378 (0x17a) | Exported Function | 0x0000000180024b40 | 0x00024b40
`public: class CWbemInterval & __ptr64 __cdecl CWbemInterval::operator=(class CWbemInterval const & __ptr64) __ptr64` | 329 (0x149) | Exported Function | 0x0000000180024b30 | 0x00024b30
`public: class CWbemInterval & __ptr64 __cdecl CWbemInterval::operator=(class CWbemInterval && __ptr64) __ptr64` | 328 (0x148) | Exported Function | 0x0000000180024b30 | 0x00024b30
`public: class CWbemTime __cdecl CWbemTime::operator+(class CWbemTimeSpan const & __ptr64)const __ptr64` | 383 (0x17f) | Exported Function | 0x0000000180024ba0 | 0x00024ba0
`public: class CWbemInstallObject & __ptr64 __cdecl CWbemInstallObject::operator=(class CWbemInstallObject const & __ptr64) __ptr64` | 327 (0x147) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class QL1_Parser & __ptr64 __cdecl QL1_Parser::operator=(class QL1_Parser const & __ptr64) __ptr64` | 336 (0x150) | Exported Function | 0x00000001800338c0 | 0x000338c0
`public: class SHA256 & __ptr64 __cdecl SHA256::operator=(class SHA256 && __ptr64) __ptr64` | 341 (0x155) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class WString2 & __ptr64 __cdecl WString2::StripToToken(unsigned short,int) __ptr64` | 1216 (0x4c0) | Exported Function | 0x0000000180042560 | 0x00042560
`public: class WString2 & __ptr64 __cdecl WString2::operator=(unsigned short const * __ptr64) __ptr64` | 344 (0x158) | Exported Function | 0x0000000180002ac0 | 0x00002ac0
`public: class WString2 & __ptr64 __cdecl WString2::operator=(class WString2 const & __ptr64) __ptr64` | 343 (0x157) | Exported Function | 0x00000001800024b0 | 0x000024b0
`public: class WString2 & __ptr64 __cdecl WString2::operator+=(unsigned short) __ptr64` | 404 (0x194) | Exported Function | 0x0000000180003360 | 0x00003360
`public: class WString2 & __ptr64 __cdecl WString2::operator+=(unsigned short const * __ptr64) __ptr64` | 405 (0x195) | Exported Function | 0x0000000180003320 | 0x00003320
`public: class WString2 & __ptr64 __cdecl WString2::operator+=(class WString2 const & __ptr64) __ptr64` | 403 (0x193) | Exported Function | 0x0000000180042110 | 0x00042110
`public: class WString __cdecl WString::operator()(int,int)const __ptr64` | 401 (0x191) | Exported Function | 0x0000000180041000 | 0x00041000
`public: class WString __cdecl WString::EscapeQuotes(void)const __ptr64` | 639 (0x27f) | Exported Function | 0x0000000180041190 | 0x00041190
`public: class Registry & __ptr64 __cdecl Registry::operator=(class Registry const & __ptr64) __ptr64` | 340 (0x154) | Exported Function | 0x0000000180023cb0 | 0x00023cb0
`public: class WString & __ptr64 __cdecl WString::TruncAtRToken(unsigned short) __ptr64` | 1250 (0x4e2) | Exported Function | 0x0000000180041a60 | 0x00041a60
`public: class WString & __ptr64 __cdecl WString::StripWs(int) __ptr64` | 1220 (0x4c4) | Exported Function | 0x0000000180041810 | 0x00041810
`public: class WString & __ptr64 __cdecl WString::StripToToken(unsigned short,int) __ptr64` | 1217 (0x4c1) | Exported Function | 0x0000000180041670 | 0x00041670
`public: class WString & __ptr64 __cdecl WString::operator=(unsigned short const * __ptr64) __ptr64` | 346 (0x15a) | Exported Function | 0x0000000180010310 | 0x00010310
`public: class WString & __ptr64 __cdecl WString::operator=(class WString const & __ptr64) __ptr64` | 345 (0x159) | Exported Function | 0x0000000180006390 | 0x00006390
`public: class WString & __ptr64 __cdecl WString::operator+=(unsigned short) __ptr64` | 407 (0x197) | Exported Function | 0x0000000180041160 | 0x00041160
`public: class WString & __ptr64 __cdecl WString::operator+=(unsigned short const * __ptr64) __ptr64` | 408 (0x198) | Exported Function | 0x0000000180008610 | 0x00008610
`public: class WString & __ptr64 __cdecl WString::operator+=(class WString const & __ptr64) __ptr64` | 406 (0x196) | Exported Function | 0x00000001800135a0 | 0x000135a0
`public: class SHA256 & __ptr64 __cdecl SHA256::operator=(class SHA256 const & __ptr64) __ptr64` | 342 (0x156) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class WString & __ptr64 __cdecl WString::TruncAtLToken(unsigned short) __ptr64` | 1248 (0x4e0) | Exported Function | 0x0000000180041a00 | 0x00041a00
`public: __cdecl WString2::WString2(class WString2 const & __ptr64) __ptr64` | 169 (0xa9) | Exported Function | 0x0000000180041c90 | 0x00041c90
`public: class CWbemCriticalSection & __ptr64 __cdecl CWbemCriticalSection::operator=(class CWbemCriticalSection const & __ptr64) __ptr64` | 326 (0x146) | Exported Function | 0x0000000180023cb0 | 0x00023cb0
`public: class CVarVector & __ptr64 __cdecl CVarVector::operator=(class CVarVector & __ptr64) __ptr64` | 320 (0x140) | Exported Function | 0x0000000180037d10 | 0x00037d10
`public: class CPersistentConfig & __ptr64 __cdecl CPersistentConfig::operator=(class CPersistentConfig const & __ptr64) __ptr64` | 300 (0x12c) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CPersistentConfig & __ptr64 __cdecl CPersistentConfig::operator=(class CPersistentConfig && __ptr64) __ptr64` | 299 (0x12b) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CNtSid * __ptr64 __cdecl CNtSecurityDescriptor::GetOwner(void) __ptr64` | 774 (0x306) | Exported Function | 0x000000018003dd70 | 0x0003dd70
`public: class CNtSid * __ptr64 __cdecl CNtSecurityDescriptor::GetGroup(void) __ptr64` | 731 (0x2db) | Exported Function | 0x000000018003dae0 | 0x0003dae0
`public: class CNtSid * __ptr64 __cdecl CNtAce::GetSid(void) __ptr64` | 818 (0x332) | Exported Function | 0x0000000180008450 | 0x00008450
`public: class CNtSid & __ptr64 __cdecl CNtSid::operator=(class CNtSid const & __ptr64) __ptr64` | 298 (0x12a) | Exported Function | 0x00000001800097b0 | 0x000097b0
`public: class CNtSecurityDescriptor & __ptr64 __cdecl CNtSecurityDescriptor::operator=(class CNtSecurityDescriptor & __ptr64) __ptr64` | 297 (0x129) | Exported Function | 0x000000018000ace0 | 0x0000ace0
`public: class CNtSecurity & __ptr64 __cdecl CNtSecurity::operator=(class CNtSecurity const & __ptr64) __ptr64` | 296 (0x128) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CPublishWMIOperationEvent & __ptr64 __cdecl CPublishWMIOperationEvent::operator=(class CPublishWMIOperationEvent const & __ptr64) __ptr64` | 303 (0x12f) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CNtSecurity & __ptr64 __cdecl CNtSecurity::operator=(class CNtSecurity && __ptr64) __ptr64` | 295 (0x127) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CNtAcl * __ptr64 __cdecl CNtSecurityDescriptor::GetDacl(void) __ptr64` | 708 (0x2c4) | Exported Function | 0x000000018000ae40 | 0x0000ae40
`public: class CNtAcl * __ptr64 __cdecl CNtAcl::OrderAces(void) __ptr64` | 996 (0x3e4) | Exported Function | 0x00000001800405b0 | 0x000405b0
`public: class CNtAcl & __ptr64 __cdecl CNtAcl::operator=(class CNtAcl const & __ptr64) __ptr64` | 294 (0x126) | Exported Function | 0x000000018003af90 | 0x0003af90
`public: class CNtAce * __ptr64 __cdecl CNtAcl::GetAce(int) __ptr64` | 666 (0x29a) | Exported Function | 0x000000018000a240 | 0x0000a240
`public: class CNtAce & __ptr64 __cdecl CNtAce::operator=(class CNtAce const & __ptr64) __ptr64` | 293 (0x125) | Exported Function | 0x000000018003af20 | 0x0003af20
`public: class CMUILocaleList & __ptr64 __cdecl CMUILocaleList::operator=(class CMUILocaleList const & __ptr64) __ptr64` | 288 (0x120) | Exported Function | 0x0000000180023c80 | 0x00023c80
`public: class CMUILocale & __ptr64 __cdecl CMUILocale::operator=(class CMUILocale const & __ptr64) __ptr64` | 287 (0x11f) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CMUILocale & __ptr64 __cdecl CMUILocale::operator=(class CMUILocale && __ptr64) __ptr64` | 286 (0x11e) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CNtAcl * __ptr64 __cdecl CNtSecurityDescriptor::GetSacl(void) __ptr64` | 805 (0x325) | Exported Function | 0x000000018003df00 | 0x0003df00
`public: class CVarVector * __ptr64 __cdecl CVar::GetVarVector(void) __ptr64` | 863 (0x35f) | Exported Function | 0x0000000180010d00 | 0x00010d00
`public: class CQl1ParseSink & __ptr64 __cdecl CQl1ParseSink::operator=(class CQl1ParseSink && __ptr64) __ptr64` | 304 (0x130) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CRegistryMinMaxLimitControl & __ptr64 __cdecl CRegistryMinMaxLimitControl::operator=(class CRegistryMinMaxLimitControl && __ptr64) __ptr64` | 306 (0x132) | Exported Function | 0x0000000180043f80 | 0x00043f80
`public: class CVar & __ptr64 __cdecl CVarVector::operator[](int) __ptr64` | 355 (0x163) | Exported Function | 0x0000000180037fc0 | 0x00037fc0
`public: class CVar & __ptr64 __cdecl CVarVector::GetAt(int) __ptr64` | 681 (0x2a9) | Exported Function | 0x0000000180008310 | 0x00008310
`public: class CVar & __ptr64 __cdecl CVar::operator=(class CVar const & __ptr64) __ptr64` | 319 (0x13f) | Exported Function | 0x0000000180006bb0 | 0x00006bb0
`public: class CUnkInternal & __ptr64 __cdecl CUnkInternal::operator=(class CUnkInternal const & __ptr64) __ptr64` | 318 (0x13e) | Exported Function | 0x000000018002b9c0 | 0x0002b9c0
`public: class CUnk & __ptr64 __cdecl CUnk::operator=(class CUnk const & __ptr64) __ptr64` | 317 (0x13d) | Exported Function | 0x000000018002b990 | 0x0002b990
`public: class CTraceSessionControl & __ptr64 __cdecl CTraceSessionControl::operator=(class CTraceSessionControl const & __ptr64) __ptr64` | 316 (0x13c) | Exported Function | 0x00000001800459e0 | 0x000459e0
`public: class CTraceSessionControl & __ptr64 __cdecl CTraceSessionControl::operator=(class CTraceSessionControl && __ptr64) __ptr64` | 315 (0x13b) | Exported Function | 0x00000001800459b0 | 0x000459b0
`public: class CTimerInstruction & __ptr64 __cdecl CTimerInstruction::operator=(class CTimerInstruction const & __ptr64) __ptr64` | 314 (0x13a) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CQl1ParseSink & __ptr64 __cdecl CQl1ParseSink::operator=(class CQl1ParseSink const & __ptr64) __ptr64` | 305 (0x131) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: class CTimerGenerator & __ptr64 __cdecl CTimerGenerator::operator=(class CTimerGenerator const & __ptr64) __ptr64` | 313 (0x139) | Exported Function | 0x0000000180036290 | 0x00036290
`public: class CStaticCritSec & __ptr64 __cdecl CStaticCritSec::operator=(class CStaticCritSec const & __ptr64) __ptr64` | 311 (0x137) | Exported Function | 0x000000018002e880 | 0x0002e880
`public: class CSmallArrayBlob * __ptr64 __cdecl CSmallArrayBlob::SetAt(int,void * __ptr64,void * __ptr64 * __ptr64) __ptr64` | 1095 (0x447) | Exported Function | 0x0000000180035a50 | 0x00035a50
`public: class CSmallArrayBlob * __ptr64 __cdecl CSmallArrayBlob::RemoveAt(int,void * __ptr64 * __ptr64) __ptr64` | 1055 (0x41f) | Exported Function | 0x0000000180035a00 | 0x00035a00
`public: class CSmallArrayBlob * __ptr64 __cdecl CSmallArrayBlob::InsertAt(int,void * __ptr64) __ptr64` | 895 (0x37f) | Exported Function | 0x0000000180013f20 | 0x00013f20
`public: class CSmallArrayBlob & __ptr64 __cdecl CSmallArrayBlob::operator=(class CSmallArrayBlob const & __ptr64) __ptr64` | 310 (0x136) | Exported Function | 0x0000000180023c60 | 0x00023c60
`public: class CSmallArrayBlob & __ptr64 __cdecl CSmallArrayBlob::operator=(class CSmallArrayBlob && __ptr64) __ptr64` | 309 (0x135) | Exported Function | 0x0000000180023d30 | 0x00023d30
`public: class CSafeArray & __ptr64 __cdecl CSafeArray::operator=(class CSafeArray & __ptr64) __ptr64` | 308 (0x134) | Exported Function | 0x00000001800352b0 | 0x000352b0
`public: class CRegistryMinMaxLimitControl & __ptr64 __cdecl CRegistryMinMaxLimitControl::operator=(class CRegistryMinMaxLimitControl const & __ptr64) __ptr64` | 307 (0x133) | Exported Function | 0x0000000180043f80 | 0x00043f80
`public: class CTextTemplate & __ptr64 __cdecl CTextTemplate::operator=(class CTextTemplate const & __ptr64) __ptr64` | 312 (0x138) | Exported Function | 0x0000000180036860 | 0x00036860
`public: class WString2 & __ptr64 __cdecl WString2::TruncAtLToken(unsigned short) __ptr64` | 1247 (0x4df) | Exported Function | 0x0000000180042710 | 0x00042710
`public: __cdecl WString2::WString2(char const * __ptr64) __ptr64` | 172 (0xac) | Exported Function | 0x0000000180041e40 | 0x00041e40
`public: __cdecl WString2::operator unsigned short * __ptr64(void) __ptr64` | 374 (0x176) | Exported Function | 0x00000001800117b0 | 0x000117b0
`public: __cdecl CNtSecurityDescriptor::CNtSecurityDescriptor(void * __ptr64) __ptr64` | 87 (0x57) | Exported Function | 0x000000018000ab70 | 0x0000ab70
`public: __cdecl CNtSecurityDescriptor::CNtSecurityDescriptor(class CNtSecurityDescriptor & __ptr64) __ptr64` | 86 (0x56) | Exported Function | 0x000000018003aa80 | 0x0003aa80
`public: __cdecl CNtAcl::~CNtAcl(void) __ptr64` | 214 (0xd6) | Exported Function | 0x0000000180005860 | 0x00005860
`public: __cdecl CNtAcl::CNtAcl(unsigned long) __ptr64` | 84 (0x54) | Exported Function | 0x000000018003aa00 | 0x0003aa00
`public: __cdecl CNtAcl::CNtAcl(struct _ACL * __ptr64) __ptr64` | 85 (0x55) | Exported Function | 0x000000018000ad70 | 0x0000ad70
`public: __cdecl CNtAcl::CNtAcl(class CNtAcl const & __ptr64) __ptr64` | 83 (0x53) | Exported Function | 0x000000018003a980 | 0x0003a980
`public: __cdecl CNtAce::CNtAce(void) __ptr64` | 82 (0x52) | Exported Function | 0x0000000180024130 | 0x00024130
`public: __cdecl CNtAce::CNtAce(unsigned long,unsigned long,unsigned long,unsigned short * __ptr64) __ptr64` | 80 (0x50) | Exported Function | 0x000000018003a840 | 0x0003a840
`public: __cdecl CNtAce::CNtAce(unsigned long,unsigned long,unsigned long,class CNtSid & __ptr64) __ptr64` | 79 (0x4f) | Exported Function | 0x0000000180003770 | 0x00003770
`public: __cdecl CNtAce::CNtAce(struct _ACCESS_ALLOWED_ACE * __ptr64) __ptr64` | 81 (0x51) | Exported Function | 0x0000000180004c90 | 0x00004c90
`public: __cdecl CNtAce::CNtAce(class CNtAce const & __ptr64) __ptr64` | 78 (0x4e) | Exported Function | 0x000000018003a7a0 | 0x0003a7a0
`public: __cdecl CMUILocaleList::~CMUILocaleList(void) __ptr64` | 211 (0xd3) | Exported Function | 0x000000018000ab30 | 0x0000ab30
`public: __cdecl CMUILocaleList::CMUILocaleList(void) __ptr64` | 73 (0x49) | Exported Function | 0x0000000180012e90 | 0x00012e90
`public: __cdecl CMRCIControl::CMRCIControl(void) __ptr64` | 72 (0x48) | Exported Function | 0x0000000180024a90 | 0x00024a90
`public: __cdecl CMRCICompression::~CMRCICompression(void) __ptr64` | 210 (0xd2) | Exported Function | 0x000000018000a140 | 0x0000a140
`public: __cdecl CMRCICompression::CMRCICompression(void) __ptr64` | 71 (0x47) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: __cdecl CMinMaxLimitControl::CMinMaxLimitControl(int,unsigned short const * __ptr64) __ptr64` | 77 (0x4d) | Exported Function | 0x0000000180043b10 | 0x00043b10
`public: __cdecl CNtSecurityDescriptor::CNtSecurityDescriptor(void) __ptr64` | 88 (0x58) | Exported Function | 0x000000018000a300 | 0x0000a300
`public: __cdecl CNtSecurityDescriptor::~CNtSecurityDescriptor(void) __ptr64` | 215 (0xd7) | Exported Function | 0x0000000180005860 | 0x00005860
`public: __cdecl CNtSid::CNtSid(class CNtSid const & __ptr64) __ptr64` | 89 (0x59) | Exported Function | 0x0000000180009820 | 0x00009820
`public: __cdecl CNtSid::CNtSid(enum CNtSid::SidType) __ptr64` | 92 (0x5c) | Exported Function | 0x000000018003ac20 | 0x0003ac20
`public: __cdecl CSafeArray::~CSafeArray(void) __ptr64` | 220 (0xdc) | Exported Function | 0x0000000180012ee0 | 0x00012ee0
`public: __cdecl CSafeArray::CSafeArray(struct tagSAFEARRAY * __ptr64,int,int,int) __ptr64` | 104 (0x68) | Exported Function | 0x000000018000c5a0 | 0x0000c5a0
`public: __cdecl CSafeArray::CSafeArray(int,int,int,int) __ptr64` | 103 (0x67) | Exported Function | 0x000000018000a0c0 | 0x0000a0c0
`public: __cdecl CSafeArray::CSafeArray(class CSafeArray & __ptr64) __ptr64` | 102 (0x66) | Exported Function | 0x0000000180035240 | 0x00035240
`public: __cdecl CRegistryMinMaxLimitControl::CRegistryMinMaxLimitControl(int,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 101 (0x65) | Exported Function | 0x0000000180043ca0 | 0x00043ca0
`public: __cdecl CRegistryMinMaxLimitControl::CRegistryMinMaxLimitControl(class CRegistryMinMaxLimitControl const & __ptr64) __ptr64` | 100 (0x64) | Exported Function | 0x0000000180043bc0 | 0x00043bc0
`public: __cdecl CRegistryMinMaxLimitControl::CRegistryMinMaxLimitControl(class CRegistryMinMaxLimitControl && __ptr64) __ptr64` | 99 (0x63) | Exported Function | 0x0000000180043bc0 | 0x00043bc0
`public: __cdecl CQl1ParseSink::CQl1ParseSink(void) __ptr64` | 98 (0x62) | Exported Function | 0x0000000180033340 | 0x00033340
`public: __cdecl CMinMaxLimitControl::CMinMaxLimitControl(class CMinMaxLimitControl const & __ptr64) __ptr64` | 76 (0x4c) | Exported Function | 0x0000000180043a40 | 0x00043a40
`public: __cdecl CQl1ParseSink::CQl1ParseSink(class CQl1ParseSink const & __ptr64) __ptr64` | 97 (0x61) | Exported Function | 0x0000000180033340 | 0x00033340
`public: __cdecl CPublishWMIOperationEvent::~CPublishWMIOperationEvent(void) __ptr64` | 218 (0xda) | Exported Function | 0x0000000180047db0 | 0x00047db0
`public: __cdecl CPropertyName::~CPropertyName(void) __ptr64` | 217 (0xd9) | Exported Function | 0x00000001800062a0 | 0x000062a0
`public: __cdecl CPropertyName::CPropertyName(void) __ptr64` | 95 (0x5f) | Exported Function | 0x0000000180011760 | 0x00011760
`public: __cdecl CPropertyName::CPropertyName(class CPropertyName const & __ptr64) __ptr64` | 94 (0x5e) | Exported Function | 0x0000000180010a40 | 0x00010a40
`public: __cdecl CNtSid::~CNtSid(void) __ptr64` | 216 (0xd8) | Exported Function | 0x00000001800118c0 | 0x000118c0
`public: __cdecl CNtSid::CNtSid(void) __ptr64` | 93 (0x5d) | Exported Function | 0x0000000180012d40 | 0x00012d40
`public: __cdecl CNtSid::CNtSid(void * __ptr64) __ptr64` | 91 (0x5b) | Exported Function | 0x00000001800094a0 | 0x000094a0
`public: __cdecl CNtSid::CNtSid(unsigned short * __ptr64) __ptr64` | 90 (0x5a) | Exported Function | 0x000000018003aab0 | 0x0003aab0
`public: __cdecl CQl1ParseSink::CQl1ParseSink(class CQl1ParseSink && __ptr64) __ptr64` | 96 (0x60) | Exported Function | 0x0000000180033340 | 0x00033340
`public: __cdecl CMinMaxLimitControl::CMinMaxLimitControl(class CMinMaxLimitControl && __ptr64) __ptr64` | 75 (0x4b) | Exported Function | 0x0000000180043a40 | 0x00043a40
`public: __cdecl CMemoryLog::CMemoryLog(void) __ptr64` | 74 (0x4a) | Exported Function | 0x0000000180045820 | 0x00045820
`public: __cdecl CLockableFlexArray<class CStaticCritSec>::~CLockableFlexArray<class CStaticCritSec>(void) __ptr64` | 182 (0xb6) | Exported Function | 0x000000018002e690 | 0x0002e690
`public: __cdecl CInsertionString::CInsertionString(class CInsertionString && __ptr64) __ptr64` | 52 (0x34) | Exported Function | 0x000000018002afb0 | 0x0002afb0
`public: __cdecl CInsertionString::CInsertionString(class CHex) __ptr64` | 57 (0x39) | Exported Function | 0x000000018002b1a0 | 0x0002b1a0
`public: __cdecl CInsertionString::CInsertionString(char const * __ptr64) __ptr64` | 55 (0x37) | Exported Function | 0x000000018002b100 | 0x0002b100
`public: __cdecl CInCritSec::~CInCritSec(void) __ptr64` | 205 (0xcd) | Exported Function | 0x00000001800102e0 | 0x000102e0
`public: __cdecl CInCritSec::CInCritSec(struct _RTL_CRITICAL_SECTION * __ptr64) __ptr64` | 51 (0x33) | Exported Function | 0x000000018000e430 | 0x0000e430
`public: __cdecl CIdentityTest::~CIdentityTest(void) __ptr64` | 204 (0xcc) | Exported Function | 0x000000018000f510 | 0x0000f510
`public: __cdecl CIdentityTest::CIdentityTest(class CTimerInstruction * __ptr64) __ptr64` | 50 (0x32) | Exported Function | 0x000000018000f570 | 0x0000f570
`public: __cdecl CIdentityTest::CIdentityTest(class CIdentityTest const & __ptr64) __ptr64` | 49 (0x31) | Exported Function | 0x0000000180035e60 | 0x00035e60
`public: __cdecl CInsertionString::CInsertionString(class CInsertionString const & __ptr64) __ptr64` | 53 (0x35) | Exported Function | 0x000000018002afb0 | 0x0002afb0
`public: __cdecl CIdentitySecurity::~CIdentitySecurity(void) __ptr64` | 203 (0xcb) | Exported Function | 0x0000000180008930 | 0x00008930
`public: __cdecl CIdentitySecurity::CIdentitySecurity(bool) __ptr64` | 48 (0x30) | Exported Function | 0x00000001800060c0 | 0x000060c0
`public: __cdecl CHex::operator long(void) __ptr64` | 359 (0x167) | Exported Function | 0x0000000180010290 | 0x00010290
`public: __cdecl CHex::CHex(long) __ptr64` | 46 (0x2e) | Exported Function | 0x0000000180024a80 | 0x00024a80
`public: __cdecl CHaltable::CHaltable(void) __ptr64` | 45 (0x2d) | Exported Function | 0x0000000180035ba0 | 0x00035ba0
`public: __cdecl CHaltable::CHaltable(class CHaltable const & __ptr64) __ptr64` | 44 (0x2c) | Exported Function | 0x0000000180023bc0 | 0x00023bc0
`public: __cdecl CFlexQueue::~CFlexQueue(void) __ptr64` | 201 (0xc9) | Exported Function | 0x000000018000b240 | 0x0000b240
`public: __cdecl CFlexQueue::CFlexQueue(int) __ptr64` | 43 (0x2b) | Exported Function | 0x000000018000bc00 | 0x0000bc00
`public: __cdecl CFlexArray::~CFlexArray(void) __ptr64` | 200 (0xc8) | Exported Function | 0x0000000180010d60 | 0x00010d60
`public: __cdecl CIdentitySecurity::CIdentitySecurity(class CIdentitySecurity const & __ptr64) __ptr64` | 47 (0x2f) | Exported Function | 0x00000001800240c0 | 0x000240c0
`public: __cdecl CStaticCritSec::CStaticCritSec(void) __ptr64` | 105 (0x69) | Exported Function | 0x0000000180012c90 | 0x00012c90
`public: __cdecl CInsertionString::CInsertionString(long) __ptr64` | 54 (0x36) | Exported Function | 0x000000018002b000 | 0x0002b000
`public: __cdecl CInsertionString::CInsertionString(void) __ptr64` | 58 (0x3a) | Exported Function | 0x000000018002b2a0 | 0x0002b2a0
`public: __cdecl CLockableFlexArray<class CStaticCritSec>::CLockableFlexArray<class CStaticCritSec>(void) __ptr64` | 3 (0x3) | Exported Function | 0x000000018002e5a0 | 0x0002e5a0
`public: __cdecl CLockableFlexArray<class CStaticCritSec>::CLockableFlexArray<class CStaticCritSec>(class CLockableFlexArray<class CStaticCritSec> && __ptr64) __ptr64` | 1 (0x1) | Exported Function | 0x000000018002e530 | 0x0002e530
`public: __cdecl CLockableFlexArray<class CStaticCritSec>::CLockableFlexArray<class CStaticCritSec>(class CLockableFlexArray<class CStaticCritSec> & __ptr64) __ptr64` | 2 (0x2) | Exported Function | 0x000000018002e530 | 0x0002e530
`public: __cdecl CLimitControl::CLimitControl(void) __ptr64` | 70 (0x46) | Exported Function | 0x0000000180043a20 | 0x00043a20
`public: __cdecl CLimitControl::CLimitControl(class CLimitControl const & __ptr64) __ptr64` | 69 (0x45) | Exported Function | 0x0000000180043a00 | 0x00043a00
`public: __cdecl CLike::~CLike(void) __ptr64` | 208 (0xd0) | Exported Function | 0x00000001800310d0 | 0x000310d0
`public: __cdecl CLike::CLike(void) __ptr64` | 68 (0x44) | Exported Function | 0x00000001800310b0 | 0x000310b0
`public: __cdecl CLike::CLike(unsigned short const * __ptr64,unsigned short) __ptr64` | 67 (0x43) | Exported Function | 0x0000000180031080 | 0x00031080
`public: __cdecl CInsertionString::CInsertionString(unsigned short const * __ptr64) __ptr64` | 56 (0x38) | Exported Function | 0x000000018002b150 | 0x0002b150
`public: __cdecl CLike::CLike(class CLike const & __ptr64) __ptr64` | 66 (0x42) | Exported Function | 0x0000000180031050 | 0x00031050
`public: __cdecl CLifeControl::CLifeControl(class CLifeControl const & __ptr64) __ptr64` | 64 (0x40) | Exported Function | 0x0000000180013500 | 0x00013500
`public: __cdecl CLifeControl::CLifeControl(class CLifeControl && __ptr64) __ptr64` | 63 (0x3f) | Exported Function | 0x0000000180013500 | 0x00013500
`public: __cdecl CInstructionTest::CInstructionTest(void) __ptr64` | 62 (0x3e) | Exported Function | 0x0000000180035f50 | 0x00035f50
`public: __cdecl CInstructionTest::CInstructionTest(class CInstructionTest const & __ptr64) __ptr64` | 61 (0x3d) | Exported Function | 0x0000000180035f50 | 0x00035f50
`public: __cdecl CInstructionTest::CInstructionTest(class CInstructionTest && __ptr64) __ptr64` | 60 (0x3c) | Exported Function | 0x0000000180035f50 | 0x00035f50
`public: __cdecl CInstructionQueue::~CInstructionQueue(void) __ptr64` | 207 (0xcf) | Exported Function | 0x0000000180036110 | 0x00036110
`public: __cdecl CInstructionQueue::CInstructionQueue(void) __ptr64` | 59 (0x3b) | Exported Function | 0x0000000180035e80 | 0x00035e80
`public: __cdecl CInsertionString::~CInsertionString(void) __ptr64` | 206 (0xce) | Exported Function | 0x000000018002b8d0 | 0x0002b8d0
`public: __cdecl CLifeControl::CLifeControl(void) __ptr64` | 65 (0x41) | Exported Function | 0x0000000180013500 | 0x00013500
`public: __cdecl CStaticCritSec::~CStaticCritSec(void) __ptr64` | 221 (0xdd) | Exported Function | 0x0000000180012f20 | 0x00012f20
`public: __cdecl CTextTemplate::CTextTemplate(class CTextTemplate const & __ptr64) __ptr64` | 106 (0x6a) | Exported Function | 0x0000000180036720 | 0x00036720
`public: __cdecl CTextTemplate::CTextTemplate(unsigned short const * __ptr64) __ptr64` | 107 (0x6b) | Exported Function | 0x0000000180036760 | 0x00036760
`public: __cdecl CWin32DefaultArena::~CWin32DefaultArena(void) __ptr64` | 234 (0xea) | Exported Function | 0x0000000180022ed0 | 0x00022ed0
`public: __cdecl CWin32DefaultArena::CWin32DefaultArena(void) __ptr64` | 158 (0x9e) | Exported Function | 0x0000000180022eb0 | 0x00022eb0
`public: __cdecl CWin32DefaultArena::CWin32DefaultArena(class CWin32DefaultArena const & __ptr64) __ptr64` | 157 (0x9d) | Exported Function | 0x0000000180022eb0 | 0x00022eb0
`public: __cdecl CWbemTimeSpan::CWbemTimeSpan(int,int,int,int,int,int,int) __ptr64` | 156 (0x9c) | Exported Function | 0x0000000180024ab0 | 0x00024ab0
`public: __cdecl CWbemTime::CWbemTime(void) __ptr64` | 155 (0x9b) | Exported Function | 0x0000000180001490 | 0x00001490
`public: __cdecl CWbemTime::CWbemTime(class CWbemTime const & __ptr64) __ptr64` | 154 (0x9a) | Exported Function | 0x0000000180023d10 | 0x00023d10
`public: __cdecl CWbemInterval::CWbemInterval(void) __ptr64` | 152 (0x98) | Exported Function | 0x0000000180024a90 | 0x00024a90
`public: __cdecl CWbemInstallObject::~CWbemInstallObject(void) __ptr64` | 233 (0xe9) | Exported Function | 0x000000018000a140 | 0x0000a140
`public: __cdecl CWMITraceSettings::CWMITraceSettings(void) __ptr64` | 142 (0x8e) | Exported Function | 0x0000000180045950 | 0x00045950
`public: __cdecl CWbemInstallObject::CWbemInstallObject(void) __ptr64` | 150 (0x96) | Exported Function | 0x0000000180012b30 | 0x00012b30
`public: __cdecl CWbemCriticalSection::CWbemCriticalSection(void) __ptr64` | 149 (0x95) | Exported Function | 0x0000000180012f50 | 0x00012f50
`public: __cdecl CVarVector::~CVarVector(void) __ptr64` | 228 (0xe4) | Exported Function | 0x00000001800012d0 | 0x000012d0
`public: __cdecl CVarVector::CVarVector(void) __ptr64` | 141 (0x8d) | Exported Function | 0x0000000180011f30 | 0x00011f30
`public: __cdecl CVarVector::CVarVector(int,struct tagSAFEARRAY * __ptr64,int) __ptr64` | 140 (0x8c) | Exported Function | 0x000000018000c670 | 0x0000c670
`public: __cdecl CVarVector::CVarVector(int,int,int) __ptr64` | 139 (0x8b) | Exported Function | 0x000000018000b890 | 0x0000b890
`public: __cdecl CVarVector::CVarVector(class CVarVector & __ptr64) __ptr64` | 138 (0x8a) | Exported Function | 0x0000000180037c50 | 0x00037c50
`public: __cdecl CVar::~CVar(void) __ptr64` | 227 (0xe3) | Exported Function | 0x000000018000c470 | 0x0000c470
`public: __cdecl CVar::operator unsigned short(void) __ptr64` | 364 (0x16c) | Exported Function | 0x0000000180012d30 | 0x00012d30
`public: __cdecl CWbemCriticalSection::~CWbemCriticalSection(void) __ptr64` | 232 (0xe8) | Exported Function | 0x0000000180035ce0 | 0x00035ce0
`public: __cdecl CVar::operator unsigned short * __ptr64(void) __ptr64` | 370 (0x172) | Exported Function | 0x0000000180010d00 | 0x00010d00
`public: __cdecl CWQLScanner::CWQLScanner(class CGenLexSource * __ptr64) __ptr64` | 144 (0x90) | Exported Function | 0x000000018000c1b0 | 0x0000c1b0
`public: __cdecl CWQLScanner::~CWQLScanner(void) __ptr64` | 229 (0xe5) | Exported Function | 0x000000018000b270 | 0x0000b270
`public: __cdecl SZLess<unsigned short const * __ptr64>::SZLess<unsigned short const * __ptr64>(void) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180034c70 | 0x00034c70
`public: __cdecl SZLess<unsigned short const * __ptr64>::SZLess<unsigned short const * __ptr64>(struct SZLess<unsigned short const * __ptr64> const & __ptr64) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180034c70 | 0x00034c70
`public: __cdecl Registry::~Registry(void) __ptr64` | 238 (0xee) | Exported Function | 0x000000018000d800 | 0x0000d800
`public: __cdecl Registry::Registry(void) __ptr64` | 168 (0xa8) | Exported Function | 0x0000000180034d50 | 0x00034d50
`public: __cdecl Registry::Registry(unsigned short const * __ptr64,unsigned long) __ptr64` | 167 (0xa7) | Exported Function | 0x000000018000df30 | 0x0000df30
`public: __cdecl Registry::Registry(struct HKEY__ * __ptr64,unsigned long,unsigned short const * __ptr64) __ptr64` | 166 (0xa6) | Exported Function | 0x000000018000d5f0 | 0x0000d5f0
`public: __cdecl Registry::Registry(struct HKEY__ * __ptr64,unsigned long,unsigned long,unsigned short const * __ptr64) __ptr64` | 165 (0xa5) | Exported Function | 0x0000000180034c90 | 0x00034c90
`public: __cdecl QL_LEVEL_1_TOKEN::~QL_LEVEL_1_TOKEN(void) __ptr64` | 237 (0xed) | Exported Function | 0x0000000180006ae0 | 0x00006ae0
`public: __cdecl CWQLScanner::CWQLScanner(class CWQLScanner & __ptr64) __ptr64` | 143 (0x8f) | Exported Function | 0x00000001800428a0 | 0x000428a0
`public: __cdecl QL_LEVEL_1_TOKEN::QL_LEVEL_1_TOKEN(void) __ptr64` | 164 (0xa4) | Exported Function | 0x0000000180011390 | 0x00011390
`public: __cdecl QL_LEVEL_1_RPN_EXPRESSION::~QL_LEVEL_1_RPN_EXPRESSION(void) __ptr64` | 236 (0xec) | Exported Function | 0x0000000180009a20 | 0x00009a20
`public: __cdecl QL_LEVEL_1_RPN_EXPRESSION::QL_LEVEL_1_RPN_EXPRESSION(void) __ptr64` | 162 (0xa2) | Exported Function | 0x0000000180009b90 | 0x00009b90
`public: __cdecl QL_LEVEL_1_RPN_EXPRESSION::QL_LEVEL_1_RPN_EXPRESSION(struct QL_LEVEL_1_RPN_EXPRESSION const & __ptr64) __ptr64` | 161 (0xa1) | Exported Function | 0x00000001800333d0 | 0x000333d0
`public: __cdecl QL1_Parser::QL1_Parser(class QL1_Parser const & __ptr64) __ptr64` | 159 (0x9f) | Exported Function | 0x0000000180033360 | 0x00033360
`public: __cdecl QL1_Parser::QL1_Parser(class CGenLexSource * __ptr64) __ptr64` | 160 (0xa0) | Exported Function | 0x0000000180005c10 | 0x00005c10
`public: __cdecl CWStringArray::~CWStringArray(void) __ptr64` | 230 (0xe6) | Exported Function | 0x00000001800024e0 | 0x000024e0
`public: __cdecl CWStringArray::CWStringArray(int,int) __ptr64` | 146 (0x92) | Exported Function | 0x00000001800116c0 | 0x000116c0
`public: __cdecl CWStringArray::CWStringArray(class CWStringArray & __ptr64) __ptr64` | 145 (0x91) | Exported Function | 0x000000018002e630 | 0x0002e630
`public: __cdecl QL_LEVEL_1_TOKEN::QL_LEVEL_1_TOKEN(struct QL_LEVEL_1_TOKEN const & __ptr64) __ptr64` | 163 (0xa3) | Exported Function | 0x0000000180010640 | 0x00010640
`public: __cdecl WString2::operator unsigned short const * __ptr64(void)const __ptr64` | 375 (0x177) | Exported Function | 0x00000001800117b0 | 0x000117b0
`public: __cdecl CVar::operator unsigned long(void) __ptr64` | 366 (0x16e) | Exported Function | 0x0000000180011410 | 0x00011410
`public: __cdecl CVar::operator struct tagBLOB * __ptr64(void) __ptr64` | 372 (0x174) | Exported Function | 0x0000000180013340 | 0x00013340
`public: __cdecl CVar::CVar(int,struct tagSAFEARRAY * __ptr64) __ptr64` | 124 (0x7c) | Exported Function | 0x000000018002b410 | 0x0002b410
`public: __cdecl CVar::CVar(int,class auto_bstr) __ptr64` | 125 (0x7d) | Exported Function | 0x000000018002b450 | 0x0002b450
`public: __cdecl CVar::CVar(float) __ptr64` | 128 (0x80) | Exported Function | 0x000000018002b540 | 0x0002b540
`public: __cdecl CVar::CVar(double) __ptr64` | 129 (0x81) | Exported Function | 0x000000018002b570 | 0x0002b570
`public: __cdecl CVar::CVar(class CVarVector * __ptr64,int) __ptr64` | 136 (0x88) | Exported Function | 0x000000018002b710 | 0x0002b710
`public: __cdecl CVar::CVar(class CVar const & __ptr64) __ptr64` | 117 (0x75) | Exported Function | 0x0000000180007180 | 0x00007180
`public: __cdecl CVar::CVar(char) __ptr64` | 118 (0x76) | Exported Function | 0x000000018002b350 | 0x0002b350
`public: __cdecl CVar::CVar(char * __ptr64,int) __ptr64` | 130 (0x82) | Exported Function | 0x000000018002b5a0 | 0x0002b5a0
`public: __cdecl CVar::CVar(int,unsigned short * __ptr64) __ptr64` | 123 (0x7b) | Exported Function | 0x0000000180012020 | 0x00012020
`public: __cdecl CUnkInternal::CUnkInternal(class CUnkInternal const & __ptr64) __ptr64` | 115 (0x73) | Exported Function | 0x000000018002b320 | 0x0002b320
`public: __cdecl CUnk::CUnk(class CUnk const & __ptr64) __ptr64` | 113 (0x71) | Exported Function | 0x000000018002b2f0 | 0x0002b2f0
`public: __cdecl CUnk::CUnk(class CLifeControl * __ptr64,struct IUnknown * __ptr64) __ptr64` | 114 (0x72) | Exported Function | 0x0000000180011c00 | 0x00011c00
`public: __cdecl CTraceSessionControl::CTraceSessionControl(void) __ptr64` | 112 (0x70) | Exported Function | 0x0000000180045930 | 0x00045930
`public: __cdecl CTimerInstruction::CTimerInstruction(void) __ptr64` | 111 (0x6f) | Exported Function | 0x00000001800360f0 | 0x000360f0
`public: __cdecl CTimerInstruction::CTimerInstruction(class CTimerInstruction const & __ptr64) __ptr64` | 110 (0x6e) | Exported Function | 0x00000001800360f0 | 0x000360f0
`public: __cdecl CTimerGenerator::CTimerGenerator(void) __ptr64` | 109 (0x6d) | Exported Function | 0x0000000180036070 | 0x00036070
`public: __cdecl CTimerGenerator::CTimerGenerator(class CTimerGenerator const & __ptr64) __ptr64` | 108 (0x6c) | Exported Function | 0x0000000180035f70 | 0x00035f70
`public: __cdecl CTextTemplate::~CTextTemplate(void) __ptr64` | 222 (0xde) | Exported Function | 0x00000001800367d0 | 0x000367d0
`public: __cdecl CUnkInternal::CUnkInternal(class CLifeControl * __ptr64) __ptr64` | 116 (0x74) | Exported Function | 0x0000000180012730 | 0x00012730
`public: __cdecl CVar::operator unsigned char(void) __ptr64` | 362 (0x16a) | Exported Function | 0x000000018002baa0 | 0x0002baa0
`public: __cdecl CVar::CVar(long) __ptr64` | 126 (0x7e) | Exported Function | 0x000000018002b4e0 | 0x0002b4e0
`public: __cdecl CVar::CVar(short,int) __ptr64` | 121 (0x79) | Exported Function | 0x0000000180011ff0 | 0x00011ff0
`public: __cdecl CVar::operator struct _GUID * __ptr64(void) __ptr64` | 371 (0x173) | Exported Function | 0x0000000180010d00 | 0x00010d00
`public: __cdecl CVar::operator struct _FILETIME(void) __ptr64` | 360 (0x168) | Exported Function | 0x000000018002ba80 | 0x0002ba80
`public: __cdecl CVar::operator short(void) __ptr64` | 363 (0x16b) | Exported Function | 0x0000000180012d30 | 0x00012d30
`public: __cdecl CVar::operator long(void) __ptr64` | 365 (0x16d) | Exported Function | 0x0000000180011410 | 0x00011410
`public: __cdecl CVar::operator float(void) __ptr64` | 367 (0x16f) | Exported Function | 0x000000018002bab0 | 0x0002bab0
`public: __cdecl CVar::operator double(void) __ptr64` | 368 (0x170) | Exported Function | 0x000000018002bac0 | 0x0002bac0
`public: __cdecl CVar::operator class CVarVector * __ptr64(void) __ptr64` | 373 (0x175) | Exported Function | 0x0000000180010d00 | 0x00010d00
`public: __cdecl CVar::operator char(void) __ptr64` | 361 (0x169) | Exported Function | 0x000000018002baa0 | 0x0002baa0
`public: __cdecl CVar::CVar(short) __ptr64` | 120 (0x78) | Exported Function | 0x000000018002b3b0 | 0x0002b3b0
`public: __cdecl CVar::operator char * __ptr64(void) __ptr64` | 369 (0x171) | Exported Function | 0x0000000180010d00 | 0x00010d00
`public: __cdecl CVar::CVar(unsigned short) __ptr64` | 122 (0x7a) | Exported Function | 0x000000018002b3e0 | 0x0002b3e0
`public: __cdecl CVar::CVar(unsigned short * __ptr64,int) __ptr64` | 131 (0x83) | Exported Function | 0x000000018002b5e0 | 0x0002b5e0
`public: __cdecl CVar::CVar(unsigned long) __ptr64` | 127 (0x7f) | Exported Function | 0x000000018002b510 | 0x0002b510
`public: __cdecl CVar::CVar(unsigned char) __ptr64` | 119 (0x77) | Exported Function | 0x000000018002b380 | 0x0002b380
`public: __cdecl CVar::CVar(struct tagVARIANT * __ptr64) __ptr64` | 135 (0x87) | Exported Function | 0x000000018002b6d0 | 0x0002b6d0
`public: __cdecl CVar::CVar(struct tagBLOB * __ptr64,int) __ptr64` | 134 (0x86) | Exported Function | 0x000000018002b690 | 0x0002b690
`public: __cdecl CVar::CVar(struct _GUID * __ptr64,int) __ptr64` | 133 (0x85) | Exported Function | 0x000000018002b650 | 0x0002b650
`public: __cdecl CVar::CVar(struct _FILETIME * __ptr64) __ptr64` | 132 (0x84) | Exported Function | 0x000000018002b620 | 0x0002b620
`public: __cdecl CVar::CVar(void) __ptr64` | 137 (0x89) | Exported Function | 0x0000000180010270 | 0x00010270
`WMIControlClientOpsCallback` | 1275 (0x4fb) | Exported Function | 0x00000001800465d0 | 0x000465d0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wbemcomn.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/a4227272ed26c1cfedc51785204f7a32f5af3579556c5d9423db1fbd82938a63/detection/


## Possible Misuse

*The following table contains possible examples of `wbemcomn.dll` being misused. While `wbemcomn.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_winword_wmidll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_winword_wmidll_load.yml) | `- '*\wbemcomn.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\wbemcomn.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


