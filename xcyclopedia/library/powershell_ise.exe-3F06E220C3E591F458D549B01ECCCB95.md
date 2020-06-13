
# powershell_ise.exe 

* File Path: `C:\Windows\system32\WindowsPowerShell\v1.0\powershell_ise.exe`
* Description: Windows PowerShell ISE
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `3F06E220C3E591F458D549B01ECCCB95`
SHA1 | `1B26F9BCAC988CC3BE3633D56E7992C60291B9CB`
SHA256 | `C2E227A3A9668D651C9F7AF5B27C4FC198F4D043D951E6EC100BEDC5497942F7`
SHA384 | `3C7574D30ED077C6FA697D26B2B3943F6324853E7CA27117627AEA3DD00992C7FC2366A4E1D8E2D99D407A7D3C2FDC61`
SHA512 | `3DF0876818ADB1A1F44E35FB682D776B1B3046543900D1A6810A51C1850E3B4BBCDFE693BF3F35FBD4DFE302EE6BEB0DE7C0B6E6591024E0E2D8CE6AD8602EBE`
SSDEEP | `3072:7SckVjGPsw402TkVjqP4w6U+ToIuWNXmmZTWl/jC7gDooMLqV:71kluZToIuUXmmZbgDooMg`

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
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: powershell_ise.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.103 (rs1_release_inmarket.160819-1924)
* Product Version: 10.0.14393.103
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


