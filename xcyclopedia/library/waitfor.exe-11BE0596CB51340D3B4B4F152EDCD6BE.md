---
title: waitfor.exe | waitfor - wait/send a signal over a network
excerpt: What is waitfor.exe?
---

# waitfor.exe 

* File Path: `C:\windows\SysWOW64\waitfor.exe`
* Description: waitfor - wait/send a signal over a network

## Hashes

Type | Hash
-- | --
MD5 | `11BE0596CB51340D3B4B4F152EDCD6BE`
SHA1 | `7C566A09D290E82943D004B91843E0E4F5729F51`
SHA256 | `09CC91B6997D3C2432AA73D0D021856B8603304DAE9B315E10289CCF941B5A21`
SHA384 | `745EF128123876C79328B9625658B557966B5F1EF35837EB9182C8A5D655BCC4AF97284B8C1202A5BE95EB6F473B4A1D`
SHA512 | `C93BE466B5D79CEF12C202FE8D500D3C33E2AA24F9060375AC78921B0E15B29E4595C5788E0EB18669F841D381413F4BF2EC2E1F289ADD8B9A9A2D7E6111F9C4`
SSDEEP | `768:PHa2di85dRs/bFz9fBItNbXXkBL/+kdy1xYxOLfrH1K:PHa2diodRs/Rz9ZIj0NGkdSxYxAf71`

## Signature

* Status: The file C:\windows\SysWOW64\waitfor.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: waitfor.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `waitfor.exe` being misused. While `waitfor.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

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



MIT License. Copyright (c) 2020-2021 Strontic.


