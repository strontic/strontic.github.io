---
title: w3wp.exe | IIS Worker Process
---

# w3wp.exe 

* File Path: `C:\windows\system32\inetsrv\w3wp.exe`
* Description: IIS Worker Process
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `0406E327338CCEA5EF7DCF58268A8BFE`
SHA1 | `447EC979C4B2C53C21B17BD9C2F7D67A9F967108`
SHA256 | `1EB51EA7407F41BC212CC699E37727AD6E6D52EC6746119EA066BD901F5E143B`
SHA384 | `A089F7FB2CA3BB2D8840AB75128C6744180DA4B39D75EAB795CC7DE13A0EC91D1EAC23EDF768265286640264039C621D`
SHA512 | `BCCCE37C2B7AE63C3CEDED8E6A7EDBF34BED4B5BB4206A1D09F7A4080C4967081CA8F276D87E4E854785583B7FADFB0B1F8E7D9E7C5AB9E5AC67EDC848F9CE94`
SSDEEP | `384:Zd71aN4xcQVNTYSFS26+fdJUjGL/IQ+NAZfHxWS9UsdX6EydQUtWSu8:Zd71aNmVVYSgN+Ptd+iZfHQnsdX9sDx`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: C:\windows\system32\inetsrv\w3wp.exe -s <site id> | -h [application host file]  
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

### Usage (stderr):
```Batchfile

```

### Child Processes:
RdpSa.exe

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

*The following table contains possible examples of `w3wp.exe` being misused. While `w3wp.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `            - '\w3wp.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc_folder.yml) | `            - '*\w3wp.exe'  # https://twitter.com/gabriele_pippi/status/1206907900268072962` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `            - '\w3wp.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_detection.yml) | `            - '*\w3wp.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_spawn.yml) | `            - '*\w3wp.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\w3wp.exe*'       ` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


