---
title: write.exe | Windows Write
excerpt: What is write.exe?
---

# write.exe 

* File Path: `C:\Windows\SysWOW64\write.exe`
* Description: Windows Write

## Hashes

Type | Hash
-- | --
MD5 | `3D6FDBA2878656FA9ECB81F6ECE45703`
SHA1 | `1765076E0E5B008AA14D8E5FCE5DE516E68F7771`
SHA256 | `6F760002730A8CA55181EB61EB7D9764D91F236EFC602168F225CB0CD9180295`
SHA384 | `991D34705B5477BC48F30C870E33B6914AF321E0772342197062D2AA733F2946E88D54D90B54F3B83DBC85AB630F7601`
SHA512 | `F6E21B25D342D47A75ACC08A4165AA144B1DE7B0DDE0452FE9AF718D232AD76F2D1B99574890118C730F81FC2BF48F62960F3AE37276B840A419D14CA65D1D76`
SSDEEP | `96:wXEPsSNEdA+Bn9Jkp2kBjDDDGjg6GHDCMq1RDJdMi2bKveLrxuJRdlEWGOWwMj3:wXEUFdA+hyQgDCMq1hPuxu/sWGOWNj`
IMP | `B05C7142E6016FF931CDC4142BE82084`
PESHA1 | `3E45FA268DAD96B552B414AD276F655E99E46781`
PE256 | `7A13C914E51109F249B0AA11F375F5730544ACEC4DCFA6C5A3B55121CA9CF995`

## Runtime Data

### Child Processes:
wordpad.exe

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\write.exe |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: write
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/6f760002730a8ca55181eb61eb7d9764d91f236efc602168f225cb0cd9180295/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\write.exe](write.exe-B947CCA7F485F6C1156F4D02E8C9874F.md) | 43
[C:\windows\SysWOW64\write.exe](write.exe-1EFA647F97009893CC54BD677751A958.md) | 44
[C:\WINDOWS\SysWOW64\write.exe](write.exe-7FBA1268E8C8AEC66A7BF9420F54A745.md) | 65
[C:\Windows\SysWOW64\write.exe](write.exe-ED73F0253A4C10F6B7C221FF6E8BD8B4.md) | 49
[C:\Windows\write.exe](write.exe-B947CCA7F485F6C1156F4D02E8C9874F.md) | 43

## Possible Misuse

*The following table contains possible examples of `write.exe` being misused. While `write.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tracker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Tracker.yml) | `- Command: Tracker.exe /d .\calc.dll /c C:\Windows\write.exe` | 



MIT License. Copyright (c) 2020 Strontic.


