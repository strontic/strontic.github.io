﻿---
title: whoami.exe | whoami - displays logged on user information
excerpt: What is whoami.exe?
---

# whoami.exe 

* File Path: `C:\Windows\system32\whoami.exe`
* Description: whoami - displays logged on user information

## Hashes

Type | Hash
-- | --
MD5 | `AA1E17EA3DB5CD9D8BC061CAEC74C6E8`
SHA1 | `9746E91BFC629D3A2E1FE6289B549C0452702004`
SHA256 | `8ECFFCCE38D4EE87ABAEE6CBE843D94D4F8FB98FAB3C356C7F6B70E60B10F88A`
SHA384 | `17F58D32D8A56D37CC46CCCCE9E63FEFD1FDD5CCF075A89FF9B0AC8D6B47797500B490CCE758D175E07250A298310526`
SHA512 | `5CAA6E849C0787B3166FDC59DD179ACBDE96EBC6BE64E0357A847DD8D7A46FE3EC27E153B9B29AAA212BFF335D41292E1FAE657D8453CFFCFCAB2FEAE11D93CA`
SSDEEP | `1536:FWrwmGBaI/GlzU7Io5hNTswuqUCP7OHL/31qOxHPkP:ormBn7phhspdCPk0Oxv6`

## Runtime Data

### Usage (stdout):
```cmhg

WhoAmI has three ways of working: 

Syntax 1:
    WHOAMI [/UPN | /FQDN | /LOGONID]

Syntax 2:
    WHOAMI { [/USER] [/GROUPS] [/CLAIMS] [/PRIV] } [/FO format] [/NH]

Syntax 3:
    WHOAMI /ALL [/FO format] [/NH]

Description:
    This utility can be used to get user name and group information
    along with the respective security identifiers (SID), claims,
    privileges, logon identifier (logon ID) for the current user
    on the local system. I.e. who is the current logged on user?
    If no switch is specified, tool displays the user name in NTLM
    format (domain\username).

Parameter List:
    /UPN                    Displays the user name in User Principal 
                            Name (UPN) format.

    /FQDN                   Displays the user name in Fully Qualified 
                            Distinguished Name (FQDN) format.

    /USER                   Displays information on the current user
                            along with the security identifier (SID).

    /GROUPS                 Displays group membership for current user,
                            type of account, security identifiers (SID)
                            and attributes.

    /CLAIMS                 Displays claims for current user,
                            including claim name, flags, type and values.

    /PRIV                   Displays security privileges of the current
                            user.

    /LOGONID                Displays the logon ID of the current user.

    /ALL                    Displays the current user name, groups 
                            belonged to along with the security 
                            identifiers (SID), claims and privileges for 
                            the current user access token.

    /FO       format        Specifies the output format to be displayed.
                            Valid values are TABLE, LIST, CSV.
                            Column headings are not displayed with CSV
                            format. Default format is TABLE.

    /NH                     Specifies that the column header should not
                            be displayed in the output. This is
                            valid only for TABLE and CSV formats.

    /?                      Displays this help message.

Examples:
    WHOAMI
    WHOAMI /UPN
    WHOAMI /FQDN 
    WHOAMI /LOGONID
    WHOAMI /USER
    WHOAMI /USER /FO LIST
    WHOAMI /USER /FO CSV
    WHOAMI /GROUPS
    WHOAMI /GROUPS /FO CSV /NH
    WHOAMI /CLAIMS
    WHOAMI /CLAIMS /FO LIST
    WHOAMI /PRIV
    WHOAMI /PRIV /FO TABLE
    WHOAMI /USER /GROUPS
    WHOAMI /USER /GROUPS /CLAIMS /PRIV
    WHOAMI /ALL
    WHOAMI /ALL /FO LIST
    WHOAMI /ALL /FO CSV /NH
    WHOAMI /?

```

### Usage (stderr):
```cmhg
ERROR: Invalid argument/option - '-help'.
Type "WHOAMI /?" for usage.

```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: whoami.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `whoami.exe` being misused. While `whoami.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- 'whoami'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `# Running whoami as LOCAL_SYSTEM (usually after privilege escalation)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `Image\|contains: '\whoami.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_webshell_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/process_creation/lnx_webshell_detection.yml) | `- '/whoami'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [web_webshell_keyword.yml](https://github.com/Neo23x0/sigma/blob/master/rules/web/web_webshell_keyword.yml) | `- =whoami`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_shell_spawn_from_winrm.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/win_susp_shell_spawn_from_winrm.yml) | `- '*\whoami.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_atlassian_confluence_cve_2021_26084_exploit.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_atlassian_confluence_cve_2021_26084_exploit.yml) | `- 'whoami'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_greenbug_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_greenbug_may20.yml) | `- '-noninteractive -executionpolicy bypass whoami'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cobaltstrike_process_patterns.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cobaltstrike_process_patterns.yml) | `CommandLine\|contains: '\cmd.exe /C whoami'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cobaltstrike_process_patterns.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cobaltstrike_process_patterns.yml) | `- '/C whoami'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cobaltstrike_process_patterns.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cobaltstrike_process_patterns.yml) | `- '\whoami.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `#       cmd.exe /Q /c whoami 1> \\127.0.0.1\ADMIN$\__1567439113.54 2>&1`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_local_system_owner_account_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_local_system_owner_account_discovery.yml) | `- Image\|endswith: '\whoami.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_dridex.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_dridex.yml) | `Image\|endswith: '\whoami.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_whoami.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_whoami.yml) | `title: Renamed Whoami Execution`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_whoami.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_whoami.yml) | `description: Detects the execution of whoami that has been renamed to a different name to avoid detection`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_whoami.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_whoami.yml) | `OriginalFileName: 'whoami.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_whoami.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_whoami.yml) | `Image\|endswith: '\whoami.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_commands_recon_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_commands_recon_activity.yml) | `- whoami`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_servu_exploitation_cve_2021_35211.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_servu_exploitation_cve_2021_35211.yml) | `CommandLine\|contains: 'whoami'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `- \whoami.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_whoami.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_whoami.yml) | `title: Whoami Execution`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_whoami.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_whoami.yml) | `description: Detects the execution of whoami, which is often used by attackers after exloitation / privilege escalation but rarely used by administrators`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_whoami.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_whoami.yml) | `Image\|endswith: '\whoami.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_whoami_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_whoami_anomaly.yml) | `title: Whoami Execution Anomaly`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_whoami_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_whoami_anomaly.yml) | `description: Detects the execution of whoami with suspicious parents or parameters`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_whoami_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_whoami_anomaly.yml) | `Image\|endswith: '\whoami.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_whoami_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_whoami_anomaly.yml) | `- 'whoami -all'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_whoami_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_whoami_anomaly.yml) | `- 'whoami /all'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_whoami_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_whoami_anomaly.yml) | `- 'whoami.exe -all'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_whoami_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_whoami_anomaly.yml) | `- 'whoami.exe /all'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_detection.yml) | `- '\whoami.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_whoami_as_system.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_whoami_as_system.yml) | `title: Run Whoami as SYSTEM`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_whoami_as_system.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_whoami_as_system.yml) | `description: Detects a whoami.exe executed by LOCAL SYSTEM. This may be a sign of a successful local privilege escalation.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_whoami_as_system.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_whoami_as_system.yml) | `Image\|endswith: '\whoami.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_whoami_priv.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_whoami_priv.yml) | `title: Run Whoami Showing Privileges`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_whoami_priv.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_whoami_priv.yml) | `description: Detects a whoami.exe executed with the /priv command line flag instructing the tool to show all current user privieleges. This is often used after a privilege escalation attempt. `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_whoami_priv.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_whoami_priv.yml) | `- https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/whoami`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_whoami_priv.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_whoami_priv.yml) | `Image\|endswith: '\whoami.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | Utilities and commands that acquire this information include <code>whoami</code>. In Mac and Linux, the currently logged in user can be identified with <code>w</code> and <code>who</code>.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | cmd.exe /C whoami | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1056.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1056.001/T1056.001.md) | whoami | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1056.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1056.001/T1056.001.md) | whoami; ausearch -i --start $(date +"%d/%m/%y %H:%M:%S") | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.003/T1070.003.md) | whoami | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1550.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1550.002/T1550.002.md) | \| command \| command to execute \| String \| whoami\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.003/T1562.003.md) | \| evil_command \| Command to run after shell history collection is disabled \| String \| whoami\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.003/T1562.003.md) | 4. whoami > recon.txt | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_lazarus_dec17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_lazarus_dec17.yar) | $x8 = "whoami /groups \| findstr /c:\"S-1-5-32-544\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | /* whoami & hostname */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $s1 = "whoami & hostname & ipconfig /all" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s5 = "WHOAMI" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_lnx_malware_indicators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_lnx_malware_indicators.yar) | $s5 = "whoami" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_p0wnshell.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_p0wnshell.yar) | $x1 = "Pshell.RunPSCommand(Whoami);" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_recon_indicators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_recon_indicators.yar) | $s4 = "whoami" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_suspicious_strings.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_suspicious_strings.yar) | $ = "whoami" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_webshells.yar) | $gen_bit_sus66 = "whoami" fullword wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s1 = "if(!$whoami)$whoami=exec(\"whoami\"); echo \"whoami :\".$whoami.\"<br>\";" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s17 = "if(!$whoami)$whoami=exec(\"whoami\");" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [55678719-e76e-4df9-92aa-10655bbd1cf4.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/collection/55678719-e76e-4df9-92aa-10655bbd1cf4.yml) | `cmd.exe /c "whoami /priv" >> C:\Windows\temp\history.log;`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [bd527b63-9f9e-46e0-9816-b8434d2b8989.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/discovery/bd527b63-9f9e-46e0-9816-b8434d2b8989.yml) | `whoami`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [c0da588f-79f0-4263-8998-7496b1a40596.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/discovery/c0da588f-79f0-4263-8998-7496b1a40596.yml) | `command: whoami`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## whoami



Displays user, group and privileges information for the user who is currently logged on to the local system. If used without parameters, **whoami** displays the current domain and user name.



### Syntax

```
whoami [/upn | /fqdn | /logonid]
whoami {[/user] [/groups] [/priv]} [/fo <Format>] [/nh]
whoami /all [/fo <Format>] [/nh]
```

#### Parameters

|Parameter|Description|
|---------|-----------|
|/upn|Displays the user name in user principal name (UPN) format.|
|/fqdn|Displays the user name in fully qualified domain name (FQDN) format.|
|/logonid|Displays the logon ID of the current user.|
|/user|Displays the current domain and user name and the security identifier (SID).|
|/groups|Displays the user groups to which the current user belongs.|
|/priv|Displays the security privileges of the current user.|
|/fo \<Format>|Specifies the output format. Valid values include:</br>**table** Displays output in a table. This is the default value.</br>**list** Displays output in a list.</br>**csv** Displays output in comma-separated value (CSV) format.|
|/all|Displays all information in the current access token, including the current user name, security identifiers (SID), privileges, and groups that the current user belongs to.|
|/nh|Specifies that the column header should not be displayed in the output. This is valid only for table and CSV formats.|
|/?|Displays help at the command prompt.|

### Examples

To display the domain and user name of the person who is currently logged on to this computer, type:
```
whoami
```
Output similar to the following appears:
```
DOMAIN1\administrator
```
To display all of the information in the current access token, type:
```
whoami /all
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


