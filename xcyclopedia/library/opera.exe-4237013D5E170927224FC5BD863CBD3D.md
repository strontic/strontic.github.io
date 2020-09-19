---
title: opera.exe | Opera Internet Browser
---

# opera.exe 

* File Path: `C:\program files\Opera\70.0.3728.133\opera.exe`
* Description: Opera Internet Browser

## Screenshot

![opera.exe](screenshots/opera.exe-C3365FF810311F43C51189D1F646D420-6.png)

## Hashes

Type | Hash
-- | --
MD5 | `4237013D5E170927224FC5BD863CBD3D`
SHA1 | `A0D2CA3B33599850BD3E974F1A411C5958A279ED`
SHA256 | `34C64630D6C37C370B54BC166BB7986BD74B3C619FBDBDF969AE9560BB6428EE`
SHA384 | `A160FEE3A376DC9E955C0325D4788E2ACC972241811B815843DBF42DCEEC97474458A2FC9491A9C4483FB35C1AA61D3F`
SHA512 | `A98EF91C16B1C9287602F8C2DB5CB706893682C9862AE9BA9AF95CBCD4597E361A089AED1A4B2D61C9C43E3157B44A1716088311B23F884F2E449CEDE91E76E9`
SSDEEP | `12288:0vwkvP/aNl347aOSvtpYb1jyUPqfM0RcNZrfAhvGOwHceR5+n3coFCC7Tu:0PaNt2aOSvjOj6fM4hv8qcEn7K`

## Runtime Data

### Usage (stdout):
```cmhg
Opera 70.0.3728.133 Stable
Features available through command-line switches:
	--with-feature:enhanced-address-bar [Enabled by default: false]
	--with-feature:handle-abp-protocol [Enabled by default: true]
	--with-feature:history-onboarding [Enabled by default: false]
	--with-feature:instagram-panel [Enabled by default: true]
	--with-feature:lookalike-url-navigation-suggestions [Enabled by default: true]
	--with-feature:procedural-tab-drawing [Enabled by default: true]
	--with-feature:search-in-closed-tabs [Enabled by default: true]
	--with-feature:search-text-in-tabs [Enabled by default: true]
	--with-feature:shared-start-page [Enabled by default: true]
	--with-feature:sidebar-site-panel [Enabled by default: false]
	--with-feature:smart-files [Enabled by default: false]
	--with-feature:suggestion-scoring-improved [Enabled by default: true]
	--with-feature:sync-passphrase-papercuts [Enabled by default: true]
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
C:\program files\Opera\70.0.3728.133\opera.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Program Files\Opera\70.0.3728.133 | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1_none_b555e41d4684ddec | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\program files\Opera\70.0.3728.133\opera.exe |
C:\Windows\SYSTEM32\AcGenral.dll |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\SYSTEM32\apphelp.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\SYSTEM32\USERENV.dll |
C:\Windows\System32\win32u.dll |


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
* File Version: 70.0.3728.133
* Product Version: 70.0.3728.133
* Language: English (United States)
* Legal Copyright: Copyright Opera Software 2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Opera\70.0.3728.106\opera.exe](opera.exe-C3365FF810311F43C51189D1F646D420.md) | 96

## Possible Misuse

*The following table contains possible examples of `opera.exe` being misused. While `opera.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_malware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_malware.yml) | `- 'Opera/8.81 (Windows NT 6.0; U; en)'  # Sality` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_malware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_malware.yml) | `- 'Opera'  # Trojan Keragany` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_outbound_kerberos_connection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_suspicious_outbound_kerberos_connection.yml) | `- '\opera.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_outbound_kerberos_connection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_suspicious_outbound_kerberos_connection.yml) | `- '\opera.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nouns.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/nouns.txt) | `opera` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1071.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1071.001/T1071.001.md) | Invoke-WebRequest #{domain} -UserAgent "Opera/8.81 (Windows NT 6.0; U; en)" \| out-null | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1071.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1071.001/T1071.001.md) | #{curl_path} -s -A "Opera/8.81 (Windows NT 6.0; U; en)" -m3 #{domain} >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1071.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1071.001/T1071.001.md) | curl -s -A "Opera/8.81 (Windows NT 6.0; U; en)" -m3 #{domain} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | 		$s2 = "Opera.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | 		$s6 = "Copyright Opera Software 1995-" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | 		$s9 = "Opera Internet Browser" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | 		$s12 = "Opera Software" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_buckeye.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_buckeye.yar) | 		$s1 = "Opera Software\\Opera Stable\\Login Data" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_dragonfly.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_dragonfly.yar) |       $s1 = "\\AppData\\Roaming\\Opera Software\\Opera Stable\\Login Data" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_dragonfly.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_dragonfly.yar) |       $s5 = "********************** Opera *********************" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_telebots.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_telebots.yar) |       $s6 = "Opera old version credentials" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_credstealer_generic.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_credstealer_generic.yar) |       $s3 = "%s\\Opera Software\\Opera Stable\\Login Data" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_credstealer_generic.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_credstealer_generic.yar) |       $s10 = "%s\\Opera\\Opera\\profile\\wand.dat" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_envrial.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_envrial.yar) |       $a1 = "\\Opera Software\\Opera Stable\\Login Data" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_ransom_ragna_locker.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_ransom_ragna_locker.yar) |       $s3 = "Opera Software" fullword wide  /* Don't touch browsers for contact him*/ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [general_cloaking.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/general_cloaking.yar) |       and not filepath contains "Opera" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) |       $s1 = "softwares.opera(" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


