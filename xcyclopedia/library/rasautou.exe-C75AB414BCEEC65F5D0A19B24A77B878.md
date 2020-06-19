
# rasautou.exe 

* File Path: `C:\Windows\system32\rasautou.exe`
* Description: Remote Access Dialer
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C75AB414BCEEC65F5D0A19B24A77B878`
SHA1 | `40324A18C7B4A6A2D3820CF3812DBFC6607A61E8`
SHA256 | `049A173C36F34089B4D427FA10AE3875B6AB49577C891565C2C5E5EE5C6EFD47`
SHA384 | `79EC0158BD86FC512D18A81591B24C9697D796AB61F599848BF417602F4839854512B37D04BCCE8FACC0AB3E31D34B09`
SHA512 | `420C27B8761A0A2FFC46E59CE467A7DC32E8F062F19610B7522CE55CC24EB234FC7CF3736BEEC15F1045B8ACF1D2BB576381C65D049AEEE7853602DB949FFB69`
SSDEEP | `384:jCiWZUm33JulLX7auWmPScTwhC8sWoBW:j343szWK+h1O`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: rasautou [-f phonebook] [-a address] [-e entry] [-s]

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

* Original Filename: rasdlui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `rasautou.exe` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `Name: Rasautou.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `  - Command: rasautou -d powershell.dll -p powershell -a a -e e ` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `  - Path: C:\Windows\System32\rasautou.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | ` - IOC: rasautou.exe command line containing -d and -p` | 



MIT License. Copyright (c) 2020 Strontic.


