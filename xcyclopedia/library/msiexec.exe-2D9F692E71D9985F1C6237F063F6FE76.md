
# msiexec.exe 

* File Path: `C:\WINDOWS\system32\msiexec.exe`
* Description: Windows installer
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `2D9F692E71D9985F1C6237F063F6FE76`
SHA1 | `8DFAE441E3885EE393BFCE27B6D1A6E32566E541`
SHA256 | `199B3890D28A1F5906F4014E73615A268B3C4414F1F71697BF13E0D464258D54`
SHA384 | `1FF9731437BC2AA4E4C8619B8E76C5F7E8FE49072FD329E13C08597BC1937D9779DED6E47102BD1613F66F5CEA64C261`
SHA512 | `2B887A9977B2B67F93B4170F0DD9EC5E518D7755BBE094A4559EF373D65701A27F80CF2EB22B2C1AEA5DC5DB125BF117713721A12B19BBDBDCA2722F4386B44A`
SSDEEP | `1536:G8/YjxjAOTVgGtAwGNcXqm4hTx4rPm4y6a:G8wtMn9NFdhTx4rPdy6a`

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

* Original Filename: msiexec.exe.mui
* Product Name: Windows Installer - Unicode
* Company Name: Microsoft Corporation
* File Version: 5.0.18362.1 (WinBuild.160101.0800)
* Product Version: 5.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# msiexec

Provides the means to install, modify, and perform operations on Windows Installer from the command line.

## Install options

Set the install type for launching an installation package.

### Syntax

```
msiexec.exe [/i][/a][/j{u|m|/g|/t}][/x] <path_to_package>
```

#### Parameters

| Parameter | Description |
| ------- | -------- |
| /i | Specifies normal installation. |
| /a | Specifies administrative installation. |
| /ju | Advertise the product to the current user. |
| /jm | Advertise the product to all users. |
| /j/g | Specifies the language identifier used by the advertised package. |
| /j/t | Applies transform to the advertised package. |
| /x | Uninstalls the package. |
| `<path_to_package>` | Specifies the location and name of the installation package file. |

#### Examples

To install a package named *example.msi* from the C: drive, using a normal installation process, type:

```
msiexec.exe /i "C:\example.msi"
```

## Display options

You can configure what a user sees during the installation process, based on your target environment. For example, if you're distributing a package to all clients for manual installation, there should be a full UI. However, if you're deploying a package using Group Policy, which requires no user interaction, there should be no UI involved.

### Syntax

```
msiexec.exe /i <path_to_package> [/quiet][/passive][/q{n|b|r|f}]
```

#### Parameters

| Parameter | Description |
| ------- | -------- |
| `<path_to_package>` | Specifies the location and name of the installation package file. |
| /quiet | Specifies quiet mode, which means there's no user interaction required. |
| /passive | Specifies unattended mode, which means the installation only shows a progress bar. |
| /qn | Specifies there's no UI during the installation process. |
| /qn+ | Specifies there's no UI during the installation process, except for a final dialog box at the end. |
| /qb | Specifies there's a basic UI during the installation process. |
| /qb+ | Specifies there's a basic UI during the installation process, including a final dialog box at the end. |
| /qr | Specifies a reduced UI experience during the installation process. |
| /qf | Specifies a full UI experience during the installation process. |

##### Remarks

- The modal box isn't shown if the installation is cancelled by the user. You can use **qb+!** or **qb!+** to hide the **CANCEL** button.

#### Examples

To install package *C:\example.msi*, using a normal installation process and no UI, type:

```
msiexec.exe /i "C:\example.msi" /qn
```

## Restart options

If your installation package overwrites files or attempts to change files that are in use, a reboot might be required before the installation completes.

### Syntax

```
msiexec.exe /i <path_to_package> [/norestart][/promptrestart][/forcerestart]
```

#### Parameters

| Parameter | Description |
| ------- | -------- |
| `<path_to_package>` | Specifies the location and name of the installation package file. |
| /norestart | Stops the device from restarting after the installation completes. |
| /promptrestart | Prompts the user if a reboot is required. |
| /forcerestart | Restarts the device after the installation completes. |

#### Examples

To install package *C:\example.msi*, using a normal installation process with no reboot at the end, type:

```
msiexec.exe /i "C:\example.msi" /norestart
```

## Logging options

If you need to debug your installation package, you can set the parameters to create a log file with specific information.

### Syntax

```
msiexec.exe [/i][/x] <path_to_package> [/L{i|w|e|a|r|u|c|m|o|p|v|x+|!|*}] <path_to_log>
```

#### Parameters

| Parameter | Description |
| ------- | -------- |
| /i | Specifies normal installation. |
| /x | Uninstalls the package. |
| `<path_to_package>` | Specifies the location and name of the installation package file. |
| /li | Turns on logging and includes status messages in the output log file. |
| /lw | Turns on logging and includes non-fatal warnings in the output log file. |
| /le | Turns on logging and includes all error messages in the output log file. |
| /la | Turns on logging and includes information about when an action started in the output log file. |
| /lr | Turns on logging and includes action-specific records in the output log file. |
| /lu | Turns on logging and includes user request information in the output log file. |
| /lc | Turns on logging and includes the initial UI parameters in the output log file. |
| /lm | Turns on logging and includes out-of-memory or fatal exit information in the output log file. |
| /lo | Turns on logging and includes out-of-disk-space messages in the output log file. |
| /lp | Turns on logging and includes terminal properties in the output log file. |
| /lp | Turns on logging and includes terminal properties in the output log file. |
| /lv | Turns on logging and includes verbose output in the output log file. |
| /lp | Turns on logging and includes terminal properties in the output log file. |
| /lx | Turns on logging and includes extra debugging information in the output log file. |
| /l+ | Turns on logging and appends the information to an existing log file. |
| /l! | Turns on logging and flushes each line to the log file. |
| /l* | Turns on logging and logs all information, except verbose information (**/lv**) or extra debugging information (**/lx**). |
| `<path_to_logfile>` | Specifies the location and name for the output log file. |

#### Examples

To install package *C:\example.msi*, using a normal installation process with all logging information provided, including verbose output, and storing the output log file at *C:\package.log*, type:

```
msiexec.exe /i "C:\example.msi" /L*V "C:\package.log"
```

## Update options

You can apply or remove updates using an installation package.

### Syntax

```
msiexec.exe [/p][/update][/uninstall[/package<product_code_of_package>]] <path_to_package>
```

#### Parameters

| Parameter | Description |
| ------- | -------- |
| /p | Installs a patch. If you're installing silently, you must also set the REINSTALLMODE property to *ecmus* and REINSTALL to *ALL*. Otherwise, the patch only updates the MSI cached on the target device. |
| /update | Install patches option. If you're applying multiple updates, you must separate them using a semi-colon (;). |
| /package | Installs or configures a product. |

#### Examples

```
msiexec.exe /p "C:\MyPatch.msp"
msiexec.exe /p "C:\MyPatch.msp" /qb REINSTALLMODE="ecmus" REINSTALL="ALL"
msiexec.exe /update "C:\MyPatch.msp"
```

```
msiexec.exe /uninstall {1BCBF52C-CD1B-454D-AEF7-852F73967318} /package {AAD3D77A-7476-469F-ADF4-04424124E91D}
```

Where the first GUID is the patch GUID, and the second one is the MSI product code to which the patch was applied.

## Repair options

You can use this command to repair an installed package.

### Syntax

```
msiexec.exe [/f{p|o|e|d|c|a|u|m|s|v}] <product_code>
```

#### Parameters

| Parameter | Description |
| ------- | -------- |
| /fp | Repairs the package if a file is missing. |
| /fo | Repairs the package if a file is missing, or if an older version is installed. |
| /fe | Repairs the package if file is missing, or if an equal or older version is installed. |
| /fd | Repairs the package if file is missing, or if a different version is installed. |
| /fc | Repairs the package if file is missing, or if checksum does not match the calculated value. |
| /fa | Forces all files to be reinstalled. |
| /fu | Repairs all the required user-specific registry entries. |
| /fm | Repairs all the required computer-specific registry entries. |
| /fs | Repairs all existing shortcuts. |
| /fc | Runs from source and re-caches the local package. |

#### Examples

To force all files to be reinstalled based on the MSI product code to be repaired, *{AAD3D77A-7476-469F-ADF4-04424124E91D}*, type:

```
msiexec.exe /fa {AAD3D77A-7476-469F-ADF4-04424124E91D}
```

## Set public properties

You can set public properties through this command. For information about the available properties and how to set them, see [Public Properties](https://docs.microsoft.com/windows/win32/msi/public-properties).

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Msiexec.exe Command-Line Options](https://docs.microsoft.com/windows/win32/msi/command-line-options)

- [Standard Installer Command-Line Options](https://docs.microsoft.com/windows/win32/msi/standard-installer-command-line-options)

---


MIT License. Copyright (c) 2020 Strontic.


