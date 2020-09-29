---
title: Tabbtn.dll | Microsoft Tablet PC Buttons Component
excerpt: What is Tabbtn.dll?
---

# Tabbtn.dll 

* File Path: `C:\Windows\system32\Tabbtn.dll`
* Description: Microsoft Tablet PC Buttons Component

## Hashes

Type | Hash
-- | --
MD5 | `DB931BCBB03F78ECD39A793BA37201C4`
SHA1 | `9F4CB9A7916366C71C07DB6446C2FCBFDAB4BF38`
SHA256 | `D19342E870809BCF20D3BAC6BB7C92CA86253DF615DBEA835F2040E6E5A94391`
SHA384 | `A70D983D5E9CD77CC006786374D27F64CE139094E064F799AB808D6F9CA81BBAD379A73ACAA06067CD88C7E4FB062C83`
SHA512 | `2B5A1D336F6AC53B012C316BBB6E575E603D19741A912150F55A1E2F96DF517062978D08E6635E6CE7588C4CABAAFED4701609A075A7E6A55856F29B5C3BD721`
SSDEEP | `3072:bFBCfzl3PvkM3BOdLD/JevD4VioEzvkYPzatZlrq:bzCfh3Pp3E1/Jeo2La`
IMP | `05F14CA8ECCF97464CDC7F83CD8A9AE5`
PESHA1 | `FF0156C09AD54270FB4C43192530A3302B1D839F`
PE256 | `57E1559716753D2B0F985565EEF1220FC93D5686A8FEC317DBF85ED325114041`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`HandleTabletButtonMessages` | 127 (0x7f) | Exported Function | 0x0000000180001010 | 0x00001010
`public: int __cdecl CButtonSettings::GetButtonCount(void)const __ptr64` | 88 (0x58) | Exported Function | 0x0000000180009890 | 0x00009890
`public: int __cdecl CButtonSettings::ShouldButtonShowUI(int)const __ptr64` | 214 (0xd6) | Exported Function | 0x000000018000c9b0 | 0x0000c9b0
`public: int __cdecl CHidButton::UnregisterHidBtnDevice(struct _hidbtndev * __ptr64,unsigned long * __ptr64) __ptr64` | 220 (0xdc) | Exported Function | 0x0000000180008b30 | 0x00008b30
`public: long __cdecl CActions::Init(void) __ptr64` | 130 (0x82) | Exported Function | 0x000000018000a340 | 0x0000a340
`public: long __cdecl CButtonAction::Clone(class CButtonAction * __ptr64 * __ptr64)const __ptr64` | 66 (0x42) | Exported Function | 0x00000001800092e0 | 0x000092e0
`public: long __cdecl CButtonAction::Set(class CButtonAction const * __ptr64) __ptr64` | 202 (0xca) | Exported Function | 0x000000018000c740 | 0x0000c740
`public: long __cdecl CButtonAction::SetData(unsigned char * __ptr64 const,unsigned long) __ptr64` | 209 (0xd1) | Exported Function | 0x000000018000c820 | 0x0000c820
`public: long __cdecl CButtonAction::SetDataDWORD(unsigned long) __ptr64` | 210 (0xd2) | Exported Function | 0x000000018000c8d0 | 0x0000c8d0
`public: long __cdecl CButtonConfig::Init(int) __ptr64` | 131 (0x83) | Exported Function | 0x000000018000a700 | 0x0000a700
`public: long __cdecl CButtonConfig::LoadSettings(void) __ptr64` | 144 (0x90) | Exported Function | 0x000000018000ac30 | 0x0000ac30
`public: long __cdecl CButtonConfig::RegReadButtonSetting(struct HKEY__ * __ptr64,int,int) __ptr64` | 172 (0xac) | Exported Function | 0x000000018000b8b0 | 0x0000b8b0
`public: int __cdecl CButtonAction::IsSameAction(class CButtonAction const * __ptr64)const __ptr64` | 142 (0x8e) | Exported Function | 0x000000018000aae0 | 0x0000aae0
`public: long __cdecl CButtonConfig::RegReadButtonsSettings(void) __ptr64` | 173 (0xad) | Exported Function | 0x000000018000bce0 | 0x0000bce0
`public: long __cdecl CButtonConfig::RegReadOrientationSeq(void) __ptr64` | 175 (0xaf) | Exported Function | 0x000000018000bf70 | 0x0000bf70
`public: long __cdecl CButtonConfig::SaveSettings(void) __ptr64` | 198 (0xc6) | Exported Function | 0x000000018000c2a0 | 0x0000c2a0
`public: long __cdecl CButtonConfig::UpdateButtonRates(void) __ptr64` | 221 (0xdd) | Exported Function | 0x000000018000ca90 | 0x0000ca90
`public: long __cdecl CButtonMonitor::Init(struct HWND__ * __ptr64) __ptr64` | 132 (0x84) | Exported Function | 0x0000000180004b80 | 0x00004b80
`public: long __cdecl CButtonMonitor::RegisterButtonDevices(void) __ptr64` | 176 (0xb0) | Exported Function | 0x0000000180001760 | 0x00001760
`public: long __cdecl CButtonMonitor::UnregisterButtonDevices(void) __ptr64` | 219 (0xdb) | Exported Function | 0x0000000180007d30 | 0x00007d30
`public: long __cdecl CButtonSetting::GetActionFromOrientation(unsigned long,class CButtonAction * __ptr64 * __ptr64,class CButtonAction * __ptr64 * __ptr64,class CButtonAction * __ptr64 * __ptr64) __ptr64` | 84 (0x54) | Exported Function | 0x0000000180009650 | 0x00009650
`public: long __cdecl CButtonSetting::MakeAllUserActionsEqual(unsigned long) __ptr64` | 146 (0x92) | Exported Function | 0x000000018000acc0 | 0x0000acc0
`public: long __cdecl CButtonSettings::GetButtonFromId(unsigned long,class CButtonSetting * __ptr64 * __ptr64) __ptr64` | 89 (0x59) | Exported Function | 0x00000001800098d0 | 0x000098d0
`public: long __cdecl CButtonSettings::GetButtonIds(unsigned long * __ptr64,int)const __ptr64` | 91 (0x5b) | Exported Function | 0x00000001800099c0 | 0x000099c0
`public: long __cdecl CFunctionNotification::Hide(void) __ptr64` | 128 (0x80) | Exported Function | 0x000000018000d5f0 | 0x0000d5f0
`public: long __cdecl CButtonConfig::RegReadDisplayOrientations(void) __ptr64` | 174 (0xae) | Exported Function | 0x0000000180001330 | 0x00001330
`public: long __cdecl CFunctionNotification::Show(void) __ptr64` | 216 (0xd8) | Exported Function | 0x000000018000d700 | 0x0000d700
`public: int __cdecl CButtonAction::CanRepeat(void)const __ptr64` | 65 (0x41) | Exported Function | 0x0000000180009280 | 0x00009280
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::SetAtIndex(int,unsigned long const & __ptr64,class CButtonImages * __ptr64 const & __ptr64) __ptr64` | 208 (0xd0) | Exported Function | 0x00000001800076c0 | 0x000076c0
`public: int __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::Find(class CButtonSetting * __ptr64 const & __ptr64)const __ptr64` | 75 (0x4b) | Exported Function | 0x0000000180004a10 | 0x00004a10
`public: int __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::GetSize(void)const __ptr64` | 122 (0x7a) | Exported Function | 0x0000000180004b20 | 0x00004b20
`public: int __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::Remove(class CButtonSetting * __ptr64 const & __ptr64) __ptr64` | 183 (0xb7) | Exported Function | 0x0000000180006f60 | 0x00006f60
`public: int __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::RemoveAt(int) __ptr64` | 193 (0xc1) | Exported Function | 0x0000000180007070 | 0x00007070
`public: int __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::SetAtIndex(int,class CButtonSetting * __ptr64 const & __ptr64) __ptr64` | 206 (0xce) | Exported Function | 0x0000000180007690 | 0x00007690
`public: int __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::Add(class COrientation * __ptr64 const & __ptr64) __ptr64` | 63 (0x3f) | Exported Function | 0x00000001800042d0 | 0x000042d0
`public: int __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::Find(class COrientation * __ptr64 const & __ptr64)const __ptr64` | 76 (0x4c) | Exported Function | 0x0000000180004a10 | 0x00004a10
`public: int __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::GetSize(void)const __ptr64` | 123 (0x7b) | Exported Function | 0x0000000180004b20 | 0x00004b20
`public: int __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::Remove(class COrientation * __ptr64 const & __ptr64) __ptr64` | 184 (0xb8) | Exported Function | 0x0000000180006f60 | 0x00006f60
`public: int __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::RemoveAt(int) __ptr64` | 194 (0xc2) | Exported Function | 0x0000000180007070 | 0x00007070
`public: int __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::SetAtIndex(int,class COrientation * __ptr64 const & __ptr64) __ptr64` | 207 (0xcf) | Exported Function | 0x0000000180007690 | 0x00007690
`public: int __cdecl CActions::GetCount(void) __ptr64` | 94 (0x5e) | Exported Function | 0x0000000180009bc0 | 0x00009bc0
`public: int __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::Add(struct ACTION * __ptr64 const & __ptr64) __ptr64` | 60 (0x3c) | Exported Function | 0x00000001800042d0 | 0x000042d0
`public: int __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::GetSize(void)const __ptr64` | 120 (0x78) | Exported Function | 0x0000000180004b20 | 0x00004b20
`public: int __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::Remove(struct ACTION * __ptr64 const & __ptr64) __ptr64` | 181 (0xb5) | Exported Function | 0x0000000180006f60 | 0x00006f60
`public: int __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::RemoveAt(int) __ptr64` | 191 (0xbf) | Exported Function | 0x0000000180007070 | 0x00007070
`public: int __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::SetAtIndex(int,struct ACTION * __ptr64 const & __ptr64) __ptr64` | 204 (0xcc) | Exported Function | 0x0000000180007690 | 0x00007690
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::Add(unsigned long const & __ptr64,class CButtonImages * __ptr64 const & __ptr64) __ptr64` | 64 (0x40) | Exported Function | 0x0000000180004370 | 0x00004370
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::FindKey(unsigned long const & __ptr64)const __ptr64` | 79 (0x4f) | Exported Function | 0x0000000180004a50 | 0x00004a50
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::FindVal(class CButtonImages * __ptr64 const & __ptr64)const __ptr64` | 81 (0x51) | Exported Function | 0x0000000180004a90 | 0x00004a90
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::GetSize(void)const __ptr64` | 124 (0x7c) | Exported Function | 0x0000000180004b30 | 0x00004b30
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::Remove(unsigned long const & __ptr64) __ptr64` | 185 (0xb9) | Exported Function | 0x0000000180006fa0 | 0x00006fa0
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::RemoveAt(int) __ptr64` | 195 (0xc3) | Exported Function | 0x0000000180007120 | 0x00007120
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::SetAt(unsigned long const & __ptr64,class CButtonImages * __ptr64 const & __ptr64) __ptr64` | 203 (0xcb) | Exported Function | 0x0000000180007630 | 0x00007630
`public: int __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::Find(struct ACTION * __ptr64 const & __ptr64)const __ptr64` | 73 (0x49) | Exported Function | 0x0000000180004a10 | 0x00004a10
`public: long __cdecl CHidButton::DispatchHidBtnEvents(struct HRAWINPUT__ * __ptr64) __ptr64` | 69 (0x45) | Exported Function | 0x00000001800081b0 | 0x000081b0
`public: long __cdecl COrientation::Init(struct HKEY__ * __ptr64) __ptr64` | 133 (0x85) | Exported Function | 0x000000018000a7c0 | 0x0000a7c0
`public: static __int64 __cdecl CFunctionNotification::WindowProc(struct HWND__ * __ptr64,unsigned int,unsigned __int64,__int64)` | 224 (0xe0) | Exported Function | 0x000000018000d910 | 0x0000d910
`public: unsigned long __cdecl COrientation::GetDefSeq(void) __ptr64` | 102 (0x66) | Exported Function | 0x0000000180009d00 | 0x00009d00
`public: unsigned long __cdecl COrientation::GetMode(void) __ptr64` | 115 (0x73) | Exported Function | 0x000000018000a1b0 | 0x0000a1b0
`public: unsigned long const __cdecl CButtonAction::GetDataDWORD(void)const __ptr64` | 101 (0x65) | Exported Function | 0x0000000180009c90 | 0x00009c90
`public: unsigned short const * __ptr64 __cdecl CButtonConfig::GetDisplayOrientationName(unsigned long) __ptr64` | 106 (0x6a) | Exported Function | 0x0000000180009ed0 | 0x00009ed0
`public: unsigned short const * __ptr64 __cdecl CButtonSetting::GetAllowedActions(void) __ptr64` | 85 (0x55) | Exported Function | 0x0000000180009810 | 0x00009810
`public: unsigned short const * __ptr64 __cdecl CButtonSetting::GetButtonName(void) __ptr64` | 92 (0x5c) | Exported Function | 0x0000000180009a70 | 0x00009a70
`public: unsigned short const * __ptr64 __cdecl CButtonSetting::GetDisallowedActions(void) __ptr64` | 105 (0x69) | Exported Function | 0x0000000180009e90 | 0x00009e90
`public: unsigned short const * __ptr64 __cdecl CButtonSettings::GetButtonName(int)const __ptr64` | 93 (0x5d) | Exported Function | 0x0000000180009b50 | 0x00009b50
`public: unsigned short const * __ptr64 __cdecl COrientation::GetDescription(void) __ptr64` | 103 (0x67) | Exported Function | 0x0000000180009d40 | 0x00009d40
`public: unsigned short const * __ptr64 __cdecl COrientation::GetKeyName(void) __ptr64` | 113 (0x71) | Exported Function | 0x000000018000a070 | 0x0000a070
`public: void __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::InternalSetAtIndex(int,class CButtonAction * __ptr64 const & __ptr64) __ptr64` | 136 (0x88) | Exported Function | 0x0000000180004c60 | 0x00004c60
`public: unsigned long __cdecl CButtonSettings::GetFnKeyButtonId(void) __ptr64` | 108 (0x6c) | Exported Function | 0x0000000180009fb0 | 0x00009fb0
`public: void __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::RemoveAll(void) __ptr64` | 187 (0xbb) | Exported Function | 0x0000000180006fe0 | 0x00006fe0
`public: void __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::RemoveAll(void) __ptr64` | 188 (0xbc) | Exported Function | 0x0000000180006fe0 | 0x00006fe0
`public: void __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::InternalSetAtIndex(int,class COrientation * __ptr64 const & __ptr64) __ptr64` | 138 (0x8a) | Exported Function | 0x0000000180004c60 | 0x00004c60
`public: void __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::RemoveAll(void) __ptr64` | 189 (0xbd) | Exported Function | 0x0000000180006fe0 | 0x00006fe0
`public: void __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::InternalSetAtIndex(int,struct ACTION * __ptr64 const & __ptr64) __ptr64` | 135 (0x87) | Exported Function | 0x0000000180004c60 | 0x00004c60
`public: void __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::RemoveAll(void) __ptr64` | 186 (0xba) | Exported Function | 0x0000000180006fe0 | 0x00006fe0
`public: void __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::InternalSetAtIndex(int,unsigned long const & __ptr64,class CButtonImages * __ptr64 const & __ptr64) __ptr64` | 139 (0x8b) | Exported Function | 0x0000000180004c80 | 0x00004c80
`public: void __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::RemoveAll(void) __ptr64` | 190 (0xbe) | Exported Function | 0x0000000180007020 | 0x00007020
`public: void __cdecl CButtonAction::FreeData(void) __ptr64` | 82 (0x52) | Exported Function | 0x0000000180009520 | 0x00009520
`public: void __cdecl CButtonAction::SetId(unsigned long) __ptr64` | 213 (0xd5) | Exported Function | 0x000000018000c960 | 0x0000c960
`public: void __cdecl CButtonConfig::RegReadActions(struct HKEY__ * __ptr64,class CButtonSetting * __ptr64,int) __ptr64` | 170 (0xaa) | Exported Function | 0x000000018000aff0 | 0x0000aff0
`public: void __cdecl CButtonConfig::UpdateCurrentDisplayOrientation(void) __ptr64` | 222 (0xde) | Exported Function | 0x000000018000cbc0 | 0x0000cbc0
`public: void __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::InternalSetAtIndex(int,class CButtonSetting * __ptr64 const & __ptr64) __ptr64` | 137 (0x89) | Exported Function | 0x0000000180004c60 | 0x00004c60
`public: unsigned long __cdecl CButtonSettings::GetButtonIdFromIndex(unsigned long) __ptr64` | 90 (0x5a) | Exported Function | 0x0000000180009990 | 0x00009990
`public: unsigned long __cdecl CButtonSetting::GetId(void) __ptr64` | 111 (0x6f) | Exported Function | 0x000000018000a030 | 0x0000a030
`public: unsigned long __cdecl CButtonSetting::GetFlags(void) __ptr64` | 107 (0x6b) | Exported Function | 0x0000000180009f70 | 0x00009f70
`public: static int __cdecl CButtonAction::IsActionRepeatable(unsigned long)` | 140 (0x8c) | Exported Function | 0x000000018000a940 | 0x0000a940
`public: static int __cdecl CButtonMonitor::IsActionUnsupported(unsigned long)` | 141 (0x8d) | Exported Function | 0x0000000180004cb0 | 0x00004cb0
`public: static long __cdecl CButtonConfig::RegReadAndAllocate(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64,unsigned char * __ptr64 * __ptr64,unsigned long * __ptr64)` | 171 (0xab) | Exported Function | 0x000000018000b670 | 0x0000b670
`public: static long __cdecl CButtonMonitor::CreateExtendedActionObject(struct IUnknown * __ptr64 * __ptr64)` | 67 (0x43) | Exported Function | 0x0000000180001470 | 0x00001470
`public: static unsigned long CButtonMonitor::sm_dwPopupCount` | 225 (0xe1) | Exported Function | 0x00000001800269f8 | 0x000269f8
`public: static void __cdecl CButtonMonitor::WinEventProc(struct HWINEVENTHOOK__ * __ptr64,unsigned long,struct HWND__ * __ptr64,long,long,unsigned long,unsigned long)` | 223 (0xdf) | Exported Function | 0x0000000180007de0 | 0x00007de0
`public: struct _hidbtndev * __ptr64 __cdecl CHidButton::FindDeviceByHandle(void * __ptr64) __ptr64` | 78 (0x4e) | Exported Function | 0x0000000180008580 | 0x00008580
`public: struct _hidbtndev * __ptr64 __cdecl CHidButton::RegisterHidBtnDevice(void * __ptr64,unsigned long * __ptr64) __ptr64` | 178 (0xb2) | Exported Function | 0x00000001800087d0 | 0x000087d0
`public: struct ACTION * __ptr64 & __ptr64 __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::operator[](int) __ptr64` | 52 (0x34) | Exported Function | 0x00000001800042a0 | 0x000042a0
`public: struct ACTION * __ptr64 * __ptr64 __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::GetData(void)const __ptr64` | 96 (0x60) | Exported Function | 0x0000000180004ae0 | 0x00004ae0
`public: struct ACTION * __ptr64 __cdecl CActions::FindActionById(unsigned long) __ptr64` | 77 (0x4d) | Exported Function | 0x0000000180009460 | 0x00009460
`public: struct ACTION * __ptr64 __cdecl CActions::GetActionAt(int) __ptr64` | 83 (0x53) | Exported Function | 0x00000001800095e0 | 0x000095e0
`public: struct ACTION * __ptr64 const & __ptr64 __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::operator[](int)const __ptr64` | 53 (0x35) | Exported Function | 0x00000001800042a0 | 0x000042a0
`public: struct HBITMAP__ * __ptr64 __cdecl CButtonSettings::GetDetailImage(unsigned long,unsigned long) __ptr64` | 104 (0x68) | Exported Function | 0x0000000180009d90 | 0x00009d90
`public: struct HBITMAP__ * __ptr64 __cdecl CButtonSettings::GetLocationImage(unsigned long,unsigned long) __ptr64` | 114 (0x72) | Exported Function | 0x000000018000a0b0 | 0x0000a0b0
`public: unsigned char * __ptr64 __cdecl CButtonAction::GetData(void)const __ptr64` | 100 (0x64) | Exported Function | 0x0000000180009c50 | 0x00009c50
`public: unsigned long & __ptr64 __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::GetKeyAt(int)const __ptr64` | 112 (0x70) | Exported Function | 0x0000000180004af0 | 0x00004af0
`public: unsigned long __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::ReverseLookup(class CButtonImages * __ptr64 const & __ptr64)const __ptr64` | 197 (0xc5) | Exported Function | 0x0000000180007280 | 0x00007280
`public: unsigned long __cdecl CButtonAction::GetId(void)const __ptr64` | 110 (0x6e) | Exported Function | 0x0000000180009ff0 | 0x00009ff0
`public: unsigned long __cdecl CButtonAction::GetOrientationMode(void)const __ptr64` | 118 (0x76) | Exported Function | 0x000000018000a280 | 0x0000a280
`public: unsigned long __cdecl CButtonAction::GetRegType(void)const __ptr64` | 119 (0x77) | Exported Function | 0x000000018000a2c0 | 0x0000a2c0
`public: unsigned long __cdecl CButtonAction::GetSize(void)const __ptr64` | 125 (0x7d) | Exported Function | 0x000000018000a300 | 0x0000a300
`public: unsigned long __cdecl CButtonConfig::GetCurrentDisplayOrientation(void) __ptr64` | 95 (0x5f) | Exported Function | 0x0000000180009c00 | 0x00009c00
`public: unsigned long __cdecl CButtonConfig::GetOrientSeq(unsigned int)const __ptr64` | 116 (0x74) | Exported Function | 0x000000018000a1f0 | 0x0000a1f0
`public: unsigned long __cdecl CButtonConfig::GetOrientSeqCount(void)const __ptr64` | 117 (0x75) | Exported Function | 0x000000018000a240 | 0x0000a240
`public: int __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::Add(class CButtonSetting * __ptr64 const & __ptr64) __ptr64` | 62 (0x3e) | Exported Function | 0x00000001800042d0 | 0x000042d0
`public: void __cdecl CButtonMonitor::OnMessage(unsigned int,unsigned __int64,__int64) __ptr64` | 164 (0xa4) | Exported Function | 0x00000001800062b0 | 0x000062b0
`public: int __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::SetAtIndex(int,class CButtonAction * __ptr64 const & __ptr64) __ptr64` | 205 (0xcd) | Exported Function | 0x0000000180007690 | 0x00007690
`public: int __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::Remove(class CButtonAction * __ptr64 const & __ptr64) __ptr64` | 182 (0xb6) | Exported Function | 0x0000000180006f60 | 0x00006f60
`private: static long __cdecl CButtonMonitor::ShowWindowSwitchWindow(void)` | 217 (0xd9) | Exported Function | 0x0000000180007b50 | 0x00007b50
`private: static void __cdecl CButtonMonitor::SendModKeys(unsigned char,int)` | 200 (0xc8) | Exported Function | 0x00000001800074a0 | 0x000074a0
`private: static void __cdecl CButtonMonitor::SendVKey(unsigned char,unsigned char,int)` | 201 (0xc9) | Exported Function | 0x0000000180007520 | 0x00007520
`private: void __cdecl CButtonConfig::ResetDeprecatedAction(class CButtonAction * __ptr64) __ptr64` | 196 (0xc4) | Exported Function | 0x000000018000c180 | 0x0000c180
`private: void __cdecl CButtonMonitor::OnButtonDown(unsigned __int64,__int64) __ptr64` | 158 (0x9e) | Exported Function | 0x0000000180005bf0 | 0x00005bf0
`private: void __cdecl CButtonMonitor::OnButtonUp(unsigned __int64,__int64) __ptr64` | 159 (0x9f) | Exported Function | 0x0000000180005db0 | 0x00005db0
`private: void __cdecl CButtonMonitor::OnDisplayChange(unsigned __int64,__int64) __ptr64` | 160 (0xa0) | Exported Function | 0x0000000180005f20 | 0x00005f20
`private: void __cdecl CButtonMonitor::OnFnKeyTimer(void) __ptr64` | 161 (0xa1) | Exported Function | 0x0000000180005f60 | 0x00005f60
`private: void __cdecl CButtonMonitor::OnHoldTimer(void) __ptr64` | 162 (0xa2) | Exported Function | 0x0000000180005fd0 | 0x00005fd0
`private: void __cdecl CButtonMonitor::OnInput(unsigned __int64,__int64) __ptr64` | 163 (0xa3) | Exported Function | 0x00000001800061e0 | 0x000061e0
`private: void __cdecl CButtonMonitor::OnRepeatTimer(void) __ptr64` | 165 (0xa5) | Exported Function | 0x00000001800063a0 | 0x000063a0
`private: long __cdecl CFunctionNotification::CreateTrayWindow(void) __ptr64` | 68 (0x44) | Exported Function | 0x000000018000d500 | 0x0000d500
`private: void __cdecl CButtonMonitor::OnSettingChange(unsigned __int64,__int64) __ptr64` | 166 (0xa6) | Exported Function | 0x0000000180006520 | 0x00006520
`private: void __cdecl CButtonMonitor::SetDisplayPower(int) __ptr64` | 212 (0xd4) | Exported Function | 0x0000000180007a90 | 0x00007a90
`public: __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >(class ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> > const & __ptr64) __ptr64` | 3 (0x3) | Exported Function | 0x00000001800039c0 | 0x000039c0
`public: __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >(void) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180003a40 | 0x00003a40
`public: __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::~CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >(void) __ptr64` | 25 (0x19) | Exported Function | 0x0000000180003d50 | 0x00003d50
`public: __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >(class ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> > const & __ptr64) __ptr64` | 5 (0x5) | Exported Function | 0x00000001800039c0 | 0x000039c0
`public: __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >(void) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180003a40 | 0x00003a40
`public: __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::~CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >(void) __ptr64` | 26 (0x1a) | Exported Function | 0x0000000180003d50 | 0x00003d50
`public: __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >(class ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> > const & __ptr64) __ptr64` | 7 (0x7) | Exported Function | 0x00000001800039c0 | 0x000039c0
`public: __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >(void) __ptr64` | 8 (0x8) | Exported Function | 0x0000000180003a40 | 0x00003a40
`public: __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::~CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >(void) __ptr64` | 27 (0x1b) | Exported Function | 0x0000000180003d50 | 0x00003d50
`public: __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >(class ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> > const & __ptr64) __ptr64` | 1 (0x1) | Exported Function | 0x00000001800039c0 | 0x000039c0
`private: void __cdecl CButtonMonitor::OnTimer(unsigned __int64,__int64) __ptr64` | 167 (0xa7) | Exported Function | 0x00000001800065f0 | 0x000065f0
`public: __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >(void) __ptr64` | 2 (0x2) | Exported Function | 0x0000000180003a40 | 0x00003a40
`private: long __cdecl CButtonMonitor::SetDisplayOrientation(int) __ptr64` | 211 (0xd3) | Exported Function | 0x00000001800076f0 | 0x000076f0
`private: long __cdecl CButtonMonitor::ReleaseRepeatOrHoldButton(void) __ptr64` | 180 (0xb4) | Exported Function | 0x0000000180006e60 | 0x00006e60
`InitializeTabletButtons` | 134 (0x86) | Exported Function | 0x00000001800010f0 | 0x000010f0
`private: int __cdecl CButtonMonitor::InSession0(void) __ptr64` | 129 (0x81) | Exported Function | 0x0000000180004b70 | 0x00004b70
`private: int __cdecl CButtonMonitor::ShouldSendEscapeForBack(void) __ptr64` | 215 (0xd7) | Exported Function | 0x0000000180007b00 | 0x00007b00
`private: int __cdecl CButtonSettings::LoadImageDLL(void) __ptr64` | 143 (0x8f) | Exported Function | 0x000000018000ab70 | 0x0000ab70
`private: int __cdecl CHidButton::FindUsage(struct _USAGE_AND_PAGE * __ptr64,unsigned long,unsigned short,unsigned short) __ptr64` | 80 (0x50) | Exported Function | 0x00000001800085f0 | 0x000085f0
`private: int __cdecl CHidButton::GetHidBtnUsages(struct _hidbtndev * __ptr64,struct tagRAWINPUT * __ptr64,unsigned short,unsigned short,struct _USAGE_AND_PAGE * __ptr64,unsigned long * __ptr64) __ptr64` | 109 (0x6d) | Exported Function | 0x0000000180008670 | 0x00008670
`private: long __cdecl CButtonMonitor::DoBuiltInAction(class CButtonAction * __ptr64,int,int) __ptr64` | 70 (0x46) | Exported Function | 0x0000000180004460 | 0x00004460
`private: long __cdecl CButtonMonitor::DoButtonAction(class CButtonAction * __ptr64,unsigned long,int,int) __ptr64` | 71 (0x47) | Exported Function | 0x00000001800046f0 | 0x000046f0
`private: long __cdecl CButtonMonitor::ExecuteObject(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 72 (0x48) | Exported Function | 0x0000000180004990 | 0x00004990
`private: long __cdecl CButtonMonitor::NotifyFnMode(int) __ptr64` | 147 (0x93) | Exported Function | 0x0000000180004dd0 | 0x00004dd0
`private: long __cdecl CButtonMonitor::OnActionAppCommand(class CButtonAction * __ptr64,int,int) __ptr64` | 148 (0x94) | Exported Function | 0x0000000180004e90 | 0x00004e90
`private: long __cdecl CButtonMonitor::SendAppCommand(unsigned short) __ptr64` | 199 (0xc7) | Exported Function | 0x00000001800072b0 | 0x000072b0
`private: long __cdecl CButtonMonitor::OnActionContextMenu(class CButtonAction * __ptr64,int,int) __ptr64` | 149 (0x95) | Exported Function | 0x0000000180004fb0 | 0x00004fb0
`private: long __cdecl CButtonMonitor::OnActionLaunchApp(class CButtonAction * __ptr64,int,int) __ptr64` | 151 (0x97) | Exported Function | 0x0000000180005140 | 0x00005140
`private: long __cdecl CButtonMonitor::OnActionMouseWheel(class CButtonAction * __ptr64,int,int) __ptr64` | 152 (0x98) | Exported Function | 0x00000001800053d0 | 0x000053d0
`private: long __cdecl CButtonMonitor::OnActionSendKey(class CButtonAction * __ptr64,int,int) __ptr64` | 153 (0x99) | Exported Function | 0x0000000180005500 | 0x00005500
`private: long __cdecl CButtonMonitor::OnActionSetOrientation(class CButtonAction * __ptr64,int,int) __ptr64` | 154 (0x9a) | Exported Function | 0x0000000180005710 | 0x00005710
`private: long __cdecl CButtonMonitor::OnActionUnknown(class CButtonAction * __ptr64,int,int) __ptr64` | 155 (0x9b) | Exported Function | 0x0000000180005840 | 0x00005840
`private: long __cdecl CButtonMonitor::OnActionWindowsFlip(class CButtonAction * __ptr64,int,int) __ptr64` | 157 (0x9d) | Exported Function | 0x0000000180005b20 | 0x00005b20
`private: long __cdecl CButtonMonitor::OnActionWindowsFlip3d(class CButtonAction * __ptr64,int,int) __ptr64` | 156 (0x9c) | Exported Function | 0x0000000180005a30 | 0x00005a30
`private: long __cdecl CButtonMonitor::ProcessAction(unsigned long,int) __ptr64` | 168 (0xa8) | Exported Function | 0x00000001800066e0 | 0x000066e0
`private: long __cdecl CButtonMonitor::ProcessEvent(unsigned long,int) __ptr64` | 169 (0xa9) | Exported Function | 0x0000000180006ab0 | 0x00006ab0
`private: long __cdecl CButtonMonitor::RegisterForPopups(void) __ptr64` | 177 (0xb1) | Exported Function | 0x0000000180001680 | 0x00001680
`private: long __cdecl CButtonMonitor::ReleaseDownButtons(void) __ptr64` | 179 (0xb3) | Exported Function | 0x0000000180006d90 | 0x00006d90
`private: long __cdecl CButtonMonitor::OnActionDisplayOff(class CButtonAction * __ptr64,int,int) __ptr64` | 150 (0x96) | Exported Function | 0x0000000180005080 | 0x00005080
`public: __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::~CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >(void) __ptr64` | 24 (0x18) | Exported Function | 0x0000000180003d50 | 0x00003d50
`public: __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >(void) __ptr64` | 9 (0x9) | Exported Function | 0x0000000180003a60 | 0x00003a60
`public: __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::~CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >(void) __ptr64` | 28 (0x1c) | Exported Function | 0x0000000180003d60 | 0x00003d60
`public: class CButtonAction & __ptr64 __cdecl CButtonAction::operator=(class CButtonAction const & __ptr64) __ptr64` | 44 (0x2c) | Exported Function | 0x0000000180003f20 | 0x00003f20
`public: class CButtonAction * __ptr64 & __ptr64 __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::operator[](int) __ptr64` | 54 (0x36) | Exported Function | 0x00000001800042a0 | 0x000042a0
`public: class CButtonAction * __ptr64 * __ptr64 __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::GetData(void)const __ptr64` | 97 (0x61) | Exported Function | 0x0000000180004ae0 | 0x00004ae0
`public: class CButtonAction * __ptr64 const & __ptr64 __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::operator[](int)const __ptr64` | 55 (0x37) | Exported Function | 0x00000001800042a0 | 0x000042a0
`public: class CButtonConfig & __ptr64 __cdecl CButtonConfig::operator=(class CButtonConfig const & __ptr64) __ptr64` | 45 (0x2d) | Exported Function | 0x0000000180003f40 | 0x00003f40
`public: class CButtonConfig * __ptr64 __cdecl CButtonMonitor::GetButtonConfig(void) __ptr64` | 87 (0x57) | Exported Function | 0x0000000180004ad0 | 0x00004ad0
`public: class CButtonImages * __ptr64 & __ptr64 __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::GetValueAt(int)const __ptr64` | 126 (0x7e) | Exported Function | 0x0000000180004b40 | 0x00004b40
`public: class CButtonImages * __ptr64 __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::Lookup(unsigned long const & __ptr64)const __ptr64` | 145 (0x91) | Exported Function | 0x0000000180004d90 | 0x00004d90
`public: class CButtonMonitor & __ptr64 __cdecl CButtonMonitor::operator=(class CButtonMonitor const & __ptr64) __ptr64` | 46 (0x2e) | Exported Function | 0x0000000180003fd0 | 0x00003fd0
`public: class CButtonSetting & __ptr64 __cdecl CButtonSetting::operator=(class CButtonSetting const & __ptr64) __ptr64` | 47 (0x2f) | Exported Function | 0x0000000180004110 | 0x00004110
`public: class CButtonSetting * __ptr64 & __ptr64 __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::operator[](int) __ptr64` | 56 (0x38) | Exported Function | 0x00000001800042a0 | 0x000042a0
`public: class CActions & __ptr64 __cdecl CActions::operator=(class CActions const & __ptr64) __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180003f00 | 0x00003f00
`public: class CButtonSetting * __ptr64 * __ptr64 __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::GetData(void)const __ptr64` | 98 (0x62) | Exported Function | 0x0000000180004ae0 | 0x00004ae0
`public: class CButtonSettings & __ptr64 __cdecl CButtonSettings::operator=(class CButtonSettings const & __ptr64) __ptr64` | 48 (0x30) | Exported Function | 0x0000000180004190 | 0x00004190
`public: class CFunctionNotification & __ptr64 __cdecl CFunctionNotification::operator=(class CFunctionNotification const & __ptr64) __ptr64` | 49 (0x31) | Exported Function | 0x0000000180003ee0 | 0x00003ee0
`public: class CHidButton & __ptr64 __cdecl CHidButton::operator=(class CHidButton const & __ptr64) __ptr64` | 50 (0x32) | Exported Function | 0x00000001800041d0 | 0x000041d0
`public: class COrientation & __ptr64 __cdecl COrientation::operator=(class COrientation const & __ptr64) __ptr64` | 51 (0x33) | Exported Function | 0x0000000180004200 | 0x00004200
`public: class COrientation * __ptr64 & __ptr64 __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::operator[](int) __ptr64` | 58 (0x3a) | Exported Function | 0x00000001800042a0 | 0x000042a0
`public: class COrientation * __ptr64 * __ptr64 __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::GetData(void)const __ptr64` | 99 (0x63) | Exported Function | 0x0000000180004ae0 | 0x00004ae0
`public: class COrientation * __ptr64 const & __ptr64 __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::operator[](int)const __ptr64` | 59 (0x3b) | Exported Function | 0x00000001800042a0 | 0x000042a0
`public: enum BUTTONACTION_TYPE const __cdecl CButtonAction::GetButtonActionType(void)const __ptr64` | 86 (0x56) | Exported Function | 0x0000000180009850 | 0x00009850
`public: int __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::Add(class CButtonAction * __ptr64 const & __ptr64) __ptr64` | 61 (0x3d) | Exported Function | 0x00000001800042d0 | 0x000042d0
`public: int __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::Find(class CButtonAction * __ptr64 const & __ptr64)const __ptr64` | 74 (0x4a) | Exported Function | 0x0000000180004a10 | 0x00004a10
`public: int __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::GetSize(void)const __ptr64` | 121 (0x79) | Exported Function | 0x0000000180004b20 | 0x00004b20
`public: class CButtonSetting * __ptr64 const & __ptr64 __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::operator[](int)const __ptr64` | 57 (0x39) | Exported Function | 0x00000001800042a0 | 0x000042a0
`public: class ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> > & __ptr64 __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::operator=(class ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> > const & __ptr64) __ptr64` | 42 (0x2a) | Exported Function | 0x0000000180003ee0 | 0x00003ee0
`public: class ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> > & __ptr64 __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::operator=(class ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> > const & __ptr64) __ptr64` | 38 (0x26) | Exported Function | 0x0000000180003e40 | 0x00003e40
`public: class ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> > & __ptr64 __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::operator=(class ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> > const & __ptr64) __ptr64` | 41 (0x29) | Exported Function | 0x0000000180003e40 | 0x00003e40
`public: __cdecl CActions::CActions(class CActions const & __ptr64) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180003a80 | 0x00003a80
`public: __cdecl CActions::CActions(void) __ptr64` | 11 (0xb) | Exported Function | 0x0000000180003a40 | 0x00003a40
`public: __cdecl CActions::~CActions(void) __ptr64` | 29 (0x1d) | Exported Function | 0x0000000180008e10 | 0x00008e10
`public: __cdecl CButtonAction::CButtonAction(enum BUTTONACTION_TYPE) __ptr64` | 12 (0xc) | Exported Function | 0x0000000180008c10 | 0x00008c10
`public: __cdecl CButtonAction::~CButtonAction(void) __ptr64` | 30 (0x1e) | Exported Function | 0x0000000180008e80 | 0x00008e80
`public: __cdecl CButtonConfig::CButtonConfig(class CButtonConfig const & __ptr64) __ptr64` | 13 (0xd) | Exported Function | 0x0000000180003aa0 | 0x00003aa0
`public: __cdecl CButtonConfig::CButtonConfig(void) __ptr64` | 14 (0xe) | Exported Function | 0x0000000180008c70 | 0x00008c70
`public: __cdecl CButtonConfig::~CButtonConfig(void) __ptr64` | 31 (0x1f) | Exported Function | 0x0000000180008ec0 | 0x00008ec0
`public: __cdecl CButtonMonitor::CButtonMonitor(class CButtonMonitor const & __ptr64) __ptr64` | 15 (0xf) | Exported Function | 0x0000000180003b20 | 0x00003b20
`public: __cdecl CButtonMonitor::CButtonMonitor(void) __ptr64` | 16 (0x10) | Exported Function | 0x00000001800018a0 | 0x000018a0
`public: __cdecl CButtonMonitor::~CButtonMonitor(void) __ptr64` | 32 (0x20) | Exported Function | 0x0000000180003d70 | 0x00003d70
`public: __cdecl CButtonSetting::CButtonSetting(class CButtonSetting const & __ptr64) __ptr64` | 17 (0x11) | Exported Function | 0x0000000180003c60 | 0x00003c60
`public: __cdecl CButtonSetting::CButtonSetting(void) __ptr64` | 18 (0x12) | Exported Function | 0x0000000180008ce0 | 0x00008ce0
`public: __cdecl CButtonSetting::~CButtonSetting(void) __ptr64` | 33 (0x21) | Exported Function | 0x0000000180008fc0 | 0x00008fc0
`public: __cdecl CButtonSettings::CButtonSettings(class CButtonSettings const & __ptr64) __ptr64` | 19 (0x13) | Exported Function | 0x0000000180003ce0 | 0x00003ce0
`public: __cdecl CButtonSettings::CButtonSettings(void) __ptr64` | 20 (0x14) | Exported Function | 0x0000000180008d60 | 0x00008d60
`public: __cdecl CButtonSettings::~CButtonSettings(void) __ptr64` | 34 (0x22) | Exported Function | 0x0000000180009150 | 0x00009150
`public: __cdecl CFunctionNotification::CFunctionNotification(void) __ptr64` | 21 (0x15) | Exported Function | 0x000000018000d420 | 0x0000d420
`public: __cdecl CFunctionNotification::~CFunctionNotification(void) __ptr64` | 35 (0x23) | Exported Function | 0x000000018000d470 | 0x0000d470
`public: __cdecl CHidButton::CHidButton(struct HWND__ * __ptr64,unsigned int,unsigned int) __ptr64` | 22 (0x16) | Exported Function | 0x0000000180008150 | 0x00008150
`public: __cdecl CHidButton::~CHidButton(void) __ptr64` | 36 (0x24) | Exported Function | 0x0000000180008180 | 0x00008180
`public: __cdecl COrientation::COrientation(void) __ptr64` | 23 (0x17) | Exported Function | 0x0000000180008dc0 | 0x00008dc0
`public: __cdecl COrientation::~COrientation(void) __ptr64` | 37 (0x25) | Exported Function | 0x0000000180009200 | 0x00009200
`public: class ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> > & __ptr64 __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::operator=(class ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> > const & __ptr64) __ptr64` | 39 (0x27) | Exported Function | 0x0000000180003e40 | 0x00003e40
`public: class ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> > & __ptr64 __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::operator=(class ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> > const & __ptr64) __ptr64` | 40 (0x28) | Exported Function | 0x0000000180003e40 | 0x00003e40
`public: int __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::RemoveAt(int) __ptr64` | 192 (0xc0) | Exported Function | 0x0000000180007070 | 0x00007070
`UninitializeTabletButtons` | 218 (0xda) | Exported Function | 0x000000018000d2c0 | 0x0000d2c0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TabBtn.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/d19342e870809bcf20d3bac6bb7c92ca86253df615dbea835f2040e6e5a94391/detection/





MIT License. Copyright (c) 2020 Strontic.


