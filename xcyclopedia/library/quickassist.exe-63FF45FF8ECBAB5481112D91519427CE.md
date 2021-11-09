---
title: quickassist.exe | Quick Assist
excerpt: What is quickassist.exe?
---

# quickassist.exe 

* File Path: `C:\WINDOWS\system32\quickassist.exe`
* Description: Quick Assist

## Screenshot

![quickassist.exe](screenshots/quickassist.exe-39AB5ED601B0C39DCE3B7D269847C944-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `63FF45FF8ECBAB5481112D91519427CE`
SHA1 | `BC8A9260611A6FAA00110CF8B9A23878EEFFF35B`
SHA256 | `81414991FCAE587B1CC93128354A1643E1BE6B166681A8904FDCE0F7BAA4CDCC`
SHA384 | `F2405C7F1CF4ADD999965829C1608205853FC026D98EFEE3DB386B26FD4002D43B2D567BAF1CD333BD123F9EC429E114`
SHA512 | `83A5A1836BFE2BC9A2F61397E7F62133FD946914D6D7F586CD4FAD5A6D3F4D0C233503AD7B5A109D6E01B5F27A9B34B6D008A303A8680192634C9606EFFACB1D`
SSDEEP | `12288:/MjgJ55JZuOml1P76eg/fabht5x0kaQpCvt112e:/MsJNZuZb76eg/uXn0Zvt11`
IMP | `088CC8C45F1D3E3327362D682B8E4FFC`
PESHA1 | `923AC5A095CBD86CE924B823DFA1CBD637B7658B`
PE256 | `69D8E7429CCF04004EB3D3BC469F01D2D8852F53BC502C7B4EBF944ABD1CBC09`

## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: QuickAssist.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/81414991fcae587b1cc93128354a1643e1be6b166681a8904fdce0f7baa4cdcc/detection


## Possible Misuse

*The following table contains possible examples of `quickassist.exe` being misused. While `quickassist.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_middle_east_talosreport.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_middle_east_talosreport.yar) | $s1 = "QuickAssist.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_middle_east_talosreport.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_middle_east_talosreport.yar) | $s4 = "name=\"QuickAssist\" " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


