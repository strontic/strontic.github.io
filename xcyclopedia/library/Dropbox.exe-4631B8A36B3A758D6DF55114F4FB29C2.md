---
title: Dropbox.exe | Dropbox
---

# Dropbox.exe 

* File Path: `C:\program files (x86)\Dropbox\Client\Dropbox.exe`
* Description: Dropbox

## Hashes

Type | Hash
-- | --
MD5 | `4631B8A36B3A758D6DF55114F4FB29C2`
SHA1 | `B723C02016239FCEE5294AEF13B4D648395847A0`
SHA256 | `89F755B3BF285A3C658D77ADCA23EA49565222CEFD7259688AF5B24CC4A6E8E7`
SHA384 | `41394A7AB8C394BF6D679864DBEC58D7D09B32D72D273D0301B20BA4AE5FD3781F6C1FB2FA1EB272EFB9A87D83AB9602`
SHA512 | `5AF4233322EE4803A1F3BEB4F2114FF654B2D01003481D6BD33AA45C85FFFA429FE265188B2010C0BD3533A8A3BA2341992B948463915D8ACBF66293A93882AD`
SSDEEP | `49152:cE9514JiLbcw6I7KkaJVwM/WCetkpNgJwHj85AOBcIv4nqRl:RsJUbcw6kM/WCetkpNLEB9`

## Runtime Data

### Usage (stderr):
```cmhg
!! dropbox: assigning process to named job object dbx4248
!! dropbox: assigned process to named job object with handle 00000210
dropbox: loading watchdog
dropbox: loaded watchdog. executing watchdog_main
!! dropbox: assigning process to named job object dbx6472
!! dropbox: assigned process to named job object with handle 00000210
dropbox: loading watchdog
dropbox: loaded watchdog. executing watchdog_main
dropbox: starting main app
dropbox: package full name is <unpackaged>
dropbox: loading bootstrap
dropbox: initializing
dropbox: initializing python 3.7.5
dropbox: setting program path 'C:\program files (x86)\Dropbox\Client\Dropbox.exe'
!! dropbox: assigning process to named job object dbx5356
!! dropbox: assigned process to named job object with handle 00000218
dropbox: loading watchdog
dropbox: setting python path 'C:\program files (x86)\Dropbox\Client\104.4.175;C:\program files (x86)\Dropbox\Client\104.4.175\python-packages.zip'
dropbox: loaded watchdog. executing watchdog_main
dropbox: python initialized
dropbox: running dropbox
dropbox: setting args
dropbox: applying overrides
dropbox: running main script
dropbox: load fq extension 'C:\\program files (x86)\\Dropbox\\Client\\104.4.175\\tornado.speedups.cp37-win32.pyd'
dropbox: load fq extension 'C:\\program files (x86)\\Dropbox\\Client\\104.4.175\\cryptography.hazmat.bindings._constant_time.cp37-win32.pyd'
dropbox: load fq extension 'C:\\program files (x86)\\Dropbox\\Client\\104.4.175\\cryptography.hazmat.bindings._openssl.cp37-win32.pyd'
dropbox: load fq extension 'C:\\program files (x86)\\Dropbox\\Client\\104.4.175\\cryptography.hazmat.bindings._padding.cp37-win32.pyd'
dropbox: load fq extension 'C:\\program files (x86)\\Dropbox\\Client\\104.4.175\\apex._apex.cp37-win32.pyd'
dropbox: load fq extension 'C:\\program files (x86)\\Dropbox\\Client\\104.4.175\\psutil._psutil_windows.cp37-win32.pyd'
dropbox: load fq extension 'C:\\program files (x86)\\Dropbox\\Client\\104.4.175\\win32com.shell.shell.cp37-win32.pyd'

```

### Child Processes:
Dropbox.exe Dropbox.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\kernel32.dll.mui | File
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(R-D)   C:\Windows\SysWOW64\FirewallAPI.dll | File
(R-D)   C:\Windows\SysWOW64\stdole2.tlb | File
(RW-)   C:\Program Files (x86)\Dropbox\Client\104.4.175 | File
(RW-)   C:\Users\user\Documents | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1_none_fd031af45b0106f2 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme4048709601 | Section
\Windows\Theme603176458 | Section


### Loaded Modules:

Path |
-- |
C:\program files (x86)\Dropbox\Client\Dropbox.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `08557A49A29FFD9253CA5AC8780F2C95`
* Thumbprint: `00D9C6C496925FFD914772B0B79F6E873B6AB8F2`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="Dropbox, Inc", O="Dropbox, Inc", L=San Francisco, S=California, C=US

## File Metadata

* Original Filename: Dropbox.exe
* Product Name: Dropbox
* Company Name: Dropbox, Inc.
* File Version: 104.4.175
* Product Version: 104.4.175
* Language: English (United States)
* Legal Copyright: Dropbox, Inc.


## Possible Misuse

*The following table contains possible examples of `Dropbox.exe` being misused. While `Dropbox.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [proxy_apt40.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_apt40.yml) | `title: APT40 Dropbox Tool User Agent` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_apt40.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_apt40.yml) | `description: Detects suspicious user agent string of APT40 Dropbox tool` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_apt40.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_apt40.yml) | `      r-dns: 'api.dropbox.com'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [net_dns_high_subdomain_rate.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/net_dns_high_subdomain_rate.yml) | `            - "dropbox.com"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [net_dns_large_domain_name.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/net_dns_large_domain_name.yml) | `            - "dropbox.com"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-machete-event.json](https://github.com/eset/malware-ioc/blob/master/machete/misp-machete-event.json) | `            "value": "https://www.dropbox.com/s/m38rq5hx5ydrg07/zingapur?dl=1",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hiddencobra_bankshot.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hiddencobra_bankshot.yar) |       $a1 = "live.dropbox.com" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_indetectables_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_indetectables_rat.yar) | 		$x2 = "URLDownloadToFileA 0, \"https://dl.dropbox.com/u/105015858/nome.exe\", \"c:\\nome.exe\", 0, 0" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_indetectables_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_indetectables_rat.yar) | 		$s5 = "https://dl.dropbox.com/u/105015858" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_khrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_khrat.yar) |       $x1 = "http.open \"POST\", \"http://update.upload-dropbox[.]com/docs/tz/GetProcess.php\",False,\"\",\"\" " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_nanocore_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_nanocore_rat.yar) |       $x1 = "C:\\Users\\Logintech\\Dropbox\\Projects\\New folder\\Latest\\Benchmark\\Benchmark\\obj\\Release\\Benchmark.pdb" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_mal_scripts.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_mal_scripts.yar) |       $x2 = "script:https://www.dropbox.com" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


