---
title: provtool.exe | Provisioning package runtime processing tool
excerpt: What is provtool.exe?
---

# provtool.exe 

* File Path: `C:\WINDOWS\system32\provtool.exe`
* Description: Provisioning package runtime processing tool

## Hashes

Type | Hash
-- | --
MD5 | `EC12EC63655B2B923B5239E36C8F1318`
SHA1 | `608D945A13DD89C657F0DC48B27ED391FEF4AD2A`
SHA256 | `E588C074E63FF29DB81E5E1730414C34482F3DD49BEEB9E0BBD2CF6E82BD2B0A`
SHA384 | `B7B6E42D75BC6B1662132311FB53FF99C127AD5BC2D39591684D319FD1EF382DE90DCB56E57F84F5EF6FC8440E465FA9`
SHA512 | `F0EFA0D2E7EC49102B530ACDB3F022F3E84EAC2C00DB130CFEA3CD9BFA1862B2A47EB8FB7798861D6B9F026E7BD0D8458E0E4FF093D3A29CB8827DAE2CEC88E3`
SSDEEP | `3072:XlJ7whpmqzmw5ZSuKcVAzLx0VOrdaBh1T61/z:XlJUhYqzmw5RKcVAHxYe6DT61`
IMP | `32A66F804CDBF1298DD7E3BAE661D502`
PESHA1 | `37B298123BFE5BC26BAD9CFC06FCCDD971462D52`
PE256 | `412290C2620E3839996074BAB85DB2D6540EEFFB20B76A12E246C6771170F679`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\dui70.dll.mui | File
(R-D)   C:\Windows\System32\en-US\provplatformdesktop.dll.mui | File
(R-D)   C:\Windows\System32\en-US\Windows.UI.Immersive.dll.mui | File
(R-D)   C:\Windows\SystemResources\Windows.UI.Immersive.dll.mun | File
(RW-)   C:\Windows\System32 | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.22000.120_none_9d947278b86cc467 | File
(RWD)   C:\Windows\Fonts\segoeuisl.ttf | File
(RWD)   C:\Windows\Fonts\seguisb.ttf | File
(RWD)   C:\Windows\Fonts\seguisym.ttf | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\SessionImmersiveColorPreference | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\combase.dll |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\msvcp110_win.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\provtool.exe |
C:\WINDOWS\System32\sechost.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: provtool
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.65 (WinBuild.160101.0800)
* Product Version: 10.0.22000.65
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/e588c074e63ff29db81e5e1730414c34482f3dd49beeb9e0bbd2cf6e82bd2b0a/detection


## Possible Misuse

*The following table contains possible examples of `provtool.exe` being misused. While `provtool.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\provtool.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


