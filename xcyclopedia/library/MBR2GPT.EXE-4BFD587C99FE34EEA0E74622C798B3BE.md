---
title: MBR2GPT.EXE | 
excerpt: What is MBR2GPT.EXE?
---

# MBR2GPT.EXE 

* File Path: `C:\Windows\system32\MBR2GPT.EXE`

## Hashes

Type | Hash
-- | --
MD5 | `4BFD587C99FE34EEA0E74622C798B3BE`
SHA1 | `39309FC62DADFFB36A6EE75DE6194121BE206728`
SHA256 | `5A54BB94F6756DEAFC0BF25C9ECA4E9DEA00DDC3AF293479BC7C3380F1BE30EA`
SHA384 | `D2E68351641BB899807167FAAA46B77286049524B9816FFD54BB368D3454E8099B13EB800E483D891D77D73979BEF5C0`
SHA512 | `F5EA0477C1C1683FC8C9F5FA7D5071FFC276F4CBF5F9B78DD9529CC20CA0905A60A123CD82BF5AC26F1B83BA0C732C5D9CA8B336275D799A8518179CB0C5ADC3`
SSDEEP | `24576:h6kHNg53pIE1OJmPJQ3IKxw9EdE+1Hii1:h6UGpAmcIJIZio`
IMP | `C1C0D14685E4D5EF5E2B7DD850598D65`
PESHA1 | `4200E0F03008A9761111A50FD877F34143E25C94`
PE256 | `E89BE625E0A0162DDEA0D0A0BFE8DCEA07045F2B698607E4752C202B0D1AA7E0`

## Runtime Data

### Usage (stdout):
```cmhg

Converts a disk from MBR to GPT partitioning without modifying or deleting data on the disk.

MBR2GPT.exe /validate|convert [/disk:<diskNumber>] [/logs:<logDirectory>] [/map:<source>=<destination>] [/allowFullOS]

Where:

 /validate
         - Validates that the selected disk can be converted
           without performing the actual conversion.

 /convert
         - Validates that the selected disk can be converted
           and performs the actual conversion.

 /disk:<diskNumber>
         - Specifies the disk number of the disk to be processed.
           If not specified, the system disk is processed.

 /logs:<logDirectory>
         - Specifies the directory for logging. By default logs
           are created in the %windir% directory.

 /map:<source>=<destination>
         - Specifies the GPT partition type to be used for a
           given MBR partition type not recognized by Windows.
           Multiple /map switches are allowed.

 /allowFullOS
         - Allows the tool to be used from the full Windows
           environment. By default, this tool can only be used
           from the Windows Preinstallation Environment.


```

### Usage (stderr):
```cmhg
Invalid argument: --help

Invalid arguments


```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MBR2GPT.EXE |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/5a54bb94f6756deafc0bf25c9eca4e9dea00ddc3af293479bc7c3380f1be30ea/detection





MIT License. Copyright (c) 2020-2021 Strontic.


