
# autochk.exe 

* File Path: `C:\WINDOWS\SysWOW64\autochk.exe`
* Description: Auto Check Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `ECCFAB8A25C3593EB8877417B98E9E59`
SHA1 | `B09DE9DA8AEB7720C50C10521D9379544AD4C120`
SHA256 | `B1D1F0551E4206732ADF4417D6F5E8D2BE04B8CDAFD70E8F8BBF821DEDBFA01B`
SHA384 | `4E110386571DA66D05A015ACF71067E47B096BEFF7EA438A50231D11D2F3236CD181C0E8C1EC60B3729AA30389C910BC`
SHA512 | `EE21F3C5392FE2937E7459AC7C3F9AA60DBF9262EDDE2F295528F3B5755DF4A17BC41FEFFCC88F7A4733CF0E427DC329378D309F9DE554A8E36429886473FB88`
SSDEEP | `24576:zRBg2mPBlKQaJaunUDUvE0MBa2o4VWtrAt0YA0iRiYq/Byhkp:zu/a8unUDUvE0MBazftr70iRi//Byhkp`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AutoChk.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

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


