
# timeout.exe 

* File Path: `C:\Windows\system32\timeout.exe`
* Description: timeout - pauses command processing
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FF04FB5121867334F841D5EFD133633B`
SHA1 | `B55BE2059C5FEE93C803CC853360766707BE8AF4`
SHA256 | `F9B3348029B76BBB658A097BF361EA72CEFA0D15CE444E9E8A689B35B67A78E7`
SHA384 | `A10FD103F0512DC1FFC554E5726610252FE2F39F4860B569FF9575F88AAAE0CC625B00FE0F66EE73938B4E570A7EFE5B`
SHA512 | `2149F650918B4665FA1D2550B9F09D024C71BBCA00CFE8B81B177F58F649843DC4F84EA2BC63EBDE00E392C5AAD4C34A2EEB1633532D436BC8A73B7BB65FB594`
SSDEEP | `768:iyTeR8xjmk7O3VKdPwKCiEW5Hfd17dLxQQWA2:5K+FEkHfLpLxyA2`

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


