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
MD5 | `380B6AA8DE133A523F008E1C78EBADA0`
SHA1 | `EAD6AB9F677D771D426A17C58C95A5CA7E7D69FC`
SHA256 | `E0D2C66CC92A80C77AB29A56641505036130A8B01BCBAFB866E28729F4985E4A`
SHA384 | `2A7184793E98A27DD6F48D44E5E7DC980943E8A95BBD77EF92C4E8086D7DC274E2FA54731EF947732EC80ADDFC0B6165`
SHA512 | `2753A27B11141DCC65623365A9579142FAE802E40FAD564BC3B98C14D761551A101E1A08EAC53575DA4158F18A29E76976F21BDBB2532FDC2D1D8041F2EE3A1B`
SSDEEP | `1536:A2S4/WRs5y2pLmUBdQyehkFnozHNWWOujzz9Zg5ooum6eEhdqv16G9jWbOMMjGyX:vTo2RmUBdQyeCnojNWWOu5ZuoouJGtgi`
IMP | `CAEB128D8391C47393ACE4DC25CDCF6B`
PESHA1 | `2A0FF6F7EB4AC815D9B4B50791CAD5BD0893C65F`
PE256 | `F87B7C294A034F269789F29ADD14B1E6C898B9AA436AD8E9C559310694F0CECA`

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
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1110_none_60b5254171f9507e | File
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
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: provtool
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.844 (WinBuild.160101.0800)
* Product Version: 10.0.19041.844
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/e0d2c66cc92a80c77ab29a56641505036130a8b01bcbafb866e28729f4985e4a/detection


## Possible Misuse

*The following table contains possible examples of `provtool.exe` being misused. While `provtool.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\provtool.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


