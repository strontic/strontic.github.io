---
title: notmyfaultc64.exe | Driver Bug Test Program
excerpt: What is notmyfaultc64.exe?
---

# notmyfaultc64.exe 

* File Path: `C:\SysinternalsSuite\notmyfaultc64.exe`
* Description: Driver Bug Test Program

## Hashes

Type | Hash
-- | --
MD5 | `1F0F2EB24B988B743113272E546E6DA8`
SHA1 | `BC33B016B6EA03C1D6CBF3C3EFCAEBAF7573D172`
SHA256 | `1DCA57298B8233D1CFE688C2E47BFFAED5AAC8CE3ED2FC909CD73139A7A7FDF0`
SHA384 | `D39D4992A615A7FB6475F5FA18619EC9D5B1843AA1E3A7647E19AF862F0538C6949C349BF51705FE7762EFB59585BC45`
SHA512 | `46832BDB9EBCAD1559328E348E7493C17BDAC2F85FF2C9BA0149E7A3CE19B81E697FBAAEAEF7C3FCB2BE5FC3EF227742B27BC5CBC903A791E4F2A93DED02BEF5`
SSDEEP | `12288:W2cfkkQaMvtBEOGXbbBXsQQdZJq1+enfaHbomeELS7PT:WuBVBEOGXbbBXsQQ0Eenfa7oSSf`
IMP | `2BAE8696D9771623FBF7A6A2F714AAEA`
PESHA1 | `651E0F24EED3215B6F1E8D4C6FF7A78B0C63876F`
PE256 | `6B682E7004E1C30380CE2C0A07E63F361876D12540130D815F987118F2418997`

## Runtime Data

### Usage (stdout):
```cmhg

Sysinternals NotMyfault v4.20 - Driver Bug Test Program
Copyright (C) 2002-2019 Mark Russinovich
Sysinternals - www.sysinternals.com


NotMyFault is a tool used in the Windows Internals books to show how common device driver bugs affect a system.
This is the console version of NotMyFault.

Usage:
    notmyfaultc.exe [/wait] /crash crash_type_num

    crash type:
      0x01: High IRQL fault (Kernel-mode)
      0x02: Buffer overflow
      0x03: Code overwrite
      0x04: Stack trash
      0x05: High IRQL fault (User-mode)
      0x06: Stack overflow
      0x07: Hardcoded breakpoint
      0x08: Double Free
    wait:
      wait until named event NOTMYFAULT is set


Or  notmyfaultc.exe /hang hang_type_num

    hang type:
      0x01: Hang with IRP
      0x02: Hang with DPC
      0x03: Deadlock


Or  notmyfaultc.exe /leak leak_type_num [/rate KB/s] [/duration seconds]

    leak type:
      0x01: Paged Leak
      0x02: Nonpaged Leak
    rate:
      default value is 1000 KB/s
    duration:
      default value is 30s

Or  notmyfaultc.exe bugcheck id


Or  notmyfaultc.exe /getdumptype
    notmyfaultc.exe /setdumptype [full|kernel|active]


```

### Child Processes:
csrss.exe winlogon.exe

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\notmyfaultc64.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001B1DDEDBA54E965B85F0001000001B1`
* Thumbprint: `9DC17888B5CFAD98B3CB35C1994E96227F061675`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NotMyfault.exe
* Product Name: Sysinternals NotMyfault
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 4.20
* Product Version: 4.20
* Language: English (United States)
* Legal Copyright: Copyright (C) 2002-2019 Mark Russinovich
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/1dca57298b8233d1cfe688c2e47bffaed5aac8ce3ed2fc909cd73139a7a7fdf0/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


