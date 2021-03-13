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
MD5 | `A599D3B2FAFBDE4C1A6D7D0F839451C7`
SHA1 | `0225BBEC16CB7B23B189F811065767180EDA9801`
SHA256 | `56F8CC2C1790C389394733B84C3FB55E10977E9F0FE0C08110AC11F0FE47F05E`
SHA384 | `94A9CBC5732353B92378FD8BCE2941AEA223991653BFD2FE330FE40C79AFE239E8CEA5FCC16439C82D8320E4094FFD83`
SHA512 | `ACFD16B245A667C3766D36EA753AA7002A03C206B7C3117CCAC92315401B536F56CEFF606D8112178DD8916A20378AB91818E0E65E6CCFD5D75955F511D6FBFB`
SSDEEP | `1536:mr0UyaEu4C1f5FJHLK9eHckIe5VZ67IrujQR4I+9TrxxIzN:y0UBEu4kNysIe5V8MCj5xxIB`
IMP | `71212588549FB37A46C8556278F180CD`
PESHA1 | `D79571C64CF61F2668BEE3A5D1A944BC6D97C8A8`
PE256 | `4EA4FAC43EEE4D1B3F7D37B81A7ABE05E880D9A7361A1A190A5014092AE585EC`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\taskkill.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: taskkill.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/56f8cc2c1790c389394733b84c3fb55e10977e9f0fe0c08110ac11f0fe47f05e/detection


## Possible Misuse

*The following table contains possible examples of `taskkill.exe` being misused. While `taskkill.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_babyshark.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_babyshark.yml) | `- cmd.exe /c taskkill /im cmd.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- taskkill.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_disable_raccine.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_disable_raccine.yml) | `- 'taskkill '`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rundll32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rundll32.yml) | `- Command: rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();h=new%20ActiveXObject("WScript.Shell").run("calc.exe",0,true);try{h.Send();b=h.ResponseText;eval(b);}catch(e){new%20ActiveXObject("WScript.Shell").Run("cmd /c taskkill /f /im rundll32.exe",0,true);}`{:.highlight .language-yaml} | 
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
[stockpile](https://github.com/mitre/stockpile) | [95727b87-175c-4a69-8c7a-a5d82746a753.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/execution/95727b87-175c-4a69-8c7a-a5d82746a753.yml) | `taskkill /s \\#{remote.host.fqdn} /FI "Imagename eq s4ndc4t.exe"`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [ece5dde3-d370-4c20-b213-a1f424aa8d03.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/execution/ece5dde3-d370-4c20-b213-a1f424aa8d03.yml) | `wmic /node:`"#{remote.host.fqdn}`" /user:`"#{domain.user.name}`" /password:`"#{domain.user.password}`" process call create "taskkill /f /im s4ndc4t.exe"`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)

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



MIT License. Copyright (c) 2020-2021 Strontic.


