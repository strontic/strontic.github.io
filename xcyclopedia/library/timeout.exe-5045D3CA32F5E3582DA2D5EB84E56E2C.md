
# timeout.exe 

* File Path: `C:\WINDOWS\system32\timeout.exe`
* Description: timeout - pauses command processing
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `5045D3CA32F5E3582DA2D5EB84E56E2C`
SHA1 | `E2B2F5F95D5698EE1D67879BCDD71CC010607675`
SHA256 | `EE3FB5E7FB6E9E8BA3039FF134BFACB760A2B238A87D67E8C3AA68D38A30A46F`
SHA384 | `77979B297E61E20570C0B17EBB8C4BF43DDF83E6361F104C75232F0038870AE3E35CFDDA4629186816599AE0BC0A3B00`
SHA512 | `ACB1E0CFF4AE7E17AF7FC2C7ED57A7310E4A3455494C6A2CE9E39A39DCA0EABCAEE0C793B80218CC004467736751A610E89F98EB71F9637E55F45DE2652BB9D7`
SSDEEP | `768:+yXXJ0xqw3ia488QC63n1Hf91WRxv8hM:sYOn1HfrmxkM`

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

* Original Filename: timeout.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


