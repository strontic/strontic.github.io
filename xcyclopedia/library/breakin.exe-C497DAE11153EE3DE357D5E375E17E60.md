---
title: breakin.exe | Microsoft Breakpoint forcer
excerpt: What is breakin.exe?
---

# breakin.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\breakin.exe`
* Description: Microsoft Breakpoint forcer

## Hashes

Type | Hash
-- | --
MD5 | `C497DAE11153EE3DE357D5E375E17E60`
SHA1 | `8A7285FBEE44F45A2578D0A9909BF0B6FCC84D26`
SHA256 | `D78FB281572D505D72A337152EFDF32B2E10F2A004DB4F86AE81C1FC747E0667`
SHA384 | `28CE2E1C6D4D33BE295C2E4BC9C8FD03FB3EDC15C4C063A98279E79581B53DCEA2FA477FA75F01EE6D7AC4E136D44887`
SHA512 | `4519A12743DF59FA27C1F933FBC17642A60E4F6120AE2D26F52971F688EC8DC8B7E7B76CB79680CE37614FE82D8D55E3F2E59BC0F18218B374E3E30F02CF3A60`
SSDEEP | `384:8aeTF6/zWKEO0xaWSkcGWYGNW6LwGyJE7olz8F:J3/P7QrSkcf1zI`
IMP | `E8F5B6B7002A3987061C7F6ED8FB24A5`
PESHA1 | `36515488610775E9450BBB57ED23DE7E6342334B`
PE256 | `2AC93D564DA7B639A895A4B6E5284132027C5D9CC4445C1E3798B09022BF37B6`

## Runtime Data

### Usage (stderr):
```cmhg
usage: breakin <pid>

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\breakin.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown


## Possible Misuse

*The following table contains possible examples of `breakin.exe` being misused. While `breakin.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-dukes-operation-ghost-event.json](https://github.com/eset/malware-ioc/blob/master/dukes/misp-dukes-operation-ghost-event.json) | `"description": "A 2015 report by F-Secure describe APT29 as: 'The Dukes are a well-resourced, highly dedicated and organized cyberespionage group that we believe has been working for the Russian Federation since at least 2008 to collect intelligence in support of foreign and security policy decision-making. The Dukes show unusual confidence in their ability to continue successfully compromising their targets, as well as in their ability to operate with impunity. The Dukes primarily target Western governments and related organizations, such as government ministries and agencies, political think tanks, and governmental subcontractors. Their targets have also included the governments of members of the Commonwealth of Independent States;Asian, African, and Middle Eastern governments;organizations associated with Chechen extremism;and Russian speakers engaged in the illicit trade of controlled substances and drugs. The Dukes are known to employ a vast arsenal of malware toolsets, which we identify as MiniDuke, CosmicDuke, OnionDuke, CozyDuke, CloudDuke, SeaDuke, HammerDuke, PinchDuke, and GeminiDuke. In recent years, the Dukes have engaged in apparently biannual large - scale spear - phishing campaigns against hundreds or even thousands of recipients associated with governmental institutions and affiliated organizations. These campaigns utilize a smash - and - grab approach involving a fast but noisy breakin followed by the rapid collection and exfiltration of as much data as possible.If the compromised target is discovered to be of value, the Dukes will quickly switch the toolset used and move to using stealthier tactics focused on persistent compromise and long - term intelligence gathering. This threat actor targets government ministries and agencies in the West, Central Asia, East Africa, and the Middle East; Chechen extremist groups; Russian organized crime; and think tanks. It is suspected to be behind the 2015 compromise of unclassified networks at the White House, Department of State, Pentagon, and the Joint Chiefs of Staff. The threat actor includes all of the Dukes tool sets, including MiniDuke, CosmicDuke, OnionDuke, CozyDuke, SeaDuke, CloudDuke (aka MiniDionis), and HammerDuke (aka Hammertoss). '",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


