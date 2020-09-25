---
title: procexp64.exe | Sysinternals Process Explorer
excerpt: What is procexp64.exe?
---

# procexp64.exe 

* File Path: `C:\SysinternalsSuite\procexp64.exe`
* Description: Sysinternals Process Explorer

## Hashes

Type | Hash
-- | --
MD5 | `6A36347F94713B99C0FC103C6F205719`
SHA1 | `6798D393958D4CD23709DA573B8522DF04897D4E`
SHA256 | `0E76203802A524BECD00392518A1B9CEA5E6CDDB8A6CF1B43DCA4290F67C0305`
SHA384 | `2EEBC32EA47E5637A8F43FEE51522820EA0F31C08E9CBF2C5C31D5E389CA3680EE33239D314AB8780F164471A2C12B43`
SHA512 | `B47CBEC2346F27008C9E0870A4B704879957908ED422D4E19AE1AA75EE5D287CFFC937131174A664D37CC1602A2A81DADC04393AC6F2A7EC279A1F8EA2A660A3`
SSDEEP | `24576:VK8dbhH8s48SH3nc3zaBzz1pr+kAUXs8J/xZs:Vj5j/gXYWZz1gXU8a`
IMP | `5661DF91E0ADEA62BC4B6DF68CC4048E`
PESHA1 | `7F62C723E0D8F7A90957E26FD8651FDF3662AC17`
PE256 | `979055B9E13CA7F174716E978796E167F52BFEE0ADF2231F7394712B9A79270F`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\aclui.dll.mui | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21 | File
(RW-)   C:\xCyclopedia | File
(RWD)   C:\Windows\System32\perfc009.dat | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\procexp64.exe |
C:\Windows\SYSTEM32\IPHLPAPI.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\SETUPAPI.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\WS2_32.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Procexp.exe
* Product Name: Process Explorer
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 16.32
* Product Version: 16.32
* Language: English (United States)
* Legal Copyright: Copyright  1998-2020 Mark Russinovich 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/62
* VirusTotal Link: https://www.virustotal.com/gui/file/0e76203802a524becd00392518a1b9cea5e6cddb8a6cf1b43dca4290f67c0305/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\SysinternalsSuite\procexp.exe](procexp.exe-4BEB112371B140401E8602529735EA5D.md) | 55

## Possible Misuse

*The following table contains possible examples of `procexp64.exe` being misused. While `procexp64.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_lsass_dump_generic.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_lsass_dump_generic.yml) | `- '\procexp64.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\procexp64.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_procexplorer_driver_created_in_tmp_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_susp_procexplorer_driver_created_in_tmp_folder.yml) | `- '*\procexp64.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cred_dump_lsass_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_cred_dump_lsass_access.yml) | `- '\procexp64.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_service_installed.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_susp_service_installed.yml) | `- '*\procexp64.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


