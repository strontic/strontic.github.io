---
title: RegDelNull.exe | Delete Registry keys with embedded Nulls
excerpt: What is RegDelNull.exe?
---

# RegDelNull.exe 

* File Path: `C:\SysinternalsSuite\RegDelNull.exe`
* Description: Delete Registry keys with embedded Nulls

## Hashes

Type | Hash
-- | --
MD5 | `BCB5CCFC0A924A222FB88BA35BC623B9`
SHA1 | `68E4A057BBEFE71A02D864223167BABD57DFF28E`
SHA256 | `E39DA31D87C447CFA9C5B1251DF92FF418F9E873997E76CCAB1CCCA72C9D65D9`
SHA384 | `2DA6A7A3A6BD249656C0FFC231DB8F7C99DD5F6A9622F2BDE2D384528BC4F8B61C6639AD1425A24E87E751C709D1D640`
SHA512 | `1C6B0BDF6B5838AC17D47DA2CDED525E0DCB4507A11C52EC64106F9F776B16935D32E8ADB52EA5DC5D04EBDECCE99F9518A14B56188D1AECC794AEDA2A2A67CF`
SSDEEP | `6144:dnKg/FRoY3QcS2HTL0WpRl0ozPg1KXVcZw7e0LSJ/:dKg/FZ3QB2HTLRpj02EjutQ/`
IMP | `3139255730B05278872883E46827DE09`
PESHA1 | `3B37509FF24E901B3239DB0756D1772F36569DFE`
PE256 | `D82A3E738228D5288B24D56A8672DD97B4FC3AB7C9EDDE1AFFFD778027C0BFC4`

## Runtime Data

### Usage (stdout):
```cmhg

RegDelNull v1.11 - Delete Registry keys with embedded Nulls
Copyright (C) 2005-2016 Mark Russinovich
Sysinternals - www.sysinternals.com

Usage: regdelnull <path> [-s]
  path    Registry path e.g. hklm\software
  -s      Recurse into subkeys
  -y      Suppress prompting for confirmation before deleting null-embedded keys.
  -nobanner
          Do not display the startup banner and copyright message.

Example: regdelnull -s hklm
This command scans all keys under HKLM.


```

### Usage (stderr):
```cmhg
The handle is invalid.

```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\RegDelNull.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RegDelNull.exe
* Product Name: Sysinternals RegDelNull
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 1.11
* Product Version: 1.11
* Language: English (United States)
* Legal Copyright: Copyright (C) 2005-2016 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/e39da31d87c447cfa9c5b1251df92ff418f9e873997e76ccab1ccca72c9d65d9/detection/


## Possible Misuse

*The following table contains possible examples of `RegDelNull.exe` being misused. While `RegDelNull.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-dukes-operation-ghost-event.json](https://github.com/eset/malware-ioc/blob/master/dukes/misp-dukes-operation-ghost-event.json) | `"https://docs.microsoft.com/en-us/sysinternals/downloads/regdelnull"` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"https://docs.microsoft.com/en-us/sysinternals/downloads/regdelnull"` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


