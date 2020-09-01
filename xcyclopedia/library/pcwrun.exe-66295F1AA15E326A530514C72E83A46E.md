---
title: pcwrun.exe | Program Compatibility Troubleshooter Invoker
---

# pcwrun.exe 

* File Path: `C:\windows\system32\pcwrun.exe`
* Description: Program Compatibility Troubleshooter Invoker

## Hashes

Type | Hash
-- | --
MD5 | `66295F1AA15E326A530514C72E83A46E`
SHA1 | `9444A51D1DD2E7A0A4FF90FFDD607A6A90697AA2`
SHA256 | `122BB4863EF62678E95A39F412B224816E20784B6D7132A7AB4036A2152966D5`
SHA384 | `2E231580E4C195D1409A78213E220415E7159441A572E3F559B497237345CCD7B8910EF69576D1EBD375636284DB4F83`
SHA512 | `2E11D08E7E82EB11D73F44D0341B8631EC88E7CDBCB5DF5761ADE4BB4EBA3433640A1748E2F155706FA51FF86FF4F6DC8FA691DC7EAF3377ACDAB8CE5E821F40`
SSDEEP | `192:v9bUq2ckx3+bWbraTgPyPvvnK7psJp5p3+/FZDVeKQy9m8WKgW:v95kxOyrGgPhup9uZDVe58WKgW`

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\SYSTEM32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\pcwrun.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\uxtheme.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: The file C:\windows\system32\pcwrun.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: pcwrun.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `pcwrun.exe` being misused. While `pcwrun.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `Name: Pcwrun.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `  - Command: Pcwrun.exe c:\temp\beacon.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwrun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Pcwrun.yml) | `  - Path: C:\Windows\System32\pcwrun.exe` | 



MIT License. Copyright (c) 2020 Strontic.


