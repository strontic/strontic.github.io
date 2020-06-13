
# powershell_ise.exe 

* File Path: `C:\WINDOWS\SysWOW64\WindowsPowerShell\v1.0\powershell_ise.exe`
* Description: Windows PowerShell ISE
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `9F47663A5E104CD1EF4079CC37F12674`
SHA1 | `25E78F7FCEA17EDA1C389857851C0BB5F07AA55B`
SHA256 | `72F9449A487F7E41F38F7A936D11B01CFF73F7DC43D7A13E020CC50940C4AE84`
SHA384 | `A839C57A695AFC0D159FDC650ECCC53A149501EA9BD62D1F13D3AC12B2D2B7CAFEF718C7B4FD65AA80815B3B2D819204`
SHA512 | `29FD3DB9B9018218EC5390A48A7CAA37AB169459B67040090D1DD085E030ED7121B1786F26CF7E17D977DFCE87D7F4C0A71B6CF0932360C450A622BEFAF1AE67`
SSDEEP | `3072:HPkVjGPsw40GLkVjqP4w6U+ToIuWNXmmZTWl/jC7gDooMLEY:vkLuZToIuUXmmZbgDooMD`

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

* Original Filename: powershell_ise.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# PowerShell_ise



Windows PowerShell Integrated Scripting Environment (ISE) is a graphical host application that enables you to read, write, run, debug, and test scripts and modules in a graphic-assisted environment. Key features such as IntelliSense, Show-Command, snippets, tab completion, syntax-coloring, visual debugging, and context-sensitive Help provide a rich scripting experience.

The **PowerShell_ISE.exe** tool starts a Windows PowerShell ISE session. When you use **PowerShell_ISE.exe**, you can use its optional parameters to open files in Windows PowerShell ISE or to start a Windows PowerShell ISE session with no profile or with a multithreaded apartment.

**PowerShell_ISE.exe** was introduced in Windows PowerShell 2.0 and expanded significantly in Windows PowerShell 3.0.

## Using PowerShell_ISE.exe

You can use **PowerShell_ISE.exe** to start and end a Windows PowerShell session as follows:
- To start a Windows PowerShell ISE session, in a Command Prompt window, in Windows PowerShell, or at the Start menu, type:
  ```
  PowerShell_Ise
  ```
- To open a script (.ps1), script module (.psm1), module manifest (.psd1), XML file, or any other supported file in Windows PowerShell ISE, use the following command format:
  ```
  PowerShell_Ise <FilePath>
  ```
  In Windows PowerShell 3.0, you can use the optional **File** parameter as follows:
  ```
  PowerShell_Ise -File <FilePath>
  ```
- To start a Windows PowerShell ISE session without your Windows PowerShell profiles, use the **NoProfile** parameter. (The **NoProfile** parameter is introduced in Windows PowerShell 3.0.)
  ```
  PowerShell_Ise -NoProfile
  ```
- To see the **PowerShell_ISE.exe** Help file in a Command Prompt window, use the following command format:
  ```
  PowerShell_Ise -help, -?, /?
  ```
  For a complete list of the **PowerShell_ISE.exe** command-line parameters, see [about_PowerShell_Ise.exe](https://go.microsoft.com/fwlink/?LinkId=256512).

## Start Windows PowerShell ISE in other ways

For information about other ways to start Windows PowerShell ISE, see [Starting Windows PowerShell](https://go.microsoft.com/fwlink/?LinkID=135259).

## Remarks

Windows PowerShell runs on the Server Core installation option of Windows Server operating systems. However, because Windows PowerShell ISE requires a graphic user interface, it does not run on Server Core installations.

## Additional References

[about_PowerShell_Ise.exe](https://go.microsoft.com/fwlink/?LinkId=256512)
[about_PowerShell.exe](https://go.microsoft.com/fwlink/?LinkID=113439)
[Windows PowerShell](https://go.microsoft.com/fwlink/?LinkID=107116)
[Scripting with Windows PowerShell](https://technet.microsoft.com/scriptcenter/dd742419)
See Also

---


MIT License. Copyright (c) 2020 Strontic.


