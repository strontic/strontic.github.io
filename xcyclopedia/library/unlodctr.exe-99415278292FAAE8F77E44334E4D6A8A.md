---
title: unlodctr.exe | Unload PerfMon Counters
---

# unlodctr.exe 

* File Path: `C:\WINDOWS\SysWOW64\unlodctr.exe`
* Description: Unload PerfMon Counters

## Hashes

Type | Hash
-- | --
MD5 | `99415278292FAAE8F77E44334E4D6A8A`
SHA1 | `D61E896D3D6E6DEEDAD364835612F59AD07B632C`
SHA256 | `CC507BB7AE21B2400D4ECC64BEF7D697EBCED8933F3C5AFED964FED302CB6DE8`
SHA384 | `E859E2774F6AA519A2500B457AF27BF5F4737AC08D3951F6C3674C7E5603569E7B11098087F2D434FC05546AEF914367`
SHA512 | `53AEE75AA94522F53D23700380C60FD140829705E10B9D38E64CD7C088643444F4F61604056E94E322D4E0EB7063F1F28075A5B15040F774406E4276E836AC45`
SSDEEP | `768:EZlM8QWNUQwjj+csTH+0RkrsmR00Id+kfHVA:GlM89UZnWH+0CsmRjI0kfHV`

## Runtime Data

### Usage (stdout):
```Batchfile

 
UNLODCTR 
       uninstalls a performance counter provider. 
Usage: 
       UNLODCTR <service-name> 
             uninstalls the v1.0 performance counter provider associated 
             with the <service-name> service.
       UNLODCTR /m:<manifest> 
             uninstall a v2.0 performance counter provider using the 
             provider GUID from the specified XML manifest.
       UNLODCTR /g:{ProviderGuid} 
             uninstall a v2.0 performance counter provider using the 
             specified provider GUID. The GUID should be specified in 
             registry form, i.e. {nnnnnnnn-nnnn...}
       UNLODCTR /p:<ProviderName> 
             uninstall a v2.0 performance counter provider matching the 
             specified provider name.

Note: any arguments with spaces in the names must be enclosed within double 
quotation marks.

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\unlodctr.exe |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: UNLODCTR.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


