---
title: fodhelper.exe | Features On Demand Helper
excerpt: What is fodhelper.exe?
---

# fodhelper.exe 

* File Path: `C:\WINDOWS\system32\fodhelper.exe`
* Description: Features On Demand Helper

## Hashes

Type | Hash
-- | --
MD5 | `23D5F6C1A37BFDE53049960B7A9564A6`
SHA1 | `F7D00C07C3AE15F3A31240D8423CC054D43D6B48`
SHA256 | `2B5089D56EB0EC9B2854102B5FE984F5BE96756A170CC46774021E36B315EDC3`
SHA384 | `FB585FAA684A351C622C3328137E80B6B1EE6B3F64E67D870A8D59A8EA30617D2471E7D587ED57AA6F080508D743E06F`
SHA512 | `BE8D23EE1619C09E5DC6D60E9D6DF777A8D3D525CC7AD42DC75FA9756EA3BC1D8684E73E95944B56C640A91BA34DB9FEB6A2073F79EF41BB04082B84CABEEC43`
SSDEEP | `3072:qS8TqE7kDPF8kkh3iu+puvpsaXprs18G5:g97Mt8kk4u+0hskSmG`
IMP | `D45B3B548671932A38988F20E31C0E52`
PESHA1 | `737B916FAF3DDD8BD2074A49F246EC2BCF53F691`
PE256 | `0519521E42CB29F7B23FF5137AC7157F2C7FE630F968B541AA3658B8C1D05C18`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\ADVAPI32.dll |
C:\WINDOWS\System32\combase.dll |
C:\WINDOWS\system32\fodhelper.exe |
C:\WINDOWS\System32\GDI32.dll |
C:\WINDOWS\System32\gdi32full.dll |
C:\WINDOWS\System32\IMM32.DLL |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcp_win.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\OLEAUT32.dll |
C:\WINDOWS\System32\RPCRT4.dll |
C:\WINDOWS\System32\sechost.dll |
C:\WINDOWS\System32\SHELL32.dll |
C:\WINDOWS\System32\ucrtbase.dll |
C:\WINDOWS\System32\USER32.dll |
C:\WINDOWS\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FodHelper.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/2b5089d56eb0ec9b2854102b5fe984f5be96756a170cc46774021e36b315edc3/detection


## Possible Misuse

*The following table contains possible examples of `fodhelper.exe` being misused. While `fodhelper.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_fodhelper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_fodhelper.yml) | `title: Bypass UAC via Fodhelper.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_fodhelper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_fodhelper.yml) | `description: Identifies use of Fodhelper.exe to bypass User Account Control. Adversaries use this technique to execute privileged processes.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_fodhelper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_fodhelper.yml) | `ParentImage\|endswith: '\fodhelper.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_fodhelper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_fodhelper.yml) | `- Legitimate use of fodhelper.exe utility by legitimate user`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_shell_open.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_uac_bypass_shell_open.yml) | `description: Detects the pattern of UAC Bypass using fodhelper.exe, computerdefaults.exe, slui.exe via registry keys (e.g. UACMe 33 or 62)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [win_apt_invisimole_uac_bypass.yml](https://github.com/eset/malware-ioc/blob/master/invisimole/sigma/win_apt_invisimole_uac_bypass.yml) | `- '\fodhelper.exe'`{:.highlight .language-yaml} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Bypass UAC using Fodhelper [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #4: Bypass UAC using Fodhelper - PowerShell [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: Bypass UAC using Fodhelper [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #4: Bypass UAC using Fodhelper - PowerShell [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | - [Atomic Test #3 - Bypass UAC using Fodhelper](#atomic-test-3---bypass-uac-using-fodhelper) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | - [Atomic Test #4 - Bypass UAC using Fodhelper - PowerShell](#atomic-test-4---bypass-uac-using-fodhelper---powershell) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | ## Atomic Test #3 - Bypass UAC using Fodhelper | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Bypasses User Account Control using the Windows 10 Features on Demand Helper (fodhelper.exe). Requires Windows 10. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | fodhelper.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | ## Atomic Test #4 - Bypass UAC using Fodhelper - PowerShell | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | PowerShell code to bypass User Account Control using the Windows 10 Features on Demand Helper (fodhelper.exe). Requires Windows 10. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Start-Process "C:\Windows\System32\fodhelper.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Target:	\system32\fodhelper.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


