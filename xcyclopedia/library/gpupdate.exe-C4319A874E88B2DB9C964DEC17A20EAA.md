
# gpupdate.exe 

* File Path: `C:\WINDOWS\SysWOW64\gpupdate.exe`
* Description: Microsoft Group Policy Update Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C4319A874E88B2DB9C964DEC17A20EAA`
SHA1 | `A4219E709B6D81E33B16857BDA709387F5ECC0C2`
SHA256 | `FB823E865DCC0BCBE540DA48AC027405757D50D46D689F92D61FF7867025D488`
SHA384 | `9E0E02A2AA2C2DF0D2973BC41224C89C9D01BA000E0E3C002E9B670116158418110B2C09AB2D9B5466CB4A5CEC0654A2`
SHA415 | `2CFAB33B164DF4419475EF52E9C219591209579CCC08A9742E796C99969BA8322B144503A6C6AAD657E6437D6B6B9D9D534F6A16CEB955609200D4D8B9D3D228`
SSDEEP | `384:VDlRT3ksKmxTDxuioN9m/2fg9OvR/Q0Rdw4/xpyWFRDWC:PJ0lUDuV5pjw4ppP`

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

* Original Filename: GPUpdate.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


