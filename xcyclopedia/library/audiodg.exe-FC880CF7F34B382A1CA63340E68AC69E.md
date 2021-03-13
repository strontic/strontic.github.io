---
title: audiodg.exe | Windows Audio Device Graph Isolation 
excerpt: What is audiodg.exe?
---

# audiodg.exe 

* File Path: `C:\Windows\system32\audiodg.exe`
* Description: Windows Audio Device Graph Isolation 

## Hashes

Type | Hash
-- | --
MD5 | `FC880CF7F34B382A1CA63340E68AC69E`
SHA1 | `A1E284FC2C001A890BE1521DD4E6A8ED36833BC1`
SHA256 | `FEA9C450C817F121E112F551A3E1B628CF71A6A61E36F697D337CA60B7486189`
SHA384 | `24767F4F0EB87BE482617F85EC4FD3A6A248F12707A50180EB7B8465A1957EFA4F7DA6686F1E746A6B6C51076C097B57`
SHA512 | `46CEFBFB2CA9448FEB41DA1A4B60CFD11FDCB1F5827BF9C9CEBEB168DA3C0DAD24844F74509F08F81F100CC501F22B601B1BEF6D140EEEE4D9AA55F5778A9A56`
SSDEEP | `12288:uFDBfxLQX+qEjnungJmzVUkFGc55qI3LI:sBmOqEjunNzyk8Q/7`
IMP | `356C5FB039EB7424A518F132A23D3232`
PESHA1 | `F2AAFDE371276DACEC655046468591B004562B08`
PE256 | `10A6B214297D7F5AA6566548D8E80D15733E23DDAA729737091FB1FD93D658F6`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\audiodg.exe |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MMDevAPI.DLL |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: audioadg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/fea9c450c817f121e112f551a3e1b628cf71a6a61e36f697d337ca60b7486189/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\audiodg.exe](audiodg.exe-B234D0A8796076CCA38DEC2C0CABE380.md) | 58

## Possible Misuse

*The following table contains possible examples of `audiodg.exe` being misused. While `audiodg.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\audiodg.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\audiodg.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


