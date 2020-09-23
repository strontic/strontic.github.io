---
title: Uninstaller.exe | Glary Utilities Uninstaller
excerpt: What is Uninstaller.exe?
---

# Uninstaller.exe 

* File Path: `C:\Program Files (x86)\Glary Utilities 5\Uninstaller.exe`
* Description: Glary Utilities Uninstaller

## Screenshot

![Uninstaller.exe](screenshots/Uninstaller.exe-6F21F9194F24996C8D7322BA72742296-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `6F21F9194F24996C8D7322BA72742296`
SHA1 | `DFECD3EAA14382BADB0D002478C2A154F9D5E7A9`
SHA256 | `F453B5C932EE145266AAE51E36934941E7FE669AB67C1F54FA4F2579F2F877BD`
SHA384 | `68279D416EDDB20D1364A89ECA7E01753CE5401E0AF9EDCCACBF34AAD27D431E7FB9C35D8AA3E7F092165DB2D71AF861`
SHA512 | `65843F4B79EB2A0E5FB84598BB0284F8F5EC5D819D7F04618CA4C90C6804412715CBD9C160E28BAC1A487C55CC97AFDDAB90F944473B7C468F37E5E838B7A429`
SSDEEP | `6144:KVWpmtlYjMRGDnHmTnED5yh/OGTPIiInUAQ8wIn:YqHjMRGLHqQ4hVSndQ8wIn`

## Signature

* Status: Signature verified.
* Serial: `0F05AE21CDC17B9F3CF09D7BFC659BA3`
* Thumbprint: `362EBB303E088105BDCC07D94E6B7875D30C0D06`
* Issuer: CN=DigiCert Assured ID Code Signing CA-1, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=Glarysoft LTD, O=Glarysoft LTD, S=Beijing, C=CN

## File Metadata

* Original Filename: unInstaller.exe
* Product Name: Glary Utilities
* Company Name: Glarysoft Ltd
* File Version: 5.3.0.28
* Product Version: 5.3.0.1
* Language: Chinese (Simplified, China)
* Legal Copyright: Copyright (c) 2003-2020 Glarysoft Ltd


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Glary Utilities 5\Uninstaller.exe](Uninstaller.exe-C1EC83CE8E0BC8BF186C638B10C4233C.md) | 94

## Possible Misuse

*The following table contains possible examples of `Uninstaller.exe` being misused. While `Uninstaller.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-kryptocibule.json](https://github.com/eset/malware-ioc/blob/master/kryptocibule/misp-kryptocibule.json) | `"value": "magnet:?xt=urn:btih:icwxb43ebmema4xnk42aines3f2jfmpd&dn=Ashampoo UnInstaller v8.00.12 (2-click run).zip&xl=30490782&fc=1",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [kryptocibule](https://github.com/eset/malware-ioc/blob/master/kryptocibule/README.adoc) | `\|`magnet[:]?xt=urn[:]btih[:]icwxb43ebmema4xnk42aines3f2jfmpd&dn=Ashampoo UnInstaller v8.00.12 (2-click run).zip&xl=30490782&fc=1`\| - ` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | Uninstall Crowdstrike Falcon. If the WindowsSensor.exe path is not provided as an argument we need to search for it. Since the executable is located in a folder named with a random guid we need to identify it before invoking the uninstaller. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wildneutron.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wildneutron.yar) | $s4 = " Player Installer/Uninstaller" fullword wide /* PEStudio Blacklist: strings */ /* score: '11.42' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


