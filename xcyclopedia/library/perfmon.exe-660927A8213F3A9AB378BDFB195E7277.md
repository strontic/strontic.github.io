---
title: perfmon.exe | Resource and Performance Monitor
---

# perfmon.exe 

* File Path: `C:\windows\SysWOW64\perfmon.exe`
* Description: Resource and Performance Monitor
* Comments: 

## Screenshot

![perfmon.exe](screenshots/perfmon.exe-805F9B64745C730A6BD789083D0EF4E2-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `660927A8213F3A9AB378BDFB195E7277`
SHA1 | `834BE26A51D0871195C3838C8FD3067A7B237B99`
SHA256 | `7B2CF6E56FE262686CE9AFDABB260854EE92B257AD95D577E9ADA6A4ECCFB9F1`
SHA384 | `80A14607ED6D7C25586D5E77D947F95336D1B587667938A2204EB70528A5005243CCA0761C357B23DCE94C393825E30E`
SHA512 | `1CC07082423DC778D6A4C69CA9BDDCB8510A2809DD2F79D94F8D0E065AC546143D1938EEDCDE17208E06508D75B548C97EC37752AE722A67485EC2769614BACF`
SSDEEP | `3072:i88RlSQBQfRwxiE+/9cghtYIo9piswTogiqQKy349a:SRlyf2xO/XhqIo9s37iTK24`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\perfmon.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: perfmon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\perfmon.exe](perfmon.exe-52BC3295597B70B1380FAA6E32BEFAD3.md) | 58
[C:\WINDOWS\system32\perfmon.exe](perfmon.exe-AE3D54BF0D325BDFB785B86511930E37.md) | 65
[C:\windows\system32\perfmon.exe](perfmon.exe-CB1511A4E14C072450E5A61BD74859E3.md) | 71
[C:\Windows\system32\perfmon.exe](perfmon.exe-D38AA59C3BEA5456BD6F95C73AD3C964.md) | 58
[C:\Windows\system32\perfmon.exe](perfmon.exe-D761794B0779B9951349E2F2507B25BC.md) | 61
[C:\windows\system32\resmon.exe](resmon.exe-6C6E586C858BFE1DE453921F67AA9206.md) | 66
[C:\Windows\system32\resmon.exe](resmon.exe-852ACA89972551B00B110EEE6ADA717A.md) | 69
[C:\Windows\system32\resmon.exe](resmon.exe-A01AB6C669DCC17E87C84C0C07D2CFAE.md) | 66
[C:\Windows\system32\resmon.exe](resmon.exe-C9221473CE8A3EF5C0FB8ABB912786FA.md) | 69
[C:\WINDOWS\system32\resmon.exe](resmon.exe-FF8CA7D9F879E176A1284F16A05A618C.md) | 69
[C:\WINDOWS\SysWOW64\perfmon.exe](perfmon.exe-14ACB06686DC70FAB341DE0721B71BF1.md) | 66
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-6284C86A1AE399794C18FBBC86CC8340.md) | 61
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-805F9B64745C730A6BD789083D0EF4E2.md) | 58
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-97F73727B423C2FEE513EB7A06E357E5.md) | 63
[C:\windows\SysWOW64\resmon.exe](resmon.exe-0FB8985E4D0F7D37BC366CFD93B73A52.md) | 68
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-29C52C15D2D68A4BBE9A36701D31100E.md) | 68
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-87427E88F06D7C568E3E4A8BD838E380.md) | 71
[C:\WINDOWS\SysWOW64\resmon.exe](resmon.exe-B44E84B38D62E787F5154983A71A864F.md) | 68
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-C182C3463D5E5DFFED8F949D2BB781D3.md) | 69


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## perfmon

Start Windows Reliability and Performance Monitor in a specific standalone mode.

### Syntax

```
perfmon </res|report|rel|sys>
```

#### Parameters

| Parameter | Description |
|--|--|
| /res | Starts the Resource View. |
| /report | Starts the System Diagnostics Data Collector Set and displays a report of the results. |
| /rel | Starts the Reliability Monitor. |
| /sys | Starts the Performance Monitor. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Windows Performance Monitor](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/cc749154(v%3dws.11))

---



MIT License. Copyright (c) 2020 Strontic.


