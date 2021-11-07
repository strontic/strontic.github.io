---
title: winrshost.exe | Host Process for WinRM's Remote Shell plugin
excerpt: What is winrshost.exe?
---

# winrshost.exe 

* File Path: `C:\windows\SysWOW64\winrshost.exe`
* Description: Host Process for WinRM's Remote Shell plugin

## Hashes

Type | Hash
-- | --
MD5 | `D72FF4940F8314B9307DC25E5C81AFC9`
SHA1 | `22D3B85A71C569E896904812FBEAF0A62D0A42E0`
SHA256 | `BB39024C490BD804BAB068AC14CF7CBABBA1C2E7E3DFEB495D23B549955CEBD1`
SHA384 | `A41070E9DB5D466880BBE3C8F4D4A4DEC5D42FCDAA9F89B58EB9688C18ADCA49C2149D23D374449610C7F1E7095986B2`
SHA512 | `61EE3AE134763079C4F8C5373DE75283E9B9C5CA23D2032B3AB61FC2C98A84538BE7DC34258ACB1F9963C01391DFB08A4147CF7DA2A022BB9CBC69570508BED2`
SSDEEP | `384:cr9KMq7bVKkfNHD4dN5rKXQVtqc+lV01cKKWsKEWwR:wdq7bVBfNj4dv/+cWq1cKzW`

## Signature

* Status: The file C:\windows\SysWOW64\winrshost.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: winrshost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `winrshost.exe` being misused. While `winrshost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\winrshost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


