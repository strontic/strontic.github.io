
# perfmon.exe 

* File Path: `C:\Windows\SysWOW64\perfmon.exe`
* Description: Resource and Performance Monitor
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `805F9B64745C730A6BD789083D0EF4E2`
SHA1 | `DF46DE4C9866BCB49381A406E9CF4D22B6EA2E7F`
SHA256 | `4A58628ABFA58DCD4E683EBEF43018B663228CB562C27716A799257A7434B6A5`
SHA384 | `185485973AF883F58E37948D316C367CE3EB3229A17966ADB9D6E33380B5968A290D447240AC415ADF9FC3B0BE6054CE`
SHA512 | `51C5A88956A17ED37A5D49445EC7E589E9A93B11A0198EBD847D40446D66B7DC7A891E61574750BEC3D615601603394F6B2CF382315D1DD50679797ED6F7588F`
SSDEEP | `3072:qWuWAqeMLVf7kaFGghtYIo9piswTogiqQKy349t:q8eCVTkaJhqIo9s37iTK24`

## Runtime Data

### Usage (stdout):
```Batchfile
Argument 'help' is unknown.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: perfmon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.00
* Product Version: 10.00
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\perfmon.exe](perfmon.exe-AE3D54BF0D325BDFB785B86511930E37.md) | 63
[C:\Windows\system32\perfmon.exe](perfmon.exe-D761794B0779B9951349E2F2507B25BC.md) | 63
[C:\Windows\system32\resmon.exe](resmon.exe-C9221473CE8A3EF5C0FB8ABB912786FA.md) | 72
[C:\WINDOWS\system32\resmon.exe](resmon.exe-FF8CA7D9F879E176A1284F16A05A618C.md) | 72
[C:\WINDOWS\SysWOW64\perfmon.exe](perfmon.exe-14ACB06686DC70FAB341DE0721B71BF1.md) | 65
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-87427E88F06D7C568E3E4A8BD838E380.md) | 74
[C:\WINDOWS\SysWOW64\resmon.exe](resmon.exe-B44E84B38D62E787F5154983A71A864F.md) | 69


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

|Parameter|Description|
|---------|-----------|
|/res|Start Resource View.|
|/report|Start the System Diagnostics Data Collector Set and display a report of the results.|
|/rel|Start Reliability Monitor.|
|/sys|Start Performance Monitor.|

### Additional References

[Windows Performance Monitor](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/cc749154(v%3dws.11))

---



MIT License. Copyright (c) 2020 Strontic.


