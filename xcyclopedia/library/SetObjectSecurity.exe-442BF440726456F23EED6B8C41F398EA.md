---
title: SetObjectSecurity.exe | Sets security descriptor on securable objects
excerpt: What is SetObjectSecurity.exe?
---

# SetObjectSecurity.exe 

* File Path: `C:\SetObjectSecurity_10\SetObjectSecurity.exe`
* Description: Sets security descriptor on securable objects
* Comments: Created by Aaron Margosis


## Hashes

Type | Hash
-- | --
MD5 | `442BF440726456F23EED6B8C41F398EA`
SHA1 | `66B9D4409690C2E666DDBCC4BDDE74B42B256020`
SHA256 | `4AC425C1A8311B2445C7FC02427852B2449BA3F4AB6A2E0D85D8307F766E6C58`
SHA384 | `B8FB982B8DCE4491D2FDE266853EDB731CF14FF42602ED5011AE0F49954EA924FE21563FE9C98B58B8D3E70406833E0B`
SHA512 | `0ED635A6B8C45EC9B4E69697A3951DCEA1F5155107D1E00955393C99434F226EB13B99F4A602851886287C1930D854AD9590CA96654851355A0162B8F3F49FE0`
SSDEEP | `6144:XdYjY4m3r9JHumJh4GyPPzOxYFscbeek9i5AOALqly:tYjY4cJOmP4GyHzOxYFpkw2Lwy`
IMP | `4B274F3F7F2007198B9B6F4F63819E49`
PESHA1 | `262238398719738090DCDE54E28BFFEC74D8C08C`
PE256 | `4AC3F746949386F9AEA9FC5E0E6C90249E2FAF25C5A53F3AEB6F9F55D05FFFE9`

## Runtime Data

### Usage (stderr):
```cmhg

SetObjectSecurity - Sets security descriptor on securable objects
Version 1.0.2004.13001
Copyright (C) 2011-2020 Microsoft Corporation
Security Compliance Toolkit - https://www.microsoft.com/download/details.aspx?id=55319

Usage:
  SetObjectSecurity objType objName SDDL [-v|-q]
where
  objType = file, FILE, key, KEY, eventlog, printer, service, share, kobject,
            process, thread, or regbinary. (All-caps FILE or KEY uses pre-Windows
            2000 APIs to avoid applying inheritance.)
  objName = the name of the object (quoted if it contains spaces); or
            a Process ID (PID) or Thread ID (TID) in decimal if objType is
            "process" or "thread"; or
            a registry value name if objType is "regbinary".
  SDDL    = the security descriptor to apply, in Security Descriptor
            Definition Language.
  -v      = reports verbose diagnostic output to stderr (optional).
  -q      = Do not display the startup banner and copyright message. (optional).

Sets the security descriptor on the target object to that specified by SDDL;
if objType is "regbinary", outputs a .reg-compatible representation of
the security descriptor for a REG_BINARY registry value.

Specify the all-uppercase "FILE" and "KEY" to use the pre-Windows 2000
SetFileSecurity and RegSetKeySecurity APIs instead of Set[Named]SecurityInfo.
The older APIs apply the pre-Win2k inheritance model, which is good if you
don't want changes recursed through a directory or key hierarchy.

Use Sysinternals AccessChk.exe with -L to get SDDL from objects.

Object examples:
  file/FILE - absolute or relative path to local or remote file or folder; or
         a device name:
        C:\TestFolder\Sample.dat
        C:\TestFolder
        Sample.dat
        ..\Sample.dat
        \\ComputerName\Share\Sample.dat
        \\.\CdRom0
  key/KEY - accepts these forms for hive roots: HKLM, HKLM:, HKEY_LOCAL_MACHINE:
        HKLM\Software\MyApp
        HKCU:\Software\MyApp
        HKEY_CLASSES_ROOT\.abc
  eventlog:
        Application
        Microsoft-Windows-AppLocker/EXE and DLL
  printer:
        MyPrinter
        \\ComputerName\MyPrinter
  service:
        MyService
        \\ComputerName\MyService
  share:
        MyShare
        \\ComputerName\MyShare
  kobject - named instance of a semaphore, event, mutex, waitable timer,
            or file mapping; prepend "Global\" for global namespace objects:
        MyEvent
        Local\MyEvent  (same as "MyEvent")
        Global\MyEvent
  process - PID in decimal:
        3022
  thread - TID in decimal:
        2044
  regbinary: see example below

SDDL examples (these usually must be quoted in PowerShell):
  Admins+System, File-All-Access, protected, inherited by all children:
        D:P(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)
  The above with Users, File-Read:
        D:P(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;FR;;;BU)
  Interactive Users, Generic-All:
        D:(A;;GA;;;IU)
  Everyone full control but deny List permission:
        D:P(D;;CC;;;WD)(A;;FA;;;WD)
  Empty DACL (no access, no inherited ACEs):
        D:P
  Reset inherited DACL (empty DACL but unprotected):
        D:
  Inherited DACL, Low IL (Vista and newer):
        D:S:(ML;;NW;;;LW)
  Inherited DACL, remove IL (Vista and newer):
        D:S:
  NULL DACL (all access):
        ""
  Set owner to BUILTIN\Administrators, leave DACL intact:
        O:BA
  Set SACL to audit Success and Failure for everything for Everyone:
        S:(AU;SAFA;GA;;;WD)
  Note that event log security descriptors must explicitly specify an
  owner SID and a group SID. If you set event log permissions with
  either missing, owner will be set to BA and group SID to SY.

regbinary example:
  SetObjectSecurity.exe regbinary SrvsvcSec O:SYG:SYD:(A;;CCSDRCWDWO;;;BA)(A;;CCSDRCWDWO;;;SY)
outputs this, which can be incorporated into a .reg file:
  "SrvsvcSec"=hex:01,00,04,80,48,00,00,00,54,00,00,00,00,00,00,00,14,00,00,00,02,00,34,00,...

Example:
Restore Windows 10 default permissions on the C:\ root directory
(Make sure to use the ALL-CAPS "FILE" option to avoid propagating inherited permissions!)
  SetObjectSecurity.exe FILE C:\ "O:S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464D:PAI(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)(A;OICIIO;SDGXGWGR;;;AU)(A;;LC;;;AU)S:P(ML;OINPIO;NW;;;HI)"


```

### Loaded Modules:

Path |
-- |
C:\SetObjectSecurity_10\SetObjectSecurity.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001529B409F5056997588000000000152`
* Thumbprint: `711AF71DC4C4952C8ED65BB4BA06826ED3922A32`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SetObjectSecurity.exe
* Product Name: SetObjectSecurity
* Company Name: Microsoft Corporation
* File Version: 1.0.2004.13001
* Product Version: 1.0.200413001
* Language: English (United States)
* Legal Copyright: Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/4ac425c1a8311b2445c7fc02427852b2449ba3f4ab6a2e0d85d8307f766e6c58/detection/





MIT License. Copyright (c) 2020 Strontic.


