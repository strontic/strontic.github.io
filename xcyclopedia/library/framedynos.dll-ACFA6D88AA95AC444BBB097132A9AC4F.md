---
title: framedynos.dll | WMI SDK Provider Framework
excerpt: What is framedynos.dll?
---

# framedynos.dll 

* File Path: `C:\Windows\SysWOW64\framedynos.dll`
* Description: WMI SDK Provider Framework

## Hashes

Type | Hash
-- | --
MD5 | `ACFA6D88AA95AC444BBB097132A9AC4F`
SHA1 | `EE0F7F26B70623A2B4387158F16CA6C9AFCB8D89`
SHA256 | `D3E9452A047D3942A7AAE42C696CAE7D277FA42638DBC738081518E69E29959C`
SHA384 | `163E8A762D20B3A5920D9F9C61B892BCAE874D6E12FDFB03BECDC689D13DE8C816F223B18B598BA18E8DE16769AD8090`
SHA512 | `FABA05972FEC0D3AC0E13FE2C1C653DF993902541F3C0FCF8F641B24DBE98BAF72DCE7E05603C35B3B686808AF973ED07B3E843B0DE500547C27F7427526BD31`
SSDEEP | `6144:YCI77Ta3LFQA7RhKIs0TZGyvRgkXHo5s9hhB8vV:YCnLF17RK0wyp1I5Yv8v`
IMP | `6B245E8E80011D6A8A108CB8D32FCDD8`
PESHA1 | `70E860EE18E7040987968EC9A228E2761B496DA0`
PE256 | `04C53C6D87B14DD73BE3639B09A977958ECD24CBBC650BFC7C3F706F6FCFCF8A`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`_DoCmd@16` | 611 (0x263) | Exported Function | 0x10022e90 | 0x00022e90
`public: long __thiscall CFrameworkQueryEx::GetValuesForProp(unsigned short const *,class std::vector<class _variant_t,class std::allocator<class _variant_t> > &)` | 381 (0x17d) | Exported Function | 0x10020ce0 | 0x00020ce0
`public: long __thiscall CFrameworkQueryEx::GetValuesForProp(unsigned short const *,class std::vector<int,class std::allocator<int> > &)` | 380 (0x17c) | Exported Function | 0x10011a40 | 0x00011a40
`public: long __thiscall CInstance::AddRef(void)` | 167 (0xa7) | Exported Function | 0x100091d0 | 0x000091d0
`public: long __thiscall CInstance::Commit(void)` | 194 (0xc2) | Exported Function | 0x10008280 | 0x00008280
`public: long __thiscall CInstance::Release(void)` | 473 (0x1d9) | Exported Function | 0x10016fd0 | 0x00016fd0
`public: long __thiscall CRegistry::CreateOpen(struct HKEY__ *,unsigned short const *,unsigned short *,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES *,unsigned long *)` | 214 (0xd6) | Exported Function | 0x100293d0 | 0x000293d0
`public: long __thiscall CRegistry::DeleteKey(class CHString *)` | 227 (0xe3) | Exported Function | 0x100294d0 | 0x000294d0
`public: long __thiscall CRegistry::DeleteValue(unsigned short const *)` | 228 (0xe4) | Exported Function | 0x100294b0 | 0x000294b0
`public: long __thiscall CRegistry::EnumerateAndGetValues(unsigned long &,unsigned short * &,unsigned char * &)` | 237 (0xed) | Exported Function | 0x10029510 | 0x00029510
`public: long __thiscall CRegistry::Open(struct HKEY__ *,unsigned short const *,unsigned long)` | 451 (0x1c3) | Exported Function | 0x1000cb80 | 0x0000cb80
`public: long __thiscall CRegistry::OpenAndEnumerateSubKeys(struct HKEY__ *,unsigned short const *,unsigned long)` | 452 (0x1c4) | Exported Function | 0x10029e50 | 0x00029e50
`public: long __thiscall CRegistry::OpenLocalMachineKeyAndReadValue(unsigned short const *,unsigned short const *,class CHString &)` | 454 (0x1c6) | Exported Function | 0x10010c00 | 0x00010c00
`public: long __thiscall CThreadBase::AddRef(void)` | 168 (0xa8) | Exported Function | 0x10022a50 | 0x00022a50
`public: long __thiscall CThreadBase::Release(void)` | 474 (0x1da) | Exported Function | 0x100144b0 | 0x000144b0
`public: long __thiscall MethodContext::AddRef(void)` | 171 (0xab) | Exported Function | 0x10022a50 | 0x00022a50
`public: long __thiscall CFrameworkQuery::Init(unsigned short * const,unsigned short * const,long,class CHString &)` | 398 (0x18e) | Exported Function | 0x1000f090 | 0x0000f090
`public: long __thiscall MethodContext::Release(void)` | 477 (0x1dd) | Exported Function | 0x10022af0 | 0x00022af0
`public: long __thiscall CFrameworkQuery::Init(struct ParsedObjectPath *,struct IWbemContext *,unsigned short const *,class CHString &)` | 397 (0x18d) | Exported Function | 0x1000fac0 | 0x0000fac0
`public: long __thiscall CFrameworkQuery::GetValuesForProp(unsigned short const *,class CHStringArray &)` | 379 (0x17b) | Exported Function | 0x100120d0 | 0x000120d0
`public: int __thiscall WBEMTime::operator!=(class WBEMTime const &)const ` | 113 (0x71) | Exported Function | 0x1001f9b0 | 0x0001f9b0
`public: int __thiscall WBEMTime::operator<(class WBEMTime const &)const ` | 131 (0x83) | Exported Function | 0x1001f9e0 | 0x0001f9e0
`public: int __thiscall WBEMTime::operator<=(class WBEMTime const &)const ` | 133 (0x85) | Exported Function | 0x1001fa10 | 0x0001fa10
`public: int __thiscall WBEMTime::operator==(class WBEMTime const &)const ` | 111 (0x6f) | Exported Function | 0x1001f980 | 0x0001f980
`public: int __thiscall WBEMTime::operator>(class WBEMTime const &)const ` | 135 (0x87) | Exported Function | 0x1001fa40 | 0x0001fa40
`public: int __thiscall WBEMTime::operator>=(class WBEMTime const &)const ` | 137 (0x89) | Exported Function | 0x1001fa70 | 0x0001fa70
`public: int __thiscall WBEMTime::SetDMTF(unsigned short * const)` | 513 (0x201) | Exported Function | 0x10028960 | 0x00028960
`public: int __thiscall WBEMTimeSpan::GetFILETIME(struct _FILETIME *)const ` | 322 (0x142) | Exported Function | 0x10028760 | 0x00028760
`public: int __thiscall WBEMTimeSpan::Gettime_t(long *)const ` | 392 (0x188) | Exported Function | 0x10028920 | 0x00028920
`public: int __thiscall WBEMTimeSpan::operator!=(class WBEMTimeSpan const &)const ` | 114 (0x72) | Exported Function | 0x1001f9b0 | 0x0001f9b0
`public: int __thiscall WBEMTimeSpan::operator<(class WBEMTimeSpan const &)const ` | 132 (0x84) | Exported Function | 0x1001f9e0 | 0x0001f9e0
`public: int __thiscall WBEMTimeSpan::operator<=(class WBEMTimeSpan const &)const ` | 134 (0x86) | Exported Function | 0x1001fa10 | 0x0001fa10
`public: int __thiscall WBEMTimeSpan::operator==(class WBEMTimeSpan const &)const ` | 112 (0x70) | Exported Function | 0x1001f980 | 0x0001f980
`public: int __thiscall WBEMTimeSpan::operator>(class WBEMTimeSpan const &)const ` | 136 (0x88) | Exported Function | 0x1001fa40 | 0x0001fa40
`public: int __thiscall WBEMTimeSpan::operator>=(class WBEMTimeSpan const &)const ` | 138 (0x8a) | Exported Function | 0x1001fa70 | 0x0001fa70
`public: long __thiscall CFrameworkQuery::GetValuesForProp(unsigned short const *,class std::vector<class _bstr_t,class std::allocator<class _bstr_t> > &)` | 378 (0x17a) | Exported Function | 0x10011c80 | 0x00011c80
`public: int __thiscall WBEMTime::Gettime_t(long *)const ` | 391 (0x187) | Exported Function | 0x100288a0 | 0x000288a0
`public: static bool __stdcall CWbemProviderGlue::IsDerivedFrom(unsigned short const *,unsigned short const *,class MethodContext *,unsigned short const *)` | 411 (0x19b) | Exported Function | 0x10014c30 | 0x00014c30
`public: static class CWbemGlueFactory * __stdcall CWbemGlueFactory::Create(long *)` | 203 (0xcb) | Exported Function | 0x100119f0 | 0x000119f0
`public: static long __stdcall CWbemProviderGlue::GetInstancesByQuery(unsigned short const *,class TRefPointerCollection<class CInstance> *,class MethodContext *,unsigned short const *)` | 328 (0x148) | Exported Function | 0x10009b40 | 0x00009b40
`public: static long __stdcall CWbemProviderGlue::GetInstancesByQueryAsynch(unsigned short const *,class Provider *,long (__stdcall*)(class Provider *,class CInstance *,class MethodContext *,void *),unsigned short const *,class MethodContext *,void *)` | 329 (0x149) | Exported Function | 0x10024850 | 0x00024850
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(long const &)` | 334 (0x14e) | Exported Function | 0x10028790 | 0x00028790
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(struct _FILETIME const *)` | 335 (0x14f) | Exported Function | 0x100287d0 | 0x000287d0
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(struct _SYSTEMTIME const *)` | 336 (0x150) | Exported Function | 0x10009530 | 0x00009530
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(struct tm const *)` | 337 (0x151) | Exported Function | 0x10028810 | 0x00028810
`public: static struct IWbemServices * __stdcall CWbemProviderGlue::GetNamespaceConnection(unsigned short const *)` | 346 (0x15a) | Exported Function | 0x10024c50 | 0x00024c50
`public: static struct IWbemServices * __stdcall CWbemProviderGlue::GetNamespaceConnection(unsigned short const *,class MethodContext *)` | 347 (0x15b) | Exported Function | 0x1000ae10 | 0x0000ae10
`public: static unsigned long __stdcall CWbemProviderGlue::GetOSMajorVersion(void)` | 349 (0x15d) | Exported Function | 0x1001fd30 | 0x0001fd30
`public: static unsigned long __stdcall CWbemProviderGlue::GetPlatform(void)` | 356 (0x164) | Exported Function | 0x1001fd40 | 0x0001fd40
`public: static unsigned short * __stdcall CObjectPathParser::GetRelativePath(unsigned short *)` | 362 (0x16a) | Exported Function | 0x10026870 | 0x00026870
`public: static unsigned short const * __stdcall CWbemProviderGlue::GetCSDVersion(void)` | 286 (0x11e) | Exported Function | 0x1001fd20 | 0x0001fd20
`public: static void __stdcall CHString::Release(struct CHStringData *)` | 472 (0x1d8) | Exported Function | 0x1000ca60 | 0x0000ca60
`public: static void __stdcall CWbemProviderGlue::FrameworkLogin(unsigned short const *,class Provider *,unsigned short const *)` | 261 (0x105) | Exported Function | 0x10024340 | 0x00024340
`public: static void __stdcall CWbemProviderGlue::FrameworkLogoff(unsigned short const *,unsigned short const *)` | 264 (0x108) | Exported Function | 0x1000d440 | 0x0000d440
`public: static long __stdcall CWbemProviderGlue::GetInstancePropertiesByPath(unsigned short const *,class CInstance * *,class MethodContext *,class CHStringArray &)` | 327 (0x147) | Exported Function | 0x10014670 | 0x00014670
`public: static bool __stdcall CWbemProviderGlue::SetStatusObject(class MethodContext *,unsigned short const *,unsigned short const *,long,struct tagSAFEARRAY const *,struct tagSAFEARRAY const *)` | 524 (0x20c) | Exported Function | 0x10025930 | 0x00025930
`public: static long __stdcall CWbemProviderGlue::GetInstanceKeysByPath(unsigned short const *,class CInstance * *,class MethodContext *)` | 326 (0x146) | Exported Function | 0x10014890 | 0x00014890
`public: static long __stdcall CWbemProviderGlue::GetEmptyInstance(unsigned short const *,class CInstance * *,unsigned short const *)` | 320 (0x140) | Exported Function | 0x10024750 | 0x00024750
`public: static class CWbemGlueFactory * __stdcall CWbemGlueFactory::Create(void)` | 204 (0xcc) | Exported Function | 0x100204e0 | 0x000204e0
`public: static int __stdcall CObjectPathParser::Unparse(struct ParsedObjectPath *,unsigned short * *)` | 548 (0x224) | Exported Function | 0x100128e0 | 0x000128e0
`public: static int __stdcall CWbemProviderGlue::FrameworkLoginDLL(unsigned short const *)` | 262 (0x106) | Exported Function | 0x100243e0 | 0x000243e0
`public: static int __stdcall CWbemProviderGlue::FrameworkLoginDLL(unsigned short const *,long *)` | 263 (0x107) | Exported Function | 0x100097e0 | 0x000097e0
`public: static int __stdcall CWbemProviderGlue::FrameworkLogoffDLL(unsigned short const *)` | 265 (0x109) | Exported Function | 0x10024400 | 0x00024400
`public: static int __stdcall CWbemProviderGlue::FrameworkLogoffDLL(unsigned short const *,long *)` | 266 (0x10a) | Exported Function | 0x10009870 | 0x00009870
`public: static int __stdcall Provider::initFailed(void)` | 565 (0x235) | Exported Function | 0x10009620 | 0x00009620
`public: static long __stdcall CWbemProviderGlue::DecrementObjectCount(void)` | 218 (0xda) | Exported Function | 0x100234c0 | 0x000234c0
`public: static long __stdcall CWbemProviderGlue::FillInstance(class CInstance *,unsigned short const *)` | 249 (0xf9) | Exported Function | 0x10024220 | 0x00024220
`public: static long __stdcall CWbemProviderGlue::FillInstance(class MethodContext *,class CInstance *)` | 250 (0xfa) | Exported Function | 0x100242c0 | 0x000242c0
`public: static long __stdcall CWbemProviderGlue::GetAllDerivedInstances(unsigned short const *,class TRefPointerCollection<class CInstance> *,class MethodContext *,unsigned short const *)` | 272 (0x110) | Exported Function | 0x10024420 | 0x00024420
`public: static long __stdcall CWbemProviderGlue::GetAllDerivedInstancesAsynch(unsigned short const *,class Provider *,long (__stdcall*)(class Provider *,class CInstance *,class MethodContext *,void *),unsigned short const *,class MethodContext *,void *)` | 273 (0x111) | Exported Function | 0x10024490 | 0x00024490
`public: static long __stdcall CWbemProviderGlue::GetAllInstances(unsigned short const *,class TRefPointerCollection<class CInstance> *,unsigned short const *,class MethodContext *)` | 274 (0x112) | Exported Function | 0x10024500 | 0x00024500
`public: static long __stdcall CWbemProviderGlue::GetAllInstancesAsynch(unsigned short const *,class Provider *,long (__stdcall*)(class Provider *,class CInstance *,class MethodContext *,void *),unsigned short const *,class MethodContext *,void *)` | 275 (0x113) | Exported Function | 0x10024570 | 0x00024570
`public: static long __stdcall CWbemProviderGlue::GetEmptyInstance(class MethodContext *,unsigned short const *,class CInstance * *,unsigned short const *)` | 319 (0x13f) | Exported Function | 0x100245e0 | 0x000245e0
`public: static long __stdcall CWbemProviderGlue::GetInstanceByPath(unsigned short const *,class CInstance * *,class MethodContext *)` | 324 (0x144) | Exported Function | 0x10014220 | 0x00014220
`public: int __thiscall WBEMTime::GetSYSTEMTIME(struct _SYSTEMTIME *)const ` | 364 (0x16c) | Exported Function | 0x10015170 | 0x00015170
`public: int __thiscall WBEMTime::GetStructtm(struct tm *)const ` | 371 (0x173) | Exported Function | 0x10028850 | 0x00028850
`public: int __thiscall WBEMTime::GetFILETIME(struct _FILETIME *)const ` | 321 (0x141) | Exported Function | 0x100151c0 | 0x000151c0
`public: class WBEMTime const & __thiscall WBEMTime::operator=(long const &)` | 101 (0x65) | Exported Function | 0x10009430 | 0x00009430
`public: class WBEMTime const & __thiscall WBEMTime::operator=(struct _FILETIME const &)` | 102 (0x66) | Exported Function | 0x10009500 | 0x00009500
`public: class WBEMTime const & __thiscall WBEMTime::operator=(struct _SYSTEMTIME const &)` | 103 (0x67) | Exported Function | 0x100094c0 | 0x000094c0
`public: class WBEMTime const & __thiscall WBEMTime::operator=(struct tm const &)` | 104 (0x68) | Exported Function | 0x10028370 | 0x00028370
`public: class WBEMTime const & __thiscall WBEMTime::operator=(unsigned short * const)` | 105 (0x69) | Exported Function | 0x100283c0 | 0x000283c0
`public: class WBEMTimeSpan & __thiscall WBEMTimeSpan::operator=(class WBEMTimeSpan &&)` | 106 (0x6a) | Exported Function | 0x1001f930 | 0x0001f930
`public: class WBEMTimeSpan & __thiscall WBEMTimeSpan::operator=(class WBEMTimeSpan const &)` | 107 (0x6b) | Exported Function | 0x1001f930 | 0x0001f930
`public: class WBEMTimeSpan __thiscall WBEMTime::operator-(class WBEMTime const &)` | 121 (0x79) | Exported Function | 0x10016c90 | 0x00016c90
`public: class WBEMTimeSpan __thiscall WBEMTimeSpan::operator+(class WBEMTimeSpan const &)const ` | 130 (0x82) | Exported Function | 0x10028530 | 0x00028530
`public: class WBEMTimeSpan __thiscall WBEMTimeSpan::operator-(class WBEMTimeSpan const &)const ` | 123 (0x7b) | Exported Function | 0x10016c90 | 0x00016c90
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator+=(class WBEMTimeSpan const &)` | 144 (0x90) | Exported Function | 0x10028580 | 0x00028580
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator-=(class WBEMTimeSpan const &)` | 146 (0x92) | Exported Function | 0x100285c0 | 0x000285c0
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator=(long const &)` | 108 (0x6c) | Exported Function | 0x10028440 | 0x00028440
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator=(struct _FILETIME const &)` | 109 (0x6d) | Exported Function | 0x10028340 | 0x00028340
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator=(unsigned short * const)` | 110 (0x6e) | Exported Function | 0x10028480 | 0x00028480
`public: class WBEMTime const & __thiscall WBEMTime::operator-=(class WBEMTimeSpan const &)` | 145 (0x91) | Exported Function | 0x100285c0 | 0x000285c0
`public: enum ProviderLog::LogLevel __thiscall ProviderLog::IsLoggingOn(class CHString *)` | 417 (0x1a1) | Exported Function | 0x1000e5d0 | 0x0000e5d0
`public: class WBEMTime const & __thiscall WBEMTime::operator+=(class WBEMTimeSpan const &)` | 143 (0x8f) | Exported Function | 0x10028580 | 0x00028580
`public: class WBEMTime __thiscall WBEMTime::operator+(class WBEMTimeSpan const &)const ` | 129 (0x81) | Exported Function | 0x10028530 | 0x00028530
`public: class CInstance & __thiscall CInstance::operator=(class CInstance const &)` | 85 (0x55) | Exported Function | 0x1001f790 | 0x0001f790
`public: class CObjectPathParser & __thiscall CObjectPathParser::operator=(class CObjectPathParser const &)` | 86 (0x56) | Exported Function | 0x1001f7c0 | 0x0001f7c0
`public: class CreateMutexAsProcess & __thiscall CreateMutexAsProcess::operator=(class CreateMutexAsProcess const &)` | 93 (0x5d) | Exported Function | 0x10020600 | 0x00020600
`public: class CRegistry & __thiscall CRegistry::operator=(class CRegistry const &)` | 87 (0x57) | Exported Function | 0x10020160 | 0x00020160
`public: class CRegistrySearch & __thiscall CRegistrySearch::operator=(class CRegistrySearch const &)` | 88 (0x58) | Exported Function | 0x10020240 | 0x00020240
`public: class CThreadBase & __thiscall CThreadBase::operator=(class CThreadBase const &)` | 89 (0x59) | Exported Function | 0x1001f7e0 | 0x0001f7e0
`public: class CWbemGlueFactory & __thiscall CWbemGlueFactory::operator=(class CWbemGlueFactory const &)` | 90 (0x5a) | Exported Function | 0x1001f820 | 0x0001f820
`public: class CWbemProviderGlue & __thiscall CWbemProviderGlue::operator=(class CWbemProviderGlue const &)` | 91 (0x5b) | Exported Function | 0x1001f840 | 0x0001f840
`public: class CWinMsgEvent & __thiscall CWinMsgEvent::operator=(class CWinMsgEvent const &)` | 92 (0x5c) | Exported Function | 0x10026ce0 | 0x00026ce0
`public: class MethodContext & __thiscall MethodContext::operator=(class MethodContext const &)` | 95 (0x5f) | Exported Function | 0x1001f880 | 0x0001f880
`public: class MethodContext * __thiscall CInstance::GetMethodContext(void)const ` | 343 (0x157) | Exported Function | 0x10009470 | 0x00009470
`public: class Provider & __thiscall Provider::operator=(class Provider const &)` | 97 (0x61) | Exported Function | 0x1001f8e0 | 0x0001f8e0
`public: class ProviderLog & __thiscall ProviderLog::operator=(class ProviderLog const &)` | 98 (0x62) | Exported Function | 0x10020280 | 0x00020280
`public: class WBEMTime & __thiscall WBEMTime::operator=(class WBEMTime &&)` | 99 (0x63) | Exported Function | 0x1001f930 | 0x0001f930
`public: class WBEMTime & __thiscall WBEMTime::operator=(class WBEMTime const &)` | 100 (0x64) | Exported Function | 0x1001f930 | 0x0001f930
`public: class WBEMTime __thiscall WBEMTime::operator-(class WBEMTimeSpan const &)const ` | 122 (0x7a) | Exported Function | 0x10016c90 | 0x00016c90
`public: int __thiscall CAutoEvent::Signal(void)` | 536 (0x218) | Exported Function | 0x10027170 | 0x00027170
`public: int __thiscall CFrameworkQueryEx::Is3TokenOR(unsigned short const *,unsigned short const *,struct tagVARIANT &,struct tagVARIANT &)` | 409 (0x199) | Exported Function | 0x100211c0 | 0x000211c0
`public: int __thiscall CFrameworkQueryEx::IsNTokenAnd(class CHStringArray &,class CHPtrArray &)` | 418 (0x1a2) | Exported Function | 0x10021310 | 0x00021310
`public: int __thiscall CRegistrySearch::FreeSearchList(int,class CHPtrArray &)` | 271 (0x10f) | Exported Function | 0x10029640 | 0x00029640
`public: int __thiscall CRegistrySearch::LocateKeyByNameOrValueName(struct HKEY__ *,unsigned short const *,unsigned short const *,unsigned short const * *,unsigned long,class CHString &,class CHString &)` | 432 (0x1b0) | Exported Function | 0x10029bb0 | 0x00029bb0
`public: int __thiscall CRegistrySearch::SearchAndBuildList(class CHString,class CHPtrArray &,class CHString,class CHString,int,struct HKEY__ *)` | 489 (0x1e9) | Exported Function | 0x10029fc0 | 0x00029fc0
`public: int __thiscall CThreadBase::BeginRead(unsigned long)` | 181 (0xb5) | Exported Function | 0x10008ec0 | 0x00008ec0
`public: int __thiscall CThreadBase::BeginWrite(unsigned long)` | 182 (0xb6) | Exported Function | 0x10008ec0 | 0x00008ec0
`public: int __thiscall ParsedObjectPath::AddKeyRef(struct KeyRef *)` | 162 (0xa2) | Exported Function | 0x10013e60 | 0x00013e60
`public: int __thiscall ParsedObjectPath::AddKeyRef(unsigned short const *,struct tagVARIANT const *)` | 163 (0xa3) | Exported Function | 0x10025fc0 | 0x00025fc0
`public: int __thiscall ParsedObjectPath::AddKeyRefEx(unsigned short const *,struct tagVARIANT const *)` | 164 (0xa4) | Exported Function | 0x10026060 | 0x00026060
`public: int __thiscall ParsedObjectPath::AddNamespace(unsigned short const *)` | 165 (0xa5) | Exported Function | 0x100140c0 | 0x000140c0
`public: int __thiscall ParsedObjectPath::IsClass(void)` | 410 (0x19a) | Exported Function | 0x10015350 | 0x00015350
`public: int __thiscall ParsedObjectPath::IsInstance(void)` | 415 (0x19f) | Exported Function | 0x10015320 | 0x00015320
`public: int __thiscall ParsedObjectPath::IsLocal(unsigned short const *)` | 416 (0x1a0) | Exported Function | 0x100128c0 | 0x000128c0
`public: int __thiscall ParsedObjectPath::IsObject(void)` | 420 (0x1a4) | Exported Function | 0x10015380 | 0x00015380
`public: int __thiscall ParsedObjectPath::IsRelative(unsigned short const *,unsigned short const *)` | 425 (0x1a9) | Exported Function | 0x10012880 | 0x00012880
`public: int __thiscall ParsedObjectPath::SetClassName(unsigned short const *)` | 504 (0x1f8) | Exported Function | 0x100268a0 | 0x000268a0
`public: int __thiscall CObjectPathParser::Parse(unsigned short const *,struct ParsedObjectPath * *)` | 457 (0x1c9) | Exported Function | 0x100138b0 | 0x000138b0
`public: int __thiscall CHStringArray::GetUpperBound(void)const ` | 376 (0x178) | Exported Function | 0x1001fd90 | 0x0001fd90
`public: int __thiscall CHStringArray::GetSize(void)const ` | 366 (0x16e) | Exported Function | 0x10009120 | 0x00009120
`public: int __thiscall CHStringArray::Append(class CHStringArray const &)` | 179 (0xb3) | Exported Function | 0x10028c30 | 0x00028c30
`public: int __thiscall CHPtrArray::Add(void *)` | 159 (0x9f) | Exported Function | 0x10014b60 | 0x00014b60
`public: int __thiscall CHPtrArray::Append(class CHPtrArray const &)` | 178 (0xb2) | Exported Function | 0x10028f30 | 0x00028f30
`public: int __thiscall CHPtrArray::GetSize(void)const ` | 365 (0x16d) | Exported Function | 0x10009120 | 0x00009120
`public: int __thiscall CHPtrArray::GetUpperBound(void)const ` | 375 (0x177) | Exported Function | 0x1001fd90 | 0x0001fd90
`public: int __thiscall CHString::Collate(unsigned short const *)const ` | 193 (0xc1) | Exported Function | 0x1001fcb0 | 0x0001fcb0
`public: int __thiscall CHString::Compare(unsigned short const *)const ` | 196 (0xc4) | Exported Function | 0x1000ec10 | 0x0000ec10
`public: int __thiscall CHString::CompareNoCase(unsigned short const *)const ` | 197 (0xc5) | Exported Function | 0x10015070 | 0x00015070
`public: static void __stdcall CWbemProviderGlue::IncrementObjectCount(void)` | 395 (0x18b) | Exported Function | 0x10024f20 | 0x00024f20
`public: int __thiscall CHString::Find(unsigned short const *)const ` | 252 (0xfc) | Exported Function | 0x10008220 | 0x00008220
`public: int __thiscall CHString::FindOneOf(unsigned short const *)const ` | 253 (0xfd) | Exported Function | 0x10028000 | 0x00028000
`public: int __thiscall CHString::GetAllocLength(void)const ` | 276 (0x114) | Exported Function | 0x1001fd00 | 0x0001fd00
`public: int __thiscall CHString::GetLength(void)const ` | 331 (0x14b) | Exported Function | 0x10008840 | 0x00008840
`public: int __thiscall CHString::IsEmpty(void)const ` | 412 (0x19c) | Exported Function | 0x10008700 | 0x00008700
`public: int __thiscall CHString::LoadStringW(unsigned int)` | 429 (0x1ad) | Exported Function | 0x10028150 | 0x00028150
`public: int __thiscall CHString::ReverseFind(unsigned short)const ` | 485 (0x1e5) | Exported Function | 0x100091a0 | 0x000091a0
`public: int __thiscall CHStringArray::Add(unsigned short const *)` | 160 (0xa0) | Exported Function | 0x10010cf0 | 0x00010cf0
`public: int __thiscall CHString::Find(unsigned short)const ` | 251 (0xfb) | Exported Function | 0x100086d0 | 0x000086d0
`public: class CHStringArray & __thiscall CHStringArray::operator=(class CHStringArray const &)` | 84 (0x54) | Exported Function | 0x1001f700 | 0x0001f700
`public: struct HKEY__ * __thiscall CRegistry::GethKey(void)` | 390 (0x186) | Exported Function | 0x10009120 | 0x00009120
`public: struct IWbemClassObject * __thiscall MethodContext::GetStatusObject(void)` | 369 (0x171) | Exported Function | 0x1000f9e0 | 0x0000f9e0
`public: void * __thiscall CHPtrArray::GetAt(int)const ` | 277 (0x115) | Exported Function | 0x10008e90 | 0x00008e90
`public: void * __thiscall CHPtrArray::operator[](int)const ` | 116 (0x74) | Exported Function | 0x10008e90 | 0x00008e90
`public: void __cdecl CHString::Format(unsigned int,...)` | 256 (0x100) | Exported Function | 0x100125b0 | 0x000125b0
`public: void __cdecl CHString::Format(unsigned short const *,...)` | 257 (0x101) | Exported Function | 0x10006bd0 | 0x00006bd0
`public: void __cdecl CHString::FormatMessageW(unsigned int,...)` | 258 (0x102) | Exported Function | 0x100125b0 | 0x000125b0
`public: void __cdecl CHString::FormatMessageW(unsigned short const *,...)` | 259 (0x103) | Exported Function | 0x10028030 | 0x00028030
`public: void __cdecl ProviderLog::LocalLogMessage(unsigned short const *,int,enum ProviderLog::LogLevel,unsigned short const *,...)` | 430 (0x1ae) | Exported Function | 0x1000b9a0 | 0x0000b9a0
`public: void __thiscall CFrameworkQuery::GetRequiredProperties(class CHStringArray &)` | 363 (0x16b) | Exported Function | 0x100208c0 | 0x000208c0
`public: void __thiscall CFrameworkQuery::Init2(struct IWbemClassObject *)` | 396 (0x18c) | Exported Function | 0x1000afa0 | 0x0000afa0
`public: void __thiscall CFrameworkQueryEx::GetPropertyBitMask(class CHPtrArray const &,void *)` | 357 (0x165) | Exported Function | 0x10014a10 | 0x00014a10
`public: void __thiscall CHPtrArray::Copy(class CHPtrArray const &)` | 200 (0xc8) | Exported Function | 0x10028f80 | 0x00028f80
`public: void __thiscall CHPtrArray::FreeExtra(void)` | 268 (0x10c) | Exported Function | 0x10028ce0 | 0x00028ce0
`public: void __thiscall CHPtrArray::InsertAt(int,class CHPtrArray *)` | 404 (0x194) | Exported Function | 0x10028fc0 | 0x00028fc0
`public: void __thiscall CHPtrArray::InsertAt(int,void *,int)` | 405 (0x195) | Exported Function | 0x10029010 | 0x00029010
`public: void __thiscall CHPtrArray::RemoveAll(void)` | 479 (0x1df) | Exported Function | 0x1000a2e0 | 0x0000a2e0
`public: void * * __thiscall CHPtrArray::GetData(void)` | 312 (0x138) | Exported Function | 0x10008920 | 0x00008920
`public: void __thiscall CHPtrArray::RemoveAt(int,int)` | 481 (0x1e1) | Exported Function | 0x10029160 | 0x00029160
`public: void * & __thiscall CHPtrArray::operator[](int)` | 115 (0x73) | Exported Function | 0x10008200 | 0x00008200
`public: virtual void __thiscall MethodContext::QueryPostProcess(void)` | 469 (0x1d5) | Exported Function | 0x100125b0 | 0x000125b0
`public: virtual long __stdcall CWbemProviderGlue::GetObjectAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 354 (0x162) | Exported Function | 0x100131a0 | 0x000131a0
`public: virtual long __stdcall CWbemProviderGlue::Initialize(unsigned short *,long,unsigned short *,unsigned short *,struct IWbemServices *,struct IWbemContext *,struct IWbemProviderInitSink *)` | 403 (0x193) | Exported Function | 0x100111d0 | 0x000111d0
`public: virtual long __stdcall CWbemProviderGlue::OpenNamespace(unsigned short * const,long,struct IWbemContext *,struct IWbemServices * *,struct IWbemCallResult * *)` | 455 (0x1c7) | Exported Function | 0x1001fcf0 | 0x0001fcf0
`public: virtual long __stdcall CWbemProviderGlue::PutClass(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemCallResult * *)` | 460 (0x1cc) | Exported Function | 0x1001fcd0 | 0x0001fcd0
`public: virtual long __stdcall CWbemProviderGlue::PutClassAsync(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemObjectSink *)` | 461 (0x1cd) | Exported Function | 0x1001fcd0 | 0x0001fcd0
`public: virtual long __stdcall CWbemProviderGlue::PutInstance(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemCallResult * *)` | 462 (0x1ce) | Exported Function | 0x1001fcd0 | 0x0001fcd0
`public: virtual long __stdcall CWbemProviderGlue::PutInstanceAsync(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemObjectSink *)` | 465 (0x1d1) | Exported Function | 0x10025460 | 0x00025460
`public: virtual long __stdcall CWbemProviderGlue::QueryInterface(struct _GUID const &,void * *)` | 467 (0x1d3) | Exported Function | 0x1000b360 | 0x0000b360
`public: virtual long __stdcall CWbemProviderGlue::QueryObjectSink(long,struct IWbemObjectSink * *)` | 468 (0x1d4) | Exported Function | 0x1001fdf0 | 0x0001fdf0
`public: virtual long __thiscall CFrameworkQueryEx::InitEx(unsigned short * const,unsigned short * const,long,class CHString &)` | 402 (0x192) | Exported Function | 0x10020fd0 | 0x00020fd0
`public: virtual struct IWbemContext * __thiscall MethodContext::GetIWBEMContext(void)` | 323 (0x143) | Exported Function | 0x10009a00 | 0x00009a00
`public: virtual unsigned long __stdcall CWbemGlueFactory::AddRef(void)` | 169 (0xa9) | Exported Function | 0x10010c40 | 0x00010c40
`public: virtual unsigned long __stdcall CWbemGlueFactory::Release(void)` | 475 (0x1db) | Exported Function | 0x10010c80 | 0x00010c80
`public: virtual unsigned long __stdcall CWbemProviderGlue::AddRef(void)` | 170 (0xaa) | Exported Function | 0x1000d310 | 0x0000d310
`public: virtual unsigned long __stdcall CWbemProviderGlue::Release(void)` | 476 (0x1dc) | Exported Function | 0x1000d290 | 0x0000d290
`public: void * & __thiscall CHPtrArray::ElementAt(int)` | 231 (0xe7) | Exported Function | 0x10008200 | 0x00008200
`public: virtual long __stdcall CWbemProviderGlue::GetObject(unsigned short * const,long,struct IWbemContext *,struct IWbemClassObject * *,struct IWbemCallResult * *)` | 350 (0x15e) | Exported Function | 0x1001fcf0 | 0x0001fcf0
`public: void __thiscall CHPtrArray::SetAt(int,void *)` | 491 (0x1eb) | Exported Function | 0x100291b0 | 0x000291b0
`public: void __thiscall CHPtrArray::SetSize(int,int)` | 522 (0x20a) | Exported Function | 0x1000a2f0 | 0x0000a2f0
`public: void __thiscall CHStringArray::SetAtGrow(int,unsigned short const *)` | 495 (0x1ef) | Exported Function | 0x1000f890 | 0x0000f890
`public: void __thiscall CHStringArray::SetSize(int,int)` | 523 (0x20b) | Exported Function | 0x1000f610 | 0x0000f610
`public: void __thiscall CObjectPathParser::``default constructor closure'(void)` | 157 (0x9d) | Exported Function | 0x1001fc60 | 0x0001fc60
`public: void __thiscall CObjectPathParser::Free(struct ParsedObjectPath *)` | 267 (0x10b) | Exported Function | 0x10012850 | 0x00012850
`public: void __thiscall CRegistry::Close(void)` | 191 (0xbf) | Exported Function | 0x10010e20 | 0x00010e20
`public: void __thiscall CRegistry::RewindSubKeys(void)` | 486 (0x1e6) | Exported Function | 0x10029fb0 | 0x00029fb0
`public: void __thiscall CThreadBase::``default constructor closure'(void)` | 158 (0x9e) | Exported Function | 0x1001fc80 | 0x0001fc80
`public: void __thiscall CThreadBase::EndRead(void)` | 235 (0xeb) | Exported Function | 0x10009190 | 0x00009190
`public: void __thiscall CThreadBase::EndWrite(void)` | 236 (0xec) | Exported Function | 0x10009190 | 0x00009190
`public: void __thiscall CWbemGlueFactory::Destroy(void)` | 229 (0xe5) | Exported Function | 0x10020520 | 0x00020520
`public: void __thiscall ParsedObjectPath::ClearKeys(void)` | 190 (0xbe) | Exported Function | 0x100262a0 | 0x000262a0
`public: void __thiscall ProviderLog::LocalLogMessage(unsigned short const *,unsigned short const *,int,enum ProviderLog::LogLevel)` | 431 (0x1af) | Exported Function | 0x1000e520 | 0x0000e520
`public: void __thiscall WBEMTime::Clear(void)` | 188 (0xbc) | Exported Function | 0x1001fca0 | 0x0001fca0
`public: void __thiscall WBEMTimeSpan::Clear(void)` | 189 (0xbd) | Exported Function | 0x1001fca0 | 0x0001fca0
`public: void const * * __thiscall CHPtrArray::GetData(void)const ` | 313 (0x139) | Exported Function | 0x10008920 | 0x00008920
`public: void __thiscall CHStringArray::SetAt(int,unsigned short const *)` | 493 (0x1ed) | Exported Function | 0x1001fe00 | 0x0001fe00
`public: void __thiscall CHPtrArray::SetAtGrow(int,void *)` | 494 (0x1ee) | Exported Function | 0x100291d0 | 0x000291d0
`public: void __thiscall CHStringArray::RemoveAt(int,int)` | 482 (0x1e2) | Exported Function | 0x10028ed0 | 0x00028ed0
`public: void __thiscall CHStringArray::InsertAt(int,unsigned short const *,int)` | 407 (0x197) | Exported Function | 0x10028e00 | 0x00028e00
`public: void __thiscall CHString::Empty(void)` | 233 (0xe9) | Exported Function | 0x100080d0 | 0x000080d0
`public: void __thiscall CHString::FormatV(unsigned short const *,char *)` | 260 (0x104) | Exported Function | 0x10006bf0 | 0x00006bf0
`public: void __thiscall CHString::FreeExtra(void)` | 269 (0x10d) | Exported Function | 0x100280c0 | 0x000280c0
`public: void __thiscall CHString::MakeLower(void)` | 440 (0x1b8) | Exported Function | 0x10028190 | 0x00028190
`public: void __thiscall CHString::MakeReverse(void)` | 441 (0x1b9) | Exported Function | 0x100281b0 | 0x000281b0
`public: void __thiscall CHString::MakeUpper(void)` | 442 (0x1ba) | Exported Function | 0x1000f870 | 0x0000f870
`public: void __thiscall CHString::Release(void)` | 471 (0x1d7) | Exported Function | 0x1000d0f0 | 0x0000d0f0
`public: void __thiscall CHString::ReleaseBuffer(int)` | 478 (0x1de) | Exported Function | 0x10008620 | 0x00008620
`public: void __thiscall CHString::SetAt(int,unsigned short)` | 492 (0x1ec) | Exported Function | 0x100153a0 | 0x000153a0
`public: void __thiscall CHString::TrimLeft(void)` | 539 (0x21b) | Exported Function | 0x10028210 | 0x00028210
`public: void __thiscall CHString::TrimRight(void)` | 540 (0x21c) | Exported Function | 0x10028290 | 0x00028290
`public: void __thiscall CHString::UnlockBuffer(void)` | 545 (0x221) | Exported Function | 0x10028300 | 0x00028300
`public: void __thiscall CHStringArray::Copy(class CHStringArray const &)` | 201 (0xc9) | Exported Function | 0x10028c80 | 0x00028c80
`public: void __thiscall CHStringArray::FreeExtra(void)` | 270 (0x10e) | Exported Function | 0x10028ce0 | 0x00028ce0
`public: void __thiscall CHStringArray::InsertAt(int,class CHStringArray *)` | 406 (0x196) | Exported Function | 0x10028d50 | 0x00028d50
`public: void __thiscall CHStringArray::RemoveAll(void)` | 480 (0x1e0) | Exported Function | 0x100153d0 | 0x000153d0
`public: virtual long __stdcall CWbemProviderGlue::ExecQueryAsync(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 247 (0xf7) | Exported Function | 0x1000b540 | 0x0000b540
`public: virtual long __stdcall CWbemProviderGlue::ExecQuery(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 245 (0xf5) | Exported Function | 0x1001fcf0 | 0x0001fcf0
`public: virtual long __stdcall CWbemProviderGlue::ExecNotificationQueryAsync(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 244 (0xf4) | Exported Function | 0x1001fcf0 | 0x0001fcf0
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyValue(unsigned short const *,class CHString &)` | 306 (0x132) | Exported Function | 0x10029b40 | 0x00029b40
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyValue(unsigned short const *,unsigned long &)` | 305 (0x131) | Exported Function | 0x10029b10 | 0x00029b10
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyValue(unsigned short const *,void *,unsigned long *)` | 307 (0x133) | Exported Function | 0x10029b70 | 0x00029b70
`public: unsigned long __thiscall CRegistry::GetLongestClassStringSize(void)` | 338 (0x152) | Exported Function | 0x10020440 | 0x00020440
`public: unsigned long __thiscall CRegistry::GetLongestSubKeySize(void)` | 339 (0x153) | Exported Function | 0x10020450 | 0x00020450
`public: unsigned long __thiscall CRegistry::GetLongestValueData(void)` | 340 (0x154) | Exported Function | 0x10020460 | 0x00020460
`public: unsigned long __thiscall CRegistry::GetLongestValueName(void)` | 341 (0x155) | Exported Function | 0x10020470 | 0x00020470
`public: unsigned long __thiscall CRegistry::GetValueCount(void)` | 377 (0x179) | Exported Function | 0x10020480 | 0x00020480
`public: unsigned long __thiscall CRegistry::NextSubKey(void)` | 446 (0x1be) | Exported Function | 0x10029e00 | 0x00029e00
`public: unsigned long __thiscall CRegistry::OpenCurrentUser(unsigned short const *,unsigned long)` | 453 (0x1c5) | Exported Function | 0x10029e70 | 0x00029e70
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHString &)` | 507 (0x1fb) | Exported Function | 0x1002a210 | 0x0002a210
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHStringArray &)` | 508 (0x1fc) | Exported Function | 0x1002a250 | 0x0002a250
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(struct HKEY__ *,unsigned short const *,unsigned long &)` | 506 (0x1fa) | Exported Function | 0x1002a1e0 | 0x0002a1e0
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(unsigned short const *,class CHString &)` | 510 (0x1fe) | Exported Function | 0x1002a400 | 0x0002a400
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(unsigned short const *,class CHStringArray &)` | 511 (0x1ff) | Exported Function | 0x1002a440 | 0x0002a440
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyPath(class CHString &)` | 304 (0x130) | Exported Function | 0x10029a60 | 0x00029a60
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(unsigned short const *,unsigned long &)` | 509 (0x1fd) | Exported Function | 0x1002a3d0 | 0x0002a3d0
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyName(class CHString &)` | 303 (0x12f) | Exported Function | 0x100299d0 | 0x000299d0
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(unsigned short const *,unsigned long &)` | 297 (0x129) | Exported Function | 0x10010d10 | 0x00010d10
`public: struct KeyRef & __thiscall KeyRef::operator=(struct KeyRef const &)` | 94 (0x5e) | Exported Function | 0x1001f7c0 | 0x0001f7c0
`public: struct ParsedObjectPath & __thiscall ParsedObjectPath::operator=(struct ParsedObjectPath const &)` | 96 (0x60) | Exported Function | 0x1001f8c0 | 0x0001f8c0
`public: unsigned __int64 __thiscall WBEMTime::GetTime(void)const ` | 372 (0x174) | Exported Function | 0x1001fd80 | 0x0001fd80
`public: unsigned __int64 __thiscall WBEMTimeSpan::GetTime(void)const ` | 373 (0x175) | Exported Function | 0x1001fd80 | 0x0001fd80
`public: unsigned long __thiscall CAutoEvent::Wait(unsigned long)` | 557 (0x22d) | Exported Function | 0x10027350 | 0x00027350
`public: unsigned long __thiscall CRegistry::DeleteCurrentKeyValue(struct HKEY__ *,unsigned short const *)` | 221 (0xdd) | Exported Function | 0x10029490 | 0x00029490
`public: unsigned long __thiscall CRegistry::DeleteCurrentKeyValue(unsigned short const *)` | 222 (0xde) | Exported Function | 0x100294b0 | 0x000294b0
`public: unsigned long __thiscall CRegistry::GetCurrentBinaryKeyValue(struct HKEY__ *,unsigned short const *,unsigned char *,unsigned long *)` | 291 (0x123) | Exported Function | 0x100296a0 | 0x000296a0
`public: unsigned long __thiscall CRegistry::GetCurrentBinaryKeyValue(unsigned short const *,class CHString &)` | 292 (0x124) | Exported Function | 0x100296d0 | 0x000296d0
`public: unsigned long __thiscall CRegistry::GetCurrentBinaryKeyValue(unsigned short const *,unsigned char *,unsigned long *)` | 293 (0x125) | Exported Function | 0x10015280 | 0x00015280
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHString &)` | 295 (0x127) | Exported Function | 0x1000edd0 | 0x0000edd0
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHStringArray &)` | 296 (0x128) | Exported Function | 0x10029830 | 0x00029830
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(struct HKEY__ *,unsigned short const *,unsigned long &)` | 294 (0x126) | Exported Function | 0x10010d30 | 0x00010d30
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(unsigned short const *,class CHString &)` | 298 (0x12a) | Exported Function | 0x1000b300 | 0x0000b300
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(unsigned short const *,class CHStringArray &)` | 299 (0x12b) | Exported Function | 0x10029940 | 0x00029940
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyCount(void)` | 302 (0x12e) | Exported Function | 0x10020430 | 0x00020430
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValueExpand(struct HKEY__ *,unsigned short const *,class CHString &)` | 512 (0x200) | Exported Function | 0x1002a460 | 0x0002a460
`public: unsigned short * __thiscall CFrameworkQuery::GetQueryClassName(void)` | 361 (0x169) | Exported Function | 0x1001fd60 | 0x0001fd60
`public: unsigned short * __thiscall CHString::AllocSysString(void)const ` | 177 (0xb1) | Exported Function | 0x10027fb0 | 0x00027fb0
`public: virtual long __stdcall CWbemGlueFactory::LockServer(int)` | 437 (0x1b5) | Exported Function | 0x10020540 | 0x00020540
`public: virtual long __stdcall CWbemGlueFactory::QueryInterface(struct _GUID const &,void * *)` | 466 (0x1d2) | Exported Function | 0x100110b0 | 0x000110b0
`public: virtual long __stdcall CWbemProviderGlue::CancelAsyncCall(struct IWbemObjectSink *)` | 183 (0xb7) | Exported Function | 0x1001fc90 | 0x0001fc90
`public: virtual long __stdcall CWbemProviderGlue::CancelAsyncRequest(long)` | 184 (0xb8) | Exported Function | 0x1001fc90 | 0x0001fc90
`public: virtual long __stdcall CWbemProviderGlue::CreateClassEnum(unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 205 (0xcd) | Exported Function | 0x1001fcd0 | 0x0001fcd0
`public: virtual long __stdcall CWbemProviderGlue::CreateClassEnumAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 206 (0xce) | Exported Function | 0x1001fcd0 | 0x0001fcd0
`public: virtual long __stdcall CWbemProviderGlue::CreateInstanceEnum(unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 208 (0xd0) | Exported Function | 0x1001fcd0 | 0x0001fcd0
`public: virtual long __stdcall CWbemProviderGlue::CreateInstanceEnumAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 210 (0xd2) | Exported Function | 0x1000bc60 | 0x0000bc60
`public: virtual long __stdcall CWbemProviderGlue::DeleteClass(unsigned short * const,long,struct IWbemContext *,struct IWbemCallResult * *)` | 219 (0xdb) | Exported Function | 0x1001fcd0 | 0x0001fcd0
`public: virtual long __stdcall CWbemProviderGlue::DeleteClassAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 220 (0xdc) | Exported Function | 0x1001fcd0 | 0x0001fcd0
`public: virtual long __stdcall CWbemProviderGlue::DeleteInstance(unsigned short * const,long,struct IWbemContext *,struct IWbemCallResult * *)` | 223 (0xdf) | Exported Function | 0x1001fcd0 | 0x0001fcd0
`public: virtual long __stdcall CWbemProviderGlue::DeleteInstanceAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 226 (0xe2) | Exported Function | 0x10023510 | 0x00023510
`public: virtual long __stdcall CWbemProviderGlue::ExecMethod(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemClassObject *,struct IWbemClassObject * *,struct IWbemCallResult * *)` | 239 (0xef) | Exported Function | 0x1001fce0 | 0x0001fce0
`public: virtual long __stdcall CWbemProviderGlue::ExecMethodAsync(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemClassObject *,struct IWbemObjectSink *)` | 242 (0xf2) | Exported Function | 0x100239d0 | 0x000239d0
`public: virtual long __stdcall CWbemProviderGlue::ExecNotificationQuery(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 243 (0xf3) | Exported Function | 0x1001fcf0 | 0x0001fcf0
`public: virtual long __stdcall CWbemGlueFactory::CreateInstance(struct IUnknown *,struct _GUID const &,void * *)` | 207 (0xcf) | Exported Function | 0x10011390 | 0x00011390
`public: virtual bool __thiscall CFrameworkQueryEx::IsExtended(void)` | 413 (0x19d) | Exported Function | 0x1000aa10 | 0x0000aa10
`public: virtual __thiscall ProviderLog::~ProviderLog(void)` | 72 (0x48) | Exported Function | 0x10011160 | 0x00011160
`public: virtual __thiscall Provider::~Provider(void)` | 71 (0x47) | Exported Function | 0x1000d350 | 0x0000d350
`public: unsigned short * __thiscall CHString::GetBuffer(int)` | 282 (0x11a) | Exported Function | 0x100079e0 | 0x000079e0
`public: unsigned short * __thiscall CHString::GetBufferSetLength(int)` | 283 (0x11b) | Exported Function | 0x100079a0 | 0x000079a0
`public: unsigned short * __thiscall CHString::LockBuffer(void)` | 434 (0x1b2) | Exported Function | 0x10028160 | 0x00028160
`public: unsigned short * __thiscall CRegistry::GetClassNameW(void)` | 287 (0x11f) | Exported Function | 0x10020420 | 0x00020420
`public: unsigned short * __thiscall ParsedObjectPath::GetKeyString(void)` | 330 (0x14a) | Exported Function | 0x10026330 | 0x00026330
`public: unsigned short * __thiscall ParsedObjectPath::GetNamespacePart(void)` | 348 (0x15c) | Exported Function | 0x100265f0 | 0x000265f0
`public: unsigned short * __thiscall ParsedObjectPath::GetParentNamespacePart(void)` | 355 (0x163) | Exported Function | 0x10026730 | 0x00026730
`public: struct IWbemClassObject * __thiscall CInstance::GetClassObjectInterface(void)` | 288 (0x120) | Exported Function | 0x10013730 | 0x00013730
`public: unsigned short * __thiscall WBEMTime::GetBSTR(void)const ` | 280 (0x118) | Exported Function | 0x10028610 | 0x00028610
`public: unsigned short * __thiscall WBEMTime::GetDMTFNonNtfs(void)const ` | 309 (0x135) | Exported Function | 0x100286f0 | 0x000286f0
`public: unsigned short * __thiscall WBEMTimeSpan::GetBSTR(void)const ` | 281 (0x119) | Exported Function | 0x10028620 | 0x00028620
`public: unsigned short __thiscall CHString::GetAt(int)const ` | 278 (0x116) | Exported Function | 0x100153e0 | 0x000153e0
`public: unsigned short __thiscall CHString::operator[](int)const ` | 117 (0x75) | Exported Function | 0x100153e0 | 0x000153e0
`public: virtual __thiscall CInstance::~CInstance(void)` | 59 (0x3b) | Exported Function | 0x10021520 | 0x00021520
`public: virtual __thiscall CThreadBase::~CThreadBase(void)` | 63 (0x3f) | Exported Function | 0x1000a4f0 | 0x0000a4f0
`public: virtual __thiscall MethodContext::~MethodContext(void)` | 69 (0x45) | Exported Function | 0x100141a0 | 0x000141a0
`public: unsigned short * __thiscall WBEMTime::GetDMTF(int)const ` | 308 (0x134) | Exported Function | 0x10015090 | 0x00015090
`unsigned long __stdcall NormalizePath(unsigned short const *,unsigned short const *,unsigned short const *,unsigned long,class CHString &)` | 448 (0x1c0) | Exported Function | 0x10012e70 | 0x00012e70
`public: class CHString const * __thiscall CHStringArray::GetData(void)const ` | 316 (0x13c) | Exported Function | 0x10008920 | 0x00008920
`public: class CHString const & __thiscall CHString::operator=(unsigned short const *)` | 83 (0x53) | Exported Function | 0x1000cf70 | 0x0000cf70
`private: static void __stdcall Provider::InitComputerName(void)` | 401 (0x191) | Exported Function | 0x1000e790 | 0x0000e790
`private: struct IWbemClassObject * __thiscall Provider::GetClassObjectInterface(class MethodContext *)` | 289 (0x121) | Exported Function | 0x1000aac0 | 0x0000aac0
`private: struct IWbemServices * __stdcall CWbemProviderGlue::InternalGetNamespaceConnection(unsigned short const *)` | 408 (0x198) | Exported Function | 0x1000ae40 | 0x0000ae40
`private: unsigned long __thiscall CRegistry::GetCurrentRawKeyValue(struct HKEY__ *,unsigned short const *,void *,unsigned long *,unsigned long *)` | 300 (0x12c) | Exported Function | 0x10029960 | 0x00029960
`private: unsigned long __thiscall CRegistry::GetCurrentRawSubKeyValue(unsigned short const *,void *,unsigned long *,unsigned long *)` | 301 (0x12d) | Exported Function | 0x10029990 | 0x00029990
`private: unsigned long __thiscall CRegistry::OpenSubKey(void)` | 456 (0x1c8) | Exported Function | 0x10029f30 | 0x00029f30
`private: void __thiscall CFrameworkQuery::Reset(void)` | 484 (0x1e4) | Exported Function | 0x1000ff40 | 0x0000ff40
`private: void __thiscall CObjectPathParser::Empty(void)` | 234 (0xea) | Exported Function | 0x10013660 | 0x00013660
`private: void __thiscall CObjectPathParser::Zero(void)` | 559 (0x22f) | Exported Function | 0x100269e0 | 0x000269e0
`private: void __thiscall CRegistry::CloseSubKey(void)` | 192 (0xc0) | Exported Function | 0x100293b0 | 0x000293b0
`private: void __thiscall CRegistry::PrepareToReOpen(void)` | 459 (0x1cb) | Exported Function | 0x10029f90 | 0x00029f90
`private: void __thiscall CRegistry::SetDefaultValues(void)` | 517 (0x205) | Exported Function | 0x10008080 | 0x00008080
`private: void __thiscall CRegistrySearch::CheckAndAddToList(class CRegistry *,class CHString,class CHString,class CHPtrArray &,class CHString,class CHString,int)` | 185 (0xb9) | Exported Function | 0x10029280 | 0x00029280
`private: void __thiscall CThreadBase::Lock(void)` | 433 (0x1b1) | Exported Function | 0x1001fda0 | 0x0001fda0
`private: void __thiscall CThreadBase::Unlock(void)` | 544 (0x220) | Exported Function | 0x10009190 | 0x00009190
`private: static void __stdcall CWinMsgEvent::WindowsDispatch(void)` | 558 (0x22e) | Exported Function | 0x10027370 | 0x00027370
`private: void __thiscall CWbemProviderGlue::AddFlushPtr(void *)` | 161 (0xa1) | Exported Function | 0x1000fa60 | 0x0000fa60
`private: static void __stdcall CWinMsgEvent::DestroyMsgWindow(void)` | 230 (0xe6) | Exported Function | 0x10026e50 | 0x00026e50
`private: static void __stdcall CWbemProviderGlue::UnlockProviderMap(void)` | 547 (0x223) | Exported Function | 0x1001fe50 | 0x0001fe50
`private: static struct IWbemClassObject * __stdcall CWbemProviderGlue::GetStatusObject(class MethodContext *,unsigned short const *)` | 368 (0x170) | Exported Function | 0x10024dc0 | 0x00024dc0
`private: static struct IWbemClassObject * CWbemProviderGlue::m_pStatusObject` | 574 (0x23e) | Exported Function | 0x10037e7c | 0x00037e7c
`private: static unsigned long __stdcall CWinMsgEvent::dwThreadProc(void *)` | 562 (0x232) | Exported Function | 0x10027470 | 0x00027470
`private: static unsigned long CRegistry::s_dwPlatform` | 603 (0x25b) | Exported Function | 0x10037e8c | 0x00037e8c
`private: static unsigned long CWbemProviderGlue::s_dwMajorVersion` | 602 (0x25a) | Exported Function | 0x10037e70 | 0x00037e70
`private: static unsigned long CWbemProviderGlue::s_dwPlatform` | 604 (0x25c) | Exported Function | 0x10037e74 | 0x00037e74
`private: static unsigned short * CWbemProviderGlue::s_wstrCSDVersion` | 610 (0x262) | Exported Function | 0x10037c68 | 0x00037c68
`private: static void * CWinMsgEvent::mg_hDevNotify` | 578 (0x242) | Exported Function | 0x10038158 | 0x00038158
`private: static void * CWinMsgEvent::mg_hThreadPumpHandle` | 579 (0x243) | Exported Function | 0x10038160 | 0x00038160
`private: static void __stdcall CWbemProviderGlue::GetComputerNameW(class CHString &)` | 290 (0x122) | Exported Function | 0x100144d0 | 0x000144d0
`private: static void __stdcall CWbemProviderGlue::Init(void)` | 400 (0x190) | Exported Function | 0x10009940 | 0x00009940
`private: static void __stdcall CWbemProviderGlue::LockFactoryMap(void)` | 435 (0x1b3) | Exported Function | 0x1001fdb0 | 0x0001fdb0
`private: static void __stdcall CWbemProviderGlue::LockProviderMap(void)` | 436 (0x1b4) | Exported Function | 0x1001fdd0 | 0x0001fdd0
`private: static void __stdcall CWbemProviderGlue::UnInit(void)` | 541 (0x21d) | Exported Function | 0x10025b30 | 0x00025b30
`private: static void __stdcall CWbemProviderGlue::UnlockFactoryMap(void)` | 546 (0x222) | Exported Function | 0x1001fe30 | 0x0001fe30
`private: static void __stdcall CWinMsgEvent::CreateMsgProvider(void)` | 211 (0xd3) | Exported Function | 0x10026cf0 | 0x00026cf0
`private: static struct HWND__ * CWinMsgEvent::mg_hWnd` | 580 (0x244) | Exported Function | 0x1003815c | 0x0003815c
`private: void __thiscall CWbemProviderGlue::FlushAll(void)` | 255 (0xff) | Exported Function | 0x10009660 | 0x00009660
`protected: bool __thiscall CWinMsgEvent::UnRegisterMessage(unsigned int,int)` | 543 (0x21f) | Exported Function | 0x10027260 | 0x00027260
`protected: static void __stdcall CWbemProviderGlue::RemoveFromFactoryMap(class CWbemGlueFactory const *)` | 483 (0x1e3) | Exported Function | 0x10011450 | 0x00011450
`protected: struct CHStringData * __thiscall CHString::GetData(void)const ` | 314 (0x13a) | Exported Function | 0x100090b0 | 0x000090b0
`protected: unsigned long __thiscall CFrameworkQuery::IsInList(class CHStringArray const &,unsigned short const *)` | 414 (0x19e) | Exported Function | 0x1000f4a0 | 0x0000f4a0
`protected: virtual long __thiscall Provider::DeleteInstance(class CInstance const &,long)` | 225 (0xe1) | Exported Function | 0x10022c90 | 0x00022c90
`protected: virtual long __thiscall Provider::EnumerateInstances(class MethodContext *,long)` | 238 (0xee) | Exported Function | 0x10022c90 | 0x00022c90
`protected: virtual long __thiscall Provider::ExecMethod(class CInstance const &,unsigned short * const,class CInstance *,class CInstance *,long)` | 241 (0xf1) | Exported Function | 0x10022d60 | 0x00022d60
`protected: virtual long __thiscall Provider::ExecQuery(class MethodContext *,class CFrameworkQuery &,long)` | 246 (0xf6) | Exported Function | 0x10009610 | 0x00009610
`protected: virtual long __thiscall Provider::GetObject(class CInstance *,long)` | 352 (0x160) | Exported Function | 0x10022c90 | 0x00022c90
`protected: virtual long __thiscall Provider::GetObject(class CInstance *,long,class CFrameworkQuery &)` | 353 (0x161) | Exported Function | 0x10014fe0 | 0x00014fe0
`protected: virtual long __thiscall Provider::PutInstance(class CInstance const &,long)` | 464 (0x1d0) | Exported Function | 0x10022c90 | 0x00022c90
`protected: virtual long __thiscall Provider::ValidateDeletionFlags(long)` | 549 (0x225) | Exported Function | 0x10022e20 | 0x00022e20
`protected: virtual long __thiscall Provider::ValidateEnumerationFlags(long)` | 550 (0x226) | Exported Function | 0x10009170 | 0x00009170
`protected: virtual long __thiscall Provider::ValidateGetObjFlags(long)` | 552 (0x228) | Exported Function | 0x10009170 | 0x00009170
`protected: virtual long __thiscall Provider::ValidateMethodFlags(long)` | 554 (0x22a) | Exported Function | 0x10022e20 | 0x00022e20
`protected: virtual long __thiscall Provider::ValidatePutInstanceFlags(long)` | 555 (0x22b) | Exported Function | 0x10022e70 | 0x00022e70
`protected: static void __stdcall CWbemProviderGlue::AddToFactoryMap(class CWbemGlueFactory const *,long *)` | 172 (0xac) | Exported Function | 0x10011700 | 0x00011700
`private: void __thiscall ProviderLog::CheckFileSize(union _LARGE_INTEGER &,class CHString const &)` | 186 (0xba) | Exported Function | 0x10020390 | 0x00020390
`protected: static long __stdcall CWbemProviderGlue::IncrementMapCount(long *)` | 393 (0x189) | Exported Function | 0x10024f00 | 0x00024f00
`protected: static long __stdcall CWbemProviderGlue::DecrementMapCount(long *)` | 216 (0xd8) | Exported Function | 0x10009630 | 0x00009630
`protected: bool __thiscall Provider::GetLocalInstancePath(class CInstance const *,class CHString &)` | 333 (0x14d) | Exported Function | 0x10012000 | 0x00012000
`protected: bool __thiscall Provider::SetCreationClassName(class CInstance *)` | 505 (0x1f9) | Exported Function | 0x10007700 | 0x00007700
`protected: class CHString __thiscall Provider::MakeLocalPath(class CHString const &)` | 439 (0x1b7) | Exported Function | 0x10006b60 | 0x00006b60
`protected: class CHString const & __thiscall CFrameworkQuery::GetNamespace(void)` | 344 (0x158) | Exported Function | 0x10020710 | 0x00020710
`protected: class CHString const & __thiscall Provider::GetLocalComputerName(void)` | 332 (0x14c) | Exported Function | 0x10008eb0 | 0x00008eb0
`protected: class CHString const & __thiscall Provider::GetNamespace(void)` | 345 (0x159) | Exported Function | 0x100095b0 | 0x000095b0
`protected: class CHString const & __thiscall Provider::GetProviderName(void)` | 359 (0x167) | Exported Function | 0x1001fd50 | 0x0001fd50
`protected: class CInstance * __thiscall Provider::CreateNewInstance(class MethodContext *)` | 213 (0xd5) | Exported Function | 0x10009ed0 | 0x00009ed0
`protected: int __thiscall CFrameworkQuery::IsReference(unsigned short const *)` | 424 (0x1a8) | Exported Function | 0x10012080 | 0x00012080
`protected: int __thiscall CHString::LoadStringW(unsigned int,unsigned short *,unsigned int)` | 428 (0x1ac) | Exported Function | 0x10028140 | 0x00028140
`protected: long __thiscall Provider::Commit(class CInstance *,bool)` | 195 (0xc3) | Exported Function | 0x10022bb0 | 0x00022bb0
`protected: long __thiscall Provider::ValidateFlags(long,enum Provider::FlagDefs)` | 551 (0x227) | Exported Function | 0x10022e40 | 0x00022e40
`protected: static int __stdcall CHString::SafeStrlen(unsigned short const *)` | 488 (0x1e8) | Exported Function | 0x1000f410 | 0x0000f410
`protected: static long * __stdcall CWbemProviderGlue::GetMapCountPtr(class CWbemGlueFactory const *)` | 342 (0x156) | Exported Function | 0x10011690 | 0x00011690
`protected: static long __stdcall CWbemProviderGlue::DecrementMapCount(class CWbemGlueFactory const *)` | 217 (0xd9) | Exported Function | 0x10011610 | 0x00011610
`protected: static long __stdcall CWbemProviderGlue::IncrementMapCount(class CWbemGlueFactory const *)` | 394 (0x18a) | Exported Function | 0x100115a0 | 0x000115a0
`private: static struct HWND__ * __stdcall CWinMsgEvent::CreateMsgWindow(void)` | 212 (0xd4) | Exported Function | 0x10026d80 | 0x00026d80
`private: static long CWbemProviderGlue::s_lObjects` | 607 (0x25f) | Exported Function | 0x10038154 | 0x00038154
`private: static long __stdcall CWinMsgEvent::MsgWndProc(struct HWND__ *,unsigned int,unsigned int,long)` | 445 (0x1bd) | Exported Function | 0x10026ed0 | 0x00026ed0
`private: int __thiscall CObjectPathParser::ident_becomes_ns(void)` | 564 (0x234) | Exported Function | 0x10026a30 | 0x00026a30
`private: int __thiscall CObjectPathParser::key_const(void)` | 567 (0x237) | Exported Function | 0x10013ea0 | 0x00013ea0
`private: int __thiscall CObjectPathParser::keyref(void)` | 568 (0x238) | Exported Function | 0x10013dc0 | 0x00013dc0
`private: int __thiscall CObjectPathParser::keyref_list(void)` | 569 (0x239) | Exported Function | 0x100149d0 | 0x000149d0
`private: int __thiscall CObjectPathParser::keyref_term(void)` | 570 (0x23a) | Exported Function | 0x100149f0 | 0x000149f0
`private: int __thiscall CObjectPathParser::NextToken(void)` | 447 (0x1bf) | Exported Function | 0x10014090 | 0x00014090
`private: int __thiscall CObjectPathParser::ns_list(void)` | 591 (0x24f) | Exported Function | 0x10014020 | 0x00014020
`private: int __thiscall CObjectPathParser::ns_list_rest(void)` | 592 (0x250) | Exported Function | 0x10014060 | 0x00014060
`private: int __thiscall CObjectPathParser::ns_or_class(void)` | 593 (0x251) | Exported Function | 0x10013d00 | 0x00013d00
`private: int __thiscall CObjectPathParser::ns_or_server(void)` | 594 (0x252) | Exported Function | 0x100145a0 | 0x000145a0
`private: int __thiscall CObjectPathParser::objref(void)` | 595 (0x253) | Exported Function | 0x10014530 | 0x00014530
`private: int __thiscall CObjectPathParser::objref_rest(void)` | 596 (0x254) | Exported Function | 0x10013d50 | 0x00013d50
`private: int __thiscall CObjectPathParser::optional_objref(void)` | 597 (0x255) | Exported Function | 0x10014570 | 0x00014570
`private: int __thiscall CObjectPathParser::propname(void)` | 598 (0x256) | Exported Function | 0x10013f20 | 0x00013f20
`private: int __thiscall Provider::SetKeyFromParsedObjectPath(class CInstance *,struct ParsedObjectPath *)` | 519 (0x207) | Exported Function | 0x100136c0 | 0x000136c0
`private: int __thiscall CObjectPathParser::ident_becomes_class(void)` | 563 (0x233) | Exported Function | 0x10026a00 | 0x00026a00
`private: int __thiscall Provider::ValidateIMOSPointer(void)` | 553 (0x229) | Exported Function | 0x10022e60 | 0x00022e60
`private: int __thiscall CObjectPathParser::begin_parse(void)` | 560 (0x230) | Exported Function | 0x10013c00 | 0x00013c00
`const ProviderLog::``vftable'` | 156 (0x9c) | Exported Function | 0x10001138 | 0x00001138
`class CHString __stdcall operator+(class CHString const &,class CHString const &)` | 124 (0x7c) | Exported Function | 0x10014f40 | 0x00014f40
`class CHString __stdcall operator+(class CHString const &,unsigned short const *)` | 126 (0x7e) | Exported Function | 0x10027e40 | 0x00027e40
`class CHString __stdcall operator+(class CHString const &,unsigned short)` | 125 (0x7d) | Exported Function | 0x10015010 | 0x00015010
`class CHString __stdcall operator+(unsigned short const *,class CHString const &)` | 128 (0x80) | Exported Function | 0x1000c170 | 0x0000c170
`class CHString __stdcall operator+(unsigned short,class CHString const &)` | 127 (0x7f) | Exported Function | 0x10027ea0 | 0x00027ea0
`class ProviderLog captainsLog` | 561 (0x231) | Exported Function | 0x10038100 | 0x00038100
`const CFrameworkQueryEx::``vftable'` | 147 (0x93) | Exported Function | 0x10001094 | 0x00001094
`const CInstance::``vftable'` | 148 (0x94) | Exported Function | 0x10001088 | 0x00001088
`const CThreadBase::``vftable'` | 149 (0x95) | Exported Function | 0x100010fc | 0x000010fc
`const CWbemGlueFactory::``vftable'` | 150 (0x96) | Exported Function | 0x10001144 | 0x00001144
`const CWbemProviderGlue::``vftable'{for ``IWbemProviderInit'}` | 151 (0x97) | Exported Function | 0x10001004 | 0x00001004
`const CWbemProviderGlue::``vftable'{for ``IWbemServices'}` | 152 (0x98) | Exported Function | 0x10001018 | 0x00001018
`const CWinMsgEvent::``vftable'` | 153 (0x99) | Exported Function | 0x10001d80 | 0x00001d80
`const MethodContext::``vftable'` | 154 (0x9a) | Exported Function | 0x100010a0 | 0x000010a0
`const Provider::``vftable'` | 155 (0x9b) | Exported Function | 0x100010b8 | 0x000010b8
`private: class CWbemProviderGlue * __thiscall MethodContext::GetProviderGlue(void)` | 358 (0x166) | Exported Function | 0x10022ac0 | 0x00022ac0
`private: long __thiscall CRegistry::myRegCreateKeyEx(struct HKEY__ *,unsigned short const *,unsigned long,unsigned short *,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES * const,struct HKEY__ * *,unsigned long *)` | 582 (0x246) | Exported Function | 0x1002a4f0 | 0x0002a4f0
`private: long __thiscall CRegistry::myRegDeleteKey(struct HKEY__ *,unsigned short const *)` | 583 (0x247) | Exported Function | 0x1002a510 | 0x0002a510
`private: long __thiscall CRegistry::myRegDeleteValue(struct HKEY__ *,unsigned short const *)` | 584 (0x248) | Exported Function | 0x10029490 | 0x00029490
`private: static class CCritSec CWinMsgEvent::mg_csWindowLock` | 577 (0x241) | Exported Function | 0x100380d8 | 0x000380d8
`private: static class CHString Provider::s_strComputerName` | 609 (0x261) | Exported Function | 0x1003802c | 0x0003802c
`private: static class Provider * __stdcall CWbemProviderGlue::AddProviderToMap(unsigned short const *,unsigned short const *,class Provider *)` | 166 (0xa6) | Exported Function | 0x1000db00 | 0x0000db00
`private: static class Provider * __stdcall CWbemProviderGlue::SearchMapForProvider(unsigned short const *,unsigned short const *)` | 490 (0x1ea) | Exported Function | 0x1000cce0 | 0x0000cce0
`private: static class std::map<class CHString,void *,struct std::less<class CHString>,class std::allocator<struct std::pair<class CHString const ,void *> > > CWbemProviderGlue::s_providersmap` | 608 (0x260) | Exported Function | 0x10038030 | 0x00038030
`private: static class std::map<void const *,long *,struct std::less<void const *>,class std::allocator<struct std::pair<void const * const,long *> > > CWbemProviderGlue::s_factorymap` | 606 (0x25e) | Exported Function | 0x10038050 | 0x00038050
`private: static class std::multimap<unsigned int,class CWinMsgEvent *,struct std::less<unsigned int>,class std::allocator<struct std::pair<unsigned int const ,class CWinMsgEvent *> > > CWinMsgEvent::mg_oSinkMap` | 581 (0x245) | Exported Function | 0x100380f4 | 0x000380f4
`private: static class std::set<void *,struct std::less<void *>,class std::allocator<void *> > CWbemProviderGlue::m_FlushPtrs` | 571 (0x23b) | Exported Function | 0x10038088 | 0x00038088
`private: static int __stdcall CRegistry::SetPlatformID(void)` | 521 (0x209) | Exported Function | 0x1002a4a0 | 0x0002a4a0
`private: static int __stdcall CWinMsgEvent::CtrlHandlerRoutine(unsigned long)` | 215 (0xd7) | Exported Function | 0x10026e10 | 0x00026e10
`private: static int CRegistry::s_fPlatformSet` | 605 (0x25d) | Exported Function | 0x10037e88 | 0x00037e88
`private: static int CWbemProviderGlue::s_bInitted` | 599 (0x257) | Exported Function | 0x10037e78 | 0x00037e78
`private: static int Provider::initFailed_` | 566 (0x236) | Exported Function | 0x10038148 | 0x00038148
`private: static long __stdcall CWbemProviderGlue::CheckImpersonationLevel(void)` | 187 (0xbb) | Exported Function | 0x1000c230 | 0x0000c230
`private: static long __stdcall CWbemProviderGlue::GetInstanceFromCIMOM(unsigned short const *,unsigned short const *,class MethodContext *,class CInstance * *)` | 325 (0x145) | Exported Function | 0x10012fc0 | 0x00012fc0
`private: static class CCritSec CWinMsgEvent::mg_csMapLock` | 576 (0x240) | Exported Function | 0x100380c0 | 0x000380c0
`private: static class CCritSec CWbemProviderGlue::s_csProviderMap` | 601 (0x259) | Exported Function | 0x10038058 | 0x00038058
`private: static class CCritSec CWbemProviderGlue::s_csFactoryMap` | 600 (0x258) | Exported Function | 0x10038038 | 0x00038038
`private: static class CCritSec CWbemProviderGlue::m_csStatusObject` | 573 (0x23d) | Exported Function | 0x10038070 | 0x00038070
`private: long __thiscall CRegistry::myRegEnumKey(struct HKEY__ *,unsigned long,unsigned short *,unsigned long)` | 585 (0x249) | Exported Function | 0x1002a530 | 0x0002a530
`private: long __thiscall CRegistry::myRegEnumValue(struct HKEY__ *,unsigned long,unsigned short *,unsigned long *,unsigned long *,unsigned long *,unsigned char *,unsigned long *)` | 586 (0x24a) | Exported Function | 0x1002a560 | 0x0002a560
`private: long __thiscall CRegistry::myRegOpenKeyEx(struct HKEY__ *,unsigned short const *,unsigned long,unsigned long,struct HKEY__ * *)` | 587 (0x24b) | Exported Function | 0x1002a580 | 0x0002a580
`private: long __thiscall CRegistry::myRegQueryInfoKey(struct HKEY__ *,unsigned short *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,struct _FILETIME *)` | 588 (0x24c) | Exported Function | 0x1002a5a0 | 0x0002a5a0
`private: long __thiscall CRegistry::myRegQueryValueEx(struct HKEY__ *,unsigned short const *,unsigned long *,unsigned long *,unsigned char *,unsigned long *)` | 589 (0x24d) | Exported Function | 0x1002a5c0 | 0x0002a5c0
`private: long __thiscall CRegistry::myRegSetValueEx(struct HKEY__ *,unsigned short const *,unsigned long,unsigned long,unsigned char const *,unsigned long)` | 590 (0x24e) | Exported Function | 0x1002a5e0 | 0x0002a5e0
`private: long __thiscall CWbemProviderGlue::NullOutUnsetProperties(struct IWbemClassObject *,struct IWbemClassObject * *,struct tagVARIANT const &)` | 449 (0x1c1) | Exported Function | 0x10024f70 | 0x00024f70
`protected: virtual long __thiscall Provider::ValidateQueryFlags(long)` | 556 (0x22c) | Exported Function | 0x10009170 | 0x00009170
`private: long __thiscall CWbemProviderGlue::PreProcessPutInstanceParms(struct IWbemClassObject *,struct IWbemClassObject * *,struct IWbemContext *)` | 458 (0x1ca) | Exported Function | 0x10025280 | 0x00025280
`private: long __thiscall Provider::DeleteInstance(struct ParsedObjectPath *,long,class MethodContext *)` | 224 (0xe0) | Exported Function | 0x10022be0 | 0x00022be0
`private: long __thiscall Provider::ExecMethod(struct ParsedObjectPath *,unsigned short *,long,class CInstance *,class CInstance *,class MethodContext *)` | 240 (0xf0) | Exported Function | 0x10022ca0 | 0x00022ca0
`private: long __thiscall Provider::ExecuteQuery(class MethodContext *,class CFrameworkQuery &,long)` | 248 (0xf8) | Exported Function | 0x1000ac50 | 0x0000ac50
`private: long __thiscall Provider::GetObject(struct ParsedObjectPath *,class MethodContext *,long)` | 351 (0x15f) | Exported Function | 0x10013760 | 0x00013760
`private: long __thiscall Provider::PutInstance(struct IWbemClassObject *,long,class MethodContext *)` | 463 (0x1cf) | Exported Function | 0x10022d70 | 0x00022d70
`private: static class CAutoEvent CWinMsgEvent::mg_aeCreateWindow` | 575 (0x23f) | Exported Function | 0x100380f0 | 0x000380f0
`private: static class CCritSec CWbemProviderGlue::m_csFlushPtrs` | 572 (0x23c) | Exported Function | 0x10038090 | 0x00038090
`private: long __thiscall Provider::CreateInstanceEnum(class MethodContext *,long)` | 209 (0xd1) | Exported Function | 0x1000fa10 | 0x0000fa10
`public: class CHString const & __thiscall CHString::operator=(unsigned short)` | 79 (0x4f) | Exported Function | 0x10027e20 | 0x00027e20
`protected: virtual void __thiscall CThreadBase::OnFinalRelease(void)` | 450 (0x1c2) | Exported Function | 0x1000ba50 | 0x0000ba50
`protected: void __thiscall CHString::AllocBeforeWrite(int)` | 174 (0xae) | Exported Function | 0x10027f50 | 0x00027f50
`public: bool __thiscall CInstance::GetWCHAR(unsigned short const *,unsigned short * *)const ` | 387 (0x183) | Exported Function | 0x10022010 | 0x00022010
`public: bool __thiscall CInstance::GetWORD(unsigned short const *,unsigned short &)const ` | 388 (0x184) | Exported Function | 0x10022190 | 0x00022190
`public: bool __thiscall CInstance::IsNull(unsigned short const *)const ` | 419 (0x1a3) | Exported Function | 0x10008730 | 0x00008730
`public: bool __thiscall CInstance::Setbool(unsigned short const *,bool)` | 535 (0x217) | Exported Function | 0x10007f40 | 0x00007f40
`public: bool __thiscall CInstance::SetByte(unsigned short const *,unsigned char)` | 496 (0x1f0) | Exported Function | 0x10008160 | 0x00008160
`public: bool __thiscall CInstance::SetCharSplat(unsigned short const *,char const *)` | 503 (0x1f7) | Exported Function | 0x10015200 | 0x00015200
`public: bool __thiscall CInstance::SetCharSplat(unsigned short const *,unsigned long)` | 502 (0x1f6) | Exported Function | 0x10022580 | 0x00022580
`public: bool __thiscall CInstance::SetCharSplat(unsigned short const *,unsigned short const *)` | 501 (0x1f5) | Exported Function | 0x10007630 | 0x00007630
`public: bool __thiscall CInstance::SetCHString(unsigned short const *,char const *)` | 499 (0x1f3) | Exported Function | 0x10015200 | 0x00015200
`public: bool __thiscall CInstance::SetCHString(unsigned short const *,class CHString const &)` | 498 (0x1f2) | Exported Function | 0x10007490 | 0x00007490
`public: bool __thiscall CInstance::SetCHString(unsigned short const *,unsigned short const *)` | 497 (0x1f1) | Exported Function | 0x10007630 | 0x00007630
`public: bool __thiscall CInstance::SetDateTime(unsigned short const *,class WBEMTime const &)` | 516 (0x204) | Exported Function | 0x10007220 | 0x00007220
`public: bool __thiscall CInstance::SetDOUBLE(unsigned short const *,double)` | 514 (0x202) | Exported Function | 0x100225a0 | 0x000225a0
`public: bool __thiscall CInstance::SetDWORD(unsigned short const *,unsigned long)` | 515 (0x203) | Exported Function | 0x10007050 | 0x00007050
`public: bool __thiscall CInstance::SetEmbeddedObject(unsigned short const *,class CInstance &)` | 518 (0x206) | Exported Function | 0x10022670 | 0x00022670
`public: bool __thiscall CInstance::GetWBEMINT64(unsigned short const *,unsigned __int64 &)const ` | 386 (0x182) | Exported Function | 0x10014ee0 | 0x00014ee0
`public: bool __thiscall CInstance::SetNull(unsigned short const *)` | 520 (0x208) | Exported Function | 0x10022780 | 0x00022780
`public: bool __thiscall CInstance::GetWBEMINT64(unsigned short const *,class CHString &)const ` | 384 (0x180) | Exported Function | 0x10021fa0 | 0x00021fa0
`public: bool __thiscall CInstance::GetWBEMINT16(unsigned short const *,short &)const ` | 383 (0x17f) | Exported Function | 0x10021e60 | 0x00021e60
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(void)` | 52 (0x34) | Exported Function | 0x10016be0 | 0x00016be0
`public: bool __thiscall CFrameworkQuery::AllPropertiesAreRequired(void)` | 173 (0xad) | Exported Function | 0x10014b50 | 0x00014b50
`public: bool __thiscall CFrameworkQuery::IsPropertyRequired(unsigned short const *)` | 423 (0x1a7) | Exported Function | 0x10014ae0 | 0x00014ae0
`public: bool __thiscall CFrameworkQuery::KeysOnly(void)` | 426 (0x1aa) | Exported Function | 0x10009600 | 0x00009600
`public: bool __thiscall CInstance::Getbool(unsigned short const *,bool &)const ` | 389 (0x185) | Exported Function | 0x100222c0 | 0x000222c0
`public: bool __thiscall CInstance::GetByte(unsigned short const *,unsigned char &)const ` | 284 (0x11c) | Exported Function | 0x10021590 | 0x00021590
`public: bool __thiscall CInstance::GetCHString(unsigned short const *,class CHString &)const ` | 285 (0x11d) | Exported Function | 0x1000ecb0 | 0x0000ecb0
`public: bool __thiscall CInstance::GetDateTime(unsigned short const *,class WBEMTime &)const ` | 317 (0x13d) | Exported Function | 0x100217f0 | 0x000217f0
`public: bool __thiscall CInstance::GetDOUBLE(unsigned short const *,double &)const ` | 310 (0x136) | Exported Function | 0x100216c0 | 0x000216c0
`public: bool __thiscall CInstance::GetDWORD(unsigned short const *,unsigned long &)const ` | 311 (0x137) | Exported Function | 0x10014e20 | 0x00014e20
`public: bool __thiscall CInstance::GetEmbeddedObject(unsigned short const *,class CInstance * *,class MethodContext *)const ` | 318 (0x13e) | Exported Function | 0x10021940 | 0x00021940
`public: bool __thiscall CInstance::GetStatus(unsigned short const *,bool &,unsigned short &)const ` | 367 (0x16f) | Exported Function | 0x10021b00 | 0x00021b00
`public: bool __thiscall CInstance::GetStringArray(unsigned short const *,struct tagSAFEARRAY * &)const ` | 370 (0x172) | Exported Function | 0x10021bc0 | 0x00021bc0
`public: bool __thiscall CInstance::GetTimeSpan(unsigned short const *,class WBEMTimeSpan &)const ` | 374 (0x176) | Exported Function | 0x10021d10 | 0x00021d10
`public: bool __thiscall CInstance::GetVariant(unsigned short const *,struct tagVARIANT &)const ` | 382 (0x17e) | Exported Function | 0x100152b0 | 0x000152b0
`public: bool __thiscall CInstance::GetWBEMINT64(unsigned short const *,__int64 &)const ` | 385 (0x181) | Exported Function | 0x10021fb0 | 0x00021fb0
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(unsigned short * const)` | 51 (0x33) | Exported Function | 0x1001f640 | 0x0001f640
`public: bool __thiscall CInstance::SetStringArray(unsigned short const *,struct tagSAFEARRAY const &)` | 526 (0x20e) | Exported Function | 0x10008860 | 0x00008860
`public: bool __thiscall CInstance::SetVariant(unsigned short const *,struct tagVARIANT const &)` | 528 (0x210) | Exported Function | 0x100087d0 | 0x000087d0
`public: class CHString __thiscall CHString::Right(int)const ` | 487 (0x1e7) | Exported Function | 0x1000c4c0 | 0x0000c4c0
`public: class CHString __thiscall CHString::SpanExcluding(unsigned short const *)const ` | 537 (0x219) | Exported Function | 0x10014fb0 | 0x00014fb0
`public: class CHString __thiscall CHString::SpanIncluding(unsigned short const *)const ` | 538 (0x21a) | Exported Function | 0x100281e0 | 0x000281e0
`public: class CHString __thiscall CHStringArray::GetAt(int)const ` | 279 (0x117) | Exported Function | 0x10007eb0 | 0x00007eb0
`public: class CHString __thiscall CHStringArray::operator[](int)const ` | 119 (0x77) | Exported Function | 0x10007eb0 | 0x00007eb0
`public: class CHString const & __thiscall CFrameworkQuery::GetQuery(void)` | 360 (0x168) | Exported Function | 0x10020720 | 0x00020720
`public: class CHString const & __thiscall CHString::operator+=(char)` | 140 (0x8c) | Exported Function | 0x1000a540 | 0x0000a540
`public: class CHString const & __thiscall CHString::operator+=(class CHString const &)` | 139 (0x8b) | Exported Function | 0x1000c910 | 0x0000c910
`public: class CHString const & __thiscall CHString::operator+=(unsigned short const *)` | 142 (0x8e) | Exported Function | 0x1000b9d0 | 0x0000b9d0
`public: class CHString const & __thiscall CHString::operator+=(unsigned short)` | 141 (0x8d) | Exported Function | 0x1000c420 | 0x0000c420
`public: class CHString const & __thiscall CHString::operator=(char const *)` | 81 (0x51) | Exported Function | 0x100077f0 | 0x000077f0
`public: class CHString const & __thiscall CHString::operator=(char)` | 78 (0x4e) | Exported Function | 0x1001f720 | 0x0001f720
`public: class CHString const & __thiscall CHString::operator=(class CHString *)` | 80 (0x50) | Exported Function | 0x1001f750 | 0x0001f750
`public: class CHString const & __thiscall CHString::operator=(class CHString const &)` | 77 (0x4d) | Exported Function | 0x1000fe70 | 0x0000fe70
`public: class CHString const & __thiscall CHString::operator=(unsigned char const *)` | 82 (0x52) | Exported Function | 0x1001f770 | 0x0001f770
`public: class CHString __thiscall CHString::Mid(int,int)const ` | 444 (0x1bc) | Exported Function | 0x1000c310 | 0x0000c310
`public: bool __thiscall CInstance::SetTimeSpan(unsigned short const *,class WBEMTimeSpan const &)` | 527 (0x20f) | Exported Function | 0x10022870 | 0x00022870
`public: class CHString __thiscall CHString::Mid(int)const ` | 443 (0x1bb) | Exported Function | 0x1000b320 | 0x0000b320
`public: class CHString * __thiscall CHStringArray::GetData(void)` | 315 (0x13b) | Exported Function | 0x10008920 | 0x00008920
`public: bool __thiscall CInstance::SetWBEMINT16(unsigned short const *,short const &)` | 529 (0x211) | Exported Function | 0x10008520 | 0x00008520
`public: bool __thiscall CInstance::SetWBEMINT64(unsigned short const *,__int64)` | 531 (0x213) | Exported Function | 0x100070f0 | 0x000070f0
`public: bool __thiscall CInstance::SetWBEMINT64(unsigned short const *,class CHString const &)` | 530 (0x212) | Exported Function | 0x10022980 | 0x00022980
`public: bool __thiscall CInstance::SetWBEMINT64(unsigned short const *,unsigned __int64)` | 532 (0x214) | Exported Function | 0x10006a60 | 0x00006a60
`public: bool __thiscall CInstance::SetWCHARSplat(unsigned short const *,unsigned short const *)` | 533 (0x215) | Exported Function | 0x10007150 | 0x00007150
`public: bool __thiscall CInstance::SetWORD(unsigned short const *,unsigned short)` | 534 (0x216) | Exported Function | 0x10009370 | 0x00009370
`public: bool __thiscall MethodContext::SetStatusObject(struct IWbemClassObject *)` | 525 (0x20d) | Exported Function | 0x10022b00 | 0x00022b00
`public: bool __thiscall WBEMTime::IsOk(void)const ` | 421 (0x1a5) | Exported Function | 0x10016bf0 | 0x00016bf0
`public: bool __thiscall WBEMTimeSpan::IsOk(void)const ` | 422 (0x1a6) | Exported Function | 0x10016bf0 | 0x00016bf0
`public: class CAutoEvent & __thiscall CAutoEvent::operator=(class CAutoEvent const &)` | 73 (0x49) | Exported Function | 0x10020600 | 0x00020600
`public: class CFrameworkQuery & __thiscall CFrameworkQuery::operator=(class CFrameworkQuery const &)` | 74 (0x4a) | Exported Function | 0x1001f680 | 0x0001f680
`public: class CFrameworkQueryEx & __thiscall CFrameworkQueryEx::operator=(class CFrameworkQueryEx const &)` | 75 (0x4b) | Exported Function | 0x10020af0 | 0x00020af0
`public: class CHPtrArray & __thiscall CHPtrArray::operator=(class CHPtrArray const &)` | 76 (0x4c) | Exported Function | 0x1001f700 | 0x0001f700
`public: class CHString & __thiscall CHStringArray::ElementAt(int)` | 232 (0xe8) | Exported Function | 0x10008200 | 0x00008200
`public: class CHString & __thiscall CHStringArray::operator[](int)` | 118 (0x76) | Exported Function | 0x10008200 | 0x00008200
`public: class CHString __thiscall CHString::Left(int)const ` | 427 (0x1ab) | Exported Function | 0x1000c800 | 0x0000c800
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(struct _FILETIME const &)` | 49 (0x31) | Exported Function | 0x10028340 | 0x00028340
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(long const &)` | 48 (0x30) | Exported Function | 0x10028320 | 0x00028320
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(int,int,int,int,int,int,int)` | 50 (0x32) | Exported Function | 0x10016c10 | 0x00016c10
`public: __thiscall CHPtrArray::~CHPtrArray(void)` | 56 (0x38) | Exported Function | 0x10008a60 | 0x00008a60
`public: __thiscall CHString::CHString(char const *)` | 9 (0x9) | Exported Function | 0x100085c0 | 0x000085c0
`public: __thiscall CHString::CHString(class CHString const &)` | 7 (0x7) | Exported Function | 0x10007ee0 | 0x00007ee0
`public: __thiscall CHString::CHString(unsigned char const *)` | 10 (0xa) | Exported Function | 0x1001f450 | 0x0001f450
`public: __thiscall CHString::CHString(unsigned short const *)` | 11 (0xb) | Exported Function | 0x10007fe0 | 0x00007fe0
`public: __thiscall CHString::CHString(unsigned short const *,int)` | 12 (0xc) | Exported Function | 0x10027d90 | 0x00027d90
`public: __thiscall CHString::CHString(unsigned short,int)` | 8 (0x8) | Exported Function | 0x10027d50 | 0x00027d50
`public: __thiscall CHString::CHString(void)` | 13 (0xd) | Exported Function | 0x100077e0 | 0x000077e0
`public: __thiscall CHString::operator unsigned short const *(void)const ` | 120 (0x78) | Exported Function | 0x10008920 | 0x00008920
`public: __thiscall CHString::~CHString(void)` | 57 (0x39) | Exported Function | 0x1000c0f0 | 0x0000c0f0
`public: __thiscall CHStringArray::CHStringArray(void)` | 14 (0xe) | Exported Function | 0x10008950 | 0x00008950
`public: __thiscall CHStringArray::~CHStringArray(void)` | 58 (0x3a) | Exported Function | 0x10010b80 | 0x00010b80
`public: __thiscall CInstance::CInstance(class CInstance const &)` | 15 (0xf) | Exported Function | 0x1001f480 | 0x0001f480
`public: __thiscall CInstance::CInstance(struct IWbemClassObject *,class MethodContext *)` | 16 (0x10) | Exported Function | 0x10012f70 | 0x00012f70
`public: __thiscall CObjectPathParser::CObjectPathParser(enum ObjectParserFlags)` | 17 (0x11) | Exported Function | 0x10015250 | 0x00015250
`public: __thiscall CHPtrArray::CHPtrArray(void)` | 6 (0x6) | Exported Function | 0x10008950 | 0x00008950
`public: __thiscall CObjectPathParser::~CObjectPathParser(void)` | 60 (0x3c) | Exported Function | 0x10012840 | 0x00012840
`public: __thiscall CFrameworkQueryEx::~CFrameworkQueryEx(void)` | 55 (0x37) | Exported Function | 0x10020ac0 | 0x00020ac0
`public: __thiscall CFrameworkQueryEx::CFrameworkQueryEx(class CFrameworkQueryEx const &)` | 4 (0x4) | Exported Function | 0x10020a00 | 0x00020a00
`protected: void __thiscall CHString::AllocBuffer(int)` | 175 (0xaf) | Exported Function | 0x1000d080 | 0x0000d080
`protected: void __thiscall CHString::AllocCopy(class CHString &,int,int,int)const ` | 176 (0xb0) | Exported Function | 0x1000ad60 | 0x0000ad60
`protected: void __thiscall CHString::AssignCopy(int,unsigned short const *)` | 180 (0xb4) | Exported Function | 0x1000f290 | 0x0000f290
`protected: void __thiscall CHString::ConcatCopy(int,unsigned short const *,int,unsigned short const *)` | 198 (0xc6) | Exported Function | 0x1000caa0 | 0x0000caa0
`protected: void __thiscall CHString::ConcatInPlace(int,unsigned short const *)` | 199 (0xc7) | Exported Function | 0x1000c5f0 | 0x0000c5f0
`protected: void __thiscall CHString::CopyBeforeWrite(void)` | 202 (0xca) | Exported Function | 0x1000f440 | 0x0000f440
`protected: void __thiscall CHString::Init(void)` | 399 (0x18f) | Exported Function | 0x10028130 | 0x00028130
`protected: void __thiscall CInstance::LogError(unsigned short const *,unsigned short const *,unsigned short const *,long)const ` | 438 (0x1b6) | Exported Function | 0x100223f0 | 0x000223f0
`protected: void __thiscall CWinMsgEvent::RegisterForMessage(unsigned int,int)` | 470 (0x1d6) | Exported Function | 0x10026fd0 | 0x00026fd0
`protected: void __thiscall CWinMsgEvent::UnRegisterAllMessages(void)` | 542 (0x21e) | Exported Function | 0x10027180 | 0x00027180
`public: __thiscall CAutoEvent::CAutoEvent(void)` | 1 (0x1) | Exported Function | 0x10009480 | 0x00009480
`public: __thiscall CAutoEvent::~CAutoEvent(void)` | 53 (0x35) | Exported Function | 0x100095c0 | 0x000095c0
`public: __thiscall CFrameworkQuery::CFrameworkQuery(class CFrameworkQuery const &)` | 2 (0x2) | Exported Function | 0x1001f3c0 | 0x0001f3c0
`public: __thiscall CFrameworkQuery::CFrameworkQuery(void)` | 3 (0x3) | Exported Function | 0x1000f920 | 0x0000f920
`public: __thiscall CFrameworkQuery::~CFrameworkQuery(void)` | 54 (0x36) | Exported Function | 0x1000baa0 | 0x0000baa0
`public: __thiscall CFrameworkQueryEx::CFrameworkQueryEx(void)` | 5 (0x5) | Exported Function | 0x10020a50 | 0x00020a50
`public: __thiscall CreateMutexAsProcess::CreateMutexAsProcess(unsigned short const *)` | 32 (0x20) | Exported Function | 0x10008b90 | 0x00008b90
`public: __thiscall CreateMutexAsProcess::~CreateMutexAsProcess(void)` | 67 (0x43) | Exported Function | 0x100205b0 | 0x000205b0
`public: __thiscall CRegistry::CRegistry(class CRegistry const &)` | 18 (0x12) | Exported Function | 0x1001fe90 | 0x0001fe90
`public: __thiscall KeyRef::~KeyRef(void)` | 68 (0x44) | Exported Function | 0x10025f60 | 0x00025f60
`public: __thiscall MethodContext::MethodContext(class MethodContext const &)` | 35 (0x23) | Exported Function | 0x1001f560 | 0x0001f560
`public: __thiscall MethodContext::MethodContext(struct IWbemContext *,class CWbemProviderGlue *)` | 36 (0x24) | Exported Function | 0x1000d1e0 | 0x0000d1e0
`public: __thiscall ParsedObjectPath::ParsedObjectPath(void)` | 37 (0x25) | Exported Function | 0x10013c70 | 0x00013c70
`public: __thiscall ParsedObjectPath::~ParsedObjectPath(void)` | 70 (0x46) | Exported Function | 0x10013550 | 0x00013550
`public: __thiscall Provider::Provider(class Provider const &)` | 38 (0x26) | Exported Function | 0x1001f5a0 | 0x0001f5a0
`public: __thiscall Provider::Provider(unsigned short const *,unsigned short const *)` | 39 (0x27) | Exported Function | 0x1000d840 | 0x0000d840
`public: __thiscall ProviderLog::ProviderLog(class ProviderLog const &)` | 40 (0x28) | Exported Function | 0x1001ffa0 | 0x0001ffa0
`public: __thiscall ProviderLog::ProviderLog(void)` | 41 (0x29) | Exported Function | 0x10011050 | 0x00011050
`public: __thiscall WBEMTime::WBEMTime(long const &)` | 42 (0x2a) | Exported Function | 0x10009410 | 0x00009410
`public: __thiscall WBEMTime::WBEMTime(struct _FILETIME const &)` | 43 (0x2b) | Exported Function | 0x10008250 | 0x00008250
`public: __thiscall WBEMTime::WBEMTime(struct _SYSTEMTIME const &)` | 44 (0x2c) | Exported Function | 0x100094a0 | 0x000094a0
`public: __thiscall WBEMTime::WBEMTime(struct tm const &)` | 45 (0x2d) | Exported Function | 0x1001f600 | 0x0001f600
`public: __thiscall WBEMTime::WBEMTime(unsigned short * const)` | 46 (0x2e) | Exported Function | 0x1001f620 | 0x0001f620
`public: __thiscall WBEMTime::WBEMTime(void)` | 47 (0x2f) | Exported Function | 0x10016be0 | 0x00016be0
`public: __thiscall KeyRef::KeyRef(void)` | 34 (0x22) | Exported Function | 0x10025ef0 | 0x00025ef0
`public: __thiscall KeyRef::KeyRef(unsigned short const *,struct tagVARIANT const *)` | 33 (0x21) | Exported Function | 0x10025e90 | 0x00025e90
`public: __thiscall CWinMsgEvent::~CWinMsgEvent(void)` | 66 (0x42) | Exported Function | 0x10026c70 | 0x00026c70
`public: __thiscall CWinMsgEvent::CWinMsgEvent(void)` | 31 (0x1f) | Exported Function | 0x10026c60 | 0x00026c60
`public: __thiscall CRegistry::CRegistry(void)` | 19 (0x13) | Exported Function | 0x10010f80 | 0x00010f80
`public: __thiscall CRegistry::~CRegistry(void)` | 61 (0x3d) | Exported Function | 0x10010db0 | 0x00010db0
`public: __thiscall CRegistrySearch::CRegistrySearch(class CRegistrySearch const &)` | 20 (0x14) | Exported Function | 0x1001ff60 | 0x0001ff60
`public: __thiscall CRegistrySearch::CRegistrySearch(void)` | 21 (0x15) | Exported Function | 0x10029200 | 0x00029200
`public: __thiscall CRegistrySearch::~CRegistrySearch(void)` | 62 (0x3e) | Exported Function | 0x10029220 | 0x00029220
`public: __thiscall CThreadBase::CThreadBase(class CThreadBase const &)` | 22 (0x16) | Exported Function | 0x1001f4b0 | 0x0001f4b0
`public: __thiscall CThreadBase::CThreadBase(enum CThreadBase::THREAD_SAFETY_MECHANISM)` | 23 (0x17) | Exported Function | 0x1000a9d0 | 0x0000a9d0
`protected: virtual void __thiscall Provider::Flush(void)` | 254 (0xfe) | Exported Function | 0x100090d0 | 0x000090d0
`public: __thiscall CWbemGlueFactory::CWbemGlueFactory(class CWbemGlueFactory const &)` | 24 (0x18) | Exported Function | 0x1001f4f0 | 0x0001f4f0
`public: __thiscall CWbemGlueFactory::CWbemGlueFactory(void)` | 26 (0x1a) | Exported Function | 0x10020490 | 0x00020490
`public: __thiscall CWbemGlueFactory::~CWbemGlueFactory(void)` | 64 (0x40) | Exported Function | 0x10011930 | 0x00011930
`public: __thiscall CWbemProviderGlue::CWbemProviderGlue(class CWbemProviderGlue const &)` | 27 (0x1b) | Exported Function | 0x1001f510 | 0x0001f510
`public: __thiscall CWbemProviderGlue::CWbemProviderGlue(long *)` | 28 (0x1c) | Exported Function | 0x10009830 | 0x00009830
`public: __thiscall CWbemProviderGlue::CWbemProviderGlue(void)` | 29 (0x1d) | Exported Function | 0x100098f0 | 0x000098f0
`public: __thiscall CWbemProviderGlue::~CWbemProviderGlue(void)` | 65 (0x41) | Exported Function | 0x10009a40 | 0x00009a40
`public: __thiscall CWinMsgEvent::CWinMsgEvent(class CWinMsgEvent const &)` | 30 (0x1e) | Exported Function | 0x10026c50 | 0x00026c50
`public: __thiscall CWbemGlueFactory::CWbemGlueFactory(long *)` | 25 (0x19) | Exported Function | 0x100119a0 | 0x000119a0
`void __stdcall SetCHStringResourceHandle(struct HINSTANCE__ *)` | 500 (0x1f4) | Exported Function | 0x100281d0 | 0x000281d0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/d3e9452a047d3942a7aae42c696cae7d277fa42638dbc738081518e69e29959c/detection/





MIT License. Copyright (c) 2020 Strontic.


