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

Function Name | Ordinal | Type
-- | -- | --
`public: bool __cdecl VolumeFveStatus::NeedsRestart(void)const __ptr64` | 85 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsWiping(void)const __ptr64` | 79 | Exported Function
`public: class VolumeFveStatus & __ptr64 __cdecl VolumeFveStatus::operator=(class VolumeFveStatus && __ptr64) __ptr64` | 7 | Exported Function
`public: class BuiVolume & __ptr64 __cdecl BuiVolume::operator=(class BuiVolume const & __ptr64) __ptr64` | 6 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsRoamingDevice(void)const __ptr64` | 76 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsPreProvisioned(void)const __ptr64` | 75 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsUnknownFveVersion(void)const __ptr64` | 78 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsSecure(void)const __ptr64` | 77 | Exported Function
`public: long __cdecl BuiVolume::Decrypt(struct HWND__ * __ptr64) __ptr64` | 23 | Exported Function
`public: long __cdecl BuiVolume::AttemptAutoUnlock(void) __ptr64` | 11 | Exported Function
`public: long __cdecl BuiVolume::DisableAutoUnlock(void) __ptr64` | 26 | Exported Function
`public: long __cdecl BuiVolume::Disable(struct HWND__ * __ptr64) __ptr64` | 25 | Exported Function
`public: double __cdecl BuiVolume::GetConvertedPercent(void)const __ptr64` | 34 | Exported Function
`public: class VolumeFveStatus & __ptr64 __cdecl VolumeFveStatus::operator=(class VolumeFveStatus const & __ptr64) __ptr64` | 8 | Exported Function
`public: long __cdecl BuiVolume::AddSmartCard(struct HWND__ * __ptr64) __ptr64` | 9 | Exported Function
`public: double __cdecl BuiVolume::GetWipedPercent(void)const __ptr64` | 43 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsDecrypting(void)const __ptr64` | 63 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsDecrypted(void)const __ptr64` | 62 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsEDriveVolume(void)const __ptr64` | 65 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsDisabled(void)const __ptr64` | 64 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsConverting(void)const __ptr64` | 58 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasTpmProtector(void)const __ptr64` | 53 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsDEAutoProvisioned(void)const __ptr64` | 61 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsCsvMetadataVolume(void)const __ptr64` | 59 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsOsVolume(void)const __ptr64` | 72 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsOsCriticalVolume(void)const __ptr64` | 71 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsPaused(void)const __ptr64` | 74 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsPartiallyConverted(void)const __ptr64` | 73 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsEncrypting(void)const __ptr64` | 67 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsEncrypted(void)const __ptr64` | 66 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsOn(void)const __ptr64` | 70 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsLocked(void)const __ptr64` | 69 | Exported Function
`public: long __cdecl BuiVolume::EnableAutoUnlock(void) __ptr64` | 29 | Exported Function
`public: static long __cdecl BuiVolume::GetAllVolumes(struct _BuiVolumeNode * __ptr64 * __ptr64)` | 33 | Exported Function
`public: long __cdecl VolumeFveStatus::GetLastConvertStatus(void)const __ptr64` | 37 | Exported Function
`public: static unsigned int const BuiVolume::NO_DRIVE_LETTER` | 83 | Exported Function
`public: static long __cdecl BuiVolume::GetOsVolume(class BuiVolume * __ptr64 * __ptr64)` | 38 | Exported Function
`public: long __cdecl BuiVolume::UnlockWithPassword(unsigned short const * __ptr64,int * __ptr64) __ptr64` | 124 | Exported Function
`public: long __cdecl BuiVolume::UnlockWithPassphrase(unsigned short const * __ptr64,int * __ptr64) __ptr64` | 123 | Exported Function
`public: long __cdecl BuiVolume::UpgradeVolume(void) __ptr64` | 126 | Exported Function
`public: long __cdecl BuiVolume::UnlockWithSmartCard(struct HWND__ * __ptr64,int * __ptr64) __ptr64` | 125 | Exported Function
`public: void __cdecl BuiVolume::ResumeStatusRefreshing(void) __ptr64` | 117 | Exported Function
`public: void __cdecl BuiVolume::ClearProxyObject(void) __ptr64` | 22 | Exported Function
`public: void __cdecl BuiVolume::SuspendStatusRefreshing(void) __ptr64` | 120 | Exported Function
`public: void __cdecl BuiVolume::SetProxyObject(struct IDispatch * __ptr64) __ptr64` | 119 | Exported Function
`public: unsigned __int64 __cdecl VolumeFveStatus::GetExtendedFlags(void)const __ptr64` | 36 | Exported Function
`public: static void __cdecl BuiVolume::DeleteVolumeList(struct _BuiVolumeNode * __ptr64 * __ptr64)` | 24 | Exported Function
`public: unsigned long __cdecl VolumeFveStatus::GetStatusFlags(void)const __ptr64` | 41 | Exported Function
`public: unsigned long __cdecl BuiVolume::GetWipeCount(void)const __ptr64` | 42 | Exported Function
`public: long __cdecl BuiVolume::IsCurrentPINEnhanced(int * __ptr64) __ptr64` | 60 | Exported Function
`public: long __cdecl BuiVolume::Init(unsigned short * __ptr64) __ptr64` | 55 | Exported Function
`public: long __cdecl BuiVolume::LaunchWizard(unsigned short) __ptr64` | 81 | Exported Function
`public: long __cdecl BuiVolume::LaunchUpdate(void) __ptr64` | 80 | Exported Function
`public: long __cdecl BuiVolume::GetPasswordBackupTypes(unsigned short const * __ptr64,unsigned long * __ptr64) __ptr64` | 39 | Exported Function
`public: long __cdecl BuiVolume::GetDescription(unsigned short * __ptr64 * __ptr64) __ptr64` | 35 | Exported Function
`public: long __cdecl BuiVolume::ImplicitPauseConversion(void) __ptr64` | 54 | Exported Function
`public: long __cdecl BuiVolume::GetPasswordId(unsigned short * __ptr64 * __ptr64) __ptr64` | 40 | Exported Function
`public: long __cdecl BuiVolume::ResumeConversion(void) __ptr64` | 116 | Exported Function
`public: long __cdecl BuiVolume::RemoveSmartCard(bool) __ptr64` | 115 | Exported Function
`public: long __cdecl BuiVolume::UnlockWithKey(unsigned short const * __ptr64,int * __ptr64) __ptr64` | 122 | Exported Function
`public: long __cdecl BuiVolume::ServiceDiscoveryVolume(void) __ptr64` | 118 | Exported Function
`public: long __cdecl BuiVolume::PauseConversion(void) __ptr64` | 86 | Exported Function
`public: long __cdecl BuiVolume::NeedsDiscoveryVolumeUpdate(int * __ptr64) __ptr64` | 84 | Exported Function
`public: long __cdecl BuiVolume::RemovePassphrase(void) __ptr64` | 114 | Exported Function
`public: long __cdecl BuiVolume::RefreshStatus(bool) __ptr64` | 113 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasStartupKeyProtector(void)const __ptr64` | 52 | Exported Function
`private: long __cdecl BuiVolume::ProxyAttemptAutoUnlock(void) __ptr64` | 89 | Exported Function
`private: long __cdecl BuiVolume::ProxyAreVolumesBound(void) __ptr64` | 88 | Exported Function
`private: long __cdecl BuiVolume::ProxyDisable(struct HWND__ * __ptr64) __ptr64` | 91 | Exported Function
`private: long __cdecl BuiVolume::ProxyDecrypt(struct HWND__ * __ptr64) __ptr64` | 90 | Exported Function
`private: long __cdecl BuiVolume::FindMountPoint(void) __ptr64` | 31 | Exported Function
`private: long __cdecl BuiVolume::Dispatch(long,struct tagDISPPARAMS * __ptr64,struct tagVARIANT * __ptr64) __ptr64` | 28 | Exported Function
`private: long __cdecl BuiVolume::ProxyAddSmartCard(struct HWND__ * __ptr64) __ptr64` | 87 | Exported Function
`private: long __cdecl BuiVolume::FormatNameAndMountPoint(void) __ptr64` | 32 | Exported Function
`private: long __cdecl BuiVolume::ProxyGetProcessId(unsigned long * __ptr64) __ptr64` | 97 | Exported Function
`private: long __cdecl BuiVolume::ProxyGetPasswordId(unsigned short * __ptr64 * __ptr64) __ptr64` | 96 | Exported Function
`private: long __cdecl BuiVolume::ProxyIsAutoUnlockEnabled(void) __ptr64` | 99 | Exported Function
`private: long __cdecl BuiVolume::ProxyImplicitPauseConversion(void) __ptr64` | 98 | Exported Function
`private: long __cdecl BuiVolume::ProxyEnableAutoUnlock(void) __ptr64` | 93 | Exported Function
`private: long __cdecl BuiVolume::ProxyDisableAutoUnlock(void) __ptr64` | 92 | Exported Function
`private: long __cdecl BuiVolume::ProxyGetPasswordBackupTypes(unsigned short const * __ptr64,unsigned long * __ptr64) __ptr64` | 95 | Exported Function
`private: long __cdecl BuiVolume::ProxyGetDescription(unsigned short * __ptr64 * __ptr64) __ptr64` | 94 | Exported Function
`private: bool __cdecl BuiVolume::CanRefreshStatus(void)const __ptr64` | 21 | Exported Function
`BuisIsHardwareReadyForConversion` | 131 | Exported Function
`private: long __cdecl BuiVolume::BasicDispatch(long,struct HWND__ * __ptr64,unsigned short const * __ptr64,long * __ptr64) __ptr64` | 12 | Exported Function
`private: long __cdecl BuiVolume::AllowForegroundWindowDisplay(void) __ptr64` | 10 | Exported Function
`BuisCreateProxyObject` | 128 | Exported Function
`BuisCreateElevatedProxyObject` | 127 | Exported Function
`BuisIsFipsEnabled` | 130 | Exported Function
`BuisDetectExistingWizard` | 129 | Exported Function
`private: long __cdecl BuiVolume::BasicDispatch(long,unsigned short const * __ptr64,unsigned short const * __ptr64,long * __ptr64) __ptr64` | 14 | Exported Function
`private: long __cdecl BuiVolume::BasicDispatch(long,unsigned short const * __ptr64,unsigned short const * __ptr64,int * __ptr64,long * __ptr64) __ptr64` | 13 | Exported Function
`private: long __cdecl BuiVolume::Dispatch(long,struct tagDISPPARAMS * __ptr64,long * __ptr64) __ptr64` | 27 | Exported Function
`private: long __cdecl BuiVolume::BasicDispatch(long,unsigned short const * __ptr64,unsigned short const * __ptr64,unsigned long * __ptr64) __ptr64` | 15 | Exported Function
`private: long __cdecl BuiVolume::BasicDispatch(long,unsigned short const * __ptr64,long * __ptr64) __ptr64` | 17 | Exported Function
`private: long __cdecl BuiVolume::BasicDispatch(long,unsigned short const * __ptr64,int * __ptr64,long * __ptr64) __ptr64` | 16 | Exported Function
`private: long __cdecl BuiVolume::BasicDispatch(long,unsigned short const * __ptr64,unsigned short * __ptr64 * __ptr64) __ptr64` | 18 | Exported Function
`private: long __cdecl BuiVolume::BasicDispatch(long,unsigned short const * __ptr64,struct tagVARIANT * __ptr64) __ptr64` | 19 | Exported Function
`private: long __cdecl BuiVolume::ProxyLaunchUpdate(void) __ptr64` | 100 | Exported Function
`public: bool __cdecl BuiVolume::IsFveNotifyNecessary(void)const __ptr64` | 68 | Exported Function
`public: bool __cdecl BuiVolume::IsAutoUnlockEnabled(void) __ptr64` | 57 | Exported Function
`public: bool __cdecl BuiVolume::UnlockRequiresElevation(void)const __ptr64` | 121 | Exported Function
`public: bool __cdecl BuiVolume::ManagementRequiresElevation(void)const __ptr64` | 82 | Exported Function
`public: __cdecl VolumeFveStatus::VolumeFveStatus(unsigned long,unsigned __int64,long,enum _FVE_WIPING_STATE) __ptr64` | 4 | Exported Function
`public: __cdecl BuiVolume::~BuiVolume(void) __ptr64` | 5 | Exported Function
`public: bool __cdecl BuiVolume::HasAutoUnlockVolumesBound(void) __ptr64` | 44 | Exported Function
`public: bool __cdecl BuiVolume::CanBeResumed(void)const __ptr64` | 20 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasRecoveryData(void)const __ptr64` | 49 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasPinProtector(void)const __ptr64` | 48 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasSmartCardProtector(void)const __ptr64` | 51 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasRecoveryPassword(void)const __ptr64` | 50 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasExternalKey(void)const __ptr64` | 45 | Exported Function
`public: bool __cdecl VolumeFveStatus::FailedDryRun(void)const __ptr64` | 30 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasPBKDF2RecoveryPassword(void)const __ptr64` | 46 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasPassphraseProtector(void)const __ptr64` | 47 | Exported Function
`private: long __cdecl BuiVolume::ProxyResumeConversion(void) __ptr64` | 106 | Exported Function
`private: long __cdecl BuiVolume::ProxyRemoveSmartCard(bool) __ptr64` | 105 | Exported Function
`private: long __cdecl BuiVolume::ProxyUnlockVolumeWithKey(unsigned short const * __ptr64,int * __ptr64) __ptr64` | 108 | Exported Function
`private: long __cdecl BuiVolume::ProxyServiceDiscoveryVolume(void) __ptr64` | 107 | Exported Function
`private: long __cdecl BuiVolume::ProxyNeedsDiscoveryVolumeUpdate(int * __ptr64) __ptr64` | 102 | Exported Function
`private: long __cdecl BuiVolume::ProxyLaunchWizard(unsigned short) __ptr64` | 101 | Exported Function
`private: long __cdecl BuiVolume::ProxyRemovePassphrase(void) __ptr64` | 104 | Exported Function
`private: long __cdecl BuiVolume::ProxyPauseConversion(void) __ptr64` | 103 | Exported Function
`protected: __cdecl VolumeFveStatus::VolumeFveStatus(void) __ptr64` | 3 | Exported Function
`private: void __cdecl BuiVolume::InitMembers(void) __ptr64` | 56 | Exported Function
`public: __cdecl BuiVolume::BuiVolume(void) __ptr64` | 1 | Exported Function
`public: __cdecl BuiVolume::BuiVolume(bool) __ptr64` | 2 | Exported Function
`private: long __cdecl BuiVolume::ProxyUnlockVolumeWithPassword(unsigned short const * __ptr64,int * __ptr64) __ptr64` | 110 | Exported Function
`private: long __cdecl BuiVolume::ProxyUnlockVolumeWithPassphrase(unsigned short const * __ptr64,int * __ptr64) __ptr64` | 109 | Exported Function
`private: long __cdecl BuiVolume::ProxyUpgradeVolume(void) __ptr64` | 112 | Exported Function
`private: long __cdecl BuiVolume::ProxyUnlockVolumeWithSmartCard(struct HWND__ * __ptr64,int * __ptr64) __ptr64` | 111 | Exported Function


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


