---
title: migisol.dll | Migration System Isolation Layer
excerpt: What is migisol.dll?
---

# migisol.dll 

* File Path: `C:\Windows\system32\migisol.dll`
* Description: Migration System Isolation Layer

## Hashes

Type | Hash
-- | --
MD5 | `124DB55B5B4ED9E86DC7F93F36E46FA8`
SHA1 | `F26737E081B5F25A09E2F1EBAFADACB54B3963B8`
SHA256 | `6D0A394840B5191CCF8B0F33DC584D2AC986D99EB72F339624BA7B5F335D2D6B`
SHA384 | `8C25A63F4C37D04CDFB6AF148EA47A54AF0C1960A210F4BE40AB5ED7DD0015174DB50E33B149FFD4D94ED2C008E0366D`
SHA512 | `4AD2F4AD8F591CCFCD184BCDFE3BEC6182DE1470E010281D12811DB42283B96C13F6AE98D7F2F07940D9BAAB9816031692BA5F6C758E38C57906B0191675F67D`
SSDEEP | `1536:ugh6fy8DKXL1suIbaNe4+ciQWwAQgm6QW01NHuMUXQ8t7e5VyX3bgp/UOI8f3gSq:Cy8DcLJvQPXQ+5OI8nbMvDnkm8Ns`
IMP | `5A80FF0726879EBF4BB765CA4DF99390`
PESHA1 | `C15B54A72FD2802A4E0926A9FD439276315B4B52`
PE256 | `CCC82E75B52F37F15EDD10D5F032419C207104A90267E1FD8331DF473C29C628`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`class CIlAdvapi32 IlAdvapi32` | 248 (0xf8) | Exported Function | 0x0000000180021230 | 0x00021230
`public: virtual int __cdecl CIlNt4Setupapi::SetupDiGetDriverInfoDetailW(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DRVINFO_DATA_V2_W * __ptr64,struct _SP_DRVINFO_DETAIL_DATA_W * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 410 (0x19a) | Exported Function | 0x0000000180006470 | 0x00006470
`public: virtual int __cdecl CIlNt4Setupapi::SetupDiOpenDeviceInfoW(void * __ptr64,unsigned short const * __ptr64,struct HWND__ * __ptr64,unsigned long,struct _SP_DEVINFO_DATA * __ptr64) __ptr64` | 412 (0x19c) | Exported Function | 0x0000000180005fc0 | 0x00005fc0
`public: virtual int __cdecl CIlNt4Setupapi::SetupDiSetDeviceInstallParamsW(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DEVINSTALL_PARAMS_W * __ptr64) __ptr64` | 413 (0x19d) | Exported Function | 0x0000000180006700 | 0x00006700
`public: virtual int __cdecl CIlNt4Setupapi::SetupDiSetSelectedDriverW(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DRVINFO_DATA_V2_W * __ptr64) __ptr64` | 414 (0x19e) | Exported Function | 0x0000000180006940 | 0x00006940
`public: virtual int __cdecl CIlNt4Setupapi::SetupGetInfInformationW(void const * __ptr64,unsigned long,struct _SP_INF_INFORMATION * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 417 (0x1a1) | Exported Function | 0x0000000180006f00 | 0x00006f00
`public: virtual int __cdecl CIlNt4Setupapi::SetupQueryInfOriginalFileInformationW(struct _SP_INF_INFORMATION * __ptr64,unsigned int,struct _SP_ALTPLATFORM_INFO_V2 * __ptr64,struct _SP_ORIGINAL_FILE_INFO_W * __ptr64) __ptr64` | 422 (0x1a6) | Exported Function | 0x0000000180007060 | 0x00007060
`public: virtual int __cdecl CIlNt4Setupapi::SetupScanFileQueueW(void * __ptr64,unsigned long,struct HWND__ * __ptr64,unsigned int (__cdecl*)(void * __ptr64,unsigned int,unsigned __int64,unsigned __int64),void * __ptr64,unsigned long * __ptr64) __ptr64` | 423 (0x1a7) | Exported Function | 0x0000000180006c80 | 0x00006c80
`public: virtual int __cdecl CIlNt4User32::LockSetForegroundWindow(unsigned int) __ptr64` | 338 (0x152) | Exported Function | 0x0000000180007a70 | 0x00007a70
`public: virtual int __cdecl CIlNt4Userenv::CreateUserProfileExW(void * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long,int) __ptr64` | 156 (0x9c) | Exported Function | 0x0000000180007bc0 | 0x00007bc0
`public: virtual int __cdecl CIlSetupapi::SetupFindFirstLineW(void * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,struct _INFCONTEXT * __ptr64) __ptr64` | 415 (0x19f) | Exported Function | 0x0000000180005a60 | 0x00005a60
`public: virtual int __cdecl CIlSetupapi::SetupFindNextLine(struct _INFCONTEXT * __ptr64,struct _INFCONTEXT * __ptr64) __ptr64` | 416 (0x1a0) | Exported Function | 0x0000000180005ad0 | 0x00005ad0
`public: virtual int __cdecl CIlSetupapi::SetupGetLineTextW(struct _INFCONTEXT * __ptr64,void * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 418 (0x1a2) | Exported Function | 0x0000000180005af0 | 0x00005af0
`public: virtual int __cdecl CIlSetupapi::SetupGetStringFieldW(struct _INFCONTEXT * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 419 (0x1a3) | Exported Function | 0x0000000180005a90 | 0x00005a90
`public: virtual int __cdecl CIlShell32::ShellExecuteExW(struct _SHELLEXECUTEINFOW * __ptr64) __ptr64` | 424 (0x1a8) | Exported Function | 0x0000000180007960 | 0x00007960
`public: virtual int __cdecl CIlUser32::MessageBoxA(struct HWND__ * __ptr64,char const * __ptr64,char const * __ptr64,unsigned int) __ptr64` | 343 (0x157) | Exported Function | 0x0000000180007a20 | 0x00007a20
`public: virtual int __cdecl CIlUser32::MessageBoxW(struct HWND__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned int) __ptr64` | 344 (0x158) | Exported Function | 0x00000001800079f0 | 0x000079f0
`public: virtual int __cdecl CIlUser32::PostMessageW(struct HWND__ * __ptr64,unsigned int,unsigned __int64,__int64) __ptr64` | 361 (0x169) | Exported Function | 0x00000001800079a0 | 0x000079a0
`public: virtual int __cdecl CIlVersion::GetFileVersionInfoW(unsigned short const * __ptr64,unsigned long,unsigned long,void * __ptr64) __ptr64` | 201 (0xc9) | Exported Function | 0x0000000180007f20 | 0x00007f20
`public: virtual int __cdecl CIlVersion::VerQueryValueW(void * __ptr64 const,unsigned short const * __ptr64,void * __ptr64 * __ptr64,unsigned int * __ptr64) __ptr64` | 432 (0x1b0) | Exported Function | 0x0000000180007f50 | 0x00007f50
`public: virtual int __cdecl CIlNt4Setupapi::SetupDiGetDeviceRegistryPropertyW(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long,unsigned long * __ptr64,unsigned char * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 409 (0x199) | Exported Function | 0x00000001800071b0 | 0x000071b0
`public: virtual int __cdecl CIlW2kDynWs2_32::getaddrinfo(char const * __ptr64,char const * __ptr64,struct addrinfo const * __ptr64,struct addrinfo * __ptr64 * __ptr64) __ptr64` | 537 (0x219) | Exported Function | 0x0000000180008720 | 0x00008720
`public: virtual int __cdecl CIlNt4Setupapi::SetupDiGetDeviceInterfaceDetailW(void * __ptr64,struct _SP_DEVICE_INTERFACE_DATA * __ptr64,struct _SP_DEVICE_INTERFACE_DETAIL_DATA_W * __ptr64,unsigned long,unsigned long * __ptr64,struct _SP_DEVINFO_DATA * __ptr64) __ptr64` | 408 (0x198) | Exported Function | 0x0000000180007770 | 0x00007770
`public: virtual int __cdecl CIlNt4Setupapi::SetupDiEnumDriverInfoW(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long,unsigned long,struct _SP_DRVINFO_DATA_V2_W * __ptr64) __ptr64` | 404 (0x194) | Exported Function | 0x0000000180007340 | 0x00007340
`public: virtual int __cdecl CIlNt4Advapi32::ConvertStringSidToSidW(unsigned short * __ptr64,void * __ptr64 * __ptr64) __ptr64` | 143 (0x8f) | Exported Function | 0x0000000180001ef0 | 0x00001ef0
`public: virtual int __cdecl CIlNt4Advapi32::CreateWellKnownSid(enum WELL_KNOWN_SID_TYPE,void * __ptr64,void * __ptr64,unsigned long * __ptr64) __ptr64` | 157 (0x9d) | Exported Function | 0x00000001800022b0 | 0x000022b0
`public: virtual int __cdecl CIlNt4Advapi32::EncryptFileW(unsigned short const * __ptr64) __ptr64` | 177 (0xb1) | Exported Function | 0x00000001800033a0 | 0x000033a0
`public: virtual int __cdecl CIlNt4Advapi32::EnumServicesStatusExW(struct SC_HANDLE__ * __ptr64,enum _SC_ENUM_TYPE,unsigned long,unsigned long,unsigned char * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned short const * __ptr64) __ptr64` | 179 (0xb3) | Exported Function | 0x0000000180002d00 | 0x00002d00
`public: virtual int __cdecl CIlNt4Advapi32::InitiateSystemShutdownExW(unsigned short * __ptr64,unsigned short * __ptr64,unsigned long,int,int,unsigned long) __ptr64` | 332 (0x14c) | Exported Function | 0x0000000180003230 | 0x00003230
`public: virtual int __cdecl CIlNt4Advapi32::QueryServiceConfigW(struct SC_HANDLE__ * __ptr64,struct _QUERY_SERVICE_CONFIGW * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 364 (0x16c) | Exported Function | 0x0000000180002630 | 0x00002630
`public: virtual int __cdecl CIlNt4Advapi32::StartServiceW(struct SC_HANDLE__ * __ptr64,unsigned long,unsigned short const * __ptr64 * __ptr64) __ptr64` | 426 (0x1aa) | Exported Function | 0x0000000180002be0 | 0x00002be0
`public: virtual int __cdecl CIlNt4Advapi32::UnlockServiceDatabase(void * __ptr64) __ptr64` | 429 (0x1ad) | Exported Function | 0x0000000180003010 | 0x00003010
`public: virtual int __cdecl CIlNt4Kernel32::GlobalMemoryStatusEx(struct _MEMORYSTATUSEX * __ptr64) __ptr64` | 237 (0xed) | Exported Function | 0x0000000180004af0 | 0x00004af0
`public: virtual int __cdecl CIlNt4Kernel32::Process32FirstW(void * __ptr64,struct tagPROCESSENTRY32W * __ptr64) __ptr64` | 362 (0x16a) | Exported Function | 0x0000000180004790 | 0x00004790
`public: virtual int __cdecl CIlNt4Kernel32::Process32NextW(void * __ptr64,struct tagPROCESSENTRY32W * __ptr64) __ptr64` | 363 (0x16b) | Exported Function | 0x00000001800048b0 | 0x000048b0
`public: virtual int __cdecl CIlNt4Kernel32::RegisterWaitForSingleObject(void * __ptr64 * __ptr64,void * __ptr64,void (__cdecl*)(void * __ptr64,unsigned char),void * __ptr64,unsigned long,unsigned long) __ptr64` | 381 (0x17d) | Exported Function | 0x0000000180004500 | 0x00004500
`public: virtual int __cdecl CIlNt4Setupapi::SetupCloseFileQueue(void * __ptr64) __ptr64` | 395 (0x18b) | Exported Function | 0x0000000180006df0 | 0x00006df0
`public: virtual int __cdecl CIlNt4Setupapi::SetupDiBuildDriverInfoList(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long) __ptr64` | 397 (0x18d) | Exported Function | 0x0000000180006350 | 0x00006350
`public: virtual int __cdecl CIlNt4Setupapi::SetupDiCallClassInstaller(unsigned int,void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64) __ptr64` | 398 (0x18e) | Exported Function | 0x0000000180006820 | 0x00006820
`public: virtual int __cdecl CIlNt4Setupapi::SetupDiDestroyDeviceInfoList(void * __ptr64) __ptr64` | 400 (0x190) | Exported Function | 0x0000000180006a60 | 0x00006a60
`public: virtual int __cdecl CIlNt4Setupapi::SetupDiDestroyDriverInfoList(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long) __ptr64` | 401 (0x191) | Exported Function | 0x0000000180006230 | 0x00006230
`public: virtual int __cdecl CIlNt4Setupapi::SetupDiEnumDeviceInfo(void * __ptr64,unsigned long,struct _SP_DEVINFO_DATA * __ptr64) __ptr64` | 402 (0x192) | Exported Function | 0x0000000180006110 | 0x00006110
`public: virtual int __cdecl CIlNt4Setupapi::SetupDiEnumDeviceInterfaces(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _GUID const * __ptr64,unsigned long,struct _SP_DEVICE_INTERFACE_DATA * __ptr64) __ptr64` | 403 (0x193) | Exported Function | 0x0000000180007610 | 0x00007610
`public: virtual int __cdecl CIlNt4Setupapi::SetupDiGetDeviceInstallParamsW(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DEVINSTALL_PARAMS_W * __ptr64) __ptr64` | 407 (0x197) | Exported Function | 0x00000001800065e0 | 0x000065e0
`public: virtual int __cdecl CIlNt4Advapi32::ConvertStringSecurityDescriptorToSecurityDescriptorW(unsigned short const * __ptr64,unsigned long,void * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 142 (0x8e) | Exported Function | 0x0000000180002160 | 0x00002160
`public: virtual int __cdecl CIlW2kDynWs2_32::getnameinfo(struct sockaddr const * __ptr64,int,char * __ptr64,unsigned long,char * __ptr64,unsigned long,int) __ptr64` | 540 (0x21c) | Exported Function | 0x0000000180008590 | 0x00008590
`public: virtual int __cdecl CIlWimgapi::WIMCloseHandle(void * __ptr64) __ptr64` | 436 (0x1b4) | Exported Function | 0x0000000180008090 | 0x00008090
`public: virtual long __cdecl CIlAdvapi32::RegCreateKeyExW(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES * __ptr64,struct HKEY__ * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 368 (0x170) | Exported Function | 0x00000001800010c0 | 0x000010c0
`public: virtual long __cdecl CIlAdvapi32::RegDeleteKeyW(struct HKEY__ * __ptr64,unsigned short const * __ptr64) __ptr64` | 369 (0x171) | Exported Function | 0x00000001800013a0 | 0x000013a0
`public: virtual long __cdecl CIlAdvapi32::RegDeleteValueW(struct HKEY__ * __ptr64,unsigned short const * __ptr64) __ptr64` | 370 (0x172) | Exported Function | 0x00000001800013c0 | 0x000013c0
`public: virtual long __cdecl CIlAdvapi32::RegEnumKeyExW(struct HKEY__ * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned short * __ptr64,unsigned long * __ptr64,struct _FILETIME * __ptr64) __ptr64` | 371 (0x173) | Exported Function | 0x0000000180001270 | 0x00001270
`public: virtual long __cdecl CIlAdvapi32::RegEnumValueW(struct HKEY__ * __ptr64,unsigned long,unsigned short * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 372 (0x174) | Exported Function | 0x0000000180001330 | 0x00001330
`public: virtual long __cdecl CIlAdvapi32::RegFlushKey(struct HKEY__ * __ptr64) __ptr64` | 373 (0x175) | Exported Function | 0x0000000180001400 | 0x00001400
`public: virtual long __cdecl CIlAdvapi32::RegLoadKeyW(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 374 (0x176) | Exported Function | 0x0000000180001080 | 0x00001080
`public: virtual long __cdecl CIlAdvapi32::RegOpenKeyExW(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,struct HKEY__ * __ptr64 * __ptr64) __ptr64` | 375 (0x177) | Exported Function | 0x0000000180001140 | 0x00001140
`public: virtual long __cdecl CIlAdvapi32::RegQueryInfoKeyW(struct HKEY__ * __ptr64,unsigned short * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,struct _FILETIME * __ptr64) __ptr64` | 376 (0x178) | Exported Function | 0x00000001800011d0 | 0x000011d0
`public: virtual long __cdecl CIlAdvapi32::RegQueryValueExW(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 377 (0x179) | Exported Function | 0x0000000180001180 | 0x00001180
`public: virtual long __cdecl CIlAdvapi32::RegSetKeySecurity(struct HKEY__ * __ptr64,unsigned long,void * __ptr64) __ptr64` | 378 (0x17a) | Exported Function | 0x0000000180001b70 | 0x00001b70
`public: virtual long __cdecl CIlAdvapi32::RegSetValueExW(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,unsigned char const * __ptr64,unsigned long) __ptr64` | 379 (0x17b) | Exported Function | 0x00000001800012e0 | 0x000012e0
`public: virtual long __cdecl CIlAdvapi32::RegUnLoadKeyW(struct HKEY__ * __ptr64,unsigned short const * __ptr64) __ptr64` | 380 (0x17c) | Exported Function | 0x00000001800010a0 | 0x000010a0
`public: virtual long __cdecl CIlNt6Userenv::CreateProfile(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long) __ptr64` | 151 (0x97) | Exported Function | 0x0000000180007d70 | 0x00007d70
`public: virtual long __cdecl CIlOle32::CoCreateInstance(struct _GUID const & __ptr64,struct IUnknown * __ptr64,unsigned long,struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 134 (0x86) | Exported Function | 0x0000000180005910 | 0x00005910
`public: virtual long __cdecl CIlOle32::CoInitialize(void * __ptr64) __ptr64` | 135 (0x87) | Exported Function | 0x00000001800058b0 | 0x000058b0
`public: virtual long __cdecl CIlOle32::CoInitializeEx(void * __ptr64,unsigned long) __ptr64` | 136 (0x88) | Exported Function | 0x00000001800058d0 | 0x000058d0
`public: virtual long __cdecl CIlOle32::CreateStreamOnHGlobal(void * __ptr64,int,struct IStream * __ptr64 * __ptr64) __ptr64` | 153 (0x99) | Exported Function | 0x00000001800059b0 | 0x000059b0
`public: virtual long __cdecl CIlOle32::GetHGlobalFromStream(struct IStream * __ptr64,void * __ptr64 * __ptr64) __ptr64` | 203 (0xcb) | Exported Function | 0x0000000180005990 | 0x00005990
`public: virtual long __cdecl CIlAdvapi32::RegCloseKey(struct HKEY__ * __ptr64) __ptr64` | 367 (0x16f) | Exported Function | 0x00000001800013e0 | 0x000013e0
`public: virtual int __cdecl CIlWimgapi::WIMApplyImage(void * __ptr64,unsigned short * __ptr64,unsigned long) __ptr64` | 435 (0x1b3) | Exported Function | 0x0000000180008070 | 0x00008070
`public: virtual int __cdecl CIlWs2_32::WSAStartup(unsigned short,struct WSAData * __ptr64) __ptr64` | 445 (0x1bd) | Exported Function | 0x00000001800080d0 | 0x000080d0
`public: virtual int __cdecl CIlWs2_32::WSAGetLastError(void) __ptr64` | 443 (0x1bb) | Exported Function | 0x0000000180008110 | 0x00008110
`public: virtual int __cdecl CIlWimgapi::WIMSetTemporaryPath(void * __ptr64,unsigned short * __ptr64) __ptr64` | 440 (0x1b8) | Exported Function | 0x0000000180007ff0 | 0x00007ff0
`public: virtual int __cdecl CIlWimgapi::WIMUnregisterMessageCallback(void * __ptr64,__int64 (__cdecl*)(void)) __ptr64` | 441 (0x1b9) | Exported Function | 0x0000000180008050 | 0x00008050
`public: virtual int __cdecl CIlWs2_32::__WSAFDIsSet(unsigned __int64,struct fd_set * __ptr64) __ptr64` | 449 (0x1c1) | Exported Function | 0x0000000180008550 | 0x00008550
`public: virtual int __cdecl CIlWs2_32::bind(unsigned __int64,struct sockaddr const * __ptr64,int) __ptr64` | 451 (0x1c3) | Exported Function | 0x00000001800082e0 | 0x000082e0
`public: virtual int __cdecl CIlWs2_32::closesocket(unsigned __int64) __ptr64` | 452 (0x1c4) | Exported Function | 0x0000000180008150 | 0x00008150
`public: virtual int __cdecl CIlWs2_32::connect(unsigned __int64,struct sockaddr const * __ptr64,int) __ptr64` | 453 (0x1c5) | Exported Function | 0x0000000180008450 | 0x00008450
`public: virtual int __cdecl CIlWs2_32::gethostname(char * __ptr64,int) __ptr64` | 539 (0x21b) | Exported Function | 0x00000001800081f0 | 0x000081f0
`public: virtual int __cdecl CIlWs2_32::getsockname(unsigned __int64,struct sockaddr * __ptr64,int * __ptr64) __ptr64` | 541 (0x21d) | Exported Function | 0x0000000180008360 | 0x00008360
`public: virtual int __cdecl CIlWs2_32::getsockopt(unsigned __int64,int,int,char * __ptr64,int * __ptr64) __ptr64` | 542 (0x21e) | Exported Function | 0x0000000180008230 | 0x00008230
`public: virtual int __cdecl CIlWs2_32::ioctlsocket(unsigned __int64,long,unsigned long * __ptr64) __ptr64` | 547 (0x223) | Exported Function | 0x0000000180008300 | 0x00008300
`public: virtual int __cdecl CIlWs2_32::listen(unsigned __int64,int) __ptr64` | 548 (0x224) | Exported Function | 0x0000000180008320 | 0x00008320
`public: virtual int __cdecl CIlWs2_32::recv(unsigned __int64,char * __ptr64,int,int) __ptr64` | 671 (0x29f) | Exported Function | 0x0000000180008380 | 0x00008380
`public: virtual int __cdecl CIlWs2_32::recvfrom(unsigned __int64,char * __ptr64,int,int,struct sockaddr * __ptr64,int * __ptr64) __ptr64` | 672 (0x2a0) | Exported Function | 0x00000001800083b0 | 0x000083b0
`public: virtual int __cdecl CIlWs2_32::select(int,struct fd_set * __ptr64,struct fd_set * __ptr64,struct fd_set * __ptr64,struct timeval const * __ptr64) __ptr64` | 734 (0x2de) | Exported Function | 0x0000000180008470 | 0x00008470
`public: virtual int __cdecl CIlWs2_32::send(unsigned __int64,char const * __ptr64,int,int) __ptr64` | 735 (0x2df) | Exported Function | 0x00000001800082b0 | 0x000082b0
`public: virtual int __cdecl CIlWs2_32::sendto(unsigned __int64,char const * __ptr64,int,int,struct sockaddr const * __ptr64,int) __ptr64` | 736 (0x2e0) | Exported Function | 0x0000000180008400 | 0x00008400
`public: virtual int __cdecl CIlWs2_32::setsockopt(unsigned __int64,int,int,char const * __ptr64,int) __ptr64` | 737 (0x2e1) | Exported Function | 0x0000000180008270 | 0x00008270
`public: virtual int __cdecl CIlWs2_32::shutdown(unsigned __int64,int) __ptr64` | 738 (0x2e2) | Exported Function | 0x0000000180008340 | 0x00008340
`public: virtual int __cdecl CIlWs2_32::WSACleanup(void) __ptr64` | 442 (0x1ba) | Exported Function | 0x00000001800080f0 | 0x000080f0
`public: virtual int __cdecl CIlWs2_32::WSAIoctl(unsigned __int64,unsigned long,void * __ptr64,unsigned long,void * __ptr64,unsigned long,unsigned long * __ptr64,struct _OVERLAPPED * __ptr64,void (__cdecl*)(unsigned long,unsigned long,struct _OVERLAPPED * __ptr64,unsigned long)) __ptr64` | 444 (0x1bc) | Exported Function | 0x00000001800084d0 | 0x000084d0
`public: virtual int __cdecl CIlNt4Advapi32::ConvertSidToStringSidW(void * __ptr64,unsigned short * __ptr64 * __ptr64) __ptr64` | 141 (0x8d) | Exported Function | 0x0000000180001dd0 | 0x00001dd0
`public: virtual int __cdecl CIlNt4Advapi32::ConvertSecurityDescriptorToStringSecurityDescriptorW(void * __ptr64,unsigned long,unsigned long,unsigned short * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 140 (0x8c) | Exported Function | 0x0000000180002010 | 0x00002010
`public: virtual int __cdecl CIlNt4Advapi32::CloseServiceHandle(struct SC_HANDLE__ * __ptr64) __ptr64` | 133 (0x85) | Exported Function | 0x0000000180003120 | 0x00003120
`public: virtual int __cdecl CIlAdvapi32::CryptDecrypt(unsigned __int64,unsigned __int64,int,unsigned long,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 160 (0xa0) | Exported Function | 0x0000000180001a20 | 0x00001a20
`public: virtual int __cdecl CIlAdvapi32::CryptDeriveKey(unsigned __int64,unsigned int,unsigned __int64,unsigned long,unsigned __int64 * __ptr64) __ptr64` | 161 (0xa1) | Exported Function | 0x0000000180001880 | 0x00001880
`public: virtual int __cdecl CIlAdvapi32::CryptDestroyHash(unsigned __int64) __ptr64` | 162 (0xa2) | Exported Function | 0x0000000180001a90 | 0x00001a90
`public: virtual int __cdecl CIlAdvapi32::CryptDestroyKey(unsigned __int64) __ptr64` | 163 (0xa3) | Exported Function | 0x0000000180001a70 | 0x00001a70
`public: virtual int __cdecl CIlAdvapi32::CryptDuplicateHash(unsigned __int64,unsigned long * __ptr64,unsigned long,unsigned __int64 * __ptr64) __ptr64` | 164 (0xa4) | Exported Function | 0x0000000180001820 | 0x00001820
`public: virtual int __cdecl CIlAdvapi32::CryptDuplicateKey(unsigned __int64,unsigned long * __ptr64,unsigned long,unsigned __int64 * __ptr64) __ptr64` | 165 (0xa5) | Exported Function | 0x00000001800018c0 | 0x000018c0
`public: virtual int __cdecl CIlAdvapi32::CryptEncrypt(unsigned __int64,unsigned __int64,int,unsigned long,unsigned char * __ptr64,unsigned long * __ptr64,unsigned long) __ptr64` | 166 (0xa6) | Exported Function | 0x00000001800019c0 | 0x000019c0
`public: virtual int __cdecl CIlAdvapi32::CryptGenRandom(unsigned __int64,unsigned long,unsigned char * __ptr64) __ptr64` | 167 (0xa7) | Exported Function | 0x00000001800018f0 | 0x000018f0
`public: virtual int __cdecl CIlAdvapi32::CryptGetHashParam(unsigned __int64,unsigned long,unsigned char * __ptr64,unsigned long * __ptr64,unsigned long) __ptr64` | 168 (0xa8) | Exported Function | 0x0000000180001910 | 0x00001910
`public: virtual int __cdecl CIlAdvapi32::CryptGetKeyParam(unsigned __int64,unsigned long,unsigned char * __ptr64,unsigned long * __ptr64,unsigned long) __ptr64` | 169 (0xa9) | Exported Function | 0x0000000180001950 | 0x00001950
`public: virtual int __cdecl CIlAdvapi32::CryptHashData(unsigned __int64,unsigned char const * __ptr64,unsigned long,unsigned long) __ptr64` | 170 (0xaa) | Exported Function | 0x0000000180001850 | 0x00001850
`public: virtual int __cdecl CIlAdvapi32::CryptReleaseContext(unsigned __int64,unsigned long) __ptr64` | 171 (0xab) | Exported Function | 0x0000000180001ab0 | 0x00001ab0
`public: virtual int __cdecl CIlAdvapi32::CryptSetKeyParam(unsigned __int64,unsigned long,unsigned char const * __ptr64,unsigned long) __ptr64` | 172 (0xac) | Exported Function | 0x0000000180001990 | 0x00001990
`public: virtual int __cdecl CIlAdvapi32::EqualSid(void * __ptr64,void * __ptr64) __ptr64` | 180 (0xb4) | Exported Function | 0x0000000180001640 | 0x00001640
`public: virtual int __cdecl CIlAdvapi32::GetSecurityDescriptorDacl(void * __ptr64,int * __ptr64,struct _ACL * __ptr64 * __ptr64,int * __ptr64) __ptr64` | 214 (0xd6) | Exported Function | 0x0000000180001b10 | 0x00001b10
`public: virtual int __cdecl CIlAdvapi32::GetSecurityDescriptorGroup(void * __ptr64,void * __ptr64 * __ptr64,int * __ptr64) __ptr64` | 215 (0xd7) | Exported Function | 0x0000000180001af0 | 0x00001af0
`public: virtual int __cdecl CIlAdvapi32::GetSecurityDescriptorOwner(void * __ptr64,void * __ptr64 * __ptr64,int * __ptr64) __ptr64` | 216 (0xd8) | Exported Function | 0x0000000180001ad0 | 0x00001ad0
`public: virtual int __cdecl CIlAdvapi32::GetSecurityDescriptorSacl(void * __ptr64,int * __ptr64,struct _ACL * __ptr64 * __ptr64,int * __ptr64) __ptr64` | 217 (0xd9) | Exported Function | 0x0000000180001b40 | 0x00001b40
`public: virtual int __cdecl CIlAdvapi32::GetTokenInformation(void * __ptr64,enum _TOKEN_INFORMATION_CLASS,void * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 225 (0xe1) | Exported Function | 0x0000000180001530 | 0x00001530
`public: virtual int __cdecl CIlAdvapi32::CryptCreateHash(unsigned __int64,unsigned int,unsigned __int64,unsigned long,unsigned __int64 * __ptr64) __ptr64` | 159 (0x9f) | Exported Function | 0x00000001800017e0 | 0x000017e0
`public: virtual int __cdecl CIlAdvapi32::GetUserNameW(unsigned short * __ptr64,unsigned long * __ptr64) __ptr64` | 228 (0xe4) | Exported Function | 0x0000000180001420 | 0x00001420
`public: virtual int __cdecl CIlAdvapi32::CryptAcquireContextW(unsigned __int64 * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long) __ptr64` | 158 (0x9e) | Exported Function | 0x00000001800017a0 | 0x000017a0
`public: virtual int __cdecl CIlAdvapi32::AdjustTokenPrivileges(void * __ptr64,int,struct _TOKEN_PRIVILEGES * __ptr64,unsigned long,struct _TOKEN_PRIVILEGES * __ptr64,unsigned long * __ptr64) __ptr64` | 129 (0x81) | Exported Function | 0x0000000180001750 | 0x00001750
`public: long (__cdecl*__cdecl CIlNt6Userenv::get_CreateProfile(void) __ptr64)(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long)` | 482 (0x1e2) | Exported Function | 0x0000000180007df0 | 0x00007df0
`public: struct HKEY__ * __ptr64 (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiOpenDevRegKey(void) __ptr64)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long,unsigned long,unsigned long,unsigned long)` | 524 (0x20c) | Exported Function | 0x0000000180007540 | 0x00007540
`public: struct SC_HANDLE__ * __ptr64 (__cdecl*__cdecl CIlNt4Advapi32::get_CreateServiceW(void) __ptr64)(struct SC_HANDLE__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,unsigned long,unsigned long,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 483 (0x1e3) | Exported Function | 0x0000000180002b10 | 0x00002b10
`public: struct SC_HANDLE__ * __ptr64 (__cdecl*__cdecl CIlNt4Advapi32::get_OpenSCManagerW(void) __ptr64)(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long)` | 503 (0x1f7) | Exported Function | 0x0000000180002440 | 0x00002440
`public: struct SC_HANDLE__ * __ptr64 (__cdecl*__cdecl CIlNt4Advapi32::get_OpenServiceW(void) __ptr64)(struct SC_HANDLE__ * __ptr64,unsigned short const * __ptr64,unsigned long)` | 504 (0x1f8) | Exported Function | 0x0000000180002560 | 0x00002560
`public: unsigned int (__cdecl*__cdecl CIlNt4Kernel32::get_GetSystemWindowsDirectoryW(void) __ptr64)(unsigned short * __ptr64,unsigned int)` | 489 (0x1e9) | Exported Function | 0x0000000180004a20 | 0x00004a20
`public: unsigned long (__cdecl*__cdecl CIlNt4Netapi32::get_NetApiBufferFree(void) __ptr64)(void * __ptr64)` | 494 (0x1ee) | Exported Function | 0x00000001800057a0 | 0x000057a0
`public: unsigned long (__cdecl*__cdecl CIlNt4Netapi32::get_NetLocalGroupAdd(void) __ptr64)(unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long * __ptr64)` | 495 (0x1ef) | Exported Function | 0x0000000180005500 | 0x00005500
`public: unsigned long (__cdecl*__cdecl CIlNt4Netapi32::get_NetLocalGroupAddMembers(void) __ptr64)(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long)` | 496 (0x1f0) | Exported Function | 0x00000001800053b0 | 0x000053b0
`public: unsigned long (__cdecl*__cdecl CIlNt4Netapi32::get_NetLocalGroupEnum(void) __ptr64)(unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64 * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64,unsigned __int64 * __ptr64)` | 497 (0x1f1) | Exported Function | 0x0000000180005690 | 0x00005690
`public: unsigned long (__cdecl*__cdecl CIlNt4Netapi32::get_NetUserAdd(void) __ptr64)(unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long * __ptr64)` | 498 (0x1f2) | Exported Function | 0x0000000180004de0 | 0x00004de0
`public: unsigned long (__cdecl*__cdecl CIlNt4Netapi32::get_NetUserDel(void) __ptr64)(unsigned short const * __ptr64,unsigned short const * __ptr64)` | 499 (0x1f3) | Exported Function | 0x0000000180004f00 | 0x00004f00
`public: unsigned long (__cdecl*__cdecl CIlNt4Netapi32::get_NetUserEnum(void) __ptr64)(unsigned short const * __ptr64,unsigned long,unsigned long,unsigned char * __ptr64 * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64)` | 500 (0x1f4) | Exported Function | 0x00000001800050b0 | 0x000050b0
`public: unsigned long (__cdecl*__cdecl CIlNt4Netapi32::get_NetUserGetLocalGroups(void) __ptr64)(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,unsigned char * __ptr64 * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64)` | 501 (0x1f5) | Exported Function | 0x0000000180005260 | 0x00005260
`public: unsigned long (__cdecl*__cdecl CIlNt4Netapi32::get_NetWkstaGetInfo(void) __ptr64)(unsigned short * __ptr64,unsigned long,unsigned char * __ptr64 * __ptr64)` | 502 (0x1f6) | Exported Function | 0x0000000180004c90 | 0x00004c90
`public: virtual __int64 (__cdecl*__cdecl CIlKernel32::GetProcAddress(struct HINSTANCE__ * __ptr64,char const * __ptr64) __ptr64)(void)` | 212 (0xd4) | Exported Function | 0x00000001800043c0 | 0x000043c0
`public: virtual char * __ptr64 __cdecl CIlWs2_32::inet_ntoa(struct in_addr) __ptr64` | 546 (0x222) | Exported Function | 0x0000000180008190 | 0x00008190
`public: virtual int (__cdecl*__cdecl CIlW2kDynWs2_32::get_getaddrinfo(void) __ptr64)(char const * __ptr64,char const * __ptr64,struct addrinfo const * __ptr64,struct addrinfo * __ptr64 * __ptr64)` | 535 (0x217) | Exported Function | 0x00000001800087a0 | 0x000087a0
`public: virtual int (__cdecl*__cdecl CIlW2kDynWs2_32::get_getnameinfo(void) __ptr64)(struct sockaddr const * __ptr64,int,char * __ptr64,unsigned long,char * __ptr64,unsigned long,int)` | 536 (0x218) | Exported Function | 0x0000000180008650 | 0x00008650
`public: virtual int __cdecl CIlAdvapi32::AllocateAndInitializeSid(struct _SID_IDENTIFIER_AUTHORITY * __ptr64,unsigned char,unsigned long,unsigned long,unsigned long,unsigned long,unsigned long,unsigned long,unsigned long,unsigned long,void * __ptr64 * __ptr64) __ptr64` | 130 (0x82) | Exported Function | 0x0000000180001570 | 0x00001570
`public: virtual int __cdecl CIlAdvapi32::InitializeSecurityDescriptor(void * __ptr64,unsigned long) __ptr64` | 331 (0x14b) | Exported Function | 0x0000000180001bb0 | 0x00001bb0
`public: virtual int __cdecl CIlAdvapi32::IsValidSid(void * __ptr64) __ptr64` | 333 (0x14d) | Exported Function | 0x0000000180001620 | 0x00001620
`public: virtual int __cdecl CIlAdvapi32::LookupAccountNameW(unsigned short const * __ptr64,unsigned short const * __ptr64,void * __ptr64,unsigned long * __ptr64,unsigned short * __ptr64,unsigned long * __ptr64,enum _SID_NAME_USE * __ptr64) __ptr64` | 339 (0x153) | Exported Function | 0x0000000180001450 | 0x00001450
`public: virtual int __cdecl CIlKernel32::GlobalUnlock(void * __ptr64) __ptr64` | 239 (0xef) | Exported Function | 0x0000000180003880 | 0x00003880
`public: virtual int __cdecl CIlKernel32::HeapDestroy(void * __ptr64) __ptr64` | 243 (0xf3) | Exported Function | 0x0000000180003750 | 0x00003750
`public: virtual int __cdecl CIlKernel32::HeapFree(void * __ptr64,unsigned long,void * __ptr64) __ptr64` | 244 (0xf4) | Exported Function | 0x00000001800037c0 | 0x000037c0
`public: virtual int __cdecl CIlKernel32::HeapValidate(void * __ptr64,unsigned long,void const * __ptr64) __ptr64` | 246 (0xf6) | Exported Function | 0x0000000180003800 | 0x00003800
`public: virtual int __cdecl CIlKernel32::HeapWalk(void * __ptr64,struct _PROCESS_HEAP_ENTRY * __ptr64) __ptr64` | 247 (0xf7) | Exported Function | 0x0000000180003820 | 0x00003820
`public: virtual int __cdecl CIlKernel32::MoveFileExW(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long) __ptr64` | 345 (0x159) | Exported Function | 0x0000000180003940 | 0x00003940
`public: virtual int __cdecl CIlKernel32::MoveFileW(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 346 (0x15a) | Exported Function | 0x0000000180003920 | 0x00003920
`public: virtual int __cdecl CIlKernel32::ReadFile(void * __ptr64,void * __ptr64,unsigned long,unsigned long * __ptr64,struct _OVERLAPPED * __ptr64) __ptr64` | 366 (0x16e) | Exported Function | 0x0000000180003a40 | 0x00003a40
`public: virtual int __cdecl CIlKernel32::RemoveDirectoryW(unsigned short const * __ptr64) __ptr64` | 383 (0x17f) | Exported Function | 0x0000000180003c90 | 0x00003c90
`public: virtual int __cdecl CIlKernel32::ResetEvent(void * __ptr64) __ptr64` | 384 (0x180) | Exported Function | 0x0000000180004070 | 0x00004070
`public: virtual int __cdecl CIlKernel32::SetEndOfFile(void * __ptr64) __ptr64` | 385 (0x181) | Exported Function | 0x0000000180003f50 | 0x00003f50
`public: virtual int __cdecl CIlKernel32::SetEvent(void * __ptr64) __ptr64` | 387 (0x183) | Exported Function | 0x0000000180004050 | 0x00004050
`public: virtual int __cdecl CIlKernel32::SetFileAttributesW(unsigned short const * __ptr64,unsigned long) __ptr64` | 388 (0x184) | Exported Function | 0x0000000180003bd0 | 0x00003bd0
`public: virtual int __cdecl CIlKernel32::SetFileTime(void * __ptr64,struct _FILETIME const * __ptr64,struct _FILETIME const * __ptr64,struct _FILETIME const * __ptr64) __ptr64` | 390 (0x186) | Exported Function | 0x0000000180003f20 | 0x00003f20
`public: virtual int __cdecl CIlKernel32::TerminateProcess(void * __ptr64,unsigned int) __ptr64` | 428 (0x1ac) | Exported Function | 0x0000000180003e70 | 0x00003e70
`public: virtual int __cdecl CIlKernel32::UnmapViewOfFile(void const * __ptr64) __ptr64` | 430 (0x1ae) | Exported Function | 0x00000001800042e0 | 0x000042e0
`public: virtual int __cdecl CIlKernel32::VirtualFree(void * __ptr64,unsigned __int64,unsigned long) __ptr64` | 434 (0x1b2) | Exported Function | 0x00000001800044e0 | 0x000044e0
`public: virtual int __cdecl CIlKernel32::WriteFile(void * __ptr64,void const * __ptr64,unsigned long,unsigned long * __ptr64,struct _OVERLAPPED * __ptr64) __ptr64` | 448 (0x1c0) | Exported Function | 0x0000000180003a80 | 0x00003a80
`public: virtual int __cdecl CIlNt4Advapi32::ChangeServiceConfigW(struct SC_HANDLE__ * __ptr64,unsigned long,unsigned long,unsigned long,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 131 (0x83) | Exported Function | 0x0000000180002780 | 0x00002780
`public: virtual int __cdecl CIlKernel32::GetVolumeInformationW(unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned short * __ptr64,unsigned long) __ptr64` | 231 (0xe7) | Exported Function | 0x0000000180003eb0 | 0x00003eb0
`public: virtual int __cdecl CIlKernel32::GetVersionExW(struct _OSVERSIONINFOW * __ptr64) __ptr64` | 230 (0xe6) | Exported Function | 0x0000000180003690 | 0x00003690
`public: virtual int __cdecl CIlKernel32::GetVersionExA(struct _OSVERSIONINFOA * __ptr64) __ptr64` | 229 (0xe5) | Exported Function | 0x0000000180003670 | 0x00003670
`public: virtual int __cdecl CIlKernel32::GetOverlappedResult(void * __ptr64,struct _OVERLAPPED * __ptr64,unsigned long * __ptr64,int) __ptr64` | 210 (0xd2) | Exported Function | 0x0000000180004150 | 0x00004150
`public: virtual int __cdecl CIlAdvapi32::LookupAccountSidW(unsigned short const * __ptr64,void * __ptr64,unsigned short * __ptr64,unsigned long * __ptr64,unsigned short * __ptr64,unsigned long * __ptr64,enum _SID_NAME_USE * __ptr64) __ptr64` | 340 (0x154) | Exported Function | 0x00000001800014b0 | 0x000014b0
`public: virtual int __cdecl CIlAdvapi32::LookupPrivilegeValueW(unsigned short const * __ptr64,unsigned short const * __ptr64,struct _LUID * __ptr64) __ptr64` | 341 (0x155) | Exported Function | 0x0000000180001730 | 0x00001730
`public: virtual int __cdecl CIlAdvapi32::OpenProcessToken(void * __ptr64,unsigned long,void * __ptr64 * __ptr64) __ptr64` | 358 (0x166) | Exported Function | 0x0000000180001510 | 0x00001510
`public: virtual int __cdecl CIlAdvapi32::SetSecurityDescriptorOwner(void * __ptr64,void * __ptr64,int) __ptr64` | 393 (0x189) | Exported Function | 0x0000000180001b90 | 0x00001b90
`public: virtual int __cdecl CIlDeplorch::SysprepIsStagedOS(void) __ptr64` | 427 (0x1ab) | Exported Function | 0x0000000180003520 | 0x00003520
`public: virtual int __cdecl CIlKernel32::CloseHandle(void * __ptr64) __ptr64` | 132 (0x84) | Exported Function | 0x00000001800039c0 | 0x000039c0
`public: virtual int __cdecl CIlKernel32::CopyFileW(unsigned short const * __ptr64,unsigned short const * __ptr64,int) __ptr64` | 144 (0x90) | Exported Function | 0x00000001800038e0 | 0x000038e0
`public: virtual int __cdecl CIlKernel32::CreateDirectoryW(unsigned short const * __ptr64,struct _SECURITY_ATTRIBUTES * __ptr64) __ptr64` | 145 (0x91) | Exported Function | 0x0000000180003b90 | 0x00003b90
`public: virtual int __cdecl CIlKernel32::CreateProcessA(char const * __ptr64,char * __ptr64,struct _SECURITY_ATTRIBUTES * __ptr64,struct _SECURITY_ATTRIBUTES * __ptr64,int,unsigned long,void * __ptr64,char const * __ptr64,struct _STARTUPINFOA * __ptr64,struct _PROCESS_INFORMATION * __ptr64) __ptr64` | 149 (0x95) | Exported Function | 0x0000000180003db0 | 0x00003db0
`public: virtual long __cdecl CIlOleaut32::VariantClear(struct tagVARIANT * __ptr64) __ptr64` | 431 (0x1af) | Exported Function | 0x00000001800059f0 | 0x000059f0
`public: virtual int __cdecl CIlKernel32::CreateProcessW(unsigned short const * __ptr64,unsigned short * __ptr64,struct _SECURITY_ATTRIBUTES * __ptr64,struct _SECURITY_ATTRIBUTES * __ptr64,int,unsigned long,void * __ptr64,unsigned short const * __ptr64,struct _STARTUPINFOW * __ptr64,struct _PROCESS_INFORMATION * __ptr64) __ptr64` | 150 (0x96) | Exported Function | 0x0000000180003d30 | 0x00003d30
`public: virtual int __cdecl CIlKernel32::DuplicateHandle(void * __ptr64,void * __ptr64,void * __ptr64,void * __ptr64 * __ptr64,unsigned long,int,unsigned long) __ptr64` | 176 (0xb0) | Exported Function | 0x0000000180003af0 | 0x00003af0
`public: virtual int __cdecl CIlKernel32::FindClose(void * __ptr64) __ptr64` | 184 (0xb8) | Exported Function | 0x0000000180003d10 | 0x00003d10
`public: virtual int __cdecl CIlKernel32::FindNextFileW(void * __ptr64,struct _WIN32_FIND_DATAW * __ptr64) __ptr64` | 186 (0xba) | Exported Function | 0x0000000180003cf0 | 0x00003cf0
`public: virtual int __cdecl CIlKernel32::FreeLibrary(struct HINSTANCE__ * __ptr64) __ptr64` | 187 (0xbb) | Exported Function | 0x00000001800043e0 | 0x000043e0
`public: virtual int __cdecl CIlKernel32::GetComputerNameW(unsigned short * __ptr64,unsigned long * __ptr64) __ptr64` | 190 (0xbe) | Exported Function | 0x00000001800040b0 | 0x000040b0
`public: virtual int __cdecl CIlKernel32::GetDiskFreeSpaceExW(unsigned short const * __ptr64,union _ULARGE_INTEGER * __ptr64,union _ULARGE_INTEGER * __ptr64,union _ULARGE_INTEGER * __ptr64) __ptr64` | 193 (0xc1) | Exported Function | 0x0000000180004220 | 0x00004220
`public: virtual int __cdecl CIlKernel32::GetDiskFreeSpaceW(unsigned short const * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 194 (0xc2) | Exported Function | 0x00000001800041e0 | 0x000041e0
`public: virtual int __cdecl CIlKernel32::GetExitCodeProcess(void * __ptr64,unsigned long * __ptr64) __ptr64` | 196 (0xc4) | Exported Function | 0x0000000180004440 | 0x00004440
`public: virtual int __cdecl CIlKernel32::GetLocaleInfoW(unsigned long,unsigned long,unsigned short * __ptr64,int) __ptr64` | 207 (0xcf) | Exported Function | 0x0000000180004480 | 0x00004480
`public: virtual int __cdecl CIlKernel32::DeleteFileW(unsigned short const * __ptr64) __ptr64` | 175 (0xaf) | Exported Function | 0x0000000180003b50 | 0x00003b50
`public: int (__cdecl*__cdecl CIlNt4Userenv::get_CreateUserProfileExW(void) __ptr64)(void * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long,int)` | 485 (0x1e5) | Exported Function | 0x0000000180007c60 | 0x00007c60
`public: virtual struct HICON__ * __ptr64 __cdecl CIlUser32::LoadIconW(struct HINSTANCE__ * __ptr64,unsigned short const * __ptr64) __ptr64` | 335 (0x14f) | Exported Function | 0x00000001800079d0 | 0x000079d0
`public: virtual struct HKEY__ * __ptr64 __cdecl CIlNt4Setupapi::SetupDiOpenDevRegKey(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long,unsigned long,unsigned long,unsigned long) __ptr64` | 411 (0x19b) | Exported Function | 0x00000001800074a0 | 0x000074a0
`public: void __cdecl CIlNt4Advapi32::release_OpenSCManagerW(void) __ptr64` | 700 (0x2bc) | Exported Function | 0x0000000180002490 | 0x00002490
`public: void __cdecl CIlNt4Advapi32::release_OpenServiceW(void) __ptr64` | 701 (0x2bd) | Exported Function | 0x00000001800025b0 | 0x000025b0
`public: void __cdecl CIlNt4Advapi32::release_QueryServiceConfigW(void) __ptr64` | 704 (0x2c0) | Exported Function | 0x0000000180002700 | 0x00002700
`public: void __cdecl CIlNt4Advapi32::release_StartServiceW(void) __ptr64` | 729 (0x2d9) | Exported Function | 0x0000000180002c80 | 0x00002c80
`public: void __cdecl CIlNt4Advapi32::release_UnlockServiceDatabase(void) __ptr64` | 730 (0x2da) | Exported Function | 0x00000001800030a0 | 0x000030a0
`public: void __cdecl CIlNt4Kernel32::release_CreateToolhelp32Snapshot(void) __ptr64` | 681 (0x2a9) | Exported Function | 0x0000000180004710 | 0x00004710
`public: void __cdecl CIlNt4Kernel32::release_GetSystemWindowsDirectoryW(void) __ptr64` | 686 (0x2ae) | Exported Function | 0x0000000180004a70 | 0x00004a70
`public: void __cdecl CIlNt4Kernel32::release_GlobalMemoryStatusEx(void) __ptr64` | 687 (0x2af) | Exported Function | 0x0000000180004b80 | 0x00004b80
`public: void __cdecl CIlNt4Kernel32::release_Process32FirstW(void) __ptr64` | 702 (0x2be) | Exported Function | 0x0000000180004830 | 0x00004830
`public: void __cdecl CIlNt4Kernel32::release_Process32NextW(void) __ptr64` | 703 (0x2bf) | Exported Function | 0x0000000180004950 | 0x00004950
`public: void __cdecl CIlNt4Kernel32::release_RegisterWaitForSingleObject(void) __ptr64` | 705 (0x2c1) | Exported Function | 0x00000001800045f0 | 0x000045f0
`public: void __cdecl CIlNt4Netapi32::release_NetApiBufferFree(void) __ptr64` | 691 (0x2b3) | Exported Function | 0x00000001800057f0 | 0x000057f0
`public: void __cdecl CIlNt4Netapi32::release_NetLocalGroupAdd(void) __ptr64` | 692 (0x2b4) | Exported Function | 0x0000000180005550 | 0x00005550
`public: void __cdecl CIlNt4Netapi32::release_NetLocalGroupAddMembers(void) __ptr64` | 693 (0x2b5) | Exported Function | 0x0000000180005400 | 0x00005400
`public: void __cdecl CIlNt4Netapi32::release_NetLocalGroupEnum(void) __ptr64` | 694 (0x2b6) | Exported Function | 0x00000001800056e0 | 0x000056e0
`public: void __cdecl CIlNt4Netapi32::release_NetUserAdd(void) __ptr64` | 695 (0x2b7) | Exported Function | 0x0000000180004e30 | 0x00004e30
`public: void __cdecl CIlNt4Netapi32::release_NetUserDel(void) __ptr64` | 696 (0x2b8) | Exported Function | 0x0000000180004f50 | 0x00004f50
`public: void __cdecl CIlNt4Netapi32::release_NetUserEnum(void) __ptr64` | 697 (0x2b9) | Exported Function | 0x0000000180005100 | 0x00005100
`public: void __cdecl CIlNt4Netapi32::release_NetUserGetLocalGroups(void) __ptr64` | 698 (0x2ba) | Exported Function | 0x00000001800052b0 | 0x000052b0
`public: void __cdecl CIlNt4Advapi32::release_LockServiceDatabase(void) __ptr64` | 689 (0x2b1) | Exported Function | 0x0000000180002f90 | 0x00002f90
`public: void __cdecl CIlNt4Netapi32::release_NetWkstaGetInfo(void) __ptr64` | 699 (0x2bb) | Exported Function | 0x0000000180004ce0 | 0x00004ce0
`public: void __cdecl CIlNt4Advapi32::release_InitiateSystemShutdownExW(void) __ptr64` | 688 (0x2b0) | Exported Function | 0x0000000180003320 | 0x00003320
`public: void __cdecl CIlNt4Advapi32::release_EncryptFileW(void) __ptr64` | 684 (0x2ac) | Exported Function | 0x0000000180003440 | 0x00003440
`public: virtual void __cdecl CIlSetupapi::SetupCloseInfFile(void * __ptr64) __ptr64` | 396 (0x18c) | Exported Function | 0x0000000180005b50 | 0x00005b50
`public: virtual void __cdecl CIlW2kDynWs2_32::freeaddrinfo(struct addrinfo * __ptr64) __ptr64` | 454 (0x1c6) | Exported Function | 0x0000000180008870 | 0x00008870
`public: virtual void __cdecl CIlW2kDynWs2_32::release_freeaddrinfo(void) __ptr64` | 731 (0x2db) | Exported Function | 0x0000000180008900 | 0x00008900
`public: virtual void __cdecl CIlW2kDynWs2_32::release_getaddrinfo(void) __ptr64` | 732 (0x2dc) | Exported Function | 0x00000001800087f0 | 0x000087f0
`public: virtual void __cdecl CIlW2kDynWs2_32::release_getnameinfo(void) __ptr64` | 733 (0x2dd) | Exported Function | 0x00000001800086a0 | 0x000086a0
`public: void * __ptr64 (__cdecl*__cdecl CIlNt4Advapi32::get_LockServiceDatabase(void) __ptr64)(struct SC_HANDLE__ * __ptr64)` | 492 (0x1ec) | Exported Function | 0x0000000180002f40 | 0x00002f40
`public: void * __ptr64 (__cdecl*__cdecl CIlNt4Kernel32::get_CreateToolhelp32Snapshot(void) __ptr64)(unsigned long,unsigned long)` | 484 (0x1e4) | Exported Function | 0x00000001800046c0 | 0x000046c0
`public: void * __ptr64 (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiCreateDeviceInfoListExW(void) __ptr64)(struct _GUID const * __ptr64,struct HWND__ * __ptr64,unsigned short const * __ptr64,void * __ptr64)` | 512 (0x200) | Exported Function | 0x0000000180005c10 | 0x00005c10
`public: void * __ptr64 (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiGetClassDevsExW(void) __ptr64)(struct _GUID const * __ptr64,unsigned short const * __ptr64,struct HWND__ * __ptr64,unsigned long,void * __ptr64,unsigned short const * __ptr64,void * __ptr64)` | 518 (0x206) | Exported Function | 0x0000000180005da0 | 0x00005da0
`public: void * __ptr64 (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiGetClassDevsW(void) __ptr64)(struct _GUID const * __ptr64,unsigned short const * __ptr64,struct HWND__ * __ptr64,unsigned long)` | 519 (0x207) | Exported Function | 0x0000000180005ef0 | 0x00005ef0
`public: void * __ptr64 (__cdecl*__cdecl CIlNt4Setupapi::get_SetupOpenFileQueue(void) __ptr64)(void)` | 529 (0x211) | Exported Function | 0x0000000180006bb0 | 0x00006bb0
`public: void __cdecl CIlNt4Advapi32::release_ChangeServiceConfigW(void) __ptr64` | 673 (0x2a1) | Exported Function | 0x0000000180002920 | 0x00002920
`public: void __cdecl CIlNt4Advapi32::release_CloseServiceHandle(void) __ptr64` | 674 (0x2a2) | Exported Function | 0x00000001800031b0 | 0x000031b0
`public: void __cdecl CIlNt4Advapi32::release_ConvertSecurityDescriptorToStringSecurityDescriptorW(void) __ptr64` | 675 (0x2a3) | Exported Function | 0x00000001800020e0 | 0x000020e0
`public: void __cdecl CIlNt4Advapi32::release_ConvertSidToStringSidW(void) __ptr64` | 676 (0x2a4) | Exported Function | 0x0000000180001e70 | 0x00001e70
`public: void __cdecl CIlNt4Advapi32::release_ConvertStringSecurityDescriptorToSecurityDescriptorW(void) __ptr64` | 677 (0x2a5) | Exported Function | 0x0000000180002230 | 0x00002230
`public: void __cdecl CIlNt4Advapi32::release_ConvertStringSidToSidW(void) __ptr64` | 678 (0x2a6) | Exported Function | 0x0000000180001f90 | 0x00001f90
`public: void __cdecl CIlNt4Advapi32::release_CreateServiceW(void) __ptr64` | 680 (0x2a8) | Exported Function | 0x0000000180002b60 | 0x00002b60
`public: void __cdecl CIlNt4Advapi32::release_CreateWellKnownSid(void) __ptr64` | 683 (0x2ab) | Exported Function | 0x0000000180002370 | 0x00002370
`public: void __cdecl CIlNt4Advapi32::release_EnumServicesStatusExW(void) __ptr64` | 685 (0x2ad) | Exported Function | 0x0000000180002e80 | 0x00002e80
`public: virtual void __cdecl CIlOle32::CoUninitialize(void) __ptr64` | 139 (0x8b) | Exported Function | 0x00000001800058f0 | 0x000058f0
`public: void __cdecl CIlNt4Setupapi::release_SetupCloseFileQueue(void) __ptr64` | 706 (0x2c2) | Exported Function | 0x0000000180006e80 | 0x00006e80
`public: void __cdecl CIlNt4Setupapi::release_SetupDiCallClassInstaller(void) __ptr64` | 708 (0x2c4) | Exported Function | 0x00000001800068c0 | 0x000068c0
`struct IAdvapi32Interface * __ptr64 __ptr64 g_Advapi32` | 455 (0x1c7) | Exported Function | 0x0000000180021030 | 0x00021030
`struct IDeplorchInterface * __ptr64 __ptr64 g_Deplorch` | 456 (0x1c8) | Exported Function | 0x0000000180021060 | 0x00021060
`struct IIphlpapiInterface * __ptr64 __ptr64 g_Iphlpapi` | 457 (0x1c9) | Exported Function | 0x0000000180021018 | 0x00021018
`struct IKernel32Interface * __ptr64 __ptr64 g_Kernel32` | 458 (0x1ca) | Exported Function | 0x0000000180021058 | 0x00021058
`struct IlW2kDynWs2_32Interface * __ptr64 __ptr64 g_W2kWs2_32` | 473 (0x1d9) | Exported Function | 0x0000000180021098 | 0x00021098
`struct IMuisetupapiInterface * __ptr64 __ptr64 g_Muisetupapi` | 459 (0x1cb) | Exported Function | 0x00000001800210a8 | 0x000210a8
`struct INt6UserenvInterface * __ptr64 __ptr64 g_Nt6Userenv` | 466 (0x1d2) | Exported Function | 0x0000000180021010 | 0x00021010
`struct IOle32Interface * __ptr64 __ptr64 g_Ole32` | 467 (0x1d3) | Exported Function | 0x0000000180021038 | 0x00021038
`struct IOleaut32Interface * __ptr64 __ptr64 g_Oleaut32` | 468 (0x1d4) | Exported Function | 0x0000000180021040 | 0x00021040
`struct ISetupapiInterface * __ptr64 __ptr64 g_Setupapi` | 469 (0x1d5) | Exported Function | 0x0000000180021028 | 0x00021028
`struct IShell32Interface * __ptr64 __ptr64 g_Shell32` | 470 (0x1d6) | Exported Function | 0x0000000180021070 | 0x00021070
`struct IUser32Interface * __ptr64 __ptr64 g_User32` | 471 (0x1d7) | Exported Function | 0x0000000180021068 | 0x00021068
`struct IVersionInterface * __ptr64 __ptr64 g_Version` | 472 (0x1d8) | Exported Function | 0x0000000180021080 | 0x00021080
`struct IW2kAdvapi32Interface * __ptr64 __ptr64 g_Nt4Advapi32` | 460 (0x1cc) | Exported Function | 0x0000000180021078 | 0x00021078
`struct IW2kKernel32Interface * __ptr64 __ptr64 g_Nt4Kernel32` | 461 (0x1cd) | Exported Function | 0x0000000180021090 | 0x00021090
`struct IW2kNetapi32Interface * __ptr64 __ptr64 g_Nt4Netapi32` | 462 (0x1ce) | Exported Function | 0x0000000180021048 | 0x00021048
`struct IW2kSetupapiInterface * __ptr64 __ptr64 g_Nt4Setupapi` | 463 (0x1cf) | Exported Function | 0x00000001800210a0 | 0x000210a0
`struct IW2kUser32Interface * __ptr64 __ptr64 g_Nt4User32` | 464 (0x1d0) | Exported Function | 0x0000000180021050 | 0x00021050
`struct IW2kUserenvInterface * __ptr64 __ptr64 g_Nt4Userenv` | 465 (0x1d1) | Exported Function | 0x0000000180021008 | 0x00021008
`public: void __cdecl CIlNt6Userenv::release_CreateProfile(void) __ptr64` | 679 (0x2a7) | Exported Function | 0x0000000180007e40 | 0x00007e40
`public: void __cdecl CIlNt4Setupapi::release_SetupDiBuildDriverInfoList(void) __ptr64` | 707 (0x2c3) | Exported Function | 0x00000001800063f0 | 0x000063f0
`public: void __cdecl CIlNt4Userenv::release_CreateUserProfileExW(void) __ptr64` | 682 (0x2aa) | Exported Function | 0x0000000180007cb0 | 0x00007cb0
`public: void __cdecl CIlNt4Setupapi::release_SetupScanFileQueueW(void) __ptr64` | 728 (0x2d8) | Exported Function | 0x0000000180006d70 | 0x00006d70
`public: void __cdecl CIlNt4Setupapi::release_SetupDiCreateDeviceInfoListExW(void) __ptr64` | 709 (0x2c5) | Exported Function | 0x0000000180005c60 | 0x00005c60
`public: void __cdecl CIlNt4Setupapi::release_SetupDiDestroyDeviceInfoList(void) __ptr64` | 710 (0x2c6) | Exported Function | 0x0000000180006af0 | 0x00006af0
`public: void __cdecl CIlNt4Setupapi::release_SetupDiDestroyDriverInfoList(void) __ptr64` | 711 (0x2c7) | Exported Function | 0x00000001800062d0 | 0x000062d0
`public: void __cdecl CIlNt4Setupapi::release_SetupDiEnumDeviceInfo(void) __ptr64` | 712 (0x2c8) | Exported Function | 0x00000001800061b0 | 0x000061b0
`public: void __cdecl CIlNt4Setupapi::release_SetupDiEnumDeviceInterfaces(void) __ptr64` | 713 (0x2c9) | Exported Function | 0x00000001800076f0 | 0x000076f0
`public: void __cdecl CIlNt4Setupapi::release_SetupDiEnumDriverInfoW(void) __ptr64` | 714 (0x2ca) | Exported Function | 0x0000000180007420 | 0x00007420
`public: void __cdecl CIlNt4Setupapi::release_SetupDiGetClassDevsExW(void) __ptr64` | 715 (0x2cb) | Exported Function | 0x0000000180005df0 | 0x00005df0
`public: void __cdecl CIlNt4Setupapi::release_SetupDiGetClassDevsW(void) __ptr64` | 716 (0x2cc) | Exported Function | 0x0000000180005f40 | 0x00005f40
`public: void __cdecl CIlNt4Setupapi::release_SetupDiGetDeviceInstallParamsW(void) __ptr64` | 717 (0x2cd) | Exported Function | 0x0000000180006680 | 0x00006680
`public: void __cdecl CIlNt4Setupapi::release_SetupDiGetDeviceInterfaceDetailW(void) __ptr64` | 718 (0x2ce) | Exported Function | 0x0000000180007860 | 0x00007860
`public: void __cdecl CIlNt4Setupapi::release_SetupDiGetDeviceRegistryPropertyW(void) __ptr64` | 719 (0x2cf) | Exported Function | 0x00000001800072c0 | 0x000072c0
`public: void __cdecl CIlNt4Setupapi::release_SetupDiGetDriverInfoDetailW(void) __ptr64` | 720 (0x2d0) | Exported Function | 0x0000000180006560 | 0x00006560
`public: void __cdecl CIlNt4Setupapi::release_SetupDiOpenDeviceInfoW(void) __ptr64` | 722 (0x2d2) | Exported Function | 0x0000000180006090 | 0x00006090
`public: void __cdecl CIlNt4Setupapi::release_SetupDiOpenDevRegKey(void) __ptr64` | 721 (0x2d1) | Exported Function | 0x0000000180007590 | 0x00007590
`public: void __cdecl CIlNt4Setupapi::release_SetupDiSetDeviceInstallParamsW(void) __ptr64` | 723 (0x2d3) | Exported Function | 0x00000001800067a0 | 0x000067a0
`public: void __cdecl CIlNt4Setupapi::release_SetupDiSetSelectedDriverW(void) __ptr64` | 724 (0x2d4) | Exported Function | 0x00000001800069e0 | 0x000069e0
`public: void __cdecl CIlNt4Setupapi::release_SetupGetInfInformationW(void) __ptr64` | 725 (0x2d5) | Exported Function | 0x0000000180006fe0 | 0x00006fe0
`public: void __cdecl CIlNt4Setupapi::release_SetupOpenFileQueue(void) __ptr64` | 726 (0x2d6) | Exported Function | 0x0000000180006c00 | 0x00006c00
`public: void __cdecl CIlNt4Setupapi::release_SetupQueryInfOriginalFileInformationW(void) __ptr64` | 727 (0x2d7) | Exported Function | 0x0000000180007130 | 0x00007130
`public: void __cdecl CIlNt4User32::release_LockSetForegroundWindow(void) __ptr64` | 690 (0x2b2) | Exported Function | 0x0000000180007b00 | 0x00007b00
`public: virtual void __cdecl CIlOle32::CoTaskMemFree(void * __ptr64) __ptr64` | 138 (0x8a) | Exported Function | 0x0000000180005970 | 0x00005970
`public: virtual void __cdecl CIlKernel32::Sleep(unsigned long) __ptr64` | 425 (0x1a9) | Exported Function | 0x0000000180004090 | 0x00004090
`public: virtual void __cdecl CIlKernel32::SetLastError(unsigned long) __ptr64` | 391 (0x187) | Exported Function | 0x0000000180003650 | 0x00003650
`public: virtual unsigned long __cdecl CIlKernel32::GetFullPathNameW(unsigned short const * __ptr64,unsigned long,unsigned short * __ptr64,unsigned short * __ptr64 * __ptr64) __ptr64` | 202 (0xca) | Exported Function | 0x0000000180003c40 | 0x00003c40
`public: virtual unsigned long __cdecl CIlKernel32::GetLastError(void) __ptr64` | 206 (0xce) | Exported Function | 0x0000000180003630 | 0x00003630
`public: virtual unsigned long __cdecl CIlKernel32::GetLogicalDrives(void) __ptr64` | 209 (0xd1) | Exported Function | 0x0000000180003a00 | 0x00003a00
`public: virtual unsigned long __cdecl CIlKernel32::GetLogicalDriveStringsW(unsigned long,unsigned short * __ptr64) __ptr64` | 208 (0xd0) | Exported Function | 0x00000001800039e0 | 0x000039e0
`public: virtual unsigned long __cdecl CIlKernel32::GetPrivateProfileStringW(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long,unsigned short const * __ptr64) __ptr64` | 211 (0xd3) | Exported Function | 0x0000000180004350 | 0x00004350
`public: virtual unsigned long __cdecl CIlKernel32::GetShortPathNameW(unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long) __ptr64` | 219 (0xdb) | Exported Function | 0x0000000180003c70 | 0x00003c70
`public: virtual unsigned long __cdecl CIlKernel32::GetTempPathW(unsigned long,unsigned short * __ptr64) __ptr64` | 223 (0xdf) | Exported Function | 0x0000000180003bf0 | 0x00003bf0
`public: virtual unsigned long __cdecl CIlKernel32::GetTickCount(void) __ptr64` | 224 (0xe0) | Exported Function | 0x0000000180003cb0 | 0x00003cb0
`public: virtual unsigned long __cdecl CIlKernel32::SetFilePointer(void * __ptr64,long,long * __ptr64,unsigned long) __ptr64` | 389 (0x185) | Exported Function | 0x0000000180003ac0 | 0x00003ac0
`public: virtual unsigned long __cdecl CIlKernel32::WaitForMultipleObjects(unsigned long,void * __ptr64 const * __ptr64,int,unsigned long) __ptr64` | 446 (0x1be) | Exported Function | 0x0000000180004010 | 0x00004010
`public: virtual unsigned long __cdecl CIlKernel32::WaitForSingleObject(void * __ptr64,unsigned long) __ptr64` | 447 (0x1bf) | Exported Function | 0x0000000180003e90 | 0x00003e90
`public: virtual unsigned long __cdecl CIlMuisetupapi::GetUpgradeLanguage(unsigned short * __ptr64,unsigned int,unsigned int) __ptr64` | 226 (0xe2) | Exported Function | 0x00000001800089c0 | 0x000089c0
`public: virtual unsigned long __cdecl CIlMuisetupapi::GetUpgradeLanguageEx(unsigned short * __ptr64,unsigned int,unsigned int,unsigned short const * __ptr64) __ptr64` | 227 (0xe3) | Exported Function | 0x00000001800089f0 | 0x000089f0
`public: virtual unsigned long __cdecl CIlNt4Netapi32::NetApiBufferFree(void * __ptr64) __ptr64` | 347 (0x15b) | Exported Function | 0x0000000180005760 | 0x00005760
`public: virtual unsigned long __cdecl CIlNt4Netapi32::NetLocalGroupAdd(unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 348 (0x15c) | Exported Function | 0x0000000180005480 | 0x00005480
`public: virtual unsigned long __cdecl CIlNt4Netapi32::NetLocalGroupAddMembers(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long) __ptr64` | 349 (0x15d) | Exported Function | 0x0000000180005330 | 0x00005330
`public: virtual unsigned long __cdecl CIlNt4Netapi32::NetLocalGroupEnum(unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64 * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 350 (0x15e) | Exported Function | 0x00000001800055d0 | 0x000055d0
`public: virtual unsigned long __cdecl CIlNt4Netapi32::NetUserAdd(unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long * __ptr64) __ptr64` | 351 (0x15f) | Exported Function | 0x0000000180004d60 | 0x00004d60
`public: virtual unsigned long __cdecl CIlNt4Netapi32::NetUserDel(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 352 (0x160) | Exported Function | 0x0000000180004eb0 | 0x00004eb0
`public: virtual unsigned long __cdecl CIlKernel32::GetFileType(void * __ptr64) __ptr64` | 199 (0xc7) | Exported Function | 0x0000000180004180 | 0x00004180
`public: virtual unsigned long __cdecl CIlNt4Netapi32::NetUserEnum(unsigned short const * __ptr64,unsigned long,unsigned long,unsigned char * __ptr64 * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 353 (0x161) | Exported Function | 0x0000000180004fd0 | 0x00004fd0
`public: virtual unsigned long __cdecl CIlKernel32::GetFileSize(void * __ptr64,unsigned long * __ptr64) __ptr64` | 198 (0xc6) | Exported Function | 0x00000001800041a0 | 0x000041a0
`public: virtual unsigned long __cdecl CIlKernel32::GetCurrentThreadId(void) __ptr64` | 192 (0xc0) | Exported Function | 0x0000000180004330 | 0x00004330
`public: virtual struct hostent * __ptr64 __cdecl CIlWs2_32::gethostbyname(char const * __ptr64) __ptr64` | 538 (0x21a) | Exported Function | 0x0000000180008210 | 0x00008210
`public: virtual struct SC_HANDLE__ * __ptr64 __cdecl CIlNt4Advapi32::CreateServiceW(struct SC_HANDLE__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,unsigned long,unsigned long,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 152 (0x98) | Exported Function | 0x00000001800029a0 | 0x000029a0
`public: virtual struct SC_HANDLE__ * __ptr64 __cdecl CIlNt4Advapi32::OpenSCManagerW(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long) __ptr64` | 359 (0x167) | Exported Function | 0x00000001800023f0 | 0x000023f0
`public: virtual struct SC_HANDLE__ * __ptr64 __cdecl CIlNt4Advapi32::OpenServiceW(struct SC_HANDLE__ * __ptr64,unsigned short const * __ptr64,unsigned long) __ptr64` | 360 (0x168) | Exported Function | 0x0000000180002510 | 0x00002510
`public: virtual unsigned __int64 __cdecl CIlKernel32::GlobalSize(void * __ptr64) __ptr64` | 238 (0xee) | Exported Function | 0x00000001800038c0 | 0x000038c0
`public: virtual unsigned __int64 __cdecl CIlKernel32::HeapCompact(void * __ptr64,unsigned long) __ptr64` | 241 (0xf1) | Exported Function | 0x00000001800037e0 | 0x000037e0
`public: virtual unsigned __int64 __cdecl CIlWs2_32::accept(unsigned __int64,struct sockaddr * __ptr64,int * __ptr64) __ptr64` | 450 (0x1c2) | Exported Function | 0x00000001800084b0 | 0x000084b0
`public: virtual unsigned __int64 __cdecl CIlWs2_32::socket(int,int,int) __ptr64` | 739 (0x2e3) | Exported Function | 0x0000000180008130 | 0x00008130
`public: virtual unsigned int __cdecl CIlKernel32::GetDriveTypeW(unsigned short const * __ptr64) __ptr64` | 195 (0xc3) | Exported Function | 0x0000000180003a20 | 0x00003a20
`public: virtual unsigned int __cdecl CIlKernel32::GetTempFileNameW(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned int,unsigned short * __ptr64) __ptr64` | 222 (0xde) | Exported Function | 0x0000000180003c10 | 0x00003c10
`public: virtual unsigned int __cdecl CIlKernel32::GetWindowsDirectoryW(unsigned short * __ptr64,unsigned int) __ptr64` | 232 (0xe8) | Exported Function | 0x0000000180003b70 | 0x00003b70
`public: virtual unsigned int __cdecl CIlKernel32::SetErrorMode(unsigned int) __ptr64` | 386 (0x182) | Exported Function | 0x00000001800041c0 | 0x000041c0
`public: virtual unsigned int __cdecl CIlNt4Kernel32::GetSystemWindowsDirectoryW(unsigned short * __ptr64,unsigned int) __ptr64` | 221 (0xdd) | Exported Function | 0x00000001800049d0 | 0x000049d0
`public: virtual unsigned int __cdecl CIlShell32::ExtractIconExW(unsigned short const * __ptr64,int,struct HICON__ * __ptr64 * __ptr64,struct HICON__ * __ptr64 * __ptr64,unsigned int) __ptr64` | 183 (0xb7) | Exported Function | 0x0000000180007920 | 0x00007920
`public: virtual unsigned long __cdecl CIlAdvapi32::GetSecurityInfo(void * __ptr64,enum _SE_OBJECT_TYPE,unsigned long,void * __ptr64 * __ptr64,void * __ptr64 * __ptr64,struct _ACL * __ptr64 * __ptr64,struct _ACL * __ptr64 * __ptr64,void * __ptr64 * __ptr64) __ptr64` | 218 (0xda) | Exported Function | 0x0000000180001660 | 0x00001660
`public: virtual unsigned long __cdecl CIlAdvapi32::SetNamedSecurityInfoW(unsigned short * __ptr64,enum _SE_OBJECT_TYPE,unsigned long,void * __ptr64,void * __ptr64,struct _ACL * __ptr64,struct _ACL * __ptr64) __ptr64` | 392 (0x188) | Exported Function | 0x0000000180001bd0 | 0x00001bd0
`public: virtual unsigned long __cdecl CIlAdvapi32::SetSecurityInfo(void * __ptr64,enum _SE_OBJECT_TYPE,unsigned long,void * __ptr64,void * __ptr64,struct _ACL * __ptr64,struct _ACL * __ptr64) __ptr64` | 394 (0x18a) | Exported Function | 0x00000001800016d0 | 0x000016d0
`public: virtual unsigned long __cdecl CIlIphlpapi::GetIpAddrTable(struct _MIB_IPADDRTABLE * __ptr64,unsigned long * __ptr64,int) __ptr64` | 205 (0xcd) | Exported Function | 0x00000001800035b0 | 0x000035b0
`public: virtual unsigned long __cdecl CIlKernel32::ExpandEnvironmentStringsW(unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long) __ptr64` | 182 (0xb6) | Exported Function | 0x0000000180004460 | 0x00004460
`public: virtual unsigned long __cdecl CIlKernel32::GetFileAttributesW(unsigned short const * __ptr64) __ptr64` | 197 (0xc5) | Exported Function | 0x0000000180003bb0 | 0x00003bb0
`public: virtual unsigned long __cdecl CIlNt4Netapi32::NetUserGetLocalGroups(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,unsigned char * __ptr64 * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64) __ptr64` | 354 (0x162) | Exported Function | 0x0000000180005180 | 0x00005180
`public: virtual unsigned long __cdecl CIlNt4Netapi32::NetWkstaGetInfo(unsigned short * __ptr64,unsigned long,unsigned char * __ptr64 * __ptr64) __ptr64` | 355 (0x163) | Exported Function | 0x0000000180004c40 | 0x00004c40
`public: virtual unsigned long __cdecl CIlVersion::GetFileVersionInfoSizeW(unsigned short const * __ptr64,unsigned long * __ptr64) __ptr64` | 200 (0xc8) | Exported Function | 0x0000000180007f00 | 0x00007f00
`public: virtual void * __ptr64 __cdecl CIlNt4Advapi32::LockServiceDatabase(struct SC_HANDLE__ * __ptr64) __ptr64` | 337 (0x151) | Exported Function | 0x0000000180002f00 | 0x00002f00
`public: virtual void * __ptr64 __cdecl CIlNt4Kernel32::CreateToolhelp32Snapshot(unsigned long,unsigned long) __ptr64` | 155 (0x9b) | Exported Function | 0x0000000180004670 | 0x00004670
`public: virtual void * __ptr64 __cdecl CIlNt4Setupapi::SetupDiCreateDeviceInfoListExW(struct _GUID const * __ptr64,struct HWND__ * __ptr64,unsigned short const * __ptr64,void * __ptr64) __ptr64` | 399 (0x18f) | Exported Function | 0x0000000180005b90 | 0x00005b90
`public: virtual void * __ptr64 __cdecl CIlNt4Setupapi::SetupDiGetClassDevsExW(struct _GUID const * __ptr64,unsigned short const * __ptr64,struct HWND__ * __ptr64,unsigned long,void * __ptr64,unsigned short const * __ptr64,void * __ptr64) __ptr64` | 405 (0x195) | Exported Function | 0x0000000180005ce0 | 0x00005ce0
`public: virtual void * __ptr64 __cdecl CIlNt4Setupapi::SetupDiGetClassDevsW(struct _GUID const * __ptr64,unsigned short const * __ptr64,struct HWND__ * __ptr64,unsigned long) __ptr64` | 406 (0x196) | Exported Function | 0x0000000180005e70 | 0x00005e70
`public: virtual void * __ptr64 __cdecl CIlNt4Setupapi::SetupOpenFileQueue(void) __ptr64` | 420 (0x1a4) | Exported Function | 0x0000000180006b70 | 0x00006b70
`public: virtual void * __ptr64 __cdecl CIlOle32::CoTaskMemAlloc(unsigned __int64) __ptr64` | 137 (0x89) | Exported Function | 0x0000000180005950 | 0x00005950
`public: virtual void * __ptr64 __cdecl CIlSetupapi::SetupOpenInfFileW(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned int * __ptr64) __ptr64` | 421 (0x1a5) | Exported Function | 0x0000000180005a30 | 0x00005a30
`public: virtual void * __ptr64 __cdecl CIlWimgapi::WIMCreateFile(unsigned short * __ptr64,unsigned long,unsigned long,unsigned long,unsigned long,unsigned long * __ptr64) __ptr64` | 437 (0x1b5) | Exported Function | 0x0000000180007fa0 | 0x00007fa0
`public: virtual void * __ptr64 __cdecl CIlWimgapi::WIMLoadImage(void * __ptr64,unsigned long) __ptr64` | 438 (0x1b6) | Exported Function | 0x0000000180008010 | 0x00008010
`public: virtual void __cdecl CIlKernel32::DebugBreak(void) __ptr64` | 173 (0xad) | Exported Function | 0x0000000180004420 | 0x00004420
`public: virtual void __cdecl CIlKernel32::DeleteCriticalSection(struct _RTL_CRITICAL_SECTION * __ptr64) __ptr64` | 174 (0xae) | Exported Function | 0x0000000180004130 | 0x00004130
`public: virtual void __cdecl CIlKernel32::EnterCriticalSection(struct _RTL_CRITICAL_SECTION * __ptr64) __ptr64` | 178 (0xb2) | Exported Function | 0x00000001800040f0 | 0x000040f0
`public: virtual void __cdecl CIlKernel32::ExitProcess(unsigned int) __ptr64` | 181 (0xb5) | Exported Function | 0x0000000180003e50 | 0x00003e50
`public: virtual void __cdecl CIlKernel32::GetSystemInfo(struct _SYSTEM_INFO * __ptr64) __ptr64` | 220 (0xdc) | Exported Function | 0x00000001800036b0 | 0x000036b0
`public: virtual void __cdecl CIlKernel32::GlobalMemoryStatus(struct _MEMORYSTATUS * __ptr64) __ptr64` | 236 (0xec) | Exported Function | 0x00000001800036d0 | 0x000036d0
`public: virtual void __cdecl CIlKernel32::InitializeCriticalSection(struct _RTL_CRITICAL_SECTION * __ptr64) __ptr64` | 330 (0x14a) | Exported Function | 0x00000001800040d0 | 0x000040d0
`public: virtual void __cdecl CIlKernel32::LeaveCriticalSection(struct _RTL_CRITICAL_SECTION * __ptr64) __ptr64` | 334 (0x14e) | Exported Function | 0x0000000180004110 | 0x00004110
`public: virtual void __cdecl CIlKernel32::RaiseException(unsigned long,unsigned long,unsigned long,unsigned __int64 const * __ptr64) __ptr64` | 365 (0x16d) | Exported Function | 0x0000000180004300 | 0x00004300
`public: virtual void * __ptr64 __cdecl CIlKernel32::VirtualAlloc(void * __ptr64,unsigned __int64,unsigned long,unsigned long) __ptr64` | 433 (0x1b1) | Exported Function | 0x00000001800044b0 | 0x000044b0
`public: virtual void * __ptr64 __cdecl CIlKernel32::OpenProcess(unsigned long,int,unsigned long) __ptr64` | 357 (0x165) | Exported Function | 0x0000000180003e30 | 0x00003e30
`public: virtual void * __ptr64 __cdecl CIlKernel32::OpenEventW(unsigned long,int,unsigned short const * __ptr64) __ptr64` | 356 (0x164) | Exported Function | 0x0000000180003ff0 | 0x00003ff0
`public: virtual void * __ptr64 __cdecl CIlKernel32::MapViewOfFile(void * __ptr64,unsigned long,unsigned long,unsigned long,unsigned __int64) __ptr64` | 342 (0x156) | Exported Function | 0x00000001800042a0 | 0x000042a0
`public: virtual unsigned long __cdecl CIlWimgapi::WIMRegisterMessageCallback(void * __ptr64,__int64 (__cdecl*)(void),void * __ptr64) __ptr64` | 439 (0x1b7) | Exported Function | 0x0000000180008030 | 0x00008030
`public: virtual unsigned long __cdecl CIlWs2_32::htonl(unsigned long) __ptr64` | 543 (0x21f) | Exported Function | 0x00000001800081b0 | 0x000081b0
`public: virtual unsigned long __cdecl CIlWs2_32::inet_addr(char const * __ptr64) __ptr64` | 545 (0x221) | Exported Function | 0x0000000180008170 | 0x00008170
`public: virtual unsigned short * __ptr64 __cdecl CIlKernel32::GetCommandLineW(void) __ptr64` | 189 (0xbd) | Exported Function | 0x00000001800043a0 | 0x000043a0
`public: virtual unsigned short __cdecl CIlWs2_32::htons(unsigned short) __ptr64` | 544 (0x220) | Exported Function | 0x00000001800081d0 | 0x000081d0
`public: virtual void (__cdecl*__cdecl CIlW2kDynWs2_32::get_freeaddrinfo(void) __ptr64)(struct addrinfo * __ptr64)` | 534 (0x216) | Exported Function | 0x00000001800088b0 | 0x000088b0
`public: virtual void * __ptr64 __cdecl CIlAdvapi32::FreeSid(void * __ptr64) __ptr64` | 188 (0xbc) | Exported Function | 0x0000000180001600 | 0x00001600
`public: virtual void * __ptr64 __cdecl CIlKernel32::CreateEventW(struct _SECURITY_ATTRIBUTES * __ptr64,int,int,unsigned short const * __ptr64) __ptr64` | 146 (0x92) | Exported Function | 0x0000000180003fc0 | 0x00003fc0
`public: virtual void * __ptr64 __cdecl CIlKernel32::CreateFileMappingW(void * __ptr64,struct _SECURITY_ATTRIBUTES * __ptr64,unsigned long,unsigned long,unsigned long,unsigned short const * __ptr64) __ptr64` | 147 (0x93) | Exported Function | 0x0000000180004250 | 0x00004250
`public: virtual struct HINSTANCE__ * __ptr64 __cdecl CIlKernel32::LoadLibraryW(unsigned short const * __ptr64) __ptr64` | 336 (0x150) | Exported Function | 0x0000000180004400 | 0x00004400
`public: virtual void * __ptr64 __cdecl CIlKernel32::CreateFileW(unsigned short const * __ptr64,unsigned long,unsigned long,struct _SECURITY_ATTRIBUTES * __ptr64,unsigned long,unsigned long,void * __ptr64) __ptr64` | 148 (0x94) | Exported Function | 0x0000000180003960 | 0x00003960
`public: virtual void * __ptr64 __cdecl CIlKernel32::FindFirstFileW(unsigned short const * __ptr64,struct _WIN32_FIND_DATAW * __ptr64) __ptr64` | 185 (0xb9) | Exported Function | 0x0000000180003cd0 | 0x00003cd0
`public: virtual void * __ptr64 __cdecl CIlKernel32::GetCurrentProcess(void) __ptr64` | 191 (0xbf) | Exported Function | 0x00000001800036f0 | 0x000036f0
`public: virtual void * __ptr64 __cdecl CIlKernel32::GetProcessHeap(void) __ptr64` | 213 (0xd5) | Exported Function | 0x0000000180003710 | 0x00003710
`public: virtual void * __ptr64 __cdecl CIlKernel32::GlobalAlloc(unsigned int,unsigned __int64) __ptr64` | 233 (0xe9) | Exported Function | 0x0000000180003840 | 0x00003840
`public: virtual void * __ptr64 __cdecl CIlKernel32::GlobalFree(void * __ptr64) __ptr64` | 234 (0xea) | Exported Function | 0x00000001800038a0 | 0x000038a0
`public: virtual void * __ptr64 __cdecl CIlKernel32::GlobalLock(void * __ptr64) __ptr64` | 235 (0xeb) | Exported Function | 0x0000000180003860 | 0x00003860
`public: virtual void * __ptr64 __cdecl CIlKernel32::HeapAlloc(void * __ptr64,unsigned long,unsigned __int64) __ptr64` | 240 (0xf0) | Exported Function | 0x0000000180003770 | 0x00003770
`public: virtual void * __ptr64 __cdecl CIlKernel32::HeapCreate(unsigned long,unsigned __int64,unsigned __int64) __ptr64` | 242 (0xf2) | Exported Function | 0x0000000180003730 | 0x00003730
`public: virtual void * __ptr64 __cdecl CIlKernel32::HeapReAlloc(void * __ptr64,unsigned long,void * __ptr64,unsigned __int64) __ptr64` | 245 (0xf5) | Exported Function | 0x0000000180003790 | 0x00003790
`public: virtual void * __ptr64 __cdecl CIlKernel32::CreateThread(struct _SECURITY_ATTRIBUTES * __ptr64,unsigned __int64,unsigned long (__cdecl*)(void * __ptr64),void * __ptr64,unsigned long,unsigned long * __ptr64) __ptr64` | 154 (0x9a) | Exported Function | 0x0000000180003f70 | 0x00003f70
`struct IWimgapiInterface * __ptr64 __ptr64 g_Wimgapi` | 474 (0x1da) | Exported Function | 0x0000000180021088 | 0x00021088
`public: int (__cdecl*__cdecl CIlNt4User32::get_LockSetForegroundWindow(void) __ptr64)(unsigned int)` | 493 (0x1ed) | Exported Function | 0x0000000180007ab0 | 0x00007ab0
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupQueryInfOriginalFileInformationW(void) __ptr64)(struct _SP_INF_INFORMATION * __ptr64,unsigned int,struct _SP_ALTPLATFORM_INFO_V2 * __ptr64,struct _SP_ORIGINAL_FILE_INFO_W * __ptr64)` | 530 (0x212) | Exported Function | 0x00000001800070e0 | 0x000070e0
`private: static int __cdecl CIlNt4Userenv::IlCreateUserProfileExW(void * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long,int)` | 258 (0x102) | Exported Function | 0x0000000180007c10 | 0x00007c10
`private: static int __cdecl CIlW2kDynWs2_32::Ilgetaddrinfo(char const * __ptr64,char const * __ptr64,struct addrinfo const * __ptr64,struct addrinfo * __ptr64 * __ptr64)` | 328 (0x148) | Exported Function | 0x0000000180008760 | 0x00008760
`private: static int __cdecl CIlW2kDynWs2_32::Ilgetnameinfo(struct sockaddr const * __ptr64,int,char * __ptr64,unsigned long,char * __ptr64,unsigned long,int)` | 329 (0x149) | Exported Function | 0x00000001800085f0 | 0x000085f0
`private: static long (__cdecl* __ptr64 CIlNt6Userenv::m_CreateProfile)(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long)` | 555 (0x22b) | Exported Function | 0x0000000180021ba8 | 0x00021ba8
`private: static long __cdecl CIlNt6Userenv::IlCreateProfile(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long)` | 255 (0xff) | Exported Function | 0x0000000180007db0 | 0x00007db0
`private: static struct HKEY__ * __ptr64 (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiOpenDevRegKey)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long,unsigned long,unsigned long,unsigned long)` | 658 (0x292) | Exported Function | 0x0000000180021928 | 0x00021928
`private: static struct HKEY__ * __ptr64 __cdecl CIlNt4Setupapi::IlSetupDiOpenDevRegKey(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long,unsigned long,unsigned long,unsigned long)` | 310 (0x136) | Exported Function | 0x00000001800074f0 | 0x000074f0
`private: static struct SC_HANDLE__ * __ptr64 (__cdecl* __ptr64 CIlNt4Advapi32::m_CreateServiceW)(struct SC_HANDLE__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,unsigned long,unsigned long,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 556 (0x22c) | Exported Function | 0x0000000180021bc8 | 0x00021bc8
`private: static struct SC_HANDLE__ * __ptr64 (__cdecl* __ptr64 CIlNt4Advapi32::m_OpenSCManagerW)(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long)` | 576 (0x240) | Exported Function | 0x0000000180021b50 | 0x00021b50
`private: static struct SC_HANDLE__ * __ptr64 (__cdecl* __ptr64 CIlNt4Advapi32::m_OpenServiceW)(struct SC_HANDLE__ * __ptr64,unsigned short const * __ptr64,unsigned long)` | 577 (0x241) | Exported Function | 0x0000000180021930 | 0x00021930
`private: static struct SC_HANDLE__ * __ptr64 __cdecl CIlNt4Advapi32::IlCreateServiceW(struct SC_HANDLE__ * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,unsigned long,unsigned long,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 256 (0x100) | Exported Function | 0x0000000180002a50 | 0x00002a50
`private: static struct SC_HANDLE__ * __ptr64 __cdecl CIlNt4Advapi32::IlOpenSCManagerW(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long)` | 289 (0x121) | Exported Function | 0x0000000180002410 | 0x00002410
`private: static struct SC_HANDLE__ * __ptr64 __cdecl CIlNt4Advapi32::IlOpenServiceW(struct SC_HANDLE__ * __ptr64,unsigned short const * __ptr64,unsigned long)` | 290 (0x122) | Exported Function | 0x0000000180002530 | 0x00002530
`private: static unsigned int (__cdecl* __ptr64 CIlNt4Kernel32::m_GetSystemWindowsDirectoryW)(unsigned short * __ptr64,unsigned int)` | 562 (0x232) | Exported Function | 0x0000000180021a68 | 0x00021a68
`private: static unsigned int __cdecl CIlNt4Kernel32::IlGetSystemWindowsDirectoryW(unsigned short * __ptr64,unsigned int)` | 263 (0x107) | Exported Function | 0x00000001800049f0 | 0x000049f0
`private: static unsigned long (__cdecl* __ptr64 CIlNt4Netapi32::m_NetApiBufferFree)(void * __ptr64)` | 567 (0x237) | Exported Function | 0x0000000180021b40 | 0x00021b40
`private: static unsigned long (__cdecl* __ptr64 CIlNt4Netapi32::m_NetLocalGroupAdd)(unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long * __ptr64)` | 568 (0x238) | Exported Function | 0x0000000180021b68 | 0x00021b68
`private: static unsigned long (__cdecl* __ptr64 CIlNt4Netapi32::m_NetLocalGroupAddMembers)(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long)` | 569 (0x239) | Exported Function | 0x0000000180021b70 | 0x00021b70
`private: static unsigned long (__cdecl* __ptr64 CIlNt4Netapi32::m_NetLocalGroupEnum)(unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64 * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64,unsigned __int64 * __ptr64)` | 570 (0x23a) | Exported Function | 0x0000000180021950 | 0x00021950
`private: static int __cdecl CIlNt4User32::IlLockSetForegroundWindow(unsigned int)` | 269 (0x10d) | Exported Function | 0x0000000180007a90 | 0x00007a90
`private: static unsigned long (__cdecl* __ptr64 CIlNt4Netapi32::m_NetUserAdd)(unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long * __ptr64)` | 571 (0x23b) | Exported Function | 0x0000000180021940 | 0x00021940
`private: static int __cdecl CIlNt4Setupapi::IlSetupScanFileQueueW(void * __ptr64,unsigned long,struct HWND__ * __ptr64,unsigned int (__cdecl*)(void * __ptr64,unsigned int,unsigned __int64,unsigned __int64),void * __ptr64,unsigned long * __ptr64)` | 317 (0x13d) | Exported Function | 0x0000000180006cd0 | 0x00006cd0
`private: static int __cdecl CIlNt4Setupapi::IlSetupGetInfInformationW(void const * __ptr64,unsigned long,struct _SP_INF_INFORMATION * __ptr64,unsigned long,unsigned long * __ptr64)` | 314 (0x13a) | Exported Function | 0x0000000180006f40 | 0x00006f40
`private: static int __cdecl CIlNt4Kernel32::IlGlobalMemoryStatusEx(struct _MEMORYSTATUSEX * __ptr64)` | 264 (0x108) | Exported Function | 0x0000000180004b10 | 0x00004b10
`private: static int __cdecl CIlNt4Kernel32::IlProcess32FirstW(void * __ptr64,struct tagPROCESSENTRY32W * __ptr64)` | 291 (0x123) | Exported Function | 0x00000001800047b0 | 0x000047b0
`private: static int __cdecl CIlNt4Kernel32::IlProcess32NextW(void * __ptr64,struct tagPROCESSENTRY32W * __ptr64)` | 292 (0x124) | Exported Function | 0x00000001800048d0 | 0x000048d0
`private: static int __cdecl CIlNt4Kernel32::IlRegisterWaitForSingleObject(void * __ptr64 * __ptr64,void * __ptr64,void (__cdecl*)(void * __ptr64,unsigned char),void * __ptr64,unsigned long,unsigned long)` | 294 (0x126) | Exported Function | 0x0000000180004550 | 0x00004550
`private: static int __cdecl CIlNt4Setupapi::IlSetupCloseFileQueue(void * __ptr64)` | 295 (0x127) | Exported Function | 0x0000000180006e10 | 0x00006e10
`private: static int __cdecl CIlNt4Setupapi::IlSetupDiBuildDriverInfoList(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long)` | 296 (0x128) | Exported Function | 0x0000000180006370 | 0x00006370
`private: static int __cdecl CIlNt4Setupapi::IlSetupDiCallClassInstaller(unsigned int,void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64)` | 297 (0x129) | Exported Function | 0x0000000180006840 | 0x00006840
`private: static int __cdecl CIlNt4Setupapi::IlSetupDiDestroyDeviceInfoList(void * __ptr64)` | 299 (0x12b) | Exported Function | 0x0000000180006a80 | 0x00006a80
`private: static int __cdecl CIlNt4Setupapi::IlSetupDiDestroyDriverInfoList(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long)` | 300 (0x12c) | Exported Function | 0x0000000180006250 | 0x00006250
`private: static int __cdecl CIlNt4Setupapi::IlSetupDiEnumDeviceInfo(void * __ptr64,unsigned long,struct _SP_DEVINFO_DATA * __ptr64)` | 301 (0x12d) | Exported Function | 0x0000000180006130 | 0x00006130
`private: static int __cdecl CIlNt4Setupapi::IlSetupDiEnumDeviceInterfaces(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _GUID const * __ptr64,unsigned long,struct _SP_DEVICE_INTERFACE_DATA * __ptr64)` | 302 (0x12e) | Exported Function | 0x0000000180007650 | 0x00007650
`private: static int __cdecl CIlNt4Setupapi::IlSetupDiEnumDriverInfoW(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long,unsigned long,struct _SP_DRVINFO_DATA_V2_W * __ptr64)` | 303 (0x12f) | Exported Function | 0x0000000180007380 | 0x00007380
`private: static int __cdecl CIlNt4Setupapi::IlSetupDiGetDeviceInstallParamsW(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DEVINSTALL_PARAMS_W * __ptr64)` | 306 (0x132) | Exported Function | 0x0000000180006600 | 0x00006600
`private: static int __cdecl CIlNt4Setupapi::IlSetupDiGetDeviceInterfaceDetailW(void * __ptr64,struct _SP_DEVICE_INTERFACE_DATA * __ptr64,struct _SP_DEVICE_INTERFACE_DETAIL_DATA_W * __ptr64,unsigned long,unsigned long * __ptr64,struct _SP_DEVINFO_DATA * __ptr64)` | 307 (0x133) | Exported Function | 0x00000001800077c0 | 0x000077c0
`private: static int __cdecl CIlNt4Setupapi::IlSetupDiGetDeviceRegistryPropertyW(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long,unsigned long * __ptr64,unsigned char * __ptr64,unsigned long,unsigned long * __ptr64)` | 308 (0x134) | Exported Function | 0x0000000180007210 | 0x00007210
`private: static int __cdecl CIlNt4Setupapi::IlSetupDiGetDriverInfoDetailW(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DRVINFO_DATA_V2_W * __ptr64,struct _SP_DRVINFO_DETAIL_DATA_W * __ptr64,unsigned long,unsigned long * __ptr64)` | 309 (0x135) | Exported Function | 0x00000001800064c0 | 0x000064c0
`private: static int __cdecl CIlNt4Setupapi::IlSetupDiOpenDeviceInfoW(void * __ptr64,unsigned short const * __ptr64,struct HWND__ * __ptr64,unsigned long,struct _SP_DEVINFO_DATA * __ptr64)` | 311 (0x137) | Exported Function | 0x0000000180006000 | 0x00006000
`private: static int __cdecl CIlNt4Setupapi::IlSetupDiSetDeviceInstallParamsW(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DEVINSTALL_PARAMS_W * __ptr64)` | 312 (0x138) | Exported Function | 0x0000000180006720 | 0x00006720
`private: static int __cdecl CIlNt4Setupapi::IlSetupDiSetSelectedDriverW(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DRVINFO_DATA_V2_W * __ptr64)` | 313 (0x139) | Exported Function | 0x0000000180006960 | 0x00006960
`private: static int __cdecl CIlNt4Setupapi::IlSetupQueryInfOriginalFileInformationW(struct _SP_INF_INFORMATION * __ptr64,unsigned int,struct _SP_ALTPLATFORM_INFO_V2 * __ptr64,struct _SP_ORIGINAL_FILE_INFO_W * __ptr64)` | 316 (0x13c) | Exported Function | 0x00000001800070a0 | 0x000070a0
`private: static int __cdecl CIlNt4Advapi32::IlUnlockServiceDatabase(void * __ptr64)` | 321 (0x141) | Exported Function | 0x0000000180003030 | 0x00003030
`private: static unsigned long (__cdecl* __ptr64 CIlNt4Netapi32::m_NetUserDel)(unsigned short const * __ptr64,unsigned short const * __ptr64)` | 572 (0x23c) | Exported Function | 0x0000000180021c08 | 0x00021c08
`private: static unsigned long (__cdecl* __ptr64 CIlNt4Netapi32::m_NetUserGetLocalGroups)(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,unsigned char * __ptr64 * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64)` | 574 (0x23e) | Exported Function | 0x0000000180021970 | 0x00021970
`private: static unsigned long CIlNt4Advapi32::m_RefCountOpenServiceW` | 609 (0x261) | Exported Function | 0x0000000180021b48 | 0x00021b48
`private: static unsigned long CIlNt4Advapi32::m_RefCountQueryServiceConfigW` | 612 (0x264) | Exported Function | 0x0000000180021b10 | 0x00021b10
`private: static unsigned long CIlNt4Advapi32::m_RefCountStartServiceW` | 637 (0x27d) | Exported Function | 0x0000000180021a28 | 0x00021a28
`private: static unsigned long CIlNt4Advapi32::m_RefCountUnlockServiceDatabase` | 638 (0x27e) | Exported Function | 0x00000001800219a8 | 0x000219a8
`private: static unsigned long CIlNt4Kernel32::m_RefCountCreateToolhelp32Snapshot` | 589 (0x24d) | Exported Function | 0x00000001800219b8 | 0x000219b8
`private: static unsigned long CIlNt4Kernel32::m_RefCountGetSystemWindowsDirectoryW` | 594 (0x252) | Exported Function | 0x0000000180021938 | 0x00021938
`private: static unsigned long CIlNt4Kernel32::m_RefCountGlobalMemoryStatusEx` | 595 (0x253) | Exported Function | 0x0000000180021b90 | 0x00021b90
`private: static unsigned long CIlNt4Kernel32::m_RefCountProcess32FirstW` | 610 (0x262) | Exported Function | 0x0000000180021a3c | 0x00021a3c
`private: static unsigned long CIlNt4Kernel32::m_RefCountProcess32NextW` | 611 (0x263) | Exported Function | 0x0000000180021a60 | 0x00021a60
`private: static unsigned long CIlNt4Kernel32::m_RefCountRegisterWaitForSingleObject` | 613 (0x265) | Exported Function | 0x0000000180021b7c | 0x00021b7c
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetApiBufferFree` | 599 (0x257) | Exported Function | 0x0000000180021b60 | 0x00021b60
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetLocalGroupAdd` | 600 (0x258) | Exported Function | 0x0000000180021ac4 | 0x00021ac4
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetLocalGroupAddMembers` | 601 (0x259) | Exported Function | 0x0000000180021b78 | 0x00021b78
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetLocalGroupEnum` | 602 (0x25a) | Exported Function | 0x0000000180021980 | 0x00021980
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetUserAdd` | 603 (0x25b) | Exported Function | 0x00000001800219a0 | 0x000219a0
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetUserDel` | 604 (0x25c) | Exported Function | 0x0000000180021bd0 | 0x00021bd0
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetUserEnum` | 605 (0x25d) | Exported Function | 0x0000000180021a74 | 0x00021a74
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetUserGetLocalGroups` | 606 (0x25e) | Exported Function | 0x0000000180021a9c | 0x00021a9c
`private: static unsigned long CIlNt4Netapi32::m_RefCountNetWkstaGetInfo` | 607 (0x25f) | Exported Function | 0x0000000180021a2c | 0x00021a2c
`private: static unsigned long CIlNt4Advapi32::m_RefCountOpenSCManagerW` | 608 (0x260) | Exported Function | 0x0000000180021be8 | 0x00021be8
`private: static unsigned long (__cdecl* __ptr64 CIlNt4Netapi32::m_NetUserEnum)(unsigned short const * __ptr64,unsigned long,unsigned long,unsigned char * __ptr64 * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64)` | 573 (0x23d) | Exported Function | 0x0000000180021968 | 0x00021968
`private: static unsigned long CIlNt4Advapi32::m_RefCountLockServiceDatabase` | 597 (0x255) | Exported Function | 0x0000000180021b14 | 0x00021b14
`private: static unsigned long CIlNt4Advapi32::m_RefCountEnumServicesStatusExW` | 593 (0x251) | Exported Function | 0x0000000180021a98 | 0x00021a98
`private: static unsigned long (__cdecl* __ptr64 CIlNt4Netapi32::m_NetWkstaGetInfo)(unsigned short * __ptr64,unsigned long,unsigned char * __ptr64 * __ptr64)` | 575 (0x23f) | Exported Function | 0x0000000180021a00 | 0x00021a00
`private: static unsigned long __cdecl CIlNt4Netapi32::IlNetApiBufferFree(void * __ptr64)` | 271 (0x10f) | Exported Function | 0x0000000180005780 | 0x00005780
`private: static unsigned long __cdecl CIlNt4Netapi32::IlNetLocalGroupAdd(unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long * __ptr64)` | 272 (0x110) | Exported Function | 0x00000001800054c0 | 0x000054c0
`private: static unsigned long __cdecl CIlNt4Netapi32::IlNetLocalGroupAddMembers(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long)` | 273 (0x111) | Exported Function | 0x0000000180005370 | 0x00005370
`private: static unsigned long __cdecl CIlNt4Netapi32::IlNetLocalGroupEnum(unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64 * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64,unsigned __int64 * __ptr64)` | 274 (0x112) | Exported Function | 0x0000000180005630 | 0x00005630
`private: static unsigned long __cdecl CIlNt4Netapi32::IlNetUserAdd(unsigned short const * __ptr64,unsigned long,unsigned char * __ptr64,unsigned long * __ptr64)` | 275 (0x113) | Exported Function | 0x0000000180004da0 | 0x00004da0
`private: static unsigned long __cdecl CIlNt4Netapi32::IlNetUserDel(unsigned short const * __ptr64,unsigned short const * __ptr64)` | 276 (0x114) | Exported Function | 0x0000000180004ed0 | 0x00004ed0
`private: static unsigned long __cdecl CIlNt4Netapi32::IlNetUserEnum(unsigned short const * __ptr64,unsigned long,unsigned long,unsigned char * __ptr64 * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64)` | 277 (0x115) | Exported Function | 0x0000000180005040 | 0x00005040
`private: static unsigned long __cdecl CIlNt4Netapi32::IlNetUserGetLocalGroups(unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long,unsigned long,unsigned char * __ptr64 * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64)` | 278 (0x116) | Exported Function | 0x00000001800051f0 | 0x000051f0
`private: static unsigned long __cdecl CIlNt4Netapi32::IlNetWkstaGetInfo(unsigned short * __ptr64,unsigned long,unsigned char * __ptr64 * __ptr64)` | 279 (0x117) | Exported Function | 0x0000000180004c60 | 0x00004c60
`private: static unsigned long CIlNt4Advapi32::m_RefCountChangeServiceConfigW` | 581 (0x245) | Exported Function | 0x0000000180021b18 | 0x00021b18
`private: static unsigned long CIlNt4Advapi32::m_RefCountCloseServiceHandle` | 582 (0x246) | Exported Function | 0x0000000180021a18 | 0x00021a18
`private: static unsigned long CIlNt4Advapi32::m_RefCountConvertSecurityDescriptorToStringSecurityDescriptorW` | 583 (0x247) | Exported Function | 0x0000000180021b94 | 0x00021b94
`private: static unsigned long CIlNt4Advapi32::m_RefCountConvertSidToStringSidW` | 584 (0x248) | Exported Function | 0x000000018002194c | 0x0002194c
`private: static unsigned long CIlNt4Advapi32::m_RefCountConvertStringSecurityDescriptorToSecurityDescriptorW` | 585 (0x249) | Exported Function | 0x0000000180021b00 | 0x00021b00
`private: static unsigned long CIlNt4Advapi32::m_RefCountConvertStringSidToSidW` | 586 (0x24a) | Exported Function | 0x0000000180021ac0 | 0x00021ac0
`private: static unsigned long CIlNt4Advapi32::m_RefCountCreateServiceW` | 588 (0x24c) | Exported Function | 0x0000000180021b80 | 0x00021b80
`private: static unsigned long CIlNt4Advapi32::m_RefCountCreateWellKnownSid` | 591 (0x24f) | Exported Function | 0x00000001800219e0 | 0x000219e0
`private: static unsigned long CIlNt4Advapi32::m_RefCountEncryptFileW` | 592 (0x250) | Exported Function | 0x0000000180021c48 | 0x00021c48
`private: static unsigned long CIlNt4Advapi32::m_RefCountInitiateSystemShutdownExW` | 596 (0x254) | Exported Function | 0x0000000180021c38 | 0x00021c38
`private: static int __cdecl CIlNt4Advapi32::IlStartServiceW(struct SC_HANDLE__ * __ptr64,unsigned long,unsigned short const * __ptr64 * __ptr64)` | 320 (0x140) | Exported Function | 0x0000000180002c00 | 0x00002c00
`private: static int __cdecl CIlNt4Advapi32::IlQueryServiceConfigW(struct SC_HANDLE__ * __ptr64,struct _QUERY_SERVICE_CONFIGW * __ptr64,unsigned long,unsigned long * __ptr64)` | 293 (0x125) | Exported Function | 0x0000000180002670 | 0x00002670
`private: static int __cdecl CIlNt4Advapi32::IlInitiateSystemShutdownExW(unsigned short * __ptr64,unsigned short * __ptr64,unsigned long,int,int,unsigned long)` | 265 (0x109) | Exported Function | 0x0000000180003280 | 0x00003280
`const CIlKernel32::``vftable'` | 111 (0x6f) | Exported Function | 0x000000018000c598 | 0x0000c598
`const CIlMuisetupapi::``vftable'` | 112 (0x70) | Exported Function | 0x000000018000c168 | 0x0000c168
`const CIlNt4Advapi32::``vftable'` | 113 (0x71) | Exported Function | 0x000000018000c388 | 0x0000c388
`const CIlNt4Kernel32::``vftable'` | 114 (0x72) | Exported Function | 0x000000018000c318 | 0x0000c318
`const CIlNt4Netapi32::``vftable'` | 115 (0x73) | Exported Function | 0x000000018000c870 | 0x0000c870
`const CIlNt4Setupapi::``vftable'` | 116 (0x74) | Exported Function | 0x000000018000c8c0 | 0x0000c8c0
`const CIlNt4User32::``vftable'` | 117 (0x75) | Exported Function | 0x000000018000c978 | 0x0000c978
`const CIlNt4Userenv::``vftable'` | 118 (0x76) | Exported Function | 0x000000018000c8b8 | 0x0000c8b8
`const CIlNt6Userenv::``vftable'` | 119 (0x77) | Exported Function | 0x000000018000c410 | 0x0000c410
`const CIlOle32::``vftable'` | 120 (0x78) | Exported Function | 0x000000018000c348 | 0x0000c348
`const CIlOleaut32::``vftable'` | 121 (0x79) | Exported Function | 0x000000018000c980 | 0x0000c980
`const CIlSetupapi::``vftable'` | 122 (0x7a) | Exported Function | 0x000000018000c138 | 0x0000c138
`const CIlShell32::``vftable'` | 123 (0x7b) | Exported Function | 0x000000018000c128 | 0x0000c128
`const CIlUser32::``vftable'` | 124 (0x7c) | Exported Function | 0x000000018000c578 | 0x0000c578
`const CIlVersion::``vftable'` | 125 (0x7d) | Exported Function | 0x000000018000c300 | 0x0000c300
`const CIlW2kDynWs2_32::``vftable'` | 126 (0x7e) | Exported Function | 0x000000018000c530 | 0x0000c530
`const CIlWimgapi::``vftable'` | 127 (0x7f) | Exported Function | 0x000000018000c4f0 | 0x0000c4f0
`const CIlWs2_32::``vftable'` | 128 (0x80) | Exported Function | 0x000000018000c418 | 0x0000c418
`private: static int (__cdecl* __ptr64 CIlNt4Advapi32::m_ChangeServiceConfigW)(struct SC_HANDLE__ * __ptr64,unsigned long,unsigned long,unsigned long,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 549 (0x225) | Exported Function | 0x0000000180021b28 | 0x00021b28
`const CIlIphlpapi::``vftable'` | 110 (0x6e) | Exported Function | 0x000000018000c868 | 0x0000c868
`private: static int (__cdecl* __ptr64 CIlNt4Advapi32::m_CloseServiceHandle)(struct SC_HANDLE__ * __ptr64)` | 550 (0x226) | Exported Function | 0x0000000180021bc0 | 0x00021bc0
`const CIlDeplorch::``vftable'` | 109 (0x6d) | Exported Function | 0x000000018000c528 | 0x0000c528
`class CIlWs2_32 IlWs2_32` | 326 (0x146) | Exported Function | 0x0000000180021280 | 0x00021280
`class CIlDeplorch IlDeplorch` | 260 (0x104) | Exported Function | 0x00000001800212b8 | 0x000212b8
`class CIlIphlpapi IlIphlpapi` | 266 (0x10a) | Exported Function | 0x00000001800212b0 | 0x000212b0
`class CIlKernel32 IlKernel32` | 267 (0x10b) | Exported Function | 0x0000000180021258 | 0x00021258
`class CIlMuisetupapi IlMuisetupapi` | 270 (0x10e) | Exported Function | 0x0000000180021288 | 0x00021288
`class CIlNt4Advapi32 IlNt4Advapi32` | 280 (0x118) | Exported Function | 0x0000000180021298 | 0x00021298
`class CIlNt4Kernel32 IlNt4Kernel32` | 281 (0x119) | Exported Function | 0x0000000180021238 | 0x00021238
`class CIlNt4Netapi32 IlNt4Netapi32` | 282 (0x11a) | Exported Function | 0x0000000180021320 | 0x00021320
`class CIlNt4Setupapi IlNt4Setupapi` | 283 (0x11b) | Exported Function | 0x00000001800212f0 | 0x000212f0
`class CIlNt4User32 IlNt4User32` | 284 (0x11c) | Exported Function | 0x0000000180021340 | 0x00021340
`class CIlNt4Userenv IlNt4Userenv` | 285 (0x11d) | Exported Function | 0x0000000180021260 | 0x00021260
`class CIlNt6Userenv IlNt6Userenv` | 286 (0x11e) | Exported Function | 0x00000001800212c8 | 0x000212c8
`class CIlOle32 IlOle32` | 287 (0x11f) | Exported Function | 0x00000001800212e8 | 0x000212e8
`class CIlOleaut32 IlOleaut32` | 288 (0x120) | Exported Function | 0x0000000180021278 | 0x00021278
`class CIlSetupapi IlSetupapi` | 318 (0x13e) | Exported Function | 0x0000000180021338 | 0x00021338
`class CIlShell32 IlShell32` | 319 (0x13f) | Exported Function | 0x00000001800212c0 | 0x000212c0
`class CIlUser32 IlUser32` | 322 (0x142) | Exported Function | 0x0000000180021250 | 0x00021250
`class CIlVersion IlVersion` | 323 (0x143) | Exported Function | 0x00000001800212e0 | 0x000212e0
`class CIlW2kDynWs2_32 IlW2kDynWs2_32` | 324 (0x144) | Exported Function | 0x0000000180021308 | 0x00021308
`class CIlWimgapi IlWimgapi` | 325 (0x145) | Exported Function | 0x0000000180021290 | 0x00021290
`const CIlAdvapi32::``vftable'` | 108 (0x6c) | Exported Function | 0x000000018000c178 | 0x0000c178
`private: static int (__cdecl* __ptr64 CIlNt4Advapi32::m_ConvertSecurityDescriptorToStringSecurityDescriptorW)(void * __ptr64,unsigned long,unsigned long,unsigned short * __ptr64 * __ptr64,unsigned long * __ptr64)` | 551 (0x227) | Exported Function | 0x0000000180021990 | 0x00021990
`private: static int (__cdecl* __ptr64 CIlNt4Advapi32::m_ConvertSidToStringSidW)(void * __ptr64,unsigned short * __ptr64 * __ptr64)` | 552 (0x228) | Exported Function | 0x0000000180021c10 | 0x00021c10
`private: static int (__cdecl* __ptr64 CIlNt4Advapi32::m_ConvertStringSecurityDescriptorToSecurityDescriptorW)(unsigned short const * __ptr64,unsigned long,void * __ptr64 * __ptr64,unsigned long * __ptr64)` | 553 (0x229) | Exported Function | 0x0000000180021a78 | 0x00021a78
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiOpenDeviceInfoW)(void * __ptr64,unsigned short const * __ptr64,struct HWND__ * __ptr64,unsigned long,struct _SP_DEVINFO_DATA * __ptr64)` | 659 (0x293) | Exported Function | 0x0000000180021bb8 | 0x00021bb8
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiSetDeviceInstallParamsW)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DEVINSTALL_PARAMS_W * __ptr64)` | 660 (0x294) | Exported Function | 0x0000000180021a90 | 0x00021a90
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiSetSelectedDriverW)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DRVINFO_DATA_V2_W * __ptr64)` | 661 (0x295) | Exported Function | 0x00000001800219c8 | 0x000219c8
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupGetInfInformationW)(void const * __ptr64,unsigned long,struct _SP_INF_INFORMATION * __ptr64,unsigned long,unsigned long * __ptr64)` | 662 (0x296) | Exported Function | 0x0000000180021a40 | 0x00021a40
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupQueryInfOriginalFileInformationW)(struct _SP_INF_INFORMATION * __ptr64,unsigned int,struct _SP_ALTPLATFORM_INFO_V2 * __ptr64,struct _SP_ORIGINAL_FILE_INFO_W * __ptr64)` | 664 (0x298) | Exported Function | 0x0000000180021b58 | 0x00021b58
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupScanFileQueueW)(void * __ptr64,unsigned long,struct HWND__ * __ptr64,unsigned int (__cdecl*)(void * __ptr64,unsigned int,unsigned __int64,unsigned __int64),void * __ptr64,unsigned long * __ptr64)` | 665 (0x299) | Exported Function | 0x0000000180021920 | 0x00021920
`private: static int (__cdecl* __ptr64 CIlNt4User32::m_LockSetForegroundWindow)(unsigned int)` | 566 (0x236) | Exported Function | 0x00000001800219c0 | 0x000219c0
`private: static int (__cdecl* __ptr64 CIlNt4Userenv::m_CreateUserProfileExW)(void * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short * __ptr64,unsigned long,int)` | 558 (0x22e) | Exported Function | 0x00000001800219d8 | 0x000219d8
`private: static int (__cdecl* __ptr64 CIlW2kDynWs2_32::m_getaddrinfo)(char const * __ptr64,char const * __ptr64,struct addrinfo const * __ptr64,struct addrinfo * __ptr64 * __ptr64)` | 669 (0x29d) | Exported Function | 0x0000000180021ae8 | 0x00021ae8
`private: static int (__cdecl* __ptr64 CIlW2kDynWs2_32::m_getnameinfo)(struct sockaddr const * __ptr64,int,char * __ptr64,unsigned long,char * __ptr64,unsigned long,int)` | 670 (0x29e) | Exported Function | 0x0000000180021be0 | 0x00021be0
`private: static int __cdecl CIlNt4Advapi32::IlChangeServiceConfigW(struct SC_HANDLE__ * __ptr64,unsigned long,unsigned long,unsigned long,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 249 (0xf9) | Exported Function | 0x0000000180002820 | 0x00002820
`private: static int __cdecl CIlNt4Advapi32::IlCloseServiceHandle(struct SC_HANDLE__ * __ptr64)` | 250 (0xfa) | Exported Function | 0x0000000180003140 | 0x00003140
`private: static int __cdecl CIlNt4Advapi32::IlConvertSecurityDescriptorToStringSecurityDescriptorW(void * __ptr64,unsigned long,unsigned long,unsigned short * __ptr64 * __ptr64,unsigned long * __ptr64)` | 251 (0xfb) | Exported Function | 0x0000000180002050 | 0x00002050
`private: static int __cdecl CIlNt4Advapi32::IlConvertSidToStringSidW(void * __ptr64,unsigned short * __ptr64 * __ptr64)` | 252 (0xfc) | Exported Function | 0x0000000180001df0 | 0x00001df0
`private: static int __cdecl CIlNt4Advapi32::IlConvertStringSecurityDescriptorToSecurityDescriptorW(unsigned short const * __ptr64,unsigned long,void * __ptr64 * __ptr64,unsigned long * __ptr64)` | 253 (0xfd) | Exported Function | 0x00000001800021a0 | 0x000021a0
`private: static int __cdecl CIlNt4Advapi32::IlConvertStringSidToSidW(unsigned short * __ptr64,void * __ptr64 * __ptr64)` | 254 (0xfe) | Exported Function | 0x0000000180001f10 | 0x00001f10
`private: static int __cdecl CIlNt4Advapi32::IlCreateWellKnownSid(enum WELL_KNOWN_SID_TYPE,void * __ptr64,void * __ptr64,unsigned long * __ptr64)` | 259 (0x103) | Exported Function | 0x00000001800022e0 | 0x000022e0
`private: static int __cdecl CIlNt4Advapi32::IlEncryptFileW(unsigned short const * __ptr64)` | 261 (0x105) | Exported Function | 0x00000001800033c0 | 0x000033c0
`private: static int __cdecl CIlNt4Advapi32::IlEnumServicesStatusExW(struct SC_HANDLE__ * __ptr64,enum _SC_ENUM_TYPE,unsigned long,unsigned long,unsigned char * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned short const * __ptr64)` | 262 (0x106) | Exported Function | 0x0000000180002d90 | 0x00002d90
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiGetDriverInfoDetailW)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DRVINFO_DATA_V2_W * __ptr64,struct _SP_DRVINFO_DETAIL_DATA_W * __ptr64,unsigned long,unsigned long * __ptr64)` | 657 (0x291) | Exported Function | 0x0000000180021a10 | 0x00021a10
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiGetDeviceRegistryPropertyW)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long,unsigned long * __ptr64,unsigned char * __ptr64,unsigned long,unsigned long * __ptr64)` | 656 (0x290) | Exported Function | 0x0000000180021af0 | 0x00021af0
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiGetDeviceInterfaceDetailW)(void * __ptr64,struct _SP_DEVICE_INTERFACE_DATA * __ptr64,struct _SP_DEVICE_INTERFACE_DETAIL_DATA_W * __ptr64,unsigned long,unsigned long * __ptr64,struct _SP_DEVINFO_DATA * __ptr64)` | 655 (0x28f) | Exported Function | 0x0000000180021aa0 | 0x00021aa0
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiGetDeviceInstallParamsW)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DEVINSTALL_PARAMS_W * __ptr64)` | 654 (0x28e) | Exported Function | 0x0000000180021c00 | 0x00021c00
`private: static int (__cdecl* __ptr64 CIlNt4Advapi32::m_ConvertStringSidToSidW)(unsigned short * __ptr64,void * __ptr64 * __ptr64)` | 554 (0x22a) | Exported Function | 0x00000001800219f0 | 0x000219f0
`private: static int (__cdecl* __ptr64 CIlNt4Advapi32::m_CreateWellKnownSid)(enum WELL_KNOWN_SID_TYPE,void * __ptr64,void * __ptr64,unsigned long * __ptr64)` | 559 (0x22f) | Exported Function | 0x0000000180021b08 | 0x00021b08
`private: static int (__cdecl* __ptr64 CIlNt4Advapi32::m_EncryptFileW)(unsigned short const * __ptr64)` | 560 (0x230) | Exported Function | 0x0000000180021c18 | 0x00021c18
`private: static int (__cdecl* __ptr64 CIlNt4Advapi32::m_EnumServicesStatusExW)(struct SC_HANDLE__ * __ptr64,enum _SC_ENUM_TYPE,unsigned long,unsigned long,unsigned char * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned short const * __ptr64)` | 561 (0x231) | Exported Function | 0x00000001800219e8 | 0x000219e8
`private: static int (__cdecl* __ptr64 CIlNt4Advapi32::m_InitiateSystemShutdownExW)(unsigned short * __ptr64,unsigned short * __ptr64,unsigned long,int,int,unsigned long)` | 564 (0x234) | Exported Function | 0x0000000180021ab8 | 0x00021ab8
`private: static int (__cdecl* __ptr64 CIlNt4Advapi32::m_QueryServiceConfigW)(struct SC_HANDLE__ * __ptr64,struct _QUERY_SERVICE_CONFIGW * __ptr64,unsigned long,unsigned long * __ptr64)` | 580 (0x244) | Exported Function | 0x0000000180021988 | 0x00021988
`private: static int (__cdecl* __ptr64 CIlNt4Advapi32::m_StartServiceW)(struct SC_HANDLE__ * __ptr64,unsigned long,unsigned short const * __ptr64 * __ptr64)` | 666 (0x29a) | Exported Function | 0x0000000180021af8 | 0x00021af8
`private: static int (__cdecl* __ptr64 CIlNt4Advapi32::m_UnlockServiceDatabase)(void * __ptr64)` | 667 (0x29b) | Exported Function | 0x0000000180021998 | 0x00021998
`private: static int (__cdecl* __ptr64 CIlNt4Kernel32::m_GlobalMemoryStatusEx)(struct _MEMORYSTATUSEX * __ptr64)` | 563 (0x233) | Exported Function | 0x0000000180021a50 | 0x00021a50
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupCloseFileQueue` | 614 (0x266) | Exported Function | 0x0000000180021b20 | 0x00021b20
`private: static int (__cdecl* __ptr64 CIlNt4Kernel32::m_Process32FirstW)(void * __ptr64,struct tagPROCESSENTRY32W * __ptr64)` | 578 (0x242) | Exported Function | 0x0000000180021a80 | 0x00021a80
`private: static int (__cdecl* __ptr64 CIlNt4Kernel32::m_RegisterWaitForSingleObject)(void * __ptr64 * __ptr64,void * __ptr64,void (__cdecl*)(void * __ptr64,unsigned char),void * __ptr64,unsigned long,unsigned long)` | 642 (0x282) | Exported Function | 0x0000000180021978 | 0x00021978
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupCloseFileQueue)(void * __ptr64)` | 643 (0x283) | Exported Function | 0x0000000180021b98 | 0x00021b98
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiBuildDriverInfoList)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long)` | 644 (0x284) | Exported Function | 0x0000000180021bf8 | 0x00021bf8
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiCallClassInstaller)(unsigned int,void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64)` | 645 (0x285) | Exported Function | 0x0000000180021a48 | 0x00021a48
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiDestroyDeviceInfoList)(void * __ptr64)` | 647 (0x287) | Exported Function | 0x0000000180021b88 | 0x00021b88
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiDestroyDriverInfoList)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long)` | 648 (0x288) | Exported Function | 0x0000000180021ad8 | 0x00021ad8
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiEnumDeviceInfo)(void * __ptr64,unsigned long,struct _SP_DEVINFO_DATA * __ptr64)` | 649 (0x289) | Exported Function | 0x0000000180021a58 | 0x00021a58
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiEnumDeviceInterfaces)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _GUID const * __ptr64,unsigned long,struct _SP_DEVICE_INTERFACE_DATA * __ptr64)` | 650 (0x28a) | Exported Function | 0x00000001800219b0 | 0x000219b0
`private: static int (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiEnumDriverInfoW)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long,unsigned long,struct _SP_DRVINFO_DATA_V2_W * __ptr64)` | 651 (0x28b) | Exported Function | 0x0000000180021958 | 0x00021958
`private: static int (__cdecl* __ptr64 CIlNt4Kernel32::m_Process32NextW)(void * __ptr64,struct tagPROCESSENTRY32W * __ptr64)` | 579 (0x243) | Exported Function | 0x0000000180021c40 | 0x00021c40
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupScanFileQueueW(void) __ptr64)(void * __ptr64,unsigned long,struct HWND__ * __ptr64,unsigned int (__cdecl*)(void * __ptr64,unsigned int,unsigned __int64,unsigned __int64),void * __ptr64,unsigned long * __ptr64)` | 531 (0x213) | Exported Function | 0x0000000180006d20 | 0x00006d20
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiBuildDriverInfoList` | 615 (0x267) | Exported Function | 0x0000000180021b30 | 0x00021b30
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiCreateDeviceInfoListExW` | 617 (0x269) | Exported Function | 0x0000000180021918 | 0x00021918
`public: class CIlNt4Advapi32 & __ptr64 __cdecl CIlNt4Advapi32::operator=(class CIlNt4Advapi32 && __ptr64) __ptr64` | 76 (0x4c) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlNt4Advapi32 & __ptr64 __cdecl CIlNt4Advapi32::operator=(class CIlNt4Advapi32 const & __ptr64) __ptr64` | 77 (0x4d) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlNt4Kernel32 & __ptr64 __cdecl CIlNt4Kernel32::operator=(class CIlNt4Kernel32 && __ptr64) __ptr64` | 78 (0x4e) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlNt4Kernel32 & __ptr64 __cdecl CIlNt4Kernel32::operator=(class CIlNt4Kernel32 const & __ptr64) __ptr64` | 79 (0x4f) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlNt4Netapi32 & __ptr64 __cdecl CIlNt4Netapi32::operator=(class CIlNt4Netapi32 && __ptr64) __ptr64` | 80 (0x50) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlNt4Netapi32 & __ptr64 __cdecl CIlNt4Netapi32::operator=(class CIlNt4Netapi32 const & __ptr64) __ptr64` | 81 (0x51) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlNt4Setupapi & __ptr64 __cdecl CIlNt4Setupapi::operator=(class CIlNt4Setupapi && __ptr64) __ptr64` | 82 (0x52) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlNt4Setupapi & __ptr64 __cdecl CIlNt4Setupapi::operator=(class CIlNt4Setupapi const & __ptr64) __ptr64` | 83 (0x53) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlNt4User32 & __ptr64 __cdecl CIlNt4User32::operator=(class CIlNt4User32 && __ptr64) __ptr64` | 84 (0x54) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlNt4User32 & __ptr64 __cdecl CIlNt4User32::operator=(class CIlNt4User32 const & __ptr64) __ptr64` | 85 (0x55) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlNt4Userenv & __ptr64 __cdecl CIlNt4Userenv::operator=(class CIlNt4Userenv && __ptr64) __ptr64` | 86 (0x56) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlNt4Userenv & __ptr64 __cdecl CIlNt4Userenv::operator=(class CIlNt4Userenv const & __ptr64) __ptr64` | 87 (0x57) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlNt6Userenv & __ptr64 __cdecl CIlNt6Userenv::operator=(class CIlNt6Userenv && __ptr64) __ptr64` | 88 (0x58) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlNt6Userenv & __ptr64 __cdecl CIlNt6Userenv::operator=(class CIlNt6Userenv const & __ptr64) __ptr64` | 89 (0x59) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlOle32 & __ptr64 __cdecl CIlOle32::operator=(class CIlOle32 && __ptr64) __ptr64` | 90 (0x5a) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlOle32 & __ptr64 __cdecl CIlOle32::operator=(class CIlOle32 const & __ptr64) __ptr64` | 91 (0x5b) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlOleaut32 & __ptr64 __cdecl CIlOleaut32::operator=(class CIlOleaut32 && __ptr64) __ptr64` | 92 (0x5c) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlOleaut32 & __ptr64 __cdecl CIlOleaut32::operator=(class CIlOleaut32 const & __ptr64) __ptr64` | 93 (0x5d) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlSetupapi & __ptr64 __cdecl CIlSetupapi::operator=(class CIlSetupapi && __ptr64) __ptr64` | 94 (0x5e) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlMuisetupapi & __ptr64 __cdecl CIlMuisetupapi::operator=(class CIlMuisetupapi const & __ptr64) __ptr64` | 75 (0x4b) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlSetupapi & __ptr64 __cdecl CIlSetupapi::operator=(class CIlSetupapi const & __ptr64) __ptr64` | 95 (0x5f) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlMuisetupapi & __ptr64 __cdecl CIlMuisetupapi::operator=(class CIlMuisetupapi && __ptr64) __ptr64` | 74 (0x4a) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlIphlpapi & __ptr64 __cdecl CIlIphlpapi::operator=(class CIlIphlpapi const & __ptr64) __ptr64` | 72 (0x48) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: __cdecl CIlVersion::CIlVersion(class CIlVersion && __ptr64) __ptr64` | 52 (0x34) | Exported Function | 0x0000000180007f80 | 0x00007f80
`public: __cdecl CIlVersion::CIlVersion(class CIlVersion const & __ptr64) __ptr64` | 53 (0x35) | Exported Function | 0x0000000180007f80 | 0x00007f80
`public: __cdecl CIlVersion::CIlVersion(void) __ptr64` | 54 (0x36) | Exported Function | 0x0000000180007f80 | 0x00007f80
`public: __cdecl CIlW2kDynWs2_32::CIlW2kDynWs2_32(class CIlW2kDynWs2_32 && __ptr64) __ptr64` | 55 (0x37) | Exported Function | 0x00000001800089a0 | 0x000089a0
`public: __cdecl CIlW2kDynWs2_32::CIlW2kDynWs2_32(class CIlW2kDynWs2_32 const & __ptr64) __ptr64` | 56 (0x38) | Exported Function | 0x00000001800089a0 | 0x000089a0
`public: __cdecl CIlW2kDynWs2_32::CIlW2kDynWs2_32(void) __ptr64` | 57 (0x39) | Exported Function | 0x0000000180008980 | 0x00008980
`public: __cdecl CIlWimgapi::CIlWimgapi(class CIlWimgapi && __ptr64) __ptr64` | 58 (0x3a) | Exported Function | 0x00000001800080b0 | 0x000080b0
`public: __cdecl CIlWimgapi::CIlWimgapi(class CIlWimgapi const & __ptr64) __ptr64` | 59 (0x3b) | Exported Function | 0x00000001800080b0 | 0x000080b0
`public: __cdecl CIlWimgapi::CIlWimgapi(void) __ptr64` | 60 (0x3c) | Exported Function | 0x00000001800080b0 | 0x000080b0
`public: __cdecl CIlWs2_32::CIlWs2_32(class CIlWs2_32 && __ptr64) __ptr64` | 61 (0x3d) | Exported Function | 0x0000000180008570 | 0x00008570
`public: __cdecl CIlWs2_32::CIlWs2_32(class CIlWs2_32 const & __ptr64) __ptr64` | 62 (0x3e) | Exported Function | 0x0000000180008570 | 0x00008570
`public: __cdecl CIlWs2_32::CIlWs2_32(void) __ptr64` | 63 (0x3f) | Exported Function | 0x0000000180008570 | 0x00008570
`public: class CDynLib & __ptr64 __cdecl CDynLib::operator=(class CDynLib && __ptr64) __ptr64` | 65 (0x41) | Exported Function | 0x0000000180001db0 | 0x00001db0
`public: class CDynLib & __ptr64 __cdecl CDynLib::operator=(class CDynLib const & __ptr64) __ptr64` | 66 (0x42) | Exported Function | 0x0000000180001d90 | 0x00001d90
`public: class CIlAdvapi32 & __ptr64 __cdecl CIlAdvapi32::operator=(class CIlAdvapi32 && __ptr64) __ptr64` | 67 (0x43) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlAdvapi32 & __ptr64 __cdecl CIlAdvapi32::operator=(class CIlAdvapi32 const & __ptr64) __ptr64` | 68 (0x44) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlDeplorch & __ptr64 __cdecl CIlDeplorch::operator=(class CIlDeplorch && __ptr64) __ptr64` | 69 (0x45) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlDeplorch & __ptr64 __cdecl CIlDeplorch::operator=(class CIlDeplorch const & __ptr64) __ptr64` | 70 (0x46) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlIphlpapi & __ptr64 __cdecl CIlIphlpapi::operator=(class CIlIphlpapi && __ptr64) __ptr64` | 71 (0x47) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlKernel32 & __ptr64 __cdecl CIlKernel32::operator=(class CIlKernel32 const & __ptr64) __ptr64` | 73 (0x49) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: __cdecl CIlUser32::CIlUser32(void) __ptr64` | 51 (0x33) | Exported Function | 0x0000000180007a50 | 0x00007a50
`public: class CIlShell32 & __ptr64 __cdecl CIlShell32::operator=(class CIlShell32 && __ptr64) __ptr64` | 96 (0x60) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlUser32 & __ptr64 __cdecl CIlUser32::operator=(class CIlUser32 && __ptr64) __ptr64` | 98 (0x62) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: int (__cdecl*__cdecl CIlNt4Kernel32::get_Process32FirstW(void) __ptr64)(void * __ptr64,struct tagPROCESSENTRY32W * __ptr64)` | 505 (0x1f9) | Exported Function | 0x00000001800047e0 | 0x000047e0
`public: int (__cdecl*__cdecl CIlNt4Kernel32::get_Process32NextW(void) __ptr64)(void * __ptr64,struct tagPROCESSENTRY32W * __ptr64)` | 506 (0x1fa) | Exported Function | 0x0000000180004900 | 0x00004900
`public: int (__cdecl*__cdecl CIlNt4Kernel32::get_RegisterWaitForSingleObject(void) __ptr64)(void * __ptr64 * __ptr64,void * __ptr64,void (__cdecl*)(void * __ptr64,unsigned char),void * __ptr64,unsigned long,unsigned long)` | 508 (0x1fc) | Exported Function | 0x00000001800045a0 | 0x000045a0
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupCloseFileQueue(void) __ptr64)(void * __ptr64)` | 509 (0x1fd) | Exported Function | 0x0000000180006e30 | 0x00006e30
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiBuildDriverInfoList(void) __ptr64)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long)` | 510 (0x1fe) | Exported Function | 0x00000001800063a0 | 0x000063a0
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiCallClassInstaller(void) __ptr64)(unsigned int,void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64)` | 511 (0x1ff) | Exported Function | 0x0000000180006870 | 0x00006870
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiDestroyDeviceInfoList(void) __ptr64)(void * __ptr64)` | 513 (0x201) | Exported Function | 0x0000000180006aa0 | 0x00006aa0
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiDestroyDriverInfoList(void) __ptr64)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long)` | 514 (0x202) | Exported Function | 0x0000000180006280 | 0x00006280
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiEnumDeviceInfo(void) __ptr64)(void * __ptr64,unsigned long,struct _SP_DEVINFO_DATA * __ptr64)` | 515 (0x203) | Exported Function | 0x0000000180006160 | 0x00006160
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiEnumDeviceInterfaces(void) __ptr64)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _GUID const * __ptr64,unsigned long,struct _SP_DEVICE_INTERFACE_DATA * __ptr64)` | 516 (0x204) | Exported Function | 0x00000001800076a0 | 0x000076a0
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiEnumDriverInfoW(void) __ptr64)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long,unsigned long,struct _SP_DRVINFO_DATA_V2_W * __ptr64)` | 517 (0x205) | Exported Function | 0x00000001800073d0 | 0x000073d0
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiGetDeviceInstallParamsW(void) __ptr64)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DEVINSTALL_PARAMS_W * __ptr64)` | 520 (0x208) | Exported Function | 0x0000000180006630 | 0x00006630
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiGetDeviceInterfaceDetailW(void) __ptr64)(void * __ptr64,struct _SP_DEVICE_INTERFACE_DATA * __ptr64,struct _SP_DEVICE_INTERFACE_DETAIL_DATA_W * __ptr64,unsigned long,unsigned long * __ptr64,struct _SP_DEVINFO_DATA * __ptr64)` | 521 (0x209) | Exported Function | 0x0000000180007810 | 0x00007810
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiGetDeviceRegistryPropertyW(void) __ptr64)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,unsigned long,unsigned long * __ptr64,unsigned char * __ptr64,unsigned long,unsigned long * __ptr64)` | 522 (0x20a) | Exported Function | 0x0000000180007270 | 0x00007270
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiGetDriverInfoDetailW(void) __ptr64)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DRVINFO_DATA_V2_W * __ptr64,struct _SP_DRVINFO_DETAIL_DATA_W * __ptr64,unsigned long,unsigned long * __ptr64)` | 523 (0x20b) | Exported Function | 0x0000000180006510 | 0x00006510
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiOpenDeviceInfoW(void) __ptr64)(void * __ptr64,unsigned short const * __ptr64,struct HWND__ * __ptr64,unsigned long,struct _SP_DEVINFO_DATA * __ptr64)` | 525 (0x20d) | Exported Function | 0x0000000180006040 | 0x00006040
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiSetDeviceInstallParamsW(void) __ptr64)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DEVINSTALL_PARAMS_W * __ptr64)` | 526 (0x20e) | Exported Function | 0x0000000180006750 | 0x00006750
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupDiSetSelectedDriverW(void) __ptr64)(void * __ptr64,struct _SP_DEVINFO_DATA * __ptr64,struct _SP_DRVINFO_DATA_V2_W * __ptr64)` | 527 (0x20f) | Exported Function | 0x0000000180006990 | 0x00006990
`public: int (__cdecl*__cdecl CIlNt4Setupapi::get_SetupGetInfInformationW(void) __ptr64)(void const * __ptr64,unsigned long,struct _SP_INF_INFORMATION * __ptr64,unsigned long,unsigned long * __ptr64)` | 528 (0x210) | Exported Function | 0x0000000180006f90 | 0x00006f90
`public: int (__cdecl*__cdecl CIlNt4Kernel32::get_GlobalMemoryStatusEx(void) __ptr64)(struct _MEMORYSTATUSEX * __ptr64)` | 490 (0x1ea) | Exported Function | 0x0000000180004b30 | 0x00004b30
`public: class CIlShell32 & __ptr64 __cdecl CIlShell32::operator=(class CIlShell32 const & __ptr64) __ptr64` | 97 (0x61) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: int (__cdecl*__cdecl CIlNt4Advapi32::get_UnlockServiceDatabase(void) __ptr64)(void * __ptr64)` | 533 (0x215) | Exported Function | 0x0000000180003050 | 0x00003050
`public: int (__cdecl*__cdecl CIlNt4Advapi32::get_QueryServiceConfigW(void) __ptr64)(struct SC_HANDLE__ * __ptr64,struct _QUERY_SERVICE_CONFIGW * __ptr64,unsigned long,unsigned long * __ptr64)` | 507 (0x1fb) | Exported Function | 0x00000001800026b0 | 0x000026b0
`public: class CIlUser32 & __ptr64 __cdecl CIlUser32::operator=(class CIlUser32 const & __ptr64) __ptr64` | 99 (0x63) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlVersion & __ptr64 __cdecl CIlVersion::operator=(class CIlVersion && __ptr64) __ptr64` | 100 (0x64) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlVersion & __ptr64 __cdecl CIlVersion::operator=(class CIlVersion const & __ptr64) __ptr64` | 101 (0x65) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlW2kDynWs2_32 & __ptr64 __cdecl CIlW2kDynWs2_32::operator=(class CIlW2kDynWs2_32 && __ptr64) __ptr64` | 102 (0x66) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlW2kDynWs2_32 & __ptr64 __cdecl CIlW2kDynWs2_32::operator=(class CIlW2kDynWs2_32 const & __ptr64) __ptr64` | 103 (0x67) | Exported Function | 0x0000000180003500 | 0x00003500
`public: class CIlWimgapi & __ptr64 __cdecl CIlWimgapi::operator=(class CIlWimgapi && __ptr64) __ptr64` | 104 (0x68) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlWimgapi & __ptr64 __cdecl CIlWimgapi::operator=(class CIlWimgapi const & __ptr64) __ptr64` | 105 (0x69) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlWs2_32 & __ptr64 __cdecl CIlWs2_32::operator=(class CIlWs2_32 && __ptr64) __ptr64` | 106 (0x6a) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: class CIlWs2_32 & __ptr64 __cdecl CIlWs2_32::operator=(class CIlWs2_32 const & __ptr64) __ptr64` | 107 (0x6b) | Exported Function | 0x0000000180001c50 | 0x00001c50
`public: int (__cdecl*__cdecl CIlNt4Advapi32::get_ChangeServiceConfigW(void) __ptr64)(struct SC_HANDLE__ * __ptr64,unsigned long,unsigned long,unsigned long,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64)` | 476 (0x1dc) | Exported Function | 0x00000001800028d0 | 0x000028d0
`public: int (__cdecl*__cdecl CIlNt4Advapi32::get_CloseServiceHandle(void) __ptr64)(struct SC_HANDLE__ * __ptr64)` | 477 (0x1dd) | Exported Function | 0x0000000180003160 | 0x00003160
`public: int (__cdecl*__cdecl CIlNt4Advapi32::get_ConvertSecurityDescriptorToStringSecurityDescriptorW(void) __ptr64)(void * __ptr64,unsigned long,unsigned long,unsigned short * __ptr64 * __ptr64,unsigned long * __ptr64)` | 478 (0x1de) | Exported Function | 0x0000000180002090 | 0x00002090
`public: int (__cdecl*__cdecl CIlNt4Advapi32::get_ConvertSidToStringSidW(void) __ptr64)(void * __ptr64,unsigned short * __ptr64 * __ptr64)` | 479 (0x1df) | Exported Function | 0x0000000180001e20 | 0x00001e20
`public: int (__cdecl*__cdecl CIlNt4Advapi32::get_ConvertStringSecurityDescriptorToSecurityDescriptorW(void) __ptr64)(unsigned short const * __ptr64,unsigned long,void * __ptr64 * __ptr64,unsigned long * __ptr64)` | 480 (0x1e0) | Exported Function | 0x00000001800021e0 | 0x000021e0
`public: int (__cdecl*__cdecl CIlNt4Advapi32::get_ConvertStringSidToSidW(void) __ptr64)(unsigned short * __ptr64,void * __ptr64 * __ptr64)` | 481 (0x1e1) | Exported Function | 0x0000000180001f40 | 0x00001f40
`public: int (__cdecl*__cdecl CIlNt4Advapi32::get_CreateWellKnownSid(void) __ptr64)(enum WELL_KNOWN_SID_TYPE,void * __ptr64,void * __ptr64,unsigned long * __ptr64)` | 486 (0x1e6) | Exported Function | 0x0000000180002320 | 0x00002320
`public: int (__cdecl*__cdecl CIlNt4Advapi32::get_EncryptFileW(void) __ptr64)(unsigned short const * __ptr64)` | 487 (0x1e7) | Exported Function | 0x00000001800033f0 | 0x000033f0
`public: int (__cdecl*__cdecl CIlNt4Advapi32::get_EnumServicesStatusExW(void) __ptr64)(struct SC_HANDLE__ * __ptr64,enum _SC_ENUM_TYPE,unsigned long,unsigned long,unsigned char * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64,unsigned long * __ptr64,unsigned short const * __ptr64)` | 488 (0x1e8) | Exported Function | 0x0000000180002e30 | 0x00002e30
`public: int (__cdecl*__cdecl CIlNt4Advapi32::get_InitiateSystemShutdownExW(void) __ptr64)(unsigned short * __ptr64,unsigned short * __ptr64,unsigned long,int,int,unsigned long)` | 491 (0x1eb) | Exported Function | 0x00000001800032d0 | 0x000032d0
`public: int (__cdecl*__cdecl CIlNt4Advapi32::get_StartServiceW(void) __ptr64)(struct SC_HANDLE__ * __ptr64,unsigned long,unsigned short const * __ptr64 * __ptr64)` | 532 (0x214) | Exported Function | 0x0000000180002c30 | 0x00002c30
`public: __cdecl CIlUser32::CIlUser32(class CIlUser32 const & __ptr64) __ptr64` | 50 (0x32) | Exported Function | 0x0000000180007a50 | 0x00007a50
`public: __cdecl CIlUser32::CIlUser32(class CIlUser32 && __ptr64) __ptr64` | 49 (0x31) | Exported Function | 0x0000000180007a50 | 0x00007a50
`public: __cdecl CIlShell32::CIlShell32(void) __ptr64` | 48 (0x30) | Exported Function | 0x0000000180007980 | 0x00007980
`private: static unsigned long CIlW2kDynWs2_32::m_RefCountgetaddrinfo` | 640 (0x280) | Exported Function | 0x00000001800219a4 | 0x000219a4
`private: static unsigned long CIlW2kDynWs2_32::m_RefCountgetnameinfo` | 641 (0x281) | Exported Function | 0x0000000180021948 | 0x00021948
`private: static void (__cdecl* __ptr64 CIlW2kDynWs2_32::m_freeaddrinfo)(struct addrinfo * __ptr64)` | 668 (0x29c) | Exported Function | 0x0000000180021b38 | 0x00021b38
`private: static void * __ptr64 (__cdecl* __ptr64 CIlNt4Advapi32::m_LockServiceDatabase)(struct SC_HANDLE__ * __ptr64)` | 565 (0x235) | Exported Function | 0x0000000180021ba0 | 0x00021ba0
`private: static void * __ptr64 (__cdecl* __ptr64 CIlNt4Kernel32::m_CreateToolhelp32Snapshot)(unsigned long,unsigned long)` | 557 (0x22d) | Exported Function | 0x0000000180021c30 | 0x00021c30
`private: static void * __ptr64 (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiCreateDeviceInfoListExW)(struct _GUID const * __ptr64,struct HWND__ * __ptr64,unsigned short const * __ptr64,void * __ptr64)` | 646 (0x286) | Exported Function | 0x0000000180021bf0 | 0x00021bf0
`private: static void * __ptr64 (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiGetClassDevsExW)(struct _GUID const * __ptr64,unsigned short const * __ptr64,struct HWND__ * __ptr64,unsigned long,void * __ptr64,unsigned short const * __ptr64,void * __ptr64)` | 652 (0x28c) | Exported Function | 0x0000000180021ab0 | 0x00021ab0
`private: static void * __ptr64 (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupDiGetClassDevsW)(struct _GUID const * __ptr64,unsigned short const * __ptr64,struct HWND__ * __ptr64,unsigned long)` | 653 (0x28d) | Exported Function | 0x0000000180021ad0 | 0x00021ad0
`private: static void * __ptr64 (__cdecl* __ptr64 CIlNt4Setupapi::m_SetupOpenFileQueue)(void)` | 663 (0x297) | Exported Function | 0x0000000180021bd8 | 0x00021bd8
`private: static void * __ptr64 __cdecl CIlNt4Advapi32::IlLockServiceDatabase(struct SC_HANDLE__ * __ptr64)` | 268 (0x10c) | Exported Function | 0x0000000180002f20 | 0x00002f20
`private: static void * __ptr64 __cdecl CIlNt4Kernel32::IlCreateToolhelp32Snapshot(unsigned long,unsigned long)` | 257 (0x101) | Exported Function | 0x0000000180004690 | 0x00004690
`private: static void * __ptr64 __cdecl CIlNt4Setupapi::IlSetupDiCreateDeviceInfoListExW(struct _GUID const * __ptr64,struct HWND__ * __ptr64,unsigned short const * __ptr64,void * __ptr64)` | 298 (0x12a) | Exported Function | 0x0000000180005bd0 | 0x00005bd0
`private: static void * __ptr64 __cdecl CIlNt4Setupapi::IlSetupDiGetClassDevsExW(struct _GUID const * __ptr64,unsigned short const * __ptr64,struct HWND__ * __ptr64,unsigned long,void * __ptr64,unsigned short const * __ptr64,void * __ptr64)` | 304 (0x130) | Exported Function | 0x0000000180005d40 | 0x00005d40
`private: static void * __ptr64 __cdecl CIlNt4Setupapi::IlSetupDiGetClassDevsW(struct _GUID const * __ptr64,unsigned short const * __ptr64,struct HWND__ * __ptr64,unsigned long)` | 305 (0x131) | Exported Function | 0x0000000180005eb0 | 0x00005eb0
`private: static void * __ptr64 __cdecl CIlNt4Setupapi::IlSetupOpenFileQueue(void)` | 315 (0x13b) | Exported Function | 0x0000000180006b90 | 0x00006b90
`private: static void __cdecl CIlW2kDynWs2_32::Ilfreeaddrinfo(struct addrinfo * __ptr64)` | 327 (0x147) | Exported Function | 0x0000000180008890 | 0x00008890
`protected: __cdecl CDynLib::CDynLib(void) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180001c60 | 0x00001c60
`protected: __int64 (__cdecl*__cdecl CDynLib::GetIlProc(unsigned short const * __ptr64,char const * __ptr64,__int64 (__cdecl*)(void),__int64 (__cdecl*& __ptr64)(void),unsigned long & __ptr64) __ptr64)(void)` | 204 (0xcc) | Exported Function | 0x0000000180001c80 | 0x00001c80
`protected: void __cdecl CDynLib::ReleaseProc(__int64 (__cdecl*& __ptr64)(void),unsigned long & __ptr64) __ptr64` | 382 (0x17e) | Exported Function | 0x0000000180001d20 | 0x00001d20
`private: static unsigned long CIlW2kDynWs2_32::m_RefCountfreeaddrinfo` | 639 (0x27f) | Exported Function | 0x0000000180021b1c | 0x00021b1c
`public: __cdecl CIlAdvapi32::CIlAdvapi32(class CIlAdvapi32 && __ptr64) __ptr64` | 2 (0x2) | Exported Function | 0x0000000180001c30 | 0x00001c30
`private: static unsigned long CIlNt6Userenv::m_RefCountCreateProfile` | 587 (0x24b) | Exported Function | 0x0000000180021a20 | 0x00021a20
`private: static unsigned long CIlNt4User32::m_RefCountLockSetForegroundWindow` | 598 (0x256) | Exported Function | 0x0000000180021960 | 0x00021960
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiDestroyDeviceInfoList` | 618 (0x26a) | Exported Function | 0x00000001800219d0 | 0x000219d0
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiDestroyDriverInfoList` | 619 (0x26b) | Exported Function | 0x0000000180021c20 | 0x00021c20
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiEnumDeviceInfo` | 620 (0x26c) | Exported Function | 0x0000000180021bb0 | 0x00021bb0
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiEnumDeviceInterfaces` | 621 (0x26d) | Exported Function | 0x0000000180021a08 | 0x00021a08
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiEnumDriverInfoW` | 622 (0x26e) | Exported Function | 0x0000000180021a1c | 0x00021a1c
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiGetClassDevsExW` | 623 (0x26f) | Exported Function | 0x0000000180021a30 | 0x00021a30
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiGetClassDevsW` | 624 (0x270) | Exported Function | 0x00000001800219f8 | 0x000219f8
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiGetDeviceInstallParamsW` | 625 (0x271) | Exported Function | 0x0000000180021c28 | 0x00021c28
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiGetDeviceInterfaceDetailW` | 626 (0x272) | Exported Function | 0x0000000180021a38 | 0x00021a38
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiGetDeviceRegistryPropertyW` | 627 (0x273) | Exported Function | 0x0000000180021984 | 0x00021984
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiGetDriverInfoDetailW` | 628 (0x274) | Exported Function | 0x0000000180021a24 | 0x00021a24
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiOpenDeviceInfoW` | 630 (0x276) | Exported Function | 0x0000000180021a70 | 0x00021a70
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiOpenDevRegKey` | 629 (0x275) | Exported Function | 0x0000000180021aa8 | 0x00021aa8
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiSetDeviceInstallParamsW` | 631 (0x277) | Exported Function | 0x0000000180021c24 | 0x00021c24
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiSetSelectedDriverW` | 632 (0x278) | Exported Function | 0x0000000180021a34 | 0x00021a34
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupGetInfInformationW` | 633 (0x279) | Exported Function | 0x0000000180021c4c | 0x00021c4c
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupOpenFileQueue` | 634 (0x27a) | Exported Function | 0x0000000180021ae0 | 0x00021ae0
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupQueryInfOriginalFileInformationW` | 635 (0x27b) | Exported Function | 0x0000000180021b64 | 0x00021b64
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupScanFileQueueW` | 636 (0x27c) | Exported Function | 0x0000000180021ac8 | 0x00021ac8
`private: static unsigned long CIlNt4Userenv::m_RefCountCreateUserProfileExW` | 590 (0x24e) | Exported Function | 0x0000000180021aac | 0x00021aac
`public: __cdecl CIlAdvapi32::CIlAdvapi32(class CIlAdvapi32 const & __ptr64) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180001c30 | 0x00001c30
`public: __cdecl CIlAdvapi32::CIlAdvapi32(void) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180001c30 | 0x00001c30
`public: __cdecl CIlDeplorch::CIlDeplorch(class CIlDeplorch && __ptr64) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180003590 | 0x00003590
`public: __cdecl CIlNt4User32::CIlNt4User32(class CIlNt4User32 const & __ptr64) __ptr64` | 29 (0x1d) | Exported Function | 0x0000000180007ba0 | 0x00007ba0
`public: __cdecl CIlNt4User32::CIlNt4User32(void) __ptr64` | 30 (0x1e) | Exported Function | 0x0000000180007b80 | 0x00007b80
`public: __cdecl CIlNt4Userenv::CIlNt4Userenv(class CIlNt4Userenv && __ptr64) __ptr64` | 31 (0x1f) | Exported Function | 0x0000000180007d50 | 0x00007d50
`public: __cdecl CIlNt4Userenv::CIlNt4Userenv(class CIlNt4Userenv const & __ptr64) __ptr64` | 32 (0x20) | Exported Function | 0x0000000180007d50 | 0x00007d50
`public: __cdecl CIlNt4Userenv::CIlNt4Userenv(void) __ptr64` | 33 (0x21) | Exported Function | 0x0000000180007d30 | 0x00007d30
`public: __cdecl CIlNt6Userenv::CIlNt6Userenv(class CIlNt6Userenv && __ptr64) __ptr64` | 34 (0x22) | Exported Function | 0x0000000180007ee0 | 0x00007ee0
`public: __cdecl CIlNt6Userenv::CIlNt6Userenv(class CIlNt6Userenv const & __ptr64) __ptr64` | 35 (0x23) | Exported Function | 0x0000000180007ee0 | 0x00007ee0
`public: __cdecl CIlNt6Userenv::CIlNt6Userenv(void) __ptr64` | 36 (0x24) | Exported Function | 0x0000000180007ec0 | 0x00007ec0
`public: __cdecl CIlOle32::CIlOle32(class CIlOle32 && __ptr64) __ptr64` | 37 (0x25) | Exported Function | 0x00000001800059d0 | 0x000059d0
`public: __cdecl CIlOle32::CIlOle32(class CIlOle32 const & __ptr64) __ptr64` | 38 (0x26) | Exported Function | 0x00000001800059d0 | 0x000059d0
`public: __cdecl CIlOle32::CIlOle32(void) __ptr64` | 39 (0x27) | Exported Function | 0x00000001800059d0 | 0x000059d0
`public: __cdecl CIlOleaut32::CIlOleaut32(class CIlOleaut32 && __ptr64) __ptr64` | 40 (0x28) | Exported Function | 0x0000000180005a10 | 0x00005a10
`public: __cdecl CIlOleaut32::CIlOleaut32(class CIlOleaut32 const & __ptr64) __ptr64` | 41 (0x29) | Exported Function | 0x0000000180005a10 | 0x00005a10
`public: __cdecl CIlOleaut32::CIlOleaut32(void) __ptr64` | 42 (0x2a) | Exported Function | 0x0000000180005a10 | 0x00005a10
`public: __cdecl CIlSetupapi::CIlSetupapi(class CIlSetupapi && __ptr64) __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180005b70 | 0x00005b70
`public: __cdecl CIlSetupapi::CIlSetupapi(class CIlSetupapi const & __ptr64) __ptr64` | 44 (0x2c) | Exported Function | 0x0000000180005b70 | 0x00005b70
`public: __cdecl CIlSetupapi::CIlSetupapi(void) __ptr64` | 45 (0x2d) | Exported Function | 0x0000000180005b70 | 0x00005b70
`public: __cdecl CIlShell32::CIlShell32(class CIlShell32 && __ptr64) __ptr64` | 46 (0x2e) | Exported Function | 0x0000000180007980 | 0x00007980
`public: __cdecl CIlShell32::CIlShell32(class CIlShell32 const & __ptr64) __ptr64` | 47 (0x2f) | Exported Function | 0x0000000180007980 | 0x00007980
`public: __cdecl CIlNt4User32::CIlNt4User32(class CIlNt4User32 && __ptr64) __ptr64` | 28 (0x1c) | Exported Function | 0x0000000180007ba0 | 0x00007ba0
`public: __cdecl CIlNt4Setupapi::CIlNt4Setupapi(void) __ptr64` | 27 (0x1b) | Exported Function | 0x00000001800078e0 | 0x000078e0
`public: __cdecl CIlNt4Setupapi::CIlNt4Setupapi(class CIlNt4Setupapi const & __ptr64) __ptr64` | 26 (0x1a) | Exported Function | 0x0000000180007900 | 0x00007900
`public: __cdecl CIlNt4Setupapi::CIlNt4Setupapi(class CIlNt4Setupapi && __ptr64) __ptr64` | 25 (0x19) | Exported Function | 0x0000000180007900 | 0x00007900
`public: __cdecl CIlDeplorch::CIlDeplorch(class CIlDeplorch const & __ptr64) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180003590 | 0x00003590
`public: __cdecl CIlDeplorch::CIlDeplorch(void) __ptr64` | 7 (0x7) | Exported Function | 0x0000000180003590 | 0x00003590
`public: __cdecl CIlIphlpapi::CIlIphlpapi(class CIlIphlpapi && __ptr64) __ptr64` | 8 (0x8) | Exported Function | 0x00000001800035d0 | 0x000035d0
`public: __cdecl CIlIphlpapi::CIlIphlpapi(class CIlIphlpapi const & __ptr64) __ptr64` | 9 (0x9) | Exported Function | 0x00000001800035d0 | 0x000035d0
`public: __cdecl CIlIphlpapi::CIlIphlpapi(void) __ptr64` | 10 (0xa) | Exported Function | 0x00000001800035d0 | 0x000035d0
`public: __cdecl CIlKernel32::CIlKernel32(class CIlKernel32 const & __ptr64) __ptr64` | 11 (0xb) | Exported Function | 0x00000001800035f0 | 0x000035f0
`public: __cdecl CIlKernel32::CIlKernel32(void) __ptr64` | 12 (0xc) | Exported Function | 0x00000001800035f0 | 0x000035f0
`public: __cdecl CIlKernel32::~CIlKernel32(void) __ptr64` | 64 (0x40) | Exported Function | 0x0000000180003610 | 0x00003610
`public: __cdecl CIlMuisetupapi::CIlMuisetupapi(class CIlMuisetupapi && __ptr64) __ptr64` | 13 (0xd) | Exported Function | 0x0000000180008a10 | 0x00008a10
`private: static unsigned long CIlNt4Setupapi::m_RefCountSetupDiCallClassInstaller` | 616 (0x268) | Exported Function | 0x0000000180021a88 | 0x00021a88
`public: __cdecl CIlMuisetupapi::CIlMuisetupapi(class CIlMuisetupapi const & __ptr64) __ptr64` | 14 (0xe) | Exported Function | 0x0000000180008a10 | 0x00008a10
`public: __cdecl CIlNt4Advapi32::CIlNt4Advapi32(class CIlNt4Advapi32 && __ptr64) __ptr64` | 16 (0x10) | Exported Function | 0x00000001800034e0 | 0x000034e0
`public: __cdecl CIlNt4Advapi32::CIlNt4Advapi32(class CIlNt4Advapi32 const & __ptr64) __ptr64` | 17 (0x11) | Exported Function | 0x00000001800034e0 | 0x000034e0
`public: __cdecl CIlNt4Advapi32::CIlNt4Advapi32(void) __ptr64` | 18 (0x12) | Exported Function | 0x00000001800034c0 | 0x000034c0
`public: __cdecl CIlNt4Kernel32::CIlNt4Kernel32(class CIlNt4Kernel32 && __ptr64) __ptr64` | 19 (0x13) | Exported Function | 0x0000000180004c20 | 0x00004c20
`public: __cdecl CIlNt4Kernel32::CIlNt4Kernel32(class CIlNt4Kernel32 const & __ptr64) __ptr64` | 20 (0x14) | Exported Function | 0x0000000180004c20 | 0x00004c20
`public: __cdecl CIlNt4Kernel32::CIlNt4Kernel32(void) __ptr64` | 21 (0x15) | Exported Function | 0x0000000180004c00 | 0x00004c00
`public: __cdecl CIlNt4Netapi32::CIlNt4Netapi32(class CIlNt4Netapi32 && __ptr64) __ptr64` | 22 (0x16) | Exported Function | 0x0000000180005890 | 0x00005890
`public: __cdecl CIlNt4Netapi32::CIlNt4Netapi32(class CIlNt4Netapi32 const & __ptr64) __ptr64` | 23 (0x17) | Exported Function | 0x0000000180005890 | 0x00005890
`public: __cdecl CIlNt4Netapi32::CIlNt4Netapi32(void) __ptr64` | 24 (0x18) | Exported Function | 0x0000000180005870 | 0x00005870
`public: __cdecl CIlMuisetupapi::CIlMuisetupapi(void) __ptr64` | 15 (0xf) | Exported Function | 0x0000000180008a10 | 0x00008a10
`struct IWs2_32Interface * __ptr64 __ptr64 g_Ws2_32` | 475 (0x1db) | Exported Function | 0x0000000180021020 | 0x00021020


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/6d0a394840b5191ccf8b0f33dc584d2ac986d99eb72f339624ba7b5f335d2d6b/detection/





MIT License. Copyright (c) 2020 Strontic.


