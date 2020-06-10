
# djoin.exe 
* File Path: `C:\Windows\system32\djoin.exe`
* Description: Unattended Setup Generic Command For Domain Join
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `111E795B25B9414BE6E43A29093E8C45`
SHA1 | `C063495FEF959F6000B0B486AA8A2E7585C03BE1`
SHA256 | `FBC1AE96D1EE1A883658C6F9101590777F95F480010ACAC4E7934505B405F507`
SHA384 | `6F6A8E24EC115B184FDA07DBF6D725EE9850017F4D1A056FD0083AA929E41FA181DC99E5683B9C953AB6D56CB3054003`
SHA415 | `E131E35A133BDF2B6E8926F04413C88C86F1D452F40A26B51C56D1001BD448349C15264F20E7C8A50A6446EEBCA9ED3D2F62A9370E08E328C231F5FB120587B7`
SSDEEP | `768:0E8pWPUVCowgo/fTDGbgNcwYKNgiZcRN5yR/2Ij8FH9Bfv/hX3bfhbj5UmhRQJ6J:D7zzgoTDCUPHZcRiRFGHnvNLfZKCRQJ`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: djoin.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


