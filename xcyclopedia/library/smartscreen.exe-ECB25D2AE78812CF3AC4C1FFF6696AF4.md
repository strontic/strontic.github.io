---
title: smartscreen.exe | Windows Defender SmartScreen
excerpt: What is smartscreen.exe?
---

# smartscreen.exe 

* File Path: `C:\Windows\system32\smartscreen.exe`
* Description: Windows Defender SmartScreen

## Hashes

Type | Hash
-- | --
MD5 | `ECB25D2AE78812CF3AC4C1FFF6696AF4`
SHA1 | `1CA1ABDC815C06D187E5BA84950715DF162EF4F7`
SHA256 | `F740FBA7B6791ABF3E000A6C4A04DDEE68D0A0722A3F5C0B44EB4E4D713BF7C9`
SHA384 | `3104230C2296629A9241D0465882EE46902757A034FF10D4E1F82B8052450D54C1238D75EC5DC1108B182FF815FF104D`
SHA512 | `6313AD8B68A1BA4CB4948A58F7395FE78F61A5018DE40FEC43A3EFEE1F4207B2579E02555CB3EEE3C60C529109A6293649C6D1F86CEB32040E2A32F66C2C3B2E`
SSDEEP | `49152:yf8eXaDPX9+m7rAIIqZA3IlvQpefUiHZDZdVeJ6aUFwNDVahv3nmUb:MI3VgNshv39b`
IMP | `C204EBCC4372F95F645AF852BFE02ADB`
PESHA1 | `C372CE6D7B1F734D951CCD05A89190C47FFD77FA`
PE256 | `00A098A9B958131AA6C7275D466E97E355D6D0ECC8BD5D34C8C863A99702B62F`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\MSASN1.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\system32\smartscreen.exe |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\user32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\WINTRUST.dll |
C:\Windows\SYSTEM32\wintypes.dll |
C:\Windows\System32\WS2_32.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: smartscreen.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 1/71
* VirusTotal Link: https://www.virustotal.com/gui/file/f740fba7b6791abf3e000a6c4a04ddee68d0a0722a3f5c0b44eb4e4d713bf7c9/detection/


## Possible Misuse

*The following table contains possible examples of `smartscreen.exe` being misused. While `smartscreen.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\smartscreen.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\smartscreen.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\smartscreen.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


