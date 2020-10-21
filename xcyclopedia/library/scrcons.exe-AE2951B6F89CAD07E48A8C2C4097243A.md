---
title: scrcons.exe | WMI Standard Event Consumer - scripting
excerpt: What is scrcons.exe?
---

# scrcons.exe 

* File Path: `C:\Windows\system32\wbem\scrcons.exe`
* Description: WMI Standard Event Consumer - scripting

## Hashes

Type | Hash
-- | --
MD5 | `AE2951B6F89CAD07E48A8C2C4097243A`
SHA1 | `2F88A2A21F4A40600EE3ED6B7D8D10B62CFEF7AB`
SHA256 | `2C91F17DD33E78430451D47F2E26715EB6E1FD8125E530182EC0CACEB4CD755F`
SHA384 | `D0D746A6089D6D33C76749110630656536984B55D95ED843149E43C34EF827CA7BDD9A7084E11E36A9A625C30DF383A6`
SHA512 | `B744E20E86C61B84FC1BDDD72F81E080B2A1399CB748F6767D4F563974607249A7FFEC640240A7C87852FBEECDC6314638D149D4A7133D203519E292C93491EC`
SSDEEP | `768:Wnc2NqrHdzJRSnc+N5QM78l/r70SA/pyf51Gk1Oxju+nzFSTIT+4i/qKVTPnyo:e5yw+w8pr70SAQf51R1OVu+nzFAnyo`
IMP | `33D9F246D162F5E1E1312E28E566A69E`
PESHA1 | `83872FBF9C0123F03166DFEA1869362849F3E754`
PE256 | `A8685B0C5C2688B34E77F45E854DE63F04132C736252077EC40B02A907CDD229`

## Runtime Data

### Usage (stdout):
```cmhg
Cannot run standalone

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\wbem\esscli.dll |
C:\Windows\system32\wbem\FastProx.dll |
C:\Windows\system32\wbem\scrcons.exe |
C:\Windows\SYSTEM32\wbemcomn.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\WS2_32.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ScrCons
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/2c91f17dd33e78430451d47f2e26715eb6e1fd8125e530182ec0caceb4cd755f/detection/


## Possible Misuse

*The following table contains possible examples of `scrcons.exe` being misused. While `scrcons.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- '*\scrcons.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_persistence_script_event_consumer_write.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_wmi_persistence_script_event_consumer_write.yml) | `Image: 'C:\WINDOWS\system32\wbem\scrcons.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '*\scrcons.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wmi_persistence_script_event_consumer.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmi_persistence_script_event_consumer.yml) | `Image: C:\WINDOWS\system32\wbem\scrcons.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


