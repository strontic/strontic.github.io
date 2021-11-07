---
title: upgrade.exe | Glary Utilities Upgrade
excerpt: What is upgrade.exe?
---

# upgrade.exe 

* File Path: `C:\program files (x86)\Glary Utilities 5\upgrade.exe`
* Description: Glary Utilities Upgrade

## Hashes

Type | Hash
-- | --
MD5 | `74869BF2044224A3F132FE0024980BC2`
SHA1 | `F7F78281C4E55958FB8D3B40DE83C1B88710248E`
SHA256 | `0100BA9D1CF2465941B9F131BC8B69B40C71CAF51950FE169B9408380CF33736`
SHA384 | `109243BA462B74DB24A6DB2431D322919F0F25F1F367E7189FACFDAA4D23E91C5EA19D730901191B8DD24BE98B127866`
SHA512 | `BBFFE22D2558EA8306C2246126DC02B4076E789D082374E0B17627DDA70095BF608B426A10A87E96229FC209B72CB9A9BC6E6DAF8DBF3A3BF669324A705BE4FF`
SSDEEP | `1536:yJMyihOOXd78vyBxF1pnOS8zORuCpeyK5jREdxOSOxiegVHvUft:yJMyihOOXd7SyBxF1pnOSQORu4ezUxOL`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Glary Utilities 5\upgrade.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `0F05AE21CDC17B9F3CF09D7BFC659BA3`
* Thumbprint: `362EBB303E088105BDCC07D94E6B7875D30C0D06`
* Issuer: CN=DigiCert Assured ID Code Signing CA-1, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=Glarysoft LTD, O=Glarysoft LTD, S=Beijing, C=CN

## File Metadata

* Original Filename: upgrade.exe
* Product Name: Glary Utilities
* Company Name: Glarysoft Ltd
* File Version: 5.0.0.12
* Product Version: 5.0.0.12
* Language: English
* Legal Copyright: Copyright (c) 2003-2020 Glarysoft Ltd


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Glary Utilities 5\upgrade.exe](upgrade.exe-798242794D23FDFF13B482C5D20AF566.md) | 94
[C:\Program Files (x86)\Glary Utilities 5\upgrade.exe](upgrade.exe-9810F0E323B516DE7A1565BFF34CC95F.md) | 94

## Possible Misuse

*The following table contains possible examples of `upgrade.exe` being misused. While `upgrade.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sigma-test.yml](https://github.com/Neo23x0/sigma/blob/master/.github/workflows/sigma-test.yml) | `python -m pip install --upgrade pip`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_service_stop.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_service_stop.yml) | `- Administrator shutting down the service due to upgrade or removal purposes`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [adjectives.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/adjectives.txt) | `upgrade`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nightscout](https://github.com/eset/malware-ioc/blob/master/nightscout/README.adoc) | `http://cdn.cloudfronter[.]com/player/upgrade/ext/20201030/1/35e3797508c555d5f5e19f721cf94700.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nightscout](https://github.com/eset/malware-ioc/blob/master/nightscout/README.adoc) | `http://cdn.cloudfronter[.]com/player/upgrade/ext/20201101/1/bf571cb46afc144cab53bf940da88fe2.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nightscout](https://github.com/eset/malware-ioc/blob/master/nightscout/README.adoc) | `http://cdn.cloudfronter[.]com/player/upgrade/ext/20201123/1/2ca0a5f57ada25657552b384cf33c5ec.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nightscout](https://github.com/eset/malware-ioc/blob/master/nightscout/README.adoc) | `http://cdn.cloudfronter[.]com/player/upgrade/ext/20201225/7c21bb4e5c767da80ab1271d84cc026d.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nightscout](https://github.com/eset/malware-ioc/blob/master/nightscout/README.adoc) | `http://cdn.cloudfronter[.]com/player/upgrade/ext/20210119/842497c20072fc9b92f2b18e1d690103.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nightscout](https://github.com/eset/malware-ioc/blob/master/nightscout/README.adoc) | `https://cdn.cloudfronte[.]com/player/upgrade/ext/20201020/1/c697ad8c21ce7aca0a98e6bbd1b81dff.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nightscout](https://github.com/eset/malware-ioc/blob/master/nightscout/README.adoc) | `http://cdn.cloudfronte[.]com/player/upgrade/ext/20201030/1/35e3797508c555d5f5e19f721cf94700.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nightscout](https://github.com/eset/malware-ioc/blob/master/nightscout/README.adoc) | `http://res06.bignox[.]com/player/upgrade/202009/6c99c19d6da741af943a35016bb05b35.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nightscout](https://github.com/eset/malware-ioc/blob/master/nightscout/README.adoc) | `http://res06.bignox[.]com/player/upgrade/202009/42af40f99512443cbee03d090658da64.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rakos.yar](https://github.com/eset/malware-ioc/blob/master/rakos/rakos.yar) | `$ = "upgrade/vars.yaml"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [vf_ioc_linux_rakos.py](https://github.com/eset/malware-ioc/blob/master/rakos/vf_ioc_linux_rakos.py) | `$ = "upgrade/vars.yaml"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_vpnfilter.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_vpnfilter.yar) | $x3 = "Please upgrade! This version of Tor (%s) is %s, according to the directory authorities. Recommended versions are: %s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_mirai.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_mirai.yar) | $s2 = "loadURL>$(echo HUAWEIUPNP)</NewDownloadURL></u:Upgrade></s:Body></s:Envelope>" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | $s2 = "Virtual hardware upgrade helper service" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


