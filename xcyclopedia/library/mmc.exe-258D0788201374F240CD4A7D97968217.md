
# mmc.exe 

* File Path: `C:\Windows\SysWOW64\mmc.exe`
* Description: Microsoft Management Console
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `258D0788201374F240CD4A7D97968217`
SHA1 | `BECBDEEF5D9E9A52B0BAACE184521D1F06195942`
SHA256 | `38B20E000EE8A8675881CA126FA85DAF9CE6A55EB7D990D8BB805D3AFE48D342`
SHA384 | `D230103D099A910DC3DC415E74802132955C877EA6C9BAF46CFE3FD67BB227C338D2C0C97B400D4AC9D2FA4D3BF4F1F6`
SHA512 | `0B5076F62BBF4EDDE874D143255CC9F277385DA5E11E21D49039B8A0F5107AA0FACF7B214CAE800CEDF656CD9DBB7EDFB5C66060A2CBCF301672D809F538BDDE`
SSDEEP | `24576:wthBrJrd+oG2TH2tVfoV5hmpbh0XOBIYplgGMo7wMo7DHDAOLiE:wtNrdSqWtVfoVTmpms7e7DH0OLiE`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:
mmc.exe

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mmc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\mmc.exe](mmc.exe-26F0B79F5A4797E4D06D164E650FC872.md) | 35
[C:\Windows\system32\mmc.exe](mmc.exe-E1328E5A4A87C376927DB685110F8D6F.md) | 35
[C:\WINDOWS\SysWOW64\mmc.exe](mmc.exe-E92C9CCE925FAF5CF45308F855F10016.md) | 29


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# mmc

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Using mmc command-line options, you can open a specific **mmc** console, open **mmc** in author mode, or specify that the 32-bit or 64-bit version of **mmc** is opened.

## Syntax

```
mmc <path>\<filename>.msc [/a] [/64] [/32]
```

### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<path>\<filename>.msc` | starts **mmc** and opens a saved console. You need to specify the complete path and file name for the saved console file. If you do not specify a console file, **mmc** opens a new console. |
| /a | Opens a saved console in author mode.  Used to make changes to saved consoles. |
| /64 | Opens the 64-bit version of **mmc** (mmc64). Use this option only if you are running a Microsoft 64-bit operating system and want to use a 64-bit snap-in. |
| /32 | Opens the 32-bit version of **mmc** (mmc32). When running a Microsoft 64-bit operating system, you can run 32-bit snap-ins by opening mmc with this command-line option when you have 32-bit only snap-ins. |
| /? | Displays help at the command prompt. |

## Remarks

- You can use environment variables to create command lines or shortcuts that don't depend on the explicit location of console files. For instance, if the path to a console file is in the system folder (for example, **mmc c:\winnt\system32\console_name.msc**), you can use the expandable data string **%systemroot%** to specify the location (**mmc%systemroot%\system32\console_name.msc**). This may be useful if you're delegating tasks to people in your organization who are working on different computers.

- When consoles are opened using the **/a** option, they're opened in author mode, regardless of their default mode. This doesn't permanently change the default mode setting for files; when you omit this option, mmc opens console files according to their default mode settings.

- After you open **mmc** or a console file in author mode, you can open any existing console by clicking **Open** on the **Console** menu.

- You can use the command line to create shortcuts for opening **mmc** and saved consoles. A command-line command works with the **Run** command on the **Start** menu, in any command-prompt window, in shortcuts, or in any batch file or program that calls the command.

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


