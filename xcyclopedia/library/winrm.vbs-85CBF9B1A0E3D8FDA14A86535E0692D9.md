---
title: winrm.vbs | 
excerpt: What is winrm.vbs?
---

# winrm.vbs 

* File Path: `C:\Windows\system32\winrm.vbs`

## Hashes

Type | Hash
-- | --
MD5 | `85CBF9B1A0E3D8FDA14A86535E0692D9`
SHA1 | `695EAA69C8766E01720DEC322064EE968812F264`
SHA256 | `AD4AC01243A9775D26945CF742A06ACB03F34056FEE9576D646FF65617BF94F5`
SHA384 | `950B29341627C770036280988C608426D06D4E45F3FF891658367DC5438DFAEC251F1B9B50E700B525612C56C041FBCD`
SHA512 | `0EECAD4E71E37B7D387938388D30589D7AE737885EB14F83813F85F9B910AC339BA8E37A9418A050AB842E0298142A5061092A261D1CF1B4C0500E6A64E84C52`
SSDEEP | `3072:A5yO1lQ014Cet1ns3wflGsZcfwMQA5PGzb8h9:A591lF1UflGsZcfb`
PESHA1 | `695EAA69C8766E01720DEC322064EE968812F264`
PE256 | `AD4AC01243A9775D26945CF742A06ACB03F34056FEE9576D646FF65617BF94F5`

## Runtime Data

### Usage (stdout):
```cmhg
Windows Remote Management Command Line Tool

Windows Remote Management (WinRM) is the Microsoft implementation of 
the WS-Management protocol which provides a secure way to communicate 
with local and remote computers using web services.  

Usage:
  winrm OPERATION RESOURCE_URI [-SWITCH:VALUE [-SWITCH:VALUE] ...]
        [@{KEY=VALUE[;KEY=VALUE]...}]

For help on a specific operation:
  winrm g[et] -?        Retrieving management information.
  winrm s[et] -?        Modifying management information.
  winrm c[reate] -?     Creating new instances of management resources.
  winrm d[elete] -?     Remove an instance of a management resource.
  winrm e[numerate] -?  List all instances of a management resource.
  winrm i[nvoke] -?     Executes a method on a management resource.
  winrm id[entify] -?   Determines if a WS-Management implementation is
                        running on the remote machine.
  winrm quickconfig -?  Configures this machine to accept WS-Management
                        requests from other machines.
  winrm configSDDL -?   Modify an existing security descriptor for a URI.
  winrm helpmsg -?      Displays error message for the error code.

For help on related topics:
  winrm help uris       How to construct resource URIs.
  winrm help aliases    Abbreviations for URIs.
  winrm help config     Configuring WinRM client and service settings.
  winrm help certmapping Configuring client certificate access.
  winrm help remoting   How to access remote machines.
  winrm help auth       Providing credentials for remote access.
  winrm help input      Providing input to create, set, and invoke.
  winrm help switches   Other switches such as formatting, options, etc.
  winrm help proxy      Providing proxy information.

```

### Usage (stderr):
```cmhg
Error: Unknown operation name: ''

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\cscript.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/ad4ac01243a9775d26945cf742a06acb03f34056fee9576d646ff65617bf94f5/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\winrm.vbs](winrm.vbs-85CBF9B1A0E3D8FDA14A86535E0692D9.md) | 100

## Possible Misuse

*The following table contains possible examples of `winrm.vbs` being misused. While `winrm.vbs` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Winrm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Winrm.yml) | `Name: winrm.vbs`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Winrm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Winrm.yml) | `- Command: '%SystemDrive%\BypassDir\cscript //nologo %windir%\System32\winrm.vbs get wmicimv2/Win32_Process?Handle=4 -format:pretty'`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Winrm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Winrm.yml) | `- Path: C:\Windows\System32\winrm.vbs`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Winrm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Winrm.yml) | `- Path: C:\Windows\SysWOW64\winrm.vbs`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Winrm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Winrm.yml) | `- Link: https://posts.specterops.io/application-whitelisting-bypass-and-arbitrary-unsigned-code-execution-technique-in-winrm-vbs-c8c24fb40404`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


