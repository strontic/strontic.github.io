---
title: framedyn.dll | WMI SDK Provider Framework
excerpt: What is framedyn.dll?
---

# framedyn.dll 

* File Path: `C:\Windows\SysWOW64\framedyn.dll`
* Description: WMI SDK Provider Framework

## Hashes

Type | Hash
-- | --
MD5 | `190642F9610123402B18AC965F7057FC`
SHA1 | `D2C67BF8428E05F93FE6E84321DA6446AF485B00`
SHA256 | `EFAD3D5181333FAA5FB523E6D62D8A13D1D31303E5CD5157BED94B81B4FDFE23`
SHA384 | `8F122C76876FDCB1C3568E12BDB27CB8289CA029B59E28A46828B7095781DCA3D8B008551645448E0D981A427D9C67F3`
SHA512 | `9FEC0DDA86D3A77BE350BB64FA1A47723AFBA8A0E971506FFCEF7F65CBF7FE5ED14165703F1DE9A4CECF74E385F12E167B8E6A3AA0BE13A6530CDD3A1239D043`
SSDEEP | `3072:S23bJqljuWogmhlLj76dwHDryKnjqTTmFDgZCpiNFgqq396QAzVk:Swbauh3Zmu1jmgcZCkglcQAh`
IMP | `7527D2F4D07397DA5AB21D94C883445E`
PESHA1 | `9D50DA3C5FFDC7A9CE494D7CFD99374858986A68`
PE256 | `7615E8AD8335E3DCD172A1895B43194FCD822CDA72738D188BF219A63A8D5A14`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: long __thiscall CInstance::Commit(void)` | 196 | Exported Function
`public: long __thiscall CInstance::AddRef(void)` | 169 | Exported Function
`public: long __thiscall CRegistry::CreateOpen(struct HKEY__ *,unsigned short const *,unsigned short *,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES *,unsigned long *)` | 216 | Exported Function
`public: long __thiscall CInstance::Release(void)` | 475 | Exported Function
`public: long __thiscall CFrameworkQueryEx::GetValuesForProp(unsigned short const *,class std::vector<int,class std::allocator<int> > &)` | 382 | Exported Function
`public: long __thiscall CFrameworkQuery::Init(struct ParsedObjectPath *,struct IWbemContext *,unsigned short const *,class CHString &)` | 399 | Exported Function
`public: long __thiscall CFrameworkQuery::GetValuesForProp(unsigned short const *,class std::vector<class _bstr_t,class std::allocator<class _bstr_t> > &)` | 380 | Exported Function
`public: long __thiscall CFrameworkQueryEx::GetValuesForProp(unsigned short const *,class std::vector<class _variant_t,class std::allocator<class _variant_t> > &)` | 383 | Exported Function
`public: long __thiscall CFrameworkQuery::Init(unsigned short * const,unsigned short * const,long,class CHString &)` | 400 | Exported Function
`public: long __thiscall CRegistry::DeleteKey(class CHString *)` | 229 | Exported Function
`public: long __thiscall CThreadBase::Release(void)` | 476 | Exported Function
`public: long __thiscall CThreadBase::AddRef(void)` | 170 | Exported Function
`public: long __thiscall MethodContext::Release(void)` | 479 | Exported Function
`public: long __thiscall MethodContext::AddRef(void)` | 173 | Exported Function
`public: long __thiscall CRegistry::OpenLocalMachineKeyAndReadValue(unsigned short const *,unsigned short const *,class CHString &)` | 456 | Exported Function
`public: long __thiscall CRegistry::EnumerateAndGetValues(unsigned long &,unsigned short * &,unsigned char * &)` | 239 | Exported Function
`public: long __thiscall CRegistry::DeleteValue(unsigned short const *)` | 230 | Exported Function
`public: long __thiscall CRegistry::OpenAndEnumerateSubKeys(struct HKEY__ *,unsigned short const *,unsigned long)` | 454 | Exported Function
`public: long __thiscall CRegistry::Open(struct HKEY__ *,unsigned short const *,unsigned long)` | 453 | Exported Function
`public: int __thiscall WBEMTime::operator==(class WBEMTime const &)const ` | 113 | Exported Function
`public: int __thiscall WBEMTime::operator<=(class WBEMTime const &)const ` | 135 | Exported Function
`public: int __thiscall WBEMTime::operator>=(class WBEMTime const &)const ` | 139 | Exported Function
`public: int __thiscall WBEMTime::operator>(class WBEMTime const &)const ` | 137 | Exported Function
`public: int __thiscall WBEMTime::operator<(class WBEMTime const &)const ` | 133 | Exported Function
`public: int __thiscall WBEMTime::GetSYSTEMTIME(struct _SYSTEMTIME *)const ` | 366 | Exported Function
`public: int __thiscall WBEMTime::GetStructtm(struct tm *)const ` | 373 | Exported Function
`public: int __thiscall WBEMTime::operator!=(class WBEMTime const &)const ` | 115 | Exported Function
`public: int __thiscall WBEMTime::Gettime_t(long *)const ` | 393 | Exported Function
`public: int __thiscall WBEMTime::SetDMTF(unsigned short * const)` | 515 | Exported Function
`public: int __thiscall WBEMTimeSpan::operator>(class WBEMTimeSpan const &)const ` | 138 | Exported Function
`public: int __thiscall WBEMTimeSpan::operator==(class WBEMTimeSpan const &)const ` | 114 | Exported Function
`public: long __thiscall CFrameworkQuery::GetValuesForProp(unsigned short const *,class CHStringArray &)` | 381 | Exported Function
`public: int __thiscall WBEMTimeSpan::operator>=(class WBEMTimeSpan const &)const ` | 140 | Exported Function
`public: int __thiscall WBEMTimeSpan::operator<=(class WBEMTimeSpan const &)const ` | 136 | Exported Function
`public: int __thiscall WBEMTimeSpan::Gettime_t(long *)const ` | 394 | Exported Function
`public: int __thiscall WBEMTimeSpan::GetFILETIME(struct _FILETIME *)const ` | 324 | Exported Function
`public: int __thiscall WBEMTimeSpan::operator<(class WBEMTimeSpan const &)const ` | 134 | Exported Function
`public: int __thiscall WBEMTimeSpan::operator!=(class WBEMTimeSpan const &)const ` | 116 | Exported Function
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(struct _FILETIME const *)` | 337 | Exported Function
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(long const &)` | 336 | Exported Function
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(struct tm const *)` | 339 | Exported Function
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(struct _SYSTEMTIME const *)` | 338 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetInstancesByQueryAsynch(unsigned short const *,class Provider *,long (__stdcall*)(class Provider *,class CInstance *,class MethodContext *,void *),unsigned short const *,class MethodContext *,void *)` | 331 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetInstanceKeysByPath(unsigned short const *,class CInstance * *,class MethodContext *)` | 328 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetInstanceByPath(unsigned short const *,class CInstance * *,class MethodContext *)` | 326 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetInstancesByQuery(unsigned short const *,class TRefPointerCollection<class CInstance> *,class MethodContext *,unsigned short const *)` | 330 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetInstancePropertiesByPath(unsigned short const *,class CInstance * *,class MethodContext *,class CHStringArray &)` | 329 | Exported Function
`public: static struct IWbemServices * __stdcall CWbemProviderGlue::GetNamespaceConnection(unsigned short const *)` | 348 | Exported Function
`public: static void __stdcall CWbemProviderGlue::FrameworkLogin(unsigned short const *,class Provider *,unsigned short const *)` | 263 | Exported Function
`public: static void __stdcall CHString::Release(struct CHStringData *)` | 474 | Exported Function
`public: static void __stdcall CWbemProviderGlue::IncrementObjectCount(void)` | 397 | Exported Function
`public: static void __stdcall CWbemProviderGlue::FrameworkLogoff(unsigned short const *,unsigned short const *)` | 266 | Exported Function
`public: static unsigned short const * __stdcall CWbemProviderGlue::GetCSDVersion(void)` | 288 | Exported Function
`public: static unsigned long __stdcall CWbemProviderGlue::GetOSMajorVersion(void)` | 351 | Exported Function
`public: static struct IWbemServices * __stdcall CWbemProviderGlue::GetNamespaceConnection(unsigned short const *,class MethodContext *)` | 349 | Exported Function
`public: static unsigned short * __stdcall CObjectPathParser::GetRelativePath(unsigned short *)` | 364 | Exported Function
`public: static unsigned long __stdcall CWbemProviderGlue::GetPlatform(void)` | 358 | Exported Function
`public: static int __stdcall CWbemProviderGlue::FrameworkLoginDLL(unsigned short const *,long *)` | 265 | Exported Function
`public: static int __stdcall CWbemProviderGlue::FrameworkLoginDLL(unsigned short const *)` | 264 | Exported Function
`public: static int __stdcall CWbemProviderGlue::FrameworkLogoffDLL(unsigned short const *,long *)` | 268 | Exported Function
`public: static int __stdcall CWbemProviderGlue::FrameworkLogoffDLL(unsigned short const *)` | 267 | Exported Function
`public: static int __stdcall CObjectPathParser::Unparse(struct ParsedObjectPath *,unsigned short * *)` | 550 | Exported Function
`public: static bool __stdcall CWbemProviderGlue::SetStatusObject(class MethodContext *,unsigned short const *,unsigned short const *,long,struct tagSAFEARRAY const *,struct tagSAFEARRAY const *)` | 526 | Exported Function
`public: static bool __stdcall CWbemProviderGlue::IsDerivedFrom(unsigned short const *,unsigned short const *,class MethodContext *,unsigned short const *)` | 413 | Exported Function
`public: static class CWbemGlueFactory * __stdcall CWbemGlueFactory::Create(void)` | 206 | Exported Function
`public: static class CWbemGlueFactory * __stdcall CWbemGlueFactory::Create(long *)` | 205 | Exported Function
`public: static int __stdcall Provider::initFailed(void)` | 568 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetAllInstancesAsynch(unsigned short const *,class Provider *,long (__stdcall*)(class Provider *,class CInstance *,class MethodContext *,void *),unsigned short const *,class MethodContext *,void *)` | 277 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetAllInstances(unsigned short const *,class TRefPointerCollection<class CInstance> *,unsigned short const *,class MethodContext *)` | 276 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetEmptyInstance(unsigned short const *,class CInstance * *,unsigned short const *)` | 322 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetEmptyInstance(class MethodContext *,unsigned short const *,class CInstance * *,unsigned short const *)` | 321 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetAllDerivedInstancesAsynch(unsigned short const *,class Provider *,long (__stdcall*)(class Provider *,class CInstance *,class MethodContext *,void *),unsigned short const *,class MethodContext *,void *)` | 275 | Exported Function
`public: static long __stdcall CWbemProviderGlue::FillInstance(class CInstance *,unsigned short const *)` | 251 | Exported Function
`public: static long __stdcall CWbemProviderGlue::DecrementObjectCount(void)` | 220 | Exported Function
`public: static long __stdcall CWbemProviderGlue::GetAllDerivedInstances(unsigned short const *,class TRefPointerCollection<class CInstance> *,class MethodContext *,unsigned short const *)` | 274 | Exported Function
`public: static long __stdcall CWbemProviderGlue::FillInstance(class MethodContext *,class CInstance *)` | 252 | Exported Function
`public: int __thiscall WBEMTime::GetFILETIME(struct _FILETIME *)const ` | 323 | Exported Function
`public: class WBEMTime const & __thiscall WBEMTime::operator=(struct tm const &)` | 106 | Exported Function
`public: class WBEMTime const & __thiscall WBEMTime::operator=(struct _SYSTEMTIME const &)` | 105 | Exported Function
`public: class WBEMTimeSpan & __thiscall WBEMTimeSpan::operator=(class WBEMTimeSpan &&)` | 108 | Exported Function
`public: class WBEMTime const & __thiscall WBEMTime::operator=(unsigned short * const)` | 107 | Exported Function
`public: class WBEMTime const & __thiscall WBEMTime::operator=(struct _FILETIME const &)` | 104 | Exported Function
`public: class WBEMTime const & __thiscall WBEMTime::operator+=(class WBEMTimeSpan const &)` | 145 | Exported Function
`public: class WBEMTime __thiscall WBEMTime::operator-(class WBEMTimeSpan const &)const ` | 124 | Exported Function
`public: class WBEMTime const & __thiscall WBEMTime::operator=(long const &)` | 103 | Exported Function
`public: class WBEMTime const & __thiscall WBEMTime::operator-=(class WBEMTimeSpan const &)` | 147 | Exported Function
`public: class WBEMTimeSpan & __thiscall WBEMTimeSpan::operator=(class WBEMTimeSpan const &)` | 109 | Exported Function
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator=(struct _FILETIME const &)` | 111 | Exported Function
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator=(long const &)` | 110 | Exported Function
`public: enum ProviderLog::LogLevel __thiscall ProviderLog::IsLoggingOn(class CHString *)` | 419 | Exported Function
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator=(unsigned short * const)` | 112 | Exported Function
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator-=(class WBEMTimeSpan const &)` | 148 | Exported Function
`public: class WBEMTimeSpan __thiscall WBEMTimeSpan::operator+(class WBEMTimeSpan const &)const ` | 132 | Exported Function
`public: class WBEMTimeSpan __thiscall WBEMTime::operator-(class WBEMTime const &)` | 123 | Exported Function
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator+=(class WBEMTimeSpan const &)` | 146 | Exported Function
`public: class WBEMTimeSpan __thiscall WBEMTimeSpan::operator-(class WBEMTimeSpan const &)const ` | 125 | Exported Function
`public: class CRegistry & __thiscall CRegistry::operator=(class CRegistry const &)` | 89 | Exported Function
`public: class CreateMutexAsProcess & __thiscall CreateMutexAsProcess::operator=(class CreateMutexAsProcess const &)` | 95 | Exported Function
`public: class CThreadBase & __thiscall CThreadBase::operator=(class CThreadBase const &)` | 91 | Exported Function
`public: class CRegistrySearch & __thiscall CRegistrySearch::operator=(class CRegistrySearch const &)` | 90 | Exported Function
`public: class CObjectPathParser & __thiscall CObjectPathParser::operator=(class CObjectPathParser const &)` | 88 | Exported Function
`public: class CHString const * __thiscall CHStringArray::GetData(void)const ` | 318 | Exported Function
`public: class CHString const & __thiscall CHString::operator=(unsigned short)` | 81 | Exported Function
`public: class CInstance & __thiscall CInstance::operator=(class CInstance const &)` | 87 | Exported Function
`public: class CHStringArray & __thiscall CHStringArray::operator=(class CHStringArray const &)` | 86 | Exported Function
`public: class CWbemGlueFactory & __thiscall CWbemGlueFactory::operator=(class CWbemGlueFactory const &)` | 92 | Exported Function
`public: class WBEMTime & __thiscall WBEMTime::operator=(class WBEMTime &&)` | 101 | Exported Function
`public: class ProviderLog & __thiscall ProviderLog::operator=(class ProviderLog const &)` | 100 | Exported Function
`public: class WBEMTime __thiscall WBEMTime::operator+(class WBEMTimeSpan const &)const ` | 131 | Exported Function
`public: class WBEMTime & __thiscall WBEMTime::operator=(class WBEMTime const &)` | 102 | Exported Function
`public: class Provider & __thiscall Provider::operator=(class Provider const &)` | 99 | Exported Function
`public: class CWinMsgEvent & __thiscall CWinMsgEvent::operator=(class CWinMsgEvent const &)` | 94 | Exported Function
`public: class CWbemProviderGlue & __thiscall CWbemProviderGlue::operator=(class CWbemProviderGlue const &)` | 93 | Exported Function
`public: class MethodContext * __thiscall CInstance::GetMethodContext(void)const ` | 345 | Exported Function
`public: class MethodContext & __thiscall MethodContext::operator=(class MethodContext const &)` | 97 | Exported Function
`public: int __thiscall CRegistrySearch::SearchAndBuildList(class CHString,class CHPtrArray &,class CHString,class CHString,int,struct HKEY__ *)` | 491 | Exported Function
`public: int __thiscall CRegistrySearch::LocateKeyByNameOrValueName(struct HKEY__ *,unsigned short const *,unsigned short const *,unsigned short const * *,unsigned long,class CHString &,class CHString &)` | 434 | Exported Function
`public: int __thiscall CThreadBase::BeginWrite(unsigned long)` | 184 | Exported Function
`public: int __thiscall CThreadBase::BeginRead(unsigned long)` | 183 | Exported Function
`public: int __thiscall CRegistrySearch::FreeSearchList(int,class CHPtrArray &)` | 273 | Exported Function
`public: int __thiscall CHStringArray::GetSize(void)const ` | 368 | Exported Function
`public: int __thiscall CHStringArray::Append(class CHStringArray const &)` | 181 | Exported Function
`public: int __thiscall CObjectPathParser::Parse(unsigned short const *,struct ParsedObjectPath * *)` | 459 | Exported Function
`public: int __thiscall CHStringArray::GetUpperBound(void)const ` | 378 | Exported Function
`public: int __thiscall ParsedObjectPath::AddKeyRef(struct KeyRef *)` | 164 | Exported Function
`public: int __thiscall ParsedObjectPath::IsObject(void)` | 422 | Exported Function
`public: int __thiscall ParsedObjectPath::IsLocal(unsigned short const *)` | 418 | Exported Function
`public: int __thiscall ParsedObjectPath::SetClassName(unsigned short const *)` | 506 | Exported Function
`public: int __thiscall ParsedObjectPath::IsRelative(unsigned short const *,unsigned short const *)` | 427 | Exported Function
`public: int __thiscall ParsedObjectPath::IsInstance(void)` | 417 | Exported Function
`public: int __thiscall ParsedObjectPath::AddKeyRefEx(unsigned short const *,struct tagVARIANT const *)` | 166 | Exported Function
`public: int __thiscall ParsedObjectPath::AddKeyRef(unsigned short const *,struct tagVARIANT const *)` | 165 | Exported Function
`public: int __thiscall ParsedObjectPath::IsClass(void)` | 412 | Exported Function
`public: int __thiscall ParsedObjectPath::AddNamespace(unsigned short const *)` | 167 | Exported Function
`public: int __thiscall CHPtrArray::GetUpperBound(void)const ` | 377 | Exported Function
`public: int __thiscall CHPtrArray::GetSize(void)const ` | 367 | Exported Function
`public: int __thiscall CHString::Compare(unsigned short const *)const ` | 198 | Exported Function
`public: int __thiscall CHString::Collate(unsigned short const *)const ` | 195 | Exported Function
`public: int __thiscall CHPtrArray::Append(class CHPtrArray const &)` | 180 | Exported Function
`public: int __thiscall CFrameworkQueryEx::Is3TokenOR(unsigned short const *,unsigned short const *,struct tagVARIANT &,struct tagVARIANT &)` | 411 | Exported Function
`public: int __thiscall CAutoEvent::Signal(void)` | 538 | Exported Function
`public: int __thiscall CHPtrArray::Add(void *)` | 161 | Exported Function
`public: int __thiscall CFrameworkQueryEx::IsNTokenAnd(class CHStringArray &,class CHPtrArray &)` | 420 | Exported Function
`public: int __thiscall CHString::CompareNoCase(unsigned short const *)const ` | 199 | Exported Function
`public: int __thiscall CHString::LoadStringW(unsigned int)` | 431 | Exported Function
`public: int __thiscall CHString::IsEmpty(void)const ` | 414 | Exported Function
`public: int __thiscall CHStringArray::Add(unsigned short const *)` | 162 | Exported Function
`public: int __thiscall CHString::ReverseFind(unsigned short)const ` | 487 | Exported Function
`public: int __thiscall CHString::GetLength(void)const ` | 333 | Exported Function
`public: int __thiscall CHString::Find(unsigned short)const ` | 253 | Exported Function
`public: int __thiscall CHString::Find(unsigned short const *)const ` | 254 | Exported Function
`public: int __thiscall CHString::GetAllocLength(void)const ` | 278 | Exported Function
`public: int __thiscall CHString::FindOneOf(unsigned short const *)const ` | 255 | Exported Function
`public: struct HKEY__ * __thiscall CRegistry::GethKey(void)` | 392 | Exported Function
`public: void __cdecl CHString::FormatMessageW(unsigned int,...)` | 260 | Exported Function
`public: void __cdecl CHString::Format(unsigned short const *,...)` | 259 | Exported Function
`public: void __cdecl ProviderLog::LocalLogMessage(unsigned short const *,int,enum ProviderLog::LogLevel,unsigned short const *,...)` | 432 | Exported Function
`public: void __cdecl CHString::FormatMessageW(unsigned short const *,...)` | 261 | Exported Function
`public: void __cdecl CHString::Format(unsigned int,...)` | 258 | Exported Function
`public: void * * __thiscall CHPtrArray::GetData(void)` | 314 | Exported Function
`public: void * & __thiscall CHPtrArray::operator[](int)` | 117 | Exported Function
`public: void * __thiscall CHPtrArray::operator[](int)const ` | 118 | Exported Function
`public: void * __thiscall CHPtrArray::GetAt(int)const ` | 279 | Exported Function
`public: void __thiscall CFrameworkQuery::GetRequiredProperties(class CHStringArray &)` | 365 | Exported Function
`public: void __thiscall CHPtrArray::RemoveAll(void)` | 481 | Exported Function
`public: void __thiscall CHPtrArray::InsertAt(int,void *,int)` | 407 | Exported Function
`public: void __thiscall CHPtrArray::SetAt(int,void *)` | 493 | Exported Function
`public: void __thiscall CHPtrArray::RemoveAt(int,int)` | 483 | Exported Function
`public: void __thiscall CHPtrArray::InsertAt(int,class CHPtrArray *)` | 406 | Exported Function
`public: void __thiscall CFrameworkQueryEx::GetPropertyBitMask(class CHPtrArray const &,void *)` | 359 | Exported Function
`public: void __thiscall CFrameworkQuery::Init2(struct IWbemClassObject *)` | 398 | Exported Function
`public: void __thiscall CHPtrArray::FreeExtra(void)` | 270 | Exported Function
`public: void __thiscall CHPtrArray::Copy(class CHPtrArray const &)` | 202 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::PutClassAsync(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemObjectSink *)` | 463 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::PutClass(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemCallResult * *)` | 462 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::PutInstanceAsync(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemObjectSink *)` | 467 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::PutInstance(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemCallResult * *)` | 464 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::OpenNamespace(unsigned short * const,long,struct IWbemContext *,struct IWbemServices * *,struct IWbemCallResult * *)` | 457 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::GetObject(unsigned short * const,long,struct IWbemContext *,struct IWbemClassObject * *,struct IWbemCallResult * *)` | 352 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::ExecQueryAsync(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 249 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::Initialize(unsigned short *,long,unsigned short *,unsigned short *,struct IWbemServices *,struct IWbemContext *,struct IWbemProviderInitSink *)` | 405 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::GetObjectAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 356 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::QueryInterface(struct _GUID const &,void * *)` | 469 | Exported Function
`public: virtual unsigned long __stdcall CWbemProviderGlue::Release(void)` | 478 | Exported Function
`public: virtual unsigned long __stdcall CWbemProviderGlue::AddRef(void)` | 172 | Exported Function
`public: void * & __thiscall CHPtrArray::ElementAt(int)` | 233 | Exported Function
`public: virtual void __thiscall MethodContext::QueryPostProcess(void)` | 471 | Exported Function
`public: virtual unsigned long __stdcall CWbemGlueFactory::Release(void)` | 477 | Exported Function
`public: virtual long __thiscall CFrameworkQueryEx::InitEx(unsigned short * const,unsigned short * const,long,class CHString &)` | 404 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::QueryObjectSink(long,struct IWbemObjectSink * *)` | 470 | Exported Function
`public: virtual unsigned long __stdcall CWbemGlueFactory::AddRef(void)` | 171 | Exported Function
`public: virtual struct IWbemContext * __thiscall MethodContext::GetIWBEMContext(void)` | 325 | Exported Function
`public: void __thiscall CRegistry::Close(void)` | 193 | Exported Function
`public: void __thiscall CObjectPathParser::Free(struct ParsedObjectPath *)` | 269 | Exported Function
`public: void __thiscall CThreadBase::``default constructor closure'(void)` | 160 | Exported Function
`public: void __thiscall CRegistry::RewindSubKeys(void)` | 488 | Exported Function
`public: void __thiscall CObjectPathParser::``default constructor closure'(void)` | 159 | Exported Function
`public: void __thiscall CHStringArray::SetAt(int,unsigned short const *)` | 495 | Exported Function
`public: void __thiscall CHStringArray::RemoveAt(int,int)` | 484 | Exported Function
`public: void __thiscall CHStringArray::SetSize(int,int)` | 525 | Exported Function
`public: void __thiscall CHStringArray::SetAtGrow(int,unsigned short const *)` | 497 | Exported Function
`public: void __thiscall CThreadBase::EndRead(void)` | 237 | Exported Function
`public: void const * * __thiscall CHPtrArray::GetData(void)const ` | 315 | Exported Function
`public: void __thiscall WBEMTimeSpan::Clear(void)` | 191 | Exported Function
`void __stdcall SetCHStringResourceHandle(struct HINSTANCE__ *)` | 502 | Exported Function
`unsigned long __stdcall NormalizePath(unsigned short const *,unsigned short const *,unsigned short const *,unsigned long,class CHString &)` | 450 | Exported Function
`public: void __thiscall WBEMTime::Clear(void)` | 190 | Exported Function
`public: void __thiscall CWbemGlueFactory::Destroy(void)` | 231 | Exported Function
`public: void __thiscall CThreadBase::EndWrite(void)` | 238 | Exported Function
`public: void __thiscall ProviderLog::LocalLogMessage(unsigned short const *,unsigned short const *,int,enum ProviderLog::LogLevel)` | 433 | Exported Function
`public: void __thiscall ParsedObjectPath::ClearKeys(void)` | 192 | Exported Function
`public: void __thiscall CHString::MakeReverse(void)` | 443 | Exported Function
`public: void __thiscall CHString::MakeLower(void)` | 442 | Exported Function
`public: void __thiscall CHString::Release(void)` | 473 | Exported Function
`public: void __thiscall CHString::MakeUpper(void)` | 444 | Exported Function
`public: void __thiscall CHString::FreeExtra(void)` | 271 | Exported Function
`public: void __thiscall CHPtrArray::SetSize(int,int)` | 524 | Exported Function
`public: void __thiscall CHPtrArray::SetAtGrow(int,void *)` | 496 | Exported Function
`public: void __thiscall CHString::FormatV(unsigned short const *,char *)` | 262 | Exported Function
`public: void __thiscall CHString::Empty(void)` | 235 | Exported Function
`public: void __thiscall CHString::ReleaseBuffer(int)` | 480 | Exported Function
`public: void __thiscall CHStringArray::InsertAt(int,class CHStringArray *)` | 408 | Exported Function
`public: void __thiscall CHStringArray::FreeExtra(void)` | 272 | Exported Function
`public: void __thiscall CHStringArray::RemoveAll(void)` | 482 | Exported Function
`public: void __thiscall CHStringArray::InsertAt(int,unsigned short const *,int)` | 409 | Exported Function
`public: void __thiscall CHStringArray::Copy(class CHStringArray const &)` | 203 | Exported Function
`public: void __thiscall CHString::TrimLeft(void)` | 541 | Exported Function
`public: void __thiscall CHString::SetAt(int,unsigned short)` | 494 | Exported Function
`public: void __thiscall CHString::UnlockBuffer(void)` | 547 | Exported Function
`public: void __thiscall CHString::TrimRight(void)` | 542 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::ExecQuery(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 247 | Exported Function
`public: unsigned long __thiscall CRegistry::GetLongestSubKeySize(void)` | 341 | Exported Function
`public: unsigned long __thiscall CRegistry::GetLongestClassStringSize(void)` | 340 | Exported Function
`public: unsigned long __thiscall CRegistry::GetLongestValueName(void)` | 343 | Exported Function
`public: unsigned long __thiscall CRegistry::GetLongestValueData(void)` | 342 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyValue(unsigned short const *,void *,unsigned long *)` | 309 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyPath(class CHString &)` | 306 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyName(class CHString &)` | 305 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyValue(unsigned short const *,unsigned long &)` | 307 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyValue(unsigned short const *,class CHString &)` | 308 | Exported Function
`public: unsigned long __thiscall CRegistry::GetValueCount(void)` | 379 | Exported Function
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(unsigned short const *,class CHStringArray &)` | 513 | Exported Function
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(unsigned short const *,class CHString &)` | 512 | Exported Function
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValueExpand(struct HKEY__ *,unsigned short const *,class CHString &)` | 514 | Exported Function
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(unsigned short const *,unsigned long &)` | 511 | Exported Function
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(struct HKEY__ *,unsigned short const *,unsigned long &)` | 508 | Exported Function
`public: unsigned long __thiscall CRegistry::OpenCurrentUser(unsigned short const *,unsigned long)` | 455 | Exported Function
`public: unsigned long __thiscall CRegistry::NextSubKey(void)` | 448 | Exported Function
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHStringArray &)` | 510 | Exported Function
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHString &)` | 509 | Exported Function
`public: unsigned long __thiscall CAutoEvent::Wait(unsigned long)` | 559 | Exported Function
`public: unsigned __int64 __thiscall WBEMTimeSpan::GetTime(void)const ` | 375 | Exported Function
`public: unsigned long __thiscall CRegistry::DeleteCurrentKeyValue(unsigned short const *)` | 224 | Exported Function
`public: unsigned long __thiscall CRegistry::DeleteCurrentKeyValue(struct HKEY__ *,unsigned short const *)` | 223 | Exported Function
`public: unsigned __int64 __thiscall WBEMTime::GetTime(void)const ` | 374 | Exported Function
`public: struct IWbemClassObject * __thiscall MethodContext::GetStatusObject(void)` | 371 | Exported Function
`public: struct IWbemClassObject * __thiscall CInstance::GetClassObjectInterface(void)` | 290 | Exported Function
`public: struct ParsedObjectPath & __thiscall ParsedObjectPath::operator=(struct ParsedObjectPath const &)` | 98 | Exported Function
`public: struct KeyRef & __thiscall KeyRef::operator=(struct KeyRef const &)` | 96 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentBinaryKeyValue(struct HKEY__ *,unsigned short const *,unsigned char *,unsigned long *)` | 293 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(unsigned short const *,class CHStringArray &)` | 301 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(unsigned short const *,class CHString &)` | 300 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyCount(void)` | 304 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(unsigned short const *,unsigned long &)` | 299 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(struct HKEY__ *,unsigned short const *,unsigned long &)` | 296 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentBinaryKeyValue(unsigned short const *,unsigned char *,unsigned long *)` | 295 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentBinaryKeyValue(unsigned short const *,class CHString &)` | 294 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHStringArray &)` | 298 | Exported Function
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHString &)` | 297 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::CancelAsyncRequest(long)` | 186 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::CancelAsyncCall(struct IWbemObjectSink *)` | 185 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::CreateClassEnumAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 208 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::CreateClassEnum(unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 207 | Exported Function
`public: virtual long __stdcall CWbemGlueFactory::QueryInterface(struct _GUID const &,void * *)` | 468 | Exported Function
`public: virtual bool __thiscall CFrameworkQueryEx::IsExtended(void)` | 415 | Exported Function
`public: virtual __thiscall ProviderLog::~ProviderLog(void)` | 73 | Exported Function
`public: virtual long __stdcall CWbemGlueFactory::LockServer(int)` | 439 | Exported Function
`public: virtual long __stdcall CWbemGlueFactory::CreateInstance(struct IUnknown *,struct _GUID const &,void * *)` | 209 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::CreateInstanceEnum(unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 210 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::ExecMethodAsync(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemClassObject *,struct IWbemObjectSink *)` | 244 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::ExecMethod(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemClassObject *,struct IWbemClassObject * *,struct IWbemCallResult * *)` | 241 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::ExecNotificationQueryAsync(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 246 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::ExecNotificationQuery(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 245 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::DeleteInstanceAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 228 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::DeleteClass(unsigned short * const,long,struct IWbemContext *,struct IWbemCallResult * *)` | 221 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::CreateInstanceEnumAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 212 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::DeleteInstance(unsigned short * const,long,struct IWbemContext *,struct IWbemCallResult * *)` | 225 | Exported Function
`public: virtual long __stdcall CWbemProviderGlue::DeleteClassAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 222 | Exported Function
`public: unsigned short * __thiscall ParsedObjectPath::GetKeyString(void)` | 332 | Exported Function
`public: unsigned short * __thiscall CRegistry::GetClassNameW(void)` | 289 | Exported Function
`public: unsigned short * __thiscall ParsedObjectPath::GetParentNamespacePart(void)` | 357 | Exported Function
`public: unsigned short * __thiscall ParsedObjectPath::GetNamespacePart(void)` | 350 | Exported Function
`public: unsigned short * __thiscall CHString::LockBuffer(void)` | 436 | Exported Function
`public: unsigned short * __thiscall CHString::AllocSysString(void)const ` | 179 | Exported Function
`public: unsigned short * __thiscall CFrameworkQuery::GetQueryClassName(void)` | 363 | Exported Function
`public: unsigned short * __thiscall CHString::GetBufferSetLength(int)` | 285 | Exported Function
`public: unsigned short * __thiscall CHString::GetBuffer(int)` | 284 | Exported Function
`public: unsigned short * __thiscall WBEMTime::GetBSTR(void)const ` | 282 | Exported Function
`public: virtual __thiscall CThreadBase::~CThreadBase(void)` | 64 | Exported Function
`public: virtual __thiscall CInstance::~CInstance(void)` | 60 | Exported Function
`public: virtual __thiscall Provider::~Provider(void)` | 72 | Exported Function
`public: virtual __thiscall MethodContext::~MethodContext(void)` | 70 | Exported Function
`public: unsigned short __thiscall CHString::operator[](int)const ` | 119 | Exported Function
`public: unsigned short * __thiscall WBEMTime::GetDMTFNonNtfs(void)const ` | 311 | Exported Function
`public: unsigned short * __thiscall WBEMTime::GetDMTF(int)const ` | 310 | Exported Function
`public: unsigned short __thiscall CHString::GetAt(int)const ` | 280 | Exported Function
`public: unsigned short * __thiscall WBEMTimeSpan::GetBSTR(void)const ` | 283 | Exported Function
`private: unsigned long __thiscall CRegistry::GetCurrentRawSubKeyValue(unsigned short const *,void *,unsigned long *,unsigned long *)` | 303 | Exported Function
`private: unsigned long __thiscall CRegistry::GetCurrentRawKeyValue(struct HKEY__ *,unsigned short const *,void *,unsigned long *,unsigned long *)` | 302 | Exported Function
`private: void __thiscall CFrameworkQuery::Reset(void)` | 486 | Exported Function
`private: unsigned long __thiscall CRegistry::OpenSubKey(void)` | 458 | Exported Function
`private: struct IWbemServices * __stdcall CWbemProviderGlue::InternalGetNamespaceConnection(unsigned short const *)` | 410 | Exported Function
`private: static void __stdcall CWinMsgEvent::WindowsDispatch(void)` | 560 | Exported Function
`private: static void __stdcall CWinMsgEvent::DestroyMsgWindow(void)` | 232 | Exported Function
`private: struct IWbemClassObject * __thiscall Provider::GetClassObjectInterface(class MethodContext *)` | 291 | Exported Function
`private: static void __stdcall Provider::InitComputerName(void)` | 403 | Exported Function
`private: void __thiscall CObjectPathParser::Empty(void)` | 236 | Exported Function
`private: void __thiscall CThreadBase::Unlock(void)` | 546 | Exported Function
`private: void __thiscall CThreadBase::Lock(void)` | 435 | Exported Function
`private: void __thiscall CWbemProviderGlue::FlushAll(void)` | 257 | Exported Function
`private: void __thiscall CWbemProviderGlue::AddFlushPtr(void *)` | 163 | Exported Function
`private: void __thiscall CRegistrySearch::CheckAndAddToList(class CRegistry *,class CHString,class CHString,class CHPtrArray &,class CHString,class CHString,int)` | 187 | Exported Function
`private: void __thiscall CRegistry::CloseSubKey(void)` | 194 | Exported Function
`private: void __thiscall CObjectPathParser::Zero(void)` | 561 | Exported Function
`private: void __thiscall CRegistry::SetDefaultValues(void)` | 519 | Exported Function
`private: void __thiscall CRegistry::PrepareToReOpen(void)` | 461 | Exported Function
`private: static unsigned long CWbemProviderGlue::s_dwMajorVersion` | 605 | Exported Function
`private: static unsigned long CRegistry::s_dwPlatform` | 606 | Exported Function
`private: static unsigned short * CWbemProviderGlue::s_wstrCSDVersion` | 613 | Exported Function
`private: static unsigned long CWbemProviderGlue::s_dwPlatform` | 607 | Exported Function
`private: static unsigned long __stdcall CWinMsgEvent::dwThreadProc(void *)` | 564 | Exported Function
`private: static struct HWND__ * CWinMsgEvent::mg_hWnd` | 583 | Exported Function
`private: static struct HWND__ * __stdcall CWinMsgEvent::CreateMsgWindow(void)` | 214 | Exported Function
`private: static struct IWbemClassObject * CWbemProviderGlue::m_pStatusObject` | 577 | Exported Function
`private: static struct IWbemClassObject * __stdcall CWbemProviderGlue::GetStatusObject(class MethodContext *,unsigned short const *)` | 370 | Exported Function
`private: static void * CWinMsgEvent::mg_hDevNotify` | 581 | Exported Function
`private: static void __stdcall CWbemProviderGlue::UnlockFactoryMap(void)` | 548 | Exported Function
`private: static void __stdcall CWbemProviderGlue::UnInit(void)` | 543 | Exported Function
`private: static void __stdcall CWinMsgEvent::CreateMsgProvider(void)` | 213 | Exported Function
`private: static void __stdcall CWbemProviderGlue::UnlockProviderMap(void)` | 549 | Exported Function
`private: static void __stdcall CWbemProviderGlue::LockProviderMap(void)` | 438 | Exported Function
`private: static void __stdcall CWbemProviderGlue::GetComputerNameW(class CHString &)` | 292 | Exported Function
`private: static void * CWinMsgEvent::mg_hThreadPumpHandle` | 582 | Exported Function
`private: static void __stdcall CWbemProviderGlue::LockFactoryMap(void)` | 437 | Exported Function
`private: static void __stdcall CWbemProviderGlue::Init(void)` | 402 | Exported Function
`protected: virtual long __thiscall Provider::EnumerateInstances(class MethodContext *,long)` | 240 | Exported Function
`protected: virtual long __thiscall Provider::DeleteInstance(class CInstance const &,long)` | 227 | Exported Function
`protected: virtual long __thiscall Provider::ExecQuery(class MethodContext *,class CFrameworkQuery &,long)` | 248 | Exported Function
`protected: virtual long __thiscall Provider::ExecMethod(class CInstance const &,unsigned short * const,class CInstance *,class CInstance *,long)` | 243 | Exported Function
`protected: unsigned long __thiscall CFrameworkQuery::IsInList(class CHStringArray const &,unsigned short const *)` | 416 | Exported Function
`protected: static void __stdcall CWbemProviderGlue::AddToFactoryMap(class CWbemGlueFactory const *,long *)` | 174 | Exported Function
`protected: static long __stdcall CWbemProviderGlue::IncrementMapCount(long *)` | 395 | Exported Function
`protected: struct CHStringData * __thiscall CHString::GetData(void)const ` | 316 | Exported Function
`protected: static void __stdcall CWbemProviderGlue::RemoveFromFactoryMap(class CWbemGlueFactory const *)` | 485 | Exported Function
`protected: virtual long __thiscall Provider::GetObject(class CInstance *,long)` | 354 | Exported Function
`protected: virtual long __thiscall Provider::ValidatePutInstanceFlags(long)` | 557 | Exported Function
`protected: virtual long __thiscall Provider::ValidateMethodFlags(long)` | 556 | Exported Function
`protected: virtual void __thiscall CThreadBase::OnFinalRelease(void)` | 452 | Exported Function
`protected: virtual long __thiscall Provider::ValidateQueryFlags(long)` | 558 | Exported Function
`protected: virtual long __thiscall Provider::ValidateGetObjFlags(long)` | 554 | Exported Function
`protected: virtual long __thiscall Provider::PutInstance(class CInstance const &,long)` | 466 | Exported Function
`protected: virtual long __thiscall Provider::GetObject(class CInstance *,long,class CFrameworkQuery &)` | 355 | Exported Function
`protected: virtual long __thiscall Provider::ValidateEnumerationFlags(long)` | 552 | Exported Function
`protected: virtual long __thiscall Provider::ValidateDeletionFlags(long)` | 551 | Exported Function
`protected: class CHString const & __thiscall Provider::GetLocalComputerName(void)` | 334 | Exported Function
`protected: class CHString const & __thiscall CFrameworkQuery::GetNamespace(void)` | 346 | Exported Function
`protected: class CHString const & __thiscall Provider::GetProviderName(void)` | 361 | Exported Function
`protected: class CHString const & __thiscall Provider::GetNamespace(void)` | 347 | Exported Function
`protected: class CHString __thiscall Provider::MakeLocalPath(class CHString const &)` | 441 | Exported Function
`protected: bool __thiscall CWinMsgEvent::UnRegisterMessage(unsigned int,int)` | 545 | Exported Function
`private: void __thiscall ProviderLog::CheckFileSize(union _LARGE_INTEGER &,class CHString const &)` | 188 | Exported Function
`protected: bool __thiscall Provider::SetCreationClassName(class CInstance *)` | 507 | Exported Function
`protected: bool __thiscall Provider::GetLocalInstancePath(class CInstance const *,class CHString &)` | 335 | Exported Function
`protected: class CInstance * __thiscall Provider::CreateNewInstance(class MethodContext *)` | 215 | Exported Function
`protected: static long __stdcall CWbemProviderGlue::DecrementMapCount(class CWbemGlueFactory const *)` | 219 | Exported Function
`protected: static long * __stdcall CWbemProviderGlue::GetMapCountPtr(class CWbemGlueFactory const *)` | 344 | Exported Function
`protected: static long __stdcall CWbemProviderGlue::IncrementMapCount(class CWbemGlueFactory const *)` | 396 | Exported Function
`protected: static long __stdcall CWbemProviderGlue::DecrementMapCount(long *)` | 218 | Exported Function
`protected: static int __stdcall CHString::SafeStrlen(unsigned short const *)` | 490 | Exported Function
`protected: int __thiscall CHString::LoadStringW(unsigned int,unsigned short *,unsigned int)` | 430 | Exported Function
`protected: int __thiscall CFrameworkQuery::IsReference(unsigned short const *)` | 426 | Exported Function
`protected: long __thiscall Provider::ValidateFlags(long,enum Provider::FlagDefs)` | 553 | Exported Function
`protected: long __thiscall Provider::Commit(class CInstance *,bool)` | 197 | Exported Function
`private: static long CWbemProviderGlue::s_lObjects` | 610 | Exported Function
`private: int __thiscall CObjectPathParser::keyref_term(void)` | 573 | Exported Function
`private: int __thiscall CObjectPathParser::keyref_list(void)` | 572 | Exported Function
`private: int __thiscall CObjectPathParser::ns_list(void)` | 594 | Exported Function
`private: int __thiscall CObjectPathParser::NextToken(void)` | 449 | Exported Function
`private: int __thiscall CObjectPathParser::keyref(void)` | 571 | Exported Function
`private: int __thiscall CObjectPathParser::ident_becomes_class(void)` | 566 | Exported Function
`private: int __thiscall CObjectPathParser::begin_parse(void)` | 562 | Exported Function
`private: int __thiscall CObjectPathParser::key_const(void)` | 570 | Exported Function
`private: int __thiscall CObjectPathParser::ident_becomes_ns(void)` | 567 | Exported Function
`private: int __thiscall CObjectPathParser::ns_list_rest(void)` | 595 | Exported Function
`private: int __thiscall Provider::SetKeyFromParsedObjectPath(class CInstance *,struct ParsedObjectPath *)` | 521 | Exported Function
`private: int __thiscall CObjectPathParser::propname(void)` | 601 | Exported Function
`private: long __thiscall CRegistry::myRegCreateKeyEx(struct HKEY__ *,unsigned short const *,unsigned long,unsigned short *,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES * const,struct HKEY__ * *,unsigned long *)` | 585 | Exported Function
`private: int __thiscall Provider::ValidateIMOSPointer(void)` | 555 | Exported Function
`private: int __thiscall CObjectPathParser::optional_objref(void)` | 600 | Exported Function
`private: int __thiscall CObjectPathParser::ns_or_server(void)` | 597 | Exported Function
`private: int __thiscall CObjectPathParser::ns_or_class(void)` | 596 | Exported Function
`private: int __thiscall CObjectPathParser::objref_rest(void)` | 599 | Exported Function
`private: int __thiscall CObjectPathParser::objref(void)` | 598 | Exported Function
`class CHString __stdcall operator+(unsigned short,class CHString const &)` | 129 | Exported Function
`class CHString __stdcall operator+(unsigned short const *,class CHString const &)` | 130 | Exported Function
`const CFrameworkQueryEx::``vftable'` | 149 | Exported Function
`class ProviderLog captainsLog` | 563 | Exported Function
`class CHString __stdcall operator+(class CHString const &,unsigned short)` | 127 | Exported Function
`class CCritSec g_cs` | 565 | Exported Function
`_DoCmd@16` | 614 | Exported Function
`class CHString __stdcall operator+(class CHString const &,unsigned short const *)` | 128 | Exported Function
`class CHString __stdcall operator+(class CHString const &,class CHString const &)` | 126 | Exported Function
`const CInstance::``vftable'` | 150 | Exported Function
`const Provider::``vftable'` | 157 | Exported Function
`const MethodContext::``vftable'` | 156 | Exported Function
`private: class CWbemProviderGlue * __thiscall MethodContext::GetProviderGlue(void)` | 360 | Exported Function
`const ProviderLog::``vftable'` | 158 | Exported Function
`const CWinMsgEvent::``vftable'` | 155 | Exported Function
`const CWbemGlueFactory::``vftable'` | 152 | Exported Function
`const CThreadBase::``vftable'` | 151 | Exported Function
`const CWbemProviderGlue::``vftable'{for ``IWbemServices'}` | 154 | Exported Function
`const CWbemProviderGlue::``vftable'{for ``IWbemProviderInit'}` | 153 | Exported Function
`private: static class Provider * __stdcall CWbemProviderGlue::SearchMapForProvider(unsigned short const *,unsigned short const *)` | 492 | Exported Function
`private: static class Provider * __stdcall CWbemProviderGlue::AddProviderToMap(unsigned short const *,unsigned short const *,class Provider *)` | 168 | Exported Function
`private: static class std::map<void const *,long *,struct std::less<void const *>,class std::allocator<long *> > CWbemProviderGlue::s_factorymap` | 609 | Exported Function
`private: static class std::map<class CHString,void *,struct std::less<class CHString>,class std::allocator<void *> > CWbemProviderGlue::s_providersmap` | 611 | Exported Function
`private: static class CHString Provider::s_strComputerName` | 612 | Exported Function
`private: static class CCritSec CWbemProviderGlue::s_csProviderMap` | 604 | Exported Function
`private: static class CCritSec CWbemProviderGlue::s_csFactoryMap` | 603 | Exported Function
`private: static class CCritSec CWinMsgEvent::mg_csWindowLock` | 580 | Exported Function
`private: static class CCritSec CWinMsgEvent::mg_csMapLock` | 579 | Exported Function
`private: static class std::multimap<unsigned int,class CWinMsgEvent *,struct std::less<unsigned int>,class std::allocator<class CWinMsgEvent *> > CWinMsgEvent::mg_oSinkMap` | 584 | Exported Function
`private: static long __stdcall CWbemProviderGlue::CheckImpersonationLevel(void)` | 189 | Exported Function
`private: static int Provider::initFailed_` | 569 | Exported Function
`private: static long __stdcall CWinMsgEvent::MsgWndProc(struct HWND__ *,unsigned int,unsigned int,long)` | 447 | Exported Function
`private: static long __stdcall CWbemProviderGlue::GetInstanceFromCIMOM(unsigned short const *,unsigned short const *,class MethodContext *,class CInstance * *)` | 327 | Exported Function
`private: static int CWbemProviderGlue::s_bInitted` | 602 | Exported Function
`private: static int __stdcall CRegistry::SetPlatformID(void)` | 523 | Exported Function
`private: static class std::set<void *,struct std::less<void *>,class std::allocator<void *> > CWbemProviderGlue::m_FlushPtrs` | 574 | Exported Function
`private: static int CRegistry::s_fPlatformSet` | 608 | Exported Function
`private: static int __stdcall CWinMsgEvent::CtrlHandlerRoutine(unsigned long)` | 217 | Exported Function
`private: long __thiscall CRegistry::myRegQueryValueEx(struct HKEY__ *,unsigned short const *,unsigned long *,unsigned long *,unsigned char *,unsigned long *)` | 592 | Exported Function
`private: long __thiscall CRegistry::myRegQueryInfoKey(struct HKEY__ *,unsigned short *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,struct _FILETIME *)` | 591 | Exported Function
`private: long __thiscall CWbemProviderGlue::NullOutUnsetProperties(struct IWbemClassObject *,struct IWbemClassObject * *,struct tagVARIANT const &)` | 451 | Exported Function
`private: long __thiscall CRegistry::myRegSetValueEx(struct HKEY__ *,unsigned short const *,unsigned long,unsigned long,unsigned char const *,unsigned long)` | 593 | Exported Function
`private: long __thiscall CRegistry::myRegOpenKeyEx(struct HKEY__ *,unsigned short const *,unsigned long,unsigned long,struct HKEY__ * *)` | 590 | Exported Function
`private: long __thiscall CRegistry::myRegDeleteValue(struct HKEY__ *,unsigned short const *)` | 587 | Exported Function
`private: long __thiscall CRegistry::myRegDeleteKey(struct HKEY__ *,unsigned short const *)` | 586 | Exported Function
`private: long __thiscall CRegistry::myRegEnumValue(struct HKEY__ *,unsigned long,unsigned short *,unsigned long *,unsigned long *,unsigned long *,unsigned char *,unsigned long *)` | 589 | Exported Function
`private: long __thiscall CRegistry::myRegEnumKey(struct HKEY__ *,unsigned long,unsigned short *,unsigned long)` | 588 | Exported Function
`private: long __thiscall CWbemProviderGlue::PreProcessPutInstanceParms(struct IWbemClassObject *,struct IWbemClassObject * *,struct IWbemContext *)` | 460 | Exported Function
`private: static class CAutoEvent CWinMsgEvent::mg_aeCreateWindow` | 578 | Exported Function
`private: long __thiscall Provider::PutInstance(struct IWbemClassObject *,long,class MethodContext *)` | 465 | Exported Function
`private: static class CCritSec CWbemProviderGlue::m_csStatusObject` | 576 | Exported Function
`private: static class CCritSec CWbemProviderGlue::m_csFlushPtrs` | 575 | Exported Function
`private: long __thiscall Provider::GetObject(struct ParsedObjectPath *,class MethodContext *,long)` | 353 | Exported Function
`private: long __thiscall Provider::DeleteInstance(struct ParsedObjectPath *,long,class MethodContext *)` | 226 | Exported Function
`private: long __thiscall Provider::CreateInstanceEnum(class MethodContext *,long)` | 211 | Exported Function
`private: long __thiscall Provider::ExecuteQuery(class MethodContext *,class CFrameworkQuery &,long)` | 250 | Exported Function
`private: long __thiscall Provider::ExecMethod(struct ParsedObjectPath *,unsigned short *,long,class CInstance *,class CInstance *,class MethodContext *)` | 242 | Exported Function
`protected: virtual void __thiscall Provider::Flush(void)` | 256 | Exported Function
`public: bool __thiscall CInstance::Setbool(unsigned short const *,bool)` | 537 | Exported Function
`public: bool __thiscall CInstance::IsNull(unsigned short const *)const ` | 421 | Exported Function
`public: bool __thiscall CInstance::SetCharSplat(unsigned short const *,char const *)` | 505 | Exported Function
`public: bool __thiscall CInstance::SetByte(unsigned short const *,unsigned char)` | 498 | Exported Function
`public: bool __thiscall CInstance::GetWORD(unsigned short const *,unsigned short &)const ` | 390 | Exported Function
`public: bool __thiscall CInstance::GetWBEMINT64(unsigned short const *,class CHString &)const ` | 386 | Exported Function
`public: bool __thiscall CInstance::GetWBEMINT64(unsigned short const *,__int64 &)const ` | 387 | Exported Function
`public: bool __thiscall CInstance::GetWCHAR(unsigned short const *,unsigned short * *)const ` | 389 | Exported Function
`public: bool __thiscall CInstance::GetWBEMINT64(unsigned short const *,unsigned __int64 &)const ` | 388 | Exported Function
`public: bool __thiscall CInstance::SetCharSplat(unsigned short const *,unsigned long)` | 504 | Exported Function
`public: bool __thiscall CInstance::SetDWORD(unsigned short const *,unsigned long)` | 517 | Exported Function
`public: bool __thiscall CInstance::SetDOUBLE(unsigned short const *,double)` | 516 | Exported Function
`public: bool __thiscall CInstance::SetNull(unsigned short const *)` | 522 | Exported Function
`public: bool __thiscall CInstance::SetEmbeddedObject(unsigned short const *,class CInstance &)` | 520 | Exported Function
`public: bool __thiscall CInstance::SetDateTime(unsigned short const *,class WBEMTime const &)` | 518 | Exported Function
`public: bool __thiscall CInstance::SetCHString(unsigned short const *,char const *)` | 501 | Exported Function
`public: bool __thiscall CInstance::SetCharSplat(unsigned short const *,unsigned short const *)` | 503 | Exported Function
`public: bool __thiscall CInstance::SetCHString(unsigned short const *,unsigned short const *)` | 499 | Exported Function
`public: bool __thiscall CInstance::SetCHString(unsigned short const *,class CHString const &)` | 500 | Exported Function
`public: bool __thiscall CFrameworkQuery::KeysOnly(void)` | 428 | Exported Function
`public: bool __thiscall CFrameworkQuery::IsPropertyRequired(unsigned short const *)` | 425 | Exported Function
`public: bool __thiscall CInstance::GetByte(unsigned short const *,unsigned char &)const ` | 286 | Exported Function
`public: bool __thiscall CInstance::Getbool(unsigned short const *,bool &)const ` | 391 | Exported Function
`public: bool __thiscall CFrameworkQuery::AllPropertiesAreRequired(void)` | 175 | Exported Function
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(struct _FILETIME const &)` | 49 | Exported Function
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(long const &)` | 48 | Exported Function
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(void)` | 52 | Exported Function
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(unsigned short * const)` | 51 | Exported Function
`public: bool __thiscall CInstance::GetCHString(unsigned short const *,class CHString &)const ` | 287 | Exported Function
`public: bool __thiscall CInstance::GetTimeSpan(unsigned short const *,class WBEMTimeSpan &)const ` | 376 | Exported Function
`public: bool __thiscall CInstance::GetStringArray(unsigned short const *,struct tagSAFEARRAY * &)const ` | 372 | Exported Function
`public: bool __thiscall CInstance::GetWBEMINT16(unsigned short const *,short &)const ` | 385 | Exported Function
`public: bool __thiscall CInstance::GetVariant(unsigned short const *,struct tagVARIANT &)const ` | 384 | Exported Function
`public: bool __thiscall CInstance::GetStatus(unsigned short const *,bool &,unsigned short &)const ` | 369 | Exported Function
`public: bool __thiscall CInstance::GetDOUBLE(unsigned short const *,double &)const ` | 312 | Exported Function
`public: bool __thiscall CInstance::GetDateTime(unsigned short const *,class WBEMTime &)const ` | 319 | Exported Function
`public: bool __thiscall CInstance::GetEmbeddedObject(unsigned short const *,class CInstance * *,class MethodContext *)const ` | 320 | Exported Function
`public: bool __thiscall CInstance::GetDWORD(unsigned short const *,unsigned long &)const ` | 313 | Exported Function
`public: class CHString __thiscall CHStringArray::GetAt(int)const ` | 281 | Exported Function
`public: class CHString __thiscall CHString::SpanIncluding(unsigned short const *)const ` | 540 | Exported Function
`public: class CHString const & __thiscall CFrameworkQuery::GetQuery(void)` | 362 | Exported Function
`public: class CHString __thiscall CHStringArray::operator[](int)const ` | 121 | Exported Function
`public: class CHString __thiscall CHString::SpanExcluding(unsigned short const *)const ` | 539 | Exported Function
`public: class CHString __thiscall CHString::Mid(int)const ` | 445 | Exported Function
`public: class CHString __thiscall CHString::Left(int)const ` | 429 | Exported Function
`public: class CHString __thiscall CHString::Right(int)const ` | 489 | Exported Function
`public: class CHString __thiscall CHString::Mid(int,int)const ` | 446 | Exported Function
`public: class CHString const & __thiscall CHString::operator+=(char)` | 142 | Exported Function
`public: class CHString const & __thiscall CHString::operator=(class CHString const &)` | 79 | Exported Function
`public: class CHString const & __thiscall CHString::operator=(class CHString *)` | 82 | Exported Function
`public: class CHString const & __thiscall CHString::operator=(unsigned short const *)` | 85 | Exported Function
`public: class CHString const & __thiscall CHString::operator=(unsigned char const *)` | 84 | Exported Function
`public: class CHString const & __thiscall CHString::operator=(char)` | 80 | Exported Function
`public: class CHString const & __thiscall CHString::operator+=(unsigned short const *)` | 144 | Exported Function
`public: class CHString const & __thiscall CHString::operator+=(class CHString const &)` | 141 | Exported Function
`public: class CHString const & __thiscall CHString::operator=(char const *)` | 83 | Exported Function
`public: class CHString const & __thiscall CHString::operator+=(unsigned short)` | 143 | Exported Function
`public: bool __thiscall CInstance::SetWBEMINT64(unsigned short const *,unsigned __int64)` | 534 | Exported Function
`public: bool __thiscall CInstance::SetWBEMINT64(unsigned short const *,class CHString const &)` | 532 | Exported Function
`public: bool __thiscall CInstance::SetWORD(unsigned short const *,unsigned short)` | 536 | Exported Function
`public: bool __thiscall CInstance::SetWCHARSplat(unsigned short const *,unsigned short const *)` | 535 | Exported Function
`public: bool __thiscall CInstance::SetWBEMINT64(unsigned short const *,__int64)` | 533 | Exported Function
`public: bool __thiscall CInstance::SetTimeSpan(unsigned short const *,class WBEMTimeSpan const &)` | 529 | Exported Function
`public: bool __thiscall CInstance::SetStringArray(unsigned short const *,struct tagSAFEARRAY const &)` | 528 | Exported Function
`public: bool __thiscall CInstance::SetWBEMINT16(unsigned short const *,short const &)` | 531 | Exported Function
`public: bool __thiscall CInstance::SetVariant(unsigned short const *,struct tagVARIANT const &)` | 530 | Exported Function
`public: bool __thiscall MethodContext::SetStatusObject(struct IWbemClassObject *)` | 527 | Exported Function
`public: class CHString & __thiscall CHStringArray::ElementAt(int)` | 234 | Exported Function
`public: class CHPtrArray & __thiscall CHPtrArray::operator=(class CHPtrArray const &)` | 78 | Exported Function
`public: class CHString * __thiscall CHStringArray::GetData(void)` | 317 | Exported Function
`public: class CHString & __thiscall CHStringArray::operator[](int)` | 120 | Exported Function
`public: class CFrameworkQueryEx & __thiscall CFrameworkQueryEx::operator=(class CFrameworkQueryEx const &)` | 77 | Exported Function
`public: bool __thiscall WBEMTimeSpan::IsOk(void)const ` | 424 | Exported Function
`public: bool __thiscall WBEMTime::IsOk(void)const ` | 423 | Exported Function
`public: class CFrameworkQuery & __thiscall CFrameworkQuery::operator=(class CFrameworkQuery const &)` | 76 | Exported Function
`public: class CAutoEvent & __thiscall CAutoEvent::operator=(class CAutoEvent const &)` | 75 | Exported Function
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(int,int,int,int,int,int,int)` | 50 | Exported Function
`public: __thiscall CHString::CHString(unsigned short const *,int)` | 12 | Exported Function
`public: __thiscall CHString::CHString(unsigned short const *)` | 11 | Exported Function
`public: __thiscall CHString::CHString(void)` | 13 | Exported Function
`public: __thiscall CHString::CHString(unsigned short,int)` | 8 | Exported Function
`public: __thiscall CHString::CHString(unsigned char const *)` | 10 | Exported Function
`public: __thiscall CHPtrArray::~CHPtrArray(void)` | 57 | Exported Function
`public: __thiscall CHPtrArray::CHPtrArray(void)` | 6 | Exported Function
`public: __thiscall CHString::CHString(class CHString const &)` | 7 | Exported Function
`public: __thiscall CHString::CHString(char const *)` | 9 | Exported Function
`public: __thiscall CHString::operator unsigned short const *(void)const ` | 122 | Exported Function
`public: __thiscall CObjectPathParser::~CObjectPathParser(void)` | 61 | Exported Function
`public: __thiscall CObjectPathParser::CObjectPathParser(enum ObjectParserFlags)` | 17 | Exported Function
`public: __thiscall CreateMutexAsProcess::~CreateMutexAsProcess(void)` | 68 | Exported Function
`public: __thiscall CreateMutexAsProcess::CreateMutexAsProcess(unsigned short const *)` | 32 | Exported Function
`public: __thiscall CInstance::CInstance(struct IWbemClassObject *,class MethodContext *)` | 16 | Exported Function
`public: __thiscall CHStringArray::CHStringArray(void)` | 14 | Exported Function
`public: __thiscall CHString::~CHString(void)` | 58 | Exported Function
`public: __thiscall CInstance::CInstance(class CInstance const &)` | 15 | Exported Function
`public: __thiscall CHStringArray::~CHStringArray(void)` | 59 | Exported Function
`protected: void __thiscall CHString::CopyBeforeWrite(void)` | 204 | Exported Function
`protected: void __thiscall CHString::ConcatInPlace(int,unsigned short const *)` | 201 | Exported Function
`protected: void __thiscall CInstance::LogError(unsigned short const *,unsigned short const *,unsigned short const *,long)const ` | 440 | Exported Function
`protected: void __thiscall CHString::Init(void)` | 401 | Exported Function
`protected: void __thiscall CHString::ConcatCopy(int,unsigned short const *,int,unsigned short const *)` | 200 | Exported Function
`protected: void __thiscall CHString::AllocBuffer(int)` | 177 | Exported Function
`protected: void __thiscall CHString::AllocBeforeWrite(int)` | 176 | Exported Function
`protected: void __thiscall CHString::AssignCopy(int,unsigned short const *)` | 182 | Exported Function
`protected: void __thiscall CHString::AllocCopy(class CHString &,int,int,int)const ` | 178 | Exported Function
`protected: void __thiscall CWinMsgEvent::RegisterForMessage(unsigned int,int)` | 472 | Exported Function
`public: __thiscall CFrameworkQueryEx::CFrameworkQueryEx(class CFrameworkQueryEx const &)` | 4 | Exported Function
`public: __thiscall CFrameworkQuery::~CFrameworkQuery(void)` | 55 | Exported Function
`public: __thiscall CFrameworkQueryEx::~CFrameworkQueryEx(void)` | 56 | Exported Function
`public: __thiscall CFrameworkQueryEx::CFrameworkQueryEx(void)` | 5 | Exported Function
`public: __thiscall CFrameworkQuery::CFrameworkQuery(void)` | 3 | Exported Function
`public: __thiscall CAutoEvent::CAutoEvent(void)` | 1 | Exported Function
`protected: void __thiscall CWinMsgEvent::UnRegisterAllMessages(void)` | 544 | Exported Function
`public: __thiscall CFrameworkQuery::CFrameworkQuery(class CFrameworkQuery const &)` | 2 | Exported Function
`public: __thiscall CAutoEvent::~CAutoEvent(void)` | 54 | Exported Function
`public: __thiscall ParsedObjectPath::~ParsedObjectPath(void)` | 71 | Exported Function
`public: __thiscall ParsedObjectPath::ParsedObjectPath(void)` | 37 | Exported Function
`public: __thiscall Provider::Provider(unsigned short const *,unsigned short const *)` | 39 | Exported Function
`public: __thiscall Provider::Provider(class Provider const &)` | 38 | Exported Function
`public: __thiscall MethodContext::MethodContext(struct IWbemContext *,class CWbemProviderGlue *)` | 36 | Exported Function
`public: __thiscall KeyRef::KeyRef(void)` | 34 | Exported Function
`public: __thiscall KeyRef::KeyRef(unsigned short const *,struct tagVARIANT const *)` | 33 | Exported Function
`public: __thiscall MethodContext::MethodContext(class MethodContext const &)` | 35 | Exported Function
`public: __thiscall KeyRef::~KeyRef(void)` | 69 | Exported Function
`public: __thiscall ProviderLog::ProviderLog(class ProviderLog const &)` | 40 | Exported Function
`public: __thiscall WBEMTime::WBEMTime(struct tm const &)` | 45 | Exported Function
`public: __thiscall WBEMTime::WBEMTime(struct _SYSTEMTIME const &)` | 44 | Exported Function
`public: __thiscall WBEMTime::WBEMTime(void)` | 47 | Exported Function
`public: __thiscall WBEMTime::WBEMTime(unsigned short * const)` | 46 | Exported Function
`public: __thiscall WBEMTime::WBEMTime(struct _FILETIME const &)` | 43 | Exported Function
`public: __thiscall std::_Lockit::_Lockit(void)` | 53 | Exported Function
`public: __thiscall ProviderLog::ProviderLog(void)` | 41 | Exported Function
`public: __thiscall WBEMTime::WBEMTime(long const &)` | 42 | Exported Function
`public: __thiscall std::_Lockit::~_Lockit(void)` | 74 | Exported Function
`public: __thiscall CThreadBase::CThreadBase(class CThreadBase const &)` | 22 | Exported Function
`public: __thiscall CRegistrySearch::~CRegistrySearch(void)` | 63 | Exported Function
`public: __thiscall CWbemGlueFactory::CWbemGlueFactory(class CWbemGlueFactory const &)` | 24 | Exported Function
`public: __thiscall CThreadBase::CThreadBase(enum CThreadBase::THREAD_SAFETY_MECHANISM)` | 23 | Exported Function
`public: __thiscall CRegistrySearch::CRegistrySearch(void)` | 21 | Exported Function
`public: __thiscall CRegistry::CRegistry(void)` | 19 | Exported Function
`public: __thiscall CRegistry::CRegistry(class CRegistry const &)` | 18 | Exported Function
`public: __thiscall CRegistrySearch::CRegistrySearch(class CRegistrySearch const &)` | 20 | Exported Function
`public: __thiscall CRegistry::~CRegistry(void)` | 62 | Exported Function
`public: __thiscall CWbemGlueFactory::CWbemGlueFactory(long *)` | 25 | Exported Function
`public: __thiscall CWinMsgEvent::CWinMsgEvent(class CWinMsgEvent const &)` | 30 | Exported Function
`public: __thiscall CWbemProviderGlue::~CWbemProviderGlue(void)` | 66 | Exported Function
`public: __thiscall CWinMsgEvent::~CWinMsgEvent(void)` | 67 | Exported Function
`public: __thiscall CWinMsgEvent::CWinMsgEvent(void)` | 31 | Exported Function
`public: __thiscall CWbemProviderGlue::CWbemProviderGlue(void)` | 29 | Exported Function
`public: __thiscall CWbemGlueFactory::~CWbemGlueFactory(void)` | 65 | Exported Function
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
* VirusTotal Link: https://www.virustotal.com/gui/file/efad3d5181333faa5fb523e6d62d8a13d1d31303e5cd5157bed94b81b4fdfe23/detection/





MIT License. Copyright (c) 2020 Strontic.


