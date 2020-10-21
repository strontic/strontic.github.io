---
title: sc.exe | Service Control Manager Configuration Tool
excerpt: What is sc.exe?
---

# sc.exe 

* File Path: `C:\Windows\SysWOW64\sc.exe`
* Description: Service Control Manager Configuration Tool

## Hashes

Type | Hash
-- | --
MD5 | `293A38365BEE67829AE093D10BF4BC85`
SHA1 | `AFCCEB4DB08190D15739D0D369ABE0F66B99557C`
SHA256 | `604492B8398751F0798079CEC26D674C125885F55B2BEAB1BC484EBDB723BB63`
SHA384 | `F68F7A7539AC69B6F8A0ED2E4B2732EE8A71780F51941A7F28C0C83FF51172BCE2FE6DD83AD118451F2A5D64CAB7C3F6`
SHA512 | `F8EBD11D3DF291889FAA38BEF19DFDE877B040D7F279CB20C6CABE0A9D422B2F6BE5872B0C9D330C0286115A99C37769615083C4D573EC4C0F57031519BD385B`
SSDEEP | `1536:VpFLNeH99G055y3em18biVPOvOTjbVTFNXo4HBxP/HOTnOsJ19XW4D8rjkQytP1F:HFLQH99G055y3em18biVPOvOTjbVTFNi`
IMP | `B037D0ADB81BF9CFC651DE01742089F1`
PESHA1 | `A43608306923FA12F6B53D2B2FC79EE111868FDA`
PE256 | `61F6AB4E6B1C1EBE8302EB136966D33145E846EDBDB9997643EC7BD05C654707`

## Runtime Data

### Usage (stdout):
```cmhg

ERROR:  Unrecognized command

DESCRIPTION:
        SC is a command line program used for communicating with the
        Service Control Manager and services.
USAGE:
        sc <server> [command] [service name] <option1> <option2>...


        The option <server> has the form "\\ServerName"
        Further help on commands can be obtained by typing: "sc [command]"
        Commands:
          query-----------Queries the status for a service, or
                          enumerates the status for types of services.
          queryex---------Queries the extended status for a service, or
                          enumerates the status for types of services.
          start-----------Starts a service.
          pause-----------Sends a PAUSE control request to a service.
          interrogate-----Sends an INTERROGATE control request to a service.
          continue--------Sends a CONTINUE control request to a service.
          stop------------Sends a STOP request to a service.
          config----------Changes the configuration of a service (persistent).
          description-----Changes the description of a service.
          failure---------Changes the actions taken by a service upon failure.
          failureflag-----Changes the failure actions flag of a service.
          sidtype---------Changes the service SID type of a service.
          privs-----------Changes the required privileges of a service.
          managedaccount--Changes the service to mark the service account 
                          password as managed by LSA.
          qc--------------Queries the configuration information for a service.
          qdescription----Queries the description for a service.
          qfailure--------Queries the actions taken by a service upon failure.
          qfailureflag----Queries the failure actions flag of a service.
          qsidtype--------Queries the service SID type of a service.
          qprivs----------Queries the required privileges of a service.
          qtriggerinfo----Queries the trigger parameters of a service.
          qpreferrednode--Queries the preferred NUMA node of a service.
          qmanagedaccount-Queries whether a services uses an account with a 
                          password managed by LSA.
          qprotection-----Queries the process protection level of a service.
          quserservice----Queries for a local instance of a user service template.
          delete----------Deletes a service (from the registry).
          create----------Creates a service. (adds it to the registry).
          control---------Sends a control to a service.
          sdshow----------Displays a service's security descriptor.
          sdset-----------Sets a service's security descriptor.
          showsid---------Displays the service SID string corresponding to an arbitrary name.
          triggerinfo-----Configures the trigger parameters of a service.
          preferrednode---Sets the preferred NUMA node of a service.
          GetDisplayName--Gets the DisplayName for a service.
          GetKeyName------Gets the ServiceKeyName for a service.
          EnumDepend------Enumerates Service Dependencies.

        The following commands don't require a service name:
        sc <server> <command> <option>
          boot------------(ok | bad) Indicates whether the last boot should
                          be saved as the last-known-good boot configuration
          Lock------------Locks the Service Database
          QueryLock-------Queries the LockStatus for the SCManager Database
EXAMPLE:
        sc start MyService


QUERY and QUERYEX OPTIONS:
        If the query command is followed by a service name, the status
        for that service is returned.  Further options do not apply in
        this case.  If the query command is followed by nothing or one of
        the options listed below, the services are enumerated.
    type=    Type of services to enumerate (driver, service, userservice, all)
             (default = service)
    state=   State of services to enumerate (inactive, all)
             (default = active)
    bufsize= The size (in bytes) of the enumeration buffer
             (default = 4096)
    ri=      The resume index number at which to begin the enumeration
             (default = 0)
    group=   Service group to enumerate
             (default = all groups)

SYNTAX EXAMPLES
sc query                - Enumerates status for active services & drivers
sc query eventlog       - Displays status for the eventlog service
sc queryex eventlog     - Displays extended status for the eventlog service
sc query type= driver   - Enumerates only active drivers
sc query type= service  - Enumerates only Win32 services
sc query state= all     - Enumerates all services & drivers
sc query bufsize= 50    - Enumerates with a 50 byte buffer
sc query ri= 14         - Enumerates with resume index = 14
sc queryex group= ""    - Enumerates active services not in a group
sc query type= interact - Enumerates all interactive services
sc query type= driver group= NDIS     - Enumerates all NDIS drivers


```

### Child Processes:
powershell.exe

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\sc.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/604492b8398751f0798079cec26d674c125885f55b2beab1bc484ebdb723bb63/detection/


## Possible Misuse

*The following table contains possible examples of `sc.exe` being misused. While `sc.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\sc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- sc.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_new_service_creation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_new_service_creation.yml) | `- Image\|endswith: '\sc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_service_stop.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_service_stop.yml) | `- '\sc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_service_path_modification.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_service_path_modification.yml) | `Image\|endswith: '\sc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_using_sc_to_change_sevice_image_path_by_non_admin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_using_sc_to_change_sevice_image_path_by_non_admin.yml) | `description: Detection of sc.exe utility spawning by user with Medium integrity level to change service ImagePath or FailureCommand` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_using_sc_to_change_sevice_image_path_by_non_admin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_using_sc_to_change_sevice_image_path_by_non_admin.yml) | `Image\|endswith: '\sc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Sc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Sc.yml) | `Name: Sc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Sc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Sc.yml) | `- Path: C:\Windows\System32\sc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Sc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Sc.yml) | `- Path: C:\Windows\SysWOW64\sc.exe` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | Stops a specified service using the sc.exe command. Upon execution, if the spooler service was running infomration will be displayed saying | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | sc.exe stop #{service_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | sc.exe start #{service_name} >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.003/T1543.003.md) | <blockquote>Adversaries may create or modify Windows services to repeatedly execute malicious payloads as part of persistence. When Windows boots up, it starts programs or applications called services that perform background system functions.(Citation: TechNet Services) Windows service configuration information, including the file path to the service's executable or recovery programs/commands, is stored in the Windows Registry. Service configurations can be modified using utilities such as sc.exe and [Reg](https://attack.mitre.org/software/S0075).  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.003/T1543.003.md) | Upon successful execution, powershell will download `AtomicService.exe` from github. cmd.exe will spawn sc.exe which will create and start the service. Results will output via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.003/T1543.003.md) | sc.exe create #{service_name} binPath= #{binary_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.003/T1543.003.md) | sc.exe start #{service_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.003/T1543.003.md) | sc.exe stop #{service_name} >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.003/T1543.003.md) | sc.exe delete #{service_name} >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if(sc.exe query sysmon \| findstr sysmon) { exit 0 } else { exit 1 }  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | sc.exe config #{service_name} start= disabled | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | sc.exe config #{service_name} start= auto >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1563.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1563.002/T1563.002.md) | sc.exe create sesshijack binpath= "cmd.exe /k tscon #{Session_ID} /dest:#{Destination_ID}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1563.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1563.002/T1563.002.md) | sc.exe delete sesshijack >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | <blockquote>Adversaries may abuse the Windows service control manager to execute malicious commands or payloads. The Windows service control manager (<code>services.exe</code>) is an interface to manage and manipulate services.(Citation: Microsoft Service Control Manager) The service control manager is accessible to users via GUI components as well as system utilities such as <code>sc.exe</code> and [Net](https://attack.mitre.org/software/S0039). | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | Upon successful execution, cmd.exe create a new service using sc.exe create that will start powershell.exe to create a new file `art-marker.txt` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | sc.exe create #{service_name} binPath= "#{executable_command}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | sc.exe start #{service_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | sc.exe delete #{service_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.011/T1574.011.md) | <blockquote>Adversaries may execute their own malicious payloads by hijacking the Registry entries used by services. Adversaries may use flaws in the permissions for registry to redirect from the originally specified executable to one that they control, in order to launch their own code at Service start.  Windows stores local service configuration information in the Registry under <code>HKLM\SYSTEM\CurrentControlSet\Services</code>. The information stored under a service's Registry keys can be manipulated to modify a service's execution parameters through tools such as the service controller, sc.exe,  [PowerShell](https://attack.mitre.org/techniques/T1059/001), or [Reg](https://attack.mitre.org/software/S0075). Access to Registry keys is controlled through Access Control Lists and permissions. (Citation: Registry Key Security) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_ransom_robinhood.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_ransom_robinhood.yar) | $s4 = "sc.exe stop SQLAgent$SQLEXPRESS" nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_empire.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_empire.yar) | $s1 = "$Result = sc.exe config $($TargetService.Name) binPath= $OriginalPath" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_empire.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_empire.yar) | $s2 = "$Result = sc.exe pause $($TargetService.Name)" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


