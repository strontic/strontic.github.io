
# autochk.exe 

* File Path: `C:\Windows\system32\autochk.exe`
* Description: Auto Check Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `33900CEB40D3ECD3504F1DD287428B49`
SHA1 | `530FB3D624E14DDB4B11B561E274944C4C54E82C`
SHA256 | `A279FC9CECA961D9040AA69F06A0A78B530E21C788C7D7590E866EFC447E979B`
SHA384 | `1A9EFA89B96A4E42C3ED132883ECDCCDCCD243E51EC638313DD8288243D7C36D35AA6361188E48DE7A2D02A010DF0BF0`
SHA512 | `406A55278AFB5BCFD70FF8C84B60AD93E427DEF558FF651E72E966A5E4BF907DAF333AC7B270F7F3D9A1ED4A54BBA748CDB6BD5A86A03DF492038732A5AEDC05`
SSDEEP | `12288:kEOVuzEjiPvADKg2ALAR3q/jiVO8dFeSoDTUm/Zg1X:bquQjHDKg2A0Ra/jedJ09/W1`

## Runtime Data

### Usage (stdout):
```Batchfile

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

* Original Filename: AutoChk.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.1532 (rs1_release_d.170711-1840)
* Product Version: 10.0.14393.1532
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# autochk

Runs when the computer is started and prior to Windows Server starting to verify the logical integrity of a file system.

**Autochk.exe** is a version of **chkdsk** that runs only on NTFS disks and only before Windows Server starts. **autochk** cannot be run directly from the command-line. Instead, **autochk** runs in the following situations:

- If you try to run **chkdsk** on the boot volume.

- If **chkdsk** cannot gain exclusive use of the volume.

- If the volume is flagged as dirty.

## Remarks

> [!WARNING]
> The **autochk** command-line tool cannot be directly run from the command-line. Instead, use the **chkntfs** command-line tool to configure the way you want **autochk** to run at startup.
>
> - You can use **chkntfs** with the **/x** parameter to prevent **autochk** from running on a specific volume or multiple volumes.
>
> - Use the **chkntfs.exe** command-line tool with the **/t** parameter to change the autochk delay from 0 seconds to up to 3 days (259,200 seconds). However, a long delay means that the computer does not start until the time elapses or until you press a key to cancel **autochk**.

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [chkdsk command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/chkdsk.md)

- [chkntfs command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/chkntfs.md)

---


MIT License. Copyright (c) 2020 Strontic.


