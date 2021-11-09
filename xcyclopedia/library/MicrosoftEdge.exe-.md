---
title: MicrosoftEdge.exe | 
excerpt: What is MicrosoftEdge.exe?
---

# MicrosoftEdge.exe 

* File Path: `C:\Users\user\AppData\Local\Microsoft\WindowsApps\MicrosoftEdge.exe`

## Hashes

Type | Hash
-- | --
MD5 | ``
SHA1 | ``
SHA256 | ``
SHA384 | ``
SHA512 | ``
SSDEEP | ``

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --

## Possible Misuse

*The following table contains possible examples of `MicrosoftEdge.exe` being misused. While `MicrosoftEdge.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [file_event_mal_vhd_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/file_event_mal_vhd_download.yml) | `- microsoftedge.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_abusing_azure_browser_sso.yml) | `- MicrosoftEdge.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `- '\microsoftedge.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1176.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1176/T1176.md) | 1. Navigate to https://microsoftedge.microsoft.com/addons/detail/fjnehcbecaggobjholekjijaaekbnlgj | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


