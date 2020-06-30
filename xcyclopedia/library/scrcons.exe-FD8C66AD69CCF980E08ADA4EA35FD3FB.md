---
title: scrcons.exe | WMI Standard Event Consumer - scripting
---

# scrcons.exe 

* File Path: `C:\Windows\system32\wbem\scrcons.exe`
* Description: WMI Standard Event Consumer - scripting
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FD8C66AD69CCF980E08ADA4EA35FD3FB`
SHA1 | `0102A12E468DCC2B40681252E311B6AFA3C6DAB0`
SHA256 | `F96C187199362265FAC87ADB337DB242D24F9B313407646F89DA62A1ED12B6D9`
SHA384 | `83F0E50AAFBA9BD059A42EC8680A1DEA22ACB08BF042BF0A608500D73FD22AEE856442586F49470F8958429B78CC84F2`
SHA512 | `69414794881801B43855A6880159E61B0D412B192F57066D8AE820267F43D5255D2660C69A4B98F7924083DE8FC66920E67EE0AFBF3C3C780147213C876A3177`
SSDEEP | `1536:5K7eR5nv5HMyhDuihPLrFj3tkj069tuNdXSnNdGjQBBBfA1bUIzB21+nFFifj:5nnv5HMyVuiHj3tgBfUbUIV21+nFQ`

## Runtime Data

### Usage (stdout):
```Batchfile
Cannot run standalone

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ScrCons
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `scrcons.exe` being misused. While `scrcons.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `            - '*\scrcons.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_persistence_script_event_consumer_write.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_wmi_persistence_script_event_consumer_write.yml) | `        Image: 'C:\WINDOWS\system32\wbem\scrcons.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `            - '*\scrcons.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wmi_persistence_script_event_consumer.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmi_persistence_script_event_consumer.yml) | `        Image: C:\WINDOWS\system32\wbem\scrcons.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_persistence_script_event_consumer_write.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_wmi_persistence_script_event_consumer_write.yml) | `        Image: 'C:\WINDOWS\system32\wbem\scrcons.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


