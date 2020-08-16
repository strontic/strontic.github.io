---
title: slide.exe | XnView SlideShow
---

# slide.exe 

* File Path: `C:\Program Files (x86)\XnView\PlugIns\slide.exe`
* Description: XnView SlideShow

## Hashes

Type | Hash
-- | --
MD5 | `525069DABF0E224533EABA59972654E5`
SHA1 | `AA75C5E0C00A1BEEBEECB52BCBB8C63A31ED9A8F`
SHA256 | `29BD36D3E9794C77BF72554FB5A6CC60E62121980C760ABA2A9E6DB9FF0FF4DA`
SHA384 | `F7A4423F7103F3BE333CF758E70C50FE0A598C043102DBB7BAD7AE8BE09811F73E88F21187BBDB72DD1177DD3F0ACABD`
SHA512 | `A9AADF6D7DE13854C5EA4F9165A1E5C24846304DD9860F527E68CE65E808C0F384731EFF237BD8C85DFD00C5F821FAE6AD0E94FD88A2D150F42C945BD763DD69`
SSDEEP | `3072:ZlGRh64nst6bfECOCJQplv2YxvQQqAkArHUnrF+84BdjlplvVJI:ZOZlJCqkkU0rFh2PVJ`

## Signature

* Status: The file C:\Program Files (x86)\XnView\PlugIns\slide.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: 
* Product Name: XnView
* Company Name: XnView, http://www.xnview.com
* File Version: 2.13
* Product Version: 2.13
* Language: English (United States)
* Legal Copyright: Copyright  1991-2005 by Gougelet Pierre-e


## Possible Misuse

*The following table contains possible examples of `slide.exe` being misused. While `slide.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `    - https://speakerdeck.com/heirhabarov/hunting-for-powershell-abuse?slide=26` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `  - Link: https://www.slideshare.net/chrisgates/windows-attacks-at-is-the-new-black-26672679 - slide 53` | 
[signature-base](https://github.com/Neo23x0/signature-base) | [airbnb_binaryalert.yar](https://github.com/Neo23x0/signature-base/blob/master/vendor/yara/airbnb_binaryalert.yar) |         $a2 = "leaked kaslr slide," wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


