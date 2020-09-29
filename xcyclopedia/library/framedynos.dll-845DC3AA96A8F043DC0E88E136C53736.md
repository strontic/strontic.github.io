---
title: framedynos.dll | WMI SDK Provider Framework
excerpt: What is framedynos.dll?
---

# framedynos.dll 

* File Path: `C:\Windows\system32\framedynos.dll`
* Description: WMI SDK Provider Framework

## Hashes

Type | Hash
-- | --
MD5 | `845DC3AA96A8F043DC0E88E136C53736`
SHA1 | `FE316F8D5858F02CF08D29B0FABBA6C98941A036`
SHA256 | `109A9BA3E471B4F73CBC87530D9361FE66855A4D822C2F283D4F2FFC4E156EDC`
SHA384 | `990F01B125F074A64B3983ABC35A087459E75C592FC325960E557CD7638A25DB9D6A8BDF76DD9DCE97211C986A4E9CAA`
SHA512 | `0E647CB73002A2D9AEB2D57C795FD37AA51F42CF417717EE2D9CFB45179A6731DFF7C19C6D9C799B4A1BF3BF86AD2B8EC860FCA39BB47019B1023E94005C205A`
SSDEEP | `6144:pXPL0PJ8mJt/HE+gCiqIVYNj/YiDGXhGtTVBNRnA:JvqvE+PoVYNjgSym7L`
IMP | `7194401A59D515830DAA2118CC1D831D`
PESHA1 | `E51815C6D0DF0BCC4E0D59838E728EC211326654`
PE256 | `B0FA54D34BCEAD9B9D6CB896AC333C2C7EE1F93A18714E43BEA1E0C401FD94AA`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`class CHString __cdecl operator+(class CHString const & __ptr64,class CHString const & __ptr64)` | 124 (0x7c) | Exported Function | 0x0000000180012210 | 0x00012210
`public: long __cdecl CFrameworkQueryEx::GetValuesForProp(unsigned short const * __ptr64,class std::vector<class _variant_t,class std::allocator<class _variant_t> > & __ptr64) __ptr64` | 381 (0x17d) | Exported Function | 0x000000018001f630 | 0x0001f630
`public: long __cdecl CFrameworkQueryEx::GetValuesForProp(unsigned short const * __ptr64,class std::vector<int,class std::allocator<int> > & __ptr64) __ptr64` | 380 (0x17c) | Exported Function | 0x000000018000e5c0 | 0x0000e5c0
`public: long __cdecl CInstance::AddRef(void) __ptr64` | 167 (0xa7) | Exported Function | 0x0000000180003150 | 0x00003150
`public: long __cdecl CInstance::Commit(void) __ptr64` | 194 (0xc2) | Exported Function | 0x0000000180002d40 | 0x00002d40
`public: long __cdecl CInstance::Release(void) __ptr64` | 473 (0x1d9) | Exported Function | 0x0000000180004930 | 0x00004930
`public: long __cdecl CRegistry::CreateOpen(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES * __ptr64,unsigned long * __ptr64) __ptr64` | 214 (0xd6) | Exported Function | 0x000000018002a7a0 | 0x0002a7a0
`public: long __cdecl CRegistry::DeleteKey(class CHString * __ptr64) __ptr64` | 227 (0xe3) | Exported Function | 0x000000018002a930 | 0x0002a930
`public: long __cdecl CRegistry::DeleteValue(unsigned short const * __ptr64) __ptr64` | 228 (0xe4) | Exported Function | 0x000000018002a910 | 0x0002a910
`public: long __cdecl CRegistry::EnumerateAndGetValues(unsigned long & __ptr64,unsigned short * __ptr64 & __ptr64,unsigned char * __ptr64 & __ptr64) __ptr64` | 237 (0xed) | Exported Function | 0x000000018002a980 | 0x0002a980
`public: long __cdecl CRegistry::Open(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long) __ptr64` | 451 (0x1c3) | Exported Function | 0x000000018000c680 | 0x0000c680
`public: long __cdecl CRegistry::OpenAndEnumerateSubKeys(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long) __ptr64` | 452 (0x1c4) | Exported Function | 0x000000018002b5a0 | 0x0002b5a0
`public: long __cdecl CRegistry::OpenLocalMachineKeyAndReadValue(unsigned short const * __ptr64,unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 454 (0x1c6) | Exported Function | 0x000000018000a920 | 0x0000a920
`public: long __cdecl CThreadBase::AddRef(void) __ptr64` | 168 (0xa8) | Exported Function | 0x0000000180021dd0 | 0x00021dd0
`public: long __cdecl CThreadBase::Release(void) __ptr64` | 474 (0x1da) | Exported Function | 0x0000000180005a00 | 0x00005a00
`public: long __cdecl MethodContext::AddRef(void) __ptr64` | 171 (0xab) | Exported Function | 0x0000000180021dd0 | 0x00021dd0
`public: long __cdecl CFrameworkQuery::Init(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,class CHString & __ptr64) __ptr64` | 398 (0x18e) | Exported Function | 0x0000000180007300 | 0x00007300
`public: long __cdecl MethodContext::Release(void) __ptr64` | 477 (0x1dd) | Exported Function | 0x0000000180021e60 | 0x00021e60
`public: long __cdecl CFrameworkQuery::Init(struct ParsedObjectPath * __ptr64,struct IWbemContext * __ptr64,unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 397 (0x18d) | Exported Function | 0x00000001800091f0 | 0x000091f0
`public: long __cdecl CFrameworkQuery::GetValuesForProp(unsigned short const * __ptr64,class CHStringArray & __ptr64) __ptr64` | 379 (0x17b) | Exported Function | 0x000000018000fa30 | 0x0000fa30
`public: int __cdecl WBEMTime::operator!=(class WBEMTime const & __ptr64)const __ptr64` | 113 (0x71) | Exported Function | 0x000000018001e210 | 0x0001e210
`public: int __cdecl WBEMTime::operator<(class WBEMTime const & __ptr64)const __ptr64` | 131 (0x83) | Exported Function | 0x000000018001e230 | 0x0001e230
`public: int __cdecl WBEMTime::operator<=(class WBEMTime const & __ptr64)const __ptr64` | 133 (0x85) | Exported Function | 0x000000018001e250 | 0x0001e250
`public: int __cdecl WBEMTime::operator==(class WBEMTime const & __ptr64)const __ptr64` | 111 (0x6f) | Exported Function | 0x000000018001e1f0 | 0x0001e1f0
`public: int __cdecl WBEMTime::operator>(class WBEMTime const & __ptr64)const __ptr64` | 135 (0x87) | Exported Function | 0x000000018001e270 | 0x0001e270
`public: int __cdecl WBEMTime::operator>=(class WBEMTime const & __ptr64)const __ptr64` | 137 (0x89) | Exported Function | 0x000000018001e290 | 0x0001e290
`public: int __cdecl WBEMTime::SetDMTF(unsigned short * __ptr64 const) __ptr64` | 513 (0x201) | Exported Function | 0x0000000180029a60 | 0x00029a60
`public: int __cdecl WBEMTimeSpan::GetFILETIME(struct _FILETIME * __ptr64)const __ptr64` | 322 (0x142) | Exported Function | 0x0000000180029840 | 0x00029840
`public: int __cdecl WBEMTimeSpan::Gettime_t(__int64 * __ptr64)const __ptr64` | 392 (0x188) | Exported Function | 0x0000000180029a30 | 0x00029a30
`public: int __cdecl WBEMTimeSpan::operator!=(class WBEMTimeSpan const & __ptr64)const __ptr64` | 114 (0x72) | Exported Function | 0x000000018001e210 | 0x0001e210
`public: int __cdecl WBEMTimeSpan::operator<(class WBEMTimeSpan const & __ptr64)const __ptr64` | 132 (0x84) | Exported Function | 0x000000018001e230 | 0x0001e230
`public: int __cdecl WBEMTimeSpan::operator<=(class WBEMTimeSpan const & __ptr64)const __ptr64` | 134 (0x86) | Exported Function | 0x000000018001e250 | 0x0001e250
`public: int __cdecl WBEMTimeSpan::operator==(class WBEMTimeSpan const & __ptr64)const __ptr64` | 112 (0x70) | Exported Function | 0x000000018001e1f0 | 0x0001e1f0
`public: int __cdecl WBEMTimeSpan::operator>(class WBEMTimeSpan const & __ptr64)const __ptr64` | 136 (0x88) | Exported Function | 0x000000018001e270 | 0x0001e270
`public: int __cdecl WBEMTimeSpan::operator>=(class WBEMTimeSpan const & __ptr64)const __ptr64` | 138 (0x8a) | Exported Function | 0x000000018001e290 | 0x0001e290
`public: long __cdecl CFrameworkQuery::GetValuesForProp(unsigned short const * __ptr64,class std::vector<class _bstr_t,class std::allocator<class _bstr_t> > & __ptr64) __ptr64` | 378 (0x17a) | Exported Function | 0x000000018000e880 | 0x0000e880
`public: int __cdecl WBEMTime::Gettime_t(__int64 * __ptr64)const __ptr64` | 391 (0x187) | Exported Function | 0x00000001800299d0 | 0x000299d0
`public: static bool __cdecl CWbemProviderGlue::IsDerivedFrom(unsigned short const * __ptr64,unsigned short const * __ptr64,class MethodContext * __ptr64,unsigned short const * __ptr64)` | 411 (0x19b) | Exported Function | 0x0000000180011db0 | 0x00011db0
`public: static class CWbemGlueFactory * __ptr64 __cdecl CWbemGlueFactory::Create(long * __ptr64)` | 203 (0xcb) | Exported Function | 0x000000018000de60 | 0x0000de60
`public: static long __cdecl CWbemProviderGlue::GetInstancesByQuery(unsigned short const * __ptr64,class TRefPointerCollection<class CInstance> * __ptr64,class MethodContext * __ptr64,unsigned short const * __ptr64)` | 328 (0x148) | Exported Function | 0x0000000180004270 | 0x00004270
`public: static long __cdecl CWbemProviderGlue::GetInstancesByQueryAsynch(unsigned short const * __ptr64,class Provider * __ptr64,long (__cdecl*)(class Provider * __ptr64,class CInstance * __ptr64,class MethodContext * __ptr64,void * __ptr64),unsigned short const * __ptr64,class MethodContext * __ptr64,void * __ptr64)` | 329 (0x149) | Exported Function | 0x0000000180024460 | 0x00024460
`public: static long __cdecl WBEMTime::GetLocalOffsetForDate(__int64 const & __ptr64)` | 334 (0x14e) | Exported Function | 0x0000000180029870 | 0x00029870
`public: static long __cdecl WBEMTime::GetLocalOffsetForDate(struct _FILETIME const * __ptr64)` | 335 (0x14f) | Exported Function | 0x00000001800298e0 | 0x000298e0
`public: static long __cdecl WBEMTime::GetLocalOffsetForDate(struct _SYSTEMTIME const * __ptr64)` | 336 (0x150) | Exported Function | 0x0000000180003ee0 | 0x00003ee0
`public: static long __cdecl WBEMTime::GetLocalOffsetForDate(struct tm const * __ptr64)` | 337 (0x151) | Exported Function | 0x0000000180029930 | 0x00029930
`public: static struct IWbemServices * __ptr64 __cdecl CWbemProviderGlue::GetNamespaceConnection(unsigned short const * __ptr64)` | 346 (0x15a) | Exported Function | 0x0000000180024a50 | 0x00024a50
`public: static struct IWbemServices * __ptr64 __cdecl CWbemProviderGlue::GetNamespaceConnection(unsigned short const * __ptr64,class MethodContext * __ptr64)` | 347 (0x15b) | Exported Function | 0x0000000180006550 | 0x00006550
`public: static unsigned long __cdecl CWbemProviderGlue::GetOSMajorVersion(void)` | 349 (0x15d) | Exported Function | 0x000000018001e550 | 0x0001e550
`public: static unsigned long __cdecl CWbemProviderGlue::GetPlatform(void)` | 356 (0x164) | Exported Function | 0x000000018001e560 | 0x0001e560
`public: static unsigned short * __ptr64 __cdecl CObjectPathParser::GetRelativePath(unsigned short * __ptr64)` | 362 (0x16a) | Exported Function | 0x0000000180026f70 | 0x00026f70
`public: static unsigned short const * __ptr64 __cdecl CWbemProviderGlue::GetCSDVersion(void)` | 286 (0x11e) | Exported Function | 0x000000018001e540 | 0x0001e540
`public: static void __cdecl CHString::Release(struct CHStringData * __ptr64)` | 472 (0x1d8) | Exported Function | 0x000000018000b390 | 0x0000b390
`public: static void __cdecl CWbemProviderGlue::FrameworkLogin(unsigned short const * __ptr64,class Provider * __ptr64,unsigned short const * __ptr64)` | 261 (0x105) | Exported Function | 0x0000000180023df0 | 0x00023df0
`public: static void __cdecl CWbemProviderGlue::FrameworkLogoff(unsigned short const * __ptr64,unsigned short const * __ptr64)` | 264 (0x108) | Exported Function | 0x0000000180007e50 | 0x00007e50
`public: static long __cdecl CWbemProviderGlue::GetInstancePropertiesByPath(unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,class MethodContext * __ptr64,class CHStringArray & __ptr64)` | 327 (0x147) | Exported Function | 0x00000001800118e0 | 0x000118e0
`public: static bool __cdecl CWbemProviderGlue::SetStatusObject(class MethodContext * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,long,struct tagSAFEARRAY const * __ptr64,struct tagSAFEARRAY const * __ptr64)` | 524 (0x20c) | Exported Function | 0x0000000180025ad0 | 0x00025ad0
`public: static long __cdecl CWbemProviderGlue::GetInstanceKeysByPath(unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,class MethodContext * __ptr64)` | 326 (0x146) | Exported Function | 0x0000000180011730 | 0x00011730
`public: static long __cdecl CWbemProviderGlue::GetEmptyInstance(unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,unsigned short const * __ptr64)` | 320 (0x140) | Exported Function | 0x0000000180024340 | 0x00024340
`public: static class CWbemGlueFactory * __ptr64 __cdecl CWbemGlueFactory::Create(void)` | 204 (0xcc) | Exported Function | 0x000000018001edb0 | 0x0001edb0
`public: static int __cdecl CObjectPathParser::Unparse(struct ParsedObjectPath * __ptr64,unsigned short * __ptr64 * __ptr64)` | 548 (0x224) | Exported Function | 0x000000018000f220 | 0x0000f220
`public: static int __cdecl CWbemProviderGlue::FrameworkLoginDLL(unsigned short const * __ptr64)` | 262 (0x106) | Exported Function | 0x0000000180023ee0 | 0x00023ee0
`public: static int __cdecl CWbemProviderGlue::FrameworkLoginDLL(unsigned short const * __ptr64,long * __ptr64)` | 263 (0x107) | Exported Function | 0x0000000180003a90 | 0x00003a90
`public: static int __cdecl CWbemProviderGlue::FrameworkLogoffDLL(unsigned short const * __ptr64)` | 265 (0x109) | Exported Function | 0x0000000180023ef0 | 0x00023ef0
`public: static int __cdecl CWbemProviderGlue::FrameworkLogoffDLL(unsigned short const * __ptr64,long * __ptr64)` | 266 (0x10a) | Exported Function | 0x0000000180003af0 | 0x00003af0
`public: static int __cdecl Provider::initFailed(void)` | 565 (0x235) | Exported Function | 0x0000000180004010 | 0x00004010
`public: static long __cdecl CWbemProviderGlue::DecrementObjectCount(void)` | 218 (0xda) | Exported Function | 0x0000000180022bd0 | 0x00022bd0
`public: static long __cdecl CWbemProviderGlue::FillInstance(class CInstance * __ptr64,unsigned short const * __ptr64)` | 249 (0xf9) | Exported Function | 0x0000000180023c70 | 0x00023c70
`public: static long __cdecl CWbemProviderGlue::FillInstance(class MethodContext * __ptr64,class CInstance * __ptr64)` | 250 (0xfa) | Exported Function | 0x0000000180023d40 | 0x00023d40
`public: static long __cdecl CWbemProviderGlue::GetAllDerivedInstances(unsigned short const * __ptr64,class TRefPointerCollection<class CInstance> * __ptr64,class MethodContext * __ptr64,unsigned short const * __ptr64)` | 272 (0x110) | Exported Function | 0x0000000180023f00 | 0x00023f00
`public: static long __cdecl CWbemProviderGlue::GetAllDerivedInstancesAsynch(unsigned short const * __ptr64,class Provider * __ptr64,long (__cdecl*)(class Provider * __ptr64,class CInstance * __ptr64,class MethodContext * __ptr64,void * __ptr64),unsigned short const * __ptr64,class MethodContext * __ptr64,void * __ptr64)` | 273 (0x111) | Exported Function | 0x0000000180023f90 | 0x00023f90
`public: static long __cdecl CWbemProviderGlue::GetAllInstances(unsigned short const * __ptr64,class TRefPointerCollection<class CInstance> * __ptr64,unsigned short const * __ptr64,class MethodContext * __ptr64)` | 274 (0x112) | Exported Function | 0x0000000180024040 | 0x00024040
`public: static long __cdecl CWbemProviderGlue::GetAllInstancesAsynch(unsigned short const * __ptr64,class Provider * __ptr64,long (__cdecl*)(class Provider * __ptr64,class CInstance * __ptr64,class MethodContext * __ptr64,void * __ptr64),unsigned short const * __ptr64,class MethodContext * __ptr64,void * __ptr64)` | 275 (0x113) | Exported Function | 0x00000001800240e0 | 0x000240e0
`public: static long __cdecl CWbemProviderGlue::GetEmptyInstance(class MethodContext * __ptr64,unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,unsigned short const * __ptr64)` | 319 (0x13f) | Exported Function | 0x0000000180024190 | 0x00024190
`public: static long __cdecl CWbemProviderGlue::GetInstanceByPath(unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,class MethodContext * __ptr64)` | 324 (0x144) | Exported Function | 0x000000018000ef30 | 0x0000ef30
`public: int __cdecl WBEMTime::GetSYSTEMTIME(struct _SYSTEMTIME * __ptr64)const __ptr64` | 364 (0x16c) | Exported Function | 0x000000018000e530 | 0x0000e530
`public: int __cdecl WBEMTime::GetStructtm(struct tm * __ptr64)const __ptr64` | 371 (0x173) | Exported Function | 0x0000000180029970 | 0x00029970
`public: int __cdecl WBEMTime::GetFILETIME(struct _FILETIME * __ptr64)const __ptr64` | 321 (0x141) | Exported Function | 0x000000018000e580 | 0x0000e580
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator=(__int64 const & __ptr64) __ptr64` | 104 (0x68) | Exported Function | 0x0000000180003c60 | 0x00003c60
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator=(struct _FILETIME const & __ptr64) __ptr64` | 101 (0x65) | Exported Function | 0x0000000180002d20 | 0x00002d20
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator=(struct _SYSTEMTIME const & __ptr64) __ptr64` | 102 (0x66) | Exported Function | 0x0000000180003e80 | 0x00003e80
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator=(struct tm const & __ptr64) __ptr64` | 103 (0x67) | Exported Function | 0x00000001800293e0 | 0x000293e0
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator=(unsigned short * __ptr64 const) __ptr64` | 105 (0x69) | Exported Function | 0x0000000180029440 | 0x00029440
`public: class WBEMTimeSpan & __ptr64 __cdecl WBEMTimeSpan::operator=(class WBEMTimeSpan && __ptr64) __ptr64` | 106 (0x6a) | Exported Function | 0x000000018001e1a0 | 0x0001e1a0
`public: class WBEMTimeSpan & __ptr64 __cdecl WBEMTimeSpan::operator=(class WBEMTimeSpan const & __ptr64) __ptr64` | 107 (0x6b) | Exported Function | 0x000000018001e1a0 | 0x0001e1a0
`public: class WBEMTimeSpan __cdecl WBEMTime::operator-(class WBEMTime const & __ptr64) __ptr64` | 121 (0x79) | Exported Function | 0x00000001800295d0 | 0x000295d0
`public: class WBEMTimeSpan __cdecl WBEMTimeSpan::operator+(class WBEMTimeSpan const & __ptr64)const __ptr64` | 130 (0x82) | Exported Function | 0x0000000180029600 | 0x00029600
`public: class WBEMTimeSpan __cdecl WBEMTimeSpan::operator-(class WBEMTimeSpan const & __ptr64)const __ptr64` | 123 (0x7b) | Exported Function | 0x00000001800295d0 | 0x000295d0
`public: class WBEMTimeSpan const & __ptr64 __cdecl WBEMTimeSpan::operator+=(class WBEMTimeSpan const & __ptr64) __ptr64` | 144 (0x90) | Exported Function | 0x0000000180029630 | 0x00029630
`public: class WBEMTimeSpan const & __ptr64 __cdecl WBEMTimeSpan::operator-=(class WBEMTimeSpan const & __ptr64) __ptr64` | 146 (0x92) | Exported Function | 0x0000000180029660 | 0x00029660
`public: class WBEMTimeSpan const & __ptr64 __cdecl WBEMTimeSpan::operator=(__int64 const & __ptr64) __ptr64` | 109 (0x6d) | Exported Function | 0x00000001800294b0 | 0x000294b0
`public: class WBEMTimeSpan const & __ptr64 __cdecl WBEMTimeSpan::operator=(struct _FILETIME const & __ptr64) __ptr64` | 108 (0x6c) | Exported Function | 0x0000000180029320 | 0x00029320
`public: class WBEMTimeSpan const & __ptr64 __cdecl WBEMTimeSpan::operator=(unsigned short * __ptr64 const) __ptr64` | 110 (0x6e) | Exported Function | 0x00000001800294e0 | 0x000294e0
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator-=(class WBEMTimeSpan const & __ptr64) __ptr64` | 145 (0x91) | Exported Function | 0x0000000180029660 | 0x00029660
`public: enum ProviderLog::LogLevel __cdecl ProviderLog::IsLoggingOn(class CHString * __ptr64) __ptr64` | 417 (0x1a1) | Exported Function | 0x0000000180008fc0 | 0x00008fc0
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator+=(class WBEMTimeSpan const & __ptr64) __ptr64` | 143 (0x8f) | Exported Function | 0x0000000180029630 | 0x00029630
`public: class WBEMTime __cdecl WBEMTime::operator+(class WBEMTimeSpan const & __ptr64)const __ptr64` | 129 (0x81) | Exported Function | 0x0000000180029600 | 0x00029600
`public: class CInstance & __ptr64 __cdecl CInstance::operator=(class CInstance const & __ptr64) __ptr64` | 85 (0x55) | Exported Function | 0x000000018001df70 | 0x0001df70
`public: class CObjectPathParser & __ptr64 __cdecl CObjectPathParser::operator=(class CObjectPathParser const & __ptr64) __ptr64` | 86 (0x56) | Exported Function | 0x000000018001dfa0 | 0x0001dfa0
`public: class CreateMutexAsProcess & __ptr64 __cdecl CreateMutexAsProcess::operator=(class CreateMutexAsProcess const & __ptr64) __ptr64` | 93 (0x5d) | Exported Function | 0x000000018001e1a0 | 0x0001e1a0
`public: class CRegistry & __ptr64 __cdecl CRegistry::operator=(class CRegistry const & __ptr64) __ptr64` | 87 (0x57) | Exported Function | 0x000000018001e990 | 0x0001e990
`public: class CRegistrySearch & __ptr64 __cdecl CRegistrySearch::operator=(class CRegistrySearch const & __ptr64) __ptr64` | 88 (0x58) | Exported Function | 0x000000018001ea80 | 0x0001ea80
`public: class CThreadBase & __ptr64 __cdecl CThreadBase::operator=(class CThreadBase const & __ptr64) __ptr64` | 89 (0x59) | Exported Function | 0x000000018001dfd0 | 0x0001dfd0
`public: class CWbemGlueFactory & __ptr64 __cdecl CWbemGlueFactory::operator=(class CWbemGlueFactory const & __ptr64) __ptr64` | 90 (0x5a) | Exported Function | 0x000000018001e010 | 0x0001e010
`public: class CWbemProviderGlue & __ptr64 __cdecl CWbemProviderGlue::operator=(class CWbemProviderGlue const & __ptr64) __ptr64` | 91 (0x5b) | Exported Function | 0x000000018001e030 | 0x0001e030
`public: class CWinMsgEvent & __ptr64 __cdecl CWinMsgEvent::operator=(class CWinMsgEvent const & __ptr64) __ptr64` | 92 (0x5c) | Exported Function | 0x0000000180027470 | 0x00027470
`public: class MethodContext & __ptr64 __cdecl MethodContext::operator=(class MethodContext const & __ptr64) __ptr64` | 95 (0x5f) | Exported Function | 0x000000018001e0a0 | 0x0001e0a0
`public: class MethodContext * __ptr64 __cdecl CInstance::GetMethodContext(void)const __ptr64` | 343 (0x157) | Exported Function | 0x0000000180003c30 | 0x00003c30
`public: class Provider & __ptr64 __cdecl Provider::operator=(class Provider const & __ptr64) __ptr64` | 97 (0x61) | Exported Function | 0x000000018001e120 | 0x0001e120
`public: class ProviderLog & __ptr64 __cdecl ProviderLog::operator=(class ProviderLog const & __ptr64) __ptr64` | 98 (0x62) | Exported Function | 0x000000018001ead0 | 0x0001ead0
`public: class WBEMTime & __ptr64 __cdecl WBEMTime::operator=(class WBEMTime && __ptr64) __ptr64` | 99 (0x63) | Exported Function | 0x000000018001e1a0 | 0x0001e1a0
`public: class WBEMTime & __ptr64 __cdecl WBEMTime::operator=(class WBEMTime const & __ptr64) __ptr64` | 100 (0x64) | Exported Function | 0x000000018001e1a0 | 0x0001e1a0
`public: class WBEMTime __cdecl WBEMTime::operator-(class WBEMTimeSpan const & __ptr64)const __ptr64` | 122 (0x7a) | Exported Function | 0x00000001800295d0 | 0x000295d0
`public: int __cdecl CAutoEvent::Signal(void) __ptr64` | 536 (0x218) | Exported Function | 0x0000000180027b30 | 0x00027b30
`public: int __cdecl CFrameworkQueryEx::Is3TokenOR(unsigned short const * __ptr64,unsigned short const * __ptr64,struct tagVARIANT & __ptr64,struct tagVARIANT & __ptr64) __ptr64` | 409 (0x199) | Exported Function | 0x000000018001fb40 | 0x0001fb40
`public: int __cdecl CFrameworkQueryEx::IsNTokenAnd(class CHStringArray & __ptr64,class CHPtrArray & __ptr64) __ptr64` | 418 (0x1a2) | Exported Function | 0x000000018001fd40 | 0x0001fd40
`public: int __cdecl CRegistrySearch::FreeSearchList(int,class CHPtrArray & __ptr64) __ptr64` | 271 (0x10f) | Exported Function | 0x000000018002ab10 | 0x0002ab10
`public: int __cdecl CRegistrySearch::LocateKeyByNameOrValueName(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64 * __ptr64,unsigned long,class CHString & __ptr64,class CHString & __ptr64) __ptr64` | 432 (0x1b0) | Exported Function | 0x000000018002b2c0 | 0x0002b2c0
`public: int __cdecl CRegistrySearch::SearchAndBuildList(class CHString,class CHPtrArray & __ptr64,class CHString,class CHString,int,struct HKEY__ * __ptr64) __ptr64` | 489 (0x1e9) | Exported Function | 0x000000018002b7c0 | 0x0002b7c0
`public: int __cdecl CThreadBase::BeginRead(unsigned long) __ptr64` | 181 (0xb5) | Exported Function | 0x0000000180003100 | 0x00003100
`public: int __cdecl CThreadBase::BeginWrite(unsigned long) __ptr64` | 182 (0xb6) | Exported Function | 0x0000000180003100 | 0x00003100
`public: int __cdecl ParsedObjectPath::AddKeyRef(struct KeyRef * __ptr64) __ptr64` | 162 (0xa2) | Exported Function | 0x0000000180011270 | 0x00011270
`public: int __cdecl ParsedObjectPath::AddKeyRef(unsigned short const * __ptr64,struct tagVARIANT const * __ptr64) __ptr64` | 163 (0xa3) | Exported Function | 0x0000000180026470 | 0x00026470
`public: int __cdecl ParsedObjectPath::AddKeyRefEx(unsigned short const * __ptr64,struct tagVARIANT const * __ptr64) __ptr64` | 164 (0xa4) | Exported Function | 0x0000000180026560 | 0x00026560
`public: int __cdecl ParsedObjectPath::AddNamespace(unsigned short const * __ptr64) __ptr64` | 165 (0xa5) | Exported Function | 0x0000000180010c10 | 0x00010c10
`public: int __cdecl ParsedObjectPath::IsClass(void) __ptr64` | 410 (0x19a) | Exported Function | 0x00000001800124c0 | 0x000124c0
`public: int __cdecl ParsedObjectPath::IsInstance(void) __ptr64` | 415 (0x19f) | Exported Function | 0x0000000180012480 | 0x00012480
`public: int __cdecl ParsedObjectPath::IsLocal(unsigned short const * __ptr64) __ptr64` | 416 (0x1a0) | Exported Function | 0x000000018000f1e0 | 0x0000f1e0
`public: int __cdecl ParsedObjectPath::IsObject(void) __ptr64` | 420 (0x1a4) | Exported Function | 0x00000001800124f0 | 0x000124f0
`public: int __cdecl ParsedObjectPath::IsRelative(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 425 (0x1a9) | Exported Function | 0x000000018000f170 | 0x0000f170
`public: int __cdecl ParsedObjectPath::SetClassName(unsigned short const * __ptr64) __ptr64` | 504 (0x1f8) | Exported Function | 0x0000000180026fa0 | 0x00026fa0
`public: int __cdecl CObjectPathParser::Parse(unsigned short const * __ptr64,struct ParsedObjectPath * __ptr64 * __ptr64) __ptr64` | 457 (0x1c9) | Exported Function | 0x0000000180010d80 | 0x00010d80
`public: int __cdecl CHStringArray::GetUpperBound(void)const __ptr64` | 376 (0x178) | Exported Function | 0x000000018001e5a0 | 0x0001e5a0
`public: int __cdecl CHStringArray::GetSize(void)const __ptr64` | 366 (0x16e) | Exported Function | 0x0000000180003070 | 0x00003070
`public: int __cdecl CHStringArray::Append(class CHStringArray const & __ptr64) __ptr64` | 179 (0xb3) | Exported Function | 0x0000000180029da0 | 0x00029da0
`public: int __cdecl CHPtrArray::Add(void * __ptr64) __ptr64` | 159 (0x9f) | Exported Function | 0x0000000180004220 | 0x00004220
`public: int __cdecl CHPtrArray::Append(class CHPtrArray const & __ptr64) __ptr64` | 178 (0xb2) | Exported Function | 0x000000018002a150 | 0x0002a150
`public: int __cdecl CHPtrArray::GetSize(void)const __ptr64` | 365 (0x16d) | Exported Function | 0x0000000180003070 | 0x00003070
`public: int __cdecl CHPtrArray::GetUpperBound(void)const __ptr64` | 375 (0x177) | Exported Function | 0x000000018001e5a0 | 0x0001e5a0
`public: int __cdecl CHString::Collate(unsigned short const * __ptr64)const __ptr64` | 193 (0xc1) | Exported Function | 0x000000018001e500 | 0x0001e500
`public: int __cdecl CHString::Compare(unsigned short const * __ptr64)const __ptr64` | 196 (0xc4) | Exported Function | 0x0000000180007d20 | 0x00007d20
`public: int __cdecl CHString::CompareNoCase(unsigned short const * __ptr64)const __ptr64` | 197 (0xc5) | Exported Function | 0x00000001800123d0 | 0x000123d0
`public: static void __cdecl CWbemProviderGlue::IncrementObjectCount(void)` | 395 (0x18b) | Exported Function | 0x0000000180024df0 | 0x00024df0
`public: int __cdecl CHString::Find(unsigned short const * __ptr64)const __ptr64` | 252 (0xfc) | Exported Function | 0x0000000180002c30 | 0x00002c30
`public: int __cdecl CHString::FindOneOf(unsigned short const * __ptr64)const __ptr64` | 253 (0xfd) | Exported Function | 0x0000000180028f00 | 0x00028f00
`public: int __cdecl CHString::GetAllocLength(void)const __ptr64` | 276 (0x114) | Exported Function | 0x000000018001e520 | 0x0001e520
`public: int __cdecl CHString::GetLength(void)const __ptr64` | 331 (0x14b) | Exported Function | 0x0000000180002d60 | 0x00002d60
`public: int __cdecl CHString::IsEmpty(void)const __ptr64` | 412 (0x19c) | Exported Function | 0x0000000180006920 | 0x00006920
`public: int __cdecl CHString::LoadStringW(unsigned int) __ptr64` | 429 (0x1ad) | Exported Function | 0x00000001800290c0 | 0x000290c0
`public: int __cdecl CHString::ReverseFind(unsigned short)const __ptr64` | 485 (0x1e5) | Exported Function | 0x0000000180002ef0 | 0x00002ef0
`public: int __cdecl CHStringArray::Add(unsigned short const * __ptr64) __ptr64` | 160 (0xa0) | Exported Function | 0x0000000180003df0 | 0x00003df0
`public: int __cdecl CHString::Find(unsigned short)const __ptr64` | 251 (0xfb) | Exported Function | 0x0000000180002da0 | 0x00002da0
`public: class CHStringArray & __ptr64 __cdecl CHStringArray::operator=(class CHStringArray const & __ptr64) __ptr64` | 84 (0x54) | Exported Function | 0x000000018001dee0 | 0x0001dee0
`public: struct HKEY__ * __ptr64 __cdecl CRegistry::GethKey(void) __ptr64` | 390 (0x186) | Exported Function | 0x00000001800034e0 | 0x000034e0
`public: struct IWbemClassObject * __ptr64 __cdecl MethodContext::GetStatusObject(void) __ptr64` | 369 (0x171) | Exported Function | 0x00000001800059a0 | 0x000059a0
`public: void * __ptr64 __cdecl CHPtrArray::GetAt(int)const __ptr64` | 277 (0x115) | Exported Function | 0x0000000180003080 | 0x00003080
`public: void * __ptr64 __cdecl CHPtrArray::operator[](int)const __ptr64` | 116 (0x74) | Exported Function | 0x0000000180003080 | 0x00003080
`public: void __cdecl CFrameworkQuery::GetRequiredProperties(class CHStringArray & __ptr64) __ptr64` | 363 (0x16b) | Exported Function | 0x000000018001f180 | 0x0001f180
`public: void __cdecl CFrameworkQuery::Init2(struct IWbemClassObject * __ptr64) __ptr64` | 396 (0x18c) | Exported Function | 0x0000000180006ab0 | 0x00006ab0
`public: void __cdecl CFrameworkQueryEx::GetPropertyBitMask(class CHPtrArray const & __ptr64,void * __ptr64) __ptr64` | 357 (0x165) | Exported Function | 0x0000000180011c50 | 0x00011c50
`public: void __cdecl CHPtrArray::Copy(class CHPtrArray const & __ptr64) __ptr64` | 200 (0xc8) | Exported Function | 0x000000018002a1b0 | 0x0002a1b0
`public: void __cdecl CHPtrArray::FreeExtra(void) __ptr64` | 268 (0x10c) | Exported Function | 0x0000000180029e90 | 0x00029e90
`public: void __cdecl CHPtrArray::InsertAt(int,class CHPtrArray * __ptr64) __ptr64` | 404 (0x194) | Exported Function | 0x000000018002a1f0 | 0x0002a1f0
`public: void __cdecl CHPtrArray::InsertAt(int,void * __ptr64,int) __ptr64` | 405 (0x195) | Exported Function | 0x000000018002a270 | 0x0002a270
`public: void __cdecl CHPtrArray::RemoveAll(void) __ptr64` | 479 (0x1df) | Exported Function | 0x0000000180002e60 | 0x00002e60
`public: void __cdecl CHPtrArray::RemoveAt(int,int) __ptr64` | 481 (0x1e1) | Exported Function | 0x000000018002a440 | 0x0002a440
`public: void __cdecl CHPtrArray::SetAt(int,void * __ptr64) __ptr64` | 491 (0x1eb) | Exported Function | 0x000000018002a4a0 | 0x0002a4a0
`public: void __cdecl CHPtrArray::SetAtGrow(int,void * __ptr64) __ptr64` | 494 (0x1ee) | Exported Function | 0x000000018002a4c0 | 0x0002a4c0
`public: void __cdecl CHPtrArray::SetSize(int,int) __ptr64` | 522 (0x20a) | Exported Function | 0x0000000180004a30 | 0x00004a30
`public: void __cdecl CHString::Empty(void) __ptr64` | 233 (0xe9) | Exported Function | 0x000000018000a8c0 | 0x0000a8c0
`public: void * __ptr64 * __ptr64 __cdecl CHPtrArray::GetData(void) __ptr64` | 312 (0x138) | Exported Function | 0x0000000180002c20 | 0x00002c20
`public: void __cdecl CHString::Format(unsigned int,...) __ptr64` | 256 (0x100) | Exported Function | 0x0000000180028f40 | 0x00028f40
`public: void * __ptr64 & __ptr64 __cdecl CHPtrArray::operator[](int) __ptr64` | 115 (0x73) | Exported Function | 0x0000000180002d80 | 0x00002d80
`public: virtual void __cdecl MethodContext::QueryPostProcess(void) __ptr64` | 469 (0x1d5) | Exported Function | 0x00000001800107d0 | 0x000107d0
`public: virtual long __cdecl CWbemProviderGlue::GetObject(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 350 (0x15e) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::GetObjectAsync(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 354 (0x162) | Exported Function | 0x0000000180010200 | 0x00010200
`public: virtual long __cdecl CWbemProviderGlue::Initialize(unsigned short * __ptr64,long,unsigned short * __ptr64,unsigned short * __ptr64,struct IWbemServices * __ptr64,struct IWbemContext * __ptr64,struct IWbemProviderInitSink * __ptr64) __ptr64` | 403 (0x193) | Exported Function | 0x000000018000d120 | 0x0000d120
`public: virtual long __cdecl CWbemProviderGlue::OpenNamespace(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemServices * __ptr64 * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 455 (0x1c7) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::PutClass(struct IWbemClassObject * __ptr64,long,struct IWbemContext * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 460 (0x1cc) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::PutClassAsync(struct IWbemClassObject * __ptr64,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 461 (0x1cd) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::PutInstance(struct IWbemClassObject * __ptr64,long,struct IWbemContext * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 462 (0x1ce) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::PutInstanceAsync(struct IWbemClassObject * __ptr64,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 465 (0x1d1) | Exported Function | 0x0000000180025500 | 0x00025500
`public: virtual long __cdecl CWbemProviderGlue::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 467 (0x1d3) | Exported Function | 0x0000000180006680 | 0x00006680
`public: virtual long __cdecl CWbemProviderGlue::QueryObjectSink(long,struct IWbemObjectSink * __ptr64 * __ptr64) __ptr64` | 468 (0x1d4) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual struct IWbemContext * __ptr64 __cdecl MethodContext::GetIWBEMContext(void) __ptr64` | 323 (0x143) | Exported Function | 0x0000000180002f50 | 0x00002f50
`public: virtual unsigned long __cdecl CWbemGlueFactory::AddRef(void) __ptr64` | 169 (0xa9) | Exported Function | 0x000000018000ca10 | 0x0000ca10
`public: virtual unsigned long __cdecl CWbemGlueFactory::Release(void) __ptr64` | 475 (0x1db) | Exported Function | 0x000000018000ca60 | 0x0000ca60
`public: virtual unsigned long __cdecl CWbemProviderGlue::AddRef(void) __ptr64` | 170 (0xaa) | Exported Function | 0x00000001800084f0 | 0x000084f0
`public: virtual unsigned long __cdecl CWbemProviderGlue::Release(void) __ptr64` | 476 (0x1dc) | Exported Function | 0x0000000180008470 | 0x00008470
`public: void * __ptr64 & __ptr64 __cdecl CHPtrArray::ElementAt(int) __ptr64` | 231 (0xe7) | Exported Function | 0x0000000180002d80 | 0x00002d80
`public: virtual long __cdecl CWbemProviderGlue::ExecQueryAsync(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 247 (0xf7) | Exported Function | 0x0000000180006f50 | 0x00006f50
`public: void __cdecl CHString::Format(unsigned short const * __ptr64,...) __ptr64` | 257 (0x101) | Exported Function | 0x00000001800015a0 | 0x000015a0
`public: void __cdecl CHString::FormatMessageW(unsigned short const * __ptr64,...) __ptr64` | 259 (0x103) | Exported Function | 0x0000000180028f60 | 0x00028f60
`public: void __cdecl CHStringArray::SetSize(int,int) __ptr64` | 523 (0x20b) | Exported Function | 0x000000018000a530 | 0x0000a530
`public: void __cdecl CObjectPathParser::``default constructor closure'(void) __ptr64` | 157 (0x9d) | Exported Function | 0x000000018001e4a0 | 0x0001e4a0
`public: void __cdecl CObjectPathParser::Free(struct ParsedObjectPath * __ptr64) __ptr64` | 267 (0x10b) | Exported Function | 0x000000018000ed90 | 0x0000ed90
`public: void __cdecl CRegistry::Close(void) __ptr64` | 191 (0xbf) | Exported Function | 0x000000018000c580 | 0x0000c580
`public: void __cdecl CRegistry::RewindSubKeys(void) __ptr64` | 486 (0x1e6) | Exported Function | 0x000000018002b7b0 | 0x0002b7b0
`public: void __cdecl CThreadBase::``default constructor closure'(void) __ptr64` | 158 (0x9e) | Exported Function | 0x000000018001e4d0 | 0x0001e4d0
`public: void __cdecl CThreadBase::EndRead(void) __ptr64` | 235 (0xeb) | Exported Function | 0x00000001800032f0 | 0x000032f0
`public: void __cdecl CThreadBase::EndWrite(void) __ptr64` | 236 (0xec) | Exported Function | 0x00000001800032f0 | 0x000032f0
`public: void __cdecl CWbemGlueFactory::Destroy(void) __ptr64` | 229 (0xe5) | Exported Function | 0x000000018001ee00 | 0x0001ee00
`public: void __cdecl ParsedObjectPath::ClearKeys(void) __ptr64` | 190 (0xbe) | Exported Function | 0x0000000180026870 | 0x00026870
`public: void __cdecl ProviderLog::LocalLogMessage(unsigned short const * __ptr64,int,enum ProviderLog::LogLevel,unsigned short const * __ptr64,...) __ptr64` | 431 (0x1af) | Exported Function | 0x0000000180006a60 | 0x00006a60
`public: void __cdecl ProviderLog::LocalLogMessage(unsigned short const * __ptr64,unsigned short const * __ptr64,int,enum ProviderLog::LogLevel) __ptr64` | 430 (0x1ae) | Exported Function | 0x0000000180008f20 | 0x00008f20
`public: void __cdecl WBEMTime::Clear(void) __ptr64` | 188 (0xbc) | Exported Function | 0x000000018001e4f0 | 0x0001e4f0
`public: void __cdecl WBEMTimeSpan::Clear(void) __ptr64` | 189 (0xbd) | Exported Function | 0x000000018001e4f0 | 0x0001e4f0
`public: void const * __ptr64 * __ptr64 __cdecl CHPtrArray::GetData(void)const __ptr64` | 313 (0x139) | Exported Function | 0x0000000180002c20 | 0x00002c20
`public: void __cdecl CHStringArray::SetAtGrow(int,unsigned short const * __ptr64) __ptr64` | 495 (0x1ef) | Exported Function | 0x0000000180006790 | 0x00006790
`public: void __cdecl CHString::FormatMessageW(unsigned int,...) __ptr64` | 258 (0x102) | Exported Function | 0x0000000180028f40 | 0x00028f40
`public: void __cdecl CHStringArray::SetAt(int,unsigned short const * __ptr64) __ptr64` | 493 (0x1ed) | Exported Function | 0x000000018001e620 | 0x0001e620
`public: void __cdecl CHStringArray::RemoveAll(void) __ptr64` | 480 (0x1e0) | Exported Function | 0x0000000180012540 | 0x00012540
`public: void __cdecl CHString::FormatV(unsigned short const * __ptr64,char * __ptr64) __ptr64` | 260 (0x104) | Exported Function | 0x00000001800015d0 | 0x000015d0
`public: void __cdecl CHString::FreeExtra(void) __ptr64` | 269 (0x10d) | Exported Function | 0x0000000180029050 | 0x00029050
`public: void __cdecl CHString::MakeLower(void) __ptr64` | 440 (0x1b8) | Exported Function | 0x0000000180029110 | 0x00029110
`public: void __cdecl CHString::MakeReverse(void) __ptr64` | 441 (0x1b9) | Exported Function | 0x0000000180029140 | 0x00029140
`public: void __cdecl CHString::MakeUpper(void) __ptr64` | 442 (0x1ba) | Exported Function | 0x000000018000ab30 | 0x0000ab30
`public: void __cdecl CHString::Release(void) __ptr64` | 471 (0x1d7) | Exported Function | 0x000000018000b960 | 0x0000b960
`public: void __cdecl CHString::ReleaseBuffer(int) __ptr64` | 478 (0x1de) | Exported Function | 0x000000018000cd20 | 0x0000cd20
`public: void __cdecl CHString::SetAt(int,unsigned short) __ptr64` | 492 (0x1ec) | Exported Function | 0x000000018000c1b0 | 0x0000c1b0
`public: void __cdecl CHString::TrimLeft(void) __ptr64` | 539 (0x21b) | Exported Function | 0x00000001800291c0 | 0x000291c0
`public: void __cdecl CHString::TrimRight(void) __ptr64` | 540 (0x21c) | Exported Function | 0x0000000180029240 | 0x00029240
`public: void __cdecl CHString::UnlockBuffer(void) __ptr64` | 545 (0x221) | Exported Function | 0x00000001800292e0 | 0x000292e0
`public: void __cdecl CHStringArray::Copy(class CHStringArray const & __ptr64) __ptr64` | 201 (0xc9) | Exported Function | 0x0000000180029e00 | 0x00029e00
`public: void __cdecl CHStringArray::FreeExtra(void) __ptr64` | 270 (0x10e) | Exported Function | 0x0000000180029e90 | 0x00029e90
`public: void __cdecl CHStringArray::InsertAt(int,class CHStringArray * __ptr64) __ptr64` | 406 (0x196) | Exported Function | 0x0000000180029f20 | 0x00029f20
`public: void __cdecl CHStringArray::InsertAt(int,unsigned short const * __ptr64,int) __ptr64` | 407 (0x197) | Exported Function | 0x000000018002a000 | 0x0002a000
`public: void __cdecl CHStringArray::RemoveAt(int,int) __ptr64` | 482 (0x1e2) | Exported Function | 0x000000018002a0d0 | 0x0002a0d0
`public: virtual long __cdecl CWbemProviderGlue::ExecQuery(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IEnumWbemClassObject * __ptr64 * __ptr64) __ptr64` | 245 (0xf5) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::ExecNotificationQueryAsync(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 244 (0xf4) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::ExecNotificationQuery(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IEnumWbemClassObject * __ptr64 * __ptr64) __ptr64` | 243 (0xf3) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyValue(unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 306 (0x132) | Exported Function | 0x000000018002b210 | 0x0002b210
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyValue(unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 305 (0x131) | Exported Function | 0x000000018002b1c0 | 0x0002b1c0
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyValue(unsigned short const * __ptr64,void * __ptr64,unsigned long * __ptr64) __ptr64` | 307 (0x133) | Exported Function | 0x000000018002b260 | 0x0002b260
`public: unsigned long __cdecl CRegistry::GetLongestClassStringSize(void) __ptr64` | 338 (0x152) | Exported Function | 0x000000018001ecf0 | 0x0001ecf0
`public: unsigned long __cdecl CRegistry::GetLongestSubKeySize(void) __ptr64` | 339 (0x153) | Exported Function | 0x000000018001ed00 | 0x0001ed00
`public: unsigned long __cdecl CRegistry::GetLongestValueData(void) __ptr64` | 340 (0x154) | Exported Function | 0x000000018001ed10 | 0x0001ed10
`public: unsigned long __cdecl CRegistry::GetLongestValueName(void) __ptr64` | 341 (0x155) | Exported Function | 0x000000018001ed20 | 0x0001ed20
`public: unsigned long __cdecl CRegistry::GetValueCount(void) __ptr64` | 377 (0x179) | Exported Function | 0x000000018001ed30 | 0x0001ed30
`public: unsigned long __cdecl CRegistry::NextSubKey(void) __ptr64` | 446 (0x1be) | Exported Function | 0x000000018002b560 | 0x0002b560
`public: unsigned long __cdecl CRegistry::OpenCurrentUser(unsigned short const * __ptr64,unsigned long) __ptr64` | 453 (0x1c5) | Exported Function | 0x000000018002b5b0 | 0x0002b5b0
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 507 (0x1fb) | Exported Function | 0x000000018002bb30 | 0x0002bb30
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,class CHStringArray & __ptr64) __ptr64` | 508 (0x1fc) | Exported Function | 0x000000018002bbb0 | 0x0002bbb0
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 506 (0x1fa) | Exported Function | 0x000000018002bb00 | 0x0002bb00
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 510 (0x1fe) | Exported Function | 0x000000018002bdd0 | 0x0002bdd0
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(unsigned short const * __ptr64,class CHStringArray & __ptr64) __ptr64` | 511 (0x1ff) | Exported Function | 0x000000018002be30 | 0x0002be30
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyPath(class CHString & __ptr64) __ptr64` | 304 (0x130) | Exported Function | 0x000000018002b0c0 | 0x0002b0c0
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 509 (0x1fd) | Exported Function | 0x000000018002bd90 | 0x0002bd90
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyName(class CHString & __ptr64) __ptr64` | 303 (0x12f) | Exported Function | 0x000000018002b030 | 0x0002b030
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 297 (0x129) | Exported Function | 0x0000000180002c70 | 0x00002c70
`public: struct KeyRef & __ptr64 __cdecl KeyRef::operator=(struct KeyRef const & __ptr64) __ptr64` | 94 (0x5e) | Exported Function | 0x000000018001e080 | 0x0001e080
`public: struct ParsedObjectPath & __ptr64 __cdecl ParsedObjectPath::operator=(struct ParsedObjectPath const & __ptr64) __ptr64` | 96 (0x60) | Exported Function | 0x000000018001e0f0 | 0x0001e0f0
`public: unsigned __int64 __cdecl WBEMTime::GetTime(void)const __ptr64` | 372 (0x174) | Exported Function | 0x0000000180002c20 | 0x00002c20
`public: unsigned __int64 __cdecl WBEMTimeSpan::GetTime(void)const __ptr64` | 373 (0x175) | Exported Function | 0x0000000180002c20 | 0x00002c20
`public: unsigned long __cdecl CAutoEvent::Wait(unsigned long) __ptr64` | 557 (0x22d) | Exported Function | 0x0000000180027e00 | 0x00027e00
`public: unsigned long __cdecl CRegistry::DeleteCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64) __ptr64` | 221 (0xdd) | Exported Function | 0x000000018002a8f0 | 0x0002a8f0
`public: unsigned long __cdecl CRegistry::DeleteCurrentKeyValue(unsigned short const * __ptr64) __ptr64` | 222 (0xde) | Exported Function | 0x000000018002a910 | 0x0002a910
`public: unsigned long __cdecl CRegistry::GetCurrentBinaryKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 291 (0x123) | Exported Function | 0x000000018002ab90 | 0x0002ab90
`public: unsigned long __cdecl CRegistry::GetCurrentBinaryKeyValue(unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 292 (0x124) | Exported Function | 0x000000018002abd0 | 0x0002abd0
`public: unsigned long __cdecl CRegistry::GetCurrentBinaryKeyValue(unsigned short const * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 293 (0x125) | Exported Function | 0x000000018000c330 | 0x0000c330
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 295 (0x127) | Exported Function | 0x000000018000b9f0 | 0x0000b9f0
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,class CHStringArray & __ptr64) __ptr64` | 296 (0x128) | Exported Function | 0x000000018002ada0 | 0x0002ada0
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 294 (0x126) | Exported Function | 0x000000018000c270 | 0x0000c270
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 298 (0x12a) | Exported Function | 0x000000018000b9d0 | 0x0000b9d0
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(unsigned short const * __ptr64,class CHStringArray & __ptr64) __ptr64` | 299 (0x12b) | Exported Function | 0x000000018002af60 | 0x0002af60
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyCount(void) __ptr64` | 302 (0x12e) | Exported Function | 0x000000018001ece0 | 0x0001ece0
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValueExpand(struct HKEY__ * __ptr64,unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 512 (0x200) | Exported Function | 0x000000018002be50 | 0x0002be50
`public: unsigned short * __ptr64 __cdecl CFrameworkQuery::GetQueryClassName(void) __ptr64` | 361 (0x169) | Exported Function | 0x000000018001e580 | 0x0001e580
`public: unsigned short * __ptr64 __cdecl CHString::AllocSysString(void)const __ptr64` | 177 (0xb1) | Exported Function | 0x0000000180028d50 | 0x00028d50
`public: virtual long __cdecl CWbemGlueFactory::CreateInstance(struct IUnknown * __ptr64,struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 207 (0xcf) | Exported Function | 0x000000018000dc20 | 0x0000dc20
`public: virtual long __cdecl CWbemGlueFactory::LockServer(int) __ptr64` | 437 (0x1b5) | Exported Function | 0x000000018001ee20 | 0x0001ee20
`public: virtual long __cdecl CWbemGlueFactory::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 466 (0x1d2) | Exported Function | 0x000000018000ce10 | 0x0000ce10
`public: virtual long __cdecl CWbemProviderGlue::CancelAsyncCall(struct IWbemObjectSink * __ptr64) __ptr64` | 183 (0xb7) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::CancelAsyncRequest(long) __ptr64` | 184 (0xb8) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::CreateClassEnum(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IEnumWbemClassObject * __ptr64 * __ptr64) __ptr64` | 205 (0xcd) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::CreateClassEnumAsync(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 206 (0xce) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::CreateInstanceEnum(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IEnumWbemClassObject * __ptr64 * __ptr64) __ptr64` | 208 (0xd0) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::CreateInstanceEnumAsync(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 210 (0xd2) | Exported Function | 0x0000000180008530 | 0x00008530
`public: virtual long __cdecl CWbemProviderGlue::DeleteClass(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 219 (0xdb) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::DeleteClassAsync(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 220 (0xdc) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::DeleteInstance(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 223 (0xdf) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::DeleteInstanceAsync(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 226 (0xe2) | Exported Function | 0x0000000180022c40 | 0x00022c40
`public: virtual long __cdecl CWbemProviderGlue::ExecMethod(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemClassObject * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 239 (0xef) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`public: virtual long __cdecl CWbemProviderGlue::ExecMethodAsync(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemClassObject * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 242 (0xf2) | Exported Function | 0x0000000180023220 | 0x00023220
`public: virtual long __cdecl CFrameworkQueryEx::InitEx(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,class CHString & __ptr64) __ptr64` | 402 (0x192) | Exported Function | 0x000000018001f910 | 0x0001f910
`public: virtual bool __cdecl CFrameworkQueryEx::IsExtended(void) __ptr64` | 413 (0x19d) | Exported Function | 0x0000000180006530 | 0x00006530
`public: virtual __cdecl ProviderLog::~ProviderLog(void) __ptr64` | 72 (0x48) | Exported Function | 0x000000018000cc00 | 0x0000cc00
`public: virtual __cdecl Provider::~Provider(void) __ptr64` | 71 (0x47) | Exported Function | 0x0000000180007d50 | 0x00007d50
`public: unsigned short * __ptr64 __cdecl CHString::GetBuffer(int) __ptr64` | 282 (0x11a) | Exported Function | 0x000000018000bed0 | 0x0000bed0
`public: unsigned short * __ptr64 __cdecl CHString::GetBufferSetLength(int) __ptr64` | 283 (0x11b) | Exported Function | 0x000000018000be90 | 0x0000be90
`public: unsigned short * __ptr64 __cdecl CHString::LockBuffer(void) __ptr64` | 434 (0x1b2) | Exported Function | 0x00000001800290d0 | 0x000290d0
`public: unsigned short * __ptr64 __cdecl CRegistry::GetClassNameW(void) __ptr64` | 287 (0x11f) | Exported Function | 0x000000018001ecd0 | 0x0001ecd0
`public: unsigned short * __ptr64 __cdecl ParsedObjectPath::GetKeyString(void) __ptr64` | 330 (0x14a) | Exported Function | 0x0000000180026900 | 0x00026900
`public: unsigned short * __ptr64 __cdecl ParsedObjectPath::GetNamespacePart(void) __ptr64` | 348 (0x15c) | Exported Function | 0x0000000180026c60 | 0x00026c60
`public: unsigned short * __ptr64 __cdecl ParsedObjectPath::GetParentNamespacePart(void) __ptr64` | 355 (0x163) | Exported Function | 0x0000000180026de0 | 0x00026de0
`public: struct IWbemClassObject * __ptr64 __cdecl CInstance::GetClassObjectInterface(void) __ptr64` | 288 (0x120) | Exported Function | 0x0000000180010130 | 0x00010130
`public: unsigned short * __ptr64 __cdecl WBEMTime::GetBSTR(void)const __ptr64` | 280 (0x118) | Exported Function | 0x0000000180029690 | 0x00029690
`public: unsigned short * __ptr64 __cdecl WBEMTime::GetDMTFNonNtfs(void)const __ptr64` | 309 (0x135) | Exported Function | 0x00000001800297c0 | 0x000297c0
`public: unsigned short * __ptr64 __cdecl WBEMTimeSpan::GetBSTR(void)const __ptr64` | 281 (0x119) | Exported Function | 0x00000001800296a0 | 0x000296a0
`public: unsigned short __cdecl CHString::GetAt(int)const __ptr64` | 278 (0x116) | Exported Function | 0x00000001800125c0 | 0x000125c0
`public: unsigned short __cdecl CHString::operator[](int)const __ptr64` | 117 (0x75) | Exported Function | 0x00000001800125c0 | 0x000125c0
`public: virtual __cdecl CInstance::~CInstance(void) __ptr64` | 59 (0x3b) | Exported Function | 0x00000001800200b0 | 0x000200b0
`public: virtual __cdecl CThreadBase::~CThreadBase(void) __ptr64` | 63 (0x3f) | Exported Function | 0x000000018000c170 | 0x0000c170
`public: virtual __cdecl MethodContext::~MethodContext(void) __ptr64` | 69 (0x45) | Exported Function | 0x0000000180011630 | 0x00011630
`public: unsigned short * __ptr64 __cdecl WBEMTime::GetDMTF(int)const __ptr64` | 308 (0x134) | Exported Function | 0x000000018000deb0 | 0x0000deb0
`unsigned long __cdecl NormalizePath(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,class CHString & __ptr64)` | 448 (0x1c0) | Exported Function | 0x000000018000f8a0 | 0x0000f8a0
`public: class CHString const * __ptr64 __cdecl CHStringArray::GetData(void)const __ptr64` | 316 (0x13c) | Exported Function | 0x0000000180002c20 | 0x00002c20
`public: class CHString const & __ptr64 __cdecl CHString::operator=(unsigned short const * __ptr64) __ptr64` | 83 (0x53) | Exported Function | 0x000000018000b790 | 0x0000b790
`private: static void __cdecl Provider::InitComputerName(void)` | 401 (0x191) | Exported Function | 0x000000018000a2e0 | 0x0000a2e0
`private: struct IWbemClassObject * __ptr64 __cdecl Provider::GetClassObjectInterface(class MethodContext * __ptr64) __ptr64` | 289 (0x121) | Exported Function | 0x00000001800056b0 | 0x000056b0
`private: struct IWbemServices * __ptr64 __cdecl CWbemProviderGlue::InternalGetNamespaceConnection(unsigned short const * __ptr64) __ptr64` | 408 (0x198) | Exported Function | 0x0000000180006580 | 0x00006580
`private: unsigned long __cdecl CRegistry::GetCurrentRawKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,void * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 300 (0x12c) | Exported Function | 0x000000018002af80 | 0x0002af80
`private: unsigned long __cdecl CRegistry::GetCurrentRawSubKeyValue(unsigned short const * __ptr64,void * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 301 (0x12d) | Exported Function | 0x000000018002afc0 | 0x0002afc0
`private: unsigned long __cdecl CRegistry::OpenSubKey(void) __ptr64` | 456 (0x1c8) | Exported Function | 0x000000018002b6f0 | 0x0002b6f0
`private: void __cdecl CFrameworkQuery::Reset(void) __ptr64` | 484 (0x1e4) | Exported Function | 0x000000018000a850 | 0x0000a850
`private: void __cdecl CObjectPathParser::Empty(void) __ptr64` | 234 (0xea) | Exported Function | 0x00000001800115b0 | 0x000115b0
`private: void __cdecl CObjectPathParser::Zero(void) __ptr64` | 559 (0x22f) | Exported Function | 0x0000000180010bf0 | 0x00010bf0
`private: void __cdecl CRegistry::CloseSubKey(void) __ptr64` | 192 (0xc0) | Exported Function | 0x000000018002a770 | 0x0002a770
`private: void __cdecl CRegistry::PrepareToReOpen(void) __ptr64` | 459 (0x1cb) | Exported Function | 0x000000018002b780 | 0x0002b780
`private: void __cdecl CRegistry::SetDefaultValues(void) __ptr64` | 517 (0x205) | Exported Function | 0x000000018000d0a0 | 0x0000d0a0
`private: void __cdecl CRegistrySearch::CheckAndAddToList(class CRegistry * __ptr64,class CHString,class CHString,class CHPtrArray & __ptr64,class CHString,class CHString,int) __ptr64` | 185 (0xb9) | Exported Function | 0x000000018002a580 | 0x0002a580
`private: void __cdecl CThreadBase::Lock(void) __ptr64` | 433 (0x1b1) | Exported Function | 0x000000018001e5c0 | 0x0001e5c0
`private: void __cdecl CThreadBase::Unlock(void) __ptr64` | 544 (0x220) | Exported Function | 0x00000001800032f0 | 0x000032f0
`private: static void __cdecl CWinMsgEvent::WindowsDispatch(void)` | 558 (0x22e) | Exported Function | 0x0000000180027e20 | 0x00027e20
`private: void __cdecl CWbemProviderGlue::AddFlushPtr(void * __ptr64) __ptr64` | 161 (0xa1) | Exported Function | 0x0000000180005840 | 0x00005840
`private: static void __cdecl CWinMsgEvent::DestroyMsgWindow(void)` | 230 (0xe6) | Exported Function | 0x00000001800276a0 | 0x000276a0
`private: static void __cdecl CWbemProviderGlue::UnlockProviderMap(void)` | 547 (0x223) | Exported Function | 0x000000018001e660 | 0x0001e660
`private: static struct IWbemClassObject * __ptr64 __cdecl CWbemProviderGlue::GetStatusObject(class MethodContext * __ptr64,unsigned short const * __ptr64)` | 368 (0x170) | Exported Function | 0x0000000180024c30 | 0x00024c30
`private: static struct IWbemClassObject * __ptr64 __ptr64 CWbemProviderGlue::m_pStatusObject` | 574 (0x23e) | Exported Function | 0x000000018004a368 | 0x0004a368
`private: static unsigned long __cdecl CWinMsgEvent::dwThreadProc(void * __ptr64)` | 562 (0x232) | Exported Function | 0x0000000180027fa0 | 0x00027fa0
`private: static unsigned long CRegistry::s_dwPlatform` | 603 (0x25b) | Exported Function | 0x000000018004a37c | 0x0004a37c
`private: static unsigned long CWbemProviderGlue::s_dwMajorVersion` | 602 (0x25a) | Exported Function | 0x000000018004a358 | 0x0004a358
`private: static unsigned long CWbemProviderGlue::s_dwPlatform` | 604 (0x25c) | Exported Function | 0x000000018004a35c | 0x0004a35c
`private: static unsigned short * CWbemProviderGlue::s_wstrCSDVersion` | 610 (0x262) | Exported Function | 0x000000018004a150 | 0x0004a150
`private: static void * __ptr64 __ptr64 CWinMsgEvent::mg_hDevNotify` | 578 (0x242) | Exported Function | 0x000000018004a708 | 0x0004a708
`private: static void * __ptr64 __ptr64 CWinMsgEvent::mg_hThreadPumpHandle` | 579 (0x243) | Exported Function | 0x000000018004a718 | 0x0004a718
`private: static void __cdecl CWbemProviderGlue::GetComputerNameW(class CHString & __ptr64)` | 290 (0x122) | Exported Function | 0x000000018000eee0 | 0x0000eee0
`private: static void __cdecl CWbemProviderGlue::Init(void)` | 400 (0x190) | Exported Function | 0x0000000180004110 | 0x00004110
`private: static void __cdecl CWbemProviderGlue::LockFactoryMap(void)` | 435 (0x1b3) | Exported Function | 0x000000018001e5e0 | 0x0001e5e0
`private: static void __cdecl CWbemProviderGlue::LockProviderMap(void)` | 436 (0x1b4) | Exported Function | 0x000000018001e600 | 0x0001e600
`private: static void __cdecl CWbemProviderGlue::UnInit(void)` | 541 (0x21d) | Exported Function | 0x000000018000cc60 | 0x0000cc60
`private: static void __cdecl CWbemProviderGlue::UnlockFactoryMap(void)` | 546 (0x222) | Exported Function | 0x000000018001e640 | 0x0001e640
`private: static void __cdecl CWinMsgEvent::CreateMsgProvider(void)` | 211 (0xd3) | Exported Function | 0x0000000180027480 | 0x00027480
`private: static struct HWND__ * __ptr64 __ptr64 CWinMsgEvent::mg_hWnd` | 580 (0x244) | Exported Function | 0x000000018004a710 | 0x0004a710
`private: void __cdecl CWbemProviderGlue::FlushAll(void) __ptr64` | 255 (0xff) | Exported Function | 0x000000018000d4f0 | 0x0000d4f0
`protected: bool __cdecl CWinMsgEvent::UnRegisterMessage(unsigned int,int) __ptr64` | 543 (0x21f) | Exported Function | 0x0000000180027ca0 | 0x00027ca0
`protected: static void __cdecl CWbemProviderGlue::RemoveFromFactoryMap(class CWbemGlueFactory const * __ptr64)` | 483 (0x1e3) | Exported Function | 0x000000018000d350 | 0x0000d350
`protected: struct CHStringData * __ptr64 __cdecl CHString::GetData(void)const __ptr64` | 314 (0x13a) | Exported Function | 0x000000018000b360 | 0x0000b360
`protected: unsigned long __cdecl CFrameworkQuery::IsInList(class CHStringArray const & __ptr64,unsigned short const * __ptr64) __ptr64` | 414 (0x19e) | Exported Function | 0x000000018000a410 | 0x0000a410
`protected: virtual long __cdecl Provider::DeleteInstance(class CInstance const & __ptr64,long) __ptr64` | 225 (0xe1) | Exported Function | 0x0000000180004000 | 0x00004000
`protected: virtual long __cdecl Provider::EnumerateInstances(class MethodContext * __ptr64,long) __ptr64` | 238 (0xee) | Exported Function | 0x0000000180004000 | 0x00004000
`protected: virtual long __cdecl Provider::ExecMethod(class CInstance const & __ptr64,unsigned short * __ptr64 const,class CInstance * __ptr64,class CInstance * __ptr64,long) __ptr64` | 241 (0xf1) | Exported Function | 0x0000000180004000 | 0x00004000
`protected: virtual long __cdecl Provider::ExecQuery(class MethodContext * __ptr64,class CFrameworkQuery & __ptr64,long) __ptr64` | 246 (0xf6) | Exported Function | 0x0000000180004000 | 0x00004000
`protected: virtual long __cdecl Provider::GetObject(class CInstance * __ptr64,long) __ptr64` | 352 (0x160) | Exported Function | 0x0000000180004000 | 0x00004000
`protected: virtual long __cdecl Provider::GetObject(class CInstance * __ptr64,long,class CFrameworkQuery & __ptr64) __ptr64` | 353 (0x161) | Exported Function | 0x0000000180012520 | 0x00012520
`protected: virtual long __cdecl Provider::PutInstance(class CInstance const & __ptr64,long) __ptr64` | 464 (0x1d0) | Exported Function | 0x0000000180004000 | 0x00004000
`protected: virtual long __cdecl Provider::ValidateDeletionFlags(long) __ptr64` | 549 (0x225) | Exported Function | 0x0000000180022220 | 0x00022220
`protected: virtual long __cdecl Provider::ValidateEnumerationFlags(long) __ptr64` | 550 (0x226) | Exported Function | 0x0000000180002ea0 | 0x00002ea0
`protected: virtual long __cdecl Provider::ValidateGetObjFlags(long) __ptr64` | 552 (0x228) | Exported Function | 0x0000000180002ea0 | 0x00002ea0
`protected: virtual long __cdecl Provider::ValidateMethodFlags(long) __ptr64` | 554 (0x22a) | Exported Function | 0x0000000180022220 | 0x00022220
`protected: virtual long __cdecl Provider::ValidatePutInstanceFlags(long) __ptr64` | 555 (0x22b) | Exported Function | 0x0000000180022270 | 0x00022270
`protected: static void __cdecl CWbemProviderGlue::AddToFactoryMap(class CWbemGlueFactory const * __ptr64,long * __ptr64)` | 172 (0xac) | Exported Function | 0x000000018000d7a0 | 0x0000d7a0
`private: void __cdecl ProviderLog::CheckFileSize(union _LARGE_INTEGER & __ptr64,class CHString const & __ptr64) __ptr64` | 186 (0xba) | Exported Function | 0x000000018001ec20 | 0x0001ec20
`protected: static long __cdecl CWbemProviderGlue::IncrementMapCount(long * __ptr64)` | 393 (0x189) | Exported Function | 0x0000000180024dd0 | 0x00024dd0
`protected: static long __cdecl CWbemProviderGlue::DecrementMapCount(long * __ptr64)` | 216 (0xd8) | Exported Function | 0x000000018000dbb0 | 0x0000dbb0
`protected: bool __cdecl Provider::GetLocalInstancePath(class CInstance const * __ptr64,class CHString & __ptr64) __ptr64` | 333 (0x14d) | Exported Function | 0x0000000180011bb0 | 0x00011bb0
`protected: bool __cdecl Provider::SetCreationClassName(class CInstance * __ptr64) __ptr64` | 505 (0x1f9) | Exported Function | 0x0000000180002010 | 0x00002010
`protected: class CHString __cdecl Provider::MakeLocalPath(class CHString const & __ptr64) __ptr64` | 439 (0x1b7) | Exported Function | 0x0000000180001510 | 0x00001510
`protected: class CHString const & __ptr64 __cdecl CFrameworkQuery::GetNamespace(void) __ptr64` | 344 (0x158) | Exported Function | 0x000000018001ef80 | 0x0001ef80
`protected: class CHString const & __ptr64 __cdecl Provider::GetLocalComputerName(void) __ptr64` | 332 (0x14c) | Exported Function | 0x00000001800030a0 | 0x000030a0
`protected: class CHString const & __ptr64 __cdecl Provider::GetNamespace(void) __ptr64` | 345 (0x159) | Exported Function | 0x0000000180003fa0 | 0x00003fa0
`protected: class CHString const & __ptr64 __cdecl Provider::GetProviderName(void) __ptr64` | 359 (0x167) | Exported Function | 0x000000018001e570 | 0x0001e570
`protected: class CInstance * __ptr64 __cdecl Provider::CreateNewInstance(class MethodContext * __ptr64) __ptr64` | 213 (0xd5) | Exported Function | 0x0000000180004620 | 0x00004620
`protected: int __cdecl CFrameworkQuery::IsReference(unsigned short const * __ptr64) __ptr64` | 424 (0x1a8) | Exported Function | 0x000000018000ed10 | 0x0000ed10
`protected: int __cdecl CHString::LoadStringW(unsigned int,unsigned short * __ptr64,unsigned int) __ptr64` | 428 (0x1ac) | Exported Function | 0x00000001800290c0 | 0x000290c0
`protected: long __cdecl Provider::Commit(class CInstance * __ptr64,bool) __ptr64` | 195 (0xc3) | Exported Function | 0x0000000180021f30 | 0x00021f30
`protected: long __cdecl Provider::ValidateFlags(long,enum Provider::FlagDefs) __ptr64` | 551 (0x227) | Exported Function | 0x0000000180022240 | 0x00022240
`protected: static int __cdecl CHString::SafeStrlen(unsigned short const * __ptr64)` | 488 (0x1e8) | Exported Function | 0x000000018000a690 | 0x0000a690
`protected: static long * __ptr64 __cdecl CWbemProviderGlue::GetMapCountPtr(class CWbemGlueFactory const * __ptr64)` | 342 (0x156) | Exported Function | 0x000000018000d720 | 0x0000d720
`protected: static long __cdecl CWbemProviderGlue::DecrementMapCount(class CWbemGlueFactory const * __ptr64)` | 217 (0xd9) | Exported Function | 0x000000018000d460 | 0x0000d460
`protected: static long __cdecl CWbemProviderGlue::IncrementMapCount(class CWbemGlueFactory const * __ptr64)` | 394 (0x18a) | Exported Function | 0x000000018000d3d0 | 0x0000d3d0
`private: static struct HWND__ * __ptr64 __cdecl CWinMsgEvent::CreateMsgWindow(void)` | 212 (0xd4) | Exported Function | 0x0000000180027550 | 0x00027550
`private: static long CWbemProviderGlue::s_lObjects` | 607 (0x25f) | Exported Function | 0x000000018004a704 | 0x0004a704
`private: static long __cdecl CWbemProviderGlue::GetInstanceFromCIMOM(unsigned short const * __ptr64,unsigned short const * __ptr64,class MethodContext * __ptr64,class CInstance * __ptr64 * __ptr64)` | 325 (0x145) | Exported Function | 0x000000018000fd80 | 0x0000fd80
`private: int __cdecl CObjectPathParser::ident_becomes_ns(void) __ptr64` | 564 (0x234) | Exported Function | 0x0000000180027110 | 0x00027110
`private: int __cdecl CObjectPathParser::key_const(void) __ptr64` | 567 (0x237) | Exported Function | 0x0000000180011320 | 0x00011320
`private: int __cdecl CObjectPathParser::keyref(void) __ptr64` | 568 (0x238) | Exported Function | 0x00000001800111c0 | 0x000111c0
`private: int __cdecl CObjectPathParser::keyref_list(void) __ptr64` | 569 (0x239) | Exported Function | 0x0000000180012580 | 0x00012580
`private: int __cdecl CObjectPathParser::keyref_term(void) __ptr64` | 570 (0x23a) | Exported Function | 0x0000000180011180 | 0x00011180
`private: int __cdecl CObjectPathParser::NextToken(void) __ptr64` | 447 (0x1bf) | Exported Function | 0x0000000180011440 | 0x00011440
`private: int __cdecl CObjectPathParser::ns_list(void) __ptr64` | 591 (0x24f) | Exported Function | 0x0000000180010c70 | 0x00010c70
`private: int __cdecl CObjectPathParser::ns_list_rest(void) __ptr64` | 592 (0x250) | Exported Function | 0x0000000180010cc0 | 0x00010cc0
`private: int __cdecl CObjectPathParser::ns_or_class(void) __ptr64` | 593 (0x251) | Exported Function | 0x0000000180010d00 | 0x00010d00
`private: int __cdecl CObjectPathParser::ns_or_server(void) __ptr64` | 594 (0x252) | Exported Function | 0x000000018000edf0 | 0x0000edf0
`private: int __cdecl CObjectPathParser::objref(void) __ptr64` | 595 (0x253) | Exported Function | 0x000000018000ee90 | 0x0000ee90
`private: int __cdecl CObjectPathParser::objref_rest(void) __ptr64` | 596 (0x254) | Exported Function | 0x0000000180011110 | 0x00011110
`private: int __cdecl CObjectPathParser::optional_objref(void) __ptr64` | 597 (0x255) | Exported Function | 0x000000018000ee40 | 0x0000ee40
`private: int __cdecl CObjectPathParser::propname(void) __ptr64` | 598 (0x256) | Exported Function | 0x00000001800112d0 | 0x000112d0
`private: int __cdecl Provider::SetKeyFromParsedObjectPath(class CInstance * __ptr64,struct ParsedObjectPath * __ptr64) __ptr64` | 519 (0x207) | Exported Function | 0x0000000180010160 | 0x00010160
`private: int __cdecl CObjectPathParser::ident_becomes_class(void) __ptr64` | 563 (0x233) | Exported Function | 0x0000000180010d40 | 0x00010d40
`private: int __cdecl Provider::ValidateIMOSPointer(void) __ptr64` | 553 (0x229) | Exported Function | 0x0000000180022260 | 0x00022260
`private: int __cdecl CObjectPathParser::begin_parse(void) __ptr64` | 560 (0x230) | Exported Function | 0x00000001800113c0 | 0x000113c0
`DoCmd` | 611 (0x263) | Exported Function | 0x0000000180022290 | 0x00022290
`class CHString __cdecl operator+(class CHString const & __ptr64,unsigned short const * __ptr64)` | 126 (0x7e) | Exported Function | 0x0000000180028b60 | 0x00028b60
`class CHString __cdecl operator+(class CHString const & __ptr64,unsigned short)` | 125 (0x7d) | Exported Function | 0x00000001800122a0 | 0x000122a0
`class CHString __cdecl operator+(unsigned short const * __ptr64,class CHString const & __ptr64)` | 128 (0x80) | Exported Function | 0x000000018000b4d0 | 0x0000b4d0
`class CHString __cdecl operator+(unsigned short,class CHString const & __ptr64)` | 127 (0x7f) | Exported Function | 0x0000000180028c10 | 0x00028c10
`class ProviderLog captainsLog` | 561 (0x231) | Exported Function | 0x000000018004a6a0 | 0x0004a6a0
`const CFrameworkQueryEx::``vftable'` | 147 (0x93) | Exported Function | 0x000000018002d020 | 0x0002d020
`const CInstance::``vftable'` | 148 (0x94) | Exported Function | 0x000000018002d008 | 0x0002d008
`const CThreadBase::``vftable'` | 149 (0x95) | Exported Function | 0x000000018002d068 | 0x0002d068
`const CWbemGlueFactory::``vftable'` | 150 (0x96) | Exported Function | 0x000000018002d288 | 0x0002d288
`const CWbemProviderGlue::``vftable'{for ``IWbemProviderInit'}` | 151 (0x97) | Exported Function | 0x000000018002d168 | 0x0002d168
`const CWbemProviderGlue::``vftable'{for ``IWbemServices'}` | 152 (0x98) | Exported Function | 0x000000018002d190 | 0x0002d190
`const CWinMsgEvent::``vftable'` | 153 (0x99) | Exported Function | 0x000000018002df20 | 0x0002df20
`const MethodContext::``vftable'` | 154 (0x9a) | Exported Function | 0x000000018002d080 | 0x0002d080
`const Provider::``vftable'` | 155 (0x9b) | Exported Function | 0x000000018002d0b0 | 0x0002d0b0
`const ProviderLog::``vftable'` | 156 (0x9c) | Exported Function | 0x000000018002d270 | 0x0002d270
`private: class CWbemProviderGlue * __ptr64 __cdecl MethodContext::GetProviderGlue(void) __ptr64` | 358 (0x166) | Exported Function | 0x0000000180021e50 | 0x00021e50
`private: long __cdecl CRegistry::myRegCreateKeyEx(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES * __ptr64 const,struct HKEY__ * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 582 (0x246) | Exported Function | 0x000000018002bed0 | 0x0002bed0
`private: long __cdecl CRegistry::myRegDeleteKey(struct HKEY__ * __ptr64,unsigned short const * __ptr64) __ptr64` | 583 (0x247) | Exported Function | 0x000000018002bf50 | 0x0002bf50
`private: long __cdecl CRegistry::myRegDeleteValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64) __ptr64` | 584 (0x248) | Exported Function | 0x000000018002a8f0 | 0x0002a8f0
`private: static class CCritSec CWinMsgEvent::mg_csMapLock` | 576 (0x240) | Exported Function | 0x000000018004a628 | 0x0004a628
`private: static class CCritSec CWinMsgEvent::mg_csWindowLock` | 577 (0x241) | Exported Function | 0x000000018004a650 | 0x0004a650
`private: static class CHString Provider::s_strComputerName` | 609 (0x261) | Exported Function | 0x000000018004a520 | 0x0004a520
`private: static class Provider * __ptr64 __cdecl CWbemProviderGlue::AddProviderToMap(unsigned short const * __ptr64,unsigned short const * __ptr64,class Provider * __ptr64)` | 166 (0xa6) | Exported Function | 0x0000000180022ab0 | 0x00022ab0
`private: static class Provider * __ptr64 __cdecl CWbemProviderGlue::SearchMapForProvider(unsigned short const * __ptr64,unsigned short const * __ptr64)` | 490 (0x1ea) | Exported Function | 0x00000001800076f0 | 0x000076f0
`private: static class std::map<class CHString,void * __ptr64,struct std::less<class CHString>,class std::allocator<struct std::pair<class CHString const ,void * __ptr64> > > CWbemProviderGlue::s_providersmap` | 608 (0x260) | Exported Function | 0x000000018004a528 | 0x0004a528
`private: static class std::map<void const * __ptr64,long * __ptr64,struct std::less<void const * __ptr64>,class std::allocator<struct std::pair<void const * __ptr64 const,long * __ptr64> > > CWbemProviderGlue::s_factorymap` | 606 (0x25e) | Exported Function | 0x000000018004a560 | 0x0004a560
`private: static class std::multimap<unsigned int,class CWinMsgEvent * __ptr64,struct std::less<unsigned int>,class std::allocator<struct std::pair<unsigned int const ,class CWinMsgEvent * __ptr64> > > CWinMsgEvent::mg_oSinkMap` | 581 (0x245) | Exported Function | 0x000000018004a680 | 0x0004a680
`private: static class std::set<void * __ptr64,struct std::less<void * __ptr64>,class std::allocator<void * __ptr64> > CWbemProviderGlue::m_FlushPtrs` | 571 (0x23b) | Exported Function | 0x000000018004a5c0 | 0x0004a5c0
`private: static int __cdecl CRegistry::SetPlatformID(void)` | 521 (0x209) | Exported Function | 0x000000018000cae0 | 0x0000cae0
`private: static int __cdecl CWinMsgEvent::CtrlHandlerRoutine(unsigned long)` | 215 (0xd7) | Exported Function | 0x0000000180027660 | 0x00027660
`private: static int CRegistry::s_fPlatformSet` | 605 (0x25d) | Exported Function | 0x000000018004a378 | 0x0004a378
`private: static int CWbemProviderGlue::s_bInitted` | 599 (0x257) | Exported Function | 0x000000018004a360 | 0x0004a360
`private: static int Provider::initFailed_` | 566 (0x236) | Exported Function | 0x000000018004a6f8 | 0x0004a6f8
`private: static long __cdecl CWbemProviderGlue::CheckImpersonationLevel(void)` | 187 (0xbb) | Exported Function | 0x0000000180008310 | 0x00008310
`private: static class CCritSec CWbemProviderGlue::s_csProviderMap` | 601 (0x259) | Exported Function | 0x000000018004a570 | 0x0004a570
`private: static class CCritSec CWbemProviderGlue::s_csFactoryMap` | 600 (0x258) | Exported Function | 0x000000018004a538 | 0x0004a538
`private: static class CCritSec CWbemProviderGlue::m_csStatusObject` | 573 (0x23d) | Exported Function | 0x000000018004a598 | 0x0004a598
`private: static class CCritSec CWbemProviderGlue::m_csFlushPtrs` | 572 (0x23c) | Exported Function | 0x000000018004a5d0 | 0x0004a5d0
`private: long __cdecl CRegistry::myRegEnumKey(struct HKEY__ * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long) __ptr64` | 585 (0x249) | Exported Function | 0x000000018002bf80 | 0x0002bf80
`private: long __cdecl CRegistry::myRegEnumValue(struct HKEY__ * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 586 (0x24a) | Exported Function | 0x000000018002bfd0 | 0x0002bfd0
`private: long __cdecl CRegistry::myRegOpenKeyEx(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,struct HKEY__ * __ptr64 * __ptr64) __ptr64` | 587 (0x24b) | Exported Function | 0x000000018002c040 | 0x0002c040
`private: long __cdecl CRegistry::myRegQueryInfoKey(struct HKEY__ * __ptr64,unsigned short * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,struct _FILETIME * __ptr64) __ptr64` | 588 (0x24c) | Exported Function | 0x000000018002c080 | 0x0002c080
`private: long __cdecl CRegistry::myRegQueryValueEx(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 589 (0x24d) | Exported Function | 0x000000018000c370 | 0x0000c370
`private: long __cdecl CRegistry::myRegSetValueEx(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,unsigned char const * __ptr64,unsigned long) __ptr64` | 590 (0x24e) | Exported Function | 0x000000018002c120 | 0x0002c120
`private: long __cdecl CWbemProviderGlue::NullOutUnsetProperties(struct IWbemClassObject * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64,struct tagVARIANT const & __ptr64) __ptr64` | 449 (0x1c1) | Exported Function | 0x0000000180024e50 | 0x00024e50
`protected: virtual long __cdecl Provider::ValidateQueryFlags(long) __ptr64` | 556 (0x22c) | Exported Function | 0x0000000180002ea0 | 0x00002ea0
`private: long __cdecl CWbemProviderGlue::PreProcessPutInstanceParms(struct IWbemClassObject * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64,struct IWbemContext * __ptr64) __ptr64` | 458 (0x1ca) | Exported Function | 0x0000000180025260 | 0x00025260
`private: long __cdecl Provider::DeleteInstance(struct ParsedObjectPath * __ptr64,long,class MethodContext * __ptr64) __ptr64` | 224 (0xe0) | Exported Function | 0x0000000180021f70 | 0x00021f70
`private: long __cdecl Provider::ExecMethod(struct ParsedObjectPath * __ptr64,unsigned short * __ptr64,long,class CInstance * __ptr64,class CInstance * __ptr64,class MethodContext * __ptr64) __ptr64` | 240 (0xf0) | Exported Function | 0x0000000180022040 | 0x00022040
`private: long __cdecl Provider::ExecuteQuery(class MethodContext * __ptr64,class CFrameworkQuery & __ptr64,long) __ptr64` | 248 (0xf8) | Exported Function | 0x00000001800058c0 | 0x000058c0
`private: long __cdecl Provider::GetObject(struct ParsedObjectPath * __ptr64,class MethodContext * __ptr64,long) __ptr64` | 351 (0x15f) | Exported Function | 0x000000018000ffc0 | 0x0000ffc0
`private: long __cdecl Provider::PutInstance(struct IWbemClassObject * __ptr64,long,class MethodContext * __ptr64) __ptr64` | 463 (0x1cf) | Exported Function | 0x0000000180022130 | 0x00022130
`private: static __int64 __cdecl CWinMsgEvent::MsgWndProc(struct HWND__ * __ptr64,unsigned int,unsigned __int64,__int64)` | 445 (0x1bd) | Exported Function | 0x0000000180027760 | 0x00027760
`private: static class CAutoEvent CWinMsgEvent::mg_aeCreateWindow` | 575 (0x23f) | Exported Function | 0x000000018004a678 | 0x0004a678
`private: long __cdecl Provider::CreateInstanceEnum(class MethodContext * __ptr64,long) __ptr64` | 209 (0xd1) | Exported Function | 0x0000000180004020 | 0x00004020
`public: class CHString const & __ptr64 __cdecl CHString::operator=(unsigned short) __ptr64` | 79 (0x4f) | Exported Function | 0x0000000180028b30 | 0x00028b30
`protected: virtual void __cdecl CThreadBase::OnFinalRelease(void) __ptr64` | 450 (0x1c2) | Exported Function | 0x0000000180002ec0 | 0x00002ec0
`protected: void __cdecl CHString::AllocBeforeWrite(int) __ptr64` | 174 (0xae) | Exported Function | 0x0000000180028d00 | 0x00028d00
`public: bool __cdecl CInstance::GetWCHAR(unsigned short const * __ptr64,unsigned short * __ptr64 * __ptr64)const __ptr64` | 387 (0x183) | Exported Function | 0x0000000180020f30 | 0x00020f30
`public: bool __cdecl CInstance::GetWORD(unsigned short const * __ptr64,unsigned short & __ptr64)const __ptr64` | 388 (0x184) | Exported Function | 0x0000000180021130 | 0x00021130
`public: bool __cdecl CInstance::IsNull(unsigned short const * __ptr64)const __ptr64` | 419 (0x1a3) | Exported Function | 0x0000000180002890 | 0x00002890
`public: bool __cdecl CInstance::Setbool(unsigned short const * __ptr64,bool) __ptr64` | 535 (0x217) | Exported Function | 0x0000000180001e10 | 0x00001e10
`public: bool __cdecl CInstance::SetByte(unsigned short const * __ptr64,unsigned char) __ptr64` | 496 (0x1f0) | Exported Function | 0x0000000180001f40 | 0x00001f40
`public: bool __cdecl CInstance::SetCharSplat(unsigned short const * __ptr64,char const * __ptr64) __ptr64` | 503 (0x1f7) | Exported Function | 0x0000000180021710 | 0x00021710
`public: bool __cdecl CInstance::SetCharSplat(unsigned short const * __ptr64,unsigned long) __ptr64` | 502 (0x1f6) | Exported Function | 0x00000001800216e0 | 0x000216e0
`public: bool __cdecl CInstance::SetCharSplat(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 501 (0x1f5) | Exported Function | 0x0000000180001c80 | 0x00001c80
`public: bool __cdecl CInstance::SetCHString(unsigned short const * __ptr64,char const * __ptr64) __ptr64` | 499 (0x1f3) | Exported Function | 0x0000000180012370 | 0x00012370
`public: bool __cdecl CInstance::SetCHString(unsigned short const * __ptr64,class CHString const & __ptr64) __ptr64` | 498 (0x1f2) | Exported Function | 0x0000000180001b90 | 0x00001b90
`public: bool __cdecl CInstance::SetCHString(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 497 (0x1f1) | Exported Function | 0x0000000180001c80 | 0x00001c80
`public: bool __cdecl CInstance::SetDateTime(unsigned short const * __ptr64,class WBEMTime const & __ptr64) __ptr64` | 516 (0x204) | Exported Function | 0x000000018000dff0 | 0x0000dff0
`public: bool __cdecl CInstance::SetDOUBLE(unsigned short const * __ptr64,double) __ptr64` | 514 (0x202) | Exported Function | 0x0000000180021780 | 0x00021780
`public: bool __cdecl CInstance::SetDWORD(unsigned short const * __ptr64,unsigned long) __ptr64` | 515 (0x203) | Exported Function | 0x0000000180001440 | 0x00001440
`public: bool __cdecl CInstance::SetEmbeddedObject(unsigned short const * __ptr64,class CInstance & __ptr64) __ptr64` | 518 (0x206) | Exported Function | 0x00000001800218a0 | 0x000218a0
`public: bool __cdecl CInstance::GetWBEMINT64(unsigned short const * __ptr64,unsigned __int64 & __ptr64)const __ptr64` | 386 (0x182) | Exported Function | 0x00000001800121a0 | 0x000121a0
`public: bool __cdecl CInstance::SetNull(unsigned short const * __ptr64) __ptr64` | 520 (0x208) | Exported Function | 0x0000000180021a20 | 0x00021a20
`public: bool __cdecl CInstance::GetWBEMINT64(unsigned short const * __ptr64,class CHString & __ptr64)const __ptr64` | 384 (0x180) | Exported Function | 0x0000000180020eb0 | 0x00020eb0
`public: bool __cdecl CInstance::GetWBEMINT16(unsigned short const * __ptr64,short & __ptr64)const __ptr64` | 383 (0x17f) | Exported Function | 0x0000000180020d00 | 0x00020d00
`public: __cdecl WBEMTimeSpan::WBEMTimeSpan(void) __ptr64` | 52 (0x34) | Exported Function | 0x000000018001de00 | 0x0001de00
`public: bool __cdecl CFrameworkQuery::AllPropertiesAreRequired(void) __ptr64` | 173 (0xad) | Exported Function | 0x0000000180006ea0 | 0x00006ea0
`public: bool __cdecl CFrameworkQuery::IsPropertyRequired(unsigned short const * __ptr64) __ptr64` | 423 (0x1a7) | Exported Function | 0x0000000180012000 | 0x00012000
`public: bool __cdecl CFrameworkQuery::KeysOnly(void) __ptr64` | 426 (0x1aa) | Exported Function | 0x0000000180003ed0 | 0x00003ed0
`public: bool __cdecl CInstance::Getbool(unsigned short const * __ptr64,bool & __ptr64)const __ptr64` | 389 (0x185) | Exported Function | 0x00000001800212d0 | 0x000212d0
`public: bool __cdecl CInstance::GetByte(unsigned short const * __ptr64,unsigned char & __ptr64)const __ptr64` | 284 (0x11c) | Exported Function | 0x0000000180020100 | 0x00020100
`public: bool __cdecl CInstance::GetCHString(unsigned short const * __ptr64,class CHString & __ptr64)const __ptr64` | 285 (0x11d) | Exported Function | 0x0000000180002500 | 0x00002500
`public: bool __cdecl CInstance::GetDateTime(unsigned short const * __ptr64,class WBEMTime & __ptr64)const __ptr64` | 317 (0x13d) | Exported Function | 0x0000000180020440 | 0x00020440
`public: bool __cdecl CInstance::GetDOUBLE(unsigned short const * __ptr64,double & __ptr64)const __ptr64` | 310 (0x136) | Exported Function | 0x00000001800202a0 | 0x000202a0
`public: bool __cdecl CInstance::GetDWORD(unsigned short const * __ptr64,unsigned long & __ptr64)const __ptr64` | 311 (0x137) | Exported Function | 0x0000000180012080 | 0x00012080
`public: bool __cdecl CInstance::GetEmbeddedObject(unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,class MethodContext * __ptr64)const __ptr64` | 318 (0x13e) | Exported Function | 0x0000000180020600 | 0x00020600
`public: bool __cdecl CInstance::GetStatus(unsigned short const * __ptr64,bool & __ptr64,unsigned short & __ptr64)const __ptr64` | 367 (0x16f) | Exported Function | 0x0000000180020840 | 0x00020840
`public: bool __cdecl CInstance::GetStringArray(unsigned short const * __ptr64,struct tagSAFEARRAY * __ptr64 & __ptr64)const __ptr64` | 370 (0x172) | Exported Function | 0x0000000180020970 | 0x00020970
`public: bool __cdecl CInstance::GetTimeSpan(unsigned short const * __ptr64,class WBEMTimeSpan & __ptr64)const __ptr64` | 374 (0x176) | Exported Function | 0x0000000180020b40 | 0x00020b40
`public: bool __cdecl CInstance::GetVariant(unsigned short const * __ptr64,struct tagVARIANT & __ptr64)const __ptr64` | 382 (0x17e) | Exported Function | 0x00000001800123f0 | 0x000123f0
`public: bool __cdecl CInstance::GetWBEMINT64(unsigned short const * __ptr64,__int64 & __ptr64)const __ptr64` | 385 (0x181) | Exported Function | 0x0000000180020ec0 | 0x00020ec0
`public: __cdecl WBEMTimeSpan::WBEMTimeSpan(unsigned short * __ptr64 const) __ptr64` | 51 (0x33) | Exported Function | 0x000000018001de10 | 0x0001de10
`public: bool __cdecl CInstance::SetStringArray(unsigned short const * __ptr64,struct tagSAFEARRAY const & __ptr64) __ptr64` | 526 (0x20e) | Exported Function | 0x0000000180002b30 | 0x00002b30
`public: bool __cdecl CInstance::SetVariant(unsigned short const * __ptr64,struct tagVARIANT const & __ptr64) __ptr64` | 528 (0x210) | Exported Function | 0x0000000180002aa0 | 0x00002aa0
`public: class CHString __cdecl CHString::Right(int)const __ptr64` | 487 (0x1e7) | Exported Function | 0x000000018000ad60 | 0x0000ad60
`public: class CHString __cdecl CHString::SpanExcluding(unsigned short const * __ptr64)const __ptr64` | 537 (0x219) | Exported Function | 0x0000000180012320 | 0x00012320
`public: class CHString __cdecl CHString::SpanIncluding(unsigned short const * __ptr64)const __ptr64` | 538 (0x21a) | Exported Function | 0x0000000180029170 | 0x00029170
`public: class CHString __cdecl CHStringArray::GetAt(int)const __ptr64` | 279 (0x117) | Exported Function | 0x0000000180002800 | 0x00002800
`public: class CHString __cdecl CHStringArray::operator[](int)const __ptr64` | 119 (0x77) | Exported Function | 0x0000000180002800 | 0x00002800
`public: class CHString const & __ptr64 __cdecl CFrameworkQuery::GetQuery(void) __ptr64` | 360 (0x168) | Exported Function | 0x000000018001ef90 | 0x0001ef90
`public: class CHString const & __ptr64 __cdecl CHString::operator+=(char) __ptr64` | 140 (0x8c) | Exported Function | 0x000000018000b030 | 0x0000b030
`public: class CHString const & __ptr64 __cdecl CHString::operator+=(class CHString const & __ptr64) __ptr64` | 139 (0x8b) | Exported Function | 0x000000018000b1d0 | 0x0000b1d0
`public: class CHString const & __ptr64 __cdecl CHString::operator+=(unsigned short const * __ptr64) __ptr64` | 142 (0x8e) | Exported Function | 0x000000018000ae90 | 0x0000ae90
`public: class CHString const & __ptr64 __cdecl CHString::operator+=(unsigned short) __ptr64` | 141 (0x8d) | Exported Function | 0x000000018000b110 | 0x0000b110
`public: class CHString const & __ptr64 __cdecl CHString::operator=(char const * __ptr64) __ptr64` | 81 (0x51) | Exported Function | 0x000000018000ceb0 | 0x0000ceb0
`public: class CHString const & __ptr64 __cdecl CHString::operator=(char) __ptr64` | 78 (0x4e) | Exported Function | 0x000000018001df00 | 0x0001df00
`public: class CHString const & __ptr64 __cdecl CHString::operator=(class CHString * __ptr64) __ptr64` | 80 (0x50) | Exported Function | 0x000000018001df30 | 0x0001df30
`public: class CHString const & __ptr64 __cdecl CHString::operator=(class CHString const & __ptr64) __ptr64` | 77 (0x4d) | Exported Function | 0x0000000180005a90 | 0x00005a90
`public: class CHString const & __ptr64 __cdecl CHString::operator=(unsigned char const * __ptr64) __ptr64` | 82 (0x52) | Exported Function | 0x000000018001df50 | 0x0001df50
`public: class CHString __cdecl CHString::Mid(int,int)const __ptr64` | 444 (0x1bc) | Exported Function | 0x000000018000abe0 | 0x0000abe0
`public: bool __cdecl CInstance::SetTimeSpan(unsigned short const * __ptr64,class WBEMTimeSpan const & __ptr64) __ptr64` | 527 (0x20f) | Exported Function | 0x0000000180021b70 | 0x00021b70
`public: class CHString __cdecl CHString::Mid(int)const __ptr64` | 443 (0x1bb) | Exported Function | 0x000000018000ad20 | 0x0000ad20
`public: class CHString * __ptr64 __cdecl CHStringArray::GetData(void) __ptr64` | 315 (0x13b) | Exported Function | 0x0000000180002c20 | 0x00002c20
`public: bool __cdecl CInstance::SetWBEMINT16(unsigned short const * __ptr64,short const & __ptr64) __ptr64` | 529 (0x211) | Exported Function | 0x0000000180002730 | 0x00002730
`public: bool __cdecl CInstance::SetWBEMINT64(unsigned short const * __ptr64,__int64) __ptr64` | 531 (0x213) | Exported Function | 0x0000000180002970 | 0x00002970
`public: bool __cdecl CInstance::SetWBEMINT64(unsigned short const * __ptr64,class CHString const & __ptr64) __ptr64` | 530 (0x212) | Exported Function | 0x0000000180021cd0 | 0x00021cd0
`public: bool __cdecl CInstance::SetWBEMINT64(unsigned short const * __ptr64,unsigned __int64) __ptr64` | 532 (0x214) | Exported Function | 0x0000000180001310 | 0x00001310
`public: bool __cdecl CInstance::SetWCHARSplat(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 533 (0x215) | Exported Function | 0x0000000180001ab0 | 0x00001ab0
`public: bool __cdecl CInstance::SetWORD(unsigned short const * __ptr64,unsigned short) __ptr64` | 534 (0x216) | Exported Function | 0x0000000180003b60 | 0x00003b60
`public: bool __cdecl MethodContext::SetStatusObject(struct IWbemClassObject * __ptr64) __ptr64` | 525 (0x20d) | Exported Function | 0x0000000180021e70 | 0x00021e70
`public: bool __cdecl WBEMTime::IsOk(void)const __ptr64` | 421 (0x1a5) | Exported Function | 0x000000018001e5b0 | 0x0001e5b0
`public: bool __cdecl WBEMTimeSpan::IsOk(void)const __ptr64` | 422 (0x1a6) | Exported Function | 0x000000018001e5b0 | 0x0001e5b0
`public: class CAutoEvent & __ptr64 __cdecl CAutoEvent::operator=(class CAutoEvent const & __ptr64) __ptr64` | 73 (0x49) | Exported Function | 0x000000018001e1a0 | 0x0001e1a0
`public: class CFrameworkQuery & __ptr64 __cdecl CFrameworkQuery::operator=(class CFrameworkQuery const & __ptr64) __ptr64` | 74 (0x4a) | Exported Function | 0x000000018001de40 | 0x0001de40
`public: class CFrameworkQueryEx & __ptr64 __cdecl CFrameworkQueryEx::operator=(class CFrameworkQueryEx const & __ptr64) __ptr64` | 75 (0x4b) | Exported Function | 0x000000018001f350 | 0x0001f350
`public: class CHPtrArray & __ptr64 __cdecl CHPtrArray::operator=(class CHPtrArray const & __ptr64) __ptr64` | 76 (0x4c) | Exported Function | 0x000000018001dee0 | 0x0001dee0
`public: class CHString & __ptr64 __cdecl CHStringArray::ElementAt(int) __ptr64` | 232 (0xe8) | Exported Function | 0x0000000180002d80 | 0x00002d80
`public: class CHString & __ptr64 __cdecl CHStringArray::operator[](int) __ptr64` | 118 (0x76) | Exported Function | 0x0000000180002d80 | 0x00002d80
`public: class CHString __cdecl CHString::Left(int)const __ptr64` | 427 (0x1ab) | Exported Function | 0x000000018000b3d0 | 0x0000b3d0
`public: __cdecl WBEMTimeSpan::WBEMTimeSpan(struct _FILETIME const & __ptr64) __ptr64` | 48 (0x30) | Exported Function | 0x0000000180029320 | 0x00029320
`public: __cdecl WBEMTimeSpan::WBEMTimeSpan(int,int,int,int,int,int,int) __ptr64` | 50 (0x32) | Exported Function | 0x0000000180029360 | 0x00029360
`public: __cdecl WBEMTimeSpan::WBEMTimeSpan(__int64 const & __ptr64) __ptr64` | 49 (0x31) | Exported Function | 0x0000000180029340 | 0x00029340
`public: __cdecl CHPtrArray::~CHPtrArray(void) __ptr64` | 56 (0x38) | Exported Function | 0x00000001800030b0 | 0x000030b0
`public: __cdecl CHString::CHString(char const * __ptr64) __ptr64` | 9 (0x9) | Exported Function | 0x000000018000cca0 | 0x0000cca0
`public: __cdecl CHString::CHString(class CHString const & __ptr64) __ptr64` | 7 (0x7) | Exported Function | 0x0000000180002830 | 0x00002830
`public: __cdecl CHString::CHString(unsigned char const * __ptr64) __ptr64` | 10 (0xa) | Exported Function | 0x000000018001db80 | 0x0001db80
`public: __cdecl CHString::CHString(unsigned short const * __ptr64) __ptr64` | 11 (0xb) | Exported Function | 0x000000018000a220 | 0x0000a220
`public: __cdecl CHString::CHString(unsigned short const * __ptr64,int) __ptr64` | 12 (0xc) | Exported Function | 0x0000000180028a90 | 0x00028a90
`public: __cdecl CHString::CHString(unsigned short,int) __ptr64` | 8 (0x8) | Exported Function | 0x00000001800289d0 | 0x000289d0
`public: __cdecl CHString::CHString(void) __ptr64` | 13 (0xd) | Exported Function | 0x0000000180001f20 | 0x00001f20
`public: __cdecl CHString::operator unsigned short const * __ptr64(void)const __ptr64` | 120 (0x78) | Exported Function | 0x0000000180002c20 | 0x00002c20
`public: __cdecl CHString::~CHString(void) __ptr64` | 57 (0x39) | Exported Function | 0x0000000180009b30 | 0x00009b30
`public: __cdecl CHStringArray::CHStringArray(void) __ptr64` | 14 (0xe) | Exported Function | 0x0000000180003050 | 0x00003050
`public: __cdecl CHStringArray::~CHStringArray(void) __ptr64` | 58 (0x3a) | Exported Function | 0x000000018000c120 | 0x0000c120
`public: __cdecl CInstance::CInstance(class CInstance const & __ptr64) __ptr64` | 15 (0xf) | Exported Function | 0x000000018001dbb0 | 0x0001dbb0
`public: __cdecl CInstance::CInstance(struct IWbemClassObject * __ptr64,class MethodContext * __ptr64) __ptr64` | 16 (0x10) | Exported Function | 0x000000018000f9d0 | 0x0000f9d0
`public: __cdecl CObjectPathParser::CObjectPathParser(enum ObjectParserFlags) __ptr64` | 17 (0x11) | Exported Function | 0x000000018000ed60 | 0x0000ed60
`public: __cdecl CHPtrArray::CHPtrArray(void) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180003050 | 0x00003050
`public: __cdecl CObjectPathParser::~CObjectPathParser(void) __ptr64` | 60 (0x3c) | Exported Function | 0x00000001800125b0 | 0x000125b0
`public: __cdecl CFrameworkQueryEx::~CFrameworkQueryEx(void) __ptr64` | 55 (0x37) | Exported Function | 0x0000000180006880 | 0x00006880
`public: __cdecl CFrameworkQueryEx::CFrameworkQueryEx(class CFrameworkQueryEx const & __ptr64) __ptr64` | 4 (0x4) | Exported Function | 0x000000018001f260 | 0x0001f260
`protected: void __cdecl CHString::AllocBuffer(int) __ptr64` | 175 (0xaf) | Exported Function | 0x000000018000b8e0 | 0x0000b8e0
`protected: void __cdecl CHString::AllocCopy(class CHString & __ptr64,int,int,int)const __ptr64` | 176 (0xb0) | Exported Function | 0x000000018000c020 | 0x0000c020
`protected: void __cdecl CHString::AssignCopy(int,unsigned short const * __ptr64) __ptr64` | 180 (0xb4) | Exported Function | 0x0000000180007580 | 0x00007580
`protected: void __cdecl CHString::ConcatCopy(int,unsigned short const * __ptr64,int,unsigned short const * __ptr64) __ptr64` | 198 (0xc6) | Exported Function | 0x000000018000b620 | 0x0000b620
`protected: void __cdecl CHString::ConcatInPlace(int,unsigned short const * __ptr64) __ptr64` | 199 (0xc7) | Exported Function | 0x0000000180028da0 | 0x00028da0
`protected: void __cdecl CHString::CopyBeforeWrite(void) __ptr64` | 202 (0xca) | Exported Function | 0x0000000180009af0 | 0x00009af0
`protected: void __cdecl CHString::Init(void) __ptr64` | 399 (0x18f) | Exported Function | 0x00000001800142d0 | 0x000142d0
`protected: void __cdecl CInstance::LogError(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,long)const __ptr64` | 438 (0x1b6) | Exported Function | 0x0000000180021480 | 0x00021480
`protected: void __cdecl CWinMsgEvent::RegisterForMessage(unsigned int,int) __ptr64` | 470 (0x1d6) | Exported Function | 0x00000001800278f0 | 0x000278f0
`protected: void __cdecl CWinMsgEvent::UnRegisterAllMessages(void) __ptr64` | 542 (0x21e) | Exported Function | 0x0000000180027b50 | 0x00027b50
`public: __cdecl CAutoEvent::CAutoEvent(void) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180003e20 | 0x00003e20
`public: __cdecl CAutoEvent::~CAutoEvent(void) __ptr64` | 53 (0x35) | Exported Function | 0x0000000180003f70 | 0x00003f70
`public: __cdecl CFrameworkQuery::CFrameworkQuery(class CFrameworkQuery const & __ptr64) __ptr64` | 2 (0x2) | Exported Function | 0x000000018001daa0 | 0x0001daa0
`public: __cdecl CFrameworkQuery::CFrameworkQuery(void) __ptr64` | 3 (0x3) | Exported Function | 0x00000001800067f0 | 0x000067f0
`public: __cdecl CFrameworkQuery::~CFrameworkQuery(void) __ptr64` | 54 (0x36) | Exported Function | 0x00000001800077e0 | 0x000077e0
`public: __cdecl CFrameworkQueryEx::CFrameworkQueryEx(void) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180006840 | 0x00006840
`public: __cdecl CreateMutexAsProcess::CreateMutexAsProcess(unsigned short const * __ptr64) __ptr64` | 32 (0x20) | Exported Function | 0x00000001800035e0 | 0x000035e0
`public: __cdecl CreateMutexAsProcess::~CreateMutexAsProcess(void) __ptr64` | 67 (0x43) | Exported Function | 0x0000000180003fb0 | 0x00003fb0
`public: __cdecl CRegistry::CRegistry(class CRegistry const & __ptr64) __ptr64` | 18 (0x12) | Exported Function | 0x000000018001e6e0 | 0x0001e6e0
`public: __cdecl KeyRef::~KeyRef(void) __ptr64` | 68 (0x44) | Exported Function | 0x0000000180026370 | 0x00026370
`public: __cdecl MethodContext::MethodContext(class MethodContext const & __ptr64) __ptr64` | 35 (0x23) | Exported Function | 0x000000018001dca0 | 0x0001dca0
`public: __cdecl MethodContext::MethodContext(struct IWbemContext * __ptr64,class CWbemProviderGlue * __ptr64) __ptr64` | 36 (0x24) | Exported Function | 0x0000000180006eb0 | 0x00006eb0
`public: __cdecl ParsedObjectPath::ParsedObjectPath(void) __ptr64` | 37 (0x25) | Exported Function | 0x0000000180011530 | 0x00011530
`public: __cdecl ParsedObjectPath::~ParsedObjectPath(void) __ptr64` | 70 (0x46) | Exported Function | 0x0000000180010ad0 | 0x00010ad0
`public: __cdecl Provider::Provider(class Provider const & __ptr64) __ptr64` | 38 (0x26) | Exported Function | 0x000000018001dd00 | 0x0001dd00
`public: __cdecl Provider::Provider(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 39 (0x27) | Exported Function | 0x00000001800078a0 | 0x000078a0
`public: __cdecl ProviderLog::ProviderLog(class ProviderLog const & __ptr64) __ptr64` | 40 (0x28) | Exported Function | 0x000000018001e860 | 0x0001e860
`public: __cdecl ProviderLog::ProviderLog(void) __ptr64` | 41 (0x29) | Exported Function | 0x000000018000cb40 | 0x0000cb40
`public: __cdecl WBEMTime::WBEMTime(__int64 const & __ptr64) __ptr64` | 45 (0x2d) | Exported Function | 0x0000000180003c40 | 0x00003c40
`public: __cdecl WBEMTime::WBEMTime(struct _FILETIME const & __ptr64) __ptr64` | 42 (0x2a) | Exported Function | 0x0000000180002d20 | 0x00002d20
`public: __cdecl WBEMTime::WBEMTime(struct _SYSTEMTIME const & __ptr64) __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180003e60 | 0x00003e60
`public: __cdecl WBEMTime::WBEMTime(struct tm const & __ptr64) __ptr64` | 44 (0x2c) | Exported Function | 0x000000018001ddc0 | 0x0001ddc0
`public: __cdecl WBEMTime::WBEMTime(unsigned short * __ptr64 const) __ptr64` | 46 (0x2e) | Exported Function | 0x000000018001dde0 | 0x0001dde0
`public: __cdecl WBEMTime::WBEMTime(void) __ptr64` | 47 (0x2f) | Exported Function | 0x000000018001de00 | 0x0001de00
`public: __cdecl KeyRef::KeyRef(void) __ptr64` | 34 (0x22) | Exported Function | 0x0000000180026300 | 0x00026300
`public: __cdecl KeyRef::KeyRef(unsigned short const * __ptr64,struct tagVARIANT const * __ptr64) __ptr64` | 33 (0x21) | Exported Function | 0x0000000180026270 | 0x00026270
`public: __cdecl CWinMsgEvent::~CWinMsgEvent(void) __ptr64` | 66 (0x42) | Exported Function | 0x0000000180027400 | 0x00027400
`public: __cdecl CWinMsgEvent::CWinMsgEvent(void) __ptr64` | 31 (0x1f) | Exported Function | 0x00000001800273e0 | 0x000273e0
`public: __cdecl CRegistry::CRegistry(void) __ptr64` | 19 (0x13) | Exported Function | 0x000000018000c960 | 0x0000c960
`public: __cdecl CRegistry::~CRegistry(void) __ptr64` | 61 (0x3d) | Exported Function | 0x000000018000c3c0 | 0x0000c3c0
`public: __cdecl CRegistrySearch::CRegistrySearch(class CRegistrySearch const & __ptr64) __ptr64` | 20 (0x14) | Exported Function | 0x000000018001e810 | 0x0001e810
`public: __cdecl CRegistrySearch::CRegistrySearch(void) __ptr64` | 21 (0x15) | Exported Function | 0x000000018002a510 | 0x0002a510
`public: __cdecl CRegistrySearch::~CRegistrySearch(void) __ptr64` | 62 (0x3e) | Exported Function | 0x000000018002a540 | 0x0002a540
`public: __cdecl CThreadBase::CThreadBase(class CThreadBase const & __ptr64) __ptr64` | 22 (0x16) | Exported Function | 0x000000018001dbe0 | 0x0001dbe0
`public: __cdecl CThreadBase::CThreadBase(enum CThreadBase::THREAD_SAFETY_MECHANISM) __ptr64` | 23 (0x17) | Exported Function | 0x000000018000c0e0 | 0x0000c0e0
`protected: virtual void __cdecl Provider::Flush(void) __ptr64` | 254 (0xfe) | Exported Function | 0x00000001800034f0 | 0x000034f0
`public: __cdecl CWbemGlueFactory::CWbemGlueFactory(class CWbemGlueFactory const & __ptr64) __ptr64` | 24 (0x18) | Exported Function | 0x000000018001dc20 | 0x0001dc20
`public: __cdecl CWbemGlueFactory::CWbemGlueFactory(void) __ptr64` | 26 (0x1a) | Exported Function | 0x000000018001ed40 | 0x0001ed40
`public: __cdecl CWbemGlueFactory::~CWbemGlueFactory(void) __ptr64` | 64 (0x40) | Exported Function | 0x000000018000dd30 | 0x0000dd30
`public: __cdecl CWbemProviderGlue::CWbemProviderGlue(class CWbemProviderGlue const & __ptr64) __ptr64` | 27 (0x1b) | Exported Function | 0x000000018001dc40 | 0x0001dc40
`public: __cdecl CWbemProviderGlue::CWbemProviderGlue(long * __ptr64) __ptr64` | 28 (0x1c) | Exported Function | 0x000000018000d0e0 | 0x0000d0e0
`public: __cdecl CWbemProviderGlue::CWbemProviderGlue(void) __ptr64` | 29 (0x1d) | Exported Function | 0x000000018000cba0 | 0x0000cba0
`public: __cdecl CWbemProviderGlue::~CWbemProviderGlue(void) __ptr64` | 65 (0x41) | Exported Function | 0x000000018000c1f0 | 0x0000c1f0
`public: __cdecl CWinMsgEvent::CWinMsgEvent(class CWinMsgEvent const & __ptr64) __ptr64` | 30 (0x1e) | Exported Function | 0x00000001800273e0 | 0x000273e0
`public: __cdecl CWbemGlueFactory::CWbemGlueFactory(long * __ptr64) __ptr64` | 25 (0x19) | Exported Function | 0x000000018000dde0 | 0x0000dde0
`void __cdecl SetCHStringResourceHandle(struct HINSTANCE__ * __ptr64)` | 500 (0x1f4) | Exported Function | 0x00000001800107d0 | 0x000107d0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: framedyn.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/109a9ba3e471b4f73cbc87530d9361fe66855a4d822c2f283d4f2ffc4e156edc/detection/





MIT License. Copyright (c) 2020 Strontic.


