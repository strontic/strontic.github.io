
# choice.exe 

* File Path: `C:\WINDOWS\system32\choice.exe`
* Description: Offers the user a choice
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `6EFD5FAFC944BB134EC351CE56E5CADE`
SHA1 | `6CBBEADC7A6F922FFB5985EEAB6B31938140DE11`
SHA256 | `C31A9D52FD3719B9A984EA8C8E911CC7F08D351C2567E0C165D5F95962DF786B`
SHA384 | `A1CF9D72250A3B4962469671528B2951603F26BB26392C00441B8BBB4BABBD8FA14B0AB609D8F8F0C49C11288DB8C1A9`
SHA415 | `C948F0B8D73C80DF6F95FBD9BA253332E4825D9ADB3E722DC0C692EADB6D162D4C80352F0F5FBBF7A4AF0D4CB1AD929E18DA889812541541B4704D79AEC39113`
SSDEEP | `768:MyxBmc9jCDEY6Jh2p3jUPvFCyJTngr/vnY26xxzj8WHa:bmxKjkwTngr/g2axnfHa`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: choice.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


