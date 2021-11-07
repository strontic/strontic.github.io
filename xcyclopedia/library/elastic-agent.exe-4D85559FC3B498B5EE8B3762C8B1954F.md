---
title: elastic-agent.exe | Agent manages other beats based on configuration provided.
excerpt: What is elastic-agent.exe?
---

# elastic-agent.exe 

* File Path: `C:\Program Files\Elastic\Agent\elastic-agent.exe`
* Description: Agent manages other beats based on configuration provided.
* Comments: commit=5ae799cb1c3c490c9a27b14cb463dc23696bc7d3


## Hashes

Type | Hash
-- | --
MD5 | `4D85559FC3B498B5EE8B3762C8B1954F`
SHA1 | `063497DA3D97A33BC856C8F375770780677DDADE`
SHA256 | `85666D9C2BB2D24CBE186899C0F6A4A350A8ABF3F9967F27A905F71FD7A28DE5`
SHA384 | `960171FB59AC3B6AE83D50C2B2CA9DC3C5CB55A90ECAB7A22266A09CCB3AE16945DE6143D1E9F371A123FD095DFA653B`
SHA512 | `D2819288AA3E285E2EF10D33A00E5D7D8C5923F3F816E942A62153DD024CA6EBD1A23437E9F6BE539B357778F7031A0021EDB91BE45DCBF94CDCF32BE1FED06E`
SSDEEP | `786432:MdCo6wCFbeLszyAAe/Me4PUG6hxJfukRa1bjK+P/FPgdkLtoWtDjHVO6jTxwlvkr:A/CBn7k`
IMP | `4D028340F95202AB4F8ED495DD117513`
PESHA1 | `757864A576477B7DFE08408C6A2995D235C6C417`
PE256 | `D6956EE801FA9AB76A68325A502B318A38FCAB27AEAF30D9CA7E8B77B0A31171`

## Runtime Data

### Usage (stdout):
```cmhg
Usage:
  elastic-agent [subcommand] [flags]
  elastic-agent [command]

Available Commands:
  enroll         Enroll the Agent into Fleet
  help           Help about any command
  inspect        Shows configuration of the agent
  install        Install Elastic Agent permanently on this system
  restart        Restart the currently running Elastic Agent daemon
  run            Start the elastic-agent.
  status         Status returns the current status of the running Elastic Agent daemon.
  uninstall      Uninstall permanent Elastic Agent from this system
  upgrade        Upgrade the currently running Elastic Agent to the specified version
  version        Display the version of the elastic-agent.
  watch          Watch watches Elastic Agent for failures and initiates rollback.

Flags:
  -c, --c string                     Configuration file, relative to path.config (default "elastic-agent.yml")
  -d, --d string                     Enable certain debug selectors
  -e, --e                            Log to stderr and disable syslog/file output
      --environment environmentVar   set environment being ran in (default default)
  -h, --help                         help for elastic-agent
      --path.config string           Config path is the directory Agent looks for its config file (default "C:\\Program Files\\Elastic\\Agent")
      --path.downloads string        Downloads path contains binaries Agent downloads
      --path.home string             Agent root path (default "C:\\Program Files\\Elastic\\Agent")
      --path.install string          Install path contains binaries Agent extracts
      --path.logs string             Logs path contains Agent log output (default "C:\\Program Files\\Elastic\\Agent")
  -v, --v                            Log at INFO level

Use "elastic-agent [command] --help" for more information about a command.

```

### Usage (stderr):
```cmhg
Error: unknown shorthand flag: 'l' in -lp
Usage:
  elastic-agent [subcommand] [flags]
  elastic-agent [command]

Available Commands:
  enroll         Enroll the Agent into Fleet
  help           Help about any command
  inspect        Shows configuration of the agent
  install        Install Elastic Agent permanently on this system
  restart        Restart the currently running Elastic Agent daemon
  run            Start the elastic-agent.
  status         Status returns the current status of the running Elastic Agent daemon.
  uninstall      Uninstall permanent Elastic Agent from this system
  upgrade        Upgrade the currently running Elastic Agent to the specified version
  version        Display the version of the elastic-agent.
  watch          Watch watches Elastic Agent for failures and initiates rollback.

Flags:
  -c, --c string                     Configuration file, relative to path.config (default "elastic-agent.yml")
  -d, --d string                     Enable certain debug selectors
  -e, --e                            Log to stderr and disable syslog/file output (default false)
      --environment environmentVar   set environment being ran in (default default)
  -h, --help                         help for elastic-agent
      --path.config string           Config path is the directory Agent looks for its config file (default "C:\\Program Files\\Elastic\\Agent")
      --path.downloads string        Downloads path contains binaries Agent downloads
      --path.home string             Agent root path (default "C:\\Program Files\\Elastic\\Agent")
      --path.install string          Install path contains binaries Agent extracts
      --path.logs string             Logs path contains Agent log output (default "C:\\Program Files\\Elastic\\Agent")
  -v, --v                            Log at INFO level

Use "elastic-agent [command] --help" for more information about a command.

unknown shorthand flag: 'l' in -lp

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Elastic\Agent\elastic-agent.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `0D6AC55C87AAE413A8D7E1303C483495`
* Thumbprint: `9F1AE2588723FD3E8F374C688D5A9FCE0EC50F44`
* Issuer: CN=DigiCert EV Code Signing CA (SHA2), OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="Elasticsearch, Inc.", O="Elasticsearch, Inc.", L=Mountain View, S=California, C=US, SERIALNUMBER=5195380, OID.2.5.4.15=Private Organization, OID.1.3.6.1.4.1.311.60.2.1.2=Delaware, OID.1.3.6.1.4.1.311.60.2.1.3=US

## File Metadata

* Original Filename: elastic-agent.exe
* Product Name: Elastic-Agent
* Company Name: Elastic
* File Version: 7.15.1
* Product Version: 7.15.1
* Language: Language Neutral
* Legal Copyright: Copyright Elastic, License Elastic License
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/85666d9c2bb2d24cbe186899c0f6a4a350a8abf3f9967f27a905f71fd7a28de5/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Elastic\Agent\data\elastic-agent-5ae799\elastic-agent.exe](elastic-agent.exe-4D85559FC3B498B5EE8B3762C8B1954F.md) | 100




MIT License. Copyright (c) 2020-2021 Strontic.


