
# timeout.exe 

* File Path: `C:\WINDOWS\SysWOW64\timeout.exe`
* Description: timeout - pauses command processing
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `36FE3599456A8E08367117A30EFABB6A`
SHA1 | `84ED87BF6D566DB2EDE9392D5754545742245EFB`
SHA256 | `D8B40A1B7CC0C5BE23C7DF31F6116C1E6829E2F1561813103C3D271A1766CFDB`
SHA384 | `DB62A4494A8DE752D44A64145553AA660E857F359602F08F7C7BE6AAA958825E23D79C570C5A24335F4476A8EFECF2DD`
SHA512 | `D936F66869367DF24251DE7241768530C1450E55BDBFC6CD476D49D5EC37252290D344D80A8418607AAEC4D013066790A2F647DC279304735A3AF184B08FAFA5`
SSDEEP | `384:Em5HP2SF6SbP8Xqb4X6tU6E1bZSzXF56eWNjq2wdXonvYI1H5Mx4viGhLI1wh0WL:Em5HPpqqS6vX2T9q2IovZ5MxYewhsO1`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: timeout.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



MIT License. Copyright (c) 2020 Strontic.


