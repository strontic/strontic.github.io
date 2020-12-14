---
title: Decoder.exe | 
excerpt: What is Decoder.exe?
---

# Decoder.exe 

* File Path: `C:\Program Files (x86)\MediaMonkey\Decoder.exe`

## Hashes

Type | Hash
-- | --
MD5 | `15D565744E247642E1FA4AD53A104B22`
SHA1 | `2CC9FC6533D887FA89A6E6A5F9E3CE647EC87472`
SHA256 | `F69A496FA88D0A8555CA7411AB126CFF318A7D452000F82A0092CBF16576C685`
SHA384 | `9BB0454A90ADC7C24D7C60D0AAC82509C32D5E6E4C72F6E921AB728BD5F5AD3B1D26793F7A53E1B983EA0F244E40A52A`
SHA512 | `4B347E8DCD2B065ADAD32D2E6CDDA6D7047279121FD233DBF9A18CC6CF83B1E970570C82BF7E37BAD5E93CA268E6922CDD2AA251BEF9F966CC2862F83A13B23C`
SSDEEP | `3072:0Txcu4nk+RWF4QNrPQTYdn/AWKNrskzsurtOW3+dw888888888888W888888888g:sxcu9+RWHFPft/LerNsAtbuG88888882`
IMP | `E353F028C5E372D09685EFED76D17327`
PESHA1 | `51FCF5F45507FFF6D7E87985F33C77693C9037AA`
PE256 | `2FB69738F2BAAF10502B2C5F47530C8B5D307B813EF93BED63C97E60578695BB`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\MediaMonkey\Decoder.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `7B48448F76331B9D5BCA1077F55FD710`
* Thumbprint: `8369C04328BF47436E5A459D1473F8DB66552DE2`
* Issuer: CN=thawte SHA256 Code Signing CA, O="thawte, Inc.", C=US
* Subject: CN="Ventis Media, Inc.", OU=Application Development, O="Ventis Media, Inc.", L=Cote Saint-Luc, S=Quebec, C=CA

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 1/72
* VirusTotal Link: https://www.virustotal.com/gui/file/f69a496fa88d0a8555ca7411ab126cff318a7d452000f82a0092cbf16576c685/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\MediaMonkey\VisHelper.exe](VisHelper.exe-6F87A8BD73D3B46423F25058CE1E3636.md) | 30

## Possible Misuse

*The following table contains possible examples of `Decoder.exe` being misused. While `Decoder.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_cobaltstrike_evasive.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_cobaltstrike_evasive.yar) | description = "Detects CobaltStrike sleep_mask decoder" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $x2 = "Here is the decoder+(encoded-decoder)+payload" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_susp_lnk_files.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_susp_lnk_files.yar) | $cert = " -decode " ascii //base64 decoder | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


