---
title: TeamViewer.exe | TeamViewer
excerpt: What is TeamViewer.exe?
---

# TeamViewer.exe 

* File Path: `C:\Program Files (x86)\TeamViewer\TeamViewer.exe`
* Description: TeamViewer

## Screenshot

![TeamViewer.exe](screenshots/TeamViewer.exe-DC7A10E3A6F2448FBCBB2E444FA67F70-4.png)
![TeamViewer.exe](screenshots/TeamViewer.exe-DC7A10E3A6F2448FBCBB2E444FA67F70-5.png)

## Hashes

Type | Hash
-- | --
MD5 | `E45DA09AB65F6E5E87CFD3E0C9E3ABD8`
SHA1 | `6A0C33B2C9D1CCEEDA578CFDBE496F0CA827C9AE`
SHA256 | `57F4BFDF47BA8B80E2641E19E28EACE5BFA6A65158D3B79EDE80BE6DCF82EA3E`
SHA384 | `784DA534E600D24E8EFF4E9FE00DA787422A1DDCD2E0C0AFF08F956870C626913BEDCCA734DA309CDACFB272C81F59CA`
SHA512 | `0EB24E58F140C80AF714F7BD65B1DE9316140859105C4DAE15E9007637A39F3072326D2A973FBEDFCEE96EC5627D6FD2C6DC81D319BCE4A0389F0E2CD7CC1FBB`
SSDEEP | `1572864:pt3zCt7nYIwqAzWfS2IVXydQs4chboH6wlJUWGeHj:pt3zCtkoJHeHj`
IMP | `E0480C10B631040A64D6F89F7D5B827B`
PESHA1 | `BF4C81E8C0B747AEE18A1934DF8A388F13569DF7`
PE256 | `9EF72FD2A6FA05554C4540DDE06C17482C01A35323349E18804CE39ECE5A4397`

## Runtime Data

### Window Title:
TeamViewer

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\crypt32.dll.mui | File
(R-D)   C:\Windows\System32\en-US\winnlsres.dll.mui | File
(R-D)   C:\Windows\SysWOW64\en-US\avicap32.dll.mui | File
(R-D)   C:\Windows\SysWOW64\en-US\msvfw32.dll.mui | File
(R-D)   C:\Windows\SysWOW64\en-US\user32.dll.mui | File
(RW-)   C:\Program Files (x86)\TeamViewer\TeamViewer15_Logfile.log | File
(RW-)   C:\Users\user\AppData\Local\TeamViewer\Database\tvchatfilecache.db | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_11b1e5df2ffd8627 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.508_none_429cdbca8a8ffa94 | File
(RW-)   C:\xCyclopedia | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\BaseNamedObjects\1b7cHWNDInterface:4a022e | Section
\Sessions\1\BaseNamedObjects\TeamViewerHooks7_SharedMemory | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme2547664911 | Section
\Windows\Theme3854699184 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\TeamViewer\TeamViewer.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `0B446546C36525BF5F084F6BBBBA7097`
* Thumbprint: `05CDF79B0EFFFF361DAC0363ADAA75B066C49DE0`
* Issuer: CN=DigiCert Assured ID Code Signing CA-1, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=TeamViewer Germany GmbH, O=TeamViewer Germany GmbH, L=Gppingen, S=Baden-Wrttemberg, C=DE

## File Metadata

* Original Filename: TeamViewer.exe
* Product Name: TeamViewer
* Company Name: TeamViewer Germany GmbH
* File Version: 15.10.5.0
* Product Version: 15.10.5.0
* Language: English (United Kingdom)
* Legal Copyright: TeamViewer Germany GmbH
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/57f4bfdf47ba8b80e2641e19e28eace5bfa6a65158d3b79ede80be6dcf82ea3e/detection/


## Possible Misuse

*The following table contains possible examples of `TeamViewer.exe` being misused. While `TeamViewer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/4.0 (compatible; RMS)'  # Attacks on industrial enterprises using RMS and TeamViewer https://goo.gl/GthvTw`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/4.0 (compatible; MSIE 6.0; DynGate)'  # Attacks on industrial enterprises using RMS and TeamViewer https://goo.gl/GthvTw`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #10: Delete TeamViewer Log Files [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: TeamViewer Files Detected Test on Windows [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #10: Delete TeamViewer Log Files [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: TeamViewer Files Detected Test on Windows [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.004/T1070.004.md) | - [Atomic Test #10 - Delete TeamViewer Log Files](#atomic-test-10---delete-teamviewer-log-files) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.004/T1070.004.md) | ## Atomic Test #10 - Delete TeamViewer Log Files | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.004/T1070.004.md) | Adversaries may delete TeamViewer log files to hide activity. This should provide a high true-positive alert ration. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.004/T1070.004.md) | This test just places the files in a non-TeamViewer folder, a detection would just check for a deletion event matching the TeamViewer | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.004/T1070.004.md) | \| teamviewer_log_file \| Teamviewer log file to delete. Run the prereq command to create it if it does not exist. \| String \| $env:TEMP&#92;TeamViewer_54.log\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1219.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1219/T1219.md) | <blockquote>An adversary may use legitimate desktop support and remote access software, such as Team Viewer, Go2Assist, LogMein, AmmyyAdmin, etc, to establish an interactive command and control channel to target systems within networks. These services are commonly used as legitimate technical support software, and may be allowed by application control within a target environment. Remote access tools like VNC, Ammyy, and Teamviewer are used frequently when compared with other legitimate software commonly used by adversaries. (Citation: Symantec Living off the Land) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1219.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1219/T1219.md) | Admin tools such as TeamViewer have been used by several groups targeting institutions in countries of interest to the Russian state and criminal campaigns. (Citation: CrowdStrike 2015 Global Threat Report) (Citation: CrySyS Blog TeamSpy)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1219.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1219/T1219.md) | - [Atomic Test #1 - TeamViewer Files Detected Test on Windows](#atomic-test-1---teamviewer-files-detected-test-on-windows) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1219.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1219/T1219.md) | ## Atomic Test #1 - TeamViewer Files Detected Test on Windows | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1219.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1219/T1219.md) | An adversary may attempt to trick the user into downloading teamviewer and using this to maintain access to the machine. Download of TeamViewer installer will be at the destination location when sucessfully executed. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1219.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1219/T1219.md) | Invoke-WebRequest -OutFile C:\Users\$env:username\Desktop\TeamViewer_Setup.exe https://download.teamviewer.com/download/TeamViewer_Setup.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1219.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1219/T1219.md) | Start-Process 'C:\Program Files (x86)\TeamViewer\TeamViewer.exe' | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1219.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1219/T1219.md) | $file = 'C:\Program Files (x86)\TeamViewer\uninstall.exe' | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | type C:\temp\evil.exe > "C:\Program Files (x86)\TeamViewer\TeamViewer12_Logfile.log:evil.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | and not filepath contains "teamviewer" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | and not filepath contains "teamviewer" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


