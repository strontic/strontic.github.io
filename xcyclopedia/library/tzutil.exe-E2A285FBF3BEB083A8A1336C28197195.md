
# tzutil.exe 

* File Path: `C:\Windows\SysWOW64\tzutil.exe`
* Description: Windows Time Zone Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E2A285FBF3BEB083A8A1336C28197195`
SHA1 | `B0C1A838A6D4D0862289B4A2FB4DA375BE389077`
SHA256 | `DA67C992ECD1330FE32C2FF3A4D6E77CE6A5A51927FBDBB3C7E8FFFDC32877EF`
SHA384 | `AB2861C319B3E7A5211BB86BEF74395D515933A5157EEFABE731B2D9376197D8824B3A1D90C46FDC812C72506DA13E28`
SHA415 | `58A8669E5571911390EB1A1C6FC01DAEE32C9E48E9DA43A75F70F0CA166338ABAEC6685A172E9677121DA1E5E62B21C59AB110B71C361B644BA59F79127996C7`
SSDEEP | `768:bfpKHTiPgnw1VzDtG+6Jc1Ra5yg8U/jGwWyu9:gHOonw3DtsJcLa5ygrrJWyu9`

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
conhost.exe

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


