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
MD5 | `7072125EE25D342DF114919ED68D34A1`
SHA1 | `080F2EDD1356B97E2C90268F68CC9BA3177F7B83`
SHA256 | `BBB90F52D01BE03C297A6D4921C79E26D3CEDA6DAB20366E32A20907E015FBE1`
SHA384 | `5DF72AABADF58D4088AFAF4F5BB43D6FC5C290F1976CFEEF965F0E7A29BB98630F0E8D1BAFC0837533B2AE2A1D0DAE0C`
SHA512 | `29F86BFD186FE2BFC93A32548F9BB4476FFC4F8F60D9B10917357B0BED977EEFB80AEBD3814762B5A3A8BF8CE1E1C66525023586174D8797ACE0CC6BFDA8297C`
SSDEEP | `192:vT+V81sDF09kycvbhH+u6pePFkzCM0Mh08G9EQjNEwzru/aW60W:vT+VCUF09FcDdEpedkU58EjNbzHW60W`
IMP | `E1B908A2F0F52AE305808122ED02A033`
PESHA1 | `26E66493598AB124A5371D1A11FD128689F94D68`
PE256 | `20A5FAD6EE8E6C59D23F6191A7FC20C973175FE83E5104F37B40A3109A56B4DC`

## Runtime Data

### Usage (stdout):
```cmhg

[Default-PC]

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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/bbb90f52d01be03c297a6d4921c79e26d3ceda6dab20366e32a20907e015fbe1/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\finger.exe](finger.exe-56C565BE7419852071C6DFCF36F31503.md) | 74

## Possible Misuse

*The following table contains possible examples of `finger.exe` being misused. While `finger.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [nouns.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/nouns.txt) | `finger` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)

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



MIT License. Copyright (c) 2020 Strontic.


