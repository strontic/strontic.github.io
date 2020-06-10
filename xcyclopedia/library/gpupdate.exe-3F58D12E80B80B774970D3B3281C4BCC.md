
# gpupdate.exe 
* File Path: `C:\Windows\SysWOW64\gpupdate.exe`
* Description: Microsoft Group Policy Update Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `3F58D12E80B80B774970D3B3281C4BCC`
SHA1 | `F5704E23CEE07E0B2E5A556DC00C77ABAFB0069F`
SHA256 | `FDC5B3487347F4F29CE6E407BB0CE886DA0A0D965384629FB4C0C6BBC6ECD4FC`
SHA384 | `0D6AA4C11AD0FD550C42BCF1601F800DF74838C05CB6A38D77D51BD943370922579BE7E00845ABA4AE396D83D8D795D1`
SHA415 | `4620797FC76F1F1ABB0756AFDFE542B6EDDD6ED9F0D9DEF697711C8B517C2D0193B81A8E6F1ABA38FD0EDA9207E7589AC0ACD9C91F13BA418773120AD0D7AB7E`
SSDEEP | `384:EUQsKmCDW+ibFRcws23XgOYeMhX1Q1P2IRCggS5b4slkK5TJWFXDW:EUQlFws8wst2ICggSmslBJQ`

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
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: GPUpdate.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


