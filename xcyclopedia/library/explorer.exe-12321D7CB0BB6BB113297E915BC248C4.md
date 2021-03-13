---
title: explorer.exe | Windows Explorer
excerpt: What is explorer.exe?
---

# explorer.exe 

* File Path: `C:\Windows\explorer.exe`
* Description: Windows Explorer

## Hashes

Type | Hash
-- | --
MD5 | `12321D7CB0BB6BB113297E915BC248C4`
SHA1 | `3F9D089A8A4E2BEF13CB28CDD3A016FA155DD04D`
SHA256 | `04441A2E82A4BD350B448B135D52F0A981CF8D011279BED98AFE48F500767B66`
SHA384 | `28791828D2B62FD36BA594C474A42614BC1EAD454864C40F5AFE316B10B4F74D5A91F991F08FCCC0BF792306FBF7F772`
SHA512 | `090E68E84706EAA454A2B798955032CBE38B11EBF4D4781EA92E5497E127E0436A2E5B21C5E60F2C7E00F8BAB6932BF470CC470D304B2C0698092F2BCF498510`
SSDEEP | `49152:6m6dAhcYFbgFmDhR5IbW+gvy6TxnHHJGLPE+6DY8aHHiacY+vK659zDw+w8A7/eH:dgOMky6FcjE+dW9w8a0cDW`
IMP | `F878258E75C60DB12F65170C43A01F2F`
PESHA1 | `9BB91AF54A76D732D3DC1C13F58445D5279FB260`
PE256 | `48058AE48EC7A373BE4BB8120949ABA0FDFC3B84B8704CA295E6CE332128BC6B`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\explorer.exe |
C:\Windows\System32\advapi32.dll |
C:\Windows\SYSTEM32\AEPIC.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\combase.dll |
C:\Windows\SYSTEM32\cryptsp.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SYSTEM32\ntmarta.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\SYSTEM32\powrprof.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\SYSTEM32\TWINAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\user32.dll |
C:\Windows\SYSTEM32\USERENV.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: EXPLORER.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.610 (WinBuild.160101.0800)
* Product Version: 10.0.19041.610
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/04441a2e82a4bd350b448b135d52f0a981cf8d011279bed98afe48f500767b66/detection


## Possible Misuse

*The following table contains possible examples of `explorer.exe` being misused. While `explorer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\explorer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_desktop_ini.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_susp_desktop_ini.yml) | `- 'C:\Windows\explorer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_logon_scripts_userinitmprlogonscript_proc.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_logon_scripts_userinitmprlogonscript_proc.yml) | `Image: '*\explorer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `#  runs %SystemRoot%\System32\rundll32.exe shell32.dll,SHCreateLocalServerRunDll {c08afd90-f2a1-11d1-8455-00a0c91f3880} but parent command is explorer.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `- '*\explorer.exe'  # dcomexec ShellBrowserWindow`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_non_interactive_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_non_interactive_powershell.yml) | `description: Detects non-interactive PowerShell activity by looking at powershell.exe with not explorer.exe as a parent.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_non_interactive_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_non_interactive_powershell.yml) | `ParentImage\|endswith: '\explorer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_explorer_break_proctree.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_explorer_break_proctree.yml) | `description: Detects a command line process that uses explorer.exe /root, which is similar to cmd.exe /c, only it breaks the process tree and makes its parent a new instance of explorer`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_explorer_break_proctree.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_explorer_break_proctree.yml) | `- 'explorer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_userinit_child.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_userinit_child.yml) | `Image: '*\explorer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\explorer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- 'C:\Windows\explorer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\explorer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Explorer.yml) | `Name: Explorer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Explorer.yml) | `- Command: explorer.exe calc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Explorer.yml) | `Description: 'Executes calc.exe as a subprocess of explorer.exe.'`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Explorer.yml) | `- c:\windows\explorer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Explorer.yml) | `- c:\windows\sysWOW64\explorer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Explorer.yml) | `Name: Explorer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Explorer.yml) | `- Command: explorer.exe /root,"C:\Windows\System32\calc.exe"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Explorer.yml) | `Description: Execute calc.exe with the parent process spawning from a new instance of explorer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Explorer.yml) | `- Command: explorer.exe C:\Windows\System32\notepad.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Explorer.yml) | `- Path: C:\Windows\explorer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Explorer.yml) | `- Path: C:\Windows\SysWOW64\explorer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Explorer.yml) | `- IOC: Multiple instances of explorer.exe or explorer.exe using the /root command line can help to detect this.`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Masquerading occurs when the name or location of an executable, legitimate or malicious, is manipulated or abused for the sake of evading defenses and observation. Several different variations of this technique have been observed.\n\nOne variant is for an executable to be placed in a commonly trusted directory or given the name of a legitimate, trusted program. Alternatively, the filename given may be a close approximation of legitimate programs or something innocuous. An example of this is when a common system utility or program is moved and renamed to avoid detection based on its usage.(Citation: FireEye APT10 Sept 2018) This is done to bypass tools that trust executables by relying on file name or path, as well as to deceive defenders and system administrators into thinking a file is benign by associating the name with something that is thought to be legitimate.\n\nA third variant uses the right-to-left override (RTLO or RLO) character (U+202E) as a means of tricking a user into executing what they think is a benign file type but is actually executable code. RTLO is a non-printing character that causes the text that follows it to be displayed in reverse.(Citation: Infosecinstitute RTLO Technique) For example, a Windows screensaver file named <code>March 25 \\u202Excod.scr</code> will display as <code>March 25 rcs.docx</code>. A JavaScript file named <code>photo_high_re\\u202Egnp.js</code> will be displayed as <code>photo_high_resj.png</code>. A common use of this technique is with spearphishing attachments since it can trick both end users and defenders if they are not aware of how their tools display and render the RTLO character. Use of the RTLO character has been seen in many targeted intrusion attempts and criminal activity.(Citation: Trend Micro PLEAD RTLO)(Citation: Kaspersky RTLO Cyber Crime) RTLO can be used in the Windows Registry as well, where regedit.exe displays the reversed characters but the command line tool reg.exe does not by default. \n\nAdversaries may modify a binary's metadata, including such fields as icons, version, name of the product, description, and copyright, to better blend in with the environment and increase chances of deceiving a security analyst or product.(Citation: Threatexpress MetaTwin 2017)\n\n### Windows\nIn another variation of this technique, an adversary may use a renamed copy of a legitimate utility, such as rundll32.exe. (Citation: Endgame Masquerade Ball) An alternative case occurs when a legitimate utility is moved to a different directory and also renamed to avoid detections based on system utilities executing from non-standard paths. (Citation: F-Secure CozyDuke)\n\nAn example of abuse of trusted locations in Windows would be the <code>C:\\Windows\\System32</code> directory. Examples of trusted binary names that can be given to malicious binares include \"explorer.exe\" and \"svchost.exe\".\n\n### Linux\nAnother variation of this technique includes malicious binaries changing the name of their running process to that of a trusted or benign process, after they have been launched as opposed to before. (Citation: Remaiten)\n\nAn example of abuse of trusted locations in Linux  would be the <code>/bin</code> directory. Examples of trusted binary names that can be given to malicious binaries include \"rsyncd\" and \"dbus-inotifier\". (Citation: Fysbis Palo Alto Analysis)  (Citation: Fysbis Dr Web Analysis)",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [hta.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Initial_Access/hta.md) | Using COM objects, mshta runs with no child processes. Explorer.exe spawns and executes cmd -> calc. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.004/T1134.004.md) | Adversaries may abuse these mechanisms to evade defenses, such as those blocking processes spawning directly from Office documents, and analysis targeting unusual/potentially malicious parent-child process relationships, such as spoofing the PPID of [PowerShell](https://attack.mitre.org/techniques/T1086)/[Rundll32](https://attack.mitre.org/techniques/T1085) to be <code>explorer.exe</code> rather than an Office document delivered as part of [Spearphishing Attachment](https://attack.mitre.org/techniques/T1566/001).(Citation: CounterCept PPID Spoofing Dec 2018) This spoofing could be executed via [Visual Basic](https://attack.mitre.org/techniques/T1059/005) within a malicious Office document or any code that can perform [Native API](https://attack.mitre.org/techniques/T1106).(Citation: CTD PPID Spoofing Macro Mar 2019)(Citation: CounterCept PPID Spoofing Dec 2018) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | $sheet.Cells.Item(20,1) = "=EXEC(`"explorer.exe C:\Users\`"&A1&`"\AppData\Local\Temp\`"&A3&`"`")" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | $sheet.Cells.Item(22,1) = "=EXEC(`"explorer.exe C:\Users\`"&A1&`"\AppData\Local\Temp\`"&A2&`"`")" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.004/T1547.004.md) | * Winlogon\Shell - points to explorer.exe, the system shell executed when a user logs on | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.004/T1547.004.md) | PowerShell code to set Winlogon shell key to execute a binary at logon along with explorer.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.004/T1547.004.md) | Set-ItemProperty "HKCU:\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\" "Shell" "explorer.exe, #{binary_to_execute}" -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy_gen3.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy_gen3.yar) | $s5 = "Explorer.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_putterpanda.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_putterpanda.yar) | $s1 = "Explorer.exe \"" fullword ascii /* PEStudio Blacklist: strings */ /* score: '16.05' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_putterpanda.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_putterpanda.yar) | $s1 = "EXPLORER.EXE" fullword ascii /* PEStudio Blacklist: strings */ /* score: '4.98' */ /* Goodware String - occured 22 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_putterpanda.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_putterpanda.yar) | $s3 = "explorer.exe" fullword ascii /* PEStudio Blacklist: strings */ /* score: '4.97' */ /* Goodware String - occured 31 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_rancor.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_rancor.yar) | $x2 = "CreateObject(\"Wscript.Shell\").Run \"explorer.exe \"\"http" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_stuxnet.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_stuxnet.yar) | $s1 = "SUCKM3 FROM EXPLORER.EXE MOTH4FUCKA #@!" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s0 = "explorer.exe http://bbs.yesmybi.net" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s0 = "explorer.exe http://user.qzone.qq.com/568148075" fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | description = "Sample from CN Honker Pentest Toolset - file Codeeer Explorer.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s2 = "Codeeer Explorer.exe" fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s3 = "explorer.exe" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | description = "Detects uncommon file size of explorer.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | and filename == "explorer.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s3 = "explorer.exe http://www.hackdos.com" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s1 = "Explorer.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s4 = "ERROR: FindProcessByName('explorer.exe')" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Abnormal explorer.exe - typical strings not found in file" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | $s1 = "EXPLORER.EXE" wide fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | filename == "explorer.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


