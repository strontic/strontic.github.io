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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`_DoCmd@16` | 614 (0x266) | Exported Function | 0x1000d0d0 | 0x0000d0d0
`public: long __thiscall CFrameworkQuery::Init(unsigned short * const,unsigned short * const,long,class CHString &)` | 400 (0x190) | Exported Function | 0x10007de0 | 0x00007de0
`public: long __thiscall CFrameworkQueryEx::GetValuesForProp(unsigned short const *,class std::vector<class _variant_t,class std::allocator<class _variant_t> > &)` | 383 (0x17f) | Exported Function | 0x100094b0 | 0x000094b0
`public: long __thiscall CFrameworkQueryEx::GetValuesForProp(unsigned short const *,class std::vector<int,class std::allocator<int> > &)` | 382 (0x17e) | Exported Function | 0x10009400 | 0x00009400
`public: long __thiscall CInstance::AddRef(void)` | 169 (0xa9) | Exported Function | 0x10009d10 | 0x00009d10
`public: long __thiscall CInstance::Commit(void)` | 196 (0xc4) | Exported Function | 0x10009e40 | 0x00009e40
`public: long __thiscall CInstance::Release(void)` | 475 (0x1db) | Exported Function | 0x10009d20 | 0x00009d20
`public: long __thiscall CRegistry::CreateOpen(struct HKEY__ *,unsigned short const *,unsigned short *,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES *,unsigned long *)` | 216 (0xd8) | Exported Function | 0x1001b5a0 | 0x0001b5a0
`public: long __thiscall CRegistry::DeleteKey(class CHString *)` | 229 (0xe5) | Exported Function | 0x1001b650 | 0x0001b650
`public: long __thiscall CRegistry::DeleteValue(unsigned short const *)` | 230 (0xe6) | Exported Function | 0x1001b680 | 0x0001b680
`public: long __thiscall CRegistry::EnumerateAndGetValues(unsigned long &,unsigned short * &,unsigned char * &)` | 239 (0xef) | Exported Function | 0x1001b330 | 0x0001b330
`public: long __thiscall CRegistry::Open(struct HKEY__ *,unsigned short const *,unsigned long)` | 453 (0x1c5) | Exported Function | 0x1001b500 | 0x0001b500
`public: long __thiscall CRegistry::OpenAndEnumerateSubKeys(struct HKEY__ *,unsigned short const *,unsigned long)` | 454 (0x1c6) | Exported Function | 0x1001b6a0 | 0x0001b6a0
`public: long __thiscall CRegistry::OpenLocalMachineKeyAndReadValue(unsigned short const *,unsigned short const *,class CHString &)` | 456 (0x1c8) | Exported Function | 0x1001b6c0 | 0x0001b6c0
`public: long __thiscall CThreadBase::AddRef(void)` | 170 (0xaa) | Exported Function | 0x1000c020 | 0x0000c020
`public: long __thiscall CThreadBase::Release(void)` | 476 (0x1dc) | Exported Function | 0x1000d3d0 | 0x0000d3d0
`public: long __thiscall CFrameworkQuery::Init(struct ParsedObjectPath *,struct IWbemContext *,unsigned short const *,class CHString &)` | 399 (0x18f) | Exported Function | 0x10008000 | 0x00008000
`public: long __thiscall MethodContext::AddRef(void)` | 173 (0xad) | Exported Function | 0x1000c020 | 0x0000c020
`public: long __thiscall CFrameworkQuery::GetValuesForProp(unsigned short const *,class std::vector<class _bstr_t,class std::allocator<class _bstr_t> > &)` | 380 (0x17c) | Exported Function | 0x10008580 | 0x00008580
`public: int __thiscall WBEMTimeSpan::operator>=(class WBEMTimeSpan const &)const ` | 140 (0x8c) | Exported Function | 0x10005ce0 | 0x00005ce0
`public: int __thiscall WBEMTime::Gettime_t(long *)const ` | 393 (0x189) | Exported Function | 0x1001a0d0 | 0x0001a0d0
`public: int __thiscall WBEMTime::operator!=(class WBEMTime const &)const ` | 115 (0x73) | Exported Function | 0x10005c20 | 0x00005c20
`public: int __thiscall WBEMTime::operator<(class WBEMTime const &)const ` | 133 (0x85) | Exported Function | 0x10005c50 | 0x00005c50
`public: int __thiscall WBEMTime::operator<=(class WBEMTime const &)const ` | 135 (0x87) | Exported Function | 0x10005c80 | 0x00005c80
`public: int __thiscall WBEMTime::operator==(class WBEMTime const &)const ` | 113 (0x71) | Exported Function | 0x10005bf0 | 0x00005bf0
`public: int __thiscall WBEMTime::operator>(class WBEMTime const &)const ` | 137 (0x89) | Exported Function | 0x10005cb0 | 0x00005cb0
`public: int __thiscall WBEMTime::operator>=(class WBEMTime const &)const ` | 139 (0x8b) | Exported Function | 0x10005ce0 | 0x00005ce0
`public: int __thiscall WBEMTime::SetDMTF(unsigned short * const)` | 515 (0x203) | Exported Function | 0x1001a230 | 0x0001a230
`public: int __thiscall WBEMTimeSpan::GetFILETIME(struct _FILETIME *)const ` | 324 (0x144) | Exported Function | 0x1001a890 | 0x0001a890
`public: int __thiscall WBEMTimeSpan::Gettime_t(long *)const ` | 394 (0x18a) | Exported Function | 0x1001a850 | 0x0001a850
`public: int __thiscall WBEMTimeSpan::operator!=(class WBEMTimeSpan const &)const ` | 116 (0x74) | Exported Function | 0x10005c20 | 0x00005c20
`public: int __thiscall WBEMTimeSpan::operator<(class WBEMTimeSpan const &)const ` | 134 (0x86) | Exported Function | 0x10005c50 | 0x00005c50
`public: int __thiscall WBEMTimeSpan::operator<=(class WBEMTimeSpan const &)const ` | 136 (0x88) | Exported Function | 0x10005c80 | 0x00005c80
`public: int __thiscall WBEMTimeSpan::operator==(class WBEMTimeSpan const &)const ` | 114 (0x72) | Exported Function | 0x10005bf0 | 0x00005bf0
`public: int __thiscall WBEMTimeSpan::operator>(class WBEMTimeSpan const &)const ` | 138 (0x8a) | Exported Function | 0x10005cb0 | 0x00005cb0
`public: long __thiscall CFrameworkQuery::GetValuesForProp(unsigned short const *,class CHStringArray &)` | 381 (0x17d) | Exported Function | 0x10008390 | 0x00008390
`public: int __thiscall WBEMTime::GetSYSTEMTIME(struct _SYSTEMTIME *)const ` | 366 (0x16e) | Exported Function | 0x1001a1a0 | 0x0001a1a0
`public: long __thiscall MethodContext::Release(void)` | 479 (0x1df) | Exported Function | 0x1000c030 | 0x0000c030
`public: static bool __stdcall CWbemProviderGlue::SetStatusObject(class MethodContext *,unsigned short const *,unsigned short const *,long,struct tagSAFEARRAY const *,struct tagSAFEARRAY const *)` | 526 (0x20e) | Exported Function | 0x1000dbc0 | 0x0000dbc0
`public: static long __stdcall CWbemProviderGlue::GetInstancePropertiesByPath(unsigned short const *,class CInstance * *,class MethodContext *,class CHStringArray &)` | 329 (0x149) | Exported Function | 0x10011150 | 0x00011150
`public: static long __stdcall CWbemProviderGlue::GetInstancesByQuery(unsigned short const *,class TRefPointerCollection<class CInstance> *,class MethodContext *,unsigned short const *)` | 330 (0x14a) | Exported Function | 0x10010720 | 0x00010720
`public: static long __stdcall CWbemProviderGlue::GetInstancesByQueryAsynch(unsigned short const *,class Provider *,long (__stdcall*)(class Provider *,class CInstance *,class MethodContext *,void *),unsigned short const *,class MethodContext *,void *)` | 331 (0x14b) | Exported Function | 0x10011cc0 | 0x00011cc0
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(long const &)` | 336 (0x150) | Exported Function | 0x10019bc0 | 0x00019bc0
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(struct _FILETIME const *)` | 337 (0x151) | Exported Function | 0x10019c40 | 0x00019c40
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(struct _SYSTEMTIME const *)` | 338 (0x152) | Exported Function | 0x10019c90 | 0x00019c90
`public: static long __stdcall WBEMTime::GetLocalOffsetForDate(struct tm const *)` | 339 (0x153) | Exported Function | 0x10019c00 | 0x00019c00
`public: static struct IWbemServices * __stdcall CWbemProviderGlue::GetNamespaceConnection(unsigned short const *)` | 348 (0x15c) | Exported Function | 0x10010160 | 0x00010160
`public: static struct IWbemServices * __stdcall CWbemProviderGlue::GetNamespaceConnection(unsigned short const *,class MethodContext *)` | 349 (0x15d) | Exported Function | 0x10012210 | 0x00012210
`public: static unsigned long __stdcall CWbemProviderGlue::GetOSMajorVersion(void)` | 351 (0x15f) | Exported Function | 0x10006410 | 0x00006410
`public: static unsigned long __stdcall CWbemProviderGlue::GetPlatform(void)` | 358 (0x166) | Exported Function | 0x10006420 | 0x00006420
`public: static unsigned short * __stdcall CObjectPathParser::GetRelativePath(unsigned short *)` | 364 (0x16c) | Exported Function | 0x10014960 | 0x00014960
`public: static unsigned short const * __stdcall CWbemProviderGlue::GetCSDVersion(void)` | 288 (0x120) | Exported Function | 0x10006430 | 0x00006430
`public: static void __stdcall CHString::Release(struct CHStringData *)` | 474 (0x1da) | Exported Function | 0x10018bf0 | 0x00018bf0
`public: static void __stdcall CWbemProviderGlue::FrameworkLogin(unsigned short const *,class Provider *,unsigned short const *)` | 263 (0x107) | Exported Function | 0x100102c0 | 0x000102c0
`public: static long __stdcall CWbemProviderGlue::GetInstanceKeysByPath(unsigned short const *,class CInstance * *,class MethodContext *)` | 328 (0x148) | Exported Function | 0x10010ff0 | 0x00010ff0
`public: static bool __stdcall CWbemProviderGlue::IsDerivedFrom(unsigned short const *,unsigned short const *,class MethodContext *,unsigned short const *)` | 413 (0x19d) | Exported Function | 0x10010ab0 | 0x00010ab0
`public: static long __stdcall CWbemProviderGlue::GetInstanceByPath(unsigned short const *,class CInstance * *,class MethodContext *)` | 326 (0x146) | Exported Function | 0x100113a0 | 0x000113a0
`public: static long __stdcall CWbemProviderGlue::GetEmptyInstance(class MethodContext *,unsigned short const *,class CInstance * *,unsigned short const *)` | 321 (0x141) | Exported Function | 0x10010d90 | 0x00010d90
`public: static class CWbemGlueFactory * __stdcall CWbemGlueFactory::Create(long *)` | 205 (0xcd) | Exported Function | 0x100074a0 | 0x000074a0
`public: static class CWbemGlueFactory * __stdcall CWbemGlueFactory::Create(void)` | 206 (0xce) | Exported Function | 0x10007460 | 0x00007460
`public: static int __stdcall CObjectPathParser::Unparse(struct ParsedObjectPath *,unsigned short * *)` | 550 (0x226) | Exported Function | 0x10014670 | 0x00014670
`public: static int __stdcall CWbemProviderGlue::FrameworkLoginDLL(unsigned short const *)` | 264 (0x108) | Exported Function | 0x10011a30 | 0x00011a30
`public: static int __stdcall CWbemProviderGlue::FrameworkLoginDLL(unsigned short const *,long *)` | 265 (0x109) | Exported Function | 0x10012240 | 0x00012240
`public: static int __stdcall CWbemProviderGlue::FrameworkLogoffDLL(unsigned short const *)` | 267 (0x10b) | Exported Function | 0x10011a50 | 0x00011a50
`public: static int __stdcall CWbemProviderGlue::FrameworkLogoffDLL(unsigned short const *,long *)` | 268 (0x10c) | Exported Function | 0x10012290 | 0x00012290
`public: static int __stdcall Provider::initFailed(void)` | 568 (0x238) | Exported Function | 0x1000c400 | 0x0000c400
`public: static long __stdcall CWbemProviderGlue::DecrementObjectCount(void)` | 220 (0xdc) | Exported Function | 0x10011ac0 | 0x00011ac0
`public: static long __stdcall CWbemProviderGlue::FillInstance(class CInstance *,unsigned short const *)` | 251 (0xfb) | Exported Function | 0x10010ed0 | 0x00010ed0
`public: static long __stdcall CWbemProviderGlue::FillInstance(class MethodContext *,class CInstance *)` | 252 (0xfc) | Exported Function | 0x10010f70 | 0x00010f70
`public: static long __stdcall CWbemProviderGlue::GetAllDerivedInstances(unsigned short const *,class TRefPointerCollection<class CInstance> *,class MethodContext *,unsigned short const *)` | 274 (0x112) | Exported Function | 0x10010640 | 0x00010640
`public: static long __stdcall CWbemProviderGlue::GetAllDerivedInstancesAsynch(unsigned short const *,class Provider *,long (__stdcall*)(class Provider *,class CInstance *,class MethodContext *,void *),unsigned short const *,class MethodContext *,void *)` | 275 (0x113) | Exported Function | 0x100106b0 | 0x000106b0
`public: static long __stdcall CWbemProviderGlue::GetAllInstances(unsigned short const *,class TRefPointerCollection<class CInstance> *,unsigned short const *,class MethodContext *)` | 276 (0x114) | Exported Function | 0x10010560 | 0x00010560
`public: static long __stdcall CWbemProviderGlue::GetAllInstancesAsynch(unsigned short const *,class Provider *,long (__stdcall*)(class Provider *,class CInstance *,class MethodContext *,void *),unsigned short const *,class MethodContext *,void *)` | 277 (0x115) | Exported Function | 0x100105d0 | 0x000105d0
`public: static long __stdcall CWbemProviderGlue::GetEmptyInstance(unsigned short const *,class CInstance * *,unsigned short const *)` | 322 (0x142) | Exported Function | 0x10010ca0 | 0x00010ca0
`public: int __thiscall WBEMTime::GetStructtm(struct tm *)const ` | 373 (0x175) | Exported Function | 0x1001a150 | 0x0001a150
`public: int __thiscall WBEMTime::GetFILETIME(struct _FILETIME *)const ` | 323 (0x143) | Exported Function | 0x1001a1f0 | 0x0001a1f0
`public: int __thiscall ParsedObjectPath::SetClassName(unsigned short const *)` | 506 (0x1fa) | Exported Function | 0x100140e0 | 0x000140e0
`public: class WBEMTime const & __thiscall WBEMTime::operator-=(class WBEMTimeSpan const &)` | 147 (0x93) | Exported Function | 0x10019ff0 | 0x00019ff0
`public: class WBEMTime const & __thiscall WBEMTime::operator=(long const &)` | 103 (0x67) | Exported Function | 0x10019ec0 | 0x00019ec0
`public: class WBEMTime const & __thiscall WBEMTime::operator=(struct _FILETIME const &)` | 104 (0x68) | Exported Function | 0x10005db0 | 0x00005db0
`public: class WBEMTime const & __thiscall WBEMTime::operator=(struct _SYSTEMTIME const &)` | 105 (0x69) | Exported Function | 0x10019e30 | 0x00019e30
`public: class WBEMTime const & __thiscall WBEMTime::operator=(struct tm const &)` | 106 (0x6a) | Exported Function | 0x10019e70 | 0x00019e70
`public: class WBEMTime const & __thiscall WBEMTime::operator=(unsigned short * const)` | 107 (0x6b) | Exported Function | 0x10019db0 | 0x00019db0
`public: class WBEMTimeSpan & __thiscall WBEMTimeSpan::operator=(class WBEMTimeSpan &&)` | 108 (0x6c) | Exported Function | 0x10005d50 | 0x00005d50
`public: class WBEMTimeSpan & __thiscall WBEMTimeSpan::operator=(class WBEMTimeSpan const &)` | 109 (0x6d) | Exported Function | 0x10005d50 | 0x00005d50
`public: class WBEMTimeSpan __thiscall WBEMTime::operator-(class WBEMTime const &)` | 123 (0x7b) | Exported Function | 0x10019f90 | 0x00019f90
`public: class WBEMTimeSpan __thiscall WBEMTimeSpan::operator+(class WBEMTimeSpan const &)const ` | 132 (0x84) | Exported Function | 0x10019f00 | 0x00019f00
`public: class WBEMTimeSpan __thiscall WBEMTimeSpan::operator-(class WBEMTimeSpan const &)const ` | 125 (0x7d) | Exported Function | 0x10019f90 | 0x00019f90
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator+=(class WBEMTimeSpan const &)` | 146 (0x92) | Exported Function | 0x10019f50 | 0x00019f50
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator-=(class WBEMTimeSpan const &)` | 148 (0x94) | Exported Function | 0x10019ff0 | 0x00019ff0
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator=(long const &)` | 110 (0x6e) | Exported Function | 0x1001a740 | 0x0001a740
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator=(struct _FILETIME const &)` | 111 (0x6f) | Exported Function | 0x1001a640 | 0x0001a640
`public: class WBEMTime const & __thiscall WBEMTime::operator+=(class WBEMTimeSpan const &)` | 145 (0x91) | Exported Function | 0x10019f50 | 0x00019f50
`public: class WBEMTimeSpan const & __thiscall WBEMTimeSpan::operator=(unsigned short * const)` | 112 (0x70) | Exported Function | 0x1001a690 | 0x0001a690
`public: class WBEMTime __thiscall WBEMTime::operator-(class WBEMTimeSpan const &)const ` | 124 (0x7c) | Exported Function | 0x10019f90 | 0x00019f90
`public: class WBEMTime & __thiscall WBEMTime::operator=(class WBEMTime const &)` | 102 (0x66) | Exported Function | 0x10005d50 | 0x00005d50
`public: class CHStringArray & __thiscall CHStringArray::operator=(class CHStringArray const &)` | 86 (0x56) | Exported Function | 0x10005ba0 | 0x00005ba0
`public: class CInstance & __thiscall CInstance::operator=(class CInstance const &)` | 87 (0x57) | Exported Function | 0x100065c0 | 0x000065c0
`public: class CObjectPathParser & __thiscall CObjectPathParser::operator=(class CObjectPathParser const &)` | 88 (0x58) | Exported Function | 0x100058d0 | 0x000058d0
`public: class CreateMutexAsProcess & __thiscall CreateMutexAsProcess::operator=(class CreateMutexAsProcess const &)` | 95 (0x5f) | Exported Function | 0x10007830 | 0x00007830
`public: class CRegistry & __thiscall CRegistry::operator=(class CRegistry const &)` | 89 (0x59) | Exported Function | 0x10006840 | 0x00006840
`public: class CRegistrySearch & __thiscall CRegistrySearch::operator=(class CRegistrySearch const &)` | 90 (0x5a) | Exported Function | 0x10006960 | 0x00006960
`public: class CThreadBase & __thiscall CThreadBase::operator=(class CThreadBase const &)` | 91 (0x5b) | Exported Function | 0x10005e60 | 0x00005e60
`public: class CWbemGlueFactory & __thiscall CWbemGlueFactory::operator=(class CWbemGlueFactory const &)` | 92 (0x5c) | Exported Function | 0x10006570 | 0x00006570
`public: class CWbemProviderGlue & __thiscall CWbemProviderGlue::operator=(class CWbemProviderGlue const &)` | 93 (0x5d) | Exported Function | 0x10006490 | 0x00006490
`public: class CWinMsgEvent & __thiscall CWinMsgEvent::operator=(class CWinMsgEvent const &)` | 94 (0x5e) | Exported Function | 0x10015e50 | 0x00015e50
`public: class MethodContext & __thiscall MethodContext::operator=(class MethodContext const &)` | 97 (0x61) | Exported Function | 0x10005fc0 | 0x00005fc0
`public: class MethodContext * __thiscall CInstance::GetMethodContext(void)const ` | 345 (0x159) | Exported Function | 0x1000bc80 | 0x0000bc80
`public: class Provider & __thiscall Provider::operator=(class Provider const &)` | 99 (0x63) | Exported Function | 0x100062d0 | 0x000062d0
`public: class ProviderLog & __thiscall ProviderLog::operator=(class ProviderLog const &)` | 100 (0x64) | Exported Function | 0x10006a00 | 0x00006a00
`public: class WBEMTime & __thiscall WBEMTime::operator=(class WBEMTime &&)` | 101 (0x65) | Exported Function | 0x10005d50 | 0x00005d50
`public: class WBEMTime __thiscall WBEMTime::operator+(class WBEMTimeSpan const &)const ` | 131 (0x83) | Exported Function | 0x10019f00 | 0x00019f00
`public: enum ProviderLog::LogLevel __thiscall ProviderLog::IsLoggingOn(class CHString *)` | 419 (0x1a3) | Exported Function | 0x10006d50 | 0x00006d50
`public: int __thiscall CAutoEvent::Signal(void)` | 538 (0x21a) | Exported Function | 0x10015e30 | 0x00015e30
`public: int __thiscall CFrameworkQueryEx::Is3TokenOR(unsigned short const *,unsigned short const *,struct tagVARIANT &,struct tagVARIANT &)` | 411 (0x19b) | Exported Function | 0x10009110 | 0x00009110
`public: int __thiscall CObjectPathParser::Parse(unsigned short const *,struct ParsedObjectPath * *)` | 459 (0x1cb) | Exported Function | 0x10014a80 | 0x00014a80
`public: int __thiscall CRegistrySearch::FreeSearchList(int,class CHPtrArray &)` | 273 (0x111) | Exported Function | 0x1001c690 | 0x0001c690
`public: int __thiscall CRegistrySearch::LocateKeyByNameOrValueName(struct HKEY__ *,unsigned short const *,unsigned short const *,unsigned short const * *,unsigned long,class CHString &,class CHString &)` | 434 (0x1b2) | Exported Function | 0x1001c6f0 | 0x0001c6f0
`public: int __thiscall CRegistrySearch::SearchAndBuildList(class CHString,class CHPtrArray &,class CHString,class CHString,int,struct HKEY__ *)` | 491 (0x1eb) | Exported Function | 0x1001c470 | 0x0001c470
`public: int __thiscall CThreadBase::BeginRead(unsigned long)` | 183 (0xb7) | Exported Function | 0x10005f40 | 0x00005f40
`public: int __thiscall CThreadBase::BeginWrite(unsigned long)` | 184 (0xb8) | Exported Function | 0x10005f40 | 0x00005f40
`public: int __thiscall ParsedObjectPath::AddKeyRef(struct KeyRef *)` | 164 (0xa4) | Exported Function | 0x10014530 | 0x00014530
`public: int __thiscall ParsedObjectPath::AddKeyRef(unsigned short const *,struct tagVARIANT const *)` | 165 (0xa5) | Exported Function | 0x100144a0 | 0x000144a0
`public: int __thiscall ParsedObjectPath::AddKeyRefEx(unsigned short const *,struct tagVARIANT const *)` | 166 (0xa6) | Exported Function | 0x10014210 | 0x00014210
`public: int __thiscall ParsedObjectPath::AddNamespace(unsigned short const *)` | 167 (0xa7) | Exported Function | 0x100141a0 | 0x000141a0
`public: int __thiscall ParsedObjectPath::IsClass(void)` | 412 (0x19c) | Exported Function | 0x10014120 | 0x00014120
`public: int __thiscall ParsedObjectPath::IsInstance(void)` | 417 (0x1a1) | Exported Function | 0x10014150 | 0x00014150
`public: int __thiscall ParsedObjectPath::IsLocal(unsigned short const *)` | 418 (0x1a2) | Exported Function | 0x100159d0 | 0x000159d0
`public: int __thiscall ParsedObjectPath::IsObject(void)` | 422 (0x1a6) | Exported Function | 0x10014180 | 0x00014180
`public: int __thiscall ParsedObjectPath::IsRelative(unsigned short const *,unsigned short const *)` | 427 (0x1ab) | Exported Function | 0x10015880 | 0x00015880
`public: int __thiscall CHStringArray::GetUpperBound(void)const ` | 378 (0x17a) | Exported Function | 0x10005af0 | 0x00005af0
`public: int __thiscall CHStringArray::GetSize(void)const ` | 368 (0x170) | Exported Function | 0x10005ae0 | 0x00005ae0
`public: int __thiscall CHStringArray::Append(class CHStringArray const &)` | 181 (0xb5) | Exported Function | 0x1001aa90 | 0x0001aa90
`public: int __thiscall CHStringArray::Add(unsigned short const *)` | 162 (0xa2) | Exported Function | 0x10005b80 | 0x00005b80
`public: int __thiscall CFrameworkQueryEx::IsNTokenAnd(class CHStringArray &,class CHPtrArray &)` | 420 (0x1a4) | Exported Function | 0x10009260 | 0x00009260
`public: int __thiscall CHPtrArray::Add(void *)` | 161 (0xa1) | Exported Function | 0x1001b200 | 0x0001b200
`public: int __thiscall CHPtrArray::Append(class CHPtrArray const &)` | 180 (0xb4) | Exported Function | 0x1001af10 | 0x0001af10
`public: int __thiscall CHPtrArray::GetSize(void)const ` | 367 (0x16f) | Exported Function | 0x10005ae0 | 0x00005ae0
`public: int __thiscall CHPtrArray::GetUpperBound(void)const ` | 377 (0x179) | Exported Function | 0x10005af0 | 0x00005af0
`public: int __thiscall CHString::Collate(unsigned short const *)const ` | 195 (0xc3) | Exported Function | 0x10005ac0 | 0x00005ac0
`public: int __thiscall CHString::Compare(unsigned short const *)const ` | 198 (0xc6) | Exported Function | 0x100191d0 | 0x000191d0
`public: static void __stdcall CWbemProviderGlue::FrameworkLogoff(unsigned short const *,unsigned short const *)` | 266 (0x10a) | Exported Function | 0x10010360 | 0x00010360
`public: int __thiscall CHString::CompareNoCase(unsigned short const *)const ` | 199 (0xc7) | Exported Function | 0x10005aa0 | 0x00005aa0
`public: int __thiscall CHString::Find(unsigned short)const ` | 253 (0xfd) | Exported Function | 0x100193e0 | 0x000193e0
`public: int __thiscall CHString::FindOneOf(unsigned short const *)const ` | 255 (0xff) | Exported Function | 0x10019410 | 0x00019410
`public: int __thiscall CHString::GetAllocLength(void)const ` | 278 (0x116) | Exported Function | 0x100059f0 | 0x000059f0
`public: int __thiscall CHString::GetLength(void)const ` | 333 (0x14d) | Exported Function | 0x10005990 | 0x00005990
`public: int __thiscall CHString::IsEmpty(void)const ` | 414 (0x19e) | Exported Function | 0x100059a0 | 0x000059a0
`public: int __thiscall CHString::LoadStringW(unsigned int)` | 431 (0x1af) | Exported Function | 0x100198d0 | 0x000198d0
`public: int __thiscall CHString::ReverseFind(unsigned short)const ` | 487 (0x1e7) | Exported Function | 0x10019440 | 0x00019440
`public: int __thiscall CHString::Find(unsigned short const *)const ` | 254 (0xfe) | Exported Function | 0x10019470 | 0x00019470
`public: static void __stdcall CWbemProviderGlue::IncrementObjectCount(void)` | 397 (0x18d) | Exported Function | 0x10011a70 | 0x00011a70
`public: struct HKEY__ * __thiscall CRegistry::GethKey(void)` | 392 (0x188) | Exported Function | 0x10005ae0 | 0x00005ae0
`public: struct IWbemClassObject * __thiscall CInstance::GetClassObjectInterface(void)` | 290 (0x122) | Exported Function | 0x10009e70 | 0x00009e70
`public: void * * __thiscall CHPtrArray::GetData(void)` | 314 (0x13a) | Exported Function | 0x100059e0 | 0x000059e0
`public: void * __thiscall CHPtrArray::GetAt(int)const ` | 279 (0x117) | Exported Function | 0x1001b1c0 | 0x0001b1c0
`public: void * __thiscall CHPtrArray::operator[](int)const ` | 118 (0x76) | Exported Function | 0x1001b1c0 | 0x0001b1c0
`public: void __cdecl CHString::Format(unsigned int,...)` | 258 (0x102) | Exported Function | 0x10007380 | 0x00007380
`public: void __cdecl CHString::Format(unsigned short const *,...)` | 259 (0x103) | Exported Function | 0x100197b0 | 0x000197b0
`public: void __cdecl CHString::FormatMessageW(unsigned int,...)` | 260 (0x104) | Exported Function | 0x10007380 | 0x00007380
`public: void __cdecl CHString::FormatMessageW(unsigned short const *,...)` | 261 (0x105) | Exported Function | 0x100197e0 | 0x000197e0
`public: void __cdecl ProviderLog::LocalLogMessage(unsigned short const *,int,enum ProviderLog::LogLevel,unsigned short const *,...)` | 432 (0x1b0) | Exported Function | 0x100072e0 | 0x000072e0
`public: void __thiscall CFrameworkQuery::GetRequiredProperties(class CHStringArray &)` | 365 (0x16d) | Exported Function | 0x100087b0 | 0x000087b0
`public: void __thiscall CFrameworkQuery::Init2(struct IWbemClassObject *)` | 398 (0x18e) | Exported Function | 0x100087e0 | 0x000087e0
`public: void __thiscall CFrameworkQueryEx::GetPropertyBitMask(class CHPtrArray const &,void *)` | 359 (0x167) | Exported Function | 0x10009700 | 0x00009700
`public: void __thiscall CHPtrArray::Copy(class CHPtrArray const &)` | 202 (0xca) | Exported Function | 0x1001af60 | 0x0001af60
`public: void __thiscall CHPtrArray::FreeExtra(void)` | 270 (0x10e) | Exported Function | 0x1001ab40 | 0x0001ab40
`public: void __thiscall CHPtrArray::InsertAt(int,class CHPtrArray *)` | 406 (0x196) | Exported Function | 0x1001b150 | 0x0001b150
`public: void __thiscall CHPtrArray::InsertAt(int,void *,int)` | 407 (0x197) | Exported Function | 0x1001afd0 | 0x0001afd0
`public: void * & __thiscall CHPtrArray::operator[](int)` | 117 (0x75) | Exported Function | 0x10005b60 | 0x00005b60
`public: void __thiscall CHPtrArray::RemoveAll(void)` | 481 (0x1e1) | Exported Function | 0x1001b1a0 | 0x0001b1a0
`public: void * & __thiscall CHPtrArray::ElementAt(int)` | 233 (0xe9) | Exported Function | 0x10005b60 | 0x00005b60
`public: virtual unsigned long __stdcall CWbemProviderGlue::Release(void)` | 478 (0x1de) | Exported Function | 0x1000da10 | 0x0000da10
`public: virtual long __stdcall CWbemProviderGlue::GetObject(unsigned short * const,long,struct IWbemContext *,struct IWbemClassObject * *,struct IWbemCallResult * *)` | 352 (0x160) | Exported Function | 0x100063c0 | 0x000063c0
`public: virtual long __stdcall CWbemProviderGlue::GetObjectAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 356 (0x164) | Exported Function | 0x1000e820 | 0x0000e820
`public: virtual long __stdcall CWbemProviderGlue::Initialize(unsigned short *,long,unsigned short *,unsigned short *,struct IWbemServices *,struct IWbemContext *,struct IWbemProviderInitSink *)` | 405 (0x195) | Exported Function | 0x1000d800 | 0x0000d800
`public: virtual long __stdcall CWbemProviderGlue::OpenNamespace(unsigned short * const,long,struct IWbemContext *,struct IWbemServices * *,struct IWbemCallResult * *)` | 457 (0x1c9) | Exported Function | 0x100063c0 | 0x000063c0
`public: virtual long __stdcall CWbemProviderGlue::PutClass(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemCallResult * *)` | 462 (0x1ce) | Exported Function | 0x100063d0 | 0x000063d0
`public: virtual long __stdcall CWbemProviderGlue::PutClassAsync(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemObjectSink *)` | 463 (0x1cf) | Exported Function | 0x100063d0 | 0x000063d0
`public: virtual long __stdcall CWbemProviderGlue::PutInstance(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemCallResult * *)` | 464 (0x1d0) | Exported Function | 0x100063d0 | 0x000063d0
`public: virtual long __stdcall CWbemProviderGlue::PutInstanceAsync(struct IWbemClassObject *,long,struct IWbemContext *,struct IWbemObjectSink *)` | 467 (0x1d3) | Exported Function | 0x1000ec70 | 0x0000ec70
`public: virtual long __stdcall CWbemProviderGlue::QueryInterface(struct _GUID const &,void * *)` | 469 (0x1d5) | Exported Function | 0x1000d690 | 0x0000d690
`public: virtual long __stdcall CWbemProviderGlue::QueryObjectSink(long,struct IWbemObjectSink * *)` | 470 (0x1d6) | Exported Function | 0x100063f0 | 0x000063f0
`public: virtual long __thiscall CFrameworkQueryEx::InitEx(unsigned short * const,unsigned short * const,long,class CHString &)` | 404 (0x194) | Exported Function | 0x100097c0 | 0x000097c0
`public: virtual struct IWbemContext * __thiscall MethodContext::GetIWBEMContext(void)` | 325 (0x145) | Exported Function | 0x1000bfe0 | 0x0000bfe0
`public: virtual unsigned long __stdcall CWbemGlueFactory::AddRef(void)` | 171 (0xab) | Exported Function | 0x10007620 | 0x00007620
`public: virtual unsigned long __stdcall CWbemGlueFactory::Release(void)` | 477 (0x1dd) | Exported Function | 0x10007660 | 0x00007660
`public: virtual unsigned long __stdcall CWbemProviderGlue::AddRef(void)` | 172 (0xac) | Exported Function | 0x1000d7a0 | 0x0000d7a0
`public: virtual void __thiscall MethodContext::QueryPostProcess(void)` | 471 (0x1d7) | Exported Function | 0x10007380 | 0x00007380
`public: void __thiscall CHPtrArray::RemoveAt(int,int)` | 483 (0x1e3) | Exported Function | 0x1001b100 | 0x0001b100
`public: void __thiscall CHPtrArray::SetAt(int,void *)` | 493 (0x1ed) | Exported Function | 0x1001b1e0 | 0x0001b1e0
`public: void __thiscall CHPtrArray::SetAtGrow(int,void *)` | 496 (0x1f0) | Exported Function | 0x1001afa0 | 0x0001afa0
`public: void __thiscall CHStringArray::SetAtGrow(int,unsigned short const *)` | 497 (0x1f1) | Exported Function | 0x1001abb0 | 0x0001abb0
`public: void __thiscall CHStringArray::SetSize(int,int)` | 525 (0x20d) | Exported Function | 0x1001a940 | 0x0001a940
`public: void __thiscall CObjectPathParser::``default constructor closure'(void)` | 159 (0x9f) | Exported Function | 0x10005910 | 0x00005910
`public: void __thiscall CObjectPathParser::Free(struct ParsedObjectPath *)` | 269 (0x10d) | Exported Function | 0x10014e40 | 0x00014e40
`public: void __thiscall CRegistry::Close(void)` | 193 (0xc1) | Exported Function | 0x1001be60 | 0x0001be60
`public: void __thiscall CRegistry::RewindSubKeys(void)` | 488 (0x1e8) | Exported Function | 0x1001bf10 | 0x0001bf10
`public: void __thiscall CThreadBase::``default constructor closure'(void)` | 160 (0xa0) | Exported Function | 0x10005ea0 | 0x00005ea0
`public: void __thiscall CThreadBase::EndRead(void)` | 237 (0xed) | Exported Function | 0x10005f60 | 0x00005f60
`public: void __thiscall CThreadBase::EndWrite(void)` | 238 (0xee) | Exported Function | 0x10005f60 | 0x00005f60
`public: void __thiscall CWbemGlueFactory::Destroy(void)` | 231 (0xe7) | Exported Function | 0x100074e0 | 0x000074e0
`public: void __thiscall ParsedObjectPath::ClearKeys(void)` | 192 (0xc0) | Exported Function | 0x10014430 | 0x00014430
`public: void __thiscall ProviderLog::LocalLogMessage(unsigned short const *,unsigned short const *,int,enum ProviderLog::LogLevel)` | 433 (0x1b1) | Exported Function | 0x10007070 | 0x00007070
`public: void __thiscall WBEMTime::Clear(void)` | 190 (0xbe) | Exported Function | 0x10005d40 | 0x00005d40
`public: void __thiscall WBEMTimeSpan::Clear(void)` | 191 (0xbf) | Exported Function | 0x10005d40 | 0x00005d40
`public: void const * * __thiscall CHPtrArray::GetData(void)const ` | 315 (0x13b) | Exported Function | 0x100059e0 | 0x000059e0
`public: void __thiscall CHStringArray::SetAt(int,unsigned short const *)` | 495 (0x1ef) | Exported Function | 0x10005b40 | 0x00005b40
`public: void __thiscall CHStringArray::RemoveAt(int,int)` | 484 (0x1e4) | Exported Function | 0x1001acb0 | 0x0001acb0
`public: void __thiscall CHStringArray::RemoveAll(void)` | 482 (0x1e2) | Exported Function | 0x10005b00 | 0x00005b00
`public: void __thiscall CHStringArray::InsertAt(int,unsigned short const *,int)` | 409 (0x199) | Exported Function | 0x1001abf0 | 0x0001abf0
`public: void __thiscall CHPtrArray::SetSize(int,int)` | 524 (0x20c) | Exported Function | 0x1001adb0 | 0x0001adb0
`public: void __thiscall CHString::Empty(void)` | 235 (0xeb) | Exported Function | 0x10018dc0 | 0x00018dc0
`public: void __thiscall CHString::FormatV(unsigned short const *,char *)` | 262 (0x106) | Exported Function | 0x100187b0 | 0x000187b0
`public: void __thiscall CHString::FreeExtra(void)` | 271 (0x10f) | Exported Function | 0x10019320 | 0x00019320
`public: void __thiscall CHString::MakeLower(void)` | 442 (0x1ba) | Exported Function | 0x100194c0 | 0x000194c0
`public: void __thiscall CHString::MakeReverse(void)` | 443 (0x1bb) | Exported Function | 0x100194e0 | 0x000194e0
`public: void __thiscall CHString::MakeUpper(void)` | 444 (0x1bc) | Exported Function | 0x100194a0 | 0x000194a0
`public: virtual long __stdcall CWbemProviderGlue::ExecQueryAsync(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 249 (0xf9) | Exported Function | 0x1000def0 | 0x0000def0
`public: void __thiscall CHString::Release(void)` | 473 (0x1d9) | Exported Function | 0x10018bb0 | 0x00018bb0
`public: void __thiscall CHString::SetAt(int,unsigned short)` | 494 (0x1ee) | Exported Function | 0x10018e40 | 0x00018e40
`public: void __thiscall CHString::TrimLeft(void)` | 541 (0x21d) | Exported Function | 0x10019750 | 0x00019750
`public: void __thiscall CHString::TrimRight(void)` | 542 (0x21e) | Exported Function | 0x100196f0 | 0x000196f0
`public: void __thiscall CHString::UnlockBuffer(void)` | 547 (0x223) | Exported Function | 0x100193b0 | 0x000193b0
`public: void __thiscall CHStringArray::Copy(class CHStringArray const &)` | 203 (0xcb) | Exported Function | 0x1001aaf0 | 0x0001aaf0
`public: void __thiscall CHStringArray::FreeExtra(void)` | 272 (0x110) | Exported Function | 0x1001ab40 | 0x0001ab40
`public: void __thiscall CHStringArray::InsertAt(int,class CHStringArray *)` | 408 (0x198) | Exported Function | 0x1001ad10 | 0x0001ad10
`public: void __thiscall CHString::ReleaseBuffer(int)` | 480 (0x1e0) | Exported Function | 0x10019290 | 0x00019290
`public: class CHString const * __thiscall CHStringArray::GetData(void)const ` | 318 (0x13e) | Exported Function | 0x100059e0 | 0x000059e0
`public: virtual long __stdcall CWbemProviderGlue::ExecQuery(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 247 (0xf7) | Exported Function | 0x100063c0 | 0x000063c0
`public: virtual long __stdcall CWbemProviderGlue::ExecNotificationQuery(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 245 (0xf5) | Exported Function | 0x100063c0 | 0x000063c0
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyPath(class CHString &)` | 306 (0x132) | Exported Function | 0x1001bdb0 | 0x0001bdb0
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyValue(unsigned short const *,class CHString &)` | 308 (0x134) | Exported Function | 0x1001bfb0 | 0x0001bfb0
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyValue(unsigned short const *,unsigned long &)` | 307 (0x133) | Exported Function | 0x1001bfe0 | 0x0001bfe0
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyValue(unsigned short const *,void *,unsigned long *)` | 309 (0x135) | Exported Function | 0x1001bf80 | 0x0001bf80
`public: unsigned long __thiscall CRegistry::GetLongestClassStringSize(void)` | 340 (0x154) | Exported Function | 0x10006730 | 0x00006730
`public: unsigned long __thiscall CRegistry::GetLongestSubKeySize(void)` | 341 (0x155) | Exported Function | 0x10006720 | 0x00006720
`public: unsigned long __thiscall CRegistry::GetLongestValueData(void)` | 342 (0x156) | Exported Function | 0x10006760 | 0x00006760
`public: unsigned long __thiscall CRegistry::GetLongestValueName(void)` | 343 (0x157) | Exported Function | 0x10006750 | 0x00006750
`public: unsigned long __thiscall CRegistry::GetValueCount(void)` | 379 (0x17b) | Exported Function | 0x10006740 | 0x00006740
`public: unsigned long __thiscall CRegistry::NextSubKey(void)` | 448 (0x1c0) | Exported Function | 0x1001c010 | 0x0001c010
`public: unsigned long __thiscall CRegistry::OpenCurrentUser(unsigned short const *,unsigned long)` | 455 (0x1c7) | Exported Function | 0x1001b450 | 0x0001b450
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHString &)` | 509 (0x1fd) | Exported Function | 0x1001c0f0 | 0x0001c0f0
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHStringArray &)` | 510 (0x1fe) | Exported Function | 0x1001c160 | 0x0001c160
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(struct HKEY__ *,unsigned short const *,unsigned long &)` | 508 (0x1fc) | Exported Function | 0x1001c130 | 0x0001c130
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(unsigned short const *,class CHString &)` | 512 (0x200) | Exported Function | 0x1001c070 | 0x0001c070
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyName(class CHString &)` | 305 (0x131) | Exported Function | 0x1001bd20 | 0x0001bd20
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(unsigned short const *,class CHStringArray &)` | 513 (0x201) | Exported Function | 0x1001c0d0 | 0x0001c0d0
`public: unsigned long __thiscall CRegistry::GetCurrentSubKeyCount(void)` | 304 (0x130) | Exported Function | 0x10006710 | 0x00006710
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(unsigned short const *,class CHStringArray &)` | 301 (0x12d) | Exported Function | 0x1001bae0 | 0x0001bae0
`public: struct IWbemClassObject * __thiscall MethodContext::GetStatusObject(void)` | 371 (0x173) | Exported Function | 0x1000c0a0 | 0x0000c0a0
`public: struct KeyRef & __thiscall KeyRef::operator=(struct KeyRef const &)` | 96 (0x60) | Exported Function | 0x100058d0 | 0x000058d0
`public: struct ParsedObjectPath & __thiscall ParsedObjectPath::operator=(struct ParsedObjectPath const &)` | 98 (0x62) | Exported Function | 0x100058f0 | 0x000058f0
`public: unsigned __int64 __thiscall WBEMTime::GetTime(void)const ` | 374 (0x176) | Exported Function | 0x10005d30 | 0x00005d30
`public: unsigned __int64 __thiscall WBEMTimeSpan::GetTime(void)const ` | 375 (0x177) | Exported Function | 0x10005d30 | 0x00005d30
`public: unsigned long __thiscall CAutoEvent::Wait(unsigned long)` | 559 (0x22f) | Exported Function | 0x10015e10 | 0x00015e10
`public: unsigned long __thiscall CRegistry::DeleteCurrentKeyValue(struct HKEY__ *,unsigned short const *)` | 223 (0xdf) | Exported Function | 0x1001c2f0 | 0x0001c2f0
`public: unsigned long __thiscall CRegistry::DeleteCurrentKeyValue(unsigned short const *)` | 224 (0xe0) | Exported Function | 0x1001b680 | 0x0001b680
`public: unsigned long __thiscall CRegistry::GetCurrentBinaryKeyValue(struct HKEY__ *,unsigned short const *,unsigned char *,unsigned long *)` | 293 (0x125) | Exported Function | 0x1001bcf0 | 0x0001bcf0
`public: unsigned long __thiscall CRegistry::GetCurrentBinaryKeyValue(unsigned short const *,class CHString &)` | 294 (0x126) | Exported Function | 0x1001bbc0 | 0x0001bbc0
`public: unsigned long __thiscall CRegistry::GetCurrentBinaryKeyValue(unsigned short const *,unsigned char *,unsigned long *)` | 295 (0x127) | Exported Function | 0x1001bcc0 | 0x0001bcc0
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHString &)` | 297 (0x129) | Exported Function | 0x1001b730 | 0x0001b730
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(struct HKEY__ *,unsigned short const *,class CHStringArray &)` | 298 (0x12a) | Exported Function | 0x1001b9d0 | 0x0001b9d0
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(struct HKEY__ *,unsigned short const *,unsigned long &)` | 296 (0x128) | Exported Function | 0x1001bb00 | 0x0001bb00
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(unsigned short const *,class CHString &)` | 300 (0x12c) | Exported Function | 0x1001b9b0 | 0x0001b9b0
`public: unsigned long __thiscall CRegistry::GetCurrentKeyValue(unsigned short const *,unsigned long &)` | 299 (0x12b) | Exported Function | 0x1001bba0 | 0x0001bba0
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValue(unsigned short const *,unsigned long &)` | 511 (0x1ff) | Exported Function | 0x1001c0b0 | 0x0001c0b0
`public: unsigned long __thiscall CRegistry::SetCurrentKeyValueExpand(struct HKEY__ *,unsigned short const *,class CHString &)` | 514 (0x202) | Exported Function | 0x1001c2b0 | 0x0001c2b0
`public: unsigned short * __thiscall CFrameworkQuery::GetQueryClassName(void)` | 363 (0x16b) | Exported Function | 0x100060e0 | 0x000060e0
`public: virtual long __stdcall CWbemGlueFactory::CreateInstance(struct IUnknown *,struct _GUID const &,void * *)` | 209 (0xd1) | Exported Function | 0x100076d0 | 0x000076d0
`public: virtual long __stdcall CWbemGlueFactory::LockServer(int)` | 439 (0x1b7) | Exported Function | 0x100077c0 | 0x000077c0
`public: virtual long __stdcall CWbemGlueFactory::QueryInterface(struct _GUID const &,void * *)` | 468 (0x1d4) | Exported Function | 0x10007570 | 0x00007570
`public: virtual long __stdcall CWbemProviderGlue::CancelAsyncCall(struct IWbemObjectSink *)` | 185 (0xb9) | Exported Function | 0x100063e0 | 0x000063e0
`public: virtual long __stdcall CWbemProviderGlue::CancelAsyncRequest(long)` | 186 (0xba) | Exported Function | 0x100063e0 | 0x000063e0
`public: virtual long __stdcall CWbemProviderGlue::CreateClassEnum(unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 207 (0xcf) | Exported Function | 0x100063d0 | 0x000063d0
`public: virtual long __stdcall CWbemProviderGlue::CreateClassEnumAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 208 (0xd0) | Exported Function | 0x100063d0 | 0x000063d0
`public: virtual long __stdcall CWbemProviderGlue::CreateInstanceEnum(unsigned short * const,long,struct IWbemContext *,struct IEnumWbemClassObject * *)` | 210 (0xd2) | Exported Function | 0x100063d0 | 0x000063d0
`public: virtual long __stdcall CWbemProviderGlue::CreateInstanceEnumAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 212 (0xd4) | Exported Function | 0x1000e3a0 | 0x0000e3a0
`public: virtual long __stdcall CWbemProviderGlue::DeleteClass(unsigned short * const,long,struct IWbemContext *,struct IWbemCallResult * *)` | 221 (0xdd) | Exported Function | 0x100063d0 | 0x000063d0
`public: virtual long __stdcall CWbemProviderGlue::DeleteClassAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 222 (0xde) | Exported Function | 0x100063d0 | 0x000063d0
`public: virtual long __stdcall CWbemProviderGlue::DeleteInstance(unsigned short * const,long,struct IWbemContext *,struct IWbemCallResult * *)` | 225 (0xe1) | Exported Function | 0x100063d0 | 0x000063d0
`public: virtual long __stdcall CWbemProviderGlue::DeleteInstanceAsync(unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 228 (0xe4) | Exported Function | 0x1000f550 | 0x0000f550
`public: virtual long __stdcall CWbemProviderGlue::ExecMethod(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemClassObject *,struct IWbemClassObject * *,struct IWbemCallResult * *)` | 241 (0xf1) | Exported Function | 0x10006400 | 0x00006400
`public: virtual long __stdcall CWbemProviderGlue::ExecMethodAsync(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemClassObject *,struct IWbemObjectSink *)` | 244 (0xf4) | Exported Function | 0x1000f9d0 | 0x0000f9d0
`public: virtual bool __thiscall CFrameworkQueryEx::IsExtended(void)` | 415 (0x19f) | Exported Function | 0x100099a0 | 0x000099a0
`public: virtual __thiscall ProviderLog::~ProviderLog(void)` | 73 (0x49) | Exported Function | 0x10006d20 | 0x00006d20
`public: virtual __thiscall Provider::~Provider(void)` | 72 (0x48) | Exported Function | 0x1000c410 | 0x0000c410
`public: virtual __thiscall MethodContext::~MethodContext(void)` | 70 (0x46) | Exported Function | 0x1000bf60 | 0x0000bf60
`public: unsigned short * __thiscall CHString::AllocSysString(void)const ` | 179 (0xb3) | Exported Function | 0x10019870 | 0x00019870
`public: unsigned short * __thiscall CHString::GetBuffer(int)` | 284 (0x11c) | Exported Function | 0x10019210 | 0x00019210
`public: unsigned short * __thiscall CHString::GetBufferSetLength(int)` | 285 (0x11d) | Exported Function | 0x100192e0 | 0x000192e0
`public: unsigned short * __thiscall CHString::LockBuffer(void)` | 436 (0x1b4) | Exported Function | 0x10019380 | 0x00019380
`public: unsigned short * __thiscall CRegistry::GetClassNameW(void)` | 289 (0x121) | Exported Function | 0x10006700 | 0x00006700
`public: unsigned short * __thiscall ParsedObjectPath::GetKeyString(void)` | 332 (0x14c) | Exported Function | 0x100154f0 | 0x000154f0
`public: unsigned short * __thiscall ParsedObjectPath::GetNamespacePart(void)` | 350 (0x15e) | Exported Function | 0x10015710 | 0x00015710
`public: virtual long __stdcall CWbemProviderGlue::ExecNotificationQueryAsync(unsigned short * const,unsigned short * const,long,struct IWbemContext *,struct IWbemObjectSink *)` | 246 (0xf6) | Exported Function | 0x100063c0 | 0x000063c0
`public: unsigned short * __thiscall ParsedObjectPath::GetParentNamespacePart(void)` | 357 (0x165) | Exported Function | 0x100157c0 | 0x000157c0
`public: unsigned short * __thiscall WBEMTime::GetDMTF(int)const ` | 310 (0x136) | Exported Function | 0x1001a440 | 0x0001a440
`public: unsigned short * __thiscall WBEMTime::GetDMTFNonNtfs(void)const ` | 311 (0x137) | Exported Function | 0x1001a050 | 0x0001a050
`public: unsigned short * __thiscall WBEMTimeSpan::GetBSTR(void)const ` | 283 (0x11b) | Exported Function | 0x1001a780 | 0x0001a780
`public: unsigned short __thiscall CHString::GetAt(int)const ` | 280 (0x118) | Exported Function | 0x100059c0 | 0x000059c0
`public: unsigned short __thiscall CHString::operator[](int)const ` | 119 (0x77) | Exported Function | 0x100059c0 | 0x000059c0
`public: virtual __thiscall CInstance::~CInstance(void)` | 60 (0x3c) | Exported Function | 0x10009ca0 | 0x00009ca0
`public: virtual __thiscall CThreadBase::~CThreadBase(void)` | 64 (0x40) | Exported Function | 0x1000d350 | 0x0000d350
`public: unsigned short * __thiscall WBEMTime::GetBSTR(void)const ` | 282 (0x11a) | Exported Function | 0x1001a040 | 0x0001a040
`public: class CHString const & __thiscall CHString::operator=(unsigned short)` | 81 (0x51) | Exported Function | 0x10018f70 | 0x00018f70
`public: class CHString const & __thiscall CHString::operator=(unsigned short const *)` | 85 (0x55) | Exported Function | 0x10018ee0 | 0x00018ee0
`public: class CHString const & __thiscall CHString::operator=(unsigned char const *)` | 84 (0x54) | Exported Function | 0x10005a00 | 0x00005a00
`private: static void __stdcall CWinMsgEvent::WindowsDispatch(void)` | 560 (0x230) | Exported Function | 0x10016470 | 0x00016470
`private: static void __stdcall Provider::InitComputerName(void)` | 403 (0x193) | Exported Function | 0x1000c480 | 0x0000c480
`private: struct IWbemClassObject * __thiscall Provider::GetClassObjectInterface(class MethodContext *)` | 291 (0x123) | Exported Function | 0x1000cdc0 | 0x0000cdc0
`private: struct IWbemServices * __stdcall CWbemProviderGlue::InternalGetNamespaceConnection(unsigned short const *)` | 410 (0x19a) | Exported Function | 0x10012080 | 0x00012080
`private: unsigned long __thiscall CRegistry::GetCurrentRawKeyValue(struct HKEY__ *,unsigned short const *,void *,unsigned long *,unsigned long *)` | 302 (0x12e) | Exported Function | 0x1001b700 | 0x0001b700
`private: unsigned long __thiscall CRegistry::GetCurrentRawSubKeyValue(unsigned short const *,void *,unsigned long *,unsigned long *)` | 303 (0x12f) | Exported Function | 0x1001bf40 | 0x0001bf40
`private: unsigned long __thiscall CRegistry::OpenSubKey(void)` | 458 (0x1ca) | Exported Function | 0x1001beb0 | 0x0001beb0
`private: void __thiscall CFrameworkQuery::Reset(void)` | 486 (0x1e6) | Exported Function | 0x10008cb0 | 0x00008cb0
`private: void __thiscall CObjectPathParser::Empty(void)` | 236 (0xec) | Exported Function | 0x100149e0 | 0x000149e0
`private: void __thiscall CObjectPathParser::Zero(void)` | 561 (0x231) | Exported Function | 0x10014990 | 0x00014990
`private: void __thiscall CRegistry::CloseSubKey(void)` | 194 (0xc2) | Exported Function | 0x1001bf20 | 0x0001bf20
`private: void __thiscall CRegistry::PrepareToReOpen(void)` | 461 (0x1cd) | Exported Function | 0x1001c050 | 0x0001c050
`private: void __thiscall CRegistry::SetDefaultValues(void)` | 519 (0x207) | Exported Function | 0x1001b2e0 | 0x0001b2e0
`private: void __thiscall CRegistrySearch::CheckAndAddToList(class CRegistry *,class CHString,class CHString,class CHPtrArray &,class CHString,class CHString,int)` | 187 (0xbb) | Exported Function | 0x1001c350 | 0x0001c350
`private: void __thiscall CThreadBase::Lock(void)` | 435 (0x1b3) | Exported Function | 0x10005f70 | 0x00005f70
`private: static void __stdcall CWinMsgEvent::DestroyMsgWindow(void)` | 232 (0xe8) | Exported Function | 0x100162e0 | 0x000162e0
`private: void __thiscall CThreadBase::Unlock(void)` | 546 (0x222) | Exported Function | 0x10005f60 | 0x00005f60
`private: static void __stdcall CWinMsgEvent::CreateMsgProvider(void)` | 213 (0xd5) | Exported Function | 0x10016250 | 0x00016250
`private: static void __stdcall CWbemProviderGlue::UnlockFactoryMap(void)` | 548 (0x224) | Exported Function | 0x10006530 | 0x00006530
`private: static struct HWND__ * CWinMsgEvent::mg_hWnd` | 583 (0x247) | Exported Function | 0x1002d078 | 0x0002d078
`private: static struct IWbemClassObject * __stdcall CWbemProviderGlue::GetStatusObject(class MethodContext *,unsigned short const *)` | 370 (0x172) | Exported Function | 0x1000ddc0 | 0x0000ddc0
`private: static struct IWbemClassObject * CWbemProviderGlue::m_pStatusObject` | 577 (0x241) | Exported Function | 0x1002d068 | 0x0002d068
`private: static unsigned long __stdcall CWinMsgEvent::dwThreadProc(void *)` | 564 (0x234) | Exported Function | 0x100163a0 | 0x000163a0
`private: static unsigned long CRegistry::s_dwPlatform` | 606 (0x25e) | Exported Function | 0x1002d094 | 0x0002d094
`private: static unsigned long CWbemProviderGlue::s_dwMajorVersion` | 605 (0x25d) | Exported Function | 0x1002d040 | 0x0002d040
`private: static unsigned long CWbemProviderGlue::s_dwPlatform` | 607 (0x25f) | Exported Function | 0x1002d044 | 0x0002d044
`private: static unsigned short * CWbemProviderGlue::s_wstrCSDVersion` | 613 (0x265) | Exported Function | 0x1002ce38 | 0x0002ce38
`private: static void * CWinMsgEvent::mg_hDevNotify` | 581 (0x245) | Exported Function | 0x1002d074 | 0x0002d074
`private: static void * CWinMsgEvent::mg_hThreadPumpHandle` | 582 (0x246) | Exported Function | 0x1002d07c | 0x0002d07c
`private: static void __stdcall CWbemProviderGlue::GetComputerNameW(class CHString &)` | 292 (0x124) | Exported Function | 0x100119e0 | 0x000119e0
`private: static void __stdcall CWbemProviderGlue::Init(void)` | 402 (0x192) | Exported Function | 0x1000d5a0 | 0x0000d5a0
`private: static void __stdcall CWbemProviderGlue::LockFactoryMap(void)` | 437 (0x1b5) | Exported Function | 0x10006510 | 0x00006510
`private: static void __stdcall CWbemProviderGlue::LockProviderMap(void)` | 438 (0x1b6) | Exported Function | 0x100064d0 | 0x000064d0
`private: static void __stdcall CWbemProviderGlue::UnInit(void)` | 543 (0x21f) | Exported Function | 0x1000d660 | 0x0000d660
`private: static void __stdcall CWbemProviderGlue::UnlockProviderMap(void)` | 549 (0x225) | Exported Function | 0x100064f0 | 0x000064f0
`private: void __thiscall CWbemProviderGlue::AddFlushPtr(void *)` | 163 (0xa3) | Exported Function | 0x100125f0 | 0x000125f0
`private: void __thiscall CWbemProviderGlue::FlushAll(void)` | 257 (0x101) | Exported Function | 0x1000daa0 | 0x0000daa0
`private: void __thiscall ProviderLog::CheckFileSize(union _LARGE_INTEGER &,class CHString const &)` | 188 (0xbc) | Exported Function | 0x10007260 | 0x00007260
`protected: static void __stdcall CWbemProviderGlue::RemoveFromFactoryMap(class CWbemGlueFactory const *)` | 485 (0x1e5) | Exported Function | 0x10012350 | 0x00012350
`protected: struct CHStringData * __thiscall CHString::GetData(void)const ` | 316 (0x13c) | Exported Function | 0x10018430 | 0x00018430
`protected: unsigned long __thiscall CFrameworkQuery::IsInList(class CHStringArray const &,unsigned short const *)` | 416 (0x1a0) | Exported Function | 0x10008c30 | 0x00008c30
`protected: virtual long __thiscall Provider::DeleteInstance(class CInstance const &,long)` | 227 (0xe3) | Exported Function | 0x1000c7a0 | 0x0000c7a0
`protected: virtual long __thiscall Provider::EnumerateInstances(class MethodContext *,long)` | 240 (0xf0) | Exported Function | 0x1000c7a0 | 0x0000c7a0
`protected: virtual long __thiscall Provider::ExecMethod(class CInstance const &,unsigned short * const,class CInstance *,class CInstance *,long)` | 243 (0xf3) | Exported Function | 0x1000c900 | 0x0000c900
`protected: virtual long __thiscall Provider::ExecQuery(class MethodContext *,class CFrameworkQuery &,long)` | 248 (0xf8) | Exported Function | 0x1000cf80 | 0x0000cf80
`protected: virtual long __thiscall Provider::GetObject(class CInstance *,long)` | 354 (0x162) | Exported Function | 0x1000c7a0 | 0x0000c7a0
`protected: virtual long __thiscall Provider::GetObject(class CInstance *,long,class CFrameworkQuery &)` | 355 (0x163) | Exported Function | 0x1000cf90 | 0x0000cf90
`protected: virtual long __thiscall Provider::PutInstance(class CInstance const &,long)` | 466 (0x1d2) | Exported Function | 0x1000c7a0 | 0x0000c7a0
`protected: virtual long __thiscall Provider::ValidateDeletionFlags(long)` | 551 (0x227) | Exported Function | 0x1000cd80 | 0x0000cd80
`protected: virtual long __thiscall Provider::ValidateEnumerationFlags(long)` | 552 (0x228) | Exported Function | 0x1000cd60 | 0x0000cd60
`protected: virtual long __thiscall Provider::ValidateGetObjFlags(long)` | 554 (0x22a) | Exported Function | 0x1000cd60 | 0x0000cd60
`protected: virtual long __thiscall Provider::ValidateMethodFlags(long)` | 556 (0x22c) | Exported Function | 0x1000cd80 | 0x0000cd80
`protected: virtual long __thiscall Provider::ValidatePutInstanceFlags(long)` | 557 (0x22d) | Exported Function | 0x1000cda0 | 0x0000cda0
`protected: static void __stdcall CWbemProviderGlue::AddToFactoryMap(class CWbemGlueFactory const *,long *)` | 174 (0xae) | Exported Function | 0x100122e0 | 0x000122e0
`protected: static long __stdcall CWbemProviderGlue::IncrementMapCount(long *)` | 395 (0x18b) | Exported Function | 0x10012470 | 0x00012470
`protected: static long __stdcall CWbemProviderGlue::IncrementMapCount(class CWbemGlueFactory const *)` | 396 (0x18c) | Exported Function | 0x100123e0 | 0x000123e0
`protected: static long __stdcall CWbemProviderGlue::DecrementMapCount(long *)` | 218 (0xda) | Exported Function | 0x10012530 | 0x00012530
`protected: bool __thiscall CWinMsgEvent::UnRegisterMessage(unsigned int,int)` | 545 (0x221) | Exported Function | 0x10016070 | 0x00016070
`protected: bool __thiscall Provider::GetLocalInstancePath(class CInstance const *,class CHString &)` | 335 (0x14f) | Exported Function | 0x1000cae0 | 0x0000cae0
`protected: bool __thiscall Provider::SetCreationClassName(class CInstance *)` | 507 (0x1fb) | Exported Function | 0x1000cd10 | 0x0000cd10
`protected: class CHString __thiscall Provider::MakeLocalPath(class CHString const &)` | 441 (0x1b9) | Exported Function | 0x1000cb60 | 0x0000cb60
`protected: class CHString const & __thiscall CFrameworkQuery::GetNamespace(void)` | 346 (0x15a) | Exported Function | 0x10008d60 | 0x00008d60
`protected: class CHString const & __thiscall Provider::GetLocalComputerName(void)` | 334 (0x14e) | Exported Function | 0x10006240 | 0x00006240
`protected: class CHString const & __thiscall Provider::GetNamespace(void)` | 347 (0x15b) | Exported Function | 0x10006250 | 0x00006250
`private: static struct HWND__ * __stdcall CWinMsgEvent::CreateMsgWindow(void)` | 214 (0xd6) | Exported Function | 0x100163e0 | 0x000163e0
`protected: class CHString const & __thiscall Provider::GetProviderName(void)` | 361 (0x169) | Exported Function | 0x10006260 | 0x00006260
`protected: int __thiscall CFrameworkQuery::IsReference(unsigned short const *)` | 426 (0x1aa) | Exported Function | 0x10008d10 | 0x00008d10
`protected: int __thiscall CHString::LoadStringW(unsigned int,unsigned short *,unsigned int)` | 430 (0x1ae) | Exported Function | 0x100198e0 | 0x000198e0
`protected: long __thiscall Provider::Commit(class CInstance *,bool)` | 197 (0xc5) | Exported Function | 0x1000c650 | 0x0000c650
`protected: long __thiscall Provider::ValidateFlags(long,enum Provider::FlagDefs)` | 553 (0x229) | Exported Function | 0x1000cd40 | 0x0000cd40
`protected: static int __stdcall CHString::SafeStrlen(unsigned short const *)` | 490 (0x1ea) | Exported Function | 0x10005930 | 0x00005930
`protected: static long * __stdcall CWbemProviderGlue::GetMapCountPtr(class CWbemGlueFactory const *)` | 344 (0x158) | Exported Function | 0x10012570 | 0x00012570
`protected: static long __stdcall CWbemProviderGlue::DecrementMapCount(class CWbemGlueFactory const *)` | 219 (0xdb) | Exported Function | 0x10012490 | 0x00012490
`protected: class CInstance * __thiscall Provider::CreateNewInstance(class MethodContext *)` | 215 (0xd7) | Exported Function | 0x1000c580 | 0x0000c580
`protected: virtual long __thiscall Provider::ValidateQueryFlags(long)` | 558 (0x22e) | Exported Function | 0x1000cd60 | 0x0000cd60
`private: static long CWbemProviderGlue::s_lObjects` | 610 (0x262) | Exported Function | 0x1002d060 | 0x0002d060
`private: static long __stdcall CWbemProviderGlue::GetInstanceFromCIMOM(unsigned short const *,unsigned short const *,class MethodContext *,class CInstance * *)` | 327 (0x147) | Exported Function | 0x100115e0 | 0x000115e0
`private: int __thiscall CObjectPathParser::ident_becomes_class(void)` | 566 (0x236) | Exported Function | 0x10015070 | 0x00015070
`private: int __thiscall CObjectPathParser::ident_becomes_ns(void)` | 567 (0x237) | Exported Function | 0x10015040 | 0x00015040
`private: int __thiscall CObjectPathParser::key_const(void)` | 570 (0x23a) | Exported Function | 0x100151b0 | 0x000151b0
`private: int __thiscall CObjectPathParser::keyref(void)` | 571 (0x23b) | Exported Function | 0x10015380 | 0x00015380
`private: int __thiscall CObjectPathParser::keyref_list(void)` | 572 (0x23c) | Exported Function | 0x10015360 | 0x00015360
`private: int __thiscall CObjectPathParser::keyref_term(void)` | 573 (0x23d) | Exported Function | 0x10015450 | 0x00015450
`private: int __thiscall CObjectPathParser::NextToken(void)` | 449 (0x1c1) | Exported Function | 0x10014e10 | 0x00014e10
`private: int __thiscall CObjectPathParser::ns_list(void)` | 594 (0x252) | Exported Function | 0x10015000 | 0x00015000
`private: int __thiscall CObjectPathParser::ns_list_rest(void)` | 595 (0x253) | Exported Function | 0x10015180 | 0x00015180
`private: int __thiscall CObjectPathParser::ns_or_class(void)` | 596 (0x254) | Exported Function | 0x10014f50 | 0x00014f50
`private: int __thiscall CObjectPathParser::ns_or_server(void)` | 597 (0x255) | Exported Function | 0x10014ee0 | 0x00014ee0
`private: int __thiscall CObjectPathParser::objref(void)` | 598 (0x256) | Exported Function | 0x10014fc0 | 0x00014fc0
`private: int __thiscall CObjectPathParser::objref_rest(void)` | 599 (0x257) | Exported Function | 0x100150a0 | 0x000150a0
`private: int __thiscall CObjectPathParser::optional_objref(void)` | 600 (0x258) | Exported Function | 0x10014f20 | 0x00014f20
`private: int __thiscall CObjectPathParser::propname(void)` | 601 (0x259) | Exported Function | 0x10015490 | 0x00015490
`private: int __thiscall CObjectPathParser::begin_parse(void)` | 562 (0x232) | Exported Function | 0x10014e70 | 0x00014e70
`private: int __thiscall Provider::SetKeyFromParsedObjectPath(class CInstance *,struct ParsedObjectPath *)` | 521 (0x209) | Exported Function | 0x1000cbd0 | 0x0000cbd0
`private: class CWbemProviderGlue * __thiscall MethodContext::GetProviderGlue(void)` | 360 (0x168) | Exported Function | 0x1000c040 | 0x0000c040
`const Provider::``vftable'` | 157 (0x9d) | Exported Function | 0x100010b0 | 0x000010b0
`class CCritSec g_cs` | 565 (0x235) | Exported Function | 0x1002cce4 | 0x0002cce4
`class CHString __stdcall operator+(class CHString const &,class CHString const &)` | 126 (0x7e) | Exported Function | 0x10018f90 | 0x00018f90
`class CHString __stdcall operator+(class CHString const &,unsigned short const *)` | 128 (0x80) | Exported Function | 0x10018ff0 | 0x00018ff0
`class CHString __stdcall operator+(class CHString const &,unsigned short)` | 127 (0x7f) | Exported Function | 0x100190b0 | 0x000190b0
`class CHString __stdcall operator+(unsigned short const *,class CHString const &)` | 130 (0x82) | Exported Function | 0x10019050 | 0x00019050
`class CHString __stdcall operator+(unsigned short,class CHString const &)` | 129 (0x81) | Exported Function | 0x10019100 | 0x00019100
`class ProviderLog captainsLog` | 563 (0x233) | Exported Function | 0x1002cd00 | 0x0002cd00
`const CFrameworkQueryEx::``vftable'` | 149 (0x95) | Exported Function | 0x10001168 | 0x00001168
`const CInstance::``vftable'` | 150 (0x96) | Exported Function | 0x100010f4 | 0x000010f4
`const CThreadBase::``vftable'` | 151 (0x97) | Exported Function | 0x10001140 | 0x00001140
`const CWbemGlueFactory::``vftable'` | 152 (0x98) | Exported Function | 0x10001110 | 0x00001110
`const CWbemProviderGlue::``vftable'{for ``IWbemProviderInit'}` | 153 (0x99) | Exported Function | 0x100010fc | 0x000010fc
`const CWbemProviderGlue::``vftable'{for ``IWbemServices'}` | 154 (0x9a) | Exported Function | 0x10001040 | 0x00001040
`const CWinMsgEvent::``vftable'` | 155 (0x9b) | Exported Function | 0x100011bc | 0x000011bc
`const MethodContext::``vftable'` | 156 (0x9c) | Exported Function | 0x10001128 | 0x00001128
`const ProviderLog::``vftable'` | 158 (0x9e) | Exported Function | 0x1000114c | 0x0000114c
`private: int __thiscall Provider::ValidateIMOSPointer(void)` | 555 (0x22b) | Exported Function | 0x1000c570 | 0x0000c570
`private: long __thiscall CRegistry::myRegCreateKeyEx(struct HKEY__ *,unsigned short const *,unsigned long,unsigned short *,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES * const,struct HKEY__ * *,unsigned long *)` | 585 (0x249) | Exported Function | 0x1001c990 | 0x0001c990
`private: long __thiscall CRegistry::myRegDeleteKey(struct HKEY__ *,unsigned short const *)` | 586 (0x24a) | Exported Function | 0x1001ca20 | 0x0001ca20
`private: static class CCritSec CWinMsgEvent::mg_csMapLock` | 579 (0x243) | Exported Function | 0x1002cdf0 | 0x0002cdf0
`private: static class CCritSec CWinMsgEvent::mg_csWindowLock` | 580 (0x244) | Exported Function | 0x1002ce08 | 0x0002ce08
`private: static class CHString Provider::s_strComputerName` | 612 (0x264) | Exported Function | 0x1002ccfc | 0x0002ccfc
`private: static class Provider * __stdcall CWbemProviderGlue::AddProviderToMap(unsigned short const *,unsigned short const *,class Provider *)` | 168 (0xa8) | Exported Function | 0x10011900 | 0x00011900
`private: static class Provider * __stdcall CWbemProviderGlue::SearchMapForProvider(unsigned short const *,unsigned short const *)` | 492 (0x1ec) | Exported Function | 0x10011820 | 0x00011820
`private: static class std::map<class CHString,void *,struct std::less<class CHString>,class std::allocator<void *> > CWbemProviderGlue::s_providersmap` | 611 (0x263) | Exported Function | 0x1002cd48 | 0x0002cd48
`private: static class std::map<void const *,long *,struct std::less<void const *>,class std::allocator<long *> > CWbemProviderGlue::s_factorymap` | 609 (0x261) | Exported Function | 0x1002cd70 | 0x0002cd70
`private: static class std::multimap<unsigned int,class CWinMsgEvent *,struct std::less<unsigned int>,class std::allocator<class CWinMsgEvent *> > CWinMsgEvent::mg_oSinkMap` | 584 (0x248) | Exported Function | 0x1002c7d0 | 0x0002c7d0
`private: static class std::set<void *,struct std::less<void *>,class std::allocator<void *> > CWbemProviderGlue::m_FlushPtrs` | 574 (0x23e) | Exported Function | 0x1002cdb0 | 0x0002cdb0
`private: static int __stdcall CRegistry::SetPlatformID(void)` | 523 (0x20b) | Exported Function | 0x1001c940 | 0x0001c940
`private: static int __stdcall CWinMsgEvent::CtrlHandlerRoutine(unsigned long)` | 217 (0xd9) | Exported Function | 0x10016360 | 0x00016360
`private: static int CRegistry::s_fPlatformSet` | 608 (0x260) | Exported Function | 0x1002d090 | 0x0002d090
`private: static int CWbemProviderGlue::s_bInitted` | 602 (0x25a) | Exported Function | 0x1002d064 | 0x0002d064
`private: static int Provider::initFailed_` | 569 (0x239) | Exported Function | 0x1002ce34 | 0x0002ce34
`private: static long __stdcall CWbemProviderGlue::CheckImpersonationLevel(void)` | 189 (0xbd) | Exported Function | 0x10011b10 | 0x00011b10
`private: static class CCritSec CWbemProviderGlue::s_csProviderMap` | 604 (0x25c) | Exported Function | 0x1002cd80 | 0x0002cd80
`private: static class CCritSec CWbemProviderGlue::s_csFactoryMap` | 603 (0x25b) | Exported Function | 0x1002cd58 | 0x0002cd58
`private: static class CCritSec CWbemProviderGlue::m_csStatusObject` | 576 (0x240) | Exported Function | 0x1002cd98 | 0x0002cd98
`private: static class CCritSec CWbemProviderGlue::m_csFlushPtrs` | 575 (0x23f) | Exported Function | 0x1002cdc0 | 0x0002cdc0
`private: long __thiscall CRegistry::myRegDeleteValue(struct HKEY__ *,unsigned short const *)` | 587 (0x24b) | Exported Function | 0x1001c2f0 | 0x0001c2f0
`private: long __thiscall CRegistry::myRegEnumKey(struct HKEY__ *,unsigned long,unsigned short *,unsigned long)` | 588 (0x24c) | Exported Function | 0x1001c9f0 | 0x0001c9f0
`private: long __thiscall CRegistry::myRegEnumValue(struct HKEY__ *,unsigned long,unsigned short *,unsigned long *,unsigned long *,unsigned long *,unsigned char *,unsigned long *)` | 589 (0x24d) | Exported Function | 0x1001ca80 | 0x0001ca80
`private: long __thiscall CRegistry::myRegOpenKeyEx(struct HKEY__ *,unsigned short const *,unsigned long,unsigned long,struct HKEY__ * *)` | 590 (0x24e) | Exported Function | 0x1001ca40 | 0x0001ca40
`private: long __thiscall CRegistry::myRegQueryInfoKey(struct HKEY__ *,unsigned short *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,struct _FILETIME *)` | 591 (0x24f) | Exported Function | 0x1001ca60 | 0x0001ca60
`private: long __thiscall CRegistry::myRegQueryValueEx(struct HKEY__ *,unsigned short const *,unsigned long *,unsigned long *,unsigned char *,unsigned long *)` | 592 (0x250) | Exported Function | 0x1001c9d0 | 0x0001c9d0
`private: long __thiscall CRegistry::myRegSetValueEx(struct HKEY__ *,unsigned short const *,unsigned long,unsigned long,unsigned char const *,unsigned long)` | 593 (0x251) | Exported Function | 0x1001c9b0 | 0x0001c9b0
`private: static long __stdcall CWinMsgEvent::MsgWndProc(struct HWND__ *,unsigned int,unsigned int,long)` | 447 (0x1bf) | Exported Function | 0x100164b0 | 0x000164b0
`private: long __thiscall CWbemProviderGlue::NullOutUnsetProperties(struct IWbemClassObject *,struct IWbemClassObject * *,struct tagVARIANT const &)` | 451 (0x1c3) | Exported Function | 0x1000f290 | 0x0000f290
`private: long __thiscall Provider::CreateInstanceEnum(class MethodContext *,long)` | 211 (0xd3) | Exported Function | 0x1000c750 | 0x0000c750
`private: long __thiscall Provider::DeleteInstance(struct ParsedObjectPath *,long,class MethodContext *)` | 226 (0xe2) | Exported Function | 0x1000c860 | 0x0000c860
`private: long __thiscall Provider::ExecMethod(struct ParsedObjectPath *,unsigned short *,long,class CInstance *,class CInstance *,class MethodContext *)` | 242 (0xf2) | Exported Function | 0x1000c910 | 0x0000c910
`private: long __thiscall Provider::ExecuteQuery(class MethodContext *,class CFrameworkQuery &,long)` | 250 (0xfa) | Exported Function | 0x1000c680 | 0x0000c680
`private: long __thiscall Provider::GetObject(struct ParsedObjectPath *,class MethodContext *,long)` | 353 (0x161) | Exported Function | 0x1000c9b0 | 0x0000c9b0
`private: long __thiscall Provider::PutInstance(struct IWbemClassObject *,long,class MethodContext *)` | 465 (0x1d1) | Exported Function | 0x1000c7b0 | 0x0000c7b0
`private: static class CAutoEvent CWinMsgEvent::mg_aeCreateWindow` | 578 (0x242) | Exported Function | 0x1002ce20 | 0x0002ce20
`private: long __thiscall CWbemProviderGlue::PreProcessPutInstanceParms(struct IWbemClassObject *,struct IWbemClassObject * *,struct IWbemContext *)` | 460 (0x1cc) | Exported Function | 0x1000f0d0 | 0x0000f0d0
`unsigned long __stdcall NormalizePath(unsigned short const *,unsigned short const *,unsigned short const *,unsigned long,class CHString &)` | 450 (0x1c2) | Exported Function | 0x1001caa0 | 0x0001caa0
`protected: virtual void __thiscall CThreadBase::OnFinalRelease(void)` | 452 (0x1c4) | Exported Function | 0x1000d3a0 | 0x0000d3a0
`protected: void __thiscall CHString::AllocBeforeWrite(int)` | 176 (0xb0) | Exported Function | 0x10018b70 | 0x00018b70
`public: bool __thiscall CInstance::GetWBEMINT64(unsigned short const *,class CHString &)const ` | 386 (0x182) | Exported Function | 0x1000b830 | 0x0000b830
`public: bool __thiscall CInstance::GetWBEMINT64(unsigned short const *,unsigned __int64 &)const ` | 388 (0x184) | Exported Function | 0x1000b8a0 | 0x0000b8a0
`public: bool __thiscall CInstance::GetWCHAR(unsigned short const *,unsigned short * *)const ` | 389 (0x185) | Exported Function | 0x1000a3e0 | 0x0000a3e0
`public: bool __thiscall CInstance::GetWORD(unsigned short const *,unsigned short &)const ` | 390 (0x186) | Exported Function | 0x1000a620 | 0x0000a620
`public: bool __thiscall CInstance::IsNull(unsigned short const *)const ` | 421 (0x1a5) | Exported Function | 0x1000bb00 | 0x0000bb00
`public: bool __thiscall CInstance::Setbool(unsigned short const *,bool)` | 537 (0x219) | Exported Function | 0x1000afb0 | 0x0000afb0
`public: bool __thiscall CInstance::SetByte(unsigned short const *,unsigned char)` | 498 (0x1f2) | Exported Function | 0x1000ab00 | 0x0000ab00
`public: bool __thiscall CInstance::SetCharSplat(unsigned short const *,char const *)` | 505 (0x1f9) | Exported Function | 0x1000be10 | 0x0000be10
`public: bool __thiscall CInstance::SetCharSplat(unsigned short const *,unsigned long)` | 504 (0x1f8) | Exported Function | 0x1000be60 | 0x0000be60
`public: bool __thiscall CInstance::SetCharSplat(unsigned short const *,unsigned short const *)` | 503 (0x1f7) | Exported Function | 0x1000be00 | 0x0000be00
`public: bool __thiscall CInstance::SetCHString(unsigned short const *,char const *)` | 501 (0x1f5) | Exported Function | 0x1000be10 | 0x0000be10
`public: bool __thiscall CInstance::SetCHString(unsigned short const *,class CHString const &)` | 500 (0x1f4) | Exported Function | 0x1000b730 | 0x0000b730
`public: bool __thiscall CInstance::SetCHString(unsigned short const *,unsigned short const *)` | 499 (0x1f3) | Exported Function | 0x1000be00 | 0x0000be00
`public: bool __thiscall CInstance::SetDateTime(unsigned short const *,class WBEMTime const &)` | 518 (0x206) | Exported Function | 0x1000b2e0 | 0x0000b2e0
`public: bool __thiscall CInstance::SetDOUBLE(unsigned short const *,double)` | 516 (0x204) | Exported Function | 0x1000a920 | 0x0000a920
`public: bool __thiscall CInstance::GetWBEMINT64(unsigned short const *,__int64 &)const ` | 387 (0x183) | Exported Function | 0x1000b840 | 0x0000b840
`public: bool __thiscall CInstance::SetDWORD(unsigned short const *,unsigned long)` | 517 (0x205) | Exported Function | 0x1000a730 | 0x0000a730
`public: bool __thiscall CInstance::GetWBEMINT16(unsigned short const *,short &)const ` | 385 (0x181) | Exported Function | 0x1000b9e0 | 0x0000b9e0
`public: bool __thiscall CInstance::GetTimeSpan(unsigned short const *,class WBEMTimeSpan &)const ` | 376 (0x178) | Exported Function | 0x1000b600 | 0x0000b600
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(struct _FILETIME const &)` | 49 (0x31) | Exported Function | 0x1001a640 | 0x0001a640
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(unsigned short * const)` | 51 (0x33) | Exported Function | 0x10005bd0 | 0x00005bd0
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(void)` | 52 (0x34) | Exported Function | 0x10005bc0 | 0x00005bc0
`public: bool __thiscall CFrameworkQuery::AllPropertiesAreRequired(void)` | 175 (0xaf) | Exported Function | 0x10006100 | 0x00006100
`public: bool __thiscall CFrameworkQuery::IsPropertyRequired(unsigned short const *)` | 425 (0x1a9) | Exported Function | 0x10008330 | 0x00008330
`public: bool __thiscall CFrameworkQuery::KeysOnly(void)` | 428 (0x1ac) | Exported Function | 0x10006110 | 0x00006110
`public: bool __thiscall CInstance::Getbool(unsigned short const *,bool &)const ` | 391 (0x187) | Exported Function | 0x1000b090 | 0x0000b090
`public: bool __thiscall CInstance::GetByte(unsigned short const *,unsigned char &)const ` | 286 (0x11e) | Exported Function | 0x1000ace0 | 0x0000ace0
`public: bool __thiscall CInstance::GetCHString(unsigned short const *,class CHString &)const ` | 287 (0x11f) | Exported Function | 0x1000a180 | 0x0000a180
`public: bool __thiscall CInstance::GetDateTime(unsigned short const *,class WBEMTime &)const ` | 319 (0x13f) | Exported Function | 0x1000b3e0 | 0x0000b3e0
`public: bool __thiscall CInstance::GetDOUBLE(unsigned short const *,double &)const ` | 312 (0x138) | Exported Function | 0x1000a9f0 | 0x0000a9f0
`public: bool __thiscall CInstance::GetDWORD(unsigned short const *,unsigned long &)const ` | 313 (0x139) | Exported Function | 0x1000a810 | 0x0000a810
`public: bool __thiscall CInstance::GetEmbeddedObject(unsigned short const *,class CInstance * *,class MethodContext *)const ` | 320 (0x140) | Exported Function | 0x1000ae00 | 0x0000ae00
`public: bool __thiscall CInstance::GetStatus(unsigned short const *,bool &,unsigned short &)const ` | 369 (0x171) | Exported Function | 0x1000bbd0 | 0x0000bbd0
`public: bool __thiscall CInstance::GetStringArray(unsigned short const *,struct tagSAFEARRAY * &)const ` | 372 (0x174) | Exported Function | 0x1000a2a0 | 0x0000a2a0
`public: bool __thiscall CInstance::GetVariant(unsigned short const *,struct tagVARIANT &)const ` | 384 (0x180) | Exported Function | 0x1000b240 | 0x0000b240
`public: bool __thiscall CInstance::SetEmbeddedObject(unsigned short const *,class CInstance &)` | 520 (0x208) | Exported Function | 0x1000abe0 | 0x0000abe0
`public: bool __thiscall CInstance::SetNull(unsigned short const *)` | 522 (0x20a) | Exported Function | 0x10009f90 | 0x00009f90
`public: bool __thiscall CInstance::SetStringArray(unsigned short const *,struct tagSAFEARRAY const &)` | 528 (0x210) | Exported Function | 0x1000a070 | 0x0000a070
`public: class CHString __thiscall CHString::Mid(int,int)const ` | 446 (0x1be) | Exported Function | 0x10019530 | 0x00019530
`public: class CHString __thiscall CHString::Right(int)const ` | 489 (0x1e9) | Exported Function | 0x100195b0 | 0x000195b0
`public: class CHString __thiscall CHString::SpanExcluding(unsigned short const *)const ` | 539 (0x21b) | Exported Function | 0x100196c0 | 0x000196c0
`public: class CHString __thiscall CHString::SpanIncluding(unsigned short const *)const ` | 540 (0x21c) | Exported Function | 0x10019690 | 0x00019690
`public: class CHString __thiscall CHStringArray::GetAt(int)const ` | 281 (0x119) | Exported Function | 0x10005b10 | 0x00005b10
`public: class CHString __thiscall CHStringArray::operator[](int)const ` | 121 (0x79) | Exported Function | 0x10005b10 | 0x00005b10
`public: class CHString const & __thiscall CFrameworkQuery::GetQuery(void)` | 362 (0x16a) | Exported Function | 0x10008af0 | 0x00008af0
`public: class CHString const & __thiscall CHString::operator+=(char)` | 142 (0x8e) | Exported Function | 0x10005a70 | 0x00005a70
`public: class CHString const & __thiscall CHString::operator+=(class CHString const &)` | 141 (0x8d) | Exported Function | 0x100191a0 | 0x000191a0
`public: class CHString const & __thiscall CHString::operator+=(unsigned short const *)` | 144 (0x90) | Exported Function | 0x10019150 | 0x00019150
`public: class CHString const & __thiscall CHString::operator+=(unsigned short)` | 143 (0x8f) | Exported Function | 0x10019180 | 0x00019180
`public: class CHString const & __thiscall CHString::operator=(char const *)` | 83 (0x53) | Exported Function | 0x10018f10 | 0x00018f10
`public: class CHString const & __thiscall CHString::operator=(char)` | 80 (0x50) | Exported Function | 0x10005a40 | 0x00005a40
`public: class CHString const & __thiscall CHString::operator=(class CHString *)` | 82 (0x52) | Exported Function | 0x10005a20 | 0x00005a20
`public: class CHString const & __thiscall CHString::operator=(class CHString const &)` | 79 (0x4f) | Exported Function | 0x10018e70 | 0x00018e70
`public: class CHString __thiscall CHString::Mid(int)const ` | 445 (0x1bd) | Exported Function | 0x10019500 | 0x00019500
`public: class CHString __thiscall CHString::Left(int)const ` | 429 (0x1ad) | Exported Function | 0x10019620 | 0x00019620
`public: class CHString * __thiscall CHStringArray::GetData(void)` | 317 (0x13d) | Exported Function | 0x100059e0 | 0x000059e0
`public: class CHString & __thiscall CHStringArray::operator[](int)` | 120 (0x78) | Exported Function | 0x10005b60 | 0x00005b60
`public: bool __thiscall CInstance::SetTimeSpan(unsigned short const *,class WBEMTimeSpan const &)` | 529 (0x211) | Exported Function | 0x1000b510 | 0x0000b510
`public: bool __thiscall CInstance::SetVariant(unsigned short const *,struct tagVARIANT const &)` | 530 (0x212) | Exported Function | 0x1000b1a0 | 0x0000b1a0
`public: bool __thiscall CInstance::SetWBEMINT16(unsigned short const *,short const &)` | 531 (0x213) | Exported Function | 0x1000b900 | 0x0000b900
`public: bool __thiscall CInstance::SetWBEMINT64(unsigned short const *,__int64)` | 533 (0x215) | Exported Function | 0x1000b750 | 0x0000b750
`public: bool __thiscall CInstance::SetWBEMINT64(unsigned short const *,class CHString const &)` | 532 (0x214) | Exported Function | 0x1000b730 | 0x0000b730
`public: bool __thiscall CInstance::SetWBEMINT64(unsigned short const *,unsigned __int64)` | 534 (0x216) | Exported Function | 0x1000b7c0 | 0x0000b7c0
`public: bool __thiscall CInstance::SetWCHARSplat(unsigned short const *,unsigned short const *)` | 535 (0x217) | Exported Function | 0x10009ea0 | 0x00009ea0
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(long const &)` | 48 (0x30) | Exported Function | 0x1001a670 | 0x0001a670
`public: bool __thiscall CInstance::SetWORD(unsigned short const *,unsigned short)` | 536 (0x218) | Exported Function | 0x1000a550 | 0x0000a550
`public: bool __thiscall WBEMTime::IsOk(void)const ` | 423 (0x1a7) | Exported Function | 0x10005d10 | 0x00005d10
`public: bool __thiscall WBEMTimeSpan::IsOk(void)const ` | 424 (0x1a8) | Exported Function | 0x10005d10 | 0x00005d10
`public: class CAutoEvent & __thiscall CAutoEvent::operator=(class CAutoEvent const &)` | 75 (0x4b) | Exported Function | 0x10007830 | 0x00007830
`public: class CFrameworkQuery & __thiscall CFrameworkQuery::operator=(class CFrameworkQuery const &)` | 76 (0x4c) | Exported Function | 0x100061b0 | 0x000061b0
`public: class CFrameworkQueryEx & __thiscall CFrameworkQueryEx::operator=(class CFrameworkQueryEx const &)` | 77 (0x4d) | Exported Function | 0x10009070 | 0x00009070
`public: class CHPtrArray & __thiscall CHPtrArray::operator=(class CHPtrArray const &)` | 78 (0x4e) | Exported Function | 0x10005ba0 | 0x00005ba0
`public: class CHString & __thiscall CHStringArray::ElementAt(int)` | 234 (0xea) | Exported Function | 0x10005b60 | 0x00005b60
`public: bool __thiscall MethodContext::SetStatusObject(struct IWbemClassObject *)` | 527 (0x20f) | Exported Function | 0x1000c050 | 0x0000c050
`protected: virtual void __thiscall Provider::Flush(void)` | 256 (0x100) | Exported Function | 0x1000c510 | 0x0000c510
`public: __thiscall WBEMTimeSpan::WBEMTimeSpan(int,int,int,int,int,int,int)` | 50 (0x32) | Exported Function | 0x1001a5c0 | 0x0001a5c0
`public: __thiscall WBEMTime::WBEMTime(unsigned short * const)` | 46 (0x2e) | Exported Function | 0x10005d70 | 0x00005d70
`public: __thiscall CHPtrArray::~CHPtrArray(void)` | 57 (0x39) | Exported Function | 0x10006ca0 | 0x00006ca0
`public: __thiscall CHString::CHString(char const *)` | 9 (0x9) | Exported Function | 0x10018cc0 | 0x00018cc0
`public: __thiscall CHString::CHString(class CHString const &)` | 7 (0x7) | Exported Function | 0x10018d70 | 0x00018d70
`public: __thiscall CHString::CHString(unsigned char const *)` | 10 (0xa) | Exported Function | 0x10005960 | 0x00005960
`public: __thiscall CHString::CHString(unsigned short const *)` | 11 (0xb) | Exported Function | 0x10018d20 | 0x00018d20
`public: __thiscall CHString::CHString(unsigned short const *,int)` | 12 (0xc) | Exported Function | 0x10018c70 | 0x00018c70
`public: __thiscall CHString::CHString(unsigned short,int)` | 8 (0x8) | Exported Function | 0x10018c30 | 0x00018c30
`public: __thiscall CHString::CHString(void)` | 13 (0xd) | Exported Function | 0x10018c20 | 0x00018c20
`public: __thiscall CHString::operator unsigned short const *(void)const ` | 122 (0x7a) | Exported Function | 0x100059e0 | 0x000059e0
`public: __thiscall CHString::~CHString(void)` | 58 (0x3a) | Exported Function | 0x10018e00 | 0x00018e00
`public: __thiscall CHStringArray::CHStringArray(void)` | 14 (0xe) | Exported Function | 0x1001a8f0 | 0x0001a8f0
`public: __thiscall CHStringArray::~CHStringArray(void)` | 59 (0x3b) | Exported Function | 0x1001a910 | 0x0001a910
`public: __thiscall CInstance::CInstance(class CInstance const &)` | 15 (0xf) | Exported Function | 0x10006590 | 0x00006590
`public: __thiscall CInstance::CInstance(struct IWbemClassObject *,class MethodContext *)` | 16 (0x10) | Exported Function | 0x10009c50 | 0x00009c50
`public: __thiscall CObjectPathParser::CObjectPathParser(enum ObjectParserFlags)` | 17 (0x11) | Exported Function | 0x100149b0 | 0x000149b0
`public: __thiscall CHPtrArray::CHPtrArray(void)` | 6 (0x6) | Exported Function | 0x1001a8f0 | 0x0001a8f0
`public: __thiscall CObjectPathParser::~CObjectPathParser(void)` | 61 (0x3d) | Exported Function | 0x10014a70 | 0x00014a70
`public: __thiscall CFrameworkQueryEx::~CFrameworkQueryEx(void)` | 56 (0x38) | Exported Function | 0x100090e0 | 0x000090e0
`public: __thiscall CFrameworkQueryEx::CFrameworkQueryEx(class CFrameworkQueryEx const &)` | 4 (0x4) | Exported Function | 0x10009020 | 0x00009020
`protected: void __thiscall CHString::AllocBuffer(int)` | 177 (0xb1) | Exported Function | 0x10018500 | 0x00018500
`protected: void __thiscall CHString::AllocCopy(class CHString &,int,int,int)const ` | 178 (0xb2) | Exported Function | 0x10018460 | 0x00018460
`protected: void __thiscall CHString::AssignCopy(int,unsigned short const *)` | 182 (0xb6) | Exported Function | 0x10018590 | 0x00018590
`protected: void __thiscall CHString::ConcatCopy(int,unsigned short const *,int,unsigned short const *)` | 200 (0xc8) | Exported Function | 0x10018600 | 0x00018600
`protected: void __thiscall CHString::ConcatInPlace(int,unsigned short const *)` | 201 (0xc9) | Exported Function | 0x100186b0 | 0x000186b0
`protected: void __thiscall CHString::CopyBeforeWrite(void)` | 204 (0xcc) | Exported Function | 0x10018b20 | 0x00018b20
`protected: void __thiscall CHString::Init(void)` | 401 (0x191) | Exported Function | 0x10018450 | 0x00018450
`protected: void __thiscall CInstance::LogError(unsigned short const *,unsigned short const *,unsigned short const *,long)const ` | 440 (0x1b8) | Exported Function | 0x1000bc90 | 0x0000bc90
`protected: void __thiscall CWinMsgEvent::RegisterForMessage(unsigned int,int)` | 472 (0x1d8) | Exported Function | 0x10015ee0 | 0x00015ee0
`protected: void __thiscall CWinMsgEvent::UnRegisterAllMessages(void)` | 544 (0x220) | Exported Function | 0x10016170 | 0x00016170
`public: __thiscall CAutoEvent::CAutoEvent(void)` | 1 (0x1) | Exported Function | 0x10015db0 | 0x00015db0
`public: __thiscall CAutoEvent::~CAutoEvent(void)` | 54 (0x36) | Exported Function | 0x10015dd0 | 0x00015dd0
`public: __thiscall CFrameworkQuery::CFrameworkQuery(class CFrameworkQuery const &)` | 2 (0x2) | Exported Function | 0x10006120 | 0x00006120
`public: __thiscall CFrameworkQuery::CFrameworkQuery(void)` | 3 (0x3) | Exported Function | 0x10007c90 | 0x00007c90
`public: __thiscall CFrameworkQuery::~CFrameworkQuery(void)` | 55 (0x37) | Exported Function | 0x10007cd0 | 0x00007cd0
`public: __thiscall CFrameworkQueryEx::CFrameworkQueryEx(void)` | 5 (0x5) | Exported Function | 0x100090b0 | 0x000090b0
`public: __thiscall CreateMutexAsProcess::CreateMutexAsProcess(unsigned short const *)` | 32 (0x20) | Exported Function | 0x10007a50 | 0x00007a50
`public: __thiscall CreateMutexAsProcess::~CreateMutexAsProcess(void)` | 68 (0x44) | Exported Function | 0x10007c40 | 0x00007c40
`public: __thiscall CRegistry::CRegistry(class CRegistry const &)` | 18 (0x12) | Exported Function | 0x10006770 | 0x00006770
`public: __thiscall KeyRef::~KeyRef(void)` | 69 (0x45) | Exported Function | 0x10014620 | 0x00014620
`public: __thiscall MethodContext::MethodContext(class MethodContext const &)` | 35 (0x23) | Exported Function | 0x10005f80 | 0x00005f80
`public: __thiscall MethodContext::MethodContext(struct IWbemContext *,class CWbemProviderGlue *)` | 36 (0x24) | Exported Function | 0x1000bf00 | 0x0000bf00
`public: __thiscall ParsedObjectPath::ParsedObjectPath(void)` | 37 (0x25) | Exported Function | 0x10014000 | 0x00014000
`public: __thiscall ParsedObjectPath::~ParsedObjectPath(void)` | 71 (0x47) | Exported Function | 0x10014060 | 0x00014060
`public: __thiscall Provider::Provider(class Provider const &)` | 38 (0x26) | Exported Function | 0x10006270 | 0x00006270
`public: __thiscall Provider::Provider(unsigned short const *,unsigned short const *)` | 39 (0x27) | Exported Function | 0x1000c370 | 0x0000c370
`public: __thiscall ProviderLog::ProviderLog(class ProviderLog const &)` | 40 (0x28) | Exported Function | 0x100069a0 | 0x000069a0
`public: __thiscall ProviderLog::ProviderLog(void)` | 41 (0x29) | Exported Function | 0x10006cc0 | 0x00006cc0
`public: __thiscall std::_Lockit::_Lockit(void)` | 53 (0x35) | Exported Function | 0x10006690 | 0x00006690
`public: __thiscall std::_Lockit::~_Lockit(void)` | 74 (0x4a) | Exported Function | 0x100066b0 | 0x000066b0
`public: __thiscall WBEMTime::WBEMTime(long const &)` | 42 (0x2a) | Exported Function | 0x10005e00 | 0x00005e00
`public: __thiscall WBEMTime::WBEMTime(struct _FILETIME const &)` | 43 (0x2b) | Exported Function | 0x10005db0 | 0x00005db0
`public: __thiscall WBEMTime::WBEMTime(struct _SYSTEMTIME const &)` | 44 (0x2c) | Exported Function | 0x10005d90 | 0x00005d90
`public: __thiscall WBEMTime::WBEMTime(struct tm const &)` | 45 (0x2d) | Exported Function | 0x10005de0 | 0x00005de0
`public: __thiscall KeyRef::KeyRef(void)` | 34 (0x22) | Exported Function | 0x100145a0 | 0x000145a0
`public: __thiscall KeyRef::KeyRef(unsigned short const *,struct tagVARIANT const *)` | 33 (0x21) | Exported Function | 0x100145c0 | 0x000145c0
`public: __thiscall CWinMsgEvent::~CWinMsgEvent(void)` | 67 (0x43) | Exported Function | 0x10015e70 | 0x00015e70
`public: __thiscall CWinMsgEvent::CWinMsgEvent(void)` | 31 (0x1f) | Exported Function | 0x10015e60 | 0x00015e60
`public: __thiscall CRegistry::CRegistry(void)` | 19 (0x13) | Exported Function | 0x1001b220 | 0x0001b220
`public: __thiscall CRegistry::~CRegistry(void)` | 62 (0x3e) | Exported Function | 0x1001b270 | 0x0001b270
`public: __thiscall CRegistrySearch::CRegistrySearch(class CRegistrySearch const &)` | 20 (0x14) | Exported Function | 0x10006920 | 0x00006920
`public: __thiscall CRegistrySearch::CRegistrySearch(void)` | 21 (0x15) | Exported Function | 0x1001c310 | 0x0001c310
`public: __thiscall CRegistrySearch::~CRegistrySearch(void)` | 63 (0x3f) | Exported Function | 0x1001c330 | 0x0001c330
`public: __thiscall CThreadBase::CThreadBase(class CThreadBase const &)` | 22 (0x16) | Exported Function | 0x10005e20 | 0x00005e20
`public: __thiscall CThreadBase::CThreadBase(enum CThreadBase::THREAD_SAFETY_MECHANISM)` | 23 (0x17) | Exported Function | 0x1000d310 | 0x0000d310
`public: __thiscall WBEMTime::WBEMTime(void)` | 47 (0x2f) | Exported Function | 0x10005bc0 | 0x00005bc0
`public: __thiscall CWbemGlueFactory::CWbemGlueFactory(class CWbemGlueFactory const &)` | 24 (0x18) | Exported Function | 0x10006550 | 0x00006550
`public: __thiscall CWbemGlueFactory::CWbemGlueFactory(void)` | 26 (0x1a) | Exported Function | 0x100073c0 | 0x000073c0
`public: __thiscall CWbemGlueFactory::~CWbemGlueFactory(void)` | 65 (0x41) | Exported Function | 0x10007500 | 0x00007500
`public: __thiscall CWbemProviderGlue::CWbemProviderGlue(class CWbemProviderGlue const &)` | 27 (0x1b) | Exported Function | 0x10006440 | 0x00006440
`public: __thiscall CWbemProviderGlue::CWbemProviderGlue(long *)` | 28 (0x1c) | Exported Function | 0x1000d4d0 | 0x0000d4d0
`public: __thiscall CWbemProviderGlue::CWbemProviderGlue(void)` | 29 (0x1d) | Exported Function | 0x1000d480 | 0x0000d480
`public: __thiscall CWbemProviderGlue::~CWbemProviderGlue(void)` | 66 (0x42) | Exported Function | 0x1000d510 | 0x0000d510
`public: __thiscall CWinMsgEvent::CWinMsgEvent(class CWinMsgEvent const &)` | 30 (0x1e) | Exported Function | 0x10015e40 | 0x00015e40
`public: __thiscall CWbemGlueFactory::CWbemGlueFactory(long *)` | 25 (0x19) | Exported Function | 0x10007410 | 0x00007410
`void __stdcall SetCHStringResourceHandle(struct HINSTANCE__ *)` | 502 (0x1f6) | Exported Function | 0x100183f0 | 0x000183f0


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


