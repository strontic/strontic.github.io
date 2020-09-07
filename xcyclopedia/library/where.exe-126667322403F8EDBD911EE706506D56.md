---
title: where.exe | Where - Lists location of files
---

# where.exe 

* File Path: `C:\windows\system32\where.exe`
* Description: Where - Lists location of files

## Hashes

Type | Hash
-- | --
MD5 | `126667322403F8EDBD911EE706506D56`
SHA1 | `E620FDA76D2437227AEC4F2D2645C1D768C8453D`
SHA256 | `7BD13C1348F438E3EF20A69D46316EBBF2AF2E73DA23F643E38CF0290785560E`
SHA384 | `D52139649D01BF12EC8A55DE0F1AC28A26AB058B2BF738B4F7ED2E09CC5B3441A0597E0552707D206B27454495F5A3F3`
SHA512 | `3262FE0CB7DBADE3E996BCD4EDD25354FC3ECF08C126EF9F9778B2C2F41A7FCD79B5AD3C20CE1CE1FA63BC317BCCEE3260E68BFB42760984A9DE5483D927C54B`
SSDEEP | `768:U3/ZgmxhIU80dLLmbmiuNFon/EMqzPiHDOgcU9DaxxTo:U3/ZhXNdubmZNdiCgTexpo`

## Signature

* Status: The file C:\windows\system32\where.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: where.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `where.exe` being misused. While `where.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if ((cmd.exe /c "where.exe Sysmon.exe 2> nul \| findstr Sysmon 2> nul") -or (Test-Path $env:Temp\Sysmon\Sysmon.exe)) { exit 0 } else { exit 1 }  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if(cmd.exe /c "where.exe Sysmon.exe 2> nul \| findstr Sysmon 2> nul") { C:\Windows\Sysmon.exe -accepteula -i } else | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


