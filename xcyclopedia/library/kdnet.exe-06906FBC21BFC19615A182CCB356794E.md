---
title: kdnet.exe | Net debugging configuration tool
excerpt: What is kdnet.exe?
---

# kdnet.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\kdnet.exe`
* Description: Net debugging configuration tool

## Hashes

Type | Hash
-- | --
MD5 | `06906FBC21BFC19615A182CCB356794E`
SHA1 | `5ADCE7DE29CB8560450176FC8D7DCDC1F10BD82B`
SHA256 | `0DB5A4DCB3BE5ABE889B94A976C203B303CBB189C4DED0C97BE7B81BD1569EBC`
SHA384 | `72527D479C8AB0C26998840DC2B77F1E5683ED3140211CCBFA081DF10F1130CD95F9E1FEF9D0A3AB56575B2AA24A145C`
SHA512 | `D22D6961AA457C7E90F7063F9CBF0E3862F7F29F4ECFD7C5FB95C6686BCD37EFF23759FF21012DBE2A1858B4753DC7BE80705406C166BD430D73B31C28A53E55`
SSDEEP | `768:49ghuT6KCEY0rPY10TQ7wc1CPJYJlrdXpGbJ5S+mQKar7UvI+3o4tAKGdV5:ggoCEY0rQyRs35W5IQKAIvI+3ZVGd`
IMP | `5697E1DEEEC21ACCCAA8B1AE2CBE0EC6`
PESHA1 | `AD9C25A847BE2E8CCC4E5F3CBCF127C24A2C2CB8`
PE256 | `AD57848D21FF448B8314055700F3FF6ED108EF7393086B0A541C03259D7E4940`

## Runtime Data

### Usage (stdout):
```cmhg

kdnet.exe [debug_host] [debug_port]
  [debug_host] is the name of the host machine running the debugger.
  [debug_port] is the network port to use for debugging this machine.

kdnet.exe /xml

kdnet.exe /busparams [debug_device] [debug_host] [debug_port]
  [debug_device] is the busparams of the debug Device to configure.
  [debug_host] is the name of the host machine running the debugger.
  [debug_port] is the network port to use for debugging this machine.

When run without parameters, kdnet.exe identifies the NICs and USB3
controllers which support network debugging. When run with parameters
kdnet.exe enables network debugging using the specified information.
If [debug_port] is not specified then it will be set to a default
value of 5364.

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\kdnet.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: kdnet.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/0db5a4dcb3be5abe889b94a976c203b303cbb189c4ded0c97be7b81bd1569ebc/detection





MIT License. Copyright (c) 2020 Strontic.


