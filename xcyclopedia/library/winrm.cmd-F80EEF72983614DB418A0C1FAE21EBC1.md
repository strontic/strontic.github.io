---
title: winrm.cmd | 
excerpt: What is winrm.cmd?
---

# winrm.cmd 

* File Path: `C:\Windows\system32\winrm.cmd`

## Hashes

Type | Hash
-- | --
MD5 | `F80EEF72983614DB418A0C1FAE21EBC1`
SHA1 | `1E741199065307B6FE1F820F20E68EA99877A008`
SHA256 | `8323D52F2FF69FEDF02AB6238E9E3319D091E47A13AFD17ED0300AAD0C0A881E`
SHA384 | `9839F2EFF2A1043EAB5F99D5E02B2E6B941C683B5EFCB02ECC6AECDFA752A697CD31C651FDE483F0CE063AE04B620A4F`
SHA512 | `28E7A256E36FB550F7B49D427162BD18DB84EA6C8DBEC637F8D50AEC086A5522BBB2C5338B669FA80A5D82BA8094D3B815C97FA6FC9513774BBA88C1B2AA94F2`
SSDEEP | `3:72K+ELH+3FV:72KNHO`
PESHA1 | `1E741199065307B6FE1F820F20E68EA99877A008`
PE256 | `8323D52F2FF69FEDF02AB6238E9E3319D091E47A13AFD17ED0300AAD0C0A881E`

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
C:\Windows\system32\cmd.exe |
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
* VirusTotal Link: https://www.virustotal.com/gui/file/8323d52f2ff69fedf02ab6238e9e3319d091e47a13afd17ed0300aad0c0a881e/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\winrm.cmd](winrm.cmd-F80EEF72983614DB418A0C1FAE21EBC1.md) | 100




MIT License. Copyright (c) 2020-2021 Strontic.


