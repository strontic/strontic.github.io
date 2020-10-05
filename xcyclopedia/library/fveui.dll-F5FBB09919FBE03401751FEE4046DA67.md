---
title: fveui.dll | BitLocker Drive Encryption UI
excerpt: What is fveui.dll?
---

# fveui.dll 

* File Path: `C:\Windows\system32\fveui.dll`
* Description: BitLocker Drive Encryption UI

## Hashes

Type | Hash
-- | --
MD5 | `F5FBB09919FBE03401751FEE4046DA67`
SHA1 | `D37A51DA877D6B06873C4F75D3DA722BFECB1F97`
SHA256 | `C2B80BEE8FA34AB31182A56AB37092BA505FE336616108880671B574F87E47D1`
SHA384 | `F6C8AE3809893F39D266CDA16E055DD3A7E28D1FD718B4F84B84683248A8FC4014CB1D45D7C729E10DE594B5E5A5474F`
SHA512 | `3903424DC55D02DC632CDB741D38FB68EB33173593ACAEC960563FBE0486B6C9E9DB52746A4434E18FFD7CBA602ACE01FB0A62873097038C569F19E3CD5887E3`
SSDEEP | `6144:k2MCBkfasytnLyJ4DpDfTQ9hkyVs7nyatGt+SYF:NMCyfasQnoKDfTPkH+S+`
IMP | `D0BFAA036380A05E8E3A47AC1BFE9659`
PESHA1 | `50D8E3ED8135AC011A36F6A2FA8257E6C8EBD1B9`
PE256 | `4E486A488011A3D99C905ED56417D1D185E21B419691BDB0F0A0329764E46277`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: bool __cdecl VolumeFveStatus::IsPartiallyConverted(void)const __ptr64` | 32 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsOsVolume(void)const __ptr64` | 31 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsPaused(void)const __ptr64` | 33 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsRoamingDevice(void)const __ptr64` | 35 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsPreProvisioned(void)const __ptr64` | 34 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsOsCriticalVolume(void)const __ptr64` | 30 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsEncrypted(void)const __ptr64` | 26 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsEDriveVolume(void)const __ptr64` | 25 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsEncrypting(void)const __ptr64` | 27 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsOn(void)const __ptr64` | 29 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsLocked(void)const __ptr64` | 28 | Exported Function
`public: long __cdecl VolumeFveStatus::GetLastConvertStatus(void)const __ptr64` | 8 | Exported Function
`public: class VolumeFveStatus & __ptr64 __cdecl VolumeFveStatus::operator=(class VolumeFveStatus const & __ptr64) __ptr64` | 5 | Exported Function
`public: static unsigned int const BuiVolume::NO_DRIVE_LETTER` | 39 | Exported Function
`public: unsigned long __cdecl VolumeFveStatus::GetStatusFlags(void)const __ptr64` | 9 | Exported Function
`public: unsigned __int64 __cdecl VolumeFveStatus::GetExtendedFlags(void)const __ptr64` | 7 | Exported Function
`public: class VolumeFveStatus & __ptr64 __cdecl VolumeFveStatus::operator=(class VolumeFveStatus && __ptr64) __ptr64` | 4 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsUnknownFveVersion(void)const __ptr64` | 37 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsSecure(void)const __ptr64` | 36 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsWiping(void)const __ptr64` | 38 | Exported Function
`public: class BuiVolume & __ptr64 __cdecl BuiVolume::operator=(class BuiVolume const & __ptr64) __ptr64` | 3 | Exported Function
`public: bool __cdecl VolumeFveStatus::NeedsRestart(void)const __ptr64` | 40 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsDisabled(void)const __ptr64` | 24 | Exported Function
`public: bool __cdecl VolumeFveStatus::FailedDryRun(void)const __ptr64` | 6 | Exported Function
`public: __cdecl VolumeFveStatus::VolumeFveStatus(unsigned long,unsigned __int64,long,enum _FVE_WIPING_STATE) __ptr64` | 2 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasExternalKey(void)const __ptr64` | 10 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasPBKDF2RecoveryPassword(void)const __ptr64` | 11 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasPassphraseProtector(void)const __ptr64` | 12 | Exported Function
`protected: __cdecl VolumeFveStatus::VolumeFveStatus(void) __ptr64` | 1 | Exported Function
`DllGetClassObject` | 42 | Exported Function
`DllCanUnloadNow` | 41 | Exported Function
`FveuiEnumSmartCardCerts` | 43 | Exported Function
`FveuiUserSelectSmartCard` | 45 | Exported Function
`FveuiUserSelectCert` | 44 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsCsvMetadataVolume(void)const __ptr64` | 20 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsConverting(void)const __ptr64` | 19 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsDEAutoProvisioned(void)const __ptr64` | 21 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsDecrypting(void)const __ptr64` | 23 | Exported Function
`public: bool __cdecl VolumeFveStatus::IsDecrypted(void)const __ptr64` | 22 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasTpmProtector(void)const __ptr64` | 18 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasRecoveryData(void)const __ptr64` | 14 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasPinProtector(void)const __ptr64` | 13 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasRecoveryPassword(void)const __ptr64` | 15 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasStartupKeyProtector(void)const __ptr64` | 17 | Exported Function
`public: bool __cdecl VolumeFveStatus::HasSmartCardProtector(void)const __ptr64` | 16 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FVEUI.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/c2b80bee8fa34ab31182a56ab37092ba505fe336616108880671b574f87e47d1/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\baaupdate.exe](baaupdate.exe-124495DF347DBB3FE50CAF55B211CBD9.md) | 52
[C:\WINDOWS\system32\baaupdate.exe](baaupdate.exe-1DE833E454562483BD0CD60D96B3CA0C.md) | 47
[C:\windows\system32\baaupdate.exe](baaupdate.exe-5B49CC654ADC1CE20F2756FB61C1E3A4.md) | 55
[C:\Windows\system32\baaupdate.exe](baaupdate.exe-A5BCC0E852AC6B17F3D0E6C9F95E95D4.md) | 52
[C:\Windows\system32\BdeHdCfg.exe](BdeHdCfg.exe-29B6905327F9571F99697BA8951F60D5.md) | 49
[C:\WINDOWS\system32\BdeHdCfg.exe](BdeHdCfg.exe-49993078062CFCCFE5EE1ACCF47B1EAF.md) | 44
[C:\Windows\system32\BdeHdCfg.exe](BdeHdCfg.exe-89D0572C9B53F34230C8514F6B11BD56.md) | 47
[C:\windows\system32\BdeHdCfg.exe](BdeHdCfg.exe-A0B0BD83DF86073C86D4111FDF4B82AB.md) | 49
[C:\Windows\system32\bdeunlock.exe](bdeunlock.exe-23C71245731416DD69B78A64BDB8A230.md) | 36
[C:\Windows\system32\bdeunlock.exe](bdeunlock.exe-6DF8548ED3BA2DF3C682A5E342DA7BE4.md) | 40
[C:\WINDOWS\system32\bdeunlock.exe](bdeunlock.exe-7EDA3DEC2AC9206D153AF752F20B4B92.md) | 36
[C:\windows\system32\bdeunlock.exe](bdeunlock.exe-F1422C3B0232F78BFB19B51CBC88BB50.md) | 36
[C:\Windows\system32\BitLockerWizard.exe](BitLockerWizard.exe-1F7EC0D141821C5BB3B51C054E7CA8D4.md) | 49
[C:\windows\system32\BitLockerWizard.exe](BitLockerWizard.exe-3F4811D92D68006E636245486A8D92B9.md) | 49
[C:\WINDOWS\system32\BitLockerWizard.exe](BitLockerWizard.exe-6B919B72E58391B39A09EE388FA89BBB.md) | 54
[C:\Windows\system32\BitLockerWizard.exe](BitLockerWizard.exe-A9C78F189E2111734F7E961EBE38188A.md) | 49
[C:\Windows\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-46A96812D5A434C3794F06DB978D0C19.md) | 49
[C:\Windows\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-68A4D7474F142060F46C37BCE45FABFE.md) | 52
[C:\WINDOWS\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-7B6ADCD4165DE7732C61E2381D69BEA3.md) | 49
[C:\windows\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-9F4A6D072BF84183E96E8B4D6D536D73.md) | 54
[C:\Windows\system32\fvecpl.dll](fvecpl.dll-7809069116F870A3555AE330B0AD66F3.md) | 40
[C:\Windows\system32\fvenotify.exe](fvenotify.exe-1DDE0327CAF5309EC597B21726028153.md) | 49
[C:\windows\system32\fvenotify.exe](fvenotify.exe-6A7644DD7F83120D7230C67D74C180EB.md) | 43
[C:\WINDOWS\system32\fvenotify.exe](fvenotify.exe-D7B50B5843EFD63DBAAE341B8E70856D.md) | 52
[C:\Windows\system32\fvenotify.exe](fvenotify.exe-EE3C814D1035CDCDF48E232742D6FA43.md) | 46
[C:\WINDOWS\system32\fveprompt.exe](fveprompt.exe-1B9EC98C9542EF45D511E3D003E00369.md) | 47
[C:\Windows\system32\fveprompt.exe](fveprompt.exe-1FDC5C40B2DE4167895EFFCAB0854C0C.md) | 46
[C:\Windows\system32\fveprompt.exe](fveprompt.exe-57935115ADFEC73AB98655EEA54DF706.md) | 49
[C:\windows\system32\fveprompt.exe](fveprompt.exe-D1A5A16C5C361DFC062E7ADFD3D0C49F.md) | 52
[C:\WINDOWS\system32\manage-bde.exe](manage-bde.exe-146C56E1598A4F568B6F0342A485DD84.md) | 41
[C:\Windows\system32\manage-bde.exe](manage-bde.exe-84021D418863A3E530D2E3F65F5D154C.md) | 41
[C:\Windows\system32\manage-bde.exe](manage-bde.exe-D44D57F5AAF9D5FD64EFC00C4761C304.md) | 43
[C:\windows\system32\manage-bde.exe](manage-bde.exe-F7E627DDF4C3B09BDB8954E02B4A375C.md) | 46
[C:\Windows\system32\repair-bde.exe](repair-bde.exe-0858920D41400F8C585AFE31B80FF884.md) | 50
[C:\WINDOWS\system32\repair-bde.exe](repair-bde.exe-7DE31602235A9B4A6C1EBCFB6E6E30E2.md) | 50
[C:\windows\system32\repair-bde.exe](repair-bde.exe-8A8A24256B145338E025DCD848CBC1EF.md) | 52
[C:\Windows\system32\repair-bde.exe](repair-bde.exe-9FA5C71841FDE30C7D62CC95E5389E6A.md) | 50




MIT License. Copyright (c) 2020 Strontic.


