---
title: finger.exe | TCPIP Finger Command
excerpt: What is finger.exe?
---

# finger.exe 

* File Path: `C:\Windows\system32\finger.exe`
* Description: TCPIP Finger Command

## Hashes

Type | Hash
-- | --
MD5 | `C9085755F831F1345CF2B0A309095522`
SHA1 | `4C7D686DE444BB2101934350A9357BF95260F4B4`
SHA256 | `D6C52EA560D6009505545E53C481F1D75579E11DADE120CF164EBD196824BA91`
SHA384 | `E6E76C1B0F724AEEA555243155F05623A582B4837D3AE365781A39EC360DD6831608DC07BDBD62C705F9B19AC376D71D`
SHA512 | `69FCF92EBE2E86EC0160B785740979E48FE87E79DDE225ABBA27CCC7028DF071416532F5B310FF0051F4949E91B509C1A7A04771B91FABB1724583F8FF5C0622`
SSDEEP | `384:LgY+HjG7lsZSy9x6R58lSGQ7O7+VjNbKfWl0W:ETWUmVjAq`
IMP | `E15D0366B0329E559CFF2A7B0126BA16`
PESHA1 | `A442D917D4FE5EBA502EE4B5736D1EAEC2290834`
PE256 | `DBE5062B44BFBD35D2839FAFF89618CE59472C452AE391777F1DB6B6B6C71DC8`

## Runtime Data

### Usage (stdout):
```cmhg

[18ce68cb-4304-4445-a952-d165bf86113f]

```

### Usage (stderr):
```cmhg

Displays information about a user on a specified system running the
Finger service. Output varies based on the remote system.

FINGER [-l] [user]@host [...]

  -l        Displays information in long list format.
  user      Specifies the user you want information about. Omit the user
            parameter to display information about all users on the
            specifed host.
  @host     Specifies the server on the remote system whose users you
            want information about.


```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\finger.exe.mui | File
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\system32\finger.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: finger.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/d6c52ea560d6009505545e53c481f1d75579e11dade120cf164ebd196824ba91/detection


## Possible Misuse

*The following table contains possible examples of `finger.exe` being misused. While `finger.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [nouns.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/nouns.txt) | `finger`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## finger

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information about users on a specified remote computer (typically a computer running UNIX) that is running the finger service or daemon. The remote computer specifies the format and output of the user information display. Used without parameters, **finger** displays help.

> [!IMPORTANT]
> This command is available only if the Internet Protocol (TCP/IP) protocol is installed as a component in the properties of a network adapter in Network Connections.

### Syntax

```
finger [-l] [<user>] [@<host>] [...]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| -l | Displays user information in long list format. |
| `<user>` | Specifies the user about which you want information. If you omit the *user* parameter, this command displays information about all users on the specified computer. |
| `@<host>` | Specifies the remote computer running the finger service where you are looking for user information. You can specify a computer name or IP address. |
| /? | Displays help at the command prompt. |

##### Remarks

- You must prefix **finger** parameters with a hyphen (-) rather than a slash (/).

- Multiple `user@host` parameters can be specified.

#### Examples

To display information for *user1* on the computer *users.microsoft.com*, type:

```
finger user1@users.microsoft.com
```

To display information for *all users* on the computer *users.microsoft.com*, type:

```
finger @users.microsoft.com
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


