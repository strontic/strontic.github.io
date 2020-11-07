---
title: ScreenCapture.dll | ScreenCapture Module
excerpt: What is ScreenCapture.dll?
---

# ScreenCapture.dll 

* File Path: `C:\Program Files (x86)\Cisco Systems\Cisco Jabber\ScreenCapture.dll`
* Description: ScreenCapture Module

## Hashes

Type | Hash
-- | --
MD5 | `5E03E1CB26D14FEE6C3EBA323AA2371E`
SHA1 | `3E44A291D8FB35AB0C4E96E23D7E61F86AFE95B8`
SHA256 | `74375CDDB9C8FEFFED034953DABEEB47CCC4C4243E560B8FDD6D279515D3C2D5`
SHA384 | `14BC8BE6DA8348E1158F06A185C7003D025290042F75153B391E2C7E69D918A4D33C9C1B3A2562A5DB479AD6A053CEC0`
SHA512 | `77ABB88504EE1111F0BA2D607DF8039AAFE6B9AA82F9BE6CE030FE379F42F36E5572ACCBDF552FCBDD5C6D4DF6762F822AA90F77FC6FD6D1BFC9E316F081B955`
SSDEEP | `3072:c6mhqH/IFAr+xy5jA51zpXa4MXns5PvHEHjmSoZhQPX:c6mhqfIEt5jA51zpXkOvHEHSJrQ`
IMP | `842834F5FD92408C912C0721278E7E3C`
PESHA1 | `7B950E59513A50E42F464CBBC12FAF312B1675BC`
PE256 | `B2A9BF76CB1F11D468B4C12CF2894C642CBA8A2D2D6AE0C7244C8B9B6FAB5DD9`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`const ScreenCapture::``vftable'` | 13 | Exported Function
`ScreenCaptureImpl::SetLogger` | 19 | Exported Function
`ScreenCaptureImpl::SetLanguage` | 18 | Exported Function
`ScreenCaptureImpl::SaveFromClipboard` | 17 | Exported Function
`ScreenCaptureFact::getInstance` | 22 | Exported Function
`ScreenCaptureObserver::operator` | 12 | Exported Function
`ScreenCaptureObserver::operator` | 11 | Exported Function
`ScreenCapture::operator` | 10 | Exported Function
`ScreenCapture::operator` | 9 | Exported Function
`ScreenCaptureObserver::ScreenCaptureObserver` | 7 | Exported Function
`ScreenCaptureObserver::ScreenCaptureObserver` | 6 | Exported Function
`ScreenCaptureObserver::ScreenCaptureObserver` | 5 | Exported Function
`public: __thiscall ScreenCaptureImpl::~ScreenCaptureImpl(void)` | 8 | Exported Function
`ScreenCaptureImpl::ScreenCaptureImpl` | 4 | Exported Function
`ScreenCapture::ScreenCapture` | 3 | Exported Function
`ScreenCapture::ScreenCapture` | 2 | Exported Function
`ScreenCapture::ScreenCapture` | 1 | Exported Function
`ScreenCaptureImpl::ResetCaptureDialogInstance` | 16 | Exported Function
`ScreenCaptureImpl::CreateCaptureDialog` | 15 | Exported Function
`const ScreenCaptureObserver::``vftable'` | 14 | Exported Function
`std::weak_ptr` | 20 | Exported Function
`ScreenCaptureImpl::StopCapture` | 21 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `59C5C9F46EA82C4C743981566B64BD6C`
* Thumbprint: `475DAEE5A6CC149389EFDE176DEA526C627D203A`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA - G2, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Cisco Systems Inc., O=Cisco Systems Inc., L=San Jose, S=California, C=US

## File Metadata

* Original Filename: ScreenCapture.dll
* Product Name: ScreenCapture Module
* Company Name: 
* File Version: 710, 2011, 5, 18
* Product Version: 710, 2011, 5, 18
* Language: English (United States)
* Legal Copyright: Copyright 2011
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/74375cddb9c8feffed034953dabeeb47ccc4c4243e560b8fdd6d279515d3c2d5/detection/

## Possible Misuse

*The following table contains possible examples of `ScreenCapture.dll` being misused. While `ScreenCapture.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Adversaries may attempt to take screen captures of the desktop to gather information over the course of an operation. Screen capturing functionality may be included as a feature of a remote access tool used in post-compromise operations.\n\n### Mac\n\nOn OSX, the native command <code>screencapture</code> is used to capture screenshots.\n\n### Linux\n\nOn Linux, there is the native command <code>xwd</code>. (Citation: Antiquated Mac Malware)",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-powerpool.json](https://github.com/eset/malware-ioc/blob/master/powerpool/misp-powerpool.json) | `"description": "Adversaries may attempt to take screen captures of the desktop to gather information over the course of an operation. Screen capturing functionality may be included as a feature of a remote access tool used in post-compromise operations.\n\n===Mac===\n\nOn OSX, the native command <code>screencapture<\/code> is used to capture screenshots.\n\n===Linux===\n\nOn Linux, there is the native command <code>xwd<\/code>.[[Citation: Antiquated Mac Malware]]\n\nDetection: Monitoring for screen capture behavior will depend on the method used to obtain data from the operating system and write output files. Detection methods could include collecting information from unusual processes using API calls used to obtain image data, and monitoring for image files written to disk. The sensor data may need to be correlated with other events to identify malicious activity, depending on the legitimacy of this behavior within a given network environment.\n\nPlatforms: Windows Server 2003, Windows Server 2008, Windows Server 2012, Windows XP, Windows 7, Windows 8, Windows Server 2003 R2, Windows Server 2008 R2, Windows Server 2012 R2, Windows Vista, Windows 8.1, Windows 10, Linux, MacOS, OS X\n\nData Sources: API monitoring, Process monitoring, File monitoring",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Screencapture [macos] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: Screencapture (silent) [macos] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #5: Windows Screencapture [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) | - Atomic Test #1: Screencapture [macos] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) | - Atomic Test #2: Screencapture (silent) [macos] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #5: Windows Screencapture [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | <blockquote>Adversaries may attempt to take screen captures of the desktop to gather information over the course of an operation. Screen capturing functionality may be included as a feature of a remote access tool used in post-compromise operations. Taking a screenshot is also typically possible through native utilities or API calls, such as <code>CopyFromScreen</code>, <code>xwd</code>, or <code>screencapture</code>.(Citation: CopyFromScreen .NET)(Citation: Antiquated Mac Malware) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | - [Atomic Test #1 - Screencapture](#atomic-test-1---screencapture) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | - [Atomic Test #2 - Screencapture (silent)](#atomic-test-2---screencapture-silent) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | - [Atomic Test #5 - Windows Screencapture](#atomic-test-5---windows-screencapture) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | ## Atomic Test #1 - Screencapture | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | Use screencapture command to collect a full desktop screenshot | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | screencapture #{output_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | ## Atomic Test #2 - Screencapture (silent) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | screencapture -x #{output_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | ## Atomic Test #5 - Windows Screencapture | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


