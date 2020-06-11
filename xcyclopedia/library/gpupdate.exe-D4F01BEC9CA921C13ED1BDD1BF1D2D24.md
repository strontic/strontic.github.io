
# gpupdate.exe 

* File Path: `C:\WINDOWS\system32\gpupdate.exe`
* Description: Microsoft Group Policy Update Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `D4F01BEC9CA921C13ED1BDD1BF1D2D24`
SHA1 | `1529CB7F7DFA798337F781A71B583371E1D43F2B`
SHA256 | `FE428F64B6920CBD542BF7097F009A576673888967CB5AE8803D310667ED428D`
SHA384 | `D77B0A254F9E11B410825D3276EBEEE37990201D4A4DABDE58E58689FC6B12EB4CBA2FEE37ED982AD19E3B0DA29FE06A`
SHA415 | `A264036B7043D475A9FB6A8C4D08860F3BC26036DF84173710B07E47D4B4272D20C2AE63A2F5FC0E89409A7DB3A247AF51E1C908B4181F17C1874CA9C893AFD5`
SSDEEP | `384:bFhlVqanxKd/cz0+i2nfXdtN2gGM+dVbFd5sBOuROnPl2R/WoDbyEV4uee0hKEou:b3qaxKVczmfdr8yPl0jVV4je0hKEof`

## Runtime Data

### Usage (stdout):
```Batchfile
Description:  Updates multiple Group Policy settings.

Syntax:  Gpupdate [/Target:{Computer | User}] [/Force] [/Wait:<value>]
     [/Logoff] [/Boot] [/Sync] 

Parameters:

Value                      Description
/Target:{Computer | User}  Specifies that only User or only Computer
                            policy settings are updated. By default,
                            both User and Computer policy settings are
                            updated.

/Force                     Reapplies all policy settings. By default,
                            only policy settings that have changed are
                            applied.

/Wait:{value}              Sets the number of seconds to wait for policy
                            processing to finish. The default is 600
                            seconds. The value '0' means not to wait.
                            The value '-1' means to wait indefinitely.
                            When the time limit is exceeded, the command
                            prompt returns, but policy processing
                            continues.

/Logoff                    Causes a logoff after the Group Policy settings
                            have been updated. This is required for
                            those Group Policy client-side extensions
                            that do not process policy on a background
                            update cycle but do process policy when a
                            user logs on. Examples include user-targeted
                            Software Installation and Folder Redirection.
                            This option has no effect if there are no
                            extensions called that require a logoff.

/Boot                      Causes a computer restart after the Group Policy settings
                            are applied. This is required for those
                            Group Policy client-side extensions that do
                            not process policy on a background update cycle
                            but do process policy at computer startup.
                            Examples include computer-targeted Software
                            Installation. This option has no effect if
                            there are no extensions called that require
                            a restart.

/Sync                      Causes the next foreground policy application to
                            be done synchronously. Foreground policy
                            applications occur at computer start up and user
                            logon. You can specify this for the user,
                            computer or both using the /Target parameter.
                            The /Force and /Wait parameters will be ignored
                            if specified.


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

* Original Filename: GPUpdate.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


