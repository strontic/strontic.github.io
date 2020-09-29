---
title: Display.dll | Display Control Panel
excerpt: What is Display.dll?
---

# Display.dll 

* File Path: `C:\Windows\system32\Display.dll`
* Description: Display Control Panel

## Hashes

Type | Hash
-- | --
MD5 | `6E3F5E9355B091FA5B40358F38151A96`
SHA1 | `88C4F0A43F885BB95ABA261B1E74622952D104EA`
SHA256 | `5D696F209AF867613CAB06B31B447C5E128C9E63B475D1B0780C00BFCC55018F`
SHA384 | `31C7656AB12E894B69F9B14D2F51E2B963543E4B63564731886F4CCA7065DD6DE0E544B02B33F54B79FA438AABA58663`
SHA512 | `BAA42D10D5D58394A974083B078566586B1E569F66B682911A96DF86F3F82E16A74B626FEEF344AF1B64671EE095E084845C8406CC3C851A87FC1FCC10FAA99D`
SSDEEP | `1536:Pehv7lv8v1me7C65L5bu+G14KGdxxD5uBi25PeU+yiosyA8lqKyvPc/nJ8agSYG5:4+8e75Dmf8xtY55Llqvv4nquYG`
IMP | `C864BD970B52B07CA184B7253E4FD3E9`
PESHA1 | `112E52BDD81E9A5FA7CE2EF8050D63EAF4AF3A38`
PE256 | `D84B23A1C0691F72C180AD4B31CC9849F7B7D4747A8707489727E349B26E4BEF`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DisplaySaveSettingsEx` | 1 (0x1) | Exported Function | 0x0000000180010b20 | 0x00010b20
`DllCanUnloadNow` | 3 (0x3) | Exported Function | 0x000000018000fc40 | 0x0000fc40
`DllGetClassObject` | 4 (0x4) | Exported Function | 0x000000018000fc60 | 0x0000fc60
`ShowAdapterSettings` | 2 (0x2) | Exported Function | 0x0000000180010b70 | 0x00010b70


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DISPLAY.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/5d696f209af867613cab06b31b447c5e128c9e63b475d1b0780c00bfcc55018f/detection/


## Possible Misuse

*The following table contains possible examples of `Display.dll` being misused. While `Display.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- 'xspy -display '` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_shell_susp_rev_shells.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_shell_susp_rev_shells.yml) | `- 'xterm -display 1'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_assembly_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_in_memory_assembly_execution.yml) | `C2 behaviour. Generally speaking, when Sysmon EventID 10 cannot reference a stack call to a dll loaded from disk (the standard way), it will display "UNKNOWN"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [attor](https://github.com/eset/malware-ioc/blob/master/attor/README.adoc) | `=== Service display names` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Masquerading occurs when the name or location of an executable, legitimate or malicious, is manipulated or abused for the sake of evading defenses and observation. Several different variations of this technique have been observed.\n\nOne variant is for an executable to be placed in a commonly trusted directory or given the name of a legitimate, trusted program. Alternatively, the filename given may be a close approximation of legitimate programs or something innocuous. An example of this is when a common system utility or program is moved and renamed to avoid detection based on its usage.(Citation: FireEye APT10 Sept 2018) This is done to bypass tools that trust executables by relying on file name or path, as well as to deceive defenders and system administrators into thinking a file is benign by associating the name with something that is thought to be legitimate.\n\nA third variant uses the right-to-left override (RTLO or RLO) character (U+202E) as a means of tricking a user into executing what they think is a benign file type but is actually executable code. RTLO is a non-printing character that causes the text that follows it to be displayed in reverse.(Citation: Infosecinstitute RTLO Technique) For example, a Windows screensaver file named <code>March 25 \\u202Excod.scr</code> will display as <code>March 25 rcs.docx</code>. A JavaScript file named <code>photo_high_re\\u202Egnp.js</code> will be displayed as <code>photo_high_resj.png</code>. A common use of this technique is with spearphishing attachments since it can trick both end users and defenders if they are not aware of how their tools display and render the RTLO character. Use of the RTLO character has been seen in many targeted intrusion attempts and criminal activity.(Citation: Trend Micro PLEAD RTLO)(Citation: Kaspersky RTLO Cyber Crime) RTLO can be used in the Windows Registry as well, where regedit.exe displays the reversed characters but the command line tool reg.exe does not by default. \n\nAdversaries may modify a binary's metadata, including such fields as icons, version, name of the product, description, and copyright, to better blend in with the environment and increase chances of deceiving a security analyst or product.(Citation: Threatexpress MetaTwin 2017)\n\n### Windows\nIn another variation of this technique, an adversary may use a renamed copy of a legitimate utility, such as rundll32.exe. (Citation: Endgame Masquerade Ball) An alternative case occurs when a legitimate utility is moved to a different directory and also renamed to avoid detections based on system utilities executing from non-standard paths. (Citation: F-Secure CozyDuke)\n\nAn example of abuse of trusted locations in Windows would be the <code>C:\\Windows\\System32</code> directory. Examples of trusted binary names that can be given to malicious binares include \"explorer.exe\" and \"svchost.exe\".\n\n### Linux\nAnother variation of this technique includes malicious binaries changing the name of their running process to that of a trusted or benign process, after they have been launched as opposed to before. (Citation: Remaiten)\n\nAn example of abuse of trusted locations in Linux  would be the <code>/bin</code> directory. Examples of trusted binary names that can be given to malicious binaries include \"rsyncd\" and \"dbus-inotifier\". (Citation: Fysbis Palo Alto Analysis)  (Citation: Fysbis Dr Web Analysis)",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus](https://github.com/eset/malware-ioc/blob/master/oceanlotus/README.adoc) | `* `HKCU\SOFTWARE\Intel\Display\igfxcui\igfxtray\;[NUMBER];[DWORD]`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `DISPLAY` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [stantinko](https://github.com/eset/malware-ioc/blob/master/stantinko/README.adoc) | `b.style.display = "none";` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [winnti_group](https://github.com/eset/malware-ioc/blob/master/winnti_group/README.adoc) | `=== Service display name` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Getting_Lateral.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-05-01/Getting_Lateral.md) | [T1117 Splunk](https://192.168.38.105:8000/en-US/app/search/search?q=search%20host%3Dwef*%20regsvr32.exe%20earliest%3D-30m%20latest%3Dnow&display.page.search.mode=smart&dispatch.sample_ratio=1&workload_pool=&earliest=-24h%40h&latest=now&sid=1588276958.707) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Getting_Lateral.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-05-01/Getting_Lateral.md) | [T1003 Splunk](https://192.168.38.105:8000/en-US/app/search/search?q=search%20host%3Dwef*%20reg.exe%20earliest%3D-30m%20latest%3Dnow%20%7C%20stats%20values(Process_Command_Line)&display.page.search.mode=smart&dispatch.sample_ratio=1&workload_pool=&earliest=-24h%40h&latest=now&sid=1588277661.75&display.page.search.tab=statistics&display.general.type=statistics) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Find and Display Internet Explorer Browser Version [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Find and Display Safari Browser Version [macos] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) | - Atomic Test #3: Find and Display Safari Browser Version [macos] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Find and Display Internet Explorer Browser Version [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | Successful execution of this test will display multiple useranames and passwords/hashes to the screen. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | Upon successful execution, cmd.exe will execute `net.exe view` and display results of local systems on the network that have file and print sharing enabled. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1037.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1037.004/T1037.004.md) | sudo echo osascript -e 'tell app "Finder" to display dialog "Hello World"' >> /etc/rc.common | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1056.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1056.002/T1056.002.md) | osascript -e 'tell app "System Preferences" to activate' -e 'tell app "System Preferences" to activate' -e 'tell app "System Preferences" to display dialog "Software Update requires that you type your password to apply changes." & return & return  default answer "" with icon 1 with hidden answer with title "Software Update"' | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | Powershell invoke mshta to download payload. Upon execution, a new PowerShell window will be opened which will display "Download Cradle test success!". | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1069.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1069.001/T1069.001.md) | Basic Permission Groups Discovery for Windows. This test will display some errors if run on a computer not connected to a domain. Upon execution, domain | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1069.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1069.001/T1069.001.md) | Permission Groups Discovery utilizing PowerShell. This test will display some errors if run on a computer not connected to a domain. Upon execution, domain | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1069.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1069.002/T1069.002.md) | Basic Permission Groups Discovery for Windows. This test will display some errors if run on a computer not connected to a domain. Upon execution, domain | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1069.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1069.002/T1069.002.md) | Permission Groups Discovery utilizing PowerShell. This test will display some errors if run on a computer not connected to a domain. Upon execution, domain | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1069.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1069.002/T1069.002.md) | test will display some errors if run on a computer not connected to a domain. Upon execution, domain information will be displayed. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518/T1518.md) | - [Atomic Test #1 - Find and Display Internet Explorer Browser Version](#atomic-test-1---find-and-display-internet-explorer-browser-version) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518/T1518.md) | - [Atomic Test #3 - Find and Display Safari Browser Version](#atomic-test-3---find-and-display-safari-browser-version) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518/T1518.md) | ## Atomic Test #1 - Find and Display Internet Explorer Browser Version | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518/T1518.md) | ## Atomic Test #3 - Find and Display Safari Browser Version | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | when sucessfully executed, the test is going to display running processes, firewall configuration on network profiles | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | when sucessfully executed, command shell  is going to display AV software it is running( Little snitch or carbon black ). | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | when sucessfully executed, the test is going to display sysmon driver instance if it is installed. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | when sucessfully executed, the test is going to display installed AV software. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | * Display Switcher: <code>C:\Windows\System32\DisplaySwitch.exe</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.006.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.006/T1552.006.md) | Successful test execution will either display the credentials found in the GPP files or indicate "No preference files found". | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [roll-the-dice.md](https://github.com/redcanaryco/atomic-red-team/blob/master/docs/roll-the-dice.md) | <table id="roll-the-dice" style="width: auto; margin: 0 auto; display: table; min-width: 700px; max-width: 700px;"> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [roll-the-dice.md](https://github.com/redcanaryco/atomic-red-team/blob/master/docs/roll-the-dice.md) | <blockquote class="random-test-description" style="display: block;"></blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [python](https://github.com/redcanaryco/atomic-red-team/blob/master/execution-frameworks/contrib/python/README.md) | #     the command, the system will display what line needs to be added to your script. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt41.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt41.yar) | $s1 = "Rundll32.exe \"%s\", DisPlay 64" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $s1 = "USAGE: xspy -display <display> -delay <usecs> -up" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_project_sauron_extras.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_project_sauron_extras.yar) | $s3 = "Do not display MAC addresses" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_querty_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_querty_fiveeyes.yar) | $s8 = "<definition>display help for this function</definition>" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


