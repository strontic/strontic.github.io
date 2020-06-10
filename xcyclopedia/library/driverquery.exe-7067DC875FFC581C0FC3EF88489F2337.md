
# driverquery.exe 
* File Path: `C:\Windows\SysWOW64\driverquery.exe`
* Description: Queries the drivers on a system
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `7067DC875FFC581C0FC3EF88489F2337`
SHA1 | `4BB4D86B70DE10F370DFB6F3B288507557652F63`
SHA256 | `8034E5DFBD3E66212FF59916536826ED259CEB9F9D85C3DF3DD01037B4619641`
SHA384 | `B93B0C3874A078C922A23FFA31156CF4D32CE2DF31B47D83B389EEAB58E2862B3BC94100E499010EC97432F13278A37C`
SHA415 | `312DF64203757B5772F2AEE1E54C76E1A3A5EED446EE25BAD59EACCDEF90F4BB44863D3580D82A29C3C7FAA3F26C7C7D75ECA40F939FFE9EC3F639CB8B682BD4`
SSDEEP | `1536:kSJkUmeeNcASrq4ccng6Bca+FyCbjf9EA1QnW8ubxE1J:AeeNdmcEYl/Fz5lbxk`

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


