---
title: provtool.exe | Provisioning package runtime processing tool
excerpt: What is provtool.exe?
---

# provtool.exe 

* File Path: `C:\Windows\system32\provtool.exe`
* Description: Provisioning package runtime processing tool

## Hashes

Type | Hash
-- | --
MD5 | `B62067B26775BDF072C328246E25AA89`
SHA1 | `4D7895566E3DC4E5600C225FBDA558DF9F37B2E1`
SHA256 | `F643689F807C0666EC44E9D9B3BD583F1254049DDDAD0758235EE5C027352CFE`
SHA384 | `3CBB49B685B57504D582E15271BAC465A89BE4577D95E39307F8C72521198E641BA85CE05B77F666E8DC6C19C716B758`
SHA512 | `FBEE96CFB888B1E45A572DCFBD4E471A4FD848495D62CEA0A371E3F7077A3F9476FB8E03485DF5397FA66CDF74952CEAA40D33C63818E32359AB1E168FAAD982`
SSDEEP | `3072:+ippC67yMMiFWCi7rvzMtfTtu/OTh22veh7MVi:+rYyMMiFWCi7rvItfTxlZehAV`
IMP | `6768183691759CB6C8852BF74C7E52F3`
PESHA1 | `BABDD2BEFA65E93926B858AB770C4DF2004E4ADA`
PE256 | `944A34F08A135C94A0FFD6B6BD76B3A10C7C167DD30C48EB42945B6B54E356B9`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\apppatch\DirectXApps_FOD.sdb | File
(R-D)   C:\Windows\System32\en-US\dui70.dll.mui | File
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(R-D)   C:\Windows\System32\en-US\provplatformdesktop.dll.mui | File
(R-D)   C:\Windows\System32\en-US\Windows.UI.Immersive.dll.mui | File
(R-D)   C:\Windows\SystemResources\Windows.UI.Immersive.dll.mun | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21 | File
(RWD)   C:\Windows\Fonts\segoeuisl.ttf | File
(RWD)   C:\Windows\Fonts\seguisb.ttf | File
(RWD)   C:\Windows\Fonts\seguisym.ttf | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\SessionImmersiveColorPreference | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\SYSTEM32\cryptsp.dll |
C:\Windows\system32\DMCmnUtils.dll |
C:\Windows\system32\dmcommandlineutils.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\system32\msvcp110_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\profapi.dll |
C:\Windows\system32\provtool.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: provtool
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.508 (WinBuild.160101.0800)
* Product Version: 10.0.19041.508
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/f643689f807c0666ec44e9d9b3bd583f1254049dddad0758235ee5c027352cfe/detection


## Possible Misuse

*The following table contains possible examples of `provtool.exe` being misused. While `provtool.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\provtool.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


