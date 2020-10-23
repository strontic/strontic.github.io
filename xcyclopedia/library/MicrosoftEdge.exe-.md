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
IMP | `n/a`
PESHA1 | `n/a`
PE256 | `n/a`

## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 
* Machine Type: n/a

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## Possible Misuse

*The following table contains possible examples of `MicrosoftEdge.exe` being misused. While `MicrosoftEdge.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `- '\microsoftedge.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_abusing_azure_browser_sso.yml) | `- MicrosoftEdge.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1176.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1176/T1176.md) | 1. Navigate to https://microsoftedge.microsoft.com/addons/detail/fjnehcbecaggobjholekjijaaekbnlgj | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


