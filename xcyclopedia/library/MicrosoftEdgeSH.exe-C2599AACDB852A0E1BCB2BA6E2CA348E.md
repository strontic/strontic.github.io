---
title: MicrosoftEdgeSH.exe | Microsoft Edge Web Platform
---

# MicrosoftEdgeSH.exe 

* File Path: `C:\Windows\system32\MicrosoftEdgeSH.exe`
* Description: Microsoft Edge Web Platform

## Hashes

Type | Hash
-- | --
MD5 | `C2599AACDB852A0E1BCB2BA6E2CA348E`
SHA1 | `2FD233F65D589BF6C4994818C3336BC8679D7CE1`
SHA256 | `E5D93718F0905B341D6FC68399257D88C56479B2A7FFB253FD88A405E6ED6E74`
SHA384 | `AB8A4059E1B3188E637C3D52642F0C71DB63799F9B13465DA9F87B1BCE03C90C5FEC6C9D4836ED981D9319AAFAE73938`
SHA512 | `ADB69E63122CD69240FB577016C77EB58A18D35528D173E31AE3E6820327606A9B83312AA308D808A635103080E6B7A00D2842F6334A7D0E6A63079ECBAC97F6`
SSDEEP | `768:el/wBBBMcf1XIOOBTn9DAvt8DQgfMycTEYL67rNFPWk+iVgkV:el/wzfhFOBThDUygL67xpr+iVgu`

## Runtime Data

### Child Processes:
MicrosoftEdgeSH.exe WerFault.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{F79646A6-8BE5-443B-A98F-AD03D667F646}.2.ver0x0000000000000001.db | Section
\Sessions\1\BaseNamedObjects\SessionImmersiveColorPreference | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\edgeIso.dll |
C:\Windows\system32\iertutil.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MicrosoftEdgeSH.exe |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\USERENV.dll |
C:\Windows\System32\WINTRUST.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MicrosoftEdgeSH.exe
* Product Name: Microsoft Edge Web Platform
* Company Name: Microsoft Corporation
* File Version: 11.00.19041.1 (WinBuild.160101.0800)
* Product Version: 11.00.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `MicrosoftEdgeSH.exe` being misused. While `MicrosoftEdgeSH.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `            - "MicrosoftEdgeSH.exe"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


