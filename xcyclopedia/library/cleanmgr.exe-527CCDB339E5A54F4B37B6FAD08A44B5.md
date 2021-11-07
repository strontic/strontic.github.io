---
title: cleanmgr.exe | Disk Space Cleanup Manager for Windows
excerpt: What is cleanmgr.exe?
---

# cleanmgr.exe 

* File Path: `C:\Windows\SysWOW64\cleanmgr.exe`
* Description: Disk Space Cleanup Manager for Windows

## Screenshot

![cleanmgr.exe](screenshots/cleanmgr.exe-1920470998932423575D36C07F8BC97E.png)
![cleanmgr.exe](screenshots/cleanmgr.exe-5AB8F80E61D780F31585E612B83FFFAD-5.png)
![cleanmgr.exe](screenshots/cleanmgr.exe-B6A5162D28FDCB87869A2ED87F46C8A6-4.png)

## Hashes

Type | Hash
-- | --
MD5 | `527CCDB339E5A54F4B37B6FAD08A44B5`
SHA1 | `081F4F602AFBB0A2985D76174DAC170B6F6E14BD`
SHA256 | `A06C4C073BF300F1F18014D4F2D082698D1005912B632742375C0E50A03EA488`
SHA384 | `068C06D4792C57171858DD221E684FC1D664E6A31492ED9CFB0DB0279BF32A310474C6DF2BD017BC651381848F80262C`
SHA512 | `1C8ED1A2510A5DA7A06521D8149999C0032BDF5C8F7CF408F147FD00DC8D9FC28C1A1548CE2C692C19931246D947CA583C88E869A6F7D0FC4BEBF706CA738B91`
SSDEEP | `3072:+IEeh6cvFj2Gbb1zpmA0lyzxAEPGRvQhRkKqUa9antF5hvvJkuXpAsq:7r1pmA0UzGE+ohSKq99UF5hvv/`
IMP | `348E19DE22D552507980318E41C60C5F`
PESHA1 | `ED6E501BBB3F8D9779074A89E43DDE63809C0B3F`
PE256 | `700421B7AF53973D91C4535504407675EDB89A1D7E44737DD84E11F480961F72`

## Runtime Data

### Window Title:
USAGE

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\cleanmgr.exe.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1110_none_a8625c1886757984 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\Windows\Theme449731986 | Section
\Windows\Theme1396518710 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\cleanmgr.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CLEANMGR.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1266 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1266
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/a06c4c073bf300f1f18014d4f2d082698d1005912b632742375c0e50a03ea488/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\cleanmgr.exe](cleanmgr.exe-B6A5162D28FDCB87869A2ED87F46C8A6.md) | 71
[C:\Windows\system32\cleanmgr.exe](cleanmgr.exe-CD0D99EBE88D11F55136EAE39CCF8F6E.md) | 68
[C:\Windows\system32\cleanmgr.exe](cleanmgr.exe-D17E532DB343357FC9EBF5E559820BD4.md) | 71
[C:\Windows\system32\cleanmgr.exe](cleanmgr.exe-FC13869B5250959618FA81B9AAA2BDF8.md) | 71
[C:\Windows\SysWOW64\cleanmgr.exe](cleanmgr.exe-3DF1CA27764BE371A667B72A664B4C65.md) | 66
[C:\Windows\SysWOW64\cleanmgr.exe](cleanmgr.exe-485C3639234C59ED6BF09F73704B110E.md) | 74
[C:\Windows\SysWOW64\cleanmgr.exe](cleanmgr.exe-5AB8F80E61D780F31585E612B83FFFAD.md) | 65

## Possible Misuse

*The following table contains possible examples of `cleanmgr.exe` being misused. While `cleanmgr.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_cleanmgr.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_cleanmgr.yml) | `description: Detects the pattern of UAC Bypass using scheduled tasks and variable expansion of cleanmgr.exe (UACMe 34)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_cleanmgr.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_cleanmgr.yml) | `CommandLine\|endswith: '"\system32\cleanmgr.exe /autoclean /d C:'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | There is an auto-elevated task called SilentCleanup located in %windir%\system32\cleanmgr.exe This can be abused to elevate any file with Administrator privileges without prompting UAC (even highest level). | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## cleanmgr

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012, Windows Server 2008 R2

Clears unnecessary files from your computer's hard disk. You can use command-line options to specify that **Cleanmgr** cleans up Temp files, Internet files, downloaded files, and Recycle Bin files. You can then schedule the task to run at a specific time by using the **Scheduled Tasks** tool.

### Syntax

```
cleanmgr [/d <driveletter>] [/sageset:n]  [/sagerun:n] [/TUNEUP:n] [/LOWDISK] [/VERYLOWDISK]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /d `<driveletter>` | Specifies the drive that you want Disk Cleanup to clean.<p>**NOTE:** The **/d** option is not utilized with `/sagerun:n`. |
| /sageset:n | Displays the **Disk Cleanup Settings** dialog box and also creates a registry key to store the settings that you select. The `n` value, which is stored in the registry, allows you to specify tasks for Disk Cleanup to run. The `n` value can be any integer value from 0 to 9999. |
| /sagerun:n | Runs the specified tasks that are assigned to the n value if you use the **/sageset** option. All drives on the computer are enumerated and the selected profile runs against each drive. |
| /tuneup:n | Run **/sageset** and **/sagerun** for the same `n` . |
| /lowdisk | Run with the default settings. |
| /verylowdisk | Run with the default settings, no user prompts. |
| /? | Displays help at the command prompt. |

##### Options

The options for the files that you can specify for Disk Cleanup by using **/sageset** and **/sagerun** include:

- **Temporary Setup Files** - These are files that were created by a Setup program that is no longer running.

- **Downloaded Program Files** - Downloaded program files are ActiveX controls and Java programs that are downloaded automatically from the Internet when you view certain pages. These files are temporarily stored in the Downloaded Program Files folder on the hard disk. This option includes a View Files button so that you can see the files before Disk Cleanup removes them. The button opens the C:\Winnt\Downloaded Program Files folder.

- **Temporary Internet Files** - The Temporary Internet Files folder contains Web pages that are stored on your hard disk for quick viewing. Disk Cleanup removes these page but leaves your personalized settings for Web pages intact. This option also includes a View Files button, which opens the C:\Documents and Settings\Username\Local Settings\Temporary Internet Files\Content.IE5 folder.

- **Old Chkdsk Files** - When Chkdsk checks a disk for errors, Chkdsk might save lost file fragments as files in the root folder on the disk. These files are unnecessary.

- **Recycle Bin** - The Recycle Bin contains files that you have deleted from the computer. These files are not permanently removed until you empty the Recycle Bin. This option includes a View Files button that opens the Recycle Bin.<p>**Note:** A Recycle Bin may appear in more than one drive, for example, not just in %SystemRoot%.

- **Temporary Files** - Programs sometimes store temporary information in a Temp folder. Before a program quits, the program usually deletes this information. You can safely delete temporary files that have not been modified within the last week.

- **Temporary Offline Files** - Temporary offline files are local copies of recently used network files. These files are automatically cached so that you can use them after you disconnect from the network. A **View Files** button opens the Offline Files folder.

- **Offline Files** - Offline files are local copies of network files that you specifically want to have available offline so that you can use them after you disconnect from the network. A **View Files** button opens the Offline Files folder.

- **Compress Old Files** - Windows can compress files that you have not used recently. Compressing files saves disk space, but you can still use the files. No files are deleted. Because files are compressed at different rates, the displayed amount of disk space that you will gain is approximate. An Options button permits you to specify the number of days to wait before Disk Cleanup compresses an unused file.

- **Catalog Files for the Content Indexer** - The Indexing service speeds up and improves file searches by maintaining an index of the files that are on the disk. These Catalog files remain from a previous indexing operation and can be deleted safely.<p>**Note:** Catalog File may appear in more than one drive, for example, not just in `%SystemRoot%`.

>[!NOTE]
> If you specify cleaning up the drive that contains the Windows installation, all of these options are available on the **Disk Cleanup** tab. If you specify any other drive, only the Recycle Bin and the Catalog files for content index options are available on the **Disk Cleanup** tab.

### Examples

To run the Disk Cleanup app so that you can use its dialog box to specify options for use later, saving the settings to the set **1**, type the following:

```
cleanmgr /sageset:1
```

To run Disk Cleanup and include the options that you specified with the cleanmgr /sageset:1 command, type:

```
cleanmgr /sagerun:1
```

To run `cleanmgr /sageset:1` and `cleanmgr /sagerun:1` together, type:

```
cleanmgr /tuneup:1
```

### Additional References

- [Free up drive space in Windows 10](https://support.microsoft.com/help/12425/windows-10-free-up-drive-space)

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


