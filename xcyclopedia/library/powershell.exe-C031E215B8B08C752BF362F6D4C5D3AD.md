---
title: powershell.exe | Windows PowerShell
---

# powershell.exe 

* File Path: `C:\windows\system32\WindowsPowerShell\v1.0\powershell.exe`
* Description: Windows PowerShell

## Hashes

Type | Hash
-- | --
MD5 | `C031E215B8B08C752BF362F6D4C5D3AD`
SHA1 | `9F1E24917EF96BBB339F4E2A226ACAFD1009F47B`
SHA256 | `840E1F9DC5A29BEBF01626822D7390251E9CF05BB3560BA7B68BDB8A41CF08E3`
SHA384 | `6D51041814E3A714461FFD740A4627C03AF5E9FFBC8FDC7CA6795DEBF0D45D2FC86FC08A5E92FF5C06F1231729D09259`
SHA512 | `25B33E428D6B130E75F14F93BE39A2D87EB6FC658993E4545A0DD5C0712BF453DC64DB3B41A9142CFD005B324164D0F8F615C6ECEBB498EB162A410762833BE0`
SSDEEP | `6144:SkdhWg9x2CyRyCXBgoDhzoNKXzJ7BapCK5d3klRzULOnWyjLsPhAQzqO:pdO7RZgQhIKXzJ4pdd3klnnWosPhnzq`

## Signature

* Status: The file C:\windows\system32\WindowsPowerShell\v1.0\powershell.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: PowerShell.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17396 (winblue_r4.141007-2030)
* Product Version: 6.3.9600.17396
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-097CE5761C89434367598B34FE32893B.md) | 79
[C:\Windows\system32\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-7353F60B1739074EB17C5F4DDDEFE239.md) | 74
[C:\WINDOWS\system32\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-CDA48FC75952AD12D99E526D0B6BF70A.md) | 71
[C:\Windows\system32\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-F8278DB78BE164632C57002E82B07813.md) | 75
[C:\Windows\SysWOW64\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-5B16D54F2AE6B74DCF863BC0F5E502B5.md) | 74
[C:\Windows\SysWOW64\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-65D86C34814C02569E2AD53FD24E7F61.md) | 75
[C:\Windows\SysWOW64\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-83767E18DB29B51A804A9E312D0ED99C.md) | 75
[C:\WINDOWS\SysWOW64\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-BCC5A6493E0641AA1E60CBF69469E579.md) | 71
[C:\windows\SysWOW64\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-EF8FA4F195C6239273C100AB370FCFDC.md) | 91

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## PowerShell

Windows PowerShell is a task-based command-line shell and scripting language designed especially for system administration. Built on the .NET Framework, Windows PowerShell helps IT professionals and power users control and automate the administration of the Windows operating system and applications that run on Windows.

### Using PowerShell.exe

The **PowerShell.exe** command-line tool starts a Windows PowerShell session in a Command Prompt window. When you use **PowerShell.exe**, you can use its optional parameters to customize the session. For example, you can start a session that uses a particular execution policy or one that excludes a Windows PowerShell profile. Otherwise, the session is the same as any session that is started in the Windows PowerShell console.

- To start a Windows PowerShell session in a Command Prompt window, type `PowerShell`. A **PS** prefix is added to the command prompt to indicate that you are in a Windows PowerShell session.

- To start a session with a particular execution policy, use the **ExecutionPolicy** parameter, and type:

    ```powershell
    PowerShell.exe -ExecutionPolicy Restricted
    ```

- To start a Windows PowerShell session without your Windows PowerShell profiles, use the **NoProfile** parameter, and type:

    ```powershell
    PowerShell.exe -NoProfile
    ```

- To start a session , use the **ExecutionPolicy** parameter, and type:

    ```powershell
    PowerShell.exe -ExecutionPolicy Restricted
    ```

- To see the PowerShell.exe help file, type:

    ```powershell
    PowerShell.exe -help
    PowerShell.exe -?
    PowerShell.exe /?
    ```

- To end a Windows PowerShell session in a Command Prompt window, type `exit`. The typical command prompt returns.

#### Remarks

- For a complete list of the **PowerShell.exe** command-line parameters, see [about_PowerShell.Exe](/powershell/module/microsoft.powershell.core/about/about_powershell_exe).

- For information about other ways to start Windows PowerShell, see [Starting Windows PowerShell](/powershell/scripting/windows-powershell/starting-windows-powershell).

- Windows PowerShell runs on the Server Core installation option of Windows Server operating systems. However, features that require a graphic user interface, such as the [Windows PowerShell Integrated Scripting Environment (ISE)](/previous-versions/hh849182(v=technet.10)), and the [Out-GridView](/powershell/module/microsoft.powershell.utility/out-gridview) and [Show-Command](/powershell/module/microsoft.powershell.utility/show-command) cmdlets, don't run on Server Core installations.

### Additional References

- [about_PowerShell.Exe](/powershell/module/microsoft.powershell.core/about/about_powershell_exe)

- [about_PowerShell_Ise.exe](/powershell/module/microsoft.powershell.core/about/about_powershell_ise_exe)

- [Windows PowerShell](/powershell/)

---



MIT License. Copyright (c) 2020 Strontic.


