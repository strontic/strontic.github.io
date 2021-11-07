---
title: WinSCP.exe | WinSCP- SFTP, FTP, WebDAV, S3 and SCP client
excerpt: What is WinSCP.exe?
---

# WinSCP.exe 

* File Path: `C:\Program Files (x86)\WinSCP\WinSCP.exe`
* Description: WinSCP: SFTP, FTP, WebDAV, S3 and SCP client

## Screenshot

![WinSCP.exe](screenshots/WinSCP.exe-B4C10246F5915CA18F7CF78A38A43EBD-1.png)
![WinSCP.exe](screenshots/WinSCP.exe-B4C10246F5915CA18F7CF78A38A43EBD-5.png)

## Hashes

Type | Hash
-- | --
MD5 | `C93E3AE1052DA30CEDFAE7F15BE04FF1`
SHA1 | `1E2736FF9FDB9AFF7F825C7F101DBA35B6C4158C`
SHA256 | `D3683BECA3A40574E5FD68D30451137E4A8BBACA8C428EBB781D565D6A70385E`
SHA384 | `063EF7DC802D08331F31EAAA57F2DB652A7C693894B9A5503D4CA2B0ECC1A99170308D7360C55B475A04A4FF97F2CCE3`
SHA512 | `D67A9635869ACBA8819D54DC1767BD82D0A631D35B8ACD4A9008CDA1B16A40006E16D08A00296EB4298B842179421B4A8543369F3C450A3C02E83848905C118A`
SSDEEP | `393216:GOrtuJ5qOB/2t8iaWY/6fucR/nWIG0i8:RtVLP/n`
IMP | `81E86A7EBE42C0696D4D694CE05E4FF1`
PESHA1 | `4B816368FDBB776FB94E474609213686E4355B20`
PE256 | `5F0B064F364A8016C3CF708E0A03DFF4937279B4F9EADB109F53EA765B4E5ECE`

## Runtime Data

### Child Processes:
conhost.exe

### Window Title:
--help - WinSCP

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\propsys.dll.mui | File
(R-D)   C:\Windows\SysWOW64\en-US\user32.dll.mui | File
(R-D)   C:\Windows\WinSxS\x86_microsoft.windows.c..-controls.resources_6595b64144ccf1df_6.0.19041.1_en-us_130e63d987a738df\comctl32.dll.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.c..-controls.resources_6595b64144ccf1df_6.0.19041.1_en-us_130e63d987a738df | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1110_none_a8625c1886757984 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\BaseNamedObjects\HOOK_SHMEM_00000000_00000ebc_00000040_00007224 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme449731986 | Section
\Windows\Theme1396518710 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\WinSCP\WinSCP.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `0232466DC95B40EC9D21D9329ABFCD5D`
* Thumbprint: `FB845245CFBB0EE97E76C775348CAA31D74BEC4C`
* Issuer: CN=DigiCert EV Code Signing CA (SHA2), OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=Martin Prikryl, O=Martin Prikryl, L=Prague, C=CZ, SERIALNUMBER=87331519, OID.2.5.4.15=Private Organization, OID.1.3.6.1.4.1.311.60.2.1.3=CZ

## File Metadata

* Original Filename: winscp.exe
* Product Name: WinSCP
* Company Name: Martin Prikryl
* File Version: 5.19.4.11829
* Product Version: 5.19.4.0
* Language: English (United States)
* Legal Copyright: (c) 2000-2021 Martin Prikryl
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/d3683beca3a40574e5fd68d30451137e4a8bbaca8c428ebb781d565d6a70385e/detection


## Possible Misuse

*The following table contains possible examples of `WinSCP.exe` being misused. While `WinSCP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\winscp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


