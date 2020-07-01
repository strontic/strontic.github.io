---
title: net1.exe | Net Command
---

# net1.exe 

* File Path: `C:\windows\system32\net1.exe`
* Description: Net Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `63DD4523677E62A73A8A7494DB321EA2`
SHA1 | `085E23DF67774ED89FD0215E1F144824F79F812B`
SHA256 | `C687157FD58EAA51757CDA87D06C30953A31F03F5356B9F5A9C004FA4BAD4BF5`
SHA384 | `B5A0B600BE1C83DFB2D8DCA07D5DC6FC0A98FE93C5B48A3153C0A89D4075BB36FA587BE3FE77F72B026FE98F4B3BF4FE`
SHA512 | `72F488E4FBBB169C96F3038638292549AC9E37F65DC0F709B2212B0AB678ADE01A813D8876693EC3D07CCD4A9D93195D3FA6BBBD5E5CBCD57BD944C91A28182D`
SSDEEP | `3072:d2ruQy5w+DoHcR1Bp4+dJjUHhYzcvmefyB2V7c86cscWE/37iJ3gmnK6HqF1A01p:d2RyoHAp4EJjUBYzcvXO2V7cfcscWE/9`

## Runtime Data

### Usage (stdout):
```Batchfile
The syntax of this command is:

NET HELP
command
     -or-
NET command /HELP

  Commands available are:

  NET ACCOUNTS             NET HELPMSG              NET STATISTICS
  NET COMPUTER             NET LOCALGROUP           NET STOP
  NET CONFIG               NET PAUSE                NET TIME
  NET CONTINUE             NET SESSION              NET USE
  NET FILE                 NET SHARE                NET USER
  NET GROUP                NET START                NET VIEW
  NET HELP

  NET HELP NAMES explains different types of names in NET HELP syntax lines.
  NET HELP SERVICES lists some of the services you can start.
  NET HELP SYNTAX explains how to read NET HELP syntax lines.
  NET HELP command | MORE displays Help one screen at a time.


```

### Usage (stderr):
```Batchfile
The syntax of this command is:

NET
    [ ACCOUNTS | COMPUTER | CONFIG | CONTINUE | FILE | GROUP | HELP |
      HELPMSG | LOCALGROUP | PAUSE | SESSION | SHARE | START |
      STATISTICS | STOP | TIME | USE | USER | VIEW ]

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: net1.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `net1.exe` being misused. While `net1.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_local_system_owner_account_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_local_system_owner_account_discovery.yml) | `            - '\net1.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_net_enum.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_net_enum.yml) | `            - '\net1.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_net_user_add.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_net_user_add.yml) | `            - '\net1.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_remote_time_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_remote_time_discovery.yml) | `            - '\net1.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `            - 'net1.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `            - '\net1.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_service_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_service_execution.yml) | `            - '\net1.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_service_stop.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_service_stop.yml) | `            - '\net1.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_net_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_net_execution.yml) | `            - '*\net1.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


