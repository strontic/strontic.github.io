---
title: breakin.exe | Microsoft Breakpoint forcer
excerpt: What is breakin.exe?
---

# breakin.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\breakin.exe`
* Description: Microsoft Breakpoint forcer

## Hashes

Type | Hash
-- | --
MD5 | `723BE264E0CCFD1E4EF1DA8C307AEC7D`
SHA1 | `0523C3721589228EB42DA555D0A31F74F616AF69`
SHA256 | `C9566AAEC773FBB5D0DCF12C2AAB85963979DFF085F8A13F03AEE95A5B6C0335`
SHA384 | `D107CBFB62B5E218D98A9C299C68DFB1A6AE7CA46BCB976D69B95D5E5202352917686F8F5AD70F74A1A8499640A5E005`
SHA512 | `7C41EBD8D69F9A6BB6D8A46E50973655904913EEDF5F0C04905645DD9AF20271A4BB96C995B42D9FB13CC4DB1684421F10EE079CBA1A77F276911EFF3EF4E000`
SSDEEP | `384:G3b+fZmLoWBrvfaxaMS0EOWYGNWtwGy2HS4JeRlFTWV:QMZOvfKxS0EXql58A`
IMP | `C77ABE483E27C8CC9A2B2DC69A1EC27E`
PESHA1 | `C3565A8E41B91308A8261C26D92807828048F019`
PE256 | `4502F2EA94E5325A26BDDB763B1936954AA9BEAFE8D2F2612BB549FC9B845698`

## Runtime Data

### Usage (stderr):
```cmhg
usage: breakin <pid>

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\breakin.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: breakin.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/c9566aaec773fbb5d0dcf12c2aab85963979dff085f8a13f03aee95a5b6c0335/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\breakin.exe](breakin.exe-3A457F977B3D6BC2A36B645608AAB8CD.md) | 35
[C:\Program Files (x86)\Windows Kits\10\Redist\10.0.19041.0\ucrt\DLLs\arm\api-ms-win-core-errorhandling-l1-1-0.dll](api-ms-win-core-errorhandling-l1-1-0.dll-428EA20CFB0FF6FB2CB00D109E29A4C0.md) | 29

## Possible Misuse

*The following table contains possible examples of `breakin.exe` being misused. While `breakin.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-dukes-operation-ghost-event.json](https://github.com/eset/malware-ioc/blob/master/dukes/misp-dukes-operation-ghost-event.json) | `"description": "A 2015 report by F-Secure describe APT29 as: 'The Dukes are a well-resourced, highly dedicated and organized cyberespionage group that we believe has been working for the Russian Federation since at least 2008 to collect intelligence in support of foreign and security policy decision-making. The Dukes show unusual confidence in their ability to continue successfully compromising their targets, as well as in their ability to operate with impunity. The Dukes primarily target Western governments and related organizations, such as government ministries and agencies, political think tanks, and governmental subcontractors. Their targets have also included the governments of members of the Commonwealth of Independent States;Asian, African, and Middle Eastern governments;organizations associated with Chechen extremism;and Russian speakers engaged in the illicit trade of controlled substances and drugs. The Dukes are known to employ a vast arsenal of malware toolsets, which we identify as MiniDuke, CosmicDuke, OnionDuke, CozyDuke, CloudDuke, SeaDuke, HammerDuke, PinchDuke, and GeminiDuke. In recent years, the Dukes have engaged in apparently biannual large - scale spear - phishing campaigns against hundreds or even thousands of recipients associated with governmental institutions and affiliated organizations. These campaigns utilize a smash - and - grab approach involving a fast but noisy breakin followed by the rapid collection and exfiltration of as much data as possible.If the compromised target is discovered to be of value, the Dukes will quickly switch the toolset used and move to using stealthier tactics focused on persistent compromise and long - term intelligence gathering. This threat actor targets government ministries and agencies in the West, Central Asia, East Africa, and the Middle East; Chechen extremist groups; Russian organized crime; and think tanks. It is suspected to be behind the 2015 compromise of unclassified networks at the White House, Department of State, Pentagon, and the Joint Chiefs of Staff. The threat actor includes all of the Dukes tool sets, including MiniDuke, CosmicDuke, OnionDuke, CozyDuke, SeaDuke, CloudDuke (aka MiniDionis), and HammerDuke (aka Hammertoss). '",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


