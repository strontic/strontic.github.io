---
title: InstallUtil.exe | .NET Framework installation utility
excerpt: What is InstallUtil.exe?
---

# InstallUtil.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\InstallUtil.exe`
* Description: .NET Framework installation utility
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `B3C141D48E14652BFFA508E1C6BDDC6B`
SHA1 | `6ECFD55D91B2E725E1EFDE5678DE5E2332A0E971`
SHA256 | `774ADCEF9CEBC4B12C2C10D0A05ED3D4F59F739DB38700E4A763085B8146137E`
SHA384 | `4937D5E91A707B812A8864806F87DF11EC7748528CFA48800B54D2408E085B372BC1CD5E81ACBE156CCCB5960E0C7523`
SHA512 | `4903758E0AB9FDC8AB019D86A5962FD5DBBCB2037DB1580709BCC38BA5B7AE951A160136DC5CB8A6050E3286CEAC0127DE4249168B4B762DF3E6733C8AC6540E`
SSDEEP | `384:utpFVymMsihB9VKS7xdgxYKJ9Yl6dnPU3SERztmbqCJstdMardz/JikPZ+LPZT3z:C5Ms2SqdCb6Iq8H5luWWa`
PESHA1 | `F301A41D2B963E8AB5E3D39E7600B8B8DEE70615`
PE256 | `0C0FC87547372B8ACFDF9F028D7B3303DE71EA84B0704A06F6B3658EE113C851`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) .NET Framework Installation utility Version 4.8.4161.0
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
C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\InstallUtil.exe |
C:\WINDOWS\System32\KERNEL32.dll |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\MSCOREE.DLL |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: InstallUtil.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4161.0 built by: NET48REL1
* Product Version: 4.8.4161.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/774adcef9cebc4b12c2c10d0a05ed3d4f59f739db38700e4a763085b8146137e/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\StoreAdm.exe](StoreAdm.exe-85B13A98346827385E170C43C6210B3C.md) | 68
[C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.Web.ApplicationServices.dll](System.Web.ApplicationServices.dll-0C1A4B54901395498BADC6CD91C6C59C.md) | 46
[C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.Web.DynamicData.Design.dll](System.Web.DynamicData.Design.dll-B2AB11DE28D8499277978488AF4C471F.md) | 61
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\AddInProcess.exe](AddInProcess.exe-929EA1AF28AFEA2A3311FD4297425C94.md) | 63
[C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\AddInProcess.exe](AddInProcess.exe-B67A67922F2BF068F52C8128459309B6.md) | 63
[C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\AddInProcess32.exe](AddInProcess32.exe-816A42D47AA933E55428DF42C2BA8505.md) | 65
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\AddInProcess32.exe](AddInProcess32.exe-9827FF3CDF4B83F9C86354606736CA9C.md) | 65
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\AddInUtil.exe](AddInUtil.exe-11BED2C86507F7DF04BA52CFC7EB7276.md) | 66
[C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\AddInUtil.exe](AddInUtil.exe-A22D448037901AAF7AE785369075DD4D.md) | 66
[C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\aspnet_regbrowsers.exe](aspnet_regbrowsers.exe-4C506220CA3C082D31AF7C725CC33A3F.md) | 65
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\aspnet_regbrowsers.exe](aspnet_regbrowsers.exe-BB8B6B54FD50C08AB579B84BF07918CF.md) | 63
[C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\InstallUtil.exe](InstallUtil.exe-3C94B02364BA067E6C181191A5273824.md) | 91
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\InstallUtil.exe](InstallUtil.exe-5D4073B2EB6D217C19F2B22F21BF8D57.md) | 88
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\AddInProcess.exe](AddInProcess.exe-929EA1AF28AFEA2A3311FD4297425C94.md) | 63
[C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\AddInProcess.exe](AddInProcess.exe-B67A67922F2BF068F52C8128459309B6.md) | 63
[C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\AddInProcess32.exe](AddInProcess32.exe-816A42D47AA933E55428DF42C2BA8505.md) | 65
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\AddInProcess32.exe](AddInProcess32.exe-9827FF3CDF4B83F9C86354606736CA9C.md) | 65
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\AddInUtil.exe](AddInUtil.exe-11BED2C86507F7DF04BA52CFC7EB7276.md) | 66
[C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\AddInUtil.exe](AddInUtil.exe-A22D448037901AAF7AE785369075DD4D.md) | 66
[C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\aspnet_regbrowsers.exe](aspnet_regbrowsers.exe-05993DA6AFECB2867DB00BFAE87A4A27.md) | 63
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\aspnet_regbrowsers.exe](aspnet_regbrowsers.exe-542F3F799FC63406802309E9D6415BA7.md) | 63
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\InstallUtil.exe](InstallUtil.exe-909A1D386235DD5F6BA61B91BA34119D.md) | 93

## Possible Misuse

*The following table contains possible examples of `InstallUtil.exe` being misused. While `InstallUtil.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\installutil.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_possible_applocker_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_possible_applocker_bypass.yml) | `- '\installutil.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_possible_applocker_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_possible_applocker_bypass.yml) | `- Using installutil to add features for .NET applications (primarily would occur in developer environments)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `Name: Installutil.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `- Command: InstallUtil.exe /logfile= /LogToConsole=false /U AllTheThings.dll`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `- Path: C:\Windows\Microsoft.NET\Framework\v2.0.50727\InstallUtil.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v2.0.50727\InstallUtil.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `- Path: C:\Windows\Microsoft.NET\Framework\v4.0.30319\InstallUtil.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\InstallUtil.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `- Link: https://pentestlab.blog/2017/05/08/applocker-bypass-installutil/`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Installutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Installutil.yml) | `- Link: https://docs.microsoft.com/en-us/dotnet/framework/tools/installutil-exe-installer-tool`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [sparklinggoblin](https://github.com/eset/malware-ioc/blob/master/sparklinggoblin/README.adoc) | `==== InstallUtil-based .NET loader used to decrypt and load SideWalk`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [sparklinggoblin](https://github.com/eset/malware-ioc/blob/master/sparklinggoblin/README.adoc) | `==== InstallUtil-based .NET loader used to decrypt and load Cobalt Strike`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [sparklinggoblin](https://github.com/eset/malware-ioc/blob/master/sparklinggoblin/README.adoc) | `\|T1218.004\|Signed Binary Proxy Execution: InstallUtil`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
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
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| Path Interception by Search Order Hijacking [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [RC Scripts](../../T1037.004/T1037.004.md) \| [InstallUtil](../../T1218.004/T1218.004.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [Path Interception by Unquoted Path](../../T1574.009/T1574.009.md) \| [Registry Run Keys / Startup Folder](../../T1547.001/T1547.001.md) \| [InstallUtil](../../T1218.004/T1218.004.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
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



MIT License. Copyright (c) 2020-2021 Strontic.


