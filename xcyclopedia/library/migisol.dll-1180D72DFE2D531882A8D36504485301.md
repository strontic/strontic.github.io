---
title: migisol.dll | Migration System Isolation Layer
excerpt: What is migisol.dll?
---

# migisol.dll 

* File Path: `C:\Windows\SysWOW64\migisol.dll`
* Description: Migration System Isolation Layer

## Hashes

Type | Hash
-- | --
MD5 | `1180D72DFE2D531882A8D36504485301`
SHA1 | `3E831BD6E3BEBE91CF2D2E1D84D2436B7D5B96B0`
SHA256 | `CBEAAC6A5B95F5AFC6C5327D98A5FEFA20E35EC1F859A79066E5856C5B87BEBB`
SHA384 | `E9C7AACD17D59BE94D7742C2BA6DAB4684119813CB53E3B131E2B47FF5FFB3705727907203E7BF861C9A12241DB63067`
SHA512 | `9C0BDE6F1BD5420D1097E266089EE72980A27CF9D22274D881B8AD52B5B4EC9EB72AF7D95EAC61D541B9356A62F409F7856A7D6DC336F8EA800151298665237A`
SSDEEP | `3072:7KtPUMsHA/Ko20D36cJYkIgJ3Rm/yzMHGm3T0/qg00fSZWUuwzZbWzyznhmmMVYg:7KtcMsHA/Ko20D36cJYkIgJ3RyyzMHGv`
IMP | `46AC9011E7F94F9FCC6E594DCB66D280`
PESHA1 | `593D4481449D39443D70493079AD17EA3BBBE1B2`
PE256 | `DB9EF9BA556D86A2C1DE5DD000E5E1160E70C85F407BCEAC8B7EA8AC235EF0B5`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`class CIlAdvapi32 IlAdvapi32` | 248 (0xf8) | Exported Function | 0x10019128 | 0x00019128
`public: virtual int __thiscall CIlNt4Setupapi::SetupDiGetDriverInfoDetailW(void *,struct _SP_DEVINFO_DATA *,struct _SP_DRVINFO_DATA_V2_W *,struct _SP_DRVINFO_DETAIL_DATA_W *,unsigned long,unsigned long *)` | 410 (0x19a) | Exported Function | 0x100090e0 | 0x000090e0
`public: virtual int __thiscall CIlNt4Setupapi::SetupDiOpenDeviceInfoW(void *,unsigned short const *,struct HWND__ *,unsigned long,struct _SP_DEVINFO_DATA *)` | 412 (0x19c) | Exported Function | 0x10008de0 | 0x00008de0
`public: virtual int __thiscall CIlNt4Setupapi::SetupDiSetDeviceInstallParamsW(void *,struct _SP_DEVINFO_DATA *,struct _SP_DEVINSTALL_PARAMS_W *)` | 413 (0x19d) | Exported Function | 0x10009270 | 0x00009270
`public: virtual int __thiscall CIlNt4Setupapi::SetupDiSetSelectedDriverW(void *,struct _SP_DEVINFO_DATA *,struct _SP_DRVINFO_DATA_V2_W *)` | 414 (0x19e) | Exported Function | 0x100093f0 | 0x000093f0
`public: virtual int __thiscall CIlNt4Setupapi::SetupGetInfInformationW(void const *,unsigned long,struct _SP_INF_INFORMATION *,unsigned long,unsigned long *)` | 417 (0x1a1) | Exported Function | 0x10009780 | 0x00009780
`public: virtual int __thiscall CIlNt4Setupapi::SetupQueryInfOriginalFileInformationW(struct _SP_INF_INFORMATION *,unsigned int,struct _SP_ALTPLATFORM_INFO_V2 *,struct _SP_ORIGINAL_FILE_INFO_W *)` | 422 (0x1a6) | Exported Function | 0x10009840 | 0x00009840
`public: virtual int __thiscall CIlNt4Setupapi::SetupScanFileQueueW(void *,unsigned long,struct HWND__ *,unsigned int (__stdcall*)(void *,unsigned int,unsigned int,unsigned int),void *,unsigned long *)` | 423 (0x1a7) | Exported Function | 0x10009600 | 0x00009600
`public: virtual int __thiscall CIlNt4User32::LockSetForegroundWindow(unsigned int)` | 338 (0x152) | Exported Function | 0x10009e40 | 0x00009e40
`public: virtual int __thiscall CIlNt4Userenv::CreateUserProfileExW(void *,unsigned short const *,unsigned short const *,unsigned short *,unsigned long,int)` | 156 (0x9c) | Exported Function | 0x10009f40 | 0x00009f40
`public: virtual int __thiscall CIlSetupapi::SetupFindFirstLineW(void *,unsigned short const *,unsigned short const *,struct _INFCONTEXT *)` | 415 (0x19f) | Exported Function | 0x10008ae0 | 0x00008ae0
`public: virtual int __thiscall CIlSetupapi::SetupFindNextLine(struct _INFCONTEXT *,struct _INFCONTEXT *)` | 416 (0x1a0) | Exported Function | 0x10008b20 | 0x00008b20
`public: virtual int __thiscall CIlSetupapi::SetupGetLineTextW(struct _INFCONTEXT *,void *,unsigned short const *,unsigned short const *,unsigned short *,unsigned long,unsigned long *)` | 418 (0x1a2) | Exported Function | 0x10008b40 | 0x00008b40
`public: virtual int __thiscall CIlSetupapi::SetupGetStringFieldW(struct _INFCONTEXT *,unsigned long,unsigned short *,unsigned long,unsigned long *)` | 419 (0x1a3) | Exported Function | 0x10008b00 | 0x00008b00
`public: virtual int __thiscall CIlShell32::ShellExecuteExW(struct _SHELLEXECUTEINFOW *)` | 424 (0x1a8) | Exported Function | 0x10009d60 | 0x00009d60
`public: virtual int __thiscall CIlUser32::MessageBoxA(struct HWND__ *,char const *,char const *,unsigned int)` | 343 (0x157) | Exported Function | 0x10009e00 | 0x00009e00
`public: virtual int __thiscall CIlUser32::MessageBoxW(struct HWND__ *,unsigned short const *,unsigned short const *,unsigned int)` | 344 (0x158) | Exported Function | 0x10009de0 | 0x00009de0
`public: virtual int __thiscall CIlUser32::PostMessageW(struct HWND__ *,unsigned int,unsigned int,long)` | 361 (0x169) | Exported Function | 0x10009da0 | 0x00009da0
`public: virtual int __thiscall CIlVersion::GetFileVersionInfoW(unsigned short const *,unsigned long,unsigned long,void *)` | 201 (0xc9) | Exported Function | 0x1000a190 | 0x0000a190
`public: virtual int __thiscall CIlVersion::VerQueryValueW(void * const,unsigned short const *,void * *,unsigned int *)` | 432 (0x1b0) | Exported Function | 0x1000a1b0 | 0x0000a1b0
`public: virtual int __thiscall CIlNt4Setupapi::SetupDiGetDeviceRegistryPropertyW(void *,struct _SP_DEVINFO_DATA *,unsigned long,unsigned long *,unsigned char *,unsigned long,unsigned long *)` | 409 (0x199) | Exported Function | 0x10009900 | 0x00009900
`public: virtual int __thiscall CIlW2kDynWs2_32::getaddrinfo(char const *,char const *,struct addrinfo const *,struct addrinfo * *)` | 537 (0x219) | Exported Function | 0x1000a720 | 0x0000a720
`public: virtual int __thiscall CIlNt4Setupapi::SetupDiGetDeviceInterfaceDetailW(void *,struct _SP_DEVICE_INTERFACE_DATA *,struct _SP_DEVICE_INTERFACE_DETAIL_DATA_W *,unsigned long,unsigned long *,struct _SP_DEVINFO_DATA *)` | 408 (0x198) | Exported Function | 0x10009c20 | 0x00009c20
`public: virtual int __thiscall CIlNt4Setupapi::SetupDiEnumDriverInfoW(void *,struct _SP_DEVINFO_DATA *,unsigned long,unsigned long,struct _SP_DRVINFO_DATA_V2_W *)` | 404 (0x194) | Exported Function | 0x100099d0 | 0x000099d0
`public: virtual int __thiscall CIlNt4Advapi32::ConvertStringSidToSidW(unsigned short *,void * *)` | 143 (0x8f) | Exported Function | 0x100065f0 | 0x000065f0
`public: virtual int __thiscall CIlNt4Advapi32::CreateWellKnownSid(enum WELL_KNOWN_SID_TYPE,void *,void *,unsigned long *)` | 157 (0x9d) | Exported Function | 0x10006820 | 0x00006820
`public: virtual int __thiscall CIlNt4Advapi32::EncryptFileW(unsigned short const *)` | 177 (0xb1) | Exported Function | 0x10007180 | 0x00007180
`public: virtual int __thiscall CIlNt4Advapi32::EnumServicesStatusExW(struct SC_HANDLE__ *,enum _SC_ENUM_TYPE,unsigned long,unsigned long,unsigned char *,unsigned long,unsigned long *,unsigned long *,unsigned long *,unsigned short const *)` | 179 (0xb3) | Exported Function | 0x10006dc0 | 0x00006dc0
`public: virtual int __thiscall CIlNt4Advapi32::InitiateSystemShutdownExW(unsigned short *,unsigned short *,unsigned long,int,int,unsigned long)` | 332 (0x14c) | Exported Function | 0x100070b0 | 0x000070b0
`public: virtual int __thiscall CIlNt4Advapi32::QueryServiceConfigW(struct SC_HANDLE__ *,struct _QUERY_SERVICE_CONFIGW *,unsigned long,unsigned long *)` | 364 (0x16c) | Exported Function | 0x10006a60 | 0x00006a60
`public: virtual int __thiscall CIlNt4Advapi32::StartServiceW(struct SC_HANDLE__ *,unsigned long,unsigned short const * *)` | 426 (0x1aa) | Exported Function | 0x10006d00 | 0x00006d00
`public: virtual int __thiscall CIlNt4Advapi32::UnlockServiceDatabase(void *)` | 429 (0x1ad) | Exported Function | 0x10006f50 | 0x00006f50
`public: virtual int __thiscall CIlNt4Kernel32::GlobalMemoryStatusEx(struct _MEMORYSTATUSEX *)` | 237 (0xed) | Exported Function | 0x10008160 | 0x00008160
`public: virtual int __thiscall CIlNt4Kernel32::Process32FirstW(void *,struct tagPROCESSENTRY32W *)` | 362 (0x16a) | Exported Function | 0x10007f50 | 0x00007f50
`public: virtual int __thiscall CIlNt4Kernel32::Process32NextW(void *,struct tagPROCESSENTRY32W *)` | 363 (0x16b) | Exported Function | 0x10008000 | 0x00008000
`public: virtual int __thiscall CIlNt4Kernel32::RegisterWaitForSingleObject(void * *,void *,void (__stdcall*)(void *,unsigned char),void *,unsigned long,unsigned long)` | 381 (0x17d) | Exported Function | 0x10007dd0 | 0x00007dd0
`public: virtual int __thiscall CIlNt4Setupapi::SetupCloseFileQueue(void *)` | 395 (0x18b) | Exported Function | 0x100096d0 | 0x000096d0
`public: virtual int __thiscall CIlNt4Setupapi::SetupDiBuildDriverInfoList(void *,struct _SP_DEVINFO_DATA *,unsigned long)` | 397 (0x18d) | Exported Function | 0x10009020 | 0x00009020
`public: virtual int __thiscall CIlNt4Setupapi::SetupDiCallClassInstaller(unsigned int,void *,struct _SP_DEVINFO_DATA *)` | 398 (0x18e) | Exported Function | 0x10009330 | 0x00009330
`public: virtual int __thiscall CIlNt4Setupapi::SetupDiDestroyDeviceInfoList(void *)` | 400 (0x190) | Exported Function | 0x100094b0 | 0x000094b0
`public: virtual int __thiscall CIlNt4Setupapi::SetupDiDestroyDriverInfoList(void *,struct _SP_DEVINFO_DATA *,unsigned long)` | 401 (0x191) | Exported Function | 0x10008f60 | 0x00008f60
`public: virtual int __thiscall CIlNt4Setupapi::SetupDiEnumDeviceInfo(void *,unsigned long,struct _SP_DEVINFO_DATA *)` | 402 (0x192) | Exported Function | 0x10008ea0 | 0x00008ea0
`public: virtual int __thiscall CIlNt4Setupapi::SetupDiEnumDeviceInterfaces(void *,struct _SP_DEVINFO_DATA *,struct _GUID const *,unsigned long,struct _SP_DEVICE_INTERFACE_DATA *)` | 403 (0x193) | Exported Function | 0x10009b60 | 0x00009b60
`public: virtual int __thiscall CIlNt4Setupapi::SetupDiGetDeviceInstallParamsW(void *,struct _SP_DEVINFO_DATA *,struct _SP_DEVINSTALL_PARAMS_W *)` | 407 (0x197) | Exported Function | 0x100091b0 | 0x000091b0
`public: virtual int __thiscall CIlNt4Advapi32::ConvertStringSecurityDescriptorToSecurityDescriptorW(unsigned short const *,unsigned long,void * *,unsigned long *)` | 142 (0x8e) | Exported Function | 0x10006760 | 0x00006760
`public: virtual int __thiscall CIlW2kDynWs2_32::getnameinfo(struct sockaddr const *,int,char *,unsigned long,char *,unsigned long,int)` | 540 (0x21c) | Exported Function | 0x1000a650 | 0x0000a650
`public: virtual int __thiscall CIlWimgapi::WIMCloseHandle(void *)` | 436 (0x1b4) | Exported Function | 0x1000a2b0 | 0x0000a2b0
`public: virtual long __thiscall CIlAdvapi32::RegCreateKeyExW(struct HKEY__ *,unsigned short const *,unsigned long,unsigned short *,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES *,struct HKEY__ * *,unsigned long *)` | 368 (0x170) | Exported Function | 0x10005e50 | 0x00005e50
`public: virtual long __thiscall CIlAdvapi32::RegDeleteKeyW(struct HKEY__ *,unsigned short const *)` | 369 (0x171) | Exported Function | 0x10005f30 | 0x00005f30
`public: virtual long __thiscall CIlAdvapi32::RegDeleteValueW(struct HKEY__ *,unsigned short const *)` | 370 (0x172) | Exported Function | 0x10005f50 | 0x00005f50
`public: virtual long __thiscall CIlAdvapi32::RegEnumKeyExW(struct HKEY__ *,unsigned long,unsigned short *,unsigned long *,unsigned long *,unsigned short *,unsigned long *,struct _FILETIME *)` | 371 (0x173) | Exported Function | 0x10005ed0 | 0x00005ed0
`public: virtual long __thiscall CIlAdvapi32::RegEnumValueW(struct HKEY__ *,unsigned long,unsigned short *,unsigned long *,unsigned long *,unsigned long *,unsigned char *,unsigned long *)` | 372 (0x174) | Exported Function | 0x10005f10 | 0x00005f10
`public: virtual long __thiscall CIlAdvapi32::RegFlushKey(struct HKEY__ *)` | 373 (0x175) | Exported Function | 0x10005f90 | 0x00005f90
`public: virtual long __thiscall CIlAdvapi32::RegLoadKeyW(struct HKEY__ *,unsigned short const *,unsigned short const *)` | 374 (0x176) | Exported Function | 0x10005e10 | 0x00005e10
`public: virtual long __thiscall CIlAdvapi32::RegOpenKeyExW(struct HKEY__ *,unsigned short const *,unsigned long,unsigned long,struct HKEY__ * *)` | 375 (0x177) | Exported Function | 0x10005e70 | 0x00005e70
`public: virtual long __thiscall CIlAdvapi32::RegQueryInfoKeyW(struct HKEY__ *,unsigned short *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,unsigned long *,struct _FILETIME *)` | 376 (0x178) | Exported Function | 0x10005eb0 | 0x00005eb0
`public: virtual long __thiscall CIlAdvapi32::RegQueryValueExW(struct HKEY__ *,unsigned short const *,unsigned long *,unsigned long *,unsigned char *,unsigned long *)` | 377 (0x179) | Exported Function | 0x10005e90 | 0x00005e90
`public: virtual long __thiscall CIlAdvapi32::RegSetKeySecurity(struct HKEY__ *,unsigned long,void *)` | 378 (0x17a) | Exported Function | 0x100063b0 | 0x000063b0
`public: virtual long __thiscall CIlAdvapi32::RegSetValueExW(struct HKEY__ *,unsigned short const *,unsigned long,unsigned long,unsigned char const *,unsigned long)` | 379 (0x17b) | Exported Function | 0x10005ef0 | 0x00005ef0
`public: virtual long __thiscall CIlAdvapi32::RegUnLoadKeyW(struct HKEY__ *,unsigned short const *)` | 380 (0x17c) | Exported Function | 0x10005e30 | 0x00005e30
`public: virtual long __thiscall CIlNt6Userenv::CreateProfile(unsigned short const *,unsigned short const *,unsigned short *,unsigned long)` | 151 (0x97) | Exported Function | 0x1000a060 | 0x0000a060
`public: virtual long __thiscall CIlOle32::CoCreateInstance(struct _GUID const &,struct IUnknown *,unsigned long,struct _GUID const &,void * *)` | 134 (0x86) | Exported Function | 0x100089d0 | 0x000089d0
`public: virtual long __thiscall CIlOle32::CoInitialize(void *)` | 135 (0x87) | Exported Function | 0x10008980 | 0x00008980
`public: virtual long __thiscall CIlOle32::CoInitializeEx(void *,unsigned long)` | 136 (0x88) | Exported Function | 0x100089a0 | 0x000089a0
`public: virtual long __thiscall CIlOle32::CreateStreamOnHGlobal(void *,int,struct IStream * *)` | 153 (0x99) | Exported Function | 0x10008a40 | 0x00008a40
`public: virtual long __thiscall CIlOle32::GetHGlobalFromStream(struct IStream *,void * *)` | 203 (0xcb) | Exported Function | 0x10008a20 | 0x00008a20
`public: virtual long __thiscall CIlAdvapi32::RegCloseKey(struct HKEY__ *)` | 367 (0x16f) | Exported Function | 0x10005f70 | 0x00005f70
`public: virtual int __thiscall CIlWimgapi::WIMApplyImage(void *,unsigned short *,unsigned long)` | 435 (0x1b3) | Exported Function | 0x1000a290 | 0x0000a290
`public: virtual int __thiscall CIlWs2_32::WSAStartup(unsigned short,struct WSAData *)` | 445 (0x1bd) | Exported Function | 0x1000a2f0 | 0x0000a2f0
`public: virtual int __thiscall CIlWs2_32::WSAGetLastError(void)` | 443 (0x1bb) | Exported Function | 0x1000a320 | 0x0000a320
`public: virtual int __thiscall CIlWimgapi::WIMSetTemporaryPath(void *,unsigned short *)` | 440 (0x1b8) | Exported Function | 0x1000a210 | 0x0000a210
`public: virtual int __thiscall CIlWimgapi::WIMUnregisterMessageCallback(void *,int (__stdcall*)(void))` | 441 (0x1b9) | Exported Function | 0x1000a270 | 0x0000a270
`public: virtual int __thiscall CIlWs2_32::__WSAFDIsSet(unsigned int,struct fd_set *)` | 449 (0x1c1) | Exported Function | 0x1000a610 | 0x0000a610
`public: virtual int __thiscall CIlWs2_32::bind(unsigned int,struct sockaddr const *,int)` | 451 (0x1c3) | Exported Function | 0x1000a490 | 0x0000a490
`public: virtual int __thiscall CIlWs2_32::closesocket(unsigned int)` | 452 (0x1c4) | Exported Function | 0x1000a350 | 0x0000a350
`public: virtual int __thiscall CIlWs2_32::connect(unsigned int,struct sockaddr const *,int)` | 453 (0x1c5) | Exported Function | 0x1000a590 | 0x0000a590
`public: virtual int __thiscall CIlWs2_32::gethostname(char *,int)` | 539 (0x21b) | Exported Function | 0x1000a3f0 | 0x0000a3f0
`public: virtual int __thiscall CIlWs2_32::getsockname(unsigned int,struct sockaddr *,int *)` | 541 (0x21d) | Exported Function | 0x1000a510 | 0x0000a510
`public: virtual int __thiscall CIlWs2_32::getsockopt(unsigned int,int,int,char *,int *)` | 542 (0x21e) | Exported Function | 0x1000a430 | 0x0000a430
`public: virtual int __thiscall CIlWs2_32::ioctlsocket(unsigned int,long,unsigned long *)` | 547 (0x223) | Exported Function | 0x1000a4b0 | 0x0000a4b0
`public: virtual int __thiscall CIlWs2_32::listen(unsigned int,int)` | 548 (0x224) | Exported Function | 0x1000a4d0 | 0x0000a4d0
`public: virtual int __thiscall CIlWs2_32::recv(unsigned int,char *,int,int)` | 671 (0x29f) | Exported Function | 0x1000a530 | 0x0000a530
`public: virtual int __thiscall CIlWs2_32::recvfrom(unsigned int,char *,int,int,struct sockaddr *,int *)` | 672 (0x2a0) | Exported Function | 0x1000a550 | 0x0000a550
`public: virtual int __thiscall CIlWs2_32::select(int,struct fd_set *,struct fd_set *,struct fd_set *,struct timeval const *)` | 734 (0x2de) | Exported Function | 0x1000a5b0 | 0x0000a5b0
`public: virtual int __thiscall CIlWs2_32::send(unsigned int,char const *,int,int)` | 735 (0x2df) | Exported Function | 0x1000a470 | 0x0000a470
`public: virtual int __thiscall CIlWs2_32::sendto(unsigned int,char const *,int,int,struct sockaddr const *,int)` | 736 (0x2e0) | Exported Function | 0x1000a570 | 0x0000a570
`public: virtual int __thiscall CIlWs2_32::setsockopt(unsigned int,int,int,char const *,int)` | 737 (0x2e1) | Exported Function | 0x1000a450 | 0x0000a450
`public: virtual int __thiscall CIlWs2_32::shutdown(unsigned int,int)` | 738 (0x2e2) | Exported Function | 0x1000a4f0 | 0x0000a4f0
`public: virtual int __thiscall CIlWs2_32::WSACleanup(void)` | 442 (0x1ba) | Exported Function | 0x1000a310 | 0x0000a310
`public: virtual int __thiscall CIlWs2_32::WSAIoctl(unsigned int,unsigned long,void *,unsigned long,void *,unsigned long,unsigned long *,struct _OVERLAPPED *,void (__stdcall*)(unsigned long,unsigned long,struct _OVERLAPPED *,unsigned long))` | 444 (0x1bc) | Exported Function | 0x1000a5f0 | 0x0000a5f0
`public: virtual int __thiscall CIlNt4Advapi32::ConvertSidToStringSidW(void *,unsigned short * *)` | 141 (0x8d) | Exported Function | 0x10006540 | 0x00006540
`public: virtual int __thiscall CIlNt4Advapi32::ConvertSecurityDescriptorToStringSecurityDescriptorW(void *,unsigned long,unsigned long,unsigned short * *,unsigned long *)` | 140 (0x8c) | Exported Function | 0x100066a0 | 0x000066a0
`public: virtual int __thiscall CIlNt4Advapi32::CloseServiceHandle(struct SC_HANDLE__ *)` | 133 (0x85) | Exported Function | 0x10007000 | 0x00007000
`public: virtual int __thiscall CIlAdvapi32::CryptDecrypt(unsigned long,unsigned long,int,unsigned long,unsigned char *,unsigned long *)` | 160 (0xa0) | Exported Function | 0x100062b0 | 0x000062b0
`public: virtual int __thiscall CIlAdvapi32::CryptDeriveKey(unsigned long,unsigned int,unsigned long,unsigned long,unsigned long *)` | 161 (0xa1) | Exported Function | 0x100061d0 | 0x000061d0
`public: virtual int __thiscall CIlAdvapi32::CryptDestroyHash(unsigned long)` | 162 (0xa2) | Exported Function | 0x100062f0 | 0x000062f0
`public: virtual int __thiscall CIlAdvapi32::CryptDestroyKey(unsigned long)` | 163 (0xa3) | Exported Function | 0x100062d0 | 0x000062d0
`public: virtual int __thiscall CIlAdvapi32::CryptDuplicateHash(unsigned long,unsigned long *,unsigned long,unsigned long *)` | 164 (0xa4) | Exported Function | 0x10006190 | 0x00006190
`public: virtual int __thiscall CIlAdvapi32::CryptDuplicateKey(unsigned long,unsigned long *,unsigned long,unsigned long *)` | 165 (0xa5) | Exported Function | 0x100061f0 | 0x000061f0
`public: virtual int __thiscall CIlAdvapi32::CryptEncrypt(unsigned long,unsigned long,int,unsigned long,unsigned char *,unsigned long *,unsigned long)` | 166 (0xa6) | Exported Function | 0x10006290 | 0x00006290
`public: virtual int __thiscall CIlAdvapi32::CryptGenRandom(unsigned long,unsigned long,unsigned char *)` | 167 (0xa7) | Exported Function | 0x10006210 | 0x00006210
`public: virtual int __thiscall CIlAdvapi32::CryptGetHashParam(unsigned long,unsigned long,unsigned char *,unsigned long *,unsigned long)` | 168 (0xa8) | Exported Function | 0x10006230 | 0x00006230
`public: virtual int __thiscall CIlAdvapi32::CryptGetKeyParam(unsigned long,unsigned long,unsigned char *,unsigned long *,unsigned long)` | 169 (0xa9) | Exported Function | 0x10006250 | 0x00006250
`public: virtual int __thiscall CIlAdvapi32::CryptHashData(unsigned long,unsigned char const *,unsigned long,unsigned long)` | 170 (0xaa) | Exported Function | 0x100061b0 | 0x000061b0
`public: virtual int __thiscall CIlAdvapi32::CryptReleaseContext(unsigned long,unsigned long)` | 171 (0xab) | Exported Function | 0x10006310 | 0x00006310
`public: virtual int __thiscall CIlAdvapi32::CryptSetKeyParam(unsigned long,unsigned long,unsigned char const *,unsigned long)` | 172 (0xac) | Exported Function | 0x10006270 | 0x00006270
`public: virtual int __thiscall CIlAdvapi32::EqualSid(void *,void *)` | 180 (0xb4) | Exported Function | 0x100060b0 | 0x000060b0
`public: virtual int __thiscall CIlAdvapi32::GetSecurityDescriptorDacl(void *,int *,struct _ACL * *,int *)` | 214 (0xd6) | Exported Function | 0x10006370 | 0x00006370
`public: virtual int __thiscall CIlAdvapi32::GetSecurityDescriptorGroup(void *,void * *,int *)` | 215 (0xd7) | Exported Function | 0x10006350 | 0x00006350
`public: virtual int __thiscall CIlAdvapi32::GetSecurityDescriptorOwner(void *,void * *,int *)` | 216 (0xd8) | Exported Function | 0x10006330 | 0x00006330
`public: virtual int __thiscall CIlAdvapi32::GetSecurityDescriptorSacl(void *,int *,struct _ACL * *,int *)` | 217 (0xd9) | Exported Function | 0x10006390 | 0x00006390
`public: virtual int __thiscall CIlAdvapi32::GetTokenInformation(void *,enum _TOKEN_INFORMATION_CLASS,void *,unsigned long,unsigned long *)` | 225 (0xe1) | Exported Function | 0x10006030 | 0x00006030
`public: virtual int __thiscall CIlAdvapi32::CryptCreateHash(unsigned long,unsigned int,unsigned long,unsigned long,unsigned long *)` | 159 (0x9f) | Exported Function | 0x10006170 | 0x00006170
`public: virtual int __thiscall CIlAdvapi32::GetUserNameW(unsigned short *,unsigned long *)` | 228 (0xe4) | Exported Function | 0x10005fb0 | 0x00005fb0
`public: virtual int __thiscall CIlAdvapi32::CryptAcquireContextW(unsigned long *,unsigned short const *,unsigned short const *,unsigned long,unsigned long)` | 158 (0x9e) | Exported Function | 0x10006150 | 0x00006150
`public: virtual int __thiscall CIlAdvapi32::AdjustTokenPrivileges(void *,int,struct _TOKEN_PRIVILEGES *,unsigned long,struct _TOKEN_PRIVILEGES *,unsigned long *)` | 129 (0x81) | Exported Function | 0x10006130 | 0x00006130
`public: long (__stdcall*__thiscall CIlNt6Userenv::get_CreateProfile(void))(unsigned short const *,unsigned short const *,unsigned short *,unsigned long)` | 482 (0x1e2) | Exported Function | 0x1000a0d0 | 0x0000a0d0
`public: struct HKEY__ * (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiOpenDevRegKey(void))(void *,struct _SP_DEVINFO_DATA *,unsigned long,unsigned long,unsigned long,unsigned long)` | 524 (0x20c) | Exported Function | 0x10009b10 | 0x00009b10
`public: struct SC_HANDLE__ * (__stdcall*__thiscall CIlNt4Advapi32::get_CreateServiceW(void))(struct SC_HANDLE__ *,unsigned short const *,unsigned short const *,unsigned long,unsigned long,unsigned long,unsigned long,unsigned short const *,unsigned short const *,unsigned long *,unsigned short const *,unsigned short const *,unsigned short const *)` | 483 (0x1e3) | Exported Function | 0x10006cb0 | 0x00006cb0
`public: struct SC_HANDLE__ * (__stdcall*__thiscall CIlNt4Advapi32::get_OpenSCManagerW(void))(unsigned short const *,unsigned short const *,unsigned long)` | 503 (0x1f7) | Exported Function | 0x10006950 | 0x00006950
`public: struct SC_HANDLE__ * (__stdcall*__thiscall CIlNt4Advapi32::get_OpenServiceW(void))(struct SC_HANDLE__ *,unsigned short const *,unsigned long)` | 504 (0x1f8) | Exported Function | 0x10006a10 | 0x00006a10
`public: unsigned int (__stdcall*__thiscall CIlNt4Kernel32::get_GetSystemWindowsDirectoryW(void))(unsigned short *,unsigned int)` | 489 (0x1e9) | Exported Function | 0x10008110 | 0x00008110
`public: unsigned long (__stdcall*__thiscall CIlNt4Netapi32::get_NetApiBufferFree(void))(void *)` | 494 (0x1ee) | Exported Function | 0x100088e0 | 0x000088e0
`public: unsigned long (__stdcall*__thiscall CIlNt4Netapi32::get_NetLocalGroupAdd(void))(unsigned short const *,unsigned long,unsigned char *,unsigned long *)` | 495 (0x1ef) | Exported Function | 0x10008760 | 0x00008760
`public: unsigned long (__stdcall*__thiscall CIlNt4Netapi32::get_NetLocalGroupAddMembers(void))(unsigned short const *,unsigned short const *,unsigned long,unsigned char *,unsigned long)` | 496 (0x1f0) | Exported Function | 0x100086a0 | 0x000086a0
`public: unsigned long (__stdcall*__thiscall CIlNt4Netapi32::get_NetLocalGroupEnum(void))(unsigned short const *,unsigned long,unsigned char * *,unsigned long,unsigned long *,unsigned long *,unsigned long *)` | 497 (0x1f1) | Exported Function | 0x10008830 | 0x00008830
`public: unsigned long (__stdcall*__thiscall CIlNt4Netapi32::get_NetUserAdd(void))(unsigned short const *,unsigned long,unsigned char *,unsigned long *)` | 498 (0x1f2) | Exported Function | 0x10008390 | 0x00008390
`public: unsigned long (__stdcall*__thiscall CIlNt4Netapi32::get_NetUserDel(void))(unsigned short const *,unsigned short const *)` | 499 (0x1f3) | Exported Function | 0x10008440 | 0x00008440
`public: unsigned long (__stdcall*__thiscall CIlNt4Netapi32::get_NetUserEnum(void))(unsigned short const *,unsigned long,unsigned long,unsigned char * *,unsigned long,unsigned long *,unsigned long *,unsigned long *)` | 500 (0x1f4) | Exported Function | 0x10008510 | 0x00008510
`public: unsigned long (__stdcall*__thiscall CIlNt4Netapi32::get_NetUserGetLocalGroups(void))(unsigned short const *,unsigned short const *,unsigned long,unsigned long,unsigned char * *,unsigned long,unsigned long *,unsigned long *)` | 501 (0x1f5) | Exported Function | 0x100085e0 | 0x000085e0
`public: unsigned long (__stdcall*__thiscall CIlNt4Netapi32::get_NetWkstaGetInfo(void))(unsigned short *,unsigned long,unsigned char * *)` | 502 (0x1f6) | Exported Function | 0x100082d0 | 0x000082d0
`public: virtual char * __thiscall CIlWs2_32::inet_ntoa(struct in_addr)` | 546 (0x222) | Exported Function | 0x1000a390 | 0x0000a390
`public: virtual int (__stdcall*__thiscall CIlKernel32::GetProcAddress(struct HINSTANCE__ *,char const *))(void)` | 212 (0xd4) | Exported Function | 0x10007cb0 | 0x00007cb0
`public: virtual int (__stdcall*__thiscall CIlW2kDynWs2_32::get_getaddrinfo(void))(char const *,char const *,struct addrinfo const *,struct addrinfo * *)` | 535 (0x217) | Exported Function | 0x1000a790 | 0x0000a790
`public: virtual int (__stdcall*__thiscall CIlW2kDynWs2_32::get_getnameinfo(void))(struct sockaddr const *,int,char *,unsigned long,char *,unsigned long,int)` | 536 (0x218) | Exported Function | 0x1000a6d0 | 0x0000a6d0
`public: virtual int __thiscall CIlAdvapi32::AllocateAndInitializeSid(struct _SID_IDENTIFIER_AUTHORITY *,unsigned char,unsigned long,unsigned long,unsigned long,unsigned long,unsigned long,unsigned long,unsigned long,unsigned long,void * *)` | 130 (0x82) | Exported Function | 0x10006050 | 0x00006050
`public: virtual int __thiscall CIlAdvapi32::InitializeSecurityDescriptor(void *,unsigned long)` | 331 (0x14b) | Exported Function | 0x100063f0 | 0x000063f0
`public: virtual int __thiscall CIlAdvapi32::IsValidSid(void *)` | 333 (0x14d) | Exported Function | 0x10006090 | 0x00006090
`public: virtual int __thiscall CIlAdvapi32::LookupAccountNameW(unsigned short const *,unsigned short const *,void *,unsigned long *,unsigned short *,unsigned long *,enum _SID_NAME_USE *)` | 339 (0x153) | Exported Function | 0x10005fd0 | 0x00005fd0
`public: virtual int __thiscall CIlKernel32::GlobalUnlock(void *)` | 239 (0xef) | Exported Function | 0x10007550 | 0x00007550
`public: virtual int __thiscall CIlKernel32::HeapDestroy(void *)` | 243 (0xf3) | Exported Function | 0x10007430 | 0x00007430
`public: virtual int __thiscall CIlKernel32::HeapFree(void *,unsigned long,void *)` | 244 (0xf4) | Exported Function | 0x10007490 | 0x00007490
`public: virtual int __thiscall CIlKernel32::HeapValidate(void *,unsigned long,void const *)` | 246 (0xf6) | Exported Function | 0x100074d0 | 0x000074d0
`public: virtual int __thiscall CIlKernel32::HeapWalk(void *,struct _PROCESS_HEAP_ENTRY *)` | 247 (0xf7) | Exported Function | 0x100074f0 | 0x000074f0
`public: virtual int __thiscall CIlKernel32::MoveFileExW(unsigned short const *,unsigned short const *,unsigned long)` | 345 (0x159) | Exported Function | 0x10007600 | 0x00007600
`public: virtual int __thiscall CIlKernel32::MoveFileW(unsigned short const *,unsigned short const *)` | 346 (0x15a) | Exported Function | 0x100075e0 | 0x000075e0
`public: virtual int __thiscall CIlKernel32::ReadFile(void *,void *,unsigned long,unsigned long *,struct _OVERLAPPED *)` | 366 (0x16e) | Exported Function | 0x100076b0 | 0x000076b0
`public: virtual int __thiscall CIlKernel32::RemoveDirectoryW(unsigned short const *)` | 383 (0x17f) | Exported Function | 0x10007850 | 0x00007850
`public: virtual int __thiscall CIlKernel32::ResetEvent(void *)` | 384 (0x180) | Exported Function | 0x10007ab0 | 0x00007ab0
`public: virtual int __thiscall CIlKernel32::SetEndOfFile(void *)` | 385 (0x181) | Exported Function | 0x100079e0 | 0x000079e0
`public: virtual int __thiscall CIlKernel32::SetEvent(void *)` | 387 (0x183) | Exported Function | 0x10007a90 | 0x00007a90
`public: virtual int __thiscall CIlKernel32::SetFileAttributesW(unsigned short const *,unsigned long)` | 388 (0x184) | Exported Function | 0x100077b0 | 0x000077b0
`public: virtual int __thiscall CIlKernel32::SetFileTime(void *,struct _FILETIME const *,struct _FILETIME const *,struct _FILETIME const *)` | 390 (0x186) | Exported Function | 0x100079c0 | 0x000079c0
`public: virtual int __thiscall CIlKernel32::TerminateProcess(void *,unsigned int)` | 428 (0x1ac) | Exported Function | 0x10007960 | 0x00007960
`public: virtual int __thiscall CIlKernel32::UnmapViewOfFile(void const *)` | 430 (0x1ae) | Exported Function | 0x10007c40 | 0x00007c40
`public: virtual int __thiscall CIlKernel32::VirtualFree(void *,unsigned long,unsigned long)` | 434 (0x1b2) | Exported Function | 0x10007da0 | 0x00007da0
`public: virtual int __thiscall CIlKernel32::WriteFile(void *,void const *,unsigned long,unsigned long *,struct _OVERLAPPED *)` | 448 (0x1c0) | Exported Function | 0x100076d0 | 0x000076d0
`public: virtual int __thiscall CIlNt4Advapi32::ChangeServiceConfigW(struct SC_HANDLE__ *,unsigned long,unsigned long,unsigned long,unsigned short const *,unsigned short const *,unsigned long *,unsigned short const *,unsigned short const *,unsigned short const *,unsigned short const *)` | 131 (0x83) | Exported Function | 0x10006b20 | 0x00006b20
`public: virtual int __thiscall CIlKernel32::GetVolumeInformationW(unsigned short const *,unsigned short *,unsigned long,unsigned long *,unsigned long *,unsigned long *,unsigned short *,unsigned long)` | 231 (0xe7) | Exported Function | 0x100079a0 | 0x000079a0
`public: virtual int __thiscall CIlKernel32::GetVersionExW(struct _OSVERSIONINFOW *)` | 230 (0xe6) | Exported Function | 0x100073b0 | 0x000073b0
`public: virtual int __thiscall CIlKernel32::GetVersionExA(struct _OSVERSIONINFOA *)` | 229 (0xe5) | Exported Function | 0x10007390 | 0x00007390
`public: virtual int __thiscall CIlKernel32::GetOverlappedResult(void *,struct _OVERLAPPED *,unsigned long *,int)` | 210 (0xd2) | Exported Function | 0x10007b40 | 0x00007b40
`public: virtual int __thiscall CIlAdvapi32::LookupAccountSidW(unsigned short const *,void *,unsigned short *,unsigned long *,unsigned short *,unsigned long *,enum _SID_NAME_USE *)` | 340 (0x154) | Exported Function | 0x10005ff0 | 0x00005ff0
`public: virtual int __thiscall CIlAdvapi32::LookupPrivilegeValueW(unsigned short const *,unsigned short const *,struct _LUID *)` | 341 (0x155) | Exported Function | 0x10006110 | 0x00006110
`public: virtual int __thiscall CIlAdvapi32::OpenProcessToken(void *,unsigned long,void * *)` | 358 (0x166) | Exported Function | 0x10006010 | 0x00006010
`public: virtual int __thiscall CIlAdvapi32::SetSecurityDescriptorOwner(void *,void *,int)` | 393 (0x189) | Exported Function | 0x100063d0 | 0x000063d0
`public: virtual int __thiscall CIlDeplorch::SysprepIsStagedOS(void)` | 427 (0x1ab) | Exported Function | 0x100072a0 | 0x000072a0
`public: virtual int __thiscall CIlKernel32::CloseHandle(void *)` | 132 (0x84) | Exported Function | 0x10007640 | 0x00007640
`public: virtual int __thiscall CIlKernel32::CopyFileW(unsigned short const *,unsigned short const *,int)` | 144 (0x90) | Exported Function | 0x100075b0 | 0x000075b0
`public: virtual int __thiscall CIlKernel32::CreateDirectoryW(unsigned short const *,struct _SECURITY_ATTRIBUTES *)` | 145 (0x91) | Exported Function | 0x10007770 | 0x00007770
`public: virtual int __thiscall CIlKernel32::CreateProcessA(char const *,char *,struct _SECURITY_ATTRIBUTES *,struct _SECURITY_ATTRIBUTES *,int,unsigned long,void *,char const *,struct _STARTUPINFOA *,struct _PROCESS_INFORMATION *)` | 149 (0x95) | Exported Function | 0x10007900 | 0x00007900
`public: virtual long __thiscall CIlOleaut32::VariantClear(struct tagVARIANT *)` | 431 (0x1af) | Exported Function | 0x10008a80 | 0x00008a80
`public: virtual int __thiscall CIlKernel32::CreateProcessW(unsigned short const *,unsigned short *,struct _SECURITY_ATTRIBUTES *,struct _SECURITY_ATTRIBUTES *,int,unsigned long,void *,unsigned short const *,struct _STARTUPINFOW *,struct _PROCESS_INFORMATION *)` | 150 (0x96) | Exported Function | 0x100078e0 | 0x000078e0
`public: virtual int __thiscall CIlKernel32::DuplicateHandle(void *,void *,void *,void * *,unsigned long,int,unsigned long)` | 176 (0xb0) | Exported Function | 0x10007710 | 0x00007710
`public: virtual int __thiscall CIlKernel32::FindClose(void *)` | 184 (0xb8) | Exported Function | 0x100078c0 | 0x000078c0
`public: virtual int __thiscall CIlKernel32::FindNextFileW(void *,struct _WIN32_FIND_DATAW *)` | 186 (0xba) | Exported Function | 0x100078a0 | 0x000078a0
`public: virtual int __thiscall CIlKernel32::FreeLibrary(struct HINSTANCE__ *)` | 187 (0xbb) | Exported Function | 0x10007cd0 | 0x00007cd0
`public: virtual int __thiscall CIlKernel32::GetComputerNameW(unsigned short *,unsigned long *)` | 190 (0xbe) | Exported Function | 0x10007ae0 | 0x00007ae0
`public: virtual int __thiscall CIlKernel32::GetDiskFreeSpaceExW(unsigned short const *,union _ULARGE_INTEGER *,union _ULARGE_INTEGER *,union _ULARGE_INTEGER *)` | 193 (0xc1) | Exported Function | 0x10007be0 | 0x00007be0
`public: virtual int __thiscall CIlKernel32::GetDiskFreeSpaceW(unsigned short const *,unsigned long *,unsigned long *,unsigned long *,unsigned long *)` | 194 (0xc2) | Exported Function | 0x10007bc0 | 0x00007bc0
`public: virtual int __thiscall CIlKernel32::GetExitCodeProcess(void *,unsigned long *)` | 196 (0xc4) | Exported Function | 0x10007d20 | 0x00007d20
`public: virtual int __thiscall CIlKernel32::GetLocaleInfoW(unsigned long,unsigned long,unsigned short *,int)` | 207 (0xcf) | Exported Function | 0x10007d60 | 0x00007d60
`public: virtual int __thiscall CIlKernel32::DeleteFileW(unsigned short const *)` | 175 (0xaf) | Exported Function | 0x10007730 | 0x00007730
`public: int (__stdcall*__thiscall CIlNt4Userenv::get_CreateUserProfileExW(void))(void *,unsigned short const *,unsigned short const *,unsigned short *,unsigned long,int)` | 485 (0x1e5) | Exported Function | 0x10009fc0 | 0x00009fc0
`public: virtual struct HICON__ * __thiscall CIlUser32::LoadIconW(struct HINSTANCE__ *,unsigned short const *)` | 335 (0x14f) | Exported Function | 0x10009dc0 | 0x00009dc0
`public: virtual struct HKEY__ * __thiscall CIlNt4Setupapi::SetupDiOpenDevRegKey(void *,struct _SP_DEVINFO_DATA *,unsigned long,unsigned long,unsigned long,unsigned long)` | 411 (0x19b) | Exported Function | 0x10009a90 | 0x00009a90
`public: void __thiscall CIlNt4Advapi32::release_OpenSCManagerW(void)` | 700 (0x2bc) | Exported Function | 0x10006980 | 0x00006980
`public: void __thiscall CIlNt4Advapi32::release_OpenServiceW(void)` | 701 (0x2bd) | Exported Function | 0x10006a40 | 0x00006a40
`public: void __thiscall CIlNt4Advapi32::release_QueryServiceConfigW(void)` | 704 (0x2c0) | Exported Function | 0x10006b00 | 0x00006b00
`public: void __thiscall CIlNt4Advapi32::release_StartServiceW(void)` | 729 (0x2d9) | Exported Function | 0x10006da0 | 0x00006da0
`public: void __thiscall CIlNt4Advapi32::release_UnlockServiceDatabase(void)` | 730 (0x2da) | Exported Function | 0x10006fe0 | 0x00006fe0
`public: void __thiscall CIlNt4Kernel32::release_CreateToolhelp32Snapshot(void)` | 681 (0x2a9) | Exported Function | 0x10007f30 | 0x00007f30
`public: void __thiscall CIlNt4Kernel32::release_GetSystemWindowsDirectoryW(void)` | 686 (0x2ae) | Exported Function | 0x10008140 | 0x00008140
`public: void __thiscall CIlNt4Kernel32::release_GlobalMemoryStatusEx(void)` | 687 (0x2af) | Exported Function | 0x100081f0 | 0x000081f0
`public: void __thiscall CIlNt4Kernel32::release_Process32FirstW(void)` | 702 (0x2be) | Exported Function | 0x10007fe0 | 0x00007fe0
`public: void __thiscall CIlNt4Kernel32::release_Process32NextW(void)` | 703 (0x2bf) | Exported Function | 0x10008090 | 0x00008090
`public: void __thiscall CIlNt4Kernel32::release_RegisterWaitForSingleObject(void)` | 705 (0x2c1) | Exported Function | 0x10007e80 | 0x00007e80
`public: void __thiscall CIlNt4Netapi32::release_NetApiBufferFree(void)` | 691 (0x2b3) | Exported Function | 0x10008910 | 0x00008910
`public: void __thiscall CIlNt4Netapi32::release_NetLocalGroupAdd(void)` | 692 (0x2b4) | Exported Function | 0x10008790 | 0x00008790
`public: void __thiscall CIlNt4Netapi32::release_NetLocalGroupAddMembers(void)` | 693 (0x2b5) | Exported Function | 0x100086d0 | 0x000086d0
`public: void __thiscall CIlNt4Netapi32::release_NetLocalGroupEnum(void)` | 694 (0x2b6) | Exported Function | 0x10008860 | 0x00008860
`public: void __thiscall CIlNt4Netapi32::release_NetUserAdd(void)` | 695 (0x2b7) | Exported Function | 0x100083c0 | 0x000083c0
`public: void __thiscall CIlNt4Netapi32::release_NetUserDel(void)` | 696 (0x2b8) | Exported Function | 0x10008470 | 0x00008470
`public: void __thiscall CIlNt4Netapi32::release_NetUserEnum(void)` | 697 (0x2b9) | Exported Function | 0x10008540 | 0x00008540
`public: void __thiscall CIlNt4Netapi32::release_NetUserGetLocalGroups(void)` | 698 (0x2ba) | Exported Function | 0x10008610 | 0x00008610
`public: void __thiscall CIlNt4Advapi32::release_LockServiceDatabase(void)` | 689 (0x2b1) | Exported Function | 0x10006f30 | 0x00006f30
`public: void __thiscall CIlNt4Netapi32::release_NetWkstaGetInfo(void)` | 699 (0x2bb) | Exported Function | 0x10008300 | 0x00008300
`public: void __thiscall CIlNt4Advapi32::release_InitiateSystemShutdownExW(void)` | 688 (0x2b0) | Exported Function | 0x10007160 | 0x00007160
`public: void __thiscall CIlNt4Advapi32::release_EncryptFileW(void)` | 684 (0x2ac) | Exported Function | 0x10007210 | 0x00007210
`public: virtual void __thiscall CIlSetupapi::SetupCloseInfFile(void *)` | 396 (0x18c) | Exported Function | 0x10008b60 | 0x00008b60
`public: virtual void __thiscall CIlW2kDynWs2_32::freeaddrinfo(struct addrinfo *)` | 454 (0x1c6) | Exported Function | 0x1000a7e0 | 0x0000a7e0
`public: virtual void __thiscall CIlW2kDynWs2_32::release_freeaddrinfo(void)` | 731 (0x2db) | Exported Function | 0x1000a870 | 0x0000a870
`public: virtual void __thiscall CIlW2kDynWs2_32::release_getaddrinfo(void)` | 732 (0x2dc) | Exported Function | 0x1000a7c0 | 0x0000a7c0
`public: virtual void __thiscall CIlW2kDynWs2_32::release_getnameinfo(void)` | 733 (0x2dd) | Exported Function | 0x1000a700 | 0x0000a700
`public: void * (__stdcall*__thiscall CIlNt4Advapi32::get_LockServiceDatabase(void))(struct SC_HANDLE__ *)` | 492 (0x1ec) | Exported Function | 0x10006f00 | 0x00006f00
`public: void * (__stdcall*__thiscall CIlNt4Kernel32::get_CreateToolhelp32Snapshot(void))(unsigned long,unsigned long)` | 484 (0x1e4) | Exported Function | 0x10007f00 | 0x00007f00
`public: void * (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiCreateDeviceInfoListExW(void))(struct _GUID const *,struct HWND__ *,unsigned short const *,void *)` | 512 (0x200) | Exported Function | 0x10008c00 | 0x00008c00
`public: void * (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiGetClassDevsExW(void))(struct _GUID const *,unsigned short const *,struct HWND__ *,unsigned long,void *,unsigned short const *,void *)` | 518 (0x206) | Exported Function | 0x10008cd0 | 0x00008cd0
`public: void * (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiGetClassDevsW(void))(struct _GUID const *,unsigned short const *,struct HWND__ *,unsigned long)` | 519 (0x207) | Exported Function | 0x10008d90 | 0x00008d90
`public: void * (__stdcall*__thiscall CIlNt4Setupapi::get_SetupOpenFileQueue(void))(void)` | 529 (0x211) | Exported Function | 0x100095b0 | 0x000095b0
`public: void __thiscall CIlNt4Advapi32::release_ChangeServiceConfigW(void)` | 673 (0x2a1) | Exported Function | 0x10006bf0 | 0x00006bf0
`public: void __thiscall CIlNt4Advapi32::release_CloseServiceHandle(void)` | 674 (0x2a2) | Exported Function | 0x10007090 | 0x00007090
`public: void __thiscall CIlNt4Advapi32::release_ConvertSecurityDescriptorToStringSecurityDescriptorW(void)` | 675 (0x2a3) | Exported Function | 0x10006740 | 0x00006740
`public: void __thiscall CIlNt4Advapi32::release_ConvertSidToStringSidW(void)` | 676 (0x2a4) | Exported Function | 0x100065d0 | 0x000065d0
`public: void __thiscall CIlNt4Advapi32::release_ConvertStringSecurityDescriptorToSecurityDescriptorW(void)` | 677 (0x2a5) | Exported Function | 0x10006800 | 0x00006800
`public: void __thiscall CIlNt4Advapi32::release_ConvertStringSidToSidW(void)` | 678 (0x2a6) | Exported Function | 0x10006680 | 0x00006680
`public: void __thiscall CIlNt4Advapi32::release_CreateServiceW(void)` | 680 (0x2a8) | Exported Function | 0x10006ce0 | 0x00006ce0
`public: void __thiscall CIlNt4Advapi32::release_CreateWellKnownSid(void)` | 683 (0x2ab) | Exported Function | 0x100068c0 | 0x000068c0
`public: void __thiscall CIlNt4Advapi32::release_EnumServicesStatusExW(void)` | 685 (0x2ad) | Exported Function | 0x10006e80 | 0x00006e80
`public: virtual void __thiscall CIlOle32::CoUninitialize(void)` | 139 (0x8b) | Exported Function | 0x100089c0 | 0x000089c0
`public: void __thiscall CIlNt4Setupapi::release_SetupCloseFileQueue(void)` | 706 (0x2c2) | Exported Function | 0x10009760 | 0x00009760
`public: void __thiscall CIlNt4Setupapi::release_SetupDiCallClassInstaller(void)` | 708 (0x2c4) | Exported Function | 0x100093d0 | 0x000093d0
`struct IAdvapi32Interface * g_Advapi32` | 455 (0x1c7) | Exported Function | 0x10019014 | 0x00019014
`struct IDeplorchInterface * g_Deplorch` | 456 (0x1c8) | Exported Function | 0x1001902c | 0x0001902c
`struct IIphlpapiInterface * g_Iphlpapi` | 457 (0x1c9) | Exported Function | 0x10019008 | 0x00019008
`struct IKernel32Interface * g_Kernel32` | 458 (0x1ca) | Exported Function | 0x10019028 | 0x00019028
`struct IlW2kDynWs2_32Interface * g_W2kWs2_32` | 473 (0x1d9) | Exported Function | 0x10019048 | 0x00019048
`struct IMuisetupapiInterface * g_Muisetupapi` | 459 (0x1cb) | Exported Function | 0x10019050 | 0x00019050
`struct INt6UserenvInterface * g_Nt6Userenv` | 466 (0x1d2) | Exported Function | 0x10019004 | 0x00019004
`struct IOle32Interface * g_Ole32` | 467 (0x1d3) | Exported Function | 0x10019018 | 0x00019018
`struct IOleaut32Interface * g_Oleaut32` | 468 (0x1d4) | Exported Function | 0x1001901c | 0x0001901c
`struct ISetupapiInterface * g_Setupapi` | 469 (0x1d5) | Exported Function | 0x10019010 | 0x00019010
`struct IShell32Interface * g_Shell32` | 470 (0x1d6) | Exported Function | 0x10019034 | 0x00019034
`struct IUser32Interface * g_User32` | 471 (0x1d7) | Exported Function | 0x10019030 | 0x00019030
`struct IVersionInterface * g_Version` | 472 (0x1d8) | Exported Function | 0x1001903c | 0x0001903c
`struct IW2kAdvapi32Interface * g_Nt4Advapi32` | 460 (0x1cc) | Exported Function | 0x10019038 | 0x00019038
`struct IW2kKernel32Interface * g_Nt4Kernel32` | 461 (0x1cd) | Exported Function | 0x10019044 | 0x00019044
`struct IW2kNetapi32Interface * g_Nt4Netapi32` | 462 (0x1ce) | Exported Function | 0x10019020 | 0x00019020
`struct IW2kSetupapiInterface * g_Nt4Setupapi` | 463 (0x1cf) | Exported Function | 0x1001904c | 0x0001904c
`struct IW2kUser32Interface * g_Nt4User32` | 464 (0x1d0) | Exported Function | 0x10019024 | 0x00019024
`struct IW2kUserenvInterface * g_Nt4Userenv` | 465 (0x1d1) | Exported Function | 0x10019000 | 0x00019000
`public: void __thiscall CIlNt6Userenv::release_CreateProfile(void)` | 679 (0x2a7) | Exported Function | 0x1000a100 | 0x0000a100
`public: void __thiscall CIlNt4Setupapi::release_SetupDiBuildDriverInfoList(void)` | 707 (0x2c3) | Exported Function | 0x100090c0 | 0x000090c0
`public: void __thiscall CIlNt4Userenv::release_CreateUserProfileExW(void)` | 682 (0x2aa) | Exported Function | 0x10009ff0 | 0x00009ff0
`public: void __thiscall CIlNt4Setupapi::release_SetupScanFileQueueW(void)` | 728 (0x2d8) | Exported Function | 0x100096b0 | 0x000096b0
`public: void __thiscall CIlNt4Setupapi::release_SetupDiCreateDeviceInfoListExW(void)` | 709 (0x2c5) | Exported Function | 0x10008c30 | 0x00008c30
`public: void __thiscall CIlNt4Setupapi::release_SetupDiDestroyDeviceInfoList(void)` | 710 (0x2c6) | Exported Function | 0x10009540 | 0x00009540
`public: void __thiscall CIlNt4Setupapi::release_SetupDiDestroyDriverInfoList(void)` | 711 (0x2c7) | Exported Function | 0x10009000 | 0x00009000
`public: void __thiscall CIlNt4Setupapi::release_SetupDiEnumDeviceInfo(void)` | 712 (0x2c8) | Exported Function | 0x10008f40 | 0x00008f40
`public: void __thiscall CIlNt4Setupapi::release_SetupDiEnumDeviceInterfaces(void)` | 713 (0x2c9) | Exported Function | 0x10009c00 | 0x00009c00
`public: void __thiscall CIlNt4Setupapi::release_SetupDiEnumDriverInfoW(void)` | 714 (0x2ca) | Exported Function | 0x10009a70 | 0x00009a70
`public: void __thiscall CIlNt4Setupapi::release_SetupDiGetClassDevsExW(void)` | 715 (0x2cb) | Exported Function | 0x10008d00 | 0x00008d00
`public: void __thiscall CIlNt4Setupapi::release_SetupDiGetClassDevsW(void)` | 716 (0x2cc) | Exported Function | 0x10008dc0 | 0x00008dc0
`public: void __thiscall CIlNt4Setupapi::release_SetupDiGetDeviceInstallParamsW(void)` | 717 (0x2cd) | Exported Function | 0x10009250 | 0x00009250
`public: void __thiscall CIlNt4Setupapi::release_SetupDiGetDeviceInterfaceDetailW(void)` | 718 (0x2ce) | Exported Function | 0x10009cd0 | 0x00009cd0
`public: void __thiscall CIlNt4Setupapi::release_SetupDiGetDeviceRegistryPropertyW(void)` | 719 (0x2cf) | Exported Function | 0x100099b0 | 0x000099b0
`public: void __thiscall CIlNt4Setupapi::release_SetupDiGetDriverInfoDetailW(void)` | 720 (0x2d0) | Exported Function | 0x10009190 | 0x00009190
`public: void __thiscall CIlNt4Setupapi::release_SetupDiOpenDeviceInfoW(void)` | 722 (0x2d2) | Exported Function | 0x10008e80 | 0x00008e80
`public: void __thiscall CIlNt4Setupapi::release_SetupDiOpenDevRegKey(void)` | 721 (0x2d1) | Exported Function | 0x10009b40 | 0x00009b40
`public: void __thiscall CIlNt4Setupapi::release_SetupDiSetDeviceInstallParamsW(void)` | 723 (0x2d3) | Exported Function | 0x10009310 | 0x00009310
`public: void __thiscall CIlNt4Setupapi::release_SetupDiSetSelectedDriverW(void)` | 724 (0x2d4) | Exported Function | 0x10009490 | 0x00009490
`public: void __thiscall CIlNt4Setupapi::release_SetupGetInfInformationW(void)` | 725 (0x2d5) | Exported Function | 0x10009820 | 0x00009820
`public: void __thiscall CIlNt4Setupapi::release_SetupOpenFileQueue(void)` | 726 (0x2d6) | Exported Function | 0x100095e0 | 0x000095e0
`public: void __thiscall CIlNt4Setupapi::release_SetupQueryInfOriginalFileInformationW(void)` | 727 (0x2d7) | Exported Function | 0x100098e0 | 0x000098e0
`public: void __thiscall CIlNt4User32::release_LockSetForegroundWindow(void)` | 690 (0x2b2) | Exported Function | 0x10009ed0 | 0x00009ed0
`public: virtual void __thiscall CIlOle32::CoTaskMemFree(void *)` | 138 (0x8a) | Exported Function | 0x10008a10 | 0x00008a10
`public: virtual void __thiscall CIlKernel32::Sleep(unsigned long)` | 425 (0x1a9) | Exported Function | 0x10007ad0 | 0x00007ad0
`public: virtual void __thiscall CIlKernel32::SetLastError(unsigned long)` | 391 (0x187) | Exported Function | 0x10007380 | 0x00007380
`public: virtual unsigned long __thiscall CIlKernel32::GetLogicalDrives(void)` | 209 (0xd1) | Exported Function | 0x10007680 | 0x00007680
`public: virtual unsigned long __thiscall CIlKernel32::GetLogicalDriveStringsW(unsigned long,unsigned short *)` | 208 (0xd0) | Exported Function | 0x10007660 | 0x00007660
`public: virtual unsigned long __thiscall CIlKernel32::GetPrivateProfileStringW(unsigned short const *,unsigned short const *,unsigned short const *,unsigned short *,unsigned long,unsigned short const *)` | 211 (0xd3) | Exported Function | 0x10007c80 | 0x00007c80
`public: virtual unsigned long __thiscall CIlKernel32::GetShortPathNameW(unsigned short const *,unsigned short *,unsigned long)` | 219 (0xdb) | Exported Function | 0x10007830 | 0x00007830
`public: virtual unsigned long __thiscall CIlKernel32::GetTempPathW(unsigned long,unsigned short *)` | 223 (0xdf) | Exported Function | 0x100077d0 | 0x000077d0
`public: virtual unsigned long __thiscall CIlKernel32::GetTickCount(void)` | 224 (0xe0) | Exported Function | 0x10007870 | 0x00007870
`public: virtual unsigned long __thiscall CIlKernel32::GlobalSize(void *)` | 238 (0xee) | Exported Function | 0x10007590 | 0x00007590
`public: virtual unsigned long __thiscall CIlKernel32::HeapCompact(void *,unsigned long)` | 241 (0xf1) | Exported Function | 0x100074b0 | 0x000074b0
`public: virtual unsigned long __thiscall CIlKernel32::SetFilePointer(void *,long,long *,unsigned long)` | 389 (0x185) | Exported Function | 0x100076f0 | 0x000076f0
`public: virtual unsigned long __thiscall CIlKernel32::WaitForMultipleObjects(unsigned long,void * const *,int,unsigned long)` | 446 (0x1be) | Exported Function | 0x10007a60 | 0x00007a60
`public: virtual unsigned long __thiscall CIlKernel32::WaitForSingleObject(void *,unsigned long)` | 447 (0x1bf) | Exported Function | 0x10007980 | 0x00007980
`public: virtual unsigned long __thiscall CIlMuisetupapi::GetUpgradeLanguage(unsigned short *,unsigned int,unsigned int)` | 226 (0xe2) | Exported Function | 0x1000a8e0 | 0x0000a8e0
`public: virtual unsigned long __thiscall CIlMuisetupapi::GetUpgradeLanguageEx(unsigned short *,unsigned int,unsigned int,unsigned short const *)` | 227 (0xe3) | Exported Function | 0x1000a910 | 0x0000a910
`public: virtual unsigned long __thiscall CIlNt4Netapi32::NetApiBufferFree(void *)` | 347 (0x15b) | Exported Function | 0x10008880 | 0x00008880
`public: virtual unsigned long __thiscall CIlNt4Netapi32::NetLocalGroupAdd(unsigned short const *,unsigned long,unsigned char *,unsigned long *)` | 348 (0x15c) | Exported Function | 0x100086f0 | 0x000086f0
`public: virtual unsigned long __thiscall CIlNt4Netapi32::NetLocalGroupAddMembers(unsigned short const *,unsigned short const *,unsigned long,unsigned char *,unsigned long)` | 349 (0x15d) | Exported Function | 0x10008630 | 0x00008630
`public: virtual unsigned long __thiscall CIlNt4Netapi32::NetLocalGroupEnum(unsigned short const *,unsigned long,unsigned char * *,unsigned long,unsigned long *,unsigned long *,unsigned long *)` | 350 (0x15e) | Exported Function | 0x100087b0 | 0x000087b0
`public: virtual unsigned long __thiscall CIlNt4Netapi32::NetUserAdd(unsigned short const *,unsigned long,unsigned char *,unsigned long *)` | 351 (0x15f) | Exported Function | 0x10008320 | 0x00008320
`public: virtual unsigned long __thiscall CIlNt4Netapi32::NetUserDel(unsigned short const *,unsigned short const *)` | 352 (0x160) | Exported Function | 0x100083e0 | 0x000083e0
`public: virtual unsigned long __thiscall CIlKernel32::GetLastError(void)` | 206 (0xce) | Exported Function | 0x10007370 | 0x00007370
`public: virtual unsigned long __thiscall CIlNt4Netapi32::NetUserEnum(unsigned short const *,unsigned long,unsigned long,unsigned char * *,unsigned long,unsigned long *,unsigned long *,unsigned long *)` | 353 (0x161) | Exported Function | 0x10008490 | 0x00008490
`public: virtual unsigned long __thiscall CIlKernel32::GetFullPathNameW(unsigned short const *,unsigned long,unsigned short *,unsigned short * *)` | 202 (0xca) | Exported Function | 0x10007810 | 0x00007810
`public: virtual unsigned long __thiscall CIlKernel32::GetFileSize(void *,unsigned long *)` | 198 (0xc6) | Exported Function | 0x10007b80 | 0x00007b80
`public: virtual struct hostent * __thiscall CIlWs2_32::gethostbyname(char const *)` | 538 (0x21a) | Exported Function | 0x1000a410 | 0x0000a410
`public: virtual struct SC_HANDLE__ * __thiscall CIlNt4Advapi32::CreateServiceW(struct SC_HANDLE__ *,unsigned short const *,unsigned short const *,unsigned long,unsigned long,unsigned long,unsigned long,unsigned short const *,unsigned short const *,unsigned long *,unsigned short const *,unsigned short const *,unsigned short const *)` | 152 (0x98) | Exported Function | 0x10006c10 | 0x00006c10
`public: virtual struct SC_HANDLE__ * __thiscall CIlNt4Advapi32::OpenSCManagerW(unsigned short const *,unsigned short const *,unsigned long)` | 359 (0x167) | Exported Function | 0x100068e0 | 0x000068e0
`public: virtual struct SC_HANDLE__ * __thiscall CIlNt4Advapi32::OpenServiceW(struct SC_HANDLE__ *,unsigned short const *,unsigned long)` | 360 (0x168) | Exported Function | 0x100069a0 | 0x000069a0
`public: virtual unsigned int __thiscall CIlKernel32::GetDriveTypeW(unsigned short const *)` | 195 (0xc3) | Exported Function | 0x10007690 | 0x00007690
`public: virtual unsigned int __thiscall CIlKernel32::GetTempFileNameW(unsigned short const *,unsigned short const *,unsigned int,unsigned short *)` | 222 (0xde) | Exported Function | 0x100077f0 | 0x000077f0
`public: virtual unsigned int __thiscall CIlKernel32::GetWindowsDirectoryW(unsigned short *,unsigned int)` | 232 (0xe8) | Exported Function | 0x10007750 | 0x00007750
`public: virtual unsigned int __thiscall CIlKernel32::SetErrorMode(unsigned int)` | 386 (0x182) | Exported Function | 0x10007ba0 | 0x00007ba0
`public: virtual unsigned int __thiscall CIlNt4Kernel32::GetSystemWindowsDirectoryW(unsigned short *,unsigned int)` | 221 (0xdd) | Exported Function | 0x100080b0 | 0x000080b0
`public: virtual unsigned int __thiscall CIlShell32::ExtractIconExW(unsigned short const *,int,struct HICON__ * *,struct HICON__ * *,unsigned int)` | 183 (0xb7) | Exported Function | 0x10009d40 | 0x00009d40
`public: virtual unsigned int __thiscall CIlWs2_32::accept(unsigned int,struct sockaddr *,int *)` | 450 (0x1c2) | Exported Function | 0x1000a5d0 | 0x0000a5d0
`public: virtual unsigned int __thiscall CIlWs2_32::socket(int,int,int)` | 739 (0x2e3) | Exported Function | 0x1000a330 | 0x0000a330
`public: virtual unsigned long __thiscall CIlAdvapi32::GetSecurityInfo(void *,enum _SE_OBJECT_TYPE,unsigned long,void * *,void * *,struct _ACL * *,struct _ACL * *,void * *)` | 218 (0xda) | Exported Function | 0x100060d0 | 0x000060d0
`public: virtual unsigned long __thiscall CIlAdvapi32::SetNamedSecurityInfoW(unsigned short *,enum _SE_OBJECT_TYPE,unsigned long,void *,void *,struct _ACL *,struct _ACL *)` | 392 (0x188) | Exported Function | 0x10006410 | 0x00006410
`public: virtual unsigned long __thiscall CIlAdvapi32::SetSecurityInfo(void *,enum _SE_OBJECT_TYPE,unsigned long,void *,void *,struct _ACL *,struct _ACL *)` | 394 (0x18a) | Exported Function | 0x100060f0 | 0x000060f0
`public: virtual unsigned long __thiscall CIlIphlpapi::GetIpAddrTable(struct _MIB_IPADDRTABLE *,unsigned long *,int)` | 205 (0xcd) | Exported Function | 0x10007310 | 0x00007310
`public: virtual unsigned long __thiscall CIlKernel32::ExpandEnvironmentStringsW(unsigned short const *,unsigned short *,unsigned long)` | 182 (0xb6) | Exported Function | 0x10007d40 | 0x00007d40
`public: virtual unsigned long __thiscall CIlKernel32::GetCurrentThreadId(void)` | 192 (0xc0) | Exported Function | 0x10007c70 | 0x00007c70
`public: virtual unsigned long __thiscall CIlKernel32::GetFileAttributesW(unsigned short const *)` | 197 (0xc5) | Exported Function | 0x10007790 | 0x00007790
`public: virtual unsigned long __thiscall CIlKernel32::GetFileType(void *)` | 199 (0xc7) | Exported Function | 0x10007b60 | 0x00007b60
`public: virtual unsigned long __thiscall CIlNt4Netapi32::NetUserGetLocalGroups(unsigned short const *,unsigned short const *,unsigned long,unsigned long,unsigned char * *,unsigned long,unsigned long *,unsigned long *)` | 354 (0x162) | Exported Function | 0x10008560 | 0x00008560
`public: virtual unsigned long __thiscall CIlNt4Netapi32::NetWkstaGetInfo(unsigned short *,unsigned long,unsigned char * *)` | 355 (0x163) | Exported Function | 0x10008260 | 0x00008260
`public: virtual unsigned long __thiscall CIlVersion::GetFileVersionInfoSizeW(unsigned short const *,unsigned long *)` | 200 (0xc8) | Exported Function | 0x1000a170 | 0x0000a170
`public: virtual void * __thiscall CIlNt4Advapi32::LockServiceDatabase(struct SC_HANDLE__ *)` | 337 (0x151) | Exported Function | 0x10006ea0 | 0x00006ea0
`public: virtual void * __thiscall CIlNt4Kernel32::CreateToolhelp32Snapshot(unsigned long,unsigned long)` | 155 (0x9b) | Exported Function | 0x10007ea0 | 0x00007ea0
`public: virtual void * __thiscall CIlNt4Setupapi::SetupDiCreateDeviceInfoListExW(struct _GUID const *,struct HWND__ *,unsigned short const *,void *)` | 399 (0x18f) | Exported Function | 0x10008b90 | 0x00008b90
`public: virtual void * __thiscall CIlNt4Setupapi::SetupDiGetClassDevsExW(struct _GUID const *,unsigned short const *,struct HWND__ *,unsigned long,void *,unsigned short const *,void *)` | 405 (0x195) | Exported Function | 0x10008c50 | 0x00008c50
`public: virtual void * __thiscall CIlNt4Setupapi::SetupDiGetClassDevsW(struct _GUID const *,unsigned short const *,struct HWND__ *,unsigned long)` | 406 (0x196) | Exported Function | 0x10008d20 | 0x00008d20
`public: virtual void * __thiscall CIlNt4Setupapi::SetupOpenFileQueue(void)` | 420 (0x1a4) | Exported Function | 0x10009560 | 0x00009560
`public: virtual void * __thiscall CIlOle32::CoTaskMemAlloc(unsigned long)` | 137 (0x89) | Exported Function | 0x100089f0 | 0x000089f0
`public: virtual void * __thiscall CIlSetupapi::SetupOpenInfFileW(unsigned short const *,unsigned short const *,unsigned long,unsigned int *)` | 421 (0x1a5) | Exported Function | 0x10008ac0 | 0x00008ac0
`public: virtual void * __thiscall CIlWimgapi::WIMCreateFile(unsigned short *,unsigned long,unsigned long,unsigned long,unsigned long,unsigned long *)` | 437 (0x1b5) | Exported Function | 0x1000a1f0 | 0x0000a1f0
`public: virtual void * __thiscall CIlWimgapi::WIMLoadImage(void *,unsigned long)` | 438 (0x1b6) | Exported Function | 0x1000a230 | 0x0000a230
`public: virtual void __thiscall CIlKernel32::DebugBreak(void)` | 173 (0xad) | Exported Function | 0x10007d10 | 0x00007d10
`public: virtual void __thiscall CIlKernel32::DeleteCriticalSection(struct _RTL_CRITICAL_SECTION *)` | 174 (0xae) | Exported Function | 0x10007b30 | 0x00007b30
`public: virtual void __thiscall CIlKernel32::EnterCriticalSection(struct _RTL_CRITICAL_SECTION *)` | 178 (0xb2) | Exported Function | 0x10007b10 | 0x00007b10
`public: virtual void __thiscall CIlKernel32::ExitProcess(unsigned int)` | 181 (0xb5) | Exported Function | 0x10007940 | 0x00007940
`public: virtual void __thiscall CIlKernel32::GetSystemInfo(struct _SYSTEM_INFO *)` | 220 (0xdc) | Exported Function | 0x100073d0 | 0x000073d0
`public: virtual void __thiscall CIlKernel32::GlobalMemoryStatus(struct _MEMORYSTATUS *)` | 236 (0xec) | Exported Function | 0x100073e0 | 0x000073e0
`public: virtual void __thiscall CIlKernel32::InitializeCriticalSection(struct _RTL_CRITICAL_SECTION *)` | 330 (0x14a) | Exported Function | 0x10007b00 | 0x00007b00
`public: virtual void __thiscall CIlKernel32::LeaveCriticalSection(struct _RTL_CRITICAL_SECTION *)` | 334 (0x14e) | Exported Function | 0x10007b20 | 0x00007b20
`public: virtual void __thiscall CIlKernel32::RaiseException(unsigned long,unsigned long,unsigned long,unsigned long const *)` | 365 (0x16d) | Exported Function | 0x10007c60 | 0x00007c60
`public: virtual void * __thiscall CIlKernel32::VirtualAlloc(void *,unsigned long,unsigned long,unsigned long)` | 433 (0x1b1) | Exported Function | 0x10007d80 | 0x00007d80
`public: virtual void * __thiscall CIlKernel32::OpenProcess(unsigned long,int,unsigned long)` | 357 (0x165) | Exported Function | 0x10007920 | 0x00007920
`public: virtual void * __thiscall CIlKernel32::OpenEventW(unsigned long,int,unsigned short const *)` | 356 (0x164) | Exported Function | 0x10007a40 | 0x00007a40
`public: virtual void * __thiscall CIlKernel32::MapViewOfFile(void *,unsigned long,unsigned long,unsigned long,unsigned long)` | 342 (0x156) | Exported Function | 0x10007c20 | 0x00007c20
`public: virtual unsigned long __thiscall CIlWimgapi::WIMRegisterMessageCallback(void *,int (__stdcall*)(void),void *)` | 439 (0x1b7) | Exported Function | 0x1000a250 | 0x0000a250
`public: virtual unsigned long __thiscall CIlWs2_32::htonl(unsigned long)` | 543 (0x21f) | Exported Function | 0x1000a3b0 | 0x0000a3b0
`public: virtual unsigned long __thiscall CIlWs2_32::inet_addr(char const *)` | 545 (0x221) | Exported Function | 0x1000a370 | 0x0000a370
`public: virtual unsigned short * __thiscall CIlKernel32::GetCommandLineW(void)` | 189 (0xbd) | Exported Function | 0x10007ca0 | 0x00007ca0
`public: virtual unsigned short __thiscall CIlWs2_32::htons(unsigned short)` | 544 (0x220) | Exported Function | 0x1000a3d0 | 0x0000a3d0
`public: virtual void (__stdcall*__thiscall CIlW2kDynWs2_32::get_freeaddrinfo(void))(struct addrinfo *)` | 534 (0x216) | Exported Function | 0x1000a840 | 0x0000a840
`public: virtual void * __thiscall CIlAdvapi32::FreeSid(void *)` | 188 (0xbc) | Exported Function | 0x10006070 | 0x00006070
`public: virtual void * __thiscall CIlKernel32::CreateEventW(struct _SECURITY_ATTRIBUTES *,int,int,unsigned short const *)` | 146 (0x92) | Exported Function | 0x10007a20 | 0x00007a20
`public: virtual void * __thiscall CIlKernel32::CreateFileMappingW(void *,struct _SECURITY_ATTRIBUTES *,unsigned long,unsigned long,unsigned long,unsigned short const *)` | 147 (0x93) | Exported Function | 0x10007c00 | 0x00007c00
`public: virtual struct HINSTANCE__ * __thiscall CIlKernel32::LoadLibraryW(unsigned short const *)` | 336 (0x150) | Exported Function | 0x10007cf0 | 0x00007cf0
`public: virtual void * __thiscall CIlKernel32::CreateFileW(unsigned short const *,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES *,unsigned long,unsigned long,void *)` | 148 (0x94) | Exported Function | 0x10007620 | 0x00007620
`public: virtual void * __thiscall CIlKernel32::FindFirstFileW(unsigned short const *,struct _WIN32_FIND_DATAW *)` | 185 (0xb9) | Exported Function | 0x10007880 | 0x00007880
`public: virtual void * __thiscall CIlKernel32::GetCurrentProcess(void)` | 191 (0xbf) | Exported Function | 0x100073f0 | 0x000073f0
`public: virtual void * __thiscall CIlKernel32::GetProcessHeap(void)` | 213 (0xd5) | Exported Function | 0x10007400 | 0x00007400
`public: virtual void * __thiscall CIlKernel32::GlobalAlloc(unsigned int,unsigned long)` | 233 (0xe9) | Exported Function | 0x10007510 | 0x00007510
`public: virtual void * __thiscall CIlKernel32::GlobalFree(void *)` | 234 (0xea) | Exported Function | 0x10007570 | 0x00007570
`public: virtual void * __thiscall CIlKernel32::GlobalLock(void *)` | 235 (0xeb) | Exported Function | 0x10007530 | 0x00007530
`public: virtual void * __thiscall CIlKernel32::HeapAlloc(void *,unsigned long,unsigned long)` | 240 (0xf0) | Exported Function | 0x10007450 | 0x00007450
`public: virtual void * __thiscall CIlKernel32::HeapCreate(unsigned long,unsigned long,unsigned long)` | 242 (0xf2) | Exported Function | 0x10007410 | 0x00007410
`public: virtual void * __thiscall CIlKernel32::HeapReAlloc(void *,unsigned long,void *,unsigned long)` | 245 (0xf5) | Exported Function | 0x10007470 | 0x00007470
`public: virtual void * __thiscall CIlKernel32::CreateThread(struct _SECURITY_ATTRIBUTES *,unsigned long,unsigned long (__stdcall*)(void *),void *,unsigned long,unsigned long *)` | 154 (0x9a) | Exported Function | 0x10007a00 | 0x00007a00
`struct IWimgapiInterface * g_Wimgapi` | 474 (0x1da) | Exported Function | 0x10019040 | 0x00019040
`public: int (__stdcall*__thiscall CIlNt4User32::get_LockSetForegroundWindow(void))(unsigned int)` | 493 (0x1ed) | Exported Function | 0x10009ea0 | 0x00009ea0
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupQueryInfOriginalFileInformationW(void))(struct _SP_INF_INFORMATION *,unsigned int,struct _SP_ALTPLATFORM_INFO_V2 *,struct _SP_ORIGINAL_FILE_INFO_W *)` | 530 (0x212) | Exported Function | 0x100098b0 | 0x000098b0
`private: static int __stdcall CIlNt4Userenv::IlCreateUserProfileExW(void *,unsigned short const *,unsigned short const *,unsigned short *,unsigned long,int)` | 258 (0x102) | Exported Function | 0x10009f80 | 0x00009f80
`private: static int __stdcall CIlW2kDynWs2_32::Ilgetaddrinfo(char const *,char const *,struct addrinfo const *,struct addrinfo * *)` | 328 (0x148) | Exported Function | 0x1000a750 | 0x0000a750
`private: static int __stdcall CIlW2kDynWs2_32::Ilgetnameinfo(struct sockaddr const *,int,char *,unsigned long,char *,unsigned long,int)` | 329 (0x149) | Exported Function | 0x1000a690 | 0x0000a690
`private: static long (__stdcall* CIlNt6Userenv::m_CreateProfile)(unsigned short const *,unsigned short const *,unsigned short *,unsigned long)` | 555 (0x22b) | Exported Function | 0x1001962c | 0x0001962c
`private: static long __stdcall CIlNt6Userenv::IlCreateProfile(unsigned short const *,unsigned short const *,unsigned short *,unsigned long)` | 255 (0xff) | Exported Function | 0x1000a090 | 0x0000a090
`private: static struct HKEY__ * (__stdcall* CIlNt4Setupapi::m_SetupDiOpenDevRegKey)(void *,struct _SP_DEVINFO_DATA *,unsigned long,unsigned long,unsigned long,unsigned long)` | 658 (0x292) | Exported Function | 0x1001965c | 0x0001965c
`private: static struct HKEY__ * __stdcall CIlNt4Setupapi::IlSetupDiOpenDevRegKey(void *,struct _SP_DEVINFO_DATA *,unsigned long,unsigned long,unsigned long,unsigned long)` | 310 (0x136) | Exported Function | 0x10009ad0 | 0x00009ad0
`private: static struct SC_HANDLE__ * (__stdcall* CIlNt4Advapi32::m_CreateServiceW)(struct SC_HANDLE__ *,unsigned short const *,unsigned short const *,unsigned long,unsigned long,unsigned long,unsigned long,unsigned short const *,unsigned short const *,unsigned long *,unsigned short const *,unsigned short const *,unsigned short const *)` | 556 (0x22c) | Exported Function | 0x100195bc | 0x000195bc
`private: static struct SC_HANDLE__ * (__stdcall* CIlNt4Advapi32::m_OpenSCManagerW)(unsigned short const *,unsigned short const *,unsigned long)` | 576 (0x240) | Exported Function | 0x10019600 | 0x00019600
`private: static struct SC_HANDLE__ * (__stdcall* CIlNt4Advapi32::m_OpenServiceW)(struct SC_HANDLE__ *,unsigned short const *,unsigned long)` | 577 (0x241) | Exported Function | 0x1001970c | 0x0001970c
`private: static struct SC_HANDLE__ * __stdcall CIlNt4Advapi32::IlCreateServiceW(struct SC_HANDLE__ *,unsigned short const *,unsigned short const *,unsigned long,unsigned long,unsigned long,unsigned long,unsigned short const *,unsigned short const *,unsigned long *,unsigned short const *,unsigned short const *,unsigned short const *)` | 256 (0x100) | Exported Function | 0x10006c60 | 0x00006c60
`private: static struct SC_HANDLE__ * __stdcall CIlNt4Advapi32::IlOpenSCManagerW(unsigned short const *,unsigned short const *,unsigned long)` | 289 (0x121) | Exported Function | 0x10006910 | 0x00006910
`private: static struct SC_HANDLE__ * __stdcall CIlNt4Advapi32::IlOpenServiceW(struct SC_HANDLE__ *,unsigned short const *,unsigned long)` | 290 (0x122) | Exported Function | 0x100069d0 | 0x000069d0
`private: static unsigned int (__stdcall* CIlNt4Kernel32::m_GetSystemWindowsDirectoryW)(unsigned short *,unsigned int)` | 562 (0x232) | Exported Function | 0x1001960c | 0x0001960c
`private: static unsigned int __stdcall CIlNt4Kernel32::IlGetSystemWindowsDirectoryW(unsigned short *,unsigned int)` | 263 (0x107) | Exported Function | 0x100080e0 | 0x000080e0
`private: static unsigned long (__stdcall* CIlNt4Netapi32::m_NetApiBufferFree)(void *)` | 567 (0x237) | Exported Function | 0x10019678 | 0x00019678
`private: static unsigned long (__stdcall* CIlNt4Netapi32::m_NetLocalGroupAdd)(unsigned short const *,unsigned long,unsigned char *,unsigned long *)` | 568 (0x238) | Exported Function | 0x100196b8 | 0x000196b8
`private: static unsigned long (__stdcall* CIlNt4Netapi32::m_NetLocalGroupAddMembers)(unsigned short const *,unsigned short const *,unsigned long,unsigned char *,unsigned long)` | 569 (0x239) | Exported Function | 0x10019694 | 0x00019694
`private: static unsigned long (__stdcall* CIlNt4Netapi32::m_NetLocalGroupEnum)(unsigned short const *,unsigned long,unsigned char * *,unsigned long,unsigned long *,unsigned long *,unsigned long *)` | 570 (0x23a) | Exported Function | 0x10019674 | 0x00019674
`private: static int __stdcall CIlNt4User32::IlLockSetForegroundWindow(unsigned int)` | 269 (0x10d) | Exported Function | 0x10009e70 | 0x00009e70
`private: static unsigned long (__stdcall* CIlNt4Netapi32::m_NetUserAdd)(unsigned short const *,unsigned long,unsigned char *,unsigned long *)` | 571 (0x23b) | Exported Function | 0x10019700 | 0x00019700
`private: static int __stdcall CIlNt4Setupapi::IlSetupScanFileQueueW(void *,unsigned long,struct HWND__ *,unsigned int (__stdcall*)(void *,unsigned int,unsigned int,unsigned int),void *,unsigned long *)` | 317 (0x13d) | Exported Function | 0x10009640 | 0x00009640
`private: static int __stdcall CIlNt4Setupapi::IlSetupGetInfInformationW(void const *,unsigned long,struct _SP_INF_INFORMATION *,unsigned long,unsigned long *)` | 314 (0x13a) | Exported Function | 0x100097b0 | 0x000097b0
`private: static int __stdcall CIlNt4Kernel32::IlGlobalMemoryStatusEx(struct _MEMORYSTATUSEX *)` | 264 (0x108) | Exported Function | 0x10008190 | 0x00008190
`private: static int __stdcall CIlNt4Kernel32::IlProcess32FirstW(void *,struct tagPROCESSENTRY32W *)` | 291 (0x123) | Exported Function | 0x10007f80 | 0x00007f80
`private: static int __stdcall CIlNt4Kernel32::IlProcess32NextW(void *,struct tagPROCESSENTRY32W *)` | 292 (0x124) | Exported Function | 0x10008030 | 0x00008030
`private: static int __stdcall CIlNt4Kernel32::IlRegisterWaitForSingleObject(void * *,void *,void (__stdcall*)(void *,unsigned char),void *,unsigned long,unsigned long)` | 294 (0x126) | Exported Function | 0x10007e10 | 0x00007e10
`private: static int __stdcall CIlNt4Setupapi::IlSetupCloseFileQueue(void *)` | 295 (0x127) | Exported Function | 0x10009700 | 0x00009700
`private: static int __stdcall CIlNt4Setupapi::IlSetupDiBuildDriverInfoList(void *,struct _SP_DEVINFO_DATA *,unsigned long)` | 296 (0x128) | Exported Function | 0x10009050 | 0x00009050
`private: static int __stdcall CIlNt4Setupapi::IlSetupDiCallClassInstaller(unsigned int,void *,struct _SP_DEVINFO_DATA *)` | 297 (0x129) | Exported Function | 0x10009360 | 0x00009360
`private: static int __stdcall CIlNt4Setupapi::IlSetupDiDestroyDeviceInfoList(void *)` | 299 (0x12b) | Exported Function | 0x100094e0 | 0x000094e0
`private: static int __stdcall CIlNt4Setupapi::IlSetupDiDestroyDriverInfoList(void *,struct _SP_DEVINFO_DATA *,unsigned long)` | 300 (0x12c) | Exported Function | 0x10008f90 | 0x00008f90
`private: static int __stdcall CIlNt4Setupapi::IlSetupDiEnumDeviceInfo(void *,unsigned long,struct _SP_DEVINFO_DATA *)` | 301 (0x12d) | Exported Function | 0x10008ed0 | 0x00008ed0
`private: static int __stdcall CIlNt4Setupapi::IlSetupDiEnumDeviceInterfaces(void *,struct _SP_DEVINFO_DATA *,struct _GUID const *,unsigned long,struct _SP_DEVICE_INTERFACE_DATA *)` | 302 (0x12e) | Exported Function | 0x10009b90 | 0x00009b90
`private: static int __stdcall CIlNt4Setupapi::IlSetupDiEnumDriverInfoW(void *,struct _SP_DEVINFO_DATA *,unsigned long,unsigned long,struct _SP_DRVINFO_DATA_V2_W *)` | 303 (0x12f) | Exported Function | 0x10009a00 | 0x00009a00
`private: static int __stdcall CIlNt4Setupapi::IlSetupDiGetDeviceInstallParamsW(void *,struct _SP_DEVINFO_DATA *,struct _SP_DEVINSTALL_PARAMS_W *)` | 306 (0x132) | Exported Function | 0x100091e0 | 0x000091e0
`private: static int __stdcall CIlNt4Setupapi::IlSetupDiGetDeviceInterfaceDetailW(void *,struct _SP_DEVICE_INTERFACE_DATA *,struct _SP_DEVICE_INTERFACE_DETAIL_DATA_W *,unsigned long,unsigned long *,struct _SP_DEVINFO_DATA *)` | 307 (0x133) | Exported Function | 0x10009c60 | 0x00009c60
`private: static int __stdcall CIlNt4Setupapi::IlSetupDiGetDeviceRegistryPropertyW(void *,struct _SP_DEVINFO_DATA *,unsigned long,unsigned long *,unsigned char *,unsigned long,unsigned long *)` | 308 (0x134) | Exported Function | 0x10009940 | 0x00009940
`private: static int __stdcall CIlNt4Setupapi::IlSetupDiGetDriverInfoDetailW(void *,struct _SP_DEVINFO_DATA *,struct _SP_DRVINFO_DATA_V2_W *,struct _SP_DRVINFO_DETAIL_DATA_W *,unsigned long,unsigned long *)` | 309 (0x135) | Exported Function | 0x10009120 | 0x00009120
`private: static int __stdcall CIlNt4Setupapi::IlSetupDiOpenDeviceInfoW(void *,unsigned short const *,struct HWND__ *,unsigned long,struct _SP_DEVINFO_DATA *)` | 311 (0x137) | Exported Function | 0x10008e10 | 0x00008e10
`private: static int __stdcall CIlNt4Setupapi::IlSetupDiSetDeviceInstallParamsW(void *,struct _SP_DEVINFO_DATA *,struct _SP_DEVINSTALL_PARAMS_W *)` | 312 (0x138) | Exported Function | 0x100092a0 | 0x000092a0
`private: static int __stdcall CIlNt4Setupapi::IlSetupDiSetSelectedDriverW(void *,struct _SP_DEVINFO_DATA *,struct _SP_DRVINFO_DATA_V2_W *)` | 313 (0x139) | Exported Function | 0x10009420 | 0x00009420
`private: static int __stdcall CIlNt4Setupapi::IlSetupQueryInfOriginalFileInformationW(struct _SP_INF_INFORMATION *,unsigned int,struct _SP_ALTPLATFORM_INFO_V2 *,struct _SP_ORIGINAL_FILE_INFO_W *)` | 316 (0x13c) | Exported Function | 0x10009870 | 0x00009870
`private: static int __stdcall CIlNt4Advapi32::IlUnlockServiceDatabase(void *)` | 321 (0x141) | Exported Function | 0x10006f80 | 0x00006f80
`private: static unsigned long (__stdcall* CIlNt4Netapi32::m_NetUserDel)(unsigned short const *,unsigned short const *)` | 572 (0x23c) | Exported Function | 0x10019668 | 0x00019668
`private: static unsigned long (__stdcall* CIlNt4Netapi32::m_NetUserGetLocalGroups)(unsigned short const *,unsigned short const *,unsigned long,unsigned long,unsigned char * *,unsigned long,unsigned long *,unsigned long *)` | 574 (0x23e) | Exported Function | 0x100195d0 | 0x000195d0
`private: static unsigned long CIlNt4Advapi32::m_RefCountOpenServiceW` | 609 (0x261) | Exported Function | 0x100196a0 | 0x000196a0
`private: static unsigned long CIlNt4Advapi32::m_RefCountQueryServiceConfigW` | 612 (0x264) | Exported Function | 0x1001966c | 0x0001966c
`private: static unsigned long CIlNt4Advapi32::m_RefCountStartServiceW` | 637 (0x27d) | Exported Function | 0x100195d4 | 0x000195d4
`private: static unsigned long CIlNt4Advapi32::m_RefCountUnlockServiceDatabase` | 638 (0x27e) | Exported Function | 0x10019580 | 0x00019580
`private: static unsigned long CIlNt4Kernel32::m_RefCountCreateToolhelp32Snapshot` | 589 (0x24d) | Exported Function | 0x10019588 | 0x00019588
`private: static unsigned long CIlNt4Kernel32::m_RefCountGetSystemWindowsDirectoryW` | 594 (0x252) | Exported Function | 0x1001953c | 0x0001953c
`private: static unsigned long CIlNt4Kernel32::m_RefCountGlobalMemoryStatusEx` | 595 (0x253) | Exported Function | 0x100196c0 | 0x000196c0
`private: static unsigned long CIlNt4Kernel32::m_RefCountProcess32FirstW` | 610 (0x262) | Exported Function | 0x100195ec | 0x000195ec
`private: static unsigned long CIlNt4Kernel32::m_RefCountProcess32NextW` | 611 (0x263) | Exported Function | 0x100195f0 | 0x000195f0
`private: static unsigned long CIlNt4Kernel32::m_RefCountRegisterWaitForSingleObject` | 613 (0x265) | Exported Function | 0x100196b0 | 0x000196b0
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetApiBufferFree` | 599 (0x257) | Exported Function | 0x100196a4 | 0x000196a4
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetLocalGroupAdd` | 600 (0x258) | Exported Function | 0x1001963c | 0x0001963c
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetLocalGroupAddMembers` | 601 (0x259) | Exported Function | 0x100196ac | 0x000196ac
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetLocalGroupEnum` | 602 (0x25a) | Exported Function | 0x10019564 | 0x00019564
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetUserAdd` | 603 (0x25b) | Exported Function | 0x10019578 | 0x00019578
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetUserDel` | 604 (0x25c) | Exported Function | 0x100196d8 | 0x000196d8
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetUserEnum` | 605 (0x25d) | Exported Function | 0x100195f8 | 0x000195f8
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetUserGetLocalGroups` | 606 (0x25e) | Exported Function | 0x10019618 | 0x00019618
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetWkstaGetInfo` | 607 (0x25f) | Exported Function | 0x100195d8 | 0x000195d8
`private: static unsigned long CIlNt4Advapi32::m_RefCountOpenSCManagerW` | 608 (0x260) | Exported Function | 0x100196dc | 0x000196dc
`private: static unsigned long (__stdcall* CIlNt4Netapi32::m_NetUserEnum)(unsigned short const *,unsigned long,unsigned long,unsigned char * *,unsigned long,unsigned long *,unsigned long *,unsigned long *)` | 573 (0x23d) | Exported Function | 0x1001954c | 0x0001954c
`private: static unsigned long CIlNt4Advapi32::m_RefCountLockServiceDatabase` | 597 (0x255) | Exported Function | 0x10019670 | 0x00019670
`private: static unsigned long CIlNt4Advapi32::m_RefCountEnumServicesStatusExW` | 593 (0x251) | Exported Function | 0x10019608 | 0x00019608
`private: static unsigned long (__stdcall* CIlNt4Netapi32::m_NetWkstaGetInfo)(unsigned short *,unsigned long,unsigned char * *)` | 575 (0x23f) | Exported Function | 0x100196d4 | 0x000196d4
`private: static unsigned long __stdcall CIlNt4Netapi32::IlNetApiBufferFree(void *)` | 271 (0x10f) | Exported Function | 0x100088b0 | 0x000088b0
`private: static unsigned long __stdcall CIlNt4Netapi32::IlNetLocalGroupAdd(unsigned short const *,unsigned long,unsigned char *,unsigned long *)` | 272 (0x110) | Exported Function | 0x10008720 | 0x00008720
`private: static unsigned long __stdcall CIlNt4Netapi32::IlNetLocalGroupAddMembers(unsigned short const *,unsigned short const *,unsigned long,unsigned char *,unsigned long)` | 273 (0x111) | Exported Function | 0x10008660 | 0x00008660
`private: static unsigned long __stdcall CIlNt4Netapi32::IlNetLocalGroupEnum(unsigned short const *,unsigned long,unsigned char * *,unsigned long,unsigned long *,unsigned long *,unsigned long *)` | 274 (0x112) | Exported Function | 0x100087f0 | 0x000087f0
`private: static unsigned long __stdcall CIlNt4Netapi32::IlNetUserAdd(unsigned short const *,unsigned long,unsigned char *,unsigned long *)` | 275 (0x113) | Exported Function | 0x10008350 | 0x00008350
`private: static unsigned long __stdcall CIlNt4Netapi32::IlNetUserDel(unsigned short const *,unsigned short const *)` | 276 (0x114) | Exported Function | 0x10008410 | 0x00008410
`private: static unsigned long __stdcall CIlNt4Netapi32::IlNetUserEnum(unsigned short const *,unsigned long,unsigned long,unsigned char * *,unsigned long,unsigned long *,unsigned long *,unsigned long *)` | 277 (0x115) | Exported Function | 0x100084d0 | 0x000084d0
`private: static unsigned long __stdcall CIlNt4Netapi32::IlNetUserGetLocalGroups(unsigned short const *,unsigned short const *,unsigned long,unsigned long,unsigned char * *,unsigned long,unsigned long *,unsigned long *)` | 278 (0x116) | Exported Function | 0x100085a0 | 0x000085a0
`private: static unsigned long __stdcall CIlNt4Netapi32::IlNetWkstaGetInfo(unsigned short *,unsigned long,unsigned char * *)` | 279 (0x117) | Exported Function | 0x10008290 | 0x00008290
`private: static unsigned long CIlNt4Advapi32::m_RefCountChangeServiceConfigW` | 581 (0x245) | Exported Function | 0x1001967c | 0x0001967c
`private: static unsigned long CIlNt4Advapi32::m_RefCountCloseServiceHandle` | 582 (0x246) | Exported Function | 0x100195b0 | 0x000195b0
`private: static unsigned long CIlNt4Advapi32::m_RefCountConvertSecurityDescriptorToStringSecurityDescriptorW` | 583 (0x247) | Exported Function | 0x100196c4 | 0x000196c4
`private: static unsigned long CIlNt4Advapi32::m_RefCountConvertSidToStringSidW` | 584 (0x248) | Exported Function | 0x10019554 | 0x00019554
`private: static unsigned long CIlNt4Advapi32::m_RefCountConvertStringSecurityDescriptorToSecurityDescriptorW` | 585 (0x249) | Exported Function | 0x10019664 | 0x00019664
`private: static unsigned long CIlNt4Advapi32::m_RefCountConvertStringSidToSidW` | 586 (0x24a) | Exported Function | 0x10019638 | 0x00019638
`private: static unsigned long CIlNt4Advapi32::m_RefCountCreateServiceW` | 588 (0x24c) | Exported Function | 0x100196b4 | 0x000196b4
`private: static unsigned long CIlNt4Advapi32::m_RefCountCreateWellKnownSid` | 591 (0x24f) | Exported Function | 0x10019594 | 0x00019594
`private: static unsigned long CIlNt4Advapi32::m_RefCountEncryptFileW` | 592 (0x250) | Exported Function | 0x10019704 | 0x00019704
`private: static unsigned long CIlNt4Advapi32::m_RefCountInitiateSystemShutdownExW` | 596 (0x254) | Exported Function | 0x100196fc | 0x000196fc
`private: static int __stdcall CIlNt4Advapi32::IlStartServiceW(struct SC_HANDLE__ *,unsigned long,unsigned short const * *)` | 320 (0x140) | Exported Function | 0x10006d30 | 0x00006d30
`private: static int __stdcall CIlNt4Advapi32::IlQueryServiceConfigW(struct SC_HANDLE__ *,struct _QUERY_SERVICE_CONFIGW *,unsigned long,unsigned long *)` | 293 (0x125) | Exported Function | 0x10006a90 | 0x00006a90
`private: static int __stdcall CIlNt4Advapi32::IlInitiateSystemShutdownExW(unsigned short *,unsigned short *,unsigned long,int,int,unsigned long)` | 265 (0x109) | Exported Function | 0x100070f0 | 0x000070f0
`const CIlKernel32::``vftable'` | 111 (0x6f) | Exported Function | 0x100012ec | 0x000012ec
`const CIlMuisetupapi::``vftable'` | 112 (0x70) | Exported Function | 0x100010d4 | 0x000010d4
`const CIlNt4Advapi32::``vftable'` | 113 (0x71) | Exported Function | 0x100011e4 | 0x000011e4
`const CIlNt4Kernel32::``vftable'` | 114 (0x72) | Exported Function | 0x100011ac | 0x000011ac
`const CIlNt4Netapi32::``vftable'` | 115 (0x73) | Exported Function | 0x10001458 | 0x00001458
`const CIlNt4Setupapi::``vftable'` | 116 (0x74) | Exported Function | 0x10001480 | 0x00001480
`const CIlNt4User32::``vftable'` | 117 (0x75) | Exported Function | 0x100014dc | 0x000014dc
`const CIlNt4Userenv::``vftable'` | 118 (0x76) | Exported Function | 0x1000147c | 0x0000147c
`const CIlNt6Userenv::``vftable'` | 119 (0x77) | Exported Function | 0x10001228 | 0x00001228
`const CIlOle32::``vftable'` | 120 (0x78) | Exported Function | 0x100011c4 | 0x000011c4
`const CIlOleaut32::``vftable'` | 121 (0x79) | Exported Function | 0x100014e0 | 0x000014e0
`const CIlSetupapi::``vftable'` | 122 (0x7a) | Exported Function | 0x100010bc | 0x000010bc
`const CIlShell32::``vftable'` | 123 (0x7b) | Exported Function | 0x100010b4 | 0x000010b4
`const CIlUser32::``vftable'` | 124 (0x7c) | Exported Function | 0x100012dc | 0x000012dc
`const CIlVersion::``vftable'` | 125 (0x7d) | Exported Function | 0x100011a0 | 0x000011a0
`const CIlW2kDynWs2_32::``vftable'` | 126 (0x7e) | Exported Function | 0x100012b8 | 0x000012b8
`const CIlWimgapi::``vftable'` | 127 (0x7f) | Exported Function | 0x10001298 | 0x00001298
`const CIlWs2_32::``vftable'` | 128 (0x80) | Exported Function | 0x1000122c | 0x0000122c
`private: static int (__stdcall* CIlNt4Advapi32::m_ChangeServiceConfigW)(struct SC_HANDLE__ *,unsigned long,unsigned long,unsigned long,unsigned short const *,unsigned short const *,unsigned long *,unsigned short const *,unsigned short const *,unsigned short const *,unsigned short const *)` | 549 (0x225) | Exported Function | 0x100196e4 | 0x000196e4
`const CIlIphlpapi::``vftable'` | 110 (0x6e) | Exported Function | 0x10001454 | 0x00001454
`private: static int (__stdcall* CIlNt4Advapi32::m_CloseServiceHandle)(struct SC_HANDLE__ *)` | 550 (0x226) | Exported Function | 0x1001969c | 0x0001969c
`const CIlDeplorch::``vftable'` | 109 (0x6d) | Exported Function | 0x100012b4 | 0x000012b4
`class CIlWs2_32 IlWs2_32` | 326 (0x146) | Exported Function | 0x10019150 | 0x00019150
`class CIlDeplorch IlDeplorch` | 260 (0x104) | Exported Function | 0x1001916c | 0x0001916c
`class CIlIphlpapi IlIphlpapi` | 266 (0x10a) | Exported Function | 0x10019168 | 0x00019168
`class CIlKernel32 IlKernel32` | 267 (0x10b) | Exported Function | 0x1001913c | 0x0001913c
`class CIlMuisetupapi IlMuisetupapi` | 270 (0x10e) | Exported Function | 0x10019154 | 0x00019154
`class CIlNt4Advapi32 IlNt4Advapi32` | 280 (0x118) | Exported Function | 0x1001915c | 0x0001915c
`class CIlNt4Kernel32 IlNt4Kernel32` | 281 (0x119) | Exported Function | 0x1001912c | 0x0001912c
`class CIlNt4Netapi32 IlNt4Netapi32` | 282 (0x11a) | Exported Function | 0x100191a0 | 0x000191a0
`class CIlNt4Setupapi IlNt4Setupapi` | 283 (0x11b) | Exported Function | 0x10019188 | 0x00019188
`class CIlNt4User32 IlNt4User32` | 284 (0x11c) | Exported Function | 0x100191b0 | 0x000191b0
`class CIlNt4Userenv IlNt4Userenv` | 285 (0x11d) | Exported Function | 0x10019140 | 0x00019140
`class CIlNt6Userenv IlNt6Userenv` | 286 (0x11e) | Exported Function | 0x10019174 | 0x00019174
`class CIlOle32 IlOle32` | 287 (0x11f) | Exported Function | 0x10019184 | 0x00019184
`class CIlOleaut32 IlOleaut32` | 288 (0x120) | Exported Function | 0x1001914c | 0x0001914c
`class CIlSetupapi IlSetupapi` | 318 (0x13e) | Exported Function | 0x100191ac | 0x000191ac
`class CIlShell32 IlShell32` | 319 (0x13f) | Exported Function | 0x10019170 | 0x00019170
`class CIlUser32 IlUser32` | 322 (0x142) | Exported Function | 0x10019138 | 0x00019138
`class CIlVersion IlVersion` | 323 (0x143) | Exported Function | 0x10019180 | 0x00019180
`class CIlW2kDynWs2_32 IlW2kDynWs2_32` | 324 (0x144) | Exported Function | 0x10019194 | 0x00019194
`class CIlWimgapi IlWimgapi` | 325 (0x145) | Exported Function | 0x10019158 | 0x00019158
`const CIlAdvapi32::``vftable'` | 108 (0x6c) | Exported Function | 0x100010dc | 0x000010dc
`private: static int (__stdcall* CIlNt4Advapi32::m_ConvertSecurityDescriptorToStringSecurityDescriptorW)(void *,unsigned long,unsigned long,unsigned short * *,unsigned long *)` | 551 (0x227) | Exported Function | 0x100195dc | 0x000195dc
`private: static int (__stdcall* CIlNt4Advapi32::m_ConvertSidToStringSidW)(void *,unsigned short * *)` | 552 (0x228) | Exported Function | 0x100195c8 | 0x000195c8
`private: static int (__stdcall* CIlNt4Advapi32::m_ConvertStringSecurityDescriptorToSecurityDescriptorW)(unsigned short const *,unsigned long,void * *,unsigned long *)` | 553 (0x229) | Exported Function | 0x10019650 | 0x00019650
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupDiOpenDeviceInfoW)(void *,unsigned short const *,struct HWND__ *,unsigned long,struct _SP_DEVINFO_DATA *)` | 659 (0x293) | Exported Function | 0x10019634 | 0x00019634
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupDiSetDeviceInstallParamsW)(void *,struct _SP_DEVINFO_DATA *,struct _SP_DEVINSTALL_PARAMS_W *)` | 660 (0x294) | Exported Function | 0x10019538 | 0x00019538
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupDiSetSelectedDriverW)(void *,struct _SP_DEVINFO_DATA *,struct _SP_DRVINFO_DATA_V2_W *)` | 661 (0x295) | Exported Function | 0x10019628 | 0x00019628
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupGetInfInformationW)(void const *,unsigned long,struct _SP_INF_INFORMATION *,unsigned long,unsigned long *)` | 662 (0x296) | Exported Function | 0x100195a0 | 0x000195a0
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupQueryInfOriginalFileInformationW)(struct _SP_INF_INFORMATION *,unsigned int,struct _SP_ALTPLATFORM_INFO_V2 *,struct _SP_ORIGINAL_FILE_INFO_W *)` | 664 (0x298) | Exported Function | 0x10019548 | 0x00019548
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupScanFileQueueW)(void *,unsigned long,struct HWND__ *,unsigned int (__stdcall*)(void *,unsigned int,unsigned int,unsigned int),void *,unsigned long *)` | 665 (0x299) | Exported Function | 0x100196cc | 0x000196cc
`private: static int (__stdcall* CIlNt4User32::m_LockSetForegroundWindow)(unsigned int)` | 566 (0x236) | Exported Function | 0x10019584 | 0x00019584
`private: static int (__stdcall* CIlNt4Userenv::m_CreateUserProfileExW)(void *,unsigned short const *,unsigned short const *,unsigned short *,unsigned long,int)` | 558 (0x22e) | Exported Function | 0x10019558 | 0x00019558
`private: static int (__stdcall* CIlW2kDynWs2_32::m_getaddrinfo)(char const *,char const *,struct addrinfo const *,struct addrinfo * *)` | 669 (0x29d) | Exported Function | 0x10019544 | 0x00019544
`private: static int (__stdcall* CIlW2kDynWs2_32::m_getnameinfo)(struct sockaddr const *,int,char *,unsigned long,char *,unsigned long,int)` | 670 (0x29e) | Exported Function | 0x100196e0 | 0x000196e0
`private: static int __stdcall CIlNt4Advapi32::IlChangeServiceConfigW(struct SC_HANDLE__ *,unsigned long,unsigned long,unsigned long,unsigned short const *,unsigned short const *,unsigned long *,unsigned short const *,unsigned short const *,unsigned short const *,unsigned short const *)` | 249 (0xf9) | Exported Function | 0x10006b70 | 0x00006b70
`private: static int __stdcall CIlNt4Advapi32::IlCloseServiceHandle(struct SC_HANDLE__ *)` | 250 (0xfa) | Exported Function | 0x10007030 | 0x00007030
`private: static int __stdcall CIlNt4Advapi32::IlConvertSecurityDescriptorToStringSecurityDescriptorW(void *,unsigned long,unsigned long,unsigned short * *,unsigned long *)` | 251 (0xfb) | Exported Function | 0x100066d0 | 0x000066d0
`private: static int __stdcall CIlNt4Advapi32::IlConvertSidToStringSidW(void *,unsigned short * *)` | 252 (0xfc) | Exported Function | 0x10006570 | 0x00006570
`private: static int __stdcall CIlNt4Advapi32::IlConvertStringSecurityDescriptorToSecurityDescriptorW(unsigned short const *,unsigned long,void * *,unsigned long *)` | 253 (0xfd) | Exported Function | 0x10006790 | 0x00006790
`private: static int __stdcall CIlNt4Advapi32::IlConvertStringSidToSidW(unsigned short *,void * *)` | 254 (0xfe) | Exported Function | 0x10006620 | 0x00006620
`private: static int __stdcall CIlNt4Advapi32::IlCreateWellKnownSid(enum WELL_KNOWN_SID_TYPE,void *,void *,unsigned long *)` | 259 (0x103) | Exported Function | 0x10006850 | 0x00006850
`private: static int __stdcall CIlNt4Advapi32::IlEncryptFileW(unsigned short const *)` | 261 (0x105) | Exported Function | 0x100071b0 | 0x000071b0
`private: static int __stdcall CIlNt4Advapi32::IlEnumServicesStatusExW(struct SC_HANDLE__ *,enum _SC_ENUM_TYPE,unsigned long,unsigned long,unsigned char *,unsigned long,unsigned long *,unsigned long *,unsigned long *,unsigned short const *)` | 262 (0x106) | Exported Function | 0x10006e00 | 0x00006e00
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupDiGetDriverInfoDetailW)(void *,struct _SP_DEVINFO_DATA *,struct _SP_DRVINFO_DATA_V2_W *,struct _SP_DRVINFO_DETAIL_DATA_W *,unsigned long,unsigned long *)` | 657 (0x291) | Exported Function | 0x10019570 | 0x00019570
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupDiGetDeviceRegistryPropertyW)(void *,struct _SP_DEVINFO_DATA *,unsigned long,unsigned long *,unsigned char *,unsigned long,unsigned long *)` | 656 (0x290) | Exported Function | 0x10019714 | 0x00019714
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupDiGetDeviceInterfaceDetailW)(void *,struct _SP_DEVICE_INTERFACE_DATA *,struct _SP_DEVICE_INTERFACE_DETAIL_DATA_W *,unsigned long,unsigned long *,struct _SP_DEVINFO_DATA *)` | 655 (0x28f) | Exported Function | 0x10019658 | 0x00019658
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupDiGetDeviceInstallParamsW)(void *,struct _SP_DEVINFO_DATA *,struct _SP_DEVINSTALL_PARAMS_W *)` | 654 (0x28e) | Exported Function | 0x10019598 | 0x00019598
`private: static int (__stdcall* CIlNt4Advapi32::m_ConvertStringSidToSidW)(unsigned short *,void * *)` | 554 (0x22a) | Exported Function | 0x10019610 | 0x00019610
`private: static int (__stdcall* CIlNt4Advapi32::m_CreateWellKnownSid)(enum WELL_KNOWN_SID_TYPE,void *,void *,unsigned long *)` | 559 (0x22f) | Exported Function | 0x100196c8 | 0x000196c8
`private: static int (__stdcall* CIlNt4Advapi32::m_EncryptFileW)(unsigned short const *)` | 560 (0x230) | Exported Function | 0x10019568 | 0x00019568
`private: static int (__stdcall* CIlNt4Advapi32::m_EnumServicesStatusExW)(struct SC_HANDLE__ *,enum _SC_ENUM_TYPE,unsigned long,unsigned long,unsigned char *,unsigned long,unsigned long *,unsigned long *,unsigned long *,unsigned short const *)` | 561 (0x231) | Exported Function | 0x100195b8 | 0x000195b8
`private: static int (__stdcall* CIlNt4Advapi32::m_InitiateSystemShutdownExW)(unsigned short *,unsigned short *,unsigned long,int,int,unsigned long)` | 564 (0x234) | Exported Function | 0x100195cc | 0x000195cc
`private: static int (__stdcall* CIlNt4Advapi32::m_QueryServiceConfigW)(struct SC_HANDLE__ *,struct _QUERY_SERVICE_CONFIGW *,unsigned long,unsigned long *)` | 580 (0x244) | Exported Function | 0x10019560 | 0x00019560
`private: static int (__stdcall* CIlNt4Advapi32::m_StartServiceW)(struct SC_HANDLE__ *,unsigned long,unsigned short const * *)` | 666 (0x29a) | Exported Function | 0x10019690 | 0x00019690
`private: static int (__stdcall* CIlNt4Advapi32::m_UnlockServiceDatabase)(void *)` | 667 (0x29b) | Exported Function | 0x1001964c | 0x0001964c
`private: static int (__stdcall* CIlNt4Kernel32::m_GlobalMemoryStatusEx)(struct _MEMORYSTATUSEX *)` | 563 (0x233) | Exported Function | 0x10019530 | 0x00019530
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupCloseFileQueue` | 614 (0x266) | Exported Function | 0x10019684 | 0x00019684
`private: static int (__stdcall* CIlNt4Kernel32::m_Process32FirstW)(void *,struct tagPROCESSENTRY32W *)` | 578 (0x242) | Exported Function | 0x10019574 | 0x00019574
`private: static int (__stdcall* CIlNt4Kernel32::m_RegisterWaitForSingleObject)(void * *,void *,void (__stdcall*)(void *,unsigned char),void *,unsigned long,unsigned long)` | 642 (0x282) | Exported Function | 0x10019660 | 0x00019660
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupCloseFileQueue)(void *)` | 643 (0x283) | Exported Function | 0x10019698 | 0x00019698
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupDiBuildDriverInfoList)(void *,struct _SP_DEVINFO_DATA *,unsigned long)` | 644 (0x284) | Exported Function | 0x10019648 | 0x00019648
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupDiCallClassInstaller)(unsigned int,void *,struct _SP_DEVINFO_DATA *)` | 645 (0x285) | Exported Function | 0x10019540 | 0x00019540
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupDiDestroyDeviceInfoList)(void *)` | 647 (0x287) | Exported Function | 0x1001958c | 0x0001958c
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupDiDestroyDriverInfoList)(void *,struct _SP_DEVINFO_DATA *,unsigned long)` | 648 (0x288) | Exported Function | 0x10019624 | 0x00019624
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupDiEnumDeviceInfo)(void *,unsigned long,struct _SP_DEVINFO_DATA *)` | 649 (0x289) | Exported Function | 0x100196f4 | 0x000196f4
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupDiEnumDeviceInterfaces)(void *,struct _SP_DEVINFO_DATA *,struct _GUID const *,unsigned long,struct _SP_DEVICE_INTERFACE_DATA *)` | 650 (0x28a) | Exported Function | 0x10019708 | 0x00019708
`private: static int (__stdcall* CIlNt4Setupapi::m_SetupDiEnumDriverInfoW)(void *,struct _SP_DEVINFO_DATA *,unsigned long,unsigned long,struct _SP_DRVINFO_DATA_V2_W *)` | 651 (0x28b) | Exported Function | 0x10019614 | 0x00019614
`private: static int (__stdcall* CIlNt4Kernel32::m_Process32NextW)(void *,struct tagPROCESSENTRY32W *)` | 579 (0x243) | Exported Function | 0x100195ac | 0x000195ac
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupScanFileQueueW(void))(void *,unsigned long,struct HWND__ *,unsigned int (__stdcall*)(void *,unsigned int,unsigned int,unsigned int),void *,unsigned long *)` | 531 (0x213) | Exported Function | 0x10009680 | 0x00009680
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiBuildDriverInfoList` | 615 (0x267) | Exported Function | 0x1001968c | 0x0001968c
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiCreateDeviceInfoListExW` | 617 (0x269) | Exported Function | 0x10019534 | 0x00019534
`public: class CIlNt4Advapi32 & __thiscall CIlNt4Advapi32::operator=(class CIlNt4Advapi32 &&)` | 76 (0x4c) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlNt4Advapi32 & __thiscall CIlNt4Advapi32::operator=(class CIlNt4Advapi32 const &)` | 77 (0x4d) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlNt4Kernel32 & __thiscall CIlNt4Kernel32::operator=(class CIlNt4Kernel32 &&)` | 78 (0x4e) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlNt4Kernel32 & __thiscall CIlNt4Kernel32::operator=(class CIlNt4Kernel32 const &)` | 79 (0x4f) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlNt4Netapi32 & __thiscall CIlNt4Netapi32::operator=(class CIlNt4Netapi32 &&)` | 80 (0x50) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlNt4Netapi32 & __thiscall CIlNt4Netapi32::operator=(class CIlNt4Netapi32 const &)` | 81 (0x51) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlNt4Setupapi & __thiscall CIlNt4Setupapi::operator=(class CIlNt4Setupapi &&)` | 82 (0x52) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlNt4Setupapi & __thiscall CIlNt4Setupapi::operator=(class CIlNt4Setupapi const &)` | 83 (0x53) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlNt4User32 & __thiscall CIlNt4User32::operator=(class CIlNt4User32 &&)` | 84 (0x54) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlNt4User32 & __thiscall CIlNt4User32::operator=(class CIlNt4User32 const &)` | 85 (0x55) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlNt4Userenv & __thiscall CIlNt4Userenv::operator=(class CIlNt4Userenv &&)` | 86 (0x56) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlNt4Userenv & __thiscall CIlNt4Userenv::operator=(class CIlNt4Userenv const &)` | 87 (0x57) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlNt6Userenv & __thiscall CIlNt6Userenv::operator=(class CIlNt6Userenv &&)` | 88 (0x58) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlNt6Userenv & __thiscall CIlNt6Userenv::operator=(class CIlNt6Userenv const &)` | 89 (0x59) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlOle32 & __thiscall CIlOle32::operator=(class CIlOle32 &&)` | 90 (0x5a) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlOle32 & __thiscall CIlOle32::operator=(class CIlOle32 const &)` | 91 (0x5b) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlOleaut32 & __thiscall CIlOleaut32::operator=(class CIlOleaut32 &&)` | 92 (0x5c) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlOleaut32 & __thiscall CIlOleaut32::operator=(class CIlOleaut32 const &)` | 93 (0x5d) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlSetupapi & __thiscall CIlSetupapi::operator=(class CIlSetupapi &&)` | 94 (0x5e) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlMuisetupapi & __thiscall CIlMuisetupapi::operator=(class CIlMuisetupapi const &)` | 75 (0x4b) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlSetupapi & __thiscall CIlSetupapi::operator=(class CIlSetupapi const &)` | 95 (0x5f) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlMuisetupapi & __thiscall CIlMuisetupapi::operator=(class CIlMuisetupapi &&)` | 74 (0x4a) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlIphlpapi & __thiscall CIlIphlpapi::operator=(class CIlIphlpapi const &)` | 72 (0x48) | Exported Function | 0x10006450 | 0x00006450
`public: __thiscall CIlVersion::CIlVersion(class CIlVersion &&)` | 52 (0x34) | Exported Function | 0x1000a1e0 | 0x0000a1e0
`public: __thiscall CIlVersion::CIlVersion(class CIlVersion const &)` | 53 (0x35) | Exported Function | 0x1000a1e0 | 0x0000a1e0
`public: __thiscall CIlVersion::CIlVersion(void)` | 54 (0x36) | Exported Function | 0x1000a1d0 | 0x0000a1d0
`public: __thiscall CIlW2kDynWs2_32::CIlW2kDynWs2_32(class CIlW2kDynWs2_32 &&)` | 55 (0x37) | Exported Function | 0x1000a8b0 | 0x0000a8b0
`public: __thiscall CIlW2kDynWs2_32::CIlW2kDynWs2_32(class CIlW2kDynWs2_32 const &)` | 56 (0x38) | Exported Function | 0x1000a8b0 | 0x0000a8b0
`public: __thiscall CIlW2kDynWs2_32::CIlW2kDynWs2_32(void)` | 57 (0x39) | Exported Function | 0x1000a890 | 0x0000a890
`public: __thiscall CIlWimgapi::CIlWimgapi(class CIlWimgapi &&)` | 58 (0x3a) | Exported Function | 0x1000a2e0 | 0x0000a2e0
`public: __thiscall CIlWimgapi::CIlWimgapi(class CIlWimgapi const &)` | 59 (0x3b) | Exported Function | 0x1000a2e0 | 0x0000a2e0
`public: __thiscall CIlWimgapi::CIlWimgapi(void)` | 60 (0x3c) | Exported Function | 0x1000a2d0 | 0x0000a2d0
`public: __thiscall CIlWs2_32::CIlWs2_32(class CIlWs2_32 &&)` | 61 (0x3d) | Exported Function | 0x1000a640 | 0x0000a640
`public: __thiscall CIlWs2_32::CIlWs2_32(class CIlWs2_32 const &)` | 62 (0x3e) | Exported Function | 0x1000a640 | 0x0000a640
`public: __thiscall CIlWs2_32::CIlWs2_32(void)` | 63 (0x3f) | Exported Function | 0x1000a630 | 0x0000a630
`public: class CDynLib & __thiscall CDynLib::operator=(class CDynLib &&)` | 65 (0x41) | Exported Function | 0x10006520 | 0x00006520
`public: class CDynLib & __thiscall CDynLib::operator=(class CDynLib const &)` | 66 (0x42) | Exported Function | 0x10006520 | 0x00006520
`public: class CIlAdvapi32 & __thiscall CIlAdvapi32::operator=(class CIlAdvapi32 &&)` | 67 (0x43) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlAdvapi32 & __thiscall CIlAdvapi32::operator=(class CIlAdvapi32 const &)` | 68 (0x44) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlDeplorch & __thiscall CIlDeplorch::operator=(class CIlDeplorch &&)` | 69 (0x45) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlDeplorch & __thiscall CIlDeplorch::operator=(class CIlDeplorch const &)` | 70 (0x46) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlIphlpapi & __thiscall CIlIphlpapi::operator=(class CIlIphlpapi &&)` | 71 (0x47) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlKernel32 & __thiscall CIlKernel32::operator=(class CIlKernel32 const &)` | 73 (0x49) | Exported Function | 0x10006450 | 0x00006450
`public: __thiscall CIlUser32::CIlUser32(void)` | 51 (0x33) | Exported Function | 0x10009e20 | 0x00009e20
`public: class CIlShell32 & __thiscall CIlShell32::operator=(class CIlShell32 &&)` | 96 (0x60) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlUser32 & __thiscall CIlUser32::operator=(class CIlUser32 &&)` | 98 (0x62) | Exported Function | 0x10006450 | 0x00006450
`public: int (__stdcall*__thiscall CIlNt4Kernel32::get_Process32FirstW(void))(void *,struct tagPROCESSENTRY32W *)` | 505 (0x1f9) | Exported Function | 0x10007fb0 | 0x00007fb0
`public: int (__stdcall*__thiscall CIlNt4Kernel32::get_Process32NextW(void))(void *,struct tagPROCESSENTRY32W *)` | 506 (0x1fa) | Exported Function | 0x10008060 | 0x00008060
`public: int (__stdcall*__thiscall CIlNt4Kernel32::get_RegisterWaitForSingleObject(void))(void * *,void *,void (__stdcall*)(void *,unsigned char),void *,unsigned long,unsigned long)` | 508 (0x1fc) | Exported Function | 0x10007e50 | 0x00007e50
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupCloseFileQueue(void))(void *)` | 509 (0x1fd) | Exported Function | 0x10009730 | 0x00009730
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiBuildDriverInfoList(void))(void *,struct _SP_DEVINFO_DATA *,unsigned long)` | 510 (0x1fe) | Exported Function | 0x10009090 | 0x00009090
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiCallClassInstaller(void))(unsigned int,void *,struct _SP_DEVINFO_DATA *)` | 511 (0x1ff) | Exported Function | 0x100093a0 | 0x000093a0
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiDestroyDeviceInfoList(void))(void *)` | 513 (0x201) | Exported Function | 0x10009510 | 0x00009510
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiDestroyDriverInfoList(void))(void *,struct _SP_DEVINFO_DATA *,unsigned long)` | 514 (0x202) | Exported Function | 0x10008fd0 | 0x00008fd0
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiEnumDeviceInfo(void))(void *,unsigned long,struct _SP_DEVINFO_DATA *)` | 515 (0x203) | Exported Function | 0x10008f10 | 0x00008f10
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiEnumDeviceInterfaces(void))(void *,struct _SP_DEVINFO_DATA *,struct _GUID const *,unsigned long,struct _SP_DEVICE_INTERFACE_DATA *)` | 516 (0x204) | Exported Function | 0x10009bd0 | 0x00009bd0
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiEnumDriverInfoW(void))(void *,struct _SP_DEVINFO_DATA *,unsigned long,unsigned long,struct _SP_DRVINFO_DATA_V2_W *)` | 517 (0x205) | Exported Function | 0x10009a40 | 0x00009a40
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiGetDeviceInstallParamsW(void))(void *,struct _SP_DEVINFO_DATA *,struct _SP_DEVINSTALL_PARAMS_W *)` | 520 (0x208) | Exported Function | 0x10009220 | 0x00009220
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiGetDeviceInterfaceDetailW(void))(void *,struct _SP_DEVICE_INTERFACE_DATA *,struct _SP_DEVICE_INTERFACE_DETAIL_DATA_W *,unsigned long,unsigned long *,struct _SP_DEVINFO_DATA *)` | 521 (0x209) | Exported Function | 0x10009ca0 | 0x00009ca0
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiGetDeviceRegistryPropertyW(void))(void *,struct _SP_DEVINFO_DATA *,unsigned long,unsigned long *,unsigned char *,unsigned long,unsigned long *)` | 522 (0x20a) | Exported Function | 0x10009980 | 0x00009980
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiGetDriverInfoDetailW(void))(void *,struct _SP_DEVINFO_DATA *,struct _SP_DRVINFO_DATA_V2_W *,struct _SP_DRVINFO_DETAIL_DATA_W *,unsigned long,unsigned long *)` | 523 (0x20b) | Exported Function | 0x10009160 | 0x00009160
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiOpenDeviceInfoW(void))(void *,unsigned short const *,struct HWND__ *,unsigned long,struct _SP_DEVINFO_DATA *)` | 525 (0x20d) | Exported Function | 0x10008e50 | 0x00008e50
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiSetDeviceInstallParamsW(void))(void *,struct _SP_DEVINFO_DATA *,struct _SP_DEVINSTALL_PARAMS_W *)` | 526 (0x20e) | Exported Function | 0x100092e0 | 0x000092e0
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupDiSetSelectedDriverW(void))(void *,struct _SP_DEVINFO_DATA *,struct _SP_DRVINFO_DATA_V2_W *)` | 527 (0x20f) | Exported Function | 0x10009460 | 0x00009460
`public: int (__stdcall*__thiscall CIlNt4Setupapi::get_SetupGetInfInformationW(void))(void const *,unsigned long,struct _SP_INF_INFORMATION *,unsigned long,unsigned long *)` | 528 (0x210) | Exported Function | 0x100097f0 | 0x000097f0
`public: int (__stdcall*__thiscall CIlNt4Kernel32::get_GlobalMemoryStatusEx(void))(struct _MEMORYSTATUSEX *)` | 490 (0x1ea) | Exported Function | 0x100081c0 | 0x000081c0
`public: class CIlShell32 & __thiscall CIlShell32::operator=(class CIlShell32 const &)` | 97 (0x61) | Exported Function | 0x10006450 | 0x00006450
`public: int (__stdcall*__thiscall CIlNt4Advapi32::get_UnlockServiceDatabase(void))(void *)` | 533 (0x215) | Exported Function | 0x10006fb0 | 0x00006fb0
`public: int (__stdcall*__thiscall CIlNt4Advapi32::get_QueryServiceConfigW(void))(struct SC_HANDLE__ *,struct _QUERY_SERVICE_CONFIGW *,unsigned long,unsigned long *)` | 507 (0x1fb) | Exported Function | 0x10006ad0 | 0x00006ad0
`public: class CIlUser32 & __thiscall CIlUser32::operator=(class CIlUser32 const &)` | 99 (0x63) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlVersion & __thiscall CIlVersion::operator=(class CIlVersion &&)` | 100 (0x64) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlVersion & __thiscall CIlVersion::operator=(class CIlVersion const &)` | 101 (0x65) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlW2kDynWs2_32 & __thiscall CIlW2kDynWs2_32::operator=(class CIlW2kDynWs2_32 &&)` | 102 (0x66) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlW2kDynWs2_32 & __thiscall CIlW2kDynWs2_32::operator=(class CIlW2kDynWs2_32 const &)` | 103 (0x67) | Exported Function | 0x10007280 | 0x00007280
`public: class CIlWimgapi & __thiscall CIlWimgapi::operator=(class CIlWimgapi &&)` | 104 (0x68) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlWimgapi & __thiscall CIlWimgapi::operator=(class CIlWimgapi const &)` | 105 (0x69) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlWs2_32 & __thiscall CIlWs2_32::operator=(class CIlWs2_32 &&)` | 106 (0x6a) | Exported Function | 0x10006450 | 0x00006450
`public: class CIlWs2_32 & __thiscall CIlWs2_32::operator=(class CIlWs2_32 const &)` | 107 (0x6b) | Exported Function | 0x10006450 | 0x00006450
`public: int (__stdcall*__thiscall CIlNt4Advapi32::get_ChangeServiceConfigW(void))(struct SC_HANDLE__ *,unsigned long,unsigned long,unsigned long,unsigned short const *,unsigned short const *,unsigned long *,unsigned short const *,unsigned short const *,unsigned short const *,unsigned short const *)` | 476 (0x1dc) | Exported Function | 0x10006bc0 | 0x00006bc0
`public: int (__stdcall*__thiscall CIlNt4Advapi32::get_CloseServiceHandle(void))(struct SC_HANDLE__ *)` | 477 (0x1dd) | Exported Function | 0x10007060 | 0x00007060
`public: int (__stdcall*__thiscall CIlNt4Advapi32::get_ConvertSecurityDescriptorToStringSecurityDescriptorW(void))(void *,unsigned long,unsigned long,unsigned short * *,unsigned long *)` | 478 (0x1de) | Exported Function | 0x10006710 | 0x00006710
`public: int (__stdcall*__thiscall CIlNt4Advapi32::get_ConvertSidToStringSidW(void))(void *,unsigned short * *)` | 479 (0x1df) | Exported Function | 0x100065a0 | 0x000065a0
`public: int (__stdcall*__thiscall CIlNt4Advapi32::get_ConvertStringSecurityDescriptorToSecurityDescriptorW(void))(unsigned short const *,unsigned long,void * *,unsigned long *)` | 480 (0x1e0) | Exported Function | 0x100067d0 | 0x000067d0
`public: int (__stdcall*__thiscall CIlNt4Advapi32::get_ConvertStringSidToSidW(void))(unsigned short *,void * *)` | 481 (0x1e1) | Exported Function | 0x10006650 | 0x00006650
`public: int (__stdcall*__thiscall CIlNt4Advapi32::get_CreateWellKnownSid(void))(enum WELL_KNOWN_SID_TYPE,void *,void *,unsigned long *)` | 486 (0x1e6) | Exported Function | 0x10006890 | 0x00006890
`public: int (__stdcall*__thiscall CIlNt4Advapi32::get_EncryptFileW(void))(unsigned short const *)` | 487 (0x1e7) | Exported Function | 0x100071e0 | 0x000071e0
`public: int (__stdcall*__thiscall CIlNt4Advapi32::get_EnumServicesStatusExW(void))(struct SC_HANDLE__ *,enum _SC_ENUM_TYPE,unsigned long,unsigned long,unsigned char *,unsigned long,unsigned long *,unsigned long *,unsigned long *,unsigned short const *)` | 488 (0x1e8) | Exported Function | 0x10006e50 | 0x00006e50
`public: int (__stdcall*__thiscall CIlNt4Advapi32::get_InitiateSystemShutdownExW(void))(unsigned short *,unsigned short *,unsigned long,int,int,unsigned long)` | 491 (0x1eb) | Exported Function | 0x10007130 | 0x00007130
`public: int (__stdcall*__thiscall CIlNt4Advapi32::get_StartServiceW(void))(struct SC_HANDLE__ *,unsigned long,unsigned short const * *)` | 532 (0x214) | Exported Function | 0x10006d70 | 0x00006d70
`public: __thiscall CIlUser32::CIlUser32(class CIlUser32 const &)` | 50 (0x32) | Exported Function | 0x10009e30 | 0x00009e30
`public: __thiscall CIlUser32::CIlUser32(class CIlUser32 &&)` | 49 (0x31) | Exported Function | 0x10009e30 | 0x00009e30
`public: __thiscall CIlShell32::CIlShell32(void)` | 48 (0x30) | Exported Function | 0x10009d80 | 0x00009d80
`private: static unsigned long CIlW2kDynWs2_32::m_RefCountgetaddrinfo` | 640 (0x280) | Exported Function | 0x1001957c | 0x0001957c
`private: static unsigned long CIlW2kDynWs2_32::m_RefCountgetnameinfo` | 641 (0x281) | Exported Function | 0x10019550 | 0x00019550
`private: static void (__stdcall* CIlW2kDynWs2_32::m_freeaddrinfo)(struct addrinfo *)` | 668 (0x29c) | Exported Function | 0x100196bc | 0x000196bc
`private: static void * (__stdcall* CIlNt4Advapi32::m_LockServiceDatabase)(struct SC_HANDLE__ *)` | 565 (0x235) | Exported Function | 0x1001961c | 0x0001961c
`private: static void * (__stdcall* CIlNt4Kernel32::m_CreateToolhelp32Snapshot)(unsigned long,unsigned long)` | 557 (0x22d) | Exported Function | 0x100196e8 | 0x000196e8
`private: static void * (__stdcall* CIlNt4Setupapi::m_SetupDiCreateDeviceInfoListExW)(struct _GUID const *,struct HWND__ *,unsigned short const *,void *)` | 646 (0x286) | Exported Function | 0x10019644 | 0x00019644
`private: static void * (__stdcall* CIlNt4Setupapi::m_SetupDiGetClassDevsExW)(struct _GUID const *,unsigned short const *,struct HWND__ *,unsigned long,void *,unsigned short const *,void *)` | 652 (0x28c) | Exported Function | 0x10019688 | 0x00019688
`private: static void * (__stdcall* CIlNt4Setupapi::m_SetupDiGetClassDevsW)(struct _GUID const *,unsigned short const *,struct HWND__ *,unsigned long)` | 653 (0x28d) | Exported Function | 0x100195a8 | 0x000195a8
`private: static void * (__stdcall* CIlNt4Setupapi::m_SetupOpenFileQueue)(void)` | 663 (0x297) | Exported Function | 0x100195fc | 0x000195fc
`private: static void * __stdcall CIlNt4Advapi32::IlLockServiceDatabase(struct SC_HANDLE__ *)` | 268 (0x10c) | Exported Function | 0x10006ed0 | 0x00006ed0
`private: static void * __stdcall CIlNt4Kernel32::IlCreateToolhelp32Snapshot(unsigned long,unsigned long)` | 257 (0x101) | Exported Function | 0x10007ed0 | 0x00007ed0
`private: static void * __stdcall CIlNt4Setupapi::IlSetupDiCreateDeviceInfoListExW(struct _GUID const *,struct HWND__ *,unsigned short const *,void *)` | 298 (0x12a) | Exported Function | 0x10008bc0 | 0x00008bc0
`private: static void * __stdcall CIlNt4Setupapi::IlSetupDiGetClassDevsExW(struct _GUID const *,unsigned short const *,struct HWND__ *,unsigned long,void *,unsigned short const *,void *)` | 304 (0x130) | Exported Function | 0x10008c90 | 0x00008c90
`private: static void * __stdcall CIlNt4Setupapi::IlSetupDiGetClassDevsW(struct _GUID const *,unsigned short const *,struct HWND__ *,unsigned long)` | 305 (0x131) | Exported Function | 0x10008d50 | 0x00008d50
`private: static void * __stdcall CIlNt4Setupapi::IlSetupOpenFileQueue(void)` | 315 (0x13b) | Exported Function | 0x10009580 | 0x00009580
`private: static void __stdcall CIlW2kDynWs2_32::Ilfreeaddrinfo(struct addrinfo *)` | 327 (0x147) | Exported Function | 0x1000a810 | 0x0000a810
`protected: __thiscall CDynLib::CDynLib(void)` | 1 (0x1) | Exported Function | 0x10006460 | 0x00006460
`protected: int (__stdcall*__thiscall CDynLib::GetIlProc(unsigned short const *,char const *,int (__stdcall*)(void),int (__stdcall*&)(void),unsigned long &))(void)` | 204 (0xcc) | Exported Function | 0x10006470 | 0x00006470
`protected: void __thiscall CDynLib::ReleaseProc(int (__stdcall*&)(void),unsigned long &)` | 382 (0x17e) | Exported Function | 0x100064d0 | 0x000064d0
`private: static unsigned long CIlW2kDynWs2_32::m_RefCountfreeaddrinfo` | 639 (0x27f) | Exported Function | 0x10019680 | 0x00019680
`public: __thiscall CIlAdvapi32::CIlAdvapi32(class CIlAdvapi32 &&)` | 2 (0x2) | Exported Function | 0x10006440 | 0x00006440
`private: static unsigned long CIlNt6Userenv::m_RefCountCreateProfile` | 587 (0x24b) | Exported Function | 0x100195c0 | 0x000195c0
`private: static unsigned long CIlNt4User32::m_RefCountLockSetForegroundWindow` | 598 (0x256) | Exported Function | 0x1001955c | 0x0001955c
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiDestroyDeviceInfoList` | 618 (0x26a) | Exported Function | 0x10019590 | 0x00019590
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiDestroyDriverInfoList` | 619 (0x26b) | Exported Function | 0x100196ec | 0x000196ec
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiEnumDeviceInfo` | 620 (0x26c) | Exported Function | 0x100196d0 | 0x000196d0
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiEnumDeviceInterfaces` | 621 (0x26d) | Exported Function | 0x100195a4 | 0x000195a4
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiEnumDriverInfoW` | 622 (0x26e) | Exported Function | 0x100195b4 | 0x000195b4
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiGetClassDevsExW` | 623 (0x26f) | Exported Function | 0x100195e0 | 0x000195e0
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiGetClassDevsW` | 624 (0x270) | Exported Function | 0x1001959c | 0x0001959c
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiGetDeviceInstallParamsW` | 625 (0x271) | Exported Function | 0x100196f8 | 0x000196f8
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiGetDeviceInterfaceDetailW` | 626 (0x272) | Exported Function | 0x100195e8 | 0x000195e8
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiGetDeviceRegistryPropertyW` | 627 (0x273) | Exported Function | 0x1001956c | 0x0001956c
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiGetDriverInfoDetailW` | 628 (0x274) | Exported Function | 0x100195c4 | 0x000195c4
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiOpenDeviceInfoW` | 630 (0x276) | Exported Function | 0x100195f4 | 0x000195f4
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiOpenDevRegKey` | 629 (0x275) | Exported Function | 0x10019620 | 0x00019620
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiSetDeviceInstallParamsW` | 631 (0x277) | Exported Function | 0x100196f0 | 0x000196f0
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiSetSelectedDriverW` | 632 (0x278) | Exported Function | 0x100195e4 | 0x000195e4
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupGetInfInformationW` | 633 (0x279) | Exported Function | 0x10019710 | 0x00019710
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupOpenFileQueue` | 634 (0x27a) | Exported Function | 0x10019654 | 0x00019654
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupQueryInfOriginalFileInformationW` | 635 (0x27b) | Exported Function | 0x100196a8 | 0x000196a8
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupScanFileQueueW` | 636 (0x27c) | Exported Function | 0x10019640 | 0x00019640
`private: static unsigned long CIlNt4Userenv::m_RefCountCreateUserProfileExW` | 590 (0x24e) | Exported Function | 0x10019630 | 0x00019630
`public: __thiscall CIlAdvapi32::CIlAdvapi32(class CIlAdvapi32 const &)` | 3 (0x3) | Exported Function | 0x10006440 | 0x00006440
`public: __thiscall CIlAdvapi32::CIlAdvapi32(void)` | 4 (0x4) | Exported Function | 0x10006430 | 0x00006430
`public: __thiscall CIlDeplorch::CIlDeplorch(class CIlDeplorch &&)` | 5 (0x5) | Exported Function | 0x10007300 | 0x00007300
`public: __thiscall CIlNt4User32::CIlNt4User32(class CIlNt4User32 const &)` | 29 (0x1d) | Exported Function | 0x10009f10 | 0x00009f10
`public: __thiscall CIlNt4User32::CIlNt4User32(void)` | 30 (0x1e) | Exported Function | 0x10009ef0 | 0x00009ef0
`public: __thiscall CIlNt4Userenv::CIlNt4Userenv(class CIlNt4Userenv &&)` | 31 (0x1f) | Exported Function | 0x1000a030 | 0x0000a030
`public: __thiscall CIlNt4Userenv::CIlNt4Userenv(class CIlNt4Userenv const &)` | 32 (0x20) | Exported Function | 0x1000a030 | 0x0000a030
`public: __thiscall CIlNt4Userenv::CIlNt4Userenv(void)` | 33 (0x21) | Exported Function | 0x1000a010 | 0x0000a010
`public: __thiscall CIlNt6Userenv::CIlNt6Userenv(class CIlNt6Userenv &&)` | 34 (0x22) | Exported Function | 0x1000a140 | 0x0000a140
`public: __thiscall CIlNt6Userenv::CIlNt6Userenv(class CIlNt6Userenv const &)` | 35 (0x23) | Exported Function | 0x1000a140 | 0x0000a140
`public: __thiscall CIlNt6Userenv::CIlNt6Userenv(void)` | 36 (0x24) | Exported Function | 0x1000a120 | 0x0000a120
`public: __thiscall CIlOle32::CIlOle32(class CIlOle32 &&)` | 37 (0x25) | Exported Function | 0x10008a70 | 0x00008a70
`public: __thiscall CIlOle32::CIlOle32(class CIlOle32 const &)` | 38 (0x26) | Exported Function | 0x10008a70 | 0x00008a70
`public: __thiscall CIlOle32::CIlOle32(void)` | 39 (0x27) | Exported Function | 0x10008a60 | 0x00008a60
`public: __thiscall CIlOleaut32::CIlOleaut32(class CIlOleaut32 &&)` | 40 (0x28) | Exported Function | 0x10008ab0 | 0x00008ab0
`public: __thiscall CIlOleaut32::CIlOleaut32(class CIlOleaut32 const &)` | 41 (0x29) | Exported Function | 0x10008ab0 | 0x00008ab0
`public: __thiscall CIlOleaut32::CIlOleaut32(void)` | 42 (0x2a) | Exported Function | 0x10008aa0 | 0x00008aa0
`public: __thiscall CIlSetupapi::CIlSetupapi(class CIlSetupapi &&)` | 43 (0x2b) | Exported Function | 0x10008b80 | 0x00008b80
`public: __thiscall CIlSetupapi::CIlSetupapi(class CIlSetupapi const &)` | 44 (0x2c) | Exported Function | 0x10008b80 | 0x00008b80
`public: __thiscall CIlSetupapi::CIlSetupapi(void)` | 45 (0x2d) | Exported Function | 0x10008b70 | 0x00008b70
`public: __thiscall CIlShell32::CIlShell32(class CIlShell32 &&)` | 46 (0x2e) | Exported Function | 0x10009d90 | 0x00009d90
`public: __thiscall CIlShell32::CIlShell32(class CIlShell32 const &)` | 47 (0x2f) | Exported Function | 0x10009d90 | 0x00009d90
`public: __thiscall CIlNt4User32::CIlNt4User32(class CIlNt4User32 &&)` | 28 (0x1c) | Exported Function | 0x10009f10 | 0x00009f10
`public: __thiscall CIlNt4Setupapi::CIlNt4Setupapi(void)` | 27 (0x1b) | Exported Function | 0x10009cf0 | 0x00009cf0
`public: __thiscall CIlNt4Setupapi::CIlNt4Setupapi(class CIlNt4Setupapi const &)` | 26 (0x1a) | Exported Function | 0x10009d10 | 0x00009d10
`public: __thiscall CIlNt4Setupapi::CIlNt4Setupapi(class CIlNt4Setupapi &&)` | 25 (0x19) | Exported Function | 0x10009d10 | 0x00009d10
`public: __thiscall CIlDeplorch::CIlDeplorch(class CIlDeplorch const &)` | 6 (0x6) | Exported Function | 0x10007300 | 0x00007300
`public: __thiscall CIlDeplorch::CIlDeplorch(void)` | 7 (0x7) | Exported Function | 0x100072f0 | 0x000072f0
`public: __thiscall CIlIphlpapi::CIlIphlpapi(class CIlIphlpapi &&)` | 8 (0x8) | Exported Function | 0x10007340 | 0x00007340
`public: __thiscall CIlIphlpapi::CIlIphlpapi(class CIlIphlpapi const &)` | 9 (0x9) | Exported Function | 0x10007340 | 0x00007340
`public: __thiscall CIlIphlpapi::CIlIphlpapi(void)` | 10 (0xa) | Exported Function | 0x10007330 | 0x00007330
`public: __thiscall CIlKernel32::CIlKernel32(class CIlKernel32 const &)` | 11 (0xb) | Exported Function | 0x10007dc0 | 0x00007dc0
`public: __thiscall CIlKernel32::CIlKernel32(void)` | 12 (0xc) | Exported Function | 0x10007350 | 0x00007350
`public: __thiscall CIlKernel32::~CIlKernel32(void)` | 64 (0x40) | Exported Function | 0x10007360 | 0x00007360
`public: __thiscall CIlMuisetupapi::CIlMuisetupapi(class CIlMuisetupapi &&)` | 13 (0xd) | Exported Function | 0x1000a940 | 0x0000a940
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiCallClassInstaller` | 616 (0x268) | Exported Function | 0x10019604 | 0x00019604
`public: __thiscall CIlMuisetupapi::CIlMuisetupapi(class CIlMuisetupapi const &)` | 14 (0xe) | Exported Function | 0x1000a940 | 0x0000a940
`public: __thiscall CIlNt4Advapi32::CIlNt4Advapi32(class CIlNt4Advapi32 &&)` | 16 (0x10) | Exported Function | 0x10007250 | 0x00007250
`public: __thiscall CIlNt4Advapi32::CIlNt4Advapi32(class CIlNt4Advapi32 const &)` | 17 (0x11) | Exported Function | 0x10007250 | 0x00007250
`public: __thiscall CIlNt4Advapi32::CIlNt4Advapi32(void)` | 18 (0x12) | Exported Function | 0x10007230 | 0x00007230
`public: __thiscall CIlNt4Kernel32::CIlNt4Kernel32(class CIlNt4Kernel32 &&)` | 19 (0x13) | Exported Function | 0x10008230 | 0x00008230
`public: __thiscall CIlNt4Kernel32::CIlNt4Kernel32(class CIlNt4Kernel32 const &)` | 20 (0x14) | Exported Function | 0x10008230 | 0x00008230
`public: __thiscall CIlNt4Kernel32::CIlNt4Kernel32(void)` | 21 (0x15) | Exported Function | 0x10008210 | 0x00008210
`public: __thiscall CIlNt4Netapi32::CIlNt4Netapi32(class CIlNt4Netapi32 &&)` | 22 (0x16) | Exported Function | 0x10008950 | 0x00008950
`public: __thiscall CIlNt4Netapi32::CIlNt4Netapi32(class CIlNt4Netapi32 const &)` | 23 (0x17) | Exported Function | 0x10008950 | 0x00008950
`public: __thiscall CIlNt4Netapi32::CIlNt4Netapi32(void)` | 24 (0x18) | Exported Function | 0x10008930 | 0x00008930
`public: __thiscall CIlMuisetupapi::CIlMuisetupapi(void)` | 15 (0xf) | Exported Function | 0x1000a930 | 0x0000a930
`struct IWs2_32Interface * g_Ws2_32` | 475 (0x1db) | Exported Function | 0x1001900c | 0x0001900c


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ISOLMIG.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/cbeaac6a5b95f5afc6c5327d98a5fefa20e35ec1f859a79066e5856c5b87bebb/detection/





MIT License. Copyright (c) 2020 Strontic.


