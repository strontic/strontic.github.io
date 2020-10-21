---
title: winhup.exe | An EC2 bootstrapper for CloudFormation
excerpt: What is winhup.exe?
---

# winhup.exe 

* File Path: `C:\Program Files\Amazon\cfn-bootstrap\winhup.exe`
* Description: An EC2 bootstrapper for CloudFormation

## Hashes

Type | Hash
-- | --
MD5 | `48FE04D8A6525EBF39345C41CE0D6842`
SHA1 | `6E7BA1E29BC808A746CCF11D447FA8BF1AE99A78`
SHA256 | `9612C7D48A0806ACE6216CC69F3D0BC2A0CD16B9CEBDEDF5A0BAE1A007330D3E`
SHA384 | `544476727EF7A908D3EF34C3B2053FF9C10B591F5419A473F9A8291B2F73423647D6B1600CAB1F9632BCEBFB46F00259`
SHA512 | `4937468B19095EBB568D565263F890000D85FC24FC3A6A54F0B0510B5A16C218F67ADC88C16512FE76813409726BE7257B942E4C9997216D8779B821387BA13A`
SSDEEP | `384:aytbeSasdkBKuZu/snjycBghtrYh8eknggMl4gKg67WhtrjHqC3V57peKbQUE7eT:1vmBjHgTsfkngjjjHV57peUWX7knV/6A`
IMP | `8571CAA1C1E39E800CB623F4B1D233D9`
PESHA1 | `7ED616869B4969DB0BE0A498822388AB9EB646AF`
PE256 | `82CEF25A25EA6184D30F7301D427EC84266128ACF9576B9717BF956453264BC8`

## Runtime Data

### Usage (stdout):
```cmhg
Services are supposed to be run by the system after they have been installed.
These command line options are available for (de)installation:
	-help
	-install
	-remove
	-auto
	-disabled
	-interactive
	-user: <arg>
	-password: <arg>

Connecting to the Service Control Manager

```

### Usage (stderr):
```cmhg
Traceback (most recent call last):
  File "boot_service.py", line 173, in <module>
pywintypes.error: (1063, 'StartServiceCtrlDispatcher', 'The service process could not connect to the service controller.')

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Amazon\cfn-bootstrap\PYTHON27.DLL |
C:\Program Files\Amazon\cfn-bootstrap\winhup.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\SYSTEM32\apphelp.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\cryptsp.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\windows.storage.dll |
C:\Windows\WinSxS\amd64_microsoft.vc90.crt_1fc8b3b9a1e18e3b_9.0.30729.9518_none_08e07c8fa840efbe\MSVCR90.dll |


## Signature

* Status: The file C:\Program Files\Amazon\cfn-bootstrap\winhup.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: winhup.exe
* Product Name: aws-cfn-bootstrap
* Company Name: 
* File Version: 1.4
* Product Version: 1.4
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/9612c7d48a0806ace6216cc69f3d0bc2a0cd16b9cebdedf5a0bae1a007330d3e/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Amazon\cfn-bootstrap\cfn-elect-cmd-leader.exe](cfn-elect-cmd-leader.exe-381A030E578E8285BF1F462CC036E4D0.md) | 86
[C:\Program Files\Amazon\cfn-bootstrap\cfn-get-metadata.exe](cfn-get-metadata.exe-AB00AE1FE4E4943F9CCB91C01E1C4F35.md) | 86
[C:\Program Files\Amazon\cfn-bootstrap\cfn-hup.exe](cfn-hup.exe-FC05F4A7EA27BD5F73BE9016B8F70BD9.md) | 61
[C:\Program Files\Amazon\cfn-bootstrap\cfn-init.exe](cfn-init.exe-5E0F3A7E9C8313FA6889B824EAB63614.md) | 86
[C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-event.exe](cfn-send-cmd-event.exe-6569521FE751E682B6AF18F84D544079.md) | 65
[C:\Program Files\Amazon\cfn-bootstrap\cfn-send-cmd-result.exe](cfn-send-cmd-result.exe-3F9A3602A5CC3B5C8C8011A9DCB76006.md) | 90
[C:\Program Files\Amazon\cfn-bootstrap\cfn-signal.exe](cfn-signal.exe-DDB912A9A7741BCFC2DB4C1DDE995AB1.md) | 65




MIT License. Copyright (c) 2020 Strontic.


