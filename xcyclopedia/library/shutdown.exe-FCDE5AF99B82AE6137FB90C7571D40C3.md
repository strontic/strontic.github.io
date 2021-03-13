---
title: shutdown.exe | Windows Shutdown and Annotation Tool
excerpt: What is shutdown.exe?
---

# shutdown.exe 

* File Path: `C:\Windows\SysWOW64\shutdown.exe`
* Description: Windows Shutdown and Annotation Tool

## Hashes

Type | Hash
-- | --
MD5 | `FCDE5AF99B82AE6137FB90C7571D40C3`
SHA1 | `91F6B1366737F1E71BAD6FE9DF6655882D9D968B`
SHA256 | `DBDC6188128B32E6E3D99CD0B136FF0F0EA6CDFA2D3C748F342C5697E7BF4C58`
SHA384 | `F2CD6CCE7DE9C78B980ACE219E3C7A941D24043FBE2C85ED42A9EEA30F8B8EDC8836B4884A9320D07454D5EC2D39576E`
SHA512 | `6FA5BA9000E83DA160534FE597D81C60DAF9B9F85E761E515AA06E1D6E7A6D7E63453854851D52EC08B306FCB08C970539A450AD498F920874C4E92EA09C8A8F`
SSDEEP | `384:wmTUCPg+2lfUgpsVQ+mzM9tjz+fUpdQHW1+SWWc:w8rx2CgpsVV9tjzCUpdJ+ac`
IMP | `8B92347E56758D2E293224C162867097`
PESHA1 | `28D51D773717086893CE114F72A541872E3C8F6E`
PE256 | `AEC954BD238BE91CCC213EC0C0A1538F5C930724DF6D46045472F5899556A4F5`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: C:\Windows\SysWOW64\shutdown.exe [/i | /l | /s | /sg | /r | /g | /a | /p | /h | /e | /o] [/hybrid] [/soft] [/fw] [/f]
    [/m \\computer][/t xxx][/d [p|u:]xx:yy [/c "comment"]]

    No args    Display help. This is the same as typing /?.
    /?         Display help. This is the same as not typing any options.
    /i         Display the graphical user interface (GUI).
               This must be the first option.
    /l         Log off. This cannot be used with /m or /d options.
    /s         Shutdown the computer.
    /sg        Shutdown the computer. On the next boot, if Automatic Restart Sign-On
               is enabled, automatically sign in and lock last interactive user.
               After sign in, restart any registered applications.
    /r         Full shutdown and restart the computer.
    /g         Full shutdown and restart the computer. After the system is rebooted,
               if Automatic Restart Sign-On is enabled, automatically sign in and
               lock last interactive user.
               After sign in, restart any registered applications.
    /a         Abort a system shutdown.
               This can only be used during the time-out period.
               Combine with /fw to clear any pending boots to firmware.
    /p         Turn off the local computer with no time-out or warning.
               Can be used with /d and /f options.
    /h         Hibernate the local computer.
               Can be used with the /f option.
    /hybrid    Performs a shutdown of the computer and prepares it for fast startup.
               Must be used with /s option.
    /fw        Combine with a shutdown option to cause the next boot to go to the
               firmware user interface.
    /e         Document the reason for an unexpected shutdown of a computer.
    /o         Go to the advanced boot options menu and restart the computer.
               Must be used with /r option.
    /m \\computer Specify the target computer.
    /t xxx     Set the time-out period before shutdown to xxx seconds.
               The valid range is 0-315360000 (10 years), with a default of 30.
               If the timeout period is greater than 0, the /f parameter is
               implied.
    /c "comment" Comment on the reason for the restart or shutdown.
               Maximum of 512 characters allowed.
    /f         Force running applications to close without forewarning users.
               The /f parameter is implied when a value greater than 0 is
               specified for the /t parameter.
    /d [p|u:]xx:yy  Provide the reason for the restart or shutdown.
               p indicates that the restart or shutdown is planned.
               u indicates that the reason is user defined.
               If neither p nor u is specified the restart or shutdown is
               unplanned.
               xx is the major reason number (positive integer less than 256).
               yy is the minor reason number (positive integer less than 65536).

Reasons on this computer:
(E = Expected U = Unexpected P = planned, C = customer defined)
Type	Major	Minor	Title

 U  	0	0	Other (Unplanned)
E   	0	0	Other (Unplanned)
E P 	0	0	Other (Planned)
 U  	0	5	Other Failure: System Unresponsive
E   	1	1	Hardware: Maintenance (Unplanned)
E P 	1	1	Hardware: Maintenance (Planned)
E   	1	2	Hardware: Installation (Unplanned)
E P 	1	2	Hardware: Installation (Planned)
E   	2	2	Operating System: Recovery (Unplanned)
E P 	2	2	Operating System: Recovery (Planned)
  P 	2	3	Operating System: Upgrade (Planned)
E   	2	4	Operating System: Reconfiguration (Unplanned)
E P 	2	4	Operating System: Reconfiguration (Planned)
  P 	2	16	Operating System: Service pack (Planned)
    	2	17	Operating System: Hot fix (Unplanned)
  P 	2	17	Operating System: Hot fix (Planned)
    	2	18	Operating System: Security fix (Unplanned)
  P 	2	18	Operating System: Security fix (Planned)
E   	4	1	Application: Maintenance (Unplanned)
E P 	4	1	Application: Maintenance (Planned)
E P 	4	2	Application: Installation (Planned)
E   	4	5	Application: Unresponsive
E   	4	6	Application: Unstable
 U  	5	15	System Failure: Stop error
 U  	5	19	Security issue (Unplanned)
E   	5	19	Security issue (Unplanned)
E P 	5	19	Security issue (Planned)
E   	5	20	Loss of network connectivity (Unplanned)
 U  	6	11	Power Failure: Cord Unplugged
 U  	6	12	Power Failure: Environment
  P 	7	0	Legacy API shutdown

```

### Usage (stderr):
```cmhg
Hibernation is not enabled on this system. You must enable hibernation in order to use the -h option.(126)

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\shutdown.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SHUTDOWN.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/dbdc6188128b32e6e3d99cd0b136ff0f0ea6cdfa2d3c748f342c5697e7bf4c58/detection


## Possible Misuse

*The following table contains possible examples of `shutdown.exe` being misused. While `shutdown.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [cisco_cli_dos.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/cisco/aaa/cisco_cli_dos.yml) | `description: Detect a system being shutdown or put into different boot mode`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [cisco_cli_dos.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/cisco/aaa/cisco_cli_dos.yml) | `- 'shutdown'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_crime_snatch_ransomware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_crime_snatch_ransomware.yml) | `# Shutdown in safe mode immediately `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_crime_snatch_ransomware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_crime_snatch_ransomware.yml) | `- 'shutdown /r /f /t 00'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_crime_snatch_ransomware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_crime_snatch_ransomware.yml) | `- Scripts that shutdown the system immediatly and reboot them in safe mode are unlikely`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `shutdown`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1529 System Shutdown/Reboot](../../T1529/T1529.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Shutdown System - Windows [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Restart System via `shutdown` - macOS/Linux [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #4: Shutdown System via `shutdown` - macOS/Linux [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #6: Shutdown System via `halt` - Linux [linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #8: Shutdown System via `poweroff` - Linux [linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - [T1529 System Shutdown/Reboot](../../T1529/T1529.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - Atomic Test #3: Restart System via `shutdown` - macOS/Linux [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - Atomic Test #4: Shutdown System via `shutdown` - macOS/Linux [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - Atomic Test #6: Shutdown System via `halt` - Linux [linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - Atomic Test #8: Shutdown System via `poweroff` - Linux [linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) | - [T1529 System Shutdown/Reboot](../../T1529/T1529.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) | - Atomic Test #3: Restart System via `shutdown` - macOS/Linux [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) | - Atomic Test #4: Shutdown System via `shutdown` - macOS/Linux [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1529 System Shutdown/Reboot](../../T1529/T1529.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Shutdown System - Windows [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/linux-matrix.md) | \|  \|  \| [Kernel Modules and Extensions](../../T1547.006/T1547.006.md) \| [Trap](../../T1546.005/T1546.005.md) \| File and Directory Permissions Modification [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Steal Application Access Token [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [System Network Configuration Discovery](../../T1016/T1016.md) \|  \| Remote Email Collection [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \| Multiband Communication [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [System Shutdown/Reboot](../../T1529/T1529.md) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/macos-matrix.md) | \|  \|  \| [Plist Modification](../../T1547.011/T1547.011.md) \| [Re-opened Applications](../../T1547.007/T1547.007.md) \| Hijack Execution Flow [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Unsecured Credentials [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| User Activity Based Checks [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \| Multiband Communication [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [System Shutdown/Reboot](../../T1529/T1529.md) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \| Shared Modules [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Create Account [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Domain Accounts [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Default Accounts](../../T1078.001/T1078.001.md) \| LLMNR/NBT-NS Poisoning and SMB Relay [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Security Software Discovery](../../T1518.001/T1518.001.md) \|  \| [Local Email Collection](../../T1114.001/T1114.001.md) \|  \| Multiband Communication [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [System Shutdown/Reboot](../../T1529/T1529.md) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \| [Windows Management Instrumentation](../../T1047/T1047.md) \| Domain Accounts [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Exploitation for Privilege Escalation [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Disable or Modify Tools](../../T1562.001/T1562.001.md) \| Modify Authentication Process [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [System Network Connections Discovery](../../T1049/T1049.md) \|  \| Remote Data Staging [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \| Multiband Communication [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [System Shutdown/Reboot](../../T1529/T1529.md) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | # T1529 - System Shutdown/Reboot | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | <blockquote>Adversaries may shutdown/reboot systems to interrupt access to, or aid in the destruction of, those systems. Operating systems may contain commands to initiate a shutdown/reboot of a machine. In some cases, these commands may also be used to initiate a shutdown/reboot of a remote computer.(Citation: Microsoft Shutdown Oct 2017) Shutting down or rebooting systems may disrupt access to computer resources for legitimate users. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | Adversaries may attempt to shutdown/reboot a system after impacting it in other ways, such as [Disk Structure Wipe](https://attack.mitre.org/techniques/T1561/002) or [Inhibit System Recovery](https://attack.mitre.org/techniques/T1490), to hasten the intended effects on system availability.(Citation: Talos Nyetya June 2017)(Citation: Talos Olympic Destroyer 2018)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | - [Atomic Test #1 - Shutdown System - Windows](#atomic-test-1---shutdown-system---windows) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | - [Atomic Test #3 - Restart System via `shutdown` - macOS/Linux](#atomic-test-3---restart-system-via-shutdown---macoslinux) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | - [Atomic Test #4 - Shutdown System via `shutdown` - macOS/Linux](#atomic-test-4---shutdown-system-via-shutdown---macoslinux) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | - [Atomic Test #6 - Shutdown System via `halt` - Linux](#atomic-test-6---shutdown-system-via-halt---linux) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | - [Atomic Test #8 - Shutdown System via `poweroff` - Linux](#atomic-test-8---shutdown-system-via-poweroff---linux) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | ## Atomic Test #1 - Shutdown System - Windows | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | \| timeout \| Timeout period before shutdown (seconds) \| string \| 1\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | shutdown /s /t #{timeout} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | shutdown /r /t #{timeout} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | ## Atomic Test #3 - Restart System via `shutdown` - macOS/Linux | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | shutdown -r #{timeout} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | ## Atomic Test #4 - Shutdown System via `shutdown` - macOS/Linux | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | \| timeout \| Time to shutdown (can be minutes or specific time) \| string \| now\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | shutdown -h #{timeout} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | ## Atomic Test #6 - Shutdown System via `halt` - Linux | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | ## Atomic Test #8 - Shutdown System via `poweroff` - Linux | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.002/T1546.002.md) | shutdown /r /t 0 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_blackenergy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_blackenergy.yar) | $s3 = "shutdown /r /t %d" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_blackenergy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_blackenergy.yar) | $s9 = "shutdown.exe" fullword wide /* Goodware String - occured 1 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) | $DK_shutdown = "shutdown /r /t %d" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keylogger_cn.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keylogger_cn.yar) | $s3 = "shutdown.exe -r -t 0" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turbo_campaign.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turbo_campaign.yar) | $s32 = "shutdown" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cn_campaign_njrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cn_campaign_njrat.yar) | $s7 = "shutdown -r -t 00" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_rats_malwareconfig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_rats_malwareconfig.yar) | $c2 = "shutdown -r -t 00" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [pua_xmrig_monero_miner.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/pua_xmrig_monero_miner.yar) | $s2 = "* COMMANDS:     'h' hashrate, 'p' pause, 'r' resume, 'q' shutdown" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [0821b0b0-7902-4a7b-8052-80bda5a43684.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/impact/0821b0b0-7902-4a7b-8052-80bda5a43684.yml) | `name: Shutdown Target System`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [0821b0b0-7902-4a7b-8052-80bda5a43684.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/impact/0821b0b0-7902-4a7b-8052-80bda5a43684.yml) | `description: Force shutdown a target system using Process Injection and raw shellcode`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## shutdown

Enables you to shut down or restart local or remote computers, one at a time.

### Syntax

```
shutdown [/i | /l | /s | /sg | /r | /g | /a | /p | /h | /e | /o] [/hybrid] [/fw] [/f] [/m \\computer][/t xxx][/d [p|u:]xx:yy [/c "comment"]]
```

#### Parameters

| Parameter | Description |
|--|--|
| /i | Displays the **Remote Shutdown** box. The **/i** option must be the first parameter following the command. If **/i** is specified, all other options are ignored. |
| /l | Logs off the current user immediately, with no time-out period. You cannot use **/l** with **/m** or **/t**. |
| /s | Shuts down the computer. |
| /sg | Shuts down the computer. On the next boot, if **Automatic Restart Sign-On** is enabled, the device automatically signs in and locks based on the last interactive user. After sign in, it restarts any registered applications. |
| /r | Restarts the computer after shutdown. |
| /g | Shuts down the computer. On the next restart, if **Automatic Restart Sign-On** is enabled, the device automatically signs in and locks based on the last interactive user. After sign in, it restarts any registered applications. |
| /a | Aborts a system shutdown. Effective only during the time-out period. To use **/a**, you must also use the **/m** option. |
| /p | Turns off the local computer only (not a remote computer)â€”with no time-out period or warning. You can use **/p** only with **/d** or **/f**. If your computer doesn't support power-off functionality, it will shut down when you use **/p**, but the power to the computer will remain on. |
| /h | Puts the local computer into hibernation, if hibernation is enabled. You can use **/h** only with **/f**. |
| hybrid | Shuts down the device and prepares it for fast startup. This option must be used with the **/s** option. |
| /fw | Combining this option with a shutdown option causes the next restart to go to the firmware user interface. |
| /e | Enables you to document the reason for the unexpected shutdown on the target computer. |
| /o | Goes to the **Advanced boot options** menu and restarts the device. This option must be used with the **/r** option. |
| /f | Forces running applications to close without warning users.<br>**Caution:** Using the **/f** option might result in loss of unsaved data. |
| /m `\\<computername>` | Specifies the target computer. Can't be used with the **/l** option. |
| /t `<xxx>` | Sets the time-out period before shutdown to *xxx* seconds. The valid range is 0-315360000 (10 years), with a default of 30. If the timeout period is greater than 0, the **/f** parameter is implied. |
| /d `[p | u:]<XX>:<YY>` | Lists the reason for the system restart or shutdown. The supported parameter values are:<ul><li>**p** - Indicates that the restart or shutdown is planned.</li><li>**u** - Indicates that the reason is user-defined.<p>**NOTE**<br>If **p** or **u** aren't specified, the restart or shutdown is unplanned.</li><li>*xx* - Specifies the major reason number (a positive integer, less than 256).</li><li>*yy* Specifies the minor reason number (a positive integer, less than 65536).</li></ul> |
| /c `<comment>` | Enables you to comment in detail about the reason for the shutdown. You must first provide a reason by using the **/d** option and you must enclose your comments in quotation marks. You can use a maximum of 511 characters. |
| /? | Displays help at the command prompt, including a list of the major and minor reasons that are defined on your local computer. |

##### Remarks

- Users must be assigned the **Shut down the system** user right to shut down a local or remotely administered computer that is using the **shutdown** command.

- Users must be members of the **Administrators** group to annotate an unexpected shutdown of a local or remotely administered computer. If the target computer is joined to a domain, members of the **Domain Admins** group might be able to perform this procedure. For more information, see:

  - [Default local groups](/previous-versions/windows/it-pro/windows-server-2003/cc785098(v=ws.10))

  - [Default groups](/previous-versions/windows/it-pro/windows-server-2003/cc756898(v=ws.10))

- If you want to shut down more than one computer at a time, you can call **shutdown** for each computer by using a script, or you can use **shutdown** **/i** to display the **Remote Shutdown** box.

- If you specify major and minor reason codes, you must first define these reason codes on each computer where you plan to use the reasons. If the reason codes aren't defined on the target computer, Shutdown Event Tracker can't log the correct reason text.

- Remember to indicate that a shutdown is planned by using the **p** parameter. Not using the **p** parameter, indicates that the shutdown was unplanned.

  - Using the **p** parameter, along the reason code for an unplanned shutdown, causes the shutdown to fail.

  - Not using the **p** parameter, and only providing the reason code for an planned shutdown, also causes the shutdown to fail

### Examples

To force apps to close and to restart the local computer after a one-minute delay, with the reason *Application: Maintenance (Planned)* and the comment "Reconfiguring myapp.exe", type:

```
shutdown /r /t 60 /c "Reconfiguring myapp.exe" /f /d p:4:1
```

To restart the remote computer *myremoteserver* with the same parameters as the previous example, type:

```
shutdown /r /m \\myremoteserver /t 60 /c "Reconfiguring myapp.exe" /f /d p:4:1
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


