---
title: cliconfg.exe | SQL Client Configuration Utility EXE
excerpt: What is cliconfg.exe?
---

# cliconfg.exe 

* File Path: `C:\WINDOWS\SysWOW64\cliconfg.exe`
* Description: SQL Client Configuration Utility EXE

## Screenshot

![cliconfg.exe](screenshots/cliconfg.exe-FF9932C30F72B19E57D9B07F230487E7-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `588677B78E8431F7822DB276E75D4DD7`
SHA1 | `1F267CBE4765C2EEDB9D73A8544850BDF5BC5AD1`
SHA256 | `08E8AC164DCE4D52DF2A0009E169DC310ECE9B5D1F3F318F9088031316DBFC56`
SHA384 | `0BDDC53A3610DCE5100AF43E966618F4F2F0A23B2FAF541927A73D8B062F75363644721D516CE1508C89EE644F56DAF6`
SHA512 | `0C982E98855E004E06DAD784EC75AE6EB65A9684F78ED7E0D0FBFA8F5765F2F469807010ACAF0B34DBE6EF763A3AEA41A94C71D598BE8B11B64370363E835F4B`
SSDEEP | `384:Vw3tm5UkF63pWFwWGPXuNvBQAMYJQ2JQSkdowyox:xd63oEuI30lJBkvTx`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cliconfg.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\cliconfg.exe](cliconfg.exe-1A81668402876DBDE84C5E111C8D4A78.md) | 63
[C:\WINDOWS\system32\cliconfg.exe](cliconfg.exe-23270B94D888BC3AC565E97C8DD6F4BB.md) | 65
[C:\Windows\system32\cliconfg.exe](cliconfg.exe-2F01F4A027E09027DBD2651FF3359DF9.md) | 63
[C:\Windows\system32\cliconfg.exe](cliconfg.exe-E06C0D21FFE629D45E3F0067B86D2CEA.md) | 65
[C:\Windows\system32\cliconfg.exe](cliconfg.exe-FF9932C30F72B19E57D9B07F230487E7.md) | 65
[C:\Windows\SysWOW64\cliconfg.exe](cliconfg.exe-5924FC77AC5B646CCF8CEF54DBED2D69.md) | 72
[C:\Windows\SysWOW64\cliconfg.exe](cliconfg.exe-5EE49921CB7AEA9FDF2938F99DB69FFA.md) | 74
[C:\Windows\SysWOW64\cliconfg.exe](cliconfg.exe-8479031B34E1F72E08EB5EC618368822.md) | 72
[C:\windows\SysWOW64\cliconfg.exe](cliconfg.exe-D742C17757BA63F0FB22715C3E0CFF68.md) | 68

## Possible Misuse

*The following table contains possible examples of `cliconfg.exe` being misused. While `cliconfg.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) | $x2 = "del /f /q %TEMP%\\setup.cab && cliconfg.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_honeybee.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_honeybee.yar) | $x1 = "cmd /c taskkill /im cliconfg.exe /f /t && del /f /q" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


