---
title: sihost.exe | Shell Infrastructure Host
excerpt: What is sihost.exe?
---

# sihost.exe 

* File Path: `C:\Windows\system32\sihost.exe`
* Description: Shell Infrastructure Host

## Hashes

Type | Hash
-- | --
MD5 | `B19D63CBAF662531A3B9071372B86595`
SHA1 | `1D1AEDCFB4F5B05490084609B54908901B35BF54`
SHA256 | `C2194F45C7B614B4520ED551C88C2B32D2E0065EDCF3D7208086A1B0EC07D835`
SHA384 | `ECC0DA5C9DD4277348214DFFD82ED1E73012B23DD0C92949B70BEEC773856DF5B304736ABA6B277C1D6E22A3542303F2`
SHA512 | `F89366599D002AA16E59D76B05D43A7E2F15B5D358BD2DC417A2366BEA7554B8C51DA4F5F6001711C374DDB843AB15E9D6D0F02215149E6FA7774141D5BBEE08`
SSDEEP | `1536:teWBpMaPLTsVD5HRQdmM0YgNJfgJSSo1CTECC2s7SUyb76AgztlNm:tzBuaHsl5xm30fxTkECC2s7/yX6dlNm`
IMP | `9FFE8029F721BD904F419F82A63D59A2`
PESHA1 | `748D08F31BDB2EADCCD7C3472C45E87414BD492C`
PE256 | `6E98752C2566F049601210956055EC12F905EF9CF25A0B201C936DE49E069595`

## Runtime Data

### Child Processes:
explorer.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\system32\sihost.exe |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sihost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/c2194f45c7b614b4520ed551c88c2b32d2e0065edcf3d7208086a1b0ec07d835/detection


## Possible Misuse

*The following table contains possible examples of `sihost.exe` being misused. While `sihost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\sihost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\sihost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


