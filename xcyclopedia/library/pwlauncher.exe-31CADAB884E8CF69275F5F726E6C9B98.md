
# pwlauncher.exe 

* File Path: `C:\WINDOWS\system32\pwlauncher.exe`
* Description: Windows To Go Startup Options Command Line Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `31CADAB884E8CF69275F5F726E6C9B98`
SHA1 | `29BEC3A35E3FAA710EBF4D5B810DC05EC86682F5`
SHA256 | `9AC4CB523107CE4FC5DC9A122124BA51B053FE6FF572B169701A69AC46939A0B`
SHA384 | `F30C4A24CD54F6680227397FF9EFE98827FB7DA969E4CE2EB07BE7A93630E6DD35B7C13AB0FDE8F01985B247218F25AC`
SHA512 | `409113EF3783181ECF952FD69C192EFB3560B3541A85F57075E4BB7A25B3F5811D282E9DC98934D643630CC2D60ACFCA4A7417CDC1B92E89BED6F34574F0A885`
SSDEEP | `768:BLc1zbEp2MX8Dr8MqgdKgLMJc2Wa3CM8lB:BAm/SHegLec2R3CNlB`

## Runtime Data

### Usage (stdout):
```Batchfile
pwlauncher.exe - Windows To Go startup options command-line tool.

The pwlauncher.exe command-line tool is used to query or change your Windows To
Go startup options.

pwlauncher [/enable | /disable]

    <<no parameter>>    Display the current state.

    /enable             Enable the startup option.

    /disable            Disable the startup option.

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

* Original Filename: pwlauncher.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# pwlauncher



Enables or disables the Windows To Go Startup Options (pwlauncher). The **pwlauncher** command-line tool allows you to configure the computer to boot into a Windows To Go workspace automatically (assuming one is present), without requiring you to enter your firmware or change your startup options.



## Syntax

```
Pwlauncher {/enable | /disable}
```

### Parameters

|Parameter|Description|
|---------|-----------|
|/enable|Enables Windows To Go startup options so that the computer will automatically boot from a USB device when present|
|/disable|Disables Windows To Go startup options so that the computer cannot be booted from a USB device unless configured manually in the firmware.|
|/?|Displays help at the command prompt.|

## Remarks

The biggest hurdle for a user wanting to use Windows To Go is getting their computer to boot from USB. This is traditionally done by entering the firmware and trying different configuration options until the computer is configured properly. This is not a simple undertaking for most users and is extremely risky because the firmware contains options that can render a system unusable if used incorrectly. To help alleviate this problem, Windows 8and later operating systems include a feature named Windows To Go Startup Options that allows a user to configure their computer to boot from USB from within Windows-without ever entering their firmware, as long as their firmware supports booting from USB. Enabling a system to always boot from USB first has implications that you should consider. For example, a USB device that includes malware could be booted inadvertently to compromise the system, or multiple USB drives could be plugged in to cause a boot conflict. For this reason, the default configuration has the Windows To Go Startup Options disabled by default. In addition, administrator privileges are required to configure Windows To Go Startup Options. If you enable the Windows To Go startup options using the pwlauncher command-line tool or the **Change Windows To Go Startup Options** app the computer will attempt to boot from any USB device that is inserted into the computer before it is started.

## Examples

To shows how you can use the **pwlauncher** command to enable boot from USB:
```
Pwlauncher /enable
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


