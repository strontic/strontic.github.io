
# print.exe 

* File Path: `C:\Windows\SysWOW64\print.exe`
* Description: Print Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4069CD49DAF015AEDF61BF092C4A3E1E`
SHA1 | `D533FB346B8B9B8FCBB2DF3496F9A561E1C345DC`
SHA256 | `A936F6B1EEA36876AA26CB02B3E52270F1361DE77847ADB170121C83385AA77E`
SHA384 | `020B62568AB84EE4C97E85402E2176EF37324C7811F0560C7BEB032EE21E5BA64AE34031C75686035A7D60E3370DCE4C`
SHA512 | `521C74FB0537341A8312D37546DBE8989C53EC01A0C60423D58B8CB84A7A0616611CCCAE79FA5CB592240899741215B71049491D089B6B64EC675F7046669E09`
SSDEEP | `192:oKQl/nVyJiwKWjYplI7U/aNXqBXT4CDmlSlLtf05T8k9W8UW6:oK8/Vmio7U/aNXqF41lSlJfS9W8UW`

## Runtime Data

### Usage (stdout):
```Batchfile
Prints a text file.

PRINT [/D:device] [[drive:][path]filename[...]]

   /D:device   Specifies a print device.


```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Print.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# print



Sends a text file to a printer.



## Syntax

```
Print [/d:<PrinterName>] [<Drive>:][<Path>]<FileName>[ ...]
```

### Parameters

|Parameter|Description|
|---------|-----------|
|/d:\<PrinterName>|Specifies the printer that you want to print the job. To print to a locally connected printer, specify the port on your computer where the printer is connected.</br>-   Valid values for parallel ports are LPT1, LPT2, and LPT3.</br>-   Valid values for serial ports are COM1, COM2, COM3, and COM4.</br>You can also specify a network printer by using its queue name (\\\\*ServerName*\*PrinterName*). If you do not specify a printer, the print job is sent to LPT1 by default.|
|\<Drive>:|Specifies the logical or physical drive where the file you want to print is located. This parameter is not required if the file you want to print is located on the current drive.|
|\<Path>|Specifies the location of the file you want to print. This parameter is not required if the file you want to print is located in the current directory.|
|\<FileName>[ ...]|Required. Specifies the file you want to print. You can include multiple files in one command.|
|/?|Displays help at the command prompt.|

## Remarks

-   A file can print in the background if you send it to a printer connected to a serial or parallel port on the local computer.
-   You can perform many configuration tasks from the command prompt by using the **Mode** command.

    See [Mode](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/mode.md) for more information about:  
    -   Configuring a printer connected to a parallel port
    -   Configuring a printer connected to a serial port
    -   Displaying the status of a printer
    -   Preparing a printer for code page switching

## Examples

To send the file Report.txt in the current directory to a printer connected to LPT2 on the local computer, type:
```
print /d:lpt2 report.txt
```
To send the file Report.txt in the c:\Accounting directory to the Printer1 print queue on the \\\\CopyRoom server, type:
```
print /d:\\copyroom\printer1 c:\accounting\report.txt 
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

[Print Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/print-command-reference.md)

[Mode](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/mode.md)

---


MIT License. Copyright (c) 2020 Strontic.


