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

Function Name | Ordinal | Type
-- | -- | --
`public: long __cdecl CInstance::Release(void) __ptr64` | 473 | Exported Function
`public: long __cdecl CInstance::Commit(void) __ptr64` | 194 | Exported Function
`public: long __cdecl CRegistry::DeleteKey(class CHString * __ptr64) __ptr64` | 227 | Exported Function
`public: long __cdecl CRegistry::CreateOpen(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES * __ptr64,unsigned long * __ptr64) __ptr64` | 214 | Exported Function
`public: long __cdecl CInstance::AddRef(void) __ptr64` | 167 | Exported Function
`public: long __cdecl CFrameworkQuery::Init(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,class CHString & __ptr64) __ptr64` | 398 | Exported Function
`public: long __cdecl CFrameworkQuery::Init(struct ParsedObjectPath * __ptr64,struct IWbemContext * __ptr64,unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 397 | Exported Function
`public: long __cdecl CFrameworkQueryEx::GetValuesForProp(unsigned short const * __ptr64,class std::vector<int,class std::allocator<int> > & __ptr64) __ptr64` | 380 | Exported Function
`public: long __cdecl CFrameworkQueryEx::GetValuesForProp(unsigned short const * __ptr64,class std::vector<class _variant_t,class std::allocator<class _variant_t> > & __ptr64) __ptr64` | 381 | Exported Function
`public: long __cdecl CRegistry::DeleteValue(unsigned short const * __ptr64) __ptr64` | 228 | Exported Function
`public: long __cdecl MethodContext::AddRef(void) __ptr64` | 171 | Exported Function
`public: long __cdecl CThreadBase::Release(void) __ptr64` | 474 | Exported Function
`public: static bool __cdecl CWbemProviderGlue::IsDerivedFrom(unsigned short const * __ptr64,unsigned short const * __ptr64,class MethodContext * __ptr64,unsigned short const * __ptr64)` | 411 | Exported Function
`public: long __cdecl MethodContext::Release(void) __ptr64` | 477 | Exported Function
`public: long __cdecl CThreadBase::AddRef(void) __ptr64` | 168 | Exported Function
`public: long __cdecl CRegistry::Open(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long) __ptr64` | 451 | Exported Function
`public: long __cdecl CRegistry::EnumerateAndGetValues(unsigned long & __ptr64,unsigned short * __ptr64 & __ptr64,unsigned char * __ptr64 & __ptr64) __ptr64` | 237 | Exported Function
`public: long __cdecl CRegistry::OpenLocalMachineKeyAndReadValue(unsigned short const * __ptr64,unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 454 | Exported Function
`public: long __cdecl CRegistry::OpenAndEnumerateSubKeys(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long) __ptr64` | 452 | Exported Function
`public: int __cdecl WBEMTime::operator>(class WBEMTime const & __ptr64)const __ptr64` | 135 | Exported Function
`public: int __cdecl WBEMTime::operator==(class WBEMTime const & __ptr64)const __ptr64` | 111 | Exported Function
`public: int __cdecl WBEMTime::SetDMTF(unsigned short * __ptr64 const) __ptr64` | 513 | Exported Function
`public: int __cdecl WBEMTime::operator>=(class WBEMTime const & __ptr64)const __ptr64` | 137 | Exported Function
`public: int __cdecl WBEMTime::operator<=(class WBEMTime const & __ptr64)const __ptr64` | 133 | Exported Function
`public: int __cdecl WBEMTime::Gettime_t(__int64 * __ptr64)const __ptr64` | 391 | Exported Function
`public: int __cdecl WBEMTime::GetSYSTEMTIME(struct _SYSTEMTIME * __ptr64)const __ptr64` | 364 | Exported Function
`public: int __cdecl WBEMTime::operator<(class WBEMTime const & __ptr64)const __ptr64` | 131 | Exported Function
`public: int __cdecl WBEMTime::operator!=(class WBEMTime const & __ptr64)const __ptr64` | 113 | Exported Function
`public: int __cdecl WBEMTimeSpan::GetFILETIME(struct _FILETIME * __ptr64)const __ptr64` | 322 | Exported Function
`public: int __cdecl WBEMTimeSpan::operator>=(class WBEMTimeSpan const & __ptr64)const __ptr64` | 138 | Exported Function
`public: int __cdecl WBEMTimeSpan::operator>(class WBEMTimeSpan const & __ptr64)const __ptr64` | 136 | Exported Function
`public: long __cdecl CFrameworkQuery::GetValuesForProp(unsigned short const * __ptr64,class std::vector<class _bstr_t,class std::allocator<class _bstr_t> > & __ptr64) __ptr64` | 378 | Exported Function
`public: long __cdecl CFrameworkQuery::GetValuesForProp(unsigned short const * __ptr64,class CHStringArray & __ptr64) __ptr64` | 379 | Exported Function
`public: int __cdecl WBEMTimeSpan::operator==(class WBEMTimeSpan const & __ptr64)const __ptr64` | 112 | Exported Function
`public: int __cdecl WBEMTimeSpan::operator!=(class WBEMTimeSpan const & __ptr64)const __ptr64` | 114 | Exported Function
`public: int __cdecl WBEMTimeSpan::Gettime_t(__int64 * __ptr64)const __ptr64` | 392 | Exported Function
`public: int __cdecl WBEMTimeSpan::operator<=(class WBEMTimeSpan const & __ptr64)const __ptr64` | 134 | Exported Function
`public: int __cdecl WBEMTimeSpan::operator<(class WBEMTimeSpan const & __ptr64)const __ptr64` | 132 | Exported Function
`public: static long __cdecl WBEMTime::GetLocalOffsetForDate(struct _SYSTEMTIME const * __ptr64)` | 336 | Exported Function
`public: static long __cdecl WBEMTime::GetLocalOffsetForDate(struct _FILETIME const * __ptr64)` | 335 | Exported Function
`public: static struct IWbemServices * __ptr64 __cdecl CWbemProviderGlue::GetNamespaceConnection(unsigned short const * __ptr64)` | 346 | Exported Function
`public: static long __cdecl WBEMTime::GetLocalOffsetForDate(struct tm const * __ptr64)` | 337 | Exported Function
`public: static long __cdecl WBEMTime::GetLocalOffsetForDate(__int64 const & __ptr64)` | 334 | Exported Function
`public: static long __cdecl CWbemProviderGlue::GetInstancePropertiesByPath(unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,class MethodContext * __ptr64,class CHStringArray & __ptr64)` | 327 | Exported Function
`public: static long __cdecl CWbemProviderGlue::GetInstanceKeysByPath(unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,class MethodContext * __ptr64)` | 326 | Exported Function
`public: static long __cdecl CWbemProviderGlue::GetInstancesByQueryAsynch(unsigned short const * __ptr64,class Provider * __ptr64,long (__cdecl*)(class Provider * __ptr64,class CInstance * __ptr64,class MethodContext * __ptr64,void * __ptr64),unsigned short const * __ptr64,class MethodContext * __ptr64,void * __ptr64)` | 329 | Exported Function
`public: static long __cdecl CWbemProviderGlue::GetInstancesByQuery(unsigned short const * __ptr64,class TRefPointerCollection<class CInstance> * __ptr64,class MethodContext * __ptr64,unsigned short const * __ptr64)` | 328 | Exported Function
`public: static struct IWbemServices * __ptr64 __cdecl CWbemProviderGlue::GetNamespaceConnection(unsigned short const * __ptr64,class MethodContext * __ptr64)` | 347 | Exported Function
`public: static void __cdecl CWbemProviderGlue::FrameworkLogoff(unsigned short const * __ptr64,unsigned short const * __ptr64)` | 264 | Exported Function
`public: static void __cdecl CWbemProviderGlue::FrameworkLogin(unsigned short const * __ptr64,class Provider * __ptr64,unsigned short const * __ptr64)` | 261 | Exported Function
`public: struct HKEY__ * __ptr64 __cdecl CRegistry::GethKey(void) __ptr64` | 390 | Exported Function
`public: static void __cdecl CWbemProviderGlue::IncrementObjectCount(void)` | 395 | Exported Function
`public: static void __cdecl CHString::Release(struct CHStringData * __ptr64)` | 472 | Exported Function
`public: static unsigned long __cdecl CWbemProviderGlue::GetPlatform(void)` | 356 | Exported Function
`public: static unsigned long __cdecl CWbemProviderGlue::GetOSMajorVersion(void)` | 349 | Exported Function
`public: static unsigned short const * __ptr64 __cdecl CWbemProviderGlue::GetCSDVersion(void)` | 286 | Exported Function
`public: static unsigned short * __ptr64 __cdecl CObjectPathParser::GetRelativePath(unsigned short * __ptr64)` | 362 | Exported Function
`public: static int __cdecl CWbemProviderGlue::FrameworkLogoffDLL(unsigned short const * __ptr64)` | 265 | Exported Function
`public: static int __cdecl CWbemProviderGlue::FrameworkLoginDLL(unsigned short const * __ptr64,long * __ptr64)` | 263 | Exported Function
`public: static int __cdecl Provider::initFailed(void)` | 565 | Exported Function
`public: static int __cdecl CWbemProviderGlue::FrameworkLogoffDLL(unsigned short const * __ptr64,long * __ptr64)` | 266 | Exported Function
`public: static int __cdecl CWbemProviderGlue::FrameworkLoginDLL(unsigned short const * __ptr64)` | 262 | Exported Function
`public: static class CWbemGlueFactory * __ptr64 __cdecl CWbemGlueFactory::Create(long * __ptr64)` | 203 | Exported Function
`public: static bool __cdecl CWbemProviderGlue::SetStatusObject(class MethodContext * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,long,struct tagSAFEARRAY const * __ptr64,struct tagSAFEARRAY const * __ptr64)` | 524 | Exported Function
`public: static int __cdecl CObjectPathParser::Unparse(struct ParsedObjectPath * __ptr64,unsigned short * __ptr64 * __ptr64)` | 548 | Exported Function
`public: static class CWbemGlueFactory * __ptr64 __cdecl CWbemGlueFactory::Create(void)` | 204 | Exported Function
`public: static long __cdecl CWbemProviderGlue::DecrementObjectCount(void)` | 218 | Exported Function
`public: static long __cdecl CWbemProviderGlue::GetEmptyInstance(class MethodContext * __ptr64,unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,unsigned short const * __ptr64)` | 319 | Exported Function
`public: static long __cdecl CWbemProviderGlue::GetAllInstancesAsynch(unsigned short const * __ptr64,class Provider * __ptr64,long (__cdecl*)(class Provider * __ptr64,class CInstance * __ptr64,class MethodContext * __ptr64,void * __ptr64),unsigned short const * __ptr64,class MethodContext * __ptr64,void * __ptr64)` | 275 | Exported Function
`public: static long __cdecl CWbemProviderGlue::GetInstanceByPath(unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,class MethodContext * __ptr64)` | 324 | Exported Function
`public: static long __cdecl CWbemProviderGlue::GetEmptyInstance(unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,unsigned short const * __ptr64)` | 320 | Exported Function
`public: static long __cdecl CWbemProviderGlue::GetAllInstances(unsigned short const * __ptr64,class TRefPointerCollection<class CInstance> * __ptr64,unsigned short const * __ptr64,class MethodContext * __ptr64)` | 274 | Exported Function
`public: static long __cdecl CWbemProviderGlue::FillInstance(class MethodContext * __ptr64,class CInstance * __ptr64)` | 250 | Exported Function
`public: static long __cdecl CWbemProviderGlue::FillInstance(class CInstance * __ptr64,unsigned short const * __ptr64)` | 249 | Exported Function
`public: static long __cdecl CWbemProviderGlue::GetAllDerivedInstancesAsynch(unsigned short const * __ptr64,class Provider * __ptr64,long (__cdecl*)(class Provider * __ptr64,class CInstance * __ptr64,class MethodContext * __ptr64,void * __ptr64),unsigned short const * __ptr64,class MethodContext * __ptr64,void * __ptr64)` | 273 | Exported Function
`public: static long __cdecl CWbemProviderGlue::GetAllDerivedInstances(unsigned short const * __ptr64,class TRefPointerCollection<class CInstance> * __ptr64,class MethodContext * __ptr64,unsigned short const * __ptr64)` | 272 | Exported Function
`public: class WBEMTimeSpan & __ptr64 __cdecl WBEMTimeSpan::operator=(class WBEMTimeSpan && __ptr64) __ptr64` | 106 | Exported Function
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator=(unsigned short * __ptr64 const) __ptr64` | 105 | Exported Function
`public: class WBEMTimeSpan __cdecl WBEMTime::operator-(class WBEMTime const & __ptr64) __ptr64` | 121 | Exported Function
`public: class WBEMTimeSpan & __ptr64 __cdecl WBEMTimeSpan::operator=(class WBEMTimeSpan const & __ptr64) __ptr64` | 107 | Exported Function
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator=(struct tm const & __ptr64) __ptr64` | 103 | Exported Function
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator=(__int64 const & __ptr64) __ptr64` | 104 | Exported Function
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator-=(class WBEMTimeSpan const & __ptr64) __ptr64` | 145 | Exported Function
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator=(struct _SYSTEMTIME const & __ptr64) __ptr64` | 102 | Exported Function
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator=(struct _FILETIME const & __ptr64) __ptr64` | 101 | Exported Function
`public: class WBEMTimeSpan __cdecl WBEMTimeSpan::operator+(class WBEMTimeSpan const & __ptr64)const __ptr64` | 130 | Exported Function
`public: enum ProviderLog::LogLevel __cdecl ProviderLog::IsLoggingOn(class CHString * __ptr64) __ptr64` | 417 | Exported Function
`public: class WBEMTimeSpan const & __ptr64 __cdecl WBEMTimeSpan::operator=(unsigned short * __ptr64 const) __ptr64` | 110 | Exported Function
`public: int __cdecl CFrameworkQueryEx::Is3TokenOR(unsigned short const * __ptr64,unsigned short const * __ptr64,struct tagVARIANT & __ptr64,struct tagVARIANT & __ptr64) __ptr64` | 409 | Exported Function
`public: int __cdecl CAutoEvent::Signal(void) __ptr64` | 536 | Exported Function
`public: class WBEMTimeSpan const & __ptr64 __cdecl WBEMTimeSpan::operator=(struct _FILETIME const & __ptr64) __ptr64` | 108 | Exported Function
`public: class WBEMTimeSpan const & __ptr64 __cdecl WBEMTimeSpan::operator+=(class WBEMTimeSpan const & __ptr64) __ptr64` | 144 | Exported Function
`public: class WBEMTimeSpan __cdecl WBEMTimeSpan::operator-(class WBEMTimeSpan const & __ptr64)const __ptr64` | 123 | Exported Function
`public: class WBEMTimeSpan const & __ptr64 __cdecl WBEMTimeSpan::operator=(__int64 const & __ptr64) __ptr64` | 109 | Exported Function
`public: class WBEMTimeSpan const & __ptr64 __cdecl WBEMTimeSpan::operator-=(class WBEMTimeSpan const & __ptr64) __ptr64` | 146 | Exported Function
`public: class CThreadBase & __ptr64 __cdecl CThreadBase::operator=(class CThreadBase const & __ptr64) __ptr64` | 89 | Exported Function
`public: class CRegistrySearch & __ptr64 __cdecl CRegistrySearch::operator=(class CRegistrySearch const & __ptr64) __ptr64` | 88 | Exported Function
`public: class CWbemProviderGlue & __ptr64 __cdecl CWbemProviderGlue::operator=(class CWbemProviderGlue const & __ptr64) __ptr64` | 91 | Exported Function
`public: class CWbemGlueFactory & __ptr64 __cdecl CWbemGlueFactory::operator=(class CWbemGlueFactory const & __ptr64) __ptr64` | 90 | Exported Function
`public: class CRegistry & __ptr64 __cdecl CRegistry::operator=(class CRegistry const & __ptr64) __ptr64` | 87 | Exported Function
`public: class CInstance & __ptr64 __cdecl CInstance::operator=(class CInstance const & __ptr64) __ptr64` | 85 | Exported Function
`public: class CHStringArray & __ptr64 __cdecl CHStringArray::operator=(class CHStringArray const & __ptr64) __ptr64` | 84 | Exported Function
`public: class CreateMutexAsProcess & __ptr64 __cdecl CreateMutexAsProcess::operator=(class CreateMutexAsProcess const & __ptr64) __ptr64` | 93 | Exported Function
`public: class CObjectPathParser & __ptr64 __cdecl CObjectPathParser::operator=(class CObjectPathParser const & __ptr64) __ptr64` | 86 | Exported Function
`public: class CWinMsgEvent & __ptr64 __cdecl CWinMsgEvent::operator=(class CWinMsgEvent const & __ptr64) __ptr64` | 92 | Exported Function
`public: class WBEMTime __cdecl WBEMTime::operator+(class WBEMTimeSpan const & __ptr64)const __ptr64` | 129 | Exported Function
`public: class WBEMTime & __ptr64 __cdecl WBEMTime::operator=(class WBEMTime const & __ptr64) __ptr64` | 100 | Exported Function
`public: class WBEMTime const & __ptr64 __cdecl WBEMTime::operator+=(class WBEMTimeSpan const & __ptr64) __ptr64` | 143 | Exported Function
`public: class WBEMTime __cdecl WBEMTime::operator-(class WBEMTimeSpan const & __ptr64)const __ptr64` | 122 | Exported Function
`public: class WBEMTime & __ptr64 __cdecl WBEMTime::operator=(class WBEMTime && __ptr64) __ptr64` | 99 | Exported Function
`public: class MethodContext * __ptr64 __cdecl CInstance::GetMethodContext(void)const __ptr64` | 343 | Exported Function
`public: class MethodContext & __ptr64 __cdecl MethodContext::operator=(class MethodContext const & __ptr64) __ptr64` | 95 | Exported Function
`public: class ProviderLog & __ptr64 __cdecl ProviderLog::operator=(class ProviderLog const & __ptr64) __ptr64` | 98 | Exported Function
`public: class Provider & __ptr64 __cdecl Provider::operator=(class Provider const & __ptr64) __ptr64` | 97 | Exported Function
`public: int __cdecl CThreadBase::BeginWrite(unsigned long) __ptr64` | 182 | Exported Function
`public: int __cdecl CThreadBase::BeginRead(unsigned long) __ptr64` | 181 | Exported Function
`public: int __cdecl ParsedObjectPath::AddKeyRef(unsigned short const * __ptr64,struct tagVARIANT const * __ptr64) __ptr64` | 163 | Exported Function
`public: int __cdecl ParsedObjectPath::AddKeyRef(struct KeyRef * __ptr64) __ptr64` | 162 | Exported Function
`public: int __cdecl CRegistrySearch::SearchAndBuildList(class CHString,class CHPtrArray & __ptr64,class CHString,class CHString,int,struct HKEY__ * __ptr64) __ptr64` | 489 | Exported Function
`public: int __cdecl CObjectPathParser::Parse(unsigned short const * __ptr64,struct ParsedObjectPath * __ptr64 * __ptr64) __ptr64` | 457 | Exported Function
`public: int __cdecl CHStringArray::GetUpperBound(void)const __ptr64` | 376 | Exported Function
`public: int __cdecl CRegistrySearch::LocateKeyByNameOrValueName(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64 * __ptr64,unsigned long,class CHString & __ptr64,class CHString & __ptr64) __ptr64` | 432 | Exported Function
`public: int __cdecl CRegistrySearch::FreeSearchList(int,class CHPtrArray & __ptr64) __ptr64` | 271 | Exported Function
`public: int __cdecl ParsedObjectPath::AddKeyRefEx(unsigned short const * __ptr64,struct tagVARIANT const * __ptr64) __ptr64` | 164 | Exported Function
`public: int __cdecl ParsedObjectPath::SetClassName(unsigned short const * __ptr64) __ptr64` | 504 | Exported Function
`public: int __cdecl ParsedObjectPath::IsRelative(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 425 | Exported Function
`public: int __cdecl WBEMTime::GetStructtm(struct tm * __ptr64)const __ptr64` | 371 | Exported Function
`public: int __cdecl WBEMTime::GetFILETIME(struct _FILETIME * __ptr64)const __ptr64` | 321 | Exported Function
`public: int __cdecl ParsedObjectPath::IsObject(void) __ptr64` | 420 | Exported Function
`public: int __cdecl ParsedObjectPath::IsClass(void) __ptr64` | 410 | Exported Function
`public: int __cdecl ParsedObjectPath::AddNamespace(unsigned short const * __ptr64) __ptr64` | 165 | Exported Function
`public: int __cdecl ParsedObjectPath::IsLocal(unsigned short const * __ptr64) __ptr64` | 416 | Exported Function
`public: int __cdecl ParsedObjectPath::IsInstance(void) __ptr64` | 415 | Exported Function
`public: int __cdecl CHString::Compare(unsigned short const * __ptr64)const __ptr64` | 196 | Exported Function
`public: int __cdecl CHString::Collate(unsigned short const * __ptr64)const __ptr64` | 193 | Exported Function
`public: int __cdecl CHString::Find(unsigned short const * __ptr64)const __ptr64` | 252 | Exported Function
`public: int __cdecl CHString::CompareNoCase(unsigned short const * __ptr64)const __ptr64` | 197 | Exported Function
`public: int __cdecl CHPtrArray::GetUpperBound(void)const __ptr64` | 375 | Exported Function
`public: int __cdecl CHPtrArray::Add(void * __ptr64) __ptr64` | 159 | Exported Function
`public: int __cdecl CFrameworkQueryEx::IsNTokenAnd(class CHStringArray & __ptr64,class CHPtrArray & __ptr64) __ptr64` | 418 | Exported Function
`public: int __cdecl CHPtrArray::GetSize(void)const __ptr64` | 365 | Exported Function
`public: int __cdecl CHPtrArray::Append(class CHPtrArray const & __ptr64) __ptr64` | 178 | Exported Function
`public: int __cdecl CHString::Find(unsigned short)const __ptr64` | 251 | Exported Function
`public: int __cdecl CHStringArray::Add(unsigned short const * __ptr64) __ptr64` | 160 | Exported Function
`public: int __cdecl CHString::ReverseFind(unsigned short)const __ptr64` | 485 | Exported Function
`public: int __cdecl CHStringArray::GetSize(void)const __ptr64` | 366 | Exported Function
`public: int __cdecl CHStringArray::Append(class CHStringArray const & __ptr64) __ptr64` | 179 | Exported Function
`public: int __cdecl CHString::LoadStringW(unsigned int) __ptr64` | 429 | Exported Function
`public: int __cdecl CHString::GetAllocLength(void)const __ptr64` | 276 | Exported Function
`public: int __cdecl CHString::FindOneOf(unsigned short const * __ptr64)const __ptr64` | 253 | Exported Function
`public: int __cdecl CHString::IsEmpty(void)const __ptr64` | 412 | Exported Function
`public: int __cdecl CHString::GetLength(void)const __ptr64` | 331 | Exported Function
`public: struct IWbemClassObject * __ptr64 __cdecl CInstance::GetClassObjectInterface(void) __ptr64` | 288 | Exported Function
`public: void __cdecl CFrameworkQueryEx::GetPropertyBitMask(class CHPtrArray const & __ptr64,void * __ptr64) __ptr64` | 357 | Exported Function
`public: void __cdecl CFrameworkQuery::Init2(struct IWbemClassObject * __ptr64) __ptr64` | 396 | Exported Function
`public: void __cdecl CHPtrArray::FreeExtra(void) __ptr64` | 268 | Exported Function
`public: void __cdecl CHPtrArray::Copy(class CHPtrArray const & __ptr64) __ptr64` | 200 | Exported Function
`public: void __cdecl CFrameworkQuery::GetRequiredProperties(class CHStringArray & __ptr64) __ptr64` | 363 | Exported Function
`public: void * __ptr64 * __ptr64 __cdecl CHPtrArray::GetData(void) __ptr64` | 312 | Exported Function
`public: void * __ptr64 & __ptr64 __cdecl CHPtrArray::operator[](int) __ptr64` | 115 | Exported Function
`public: void * __ptr64 __cdecl CHPtrArray::operator[](int)const __ptr64` | 116 | Exported Function
`public: void * __ptr64 __cdecl CHPtrArray::GetAt(int)const __ptr64` | 277 | Exported Function
`public: void __cdecl CHPtrArray::InsertAt(int,class CHPtrArray * __ptr64) __ptr64` | 404 | Exported Function
`public: void __cdecl CHString::Empty(void) __ptr64` | 233 | Exported Function
`public: void __cdecl CHPtrArray::SetSize(int,int) __ptr64` | 522 | Exported Function
`public: void __cdecl CHString::Format(unsigned short const * __ptr64,...) __ptr64` | 257 | Exported Function
`public: void __cdecl CHString::Format(unsigned int,...) __ptr64` | 256 | Exported Function
`public: void __cdecl CHPtrArray::SetAtGrow(int,void * __ptr64) __ptr64` | 494 | Exported Function
`public: void __cdecl CHPtrArray::RemoveAll(void) __ptr64` | 479 | Exported Function
`public: void __cdecl CHPtrArray::InsertAt(int,void * __ptr64,int) __ptr64` | 405 | Exported Function
`public: void __cdecl CHPtrArray::SetAt(int,void * __ptr64) __ptr64` | 491 | Exported Function
`public: void __cdecl CHPtrArray::RemoveAt(int,int) __ptr64` | 481 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::PutClass(struct IWbemClassObject * __ptr64,long,struct IWbemContext * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 460 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::OpenNamespace(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemServices * __ptr64 * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 455 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::PutInstance(struct IWbemClassObject * __ptr64,long,struct IWbemContext * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 462 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::PutClassAsync(struct IWbemClassObject * __ptr64,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 461 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::Initialize(unsigned short * __ptr64,long,unsigned short * __ptr64,unsigned short * __ptr64,struct IWbemServices * __ptr64,struct IWbemContext * __ptr64,struct IWbemProviderInitSink * __ptr64) __ptr64` | 403 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::ExecQueryAsync(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 247 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::ExecQuery(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IEnumWbemClassObject * __ptr64 * __ptr64) __ptr64` | 245 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::GetObjectAsync(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 354 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::GetObject(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 350 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::PutInstanceAsync(struct IWbemClassObject * __ptr64,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 465 | Exported Function
`public: virtual unsigned long __cdecl CWbemProviderGlue::Release(void) __ptr64` | 476 | Exported Function
`public: virtual unsigned long __cdecl CWbemProviderGlue::AddRef(void) __ptr64` | 170 | Exported Function
`public: void * __ptr64 & __ptr64 __cdecl CHPtrArray::ElementAt(int) __ptr64` | 231 | Exported Function
`public: virtual void __cdecl MethodContext::QueryPostProcess(void) __ptr64` | 469 | Exported Function
`public: virtual unsigned long __cdecl CWbemGlueFactory::Release(void) __ptr64` | 475 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::QueryObjectSink(long,struct IWbemObjectSink * __ptr64 * __ptr64) __ptr64` | 468 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 467 | Exported Function
`public: virtual unsigned long __cdecl CWbemGlueFactory::AddRef(void) __ptr64` | 169 | Exported Function
`public: virtual struct IWbemContext * __ptr64 __cdecl MethodContext::GetIWBEMContext(void) __ptr64` | 323 | Exported Function
`public: void __cdecl CRegistry::RewindSubKeys(void) __ptr64` | 486 | Exported Function
`public: void __cdecl CRegistry::Close(void) __ptr64` | 191 | Exported Function
`public: void __cdecl CThreadBase::EndRead(void) __ptr64` | 235 | Exported Function
`public: void __cdecl CThreadBase::``default constructor closure'(void) __ptr64` | 158 | Exported Function
`public: void __cdecl CObjectPathParser::Free(struct ParsedObjectPath * __ptr64) __ptr64` | 267 | Exported Function
`public: void __cdecl CHStringArray::SetAtGrow(int,unsigned short const * __ptr64) __ptr64` | 495 | Exported Function
`public: void __cdecl CHStringArray::SetAt(int,unsigned short const * __ptr64) __ptr64` | 493 | Exported Function
`public: void __cdecl CObjectPathParser::``default constructor closure'(void) __ptr64` | 157 | Exported Function
`public: void __cdecl CHStringArray::SetSize(int,int) __ptr64` | 523 | Exported Function
`public: void __cdecl CThreadBase::EndWrite(void) __ptr64` | 236 | Exported Function
`public: void const * __ptr64 * __ptr64 __cdecl CHPtrArray::GetData(void)const __ptr64` | 313 | Exported Function
`public: void __cdecl WBEMTimeSpan::Clear(void) __ptr64` | 189 | Exported Function
`void __cdecl SetCHStringResourceHandle(struct HINSTANCE__ * __ptr64)` | 500 | Exported Function
`unsigned long __cdecl NormalizePath(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,class CHString & __ptr64)` | 448 | Exported Function
`public: void __cdecl WBEMTime::Clear(void) __ptr64` | 188 | Exported Function
`public: void __cdecl ParsedObjectPath::ClearKeys(void) __ptr64` | 190 | Exported Function
`public: void __cdecl CWbemGlueFactory::Destroy(void) __ptr64` | 229 | Exported Function
`public: void __cdecl ProviderLog::LocalLogMessage(unsigned short const * __ptr64,unsigned short const * __ptr64,int,enum ProviderLog::LogLevel) __ptr64` | 430 | Exported Function
`public: void __cdecl ProviderLog::LocalLogMessage(unsigned short const * __ptr64,int,enum ProviderLog::LogLevel,unsigned short const * __ptr64,...) __ptr64` | 431 | Exported Function
`public: void __cdecl CHString::MakeUpper(void) __ptr64` | 442 | Exported Function
`public: void __cdecl CHString::MakeReverse(void) __ptr64` | 441 | Exported Function
`public: void __cdecl CHString::ReleaseBuffer(int) __ptr64` | 478 | Exported Function
`public: void __cdecl CHString::Release(void) __ptr64` | 471 | Exported Function
`public: void __cdecl CHString::MakeLower(void) __ptr64` | 440 | Exported Function
`public: void __cdecl CHString::FormatMessageW(unsigned short const * __ptr64,...) __ptr64` | 259 | Exported Function
`public: void __cdecl CHString::FormatMessageW(unsigned int,...) __ptr64` | 258 | Exported Function
`public: void __cdecl CHString::FreeExtra(void) __ptr64` | 269 | Exported Function
`public: void __cdecl CHString::FormatV(unsigned short const * __ptr64,char * __ptr64) __ptr64` | 260 | Exported Function
`public: void __cdecl CHString::SetAt(int,unsigned short) __ptr64` | 492 | Exported Function
`public: void __cdecl CHStringArray::InsertAt(int,unsigned short const * __ptr64,int) __ptr64` | 407 | Exported Function
`public: void __cdecl CHStringArray::InsertAt(int,class CHStringArray * __ptr64) __ptr64` | 406 | Exported Function
`public: void __cdecl CHStringArray::RemoveAt(int,int) __ptr64` | 482 | Exported Function
`public: void __cdecl CHStringArray::RemoveAll(void) __ptr64` | 480 | Exported Function
`public: void __cdecl CHStringArray::FreeExtra(void) __ptr64` | 270 | Exported Function
`public: void __cdecl CHString::TrimRight(void) __ptr64` | 540 | Exported Function
`public: void __cdecl CHString::TrimLeft(void) __ptr64` | 539 | Exported Function
`public: void __cdecl CHStringArray::Copy(class CHStringArray const & __ptr64) __ptr64` | 201 | Exported Function
`public: void __cdecl CHString::UnlockBuffer(void) __ptr64` | 545 | Exported Function
`public: unsigned long __cdecl CRegistry::GetLongestValueData(void) __ptr64` | 340 | Exported Function
`public: unsigned long __cdecl CRegistry::GetLongestSubKeySize(void) __ptr64` | 339 | Exported Function
`public: unsigned long __cdecl CRegistry::GetValueCount(void) __ptr64` | 377 | Exported Function
`public: unsigned long __cdecl CRegistry::GetLongestValueName(void) __ptr64` | 341 | Exported Function
`public: unsigned long __cdecl CRegistry::GetLongestClassStringSize(void) __ptr64` | 338 | Exported Function
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyValue(unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 306 | Exported Function
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyPath(class CHString & __ptr64) __ptr64` | 304 | Exported Function
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyValue(unsigned short const * __ptr64,void * __ptr64,unsigned long * __ptr64) __ptr64` | 307 | Exported Function
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyValue(unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 305 | Exported Function
`public: unsigned long __cdecl CRegistry::NextSubKey(void) __ptr64` | 446 | Exported Function
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 509 | Exported Function
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(unsigned short const * __ptr64,class CHStringArray & __ptr64) __ptr64` | 511 | Exported Function
`public: unsigned short * __ptr64 __cdecl CFrameworkQuery::GetQueryClassName(void) __ptr64` | 361 | Exported Function
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValueExpand(struct HKEY__ * __ptr64,unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 512 | Exported Function
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 510 | Exported Function
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 507 | Exported Function
`public: unsigned long __cdecl CRegistry::OpenCurrentUser(unsigned short const * __ptr64,unsigned long) __ptr64` | 453 | Exported Function
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 506 | Exported Function
`public: unsigned long __cdecl CRegistry::SetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,class CHStringArray & __ptr64) __ptr64` | 508 | Exported Function
`public: unsigned long __cdecl CRegistry::DeleteCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64) __ptr64` | 221 | Exported Function
`public: unsigned long __cdecl CAutoEvent::Wait(unsigned long) __ptr64` | 557 | Exported Function
`public: unsigned long __cdecl CRegistry::GetCurrentBinaryKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 291 | Exported Function
`public: unsigned long __cdecl CRegistry::DeleteCurrentKeyValue(unsigned short const * __ptr64) __ptr64` | 222 | Exported Function
`public: unsigned __int64 __cdecl WBEMTimeSpan::GetTime(void)const __ptr64` | 373 | Exported Function
`public: struct KeyRef & __ptr64 __cdecl KeyRef::operator=(struct KeyRef const & __ptr64) __ptr64` | 94 | Exported Function
`public: struct IWbemClassObject * __ptr64 __cdecl MethodContext::GetStatusObject(void) __ptr64` | 369 | Exported Function
`public: unsigned __int64 __cdecl WBEMTime::GetTime(void)const __ptr64` | 372 | Exported Function
`public: struct ParsedObjectPath & __ptr64 __cdecl ParsedObjectPath::operator=(struct ParsedObjectPath const & __ptr64) __ptr64` | 96 | Exported Function
`public: unsigned long __cdecl CRegistry::GetCurrentBinaryKeyValue(unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 292 | Exported Function
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 297 | Exported Function
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(unsigned short const * __ptr64,class CHStringArray & __ptr64) __ptr64` | 299 | Exported Function
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyName(class CHString & __ptr64) __ptr64` | 303 | Exported Function
`public: unsigned long __cdecl CRegistry::GetCurrentSubKeyCount(void) __ptr64` | 302 | Exported Function
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 298 | Exported Function
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,class CHString & __ptr64) __ptr64` | 295 | Exported Function
`public: unsigned long __cdecl CRegistry::GetCurrentBinaryKeyValue(unsigned short const * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 293 | Exported Function
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long & __ptr64) __ptr64` | 294 | Exported Function
`public: unsigned long __cdecl CRegistry::GetCurrentKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,class CHStringArray & __ptr64) __ptr64` | 296 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::CancelAsyncRequest(long) __ptr64` | 184 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::CancelAsyncCall(struct IWbemObjectSink * __ptr64) __ptr64` | 183 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::CreateClassEnumAsync(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 206 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::CreateClassEnum(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IEnumWbemClassObject * __ptr64 * __ptr64) __ptr64` | 205 | Exported Function
`public: virtual long __cdecl CWbemGlueFactory::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 466 | Exported Function
`public: virtual long __cdecl CFrameworkQueryEx::InitEx(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,class CHString & __ptr64) __ptr64` | 402 | Exported Function
`public: virtual bool __cdecl CFrameworkQueryEx::IsExtended(void) __ptr64` | 413 | Exported Function
`public: virtual long __cdecl CWbemGlueFactory::LockServer(int) __ptr64` | 437 | Exported Function
`public: virtual long __cdecl CWbemGlueFactory::CreateInstance(struct IUnknown * __ptr64,struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 207 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::CreateInstanceEnum(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IEnumWbemClassObject * __ptr64 * __ptr64) __ptr64` | 208 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::ExecMethodAsync(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemClassObject * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 242 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::ExecMethod(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemClassObject * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 239 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::ExecNotificationQueryAsync(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 244 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::ExecNotificationQuery(unsigned short * __ptr64 const,unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IEnumWbemClassObject * __ptr64 * __ptr64) __ptr64` | 243 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::DeleteInstanceAsync(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 226 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::DeleteClass(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 219 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::CreateInstanceEnumAsync(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 210 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::DeleteInstance(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemCallResult * __ptr64 * __ptr64) __ptr64` | 223 | Exported Function
`public: virtual long __cdecl CWbemProviderGlue::DeleteClassAsync(unsigned short * __ptr64 const,long,struct IWbemContext * __ptr64,struct IWbemObjectSink * __ptr64) __ptr64` | 220 | Exported Function
`public: unsigned short * __ptr64 __cdecl ParsedObjectPath::GetNamespacePart(void) __ptr64` | 348 | Exported Function
`public: unsigned short * __ptr64 __cdecl ParsedObjectPath::GetKeyString(void) __ptr64` | 330 | Exported Function
`public: unsigned short * __ptr64 __cdecl WBEMTime::GetBSTR(void)const __ptr64` | 280 | Exported Function
`public: unsigned short * __ptr64 __cdecl ParsedObjectPath::GetParentNamespacePart(void) __ptr64` | 355 | Exported Function
`public: unsigned short * __ptr64 __cdecl CRegistry::GetClassNameW(void) __ptr64` | 287 | Exported Function
`public: unsigned short * __ptr64 __cdecl CHString::GetBuffer(int) __ptr64` | 282 | Exported Function
`public: unsigned short * __ptr64 __cdecl CHString::AllocSysString(void)const __ptr64` | 177 | Exported Function
`public: unsigned short * __ptr64 __cdecl CHString::LockBuffer(void) __ptr64` | 434 | Exported Function
`public: unsigned short * __ptr64 __cdecl CHString::GetBufferSetLength(int) __ptr64` | 283 | Exported Function
`public: unsigned short * __ptr64 __cdecl WBEMTime::GetDMTF(int)const __ptr64` | 308 | Exported Function
`public: virtual __cdecl MethodContext::~MethodContext(void) __ptr64` | 69 | Exported Function
`public: virtual __cdecl CThreadBase::~CThreadBase(void) __ptr64` | 63 | Exported Function
`public: virtual __cdecl ProviderLog::~ProviderLog(void) __ptr64` | 72 | Exported Function
`public: virtual __cdecl Provider::~Provider(void) __ptr64` | 71 | Exported Function
`public: virtual __cdecl CInstance::~CInstance(void) __ptr64` | 59 | Exported Function
`public: unsigned short * __ptr64 __cdecl WBEMTimeSpan::GetBSTR(void)const __ptr64` | 281 | Exported Function
`public: unsigned short * __ptr64 __cdecl WBEMTime::GetDMTFNonNtfs(void)const __ptr64` | 309 | Exported Function
`public: unsigned short __cdecl CHString::operator[](int)const __ptr64` | 117 | Exported Function
`public: unsigned short __cdecl CHString::GetAt(int)const __ptr64` | 278 | Exported Function
`public: class CHString const * __ptr64 __cdecl CHStringArray::GetData(void)const __ptr64` | 316 | Exported Function
`private: unsigned long __cdecl CRegistry::GetCurrentRawSubKeyValue(unsigned short const * __ptr64,void * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 301 | Exported Function
`private: unsigned long __cdecl CRegistry::GetCurrentRawKeyValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64,void * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 300 | Exported Function
`private: void __cdecl CFrameworkQuery::Reset(void) __ptr64` | 484 | Exported Function
`private: unsigned long __cdecl CRegistry::OpenSubKey(void) __ptr64` | 456 | Exported Function
`private: struct IWbemServices * __ptr64 __cdecl CWbemProviderGlue::InternalGetNamespaceConnection(unsigned short const * __ptr64) __ptr64` | 408 | Exported Function
`private: static void __cdecl CWinMsgEvent::WindowsDispatch(void)` | 558 | Exported Function
`private: static void __cdecl CWinMsgEvent::DestroyMsgWindow(void)` | 230 | Exported Function
`private: struct IWbemClassObject * __ptr64 __cdecl Provider::GetClassObjectInterface(class MethodContext * __ptr64) __ptr64` | 289 | Exported Function
`private: static void __cdecl Provider::InitComputerName(void)` | 401 | Exported Function
`private: void __cdecl CObjectPathParser::Empty(void) __ptr64` | 234 | Exported Function
`private: void __cdecl CThreadBase::Unlock(void) __ptr64` | 544 | Exported Function
`private: void __cdecl CThreadBase::Lock(void) __ptr64` | 433 | Exported Function
`private: void __cdecl CWbemProviderGlue::FlushAll(void) __ptr64` | 255 | Exported Function
`private: void __cdecl CWbemProviderGlue::AddFlushPtr(void * __ptr64) __ptr64` | 161 | Exported Function
`private: void __cdecl CRegistrySearch::CheckAndAddToList(class CRegistry * __ptr64,class CHString,class CHString,class CHPtrArray & __ptr64,class CHString,class CHString,int) __ptr64` | 185 | Exported Function
`private: void __cdecl CRegistry::CloseSubKey(void) __ptr64` | 192 | Exported Function
`private: void __cdecl CObjectPathParser::Zero(void) __ptr64` | 559 | Exported Function
`private: void __cdecl CRegistry::SetDefaultValues(void) __ptr64` | 517 | Exported Function
`private: void __cdecl CRegistry::PrepareToReOpen(void) __ptr64` | 459 | Exported Function
`private: static unsigned long CWbemProviderGlue::s_dwMajorVersion` | 602 | Exported Function
`private: static unsigned long CRegistry::s_dwPlatform` | 603 | Exported Function
`private: static unsigned short * CWbemProviderGlue::s_wstrCSDVersion` | 610 | Exported Function
`private: static unsigned long CWbemProviderGlue::s_dwPlatform` | 604 | Exported Function
`private: static unsigned long __cdecl CWinMsgEvent::dwThreadProc(void * __ptr64)` | 562 | Exported Function
`private: static struct HWND__ * __ptr64 __ptr64 CWinMsgEvent::mg_hWnd` | 580 | Exported Function
`private: static struct HWND__ * __ptr64 __cdecl CWinMsgEvent::CreateMsgWindow(void)` | 212 | Exported Function
`private: static struct IWbemClassObject * __ptr64 __ptr64 CWbemProviderGlue::m_pStatusObject` | 574 | Exported Function
`private: static struct IWbemClassObject * __ptr64 __cdecl CWbemProviderGlue::GetStatusObject(class MethodContext * __ptr64,unsigned short const * __ptr64)` | 368 | Exported Function
`private: static void * __ptr64 __ptr64 CWinMsgEvent::mg_hDevNotify` | 578 | Exported Function
`private: static void __cdecl CWbemProviderGlue::UnlockFactoryMap(void)` | 546 | Exported Function
`private: static void __cdecl CWbemProviderGlue::UnInit(void)` | 541 | Exported Function
`private: static void __cdecl CWinMsgEvent::CreateMsgProvider(void)` | 211 | Exported Function
`private: static void __cdecl CWbemProviderGlue::UnlockProviderMap(void)` | 547 | Exported Function
`private: static void __cdecl CWbemProviderGlue::LockProviderMap(void)` | 436 | Exported Function
`private: static void __cdecl CWbemProviderGlue::GetComputerNameW(class CHString & __ptr64)` | 290 | Exported Function
`private: static void * __ptr64 __ptr64 CWinMsgEvent::mg_hThreadPumpHandle` | 579 | Exported Function
`private: static void __cdecl CWbemProviderGlue::LockFactoryMap(void)` | 435 | Exported Function
`private: static void __cdecl CWbemProviderGlue::Init(void)` | 400 | Exported Function
`protected: virtual long __cdecl Provider::EnumerateInstances(class MethodContext * __ptr64,long) __ptr64` | 238 | Exported Function
`protected: virtual long __cdecl Provider::DeleteInstance(class CInstance const & __ptr64,long) __ptr64` | 225 | Exported Function
`protected: virtual long __cdecl Provider::ExecQuery(class MethodContext * __ptr64,class CFrameworkQuery & __ptr64,long) __ptr64` | 246 | Exported Function
`protected: virtual long __cdecl Provider::ExecMethod(class CInstance const & __ptr64,unsigned short * __ptr64 const,class CInstance * __ptr64,class CInstance * __ptr64,long) __ptr64` | 241 | Exported Function
`protected: unsigned long __cdecl CFrameworkQuery::IsInList(class CHStringArray const & __ptr64,unsigned short const * __ptr64) __ptr64` | 414 | Exported Function
`protected: static void __cdecl CWbemProviderGlue::AddToFactoryMap(class CWbemGlueFactory const * __ptr64,long * __ptr64)` | 172 | Exported Function
`protected: static long __cdecl CWbemProviderGlue::IncrementMapCount(long * __ptr64)` | 393 | Exported Function
`protected: struct CHStringData * __ptr64 __cdecl CHString::GetData(void)const __ptr64` | 314 | Exported Function
`protected: static void __cdecl CWbemProviderGlue::RemoveFromFactoryMap(class CWbemGlueFactory const * __ptr64)` | 483 | Exported Function
`protected: virtual long __cdecl Provider::GetObject(class CInstance * __ptr64,long) __ptr64` | 352 | Exported Function
`protected: virtual long __cdecl Provider::ValidatePutInstanceFlags(long) __ptr64` | 555 | Exported Function
`protected: virtual long __cdecl Provider::ValidateMethodFlags(long) __ptr64` | 554 | Exported Function
`protected: virtual void __cdecl CThreadBase::OnFinalRelease(void) __ptr64` | 450 | Exported Function
`protected: virtual long __cdecl Provider::ValidateQueryFlags(long) __ptr64` | 556 | Exported Function
`protected: virtual long __cdecl Provider::ValidateGetObjFlags(long) __ptr64` | 552 | Exported Function
`protected: virtual long __cdecl Provider::PutInstance(class CInstance const & __ptr64,long) __ptr64` | 464 | Exported Function
`protected: virtual long __cdecl Provider::GetObject(class CInstance * __ptr64,long,class CFrameworkQuery & __ptr64) __ptr64` | 353 | Exported Function
`protected: virtual long __cdecl Provider::ValidateEnumerationFlags(long) __ptr64` | 550 | Exported Function
`protected: virtual long __cdecl Provider::ValidateDeletionFlags(long) __ptr64` | 549 | Exported Function
`protected: class CHString const & __ptr64 __cdecl Provider::GetLocalComputerName(void) __ptr64` | 332 | Exported Function
`protected: class CHString const & __ptr64 __cdecl CFrameworkQuery::GetNamespace(void) __ptr64` | 344 | Exported Function
`protected: class CHString const & __ptr64 __cdecl Provider::GetProviderName(void) __ptr64` | 359 | Exported Function
`protected: class CHString const & __ptr64 __cdecl Provider::GetNamespace(void) __ptr64` | 345 | Exported Function
`protected: class CHString __cdecl Provider::MakeLocalPath(class CHString const & __ptr64) __ptr64` | 439 | Exported Function
`protected: bool __cdecl CWinMsgEvent::UnRegisterMessage(unsigned int,int) __ptr64` | 543 | Exported Function
`private: void __cdecl ProviderLog::CheckFileSize(union _LARGE_INTEGER & __ptr64,class CHString const & __ptr64) __ptr64` | 186 | Exported Function
`protected: bool __cdecl Provider::SetCreationClassName(class CInstance * __ptr64) __ptr64` | 505 | Exported Function
`protected: bool __cdecl Provider::GetLocalInstancePath(class CInstance const * __ptr64,class CHString & __ptr64) __ptr64` | 333 | Exported Function
`protected: class CInstance * __ptr64 __cdecl Provider::CreateNewInstance(class MethodContext * __ptr64) __ptr64` | 213 | Exported Function
`protected: static long __cdecl CWbemProviderGlue::DecrementMapCount(class CWbemGlueFactory const * __ptr64)` | 217 | Exported Function
`protected: static long * __ptr64 __cdecl CWbemProviderGlue::GetMapCountPtr(class CWbemGlueFactory const * __ptr64)` | 342 | Exported Function
`protected: static long __cdecl CWbemProviderGlue::IncrementMapCount(class CWbemGlueFactory const * __ptr64)` | 394 | Exported Function
`protected: static long __cdecl CWbemProviderGlue::DecrementMapCount(long * __ptr64)` | 216 | Exported Function
`protected: static int __cdecl CHString::SafeStrlen(unsigned short const * __ptr64)` | 488 | Exported Function
`protected: int __cdecl CHString::LoadStringW(unsigned int,unsigned short * __ptr64,unsigned int) __ptr64` | 428 | Exported Function
`protected: int __cdecl CFrameworkQuery::IsReference(unsigned short const * __ptr64) __ptr64` | 424 | Exported Function
`protected: long __cdecl Provider::ValidateFlags(long,enum Provider::FlagDefs) __ptr64` | 551 | Exported Function
`protected: long __cdecl Provider::Commit(class CInstance * __ptr64,bool) __ptr64` | 195 | Exported Function
`private: int __cdecl CObjectPathParser::NextToken(void) __ptr64` | 447 | Exported Function
`private: int __cdecl CObjectPathParser::keyref_term(void) __ptr64` | 570 | Exported Function
`private: int __cdecl CObjectPathParser::ns_list_rest(void) __ptr64` | 592 | Exported Function
`private: int __cdecl CObjectPathParser::ns_list(void) __ptr64` | 591 | Exported Function
`private: int __cdecl CObjectPathParser::keyref_list(void) __ptr64` | 569 | Exported Function
`private: int __cdecl CObjectPathParser::ident_becomes_ns(void) __ptr64` | 564 | Exported Function
`private: int __cdecl CObjectPathParser::ident_becomes_class(void) __ptr64` | 563 | Exported Function
`private: int __cdecl CObjectPathParser::keyref(void) __ptr64` | 568 | Exported Function
`private: int __cdecl CObjectPathParser::key_const(void) __ptr64` | 567 | Exported Function
`private: int __cdecl CObjectPathParser::ns_or_class(void) __ptr64` | 593 | Exported Function
`private: int __cdecl Provider::ValidateIMOSPointer(void) __ptr64` | 553 | Exported Function
`private: int __cdecl Provider::SetKeyFromParsedObjectPath(class CInstance * __ptr64,struct ParsedObjectPath * __ptr64) __ptr64` | 519 | Exported Function
`private: long __cdecl CRegistry::myRegDeleteKey(struct HKEY__ * __ptr64,unsigned short const * __ptr64) __ptr64` | 583 | Exported Function
`private: long __cdecl CRegistry::myRegCreateKeyEx(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES * __ptr64 const,struct HKEY__ * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 582 | Exported Function
`private: int __cdecl CObjectPathParser::propname(void) __ptr64` | 598 | Exported Function
`private: int __cdecl CObjectPathParser::objref(void) __ptr64` | 595 | Exported Function
`private: int __cdecl CObjectPathParser::ns_or_server(void) __ptr64` | 594 | Exported Function
`private: int __cdecl CObjectPathParser::optional_objref(void) __ptr64` | 597 | Exported Function
`private: int __cdecl CObjectPathParser::objref_rest(void) __ptr64` | 596 | Exported Function
`const CFrameworkQueryEx::``vftable'` | 147 | Exported Function
`class ProviderLog captainsLog` | 561 | Exported Function
`const CThreadBase::``vftable'` | 149 | Exported Function
`const CInstance::``vftable'` | 148 | Exported Function
`class CHString __cdecl operator+(unsigned short,class CHString const & __ptr64)` | 127 | Exported Function
`class CHString __cdecl operator+(class CHString const & __ptr64,unsigned short const * __ptr64)` | 126 | Exported Function
`class CHString __cdecl operator+(class CHString const & __ptr64,class CHString const & __ptr64)` | 124 | Exported Function
`class CHString __cdecl operator+(unsigned short const * __ptr64,class CHString const & __ptr64)` | 128 | Exported Function
`class CHString __cdecl operator+(class CHString const & __ptr64,unsigned short)` | 125 | Exported Function
`const CWbemGlueFactory::``vftable'` | 150 | Exported Function
`DoCmd` | 611 | Exported Function
`const ProviderLog::``vftable'` | 156 | Exported Function
`private: int __cdecl CObjectPathParser::begin_parse(void) __ptr64` | 560 | Exported Function
`private: class CWbemProviderGlue * __ptr64 __cdecl MethodContext::GetProviderGlue(void) __ptr64` | 358 | Exported Function
`const Provider::``vftable'` | 155 | Exported Function
`const CWbemProviderGlue::``vftable'{for ``IWbemServices'}` | 152 | Exported Function
`const CWbemProviderGlue::``vftable'{for ``IWbemProviderInit'}` | 151 | Exported Function
`const MethodContext::``vftable'` | 154 | Exported Function
`const CWinMsgEvent::``vftable'` | 153 | Exported Function
`private: static class Provider * __ptr64 __cdecl CWbemProviderGlue::SearchMapForProvider(unsigned short const * __ptr64,unsigned short const * __ptr64)` | 490 | Exported Function
`private: static class Provider * __ptr64 __cdecl CWbemProviderGlue::AddProviderToMap(unsigned short const * __ptr64,unsigned short const * __ptr64,class Provider * __ptr64)` | 166 | Exported Function
`private: static class std::map<void const * __ptr64,long * __ptr64,struct std::less<void const * __ptr64>,class std::allocator<struct std::pair<void const * __ptr64 const,long * __ptr64> > > CWbemProviderGlue::s_factorymap` | 606 | Exported Function
`private: static class std::map<class CHString,void * __ptr64,struct std::less<class CHString>,class std::allocator<struct std::pair<class CHString const ,void * __ptr64> > > CWbemProviderGlue::s_providersmap` | 608 | Exported Function
`private: static class CHString Provider::s_strComputerName` | 609 | Exported Function
`private: static class CCritSec CWbemProviderGlue::s_csProviderMap` | 601 | Exported Function
`private: static class CCritSec CWbemProviderGlue::s_csFactoryMap` | 600 | Exported Function
`private: static class CCritSec CWinMsgEvent::mg_csWindowLock` | 577 | Exported Function
`private: static class CCritSec CWinMsgEvent::mg_csMapLock` | 576 | Exported Function
`private: static class std::multimap<unsigned int,class CWinMsgEvent * __ptr64,struct std::less<unsigned int>,class std::allocator<struct std::pair<unsigned int const ,class CWinMsgEvent * __ptr64> > > CWinMsgEvent::mg_oSinkMap` | 581 | Exported Function
`private: static long __cdecl CWbemProviderGlue::CheckImpersonationLevel(void)` | 187 | Exported Function
`private: static int Provider::initFailed_` | 566 | Exported Function
`private: static long CWbemProviderGlue::s_lObjects` | 607 | Exported Function
`private: static long __cdecl CWbemProviderGlue::GetInstanceFromCIMOM(unsigned short const * __ptr64,unsigned short const * __ptr64,class MethodContext * __ptr64,class CInstance * __ptr64 * __ptr64)` | 325 | Exported Function
`private: static int CWbemProviderGlue::s_bInitted` | 599 | Exported Function
`private: static int __cdecl CRegistry::SetPlatformID(void)` | 521 | Exported Function
`private: static class std::set<void * __ptr64,struct std::less<void * __ptr64>,class std::allocator<void * __ptr64> > CWbemProviderGlue::m_FlushPtrs` | 571 | Exported Function
`private: static int CRegistry::s_fPlatformSet` | 605 | Exported Function
`private: static int __cdecl CWinMsgEvent::CtrlHandlerRoutine(unsigned long)` | 215 | Exported Function
`private: long __cdecl CRegistry::myRegSetValueEx(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,unsigned char const * __ptr64,unsigned long) __ptr64` | 590 | Exported Function
`private: long __cdecl CRegistry::myRegQueryValueEx(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 589 | Exported Function
`private: long __cdecl CWbemProviderGlue::PreProcessPutInstanceParms(struct IWbemClassObject * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64,struct IWbemContext * __ptr64) __ptr64` | 458 | Exported Function
`private: long __cdecl CWbemProviderGlue::NullOutUnsetProperties(struct IWbemClassObject * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64,struct tagVARIANT const & __ptr64) __ptr64` | 449 | Exported Function
`private: long __cdecl CRegistry::myRegQueryInfoKey(struct HKEY__ * __ptr64,unsigned short * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,struct _FILETIME * __ptr64) __ptr64` | 588 | Exported Function
`private: long __cdecl CRegistry::myRegEnumKey(struct HKEY__ * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long) __ptr64` | 585 | Exported Function
`private: long __cdecl CRegistry::myRegDeleteValue(struct HKEY__ * __ptr64,unsigned short const * __ptr64) __ptr64` | 584 | Exported Function
`private: long __cdecl CRegistry::myRegOpenKeyEx(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,struct HKEY__ * __ptr64 * __ptr64) __ptr64` | 587 | Exported Function
`private: long __cdecl CRegistry::myRegEnumValue(struct HKEY__ * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 586 | Exported Function
`private: long __cdecl Provider::CreateInstanceEnum(class MethodContext * __ptr64,long) __ptr64` | 209 | Exported Function
`private: static class CAutoEvent CWinMsgEvent::mg_aeCreateWindow` | 575 | Exported Function
`private: static __int64 __cdecl CWinMsgEvent::MsgWndProc(struct HWND__ * __ptr64,unsigned int,unsigned __int64,__int64)` | 445 | Exported Function
`private: static class CCritSec CWbemProviderGlue::m_csStatusObject` | 573 | Exported Function
`private: static class CCritSec CWbemProviderGlue::m_csFlushPtrs` | 572 | Exported Function
`private: long __cdecl Provider::PutInstance(struct IWbemClassObject * __ptr64,long,class MethodContext * __ptr64) __ptr64` | 463 | Exported Function
`private: long __cdecl Provider::ExecMethod(struct ParsedObjectPath * __ptr64,unsigned short * __ptr64,long,class CInstance * __ptr64,class CInstance * __ptr64,class MethodContext * __ptr64) __ptr64` | 240 | Exported Function
`private: long __cdecl Provider::DeleteInstance(struct ParsedObjectPath * __ptr64,long,class MethodContext * __ptr64) __ptr64` | 224 | Exported Function
`private: long __cdecl Provider::GetObject(struct ParsedObjectPath * __ptr64,class MethodContext * __ptr64,long) __ptr64` | 351 | Exported Function
`private: long __cdecl Provider::ExecuteQuery(class MethodContext * __ptr64,class CFrameworkQuery & __ptr64,long) __ptr64` | 248 | Exported Function
`protected: virtual void __cdecl Provider::Flush(void) __ptr64` | 254 | Exported Function
`public: bool __cdecl CInstance::SetByte(unsigned short const * __ptr64,unsigned char) __ptr64` | 496 | Exported Function
`public: bool __cdecl CInstance::Setbool(unsigned short const * __ptr64,bool) __ptr64` | 535 | Exported Function
`public: bool __cdecl CInstance::SetCharSplat(unsigned short const * __ptr64,unsigned long) __ptr64` | 502 | Exported Function
`public: bool __cdecl CInstance::SetCharSplat(unsigned short const * __ptr64,char const * __ptr64) __ptr64` | 503 | Exported Function
`public: bool __cdecl CInstance::IsNull(unsigned short const * __ptr64)const __ptr64` | 419 | Exported Function
`public: bool __cdecl CInstance::GetWBEMINT64(unsigned short const * __ptr64,unsigned __int64 & __ptr64)const __ptr64` | 386 | Exported Function
`public: bool __cdecl CInstance::GetWBEMINT64(unsigned short const * __ptr64,class CHString & __ptr64)const __ptr64` | 384 | Exported Function
`public: bool __cdecl CInstance::GetWORD(unsigned short const * __ptr64,unsigned short & __ptr64)const __ptr64` | 388 | Exported Function
`public: bool __cdecl CInstance::GetWCHAR(unsigned short const * __ptr64,unsigned short * __ptr64 * __ptr64)const __ptr64` | 387 | Exported Function
`public: bool __cdecl CInstance::SetCharSplat(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 501 | Exported Function
`public: bool __cdecl CInstance::SetEmbeddedObject(unsigned short const * __ptr64,class CInstance & __ptr64) __ptr64` | 518 | Exported Function
`public: bool __cdecl CInstance::SetDWORD(unsigned short const * __ptr64,unsigned long) __ptr64` | 515 | Exported Function
`public: bool __cdecl CInstance::SetStringArray(unsigned short const * __ptr64,struct tagSAFEARRAY const & __ptr64) __ptr64` | 526 | Exported Function
`public: bool __cdecl CInstance::SetNull(unsigned short const * __ptr64) __ptr64` | 520 | Exported Function
`public: bool __cdecl CInstance::SetDOUBLE(unsigned short const * __ptr64,double) __ptr64` | 514 | Exported Function
`public: bool __cdecl CInstance::SetCHString(unsigned short const * __ptr64,class CHString const & __ptr64) __ptr64` | 498 | Exported Function
`public: bool __cdecl CInstance::SetCHString(unsigned short const * __ptr64,char const * __ptr64) __ptr64` | 499 | Exported Function
`public: bool __cdecl CInstance::SetDateTime(unsigned short const * __ptr64,class WBEMTime const & __ptr64) __ptr64` | 516 | Exported Function
`public: bool __cdecl CInstance::SetCHString(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 497 | Exported Function
`public: bool __cdecl CInstance::Getbool(unsigned short const * __ptr64,bool & __ptr64)const __ptr64` | 389 | Exported Function
`public: bool __cdecl CFrameworkQuery::KeysOnly(void) __ptr64` | 426 | Exported Function
`public: bool __cdecl CInstance::GetCHString(unsigned short const * __ptr64,class CHString & __ptr64)const __ptr64` | 285 | Exported Function
`public: bool __cdecl CInstance::GetByte(unsigned short const * __ptr64,unsigned char & __ptr64)const __ptr64` | 284 | Exported Function
`public: bool __cdecl CFrameworkQuery::IsPropertyRequired(unsigned short const * __ptr64) __ptr64` | 423 | Exported Function
`public: __cdecl WBEMTimeSpan::WBEMTimeSpan(unsigned short * __ptr64 const) __ptr64` | 51 | Exported Function
`public: __cdecl WBEMTimeSpan::WBEMTimeSpan(struct _FILETIME const & __ptr64) __ptr64` | 48 | Exported Function
`public: bool __cdecl CFrameworkQuery::AllPropertiesAreRequired(void) __ptr64` | 173 | Exported Function
`public: __cdecl WBEMTimeSpan::WBEMTimeSpan(void) __ptr64` | 52 | Exported Function
`public: bool __cdecl CInstance::GetDateTime(unsigned short const * __ptr64,class WBEMTime & __ptr64)const __ptr64` | 317 | Exported Function
`public: bool __cdecl CInstance::GetVariant(unsigned short const * __ptr64,struct tagVARIANT & __ptr64)const __ptr64` | 382 | Exported Function
`public: bool __cdecl CInstance::GetTimeSpan(unsigned short const * __ptr64,class WBEMTimeSpan & __ptr64)const __ptr64` | 374 | Exported Function
`public: bool __cdecl CInstance::GetWBEMINT64(unsigned short const * __ptr64,__int64 & __ptr64)const __ptr64` | 385 | Exported Function
`public: bool __cdecl CInstance::GetWBEMINT16(unsigned short const * __ptr64,short & __ptr64)const __ptr64` | 383 | Exported Function
`public: bool __cdecl CInstance::GetStringArray(unsigned short const * __ptr64,struct tagSAFEARRAY * __ptr64 & __ptr64)const __ptr64` | 370 | Exported Function
`public: bool __cdecl CInstance::GetDWORD(unsigned short const * __ptr64,unsigned long & __ptr64)const __ptr64` | 311 | Exported Function
`public: bool __cdecl CInstance::GetDOUBLE(unsigned short const * __ptr64,double & __ptr64)const __ptr64` | 310 | Exported Function
`public: bool __cdecl CInstance::GetStatus(unsigned short const * __ptr64,bool & __ptr64,unsigned short & __ptr64)const __ptr64` | 367 | Exported Function
`public: bool __cdecl CInstance::GetEmbeddedObject(unsigned short const * __ptr64,class CInstance * __ptr64 * __ptr64,class MethodContext * __ptr64)const __ptr64` | 318 | Exported Function
`public: class CHString __cdecl CHStringArray::operator[](int)const __ptr64` | 119 | Exported Function
`public: class CHString __cdecl CHStringArray::GetAt(int)const __ptr64` | 279 | Exported Function
`public: class CHString const & __ptr64 __cdecl CHString::operator+=(char) __ptr64` | 140 | Exported Function
`public: class CHString const & __ptr64 __cdecl CFrameworkQuery::GetQuery(void) __ptr64` | 360 | Exported Function
`public: class CHString __cdecl CHString::SpanIncluding(unsigned short const * __ptr64)const __ptr64` | 538 | Exported Function
`public: class CHString __cdecl CHString::Mid(int,int)const __ptr64` | 444 | Exported Function
`public: class CHString __cdecl CHString::Mid(int)const __ptr64` | 443 | Exported Function
`public: class CHString __cdecl CHString::SpanExcluding(unsigned short const * __ptr64)const __ptr64` | 537 | Exported Function
`public: class CHString __cdecl CHString::Right(int)const __ptr64` | 487 | Exported Function
`public: class CHString const & __ptr64 __cdecl CHString::operator+=(class CHString const & __ptr64) __ptr64` | 139 | Exported Function
`public: class CHString const & __ptr64 __cdecl CHString::operator=(unsigned char const * __ptr64) __ptr64` | 82 | Exported Function
`public: class CHString const & __ptr64 __cdecl CHString::operator=(class CHString const & __ptr64) __ptr64` | 77 | Exported Function
`public: class CHString const & __ptr64 __cdecl CHString::operator=(unsigned short) __ptr64` | 79 | Exported Function
`public: class CHString const & __ptr64 __cdecl CHString::operator=(unsigned short const * __ptr64) __ptr64` | 83 | Exported Function
`public: class CHString const & __ptr64 __cdecl CHString::operator=(class CHString * __ptr64) __ptr64` | 80 | Exported Function
`public: class CHString const & __ptr64 __cdecl CHString::operator+=(unsigned short) __ptr64` | 141 | Exported Function
`public: class CHString const & __ptr64 __cdecl CHString::operator+=(unsigned short const * __ptr64) __ptr64` | 142 | Exported Function
`public: class CHString const & __ptr64 __cdecl CHString::operator=(char) __ptr64` | 78 | Exported Function
`public: class CHString const & __ptr64 __cdecl CHString::operator=(char const * __ptr64) __ptr64` | 81 | Exported Function
`public: bool __cdecl CInstance::SetWCHARSplat(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 533 | Exported Function
`public: bool __cdecl CInstance::SetWBEMINT64(unsigned short const * __ptr64,unsigned __int64) __ptr64` | 532 | Exported Function
`public: bool __cdecl MethodContext::SetStatusObject(struct IWbemClassObject * __ptr64) __ptr64` | 525 | Exported Function
`public: bool __cdecl CInstance::SetWORD(unsigned short const * __ptr64,unsigned short) __ptr64` | 534 | Exported Function
`public: bool __cdecl CInstance::SetWBEMINT64(unsigned short const * __ptr64,class CHString const & __ptr64) __ptr64` | 530 | Exported Function
`public: bool __cdecl CInstance::SetVariant(unsigned short const * __ptr64,struct tagVARIANT const & __ptr64) __ptr64` | 528 | Exported Function
`public: bool __cdecl CInstance::SetTimeSpan(unsigned short const * __ptr64,class WBEMTimeSpan const & __ptr64) __ptr64` | 527 | Exported Function
`public: bool __cdecl CInstance::SetWBEMINT64(unsigned short const * __ptr64,__int64) __ptr64` | 531 | Exported Function
`public: bool __cdecl CInstance::SetWBEMINT16(unsigned short const * __ptr64,short const & __ptr64) __ptr64` | 529 | Exported Function
`public: bool __cdecl WBEMTime::IsOk(void)const __ptr64` | 421 | Exported Function
`public: class CHString & __ptr64 __cdecl CHStringArray::operator[](int) __ptr64` | 118 | Exported Function
`public: class CHString & __ptr64 __cdecl CHStringArray::ElementAt(int) __ptr64` | 232 | Exported Function
`public: class CHString __cdecl CHString::Left(int)const __ptr64` | 427 | Exported Function
`public: class CHString * __ptr64 __cdecl CHStringArray::GetData(void) __ptr64` | 315 | Exported Function
`public: class CHPtrArray & __ptr64 __cdecl CHPtrArray::operator=(class CHPtrArray const & __ptr64) __ptr64` | 76 | Exported Function
`public: class CAutoEvent & __ptr64 __cdecl CAutoEvent::operator=(class CAutoEvent const & __ptr64) __ptr64` | 73 | Exported Function
`public: bool __cdecl WBEMTimeSpan::IsOk(void)const __ptr64` | 422 | Exported Function
`public: class CFrameworkQueryEx & __ptr64 __cdecl CFrameworkQueryEx::operator=(class CFrameworkQueryEx const & __ptr64) __ptr64` | 75 | Exported Function
`public: class CFrameworkQuery & __ptr64 __cdecl CFrameworkQuery::operator=(class CFrameworkQuery const & __ptr64) __ptr64` | 74 | Exported Function
`public: __cdecl CHString::CHString(unsigned short const * __ptr64,int) __ptr64` | 12 | Exported Function
`public: __cdecl CHString::CHString(unsigned short const * __ptr64) __ptr64` | 11 | Exported Function
`public: __cdecl CHString::CHString(void) __ptr64` | 13 | Exported Function
`public: __cdecl CHString::CHString(unsigned short,int) __ptr64` | 8 | Exported Function
`public: __cdecl CHString::CHString(unsigned char const * __ptr64) __ptr64` | 10 | Exported Function
`public: __cdecl CHPtrArray::~CHPtrArray(void) __ptr64` | 56 | Exported Function
`public: __cdecl CHPtrArray::CHPtrArray(void) __ptr64` | 6 | Exported Function
`public: __cdecl CHString::CHString(class CHString const & __ptr64) __ptr64` | 7 | Exported Function
`public: __cdecl CHString::CHString(char const * __ptr64) __ptr64` | 9 | Exported Function
`public: __cdecl CHString::operator unsigned short const * __ptr64(void)const __ptr64` | 120 | Exported Function
`public: __cdecl CObjectPathParser::~CObjectPathParser(void) __ptr64` | 60 | Exported Function
`public: __cdecl CObjectPathParser::CObjectPathParser(enum ObjectParserFlags) __ptr64` | 17 | Exported Function
`public: __cdecl CreateMutexAsProcess::~CreateMutexAsProcess(void) __ptr64` | 67 | Exported Function
`public: __cdecl CreateMutexAsProcess::CreateMutexAsProcess(unsigned short const * __ptr64) __ptr64` | 32 | Exported Function
`public: __cdecl CInstance::CInstance(struct IWbemClassObject * __ptr64,class MethodContext * __ptr64) __ptr64` | 16 | Exported Function
`public: __cdecl CHStringArray::CHStringArray(void) __ptr64` | 14 | Exported Function
`public: __cdecl CHString::~CHString(void) __ptr64` | 57 | Exported Function
`public: __cdecl CInstance::CInstance(class CInstance const & __ptr64) __ptr64` | 15 | Exported Function
`public: __cdecl CHStringArray::~CHStringArray(void) __ptr64` | 58 | Exported Function
`protected: void __cdecl CHString::CopyBeforeWrite(void) __ptr64` | 202 | Exported Function
`protected: void __cdecl CHString::ConcatInPlace(int,unsigned short const * __ptr64) __ptr64` | 199 | Exported Function
`protected: void __cdecl CInstance::LogError(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,long)const __ptr64` | 438 | Exported Function
`protected: void __cdecl CHString::Init(void) __ptr64` | 399 | Exported Function
`protected: void __cdecl CHString::ConcatCopy(int,unsigned short const * __ptr64,int,unsigned short const * __ptr64) __ptr64` | 198 | Exported Function
`protected: void __cdecl CHString::AllocBuffer(int) __ptr64` | 175 | Exported Function
`protected: void __cdecl CHString::AllocBeforeWrite(int) __ptr64` | 174 | Exported Function
`protected: void __cdecl CHString::AssignCopy(int,unsigned short const * __ptr64) __ptr64` | 180 | Exported Function
`protected: void __cdecl CHString::AllocCopy(class CHString & __ptr64,int,int,int)const __ptr64` | 176 | Exported Function
`protected: void __cdecl CWinMsgEvent::RegisterForMessage(unsigned int,int) __ptr64` | 470 | Exported Function
`public: __cdecl CFrameworkQueryEx::CFrameworkQueryEx(class CFrameworkQueryEx const & __ptr64) __ptr64` | 4 | Exported Function
`public: __cdecl CFrameworkQuery::~CFrameworkQuery(void) __ptr64` | 54 | Exported Function
`public: __cdecl CFrameworkQueryEx::~CFrameworkQueryEx(void) __ptr64` | 55 | Exported Function
`public: __cdecl CFrameworkQueryEx::CFrameworkQueryEx(void) __ptr64` | 5 | Exported Function
`public: __cdecl CFrameworkQuery::CFrameworkQuery(void) __ptr64` | 3 | Exported Function
`public: __cdecl CAutoEvent::CAutoEvent(void) __ptr64` | 1 | Exported Function
`protected: void __cdecl CWinMsgEvent::UnRegisterAllMessages(void) __ptr64` | 542 | Exported Function
`public: __cdecl CFrameworkQuery::CFrameworkQuery(class CFrameworkQuery const & __ptr64) __ptr64` | 2 | Exported Function
`public: __cdecl CAutoEvent::~CAutoEvent(void) __ptr64` | 53 | Exported Function
`public: __cdecl ParsedObjectPath::~ParsedObjectPath(void) __ptr64` | 70 | Exported Function
`public: __cdecl ParsedObjectPath::ParsedObjectPath(void) __ptr64` | 37 | Exported Function
`public: __cdecl Provider::Provider(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 39 | Exported Function
`public: __cdecl Provider::Provider(class Provider const & __ptr64) __ptr64` | 38 | Exported Function
`public: __cdecl MethodContext::MethodContext(struct IWbemContext * __ptr64,class CWbemProviderGlue * __ptr64) __ptr64` | 36 | Exported Function
`public: __cdecl KeyRef::KeyRef(void) __ptr64` | 34 | Exported Function
`public: __cdecl KeyRef::KeyRef(unsigned short const * __ptr64,struct tagVARIANT const * __ptr64) __ptr64` | 33 | Exported Function
`public: __cdecl MethodContext::MethodContext(class MethodContext const & __ptr64) __ptr64` | 35 | Exported Function
`public: __cdecl KeyRef::~KeyRef(void) __ptr64` | 68 | Exported Function
`public: __cdecl ProviderLog::ProviderLog(class ProviderLog const & __ptr64) __ptr64` | 40 | Exported Function
`public: __cdecl WBEMTime::WBEMTime(void) __ptr64` | 47 | Exported Function
`public: __cdecl WBEMTime::WBEMTime(unsigned short * __ptr64 const) __ptr64` | 46 | Exported Function
`public: __cdecl WBEMTimeSpan::WBEMTimeSpan(int,int,int,int,int,int,int) __ptr64` | 50 | Exported Function
`public: __cdecl WBEMTimeSpan::WBEMTimeSpan(__int64 const & __ptr64) __ptr64` | 49 | Exported Function
`public: __cdecl WBEMTime::WBEMTime(struct tm const & __ptr64) __ptr64` | 44 | Exported Function
`public: __cdecl WBEMTime::WBEMTime(__int64 const & __ptr64) __ptr64` | 45 | Exported Function
`public: __cdecl ProviderLog::ProviderLog(void) __ptr64` | 41 | Exported Function
`public: __cdecl WBEMTime::WBEMTime(struct _SYSTEMTIME const & __ptr64) __ptr64` | 43 | Exported Function
`public: __cdecl WBEMTime::WBEMTime(struct _FILETIME const & __ptr64) __ptr64` | 42 | Exported Function
`public: __cdecl CThreadBase::CThreadBase(class CThreadBase const & __ptr64) __ptr64` | 22 | Exported Function
`public: __cdecl CRegistrySearch::~CRegistrySearch(void) __ptr64` | 62 | Exported Function
`public: __cdecl CWbemGlueFactory::CWbemGlueFactory(class CWbemGlueFactory const & __ptr64) __ptr64` | 24 | Exported Function
`public: __cdecl CThreadBase::CThreadBase(enum CThreadBase::THREAD_SAFETY_MECHANISM) __ptr64` | 23 | Exported Function
`public: __cdecl CRegistrySearch::CRegistrySearch(void) __ptr64` | 21 | Exported Function
`public: __cdecl CRegistry::CRegistry(void) __ptr64` | 19 | Exported Function
`public: __cdecl CRegistry::CRegistry(class CRegistry const & __ptr64) __ptr64` | 18 | Exported Function
`public: __cdecl CRegistrySearch::CRegistrySearch(class CRegistrySearch const & __ptr64) __ptr64` | 20 | Exported Function
`public: __cdecl CRegistry::~CRegistry(void) __ptr64` | 61 | Exported Function
`public: __cdecl CWbemGlueFactory::CWbemGlueFactory(long * __ptr64) __ptr64` | 25 | Exported Function
`public: __cdecl CWinMsgEvent::CWinMsgEvent(class CWinMsgEvent const & __ptr64) __ptr64` | 30 | Exported Function
`public: __cdecl CWbemProviderGlue::~CWbemProviderGlue(void) __ptr64` | 65 | Exported Function
`public: __cdecl CWinMsgEvent::~CWinMsgEvent(void) __ptr64` | 66 | Exported Function
`public: __cdecl CWinMsgEvent::CWinMsgEvent(void) __ptr64` | 31 | Exported Function
`public: __cdecl CWbemProviderGlue::CWbemProviderGlue(void) __ptr64` | 29 | Exported Function
`public: __cdecl CWbemGlueFactory::~CWbemGlueFactory(void) __ptr64` | 64 | Exported Function
`public: __cdecl CWbemGlueFactory::CWbemGlueFactory(void) __ptr64` | 26 | Exported Function
`public: __cdecl CWbemProviderGlue::CWbemProviderGlue(long * __ptr64) __ptr64` | 28 | Exported Function
`public: __cdecl CWbemProviderGlue::CWbemProviderGlue(class CWbemProviderGlue const & __ptr64) __ptr64` | 27 | Exported Function


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


