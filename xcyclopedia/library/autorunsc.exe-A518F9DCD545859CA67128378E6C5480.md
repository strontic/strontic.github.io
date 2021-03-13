---
title: autorunsc.exe | Autostart program viewer
excerpt: What is autorunsc.exe?
---

# autorunsc.exe 

* File Path: `C:\SysinternalsSuite\autorunsc.exe`
* Description: Autostart program viewer

## Hashes

Type | Hash
-- | --
MD5 | `A518F9DCD545859CA67128378E6C5480`
SHA1 | `CCFE528A8C2834EC07318925B1E4F180E5EFDD9A`
SHA256 | `710328EE28126E8C4755C2371AEEF2A0EF0626F4FB73A42D15271C8BA6C89BAC`
SHA384 | `FAD61F890D3FE11EB7B6DC4F43FDC0769188336D87048AE4FF16818F197CCA86D788FA03E36F34217202774E766CA2EA`
SHA512 | `AFB2BB552592FAA68672A3EB53F3E5D8895BD47E9B7251D96B18EEE27552083C81A5D7BEBB21C6EA602A97910059C4C3DEF567F013A73D7129E503F9213D5C6A`
SSDEEP | `12288:czZQxkm+YQuBcpIz6fZ0+WVbnyoVZVWYs8EwOGY798R46:clQxAMBcOzGDoLUYDxO5iv`
IMP | `48EF03BECDB691242DB40EC056A3DDBB`
PESHA1 | `B197435694B0F88AC2AF553219E6034495A54AE3`
PE256 | `7A10DAAF616950D10E372834E8B0616185867B620C2DA34CDC863FF54E19CFB4`

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
C:\SysinternalsSuite\autorunsc.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/710328ee28126e8c4755c2371aeef2a0ef0626f4fb73a42d15271c8ba6c89bac/detection/


## Possible Misuse

*The following table contains possible examples of `autorunsc.exe` being misused. While `autorunsc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[stockpile](https://github.com/mitre/stockpile) | [7a6ba833-de40-466a-8969-5c37b13603e0.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/7a6ba833-de40-466a-8969-5c37b13603e0.yml) | `"autorunsc",`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


