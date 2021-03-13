---
title: OfficeClickToRun.exe | Microsoft Office Click-to-Run IntegratedOfficeExe
excerpt: What is OfficeClickToRun.exe?
---

# OfficeClickToRun.exe 

* File Path: `C:\Program Files\Microsoft Office 15\ClientX64\OfficeClickToRun.exe`
* Description: Microsoft Office Click-to-Run IntegratedOfficeExe

## Hashes

Type | Hash
-- | --
MD5 | `2864C8B005A6414E2FA9B06C1E089DCC`
SHA1 | `3041FBD63AE570B537C38A315050C06AA566362F`
SHA256 | `78425E626D0830C35EE05307AD6958055493ACEBBB8A2548BA3DE4AF6D6378F7`
SHA384 | `007CDBC18CD4C93253FF2502FFD5B45554D8114ED4B058438632BAD9B8DD4240546E14CE769A81F94EEB46D6E279ABE5`
SHA512 | `BF8FD10E7D517C183F0273B9B997C57C552154E8E65889A4277DEA81C3D8104EEBF12B4E5B179E95F5F261B5BE01D3DB13B7C46B8D723D951FBDAA0B15EC70C3`
SSDEEP | `49152:ZQIlquu1Gn1jKm4ptlQzJWwbwLqd3ZrzsTfov3/euNw5TScWwJb9DN5J8NRV3TH/:ZQvGAdlCEL8c/bRNw5CO`
IMP | `D3751AB33B3858F3B8B8D3275495BABA`
PESHA1 | `4DDBD04BC1016AE074C0F6BB19173697DCCF6BF6`
PE256 | `41053CDE0FF7B1B3A6FE8FEFC72C2315A556B3B783054C29FF3AB43B333E6990`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Program Files\Microsoft Office 15\ClientX64\OfficeClickToRun.exe |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CE7C9ACE7D905ED2B70000000002CE`
* Thumbprint: `B10607FB914700B40F794610850C1DE0A21566C1`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: IntegratedOffice.exe
* Product Name: Microsoft Office
* Company Name: Microsoft Corporation
* File Version: 16.0.12527.20470
* Product Version: 16.0.12527.20470
* Language: Language Neutral
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/78425e626d0830c35ee05307ad6958055493acebbb8a2548ba3de4af6d6378f7/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Common Files\microsoft shared\ClickToRun\IntegratedOffice.exe](IntegratedOffice.exe-2864C8B005A6414E2FA9B06C1E089DCC.md) | 100
[C:\Program Files\Microsoft Office 15\ClientX64\IntegratedOffice.exe](IntegratedOffice.exe-2864C8B005A6414E2FA9B06C1E089DCC.md) | 100

## Possible Misuse

*The following table contains possible examples of `OfficeClickToRun.exe` being misused. While `OfficeClickToRun.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") source="WinEventLog:Microsoft-Windows-Sysmon/Operational" schtasks.exe CommandLine=*Create* ParentImage!=*\\OfficeClicktoRun.exe \| stats values(CommandLine) by Computer` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") source="WinEventLog:Microsoft-Windows-Sysmon/Operational" schtasks.exe CommandLine=*Create* ParentImage!=*\\OfficeClicktoRun.exe \| table Computer, User, CommandLine, _time` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


