
# choice.exe 
* File Path: `C:\Windows\SysWOW64\choice.exe`
* Description: Offers the user a choice
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `24DC53063C7AAE1ACB97183F0B42FC8F`
SHA1 | `CD606C2395DBB90523AE88890B670FE3DFD6A652`
SHA256 | `DBF371B359E27FD7595E4487235940ED2E92FD88021965C589C6723A5226FF70`
SHA384 | `ABCFDC77E45AA5F8DE1FB80075603C6BC43ADC0185831593454A027EA0FDDC3454054F9BC3AC5E5E12D2C19B6AA03A18`
SHA415 | `36BC313CEBF54043D96A3F91B2C68FE8B314DB6FEEE5B051B96A51CDDE4BC8B78AFEEFA0027C8F23D764AC72100AB02DF45CF30D76174C510E94FD77B4AF414A`
SSDEEP | `768:xrfAwxn1QakWyzRE+pDNZse3E1HXmE7IBIxhNfw:xrfA6HbmREAsek3RvxLfw`

## Runtime Data
### Usage (stdout):
```Batchfile

CHOICE [/C choices] [/N] [/CS] [/T timeout /D choice] [/M text]

Description:
    This tool allows users to select one item from a list 
    of choices and returns the index of the selected choice.

Parameter List:
   /C    choices       Specifies the list of choices to be created.
                       Default list is "YN".

   /N                  Hides the list of choices in the prompt.
                       The message before the prompt is displayed
                       and the choices are still enabled.

   /CS                 Enables case-sensitive choices to be selected.
                       By default, the utility is case-insensitive.

   /T    timeout       The number of seconds to pause before a default 
                       choice is made. Acceptable values are from 0 to 
                       9999. If 0 is specified, there will be no pause 
                       and the default choice is selected.

   /D    choice        Specifies the default choice after nnnn seconds.
                       Character must be in the set of choices specified
                       by /C option and must also specify nnnn with /T.

   /M    text          Specifies the message to be displayed before 
                       the prompt. If not specified, the utility 
                       displays only a prompt.

   /?                  Displays this help message.

   NOTE:
   The ERRORLEVEL environment variable is set to the index of the
   key that was selected from the set of choices. The first choice
   listed returns a value of 1, the second a value of 2, and so on.
   If the user presses a key that is not a valid choice, the tool 
   sounds a warning beep. If tool detects an error condition,
   it returns an ERRORLEVEL value of 255. If the user presses 
   CTRL+BREAK or CTRL+C, the tool returns an ERRORLEVEL value
   of 0. When you use ERRORLEVEL parameters in a batch program, list
   them in decreasing order.

Examples:
   CHOICE /?
   CHOICE /C YNC /M "Press Y for Yes, N for No or C for Cancel."
   CHOICE /T 10 /C ync /CS /D y 
   CHOICE /C ab /M "Select a for option 1 and b for option 2."
   CHOICE /C ab /N /M "Select a for option 1 and b for option 2."

```

### Usage (stderr):
```Batchfile
ERROR: Invalid argument/option - '-help'.
Type "CHOICE /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: choice.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


