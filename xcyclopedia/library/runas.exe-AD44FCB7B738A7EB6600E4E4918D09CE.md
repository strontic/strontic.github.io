
# runas.exe 

* File Path: `C:\WINDOWS\SysWOW64\runas.exe`
* Description: Run As Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `AD44FCB7B738A7EB6600E4E4918D09CE`
SHA1 | `7501BE58AC9E04FF319E6EE4D5165750C65AAFF7`
SHA256 | `3AD838CF790C9BEB95CB3A9CA5126BE0F99ED59A8A4C9DB36F9484C43C481F61`
SHA384 | `2D21A7C526546CEFC317ACA373E0CB4D74D2E430B7402FF20F93B3AF630A5F4E76F35903BEB6534781BC34BF5FD5EFAF`
SHA512 | `D740CF4625184AC8E090E1D761F37064D01803AE8FA2BFB18F0600128A6F75301AB7F105E218555F5B52DC83C513995BBC16B74D7DB727E8855111499C9CD255`
SSDEEP | `384:u2CYsv42S8WuW8kTqMgTscYfHu9WLOWHbPy:ulrSJNuMmYfHuGLa`

## Runtime Data

### Usage (stdout):
```Batchfile

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

* Original Filename: RUNAS.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `runas.exe` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_overpass_the_hash.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_overpass_the_hash.yml) | `    - Runas command-line tool using /netonly parameter` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_malicious_commandlets.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_malicious_commandlets.yml) | `            - "*Invoke-RunAs*"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `            - runas.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_powershell_exploit_scripts.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_powershell_exploit_scripts.yml) | `            - '*\Invoke-RunAs.ps1'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_uac_bypass_sdclt.yml) | `description: Detects changes to HKCU:\Software\Classes\exefile\shell\runas\command\isolatedCommand` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_uac_bypass_sdclt.yml) | `        TargetObject: 'HKU\\*_Classes\exefile\shell\runas\command\isolatedCommand'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `lpe-runas-flags` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `runas` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


