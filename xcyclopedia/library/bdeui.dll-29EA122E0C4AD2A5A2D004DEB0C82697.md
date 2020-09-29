---
title: bdeui.dll | Windows BitLocker Drive Encryption User Interface
excerpt: What is bdeui.dll?
---

# bdeui.dll 

* File Path: `C:\Windows\system32\bdeui.dll`
* Description: Windows BitLocker Drive Encryption User Interface

## Hashes

Type | Hash
-- | --
MD5 | `29EA122E0C4AD2A5A2D004DEB0C82697`
SHA1 | `BA4CD3ED3BDC55BD30F08D9464AACB8E04DA6F79`
SHA256 | `4F41351146C6E14B439ABE5C0A7C53082CD7C72ADD996EC5AB92DF45A32F78F2`
SHA384 | `3F35D28A0FBA063A7F540BD2C39E803D07898ACCC567E06D42592248FF390F61EA16BF42008CBABCB6072AFF6E73D7C3`
SHA512 | `7D016C1C7D7FE833DA6827DCA2A207200D5977D34FD26FC27EDEE6336333FB023F558F02A8856713617F08A66223A1F0A6D821ECA22E22D24E9CD460E752A77C`
SSDEEP | `768:ZIpPCcX45a/bjk3KmInKWnflpPw/CSmGCjuScB8r:epPCcTbjkalln9p4/jXCCScB8r`
IMP | `9311C1BFFD099E5E16E604E7B1771CF3`
PESHA1 | `E1EAA0F144AD6EB2A7436C33251981997E4F1E13`
PE256 | `BD4164D223110936F43FA8355257CA59A1F984699A432FBA82E903FA2CED2223`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`BuisCreateElevatedProxyObject` | 127 (0x7f) | Exported Function | 0x0000000180001370 | 0x00001370
`public: long __cdecl BuiVolume::Decrypt(struct HWND__ * __ptr64) __ptr64` | 23 (0x17) | Exported Function | 0x0000000180002950 | 0x00002950
`public: long __cdecl BuiVolume::AttemptAutoUnlock(void) __ptr64` | 11 (0xb) | Exported Function | 0x0000000180002760 | 0x00002760
`public: long __cdecl BuiVolume::AddSmartCard(struct HWND__ * __ptr64) __ptr64` | 9 (0x9) | Exported Function | 0x0000000180002a10 | 0x00002a10
`public: double __cdecl BuiVolume::GetWipedPercent(void)const __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180004470 | 0x00004470
`public: double __cdecl BuiVolume::GetConvertedPercent(void)const __ptr64` | 34 (0x22) | Exported Function | 0x0000000180004460 | 0x00004460
`public: class VolumeFveStatus & __ptr64 __cdecl VolumeFveStatus::operator=(class VolumeFveStatus const & __ptr64) __ptr64` | 8 (0x8) | Exported Function | 0x00000001800012f0 | 0x000012f0
`public: class VolumeFveStatus & __ptr64 __cdecl VolumeFveStatus::operator=(class VolumeFveStatus && __ptr64) __ptr64` | 7 (0x7) | Exported Function | 0x0000000180001310 | 0x00001310
`public: class BuiVolume & __ptr64 __cdecl BuiVolume::operator=(class BuiVolume const & __ptr64) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180001340 | 0x00001340
`public: bool __cdecl VolumeFveStatus::NeedsRestart(void)const __ptr64` | 85 (0x55) | Exported Function | 0x00000001800011d0 | 0x000011d0
`public: bool __cdecl VolumeFveStatus::IsWiping(void)const __ptr64` | 79 (0x4f) | Exported Function | 0x00000001800011a0 | 0x000011a0
`public: bool __cdecl VolumeFveStatus::IsUnknownFveVersion(void)const __ptr64` | 78 (0x4e) | Exported Function | 0x0000000180001280 | 0x00001280
`public: bool __cdecl VolumeFveStatus::IsSecure(void)const __ptr64` | 77 (0x4d) | Exported Function | 0x00000001800011c0 | 0x000011c0
`public: bool __cdecl VolumeFveStatus::IsRoamingDevice(void)const __ptr64` | 76 (0x4c) | Exported Function | 0x00000001800010f0 | 0x000010f0
`public: bool __cdecl VolumeFveStatus::IsPreProvisioned(void)const __ptr64` | 75 (0x4b) | Exported Function | 0x0000000180001220 | 0x00001220
`public: bool __cdecl VolumeFveStatus::IsPaused(void)const __ptr64` | 74 (0x4a) | Exported Function | 0x0000000180001110 | 0x00001110
`public: bool __cdecl VolumeFveStatus::IsPartiallyConverted(void)const __ptr64` | 73 (0x49) | Exported Function | 0x0000000180001150 | 0x00001150
`public: bool __cdecl VolumeFveStatus::IsOsVolume(void)const __ptr64` | 72 (0x48) | Exported Function | 0x00000001800010c0 | 0x000010c0
`public: bool __cdecl VolumeFveStatus::IsOsCriticalVolume(void)const __ptr64` | 71 (0x47) | Exported Function | 0x00000001800010d0 | 0x000010d0
`public: bool __cdecl VolumeFveStatus::IsOn(void)const __ptr64` | 70 (0x46) | Exported Function | 0x0000000180001100 | 0x00001100
`public: bool __cdecl VolumeFveStatus::IsLocked(void)const __ptr64` | 69 (0x45) | Exported Function | 0x0000000180001200 | 0x00001200
`public: bool __cdecl VolumeFveStatus::IsEncrypting(void)const __ptr64` | 67 (0x43) | Exported Function | 0x0000000180001160 | 0x00001160
`public: bool __cdecl VolumeFveStatus::IsEncrypted(void)const __ptr64` | 66 (0x42) | Exported Function | 0x0000000180001170 | 0x00001170
`public: bool __cdecl VolumeFveStatus::IsEDriveVolume(void)const __ptr64` | 65 (0x41) | Exported Function | 0x0000000180001260 | 0x00001260
`public: bool __cdecl VolumeFveStatus::IsDisabled(void)const __ptr64` | 64 (0x40) | Exported Function | 0x00000001800011e0 | 0x000011e0
`public: bool __cdecl VolumeFveStatus::IsDecrypting(void)const __ptr64` | 63 (0x3f) | Exported Function | 0x0000000180001180 | 0x00001180
`public: bool __cdecl VolumeFveStatus::IsDecrypted(void)const __ptr64` | 62 (0x3e) | Exported Function | 0x0000000180001190 | 0x00001190
`public: bool __cdecl VolumeFveStatus::IsDEAutoProvisioned(void)const __ptr64` | 61 (0x3d) | Exported Function | 0x00000001800012a0 | 0x000012a0
`public: bool __cdecl VolumeFveStatus::IsCsvMetadataVolume(void)const __ptr64` | 59 (0x3b) | Exported Function | 0x0000000180001270 | 0x00001270
`public: bool __cdecl VolumeFveStatus::IsConverting(void)const __ptr64` | 58 (0x3a) | Exported Function | 0x0000000180001130 | 0x00001130
`public: long __cdecl BuiVolume::Disable(struct HWND__ * __ptr64) __ptr64` | 25 (0x19) | Exported Function | 0x0000000180002960 | 0x00002960
`public: bool __cdecl VolumeFveStatus::HasTpmProtector(void)const __ptr64` | 53 (0x35) | Exported Function | 0x0000000180001040 | 0x00001040
`public: long __cdecl BuiVolume::DisableAutoUnlock(void) __ptr64` | 26 (0x1a) | Exported Function | 0x0000000180002730 | 0x00002730
`public: long __cdecl BuiVolume::GetDescription(unsigned short * __ptr64 * __ptr64) __ptr64` | 35 (0x23) | Exported Function | 0x00000001800028e0 | 0x000028e0
`public: void __cdecl BuiVolume::ResumeStatusRefreshing(void) __ptr64` | 117 (0x75) | Exported Function | 0x0000000180001f10 | 0x00001f10
`public: void __cdecl BuiVolume::ClearProxyObject(void) __ptr64` | 22 (0x16) | Exported Function | 0x0000000180002530 | 0x00002530
`public: unsigned long __cdecl VolumeFveStatus::GetStatusFlags(void)const __ptr64` | 41 (0x29) | Exported Function | 0x00000001800012b0 | 0x000012b0
`public: unsigned long __cdecl BuiVolume::GetWipeCount(void)const __ptr64` | 42 (0x2a) | Exported Function | 0x0000000180004480 | 0x00004480
`public: unsigned __int64 __cdecl VolumeFveStatus::GetExtendedFlags(void)const __ptr64` | 36 (0x24) | Exported Function | 0x00000001800012c0 | 0x000012c0
`public: static void __cdecl BuiVolume::DeleteVolumeList(struct _BuiVolumeNode * __ptr64 * __ptr64)` | 24 (0x18) | Exported Function | 0x0000000180004190 | 0x00004190
`public: static unsigned int const BuiVolume::NO_DRIVE_LETTER` | 83 (0x53) | Exported Function | 0x0000000180006690 | 0x00006690
`public: static long __cdecl BuiVolume::GetOsVolume(class BuiVolume * __ptr64 * __ptr64)` | 38 (0x26) | Exported Function | 0x0000000180004200 | 0x00004200
`public: static long __cdecl BuiVolume::GetAllVolumes(struct _BuiVolumeNode * __ptr64 * __ptr64)` | 33 (0x21) | Exported Function | 0x0000000180003e70 | 0x00003e70
`public: long __cdecl VolumeFveStatus::GetLastConvertStatus(void)const __ptr64` | 37 (0x25) | Exported Function | 0x00000001800012d0 | 0x000012d0
`public: long __cdecl BuiVolume::UpgradeVolume(void) __ptr64` | 126 (0x7e) | Exported Function | 0x0000000180002a90 | 0x00002a90
`public: long __cdecl BuiVolume::UnlockWithSmartCard(struct HWND__ * __ptr64,int * __ptr64) __ptr64` | 125 (0x7d) | Exported Function | 0x0000000180002890 | 0x00002890
`public: long __cdecl BuiVolume::UnlockWithPassword(unsigned short const * __ptr64,int * __ptr64) __ptr64` | 124 (0x7c) | Exported Function | 0x00000001800027a0 | 0x000027a0
`public: long __cdecl BuiVolume::UnlockWithPassphrase(unsigned short const * __ptr64,int * __ptr64) __ptr64` | 123 (0x7b) | Exported Function | 0x0000000180002840 | 0x00002840
`public: long __cdecl BuiVolume::UnlockWithKey(unsigned short const * __ptr64,int * __ptr64) __ptr64` | 122 (0x7a) | Exported Function | 0x00000001800027f0 | 0x000027f0
`public: long __cdecl BuiVolume::ServiceDiscoveryVolume(void) __ptr64` | 118 (0x76) | Exported Function | 0x00000001800029b0 | 0x000029b0
`public: long __cdecl BuiVolume::ResumeConversion(void) __ptr64` | 116 (0x74) | Exported Function | 0x00000001800026d0 | 0x000026d0
`public: long __cdecl BuiVolume::RemoveSmartCard(bool) __ptr64` | 115 (0x73) | Exported Function | 0x0000000180002a50 | 0x00002a50
`public: long __cdecl BuiVolume::RemovePassphrase(void) __ptr64` | 114 (0x72) | Exported Function | 0x00000001800029d0 | 0x000029d0
`public: long __cdecl BuiVolume::RefreshStatus(bool) __ptr64` | 113 (0x71) | Exported Function | 0x0000000180001c80 | 0x00001c80
`public: long __cdecl BuiVolume::PauseConversion(void) __ptr64` | 86 (0x56) | Exported Function | 0x0000000180002670 | 0x00002670
`public: long __cdecl BuiVolume::NeedsDiscoveryVolumeUpdate(int * __ptr64) __ptr64` | 84 (0x54) | Exported Function | 0x00000001800029c0 | 0x000029c0
`public: long __cdecl BuiVolume::LaunchWizard(unsigned short) __ptr64` | 81 (0x51) | Exported Function | 0x0000000180002990 | 0x00002990
`public: long __cdecl BuiVolume::LaunchUpdate(void) __ptr64` | 80 (0x50) | Exported Function | 0x00000001800029a0 | 0x000029a0
`public: long __cdecl BuiVolume::IsCurrentPINEnhanced(int * __ptr64) __ptr64` | 60 (0x3c) | Exported Function | 0x0000000180001f40 | 0x00001f40
`public: long __cdecl BuiVolume::Init(unsigned short * __ptr64) __ptr64` | 55 (0x37) | Exported Function | 0x0000000180001ab0 | 0x00001ab0
`public: long __cdecl BuiVolume::ImplicitPauseConversion(void) __ptr64` | 54 (0x36) | Exported Function | 0x00000001800026a0 | 0x000026a0
`public: long __cdecl BuiVolume::GetPasswordId(unsigned short * __ptr64 * __ptr64) __ptr64` | 40 (0x28) | Exported Function | 0x0000000180002900 | 0x00002900
`public: long __cdecl BuiVolume::GetPasswordBackupTypes(unsigned short const * __ptr64,unsigned long * __ptr64) __ptr64` | 39 (0x27) | Exported Function | 0x0000000180002920 | 0x00002920
`public: long __cdecl BuiVolume::EnableAutoUnlock(void) __ptr64` | 29 (0x1d) | Exported Function | 0x0000000180002700 | 0x00002700
`public: void __cdecl BuiVolume::SetProxyObject(struct IDispatch * __ptr64) __ptr64` | 119 (0x77) | Exported Function | 0x00000001800024e0 | 0x000024e0
`public: bool __cdecl VolumeFveStatus::HasStartupKeyProtector(void)const __ptr64` | 52 (0x34) | Exported Function | 0x0000000180001090 | 0x00001090
`public: bool __cdecl VolumeFveStatus::HasRecoveryPassword(void)const __ptr64` | 50 (0x32) | Exported Function | 0x0000000180001060 | 0x00001060
`private: long __cdecl BuiVolume::ProxyGetProcessId(unsigned long * __ptr64) __ptr64` | 97 (0x61) | Exported Function | 0x0000000180003500 | 0x00003500
`private: long __cdecl BuiVolume::ProxyGetPasswordId(unsigned short * __ptr64 * __ptr64) __ptr64` | 96 (0x60) | Exported Function | 0x0000000180002900 | 0x00002900
`private: long __cdecl BuiVolume::ProxyGetPasswordBackupTypes(unsigned short const * __ptr64,unsigned long * __ptr64) __ptr64` | 95 (0x5f) | Exported Function | 0x0000000180002920 | 0x00002920
`private: long __cdecl BuiVolume::ProxyGetDescription(unsigned short * __ptr64 * __ptr64) __ptr64` | 94 (0x5e) | Exported Function | 0x00000001800028e0 | 0x000028e0
`private: long __cdecl BuiVolume::ProxyEnableAutoUnlock(void) __ptr64` | 93 (0x5d) | Exported Function | 0x0000000180003830 | 0x00003830
`private: long __cdecl BuiVolume::ProxyDisableAutoUnlock(void) __ptr64` | 92 (0x5c) | Exported Function | 0x0000000180003870 | 0x00003870
`private: long __cdecl BuiVolume::ProxyDisable(struct HWND__ * __ptr64) __ptr64` | 91 (0x5b) | Exported Function | 0x00000001800039b0 | 0x000039b0
`private: long __cdecl BuiVolume::ProxyDecrypt(struct HWND__ * __ptr64) __ptr64` | 90 (0x5a) | Exported Function | 0x0000000180003970 | 0x00003970
`private: long __cdecl BuiVolume::ProxyAttemptAutoUnlock(void) __ptr64` | 89 (0x59) | Exported Function | 0x00000001800038b0 | 0x000038b0
`private: long __cdecl BuiVolume::ProxyAreVolumesBound(void) __ptr64` | 88 (0x58) | Exported Function | 0x0000000180003930 | 0x00003930
`private: long __cdecl BuiVolume::ProxyAddSmartCard(struct HWND__ * __ptr64) __ptr64` | 87 (0x57) | Exported Function | 0x0000000180003ba0 | 0x00003ba0
`private: long __cdecl BuiVolume::FormatNameAndMountPoint(void) __ptr64` | 32 (0x20) | Exported Function | 0x0000000180002070 | 0x00002070
`private: long __cdecl BuiVolume::FindMountPoint(void) __ptr64` | 31 (0x1f) | Exported Function | 0x0000000180002210 | 0x00002210
`private: long __cdecl BuiVolume::Dispatch(long,struct tagDISPPARAMS * __ptr64,struct tagVARIANT * __ptr64) __ptr64` | 28 (0x1c) | Exported Function | 0x0000000180002b30 | 0x00002b30
`private: long __cdecl BuiVolume::Dispatch(long,struct tagDISPPARAMS * __ptr64,long * __ptr64) __ptr64` | 27 (0x1b) | Exported Function | 0x0000000180002ba0 | 0x00002ba0
`private: long __cdecl BuiVolume::BasicDispatch(long,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64) __ptr64` | 15 (0xf) | Exported Function | 0x00000001800033b0 | 0x000033b0
`private: long __cdecl BuiVolume::BasicDispatch(long,unsigned short const * __ptr64,unsigned short const * __ptr64,long * __ptr64) __ptr64` | 14 (0xe) | Exported Function | 0x0000000180002dd0 | 0x00002dd0
`private: long __cdecl BuiVolume::BasicDispatch(long,unsigned short const * __ptr64,unsigned short const * __ptr64,int * __ptr64,long * __ptr64) __ptr64` | 13 (0xd) | Exported Function | 0x0000000180002f00 | 0x00002f00
`private: long __cdecl BuiVolume::BasicDispatch(long,unsigned short const * __ptr64,unsigned short * __ptr64 * __ptr64) __ptr64` | 18 (0x12) | Exported Function | 0x0000000180003080 | 0x00003080
`private: long __cdecl BuiVolume::BasicDispatch(long,unsigned short const * __ptr64,struct tagVARIANT * __ptr64) __ptr64` | 19 (0x13) | Exported Function | 0x0000000180003220 | 0x00003220
`private: long __cdecl BuiVolume::BasicDispatch(long,unsigned short const * __ptr64,long * __ptr64) __ptr64` | 17 (0x11) | Exported Function | 0x0000000180002c20 | 0x00002c20
`private: long __cdecl BuiVolume::BasicDispatch(long,unsigned short const * __ptr64,int * __ptr64,long * __ptr64) __ptr64` | 16 (0x10) | Exported Function | 0x0000000180002cd0 | 0x00002cd0
`private: long __cdecl BuiVolume::BasicDispatch(long,struct HWND__ * __ptr64,unsigned short const * __ptr64,long * __ptr64) __ptr64` | 12 (0xc) | Exported Function | 0x00000001800032e0 | 0x000032e0
`private: long __cdecl BuiVolume::AllowForegroundWindowDisplay(void) __ptr64` | 10 (0xa) | Exported Function | 0x0000000180002480 | 0x00002480
`private: bool __cdecl BuiVolume::CanRefreshStatus(void)const __ptr64` | 21 (0x15) | Exported Function | 0x0000000180001f20 | 0x00001f20
`BuisIsHardwareReadyForConversion` | 131 (0x83) | Exported Function | 0x0000000180001510 | 0x00001510
`BuisIsFipsEnabled` | 130 (0x82) | Exported Function | 0x00000001800014e0 | 0x000014e0
`BuisDetectExistingWizard` | 129 (0x81) | Exported Function | 0x0000000180001590 | 0x00001590
`BuisCreateProxyObject` | 128 (0x80) | Exported Function | 0x0000000180001490 | 0x00001490
`private: long __cdecl BuiVolume::ProxyImplicitPauseConversion(void) __ptr64` | 98 (0x62) | Exported Function | 0x00000001800035d0 | 0x000035d0
`public: bool __cdecl VolumeFveStatus::HasSmartCardProtector(void)const __ptr64` | 51 (0x33) | Exported Function | 0x00000001800010b0 | 0x000010b0
`private: long __cdecl BuiVolume::ProxyIsAutoUnlockEnabled(void) __ptr64` | 99 (0x63) | Exported Function | 0x00000001800038f0 | 0x000038f0
`private: long __cdecl BuiVolume::ProxyLaunchWizard(unsigned short) __ptr64` | 101 (0x65) | Exported Function | 0x00000001800039f0 | 0x000039f0
`public: bool __cdecl VolumeFveStatus::HasRecoveryData(void)const __ptr64` | 49 (0x31) | Exported Function | 0x0000000180001210 | 0x00001210
`public: bool __cdecl VolumeFveStatus::HasPinProtector(void)const __ptr64` | 48 (0x30) | Exported Function | 0x0000000180001050 | 0x00001050
`public: bool __cdecl VolumeFveStatus::HasPBKDF2RecoveryPassword(void)const __ptr64` | 46 (0x2e) | Exported Function | 0x0000000180001070 | 0x00001070
`public: bool __cdecl VolumeFveStatus::HasPassphraseProtector(void)const __ptr64` | 47 (0x2f) | Exported Function | 0x00000001800010a0 | 0x000010a0
`public: bool __cdecl VolumeFveStatus::HasExternalKey(void)const __ptr64` | 45 (0x2d) | Exported Function | 0x0000000180001080 | 0x00001080
`public: bool __cdecl VolumeFveStatus::FailedDryRun(void)const __ptr64` | 30 (0x1e) | Exported Function | 0x0000000180001230 | 0x00001230
`public: bool __cdecl BuiVolume::UnlockRequiresElevation(void)const __ptr64` | 121 (0x79) | Exported Function | 0x0000000180004430 | 0x00004430
`public: bool __cdecl BuiVolume::ManagementRequiresElevation(void)const __ptr64` | 82 (0x52) | Exported Function | 0x0000000180004400 | 0x00004400
`public: bool __cdecl BuiVolume::IsFveNotifyNecessary(void)const __ptr64` | 68 (0x44) | Exported Function | 0x0000000180004340 | 0x00004340
`public: bool __cdecl BuiVolume::IsAutoUnlockEnabled(void) __ptr64` | 57 (0x39) | Exported Function | 0x0000000180002570 | 0x00002570
`public: bool __cdecl BuiVolume::HasAutoUnlockVolumesBound(void) __ptr64` | 44 (0x2c) | Exported Function | 0x0000000180002640 | 0x00002640
`public: bool __cdecl BuiVolume::CanBeResumed(void)const __ptr64` | 20 (0x14) | Exported Function | 0x00000001800043d0 | 0x000043d0
`public: __cdecl VolumeFveStatus::VolumeFveStatus(unsigned long,unsigned __int64,long,enum _FVE_WIPING_STATE) __ptr64` | 4 (0x4) | Exported Function | 0x0000000180001010 | 0x00001010
`public: __cdecl BuiVolume::~BuiVolume(void) __ptr64` | 5 (0x5) | Exported Function | 0x0000000180001a70 | 0x00001a70
`public: __cdecl BuiVolume::BuiVolume(void) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180001940 | 0x00001940
`public: __cdecl BuiVolume::BuiVolume(bool) __ptr64` | 2 (0x2) | Exported Function | 0x00000001800019a0 | 0x000019a0
`protected: __cdecl VolumeFveStatus::VolumeFveStatus(void) __ptr64` | 3 (0x3) | Exported Function | 0x00000001800012e0 | 0x000012e0
`private: void __cdecl BuiVolume::InitMembers(void) __ptr64` | 56 (0x38) | Exported Function | 0x0000000180001a10 | 0x00001a10
`private: long __cdecl BuiVolume::ProxyUpgradeVolume(void) __ptr64` | 112 (0x70) | Exported Function | 0x0000000180003d50 | 0x00003d50
`private: long __cdecl BuiVolume::ProxyUnlockVolumeWithSmartCard(struct HWND__ * __ptr64,int * __ptr64) __ptr64` | 111 (0x6f) | Exported Function | 0x0000000180003740 | 0x00003740
`private: long __cdecl BuiVolume::ProxyUnlockVolumeWithPassword(unsigned short const * __ptr64,int * __ptr64) __ptr64` | 110 (0x6e) | Exported Function | 0x0000000180003650 | 0x00003650
`private: long __cdecl BuiVolume::ProxyUnlockVolumeWithPassphrase(unsigned short const * __ptr64,int * __ptr64) __ptr64` | 109 (0x6d) | Exported Function | 0x00000001800036f0 | 0x000036f0
`private: long __cdecl BuiVolume::ProxyUnlockVolumeWithKey(unsigned short const * __ptr64,int * __ptr64) __ptr64` | 108 (0x6c) | Exported Function | 0x00000001800036a0 | 0x000036a0
`private: long __cdecl BuiVolume::ProxyServiceDiscoveryVolume(void) __ptr64` | 107 (0x6b) | Exported Function | 0x0000000180003ae0 | 0x00003ae0
`private: long __cdecl BuiVolume::ProxyResumeConversion(void) __ptr64` | 106 (0x6a) | Exported Function | 0x0000000180003610 | 0x00003610
`private: long __cdecl BuiVolume::ProxyRemoveSmartCard(bool) __ptr64` | 105 (0x69) | Exported Function | 0x0000000180003c70 | 0x00003c70
`private: long __cdecl BuiVolume::ProxyRemovePassphrase(void) __ptr64` | 104 (0x68) | Exported Function | 0x0000000180003b60 | 0x00003b60
`private: long __cdecl BuiVolume::ProxyPauseConversion(void) __ptr64` | 103 (0x67) | Exported Function | 0x0000000180003590 | 0x00003590
`private: long __cdecl BuiVolume::ProxyNeedsDiscoveryVolumeUpdate(int * __ptr64) __ptr64` | 102 (0x66) | Exported Function | 0x0000000180003b20 | 0x00003b20
`private: long __cdecl BuiVolume::ProxyLaunchUpdate(void) __ptr64` | 100 (0x64) | Exported Function | 0x0000000180003aa0 | 0x00003aa0
`public: void __cdecl BuiVolume::SuspendStatusRefreshing(void) __ptr64` | 120 (0x78) | Exported Function | 0x0000000180001ed0 | 0x00001ed0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: BdeUi.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/4f41351146c6e14b439abe5c0a7c53082cd7c72add996ec5ab92df45a32f78f2/detection/





MIT License. Copyright (c) 2020 Strontic.


