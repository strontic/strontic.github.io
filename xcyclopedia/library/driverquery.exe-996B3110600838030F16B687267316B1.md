
# driverquery.exe 
* File Path: `C:\Windows\system32\driverquery.exe`
* Description: Queries the drivers on a system
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `996B3110600838030F16B687267316B1`
SHA1 | `82D6F1F5AAF4164A176A6F005E586279E19C53E2`
SHA256 | `C201D26820B30BDCA8FCDBA7F043EF5A191F6FA1FF8A82F7A56EA6FE449BA4C7`
SHA384 | `438A5A316F7CE4BD789A050126BF26B32304F19CB9AABDD91E3F446F1D4D57CAFB2B1E2AC8D3ED4745433882057D26C5`
SHA415 | `6D281F089DF8E262195FB9E4939F2F2A4F44012ABAD8741A2E609E73C6E9EFECD15057AB63FF86507EE5E417AC299C193EB8B6E4D993DFB0EAA97AAFE948E040`
SSDEEP | `1536:G7Wb3B2Zx9F7bEF405V2zfj4qXlOSJRiLxYZG8mmVoxqpXN:AO296uzfj4oELLQoxqP`

## Runtime Data
### Usage (stdout):
```Batchfile

DRIVERQUERY [/S system [/U username [/P [password]]]]
              [/FO format] [/NH] [/SI] [/V] 
Description:
    Enables an administrator to display a list of 
    installed device drivers.

Parameter List:
      /S     system           Specifies the remote system to connect to.

      /U     [domain\]user    Specifies the user context 
                              under which the command should execute.

      /P     [password]       Specify the password for the given 
                              user context.

      /FO    format           Specifies the type of output to display.
                              Valid values to be passed with the
                              switch are "TABLE", "LIST", "CSV".

      /NH                     Specifies that the "Column Header" 
                              should not be displayed. Valid for  
                              "TABLE" and "CSV" format only.

      /SI                     Provides information about signed drivers.

      /V                      Displays verbose output. Not valid 
                              for signed drivers.

      /?                      Displays this help message.

Examples:
    DRIVERQUERY
    DRIVERQUERY /FO CSV /SI
    DRIVERQUERY /NH
    DRIVERQUERY /S ipaddress /U user /V 
    DRIVERQUERY /S system /U domain\user /P password /FO LIST

```

### Usage (stderr):
```Batchfile
ERROR: Invalid argument/option - '-help'.
Type "DRIVERQUERY /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: drvqry.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


