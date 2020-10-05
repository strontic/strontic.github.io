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

Function Name | Ordinal | Type
-- | -- | --
`public: long __thiscall CInstance::Release(void)` | 473 | Exported Function
`public: long __thiscall CInstance::Commit(void)` | 194 | Exported Function
`public: long __thiscall CRegistry::DeleteKey(class CHString *)` | 227 | Exported Function
`public: long __thiscall CRegistry::CreateOpen(struct HKEY__ *,unsigned short const *,unsigned short *,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES *,unsigned long *)` | 214 | Exported Function
`public: long __thiscall CInstance::AddRef(void)` | 167 | Exported Function
`public: long __thiscall CFrameworkQuery::Init(unsigned short * const,unsigned short * const,long,class CHString &)` | 398 | Exported Function
`public: long __thiscall CFrameworkQuery::Init(struct ParsedObjectPath *,struct IWbemContext *,unsigned short const *,class CHString &)` | 397 | Exported Function
`public: long __thiscall CFrameworkQueryEx::GetValuesForProp(unsigned short const *,class std::vector<int,class std::allocator<int> > &)` | 380 | Exported Function
`public: long __thiscall CFrameworkQueryEx::GetValuesForProp(unsigned short const *,class std::vector<class _variant_t,class std::allocator<class _variant_t> > &)` | 381 | Exported Function
`public: long __thiscall CRegistry::DeleteValue(unsigned short const *)` | 228 | Exported Function
`public: long __thiscall MethodContext::AddRef(void)` | 171 | Exported Function
`public: long __thiscall CThreadBase::Release(void)` | 474 | Exported Function
`public: static bool __stdcall CWbemProviderGlue::IsDerivedFrom(unsigned short const *,unsigned short const *,class MethodContext *,unsigned short const *)` | 411 | Exported Function
`public: long __thiscall MethodContext::Release(void)` | 477 | Exported Function
`public: long __thiscall CThreadBase::AddRef(void)` | 168 | Exported Function
`public: long __thiscall CRegistry::Open(struct HKEY__ *,unsigned short const *,unsigned long)` | 451 | Exported Function
`public: long __thiscall CRegistry::EnumerateAndGetValues(unsigned long &,unsigned short * &,unsigned char * &)` | 237 | Exported Function
`public: long __thiscall CRegistry::OpenLocalMachineKeyAndReadValue(unsigned short const *,unsigned short const *,class CHString &)` | 454 | Exported Function
`public: long __thiscall CRegistry::OpenAndEnumerateSubKeys(struct HKEY__ *,unsigned short const *,unsigned long)` | 452 | Exported Function
`public: int __thiscall WBEMTime::operator>(class WBEMTime const &)const ` | 135 | Exported Function
`public: int __thiscall WBEMTime::operator==(class WBEMTime const &)const ` | 111 | Exported Function
`public: int __thiscall WBEMTime::SetDMTF(unsigned short * const)` | 513 | Exported Function
`public: int __thiscall WBEMTime::operator>=(class WBEMTime const &)const ` | 137 | Exported Function
`public: int __thiscall WBEMTime::operator<=(class WBEMTime const &)const ` | 133 | Exported Function
`public: int __thiscall WBEMTime::Gettime_t(long *)const ` | 391 | Exported Function
`public: int __thiscall WBEMTime::GetSYSTEMTIME(struct _SYSTEMTIME *)const ` | 364 | Exported Function
`public: int __thiscall WBEMTime::operator<(class WBEMTime const &)const ` | 131 | Exported Function
`public: int __thiscall WBEMTime::operator!=(class WBEMTime const &)const ` | 113 | Exported Function
`public: int __thiscall WBEMTimeSpan::GetFILETIME(struct _FILETIME *)const ` | 322 | Exported Function
`public: int __thiscall WBEMTimeSpan::operator>=(class WBEMTimeSpan const &)const ` | 138 | Exported Function
`public: int __thiscall WBEMTimeSpan::operator>(class WBEMTimeSpan const &)const ` | 136 | Exported Function
`public: long __thiscall CFrameworkQuery::GetValuesForProp(unsigned short const *,class std::vector<class _bstr_t,class std::allocator<class _bstr_t> > &)` | 378 | Exported Function
`public: long __thiscall CFrameworkQuery::GetValuesForProp(unsigned short const *,class CHStringArray &)` | 379 | Exported Function
`public: int __thiscall WBEMTimeSpan::operator==(class WBEMTimeSpan const &)const ` | 112 | Exported Function
`public: int __thiscall WBEMTimeSpan::operator!=(class WBEMTimeSpan const &)const ` | 114 | Exported Function
`public: int __thiscall WBEMTimeSpan::Gettime_t(long *)const ` | 392 | Exported Function
`public: int __thiscall WBEMTimeSpan::operator<=(class WBEMTimeSpan const &)const ` | 134 | Exported Function
`public: int __thiscall WBEMTimeSpan::operator<(class WBEMTimeSpan const &)const ` | 132 | Exported Function
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(struct _SYSTEMTIME const *)` | 336 | Exported Function
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(struct _FILETIME const *)` | 335 | Exported Function
`public: static struct IWbemServices * __stdcall CWbemProviderGlue::GetNamespaceConnection(unsigned short const *)` | 346 | Exported Function
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(struct tm const *)` | 337 | Exported Function
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(long const &)` | 334 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetInstancePropertiesByPath(unsigned short const *,class CInstance * *,class MethodContext *,class CHStringArray &)` | 327 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetInstanceKeysByPath(unsigned short const *,class CInstance * *,class MethodContext *)` | 326 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetInstancesByQueryAsynch(unsigned short const *,class Provider *,long (__stdcall*)(class Provider *,class CInstance *,class MethodContext *,void *),unsigned short const *,class MethodContext *,void *)` | 329 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetInstancesByQuery(unsigned short const *,class TRefPointerCollection<class CInstance> *,class MethodContext *,unsigned short const *)` | 328 | Exported Function
`public: static struct IWbemServices * __stdcall CWbemProviderGlue::GetNamespaceConnection(unsigned short const *,class MethodContext *)` | 347 | Exported Function
`public: static void __stdcall CWbemProviderGlue::FrameworkLogoff(unsigned short const *,unsigned short const *)` | 264 | Exported Function
`public: static void __stdcall CWbemProviderGlue::FrameworkLogin(unsigned short const *,class Provider *,unsigned short const *)` | 261 | Exported Function
`public: struct HKEY__ * __thiscall CRegistry::GethKey(void)` | 390 | Exported Function
`public: static void __stdcall CWbemProviderGlue::IncrementObjectCount(void)` | 395 | Exported Function
`public: static void __stdcall CHString::Release(struct CHStringData *)` | 472 | Exported Function
`public: static unsigned long __stdcall CWbemProviderGlue::GetPlatform(void)` | 356 | Exported Function
`public: static unsigned long __stdcall CWbemProviderGlue::GetOSMajorVersion(void)` | 349 | Exported Function
`public: static unsigned short const * __stdcall CWbemProviderGlue::GetCSDVersion(void)` | 286 | Exported Function
`public: static unsigned short * __stdcall CObjectPathParser::GetRelativePath(unsigned short *)` | 362 | Exported Function
`public: static int __stdcall CWbemProviderGlue::FrameworkLogoffDLL(unsigned short const *)` | 265 | Exported Function
`public: static int __stdcall CWbemProviderGlue::FrameworkLoginDLL(unsigned short const *,long *)` | 263 | Exported Function
`public: static int __stdcall Provider::initFailed(void)` | 565 | Exported Function
`public: static int __stdcall CWbemProviderGlue::FrameworkLogoffDLL(unsigned short const *,long *)` | 266 | Exported Function
`public: static int __stdcall CWbemProviderGlue::FrameworkLoginDLL(unsigned short const *)` | 262 | Exported Function
`public: static class CWbemGlueFactory * __stdcall CWbemGlueFactory::Create(long *)` | 203 | Exported Function
`public: static bool __stdcall CWbemProviderGlue::SetStatusObject(class MethodContext *,unsigned short const *,unsigned short const *,long,struct tagSAFEARRAY const *,struct tagSAFEARRAY const *)` | 524 | Exported Function
`public: static int __stdcall CObjectPathParser::Unparse(struct ParsedObjectPath *,unsigned short * *)` | 548 | Exported Function
`public: static class CWbemGlueFactory * __stdcall CWbemGlueFactory::Create(void)` | 204 | Exported Function
`public: static long __stdcall CWbemProviderGlue::DecrementObjectCount(void)` | 218 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetEmptyInstance(class MethodContext *,unsigned short const *,class CInstance * *,unsigned short const *)` | 319 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetAllInstancesAsynch(unsigned short const *,class Provider *,long (__stdcall*)(class Provider *,class CInstance *,class MethodContext *,void *),unsigned short const *,class MethodContext *,void *)` | 275 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetInstanceByPath(unsigned short const *,class CInstance * *,class MethodContext *)` | 324 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetEmptyInstance(unsigned short const *,class CInstance * *,unsigned short const *)` | 320 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetAllInstances(unsigned short const *,class TRefPointerCollection<class CInstance> *,unsigned short const *,class MethodContext *)` | 274 | Exported Function
`public: static long __stdcall CWbemProviderGlue::FillInstance(class MethodContext *,class CInstance *)` | 250 | Exported Function
`public: static long __stdcall CWbemProviderGlue::FillInstance(class CInstance *,unsigned short const *)` | 249 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetAllDerivedInstancesAsynch(unsigned short const *,class Provider *,long (__stdcall*)(class Provider *,class CInstance *,class MethodContext *,void *),unsigned short const *,class MethodContext *,void *)` | 273 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetAllDerivedInstances(unsigned short const *,class TRefPointerCollection<class CInstance> *,class MethodContext *,unsigned short const *)` | 272 | Exported Function
`public: class WBEMTimeSpan & __thiscall WBEMTimeSpan::operator=(class WBEMTimeSpan &&)` | 106 | Exported Function
`public: class WBEMTime const & __thiscall WBEMTime::operator=(unsigned short * const)` | 105 | Exported Function
`public: class WBEMTimeSpan __thiscall WBEMTime::operator-(class WBEMTime const &)` | 121 | Exported Function
`public: class WBEMTimeSpan & __thiscall WBEMTimeSpan::operator=(class WBEMTimeSpan const &)` | 107 | Exported Function
`public: class WBEMTime const & __thiscall WBEMTime::operator=(struct tm const &)` | 104 | Exported Function
`public: class WBEMTime const & __thiscall WBEMTime::operator=(long const &)` | 101 | Exported Function
`public: class WBEMTime const & __thiscall WBEMTime::operator-=(class WBEMTimeSpan const &)` | 145 | Exported Function
`public: class WBEMTime const & __thiscall WBEMTime::operator=(struct _SYSTEMTIME const &)` | 103 | Exported Function
`public: class WBEMTime const & __thiscall WBEMTime::operator=(struct _FILETIME const &)` | 102 | Exported Function
`public: class WBEMTimeSpan __thiscall WBEMTimeSpan::operator+(class WBEMTimeSpan const &)const ` | 130 | Exported Function
`public: enum ProviderLog::LogLevel __thiscall ProviderLog::IsLoggingOn(class CHString *)` | 417 | Exported Function
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator=(unsigned short * const)` | 110 | Exported Function
`public: int __thiscall CFrameworkQueryEx::Is3TokenOR(unsigned short const *,unsigned short const *,struct tagVARIANT &,struct tagVARIANT &)` | 409 | Exported Function
`public: int __thiscall CAutoEvent::Signal(void)` | 536 | Exported Function
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator=(struct _FILETIME const &)` | 109 | Exported Function
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator+=(class WBEMTimeSpan const &)` | 144 | Exported Function
`public: class WBEMTimeSpan __thiscall WBEMTimeSpan::operator-(class WBEMTimeSpan const &)const ` | 123 | Exported Function
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator=(long const &)` | 108 | Exported Function
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator-=(class WBEMTimeSpan const &)` | 146 | Exported Function
`public: class CThreadBase & __thiscall CThreadBase::operator=(class CThreadBase const &)` | 89 | Exported Function
`public: class CRegistrySearch & __thiscall CRegistrySearch::operator=(class CRegistrySearch const &)` | 88 | Exported Function
`public: class CWbemProviderGlue & __thiscall CWbemProviderGlue::operator=(class CWbemProviderGlue const &)` | 91 | Exported Function
`public: class CWbemGlueFactory & __thiscall CWbemGlueFactory::operator=(class CWbemGlueFactory const &)` | 90 | Exported Function
`public: class CRegistry & __thiscall CRegistry::operator=(class CRegistry const &)` | 87 | Exported Function
`public: class CInstance & __thiscall CInstance::operator=(class CInstance const &)` | 85 | Exported Function
`public: class CHStringArray & __thiscall CHStringArray::operator=(class CHStringArray const &)` | 84 | Exported Function
`public: class CreateMutexAsProcess & __thiscall CreateMutexAsProcess::operator=(class CreateMutexAsProcess const &)` | 93 | Exported Function
`public: class CObjectPathParser & __thiscall CObjectPathParser::operator=(class CObjectPathParser const &)` | 86 | Exported Function
`public: class CWinMsgEvent & __thiscall CWinMsgEvent::operator=(class CWinMsgEvent const &)` | 92 | Exported Function
`public: class WBEMTime __thiscall WBEMTime::operator+(class WBEMTimeSpan const &)const ` | 129 | Exported Function
`public: class WBEMTime & __thiscall WBEMTime::operator=(class WBEMTime const &)` | 100 | Exported Function
`public: class WBEMTime const & __thiscall WBEMTime::operator+=(class WBEMTimeSpan const &)` | 143 | Exported Function
`public: class WBEMTime __thiscall WBEMTime::operator-(class WBEMTimeSpan const &)const ` | 122 | Exported Function
`public: class WBEMTime & __thiscall WBEMTime::operator=(class WBEMTime &&)` | 99 | Exported Function
`public: class MethodContext * __thiscall CInstance::GetMethodContext(void)const ` | 343 | Exported Function
`public: class MethodContext & __thiscall MethodContext::operator=(class MethodContext const &)` | 95 | Exported Function
`public: class ProviderLog & __thiscall ProviderLog::operator=(class ProviderLog const &)` | 98 | Exported Function
`public: class Provider & __thiscall Provider::operator=(class Provider const &)` | 97 | Exported Function
`public: int __thiscall CThreadBase::BeginWrite(unsigned long)` | 182 | Exported Function
`public: int __thiscall CThreadBase::BeginRead(unsigned long)` | 181 | Exported Function
`public: int __thiscall ParsedObjectPath::AddKeyRef(unsigned short const *,struct tagVARIANT const *)` | 163 | Exported Function
`public: int __thiscall ParsedObjectPath::AddKeyRef(struct KeyRef *)` | 162 | Exported Function
`public: int __thiscall CRegistrySearch::SearchAndBuildList(class CHString,class CHPtrArray &,class CHString,class CHString,int,struct HKEY__ *)` | 489 | Exported Function
`public: int __thiscall CObjectPathParser::Parse(unsigned short const *,struct ParsedObjectPath * *)` | 457 | Exported Function
`public: int __thiscall CHStringArray::GetUpperBound(void)const ` | 376 | Exported Function
`public: int __thiscall CRegistrySearch::LocateKeyByNameOrValueName(struct HKEY__ *,unsigned short const *,unsigned short const *,unsigned short const * *,unsigned long,class CHString &,class CHString &)` | 432 | Exported Function
`public: int __thiscall CRegistrySearch::FreeSearchList(int,class CHPtrArray &)` | 271 | Exported Function
`public: int __thiscall ParsedObjectPath::AddKeyRefEx(unsigned short const *,struct tagVARIANT const *)` | 164 | Exported Function
`public: int __thiscall ParsedObjectPath::SetClassName(unsigned short const *)` | 504 | Exported Function
`public: int __thiscall ParsedObjectPath::IsRelative(unsigned short const *,unsigned short const *)` | 425 | Exported Function
`public: int __thiscall WBEMTime::GetStructtm(struct tm *)const ` | 371 | Exported Function
`public: int __thiscall WBEMTime::GetFILETIME(struct _FILETIME *)const ` | 321 | Exported Function
`public: int __thiscall ParsedObjectPath::IsObject(void)` | 420 | Exported Function
`public: int __thiscall ParsedObjectPath::IsClass(void)` | 410 | Exported Function
`public: int __thiscall ParsedObjectPath::AddNamespace(unsigned short const *)` | 165 | Exported Function
`public: int __thiscall ParsedObjectPath::IsLocal(unsigned short const *)` | 416 | Exported Function
`public: int __thiscall ParsedObjectPath::IsInstance(void)` | 415 | Exported Function
`public: int __thiscall CHString::Compare(unsigned short const *)const ` | 196 | Exported Function
`public: int __thiscall CHString::Collate(unsigned short const *)const ` | 193 | Exported Function
`public: int __thiscall CHString::Find(unsigned short const *)const ` | 252 | Exported Function
`public: int __thiscall CHString::CompareNoCase(unsigned short const *)const ` | 197 | Exported Function
`public: int __thiscall CHPtrArray::GetUpperBound(void)const ` | 375 | Exported Function
`public: int __thiscall CHPtrArray::Add(void *)` | 159 | Exported Function
`public: int __thiscall CFrameworkQueryEx::IsNTokenAnd(class CHStringArray &,class CHPtrArray &)` | 418 | Exported Function
`public: int __thiscall CHPtrArray::GetSize(void)const ` | 365 | Exported Function
`public: int __thiscall CHPtrArray::Append(class CHPtrArray const &)` | 178 | Exported Function
`public: int __thiscall CHString::Find(unsigned short)const ` | 251 | Exported Function
`public: int __thiscall CHStringArray::Add(unsigned short const *)` | 160 | Exported Function
`public: int __thiscall CHString::ReverseFind(unsigned short)const ` | 485 | Exported Function
`public: int __thiscall CHStringArray::GetSize(void)const ` | 366 | Exported Function
`public: int __thiscall CHStringArray::Append(class CHStringArray const &)` | 179 | Exported Function
`public: int __thiscall CHString::LoadStringW(unsigned int)` | 429 | Exported Function
`public: int __thiscall CHString::GetAllocLength(void)const ` | 276 | Exported Function
`public: int __thiscall CHString::FindOneOf(unsigned short const *)const ` | 253 | Exported Function
`public: int __thiscall CHString::IsEmpty(void)const ` | 412 | Exported Function
`public: int __thiscall CHString::GetLength(void)const ` | 331 | Exported Function
`public: struct IWbemClassObject * __thiscall CInstance::GetClassObjectInterface(void)` | 288 | Exported Function
`public: void __cdecl CHString::FormatMessageW(unsigned int,...)` | 258 | Exported Function
`public: void __cdecl CHString::Format(unsigned short const *,...)` | 257 | Exported Function
`public: void __cdecl ProviderLog::LocalLogMessage(unsigned short const *,int,enum ProviderLog::LogLevel,unsigned short const *,...)` | 430 | Exported Function
`public: void __cdecl CHString::FormatMessageW(unsigned short const *,...)` | 259 | Exported Function
`public: void __cdecl CHString::Format(unsigned int,...)` | 256 | Exported Function
`public: void * * __thiscall CHPtrArray::GetData(void)` | 312 | Exported Function
`public: void * & __thiscall CHPtrArray::operator[](int)` | 115 | Exported Function
`public: void * __thiscall CHPtrArray::operator[](int)const ` | 116 | Exported Function
`public: void * __thiscall CHPtrArray::GetAt(int)const ` | 277 | Exported Function
`public: void __thiscall CFrameworkQuery::GetRequiredProperties(class CHStringArray &)` | 363 | Exported Function
`public: void __thiscall CHPtrArray::RemoveAll(void)` | 479 | Exported Function
`public: void __thiscall CHPtrArray::InsertAt(int,void *,int)` | 405 | Exported Function
`public: void __thiscall CHPtrArray::SetAt(int,void *)` | 491 | Exported Function
`public: void __thiscall CHPtrArray::RemoveAt(int,int)` | 481 | Exported Function
`public: void __thiscall CHPtrArray::InsertAt(int,class CHPtrArray *)` | 404 | Exported Function
`public: void __thiscall CFrameworkQueryEx::GetPropertyBitMask(class CHPtrArray const &,void *)` | 357 | Exported Function
`public: void __thiscall CFrameworkQuery::Init2(struct IWbemClassObject *)` | 396 | Exported Function
`public: void __thiscall CHPtrArray::FreeExtra(void)` | 268 | Exported Function
`public: void __thiscall CHPtrArray::Copy(class CHPtrArray const &)` | 200 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::PutClassAsync(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemObjectSink *)` | 461 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::PutClass(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemCallResult * *)` | 460 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::PutInstanceAsync(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemObjectSink *)` | 465 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::PutInstance(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemCallResult * *)` | 462 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::OpenNamespace(unsigned short * const,long,struct IWbemContext *,struct IWbemServices * *,struct IWbemCallResult * *)` | 455 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::GetObject(unsigned short * const,long,struct IWbemContext *,struct IWbemClassObject * *,struct IWbemCallResult * *)` | 350 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::ExecQueryAsync(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 247 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::Initialize(unsigned short *,long,unsigned short *,unsigned short *,struct IWbemServices *,struct IWbemContext *,struct IWbemProviderInitSink *)` | 403 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::GetObjectAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 354 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::QueryInterface(struct _GUID const &,void * *)` | 467 | Exported Function
`public: virtual unsigned long __stdcall CWbemProviderGlue::Release(void)` | 476 | Exported Function
`public: virtual unsigned long __stdcall CWbemProviderGlue::AddRef(void)` | 170 | Exported Function
`public: void * & __thiscall CHPtrArray::ElementAt(int)` | 231 | Exported Function
`public: virtual void __thiscall MethodContext::QueryPostProcess(void)` | 469 | Exported Function
`public: virtual unsigned long __stdcall CWbemGlueFactory::Release(void)` | 475 | Exported Function
`public: virtual long __thiscall CFrameworkQueryEx::InitEx(unsigned short * const,unsigned short * const,long,class CHString &)` | 402 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::QueryObjectSink(long,struct IWbemObjectSink * *)` | 468 | Exported Function
`public: virtual unsigned long __stdcall CWbemGlueFactory::AddRef(void)` | 169 | Exported Function
`public: virtual struct IWbemContext * __thiscall MethodContext::GetIWBEMContext(void)` | 323 | Exported Function
`public: void __thiscall CRegistry::Close(void)` | 191 | Exported Function
`public: void __thiscall CObjectPathParser::Free(struct ParsedObjectPath *)` | 267 | Exported Function
`public: void __thiscall CThreadBase::``default constructor closure'(void)` | 158 | Exported Function
`public: void __thiscall CRegistry::RewindSubKeys(void)` | 486 | Exported Function
`public: void __thiscall CObjectPathParser::``default constructor closure'(void)` | 157 | Exported Function
`public: void __thiscall CHStringArray::SetAt(int,unsigned short const *)` | 493 | Exported Function
`public: void __thiscall CHStringArray::RemoveAt(int,int)` | 482 | Exported Function
`public: void __thiscall CHStringArray::SetSize(int,int)` | 523 | Exported Function
`public: void __thiscall CHStringArray::SetAtGrow(int,unsigned short const *)` | 495 | Exported Function
`public: void __thiscall CThreadBase::EndRead(void)` | 235 | Exported Function
`public: void const * * __thiscall CHPtrArray::GetData(void)const ` | 313 | Exported Function
`public: void __thiscall WBEMTimeSpan::Clear(void)` | 189 | Exported Function
`void __stdcall SetCHStringResourceHandle(struct HINSTANCE__ *)` | 500 | Exported Function
`unsigned long __stdcall NormalizePath(unsigned short const *,unsigned short const *,unsigned short const *,unsigned long,class CHString &)` | 448 | Exported Function
`public: void __thiscall WBEMTime::Clear(void)` | 188 | Exported Function
`public: void __thiscall CWbemGlueFactory::Destroy(void)` | 229 | Exported Function
`public: void __thiscall CThreadBase::EndWrite(void)` | 236 | Exported Function
`public: void __thiscall ProviderLog::LocalLogMessage(unsigned short const *,unsigned short const *,int,enum ProviderLog::LogLevel)` | 431 | Exported Function
`public: void __thiscall ParsedObjectPath::ClearKeys(void)` | 190 | Exported Function
`public: void __thiscall CHString::MakeReverse(void)` | 441 | Exported Function
`public: void __thiscall CHString::MakeLower(void)` | 440 | Exported Function
`public: void __thiscall CHString::Release(void)` | 471 | Exported Function
`public: void __thiscall CHString::MakeUpper(void)` | 442 | Exported Function
`public: void __thiscall CHString::FreeExtra(void)` | 269 | Exported Function
`public: void __thiscall CHPtrArray::SetSize(int,int)` | 522 | Exported Function
`public: void __thiscall CHPtrArray::SetAtGrow(int,void *)` | 494 | Exported Function
`public: void __thiscall CHString::FormatV(unsigned short const *,char *)` | 260 | Exported Function
`public: void __thiscall CHString::Empty(void)` | 233 | Exported Function
`public: void __thiscall CHString::ReleaseBuffer(int)` | 478 | Exported Function
`public: void __thiscall CHStringArray::InsertAt(int,class CHStringArray *)` | 406 | Exported Function
`public: void __thiscall CHStringArray::FreeExtra(void)` | 270 | Exported Function
`public: void __thiscall CHStringArray::RemoveAll(void)` | 480 | Exported Function
`public: void __thiscall CHStringArray::InsertAt(int,unsigned short const *,int)` | 407 | Exported Function
`public: void __thiscall CHStringArray::Copy(class CHStringArray const &)` | 201 | Exported Function
`public: void __thiscall CHString::TrimLeft(void)` | 539 | Exported Function
`public: void __thiscall CHString::SetAt(int,unsigned short)` | 492 | Exported Function
`public: void __thiscall CHString::UnlockBuffer(void)` | 545 | Exported Function
`public: void __thiscall CHString::TrimRight(void)` | 540 | Exported Function
`public: unsigned long __thiscall CRegistry::GetLongestValueData(void)` | 340 | Exported Function
`public: unsigned long __thiscall CRegistry::GetLongestSubKeySize(void)` | 339 | Exported Function
`public: unsigned long __thiscall CRegistry::GetValueCount(void)` | 377 | Exported Function
`public: unsigned long __thiscall CRegistry::GetLongestValueName(void)` | 341 | Exported Function
`public: unsigned long __thiscall CRegistry::GetLongestClassStringSize(void)` | 338 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyValue(unsigned short const *,class CHString &)` | 306 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyPath(class CHString &)` | 304 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyValue(unsigned short const *,void *,unsigned long *)` | 307 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyValue(unsigned short const *,unsigned long &)` | 305 | Exported Function
`public: unsigned long __thiscall CRegistry::NextSubKey(void)` | 446 | Exported Function
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(unsigned short const *,unsigned long &)` | 509 | Exported Function
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(unsigned short const *,class CHStringArray &)` | 511 | Exported Function
`public: unsigned short * __thiscall CFrameworkQuery::GetQueryClassName(void)` | 361 | Exported Function
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValueExpand(struct HKEY__ *,unsigned short const *,class CHString &)` | 512 | Exported Function
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(unsigned short const *,class CHString &)` | 510 | Exported Function
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHString &)` | 507 | Exported Function
`public: unsigned long __thiscall CRegistry::OpenCurrentUser(unsigned short const *,unsigned long)` | 453 | Exported Function
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(struct HKEY__ *,unsigned short const *,unsigned long &)` | 506 | Exported Function
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHStringArray &)` | 508 | Exported Function
`public: unsigned long __thiscall CRegistry::DeleteCurrentKeyValue(struct HKEY__ *,unsigned short const *)` | 221 | Exported Function
`public: unsigned long __thiscall CAutoEvent::Wait(unsigned long)` | 557 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentBinaryKeyValue(struct HKEY__ *,unsigned short const *,unsigned char *,unsigned long *)` | 291 | Exported Function
`public: unsigned long __thiscall CRegistry::DeleteCurrentKeyValue(unsigned short const *)` | 222 | Exported Function
`public: unsigned __int64 __thiscall WBEMTimeSpan::GetTime(void)const ` | 373 | Exported Function
`public: struct KeyRef & __thiscall KeyRef::operator=(struct KeyRef const &)` | 94 | Exported Function
`public: struct IWbemClassObject * __thiscall MethodContext::GetStatusObject(void)` | 369 | Exported Function
`public: unsigned __int64 __thiscall WBEMTime::GetTime(void)const ` | 372 | Exported Function
`public: struct ParsedObjectPath & __thiscall ParsedObjectPath::operator=(struct ParsedObjectPath const &)` | 96 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentBinaryKeyValue(unsigned short const *,class CHString &)` | 292 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(unsigned short const *,unsigned long &)` | 297 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(unsigned short const *,class CHStringArray &)` | 299 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyName(class CHString &)` | 303 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyCount(void)` | 302 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(unsigned short const *,class CHString &)` | 298 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHString &)` | 295 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentBinaryKeyValue(unsigned short const *,unsigned char *,unsigned long *)` | 293 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(struct HKEY__ *,unsigned short const *,unsigned long &)` | 294 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHStringArray &)` | 296 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::CreateClassEnum(unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 205 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::CancelAsyncRequest(long)` | 184 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::CreateInstanceEnum(unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 208 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::CreateClassEnumAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 206 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::CancelAsyncCall(struct IWbemObjectSink *)` | 183 | Exported Function
`public: virtual long __stdcall CWbemGlueFactory::CreateInstance(struct IUnknown *,struct _GUID const &,void * *)` | 207 | Exported Function
`public: virtual bool __thiscall CFrameworkQueryEx::IsExtended(void)` | 413 | Exported Function
`public: virtual long __stdcall CWbemGlueFactory::QueryInterface(struct _GUID const &,void * *)` | 466 | Exported Function
`public: virtual long __stdcall CWbemGlueFactory::LockServer(int)` | 437 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::CreateInstanceEnumAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 210 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::ExecNotificationQuery(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 243 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::ExecMethodAsync(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemClassObject *,struct IWbemObjectSink *)` | 242 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::ExecQuery(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 245 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::ExecNotificationQueryAsync(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 244 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::ExecMethod(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemClassObject *,struct IWbemClassObject * *,struct IWbemCallResult * *)` | 239 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::DeleteClassAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 220 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::DeleteClass(unsigned short * const,long,struct IWbemContext *,struct IWbemCallResult * *)` | 219 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::DeleteInstanceAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 226 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::DeleteInstance(unsigned short * const,long,struct IWbemContext *,struct IWbemCallResult * *)` | 223 | Exported Function
`public: unsigned short * __thiscall ParsedObjectPath::GetNamespacePart(void)` | 348 | Exported Function
`public: unsigned short * __thiscall ParsedObjectPath::GetKeyString(void)` | 330 | Exported Function
`public: unsigned short * __thiscall WBEMTime::GetBSTR(void)const ` | 280 | Exported Function
`public: unsigned short * __thiscall ParsedObjectPath::GetParentNamespacePart(void)` | 355 | Exported Function
`public: unsigned short * __thiscall CRegistry::GetClassNameW(void)` | 287 | Exported Function
`public: unsigned short * __thiscall CHString::GetBuffer(int)` | 282 | Exported Function
`public: unsigned short * __thiscall CHString::AllocSysString(void)const ` | 177 | Exported Function
`public: unsigned short * __thiscall CHString::LockBuffer(void)` | 434 | Exported Function
`public: unsigned short * __thiscall CHString::GetBufferSetLength(int)` | 283 | Exported Function
`public: unsigned short * __thiscall WBEMTime::GetDMTF(int)const ` | 308 | Exported Function
`public: virtual __thiscall MethodContext::~MethodContext(void)` | 69 | Exported Function
`public: virtual __thiscall CThreadBase::~CThreadBase(void)` | 63 | Exported Function
`public: virtual __thiscall ProviderLog::~ProviderLog(void)` | 72 | Exported Function
`public: virtual __thiscall Provider::~Provider(void)` | 71 | Exported Function
`public: virtual __thiscall CInstance::~CInstance(void)` | 59 | Exported Function
`public: unsigned short * __thiscall WBEMTimeSpan::GetBSTR(void)const ` | 281 | Exported Function
`public: unsigned short * __thiscall WBEMTime::GetDMTFNonNtfs(void)const ` | 309 | Exported Function
`public: unsigned short __thiscall CHString::operator[](int)const ` | 117 | Exported Function
`public: unsigned short __thiscall CHString::GetAt(int)const ` | 278 | Exported Function
`public: class CHString const * __thiscall CHStringArray::GetData(void)const ` | 316 | Exported Function
`private: unsigned long __thiscall CRegistry::GetCurrentRawSubKeyValue(unsigned short const *,void *,unsigned long *,unsigned long *)` | 301 | Exported Function
`private: unsigned long __thiscall CRegistry::GetCurrentRawKeyValue(struct HKEY__ *,unsigned short const *,void *,unsigned long *,unsigned long *)` | 300 | Exported Function
`private: void __thiscall CFrameworkQuery::Reset(void)` | 484 | Exported Function
`private: unsigned long __thiscall CRegistry::OpenSubKey(void)` | 456 | Exported Function
`private: struct IWbemServices * __stdcall CWbemProviderGlue::InternalGetNamespaceConnection(unsigned short const *)` | 408 | Exported Function
`private: static void __stdcall CWinMsgEvent::WindowsDispatch(void)` | 558 | Exported Function
`private: static void __stdcall CWinMsgEvent::DestroyMsgWindow(void)` | 230 | Exported Function
`private: struct IWbemClassObject * __thiscall Provider::GetClassObjectInterface(class MethodContext *)` | 289 | Exported Function
`private: static void __stdcall Provider::InitComputerName(void)` | 401 | Exported Function
`private: void __thiscall CObjectPathParser::Empty(void)` | 234 | Exported Function
`private: void __thiscall CThreadBase::Unlock(void)` | 544 | Exported Function
`private: void __thiscall CThreadBase::Lock(void)` | 433 | Exported Function
`private: void __thiscall CWbemProviderGlue::FlushAll(void)` | 255 | Exported Function
`private: void __thiscall CWbemProviderGlue::AddFlushPtr(void *)` | 161 | Exported Function
`private: void __thiscall CRegistrySearch::CheckAndAddToList(class CRegistry *,class CHString,class CHString,class CHPtrArray &,class CHString,class CHString,int)` | 185 | Exported Function
`private: void __thiscall CRegistry::CloseSubKey(void)` | 192 | Exported Function
`private: void __thiscall CObjectPathParser::Zero(void)` | 559 | Exported Function
`private: void __thiscall CRegistry::SetDefaultValues(void)` | 517 | Exported Function
`private: void __thiscall CRegistry::PrepareToReOpen(void)` | 459 | Exported Function
`private: static unsigned long CWbemProviderGlue::s_dwMajorVersion` | 602 | Exported Function
`private: static unsigned long CRegistry::s_dwPlatform` | 603 | Exported Function
`private: static unsigned short * CWbemProviderGlue::s_wstrCSDVersion` | 610 | Exported Function
`private: static unsigned long CWbemProviderGlue::s_dwPlatform` | 604 | Exported Function
`private: static unsigned long __stdcall CWinMsgEvent::dwThreadProc(void *)` | 562 | Exported Function
`private: static struct HWND__ * CWinMsgEvent::mg_hWnd` | 580 | Exported Function
`private: static struct HWND__ * __stdcall CWinMsgEvent::CreateMsgWindow(void)` | 212 | Exported Function
`private: static struct IWbemClassObject * CWbemProviderGlue::m_pStatusObject` | 574 | Exported Function
`private: static struct IWbemClassObject * __stdcall CWbemProviderGlue::GetStatusObject(class MethodContext *,unsigned short const *)` | 368 | Exported Function
`private: static void * CWinMsgEvent::mg_hDevNotify` | 578 | Exported Function
`private: static void __stdcall CWbemProviderGlue::UnlockFactoryMap(void)` | 546 | Exported Function
`private: static void __stdcall CWbemProviderGlue::UnInit(void)` | 541 | Exported Function
`private: static void __stdcall CWinMsgEvent::CreateMsgProvider(void)` | 211 | Exported Function
`private: static void __stdcall CWbemProviderGlue::UnlockProviderMap(void)` | 547 | Exported Function
`private: static void __stdcall CWbemProviderGlue::LockProviderMap(void)` | 436 | Exported Function
`private: static void __stdcall CWbemProviderGlue::GetComputerNameW(class CHString &)` | 290 | Exported Function
`private: static void * CWinMsgEvent::mg_hThreadPumpHandle` | 579 | Exported Function
`private: static void __stdcall CWbemProviderGlue::LockFactoryMap(void)` | 435 | Exported Function
`private: static void __stdcall CWbemProviderGlue::Init(void)` | 400 | Exported Function
`protected: virtual long __thiscall Provider::EnumerateInstances(class MethodContext *,long)` | 238 | Exported Function
`protected: virtual long __thiscall Provider::DeleteInstance(class CInstance const &,long)` | 225 | Exported Function
`protected: virtual long __thiscall Provider::ExecQuery(class MethodContext *,class CFrameworkQuery &,long)` | 246 | Exported Function
`protected: virtual long __thiscall Provider::ExecMethod(class CInstance const &,unsigned short * const,class CInstance *,class CInstance *,long)` | 241 | Exported Function
`protected: unsigned long __thiscall CFrameworkQuery::IsInList(class CHStringArray const &,unsigned short const *)` | 414 | Exported Function
`protected: static void __stdcall CWbemProviderGlue::AddToFactoryMap(class CWbemGlueFactory const *,long *)` | 172 | Exported Function
`protected: static long __stdcall CWbemProviderGlue::IncrementMapCount(long *)` | 393 | Exported Function
`protected: struct CHStringData * __thiscall CHString::GetData(void)const ` | 314 | Exported Function
`protected: static void __stdcall CWbemProviderGlue::RemoveFromFactoryMap(class CWbemGlueFactory const *)` | 483 | Exported Function
`protected: virtual long __thiscall Provider::GetObject(class CInstance *,long)` | 352 | Exported Function
`protected: virtual long __thiscall Provider::ValidatePutInstanceFlags(long)` | 555 | Exported Function
`protected: virtual long __thiscall Provider::ValidateMethodFlags(long)` | 554 | Exported Function
`protected: virtual void __thiscall CThreadBase::OnFinalRelease(void)` | 450 | Exported Function
`protected: virtual long __thiscall Provider::ValidateQueryFlags(long)` | 556 | Exported Function
`protected: virtual long __thiscall Provider::ValidateGetObjFlags(long)` | 552 | Exported Function
`protected: virtual long __thiscall Provider::PutInstance(class CInstance const &,long)` | 464 | Exported Function
`protected: virtual long __thiscall Provider::GetObject(class CInstance *,long,class CFrameworkQuery &)` | 353 | Exported Function
`protected: virtual long __thiscall Provider::ValidateEnumerationFlags(long)` | 550 | Exported Function
`protected: virtual long __thiscall Provider::ValidateDeletionFlags(long)` | 549 | Exported Function
`protected: class CHString const & __thiscall Provider::GetLocalComputerName(void)` | 332 | Exported Function
`protected: class CHString const & __thiscall CFrameworkQuery::GetNamespace(void)` | 344 | Exported Function
`protected: class CHString const & __thiscall Provider::GetProviderName(void)` | 359 | Exported Function
`protected: class CHString const & __thiscall Provider::GetNamespace(void)` | 345 | Exported Function
`protected: class CHString __thiscall Provider::MakeLocalPath(class CHString const &)` | 439 | Exported Function
`protected: bool __thiscall CWinMsgEvent::UnRegisterMessage(unsigned int,int)` | 543 | Exported Function
`private: void __thiscall ProviderLog::CheckFileSize(union _LARGE_INTEGER &,class CHString const &)` | 186 | Exported Function
`protected: bool __thiscall Provider::SetCreationClassName(class CInstance *)` | 505 | Exported Function
`protected: bool __thiscall Provider::GetLocalInstancePath(class CInstance const *,class CHString &)` | 333 | Exported Function
`protected: class CInstance * __thiscall Provider::CreateNewInstance(class MethodContext *)` | 213 | Exported Function
`protected: static long __stdcall CWbemProviderGlue::DecrementMapCount(class CWbemGlueFactory const *)` | 217 | Exported Function
`protected: static long * __stdcall CWbemProviderGlue::GetMapCountPtr(class CWbemGlueFactory const *)` | 342 | Exported Function
`protected: static long __stdcall CWbemProviderGlue::IncrementMapCount(class CWbemGlueFactory const *)` | 394 | Exported Function
`protected: static long __stdcall CWbemProviderGlue::DecrementMapCount(long *)` | 216 | Exported Function
`protected: static int __stdcall CHString::SafeStrlen(unsigned short const *)` | 488 | Exported Function
`protected: int __thiscall CHString::LoadStringW(unsigned int,unsigned short *,unsigned int)` | 428 | Exported Function
`protected: int __thiscall CFrameworkQuery::IsReference(unsigned short const *)` | 424 | Exported Function
`protected: long __thiscall Provider::ValidateFlags(long,enum Provider::FlagDefs)` | 551 | Exported Function
`protected: long __thiscall Provider::Commit(class CInstance *,bool)` | 195 | Exported Function
`private: int __thiscall CObjectPathParser::NextToken(void)` | 447 | Exported Function
`private: int __thiscall CObjectPathParser::keyref_term(void)` | 570 | Exported Function
`private: int __thiscall CObjectPathParser::ns_list_rest(void)` | 592 | Exported Function
`private: int __thiscall CObjectPathParser::ns_list(void)` | 591 | Exported Function
`private: int __thiscall CObjectPathParser::keyref_list(void)` | 569 | Exported Function
`private: int __thiscall CObjectPathParser::ident_becomes_ns(void)` | 564 | Exported Function
`private: int __thiscall CObjectPathParser::ident_becomes_class(void)` | 563 | Exported Function
`private: int __thiscall CObjectPathParser::keyref(void)` | 568 | Exported Function
`private: int __thiscall CObjectPathParser::key_const(void)` | 567 | Exported Function
`private: int __thiscall CObjectPathParser::ns_or_class(void)` | 593 | Exported Function
`private: int __thiscall Provider::ValidateIMOSPointer(void)` | 553 | Exported Function
`private: int __thiscall Provider::SetKeyFromParsedObjectPath(class CInstance *,struct ParsedObjectPath *)` | 519 | Exported Function
`private: long __thiscall CRegistry::myRegDeleteKey(struct HKEY__ *,unsigned short const *)` | 583 | Exported Function
`private: long __thiscall CRegistry::myRegCreateKeyEx(struct HKEY__ *,unsigned short const *,unsigned long,unsigned short *,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES * const,struct HKEY__ * *,unsigned long *)` | 582 | Exported Function
`private: int __thiscall CObjectPathParser::propname(void)` | 598 | Exported Function
`private: int __thiscall CObjectPathParser::objref(void)` | 595 | Exported Function
`private: int __thiscall CObjectPathParser::ns_or_server(void)` | 594 | Exported Function
`private: int __thiscall CObjectPathParser::optional_objref(void)` | 597 | Exported Function
`private: int __thiscall CObjectPathParser::objref_rest(void)` | 596 | Exported Function
`class ProviderLog captainsLog` | 561 | Exported Function
`class CHString __stdcall operator+(unsigned short,class CHString const &)` | 127 | Exported Function
`const CInstance::``vftable'` | 148 | Exported Function
`const CFrameworkQueryEx::``vftable'` | 147 | Exported Function
`class CHString __stdcall operator+(unsigned short const *,class CHString const &)` | 128 | Exported Function
`class CHString __stdcall operator+(class CHString const &,class CHString const &)` | 124 | Exported Function
`_DoCmd@16` | 611 | Exported Function
`class CHString __stdcall operator+(class CHString const &,unsigned short)` | 125 | Exported Function
`class CHString __stdcall operator+(class CHString const &,unsigned short const *)` | 126 | Exported Function
`const CThreadBase::``vftable'` | 149 | Exported Function
`const ProviderLog::``vftable'` | 156 | Exported Function
`const Provider::``vftable'` | 155 | Exported Function
`private: int __thiscall CObjectPathParser::begin_parse(void)` | 560 | Exported Function
`private: class CWbemProviderGlue * __thiscall MethodContext::GetProviderGlue(void)` | 358 | Exported Function
`const MethodContext::``vftable'` | 154 | Exported Function
`const CWbemProviderGlue::``vftable'{for ``IWbemProviderInit'}` | 151 | Exported Function
`const CWbemGlueFactory::``vftable'` | 150 | Exported Function
`const CWinMsgEvent::``vftable'` | 153 | Exported Function
`const CWbemProviderGlue::``vftable'{for ``IWbemServices'}` | 152 | Exported Function
`private: static class std::map<class CHString,void *,struct std::less<class CHString>,class std::allocator<struct std::pair<class CHString const ,void *> > > CWbemProviderGlue::s_providersmap` | 608 | Exported Function
`private: static class Provider * __stdcall CWbemProviderGlue::SearchMapForProvider(unsigned short const *,unsigned short const *)` | 490 | Exported Function
`private: static class std::multimap<unsigned int,class CWinMsgEvent *,struct std::less<unsigned int>,class std::allocator<struct std::pair<unsigned int const ,class CWinMsgEvent *> > > CWinMsgEvent::mg_oSinkMap` | 581 | Exported Function
`private: static class std::map<void const *,long *,struct std::less<void const *>,class std::allocator<struct std::pair<void const * const,long *> > > CWbemProviderGlue::s_factorymap` | 606 | Exported Function
`private: static class Provider * __stdcall CWbemProviderGlue::AddProviderToMap(unsigned short const *,unsigned short const *,class Provider *)` | 166 | Exported Function
`private: static class CCritSec CWinMsgEvent::mg_csMapLock` | 576 | Exported Function
`private: static class CCritSec CWbemProviderGlue::s_csProviderMap` | 601 | Exported Function
`private: static class CHString Provider::s_strComputerName` | 609 | Exported Function
`private: static class CCritSec CWinMsgEvent::mg_csWindowLock` | 577 | Exported Function
`private: static class std::set<void *,struct std::less<void *>,class std::allocator<void *> > CWbemProviderGlue::m_FlushPtrs` | 571 | Exported Function
`private: static long __stdcall CWbemProviderGlue::GetInstanceFromCIMOM(unsigned short const *,unsigned short const *,class MethodContext *,class CInstance * *)` | 325 | Exported Function
`private: static long __stdcall CWbemProviderGlue::CheckImpersonationLevel(void)` | 187 | Exported Function
`private: static long CWbemProviderGlue::s_lObjects` | 607 | Exported Function
`private: static long __stdcall CWinMsgEvent::MsgWndProc(struct HWND__ *,unsigned int,unsigned int,long)` | 445 | Exported Function
`private: static int Provider::initFailed_` | 566 | Exported Function
`private: static int __stdcall CWinMsgEvent::CtrlHandlerRoutine(unsigned long)` | 215 | Exported Function
`private: static int __stdcall CRegistry::SetPlatformID(void)` | 521 | Exported Function
`private: static int CWbemProviderGlue::s_bInitted` | 599 | Exported Function
`private: static int CRegistry::s_fPlatformSet` | 605 | Exported Function
`private: long __thiscall CRegistry::myRegSetValueEx(struct HKEY__ *,unsigned short const *,unsigned long,unsigned long,unsigned char const *,unsigned long)` | 590 | Exported Function
`private: long __thiscall CRegistry::myRegQueryValueEx(struct HKEY__ *,unsigned short const *,unsigned long *,unsigned long *,unsigned char *,unsigned long *)` | 589 | Exported Function
`private: long __thiscall CWbemProviderGlue::PreProcessPutInstanceParms(struct IWbemClassObject *,struct IWbemClassObject * *,struct IWbemContext *)` | 458 | Exported Function
`private: long __thiscall CWbemProviderGlue::NullOutUnsetProperties(struct IWbemClassObject *,struct IWbemClassObject * *,struct tagVARIANT const &)` | 449 | Exported Function
`private: long __thiscall CRegistry::myRegQueryInfoKey(struct HKEY__ *,unsigned short *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,struct _FILETIME *)` | 588 | Exported Function
`private: long __thiscall CRegistry::myRegEnumKey(struct HKEY__ *,unsigned long,unsigned short *,unsigned long)` | 585 | Exported Function
`private: long __thiscall CRegistry::myRegDeleteValue(struct HKEY__ *,unsigned short const *)` | 584 | Exported Function
`private: long __thiscall CRegistry::myRegOpenKeyEx(struct HKEY__ *,unsigned short const *,unsigned long,unsigned long,struct HKEY__ * *)` | 587 | Exported Function
`private: long __thiscall CRegistry::myRegEnumValue(struct HKEY__ *,unsigned long,unsigned short *,unsigned long *,unsigned long *,unsigned long *,unsigned char *,unsigned long *)` | 586 | Exported Function
`private: long __thiscall Provider::CreateInstanceEnum(class MethodContext *,long)` | 209 | Exported Function
`private: static class CCritSec CWbemProviderGlue::m_csFlushPtrs` | 572 | Exported Function
`private: static class CAutoEvent CWinMsgEvent::mg_aeCreateWindow` | 575 | Exported Function
`private: static class CCritSec CWbemProviderGlue::s_csFactoryMap` | 600 | Exported Function
`private: static class CCritSec CWbemProviderGlue::m_csStatusObject` | 573 | Exported Function
`private: long __thiscall Provider::PutInstance(struct IWbemClassObject *,long,class MethodContext *)` | 463 | Exported Function
`private: long __thiscall Provider::ExecMethod(struct ParsedObjectPath *,unsigned short *,long,class CInstance *,class CInstance *,class MethodContext *)` | 240 | Exported Function
`private: long __thiscall Provider::DeleteInstance(struct ParsedObjectPath *,long,class MethodContext *)` | 224 | Exported Function
`private: long __thiscall Provider::GetObject(struct ParsedObjectPath *,class MethodContext *,long)` | 351 | Exported Function
`private: long __thiscall Provider::ExecuteQuery(class MethodContext *,class CFrameworkQuery &,long)` | 248 | Exported Function
`protected: virtual void __thiscall Provider::Flush(void)` | 254 | Exported Function
`public: bool __thiscall CInstance::SetByte(unsigned short const *,unsigned char)` | 496 | Exported Function
`public: bool __thiscall CInstance::Setbool(unsigned short const *,bool)` | 535 | Exported Function
`public: bool __thiscall CInstance::SetCharSplat(unsigned short const *,unsigned long)` | 502 | Exported Function
`public: bool __thiscall CInstance::SetCharSplat(unsigned short const *,char const *)` | 503 | Exported Function
`public: bool __thiscall CInstance::IsNull(unsigned short const *)const ` | 419 | Exported Function
`public: bool __thiscall CInstance::GetWBEMINT64(unsigned short const *,unsigned __int64 &)const ` | 386 | Exported Function
`public: bool __thiscall CInstance::GetWBEMINT64(unsigned short const *,class CHString &)const ` | 384 | Exported Function
`public: bool __thiscall CInstance::GetWORD(unsigned short const *,unsigned short &)const ` | 388 | Exported Function
`public: bool __thiscall CInstance::GetWCHAR(unsigned short const *,unsigned short * *)const ` | 387 | Exported Function
`public: bool __thiscall CInstance::SetCharSplat(unsigned short const *,unsigned short const *)` | 501 | Exported Function
`public: bool __thiscall CInstance::SetEmbeddedObject(unsigned short const *,class CInstance &)` | 518 | Exported Function
`public: bool __thiscall CInstance::SetDWORD(unsigned short const *,unsigned long)` | 515 | Exported Function
`public: bool __thiscall CInstance::SetStringArray(unsigned short const *,struct tagSAFEARRAY const &)` | 526 | Exported Function
`public: bool __thiscall CInstance::SetNull(unsigned short const *)` | 520 | Exported Function
`public: bool __thiscall CInstance::SetDOUBLE(unsigned short const *,double)` | 514 | Exported Function
`public: bool __thiscall CInstance::SetCHString(unsigned short const *,class CHString const &)` | 498 | Exported Function
`public: bool __thiscall CInstance::SetCHString(unsigned short const *,char const *)` | 499 | Exported Function
`public: bool __thiscall CInstance::SetDateTime(unsigned short const *,class WBEMTime const &)` | 516 | Exported Function
`public: bool __thiscall CInstance::SetCHString(unsigned short const *,unsigned short const *)` | 497 | Exported Function
`public: bool __thiscall CInstance::Getbool(unsigned short const *,bool &)const ` | 389 | Exported Function
`public: bool __thiscall CFrameworkQuery::KeysOnly(void)` | 426 | Exported Function
`public: bool __thiscall CInstance::GetCHString(unsigned short const *,class CHString &)const ` | 285 | Exported Function
`public: bool __thiscall CInstance::GetByte(unsigned short const *,unsigned char &)const ` | 284 | Exported Function
`public: bool __thiscall CFrameworkQuery::IsPropertyRequired(unsigned short const *)` | 423 | Exported Function
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(unsigned short * const)` | 51 | Exported Function
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(struct _FILETIME const &)` | 49 | Exported Function
`public: bool __thiscall CFrameworkQuery::AllPropertiesAreRequired(void)` | 173 | Exported Function
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(void)` | 52 | Exported Function
`public: bool __thiscall CInstance::GetDateTime(unsigned short const *,class WBEMTime &)const ` | 317 | Exported Function
`public: bool __thiscall CInstance::GetVariant(unsigned short const *,struct tagVARIANT &)const ` | 382 | Exported Function
`public: bool __thiscall CInstance::GetTimeSpan(unsigned short const *,class WBEMTimeSpan &)const ` | 374 | Exported Function
`public: bool __thiscall CInstance::GetWBEMINT64(unsigned short const *,__int64 &)const ` | 385 | Exported Function
`public: bool __thiscall CInstance::GetWBEMINT16(unsigned short const *,short &)const ` | 383 | Exported Function
`public: bool __thiscall CInstance::GetStringArray(unsigned short const *,struct tagSAFEARRAY * &)const ` | 370 | Exported Function
`public: bool __thiscall CInstance::GetDWORD(unsigned short const *,unsigned long &)const ` | 311 | Exported Function
`public: bool __thiscall CInstance::GetDOUBLE(unsigned short const *,double &)const ` | 310 | Exported Function
`public: bool __thiscall CInstance::GetStatus(unsigned short const *,bool &,unsigned short &)const ` | 367 | Exported Function
`public: bool __thiscall CInstance::GetEmbeddedObject(unsigned short const *,class CInstance * *,class MethodContext *)const ` | 318 | Exported Function
`public: class CHString __thiscall CHStringArray::operator[](int)const ` | 119 | Exported Function
`public: class CHString __thiscall CHStringArray::GetAt(int)const ` | 279 | Exported Function
`public: class CHString const & __thiscall CHString::operator+=(char)` | 140 | Exported Function
`public: class CHString const & __thiscall CFrameworkQuery::GetQuery(void)` | 360 | Exported Function
`public: class CHString __thiscall CHString::SpanIncluding(unsigned short const *)const ` | 538 | Exported Function
`public: class CHString __thiscall CHString::Mid(int,int)const ` | 444 | Exported Function
`public: class CHString __thiscall CHString::Mid(int)const ` | 443 | Exported Function
`public: class CHString __thiscall CHString::SpanExcluding(unsigned short const *)const ` | 537 | Exported Function
`public: class CHString __thiscall CHString::Right(int)const ` | 487 | Exported Function
`public: class CHString const & __thiscall CHString::operator+=(class CHString const &)` | 139 | Exported Function
`public: class CHString const & __thiscall CHString::operator=(unsigned char const *)` | 82 | Exported Function
`public: class CHString const & __thiscall CHString::operator=(class CHString const &)` | 77 | Exported Function
`public: class CHString const & __thiscall CHString::operator=(unsigned short)` | 79 | Exported Function
`public: class CHString const & __thiscall CHString::operator=(unsigned short const *)` | 83 | Exported Function
`public: class CHString const & __thiscall CHString::operator=(class CHString *)` | 80 | Exported Function
`public: class CHString const & __thiscall CHString::operator+=(unsigned short)` | 141 | Exported Function
`public: class CHString const & __thiscall CHString::operator+=(unsigned short const *)` | 142 | Exported Function
`public: class CHString const & __thiscall CHString::operator=(char)` | 78 | Exported Function
`public: class CHString const & __thiscall CHString::operator=(char const *)` | 81 | Exported Function
`public: bool __thiscall CInstance::SetWCHARSplat(unsigned short const *,unsigned short const *)` | 533 | Exported Function
`public: bool __thiscall CInstance::SetWBEMINT64(unsigned short const *,unsigned __int64)` | 532 | Exported Function
`public: bool __thiscall MethodContext::SetStatusObject(struct IWbemClassObject *)` | 525 | Exported Function
`public: bool __thiscall CInstance::SetWORD(unsigned short const *,unsigned short)` | 534 | Exported Function
`public: bool __thiscall CInstance::SetWBEMINT64(unsigned short const *,class CHString const &)` | 530 | Exported Function
`public: bool __thiscall CInstance::SetVariant(unsigned short const *,struct tagVARIANT const &)` | 528 | Exported Function
`public: bool __thiscall CInstance::SetTimeSpan(unsigned short const *,class WBEMTimeSpan const &)` | 527 | Exported Function
`public: bool __thiscall CInstance::SetWBEMINT64(unsigned short const *,__int64)` | 531 | Exported Function
`public: bool __thiscall CInstance::SetWBEMINT16(unsigned short const *,short const &)` | 529 | Exported Function
`public: bool __thiscall WBEMTime::IsOk(void)const ` | 421 | Exported Function
`public: class CHString & __thiscall CHStringArray::operator[](int)` | 118 | Exported Function
`public: class CHString & __thiscall CHStringArray::ElementAt(int)` | 232 | Exported Function
`public: class CHString __thiscall CHString::Left(int)const ` | 427 | Exported Function
`public: class CHString * __thiscall CHStringArray::GetData(void)` | 315 | Exported Function
`public: class CHPtrArray & __thiscall CHPtrArray::operator=(class CHPtrArray const &)` | 76 | Exported Function
`public: class CAutoEvent & __thiscall CAutoEvent::operator=(class CAutoEvent const &)` | 73 | Exported Function
`public: bool __thiscall WBEMTimeSpan::IsOk(void)const ` | 422 | Exported Function
`public: class CFrameworkQueryEx & __thiscall CFrameworkQueryEx::operator=(class CFrameworkQueryEx const &)` | 75 | Exported Function
`public: class CFrameworkQuery & __thiscall CFrameworkQuery::operator=(class CFrameworkQuery const &)` | 74 | Exported Function
`public: __thiscall CHString::CHString(unsigned short const *,int)` | 12 | Exported Function
`public: __thiscall CHString::CHString(unsigned short const *)` | 11 | Exported Function
`public: __thiscall CHString::CHString(void)` | 13 | Exported Function
`public: __thiscall CHString::CHString(unsigned short,int)` | 8 | Exported Function
`public: __thiscall CHString::CHString(unsigned char const *)` | 10 | Exported Function
`public: __thiscall CHPtrArray::~CHPtrArray(void)` | 56 | Exported Function
`public: __thiscall CHPtrArray::CHPtrArray(void)` | 6 | Exported Function
`public: __thiscall CHString::CHString(class CHString const &)` | 7 | Exported Function
`public: __thiscall CHString::CHString(char const *)` | 9 | Exported Function
`public: __thiscall CHString::operator unsigned short const *(void)const ` | 120 | Exported Function
`public: __thiscall CObjectPathParser::~CObjectPathParser(void)` | 60 | Exported Function
`public: __thiscall CObjectPathParser::CObjectPathParser(enum ObjectParserFlags)` | 17 | Exported Function
`public: __thiscall CreateMutexAsProcess::~CreateMutexAsProcess(void)` | 67 | Exported Function
`public: __thiscall CreateMutexAsProcess::CreateMutexAsProcess(unsigned short const *)` | 32 | Exported Function
`public: __thiscall CInstance::CInstance(struct IWbemClassObject *,class MethodContext *)` | 16 | Exported Function
`public: __thiscall CHStringArray::CHStringArray(void)` | 14 | Exported Function
`public: __thiscall CHString::~CHString(void)` | 57 | Exported Function
`public: __thiscall CInstance::CInstance(class CInstance const &)` | 15 | Exported Function
`public: __thiscall CHStringArray::~CHStringArray(void)` | 58 | Exported Function
`protected: void __thiscall CHString::CopyBeforeWrite(void)` | 202 | Exported Function
`protected: void __thiscall CHString::ConcatInPlace(int,unsigned short const *)` | 199 | Exported Function
`protected: void __thiscall CInstance::LogError(unsigned short const *,unsigned short const *,unsigned short const *,long)const ` | 438 | Exported Function
`protected: void __thiscall CHString::Init(void)` | 399 | Exported Function
`protected: void __thiscall CHString::ConcatCopy(int,unsigned short const *,int,unsigned short const *)` | 198 | Exported Function
`protected: void __thiscall CHString::AllocBuffer(int)` | 175 | Exported Function
`protected: void __thiscall CHString::AllocBeforeWrite(int)` | 174 | Exported Function
`protected: void __thiscall CHString::AssignCopy(int,unsigned short const *)` | 180 | Exported Function
`protected: void __thiscall CHString::AllocCopy(class CHString &,int,int,int)const ` | 176 | Exported Function
`protected: void __thiscall CWinMsgEvent::RegisterForMessage(unsigned int,int)` | 470 | Exported Function
`public: __thiscall CFrameworkQueryEx::CFrameworkQueryEx(class CFrameworkQueryEx const &)` | 4 | Exported Function
`public: __thiscall CFrameworkQuery::~CFrameworkQuery(void)` | 54 | Exported Function
`public: __thiscall CFrameworkQueryEx::~CFrameworkQueryEx(void)` | 55 | Exported Function
`public: __thiscall CFrameworkQueryEx::CFrameworkQueryEx(void)` | 5 | Exported Function
`public: __thiscall CFrameworkQuery::CFrameworkQuery(void)` | 3 | Exported Function
`public: __thiscall CAutoEvent::CAutoEvent(void)` | 1 | Exported Function
`protected: void __thiscall CWinMsgEvent::UnRegisterAllMessages(void)` | 542 | Exported Function
`public: __thiscall CFrameworkQuery::CFrameworkQuery(class CFrameworkQuery const &)` | 2 | Exported Function
`public: __thiscall CAutoEvent::~CAutoEvent(void)` | 53 | Exported Function
`public: __thiscall ParsedObjectPath::~ParsedObjectPath(void)` | 70 | Exported Function
`public: __thiscall ParsedObjectPath::ParsedObjectPath(void)` | 37 | Exported Function
`public: __thiscall Provider::Provider(unsigned short const *,unsigned short const *)` | 39 | Exported Function
`public: __thiscall Provider::Provider(class Provider const &)` | 38 | Exported Function
`public: __thiscall MethodContext::MethodContext(struct IWbemContext *,class CWbemProviderGlue *)` | 36 | Exported Function
`public: __thiscall KeyRef::KeyRef(void)` | 34 | Exported Function
`public: __thiscall KeyRef::KeyRef(unsigned short const *,struct tagVARIANT const *)` | 33 | Exported Function
`public: __thiscall MethodContext::MethodContext(class MethodContext const &)` | 35 | Exported Function
`public: __thiscall KeyRef::~KeyRef(void)` | 68 | Exported Function
`public: __thiscall ProviderLog::ProviderLog(class ProviderLog const &)` | 40 | Exported Function
`public: __thiscall WBEMTime::WBEMTime(void)` | 47 | Exported Function
`public: __thiscall WBEMTime::WBEMTime(unsigned short * const)` | 46 | Exported Function
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(long const &)` | 48 | Exported Function
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(int,int,int,int,int,int,int)` | 50 | Exported Function
`public: __thiscall WBEMTime::WBEMTime(struct tm const &)` | 45 | Exported Function
`public: __thiscall WBEMTime::WBEMTime(long const &)` | 42 | Exported Function
`public: __thiscall ProviderLog::ProviderLog(void)` | 41 | Exported Function
`public: __thiscall WBEMTime::WBEMTime(struct _SYSTEMTIME const &)` | 44 | Exported Function
`public: __thiscall WBEMTime::WBEMTime(struct _FILETIME const &)` | 43 | Exported Function
`public: __thiscall CThreadBase::CThreadBase(class CThreadBase const &)` | 22 | Exported Function
`public: __thiscall CRegistrySearch::~CRegistrySearch(void)` | 62 | Exported Function
`public: __thiscall CWbemGlueFactory::CWbemGlueFactory(class CWbemGlueFactory const &)` | 24 | Exported Function
`public: __thiscall CThreadBase::CThreadBase(enum CThreadBase::THREAD_SAFETY_MECHANISM)` | 23 | Exported Function
`public: __thiscall CRegistrySearch::CRegistrySearch(void)` | 21 | Exported Function
`public: __thiscall CRegistry::CRegistry(void)` | 19 | Exported Function
`public: __thiscall CRegistry::CRegistry(class CRegistry const &)` | 18 | Exported Function
`public: __thiscall CRegistrySearch::CRegistrySearch(class CRegistrySearch const &)` | 20 | Exported Function
`public: __thiscall CRegistry::~CRegistry(void)` | 61 | Exported Function
`public: __thiscall CWbemGlueFactory::CWbemGlueFactory(long *)` | 25 | Exported Function
`public: __thiscall CWinMsgEvent::CWinMsgEvent(class CWinMsgEvent const &)` | 30 | Exported Function
`public: __thiscall CWbemProviderGlue::~CWbemProviderGlue(void)` | 65 | Exported Function
`public: __thiscall CWinMsgEvent::~CWinMsgEvent(void)` | 66 | Exported Function
`public: __thiscall CWinMsgEvent::CWinMsgEvent(void)` | 31 | Exported Function
`public: __thiscall CWbemProviderGlue::CWbemProviderGlue(void)` | 29 | Exported Function
`public: __thiscall CWbemGlueFactory::~CWbemGlueFactory(void)` | 64 | Exported Function
`public: __thiscall CWbemGlueFactory::CWbemGlueFactory(void)` | 26 | Exported Function
`public: __thiscall CWbemProviderGlue::CWbemProviderGlue(long *)` | 28 | Exported Function
`public: __thiscall CWbemProviderGlue::CWbemProviderGlue(class CWbemProviderGlue const &)` | 27 | Exported Function


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


