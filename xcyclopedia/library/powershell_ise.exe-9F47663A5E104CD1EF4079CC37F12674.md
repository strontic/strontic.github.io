﻿---
title: powershell_ise.exe | Windows PowerShell ISE
excerpt: What is powershell_ise.exe?
---

# powershell_ise.exe 

* File Path: `C:\WINDOWS\SysWOW64\WindowsPowerShell\v1.0\powershell_ise.exe`
* Description: Windows PowerShell ISE

## Screenshot

![powershell_ise.exe](screenshots/powershell_ise.exe-8F1F1C4EDA2CFA2073E82A409BBE35D0-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `9F47663A5E104CD1EF4079CC37F12674`
SHA1 | `25E78F7FCEA17EDA1C389857851C0BB5F07AA55B`
SHA256 | `72F9449A487F7E41F38F7A936D11B01CFF73F7DC43D7A13E020CC50940C4AE84`
SHA384 | `A839C57A695AFC0D159FDC650ECCC53A149501EA9BD62D1F13D3AC12B2D2B7CAFEF718C7B4FD65AA80815B3B2D819204`
SHA512 | `29FD3DB9B9018218EC5390A48A7CAA37AB169459B67040090D1DD085E030ED7121B1786F26CF7E17D977DFCE87D7F4C0A71B6CF0932360C450A622BEFAF1AE67`
SSDEEP | `3072:HPkVjGPsw40GLkVjqP4w6U+ToIuWNXmmZTWl/jC7gDooMLEY:vkLuZToIuUXmmZbgDooMD`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: powershell_ise.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\WindowsPowerShell\v1.0\powershell_ise.exe](powershell_ise.exe-2A02490E8930ACC10F135F86F7A4BAE9.md) | 91
[C:\WINDOWS\system32\WindowsPowerShell\v1.0\powershell_ise.exe](powershell_ise.exe-30A2792A2428CD06CFEC23ECB074889A.md) | 94
[C:\Windows\system32\WindowsPowerShell\v1.0\powershell_ise.exe](powershell_ise.exe-3F06E220C3E591F458D549B01ECCCB95.md) | 88
[C:\Windows\system32\WindowsPowerShell\v1.0\powershell_ise.exe](powershell_ise.exe-9577A63626D2536E7416494F09F0EEC2.md) | 90
[C:\Windows\system32\WindowsPowerShell\v1.0\powershell_ise.exe](powershell_ise.exe-E05920670516CC96822699E5688A79FA.md) | 91
[C:\Windows\SysWOW64\WindowsPowerShell\v1.0\powershell_ise.exe](powershell_ise.exe-0722BC6EA7EB1A21AC2FAC7BE9B4C9A6.md) | 91
[C:\Windows\SysWOW64\WindowsPowerShell\v1.0\powershell_ise.exe](powershell_ise.exe-83B61B8AE3AE5CA669E1CBB191B4852D.md) | 90
[C:\Windows\SysWOW64\WindowsPowerShell\v1.0\powershell_ise.exe](powershell_ise.exe-8F1F1C4EDA2CFA2073E82A409BBE35D0.md) | 90
[C:\WINDOWS\SysWOW64\WindowsPowerShell\v1.0\powershell_ise.exe](powershell_ise.exe-C6F1756BFE0CBE8F9E32670748F5E833.md) | 91

## Possible Misuse

*The following table contains possible examples of `powershell_ise.exe` being misused. While `powershell_ise.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\powershell_ise.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_alternate_powershell_hosts_pipe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/pipe_created/sysmon_alternate_powershell_hosts_pipe.yml) | `- '\powershell_ise.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- 'powershell_ise.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- '\powershell_ise.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- "powershell_ise.exe"`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- '\powershell_ise.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_powershell.yml) | `- '\powershell_ise.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_bitstransfer.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_bitstransfer.yml) | `- '\powershell_ise.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | 1. Open Powershell_ise as a Privileged Account | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## PowerShell_ise

Windows PowerShell Integrated Scripting Environment (ISE) is a graphical host application that enables you to read, write, run, debug, and test scripts and modules in a graphic-assisted environment. Key features such as IntelliSense, Show-Command, snippets, tab completion, syntax-coloring, visual debugging, and context-sensitive Help provide a rich scripting experience.

### Using PowerShell.exe

The **PowerShell_ISE.exe** tool starts a Windows PowerShell ISE session. When you use **PowerShell_ISE.exe**, you can use its optional parameters to open files in Windows PowerShell ISE or to start a Windows PowerShell ISE session with no profile or with a multithreaded apartment.

- To start a Windows PowerShell ISE session in a Command Prompt window, in Windows PowerShell, or at the **Start** menu, type:

  ```powershell
  PowerShell_Ise.exe
  ```

- To open a script (.ps1), script module (.psm1), module manifest (.psd1), XML file, or any other supported file in Windows PowerShell ISE, type:

  ```powershell
  PowerShell_Ise.exe <filepath>
  ```

  In Windows PowerShell 3.0, you can use the optional **File** parameter as follows:

  ```powershell
  PowerShell_Ise.exe -file <filepath>
  ```

- To start a Windows PowerShell ISE session without your Windows PowerShell profiles, use the **NoProfile** parameter. (The **NoProfile** parameter is introduced in Windows PowerShell 3.0.), type:

  ```powershell
  PowerShell_Ise.exe -NoProfile
  ```

- To see the PowerShell_ISE.exe help file, type:

    ```powershell
    PowerShell_Ise.exe -help
    PowerShell_Ise.exe -?
    PowerShell_Ise.exe /?
    ```

#### Remarks

- For a complete list of the **PowerShell_ISE.exe** command-line parameters, see [about_PowerShell_Ise.Exe](/powershell/module/microsoft.powershell.core/about/about_powershell_ise_exe).

- For information about other ways to start Windows PowerShell, see [Starting Windows PowerShell](/powershell/scripting/windows-powershell/starting-windows-powershell).

- Windows PowerShell runs on the Server Core installation option of Windows Server operating systems. However, because Windows PowerShell ISE requires a graphic user interface, it does not run on Server Core installations.

### Additional References

- [about_PowerShell_Ise.exe](/powershell/module/microsoft.powershell.core/about/about_powershell_exe)

---



MIT License. Copyright (c) 2020-2021 Strontic.


