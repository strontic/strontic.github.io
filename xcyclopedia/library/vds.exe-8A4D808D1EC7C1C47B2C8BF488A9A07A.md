---
title: vds.exe | Virtual Disk Service
excerpt: What is vds.exe?
---

# vds.exe 

* File Path: `C:\windows\system32\vds.exe`
* Description: Virtual Disk Service

## Hashes

Type | Hash
-- | --
MD5 | `8A4D808D1EC7C1C47B2C8BF488A9A07A`
SHA1 | `B2953A71F01F6E2A59BF987786F5A8AE550BF83C`
SHA256 | `63C07312ADB6F8A8BDE93361C30AC63DAB4DE1141AF54630EEF11E54B0BF983D`
SHA384 | `95D6EA2F979696761FCC5CB0FAA9D9DC0CDA8EA6A01C4C6B2AB4A59700571658E558AFA098183AD5653EF6DF52ECA365`
SHA512 | `234F212BDE497FDF364C7058416F1D1C7C3D09AD9EFB0A497C4EC926F3D9469F603159C7B0F7C991F9200DCD2363AB5E2DB363C15404369A7A3E79A7FDFB27B5`
SSDEEP | `6144:oOUHZhqqDGFXU+wxku2gw7UhHS805f94GvxxU3RegjCcLvUKguT2t:oJZcqSh3eBet/2d7UKgP`

## Signature

* Status: The file C:\windows\system32\vds.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: vds.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `vds.exe` being misused. While `vds.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\vds.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


