---
title: windbg.exe | Windows GUI symbolic debugger
excerpt: What is windbg.exe?
---

# windbg.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\windbg.exe`
* Description: Windows GUI symbolic debugger

## Screenshot

![windbg.exe](screenshots/windbg.exe-8CC7AB7DC9C670809113929568FB3F31-5.png)

## Hashes

Type | Hash
-- | --
MD5 | `703B2F8C342FEB9FC8782F48B47BA698`
SHA1 | `2CFAE4B5F01E36B937E7AB2BAB4DEF4563330062`
SHA256 | `B1CE9D33E94CFB98989147AD1A9CC190FF2EDB97BA24F47A80C5ADAAB01EE80C`
SHA384 | `FCB1F8A7686EF7681FA0B75988B41E38A77222F98EBC5CBCCAD111F262FE6A3E1B59E6F057E5CFAF1164BF96D2A92A2B`
SHA512 | `81CBC23BA64CFF21B89D5773A269516C44F91F4BAFD60E9E58EF8ABA654070A5573E8035F10A498EE5719C54C91E027E1D3E7D78285FC72C0E95D864A6BA0C2C`
SSDEEP | `12288:ziaAINi0BQjAHXrzYWZci2+Tousrte4XL:D9/L7zYWZT2+Touge`
IMP | `CE2DF536539DE0880E2AEF4A9EE567FE`
PESHA1 | `FF6C1246D69A9A92F08DD9C9F74CDD38752478A9`
PE256 | `5B2D3184EF2BEB5F69E50B95D0671B338F5ED4E4A263DA11C2DA66510F78A91B`

## Runtime Data

### Child Processes:
help.exe

### Window Title:
help - WinDbg:10.0.19041.1 X86 

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\sym\wntdll.pdb\3CCC2398F623C3D0915D0E0ADC5714A71\wntdll.pdb | File
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_11b1e5df2ffd8627 | File
(RWD)   C:\Windows\SysWOW64\ntdll.dll | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\1f50HWNDInterface:40030c | Section
\Sessions\1\Windows\Theme1383959086 | Section
\Windows\Theme2042523233 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\windbg.exe |
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

* Original Filename: windbg.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/b1ce9d33e94cfb98989147ad1a9cc190ff2edb97ba24f47a80c5adaab01ee80c/detection


## Possible Misuse

*The following table contains possible examples of `windbg.exe` being misused. While `windbg.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_cdb.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_cdb.yml) | `title: Possible App Whitelisting Bypass via WinDbg/CDB as a Shellcode Runner`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_cdb.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_cdb.yml) | `- http://www.exploit-monday.com/2016/08/windbg-cdb-shellcode-runner.html`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `- Link: http://www.exploit-monday.com/2016/08/windbg-cdb-shellcode-runner.html`{:.highlight .language-yaml} | 
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_deviceguard_evasion.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_deviceguard_evasion.yar) | reference = "http://www.exploit-monday.com/2016/08/windbg-cdb-shellcode-runner.html" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [7a6ba833-de40-466a-8969-5c37b13603e0.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/7a6ba833-de40-466a-8969-5c37b13603e0.yml) | `"windbg",`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


