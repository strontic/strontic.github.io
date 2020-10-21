---
title: waitfor.exe | waitfor - wait/send a signal over a network
excerpt: What is waitfor.exe?
---

# waitfor.exe 

* File Path: `C:\Windows\SysWOW64\waitfor.exe`
* Description: waitfor - wait/send a signal over a network

## Hashes

Type | Hash
-- | --
MD5 | `E58E152B44F20DD099C5105DE482DF24`
SHA1 | `BD67490FD205C697CC481B5D1741D63A96D136EA`
SHA256 | `D9E9DD5A87E171DCBEF7CA034E3A7DFB5C37A7F70AA7DB99A0CCAD24F16C97DC`
SHA384 | `FAFB9D5FEB92EA3903DC92C59CCBA9AC04C310EF2FA0EB1277C12020B1689A249309F77A05EE21C2B5031072FD1C2B66`
SHA512 | `3CE9EB3B9A3FBD40E1D4932A8E265CD80FBAF3767DD602631A96661F57BABF055031D99B635597D802E23A316CD5B22527AA9402CB0A39E486E9D701E35C78CC`
SSDEEP | `768:7HafjFdAjL+LAACIOtev4ioK5VDAeHeqO9xapd1pSx:7HafjFYIOg4if5Se+qCxidC`
IMP | `B03EDAA7CAD5E6CDC3A3B4CB4A721AD1`
PESHA1 | `29B46F276A06968F55ED82DBB5FCA0DCFF85E2FD`
PE256 | `930643A9D187078EAFAEEF9849DE34F3EBF9BF891B6B67CE89341A13E79C4FDA`

## Runtime Data

### Usage (stdout):
```cmhg

WaitFor has two ways of working: 

Syntax 1: to send a signal
    WAITFOR [/S system [/U user [/P [password]]]] /SI signal

Syntax 2: to wait for a signal
    WAITFOR [/T timeout] signal 

Description:
    This tool sends, or waits for, a signal on a system. When /S is not
    specified, the signal will be broadcasted to all the systems in a
    domain. If /S is specified, then the signal will be sent only
    to the specified system.

Parameter List:
    /S     system         Specifies remote system to send signal to.

    /U     [domain\]user  Specifies the user context under which
                          the command should execute.

    /P     [password]     Specifies the password for the given user context.

    /SI                   Sends the signal across the net to waiting machines

    /T     timeout        Number of seconds to wait for signal. Valid range
                          is 1 - 99999. Default is to wait forever for signal.

    signal                The name of the signal to wait for or to send.

    /?                    Displays this help message.

    NOTE: A system can wait for multiple unique signal names.
    The signal name cannot exceed 225 characters and cannot
    contain characters other than a-z, A-Z, 0-9 and ASCII 
    characters in the range 128-255.

Examples:
    WAITFOR /?
    WAITFOR SetupReady 
    WAITFOR CopyDone /T 100 
    WAITFOR /SI SetupReady 
    WAITFOR /S system  /U user /P password /SI CopyDone

```

### Usage (stderr):
```cmhg
ERROR: The signal cannot contain characters other than a-z, A-Z, 0-9 
and ASCII characters in the range 128-255.

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\waitfor.exe.mui | File
(RW-)   C:\Users\user\Documents | File
(RW-)   C:\Windows | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\waitfor.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: waitfor.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/d9e9dd5a87e171dcbef7ca034e3a7dfb5c37a7f70aa7db99a0ccad24f16c97dc/detection/


## Possible Misuse

*The following table contains possible examples of `waitfor.exe` being misused. While `waitfor.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $x2 = "wss.Run \"powershell.exe \" & Chr(34) & \"& {waitfor haha /T 2}\" & Chr(34), 0" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## waitfor

Sends or waits for a signal on a system. This command is used to synchronize computers across a network.

### Syntax

```
waitfor [/s <computer> [/u [<domain>\]<user> [/p [<password>]]]] /si <signalname>
waitfor [/t <timeout>] <signalname>
```

#### Parameters

| Parameter | Description |
|--|--|
| /s `<computer>` | Specifies the name or IP address of a remote computer (don't use backslashes). The default is the local computer. This parameter applies to all files and folders specified in the command. If you don't use this parameter, the signal is broadcast to all the systems in a domain. If you do use this parameter, the signal is sent only to the specified system. |
| /u `[<domain>]<user>` | Runs the script using the credentials of the specified user account. By default, **waitfor** uses the current user's credentials. |
| /p `[\<password>]` | Specifies the password of the user account that is specified in the **/u** parameter. |
| /si | Sends the specified signal across the network. This parameter also lets you manually activate a signal. |
| /t `<timeout>` | Specifies the number of seconds to wait for a signal. By default, **waitfor** waits indefinitely. |
| `<signalname>` | Specifies the signal that **waitfor** waits for or sends. This parameter isn't case-sensitive and can't exceed 225 characters. Valid characters include a-z, A-Z, 0-9, and the ASCII extended character set (128-255). |
| /? | Displays help at the command prompt. |

##### Remarks

- You can run multiple instances of **waitfor** on a single computer, but each instance of **waitfor** must wait for a different signal. Only one instance of **waitfor** can wait for a given signal on a given computer.

- Computers can only receive signals if they are in the same domain as the computer sending the signal.

- You can use this command when you test software builds. For example, the compiling computer can send a signal to several computers running **waitfor** after the compile has completed successfully. On receipt of the signal, the batch file that includes **waitfor** can instruct the computers to immediately start installing software or running tests on the compiled build.

### Examples

To wait until the *espresso\build007* signal is received, type:

```
waitfor espresso\build007
```

By default, **waitfor** waits indefinitely for a signal.

To wait *10 seconds* for the *espresso\compile007* signal to be received before timing out, type:

```
waitfor /t 10 espresso\build007
```

To manually activate the *espresso\build007* signal, type:

```
waitfor /si espresso\build007
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


