---
title: cliconfg.exe | SQL Client Configuration Utility EXE
---

# cliconfg.exe 

* File Path: `C:\windows\SysWOW64\cliconfg.exe`
* Description: SQL Client Configuration Utility EXE

## Screenshot

![cliconfg.exe](screenshots/cliconfg.exe-FF9932C30F72B19E57D9B07F230487E7-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `D742C17757BA63F0FB22715C3E0CFF68`
SHA1 | `1697CC917798DECF6A43088F339E8948EE596C8C`
SHA256 | `18CEE4DD64171378598E362309BEE02E6A4B16119AEEF5D19FA8384766DEBDF1`
SHA384 | `65AA1C2BFFD7B60309B0B4CA1FAEC0B5FFE32D7871142F885FF358106D71E79BC53871069672B7FFD52A424EC649DA66`
SHA512 | `6AAEAA5D35959EF5B7C33E1B2348CBB7816B93B17A6331151C9290BF92204B7E5643C6E3CB3912776CA742E3058533CAD4EDD0600D6C17F000824E4EA1F69080`
SSDEEP | `384:h5XS7aGvJGWWCwWSPXuNvBQAMYJQ2JQSkdowyoh:h8GWJGKwuI30lJBkvT`

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\cliconfg.exe |


## Signature

* Status: The file C:\windows\SysWOW64\cliconfg.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: cliconfg.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\cliconfg.exe](cliconfg.exe-1A81668402876DBDE84C5E111C8D4A78.md) | 69
[C:\WINDOWS\system32\cliconfg.exe](cliconfg.exe-23270B94D888BC3AC565E97C8DD6F4BB.md) | 58
[C:\Windows\system32\cliconfg.exe](cliconfg.exe-2F01F4A027E09027DBD2651FF3359DF9.md) | 63
[C:\Windows\system32\cliconfg.exe](cliconfg.exe-E06C0D21FFE629D45E3F0067B86D2CEA.md) | 66
[C:\Windows\system32\cliconfg.exe](cliconfg.exe-FF9932C30F72B19E57D9B07F230487E7.md) | 63
[C:\WINDOWS\SysWOW64\cliconfg.exe](cliconfg.exe-588677B78E8431F7822DB276E75D4DD7.md) | 68
[C:\Windows\SysWOW64\cliconfg.exe](cliconfg.exe-5924FC77AC5B646CCF8CEF54DBED2D69.md) | 71
[C:\Windows\SysWOW64\cliconfg.exe](cliconfg.exe-5EE49921CB7AEA9FDF2938F99DB69FFA.md) | 69
[C:\Windows\SysWOW64\cliconfg.exe](cliconfg.exe-8479031B34E1F72E08EB5EC618368822.md) | 66

## Possible Misuse

*The following table contains possible examples of `cliconfg.exe` being misused. While `cliconfg.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) |       $x2 = "del /f /q %TEMP%\\setup.cab && cliconfg.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) |       $x1 = "cmd /c taskkill /im cliconfg.exe /f /t && del /f /q" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


