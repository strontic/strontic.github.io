---
title: timeout.exe | timeout - pauses command processing
excerpt: What is timeout.exe?
---

# timeout.exe 

* File Path: `C:\Windows\SysWOW64\timeout.exe`
* Description: timeout - pauses command processing

## Hashes

Type | Hash
-- | --
MD5 | `E26D6B70C2C4B4E47F4A7287CFD33554`
SHA1 | `2FA9BC458A3CB15446F976D7DA926058FF4E002F`
SHA256 | `A7B4ACFB3A3EFDD83AF8664F404D937FFD440564CB43A872DAE0AC21D99AFBD8`
SHA384 | `EBA858AC55B31D96B7A0B2B170AF2BB5F52EFD45620BEE743DE39FDC3ED904DF75500BD40D2CEB980938E0FBC935A31A`
SHA512 | `5CC454C35BCBAB3938F524AB185BA4D42618FA7980F9CF4BA5D9A820CD2A464F8F53D5FD86E6C192A62AEE9E3587985180EC1B25AD12F024F7C7783447AF7326`
SSDEEP | `384:WeHPRuRW/4PyYUKbdOqvbHAGn5qpKc4Q3s6syXUnj8MXsPxzDjGX5PfxY8K8tI1R:tHP4RSEAqj8TVXRXPxzDj6fxverWz0P`

## Runtime Data

### Usage (stdout):
```cmhg

TIMEOUT [/T] timeout [/NOBREAK] 

Description:
    This utility accepts a timeout parameter to wait for the specified
    time period (in seconds) or until any key is pressed. It also 
    accepts a parameter to ignore the key press. 

Parameter List:
    /T        timeout       Specifies the number of seconds to wait.
                            Valid range is -1 to 99999 seconds.

    /NOBREAK                Ignore key presses and wait specified time.

    /?                      Displays this help message.

NOTE: A timeout value of -1 means to wait indefinitely for a key press.

Examples:
    TIMEOUT /?
    TIMEOUT /T 10
    TIMEOUT /T 300 /NOBREAK
    TIMEOUT /T -1

```

### Usage (stderr):
```cmhg
ERROR: Invalid value for timeout (/T) specified. Valid range is -1 to 99999.

```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: timeout.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `timeout.exe` being misused. While `timeout.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_susp_del.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_susp_del.yml) | `#cmd.exe (PID: 1044 cmdline: 'C:\Windows\System32\cmd.exe' /c taskkill /im A8D4.exe /f & timeout /t 6 & del /f /q 'C:\Users\user~1\AppData\Local\Temp\A8D4.exe' & del C:\ProgramData\*.dll & exit `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `==== :timeout`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [kessel_config.ksy](https://github.com/eset/malware-ioc/blob/master/sshdoor/kessel_config.ksy) | `- id: timeout`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor.yar](https://github.com/eset/malware-ioc/blob/master/sshdoor/sshdoor.yar) | `$usage = "usage: %s [-46Hv] [-f file] [-p port] [-T timeout] [-t type]"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: Unlimited sudo cache timeout [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - Atomic Test #2: Unlimited sudo cache timeout [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) | - Atomic Test #2: Unlimited sudo cache timeout [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | Upon execution, cmd will be launched by powershell. If using Invoke-AtomicTest, The test will hang until the 120 second timeout cancels the session | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1040.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1040/T1040.md) | TIMEOUT /T 50 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | \| timeout \| Timeout period before ending process (seconds) \| Integer \| 1\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | timeout --preserve-status #{timeout} whois -h #{remote_host} -p #{remote_port} "#{query}" > #{output_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | ##### Description: The whois and timeout commands must be present | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | which whois && which timeout | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | echo "Please install timeout and the whois package" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | cmd /c "timeout #{recording_time} > NULL && psr.exe /stop" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1197.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1197/T1197.md) | timeout 5 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | \| timeout \| Timeout period before shutdown (seconds) \| Integer \| 1\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | shutdown /s /t #{timeout} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | \| timeout \| Timeout period before restart (seconds) \| Integer \| 1\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | shutdown /r /t #{timeout} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | \| timeout \| Time to restart (can be minutes or specific time) \| String \| now\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | shutdown -r #{timeout} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | \| timeout \| Time to shutdown (can be minutes or specific time) \| String \| now\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1529.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1529/T1529.md) | shutdown -h #{timeout} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.002/T1546.002.md) | * <code>ScreenSaveTimeout</code> - sets user inactivity timeout before screensaver is executed | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.003/T1548.003.md) | Within Linux and MacOS systems, sudo (sometimes referred to as "superuser do") allows users to perform commands from terminals with elevated privileges and to control who can perform these commands on the system. The <code>sudo</code> command "allows a system administrator to delegate authority to give certain users (or groups of users) the ability to run some (or all) commands as root or another user while providing an audit trail of the commands and their arguments."(Citation: sudo man page 2018) Since sudo was made for the system administrator, it has some useful configuration features such as a <code>timestamp_timeout</code>, which is the amount of time in minutes between instances of <code>sudo</code> before it will re-prompt for a password. This is because <code>sudo</code> has the ability to cache credentials for a period of time. Sudo creates (or touches) a file at <code>/var/db/sudo</code> with a timestamp of when sudo was last run to determine this timeout. Additionally, there is a <code>tty_tickets</code> variable that treats each new tty (terminal session) in isolation. This means that, for example, the sudo timeout of one tty will not affect another tty (you will have to type the password again). | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.003/T1548.003.md) | - [Atomic Test #2 - Unlimited sudo cache timeout](#atomic-test-2---unlimited-sudo-cache-timeout) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.003/T1548.003.md) | ## Atomic Test #2 - Unlimited sudo cache timeout | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt15.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt15.yar) | $s6 = "Cmd timeout %d" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_aus_parl_compromise.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_aus_parl_compromise.yar) | $x1 = "not a valid timeout format!" ascii wide fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_emissary.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_emissary.yar) | $s2 = "execute cmd timeout." fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $s1 = "Active connections will be maintained for this tunnel. Timeout:" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $x2 = "[-] timeout waiting for response - target may have crashed" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $s5 = "WARNING: LP Timeout specified (%lu seconds) less than default (%u seconds).  Setting default" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $s4 = "Timeout waiting for daemon to die.  Exploit probably failed." fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $x1 = "Probe #2 usage: %s -i TargetIp -p TargetPort -r %d [-o TimeOut] -t Protocol -n IMailUserName -a IMailPassword" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_lazarus_dec20.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_lazarus_dec20.yar) | $g4 = "session.timeout=600" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_triton_mal_sshdoor.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_triton_mal_sshdoor.yar) | $a_usage = "usage: %s [-46Hv] [-f file] [-p port] [-T timeout] [-t type]" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s1 = "Retransmission Timeout Algorithm    = unknown (%1!u!)" fullword wide  /* Goodware String - occured 2 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s4 = "Mutex object did not timeout, list not patched" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s5 = "Mutex object did not timeout, list not patched" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_empire.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_empire.yar) | $s1 = "Test-Port -h $h -p $Port -timeout $Timeout" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_empire.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_empire.yar) | $s2 = "1 {$nHosts=10;  $Threads = 32;   $Timeout = 5000 }" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_equation_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_equation_fiveeyes.yar) | $s3 = "Timeout waiting for the \"canInstallNow\" event from the implant-specific EXE!" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s5 = "TIMEOUT while waiting for Ack block %d. file <%s>" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s1 = "usage: %s <fisier ipuri> <fisier useri:parole> <connect timeout> <fail2ban wait> <threads> <outfile> <port>" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s3 = "$sock = @ftp_connect($host,$port,$timeout);" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "function ftp_check($host,$user,$pass,$timeout){" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [1b4fb81c-8090-426c-93ab-0a633e7a16a7.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/credential-access/1b4fb81c-8090-426c-93ab-0a633e7a16a7.yml) | `timeout: 80`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [5f844ac9-5f24-4196-a70d-17f0bd44a934.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/5f844ac9-5f24-4196-a70d-17f0bd44a934.yml) | `Commandline = 'cmd.exe /c "timeout /nobreak /t 10 >nul 2>nul & del /f #{location}"';`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [5a4cb2be-2684-4801-9355-3a90c91e0004.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/discovery/5a4cb2be-2684-4801-9355-3a90c91e0004.yml) | `timeout: 180`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [95727b87-175c-4a69-8c7a-a5d82746a753.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/execution/95727b87-175c-4a69-8c7a-a5d82746a753.yml) | `timeout: 300`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [46da2385-cf37-49cb-ba4b-a739c7a19de4.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/impact/46da2385-cf37-49cb-ba4b-a739c7a19de4.yml) | `# Linux distros should include `timeout` making this easy.`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [46da2385-cf37-49cb-ba4b-a739c7a19de4.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/impact/46da2385-cf37-49cb-ba4b-a739c7a19de4.yml) | `# We expect timeout to return a 124, which needs to then return a 0`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [46da2385-cf37-49cb-ba4b-a739c7a19de4.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/impact/46da2385-cf37-49cb-ba4b-a739c7a19de4.yml) | `timeout 60 ./xmrig-6.11.2/xmrig;`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [46da2385-cf37-49cb-ba4b-a739c7a19de4.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/impact/46da2385-cf37-49cb-ba4b-a739c7a19de4.yml) | `timeout: 120`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [46da2385-cf37-49cb-ba4b-a739c7a19de4.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/impact/46da2385-cf37-49cb-ba4b-a739c7a19de4.yml) | `# MacOS does not include timeout, but can mimic the process with screen.`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [78524da1-f347-4fbb-9295-209f1f408330.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/impact/78524da1-f347-4fbb-9295-209f1f408330.yml) | `timeout: 120`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## timeout

Pauses the command processor for the specified number of seconds. This command is typically used in batch files.

### Syntax

```
timeout /t <timeoutinseconds> [/nobreak]
```

#### Parameters

| Parameter | Description |
|--|--|
| /t `<timeoutinseconds>` | Specifies the decimal number of seconds (between -1 and 99999) to wait before the command processor continues processing. The value **-1** causes the computer to wait indefinitely for a keystroke. |
| /nobreak | Specifies to ignore user key strokes. |
| /? | Displays help at the command prompt. |

##### Remarks

- A user keystroke resumes the command processor execution immediately, even if the timeout period has not expired.

- When used in conjunction with the resource kit's **Sleep** tool, **timeout** is similar to the **pause** command.

### Examples

To pause the command processor for ten seconds, type:

```
timeout /t 10
```

To pause the command processor for 100 seconds and ignore any keystroke, type:

```
timeout /t 100 /nobreak
```

To pause the command processor indefinitely until a key is pressed, type:

```
timeout /t -1
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


