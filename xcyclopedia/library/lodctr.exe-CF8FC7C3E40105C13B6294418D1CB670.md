
# lodctr.exe 

* File Path: `C:\WINDOWS\SysWOW64\lodctr.exe`
* Description: Load PerfMon Counters
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `CF8FC7C3E40105C13B6294418D1CB670`
SHA1 | `4DAABE128CF5BDE34C4187927288274D3C87109A`
SHA256 | `8F2A9CDA849446E9312441429F26FC6A13C2428E512EE84C58FB837D2BE8065F`
SHA384 | `D870B3BE21A1A6A704FEEECFCEA186415BF6DDB4B3F2E3F89546C777AC6935F3233C616071F44883A47D9F33EC07C73A`
SHA415 | `26AE574F982703CCD587EECC329FB7C77A53560A9C4A4CD65AEC82BFEFD2AFEE767E3A59E528883067D9E95CF717A79F022903D3A90510B180BEBD67CEE8336D`
SSDEEP | `768:tJ3ZlM8ZiyQE48ejycQTHoAug/NkSAjdA8VoczAtJuHygYnHuw7XJ:9lM8oyQEVImHoAugCSAjVVBHkHuw7XJ`

## Runtime Data

### Usage (stdout):
```Batchfile

 
LODCTR 
       Updates registry values related to performance counters. 
Usage: 
       LODCTR <INI-filename> 
             Installs counter text strings. INI-filename is the name of the 
             initialization file that contains the counter name definitions 
             and explain text for an extensible counter DLL.

       LODCTR /C:<filename> 
             Upgrades counter text strings using <filename>

       LODCTR /H:<filename> 
             Upgrades help text strings using <filename>

       LODCTR /L:<LangID> 
             Specifies the language for the /C and /H commands

       LODCTR /S:<Backup-filename> 
             Saves the current perf registry strings and info to 
             <Backup-filename>

       LODCTR /R 
             Rebuilds perf registry from scratch based on current registry 
             settings and backup INI files.

       LODCTR /R:<filename> 
             Restores perf registry strings & info using <filename>

       LODCTR /T:<service-name> 
             Sets the specified performance counter provider as trusted.

       LODCTR /Q 
             Displays performance counter provider information.

       LODCTR /Q:<service-name> 
             Displays performance counter provider information for a 
             specific provider.

       LODCTR /E:<service-name> 
             Enables the performance counter provider.

       LODCTR /D:<service-name> 
             Disables the performance counter provider.

       LODCTR /M:<Counter-Manifest> [<Installation-Path>]
             Installs a v2.0 performance counter provider using the specified 
             XML manifest. 

             The installation requires a full path to the DLL containing the 
             performance counter resources (localized  strings). The path 
             to the DLL will be determined as follows:

             If the applicationIdentity attribute in the manifest is a full 
             path, that will be used.

             Otherwise, if <Installation-Path> is provided and is a full 
             path, that will be used.

             Otherwise, if <Counter-Manifest> is a full path, the directory 
             from <Counter-Manifest> will be combined with the DLL name from 
             the applicationIdentity attribute in the manifest.

             Otherwise, the current directory will be combined with the DLL 
             name from the applicationIdentity attribute in the manifest.

Note: Any arguments with spaces in the names must be enclosed within double 
quotation marks.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: LODCTR.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


