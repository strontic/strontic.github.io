
# djoin.exe 

* File Path: `C:\WINDOWS\system32\djoin.exe`
* Description: Unattended Setup Generic Command For Domain Join
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FC389A4A4EE92F6472F7A19849AC7DF4`
SHA1 | `03DD66C468D4AE21A5B495204571D89F01B1A53C`
SHA256 | `110082DDD72069DBC9A64FCA588DB41E6C2049CF2860CA51DE3C14A175609AD5`
SHA384 | `B4B4A0EC92E43DFB614056A533766688359A17036FA0076A1FA34C329690F75148662480E2845E9157182E024791F0CF`
SHA512 | `AAC75C26BC9CE73C77B8B97FA551D983FF282D907EE1B8E2FCC98BB78C0E0D6F6722CB2D5EC4B8FD0021E4EB4CC52935AAA45CC2AC4FF4B026C556B6ECD38B60`
SSDEEP | `768:3TEB5BmzKrhhEghX5uPewgHIUajrWQy9N0G9Bkj2sMIj8FY8MEyGpqAJrb0L/YO7:DknrhthAp22CfBkj2s3GtywzJXGMyQJ`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: djoin.exe [/OPTIONS]

  /PROVISION  - Provision a computer account in the domain
      /DOMAIN <Name> - <Name> of the domain to join
      /MACHINE <Name> - Host <Name> of the computer joining the domain
      /MACHINEOU <OU> - Optional <OU> where the account is created
      /DCNAME <DC> - Optional <DC> to target for account creation
      /REUSE - Reuse any existing account (password will be reset)
      /SAVEFILE <FilePath> - Save provisioning data to a file at <FilePath>
      /NOSEARCH - Skip account conflict detection, requires DCNAME (faster)
      /DOWNLEVEL - Support using a Windows Server 2008 DC or earlier
      /PRINTBLOB - Return base64 encoded metadata blob for an answer file
      /DEFPWD - Use default machine account password (not recommended)
      /ROOTCACERTS - Opt. include root Certificate Authority certificates.
      /CERTTEMPLATE <Name> - Optional <Name> of machine certificate template.
                             Includes root Certificate Authority certificates.
      /POLICYNAMES <Name(s)> - Opt. semicolon-separated list of policy names.
                               Each name is the displayName of the GPO in AD.
      /POLICYPATHS <Path(s)> - Opt. semicolon-separated list of policy paths.
                               Each path is a path to a registry policy file.
      /NETBIOS <Name> - Opt. Netbios <Name> of the computer joining the domain.
      /PSITE <Name> - Opt. <Name> of persistent site to put the computer joining
                      the domain in.
      /DSITE <Name> - Opt. <Name> of dynamic site to initially put the computer 
                      joining the domain in.
      /PRIMARYDNS <Name> - Opt. <Name> of primary DNS domain of the computer
                           joining the domain.

  /REQUESTODJ  - Request offline domain join at next boot
      /LOADFILE <FilePath> - <FilePath> specified previously via /SAVEFILE
      /WINDOWSPATH <Path> - <Path> to the Windows directory in an offline image
      /LOCALOS - Allows /WINDOWSPATH to specify the locally running OS.
                 This command must be run as a local Administrator.
                 This option requires a reboot for changes to be applied.
      
Examples:

To provision a computer account in the domain:
djoin.exe /PROVISION /DOMAIN <DomainName> /MACHINE <MachineName>
          /SAVEFILE <FilePath>
          Note: Other parameters are optional
          
To request the local machine to perform an offline domain join:
djoin.exe /REQUESTODJ /LOADFILE <FilePath> /WINDOWSPATH <Path>
          Note: Other parameters are optional
The parameter is incorrect.

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

* Original Filename: djoin.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


