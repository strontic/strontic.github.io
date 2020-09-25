---
title: autorunsc64.exe | Autostart program viewer
excerpt: What is autorunsc64.exe?
---

# autorunsc64.exe 

* File Path: `C:\SysinternalsSuite\autorunsc64.exe`
* Description: Autostart program viewer

## Hashes

Type | Hash
-- | --
MD5 | `F40FCC7D343A76F7B00B701B439F1C5F`
SHA1 | `E14C86D5BBF05FA82CCC9ACA6C065E8B29463981`
SHA256 | `A1EEB7CAAD26ABB9153B74BA7CE6C0DC9DDFF04283380DE342070256C0E59D1A`
SHA384 | `D75C084DFCB11E363027393A396426F050D8A4C37D39995DD3E800CD706E4A13B0C80C4B28A83F3D723C31931218FA2D`
SHA512 | `F2B1BA2D7D2F01AA49C17B5752F20C507537AA81996496F33924ED7208CEAB85DF8940462939728E45B70EE40488EC6247F0BF7468748FADF20F3ED2FE03B1C8`
SSDEEP | `6144:IqDxzYCo8O1zPD88Qnh5rg6BhJqtjBTv8qx+d2sVLgUR+Lkc9Xgxi79QbTIBX7XV:HDx8J8aNy/SNQs+xVLgPLqwB2wOi`
IMP | `820C4031FD7AF3EA8D4419803462C65D`
PESHA1 | `5B1E9BC8051409564099F6FFA81B4F79016E019E`
PE256 | `9B5993CC151945B69DF8C7E7E67A293C7C30B40C1F6C60F8B95C6116D4F3D815`

## Runtime Data

### Usage (stdout):
```cmhg

Sysinternals Autoruns v13.98 - Autostart program viewer
Copyright (C) 2002-2019 Mark Russinovich
Sysinternals - www.sysinternals.com


HKLM\System\CurrentControlSet\Control\Terminal Server\Wds\rdpwd\StartupPrograms
   rdpclip
     rdpclip
     RDP Clipboard Monitor
     Microsoft Corporation
     10.0.19041.423
     c:\windows\system32\rdpclip.exe
     7/24/1933 7:41 AM

HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon\Userinit
   C:\Windows\system32\userinit.exe
     C:\Windows\system32\userinit.exe
     Userinit Logon Application
     Microsoft Corporation
     10.0.19041.1
     c:\windows\system32\userinit.exe
     3/2/1950 2:07 AM

HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon\VmApplet
   SystemPropertiesPerformance.exe
     SystemPropertiesPerformance.exe
     Change Computer Performance Settings
     Microsoft Corporation
     10.0.19041.1
     c:\windows\system32\systempropertiesperformance.exe
     1/2/1968 1:18 AM

HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon\Shell
   explorer.exe
     explorer.exe
     Windows Explorer
     Microsoft Corporation
     10.0.19041.488
     c:\windows\explorer.exe
     5/5/1928 4:14 AM

HKLM\SYSTEM\CurrentControlSet\Control\SafeBoot\AlternateShell
   cmd.exe
     cmd.exe
     Windows Command Processor
     Microsoft Corporation
     10.0.19041.1
     c:\windows\system32\cmd.exe
     6/8/1986 8:13 AM

HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce
   Unattend0000000001{7C6A98B9-375C-4F62-AB1F-FB64F8598AA2}
     cmd /C wmic useraccount where "name='user'" set PasswordExpires=FALSE
     File not found: cmd
     

HKLM\SOFTWARE\Microsoft\Active Setup\Installed Components
   Microsoft Windows Media Player
     %SystemRoot%\system32\unregmp2.exe /ShowWMP
     Microsoft Windows Media Player Setup Utility
     Microsoft Corporation
     12.0.19041.1
     c:\windows\system32\unregmp2.exe
     11/8/1972 11:00 AM
   Themes Setup
     themeui.dll
     Windows Theme API
     Microsoft Corporation
     10.0.19041.1
     c:\windows\system32\themeui.dll
     9/26/1979 4:04 PM
   Microsoft Windows Media Player
     %SystemRoot%\system32\unregmp2.exe /FirstLogon
     Microsoft Windows Media Player Setup Utility
     Microsoft Corporation
     12.0.19041.1
     c:\windows\system32\unregmp2.exe
     11/8/1972 11:00 AM
   Windows Desktop Update
     shell32.dll
     Windows Shell Common Dll
     Microsoft Corporation
     10.0.19041.488
     c:\windows\system32\shell32.dll
     11/15/1920 4:31 PM
   Web Platform Customizations
     C:\Windows\System32\ie4uinit.exe -UserConfig
     IE Per-User Initialization Utility
     Microsoft Corporation
     11.0.19041.1
     c:\windows\system32\ie4uinit.exe
     11/6/1934 9:53 PM
   n/a
     C:\Windows\System32\Rundll32.exe C:\Windows\System32\mscories.dll,Install
     Microsoft .NET IE SECURITY REGISTRATION
     Microsoft Corporation
     2.0.50727.9149
     c:\windows\system32\mscories.dll
     10/24/2019 11:45 PM

HKLM\SOFTWARE\Wow6432Node\Microsoft\Active Setup\Installed Components
   Microsoft Windows Media Player
     %SystemRoot%\system32\unregmp2.exe /ShowWMP
     Microsoft Windows Media Player Setup Utility
     Microsoft Corporation
     12.0.19041.1
     c:\windows\syswow64\unregmp2.exe
     10/3/1955 9:34 AM
   Microsoft Windows Media Player
     %SystemRoot%\system32\unregmp2.exe /FirstLogon
     Microsoft Windows Media Player Setup Utility
     Microsoft Corporation
     12.0.19041.1
     c:\windows\syswow64\unregmp2.exe
     10/3/1955 9:34 AM
   n/a
     C:\Windows\SysWOW64\Rundll32.exe C:\Windows\SysWOW64\mscories.dll,Install
     Microsoft .NET IE SECURITY REGISTRATION
     Microsoft Corporation
     2.0.50727.9149
     c:\windows\syswow64\mscories.dll
     10/25/2019 4:48 AM

HKLM\Software\Microsoft\Windows NT\CurrentVersion\Windows\IconServiceLib
   IconCodecService.dll
     IconCodecService.dll
     Converts a PNG part of the icon to a legacy bmp icon
     Microsoft Corporation
     10.0.19041.1
     c:\windows\system32\iconcodecservice.dll
     3/14/1957 8:50 AM

```

### Usage (stderr):
```cmhg
Autorunsc shows programs configured to autostart during boot.

Usage: autorunsc [-a <*|bdeghiklmoprsw>] [-c|-ct] [-h] [-m] [-s] [-u] [-vt] [-o <output file>] [[-z <systemroot> <userprofile>] | [user]]]
  -a   Autostart entry selection:
     *    All.
     b    Boot execute.
     c    Codecs.
     d    Appinit DLLs.
     e    Explorer addons.
     g    Sidebar gadgets (Vista and higher)
     h    Image hijacks.
     i    Internet Explorer addons.
     k    Known DLLs.
     l    Logon startups (this is the default).
     m    WMI entries.
     n    Winsock protocol and network providers.
     o    Office addins.
     p    Printer monitor DLLs.
     r    LSA security providers.
     s    Autostart services and non-disabled drivers.
     t    Scheduled tasks.
     w    Winlogon entries.
  -c     Print output as CSV.
  -ct    Print output as tab-delimited values.
  -h     Show file hashes.
  -m     Hide Microsoft entries (signed entries if used with -s).
  -o     Write output to the specified file.
  -s     Verify digital signatures.
  -t     Show timestamps in normalized UTC (YYYYMMDD-hhmmss).
  -u     If VirusTotal check is enabled, show files that are unknown
         by VirusTotal or have non-zero detection, otherwise show only
         unsigned files.
  -x     Print output as XML.
  -v[rs] Query VirusTotal (www.virustotal.com) for malware based on file hash.
         Add 'r' to open reports for files with non-zero detection. Files
         reported as not previously scanned will be uploaded to VirusTotal
         if the 's' option is specified. Note scan results may not be
         available for five or more minutes.
  -vt    Before using VirusTotal features, you must accept
         VirusTotal terms of service. See:

              https://www.virustotal.com/en/about/terms-of-service/

         If you haven't accepted the terms and you omit this
         option, you will be interactively prompted.
  -z     Specifies the offline Windows system to scan.
  user   Specifies the name of the user account for which
         autorun items will be shown. Specify '*' to scan
         all user profiles.
  -nobanner
         Do not display the startup banner and copyright message.


```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\autorunsc64.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: autoruns.exe
* Product Name: Sysinternals autoruns
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 13.98
* Product Version: 13.98
* Language: English (United States)
* Legal Copyright: Copyright (C) 2002-2019 Mark Russinovich
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/a1eeb7caad26abb9153b74ba7ce6c0dc9ddff04283380de342070256c0e59d1a/detection/





MIT License. Copyright (c) 2020 Strontic.


