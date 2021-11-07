---
title: w3wp.exe | IIS Worker Process
excerpt: What is w3wp.exe?
---

# w3wp.exe 

* File Path: `C:\Windows\system32\inetsrv\w3wp.exe`
* Description: IIS Worker Process

## Hashes

Type | Hash
-- | --
MD5 | `AB6D6849B3B8B8F4A292DC76EBB1243F`
SHA1 | `54443C275EDDD9BBE75C6D47CF9C24076B5D785C`
SHA256 | `A0A37FDE4D8CD7385E819AFA967BC525231C2F166C38591532D8FEEAB94E40DA`
SHA384 | `623AEC4602A36447576C259D1865650052EC3C533CFE541C5D101AC7203E4EFAF37C45B22D23B6250533C6A64B91B619`
SHA512 | `EAE9436AB3896AF2F3E1F11305DA1955116C777F3627D333E99378E7702865A480A5268E3D4A41197C19088509056F47629C686CA391A6DDCA9772DF9986911A`
SSDEEP | `384:zHOsMck/6v+UVWcrqNYOmOMC2nUxVYXZfw8gtUUMkHutQdKWSuY:zHLMck/q+U0WqNgOt2oVAZfMaUMkOty4`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: C:\Windows\system32\inetsrv\w3wp.exe -s <site id> | -h [application host file]  
                           -w <optional root web.config file>  
                           -in <optional instance name>  
 
	-debug 
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

```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: w3wp.exe.mui
* Product Name: Internet Information Services
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
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


