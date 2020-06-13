
# autochk.exe 

* File Path: `C:\WINDOWS\system32\autochk.exe`
* Description: Auto Check Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `F752225A44526D36E2B0F56090AFA881`
SHA1 | `43B1D92162DA7FD0624FD563911918955475D3CB`
SHA256 | `60169BAA6E0122DE2BD46303611D6B4F9F3128BE65DEAB26F661C58F4182DA94`
SHA384 | `3BAB6C7B8B5FEA95E47DC3D16513574A6A2855FF821845C03FB4A5CAA89C80FF2C145182A8255726B2BFD12BC8474FC4`
SHA512 | `76B29C72D55E4D2FA34290D61F023B3CFC57C2EC5DF00EFD774FDAA82A2DF7B86090AA2BA9B663CD8FDE33DC4E875988BA04068F4065E73F9937A6B70DB55763`
SSDEEP | `12288:KlGtmbnVpY9PCU6gUEHElN9+IVrnqTBrsFBnr/sojYq/nlFFstr:KS2PY9sg7HET99rq9rUB7sSYoEh`

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

* Original Filename: AutoChk.Exe.MUI
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


