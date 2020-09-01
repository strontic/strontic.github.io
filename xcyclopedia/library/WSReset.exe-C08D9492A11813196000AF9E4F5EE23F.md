---
title: WSReset.exe | This tool resets the Windows Store without changing account settings or deleting installed apps
---

# WSReset.exe 

* File Path: `C:\Windows\system32\WSReset.exe`
* Description: This tool resets the Windows Store without changing account settings or deleting installed apps

## Hashes

Type | Hash
-- | --
MD5 | `C08D9492A11813196000AF9E4F5EE23F`
SHA1 | `2404225C00764ADB780FF21C06890CFB3FA327F0`
SHA256 | `E1E8F9FB5503A7EC9731BC81CDD3F428001C2AFB0528CF99DA451C5220A1580F`
SHA384 | `39474778BF617D16343F3FCADF197C268EA1B9409B5C6C3DD16061188A75F9AA4E638A9F82182301FD81B9989A7352C6`
SHA512 | `6F3539EC0F15184F887D2CC8417D5133FBED65666A8FA4459351422F408401B13CCBA3162B9BF8693E5F24858DD72155FF1EB7409ECF6692FDFFD4CA1C53BEBF`
SSDEEP | `768:lJKVfVIDwlvjEFLSj1cKSSSzSSoMo9b1Nsn4FOBkStBW/:mbiMjEFLi1tFGg0Y/`

## Runtime Data

### Child Processes:
conhost.exe

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
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\WSReset.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WSReset.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\WSCollect.exe](WSCollect.exe-1C4F7AB2AD0B867487E42F77A637A3F2.md) | 43
[C:\Windows\system32\WSCollect.exe](WSCollect.exe-4F67D9A480038D06463A43AE66880245.md) | 44
[C:\Windows\system32\WSCollect.exe](WSCollect.exe-6212500CE0BBE755AFCC8DDF64698A87.md) | 43
[C:\WINDOWS\system32\WSCollect.exe](WSCollect.exe-C471046B92D04242ED85AB1522E90012.md) | 40
[C:\Windows\system32\WSReset.exe](WSReset.exe-0D2BE4AE7AE5B93B47E12F4EFF38A0D7.md) | 46
[C:\Windows\system32\WSReset.exe](WSReset.exe-374AB8022CA5EE56684BC28626F36F73.md) | 38
[C:\WINDOWS\system32\WSReset.exe](WSReset.exe-FB3CE16149961934341850A6F1ED869E.md) | 46

## Possible Misuse

*The following table contains possible examples of `WSReset.exe` being misused. While `WSReset.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_wsreset.yml) | `title: Bypass UAC via WSReset.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_wsreset.yml) | `description: Identifies use of WSReset.exe to bypass User Account Control. Adversaries use this technique to execute privileged processes.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_wsreset.yml) | `        ParentImage\|endswith: '\wsreset.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wsreset_uac_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wsreset_uac_bypass.yml) | `title: Wsreset UAC Bypass` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wsreset_uac_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wsreset_uac_bypass.yml) | `description: Detects a method that uses Wsreset.exe tool that can be used to reset the Windows Store to bypass UAC` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wsreset_uac_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wsreset_uac_bypass.yml) | `    - https://lolbas-project.github.io/lolbas/Binaries/Wsreset/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wsreset_uac_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wsreset_uac_bypass.yml) | `            - '\WSreset.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wsreset_uac_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wsreset_uac_bypass.yml) | `    - Unknown sub processes of Wsreset.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsreset.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wsreset.yml) | `Name: Wsreset.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsreset.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wsreset.yml) | `  - Command: wsreset.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsreset.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wsreset.yml) | `    Description: During startup, wsreset.exe checks the registry value HKCU\Software\Classes\AppX82a6gwre4fdg3bt635tn5ctqjf8msdd2\Shell\open\command for the command to run. Binary will be executed as a high-integrity process without a UAC prompt being displayed to the user. ` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsreset.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wsreset.yml) | `  - Path: C:\Windows\System32\wsreset.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsreset.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wsreset.yml) | ` - IOC: wsreset.exe launching child process other than mmc.exe` | 



MIT License. Copyright (c) 2020 Strontic.


