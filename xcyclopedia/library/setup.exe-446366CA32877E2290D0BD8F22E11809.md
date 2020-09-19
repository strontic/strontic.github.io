---
title: setup.exe | Adobe Bootstrapper for Single Installation
---

# setup.exe 

* File Path: `C:\ProgramData\Adobe\Setup\{00000000-0000-0000-0000-000000000000}\RDC\setup.exe`
* Description: Adobe Bootstrapper for Single Installation

## Screenshot

![setup.exe](screenshots/Setup.exe-8BBDBD0FA1F6AD661B85FC8A5BD3E2B3-1.png)
![setup.exe](screenshots/Setup.exe-DE608134E33D3ABFFA944723ACD3E292.png)
![setup.exe](screenshots/Setup.exe-F35692328D9B6BFDBD9A69D60867693B-5.png)

## Hashes

Type | Hash
-- | --
MD5 | `446366CA32877E2290D0BD8F22E11809`
SHA1 | `B620D296D53566D9A07C1CABC92C50D0F5C4F34A`
SHA256 | `4B76C0EA832D58966F824CFEDB9A3831B1C286B13CC22D56E29DAD7966847184`
SHA384 | `A4F12C6410FB08E3008A1169936F08127CC345FE9115E9780CC681D25A80CBEAE5048091C640F99F345AE61364FE04EC`
SHA512 | `EDBB4CD70B9C372F827136DB217087451732F83A34AF854FF031A659E9AEE0FE849C0005A38D2BD19F438F8277147101A577FA900B89E2E1F804B369134255CF`
SSDEEP | `6144:aYrIOXsqmWzJrdc6GJRQUWGUA9PRWLiFSbE56FORF:q2lWRPWhA9PRWg9`

## Signature

* Status: Signature verified.
* Serial: `0EE3F1C8F451CBF21203341A53F23E71`
* Thumbprint: `1BFC555FD6489422BC2BABA036B31AA75DC0AA17`
* Issuer: CN=DigiCert EV Code Signing CA (SHA2), OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=Adobe Inc., OU=Acrobat DC, O=Adobe Inc., L=San Jose, S=ca, C=US, SERIALNUMBER=2748129, OID.2.5.4.15=Private Organization, OID.1.3.6.1.4.1.311.60.2.1.2=Delaware, OID.1.3.6.1.4.1.311.60.2.1.3=US

## File Metadata

* Original Filename: Setup.exe
* Product Name: Bootstrapper Small
* Company Name: Adobe Systems Incorporated
* File Version: 20.9.20063.381938
* Product Version: 20.9.20063.381938
* Language: English (United States)
* Legal Copyright: Copyright  2020 Adobe Systems Incorporated.  All rights reserved.


## Possible Misuse

*The following table contains possible examples of `setup.exe` being misused. While `setup.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [pypi-publish.yml](https://github.com/Neo23x0/sigma/blob/master/.github/workflows/pypi-publish.yml) | `uses: actions/setup-python@v1` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sigma-test.yml](https://github.com/Neo23x0/sigma/blob/master/.github/workflows/sigma-test.yml) | `uses: actions/setup-python@v1` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [cisco_cli_net_sniff.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/cisco/aaa/cisco_cli_net_sniff.yml) | `description: Show when a monitor or a span/rspan is setup or modified` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [cisco_cli_net_sniff.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/cisco/aaa/cisco_cli_net_sniff.yml) | `- Admins may setup new or modify old spans, or use a monitor for troubleshooting.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_security_eventlog_cleared.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_security_eventlog_cleared.yml) | `- Rollout of log collection agents (the setup routine often includes a reset of the local Eventlog)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mal_flowcloud.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/malware/win_mal_flowcloud.yml) | `- 'HKLM\SYSTEM\Setup\PrintResponsor\\*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_winnti_pipemon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_winnti_pipemon.yml) | `- 'setup.exe -x:0'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_winnti_pipemon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_winnti_pipemon.yml) | `- 'setup.exe -x:1'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_winnti_pipemon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_winnti_pipemon.yml) | `- 'setup.exe -x:2'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2019_1378.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2019_1378.yml) | `- '*\cmd.exe /c C:\Windows\Setup\Scripts\SetupComplete.cmd'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2019_1378.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2019_1378.yml) | `- '*\cmd.exe /c C:\Windows\Setup\Scripts\PartnerSetupComplete.cmd'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2019_1378.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2019_1378.yml) | `- 'C:\Windows\Setup\\*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Setup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Setup.yml) | `Name: Setup.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Setup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Setup.yml) | `- Command: Run Setup.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Setup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Setup.yml) | `Description: Hijack hpbcsiServiceMarshaller.exe and run Setup.exe to launch a payload.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `- IOC: HKLM\SOFTWARE\Microsoft\Active Setup\Installed Components\YOURKEY` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Setupapi.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Setupapi.yml) | `Description: Windows Setup Application Programming Interface` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syssetup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Syssetup.yml) | `Description: Windows NT System Setup` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [attor](https://github.com/eset/malware-ioc/blob/master/attor/README.adoc) | `%COMMONAPPDATA%\Adobe\Setup\Replicate\US-sf` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [attor](https://github.com/eset/malware-ioc/blob/master/attor/README.adoc) | `%COMMONAPPDATA%\Adobe\Setup\Replicate\US-nh` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [attor](https://github.com/eset/malware-ioc/blob/master/attor/README.adoc) | `%COMMONAPPDATA%\Adobe\Setup\Replicate\US-zn` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [attor](https://github.com/eset/malware-ioc/blob/master/attor/README.adoc) | `%COMMONAPPDATA%\Adobe\Setup\Replicate\US-pq` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [glupteba.misp-event.json](https://github.com/eset/malware-ioc/blob/master/glupteba/glupteba.misp-event.json) | `"value": "setup.exe\|f7230b2cab4e4910bca473b39ee8fd4df394ce0d",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [glupteba](https://github.com/eset/malware-ioc/blob/master/glupteba/README.adoc) | `\|`F7230B2CAB4E4910BCA473B39EE8FD4DF394CE0D`\|setup.exe   \|MSIL/Adware.CsdiMonetize.AG` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-kryptocibule.json](https://github.com/eset/malware-ioc/blob/master/kryptocibule/misp-kryptocibule.json) | `"value": "%ProgramFiles(X86)%\\Adobe\\Acrobat Reader DC\\Reader\\Update\\Setup.dll",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-kryptocibule.json](https://github.com/eset/malware-ioc/blob/master/kryptocibule/misp-kryptocibule.json) | `"value": "%ProgramFiles(X86)%\\Adobe\\Acrobat Reader DC\\Reader\\Update\\setup-version.json",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [kryptocibule](https://github.com/eset/malware-ioc/blob/master/kryptocibule/README.adoc) | `%ProgramFiles(X86)%\Adobe\Acrobat Reader DC\Reader\Update\Setup.dll` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [kryptocibule](https://github.com/eset/malware-ioc/blob/master/kryptocibule/README.adoc) | `%ProgramFiles(X86)%\Adobe\Acrobat Reader DC\Reader\Update\setup-version.json` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [potao](https://github.com/eset/malware-ioc/blob/master/potao/README.adoc) | `Fake TrueCrypt Setup:` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `depending on your setup. For example we know that `suPHP` uses shared memory.` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | `setup.exe` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-05-01/Atomic_Friday.md) | ## Setup | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Getting_Lateral.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-05-01/Getting_Lateral.md) | ## Setup | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1046.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1046/T1046.md) | \| nmap_url \| NMap installer download URL \| url \| https://nmap.org/dist/nmap-7.80-setup.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1046.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1046/T1046.md) | Invoke-WebRequest -OutFile $env:temp\nmap-7.80-setup.exe #{nmap_url} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1046.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1046/T1046.md) | Start-Process $env:temp\nmap-7.80-setup.exe /S | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [airbnb_binaryalert.yar](https://github.com/Neo23x0/signature-base/blob/master/vendor/yara/airbnb_binaryalert.yar) |         $a1 = "https://setup.icloud.com/setup/authenticate/" wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [airbnb_binaryalert.yar](https://github.com/Neo23x0/signature-base/blob/master/vendor/yara/airbnb_binaryalert.yar) |         $s8 = "Setup a communication socket with the process by injecting" fullword ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_bluetermite_emdivi.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_bluetermite_emdivi.yar) | 		$x1 = "Setup=unsecess.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_bluetermite_emdivi.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_bluetermite_emdivi.yar) | 		$x2 = "Setup=leassnp.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_irontiger.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_irontiger.yar) | 		$s0 = "\\setup.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_irontiger.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_irontiger.yar) | 		$s3 = "setup.exeUT" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_miniasp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_miniasp.yar) | 		$x2 = "run http://%s/logo.png setup.exe" fullword ascii /* PEStudio Blacklist: strings */ /* score: '37.02' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) |       $x1 = "cmd /c expand %TEMP%\\setup.cab -F:* %SystemRoot%\\System32" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) |       $x2 = "del /f /q %TEMP%\\setup.cab && cliconfg.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) |       $s6 = "\\setup.cab" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_promethium_neodymium.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_promethium_neodymium.yar) |       $s2 = "c:\\windows\\temp\\TrueCrypt-Setup-7.1a-tamindir.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sakula.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sakula.yar) |     description = "Sakula shellcode - taken from decoded setup.msi but may not be unique enough to identify Sakula" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_threatgroup_3390.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_threatgroup_3390.yar) | 		$s7 = "setup.exeUT" fullword ascii  | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_threatgroup_3390.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_threatgroup_3390.yar) | 		$s6 = "\\setup.exe" fullword ascii  | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti_burning_umbrella.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti_burning_umbrella.yar) |       $s1 = "c:\\windows\\ime\\setup.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | 		description = "Sample from CN Honker Pentest Toolset - file setup.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_fireball.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_fireball.yar) |       $s3 = "\\SETUP.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_nopetya_jun17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_nopetya_jun17.yar) |       $x6 = "wevtutil cl Setup & wevtutil cl System" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | 		$s2 = "SwitchSniffer Setup" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


