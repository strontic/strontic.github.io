---
title: msfeedssync.exe | Microsoft Feeds Synchronization
---

# msfeedssync.exe 

* File Path: `C:\windows\system32\msfeedssync.exe`
* Description: Microsoft Feeds Synchronization
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `66585D645C4E23A0FD5124BD714AE020`
SHA1 | `A18AD0083D38CA7454C133A7CB49718404C70859`
SHA256 | `EFDC52DA3624C831447403A0BD3E6914EB0FD545B2F969B18F908953DEF3757C`
SHA384 | `DEA6010C8857466B7F95C7D61DB25EEA4580927B435F81FD5736CDF79FE51BA55BDBC60B511696A283D9394890CD5301`
SHA512 | `4235B504628377A3A3431A7031131D411EDB0E62D289AB299E74C899351A3F6C37D3731C21D96B7F36C00A4DFBBBE3EA4E9FA0E6C3521E94E4D643E1AD71C9E6`
SSDEEP | `192:XM4owhaON40r1UDPgyCS1dp3QbHafWcY1DzKeKooTTUxWcsX:c4owhjKk1Uw4zU6f41D2ezWcsX`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\msfeedssync.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: msfeedssync.exe
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.9600.17416 (winblue_r4.141030-1500)
* Product Version: 11.00.9600.17416
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `msfeedssync.exe` being misused. While `msfeedssync.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_wmi_module_load.yml) | `            - '\msfeedssync.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


