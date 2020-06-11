
# shutdown.exe 

* File Path: `C:\Windows\SysWOW64\shutdown.exe`
* Description: Windows Shutdown and Annotation Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `AF35F0AACC196B16C03A1393209F5A53`
SHA1 | `0F6AFF0BC2C64CCFFE12C0956EF1FA5CF018B7F3`
SHA256 | `C85C8670663B6CD40D3A90179419CAF5D0C340993177CD748B58D72E034B4F02`
SHA384 | `89E95CA4DA5AA845A84E88F4C93C4F6A5B9FFACD9430ADFA930C7DEB0640E294ED00B820541234707D3A4EF18EA311AB`
SHA415 | `5EB2661922DC5B8548293F4BB3BEBEE5A4064AC95278D2815AA104465E130B440F2605BBD25D0FA7893EB90741419A3E64CD63879428C88371392AC4C78B72FE`
SSDEEP | `384:kwuHczKroKtM8YFUDQ8QBxTDTXehmkbntJDJ1SuQ3Wm+SWDH:kziKrob8YFeQ8QBxTDctFJ1Su6+X`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: C:\Windows\SysWOW64\shutdown.exe [/i | /l | /s | /r | /g | /a | /p | /h | /e | /o] [/hybrid] [/soft] [/fw] [/f]
    [/m \\computer][/t xxx][/d [p|u:]xx:yy [/c "comment"]]

    No args    Display help. This is the same as typing /?.
    /?         Display help. This is the same as not typing any options.
    /i         Display the graphical user interface (GUI).
               This must be the first option.
    /l         Log off. This cannot be used with /m or /d options.
    /s         Shutdown the computer.
    /r         Full shutdown and restart the computer.
    /g         Full shutdown and restart the computer. After the system is
               rebooted, restart any registered applications.
    /a         Abort a system shutdown.
               This can only be used during the time-out period.
               Combine with /fw to clear any pending boots to firmware.
    /p         Turn off the local computer with no time-out or warning.
               Can be used with /d and /f options.
    /h         Hibernate the local computer.
               Can be used with the /f option.
    /hybrid    Performs a shutdown of the computer and prepares it for fast startup.
               Must be used with /s option.
    /fw        Combine with a shutdown option to cause the next boot to go to the
               firmware user interface.
    /e         Document the reason for an unexpected shutdown of a computer.
    /o         Go to the advanced boot options menu and restart the computer.
               Must be used with /r option.
    /m \\computer Specify the target computer.
    /t xxx     Set the time-out period before shutdown to xxx seconds.
               The valid range is 0-315360000 (10 years), with a default of 30.
               If the timeout period is greater than 0, the /f parameter is
               implied.
    /c "comment" Comment on the reason for the restart or shutdown.
               Maximum of 512 characters allowed.
    /f         Force running applications to close without forewarning users.
               The /f parameter is implied when a value greater than 0 is
               specified for the /t parameter.
    /d [p|u:]xx:yy  Provide the reason for the restart or shutdown.
               p indicates that the restart or shutdown is planned.
               u indicates that the reason is user defined.
               If neither p nor u is specified the restart or shutdown is
               unplanned.
               xx is the major reason number (positive integer less than 256).
               yy is the minor reason number (positive integer less than 65536).

Reasons on this computer:
(E = Expected U = Unexpected P = planned, C = customer defined)
Type	Major	Minor	Title

 U  	0	0	Other (Unplanned)
E   	0	0	Other (Unplanned)
E P 	0	0	Other (Planned)
 U  	0	5	Other Failure: System Unresponsive
E   	1	1	Hardware: Maintenance (Unplanned)
E P 	1	1	Hardware: Maintenance (Planned)
E   	1	2	Hardware: Installation (Unplanned)
E P 	1	2	Hardware: Installation (Planned)
E   	2	2	Operating System: Recovery (Unplanned)
E P 	2	2	Operating System: Recovery (Planned)
  P 	2	3	Operating System: Upgrade (Planned)
E   	2	4	Operating System: Reconfiguration (Unplanned)
E P 	2	4	Operating System: Reconfiguration (Planned)
  P 	2	16	Operating System: Service pack (Planned)
    	2	17	Operating System: Hot fix (Unplanned)
  P 	2	17	Operating System: Hot fix (Planned)
    	2	18	Operating System: Security fix (Unplanned)
  P 	2	18	Operating System: Security fix (Planned)
E   	4	1	Application: Maintenance (Unplanned)
E P 	4	1	Application: Maintenance (Planned)
E P 	4	2	Application: Installation (Planned)
E   	4	5	Application: Unresponsive
E   	4	6	Application: Unstable
 U  	5	15	System Failure: Stop error
 U  	5	19	Security issue (Unplanned)
E   	5	19	Security issue (Unplanned)
E P 	5	19	Security issue (Planned)
E   	5	20	Loss of network connectivity (Unplanned)
 U  	6	11	Power Failure: Cord Unplugged
 U  	6	12	Power Failure: Environment
  P 	7	0	Legacy API shutdown

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

* Original Filename: SHUTDOWN.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


