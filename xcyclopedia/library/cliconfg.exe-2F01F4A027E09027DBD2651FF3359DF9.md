---
title: cliconfg.exe | SQL Client Configuration Utility EXE
---

# cliconfg.exe 

* File Path: `C:\windows\system32\cliconfg.exe`
* Description: SQL Client Configuration Utility EXE

## Screenshot

![cliconfg.exe](screenshots/cliconfg.exe-FF9932C30F72B19E57D9B07F230487E7-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `2F01F4A027E09027DBD2651FF3359DF9`
SHA1 | `DD2A6B32B9F2C746A504632A45D349740C8319A5`
SHA256 | `890D486F00726E694BE483CDEEF17A22EAD2853D8D8C6D4BF1453D7CB44A6BCA`
SHA384 | `D67A01687A619CB07B61C2221470DAD2359C3D6F72651DFE68128CE08580812C4F02E8292D9CC6DC0E067A9FD1BACCCF`
SHA512 | `DE24B51CEDCF0CFBFC1A9ECAB0916E0F2358B63F17A19D8BC9AC6FF4F52B66D8C95696E0AC16207FABB79AEA9246BC79E081596FB0C96CC5F80CD63DFDD8D53B`
SSDEEP | `384:qbyf4ZRmiVJklCrxPQu8hWPwWsPXuNvBQAMYJQ2JQSkdowyo:qbyYRm4uLGKuI30lJBkvT`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cliconfg.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\cliconfg.exe](cliconfg.exe-1A81668402876DBDE84C5E111C8D4A78.md) | 57
[C:\WINDOWS\system32\cliconfg.exe](cliconfg.exe-23270B94D888BC3AC565E97C8DD6F4BB.md) | 75
[C:\Windows\system32\cliconfg.exe](cliconfg.exe-E06C0D21FFE629D45E3F0067B86D2CEA.md) | 60
[C:\Windows\system32\cliconfg.exe](cliconfg.exe-FF9932C30F72B19E57D9B07F230487E7.md) | 57
[C:\WINDOWS\SysWOW64\cliconfg.exe](cliconfg.exe-588677B78E8431F7822DB276E75D4DD7.md) | 63
[C:\Windows\SysWOW64\cliconfg.exe](cliconfg.exe-5924FC77AC5B646CCF8CEF54DBED2D69.md) | 66
[C:\Windows\SysWOW64\cliconfg.exe](cliconfg.exe-5EE49921CB7AEA9FDF2938F99DB69FFA.md) | 63
[C:\Windows\SysWOW64\cliconfg.exe](cliconfg.exe-8479031B34E1F72E08EB5EC618368822.md) | 66
[C:\windows\SysWOW64\cliconfg.exe](cliconfg.exe-D742C17757BA63F0FB22715C3E0CFF68.md) | 63

## Possible Misuse

*The following table contains possible examples of `cliconfg.exe` being misused. While `cliconfg.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) |       $x2 = "del /f /q %TEMP%\\setup.cab && cliconfg.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) |       $x1 = "cmd /c taskkill /im cliconfg.exe /f /t && del /f /q" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


