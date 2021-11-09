---
title: SearchIndexer.exe | Microsoft Windows Search Indexer
excerpt: What is SearchIndexer.exe?
---

# SearchIndexer.exe 

* File Path: `C:\WINDOWS\system32\SearchIndexer.exe`
* Description: Microsoft Windows Search Indexer

## Hashes

Type | Hash
-- | --
MD5 | `CC2F805DD6D1FAE2187DFE79E9DFFA8E`
SHA1 | `946C413272BB18A441D897D0AEC5BE7453D90694`
SHA256 | `3548A0C05A9ACE8823296737B2C8131A7A3B0B5A3C53EB55F60816DC73DCD10A`
SHA384 | `17EEC9446C68177C0DA4057833C502EEEF62A04F246DB3E74E9EB55A449C0387578EADC13CF328CDDA2C4D5199FE73F5`
SHA512 | `6668201835C73A1E36D23E913519543E234C871F73A9B80E19B7E444486AD2391BB290E5D367E46A9FF1DD49380E6E3FABAA2DCB93794CD94AC686287054C245`
SSDEEP | `24576:+13oeLLYI84VlrtoAcPJpPbdRD4NJrwl+lSSKy4yy2wG8i0RJMWVaKMbXvxu+x7x:+13oefYI84Vlr2AaJ9pRD4Lwl+lSSKyg`
IMP | `9CE87BA8E383099432A52E221155DDB6`
PESHA1 | `C30FF364535BE21C8B73DE9B0A27E46232680C1F`
PE256 | `1ED4656B64954F51108673C4305EA64FA816A0D58856F8FCF50B6C6FCEB04ECA`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\SearchIndexer.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SearchIndexer.exe.mui
* Product Name: Windows Search
* Company Name: Microsoft Corporation
* File Version: 7.0.22000.1 (WinBuild.160101.0800)
* Product Version: 7.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/3548a0c05a9ace8823296737b2c8131a7a3b0b5a3c53eb55f60816dc73dcd10a/detection


## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_vss_ps_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/win_suspicious_vss_ps_load.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_debug_privilege.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_abusing_debug_privilege.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


