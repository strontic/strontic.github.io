
# autochk.exe 

* File Path: `C:\Windows\SysWOW64\autochk.exe`
* Description: Auto Check Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `179B4BE70851AB36F11BC94B910C1ADB`
SHA1 | `A339014942AC7618AF8798AA180C7F92A73AD026`
SHA256 | `DAAFE2EC56BBD8F5C082B6690BC81097426D2D544D06D1E94F48A1C45942233E`
SHA384 | `05D6500A0C18E1942A1E926173C8A0A4008AD41D3503D111E1C3A4A83946C6889D8D2894EED317024FB03DC7DC775CD4`
SHA512 | `56DC7805E8D70658F7BBE3441FEBF0878CBF62ADD6566D383ABF56F5AF6626EAA9C044DCBAD8B38ACBB93976C40AA49DF87A07ABDCAB5833E11AF15188AD21B7`
SSDEEP | `12288:gOWD43HlyZMuIlyokrhVngqT07MiUGo7nj1KRfEMBUv1V5WqQJcR2lAg1X:gYHY1ayokrhH1KRfEMBgV5WLJcR2Ag1`

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


