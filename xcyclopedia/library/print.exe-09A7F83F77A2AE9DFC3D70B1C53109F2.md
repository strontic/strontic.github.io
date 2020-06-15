
# print.exe 

* File Path: `C:\WINDOWS\system32\print.exe`
* Description: Print Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `09A7F83F77A2AE9DFC3D70B1C53109F2`
SHA1 | `F33661FB9A4ACFCD3370C2C0E4CE192861A575A0`
SHA256 | `EE6F8BBDE72BDE2E7B28E80370C61E6ADC4789103EE6C94B9584A0190C0F71A7`
SHA384 | `93686B6D04E509AD336228E9BB21F275FE66ED69721C36B6CC4F96EA2220BF639619056590059D3993BC4E486CD1D04D`
SHA512 | `C23BBAA001E7911EB732AC2E953A8381A0958E005EDE9E2BF52DE3670DE5E3EF158FBFF46D83C8DCF25D70ACA1DE1B8CA6948FF327BF8E16B6710EE7D58155D4`
SSDEEP | `192:VhNoDIoDi6I+OktNEeEaMyhvFSP90yhMIGCbhuUasjn/A9eQ2FpGOKcCOdmFWuUW:Xo+1WtnECdS2ThCVuC/AH2zPKvFWuUW`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Print.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

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


