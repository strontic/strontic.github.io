---
title: ashelper.exe | Cisco WebEx Application Advance Sharing Module
---

# ashelper.exe 

* File Path: `C:\ProgramData\WebEx\WebEx\T33_UMC\ashelper.exe`
* Description: Cisco WebEx Application Advance Sharing Module
* Comments: 01/16/2018 T32(Unicode)


## Hashes

Type | Hash
-- | --
MD5 | `97FADB5EF08B33E8F5CD910A3B1A8D07`
SHA1 | `899E9F90ECE56AE0032F686D8D8590C2A64CFFF6`
SHA256 | `62CEBCB83DE017D7C712EC42424F43C509AC1FFDB79C83931606B290FF01BE1F`
SHA384 | `0CFC064D2B9899239AD97E3D36E5DC4A216F3B9CEBF10D05BE2F3C625951DDB158AB626CF7576DADBD8662685756580A`
SHA512 | `D09D2F16C2977D515CA2B5B06C24D645940131EEC2B063EF7315AC6DE6A0060472BE7CC4D5A4B9961147161A1DF41BAC39A5767DAC5E655659138F9638D2D050`
SSDEEP | `1536:JjvLxD4cYK5AQsQxiu+DCNLk9l9KYn23h+N:JzLpTIQxi9DCLk9jLnPN`

## Signature

* Status: Signature verified.
* Serial: `4E5B56471959570CA0F805DF61D018DF`
* Thumbprint: `2491FC608AE018A29565D564DDB14BCDE435DC9C`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Cisco WebEx LLC, O=Cisco WebEx LLC, L=San Jose, S=California, C=US

## File Metadata

* Original Filename: ASHelper.exe
* Product Name: WebEx Application Sharing
* Company Name: Cisco WebEx LLC
* File Version: 1032,1811,0100,1600
* Product Version: 1032,1811,0100,1600
* Language: English (United States)
* Legal Copyright:  1997-2018 Cisco and/or its affiliates. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `ashelper.exe` being misused. While `ashelper.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | 		$s0 = "regsvr32 /s \"%ProgramFiles%\\Norton360\\Engine\\5.1.0.29\\ashelper.dll\"" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | 		$s4 = "\\ashelper.dll" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


