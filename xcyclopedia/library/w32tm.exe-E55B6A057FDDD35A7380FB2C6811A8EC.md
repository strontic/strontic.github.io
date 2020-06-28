---
title: w32tm.exe | Windows Time Service Diagnostic Tool
---

# w32tm.exe 

* File Path: `C:\Windows\SysWOW64\w32tm.exe`
* Description: Windows Time Service Diagnostic Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E55B6A057FDDD35A7380FB2C6811A8EC`
SHA1 | `82278696B965951D33693EDC5F0B99525027BDDE`
SHA256 | `8AB5C40895D73907B4F96BA73E73C5BF12A76A00965034A4146F85533B14F5C4`
SHA384 | `AE76E7A4DB93F7B25A6BBDA9E809963415054C7DC9C580BFA884BCB5E176BBF5F6DCFFAEFEDC4A0819373157A3D86056`
SHA512 | `F7C44CEDF76A8DAEF70AD49AE5E1A689D385404BC7D082A755B583FADA9322286877C76576969C7B1B74C17DD0C11A444CC0A97B7F07F7AEED5AD49D95ACF620`
SSDEEP | `1536:JkYpn6hGSs+J6+b2Y+q1cwg923QHDD1sXmQIIeaHWS0yZjXoHIdw:JN6hGSj3yiHAHDD1sXmQIKHV0yZDood`

## Runtime Data

### Usage (stdout):
```Batchfile
w32tm [/? | /register | /unregister ]
  ? - this help screen.
  register - register to run as a service and add default
    configuration to the registry.
  unregister - unregister service and remove all configuration
    information from the registry.

w32tm /monitor [/domain:<domain name>]
               [/computers:<name>[,<name>[,<name>...]]]
               [/threads:<num>] [/ipprotocol:<4|6>] [/nowarn]
  domain - specifies which domain to monitor. If no domain name
    is given, or neither the domain nor computers option is
    specified, the default domain is used. This option may be
    used more than once.
  computers - monitors the given list of computers. Computer
   names are separated by commas, with no spaces. If a name is
    prefixed with a '*', it is treated as an AD PDC. This option
    may be used more than once.
  threads - how many computers to analyze simultaneously. The
    default value is 3. Allowed range is 1-50.
  ipprotocol - specify the IP protocol to use. The default is
    to use whatever is available.
  nowarn - skip warning message.

w32tm /ntte <NT time epoch>
  Convert a NT system time, in (10^-7)s intervals from 0h 1-Jan 1601,
  into a readable format.

w32tm /ntpte <NTP time epoch>
  Convert an NTP time, in (2^-32)s intervals from 0h 1-Jan 1900, into
  a readable format.

w32tm /resync [/computer:<computer>] [/nowait] [/rediscover] [/soft]
  Tell a computer that it should resynchronize its clock as soon
  as possible, throwing out all accumulated error statistics.
  computer:<computer> - computer that should resync. If not
    specified, the local computer will resync.
  nowait - do not wait for the resync to occur;
    return immediately. Otherwise, wait for the resync to
    complete before returning.
  rediscover - redetect the network configuration and rediscover
    network sources, then resynchronize.
  soft - resync utilizing existing error statistics. Not useful,
    provided for compatibility.

w32tm /stripchart /computer:<target> [/period:<refresh>]
    [/dataonly] [/samples:<count>] [/packetinfo] [/ipprotocol:<4|6>] [/rdtsc]
  Display a strip chart of the offset between this computer and
  another computer.
  computer:<target> - the computer to measure the offset against.
  period:<refresh> - the time between samples, in seconds. The
    default is 2s
  dataonly - display only the data, no graphics.
  samples:<count> - collect <count> samples, then stop. If not
    specified, samples will be collected until Ctrl-C is pressed.
  packetinfo - print out NTP packet response message.
  ipprotocol - specify the IP protocol to use. The default is 
    to use whatever is available.
  rdtsc - display the TSC values and time offset data in CSV format.
    The output displays TSC and FILETIME values captured before the 
    NTP request is sent, TSC value after an NTP response is received
    along with NTP roundtrip and time offset values.


w32tm /config [/computer:<target>] [/update]
    [/manualpeerlist:<peers>] [/syncfromflags:<source>]
    [/LocalClockDispersion:<seconds>]
    [/reliable:(YES|NO)]
    [/largephaseoffset:<milliseconds>]
  computer:<target> - adjusts the configuration of <target>. If not
    specified, the default is the local computer.
  update - notifies the time service that the configuration has
    changed, causing the changes to take effect.
  manualpeerlist:<peers> - sets the manual peer list to <peers>,
    which is a space-delimited list of DNS and/or IP addresses.
    When specifying multiple peers, this switch must be enclosed in
    quotes.
  syncfromflags:<source> - sets what sources the NTP client should
    sync from. <source> should be a comma separated list of
    these keywords (not case sensitive):
      MANUAL - sync from peers in the manual peer list
      DOMHIER - sync from an AD DC in the domain hierarchy
      NO - sync from none
      ALL - sync from both manual and domain peers 
  LocalClockDispersion:<seconds> - configures the accuracy of the
    internal clock that w32time will assume when it can't acquire 
    time from its configured sources.  
  reliable:(YES|NO) - set whether this machine is a reliable time source.
    This setting is only meaningful on domain controllers.  
      YES - this machine is a reliable time service
      NO - this machine is not a reliable time service
  largephaseoffset:<milliseconds> - sets the time difference between 
    local and network time which w32time will consider a spike.  

w32tm /tz
  Display the current time zone settings.

w32tm /dumpreg [/subkey:<key>] [/computer:<target>]
  Display the values associated with a given registry key.
  The default key is HKLM\System\CurrentControlSet\Services\W32Time
    (the root key for the time service).
  subkey:<key> - displays the values associated with subkey <key> 
    of the default key.
  computer:<target> - queries registry settings for computer <target>.

w32tm /query [/computer:<target>] 
    {/source | /configuration | /peers | /status} 
    [/verbose]
  Display a computer's windows time service information.
  computer:<target> - query the information of <target>. If not
    specified, the default is the local computer.
  source: display the time source.
  configuration: display the configuration of run-time and where 
    the setting comes from. In verbose mode, display the undefined 
    or unused setting too.
  peers: display a list of peers and their status.
  status: display windows time service status.
  verbose: set the verbose mode to display more information.

w32tm /debug {/disable | {/enable /file:<name> /size:<bytes> /entries:<value>
    [/truncate]}}  
  Enable or disable local computer windows time service private log.
  disable: disable the private log.
  enable: enable the private log.
    file:<name> - specify the absolute filename.
    size:<bytes> - specify the maximum size for circular logging.
    entries:<value> - contains a list of flags, specified by number and
      separated by commas, that specify the types of information that 
      should be logged. Valid numbers are 0 to 300. A range of numbers 
      is valid, in addition to single numbers, such as 0-100,103,106. 
      Value 0-300 is for logging all information.
  truncate: truncate the file if it exists.

w32tm /leapseconds /getstatus [/verbose]
  Display the status of leap seconds on the local machine.
  verbose: Set the verbose mode to display more information.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: w32time.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\w32tm.exe](w32tm.exe-F314879F9C86A478D321FABDE0CC8FD1.md) | 35

## Possible Misuse

*The following table contains possible examples of `w32tm.exe` being misused. While `w32tm.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_remote_time_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_remote_time_discovery.yml) | `      - Image\|endswith: '\w32tm.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `                "description": "The system time is set and stored by the Windows Time Service within a domain to maintain time synchronization between systems and services in an enterprise network. (Citation: MSDN System Time) (Citation: Technet Windows Time Service)\n\nAn adversary may gather the system time and/or time zone from a local or remote system. This information may be gathered in a number of ways, such as with [Net](https://attack.mitre.org/software/S0039) on Windows by performing <code>net time \\\\hostname</code> to gather the system time on a remote system. The victim's time zone may also be inferred from the current system time or gathered by using <code>w32tm /tz</code>. (Citation: Technet Windows Time Service) The information could be useful for performing other techniques, such as executing a file with a [Scheduled Task](https://attack.mitre.org/techniques/T1053) (Citation: RSA EU12 They're Inside), or to discover locality information based on time zone to assist in victim targeting.",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1124.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1124/T1124.md) | System time information may be gathered in a number of ways, such as with [Net](https://attack.mitre.org/software/S0039) on Windows by performing <code>net time \\hostname</code> to gather the system time on a remote system. The victim's time zone may also be inferred from the current system time or gathered by using <code>w32tm /tz</code>. (Citation: Technet Windows Time Service) The information could be useful for performing other techniques, such as executing a file with a [Scheduled Task/Job](https://attack.mitre.org/techniques/T1053) (Citation: RSA EU12 They're Inside), or to discover locality information based on time zone to assist in victim targeting.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1124.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1124/T1124.md) | w32tm /tz | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


