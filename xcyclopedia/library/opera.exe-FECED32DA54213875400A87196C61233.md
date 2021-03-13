---
title: opera.exe | Opera Internet Browser
excerpt: What is opera.exe?
---

# opera.exe 

* File Path: `C:\Program Files\Opera\71.0.3770.171\opera.exe`
* Description: Opera Internet Browser

## Screenshot

![opera.exe](screenshots/opera.exe-C3365FF810311F43C51189D1F646D420-6.png)

## Hashes

Type | Hash
-- | --
MD5 | `FECED32DA54213875400A87196C61233`
SHA1 | `EA76E94BAA1C23B76E3B14E6AA9DEE6F3AFCA12D`
SHA256 | `B1B08564EDA71D5442BD43E8260878D2971CC42A276A196B825CDF1439DA7FC3`
SHA384 | `47D074727F8A638FD2A386BD6087A76532D5A93BF288F64101871BCEAA10504D28015297E7798FA1739C4E7028D0B2F6`
SHA512 | `117080BD874B22A5958455238C24BA4AD0CDC2C0DF7E28ACBFF627B3055D864D34057350D21E717BAE75A80E013B50E5F27763BF67D2A222B7167D0FEAF1669A`
SSDEEP | `12288:bw/nvSikZ2xFPqIzJimxhwaBi82z5hHGkmLSluukPyq5eR5+nbojdfU39:ins2xkI1imxhVeKLSkuwyeCW9`
IMP | `4FCB68C6DA9F8547EAC0E5E83F13DDCB`
PESHA1 | `BD4038183919CF077881BDF99627AD430CAE2CFA`
PE256 | `3020CAD4195CA31AB988BB48ABE207AF40E412025461F8B68C16B75D5703A3F1`

## Runtime Data

### Usage (stdout):
```cmhg
Opera 71.0.3770.171 Stable
Features available through command-line switches:
	--with-feature:advanced-search-in-history [Enabled by default: true]
	--with-feature:enhanced-address-bar [Enabled by default: false]
	--with-feature:easy-files [Enabled by default: true]
	--with-feature:handle-abp-protocol [Enabled by default: true]
	--with-feature:history-onboarding [Enabled by default: false]
	--with-feature:instagram-panel [Enabled by default: true]
	--with-feature:lookalike-url-navigation-suggestions [Enabled by default: true]
	--with-feature:procedural-tab-drawing [Enabled by default: true]
	--with-feature:search-in-closed-tabs [Enabled by default: true]
	--with-feature:search-in-closed-tabs-show-more [Enabled by default: true]
	--with-feature:search-text-in-tabs [Enabled by default: true]
	--with-feature:sidebar-site-panel [Enabled by default: false]
	--with-feature:suggestion-scoring-improved [Enabled by default: true]
	--with-feature:sync-passphrase-papercuts [Enabled by default: true]
	--with-feature:tutorials [Enabled by default: false]
	--with-feature:weather-on-startpage [Enabled by default: true]
	--with-feature:workspaces [Enabled by default: true]
	--with-feature:workspaces-bookmark-context-menu [Enabled by default: true]
	--with-feature:workspaces-extended-menu [Enabled by default: false]
	--with-feature:workspaces-sidebar-context-menu [Enabled by default: true]
	--with-feature:workspaces-sidebar-notification [Enabled by default: true]
	--with-feature:workspaces-dnd [Enabled by default: false]
	--with-feature:yandex-zen-news [Enabled by default: false]
Press any key to continue . . . 

```

### Child Processes:
launcher.exe

### Window Title:
C:\Program Files\Opera\71.0.3770.171\opera.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Program Files\Opera\71.0.3770.171 | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21 | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\Program Files\Opera\71.0.3770.171\opera.exe |
C:\Windows\SYSTEM32\apphelp.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `05F4210DB2B283A32FF2AED29FCB68A4`
* Thumbprint: `878B0B298671F44FC739C08D826BB22DB1A2A021`
* Issuer: CN=DigiCert EV Code Signing CA (SHA2), OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=Opera Software AS, O=Opera Software AS, L=Oslo, C=NO, SERIALNUMBER=916 368 127, OID.2.5.4.15=Private Organization, OID.1.3.6.1.4.1.311.60.2.1.3=NO

## File Metadata

* Original Filename: 
* Product Name: Opera Internet Browser
* Company Name: Opera Software
* File Version: 71.0.3770.171
* Product Version: 71.0.3770.171
* Language: English (United States)
* Legal Copyright: Copyright Opera Software 2020
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/b1b08564eda71d5442bd43e8260878d2971cc42a276a196b825cdf1439da7fc3/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Opera\70.0.3728.106\notification_helper.exe](notification_helper.exe-A70473F8F527CFD2A36E528D87380858.md) | 33
[C:\program files\Opera\70.0.3728.133\notification_helper.exe](notification_helper.exe-47CB245ADC19F618D9F82E4A4CF9205F.md) | 32

## Possible Misuse

*The following table contains possible examples of `opera.exe` being misused. While `opera.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_malware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_malware.yml) | `- 'Opera/8.81 (Windows NT 6.0; U; en)'  # Sality`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_malware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_malware.yml) | `- 'Opera'  # Trojan Keragany`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_outbound_kerberos_connection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_suspicious_outbound_kerberos_connection.yml) | `- '\opera.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_outbound_kerberos_connection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_suspicious_outbound_kerberos_connection.yml) | `- '\opera.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nouns.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/nouns.txt) | `opera`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1071.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1071.001/T1071.001.md) | Invoke-WebRequest #{domain} -UserAgent "Opera/8.81 (Windows NT 6.0; U; en)" \| out-null | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1071.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1071.001/T1071.001.md) | #{curl_path} -s -A "Opera/8.81 (Windows NT 6.0; U; en)" -m3 #{domain} >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1071.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1071.001/T1071.001.md) | curl -s -A "Opera/8.81 (Windows NT 6.0; U; en)" -m3 #{domain} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | $s2 = "Opera.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | $s6 = "Copyright Opera Software 1995-" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | $s9 = "Opera Internet Browser" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | $s12 = "Opera Software" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_buckeye.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_buckeye.yar) | $s1 = "Opera Software\\Opera Stable\\Login Data" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_dragonfly.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_dragonfly.yar) | $s1 = "\\AppData\\Roaming\\Opera Software\\Opera Stable\\Login Data" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_dragonfly.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_dragonfly.yar) | $s5 = "********************** Opera *********************" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_telebots.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_telebots.yar) | $s6 = "Opera old version credentials" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_credstealer_generic.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_credstealer_generic.yar) | $s3 = "%s\\Opera Software\\Opera Stable\\Login Data" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_credstealer_generic.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_credstealer_generic.yar) | $s10 = "%s\\Opera\\Opera\\profile\\wand.dat" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_envrial.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_envrial.yar) | $a1 = "\\Opera Software\\Opera Stable\\Login Data" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_ransom_ragna_locker.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_ransom_ragna_locker.yar) | $s3 = "Opera Software" fullword wide  /* Don't touch browsers for contact him*/ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [general_cloaking.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/general_cloaking.yar) | and not filepath contains "Opera" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s1 = "softwares.opera(" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


