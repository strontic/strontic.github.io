---
title: w3wp.exe | IIS Worker Process
excerpt: What is w3wp.exe?
---

# w3wp.exe 

* File Path: `C:\Windows\SysWOW64\inetsrv\w3wp.exe`
* Description: IIS Worker Process

## Hashes

Type | Hash
-- | --
MD5 | `3C49492762BE5985185665A7202C4DDA`
SHA1 | `706169C6C12C24470F6F724E90314E5F3417B9EA`
SHA256 | `3FB9F0B5E922208C56707FE98133265C1676A9937ADCB7DBEABC3EB67A05C22B`
SHA384 | `9389DA69916F6E7AF3BD9BC4DDDD18107BCEC3F7D8F66FD062AD106FA4FC39805DB6296C987AAB9AAC11F0C399F91316`
SHA512 | `616437A600BB57CE16B1BAB0AF2CC003B288DB6BD8A80E6E4EC979BCD0A3C682E1F773C986D54FE36F8E15441DA58EF9719CBA09F2998AA76C723C2967221CAC`
SSDEEP | `384:U+NQJPvshyN8jfV3rC3F258eH3VwufI8p+8s09Ux0X6gwRtWSu8fyDE:U+SJPveVcFLe3+CZ+nVx0XpwRxfW`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: C:\Windows\SysWOW64\inetsrv\w3wp.exe -s <site id> | -h [application host file]  
                           -w <optional root web.config file>  
                           -in <optional instance name>  
 
	-u 
		 This option launches a worker process using the default 
		 application host config file.  By default, it will use 
		 site id 1. 
 
	-s <site id> 
		 Optional parameter to use a siteinformation from the provided 
		 site id. 
 
	or 
 
	-h [Application host config filename] 
		 Launches a worker process using the specified application host 
		 config file. 
 
	-in <Instance Name> 
		 Optional instance name to use.  Defaults to 'HWC-<PID>' 
 
	-w <Root web config filename> 
		 Optional root web config file to use. 
 
	-tt <Shutdown timeout in seconds> 
		 Optional parameter for graceful shutdown when user launched w3wp.exe directly, default 30s. 
		 Graceful shutdown will only be triggered by ctrl+break signal  
 
	-g  <Enable locale> 
		 Optional parameter for enabling locale to use user's setting on language,  
		 environ
```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: w3wp.exe
* Product Name: Internet Information Services
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `w3wp.exe` being misused. While `w3wp.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- '\w3wp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\w3wp.exe'       `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc_folder.yml) | `- '\w3wp.exe'        # https://twitter.com/gabriele_pippi/status/1206907900268072962`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `- '\w3wp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_detection.yml) | `- '\w3wp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_recon_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_recon_detection.yml) | `- '\w3wp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_spawn.yml) | `- '\w3wp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hafnium.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hafnium.yar) | $s1 = "AppPath=c:\\windows\\system32\\inetsrv\\w3wp.exe" wide fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


