---
title: sdiagnhost.exe | Scripted Diagnostics Native Host
excerpt: What is sdiagnhost.exe?
---

# sdiagnhost.exe 

* File Path: `C:\windows\system32\sdiagnhost.exe`
* Description: Scripted Diagnostics Native Host

## Hashes

Type | Hash
-- | --
MD5 | `4946EEFDBC08E0BAD98033137502FAA6`
SHA1 | `26FE58C5AD30EFDB3FEE149813BD08B6403DD829`
SHA256 | `480AAFBF73786AFDB295F1DB4E2CC26CE962EEFB38669C14672590C5E11A3C5A`
SHA384 | `5447A2BF2C7B123DF54C4D07340E1175F1BC00876639359F42C039CB53E581C9B61D5FECE575BE54FFE6AC169D464328`
SHA512 | `5D092AE19886262BA8CC281C00BE80C57754DBA08EA1937265F3D1384F25E921930C3BD89145EC9C96AE87161953EEFC96071C0C9FC28C07177BBD8F7E99DA5A`
SSDEEP | `384:rHGcMXgvaDJmvx/E1UAUC1CnfnwzqduYRbCqrXmKWneEToQPiutWj7DW:oVQOe6Cnvx1CgXXXE5Piu6`

## Signature

* Status: The file C:\windows\system32\sdiagnhost.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: sdiagnhost.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\sdiagnhost.exe](sdiagnhost.exe-6458634E67F8AE415A0A871953C04F06.md) | 29
[C:\Windows\system32\sdiagnhost.exe](sdiagnhost.exe-6A21B1893DDE94CB87BA56111375888A.md) | 22
[C:\Windows\system32\sdiagnhost.exe](sdiagnhost.exe-9BB47FC39CB24A16A0AB0302960645BA.md) | 30

## Possible Misuse

*The following table contains possible examples of `sdiagnhost.exe` being misused. While `sdiagnhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\WINDOWS\System32\sdiagnhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\sdiagnhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_assembly_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_in_memory_assembly_execution.yml) | `- '\Windows\System32\sdiagnhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc_folder.yml) | `- '\sdiagnhost.exe'  # https://twitter.com/gN3mes1s/status/1206874118282448897`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\sdiagnhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


