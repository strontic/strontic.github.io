
# tzutil.exe 

* File Path: `C:\Windows\system32\tzutil.exe`
* Description: Windows Time Zone Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `F152E16FC4FE1EDF606D9DFAD92C5242`
SHA1 | `F18018561FE70713083BC2E269D3395A737A0861`
SHA256 | `82DD94761865BE53BA3122E0542BA05D373445B376AFACAF20B6E3AF2B33CE79`
SHA384 | `984F05065462B54596E1F715311259F1AC8D9A02112C5CD25B1E3F7C121DBD53FE2D1CA40E4B57318E9BD4C3A1C6E4DA`
SHA415 | `0DF4988648DD1123E8C83DFD885D75FF2EA4CDE06DAE2ED69B7A4F686079C8855539BC2827142096E48D378D6321AA4120A94DAD6344F21A6D45DFE52529089D`
SSDEEP | `768:Jy3gEqgeQNCkA2Qe75rpcPGqKlLtqljprTllDyVO1vTzwabxFu5TwgtL4:gwEqgJNCkA2Lrpa5fHuYHwREgtL4`

## Runtime Data

### Usage (stdout):
```Batchfile
Windows Time Zone Utility

Usage:
TZUTIL </? | /g | /s TimeZoneID[_dstoff] | /l>

Parameters:
    /? Displays usage information.

    /g Displays the current time zone ID.

    /s TimeZoneID[_dstoff]
       Sets the current time zone using the specified time zone ID.
       The _dstoff suffix disables Daylight Saving Time adjustments
       for the time zone (where applicable).

    /l Lists all valid time zone IDs and display names. The output will
       be: 
           <display name>
           <time zone ID>

Examples:
    TZUTIL /g
    TZUTIL /s "Pacific Standard Time"
    TZUTIL /s "Pacific Standard Time_dstoff"

Remarks:
    An exit code of 0 indicates the command completed successfully.

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

* Original Filename: tzutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


