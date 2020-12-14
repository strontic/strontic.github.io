---
title: wow64.dll | Win32 Emulation on NT64
excerpt: What is wow64.dll?
---

# wow64.dll 

* File Path: `C:\Windows\system32\wow64.dll`
* Description: Win32 Emulation on NT64

## Hashes

Type | Hash
-- | --
MD5 | `21BBDC91CF4EDEB927BB06456D82556F`
SHA1 | `8EC8F242A0AD29E03AB49278DE81B082598B65DB`
SHA256 | `85CDB8646116D732D68D3A76C246BB825DDD7A9EE7B8491528C46422722BB867`
SHA384 | `AE7354FF65FBF4BCE27B535659C41B1ABB766924A6013564F787AB94365971BE5075BB764F357F7B9558B45DA43D9606`
SHA512 | `0B7F4A42FEDFE793B1D6E34B266D9443BCE75CB3152B03D46058DC8B0FFA36E2DFCD29ECD5E4E4EDE55B258F8AB8860715B66A8AEFFCE72E92EAD84C0400AF9E`
SSDEEP | `6144:uWujXA5fXbqDcgx6U5mXzzTOTunfGUU3QT:o7AslCGvs`
IMP | `744FD877C0939A2EE8523E2B7AF109C2`
PESHA1 | `4EE202F5E21A9DB598129B5D38DA9ABC822E1D12`
PE256 | `4230742D007C01739ECCDC8483A7ACF7F2C5C0BB43BCC7C20EEA5FCE4501EE4A`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`Wow64RaiseException` | 20 | Exported Function
`Wow64ShallowThunkAllocObjectAttributes32TO64_FNC` | 21 | Exported Function
`Wow64ShallowThunkAllocSecurityQualityOfService32TO64_FNC` | 22 | Exported Function
`Wow64ProcessPendingCrossProcessItems` | 19 | Exported Function
`Wow64PassExceptionToGuest` | 16 | Exported Function
`Wow64PrepareForDebuggerAttach` | 17 | Exported Function
`Wow64PrepareForException` | 18 | Exported Function
`Wow64SystemServiceEx` | 27 | Exported Function
`Wow64ValidateUserCallTarget` | 28 | Exported Function
`Wow64ValidateUserCallTargetFilter` | 29 | Exported Function
`Wow64SuspendLocalThread` | 26 | Exported Function
`Wow64ShallowThunkSIZE_T32TO64` | 23 | Exported Function
`Wow64ShallowThunkSIZE_T64TO32` | 24 | Exported Function
`Wow64SuspendLocalProcess` | 25 | Exported Function
`Wow64NotifyUnsimulateComplete` | 15 | Exported Function
`Wow64CheckIfNXEnabled` | 5 | Exported Function
`Wow64DispatchExceptionCHPE` | 6 | Exported Function
`Wow64EmulateAtlThunk` | 7 | Exported Function
`Wow64ApcRoutine` | 4 | Exported Function
`Wow64AllocateHeap` | 2 | Exported Function
`Wow64AllocateTemp` | 3 | Exported Function
`Wow64AllocThreadHeap` | 1 | Exported Function
`Wow64KiUserCallbackDispatcher` | 12 | Exported Function
`Wow64LdrpInitialize` | 13 | Exported Function
`Wow64LogPrint` | 14 | Exported Function
`Wow64IsStackExtentsCheckEnforced` | 11 | Exported Function
`Wow64FreeHeap` | 8 | Exported Function
`Wow64FreeThreadHeap` | 9 | Exported Function
`Wow64IsControlFlowGuardEnforced` | 10 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wow64.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.84 (WinBuild.160101.0800)
* Product Version: 10.0.19041.84
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/85cdb8646116d732d68d3a76c246bb825ddd7a9ee7b8491528c46422722bb867/detection/


## Possible Misuse

*The following table contains possible examples of `wow64.dll` being misused. While `wow64.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [proxy_apt40.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_apt40.yml) | `c-useragent: 'Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.143 Safari/537.36'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_cobalt_amazon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_cobalt_amazon.yml) | `c-useragent: "Mozilla/5.0 (Windows NT 6.1; WOW64; Trident/7.0; rv:11.0) like Gecko"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_download_susp_dyndns.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_download_susp_dyndns.yml) | `- '*.wow64.net'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_empire_ua_uri_combos.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_empire_ua_uri_combos.yml) | `c-useragent: 'Mozilla/5.0 (Windows NT 6.1; WOW64; Trident/7.0; rv:11.0) like Gecko'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/5.0 (Windows NT 6.; WOW64; rv:20.0) Gecko/20100101 Firefox/20.0'  # APT GrizzlySteppe - ChopStick - US CERT https://goo.gl/1DTHwi` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/5.0 (Windows NT 6.3; WOW64; rv:28.0) Gecko/20100101 Firefox/28.0'  # Sofacy - Xtunnel` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/5.0 (Windows NT 6.2; WOW64; rv:20.0) Gecko/20100101 Firefox/'  # Sofacy - Xtunnel` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/5.0 (Windows NT 6.; WOW64; rv:20.0) Gecko/20100101 Firefox/2'  # Sofacy - Xtunnel` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/5.0 (compatible; MSIE 9.0; Windows NT 6.1; WOW64; Trident/5.0)'  # Winnti related` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1; WOW64; Trident/4.0; SLCC2; .NETCLR 2.0.50727)'  # APT17` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/5.0 (Windows NT 6.1; WOW64) WinHttp/1.6.3.8 (WinHTTP/5.1) like Gecko'  # Sofacy User-Agent https://researchcenter.paloaltonetworks.com/2018/06/unit42-sofacy-groups-parallel-attacks/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/5.0 (Windows NT 6.1; WOW64) Chrome/28.0.1500.95 Safari/537.36'  # Hidden Cobra malware` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_frameworks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_frameworks.yml) | `- 'Mozilla/5.0 (compatible; MSIE 9.0; Windows NT 6.1; WOW64; Trident/5.0; MAAU)'  # Payloads` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_malware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_malware.yml) | `- 'Mozilla/5.0 (Windows NT 6.1; WOW64; rv:53.0) Gecko/20100101 Chrome /53.0'  # DargonOK` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_malware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_malware.yml) | `- 'Mozilla/4.0 (compatible; MSIE 7.0; Windows NT 6.2; WOW64; Trident/7.0; .NET4.0C; .NET4.0E; InfoPath.3)'  # https://twitter.com/webbthewombat/status/1225827092132179968` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_suspicious.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_suspicious.yml) | `- 'Mozilla/5.0 (Windows NT 6.3; WOW64; rv:28.0) Gecko/20100101 Firefox/28.0'  # used by APT28 malware https://threatvector.cylance.com/en_us/home/inside-the-apt28-dll-backdoor-blitz.html` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt17_mal_sep17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt17_mal_sep17.yar) | $x1 = "Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1; WOW64; Trident/4.0; SLCC2; .NETCLR 2.0.50727)" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt37.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt37.yar) | $a1 = "Mozilla/5.0 (Windows NT 6.1; WOW64; Trident/7.0; rv:11.0) like Gecko" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt41.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt41.yar) | $s3 = "Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/54.0.2840.71 Safari/537.36" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt6_malware.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt6_malware.yar) | $s1 = "Mozilla/5.0 (compatible; MSIE 9.0; Windows NT 6.1; WOW64; Trident/5.0)" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_casper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_casper.yar) | $z2 = "Mozilla/5.0 (compatible; MSIE 9.0; Windows NT 6.1; WOW64; Trident/5.0; MALC)" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_duqu2.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_duqu2.yar) | $x2 = "Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/535.7 (KHTML, like Gecko) Chrome/16.0.912.63 Safari/535.7xs5D9rRDFpg2g" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_duqu2.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_duqu2.yar) | $x4 = "Mozilla/5.0 (Windows NT 6.1; WOW64; rv:6.0a2) Gecko/20110612 Firefox/6.0a2" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) | $STR3 = "User-Agent: Mozilla/5.0 (Windows NT 6.; WOW64; rv:20.0) Gecko/20100101 Firefox/20.0" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | $s5 = "Mozilla/4.0 (compatible; MSIE 7.0; Windows NT 6.1; WOW64; Trident/5.0; SLCC2; .NET CLR 2.0.50727; .NET CLR 3.5.30729; .NET CLR 3" ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_inocnation.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_inocnation.yar) | // Mozilla/5.0 (Windows NT 6.3; WOW64; Trident/7.0;rv:11.0) like Gecko | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_rehashed_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_rehashed_rat.yar) | $s1 = "User-Agent: Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1; WOW64; Trident/4.0; SLCC2; .NET CLR 2.0.50727; .NET CLR 3.5.30729" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_rehashed_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_rehashed_rat.yar) | $a1 = "User-Agent: Mozilla/5.0 (compatible; MSIE 8.0; Windows NT 6.1; WOW64)" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_rehashed_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_rehashed_rat.yar) | $a2 = "Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1; WOW64; Trident/4.0; SLCC2; .NET CLR 2.0.50727; .NET CLR 3.5.30729; .NET CLR 3" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sakula.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sakula.yar) | $str07 = "Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1; WOW64; Trident/4.0; SLCC2; .NET CLR 2.0.50727; .NET CLR 3.5.30729; .NET CLR 3.0.30729; Media Center PC 6.0)" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sandworm_exim_expl.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sandworm_exim_expl.yar) | $x2 = "UA='Mozilla/5.0 (Windows NT 6.1; WOW64; Trident/7.0; rv:11.0) like Gecko';server='http" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_shellcrew_streamex.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_shellcrew_streamex.yar) | $d = "Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/39.0.2171.95 Safari/537.36" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy_xtunnel_bundestag.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy_xtunnel_bundestag.yar) | $variant21 = "User-Agent: Mozilla/5.0 (Windows NT 6.3; WOW64; rv:28.0) Gecko/20100101 Firefox/28.0" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy_xtunnel_bundestag.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy_xtunnel_bundestag.yar) | $x1 = "User-Agent: Mozilla/5.0 (Windows NT 6.2; WOW64; rv:20.0) Gecko/20100101 Firefox/" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy_xtunnel_bundestag.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy_xtunnel_bundestag.yar) | $x2 = "User-Agent: Mozilla/5.0 (Windows NT 6.; WOW64; rv:20.0) Gecko/20100101 Firefox/2" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s1 = "User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64; Trident/7.0; AS; rv:11.0) like Gecko" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_xrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_xrat.yar) | $s3 = "Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.1916.114 Safari/537.36" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s3 = "Mozilla/5.0 (Windows NT 6.3; WOW64; rv:26.0) Gecko/20100101 Firefox/26.0" fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cn_campaign_njrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cn_campaign_njrat.yar) | $x1 = "User-Agent: Mozilla/5.0 (compatible; MSIE 10.0; Windows NT 6.1; WOW64; Trident/6.0)" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cobaltgang.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cobaltgang.yar) | $s1 = "Mozilla/5.0 (compatible; MSIE 9.0; Windows NT 6.1; WOW64; Trident/5.0; BOIE9;ENGB)" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_malware_generic.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_malware_generic.yar) | $s1 = "User-Agent: Mozilla/4.0 (Windows NT 6.1; WOW64; Trident/7.0; rv:11.0) like Gecko" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_mirai.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_mirai.yar) | $s1 = "User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2272.101 Safari/537.36" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_rombertik_carbongrabber.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_rombertik_carbongrabber.yar) | $s8 = "Mozilla/5.0 (Windows NT 6.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_cve_2015_2426.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_cve_2015_2426.yar) | $s3 = "Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.125 Safari/537.36" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s4 = "wow64 process NOT created" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s5 = "Mozilla/5.0 (Windows NT 6.1; WOW64; Trident/7.0; rv:11.0) like Gecko" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


