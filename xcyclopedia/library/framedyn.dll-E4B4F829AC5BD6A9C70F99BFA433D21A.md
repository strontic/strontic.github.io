---
title: framedyn.dll | WMI SDK Provider Framework
excerpt: What is framedyn.dll?
---

# framedyn.dll 

* File Path: `C:\Windows\system32\framedyn.dll`
* Description: WMI SDK Provider Framework

## Hashes

Type | Hash
-- | --
MD5 | `E4B4F829AC5BD6A9C70F99BFA433D21A`
SHA1 | `C3006531030859663D8D168C8E0677CD73CC2926`
SHA256 | `9EE3B8287876F6A17C8A11C5A60130D182F5FB7DDD9569182969ECB91380A948`
SHA384 | `AF19E56715823C2154D6FF9BBE89FD851E6676A2A514C597DE22DA43D11A64C82EFAF4FB493180D97C8837C9E021404E`
SHA512 | `9DF261CA4CB38C9F35EB948A5210D22925444D5F8A6BD3029A44E32E8F4DFDE635CD43D8447D51E288B491ADCBBBC4AA14B829CEDA1E57EF16B2436834EC0E71`
SSDEEP | `3072:MHlkRKSrR8OnhqiX+uHjsF0NbjnxX4oXxapHd0Nn74LOtKk6Kgwp77C4UTMB:M2DKOhqiX+4sF0Fn5b0ozvTUTM`
IMP | `D3CB325902233FC77D38F1CA3745D21E`
PESHA1 | `8B03831EF93864B821B1303E556A88BCA1A557DB`
PE256 | `574CE54D7EEFFB9E52469A137697B75A02E4A26A3FEE44F797F715A3F4D4F28B`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`class CCritSec g_cs` | 565 (0x235) | Exported Function | 0x000000018003d0c0 | 0x0003d0c0
`public: long __cdecl CFrameworkQuery::Init(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,class CHString & __ptr64) __ptr64` | 400 (0x190) | Exported Function | 0x0000000180004290 | 0x00004290
`public: long __cdecl CFrameworkQueryEx::GetValuesForProp(unsigned short const * __ptr64,class std::vector<class _variant_t,class std::allocator<class _variant_t> > & __ptr64) __ptr64` | 383 (0x17f) | Exported Function | 0x0000000180006080 | 0x00006080
`public: long __cdecl CFrameworkQueryEx::GetValuesForProp(unsigned short const * __ptr64,class std::vector<int,class std::allocator<int> > & __ptr64) __ptr64` | 382 (0x17e) | Exported Function | 0x0000000180005f50 | 0x00005f50
`public: long __cdecl CInstance::AddRef(void) __ptr64` | 169 (0xa9) | Exported Function | 0x0000000180006b80 | 0x00006b80
`public: long __cdecl CInstance::Commit(void) __ptr64` | 196 (0xc4) | Exported Function | 0x0000000180006d80 | 0x00006d80
`public: long __cdecl CInstance::Release(void) __ptr64` | 475 (0x1db) | Exported Function | 0x0000000180006ba0 | 0x00006ba0
`public: long __cdecl CRegistry::CreateOpen(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES * __ptr64,unsigned long * __ptr64) __ptr64` | 216 (0xd8) | Exported Function | 0x000000018001db40 | 0x0001db40
`public: long __cdecl CRegistry::DeleteKey(class CHString * __ptr64) __ptr64` | 229 (0xe5) | Exported Function | 0x000000018001dc90 | 0x0001dc90
`public: long __cdecl CRegistry::DeleteValue(unsigned short const * __ptr64) __ptr64` | 230 (0xe6) | Exported Function | 0x000000018001dcd0 | 0x0001dcd0
`public: long __cdecl CRegistry::EnumerateAndGetValues(unsigned long & __ptr64,unsigned short * __ptr64 & __ptr64,unsigned char * __ptr64 & __ptr64) __ptr64` | 239 (0xef) | Exported Function | 0x000000018001d750 | 0x0001d750
`public: long __cdecl CRegistry::Open(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long) __ptr64` | 453 (0x1c5) | Exported Function | 0x000000018001da20 | 0x0001da20
`public: long __cdecl CRegistry::OpenAndEnumerateSubKeys(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long) __ptr64` | 454 (0x1c6) | Exported Function | 0x000000018001dcf0 | 0x0001dcf0
`public: long __cdecl CRegistry::OpenLocalMachineKeyAndReadValue(unsigned short const * __ptr64,unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 456 (0x1c8) | Exported Function | 0x000000018001dd00 | 0x0001dd00
`public: long __cdecl CThreadBase::AddRef(void) __ptr64` | 170 (0xaa) | Exported Function | 0x0000000180009920 | 0x00009920
`public: long __cdecl CThreadBase::Release(void) __ptr64` | 476 (0x1dc) | Exported Function | 0x000000018000b290 | 0x0000b290
`public: long __cdecl CFrameworkQuery::Init(struct ParsedObjectPath * __ptr64,struct IWbemContext * __ptr64,unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 399 (0x18f) | Exported Function | 0x0000000180004550 | 0x00004550
`public: long __cdecl MethodContext::AddRef(void) __ptr64` | 173 (0xad) | Exported Function | 0x0000000180009920 | 0x00009920
`public: long __cdecl CFrameworkQuery::GetValuesForProp(unsigned short const * __ptr64,class std::vector<class _bstr_t,class std::allocator<class _bstr_t> > & __ptr64) __ptr64` | 380 (0x17c) | Exported Function | 0x0000000180004c60 | 0x00004c60
`public: int __cdecl WBEMTimeSpan::operator>=(class WBEMTimeSpan const & __ptr64)const __ptr64` | 140 (0x8c) | Exported Function | 0x0000000180001a70 | 0x00001a70
`public: int __cdecl WBEMTime::Gettime_t(__int64 * __ptr64)const __ptr64` | 393 (0x189) | Exported Function | 0x000000018001c020 | 0x0001c020
`public: int __cdecl WBEMTime::operator!=(class WBEMTime const & __ptr64)const __ptr64` | 115 (0x73) | Exported Function | 0x00000001800019f0 | 0x000019f0
`public: int __cdecl WBEMTime::operator<(class WBEMTime const & __ptr64)const __ptr64` | 133 (0x85) | Exported Function | 0x0000000180001a10 | 0x00001a10
`public: int __cdecl WBEMTime::operator<=(class WBEMTime const & __ptr64)const __ptr64` | 135 (0x87) | Exported Function | 0x0000000180001a30 | 0x00001a30
`public: int __cdecl WBEMTime::operator==(class WBEMTime const & __ptr64)const __ptr64` | 113 (0x71) | Exported Function | 0x00000001800019d0 | 0x000019d0
`public: int __cdecl WBEMTime::operator>(class WBEMTime const & __ptr64)const __ptr64` | 137 (0x89) | Exported Function | 0x0000000180001a50 | 0x00001a50
`public: int __cdecl WBEMTime::operator>=(class WBEMTime const & __ptr64)const __ptr64` | 139 (0x8b) | Exported Function | 0x0000000180001a70 | 0x00001a70
`public: int __cdecl WBEMTime::SetDMTF(unsigned short * __ptr64 const) __ptr64` | 515 (0x203) | Exported Function | 0x000000018001c1a0 | 0x0001c1a0
`public: int __cdecl WBEMTimeSpan::GetFILETIME(struct _FILETIME * __ptr64)const __ptr64` | 324 (0x144) | Exported Function | 0x000000018001c8f0 | 0x0001c8f0
`public: int __cdecl WBEMTimeSpan::Gettime_t(__int64 * __ptr64)const __ptr64` | 394 (0x18a) | Exported Function | 0x000000018001c8c0 | 0x0001c8c0
`public: int __cdecl WBEMTimeSpan::operator!=(class WBEMTimeSpan const & __ptr64)const __ptr64` | 116 (0x74) | Exported Function | 0x00000001800019f0 | 0x000019f0
`public: int __cdecl WBEMTimeSpan::operator<(class WBEMTimeSpan const & __ptr64)const __ptr64` | 134 (0x86) | Exported Function | 0x0000000180001a10 | 0x00001a10
`public: int __cdecl WBEMTimeSpan::operator<=(class WBEMTimeSpan const & __ptr64)const __ptr64` | 136 (0x88) | Exported Function | 0x0000000180001a30 | 0x00001a30
`public: int __cdecl WBEMTimeSpan::operator==(class WBEMTimeSpan const & __ptr64)const __ptr64` | 114 (0x72) | Exported Function | 0x00000001800019d0 | 0x000019d0
`public: int __cdecl WBEMTimeSpan::operator>(class WBEMTimeSpan const & __ptr64)const __ptr64` | 138 (0x8a) | Exported Function | 0x0000000180001a50 | 0x00001a50
`public: long __cdecl CFrameworkQuery::GetValuesForProp(unsigned short const * __ptr64,class CHStringArray & __ptr64) __ptr64` | 381 (0x17d) | Exported Function | 0x00000001800049a0 | 0x000049a0
`public: int __cdecl WBEMTime::GetSYSTEMTIME(struct _SYSTEMTIME * __ptr64)const __ptr64` | 366 (0x16e) | Exported Function | 0x000000018001c120 | 0x0001c120
`public: long __cdecl MethodContext::Release(void) __ptr64` | 479 (0x1df) | Exported Function | 0x0000000180009940 | 0x00009940
`public: static bool __cdecl CWbemProviderGlue::SetStatusObject(class MethodContext * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,long,struct tagSAFEARRAY const * __ptr64,struct tagSAFEARRAY const * __ptr64)` | 526 (0x20e) | Exported Function | 0x000000018000bc20 | 0x0000bc20
`public: static long __cdecl CWbemProviderGlue::GetInstancePropertiesByPath(unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,class MethodContext * __ptr64,class CHStringArray & __ptr64)` | 329 (0x149) | Exported Function | 0x000000018000fe50 | 0x0000fe50
`public: static long __cdecl CWbemProviderGlue::GetInstancesByQuery(unsigned short const * __ptr64,class TRefPointerCollection<class CInstance> * __ptr64,class MethodContext * __ptr64,unsigned short const * __ptr64)` | 330 (0x14a) | Exported Function | 0x000000018000f100 | 0x0000f100
`public: static long __cdecl CWbemProviderGlue::GetInstancesByQueryAsynch(unsigned short const * __ptr64,class Provider * __ptr64,long (__cdecl*)(class Provider * __ptr64,class CInstance * __ptr64,class MethodContext * __ptr64,void * __ptr64),unsigned short const * __ptr64,class MethodContext * __ptr64,void * __ptr64)` | 331 (0x14b) | Exported Function | 0x0000000180010eb0 | 0x00010eb0
`public: static long __cdecl WBEMTime::GetLocalOffsetForDate(__int64 const & __ptr64)` | 336 (0x150) | Exported Function | 0x000000018001bb50 | 0x0001bb50
`public: static long __cdecl WBEMTime::GetLocalOffsetForDate(struct _FILETIME const * __ptr64)` | 337 (0x151) | Exported Function | 0x000000018001bbd0 | 0x0001bbd0
`public: static long __cdecl WBEMTime::GetLocalOffsetForDate(struct _SYSTEMTIME const * __ptr64)` | 338 (0x152) | Exported Function | 0x000000018001bc20 | 0x0001bc20
`public: static long __cdecl WBEMTime::GetLocalOffsetForDate(struct tm const * __ptr64)` | 339 (0x153) | Exported Function | 0x000000018001bb90 | 0x0001bb90
`public: static struct IWbemServices * __ptr64 __cdecl CWbemProviderGlue::GetNamespaceConnection(unsigned short const * __ptr64)` | 348 (0x15c) | Exported Function | 0x000000018000e910 | 0x0000e910
`public: static struct IWbemServices * __ptr64 __cdecl CWbemProviderGlue::GetNamespaceConnection(unsigned short const * __ptr64,class MethodContext * __ptr64)` | 349 (0x15d) | Exported Function | 0x00000001800115f0 | 0x000115f0
`public: static unsigned long __cdecl CWbemProviderGlue::GetOSMajorVersion(void)` | 351 (0x15f) | Exported Function | 0x0000000180002260 | 0x00002260
`public: static unsigned long __cdecl CWbemProviderGlue::GetPlatform(void)` | 358 (0x166) | Exported Function | 0x0000000180002270 | 0x00002270
`public: static unsigned short * __ptr64 __cdecl CObjectPathParser::GetRelativePath(unsigned short * __ptr64)` | 364 (0x16c) | Exported Function | 0x0000000180014b50 | 0x00014b50
`public: static unsigned short const * __ptr64 __cdecl CWbemProviderGlue::GetCSDVersion(void)` | 288 (0x120) | Exported Function | 0x0000000180002280 | 0x00002280
`public: static void __cdecl CHString::Release(struct CHStringData * __ptr64)` | 474 (0x1da) | Exported Function | 0x000000018001a4d0 | 0x0001a4d0
`public: static void __cdecl CWbemProviderGlue::FrameworkLogin(unsigned short const * __ptr64,class Provider * __ptr64,unsigned short const * __ptr64)` | 263 (0x107) | Exported Function | 0x000000018000eb10 | 0x0000eb10
`public: static long __cdecl CWbemProviderGlue::GetInstanceKeysByPath(unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,class MethodContext * __ptr64)` | 328 (0x148) | Exported Function | 0x000000018000fc80 | 0x0000fc80
`public: static bool __cdecl CWbemProviderGlue::IsDerivedFrom(unsigned short const * __ptr64,unsigned short const * __ptr64,class MethodContext * __ptr64,unsigned short const * __ptr64)` | 413 (0x19d) | Exported Function | 0x000000018000f5a0 | 0x0000f5a0
`public: static long __cdecl CWbemProviderGlue::GetInstanceByPath(unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,class MethodContext * __ptr64)` | 326 (0x146) | Exported Function | 0x0000000180010170 | 0x00010170
`public: static long __cdecl CWbemProviderGlue::GetEmptyInstance(class MethodContext * __ptr64,unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,unsigned short const * __ptr64)` | 321 (0x141) | Exported Function | 0x000000018000f980 | 0x0000f980
`public: static class CWbemGlueFactory * __ptr64 __cdecl CWbemGlueFactory::Create(long * __ptr64)` | 205 (0xcd) | Exported Function | 0x0000000180003670 | 0x00003670
`public: static class CWbemGlueFactory * __ptr64 __cdecl CWbemGlueFactory::Create(void)` | 206 (0xce) | Exported Function | 0x0000000180003630 | 0x00003630
`public: static int __cdecl CObjectPathParser::Unparse(struct ParsedObjectPath * __ptr64,unsigned short * __ptr64 * __ptr64)` | 550 (0x226) | Exported Function | 0x0000000180014850 | 0x00014850
`public: static int __cdecl CWbemProviderGlue::FrameworkLoginDLL(unsigned short const * __ptr64)` | 264 (0x108) | Exported Function | 0x0000000180010b10 | 0x00010b10
`public: static int __cdecl CWbemProviderGlue::FrameworkLoginDLL(unsigned short const * __ptr64,long * __ptr64)` | 265 (0x109) | Exported Function | 0x0000000180011620 | 0x00011620
`public: static int __cdecl CWbemProviderGlue::FrameworkLogoffDLL(unsigned short const * __ptr64)` | 267 (0x10b) | Exported Function | 0x0000000180010b20 | 0x00010b20
`public: static int __cdecl CWbemProviderGlue::FrameworkLogoffDLL(unsigned short const * __ptr64,long * __ptr64)` | 268 (0x10c) | Exported Function | 0x0000000180011680 | 0x00011680
`public: static int __cdecl Provider::initFailed(void)` | 568 (0x238) | Exported Function | 0x0000000180009eb0 | 0x00009eb0
`public: static long __cdecl CWbemProviderGlue::DecrementObjectCount(void)` | 220 (0xdc) | Exported Function | 0x0000000180010b90 | 0x00010b90
`public: static long __cdecl CWbemProviderGlue::FillInstance(class CInstance * __ptr64,unsigned short const * __ptr64)` | 251 (0xfb) | Exported Function | 0x000000018000fb20 | 0x0000fb20
`public: static long __cdecl CWbemProviderGlue::FillInstance(class MethodContext * __ptr64,class CInstance * __ptr64)` | 252 (0xfc) | Exported Function | 0x000000018000fbe0 | 0x0000fbe0
`public: static long __cdecl CWbemProviderGlue::GetAllDerivedInstances(unsigned short const * __ptr64,class TRefPointerCollection<class CInstance> * __ptr64,class MethodContext * __ptr64,unsigned short const * __ptr64)` | 274 (0x112) | Exported Function | 0x000000018000efd0 | 0x0000efd0
`public: static long __cdecl CWbemProviderGlue::GetAllDerivedInstancesAsynch(unsigned short const * __ptr64,class Provider * __ptr64,long (__cdecl*)(class Provider * __ptr64,class CInstance * __ptr64,class MethodContext * __ptr64,void * __ptr64),unsigned short const * __ptr64,class MethodContext * __ptr64,void * __ptr64)` | 275 (0x113) | Exported Function | 0x000000018000f060 | 0x0000f060
`public: static long __cdecl CWbemProviderGlue::GetAllInstances(unsigned short const * __ptr64,class TRefPointerCollection<class CInstance> * __ptr64,unsigned short const * __ptr64,class MethodContext * __ptr64)` | 276 (0x114) | Exported Function | 0x000000018000eea0 | 0x0000eea0
`public: static long __cdecl CWbemProviderGlue::GetAllInstancesAsynch(unsigned short const * __ptr64,class Provider * __ptr64,long (__cdecl*)(class Provider * __ptr64,class CInstance * __ptr64,class MethodContext * __ptr64,void * __ptr64),unsigned short const * __ptr64,class MethodContext * __ptr64,void * __ptr64)` | 277 (0x115) | Exported Function | 0x000000018000ef30 | 0x0000ef30
`public: static long __cdecl CWbemProviderGlue::GetEmptyInstance(unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,unsigned short const * __ptr64)` | 322 (0x142) | Exported Function | 0x000000018000f860 | 0x0000f860
`public: int __cdecl WBEMTime::GetStructtm(struct tm * __ptr64)const __ptr64` | 373 (0x175) | Exported Function | 0x000000018001c080 | 0x0001c080
`public: int __cdecl WBEMTime::GetFILETIME(struct _FILETIME * __ptr64)const __ptr64` | 323 (0x143) | Exported Function | 0x000000018001c170 | 0x0001c170
`public: int __cdecl ParsedObjectPath::SetClassName(unsigned short const * __ptr64) __ptr64` | 506 (0x1fa) | Exported Function | 0x0000000180014040 | 0x00014040
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator-=(class WBEMTimeSpan const & __ptr64) __ptr64` | 147 (0x93) | Exported Function | 0x000000018001bf60 | 0x0001bf60
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator=(__int64 const & __ptr64) __ptr64` | 106 (0x6a) | Exported Function | 0x000000018001be90 | 0x0001be90
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator=(struct _FILETIME const & __ptr64) __ptr64` | 103 (0x67) | Exported Function | 0x0000000180001b10 | 0x00001b10
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator=(struct _SYSTEMTIME const & __ptr64) __ptr64` | 104 (0x68) | Exported Function | 0x000000018001bde0 | 0x0001bde0
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator=(struct tm const & __ptr64) __ptr64` | 105 (0x69) | Exported Function | 0x000000018001be30 | 0x0001be30
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator=(unsigned short * __ptr64 const) __ptr64` | 107 (0x6b) | Exported Function | 0x000000018001bd70 | 0x0001bd70
`public: class WBEMTimeSpan & __ptr64 __cdecl WBEMTimeSpan::operator=(class WBEMTimeSpan && __ptr64) __ptr64` | 108 (0x6c) | Exported Function | 0x0000000180001ab0 | 0x00001ab0
`public: class WBEMTimeSpan & __ptr64 __cdecl WBEMTimeSpan::operator=(class WBEMTimeSpan const & __ptr64) __ptr64` | 109 (0x6d) | Exported Function | 0x0000000180001ab0 | 0x00001ab0
`public: class WBEMTimeSpan __cdecl WBEMTime::operator-(class WBEMTime const & __ptr64) __ptr64` | 123 (0x7b) | Exported Function | 0x000000018001bf30 | 0x0001bf30
`public: class WBEMTimeSpan __cdecl WBEMTimeSpan::operator+(class WBEMTimeSpan const & __ptr64)const __ptr64` | 132 (0x84) | Exported Function | 0x000000018001bed0 | 0x0001bed0
`public: class WBEMTimeSpan __cdecl WBEMTimeSpan::operator-(class WBEMTimeSpan const & __ptr64)const __ptr64` | 125 (0x7d) | Exported Function | 0x000000018001bf30 | 0x0001bf30
`public: class WBEMTimeSpan const & __ptr64 __cdecl WBEMTimeSpan::operator+=(class WBEMTimeSpan const & __ptr64) __ptr64` | 146 (0x92) | Exported Function | 0x000000018001bf00 | 0x0001bf00
`public: class WBEMTimeSpan const & __ptr64 __cdecl WBEMTimeSpan::operator-=(class WBEMTimeSpan const & __ptr64) __ptr64` | 148 (0x94) | Exported Function | 0x000000018001bf60 | 0x0001bf60
`public: class WBEMTimeSpan const & __ptr64 __cdecl WBEMTimeSpan::operator=(__int64 const & __ptr64) __ptr64` | 111 (0x6f) | Exported Function | 0x000000018001c670 | 0x0001c670
`public: class WBEMTimeSpan const & __ptr64 __cdecl WBEMTimeSpan::operator=(struct _FILETIME const & __ptr64) __ptr64` | 110 (0x6e) | Exported Function | 0x000000018001c650 | 0x0001c650
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator+=(class WBEMTimeSpan const & __ptr64) __ptr64` | 145 (0x91) | Exported Function | 0x000000018001bf00 | 0x0001bf00
`public: class WBEMTimeSpan const & __ptr64 __cdecl WBEMTimeSpan::operator=(unsigned short * __ptr64 const) __ptr64` | 112 (0x70) | Exported Function | 0x000000018001c6a0 | 0x0001c6a0
`public: class WBEMTime __cdecl WBEMTime::operator-(class WBEMTimeSpan const & __ptr64)const __ptr64` | 124 (0x7c) | Exported Function | 0x000000018001bf30 | 0x0001bf30
`public: class WBEMTime & __ptr64 __cdecl WBEMTime::operator=(class WBEMTime const & __ptr64) __ptr64` | 102 (0x66) | Exported Function | 0x0000000180001ab0 | 0x00001ab0
`public: class CHStringArray & __ptr64 __cdecl CHStringArray::operator=(class CHStringArray const & __ptr64) __ptr64` | 86 (0x56) | Exported Function | 0x0000000180001980 | 0x00001980
`public: class CInstance & __ptr64 __cdecl CInstance::operator=(class CInstance const & __ptr64) __ptr64` | 87 (0x57) | Exported Function | 0x0000000180002430 | 0x00002430
`public: class CObjectPathParser & __ptr64 __cdecl CObjectPathParser::operator=(class CObjectPathParser const & __ptr64) __ptr64` | 88 (0x58) | Exported Function | 0x0000000180001650 | 0x00001650
`public: class CreateMutexAsProcess & __ptr64 __cdecl CreateMutexAsProcess::operator=(class CreateMutexAsProcess const & __ptr64) __ptr64` | 95 (0x5f) | Exported Function | 0x0000000180001ab0 | 0x00001ab0
`public: class CRegistry & __ptr64 __cdecl CRegistry::operator=(class CRegistry const & __ptr64) __ptr64` | 89 (0x59) | Exported Function | 0x0000000180002730 | 0x00002730
`public: class CRegistrySearch & __ptr64 __cdecl CRegistrySearch::operator=(class CRegistrySearch const & __ptr64) __ptr64` | 90 (0x5a) | Exported Function | 0x0000000180002870 | 0x00002870
`public: class CThreadBase & __ptr64 __cdecl CThreadBase::operator=(class CThreadBase const & __ptr64) __ptr64` | 91 (0x5b) | Exported Function | 0x0000000180001bb0 | 0x00001bb0
`public: class CWbemGlueFactory & __ptr64 __cdecl CWbemGlueFactory::operator=(class CWbemGlueFactory const & __ptr64) __ptr64` | 92 (0x5c) | Exported Function | 0x00000001800023e0 | 0x000023e0
`public: class CWbemProviderGlue & __ptr64 __cdecl CWbemProviderGlue::operator=(class CWbemProviderGlue const & __ptr64) __ptr64` | 93 (0x5d) | Exported Function | 0x00000001800022f0 | 0x000022f0
`public: class CWinMsgEvent & __ptr64 __cdecl CWinMsgEvent::operator=(class CWinMsgEvent const & __ptr64) __ptr64` | 94 (0x5e) | Exported Function | 0x00000001800164b0 | 0x000164b0
`public: class MethodContext & __ptr64 __cdecl MethodContext::operator=(class MethodContext const & __ptr64) __ptr64` | 97 (0x61) | Exported Function | 0x0000000180001d60 | 0x00001d60
`public: class MethodContext * __ptr64 __cdecl CInstance::GetMethodContext(void)const __ptr64` | 345 (0x159) | Exported Function | 0x0000000180009490 | 0x00009490
`public: class Provider & __ptr64 __cdecl Provider::operator=(class Provider const & __ptr64) __ptr64` | 99 (0x63) | Exported Function | 0x0000000180002140 | 0x00002140
`public: class ProviderLog & __ptr64 __cdecl ProviderLog::operator=(class ProviderLog const & __ptr64) __ptr64` | 100 (0x64) | Exported Function | 0x0000000180002950 | 0x00002950
`public: class WBEMTime & __ptr64 __cdecl WBEMTime::operator=(class WBEMTime && __ptr64) __ptr64` | 101 (0x65) | Exported Function | 0x0000000180001ab0 | 0x00001ab0
`public: class WBEMTime __cdecl WBEMTime::operator+(class WBEMTimeSpan const & __ptr64)const __ptr64` | 131 (0x83) | Exported Function | 0x000000018001bed0 | 0x0001bed0
`public: enum ProviderLog::LogLevel __cdecl ProviderLog::IsLoggingOn(class CHString * __ptr64) __ptr64` | 419 (0x1a3) | Exported Function | 0x0000000180002cf0 | 0x00002cf0
`public: int __cdecl CAutoEvent::Signal(void) __ptr64` | 538 (0x21a) | Exported Function | 0x0000000180016470 | 0x00016470
`public: int __cdecl CFrameworkQueryEx::Is3TokenOR(unsigned short const * __ptr64,unsigned short const * __ptr64,struct tagVARIANT & __ptr64,struct tagVARIANT & __ptr64) __ptr64` | 411 (0x19b) | Exported Function | 0x0000000180005b90 | 0x00005b90
`public: int __cdecl CObjectPathParser::Parse(unsigned short const * __ptr64,struct ParsedObjectPath * __ptr64 * __ptr64) __ptr64` | 459 (0x1cb) | Exported Function | 0x0000000180014c80 | 0x00014c80
`public: int __cdecl CRegistrySearch::FreeSearchList(int,class CHPtrArray & __ptr64) __ptr64` | 273 (0x111) | Exported Function | 0x000000018001f260 | 0x0001f260
`public: int __cdecl CRegistrySearch::LocateKeyByNameOrValueName(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64 * __ptr64,unsigned long,class CHString & __ptr64,class CHString & __ptr64) __ptr64` | 434 (0x1b2) | Exported Function | 0x000000018001f300 | 0x0001f300
`public: int __cdecl CRegistrySearch::SearchAndBuildList(class CHString,class CHPtrArray & __ptr64,class CHString,class CHString,int,struct HKEY__ * __ptr64) __ptr64` | 491 (0x1eb) | Exported Function | 0x000000018001efd0 | 0x0001efd0
`public: int __cdecl CThreadBase::BeginRead(unsigned long) __ptr64` | 183 (0xb7) | Exported Function | 0x0000000180001c90 | 0x00001c90
`public: int __cdecl CThreadBase::BeginWrite(unsigned long) __ptr64` | 184 (0xb8) | Exported Function | 0x0000000180001c90 | 0x00001c90
`public: int __cdecl ParsedObjectPath::AddKeyRef(struct KeyRef * __ptr64) __ptr64` | 164 (0xa4) | Exported Function | 0x00000001800146a0 | 0x000146a0
`public: int __cdecl ParsedObjectPath::AddKeyRef(unsigned short const * __ptr64,struct tagVARIANT const * __ptr64) __ptr64` | 165 (0xa5) | Exported Function | 0x00000001800145d0 | 0x000145d0
`public: int __cdecl ParsedObjectPath::AddKeyRefEx(unsigned short const * __ptr64,struct tagVARIANT const * __ptr64) __ptr64` | 166 (0xa6) | Exported Function | 0x0000000180014200 | 0x00014200
`public: int __cdecl ParsedObjectPath::AddNamespace(unsigned short const * __ptr64) __ptr64` | 167 (0xa7) | Exported Function | 0x0000000180014150 | 0x00014150
`public: int __cdecl ParsedObjectPath::IsClass(void) __ptr64` | 412 (0x19c) | Exported Function | 0x0000000180014090 | 0x00014090
`public: int __cdecl ParsedObjectPath::IsInstance(void) __ptr64` | 417 (0x1a1) | Exported Function | 0x00000001800140d0 | 0x000140d0
`public: int __cdecl ParsedObjectPath::IsLocal(unsigned short const * __ptr64) __ptr64` | 418 (0x1a2) | Exported Function | 0x0000000180015ed0 | 0x00015ed0
`public: int __cdecl ParsedObjectPath::IsObject(void) __ptr64` | 422 (0x1a6) | Exported Function | 0x0000000180014120 | 0x00014120
`public: int __cdecl ParsedObjectPath::IsRelative(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 427 (0x1ab) | Exported Function | 0x0000000180015d60 | 0x00015d60
`public: int __cdecl CHStringArray::GetUpperBound(void)const __ptr64` | 378 (0x17a) | Exported Function | 0x00000001800018b0 | 0x000018b0
`public: int __cdecl CHStringArray::GetSize(void)const __ptr64` | 368 (0x170) | Exported Function | 0x00000001800018a0 | 0x000018a0
`public: int __cdecl CHStringArray::Append(class CHStringArray const & __ptr64) __ptr64` | 181 (0xb5) | Exported Function | 0x000000018001cba0 | 0x0001cba0
`public: int __cdecl CHStringArray::Add(unsigned short const * __ptr64) __ptr64` | 162 (0xa2) | Exported Function | 0x0000000180001950 | 0x00001950
`public: int __cdecl CFrameworkQueryEx::IsNTokenAnd(class CHStringArray & __ptr64,class CHPtrArray & __ptr64) __ptr64` | 420 (0x1a4) | Exported Function | 0x0000000180005da0 | 0x00005da0
`public: int __cdecl CHPtrArray::Add(void * __ptr64) __ptr64` | 161 (0xa1) | Exported Function | 0x000000018001d640 | 0x0001d640
`public: int __cdecl CHPtrArray::Append(class CHPtrArray const & __ptr64) __ptr64` | 180 (0xb4) | Exported Function | 0x000000018001d190 | 0x0001d190
`public: int __cdecl CHPtrArray::GetSize(void)const __ptr64` | 367 (0x16f) | Exported Function | 0x00000001800018a0 | 0x000018a0
`public: int __cdecl CHPtrArray::GetUpperBound(void)const __ptr64` | 377 (0x179) | Exported Function | 0x00000001800018b0 | 0x000018b0
`public: int __cdecl CHString::Collate(unsigned short const * __ptr64)const __ptr64` | 195 (0xc3) | Exported Function | 0x0000000180001880 | 0x00001880
`public: int __cdecl CHString::Compare(unsigned short const * __ptr64)const __ptr64` | 198 (0xc6) | Exported Function | 0x000000018001adb0 | 0x0001adb0
`public: static void __cdecl CWbemProviderGlue::FrameworkLogoff(unsigned short const * __ptr64,unsigned short const * __ptr64)` | 266 (0x10a) | Exported Function | 0x000000018000ec00 | 0x0000ec00
`public: int __cdecl CHString::CompareNoCase(unsigned short const * __ptr64)const __ptr64` | 199 (0xc7) | Exported Function | 0x0000000180001860 | 0x00001860
`public: int __cdecl CHString::Find(unsigned short)const __ptr64` | 253 (0xfd) | Exported Function | 0x000000018001b080 | 0x0001b080
`public: int __cdecl CHString::FindOneOf(unsigned short const * __ptr64)const __ptr64` | 255 (0xff) | Exported Function | 0x000000018001b0c0 | 0x0001b0c0
`public: int __cdecl CHString::GetAllocLength(void)const __ptr64` | 278 (0x116) | Exported Function | 0x0000000180001790 | 0x00001790
`public: int __cdecl CHString::GetLength(void)const __ptr64` | 333 (0x14d) | Exported Function | 0x0000000180001700 | 0x00001700
`public: int __cdecl CHString::IsEmpty(void)const __ptr64` | 414 (0x19e) | Exported Function | 0x0000000180001730 | 0x00001730
`public: int __cdecl CHString::LoadStringW(unsigned int) __ptr64` | 431 (0x1af) | Exported Function | 0x000000018001b800 | 0x0001b800
`public: int __cdecl CHString::ReverseFind(unsigned short)const __ptr64` | 487 (0x1e7) | Exported Function | 0x000000018001b100 | 0x0001b100
`public: int __cdecl CHString::Find(unsigned short const * __ptr64)const __ptr64` | 254 (0xfe) | Exported Function | 0x000000018001b140 | 0x0001b140
`public: static void __cdecl CWbemProviderGlue::IncrementObjectCount(void)` | 397 (0x18d) | Exported Function | 0x0000000180010b30 | 0x00010b30
`public: struct HKEY__ * __ptr64 __cdecl CRegistry::GethKey(void) __ptr64` | 392 (0x188) | Exported Function | 0x0000000180002580 | 0x00002580
`public: struct IWbemClassObject * __ptr64 __cdecl CInstance::GetClassObjectInterface(void) __ptr64` | 290 (0x122) | Exported Function | 0x0000000180006da0 | 0x00006da0
`public: void * __ptr64 * __ptr64 __cdecl CHPtrArray::GetData(void) __ptr64` | 314 (0x13a) | Exported Function | 0x0000000180001780 | 0x00001780
`public: void * __ptr64 __cdecl CHPtrArray::GetAt(int)const __ptr64` | 279 (0x117) | Exported Function | 0x000000018001d600 | 0x0001d600
`public: void * __ptr64 __cdecl CHPtrArray::operator[](int)const __ptr64` | 118 (0x76) | Exported Function | 0x000000018001d600 | 0x0001d600
`public: void __cdecl CFrameworkQuery::GetRequiredProperties(class CHStringArray & __ptr64) __ptr64` | 365 (0x16d) | Exported Function | 0x0000000180004fa0 | 0x00004fa0
`public: void __cdecl CFrameworkQuery::Init2(struct IWbemClassObject * __ptr64) __ptr64` | 398 (0x18e) | Exported Function | 0x0000000180004fe0 | 0x00004fe0
`public: void __cdecl CFrameworkQueryEx::GetPropertyBitMask(class CHPtrArray const & __ptr64,void * __ptr64) __ptr64` | 359 (0x167) | Exported Function | 0x0000000180006630 | 0x00006630
`public: void __cdecl CHPtrArray::Copy(class CHPtrArray const & __ptr64) __ptr64` | 202 (0xca) | Exported Function | 0x000000018001d1f0 | 0x0001d1f0
`public: void __cdecl CHPtrArray::FreeExtra(void) __ptr64` | 270 (0x10e) | Exported Function | 0x000000018001cc90 | 0x0001cc90
`public: void __cdecl CHPtrArray::InsertAt(int,class CHPtrArray * __ptr64) __ptr64` | 406 (0x196) | Exported Function | 0x000000018001d550 | 0x0001d550
`public: void __cdecl CHPtrArray::InsertAt(int,void * __ptr64,int) __ptr64` | 407 (0x197) | Exported Function | 0x000000018001d280 | 0x0001d280
`public: void __cdecl CHPtrArray::RemoveAll(void) __ptr64` | 481 (0x1e1) | Exported Function | 0x000000018001d5d0 | 0x0001d5d0
`public: void __cdecl CHPtrArray::RemoveAt(int,int) __ptr64` | 483 (0x1e3) | Exported Function | 0x000000018001d4f0 | 0x0001d4f0
`public: void __cdecl CHPtrArray::SetAt(int,void * __ptr64) __ptr64` | 493 (0x1ed) | Exported Function | 0x000000018001d620 | 0x0001d620
`public: void __cdecl CHPtrArray::SetAtGrow(int,void * __ptr64) __ptr64` | 496 (0x1f0) | Exported Function | 0x000000018001d230 | 0x0001d230
`public: void __cdecl CHPtrArray::SetSize(int,int) __ptr64` | 524 (0x20c) | Exported Function | 0x000000018001cfd0 | 0x0001cfd0
`public: void * __ptr64 & __ptr64 __cdecl CHPtrArray::operator[](int) __ptr64` | 117 (0x75) | Exported Function | 0x0000000180001930 | 0x00001930
`public: void __cdecl CHString::Empty(void) __ptr64` | 235 (0xeb) | Exported Function | 0x000000018001a7b0 | 0x0001a7b0
`public: void * __ptr64 & __ptr64 __cdecl CHPtrArray::ElementAt(int) __ptr64` | 233 (0xe9) | Exported Function | 0x0000000180001930 | 0x00001930
`public: virtual unsigned long __cdecl CWbemProviderGlue::Release(void) __ptr64` | 478 (0x1de) | Exported Function | 0x000000018000b9d0 | 0x0000b9d0
`public: virtual long __cdecl CWbemProviderGlue::ExecQueryAsync(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 249 (0xf9) | Exported Function | 0x000000018000c090 | 0x0000c090
`public: virtual long __cdecl CWbemProviderGlue::GetObject(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 352 (0x160) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual long __cdecl CWbemProviderGlue::GetObjectAsync(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 356 (0x164) | Exported Function | 0x000000018000cc00 | 0x0000cc00
`public: virtual long __cdecl CWbemProviderGlue::Initialize(unsigned short * __ptr64,long,unsigned short * __ptr64,unsigned short * __ptr64,struct IWbemServices * __ptr64,struct IWbemContext * __ptr64,struct IWbemProviderInitSink * __ptr64) __ptr64` | 405 (0x195) | Exported Function | 0x000000018000b720 | 0x0000b720
`public: virtual long __cdecl CWbemProviderGlue::OpenNamespace(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemServices * __ptr64 * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 457 (0x1c9) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual long __cdecl CWbemProviderGlue::PutClass(struct IWbemClassObject * __ptr64,long,struct IWbemContext * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 462 (0x1ce) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual long __cdecl CWbemProviderGlue::PutClassAsync(struct IWbemClassObject * __ptr64,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 463 (0x1cf) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual long __cdecl CWbemProviderGlue::PutInstance(struct IWbemClassObject * __ptr64,long,struct IWbemContext * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 464 (0x1d0) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual long __cdecl CWbemProviderGlue::PutInstanceAsync(struct IWbemClassObject * __ptr64,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 467 (0x1d3) | Exported Function | 0x000000018000d0b0 | 0x0000d0b0
`public: virtual long __cdecl CWbemProviderGlue::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 469 (0x1d5) | Exported Function | 0x000000018000b560 | 0x0000b560
`public: virtual long __cdecl CWbemProviderGlue::QueryObjectSink(long,struct IWbemObjectSink * __ptr64 * __ptr64) __ptr64` | 470 (0x1d6) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual struct IWbemContext * __ptr64 __cdecl MethodContext::GetIWBEMContext(void) __ptr64` | 325 (0x145) | Exported Function | 0x00000001800098c0 | 0x000098c0
`public: virtual unsigned long __cdecl CWbemGlueFactory::AddRef(void) __ptr64` | 171 (0xab) | Exported Function | 0x0000000180003820 | 0x00003820
`public: virtual unsigned long __cdecl CWbemGlueFactory::Release(void) __ptr64` | 477 (0x1dd) | Exported Function | 0x0000000180003870 | 0x00003870
`public: virtual unsigned long __cdecl CWbemProviderGlue::AddRef(void) __ptr64` | 172 (0xac) | Exported Function | 0x000000018000b6b0 | 0x0000b6b0
`public: virtual void __cdecl MethodContext::QueryPostProcess(void) __ptr64` | 471 (0x1d7) | Exported Function | 0x00000001800034e0 | 0x000034e0
`public: void __cdecl CHString::Format(unsigned int,...) __ptr64` | 258 (0x102) | Exported Function | 0x000000018001b660 | 0x0001b660
`public: void __cdecl CHString::Format(unsigned short const * __ptr64,...) __ptr64` | 259 (0x103) | Exported Function | 0x000000018001b630 | 0x0001b630
`public: void __cdecl CHString::FormatMessageW(unsigned int,...) __ptr64` | 260 (0x104) | Exported Function | 0x000000018001b660 | 0x0001b660
`public: void __cdecl CHStringArray::SetSize(int,int) __ptr64` | 525 (0x20d) | Exported Function | 0x000000018001c9a0 | 0x0001c9a0
`public: void __cdecl CObjectPathParser::``default constructor closure'(void) __ptr64` | 159 (0x9f) | Exported Function | 0x0000000180001680 | 0x00001680
`public: void __cdecl CObjectPathParser::Free(struct ParsedObjectPath * __ptr64) __ptr64` | 269 (0x10d) | Exported Function | 0x00000001800150b0 | 0x000150b0
`public: void __cdecl CRegistry::Close(void) __ptr64` | 193 (0xc1) | Exported Function | 0x000000018001e710 | 0x0001e710
`public: void __cdecl CRegistry::RewindSubKeys(void) __ptr64` | 488 (0x1e8) | Exported Function | 0x000000018001e810 | 0x0001e810
`public: void __cdecl CThreadBase::``default constructor closure'(void) __ptr64` | 160 (0xa0) | Exported Function | 0x0000000180001bf0 | 0x00001bf0
`public: void __cdecl CThreadBase::EndRead(void) __ptr64` | 237 (0xed) | Exported Function | 0x0000000180001cc0 | 0x00001cc0
`public: void __cdecl CThreadBase::EndWrite(void) __ptr64` | 238 (0xee) | Exported Function | 0x0000000180001cc0 | 0x00001cc0
`public: void __cdecl CWbemGlueFactory::Destroy(void) __ptr64` | 231 (0xe7) | Exported Function | 0x00000001800036c0 | 0x000036c0
`public: void __cdecl ParsedObjectPath::ClearKeys(void) __ptr64` | 192 (0xc0) | Exported Function | 0x0000000180014530 | 0x00014530
`public: void __cdecl ProviderLog::LocalLogMessage(unsigned short const * __ptr64,int,enum ProviderLog::LogLevel,unsigned short const * __ptr64,...) __ptr64` | 433 (0x1b1) | Exported Function | 0x0000000180003420 | 0x00003420
`public: void __cdecl ProviderLog::LocalLogMessage(unsigned short const * __ptr64,unsigned short const * __ptr64,int,enum ProviderLog::LogLevel) __ptr64` | 432 (0x1b0) | Exported Function | 0x0000000180003070 | 0x00003070
`public: void __cdecl WBEMTime::Clear(void) __ptr64` | 190 (0xbe) | Exported Function | 0x0000000180001aa0 | 0x00001aa0
`public: void __cdecl WBEMTimeSpan::Clear(void) __ptr64` | 191 (0xbf) | Exported Function | 0x0000000180001aa0 | 0x00001aa0
`public: void const * __ptr64 * __ptr64 __cdecl CHPtrArray::GetData(void)const __ptr64` | 315 (0x13b) | Exported Function | 0x0000000180001780 | 0x00001780
`public: void __cdecl CHStringArray::SetAtGrow(int,unsigned short const * __ptr64) __ptr64` | 497 (0x1f1) | Exported Function | 0x000000018001cd20 | 0x0001cd20
`public: void __cdecl CHStringArray::SetAt(int,unsigned short const * __ptr64) __ptr64` | 495 (0x1ef) | Exported Function | 0x0000000180001910 | 0x00001910
`public: void __cdecl CHStringArray::RemoveAt(int,int) __ptr64` | 484 (0x1e4) | Exported Function | 0x000000018001ce60 | 0x0001ce60
`public: void __cdecl CHStringArray::RemoveAll(void) __ptr64` | 482 (0x1e2) | Exported Function | 0x00000001800018c0 | 0x000018c0
`public: void __cdecl CHString::FormatMessageW(unsigned short const * __ptr64,...) __ptr64` | 261 (0x105) | Exported Function | 0x000000018001b690 | 0x0001b690
`public: void __cdecl CHString::FormatV(unsigned short const * __ptr64,char * __ptr64) __ptr64` | 262 (0x106) | Exported Function | 0x0000000180019f80 | 0x00019f80
`public: void __cdecl CHString::FreeExtra(void) __ptr64` | 271 (0x10f) | Exported Function | 0x000000018001af80 | 0x0001af80
`public: void __cdecl CHString::MakeLower(void) __ptr64` | 442 (0x1ba) | Exported Function | 0x000000018001b1b0 | 0x0001b1b0
`public: void __cdecl CHString::MakeReverse(void) __ptr64` | 443 (0x1bb) | Exported Function | 0x000000018001b1e0 | 0x0001b1e0
`public: void __cdecl CHString::MakeUpper(void) __ptr64` | 444 (0x1bc) | Exported Function | 0x000000018001b180 | 0x0001b180
`public: void __cdecl CHString::Release(void) __ptr64` | 473 (0x1d9) | Exported Function | 0x000000018001a460 | 0x0001a460
`public: virtual long __cdecl CWbemProviderGlue::ExecQuery(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IEnumWbemClassObject * __ptr64 * __ptr64) __ptr64` | 247 (0xf7) | Exported Function | 0x0000000180002250 | 0x00002250
`public: void __cdecl CHString::ReleaseBuffer(int) __ptr64` | 480 (0x1e0) | Exported Function | 0x000000018001aeb0 | 0x0001aeb0
`public: void __cdecl CHString::TrimLeft(void) __ptr64` | 541 (0x21d) | Exported Function | 0x000000018001b590 | 0x0001b590
`public: void __cdecl CHString::TrimRight(void) __ptr64` | 542 (0x21e) | Exported Function | 0x000000018001b4f0 | 0x0001b4f0
`public: void __cdecl CHString::UnlockBuffer(void) __ptr64` | 547 (0x223) | Exported Function | 0x000000018001b050 | 0x0001b050
`public: void __cdecl CHStringArray::Copy(class CHStringArray const & __ptr64) __ptr64` | 203 (0xcb) | Exported Function | 0x000000018001cc20 | 0x0001cc20
`public: void __cdecl CHStringArray::FreeExtra(void) __ptr64` | 272 (0x110) | Exported Function | 0x000000018001cc90 | 0x0001cc90
`public: void __cdecl CHStringArray::InsertAt(int,class CHStringArray * __ptr64) __ptr64` | 408 (0x198) | Exported Function | 0x000000018001cf00 | 0x0001cf00
`public: void __cdecl CHStringArray::InsertAt(int,unsigned short const * __ptr64,int) __ptr64` | 409 (0x199) | Exported Function | 0x000000018001cd70 | 0x0001cd70
`public: void __cdecl CHString::SetAt(int,unsigned short) __ptr64` | 494 (0x1ee) | Exported Function | 0x000000018001a880 | 0x0001a880
`public: class CHString const * __ptr64 __cdecl CHStringArray::GetData(void)const __ptr64` | 318 (0x13e) | Exported Function | 0x0000000180001780 | 0x00001780
`public: virtual long __cdecl CWbemProviderGlue::ExecNotificationQueryAsync(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 246 (0xf6) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual long __cdecl CWbemProviderGlue::ExecMethodAsync(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemClassObject * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 244 (0xf4) | Exported Function | 0x000000018000e020 | 0x0000e020
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyPath(class CHString & __ptr64) __ptr64` | 306 (0x132) | Exported Function | 0x000000018001e640 | 0x0001e640
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyValue(unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 308 (0x134) | Exported Function | 0x000000018001e920 | 0x0001e920
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyValue(unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 307 (0x133) | Exported Function | 0x000000018001e970 | 0x0001e970
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyValue(unsigned short const * __ptr64,void * __ptr64,unsigned long * __ptr64) __ptr64` | 309 (0x135) | Exported Function | 0x000000018001e8c0 | 0x0001e8c0
`public: unsigned long __cdecl CRegistry::GetLongestClassStringSize(void) __ptr64` | 340 (0x154) | Exported Function | 0x00000001800025c0 | 0x000025c0
`public: unsigned long __cdecl CRegistry::GetLongestSubKeySize(void) __ptr64` | 341 (0x155) | Exported Function | 0x00000001800025b0 | 0x000025b0
`public: unsigned long __cdecl CRegistry::GetLongestValueData(void) __ptr64` | 342 (0x156) | Exported Function | 0x00000001800025f0 | 0x000025f0
`public: unsigned long __cdecl CRegistry::GetLongestValueName(void) __ptr64` | 343 (0x157) | Exported Function | 0x00000001800025e0 | 0x000025e0
`public: unsigned long __cdecl CRegistry::GetValueCount(void) __ptr64` | 379 (0x17b) | Exported Function | 0x00000001800025d0 | 0x000025d0
`public: unsigned long __cdecl CRegistry::NextSubKey(void) __ptr64` | 448 (0x1c0) | Exported Function | 0x000000018001e9c0 | 0x0001e9c0
`public: unsigned long __cdecl CRegistry::OpenCurrentUser(unsigned short const * __ptr64,unsigned long) __ptr64` | 455 (0x1c7) | Exported Function | 0x000000018001d8e0 | 0x0001d8e0
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 509 (0x1fd) | Exported Function | 0x000000018001ead0 | 0x0001ead0
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,class CHStringArray & __ptr64) __ptr64` | 510 (0x1fe) | Exported Function | 0x000000018001eb70 | 0x0001eb70
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 508 (0x1fc) | Exported Function | 0x000000018001eb30 | 0x0001eb30
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 512 (0x200) | Exported Function | 0x000000018001ea30 | 0x0001ea30
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyName(class CHString & __ptr64) __ptr64` | 305 (0x131) | Exported Function | 0x000000018001e590 | 0x0001e590
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(unsigned short const * __ptr64,class CHStringArray & __ptr64) __ptr64` | 513 (0x201) | Exported Function | 0x000000018001eab0 | 0x0001eab0
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyCount(void) __ptr64` | 304 (0x130) | Exported Function | 0x00000001800025a0 | 0x000025a0
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(unsigned short const * __ptr64,class CHStringArray & __ptr64) __ptr64` | 301 (0x12d) | Exported Function | 0x000000018001e2a0 | 0x0001e2a0
`public: struct IWbemClassObject * __ptr64 __cdecl MethodContext::GetStatusObject(void) __ptr64` | 371 (0x173) | Exported Function | 0x00000001800099e0 | 0x000099e0
`public: struct KeyRef & __ptr64 __cdecl KeyRef::operator=(struct KeyRef const & __ptr64) __ptr64` | 96 (0x60) | Exported Function | 0x0000000180001600 | 0x00001600
`public: struct ParsedObjectPath & __ptr64 __cdecl ParsedObjectPath::operator=(struct ParsedObjectPath const & __ptr64) __ptr64` | 98 (0x62) | Exported Function | 0x0000000180001620 | 0x00001620
`public: unsigned __int64 __cdecl WBEMTime::GetTime(void)const __ptr64` | 374 (0x176) | Exported Function | 0x0000000180001780 | 0x00001780
`public: unsigned __int64 __cdecl WBEMTimeSpan::GetTime(void)const __ptr64` | 375 (0x177) | Exported Function | 0x0000000180001780 | 0x00001780
`public: unsigned long __cdecl CAutoEvent::Wait(unsigned long) __ptr64` | 559 (0x22f) | Exported Function | 0x0000000180016450 | 0x00016450
`public: unsigned long __cdecl CRegistry::DeleteCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64) __ptr64` | 223 (0xdf) | Exported Function | 0x000000018001edb0 | 0x0001edb0
`public: unsigned long __cdecl CRegistry::DeleteCurrentKeyValue(unsigned short const * __ptr64) __ptr64` | 224 (0xe0) | Exported Function | 0x000000018001dcd0 | 0x0001dcd0
`public: unsigned long __cdecl CRegistry::GetCurrentBinaryKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 293 (0x125) | Exported Function | 0x000000018001e550 | 0x0001e550
`public: unsigned long __cdecl CRegistry::GetCurrentBinaryKeyValue(unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 294 (0x126) | Exported Function | 0x000000018001e3d0 | 0x0001e3d0
`public: unsigned long __cdecl CRegistry::GetCurrentBinaryKeyValue(unsigned short const * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 295 (0x127) | Exported Function | 0x000000018001e510 | 0x0001e510
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 297 (0x129) | Exported Function | 0x000000018001dda0 | 0x0001dda0
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,class CHStringArray & __ptr64) __ptr64` | 298 (0x12a) | Exported Function | 0x000000018001e110 | 0x0001e110
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 296 (0x128) | Exported Function | 0x000000018001e2c0 | 0x0001e2c0
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 300 (0x12c) | Exported Function | 0x000000018001e0f0 | 0x0001e0f0
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 299 (0x12b) | Exported Function | 0x000000018001e3b0 | 0x0001e3b0
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 511 (0x1ff) | Exported Function | 0x000000018001ea90 | 0x0001ea90
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValueExpand(struct HKEY__ * __ptr64,unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 514 (0x202) | Exported Function | 0x000000018001ed50 | 0x0001ed50
`public: unsigned short * __ptr64 __cdecl CFrameworkQuery::GetQueryClassName(void) __ptr64` | 363 (0x16b) | Exported Function | 0x0000000180001ed0 | 0x00001ed0
`public: virtual long __cdecl CFrameworkQueryEx::InitEx(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,class CHString & __ptr64) __ptr64` | 404 (0x194) | Exported Function | 0x0000000180006710 | 0x00006710
`public: virtual long __cdecl CWbemGlueFactory::CreateInstance(struct IUnknown * __ptr64,struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 209 (0xd1) | Exported Function | 0x0000000180003900 | 0x00003900
`public: virtual long __cdecl CWbemGlueFactory::LockServer(int) __ptr64` | 439 (0x1b7) | Exported Function | 0x0000000180003a50 | 0x00003a50
`public: virtual long __cdecl CWbemGlueFactory::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 468 (0x1d4) | Exported Function | 0x0000000180003760 | 0x00003760
`public: virtual long __cdecl CWbemProviderGlue::CancelAsyncCall(struct IWbemObjectSink * __ptr64) __ptr64` | 185 (0xb9) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual long __cdecl CWbemProviderGlue::CancelAsyncRequest(long) __ptr64` | 186 (0xba) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual long __cdecl CWbemProviderGlue::CreateClassEnum(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IEnumWbemClassObject * __ptr64 * __ptr64) __ptr64` | 207 (0xcf) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual long __cdecl CWbemProviderGlue::CreateClassEnumAsync(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 208 (0xd0) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual long __cdecl CWbemProviderGlue::CreateInstanceEnum(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IEnumWbemClassObject * __ptr64 * __ptr64) __ptr64` | 210 (0xd2) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual long __cdecl CWbemProviderGlue::CreateInstanceEnumAsync(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 212 (0xd4) | Exported Function | 0x000000018000c690 | 0x0000c690
`public: virtual long __cdecl CWbemProviderGlue::DeleteClass(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 221 (0xdd) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual long __cdecl CWbemProviderGlue::DeleteClassAsync(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 222 (0xde) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual long __cdecl CWbemProviderGlue::DeleteInstance(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 225 (0xe1) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual long __cdecl CWbemProviderGlue::DeleteInstanceAsync(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 228 (0xe4) | Exported Function | 0x000000018000db20 | 0x0000db20
`public: virtual long __cdecl CWbemProviderGlue::ExecMethod(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemClassObject * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 241 (0xf1) | Exported Function | 0x0000000180002250 | 0x00002250
`public: virtual bool __cdecl CFrameworkQueryEx::IsExtended(void) __ptr64` | 415 (0x19f) | Exported Function | 0x0000000180006930 | 0x00006930
`public: virtual __cdecl ProviderLog::~ProviderLog(void) __ptr64` | 73 (0x49) | Exported Function | 0x0000000180002cb0 | 0x00002cb0
`public: virtual __cdecl Provider::~Provider(void) __ptr64` | 72 (0x48) | Exported Function | 0x0000000180009ec0 | 0x00009ec0
`public: virtual __cdecl MethodContext::~MethodContext(void) __ptr64` | 70 (0x46) | Exported Function | 0x0000000180009860 | 0x00009860
`public: unsigned short * __ptr64 __cdecl CHString::AllocSysString(void)const __ptr64` | 179 (0xb3) | Exported Function | 0x000000018001b760 | 0x0001b760
`public: unsigned short * __ptr64 __cdecl CHString::GetBuffer(int) __ptr64` | 284 (0x11c) | Exported Function | 0x000000018001ade0 | 0x0001ade0
`public: unsigned short * __ptr64 __cdecl CHString::GetBufferSetLength(int) __ptr64` | 285 (0x11d) | Exported Function | 0x000000018001af20 | 0x0001af20
`public: unsigned short * __ptr64 __cdecl CHString::LockBuffer(void) __ptr64` | 436 (0x1b4) | Exported Function | 0x000000018001b010 | 0x0001b010
`public: unsigned short * __ptr64 __cdecl CRegistry::GetClassNameW(void) __ptr64` | 289 (0x121) | Exported Function | 0x0000000180002590 | 0x00002590
`public: unsigned short * __ptr64 __cdecl ParsedObjectPath::GetKeyString(void) __ptr64` | 332 (0x14c) | Exported Function | 0x0000000180015940 | 0x00015940
`public: unsigned short * __ptr64 __cdecl ParsedObjectPath::GetNamespacePart(void) __ptr64` | 350 (0x15e) | Exported Function | 0x0000000180015b90 | 0x00015b90
`public: virtual long __cdecl CWbemProviderGlue::ExecNotificationQuery(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IEnumWbemClassObject * __ptr64 * __ptr64) __ptr64` | 245 (0xf5) | Exported Function | 0x0000000180002250 | 0x00002250
`public: unsigned short * __ptr64 __cdecl ParsedObjectPath::GetParentNamespacePart(void) __ptr64` | 357 (0x165) | Exported Function | 0x0000000180015c70 | 0x00015c70
`public: unsigned short * __ptr64 __cdecl WBEMTime::GetDMTF(int)const __ptr64` | 310 (0x136) | Exported Function | 0x000000018001c400 | 0x0001c400
`public: unsigned short * __ptr64 __cdecl WBEMTime::GetDMTFNonNtfs(void)const __ptr64` | 311 (0x137) | Exported Function | 0x000000018001bfa0 | 0x0001bfa0
`public: unsigned short * __ptr64 __cdecl WBEMTimeSpan::GetBSTR(void)const __ptr64` | 283 (0x11b) | Exported Function | 0x000000018001c7a0 | 0x0001c7a0
`public: unsigned short __cdecl CHString::GetAt(int)const __ptr64` | 280 (0x118) | Exported Function | 0x0000000180001760 | 0x00001760
`public: unsigned short __cdecl CHString::operator[](int)const __ptr64` | 119 (0x77) | Exported Function | 0x0000000180001760 | 0x00001760
`public: virtual __cdecl CInstance::~CInstance(void) __ptr64` | 60 (0x3c) | Exported Function | 0x0000000180006b30 | 0x00006b30
`public: virtual __cdecl CThreadBase::~CThreadBase(void) __ptr64` | 64 (0x40) | Exported Function | 0x000000018000b220 | 0x0000b220
`public: unsigned short * __ptr64 __cdecl WBEMTime::GetBSTR(void)const __ptr64` | 282 (0x11a) | Exported Function | 0x000000018001bf90 | 0x0001bf90
`public: class CHString const & __ptr64 __cdecl CHString::operator=(unsigned short) __ptr64` | 81 (0x51) | Exported Function | 0x000000018001aa30 | 0x0001aa30
`public: class CHString const & __ptr64 __cdecl CHString::operator=(unsigned short const * __ptr64) __ptr64` | 85 (0x55) | Exported Function | 0x000000018001a970 | 0x0001a970
`public: class CHString const & __ptr64 __cdecl CHString::operator=(unsigned char const * __ptr64) __ptr64` | 84 (0x54) | Exported Function | 0x00000001800017c0 | 0x000017c0
`private: static void __cdecl CWinMsgEvent::WindowsDispatch(void)` | 560 (0x230) | Exported Function | 0x0000000180016e00 | 0x00016e00
`private: static void __cdecl Provider::InitComputerName(void)` | 403 (0x193) | Exported Function | 0x0000000180009f30 | 0x00009f30
`private: struct IWbemClassObject * __ptr64 __cdecl Provider::GetClassObjectInterface(class MethodContext * __ptr64) __ptr64` | 291 (0x123) | Exported Function | 0x000000018000ab50 | 0x0000ab50
`private: struct IWbemServices * __ptr64 __cdecl CWbemProviderGlue::InternalGetNamespaceConnection(unsigned short const * __ptr64) __ptr64` | 410 (0x19a) | Exported Function | 0x00000001800113b0 | 0x000113b0
`private: unsigned long __cdecl CRegistry::GetCurrentRawKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,void * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 302 (0x12e) | Exported Function | 0x000000018001dd60 | 0x0001dd60
`private: unsigned long __cdecl CRegistry::GetCurrentRawSubKeyValue(unsigned short const * __ptr64,void * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 303 (0x12f) | Exported Function | 0x000000018001e850 | 0x0001e850
`private: unsigned long __cdecl CRegistry::OpenSubKey(void) __ptr64` | 458 (0x1ca) | Exported Function | 0x000000018001e780 | 0x0001e780
`private: void __cdecl CFrameworkQuery::Reset(void) __ptr64` | 486 (0x1e6) | Exported Function | 0x0000000180005670 | 0x00005670
`private: void __cdecl CObjectPathParser::Empty(void) __ptr64` | 236 (0xec) | Exported Function | 0x0000000180014bd0 | 0x00014bd0
`private: void __cdecl CObjectPathParser::Zero(void) __ptr64` | 561 (0x231) | Exported Function | 0x0000000180014b80 | 0x00014b80
`private: void __cdecl CRegistry::CloseSubKey(void) __ptr64` | 194 (0xc2) | Exported Function | 0x000000018001e820 | 0x0001e820
`private: void __cdecl CRegistry::PrepareToReOpen(void) __ptr64` | 461 (0x1cd) | Exported Function | 0x000000018001ea00 | 0x0001ea00
`private: void __cdecl CRegistry::SetDefaultValues(void) __ptr64` | 519 (0x207) | Exported Function | 0x000000018001d710 | 0x0001d710
`private: void __cdecl CRegistrySearch::CheckAndAddToList(class CRegistry * __ptr64,class CHString,class CHString,class CHPtrArray & __ptr64,class CHString,class CHString,int) __ptr64` | 187 (0xbb) | Exported Function | 0x000000018001ee40 | 0x0001ee40
`private: void __cdecl CThreadBase::Lock(void) __ptr64` | 435 (0x1b3) | Exported Function | 0x0000000180001ce0 | 0x00001ce0
`private: static void __cdecl CWinMsgEvent::DestroyMsgWindow(void)` | 232 (0xe8) | Exported Function | 0x0000000180016ba0 | 0x00016ba0
`private: void __cdecl CThreadBase::Unlock(void) __ptr64` | 546 (0x222) | Exported Function | 0x0000000180001cc0 | 0x00001cc0
`private: static void __cdecl CWinMsgEvent::CreateMsgProvider(void)` | 213 (0xd5) | Exported Function | 0x0000000180016ae0 | 0x00016ae0
`private: static void __cdecl CWbemProviderGlue::UnlockFactoryMap(void)` | 548 (0x224) | Exported Function | 0x00000001800023a0 | 0x000023a0
`private: static struct HWND__ * __ptr64 __ptr64 CWinMsgEvent::mg_hWnd` | 583 (0x247) | Exported Function | 0x000000018003d548 | 0x0003d548
`private: static struct IWbemClassObject * __ptr64 __cdecl CWbemProviderGlue::GetStatusObject(class MethodContext * __ptr64,unsigned short const * __ptr64)` | 370 (0x172) | Exported Function | 0x000000018000bef0 | 0x0000bef0
`private: static struct IWbemClassObject * __ptr64 __ptr64 CWbemProviderGlue::m_pStatusObject` | 577 (0x241) | Exported Function | 0x000000018003d528 | 0x0003d528
`private: static unsigned long __cdecl CWinMsgEvent::dwThreadProc(void * __ptr64)` | 564 (0x234) | Exported Function | 0x0000000180016ca0 | 0x00016ca0
`private: static unsigned long CRegistry::s_dwPlatform` | 606 (0x25e) | Exported Function | 0x000000018003d56c | 0x0003d56c
`private: static unsigned long CWbemProviderGlue::s_dwMajorVersion` | 605 (0x25d) | Exported Function | 0x000000018003d4e8 | 0x0003d4e8
`private: static unsigned long CWbemProviderGlue::s_dwPlatform` | 607 (0x25f) | Exported Function | 0x000000018003d4ec | 0x0003d4ec
`private: static unsigned short * CWbemProviderGlue::s_wstrCSDVersion` | 613 (0x265) | Exported Function | 0x000000018003d2e0 | 0x0003d2e0
`private: static void * __ptr64 __ptr64 CWinMsgEvent::mg_hDevNotify` | 581 (0x245) | Exported Function | 0x000000018003d540 | 0x0003d540
`private: static void * __ptr64 __ptr64 CWinMsgEvent::mg_hThreadPumpHandle` | 582 (0x246) | Exported Function | 0x000000018003d550 | 0x0003d550
`private: static void __cdecl CWbemProviderGlue::GetComputerNameW(class CHString & __ptr64)` | 292 (0x124) | Exported Function | 0x0000000180010a50 | 0x00010a50
`private: static void __cdecl CWbemProviderGlue::Init(void)` | 402 (0x192) | Exported Function | 0x000000018000b430 | 0x0000b430
`private: static void __cdecl CWbemProviderGlue::LockFactoryMap(void)` | 437 (0x1b5) | Exported Function | 0x0000000180002380 | 0x00002380
`private: static void __cdecl CWbemProviderGlue::LockProviderMap(void)` | 438 (0x1b6) | Exported Function | 0x0000000180002340 | 0x00002340
`private: static void __cdecl CWbemProviderGlue::UnInit(void)` | 543 (0x21f) | Exported Function | 0x000000018000b520 | 0x0000b520
`private: static void __cdecl CWbemProviderGlue::UnlockProviderMap(void)` | 549 (0x225) | Exported Function | 0x0000000180002360 | 0x00002360
`private: void __cdecl CWbemProviderGlue::AddFlushPtr(void * __ptr64) __ptr64` | 163 (0xa3) | Exported Function | 0x0000000180011b80 | 0x00011b80
`private: void __cdecl CWbemProviderGlue::FlushAll(void) __ptr64` | 257 (0x101) | Exported Function | 0x000000018000ba90 | 0x0000ba90
`private: void __cdecl ProviderLog::CheckFileSize(union _LARGE_INTEGER & __ptr64,class CHString const & __ptr64) __ptr64` | 188 (0xbc) | Exported Function | 0x0000000180003380 | 0x00003380
`protected: static void __cdecl CWbemProviderGlue::RemoveFromFactoryMap(class CWbemGlueFactory const * __ptr64)` | 485 (0x1e5) | Exported Function | 0x0000000180011770 | 0x00011770
`protected: struct CHStringData * __ptr64 __cdecl CHString::GetData(void)const __ptr64` | 316 (0x13c) | Exported Function | 0x0000000180019950 | 0x00019950
`protected: unsigned long __cdecl CFrameworkQuery::IsInList(class CHStringArray const & __ptr64,unsigned short const * __ptr64) __ptr64` | 416 (0x1a0) | Exported Function | 0x00000001800055e0 | 0x000055e0
`protected: virtual long __cdecl Provider::DeleteInstance(class CInstance const & __ptr64,long) __ptr64` | 227 (0xe3) | Exported Function | 0x000000018000a370 | 0x0000a370
`protected: virtual long __cdecl Provider::EnumerateInstances(class MethodContext * __ptr64,long) __ptr64` | 240 (0xf0) | Exported Function | 0x000000018000a370 | 0x0000a370
`protected: virtual long __cdecl Provider::ExecMethod(class CInstance const & __ptr64,unsigned short * __ptr64 const,class CInstance * __ptr64,class CInstance * __ptr64,long) __ptr64` | 243 (0xf3) | Exported Function | 0x000000018000a370 | 0x0000a370
`protected: virtual long __cdecl Provider::ExecQuery(class MethodContext * __ptr64,class CFrameworkQuery & __ptr64,long) __ptr64` | 248 (0xf8) | Exported Function | 0x000000018000a370 | 0x0000a370
`protected: virtual long __cdecl Provider::GetObject(class CInstance * __ptr64,long) __ptr64` | 354 (0x162) | Exported Function | 0x000000018000a370 | 0x0000a370
`protected: virtual long __cdecl Provider::GetObject(class CInstance * __ptr64,long,class CFrameworkQuery & __ptr64) __ptr64` | 355 (0x163) | Exported Function | 0x000000018000ad80 | 0x0000ad80
`protected: virtual long __cdecl Provider::PutInstance(class CInstance const & __ptr64,long) __ptr64` | 466 (0x1d2) | Exported Function | 0x000000018000a370 | 0x0000a370
`protected: virtual long __cdecl Provider::ValidateDeletionFlags(long) __ptr64` | 551 (0x227) | Exported Function | 0x000000018000ab10 | 0x0000ab10
`protected: virtual long __cdecl Provider::ValidateEnumerationFlags(long) __ptr64` | 552 (0x228) | Exported Function | 0x000000018000aaf0 | 0x0000aaf0
`protected: virtual long __cdecl Provider::ValidateGetObjFlags(long) __ptr64` | 554 (0x22a) | Exported Function | 0x000000018000aaf0 | 0x0000aaf0
`protected: virtual long __cdecl Provider::ValidateMethodFlags(long) __ptr64` | 556 (0x22c) | Exported Function | 0x000000018000ab10 | 0x0000ab10
`protected: virtual long __cdecl Provider::ValidatePutInstanceFlags(long) __ptr64` | 557 (0x22d) | Exported Function | 0x000000018000ab30 | 0x0000ab30
`protected: static void __cdecl CWbemProviderGlue::AddToFactoryMap(class CWbemGlueFactory const * __ptr64,long * __ptr64)` | 174 (0xae) | Exported Function | 0x00000001800116f0 | 0x000116f0
`protected: static long __cdecl CWbemProviderGlue::IncrementMapCount(long * __ptr64)` | 395 (0x18b) | Exported Function | 0x0000000180011930 | 0x00011930
`protected: static long __cdecl CWbemProviderGlue::IncrementMapCount(class CWbemGlueFactory const * __ptr64)` | 396 (0x18c) | Exported Function | 0x0000000180011850 | 0x00011850
`protected: static long __cdecl CWbemProviderGlue::DecrementMapCount(long * __ptr64)` | 218 (0xda) | Exported Function | 0x0000000180011a50 | 0x00011a50
`protected: bool __cdecl CWinMsgEvent::UnRegisterMessage(unsigned int,int) __ptr64` | 545 (0x221) | Exported Function | 0x00000001800167e0 | 0x000167e0
`protected: bool __cdecl Provider::GetLocalInstancePath(class CInstance const * __ptr64,class CHString & __ptr64) __ptr64` | 335 (0x14f) | Exported Function | 0x000000018000a7f0 | 0x0000a7f0
`protected: bool __cdecl Provider::SetCreationClassName(class CInstance * __ptr64) __ptr64` | 507 (0x1fb) | Exported Function | 0x000000018000aaa0 | 0x0000aaa0
`protected: class CHString __cdecl Provider::MakeLocalPath(class CHString const & __ptr64) __ptr64` | 441 (0x1b9) | Exported Function | 0x000000018000a890 | 0x0000a890
`protected: class CHString const & __ptr64 __cdecl CFrameworkQuery::GetNamespace(void) __ptr64` | 346 (0x15a) | Exported Function | 0x0000000180005730 | 0x00005730
`protected: class CHString const & __ptr64 __cdecl Provider::GetLocalComputerName(void) __ptr64` | 334 (0x14e) | Exported Function | 0x0000000180002070 | 0x00002070
`protected: class CHString const & __ptr64 __cdecl Provider::GetNamespace(void) __ptr64` | 347 (0x15b) | Exported Function | 0x0000000180002080 | 0x00002080
`private: static struct HWND__ * __ptr64 __cdecl CWinMsgEvent::CreateMsgWindow(void)` | 214 (0xd6) | Exported Function | 0x0000000180016cf0 | 0x00016cf0
`protected: class CHString const & __ptr64 __cdecl Provider::GetProviderName(void) __ptr64` | 361 (0x169) | Exported Function | 0x0000000180002090 | 0x00002090
`protected: int __cdecl CFrameworkQuery::IsReference(unsigned short const * __ptr64) __ptr64` | 426 (0x1aa) | Exported Function | 0x00000001800056e0 | 0x000056e0
`protected: int __cdecl CHString::LoadStringW(unsigned int,unsigned short * __ptr64,unsigned int) __ptr64` | 430 (0x1ae) | Exported Function | 0x000000018001b800 | 0x0001b800
`protected: long __cdecl Provider::Commit(class CInstance * __ptr64,bool) __ptr64` | 197 (0xc5) | Exported Function | 0x000000018000a1e0 | 0x0000a1e0
`protected: long __cdecl Provider::ValidateFlags(long,enum Provider::FlagDefs) __ptr64` | 553 (0x229) | Exported Function | 0x000000018000aad0 | 0x0000aad0
`protected: static int __cdecl CHString::SafeStrlen(unsigned short const * __ptr64)` | 490 (0x1ea) | Exported Function | 0x00000001800016b0 | 0x000016b0
`protected: static long * __ptr64 __cdecl CWbemProviderGlue::GetMapCountPtr(class CWbemGlueFactory const * __ptr64)` | 344 (0x158) | Exported Function | 0x0000000180011ab0 | 0x00011ab0
`protected: static long __cdecl CWbemProviderGlue::DecrementMapCount(class CWbemGlueFactory const * __ptr64)` | 219 (0xdb) | Exported Function | 0x0000000180011950 | 0x00011950
`protected: class CInstance * __ptr64 __cdecl Provider::CreateNewInstance(class MethodContext * __ptr64) __ptr64` | 215 (0xd7) | Exported Function | 0x000000018000a0c0 | 0x0000a0c0
`protected: virtual long __cdecl Provider::ValidateQueryFlags(long) __ptr64` | 558 (0x22e) | Exported Function | 0x000000018000aaf0 | 0x0000aaf0
`private: static long CWbemProviderGlue::s_lObjects` | 610 (0x262) | Exported Function | 0x000000018003d520 | 0x0003d520
`private: static long __cdecl CWbemProviderGlue::CheckImpersonationLevel(void)` | 189 (0xbd) | Exported Function | 0x0000000180010c00 | 0x00010c00
`private: int __cdecl CObjectPathParser::ident_becomes_class(void) __ptr64` | 566 (0x236) | Exported Function | 0x0000000180015390 | 0x00015390
`private: int __cdecl CObjectPathParser::ident_becomes_ns(void) __ptr64` | 567 (0x237) | Exported Function | 0x0000000180015350 | 0x00015350
`private: int __cdecl CObjectPathParser::key_const(void) __ptr64` | 570 (0x23a) | Exported Function | 0x0000000180015520 | 0x00015520
`private: int __cdecl CObjectPathParser::keyref(void) __ptr64` | 571 (0x23b) | Exported Function | 0x0000000180015760 | 0x00015760
`private: int __cdecl CObjectPathParser::keyref_list(void) __ptr64` | 572 (0x23c) | Exported Function | 0x0000000180015730 | 0x00015730
`private: int __cdecl CObjectPathParser::keyref_term(void) __ptr64` | 573 (0x23d) | Exported Function | 0x0000000180015870 | 0x00015870
`private: int __cdecl CObjectPathParser::NextToken(void) __ptr64` | 449 (0x1c1) | Exported Function | 0x0000000180015080 | 0x00015080
`private: int __cdecl CObjectPathParser::ns_list(void) __ptr64` | 594 (0x252) | Exported Function | 0x0000000180015300 | 0x00015300
`private: int __cdecl CObjectPathParser::ns_list_rest(void) __ptr64` | 595 (0x253) | Exported Function | 0x00000001800154e0 | 0x000154e0
`private: int __cdecl CObjectPathParser::ns_or_class(void) __ptr64` | 596 (0x254) | Exported Function | 0x0000000180015220 | 0x00015220
`private: int __cdecl CObjectPathParser::ns_or_server(void) __ptr64` | 597 (0x255) | Exported Function | 0x0000000180015180 | 0x00015180
`private: int __cdecl CObjectPathParser::objref(void) __ptr64` | 598 (0x256) | Exported Function | 0x00000001800152b0 | 0x000152b0
`private: int __cdecl CObjectPathParser::objref_rest(void) __ptr64` | 599 (0x257) | Exported Function | 0x00000001800153d0 | 0x000153d0
`private: int __cdecl CObjectPathParser::optional_objref(void) __ptr64` | 600 (0x258) | Exported Function | 0x00000001800151d0 | 0x000151d0
`private: int __cdecl CObjectPathParser::propname(void) __ptr64` | 601 (0x259) | Exported Function | 0x00000001800158c0 | 0x000158c0
`private: int __cdecl CObjectPathParser::begin_parse(void) __ptr64` | 562 (0x232) | Exported Function | 0x00000001800150f0 | 0x000150f0
`private: int __cdecl Provider::SetKeyFromParsedObjectPath(class CInstance * __ptr64,struct ParsedObjectPath * __ptr64) __ptr64` | 521 (0x209) | Exported Function | 0x000000018000a920 | 0x0000a920
`private: class CWbemProviderGlue * __ptr64 __cdecl MethodContext::GetProviderGlue(void) __ptr64` | 360 (0x168) | Exported Function | 0x0000000180009950 | 0x00009950
`const ProviderLog::``vftable'` | 158 (0x9e) | Exported Function | 0x0000000180025298 | 0x00025298
`class CHString __cdecl operator+(class CHString const & __ptr64,class CHString const & __ptr64)` | 126 (0x7e) | Exported Function | 0x000000018001aa60 | 0x0001aa60
`class CHString __cdecl operator+(class CHString const & __ptr64,unsigned short const * __ptr64)` | 128 (0x80) | Exported Function | 0x000000018001aae0 | 0x0001aae0
`class CHString __cdecl operator+(class CHString const & __ptr64,unsigned short)` | 127 (0x7f) | Exported Function | 0x000000018001ac00 | 0x0001ac00
`class CHString __cdecl operator+(unsigned short const * __ptr64,class CHString const & __ptr64)` | 130 (0x82) | Exported Function | 0x000000018001ab70 | 0x0001ab70
`class CHString __cdecl operator+(unsigned short,class CHString const & __ptr64)` | 129 (0x81) | Exported Function | 0x000000018001ac80 | 0x0001ac80
`class ProviderLog captainsLog` | 563 (0x233) | Exported Function | 0x000000018003d0f0 | 0x0003d0f0
`const CFrameworkQueryEx::``vftable'` | 149 (0x95) | Exported Function | 0x00000001800252d0 | 0x000252d0
`const CInstance::``vftable'` | 150 (0x96) | Exported Function | 0x00000001800251e8 | 0x000251e8
`const CThreadBase::``vftable'` | 151 (0x97) | Exported Function | 0x0000000180025280 | 0x00025280
`const CWbemGlueFactory::``vftable'` | 152 (0x98) | Exported Function | 0x0000000180025220 | 0x00025220
`const CWbemProviderGlue::``vftable'{for ``IWbemProviderInit'}` | 153 (0x99) | Exported Function | 0x00000001800251f8 | 0x000251f8
`const CWbemProviderGlue::``vftable'{for ``IWbemServices'}` | 154 (0x9a) | Exported Function | 0x0000000180025080 | 0x00025080
`const CWinMsgEvent::``vftable'` | 155 (0x9b) | Exported Function | 0x0000000180025378 | 0x00025378
`const MethodContext::``vftable'` | 156 (0x9c) | Exported Function | 0x0000000180025250 | 0x00025250
`const Provider::``vftable'` | 157 (0x9d) | Exported Function | 0x0000000180025160 | 0x00025160
`DoCmd` | 614 (0x266) | Exported Function | 0x000000018000aec0 | 0x0000aec0
`private: int __cdecl Provider::ValidateIMOSPointer(void) __ptr64` | 555 (0x22b) | Exported Function | 0x000000018000a0b0 | 0x0000a0b0
`private: long __cdecl CRegistry::myRegCreateKeyEx(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES * __ptr64 const,struct HKEY__ * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 585 (0x249) | Exported Function | 0x000000018001f5b0 | 0x0001f5b0
`private: long __cdecl CRegistry::myRegDeleteKey(struct HKEY__ * __ptr64,unsigned short const * __ptr64) __ptr64` | 586 (0x24a) | Exported Function | 0x000000018001f720 | 0x0001f720
`private: static class CCritSec CWbemProviderGlue::s_csProviderMap` | 604 (0x25c) | Exported Function | 0x000000018003d1b0 | 0x0003d1b0
`private: static class CCritSec CWinMsgEvent::mg_csMapLock` | 579 (0x243) | Exported Function | 0x000000018003d278 | 0x0003d278
`private: static class CCritSec CWinMsgEvent::mg_csWindowLock` | 580 (0x244) | Exported Function | 0x000000018003d2a0 | 0x0003d2a0
`private: static class CHString Provider::s_strComputerName` | 612 (0x264) | Exported Function | 0x000000018003d0e8 | 0x0003d0e8
`private: static class Provider * __ptr64 __cdecl CWbemProviderGlue::AddProviderToMap(unsigned short const * __ptr64,unsigned short const * __ptr64,class Provider * __ptr64)` | 168 (0xa8) | Exported Function | 0x0000000180010850 | 0x00010850
`private: static class Provider * __ptr64 __cdecl CWbemProviderGlue::SearchMapForProvider(unsigned short const * __ptr64,unsigned short const * __ptr64)` | 492 (0x1ec) | Exported Function | 0x0000000180010710 | 0x00010710
`private: static class std::map<class CHString,void * __ptr64,struct std::less<class CHString>,class std::allocator<void * __ptr64> > CWbemProviderGlue::s_providersmap` | 611 (0x263) | Exported Function | 0x000000018003d148 | 0x0003d148
`private: static class std::map<void const * __ptr64,long * __ptr64,struct std::less<void const * __ptr64>,class std::allocator<long * __ptr64> > CWbemProviderGlue::s_factorymap` | 609 (0x261) | Exported Function | 0x000000018003d190 | 0x0003d190
`private: static class std::multimap<unsigned int,class CWinMsgEvent * __ptr64,struct std::less<unsigned int>,class std::allocator<class CWinMsgEvent * __ptr64> > CWinMsgEvent::mg_oSinkMap` | 584 (0x248) | Exported Function | 0x000000018003c908 | 0x0003c908
`private: static class std::set<void * __ptr64,struct std::less<void * __ptr64>,class std::allocator<void * __ptr64> > CWbemProviderGlue::m_FlushPtrs` | 574 (0x23e) | Exported Function | 0x000000018003d200 | 0x0003d200
`private: static int __cdecl CRegistry::SetPlatformID(void)` | 523 (0x20b) | Exported Function | 0x000000018001f550 | 0x0001f550
`private: static int __cdecl CWinMsgEvent::CtrlHandlerRoutine(unsigned long)` | 217 (0xd9) | Exported Function | 0x0000000180016c60 | 0x00016c60
`private: static int CRegistry::s_fPlatformSet` | 608 (0x260) | Exported Function | 0x000000018003d568 | 0x0003d568
`private: static int CWbemProviderGlue::s_bInitted` | 602 (0x25a) | Exported Function | 0x000000018003d524 | 0x0003d524
`private: static int Provider::initFailed_` | 569 (0x239) | Exported Function | 0x000000018003d2d4 | 0x0003d2d4
`private: static class CCritSec CWbemProviderGlue::s_csFactoryMap` | 603 (0x25b) | Exported Function | 0x000000018003d168 | 0x0003d168
`private: static class CCritSec CWbemProviderGlue::m_csStatusObject` | 576 (0x240) | Exported Function | 0x000000018003d1d8 | 0x0003d1d8
`private: static class CCritSec CWbemProviderGlue::m_csFlushPtrs` | 575 (0x23f) | Exported Function | 0x000000018003d220 | 0x0003d220
`private: static class CAutoEvent CWinMsgEvent::mg_aeCreateWindow` | 578 (0x242) | Exported Function | 0x000000018003d2c8 | 0x0003d2c8
`private: long __cdecl CRegistry::myRegDeleteValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64) __ptr64` | 587 (0x24b) | Exported Function | 0x000000018001edb0 | 0x0001edb0
`private: long __cdecl CRegistry::myRegEnumKey(struct HKEY__ * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long) __ptr64` | 588 (0x24c) | Exported Function | 0x000000018001f6d0 | 0x0001f6d0
`private: long __cdecl CRegistry::myRegEnumValue(struct HKEY__ * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 589 (0x24d) | Exported Function | 0x000000018001f830 | 0x0001f830
`private: long __cdecl CRegistry::myRegOpenKeyEx(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,struct HKEY__ * __ptr64 * __ptr64) __ptr64` | 590 (0x24e) | Exported Function | 0x000000018001f750 | 0x0001f750
`private: long __cdecl CRegistry::myRegQueryInfoKey(struct HKEY__ * __ptr64,unsigned short * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,struct _FILETIME * __ptr64) __ptr64` | 591 (0x24f) | Exported Function | 0x000000018001f790 | 0x0001f790
`private: long __cdecl CRegistry::myRegQueryValueEx(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 592 (0x250) | Exported Function | 0x000000018001f680 | 0x0001f680
`private: long __cdecl CRegistry::myRegSetValueEx(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,unsigned char const * __ptr64,unsigned long) __ptr64` | 593 (0x251) | Exported Function | 0x000000018001f630 | 0x0001f630
`private: static long __cdecl CWbemProviderGlue::GetInstanceFromCIMOM(unsigned short const * __ptr64,unsigned short const * __ptr64,class MethodContext * __ptr64,class CInstance * __ptr64 * __ptr64)` | 327 (0x147) | Exported Function | 0x0000000180010400 | 0x00010400
`private: long __cdecl CWbemProviderGlue::NullOutUnsetProperties(struct IWbemClassObject * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64,struct tagVARIANT const & __ptr64) __ptr64` | 451 (0x1c3) | Exported Function | 0x000000018000d7a0 | 0x0000d7a0
`private: long __cdecl Provider::CreateInstanceEnum(class MethodContext * __ptr64,long) __ptr64` | 211 (0xd3) | Exported Function | 0x000000018000a310 | 0x0000a310
`private: long __cdecl Provider::DeleteInstance(struct ParsedObjectPath * __ptr64,long,class MethodContext * __ptr64) __ptr64` | 226 (0xe2) | Exported Function | 0x000000018000a450 | 0x0000a450
`private: long __cdecl Provider::ExecMethod(struct ParsedObjectPath * __ptr64,unsigned short * __ptr64,long,class CInstance * __ptr64,class CInstance * __ptr64,class MethodContext * __ptr64) __ptr64` | 242 (0xf2) | Exported Function | 0x000000018000a510 | 0x0000a510
`private: long __cdecl Provider::ExecuteQuery(class MethodContext * __ptr64,class CFrameworkQuery & __ptr64,long) __ptr64` | 250 (0xfa) | Exported Function | 0x000000018000a220 | 0x0000a220
`private: long __cdecl Provider::GetObject(struct ParsedObjectPath * __ptr64,class MethodContext * __ptr64,long) __ptr64` | 353 (0x161) | Exported Function | 0x000000018000a600 | 0x0000a600
`private: long __cdecl Provider::PutInstance(struct IWbemClassObject * __ptr64,long,class MethodContext * __ptr64) __ptr64` | 465 (0x1d1) | Exported Function | 0x000000018000a380 | 0x0000a380
`private: static __int64 __cdecl CWinMsgEvent::MsgWndProc(struct HWND__ * __ptr64,unsigned int,unsigned __int64,__int64)` | 447 (0x1bf) | Exported Function | 0x0000000180016e60 | 0x00016e60
`private: long __cdecl CWbemProviderGlue::PreProcessPutInstanceParms(struct IWbemClassObject * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64,struct IWbemContext * __ptr64) __ptr64` | 460 (0x1cc) | Exported Function | 0x000000018000d580 | 0x0000d580
`unsigned long __cdecl NormalizePath(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,class CHString & __ptr64)` | 450 (0x1c2) | Exported Function | 0x000000018001f8a0 | 0x0001f8a0
`protected: virtual void __cdecl CThreadBase::OnFinalRelease(void) __ptr64` | 452 (0x1c4) | Exported Function | 0x000000018000b260 | 0x0000b260
`protected: void __cdecl CHString::AllocBeforeWrite(int) __ptr64` | 176 (0xb0) | Exported Function | 0x000000018001a3f0 | 0x0001a3f0
`public: bool __cdecl CInstance::GetWBEMINT64(unsigned short const * __ptr64,class CHString & __ptr64)const __ptr64` | 386 (0x182) | Exported Function | 0x0000000180008f00 | 0x00008f00
`public: bool __cdecl CInstance::GetWBEMINT64(unsigned short const * __ptr64,unsigned __int64 & __ptr64)const __ptr64` | 388 (0x184) | Exported Function | 0x0000000180008f80 | 0x00008f80
`public: bool __cdecl CInstance::GetWCHAR(unsigned short const * __ptr64,unsigned short * __ptr64 * __ptr64)const __ptr64` | 389 (0x185) | Exported Function | 0x00000001800074d0 | 0x000074d0
`public: bool __cdecl CInstance::GetWORD(unsigned short const * __ptr64,unsigned short & __ptr64)const __ptr64` | 390 (0x186) | Exported Function | 0x00000001800077d0 | 0x000077d0
`public: bool __cdecl CInstance::IsNull(unsigned short const * __ptr64)const __ptr64` | 421 (0x1a5) | Exported Function | 0x0000000180009290 | 0x00009290
`public: bool __cdecl CInstance::Setbool(unsigned short const * __ptr64,bool) __ptr64` | 537 (0x219) | Exported Function | 0x0000000180008410 | 0x00008410
`public: bool __cdecl CInstance::SetByte(unsigned short const * __ptr64,unsigned char) __ptr64` | 498 (0x1f2) | Exported Function | 0x0000000180007e40 | 0x00007e40
`public: bool __cdecl CInstance::SetCharSplat(unsigned short const * __ptr64,char const * __ptr64) __ptr64` | 505 (0x1f9) | Exported Function | 0x00000001800096d0 | 0x000096d0
`public: bool __cdecl CInstance::SetCharSplat(unsigned short const * __ptr64,unsigned long) __ptr64` | 504 (0x1f8) | Exported Function | 0x0000000180009730 | 0x00009730
`public: bool __cdecl CInstance::SetCharSplat(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 503 (0x1f7) | Exported Function | 0x00000001800096c0 | 0x000096c0
`public: bool __cdecl CInstance::SetCHString(unsigned short const * __ptr64,char const * __ptr64) __ptr64` | 501 (0x1f5) | Exported Function | 0x00000001800096d0 | 0x000096d0
`public: bool __cdecl CInstance::SetCHString(unsigned short const * __ptr64,class CHString const & __ptr64) __ptr64` | 500 (0x1f4) | Exported Function | 0x0000000180008dd0 | 0x00008dd0
`public: bool __cdecl CInstance::SetCHString(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 499 (0x1f3) | Exported Function | 0x00000001800096c0 | 0x000096c0
`public: bool __cdecl CInstance::SetDateTime(unsigned short const * __ptr64,class WBEMTime const & __ptr64) __ptr64` | 518 (0x206) | Exported Function | 0x0000000180008840 | 0x00008840
`public: bool __cdecl CInstance::SetDOUBLE(unsigned short const * __ptr64,double) __ptr64` | 516 (0x204) | Exported Function | 0x0000000180007bc0 | 0x00007bc0
`public: bool __cdecl CInstance::GetWBEMINT64(unsigned short const * __ptr64,__int64 & __ptr64)const __ptr64` | 387 (0x183) | Exported Function | 0x0000000180008f10 | 0x00008f10
`public: bool __cdecl CInstance::SetDWORD(unsigned short const * __ptr64,unsigned long) __ptr64` | 517 (0x205) | Exported Function | 0x0000000180007940 | 0x00007940
`public: bool __cdecl CInstance::GetWBEMINT16(unsigned short const * __ptr64,short & __ptr64)const __ptr64` | 385 (0x181) | Exported Function | 0x0000000180009110 | 0x00009110
`public: bool __cdecl CInstance::GetTimeSpan(unsigned short const * __ptr64,class WBEMTimeSpan & __ptr64)const __ptr64` | 376 (0x178) | Exported Function | 0x0000000180008c40 | 0x00008c40
`public: __cdecl WBEMTimeSpan::WBEMTimeSpan(struct _FILETIME const & __ptr64) __ptr64` | 48 (0x30) | Exported Function | 0x000000018001c650 | 0x0001c650
`public: __cdecl WBEMTimeSpan::WBEMTimeSpan(unsigned short * __ptr64 const) __ptr64` | 51 (0x33) | Exported Function | 0x00000001800019b0 | 0x000019b0
`public: __cdecl WBEMTimeSpan::WBEMTimeSpan(void) __ptr64` | 52 (0x34) | Exported Function | 0x00000001800019a0 | 0x000019a0
`public: bool __cdecl CFrameworkQuery::AllPropertiesAreRequired(void) __ptr64` | 175 (0xaf) | Exported Function | 0x0000000180001ef0 | 0x00001ef0
`public: bool __cdecl CFrameworkQuery::IsPropertyRequired(unsigned short const * __ptr64) __ptr64` | 425 (0x1a9) | Exported Function | 0x0000000180004930 | 0x00004930
`public: bool __cdecl CFrameworkQuery::KeysOnly(void) __ptr64` | 428 (0x1ac) | Exported Function | 0x0000000180001f00 | 0x00001f00
`public: bool __cdecl CInstance::Getbool(unsigned short const * __ptr64,bool & __ptr64)const __ptr64` | 391 (0x187) | Exported Function | 0x0000000180008540 | 0x00008540
`public: bool __cdecl CInstance::GetByte(unsigned short const * __ptr64,unsigned char & __ptr64)const __ptr64` | 286 (0x11e) | Exported Function | 0x00000001800080a0 | 0x000080a0
`public: bool __cdecl CInstance::GetCHString(unsigned short const * __ptr64,class CHString & __ptr64)const __ptr64` | 287 (0x11f) | Exported Function | 0x00000001800071a0 | 0x000071a0
`public: bool __cdecl CInstance::GetDateTime(unsigned short const * __ptr64,class WBEMTime & __ptr64)const __ptr64` | 319 (0x13f) | Exported Function | 0x0000000180008980 | 0x00008980
`public: bool __cdecl CInstance::GetDOUBLE(unsigned short const * __ptr64,double & __ptr64)const __ptr64` | 312 (0x138) | Exported Function | 0x0000000180007cd0 | 0x00007cd0
`public: bool __cdecl CInstance::GetDWORD(unsigned short const * __ptr64,unsigned long & __ptr64)const __ptr64` | 313 (0x139) | Exported Function | 0x0000000180007a50 | 0x00007a50
`public: bool __cdecl CInstance::GetEmbeddedObject(unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,class MethodContext * __ptr64)const __ptr64` | 320 (0x140) | Exported Function | 0x0000000180008210 | 0x00008210
`public: bool __cdecl CInstance::GetStatus(unsigned short const * __ptr64,bool & __ptr64,unsigned short & __ptr64)const __ptr64` | 369 (0x171) | Exported Function | 0x00000001800093a0 | 0x000093a0
`public: bool __cdecl CInstance::GetStringArray(unsigned short const * __ptr64,struct tagSAFEARRAY * __ptr64 & __ptr64)const __ptr64` | 372 (0x174) | Exported Function | 0x0000000180007320 | 0x00007320
`public: bool __cdecl CInstance::GetVariant(unsigned short const * __ptr64,struct tagVARIANT & __ptr64)const __ptr64` | 384 (0x180) | Exported Function | 0x0000000180008770 | 0x00008770
`public: bool __cdecl CInstance::SetEmbeddedObject(unsigned short const * __ptr64,class CInstance & __ptr64) __ptr64` | 520 (0x208) | Exported Function | 0x0000000180007f50 | 0x00007f50
`public: bool __cdecl CInstance::SetNull(unsigned short const * __ptr64) __ptr64` | 522 (0x20a) | Exported Function | 0x0000000180006f20 | 0x00006f20
`public: bool __cdecl CInstance::SetStringArray(unsigned short const * __ptr64,struct tagSAFEARRAY const & __ptr64) __ptr64` | 528 (0x210) | Exported Function | 0x0000000180007040 | 0x00007040
`public: class CHString __cdecl CHString::Mid(int,int)const __ptr64` | 446 (0x1be) | Exported Function | 0x000000018001b250 | 0x0001b250
`public: class CHString __cdecl CHString::Right(int)const __ptr64` | 489 (0x1e9) | Exported Function | 0x000000018001b320 | 0x0001b320
`public: class CHString __cdecl CHString::SpanExcluding(unsigned short const * __ptr64)const __ptr64` | 539 (0x21b) | Exported Function | 0x000000018001b4a0 | 0x0001b4a0
`public: class CHString __cdecl CHString::SpanIncluding(unsigned short const * __ptr64)const __ptr64` | 540 (0x21c) | Exported Function | 0x000000018001b450 | 0x0001b450
`public: class CHString __cdecl CHStringArray::GetAt(int)const __ptr64` | 281 (0x119) | Exported Function | 0x00000001800018e0 | 0x000018e0
`public: class CHString __cdecl CHStringArray::operator[](int)const __ptr64` | 121 (0x79) | Exported Function | 0x00000001800018e0 | 0x000018e0
`public: class CHString const & __ptr64 __cdecl CFrameworkQuery::GetQuery(void) __ptr64` | 362 (0x16a) | Exported Function | 0x0000000180005390 | 0x00005390
`public: class CHString const & __ptr64 __cdecl CHString::operator+=(char) __ptr64` | 142 (0x8e) | Exported Function | 0x0000000180001830 | 0x00001830
`public: class CHString const & __ptr64 __cdecl CHString::operator+=(class CHString const & __ptr64) __ptr64` | 141 (0x8d) | Exported Function | 0x000000018001ad70 | 0x0001ad70
`public: class CHString const & __ptr64 __cdecl CHString::operator+=(unsigned short const * __ptr64) __ptr64` | 144 (0x90) | Exported Function | 0x000000018001ad00 | 0x0001ad00
`public: class CHString const & __ptr64 __cdecl CHString::operator+=(unsigned short) __ptr64` | 143 (0x8f) | Exported Function | 0x000000018001ad40 | 0x0001ad40
`public: class CHString const & __ptr64 __cdecl CHString::operator=(char const * __ptr64) __ptr64` | 83 (0x53) | Exported Function | 0x000000018001a9b0 | 0x0001a9b0
`public: class CHString const & __ptr64 __cdecl CHString::operator=(char) __ptr64` | 80 (0x50) | Exported Function | 0x0000000180001800 | 0x00001800
`public: class CHString const & __ptr64 __cdecl CHString::operator=(class CHString * __ptr64) __ptr64` | 82 (0x52) | Exported Function | 0x00000001800017e0 | 0x000017e0
`public: class CHString const & __ptr64 __cdecl CHString::operator=(class CHString const & __ptr64) __ptr64` | 79 (0x4f) | Exported Function | 0x000000018001a8c0 | 0x0001a8c0
`public: class CHString __cdecl CHString::Mid(int)const __ptr64` | 445 (0x1bd) | Exported Function | 0x000000018001b210 | 0x0001b210
`public: class CHString __cdecl CHString::Left(int)const __ptr64` | 429 (0x1ad) | Exported Function | 0x000000018001b3c0 | 0x0001b3c0
`public: class CHString * __ptr64 __cdecl CHStringArray::GetData(void) __ptr64` | 317 (0x13d) | Exported Function | 0x0000000180001780 | 0x00001780
`public: class CHString & __ptr64 __cdecl CHStringArray::operator[](int) __ptr64` | 120 (0x78) | Exported Function | 0x0000000180001930 | 0x00001930
`public: bool __cdecl CInstance::SetTimeSpan(unsigned short const * __ptr64,class WBEMTimeSpan const & __ptr64) __ptr64` | 529 (0x211) | Exported Function | 0x0000000180008b10 | 0x00008b10
`public: bool __cdecl CInstance::SetVariant(unsigned short const * __ptr64,struct tagVARIANT const & __ptr64) __ptr64` | 530 (0x212) | Exported Function | 0x00000001800086b0 | 0x000086b0
`public: bool __cdecl CInstance::SetWBEMINT16(unsigned short const * __ptr64,short const & __ptr64) __ptr64` | 531 (0x213) | Exported Function | 0x0000000180008ff0 | 0x00008ff0
`public: bool __cdecl CInstance::SetWBEMINT64(unsigned short const * __ptr64,__int64) __ptr64` | 533 (0x215) | Exported Function | 0x0000000180008de0 | 0x00008de0
`public: bool __cdecl CInstance::SetWBEMINT64(unsigned short const * __ptr64,class CHString const & __ptr64) __ptr64` | 532 (0x214) | Exported Function | 0x0000000180008dd0 | 0x00008dd0
`public: bool __cdecl CInstance::SetWBEMINT64(unsigned short const * __ptr64,unsigned __int64) __ptr64` | 534 (0x216) | Exported Function | 0x0000000180008e70 | 0x00008e70
`public: bool __cdecl CInstance::SetWCHARSplat(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 535 (0x217) | Exported Function | 0x0000000180006dd0 | 0x00006dd0
`public: __cdecl WBEMTimeSpan::WBEMTimeSpan(int,int,int,int,int,int,int) __ptr64` | 50 (0x32) | Exported Function | 0x000000018001c5d0 | 0x0001c5d0
`public: bool __cdecl CInstance::SetWORD(unsigned short const * __ptr64,unsigned short) __ptr64` | 536 (0x218) | Exported Function | 0x00000001800076c0 | 0x000076c0
`public: bool __cdecl WBEMTime::IsOk(void)const __ptr64` | 423 (0x1a7) | Exported Function | 0x0000000180001a90 | 0x00001a90
`public: bool __cdecl WBEMTimeSpan::IsOk(void)const __ptr64` | 424 (0x1a8) | Exported Function | 0x0000000180001a90 | 0x00001a90
`public: class CAutoEvent & __ptr64 __cdecl CAutoEvent::operator=(class CAutoEvent const & __ptr64) __ptr64` | 75 (0x4b) | Exported Function | 0x0000000180001ab0 | 0x00001ab0
`public: class CFrameworkQuery & __ptr64 __cdecl CFrameworkQuery::operator=(class CFrameworkQuery const & __ptr64) __ptr64` | 76 (0x4c) | Exported Function | 0x0000000180001fc0 | 0x00001fc0
`public: class CFrameworkQueryEx & __ptr64 __cdecl CFrameworkQueryEx::operator=(class CFrameworkQueryEx const & __ptr64) __ptr64` | 77 (0x4d) | Exported Function | 0x0000000180005ab0 | 0x00005ab0
`public: class CHPtrArray & __ptr64 __cdecl CHPtrArray::operator=(class CHPtrArray const & __ptr64) __ptr64` | 78 (0x4e) | Exported Function | 0x0000000180001980 | 0x00001980
`public: class CHString & __ptr64 __cdecl CHStringArray::ElementAt(int) __ptr64` | 234 (0xea) | Exported Function | 0x0000000180001930 | 0x00001930
`public: bool __cdecl MethodContext::SetStatusObject(struct IWbemClassObject * __ptr64) __ptr64` | 527 (0x20f) | Exported Function | 0x0000000180009960 | 0x00009960
`protected: virtual void __cdecl Provider::Flush(void) __ptr64` | 256 (0x100) | Exported Function | 0x000000018000a030 | 0x0000a030
`public: __cdecl WBEMTimeSpan::WBEMTimeSpan(__int64 const & __ptr64) __ptr64` | 49 (0x31) | Exported Function | 0x000000018001c670 | 0x0001c670
`public: __cdecl WBEMTime::WBEMTime(unsigned short * __ptr64 const) __ptr64` | 46 (0x2e) | Exported Function | 0x0000000180001ad0 | 0x00001ad0
`public: __cdecl CHPtrArray::~CHPtrArray(void) __ptr64` | 57 (0x39) | Exported Function | 0x0000000180002c20 | 0x00002c20
`public: __cdecl CHString::CHString(char const * __ptr64) __ptr64` | 9 (0x9) | Exported Function | 0x000000018001a650 | 0x0001a650
`public: __cdecl CHString::CHString(class CHString const & __ptr64) __ptr64` | 7 (0x7) | Exported Function | 0x000000018001a740 | 0x0001a740
`public: __cdecl CHString::CHString(unsigned char const * __ptr64) __ptr64` | 10 (0xa) | Exported Function | 0x00000001800016d0 | 0x000016d0
`public: __cdecl CHString::CHString(unsigned short const * __ptr64) __ptr64` | 11 (0xb) | Exported Function | 0x000000018001a6d0 | 0x0001a6d0
`public: __cdecl CHString::CHString(unsigned short const * __ptr64,int) __ptr64` | 12 (0xc) | Exported Function | 0x000000018001a5f0 | 0x0001a5f0
`public: __cdecl CHString::CHString(unsigned short,int) __ptr64` | 8 (0x8) | Exported Function | 0x000000018001a530 | 0x0001a530
`public: __cdecl CHString::CHString(void) __ptr64` | 13 (0xd) | Exported Function | 0x000000018001a510 | 0x0001a510
`public: __cdecl CHString::operator unsigned short const * __ptr64(void)const __ptr64` | 122 (0x7a) | Exported Function | 0x0000000180001780 | 0x00001780
`public: __cdecl CHString::~CHString(void) __ptr64` | 58 (0x3a) | Exported Function | 0x000000018001a820 | 0x0001a820
`public: __cdecl CHStringArray::CHStringArray(void) __ptr64` | 14 (0xe) | Exported Function | 0x000000018001c920 | 0x0001c920
`public: __cdecl CHStringArray::~CHStringArray(void) __ptr64` | 59 (0x3b) | Exported Function | 0x000000018001c940 | 0x0001c940
`public: __cdecl CInstance::CInstance(class CInstance const & __ptr64) __ptr64` | 15 (0xf) | Exported Function | 0x0000000180002400 | 0x00002400
`public: __cdecl CInstance::CInstance(struct IWbemClassObject * __ptr64,class MethodContext * __ptr64) __ptr64` | 16 (0x10) | Exported Function | 0x0000000180006ad0 | 0x00006ad0
`public: __cdecl CObjectPathParser::CObjectPathParser(enum ObjectParserFlags) __ptr64` | 17 (0x11) | Exported Function | 0x0000000180014ba0 | 0x00014ba0
`public: __cdecl CHPtrArray::CHPtrArray(void) __ptr64` | 6 (0x6) | Exported Function | 0x000000018001c920 | 0x0001c920
`public: __cdecl CObjectPathParser::~CObjectPathParser(void) __ptr64` | 61 (0x3d) | Exported Function | 0x0000000180014c70 | 0x00014c70
`public: __cdecl CFrameworkQueryEx::~CFrameworkQueryEx(void) __ptr64` | 56 (0x38) | Exported Function | 0x0000000180005b60 | 0x00005b60
`public: __cdecl CFrameworkQueryEx::CFrameworkQueryEx(class CFrameworkQueryEx const & __ptr64) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180005a50 | 0x00005a50
`protected: void __cdecl CHString::AllocBuffer(int) __ptr64` | 177 (0xb1) | Exported Function | 0x0000000180019b00 | 0x00019b00
`protected: void __cdecl CHString::AllocCopy(class CHString & __ptr64,int,int,int)const __ptr64` | 178 (0xb2) | Exported Function | 0x00000001800199a0 | 0x000199a0
`protected: void __cdecl CHString::AssignCopy(int,unsigned short const * __ptr64) __ptr64` | 182 (0xb6) | Exported Function | 0x0000000180019bd0 | 0x00019bd0
`protected: void __cdecl CHString::ConcatCopy(int,unsigned short const * __ptr64,int,unsigned short const * __ptr64) __ptr64` | 200 (0xc8) | Exported Function | 0x0000000180019c90 | 0x00019c90
`protected: void __cdecl CHString::ConcatInPlace(int,unsigned short const * __ptr64) __ptr64` | 201 (0xc9) | Exported Function | 0x0000000180019dd0 | 0x00019dd0
`protected: void __cdecl CHString::CopyBeforeWrite(void) __ptr64` | 204 (0xcc) | Exported Function | 0x000000018001a370 | 0x0001a370
`protected: void __cdecl CHString::Init(void) __ptr64` | 401 (0x191) | Exported Function | 0x0000000180019980 | 0x00019980
`protected: void __cdecl CInstance::LogError(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,long)const __ptr64` | 440 (0x1b8) | Exported Function | 0x00000001800094a0 | 0x000094a0
`protected: void __cdecl CWinMsgEvent::RegisterForMessage(unsigned int,int) __ptr64` | 472 (0x1d8) | Exported Function | 0x0000000180016540 | 0x00016540
`protected: void __cdecl CWinMsgEvent::UnRegisterAllMessages(void) __ptr64` | 544 (0x220) | Exported Function | 0x0000000180016980 | 0x00016980
`public: __cdecl CAutoEvent::CAutoEvent(void) __ptr64` | 1 (0x1) | Exported Function | 0x00000001800163e0 | 0x000163e0
`public: __cdecl CAutoEvent::~CAutoEvent(void) __ptr64` | 54 (0x36) | Exported Function | 0x0000000180016420 | 0x00016420
`public: __cdecl CFrameworkQuery::CFrameworkQuery(class CFrameworkQuery const & __ptr64) __ptr64` | 2 (0x2) | Exported Function | 0x0000000180001f10 | 0x00001f10
`public: __cdecl CFrameworkQuery::CFrameworkQuery(void) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180004100 | 0x00004100
`public: __cdecl CFrameworkQuery::~CFrameworkQuery(void) __ptr64` | 55 (0x37) | Exported Function | 0x0000000180004150 | 0x00004150
`public: __cdecl CFrameworkQueryEx::CFrameworkQueryEx(void) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180005af0 | 0x00005af0
`public: __cdecl CreateMutexAsProcess::CreateMutexAsProcess(unsigned short const * __ptr64) __ptr64` | 32 (0x20) | Exported Function | 0x0000000180003de0 | 0x00003de0
`public: __cdecl CreateMutexAsProcess::~CreateMutexAsProcess(void) __ptr64` | 68 (0x44) | Exported Function | 0x00000001800040b0 | 0x000040b0
`public: __cdecl CRegistry::CRegistry(class CRegistry const & __ptr64) __ptr64` | 18 (0x12) | Exported Function | 0x0000000180002600 | 0x00002600
`public: __cdecl KeyRef::~KeyRef(void) __ptr64` | 69 (0x45) | Exported Function | 0x0000000180014810 | 0x00014810
`public: __cdecl MethodContext::MethodContext(class MethodContext const & __ptr64) __ptr64` | 35 (0x23) | Exported Function | 0x0000000180001d00 | 0x00001d00
`public: __cdecl MethodContext::MethodContext(struct IWbemContext * __ptr64,class CWbemProviderGlue * __ptr64) __ptr64` | 36 (0x24) | Exported Function | 0x00000001800097e0 | 0x000097e0
`public: __cdecl ParsedObjectPath::ParsedObjectPath(void) __ptr64` | 37 (0x25) | Exported Function | 0x0000000180013f00 | 0x00013f00
`public: __cdecl ParsedObjectPath::~ParsedObjectPath(void) __ptr64` | 71 (0x47) | Exported Function | 0x0000000180013f80 | 0x00013f80
`public: __cdecl Provider::Provider(class Provider const & __ptr64) __ptr64` | 38 (0x26) | Exported Function | 0x00000001800020a0 | 0x000020a0
`public: __cdecl Provider::Provider(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 39 (0x27) | Exported Function | 0x0000000180009e00 | 0x00009e00
`public: __cdecl ProviderLog::ProviderLog(class ProviderLog const & __ptr64) __ptr64` | 40 (0x28) | Exported Function | 0x00000001800028c0 | 0x000028c0
`public: __cdecl ProviderLog::ProviderLog(void) __ptr64` | 41 (0x29) | Exported Function | 0x0000000180002c50 | 0x00002c50
`public: __cdecl std::_Lockit::_Lockit(void) __ptr64` | 53 (0x35) | Exported Function | 0x0000000180002520 | 0x00002520
`public: __cdecl std::_Lockit::~_Lockit(void) __ptr64` | 74 (0x4a) | Exported Function | 0x0000000180002550 | 0x00002550
`public: __cdecl WBEMTime::WBEMTime(__int64 const & __ptr64) __ptr64` | 45 (0x2d) | Exported Function | 0x0000000180001b50 | 0x00001b50
`public: __cdecl WBEMTime::WBEMTime(struct _FILETIME const & __ptr64) __ptr64` | 42 (0x2a) | Exported Function | 0x0000000180001b10 | 0x00001b10
`public: __cdecl WBEMTime::WBEMTime(struct _SYSTEMTIME const & __ptr64) __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180001af0 | 0x00001af0
`public: __cdecl WBEMTime::WBEMTime(struct tm const & __ptr64) __ptr64` | 44 (0x2c) | Exported Function | 0x0000000180001b30 | 0x00001b30
`public: __cdecl KeyRef::KeyRef(void) __ptr64` | 34 (0x22) | Exported Function | 0x0000000180014750 | 0x00014750
`public: __cdecl KeyRef::KeyRef(unsigned short const * __ptr64,struct tagVARIANT const * __ptr64) __ptr64` | 33 (0x21) | Exported Function | 0x0000000180014780 | 0x00014780
`public: __cdecl CWinMsgEvent::~CWinMsgEvent(void) __ptr64` | 67 (0x43) | Exported Function | 0x00000001800164c0 | 0x000164c0
`public: __cdecl CWinMsgEvent::CWinMsgEvent(void) __ptr64` | 31 (0x1f) | Exported Function | 0x0000000180016490 | 0x00016490
`public: __cdecl CRegistry::CRegistry(void) __ptr64` | 19 (0x13) | Exported Function | 0x000000018001d670 | 0x0001d670
`public: __cdecl CRegistry::~CRegistry(void) __ptr64` | 62 (0x3e) | Exported Function | 0x000000018001d6d0 | 0x0001d6d0
`public: __cdecl CRegistrySearch::CRegistrySearch(class CRegistrySearch const & __ptr64) __ptr64` | 20 (0x14) | Exported Function | 0x0000000180002820 | 0x00002820
`public: __cdecl CRegistrySearch::CRegistrySearch(void) __ptr64` | 21 (0x15) | Exported Function | 0x000000018001edd0 | 0x0001edd0
`public: __cdecl CRegistrySearch::~CRegistrySearch(void) __ptr64` | 63 (0x3f) | Exported Function | 0x000000018001ee00 | 0x0001ee00
`public: __cdecl CThreadBase::CThreadBase(class CThreadBase const & __ptr64) __ptr64` | 22 (0x16) | Exported Function | 0x0000000180001b70 | 0x00001b70
`public: __cdecl CThreadBase::CThreadBase(enum CThreadBase::THREAD_SAFETY_MECHANISM) __ptr64` | 23 (0x17) | Exported Function | 0x000000018000b1e0 | 0x0000b1e0
`public: __cdecl WBEMTime::WBEMTime(void) __ptr64` | 47 (0x2f) | Exported Function | 0x00000001800019a0 | 0x000019a0
`public: __cdecl CWbemGlueFactory::CWbemGlueFactory(class CWbemGlueFactory const & __ptr64) __ptr64` | 24 (0x18) | Exported Function | 0x00000001800023c0 | 0x000023c0
`public: __cdecl CWbemGlueFactory::CWbemGlueFactory(void) __ptr64` | 26 (0x1a) | Exported Function | 0x0000000180003540 | 0x00003540
`public: __cdecl CWbemGlueFactory::~CWbemGlueFactory(void) __ptr64` | 65 (0x41) | Exported Function | 0x00000001800036f0 | 0x000036f0
`public: __cdecl CWbemProviderGlue::CWbemProviderGlue(class CWbemProviderGlue const & __ptr64) __ptr64` | 27 (0x1b) | Exported Function | 0x0000000180002290 | 0x00002290
`public: __cdecl CWbemProviderGlue::CWbemProviderGlue(long * __ptr64) __ptr64` | 28 (0x1c) | Exported Function | 0x000000018000b370 | 0x0000b370
`public: __cdecl CWbemProviderGlue::CWbemProviderGlue(void) __ptr64` | 29 (0x1d) | Exported Function | 0x000000018000b310 | 0x0000b310
`public: __cdecl CWbemProviderGlue::~CWbemProviderGlue(void) __ptr64` | 66 (0x42) | Exported Function | 0x000000018000b3b0 | 0x0000b3b0
`public: __cdecl CWinMsgEvent::CWinMsgEvent(class CWinMsgEvent const & __ptr64) __ptr64` | 30 (0x1e) | Exported Function | 0x0000000180016490 | 0x00016490
`public: __cdecl CWbemGlueFactory::CWbemGlueFactory(long * __ptr64) __ptr64` | 25 (0x19) | Exported Function | 0x00000001800035b0 | 0x000035b0
`void __cdecl SetCHStringResourceHandle(struct HINSTANCE__ * __ptr64)` | 502 (0x1f6) | Exported Function | 0x00000001800034e0 | 0x000034e0


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

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/9ee3b8287876f6a17c8a11c5a60130d182f5fb7ddd9569182969ecb91380a948/detection/





MIT License. Copyright (c) 2020 Strontic.


