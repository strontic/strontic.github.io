
# choice.exe 

* File Path: `C:\WINDOWS\SysWOW64\choice.exe`
* Description: Offers the user a choice
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `5EDAB7F7B5510390EDAE2FFDC0A75AE2`
SHA1 | `64B18854B8410D7B9CD5567105AFB654AA56013E`
SHA256 | `A5A0B18EC249033CBC5629CC477EE81AA1B159C3F8B8EED4BE95F4494D4B52BD`
SHA384 | `46055135B560DD616F4BFDA46F538D14EAC2EFF367E94224CF80A702422B74539E7AAF20C3CB50DDF65449FF131BF98C`
SHA415 | `A1993163378844FB76761ACFB870A8333B1AD0272EDE209D78BC0B094E37CF932DAC307622762201CC675BA022D2F8D4DDB4A64837C785A894417C255D9FEC7A`
SSDEEP | `768:IrfncV1WY8YPQNk6W6is4jMtNBHxpxGrdHaY:IrfncVUJgu9W6i1mNBHnxiHaY`

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

* Original Filename: choice.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


