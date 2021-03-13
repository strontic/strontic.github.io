---
title: rasautou.exe | Remote Access Dialer
excerpt: What is rasautou.exe?
---

# rasautou.exe 

* File Path: `C:\Windows\system32\rasautou.exe`
* Description: Remote Access Dialer

## Hashes

Type | Hash
-- | --
MD5 | `33AA72B1C83985F0FE3F51E1E0C8C5DF`
SHA1 | `BC228FD0EDF7E3E2E07DE9325FD4BB6E76EC2AE7`
SHA256 | `F9A9DB182517C828FC9E23EA1FDC9902C07BAD260DD4FD34086446BD9C109B70`
SHA384 | `3E851178181C9BA16B0F60B9B8196DBC05725A4CD83EE1EB259911F7C6814658F691A72A5A774EFA656445F2A0745379`
SHA512 | `EF5855018AA76FD6D36D78B53AEC28337D2D708E7EF85C83D92E07E3D29390C3B5B318B149EFFE25C1205FBFEEEE0D2CD9C529866C1111A49CEAE3621EE971C4`
SSDEEP | `384:/v5URAsJftvOTs27O++QETwRLRxkWMBW:XFSt4Y+bfx6`
IMP | `5EFE6408CA2D8147E0964600DE72232E`
PESHA1 | `6C76BE40ED117095B7A1FA7DFA7217A9AFA893E7`
PE256 | `FCE02A7A9FDC57912213D451CB7C2617D3A65C0294BB2FD43178A07416998F68`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: rasautou [-f phonebook] [-a address] [-e entry] [-s]

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\rasautou.exe.mui | File
(R-D)   C:\Windows\System32\en-US\rasdlg.dll.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.17763.1518_none_de6e2bd0534e2567 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\2\Windows\Theme2131664586 | Section
\Windows\Theme966197582 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\CRYPTSP.dll |
C:\Windows\system32\DPAPI.dll |
C:\Windows\system32\dwmapi.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MPRAPI.dll |
C:\Windows\System32\MSASN1.dll |
C:\Windows\System32\MSCTF.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\RASAPI32.dll |
C:\Windows\system32\rasautou.exe |
C:\Windows\system32\RASDLG.dll |
C:\Windows\system32\rasman.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\rtutils.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\system32\TAPI32.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\uxtheme.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\WS2_32.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.17763.1518_none_de6e2bd0534e2567\comctl32.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rasdlui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/f9a9db182517c828fc9e23ea1fdc9902c07bad260dd4fd34086446bd9c109b70/detection/


## Possible Misuse

*The following table contains possible examples of `rasautou.exe` being misused. While `rasautou.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `Name: Rasautou.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Command: rasautou -d powershell.dll -p powershell -a a -e e `{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Path: C:\Windows\System32\rasautou.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- IOC: rasautou.exe command line containing -d and -p`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


