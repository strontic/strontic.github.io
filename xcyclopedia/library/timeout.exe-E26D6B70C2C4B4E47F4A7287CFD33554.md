
# timeout.exe 

* File Path: `C:\Windows\SysWOW64\timeout.exe`
* Description: timeout - pauses command processing
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E26D6B70C2C4B4E47F4A7287CFD33554`
SHA1 | `2FA9BC458A3CB15446F976D7DA926058FF4E002F`
SHA256 | `A7B4ACFB3A3EFDD83AF8664F404D937FFD440564CB43A872DAE0AC21D99AFBD8`
SHA384 | `EBA858AC55B31D96B7A0B2B170AF2BB5F52EFD45620BEE743DE39FDC3ED904DF75500BD40D2CEB980938E0FBC935A31A`
SHA512 | `5CC454C35BCBAB3938F524AB185BA4D42618FA7980F9CF4BA5D9A820CD2A464F8F53D5FD86E6C192A62AEE9E3587985180EC1B25AD12F024F7C7783447AF7326`
SSDEEP | `384:WeHPRuRW/4PyYUKbdOqvbHAGn5qpKc4Q3s6syXUnj8MXsPxzDjGX5PfxY8K8tI1R:tHP4RSEAqj8TVXRXPxzDj6fxverWz0P`

## Runtime Data

### Usage (stdout):
```Batchfile

TIMEOUT [/T] timeout [/NOBREAK] 

Description:
    This utility accepts a timeout parameter to wait for the specified
    time period (in seconds) or until any key is pressed. It also 
    accepts a parameter to ignore the key press. 

Parameter List:
    /T        timeout       Specifies the number of seconds to wait.
                            Valid range is -1 to 99999 seconds.

    /NOBREAK                Ignore key presses and wait specified time.

    /?                      Displays this help message.

NOTE: A timeout value of -1 means to wait indefinitely for a key press.

Examples:
    TIMEOUT /?
    TIMEOUT /T 10
    TIMEOUT /T 300 /NOBREAK
    TIMEOUT /T -1

```

### Usage (stderr):
```Batchfile
ERROR: Invalid value for timeout (/T) specified. Valid range is -1 to 99999.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: timeout.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


