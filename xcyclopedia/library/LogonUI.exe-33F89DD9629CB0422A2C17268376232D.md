---
title: LogonUI.exe | Windows Logon User Interface Host
excerpt: What is LogonUI.exe?
---

# LogonUI.exe 

* File Path: `C:\Windows\system32\LogonUI.exe`
* Description: Windows Logon User Interface Host

## Hashes

Type | Hash
-- | --
MD5 | `33F89DD9629CB0422A2C17268376232D`
SHA1 | `E1AB36E5C3C1453C592E2901330EB13C5D29B351`
SHA256 | `9358EF8CB7FB08581D74274005263BD8FA2E6E0FC443930B25FD345CF6CE9071`
SHA384 | `9FF778D98AD2E947032CB357E64CB3D9BB00B969DEF284B72907B9001403EFDCC255A409D6AAFA48E652E7E544C702E8`
SHA512 | `0FEE2E5626750AB6B15D82CD12F736790C4C703D02109D2704235186E3E85AAA22114D0E302626ABD960AECCCCFB03C11087668E8778D6523E4635400FB783F3`
SSDEEP | `192:i/1JmsaTvA/oN+wHKBCB0lJUKsRFdNEuZssvllWjUW:IKTvGq+eKB9JUFTZssvvWjUW`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\LogonUI.exe |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\user32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: logonui.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\LogonUI.exe](LogonUI.exe-DAA5CD4C86D5FCD6B3A215B34264FE78.md) | 60

## Possible Misuse

*The following table contains possible examples of `LogonUI.exe` being misused. While `LogonUI.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_seaduke_unit42.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_seaduke_unit42.yar) | $s2 = "LogonUI.exe" fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


