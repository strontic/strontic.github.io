---
title: logonsessions64.exe | Lists logon session information
excerpt: What is logonsessions64.exe?
---

# logonsessions64.exe 

* File Path: `C:\SysinternalsSuite\logonsessions64.exe`
* Description: Lists logon session information

## Hashes

Type | Hash
-- | --
MD5 | `CF1D2295B6DD515BFDF78D17FA2DC211`
SHA1 | `2ACF9323D59AD1AB6D71C3F9173588B3BA847817`
SHA256 | `828038E4AB466FA972387001BFA8BC9A2252872B46446C1C43F0120D850B7D56`
SHA384 | `7A8EB489CAE062EF2C570C3D3FC891FCBB13010BA6E6ADEC296D6D6A1FC1E46B5F8645ED16A962B96E96F05A6A409C1B`
SHA512 | `ED35273C781EFF47E3B7D12017F06633C030E8F465AD3872B021C049F3C5B3AEBD52559DD8F0941FC16211CB576149AD3619825D147373E39C80611D8B01A919`
SSDEEP | `3072:zoKK9SWTEmN535PIXaCU3TmMxII58Ji5UFjtlvzxmejcpYu3EYcpKhD6LF4vGEmi:8d7TEmb5cbU3T9+E8Zjvk6a3EjpKefq`
IMP | `4F2B9AD89041FEDC43298C09C8E7B948`
PESHA1 | `0C460427E9315AE1D11825570BBE1835B5B07691`
PE256 | `26D786803AE98A15D024ABE378CF6CAED7D70BB3E770B11321E2FDAE62C030DE`

## Runtime Data

### Usage (stdout):
```cmhg

LogonSessions v1.4 - Lists logon session information
Copyright (C) 2004-2016 Mark Russinovich
Sysinternals - www.sysinternals.com


[0] Logon session 00000000:000003e7:
    User name:    WORKGROUP\37AACD8D-548A-4$
    Auth package: NTLM
    Logon type:   (none)
    Session:      0
    Sid:          S-1-5-18
    Logon time:   9/9/2020 6:07:57 AM
    Logon server: 
    DNS Domain:   
    UPN:          

[1] Logon session 00000000:0000783a:
    User name:    
    Auth package: NTLM
    Logon type:   (none)
    Session:      0
    Sid:          (none)
    Logon time:   9/9/2020 6:07:57 AM
    Logon server: 
    DNS Domain:   
    UPN:          

[2] Logon session 00000000:00007d3b:
    User name:    Font Driver Host\UMFD-0
    Auth package: Negotiate
    Logon type:   Interactive
    Session:      0
    Sid:          S-1-5-96-0-0
    Logon time:   9/9/2020 6:07:58 AM
    Logon server: 
    DNS Domain:   
    UPN:          

[3] Logon session 00000000:000003e4:
    User name:    WORKGROUP\37AACD8D-548A-4$
    Auth package: Negotiate
    Logon type:   Service
    Session:      0
    Sid:          S-1-5-20
    Logon time:   9/9/2020 6:07:58 AM
    Logon server: 
    DNS Domain:   
    UPN:          

[4] Logon session 00000000:000003e5:
    User name:    NT AUTHORITY\LOCAL SERVICE
    Auth package: Negotiate
    Logon type:   Service
    Session:      0
    Sid:          S-1-5-19
    Logon time:   9/9/2020 6:07:58 AM
    Logon server: 
    DNS Domain:   
    UPN:          

[5] Logon session 00000000:0002e3ee:
    User name:    37AACD8D-548A-4\user
    Auth package: NTLM
    Logon type:   Network
    Session:      0
    Sid:          S-1-5-21-2047949552-857980807-821054962-504
    Logon time:   9/25/2020 8:15:06 AM
    Logon server: 37AACD8D-548A-4
    DNS Domain:   
    UPN:          

[6] Logon session 00000000:00031b58:
    User name:    Font Driver Host\UMFD-1
    Auth package: Negotiate
    Logon type:   Interactive
    Session:      1
    Sid:          S-1-5-96-0-1
    Logon time:   9/25/2020 8:15:07 AM
    Logon server: 
    DNS Domain:   
    UPN:          

[7] Logon session 00000000:00032753:
    User name:    Window Manager\DWM-1
    Auth package: Negotiate
    Logon type:   Interactive
    Session:      1
    Sid:          S-1-5-90-0-1
    Logon time:   9/25/2020 8:15:07 AM
    Logon server: 
    DNS Domain:   
    UPN:          

[8] Logon session 00000000:0003b067:
    User name:    37AACD8D-548A-4\user
    Auth package: NTLM
    Logon type:   RemoteInteractive
    Session:      1
    Sid:          S-1-5-21-2047949552-857980807-821054962-504
    Logon time:   9/25/2020 8:15:08 AM
    Logon server: 37AACD8D-548A-4
    DNS Domain:   
    UPN:          

```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\logonsessions64.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000010A2C79AED7797BA6AC00010000010A`
* Thumbprint: `3BDA323E552DB1FDE5F4FBEE75D6D5B2B187EEDC`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: logonsessions.exe
* Product Name: Sysinternals LogonSessions
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 1.4
* Product Version: 1.4
* Language: English (United States)
* Legal Copyright: Copyright (C) 2004-2016 Mark Russinovich
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/828038e4ab466fa972387001bfa8bc9a2252872b46446c1c43f0120d850b7d56/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\SysinternalsSuite\logonsessions.exe](logonsessions.exe-7A276034BE0F4189E2F6CEA85054F492.md) | 41




MIT License. Copyright (c) 2020 Strontic.


