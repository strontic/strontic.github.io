---
title: InstallUtil.exe | .NET Framework installation utility
excerpt: What is InstallUtil.exe?
---

# InstallUtil.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\InstallUtil.exe`
* Description: .NET Framework installation utility
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `5D4073B2EB6D217C19F2B22F21BF8D57`
SHA1 | `F0209900FBF08D004B886A0B3BA33EA2B0BF9DA8`
SHA256 | `AC1A3F21FCC88F9CEE7BF51581EAFBA24CC76C924F0821DEB2AFDF1080DDF3D3`
SHA384 | `3E9AE9529ADFA9761BD67D369ADFEC7C48221AEF5DCEBE187B3A1D5B9CDB520A0BC5FAE2C45F5AF96004735DE229743F`
SHA512 | `9AC94880684933BA3407CDC135ABC3047543436567AF14CD9269C4ADC5A6535DB7B867D6DE0D6238A21B94E69F9890DBB5739155871A624520623A7E56872159`
SSDEEP | `384:qtpFVLK0MsihB9VKS7xdgl6KJ9Yl6dnPU3SERztmbqCJstdMardz/JikPZ+RPZTg:GBMs2SqdSZ6Iq8BxTfqWR8h7ukP`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `793F60036EE1B811BC1AAEC4257E0191D9B381FF`
PE256 | `29BCDA3CF8EB64A4634E5BCFB1949B734D27F5A9652A207F75E6DFA468AF4394`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) .NET Framework Installation utility Version 4.8.4084.0
Copyright (C) Microsoft Corporation.  All rights reserved.

Usage: InstallUtil [/u | /uninstall] [option [...]] assembly [[option [...]] assembly] [...]]

InstallUtil executes the installers in each given assembly.
If the /u or /uninstall switch is specified, it uninstalls
the assemblies, otherwise it installs them. Unlike other
options, /u applies to all assemblies, regardless of where it
appears on the command line.

Installation is done in a transactioned way: If one of the
assemblies fails to install, the installations of all other
assemblies are rolled back. Uninstall is not transactioned.

Options take the form /switch=[value]. Any option that occurs
before the name of an assembly will apply to that assembly's
installation. Options are cumulative but overridable - options
specified for one assembly will apply to the next as well unless
the option is specified with a new value. The default for all
options is empty or false unless otherwise specified.

Options recognized:

Options for installing any assembly:
/AssemblyName
 The assembly parameter will be interpreted as an assembly name (Name,
 Locale, PublicKeyToken, Version). The default is to interpret the
 assembly parameter as the filename of the assembly on disk.

/LogFile=[filename]
 File to write progress to. If empty, do not write log. Default
 is <assemblyname>.InstallLog

/LogToConsole={true|false}
 If false, suppresses output to the console.

/ShowCallStack
 If an exception occurs at any point during installation, the call
 stack will be printed to the log.

/InstallStateDir=[directoryname]
 Directory in which the .InstallState file will be stored. Default
 is the directory of the assembly.


Individual installers used within an assembly may recognize other
options. To learn about these options, run InstallUtil with the paths
of the assemblies on the command line along with the /? or /help option.



```

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework\v4.0.30319\InstallUtil.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: InstallUtil.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/ac1a3f21fcc88f9cee7bf51581eafba24cc76c924f0821deb2afdf1080ddf3d3/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\AddInProcess.exe](AddInProcess.exe-929EA1AF28AFEA2A3311FD4297425C94.md) | 63
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\AddInProcess32.exe](AddInProcess32.exe-9827FF3CDF4B83F9C86354606736CA9C.md) | 66
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\AddInUtil.exe](AddInUtil.exe-11BED2C86507F7DF04BA52CFC7EB7276.md) | 63
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\aspnet_regbrowsers.exe](aspnet_regbrowsers.exe-BB8B6B54FD50C08AB579B84BF07918CF.md) | 63
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\AddInProcess.exe](AddInProcess.exe-929EA1AF28AFEA2A3311FD4297425C94.md) | 63
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\AddInProcess32.exe](AddInProcess32.exe-9827FF3CDF4B83F9C86354606736CA9C.md) | 66
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\AddInUtil.exe](AddInUtil.exe-11BED2C86507F7DF04BA52CFC7EB7276.md) | 63
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\aspnet_regbrowsers.exe](aspnet_regbrowsers.exe-542F3F799FC63406802309E9D6415BA7.md) | 61
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\InstallUtil.exe](InstallUtil.exe-909A1D386235DD5F6BA61B91BA34119D.md) | 91

## Possible Misuse

*The following table contains possible examples of `InstallUtil.exe` being misused. While `InstallUtil.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_possible_applocker_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_possible_applocker_bypass.yml) | `- '\installutil.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_possible_applocker_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_possible_applocker_bypass.yml) | `- Using installutil to add features for .NET applications (primarly would occur in developer environments)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\installutil.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `Name: Installutil.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `- Command: InstallUtil.exe /logfile= /LogToConsole=false /U AllTheThings.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `- Path: C:\Windows\Microsoft.NET\Framework\v2.0.50727\InstallUtil.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v2.0.50727\InstallUtil.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `- Path: C:\Windows\Microsoft.NET\Framework\v4.0.30319\InstallUtil.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\InstallUtil.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `- Link: https://pentestlab.blog/2017/05/08/applocker-bypass-installutil/` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `- Link: https://docs.microsoft.com/en-us/dotnet/framework/tools/installutil-exe-installer-tool` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1218.004 InstallUtil](../../T1218.004/T1218.004.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: InstallUtil class constructor method call [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #4: InstallUtil Install method call [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #5: InstallUtil Uninstall method call - /U variant [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #6: InstallUtil Uninstall method call - '/installtype=notransaction /action=uninstall' variant [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #7: InstallUtil HelpText method call [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #8: InstallUtil evasive invocation [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1218.004 InstallUtil](../../T1218.004/T1218.004.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: InstallUtil class constructor method call [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #4: InstallUtil Install method call [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #5: InstallUtil Uninstall method call - /U variant [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #6: InstallUtil Uninstall method call - '/installtype=notransaction /action=uninstall' variant [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #7: InstallUtil HelpText method call [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #8: InstallUtil evasive invocation [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| Outlook Home Page [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Process Doppelgänging [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [InstallUtil](../../T1218.004/T1218.004.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| Path Interception by Search Order Hijacking [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Registry Run Keys / Startup Folder](../../T1547.001/T1547.001.md) \| [InstallUtil](../../T1218.004/T1218.004.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | # T1218.004 - InstallUtil | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | <blockquote>Adversaries may use InstallUtil to proxy execution of code through a trusted Windows utility. InstallUtil is a command-line utility that allows for installation and uninstallation of resources by executing specific installer components specified in .NET binaries. (Citation: MSDN InstallUtil) InstallUtil is digitally signed by Microsoft and located in the .NET directories on a Windows system: <code>C:\Windows\Microsoft.NET\Framework\v<version>\InstallUtil.exe</code> and <code>C:\Windows\Microsoft.NET\Framework64\v<version>\InstallUtil.exe</code>. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | InstallUtil may also be used to bypass application control through use of attributes within the binary that execute the class decorated with the attribute <code>[System.ComponentModel.RunInstaller(true)]</code>. (Citation: LOLBAS Installutil)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | - [Atomic Test #3 - InstallUtil class constructor method call](#atomic-test-3---installutil-class-constructor-method-call) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | - [Atomic Test #4 - InstallUtil Install method call](#atomic-test-4---installutil-install-method-call) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | - [Atomic Test #5 - InstallUtil Uninstall method call - /U variant](#atomic-test-5---installutil-uninstall-method-call---u-variant) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | - [Atomic Test #6 - InstallUtil Uninstall method call - '/installtype=notransaction /action=uninstall' variant](#atomic-test-6---installutil-uninstall-method-call---installtypenotransaction-actionuninstall-variant) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | - [Atomic Test #7 - InstallUtil HelpText method call](#atomic-test-7---installutil-helptext-method-call) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | - [Atomic Test #8 - InstallUtil evasive invocation](#atomic-test-8---installutil-evasive-invocation) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | Executes the CheckIfInstallable class constructor runner instead of executing InstallUtil. Upon execution, the InstallUtil test harness will be executed. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | \| invocation_method \| the type of InstallUtil invocation variant - Executable, InstallHelper, or CheckIfInstallable \| String \| CheckIfInstallable\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | ##### Description: InstallUtil test harness script must be installed at specified location (#{test_harness}) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | Executes the InstallHelper class constructor runner instead of executing InstallUtil. Upon execution, no output will be displayed if the test | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | \| invocation_method \| the type of InstallUtil invocation variant - Executable, InstallHelper, or CheckIfInstallable \| String \| InstallHelper\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | ## Atomic Test #3 - InstallUtil class constructor method call | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | \| invocation_method \| the type of InstallUtil invocation variant - Executable, InstallHelper, or CheckIfInstallable \| String \| Executable\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | InstallUtil class constructor execution test failure. Installer assembly execution output did not match the expected output. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | ## Atomic Test #4 - InstallUtil Install method call | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | InstallUtil Install method execution test failure. Installer assembly execution output did not match the expected output. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | ## Atomic Test #5 - InstallUtil Uninstall method call - /U variant | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | InstallUtil Uninstall method execution test failure. Installer assembly execution output did not match the expected output. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | ## Atomic Test #6 - InstallUtil Uninstall method call - '/installtype=notransaction /action=uninstall' variant | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | ## Atomic Test #7 - InstallUtil HelpText method call | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | Executes the Uninstall Method. Upon execution, help information will be displayed for InstallUtil. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | InstallUtil HelpText property execution test failure. Installer assembly execution output did not match the expected output. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | ## Atomic Test #8 - InstallUtil evasive invocation | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | Executes an InstallUtil assembly by renaming InstallUtil.exe and using a nonstandard extension for the assembly. Upon execution, "Running a transacted installation." | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | Copy-Item -Path "$([System.Runtime.InteropServices.RuntimeEnvironment]::GetRuntimeDirectory())InstallUtil.exe" -Destination "$Env:windir\System32\Tasks\notepad.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.004/T1218.004.md) | Evasive Installutil invocation test failure. Installer assembly execution output did not match the expected output. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


