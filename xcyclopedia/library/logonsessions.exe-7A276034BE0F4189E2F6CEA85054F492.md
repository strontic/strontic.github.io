---
title: logonsessions.exe | Lists logon session information
excerpt: What is logonsessions.exe?
---

# logonsessions.exe 

* File Path: `C:\SysinternalsSuite\logonsessions.exe`
* Description: Lists logon session information

## Hashes

Type | Hash
-- | --
MD5 | `7A276034BE0F4189E2F6CEA85054F492`
SHA1 | `B1C86476AACFC588EDDA691B6417D5267DD45776`
SHA256 | `024291596CE8F9A7C4ECF6025800E5F208D90ACB93638B076511DF515BBE9BC3`
SHA384 | `893EC3A02FD59DE49A75DA7A4328DB03A3171D7ED5D9EF07DA2EE78B26CDEE90A1985D217CA27BEA8DED31A1AC5318F6`
SHA512 | `145CDAE944CBC563DE8A3A5C2A954BFBBAB24B7AE097F56D515BF5C3C1B3A54AE250509CA95004FA04AC98F7E12A95792B78C9FE8BBBAB75735C3D995468669D`
SSDEEP | `3072:35lKeu7Ex5euZUF7GHfxa6BfYu3EYcpKhD6LF4ROCttEKLfs:354wA7JkX3EjpKmMLfs`
IMP | `14877AAC65E60D14428AC27347C23346`
PESHA1 | `B9D81C47B4A40B93BEF31F21CC1111DDE7FB164E`
PE256 | `7281A431504A020E1EBD19D3D6971782462C636226EB0F21C8306089BBC635E0`

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
C:\SysinternalsSuite\logonsessions.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/024291596ce8f9a7c4ecf6025800e5f208d90acb93638b076511df515bbe9bc3/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\SysinternalsSuite\logonsessions64.exe](logonsessions64.exe-CF1D2295B6DD515BFDF78D17FA2DC211.md) | 41




MIT License. Copyright (c) 2020 Strontic.


