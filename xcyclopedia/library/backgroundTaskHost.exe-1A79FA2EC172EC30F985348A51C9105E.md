---
title: backgroundTaskHost.exe | Background Task Host
excerpt: What is backgroundTaskHost.exe?
---

# backgroundTaskHost.exe 

* File Path: `C:\WINDOWS\SysWOW64\backgroundTaskHost.exe`
* Description: Background Task Host

## Hashes

Type | Hash
-- | --
MD5 | `1A79FA2EC172EC30F985348A51C9105E`
SHA1 | `B4E1355680805AE75C5B5883696C0BDDE425C648`
SHA256 | `329061796EAE488A7975F2AFD2A6D006B6B298F46EFEC27586F912133EDFDE77`
SHA384 | `C3D36D21E3683822FBA395A2B911BA30BAE970ACA13B3DFD9884EC9BE6EDBB1A8EFB9089A66F079D6674C4DBD480EDB6`
SHA512 | `CDBC3D9F66FBCAE7E4C45A18E686D067B830894B7C5CF2AC4CD00CDD6ADFBCA59722CF7C31CE36B68662B3B71AEEEFEB16EAE56EDA339B7176E31BDDAB5C0A32`
SSDEEP | `192:3/DxJwhRzyPhs/vYuYg4MQfcHbHZWWeGWLWUyfUlHDBQABJa8sJxZAqnajKs7pA:v0OP6XYi7Hb5WBGWDDBRJMJ/AlGs7pA`
IMP | `A31469248789F14C80924950705CFE3E`
PESHA1 | `DD0EF08E1A1A1AB8FDE1640853ADB7A45B3D8E82`
PE256 | `6781A2E0E7887879840962CC4F5DBFF0865CF487AF1744055DA8CFA266D0E71B`

## Runtime Data

### Child Processes:
backgroundTaskHost.exe WerFault.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Windows | File
(RW-)   C:\Windows\SysWOW64 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\backgroundTaskHost.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: backgroundTaskHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/329061796eae488a7975f2afd2a6d006b6b298f46efec27586f912133edfde77/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\backgroundTaskHost.exe](backgroundTaskHost.exe-AFFD26BF186915A32218A855976E6697.md) | 50
[C:\WINDOWS\system32\dllhost.exe](dllhost.exe-B620F16B5BE791ADE73EC395C7EC1B53.md) | 38
[C:\WINDOWS\system32\icsunattend.exe](icsunattend.exe-D4B94D62AD95291F1C61D312B6B22044.md) | 38

## Possible Misuse

*The following table contains possible examples of `backgroundTaskHost.exe` being misused. While `backgroundTaskHost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_abusing_azure_browser_sso.yml) | `- BackgroundTaskHost.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


