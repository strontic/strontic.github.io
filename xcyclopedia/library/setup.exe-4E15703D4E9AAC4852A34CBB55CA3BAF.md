
# setup.exe 

* File Path: `C:\ProgramData\Adobe\Setup\{00000000-0000-0000-0000-000000000000}\setup.exe`
* Description: Adobe Bootstrapper for Single Installation
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4E15703D4E9AAC4852A34CBB55CA3BAF`
SHA1 | `056F3B7ECCE7108A7F0D2D6BE8FA84B8DDDEC5A3`
SHA256 | `2CC96093D90228AB6F74AD1737E5B5AF92AD60F934EFC4A0D9B665EF8A7B40EA`
SHA384 | `F44F59B6295CAA528B4179451C11659B76C424B8E6E64400A0EC6896C8098BD8ADA419294AE21C801B84B286F9906E87`
SHA512 | `1EE19FC5F90722173F6CB42C81AB680257B398684F0F8F3E343B6132D583E7C7DF0E58C2B8C0509467F1B9C3DE205604C50CE992A739FA533D570BE5F4239D09`
SSDEEP | `6144:o+fHmTywXJ76XX9fbkAP4sV1qHXX3V/AFyp:oMs7C9fbkAP4sVIHXd7p`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `10FB713319027F3F1F1C0667B3C38CA9`
* Thumbprint: `45548B92B80CB79A7C628B83D9DBA37B9C86971D`
* Issuer: CN=Symantec Class 3 Extended Validation Code Signing CA - G2, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN="Adobe Systems, Incorporated", OU=Acrobat DC, O="Adobe Systems, Incorporated", L=San Jose, S=California, C=US, SERIALNUMBER=2748129, OID.2.5.4.15=Private Organization, OID.1.3.6.1.4.1.311.60.2.1.2=Delaware, OID.1.3.6.1.4.1.311.60.2.1.3=US

## File Metadata

* Original Filename: Setup.exe
* Product Name: Bootstrapper Small
* Company Name: Adobe Systems Incorporated
* File Version: 15.9.20069.159242
* Product Version: 15.9.20069.159242
* Language: English (United States)
* Legal Copyright: Copyright  2015 Adobe Systems Incorporated.  All rights reserved.


## Possible Misuse

*The following table contains possible examples of `setup.exe` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [pypi-publish.yml](https://github.com/Neo23x0/sigma/blob/master/.github/workflows/pypi-publish.yml) | `      uses: actions/setup-python@v1` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sigma-test.yml](https://github.com/Neo23x0/sigma/blob/master/.github/workflows/sigma-test.yml) | `      uses: actions/setup-python@v1` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [cisco_cli_net_sniff.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/cisco/aaa/cisco_cli_net_sniff.yml) | `description: Show when a monitor or a span/rspan is setup or modified` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [cisco_cli_net_sniff.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/cisco/aaa/cisco_cli_net_sniff.yml) | `    - Admins may setup new or modify old spans, or use a monitor for troubleshooting.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_security_eventlog_cleared.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_security_eventlog_cleared.yml) | `    - Rollout of log collection agents (the setup routine often includes a reset of the local Eventlog)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mal_flowcloud.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/malware/win_mal_flowcloud.yml) | `      - 'HKLM\SYSTEM\Setup\PrintResponsor\\*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2019_1378.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2019_1378.yml) | `            - '*\cmd.exe /c C:\Windows\Setup\Scripts\SetupComplete.cmd'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2019_1378.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2019_1378.yml) | `            - '*\cmd.exe /c C:\Windows\Setup\Scripts\PartnerSetupComplete.cmd'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2019_1378.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2019_1378.yml) | `            - 'C:\Windows\Setup\\*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Setup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Setup.yml) | `Name: Setup.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Setup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Setup.yml) | `  - Command: Run Setup.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Setup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Setup.yml) | `    Description: Hijack hpbcsiServiceMarshaller.exe and run Setup.exe to launch a payload.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | ` - IOC: HKLM\SOFTWARE\Microsoft\Active Setup\Installed Components\YOURKEY` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Setupapi.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Setupapi.yml) | `Description: Windows Setup Application Programming Interface` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syssetup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Syssetup.yml) | `Description: Windows NT System Setup` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [attor](https://github.com/eset/malware-ioc/blob/master/attor/README.adoc) | `%COMMONAPPDATA%\Adobe\Setup\Replicate\US-sf` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [attor](https://github.com/eset/malware-ioc/blob/master/attor/README.adoc) | `%COMMONAPPDATA%\Adobe\Setup\Replicate\US-nh` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [attor](https://github.com/eset/malware-ioc/blob/master/attor/README.adoc) | `%COMMONAPPDATA%\Adobe\Setup\Replicate\US-zn` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [attor](https://github.com/eset/malware-ioc/blob/master/attor/README.adoc) | `%COMMONAPPDATA%\Adobe\Setup\Replicate\US-pq` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [glupteba.misp-event.json](https://github.com/eset/malware-ioc/blob/master/glupteba/glupteba.misp-event.json) | `                "value": "setup.exe\|f7230b2cab4e4910bca473b39ee8fd4df394ce0d",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [glupteba](https://github.com/eset/malware-ioc/blob/master/glupteba/README.adoc) | `\|`F7230B2CAB4E4910BCA473B39EE8FD4DF394CE0D`\|setup.exe   \|MSIL/Adware.CsdiMonetize.AG` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [potao](https://github.com/eset/malware-ioc/blob/master/potao/README.adoc) | `Fake TrueCrypt Setup:` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [windigo](https://github.com/eset/malware-ioc/blob/master/windigo/README.adoc) | `depending on your setup. For example we know that `suPHP` uses shared memory.` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | `setup.exe` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-05-01/Atomic_Friday.md) | ## Setup | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Getting_Lateral.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-05-01/Getting_Lateral.md) | ## Setup | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


