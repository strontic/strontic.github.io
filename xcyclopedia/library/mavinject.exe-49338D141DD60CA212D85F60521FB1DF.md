---
title: mavinject.exe | Microsoft Application Virtualization Injector
excerpt: What is mavinject.exe?
---

# mavinject.exe 

* File Path: `C:\Windows\SysWOW64\mavinject.exe`
* Description: Microsoft Application Virtualization Injector

## Hashes

Type | Hash
-- | --
MD5 | `49338D141DD60CA212D85F60521FB1DF`
SHA1 | `7751C7C2371AC15896D855759037757DEB1C7954`
SHA256 | `BD4D2AEA5385982D180C36077ECFC007CE65C5B41AABAE97239643EE940858A3`
SHA384 | `AC0B888F0E0FAD2A3C5C8F03F01F688844DB872530538353F5C0D3CC494012AE285D13D175EC3AEA8FC99BC7C6666069`
SHA512 | `741BDC29B143627605DB2BE147536418D78F92D73D0B28989EEE2EDF3E5E194AAF9BF2939F91AF25D769DFFA8306D5DA5CD085629064EAF9C094AC3765870BE9`
SSDEEP | `3072:Av8vmmt0fSoD7WHi88+Yed7BF1OKp7Xgy:Av0mmt0fSoD7WHi7+YLK`
IMP | `92734E64BEDF9E93EEC501508D2B049C`
PESHA1 | `E4DDF26C081DA0354E40DED3B17C75FED5572A5A`
PE256 | `D40DB7FF5C47ADD4AA99546994D6ABE8D3468E575A05FED744DA3518604DB0DB`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\mavinject.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mavinject32.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/bd4d2aea5385982d180c36077ecfc007ce65c5b41aabae97239643ee940858a3/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft Office\root\Client\AppVDllSurrogate32.exe](AppVDllSurrogate32.exe-BB87D970CD29CC07A84A92E637ADD9A2.md) | 50
[C:\Program Files (x86)\Microsoft Office\root\Client\AppVLP.exe](AppVLP.exe-F8CF92A63D69595CE0E6ECB9265EA7F7.md) | 33
[C:\Program Files\Common Files\microsoft shared\ClickToRun\MavInject32.exe](MavInject32.exe-AC6978D0FEF8F6F2F07051473D188F02.md) | 32
[C:\Windows\SysWOW64\mavinject.exe](mavinject.exe-644673C741AB152A3E8904A5B4080489.md) | 49
[C:\WINDOWS\SysWOW64\mavinject.exe](mavinject.exe-8FE5871DE2870F39CFA317FA5C28988D.md) | 50
[C:\Windows\SysWOW64\mavinject.exe](mavinject.exe-A0B66B648C645B6B2A982C9414153437.md) | 44
[C:\Windows\SysWOW64\mavinject.exe](mavinject.exe-B8B01B6A24B8A2BA242D96DB63298120.md) | 65
[C:\Windows\SysWOW64\mavinject.exe](mavinject.exe-CB3E03CBECB798CE4254E1D17716C623.md) | 38

## Possible Misuse

*The following table contains possible examples of `mavinject.exe` being misused. While `mavinject.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_mavinject_proc_inj.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mavinject_proc_inj.yml) | `title: MavInject Process Injection`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mavinject_proc_inj.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mavinject_proc_inj.yml) | `- https://reaqta.com/2017/12/mavinject-microsoft-injector/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `Name: Mavinject.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `- Command: MavInject.exe 3110 /INJECTRUNNING c:\folder\evil.dll`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `- Command: Mavinject.exe 4172 /INJECTRUNNING "c:\ads\file.txt:file.dll"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `- Path: C:\Windows\System32\mavinject.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `- Path: C:\Windows\SysWOW64\mavinject.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mavinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mavinject.yml) | `- IOC: mavinject.exe should not run unless APP-v is in use on the workstation`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Process Injection via mavinject.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: mavinject - Inject DLL into running process [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Process Injection via mavinject.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: mavinject - Inject DLL into running process [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055/T1055.md) | - [Atomic Test #1 - Process Injection via mavinject.exe](#atomic-test-1---process-injection-via-mavinjectexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055/T1055.md) | ## Atomic Test #1 - Process Injection via mavinject.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055/T1055.md) | Upon successful execution, powershell.exe will download T1055.dll to disk. Powershell will then spawn mavinject.exe to perform process injection in T1055.dll. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055/T1055.md) | mavinject $mypid /INJECTRUNNING #{dll_payload} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1056.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1056.004/T1056.004.md) | mavinject $pid /INJECTRUNNING #{file_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | - [Atomic Test #1 - mavinject - Inject DLL into running process](#atomic-test-1---mavinject---inject-dll-into-running-process) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | ## Atomic Test #1 - mavinject - Inject DLL into running process | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | mavinject.exe #{process_id} /INJECTRUNNING #{dll_payload} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[stockpile](https://github.com/mitre/stockpile) | [e5bcefee-262d-4568-a261-e8a20855ec81.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/e5bcefee-262d-4568-a261-e8a20855ec81.yml) | `name: Signed Binary Execution - Mavinject`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [e5bcefee-262d-4568-a261-e8a20855ec81.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/e5bcefee-262d-4568-a261-e8a20855ec81.yml) | `description: Leverage Mavinject (signed binary) for DLL injection`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [e5bcefee-262d-4568-a261-e8a20855ec81.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/e5bcefee-262d-4568-a261-e8a20855ec81.yml) | `mavinject.exe $explorer.id C:\Users\Public\sandcat.dll`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


