---
title: MoUsoCoreWorker.exe | MoUSO Core Worker Process
excerpt: What is MoUsoCoreWorker.exe?
---

# MoUsoCoreWorker.exe 

* File Path: `C:\Windows\system32\MoUsoCoreWorker.exe`
* Description: MoUSO Core Worker Process

## Hashes

Type | Hash
-- | --
MD5 | `B6792D02AEB8DB441B4839AB0A5E9708`
SHA1 | `9D3F5723E584E544D0FAB346C9658CC3D931C176`
SHA256 | `4D61C6EA5CB8CB6E393FB0042987E4AF667BD4314A4918F48A29E497528D60AD`
SHA384 | `469DA1A4C3CA72E111578343EF5C65F64A234F7D9D42F0154ED95EFECD2A7A5476054C61084077D42AE5D6B878DEC1DD`
SHA512 | `7CFC85B05EE70E7CCA46E1669F41F20A2E42519B339F28BFA7DCEB3F42B8606F14EE98E3BD7E5E741F2CA091A9FD76CF466A66442DA050FEC097E7DC3FB55DA2`
SSDEEP | `24576:ncFFsrfwbnEpD6WcJlFiPvJtLgSgEs+ktsG3CZ:YirfwDJsgSgEutC`
IMP | `39233DDAE71CD9D2B0CA5AA6FDD61054`
PESHA1 | `F8DE8EAF173F08323B6B700DBF182F80595620DD`
PE256 | `CE0ADCAE28CFC8E758C791CD345C376D7E7C77DE35A70BD9B2887FD9364E15EC`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user\Documents | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MoUsoCoreWorker.exe |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MoUSOCoreWorker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/4d61c6ea5cb8cb6e393fb0042987e4af667bd4314a4918f48a29e497528d60ad/detection/


## Possible Misuse

*The following table contains possible examples of `MoUsoCoreWorker.exe` being misused. While `MoUsoCoreWorker.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\MoUsoCoreWorker.exe'  # c:\windows\System32\MoUsoCoreWorker.exe on win10 20H04 at least` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


