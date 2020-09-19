---
title: waitfor.exe | waitfor - wait/send a signal over a network
---

# waitfor.exe 

* File Path: `C:\WINDOWS\system32\waitfor.exe`
* Description: waitfor - wait/send a signal over a network

## Hashes

Type | Hash
-- | --
MD5 | `E6F52AF752157757EA5B0B1F1C997314`
SHA1 | `B1F46293696764C26BFB2F6BD172FA2FBDD95740`
SHA256 | `4C2F9EFA10013D1E95810973DC5A47795C0B62AF923165E4CC232399A89E5767`
SHA384 | `680A6BB4769E40C5AB3D70BC801877F466B4271207239D94FCC25828117B6FBD3237F7C5EDE5C1813174D8F48154320A`
SHA512 | `76CB0ECDC1A867A3785C8A9FFEF74154E3ECA3E86D65A70205CCAFB16ECD85342AC9F50E4DC4564FE3DE4514161DCC90987D6832C7B32522BDAF59F387987809`
SSDEEP | `768:Yf98nv2Ciy9wn0bgdr5g+L3Rcy95XX6GgHKePKx6nUM8:Uoevjn6lHKVx6N8`

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

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: waitfor.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `waitfor.exe` being misused. While `waitfor.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_process_creations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_process_creations.yml) | `            - '*waitfor*/s*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_process_creations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_process_creations.yml) | `            - '*waitfor*/si persist*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) |       $x2 = "wss.Run \"powershell.exe \" & Chr(34) & \"& {waitfor haha /T 2}\" & Chr(34), 0" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## waitfor



Sends or waits for a signal on a system. **Waitfor** is used to synchronize computers across a network.



### Syntax

```
waitfor [/s <Computer> [/u [<Domain>\]<User> [/p [<Password>]]]] /si <SignalName>
waitfor [/t <Timeout>] <SignalName>
```

#### Parameters

|       Parameter       |                                                                                         Description                                                                                          |
|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|    /s \<Computer>     | Specifies the name or IP address of a remote computer (do not use backslashes). The default is the local computer. This parameter applies to all files and folders specified in the command. |
| /u [\<Domain>\]<User> |                              Runs the script using the credentials of the specified user account. By default, **waitfor** uses the current user's credentials.                               |
|   /p [\<Password>]    |                                                    Specifies the password of the user account that is specified in the **/u** parameter.                                                     |
|          /si          |                                                                        Sends the specified signal across the network.                                                                        |
|     /t \<Timeout>     |                                              Specifies the number of seconds to wait for a signal. By default, **waitfor** waits indefinitely.                                               |
|     \<SignalName>     |                                                Specifies the signal that **waitfor** waits for or sends. *SignalName* is not case-sensitive.                                                 |
|          /?           |                                                                             Displays help at the command prompt.                                                                             |

### Remarks

-   Signal names cannot exceed 225 characters. Valid characters include a-z, A-Z, 0-9, and the ASCII extended character set (128-255).
-   If you do not use **/s**, the signal is broadcast to all the systems in a domain. If you use **/s**, the signal is sent only to the specified system.
-   You can run multiple instances of **waitfor** on a single computer, but each instance of **waitfor** must wait for a different signal. Only one instance of **waitfor** can wait for a given signal on a given computer.
-   You can activate a signal manually by using the **/si** command-line option.
-   **Waitfor** runs only on Windows XP and servers running a Windows Server 2003 operating system, but it can send signals to any computer running a Windows operating system.
-   Computers can only receive signals if they are in the same domain as the computer sending the signal.
-   You can use **waitfor** when you test software builds. For example, the compiling computer can send a signal to several computers running **waitfor** after the compile has completed successfully. On receipt of the signal, the batch file that includes **waitfor** can instruct the computers to immediately start installing software or running tests on the compiled build.

### Examples

To wait until the espresso\build007 signal is received, type:
```
waitfor espresso\build007
```
By default, **waitfor** waits indefinitely for a signal.

To wait 10 seconds for the espresso\compile007 signal to be received before timing out, type:
```
waitfor /t 10 espresso\build007
```
To manually activate the espresso\build007 signal, type:
```
waitfor /si espresso\build007
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


