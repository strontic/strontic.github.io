---
title: taskkill.exe | Terminates Processes
excerpt: What is taskkill.exe?
---

# taskkill.exe 

* File Path: `C:\Windows\system32\taskkill.exe`
* Description: Terminates Processes

## Hashes

Type | Hash
-- | --
MD5 | `ABA3AAD5620E89D22D51028EEDAD3FD6`
SHA1 | `B32550D8266D1DC12321256A22E9F04E9EBF9399`
SHA256 | `9472F2DA48163A7BF36AF3D5A923957788721DCE35A3DA543CC5E7A1F5CA5475`
SHA384 | `56B76699A1D772CFEAC9D2EC8C240D2B435FA1038A45E0D164618F6B4593620345C351D67786B35BE436A785EDC53766`
SHA512 | `A7F714909113F5AC779B125605DACFD78A3EF4295803F6854E016CF48883342F397A364EDE7E2C493A23596A6D54D009C5A11439E431E4FF77A3B4467F86E8B4`
SSDEEP | `1536:cAp6xbI3UqPle0lubx7WapilgWXZpf8mhPBdsakczahKq4o+rpWwzD7aInBxleUX:cAp6xbI3UqPleYXiaLH7dsakcGhaWIaw`
IMP | `100938B32F577E925618EA395A8C469B`
PESHA1 | `9BE55E3B57E5349957E8D8FF27856CCC54A38641`
PE256 | `9022AC50A57A60589C16A7E1917AAFF4C879EE2BCB98367D9068A5450A63A18B`

## Runtime Data

### Usage (stdout):
```cmhg

TASKKILL [/S system [/U username [/P [password]]]]
         { [/FI filter] [/PID processid | /IM imagename] } [/T] [/F]

Description:
    This tool is used to terminate tasks by process id (PID) or image name.

Parameter List:
    /S    system           Specifies the remote system to connect to.

    /U    [domain\]user    Specifies the user context under which the
                           command should execute.

    /P    [password]       Specifies the password for the given user
                           context. Prompts for input if omitted.

    /FI   filter           Applies a filter to select a set of tasks.
                           Allows "*" to be used. ex. imagename eq acme*

    /PID  processid        Specifies the PID of the process to be terminated.
                           Use TaskList to get the PID.

    /IM   imagename        Specifies the image name of the process
                           to be terminated. Wildcard '*' can be used
                           to specify all tasks or image names.

    /T                     Terminates the specified process and any
                           child processes which were started by it.

    /F                     Specifies to forcefully terminate the process(es).

    /?                     Displays this help message.

Filters:
    Filter Name   Valid Operators           Valid Value(s)
    -----------   ---------------           -------------------------
    STATUS        eq, ne                    RUNNING |
                                            NOT RESPONDING | UNKNOWN
    IMAGENAME     eq, ne                    Image name
    PID           eq, ne, gt, lt, ge, le    PID value
    SESSION       eq, ne, gt, lt, ge, le    Session number.
    CPUTIME       eq, ne, gt, lt, ge, le    CPU time in the format
                                            of hh:mm:ss.
                                            hh - hours,
                                            mm - minutes, ss - seconds
    MEMUSAGE      eq, ne, gt, lt, ge, le    Memory usage in KB
    USERNAME      eq, ne                    User name in [domain\]user
                                            format
    MODULES       eq, ne                    DLL name
    SERVICES      eq, ne                    Service name
    WINDOWTITLE   eq, ne                    Window title

    NOTE
    ----
    1) Wildcard '*' for /IM switch is accepted only when a filter is applied.
    2) Termination of remote processes will always be done forcefully (/F).
    3) "WINDOWTITLE" and "STATUS" filters are not considered when a remote
       machine is specified.

Examples:
    TASKKILL /IM notepad.exe
    TASKKILL /PID 1230 /PID 1241 /PID 1253 /T
    TASKKILL /F /IM cmd.exe /T 
    TASKKILL /F /FI "PID ge 1000" /FI "WINDOWTITLE ne untitle*"
    TASKKILL /F /FI "USERNAME eq NT AUTHORITY\SYSTEM" /IM notepad.exe
    TASKKILL /S system /U domain\username /FI "USERNAME ne NT*" /IM *
    TASKKILL /S system /U username /P password /FI "IMAGENAME eq note*"

```

### Usage (stderr):
```cmhg
ERROR: Invalid argument/option - '--help'.
Type "TASKKILL /?" for usage.

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\dbghelp.dll |
C:\Windows\system32\framedynos.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MPR.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\system32\netutils.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\system32\srvcli.dll |
C:\Windows\system32\SspiCli.dll |
C:\Windows\system32\taskkill.exe |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\VERSION.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\WS2_32.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: taskkill.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/9472f2da48163a7bf36af3d5a923957788721dce35a3da543cc5e7a1f5ca5475/detection/


## Possible Misuse

*The following table contains possible examples of `taskkill.exe` being misused. While `taskkill.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_babyshark.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_babyshark.yml) | `- cmd.exe /c taskkill /im cmd.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- taskkill.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rundll32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rundll32.yml) | `- Command: rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();h=new%20ActiveXObject("WScript.Shell").run("calc.exe",0,true);try{h.Send();b=h.ResponseText;eval(b);}catch(e){new%20ActiveXObject("WScript.Shell").Run("cmd /c taskkill /f /im rundll32.exe",0,true);}` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027/T1027.md) | taskkill /f /im calculator.exe >nul 2>nul | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | taskkill.exe /f /im #{process_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.002/T1574.002.md) | taskkill /F /IM #{process_name} >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_golddragon.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_golddragon.yar) | $s3 = "taskkill /f /im daumcleaner.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_greenbug.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_greenbug.yar) | $s4 = "taskkill /im winit.exe /f" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_irontiger.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_irontiger.yar) | $s5 = "taskkill /im conime.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keyboys.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keyboys.yar) | $s1 = "taskkill /f /pid %s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_leviathan.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_leviathan.yar) | $x2 = ".Run \"taskkill /im mshta.exe" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $a1 = "taskkill /F /IM cscript.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) | $x1 = "cmd /c taskkill /im cliconfg.exe /f /t && del /f /q" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti_burning_umbrella.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti_burning_umbrella.yar) | $s1 = "Taskkill /IM  %s /F &  %s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cn_campaign_njrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cn_campaign_njrat.yar) | $a1 = "taskkill /f /im cmd.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cn_campaign_njrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cn_campaign_njrat.yar) | $a2 = "taskkill /f /im mstsc.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cn_campaign_njrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cn_campaign_njrat.yar) | $a3 = "taskkill /f /im taskmgr.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cn_campaign_njrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cn_campaign_njrat.yar) | $a4 = "taskkill /f /im regedit.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cn_campaign_njrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cn_campaign_njrat.yar) | $a5 = "taskkill /f /im mmc.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_nansh0u.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_nansh0u.yar) | $s1 = "taskkill /im cmd.exe /f" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## taskkill

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Ends one or more tasks or processes. Processes can be ended by process ID or image name. You can use the [tasklist command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/tasklist.md) command to determine the process ID (PID) for the process to be ended.

> [!NOTE]
> This command replaces the **kill** tool.

### Syntax

```
taskkill [/s <computer> [/u [<domain>\]<username> [/p [<password>]]]] {[/fi <filter>] [...] [/pid <processID> | /im <imagename>]} [/f] [/t]
```

#### Parameters

| Parameter | Description |
|--|--|
|  /s `<computer>` | Specifies the name or IP address of a remote computer (do not use backslashes). The default is the local computer. |
| /u `<domain>\<username>` | Runs the command with the account permissions of the user who is specified by `<username>` or by `<domain>\<username>`. The **/u** parameter can be specified only if **/s** is also specified. The default is the permissions of the user who is currently logged on to the computer that is issuing the command. |
| /p `<password>` | Specifies the password of the user account that is specified in the **/u** parameter. |
| /fi `<filter>` | Applies a filter to select a set of tasks. You can use more than one filter or use the wildcard character (`*`) to specify all tasks or image names. The valid filters are listed in the **Filter names, operators, and values** section of this article. |
| /pid `<processID>` | Specifies the process ID of the process to be terminated. |
| /im `<imagename>` | Specifies the image name of the process to be terminated. Use the wildcard character (`*`) to specify all image names. |
| /f | Specifies that processes be forcefully ended. This parameter is ignored for remote processes; all remote processes are forcefully ended. |
| /t | Ends the specified process and any child processes started by it. |

##### Filter names, operators, and values

| Filter Name | Valid Operators | Valid Value(s) |
|--|--|--|
| STATUS | eq, ne | `RUNNING | NOT RESPONDING | UNKNOWN` |
| IMAGENAME | eq, ne | Image name |
| PID | eq, ne, gt, lt, ge, le | PID value |
| SESSION | eq, ne, gt, lt, ge, le | Session number |
| CPUtime | eq, ne, gt, lt, ge, le | CPU time in the format *HH:MM:SS*, where *MM* and *SS* are between 0 and 59 and *HH* is any unsigned number |
| MEMUSAGE | eq, ne, gt, lt, ge, le | Memory usage in KB |
| USERNAME | eq, ne | Any valid user name (`<user>` or `<domain\user>`) |
| SERVICES | eq, ne | Service name |
| WINDOWTITLE | eq, ne | Window title |
| MODULES | eq, ne | DLL name |

### Remarks

- The **WINDOWTITLE** and **STATUS** filters aren't supported when a remote system is specified.

- The wildcard character (`*`) is accepted for the `*/im` option, only when a filter is applied.

- Ending a remote process is always carried out forcefully, regardless whether the **/f** option is specified.

- Providing a computer name to the hostname filter causes a shutdown, stopping all processes.

### Examples

To end the processes with process IDs *1230*, *1241*, and *1253*, type:

```
taskkill /pid 1230 /pid 1241 /pid 1253
```

To forcefully end the process *Notepad.exe* if it was started by the system, type:

```
taskkill /f /fi "USERNAME eq NT AUTHORITY\SYSTEM" /im notepad.exe
```

To end all processes on the remote computer *Srvmain* with an image name beginning with *note*, while using the credentials for the user account *Hiropln*, type:

```
taskkill /s srvmain /u maindom\hiropln /p p@ssW23 /fi "IMAGENAME eq note*" /im *
```

To end the process with the process ID *2134* and any child processes that it started, but only if those processes were started by the Administrator account, type:

```
taskkill /pid 2134 /t /fi "username eq administrator"
```

To end all processes that have a process ID *greater than or equal to 1000*, regardless of their image names, type:

```
taskkill /f /fi "PID ge 1000" /im *
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [tasklist command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/tasklist.md)

---



MIT License. Copyright (c) 2020 Strontic.


