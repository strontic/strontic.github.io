---
title: splunk.exe | splunk Application
excerpt: What is splunk.exe?
---

# splunk.exe 

* File Path: `C:\Program Files\SplunkUniversalForwarder\bin\splunk.exe`
* Description: splunk Application

## Hashes

Type | Hash
-- | --
MD5 | `87A52CAA71B8734128F7CE6E299E50A5`
SHA1 | `CED35A2AEC7810CE1B24D186E1B4AE2CDBC3F892`
SHA256 | `6CB28705C1D87277335B9C8889DE44451407C49994622F46BB51561832207462`
SHA384 | `987EC2817F86F97F3AED8962515E1E4E358BAC2EE56453DB5E312B34D01FE802A8AB2FB2D767706FFDAE2A1547899A35`
SHA512 | `3B3456DD2233BB311CDC88F731D4FA969FF6695131527AE66744B09CD74CE8B5F5B59B1E47D900B31619D0CCDA24EAE6E2E2E01A3A9560AE4AB22DE7A1224AEB`
SSDEEP | `6144:JxHCzcSY0hNJoMM+AFe+5Zx6w+uZ1ptdoRa2tIG7qLwCp2kJ4QW8e+fvLb:JxHOcSzJoVFbtOEuInLZp2kJfxfvLb`
IMP | `88D6255781D526DD9C6D614B7EA689F4`
PESHA1 | `DF62BDE2849403C801B2440B6156CAF1D6F8403F`
PE256 | `1143D3E3E40A269A4FA04939F6BE048EEF42582A76183F043693D23BFB8F0697`

## Runtime Data

### Usage (stdout):
```cmhg



Welcome to Splunk's Command Line Interface (CLI).

    Type these commands for more help:

        help [command]             type a command name to access its help page
        help [object]              type an object name to access its help page
        help [topic]               type a topic keyword to get help on a topic
        help commands              display a full list of CLI commands
        help clustering            commands that can be used to configure the clustering setup
        help shclustering          commands that can be used to configure the Search Head Cluster setup
        help control, controls     tools to start, stop, manage Splunk processes
        help datastore             manage Splunk's local filesystem use
        help distributed           manage distributed configurations such as
                                   data cloning, routing, and distributed search
        help forwarding            manage deployments
        help input, inputs         manage data inputs
        help licensing             manage licenses for your Splunk server
        help settings              manage settings for your Splunk server
        help simple, cheatsheet    display a list of common commands with syntax
        help tools                 tools to help your Splunk server
        help search                help with Splunk searches

    Universal Parameters:

        The following parameters are usable by any command. For more details on each parameter, type "help [parameter]".
                
Syntax:

	[command] [object] [-parameter <value> | <value>]... [-uri][-auth]

      app        specify the app or namespace to run the command; for search, defaults to
                 the Search app

      auth       specify login credentials to execute commands that require you to be logged in

      owner      specify the owner/user context associated with an object; if not specified,
                 defaults to the currently logged in user

      uri        execute a command on any specified Splunk server. Use the
                 format: <ip>:<port>

      Note: Both IPv4 and IPv6 formats are supported for specifying an IP address, for example:
      127.0.0.1:80 or "[2001:db8::1]:80". By default, splunkd listens on IPv4 only. To enable
      IPv6 support, refer to the instructions in:
      http://docs.splunk.com/Documentation/Splunk/latest/Admin/ConfigureSplunkforIPv6 
                

Objects:

	None

Required Parameters:

	None

Optional Parameters:

	None

Examples:

	None

Type "help [command]" to get help with parameters for a specific command.

Complete documentation is available online at: http://docs.splunk.com/Documentation


```

### Loaded Modules:

Path |
-- |
C:\Program Files\SplunkUniversalForwarder\bin\splunk.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `014E132916D610BB301B22ABBD994616`
* Thumbprint: `B8B4F0D3FD0571E184DEBB76A1F6DB73F30FA233`
* Issuer: CN=DigiCert EV Code Signing CA (SHA2), OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="Splunk, Inc.", O="Splunk, Inc.", L=San Francisco, S=California, C=US, SERIALNUMBER=4109614, OID.2.5.4.15=Private Organization, OID.1.3.6.1.4.1.311.60.2.1.2=Delaware, OID.1.3.6.1.4.1.311.60.2.1.3=US

## File Metadata

* Original Filename: splunk.exe
* Product Name: splunk Application
* Company Name: Splunk Inc.
* File Version: 8.2.3
* Product Version: 8.2.3 (Build cd0848707637)
* Language: English (United States)
* Legal Copyright: Copyright (C) 2005-2021
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/6cb28705c1d87277335b9c8889de44451407c49994622f46bb51561832207462/detection


## Possible Misuse

*The following table contains possible examples of `splunk.exe` being misused. While `splunk.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_petitpotam_network_share.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_petitpotam_network_share.yml) | `- https://github.com/splunk/security_content/blob/0dd6de32de2118b2818550df9e65255f4109a56d/detections/endpoint/petitpotam_network_share_access_request.yml`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_petitpotam_susp_tgt_request.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_petitpotam_susp_tgt_request.yml) | `- https://github.com/splunk/security_content/blob/develop/detections/endpoint/petitpotam_suspicious_kerberos_tgt_request.yml`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_failed_logons_explicit_credentials.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_failed_logons_explicit_credentials.yml) | `- https://docs.splunk.com/Documentation/ESSOC/3.22.0/stories/UseCase#Active_directory_password_spraying`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_failed_logons_single_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_failed_logons_single_process.yml) | `- https://docs.splunk.com/Documentation/ESSOC/3.22.0/stories/UseCase#Active_directory_password_spraying`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_failed_logons_single_source_kerberos.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_failed_logons_single_source_kerberos.yml) | `- https://docs.splunk.com/Documentation/ESSOC/3.22.0/stories/UseCase#Active_directory_password_spraying`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_failed_logons_single_source_kerberos2.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_failed_logons_single_source_kerberos2.yml) | `- https://docs.splunk.com/Documentation/ESSOC/3.22.0/stories/UseCase#Active_directory_password_spraying`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_failed_logons_single_source_kerberos3.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_failed_logons_single_source_kerberos3.yml) | `- https://docs.splunk.com/Documentation/ESSOC/3.22.0/stories/UseCase#Active_directory_password_spraying`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_failed_logons_single_source_ntlm.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_failed_logons_single_source_ntlm.yml) | `- https://docs.splunk.com/Documentation/ESSOC/3.22.0/stories/UseCase#Active_directory_password_spraying`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_failed_logons_single_source_ntlm2.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_failed_logons_single_source_ntlm2.yml) | `- https://docs.splunk.com/Documentation/ESSOC/3.22.0/stories/UseCase#Active_directory_password_spraying`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_failed_remote_logons_single_source.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_failed_remote_logons_single_source.yml) | `- https://docs.splunk.com/Documentation/ESSOC/3.22.0/stories/UseCase#Active_directory_password_spraying`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_rclone_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/sysmon_rclone_execution.yml) | `- https://www.splunk.com/en_us/blog/security/darkside-ransomware-splunk-threat-update-and-detections.html`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [file_event_mal_adwind.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/file_event_mal_adwind.yml) | `- https://www.first.org/resources/papers/conf2017/Advanced-Incident-Detection-and-Threat-Hunting-using-Sysmon-and-Splunk.pdf`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mal_adwind.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mal_adwind.yml) | `- https://www.first.org/resources/papers/conf2017/Advanced-Incident-Detection-and-Threat-Hunting-using-Sysmon-and-Splunk.pdf`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_net_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_net_execution.yml) | `- Will need to be tuned. If using Splunk, I recommend \| stats count by Computer,CommandLine following the search for easy hunting by computer/CommandLine.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rclone_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rclone_execution.yml) | `- https://www.splunk.com/en_us/blog/security/darkside-ransomware-splunk-threat-update-and-detections.html`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_wmi_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_wmi_execution.yml) | `- If using Splunk, we recommend \| stats count by Computer,CommandLine following for easy hunting by Computer/CommandLine`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [registry_event_mal_adwind.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/registry_event_mal_adwind.yml) | `- https://www.first.org/resources/papers/conf2017/Advanced-Incident-Detection-and-Threat-Hunting-using-Sysmon-and-Splunk.pdf`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_remote_schtask.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/win_remote_schtask.yml) | `#   This logic would be similar to the Splunk 'Transaction' operator which groups related events over a timeframe. `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_remote_service.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/win_remote_service.yml) | `#   This logic would be similar to the Splunk 'Transaction' operator which groups related events over a timeframe. `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [crowdstrike.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/crowdstrike.yml) | `title: Splunk used in Falcon Portal`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [splunk-windows-index.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/splunk-windows-index.yml) | `title: Splunk Windows index and EventID field mapping`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [splunk-windows-index.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/splunk-windows-index.yml) | `- splunk`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [splunk-windows.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/splunk-windows.yml) | `title: Splunk Windows log source conditions`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [splunk-windows.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/splunk-windows.yml) | `- splunk`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [splunk-windows.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/splunk-windows.yml) | `# This also supports custom splunk macros, just like they are written in splunk (i.e. as `macro`), minding that it has to be written inside the string quotes here.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [splunk-zeek.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/splunk-zeek.yml) | `title: Splunk Zeek sourcetype mappings`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [splunk-zeek.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/splunk-zeek.yml) | `- splunk`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


