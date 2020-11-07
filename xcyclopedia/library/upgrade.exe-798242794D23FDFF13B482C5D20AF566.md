---
title: upgrade.exe | Glary Utilities Upgrade
excerpt: What is upgrade.exe?
---

# upgrade.exe 

* File Path: `C:\Program Files (x86)\Glary Utilities 5\upgrade.exe`
* Description: Glary Utilities Upgrade

## Hashes

Type | Hash
-- | --
MD5 | `798242794D23FDFF13B482C5D20AF566`
SHA1 | `B579ABB462609D27AF5179101668DBDCC9B9747D`
SHA256 | `5619BFF1CA4B89340A4CB40596257EBAFC79605FCD864A391CC5BE9B4F3216B0`
SHA384 | `0875086E31A586EB0A6DA4D7F8A8B1B868A0A2351937D3607CF0E138EF1599A4FC67603B279A71A0659FB7B370373955`
SHA512 | `752A160C826099252BA55DEEC90FE0A58BA1C2F0EFEB3A8A6A9A815EBF9BE60D330E305A538876A18144BBA698B5C39E71A0282A49CA08B7B6A5CDC7D44C57E9`
SSDEEP | `1536:oJMyihOOXd78vyBxF1pnOS8zORuCpeyK5jREdxOSOxiebVHxUfc:oJMyihOOXd7SyBxF1pnOSQORu4ezUxOp`
IMP | `C86E4545EC619A9589CB00E12FAC7A3B`
PESHA1 | `155128C1C84B0E75AD10627E4D742F749514FE5D`
PE256 | `97E31FB4B9E36423209D5EE0B0A7196636282E00ED1EC99F3E2C12480207D0D0`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Glary Utilities 5\upgrade.exe |
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/5619bff1ca4b89340a4cb40596257ebafc79605fcd864a391cc5be9b4f3216b0/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Glary Utilities 5\upgrade.exe](upgrade.exe-74869BF2044224A3F132FE0024980BC2.md) | 94
[C:\Program Files (x86)\Glary Utilities 5\upgrade.exe](upgrade.exe-9810F0E323B516DE7A1565BFF34CC95F.md) | 94

## Possible Misuse

*The following table contains possible examples of `upgrade.exe` being misused. While `upgrade.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [pypi-publish.yml](https://github.com/Neo23x0/sigma/blob/master/.github/workflows/pypi-publish.yml) | `python -m pip install --upgrade pip` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sigma-test.yml](https://github.com/Neo23x0/sigma/blob/master/.github/workflows/sigma-test.yml) | `python -m pip install --upgrade pip` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_service_stop.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_service_stop.yml) | `- Administrator shutting down the service due to upgrade or removal purposes` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [adjectives.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/adjectives.txt) | `upgrade` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rakos.yar](https://github.com/eset/malware-ioc/blob/master/rakos/rakos.yar) | `$ = "upgrade/vars.yaml"` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [vf_ioc_linux_rakos.py](https://github.com/eset/malware-ioc/blob/master/rakos/vf_ioc_linux_rakos.py) | `$ = "upgrade/vars.yaml"` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_vpnfilter.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_vpnfilter.yar) | $x3 = "Please upgrade! This version of Tor (%s) is %s, according to the directory authorities. Recommended versions are: %s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_mirai.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_mirai.yar) | $s2 = "loadURL>$(echo HUAWEIUPNP)</NewDownloadURL></u:Upgrade></s:Body></s:Envelope>" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | $s2 = "Virtual hardware upgrade helper service" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


