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

Function Name | Ordinal | Type
-- | -- | --
`public: long __cdecl CButtonConfig::Init(int) __ptr64` | 131 | Exported Function
`public: long __cdecl CButtonAction::SetDataDWORD(unsigned long) __ptr64` | 210 | Exported Function
`public: long __cdecl CButtonAction::SetData(unsigned char * __ptr64 const,unsigned long) __ptr64` | 209 | Exported Function
`public: long __cdecl CButtonConfig::LoadSettings(void) __ptr64` | 144 | Exported Function
`public: long __cdecl CButtonConfig::RegReadDisplayOrientations(void) __ptr64` | 174 | Exported Function
`public: long __cdecl CButtonConfig::RegReadButtonsSettings(void) __ptr64` | 173 | Exported Function
`public: long __cdecl CButtonConfig::RegReadButtonSetting(struct HKEY__ * __ptr64,int,int) __ptr64` | 172 | Exported Function
`public: int __cdecl CButtonSettings::ShouldButtonShowUI(int)const __ptr64` | 214 | Exported Function
`public: int __cdecl CButtonSettings::GetButtonCount(void)const __ptr64` | 88 | Exported Function
`public: int __cdecl CButtonAction::IsSameAction(class CButtonAction const * __ptr64)const __ptr64` | 142 | Exported Function
`public: int __cdecl CHidButton::UnregisterHidBtnDevice(struct _hidbtndev * __ptr64,unsigned long * __ptr64) __ptr64` | 220 | Exported Function
`public: long __cdecl CButtonAction::Set(class CButtonAction const * __ptr64) __ptr64` | 202 | Exported Function
`public: long __cdecl CButtonAction::Clone(class CButtonAction * __ptr64 * __ptr64)const __ptr64` | 66 | Exported Function
`public: long __cdecl CActions::Init(void) __ptr64` | 130 | Exported Function
`public: long __cdecl CButtonSettings::GetButtonIds(unsigned long * __ptr64,int)const __ptr64` | 91 | Exported Function
`public: long __cdecl CButtonSettings::GetButtonFromId(unsigned long,class CButtonSetting * __ptr64 * __ptr64) __ptr64` | 89 | Exported Function
`public: long __cdecl CButtonSetting::MakeAllUserActionsEqual(unsigned long) __ptr64` | 146 | Exported Function
`public: long __cdecl CFunctionNotification::Hide(void) __ptr64` | 128 | Exported Function
`public: long __cdecl COrientation::Init(struct HKEY__ * __ptr64) __ptr64` | 133 | Exported Function
`public: long __cdecl CHidButton::DispatchHidBtnEvents(struct HRAWINPUT__ * __ptr64) __ptr64` | 69 | Exported Function
`public: long __cdecl CFunctionNotification::Show(void) __ptr64` | 216 | Exported Function
`public: long __cdecl CButtonConfig::UpdateButtonRates(void) __ptr64` | 221 | Exported Function
`public: long __cdecl CButtonConfig::SaveSettings(void) __ptr64` | 198 | Exported Function
`public: long __cdecl CButtonConfig::RegReadOrientationSeq(void) __ptr64` | 175 | Exported Function
`public: long __cdecl CButtonMonitor::Init(struct HWND__ * __ptr64) __ptr64` | 132 | Exported Function
`public: long __cdecl CButtonSetting::GetActionFromOrientation(unsigned long,class CButtonAction * __ptr64 * __ptr64,class CButtonAction * __ptr64 * __ptr64,class CButtonAction * __ptr64 * __ptr64) __ptr64` | 84 | Exported Function
`public: long __cdecl CButtonMonitor::UnregisterButtonDevices(void) __ptr64` | 219 | Exported Function
`public: long __cdecl CButtonMonitor::RegisterButtonDevices(void) __ptr64` | 176 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::Remove(class COrientation * __ptr64 const & __ptr64) __ptr64` | 184 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::GetSize(void)const __ptr64` | 123 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::Find(class COrientation * __ptr64 const & __ptr64)const __ptr64` | 76 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::RemoveAt(int) __ptr64` | 194 | Exported Function
`public: int __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::Find(struct ACTION * __ptr64 const & __ptr64)const __ptr64` | 73 | Exported Function
`public: int __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::Add(struct ACTION * __ptr64 const & __ptr64) __ptr64` | 60 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::SetAtIndex(int,class COrientation * __ptr64 const & __ptr64) __ptr64` | 207 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::GetSize(void)const __ptr64` | 122 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::Find(class CButtonSetting * __ptr64 const & __ptr64)const __ptr64` | 75 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::Add(class CButtonSetting * __ptr64 const & __ptr64) __ptr64` | 62 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::Remove(class CButtonSetting * __ptr64 const & __ptr64) __ptr64` | 183 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::Add(class COrientation * __ptr64 const & __ptr64) __ptr64` | 63 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::SetAtIndex(int,class CButtonSetting * __ptr64 const & __ptr64) __ptr64` | 206 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::RemoveAt(int) __ptr64` | 193 | Exported Function
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::RemoveAt(int) __ptr64` | 195 | Exported Function
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::Remove(unsigned long const & __ptr64) __ptr64` | 185 | Exported Function
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::GetSize(void)const __ptr64` | 124 | Exported Function
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::SetAt(unsigned long const & __ptr64,class CButtonImages * __ptr64 const & __ptr64) __ptr64` | 203 | Exported Function
`public: int __cdecl CButtonAction::CanRepeat(void)const __ptr64` | 65 | Exported Function
`public: int __cdecl CActions::GetCount(void) __ptr64` | 94 | Exported Function
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::SetAtIndex(int,unsigned long const & __ptr64,class CButtonImages * __ptr64 const & __ptr64) __ptr64` | 208 | Exported Function
`public: int __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::RemoveAt(int) __ptr64` | 191 | Exported Function
`public: int __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::Remove(struct ACTION * __ptr64 const & __ptr64) __ptr64` | 181 | Exported Function
`public: int __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::GetSize(void)const __ptr64` | 120 | Exported Function
`public: int __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::SetAtIndex(int,struct ACTION * __ptr64 const & __ptr64) __ptr64` | 204 | Exported Function
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::FindVal(class CButtonImages * __ptr64 const & __ptr64)const __ptr64` | 81 | Exported Function
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::FindKey(unsigned long const & __ptr64)const __ptr64` | 79 | Exported Function
`public: int __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::Add(unsigned long const & __ptr64,class CButtonImages * __ptr64 const & __ptr64) __ptr64` | 64 | Exported Function
`public: unsigned short const * __ptr64 __cdecl CButtonSettings::GetButtonName(int)const __ptr64` | 93 | Exported Function
`public: unsigned short const * __ptr64 __cdecl CButtonSetting::GetDisallowedActions(void) __ptr64` | 105 | Exported Function
`public: unsigned short const * __ptr64 __cdecl CButtonSetting::GetButtonName(void) __ptr64` | 92 | Exported Function
`public: unsigned short const * __ptr64 __cdecl COrientation::GetDescription(void) __ptr64` | 103 | Exported Function
`public: void __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::RemoveAll(void) __ptr64` | 187 | Exported Function
`public: void __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::InternalSetAtIndex(int,class CButtonAction * __ptr64 const & __ptr64) __ptr64` | 136 | Exported Function
`public: unsigned short const * __ptr64 __cdecl COrientation::GetKeyName(void) __ptr64` | 113 | Exported Function
`public: unsigned long __cdecl COrientation::GetDefSeq(void) __ptr64` | 102 | Exported Function
`public: unsigned long __cdecl CButtonSettings::GetFnKeyButtonId(void) __ptr64` | 108 | Exported Function
`public: unsigned long __cdecl CButtonSettings::GetButtonIdFromIndex(unsigned long) __ptr64` | 90 | Exported Function
`public: unsigned long __cdecl COrientation::GetMode(void) __ptr64` | 115 | Exported Function
`public: unsigned short const * __ptr64 __cdecl CButtonSetting::GetAllowedActions(void) __ptr64` | 85 | Exported Function
`public: unsigned short const * __ptr64 __cdecl CButtonConfig::GetDisplayOrientationName(unsigned long) __ptr64` | 106 | Exported Function
`public: unsigned long const __cdecl CButtonAction::GetDataDWORD(void)const __ptr64` | 101 | Exported Function
`public: void __cdecl CButtonAction::SetId(unsigned long) __ptr64` | 213 | Exported Function
`public: void __cdecl CButtonAction::FreeData(void) __ptr64` | 82 | Exported Function
`public: void __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::RemoveAll(void) __ptr64` | 190 | Exported Function
`public: void __cdecl CButtonConfig::RegReadActions(struct HKEY__ * __ptr64,class CButtonSetting * __ptr64,int) __ptr64` | 170 | Exported Function
`UninitializeTabletButtons` | 218 | Exported Function
`public: void __cdecl CButtonMonitor::OnMessage(unsigned int,unsigned __int64,__int64) __ptr64` | 164 | Exported Function
`public: void __cdecl CButtonConfig::UpdateCurrentDisplayOrientation(void) __ptr64` | 222 | Exported Function
`public: void __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::InternalSetAtIndex(int,class COrientation * __ptr64 const & __ptr64) __ptr64` | 138 | Exported Function
`public: void __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::RemoveAll(void) __ptr64` | 188 | Exported Function
`public: void __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::InternalSetAtIndex(int,class CButtonSetting * __ptr64 const & __ptr64) __ptr64` | 137 | Exported Function
`public: void __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::RemoveAll(void) __ptr64` | 189 | Exported Function
`public: void __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::InternalSetAtIndex(int,unsigned long const & __ptr64,class CButtonImages * __ptr64 const & __ptr64) __ptr64` | 139 | Exported Function
`public: void __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::RemoveAll(void) __ptr64` | 186 | Exported Function
`public: void __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::InternalSetAtIndex(int,struct ACTION * __ptr64 const & __ptr64) __ptr64` | 135 | Exported Function
`public: struct ACTION * __ptr64 & __ptr64 __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::operator[](int) __ptr64` | 52 | Exported Function
`public: struct _hidbtndev * __ptr64 __cdecl CHidButton::RegisterHidBtnDevice(void * __ptr64,unsigned long * __ptr64) __ptr64` | 178 | Exported Function
`public: struct _hidbtndev * __ptr64 __cdecl CHidButton::FindDeviceByHandle(void * __ptr64) __ptr64` | 78 | Exported Function
`public: struct ACTION * __ptr64 * __ptr64 __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::GetData(void)const __ptr64` | 96 | Exported Function
`public: struct ACTION * __ptr64 const & __ptr64 __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::operator[](int)const __ptr64` | 53 | Exported Function
`public: struct ACTION * __ptr64 __cdecl CActions::GetActionAt(int) __ptr64` | 83 | Exported Function
`public: struct ACTION * __ptr64 __cdecl CActions::FindActionById(unsigned long) __ptr64` | 77 | Exported Function
`public: static int __cdecl CButtonMonitor::IsActionUnsupported(unsigned long)` | 141 | Exported Function
`public: static int __cdecl CButtonAction::IsActionRepeatable(unsigned long)` | 140 | Exported Function
`public: static __int64 __cdecl CFunctionNotification::WindowProc(struct HWND__ * __ptr64,unsigned int,unsigned __int64,__int64)` | 224 | Exported Function
`public: static long __cdecl CButtonConfig::RegReadAndAllocate(struct HKEY__ * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64,unsigned char * __ptr64 * __ptr64,unsigned long * __ptr64)` | 171 | Exported Function
`public: static void __cdecl CButtonMonitor::WinEventProc(struct HWINEVENTHOOK__ * __ptr64,unsigned long,struct HWND__ * __ptr64,long,long,unsigned long,unsigned long)` | 223 | Exported Function
`public: static unsigned long CButtonMonitor::sm_dwPopupCount` | 225 | Exported Function
`public: static long __cdecl CButtonMonitor::CreateExtendedActionObject(struct IUnknown * __ptr64 * __ptr64)` | 67 | Exported Function
`public: unsigned long __cdecl CButtonConfig::GetCurrentDisplayOrientation(void) __ptr64` | 95 | Exported Function
`public: unsigned long __cdecl CButtonAction::GetSize(void)const __ptr64` | 125 | Exported Function
`public: unsigned long __cdecl CButtonAction::GetRegType(void)const __ptr64` | 119 | Exported Function
`public: unsigned long __cdecl CButtonConfig::GetOrientSeq(unsigned int)const __ptr64` | 116 | Exported Function
`public: unsigned long __cdecl CButtonSetting::GetId(void) __ptr64` | 111 | Exported Function
`public: unsigned long __cdecl CButtonSetting::GetFlags(void) __ptr64` | 107 | Exported Function
`public: unsigned long __cdecl CButtonConfig::GetOrientSeqCount(void)const __ptr64` | 117 | Exported Function
`public: unsigned char * __ptr64 __cdecl CButtonAction::GetData(void)const __ptr64` | 100 | Exported Function
`public: struct HBITMAP__ * __ptr64 __cdecl CButtonSettings::GetLocationImage(unsigned long,unsigned long) __ptr64` | 114 | Exported Function
`public: struct HBITMAP__ * __ptr64 __cdecl CButtonSettings::GetDetailImage(unsigned long,unsigned long) __ptr64` | 104 | Exported Function
`public: unsigned long & __ptr64 __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::GetKeyAt(int)const __ptr64` | 112 | Exported Function
`public: unsigned long __cdecl CButtonAction::GetOrientationMode(void)const __ptr64` | 118 | Exported Function
`public: unsigned long __cdecl CButtonAction::GetId(void)const __ptr64` | 110 | Exported Function
`public: unsigned long __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::ReverseLookup(class CButtonImages * __ptr64 const & __ptr64)const __ptr64` | 197 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::SetAtIndex(int,class CButtonAction * __ptr64 const & __ptr64) __ptr64` | 205 | Exported Function
`private: void __cdecl CButtonMonitor::OnHoldTimer(void) __ptr64` | 162 | Exported Function
`private: void __cdecl CButtonMonitor::OnFnKeyTimer(void) __ptr64` | 161 | Exported Function
`private: void __cdecl CButtonMonitor::OnDisplayChange(unsigned __int64,__int64) __ptr64` | 160 | Exported Function
`private: void __cdecl CButtonMonitor::OnInput(unsigned __int64,__int64) __ptr64` | 163 | Exported Function
`private: void __cdecl CButtonMonitor::OnTimer(unsigned __int64,__int64) __ptr64` | 167 | Exported Function
`private: void __cdecl CButtonMonitor::OnSettingChange(unsigned __int64,__int64) __ptr64` | 166 | Exported Function
`private: void __cdecl CButtonMonitor::OnRepeatTimer(void) __ptr64` | 165 | Exported Function
`private: static void __cdecl CButtonMonitor::SendModKeys(unsigned char,int)` | 200 | Exported Function
`private: static long __cdecl CButtonMonitor::ShowWindowSwitchWindow(void)` | 217 | Exported Function
`private: long __cdecl CFunctionNotification::CreateTrayWindow(void) __ptr64` | 68 | Exported Function
`private: static void __cdecl CButtonMonitor::SendVKey(unsigned char,unsigned char,int)` | 201 | Exported Function
`private: void __cdecl CButtonMonitor::OnButtonUp(unsigned __int64,__int64) __ptr64` | 159 | Exported Function
`private: void __cdecl CButtonMonitor::OnButtonDown(unsigned __int64,__int64) __ptr64` | 158 | Exported Function
`private: void __cdecl CButtonConfig::ResetDeprecatedAction(class CButtonAction * __ptr64) __ptr64` | 196 | Exported Function
`public: __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::~CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >(void) __ptr64` | 27 | Exported Function
`public: __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >(void) __ptr64` | 8 | Exported Function
`public: __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >(class ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> > const & __ptr64) __ptr64` | 7 | Exported Function
`public: __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >(class ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> > const & __ptr64) __ptr64` | 1 | Exported Function
`public: __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >(void) __ptr64` | 9 | Exported Function
`public: __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::~CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >(void) __ptr64` | 24 | Exported Function
`public: __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >(void) __ptr64` | 2 | Exported Function
`public: __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >(void) __ptr64` | 4 | Exported Function
`public: __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >(class ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> > const & __ptr64) __ptr64` | 3 | Exported Function
`private: void __cdecl CButtonMonitor::SetDisplayPower(int) __ptr64` | 212 | Exported Function
`public: __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::~CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >(void) __ptr64` | 25 | Exported Function
`public: __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::~CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >(void) __ptr64` | 26 | Exported Function
`public: __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >(void) __ptr64` | 6 | Exported Function
`public: __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >(class ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> > const & __ptr64) __ptr64` | 5 | Exported Function
`private: long __cdecl CButtonMonitor::ExecuteObject(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 72 | Exported Function
`private: long __cdecl CButtonMonitor::DoButtonAction(class CButtonAction * __ptr64,unsigned long,int,int) __ptr64` | 71 | Exported Function
`private: long __cdecl CButtonMonitor::DoBuiltInAction(class CButtonAction * __ptr64,int,int) __ptr64` | 70 | Exported Function
`private: long __cdecl CButtonMonitor::NotifyFnMode(int) __ptr64` | 147 | Exported Function
`private: long __cdecl CButtonMonitor::OnActionDisplayOff(class CButtonAction * __ptr64,int,int) __ptr64` | 150 | Exported Function
`private: long __cdecl CButtonMonitor::OnActionContextMenu(class CButtonAction * __ptr64,int,int) __ptr64` | 149 | Exported Function
`private: long __cdecl CButtonMonitor::OnActionAppCommand(class CButtonAction * __ptr64,int,int) __ptr64` | 148 | Exported Function
`private: int __cdecl CButtonMonitor::InSession0(void) __ptr64` | 129 | Exported Function
`InitializeTabletButtons` | 134 | Exported Function
`HandleTabletButtonMessages` | 127 | Exported Function
`private: int __cdecl CButtonMonitor::ShouldSendEscapeForBack(void) __ptr64` | 215 | Exported Function
`private: int __cdecl CHidButton::GetHidBtnUsages(struct _hidbtndev * __ptr64,struct tagRAWINPUT * __ptr64,unsigned short,unsigned short,struct _USAGE_AND_PAGE * __ptr64,unsigned long * __ptr64) __ptr64` | 109 | Exported Function
`private: int __cdecl CHidButton::FindUsage(struct _USAGE_AND_PAGE * __ptr64,unsigned long,unsigned short,unsigned short) __ptr64` | 80 | Exported Function
`private: int __cdecl CButtonSettings::LoadImageDLL(void) __ptr64` | 143 | Exported Function
`private: long __cdecl CButtonMonitor::RegisterForPopups(void) __ptr64` | 177 | Exported Function
`private: long __cdecl CButtonMonitor::ProcessEvent(unsigned long,int) __ptr64` | 169 | Exported Function
`private: long __cdecl CButtonMonitor::ProcessAction(unsigned long,int) __ptr64` | 168 | Exported Function
`private: long __cdecl CButtonMonitor::ReleaseDownButtons(void) __ptr64` | 179 | Exported Function
`private: long __cdecl CButtonMonitor::SetDisplayOrientation(int) __ptr64` | 211 | Exported Function
`private: long __cdecl CButtonMonitor::SendAppCommand(unsigned short) __ptr64` | 199 | Exported Function
`private: long __cdecl CButtonMonitor::ReleaseRepeatOrHoldButton(void) __ptr64` | 180 | Exported Function
`private: long __cdecl CButtonMonitor::OnActionSendKey(class CButtonAction * __ptr64,int,int) __ptr64` | 153 | Exported Function
`private: long __cdecl CButtonMonitor::OnActionMouseWheel(class CButtonAction * __ptr64,int,int) __ptr64` | 152 | Exported Function
`private: long __cdecl CButtonMonitor::OnActionLaunchApp(class CButtonAction * __ptr64,int,int) __ptr64` | 151 | Exported Function
`private: long __cdecl CButtonMonitor::OnActionSetOrientation(class CButtonAction * __ptr64,int,int) __ptr64` | 154 | Exported Function
`private: long __cdecl CButtonMonitor::OnActionWindowsFlip3d(class CButtonAction * __ptr64,int,int) __ptr64` | 156 | Exported Function
`private: long __cdecl CButtonMonitor::OnActionWindowsFlip(class CButtonAction * __ptr64,int,int) __ptr64` | 157 | Exported Function
`private: long __cdecl CButtonMonitor::OnActionUnknown(class CButtonAction * __ptr64,int,int) __ptr64` | 155 | Exported Function
`public: class CButtonImages * __ptr64 __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::Lookup(unsigned long const & __ptr64)const __ptr64` | 145 | Exported Function
`public: class CButtonImages * __ptr64 & __ptr64 __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::GetValueAt(int)const __ptr64` | 126 | Exported Function
`public: class CButtonConfig * __ptr64 __cdecl CButtonMonitor::GetButtonConfig(void) __ptr64` | 87 | Exported Function
`public: class CButtonMonitor & __ptr64 __cdecl CButtonMonitor::operator=(class CButtonMonitor const & __ptr64) __ptr64` | 46 | Exported Function
`public: class CButtonSetting * __ptr64 * __ptr64 __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::GetData(void)const __ptr64` | 98 | Exported Function
`public: class CButtonSetting * __ptr64 & __ptr64 __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::operator[](int) __ptr64` | 56 | Exported Function
`public: class CButtonSetting & __ptr64 __cdecl CButtonSetting::operator=(class CButtonSetting const & __ptr64) __ptr64` | 47 | Exported Function
`public: class CButtonAction & __ptr64 __cdecl CButtonAction::operator=(class CButtonAction const & __ptr64) __ptr64` | 44 | Exported Function
`public: class CActions & __ptr64 __cdecl CActions::operator=(class CActions const & __ptr64) __ptr64` | 43 | Exported Function
`public: class ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> > & __ptr64 __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::operator=(class ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> > const & __ptr64) __ptr64` | 42 | Exported Function
`public: class CButtonAction * __ptr64 & __ptr64 __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::operator[](int) __ptr64` | 54 | Exported Function
`public: class CButtonConfig & __ptr64 __cdecl CButtonConfig::operator=(class CButtonConfig const & __ptr64) __ptr64` | 45 | Exported Function
`public: class CButtonAction * __ptr64 const & __ptr64 __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::operator[](int)const __ptr64` | 55 | Exported Function
`public: class CButtonAction * __ptr64 * __ptr64 __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::GetData(void)const __ptr64` | 97 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::Add(class CButtonAction * __ptr64 const & __ptr64) __ptr64` | 61 | Exported Function
`public: enum BUTTONACTION_TYPE const __cdecl CButtonAction::GetButtonActionType(void)const __ptr64` | 86 | Exported Function
`public: class COrientation * __ptr64 const & __ptr64 __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::operator[](int)const __ptr64` | 59 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::Find(class CButtonAction * __ptr64 const & __ptr64)const __ptr64` | 74 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::RemoveAt(int) __ptr64` | 192 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::Remove(class CButtonAction * __ptr64 const & __ptr64) __ptr64` | 182 | Exported Function
`public: int __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::GetSize(void)const __ptr64` | 121 | Exported Function
`public: class CFunctionNotification & __ptr64 __cdecl CFunctionNotification::operator=(class CFunctionNotification const & __ptr64) __ptr64` | 49 | Exported Function
`public: class CButtonSettings & __ptr64 __cdecl CButtonSettings::operator=(class CButtonSettings const & __ptr64) __ptr64` | 48 | Exported Function
`public: class CButtonSetting * __ptr64 const & __ptr64 __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::operator[](int)const __ptr64` | 57 | Exported Function
`public: class CHidButton & __ptr64 __cdecl CHidButton::operator=(class CHidButton const & __ptr64) __ptr64` | 50 | Exported Function
`public: class COrientation * __ptr64 * __ptr64 __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::GetData(void)const __ptr64` | 99 | Exported Function
`public: class COrientation * __ptr64 & __ptr64 __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::operator[](int) __ptr64` | 58 | Exported Function
`public: class COrientation & __ptr64 __cdecl COrientation::operator=(class COrientation const & __ptr64) __ptr64` | 51 | Exported Function
`public: __cdecl CButtonMonitor::CButtonMonitor(class CButtonMonitor const & __ptr64) __ptr64` | 15 | Exported Function
`public: __cdecl CButtonConfig::~CButtonConfig(void) __ptr64` | 31 | Exported Function
`public: __cdecl CButtonConfig::CButtonConfig(void) __ptr64` | 14 | Exported Function
`public: __cdecl CButtonMonitor::CButtonMonitor(void) __ptr64` | 16 | Exported Function
`public: __cdecl CButtonSetting::CButtonSetting(void) __ptr64` | 18 | Exported Function
`public: __cdecl CButtonSetting::CButtonSetting(class CButtonSetting const & __ptr64) __ptr64` | 17 | Exported Function
`public: __cdecl CButtonMonitor::~CButtonMonitor(void) __ptr64` | 32 | Exported Function
`public: __cdecl CActions::CActions(void) __ptr64` | 11 | Exported Function
`public: __cdecl CActions::CActions(class CActions const & __ptr64) __ptr64` | 10 | Exported Function
`public: __cdecl ATL::CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >::~CSimpleMap<unsigned long,class CButtonImages * __ptr64,class ATL::CSimpleMapEqualHelper<unsigned long,class CButtonImages * __ptr64> >(void) __ptr64` | 28 | Exported Function
`public: __cdecl CActions::~CActions(void) __ptr64` | 29 | Exported Function
`public: __cdecl CButtonConfig::CButtonConfig(class CButtonConfig const & __ptr64) __ptr64` | 13 | Exported Function
`public: __cdecl CButtonAction::~CButtonAction(void) __ptr64` | 30 | Exported Function
`public: __cdecl CButtonAction::CButtonAction(enum BUTTONACTION_TYPE) __ptr64` | 12 | Exported Function
`public: __cdecl COrientation::~COrientation(void) __ptr64` | 37 | Exported Function
`public: __cdecl COrientation::COrientation(void) __ptr64` | 23 | Exported Function
`public: __cdecl CHidButton::~CHidButton(void) __ptr64` | 36 | Exported Function
`public: class ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> > & __ptr64 __cdecl ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> >::operator=(class ATL::CSimpleArray<class CButtonAction * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonAction * __ptr64> > const & __ptr64) __ptr64` | 39 | Exported Function
`public: class ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> > & __ptr64 __cdecl ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> >::operator=(class ATL::CSimpleArray<struct ACTION * __ptr64,class ATL::CSimpleArrayEqualHelper<struct ACTION * __ptr64> > const & __ptr64) __ptr64` | 38 | Exported Function
`public: class ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> > & __ptr64 __cdecl ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> >::operator=(class ATL::CSimpleArray<class COrientation * __ptr64,class ATL::CSimpleArrayEqualHelper<class COrientation * __ptr64> > const & __ptr64) __ptr64` | 41 | Exported Function
`public: class ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> > & __ptr64 __cdecl ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> >::operator=(class ATL::CSimpleArray<class CButtonSetting * __ptr64,class ATL::CSimpleArrayEqualHelper<class CButtonSetting * __ptr64> > const & __ptr64) __ptr64` | 40 | Exported Function
`public: __cdecl CButtonSettings::CButtonSettings(void) __ptr64` | 20 | Exported Function
`public: __cdecl CButtonSettings::CButtonSettings(class CButtonSettings const & __ptr64) __ptr64` | 19 | Exported Function
`public: __cdecl CButtonSetting::~CButtonSetting(void) __ptr64` | 33 | Exported Function
`public: __cdecl CButtonSettings::~CButtonSettings(void) __ptr64` | 34 | Exported Function
`public: __cdecl CHidButton::CHidButton(struct HWND__ * __ptr64,unsigned int,unsigned int) __ptr64` | 22 | Exported Function
`public: __cdecl CFunctionNotification::~CFunctionNotification(void) __ptr64` | 35 | Exported Function
`public: __cdecl CFunctionNotification::CFunctionNotification(void) __ptr64` | 21 | Exported Function


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


