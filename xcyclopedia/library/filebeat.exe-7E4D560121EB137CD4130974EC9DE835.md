---
title: filebeat.exe | Filebeat sends log files to Logstash or directly to Elasticsearch.
excerpt: What is filebeat.exe?
---

# filebeat.exe 

* File Path: `C:\Program Files\Elastic\Agent\data\elastic-agent-5ae799\install\filebeat-7.15.1-windows-x86_64\filebeat.exe`
* Description: Filebeat sends log files to Logstash or directly to Elasticsearch.
* Comments: commit=5ae799cb1c3c490c9a27b14cb463dc23696bc7d3


## Hashes

Type | Hash
-- | --
MD5 | `7E4D560121EB137CD4130974EC9DE835`
SHA1 | `34BA04A66117665BC2823008188EB0C576303408`
SHA256 | `393BA05D660901E1034D4C7D0972E2EE3B7E59FD06B95E45AA13A6F04C099C91`
SHA384 | `8D5336B9709D1B613A3D5EED8F7629CB0B4952490C2D7F44294CE4738AC7B7CDEF391864E249C2CDE77CC7D69844D155`
SHA512 | `C5EE1EFD10EA4223832023D771E3AB09EBE981312D7F033DBF504550CC7A768D70CB9046F3DD199EF57C1276C3A690391725E7D364F1D96E510ED99C4D8E8D1D`
SSDEEP | `786432:w1uxLGubh717hREuxZEahUCodVIS7W4ouuXV5cS2MzK2dLp0DQaK7y/hqzyXReft:1Kut717tmy`
IMP | `3F0F065D59BD9A8EC45FE4CB67BE72E2`
PESHA1 | `91BE2562A34B35E525151FF41C8F9DFDDE20E05B`
PE256 | `071D7A06AE6C277064112055BCD3C2713386AA95004BB4FC563F1954163BF61D`

## Runtime Data

### Usage (stdout):
```cmhg
Usage:
  filebeat [flags]
  filebeat [command]

Available Commands:
  export      Export current config or index template
  generate    Generate Filebeat modules, filesets and fields.yml
  help        Help about any command
  keystore    Manage secrets keystore
  modules     Manage configured modules
  run         Run filebeat
  setup       Setup index template, dashboards and ML jobs
  test        Test config
  version     Show current version info

Flags:
  -E, --E setting=value              Configuration overwrite
  -M, --M setting=value              Module configuration overwrite
  -N, --N                            Disable actual publishing for testing
  -c, --c string                     Configuration file, relative to path.config (default "filebeat.yml")
      --cpuprofile string            Write cpu profile to file
  -d, --d string                     Enable certain debug selectors
  -e, --e                            Log to stderr and disable syslog/file output
      --environment environmentVar   set environment being ran in (default default)
  -h, --help                         help for filebeat
      --httpprof string              Start pprof http server
      --memprofile string            Write memory profile to this file
      --modules string               List of enabled modules (comma separated)
      --once                         Run filebeat only once until all harvesters reach EOF
      --path.config string           Configuration path
      --path.data string             Data path
      --path.home string             Home path
      --path.logs string             Logs path
      --strict.perms                 Strict permission checking on config files (default true)
      --system.hostfs string         Mount point of the host's filesystem for use in monitoring a host from within a container
  -v, --v                            Log at INFO level

Use "filebeat [command] --help" for more information about a command.

```

### Usage (stderr):
```cmhg
Error: unknown command "/?" for "filebeat"
Run 'filebeat --help' for usage.

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Elastic\Agent\data\elastic-agent-5ae799\install\filebeat-7.15.1-windows-x86_64\filebeat.exe |
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

* Original Filename: filebeat.exe
* Product Name: Filebeat
* Company Name: Elastic
* File Version: 7.15.1
* Product Version: 7.15.1
* Language: Language Neutral
* Legal Copyright: Copyright Elastic, License Elastic License
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/393ba05d660901e1034d4c7d0972e2ee3b7e59fd06b95e45aa13a6f04c099c91/detection


## Possible Misuse

*The following table contains possible examples of `filebeat.exe` being misused. While `filebeat.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [macos_disable_security_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/macos_disable_security_tools.yml) | `- 'filebeat'                                         # elastic log file shipper`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [macos_security_software_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/macos_security_software_discovery.yml) | `- 'filebeat'       # elastic log file shipper`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_security_software_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/process_creation/lnx_security_software_discovery.yml) | `- 'filebeat'       # elastic log file shipper`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-dns.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-dns.yml) | `- filebeat-*`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-filebeat.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-filebeat.yml) | `title: Elastic filebeat (from 7.x) index pattern and field mapping following Elastic Common Schema`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-filebeat.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-filebeat.yml) | `defaultindex: filebeat-*`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-proxy.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-proxy.yml) | `- filebeat-*`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-elastic-beats-implementation.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-elastic-beats-implementation.yml) | `title: Elastic Common Schema (ECS) implementation for Zeek using filebeat modules enabled based on version 7.6.1`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-elastic-beats-implementation.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-elastic-beats-implementation.yml) | `index: 'filebeat*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-zeek-elastic-beats-implementation.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-zeek-elastic-beats-implementation.yml) | `defaultindex: 'filebeat*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [elk-defaultindex-filebeat.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/elk-defaultindex-filebeat.yml) | `title: ELK default indices filebeat-*`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [elk-defaultindex-filebeat.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/elk-defaultindex-filebeat.yml) | `- filebeat-*`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [elk-defaultindex.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/elk-defaultindex.yml) | `title: ELK default indices logstash-* and filebeat-*`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [elk-defaultindex.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/elk-defaultindex.yml) | `- filebeat-*`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [filebeat-defaultindex.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/filebeat-defaultindex.yml) | `title: Elastic Filebeat default index name`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [filebeat-defaultindex.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/filebeat-defaultindex.yml) | `- filebeat-*`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | ps aux \| egrep 'Little\ Snitch\|CbOsxSensorService\|falcond\|nessusd\|santad\|CbDefense\|td-agent\|packetbeat\|filebeat\|auditbeat\|osqueryd\|BlockBlock\|LuLu' | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1518.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1518.001/T1518.001.md) | ps aux \| egrep 'falcond\|nessusd\|cbagentd\|td-agent\|packetbeat\|filebeat\|auditbeat\|osqueryd' | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


