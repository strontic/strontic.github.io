
# setspn.exe 
* File Path: `C:\Windows\system32\setspn.exe`
* Description: Query or reset the computer's SPN attribute
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `5C184D581524245DAD7A0A02B51FD2C2`
SHA1 | `E1737531283F547AF57153D6D09BE54E023B2957`
SHA256 | `909C2DDF06CFEB1F79004DBB5E9B9D36B693CFDFF3459E0A6A51616B2AD6D2D1`
SHA384 | `BF81D5EAFAC0B9DE14D3C25D403D4B2746D7B6781C643E9F765FDB1E47196D2DCF0CE5BB6D88336107780921C3EAD9CD`
SHA415 | `516AE7B3D0ABE7C0ACB9CF419826823CCE20B5C46BF1FC60AF7CC7887745A5F8CC2A37D27663B678BEBC177CF663E234BB427701D5D462BDB4240D311A9271F6`
SSDEEP | `768:sY+4keaRDMP3gJtmH+9IFrf0DkvwNMq7VEe:hcDMfwOwDkX8VEe`

## Runtime Data
### Usage (stdout):
```Batchfile
Usage: C:\Windows\system32\setspn.exe [modifiers switch] [accountname] 
  Where "accountname" can be the name or domain\name
  of the target computer or user account

  Edit Mode Switches:
   -R = reset HOST ServicePrincipalName
    Usage:   setspn -R accountname
   -S = add arbitrary SPN after verifying no duplicates exist
    Usage:   setspn -S SPN accountname
   -D = delete arbitrary SPN
    Usage:   setspn -D SPN accountname
   -L = list SPNs registered to target account
    Usage:   setspn [-L] accountname   

  Edit Mode Modifiers:
   -C = specify that accountname is a computer account
   -U = specify that accountname is a user account
   
    Note: -C and -U are exclusive.  If neither is specified, the tool
     will interpret accountname as a computer name if such a computer
     exists, and a user name if it does not.

  Query Mode Switches:
   -Q = query for existence of SPN
    Usage:   setspn -Q SPN 
   -X = search for duplicate SPNs
    Usage:   setspn -X 

    Note: searching for duplicates, especially forestwide, can take
     a long period of time and a large amount of memory.  -Q will execute
     on each target domain/forest.  -X will return duplicates that exist
     across all targets. SPNs are not required to be unique across forests,
     but duplicates can cause authentication issues when authenticating
     cross-forest.

  Query Mode Modifiers:
   -P = suppresses progress to the console and can be used when redirecting
    output to a file or when used in an unattended script.  There will be no
    output until the command is complete.
   -F = perform queries at the forest, rather than domain level
   -T = perform query on the speicified domain or forest (when -F is also used)
    Usage:   setspn -T domain (switches and other parameters)
     "" or * can be used to indicate the current domain or forest.

    Note: these modifiers can be used with the -S switch in order to specify
     where the check for duplicates should be performed before adding the SPN.
    Note: -T can be specified multiple times.

Examples: 
setspn -R daserver1 
   It will register SPN "HOST/daserver1" and "HOST/{DNS of daserver1}" 
setspn -S http/daserver daserver1 
   It will register SPN "http/daserver" for computer "daserver1" 
    if no such SPN exists in the domain
setspn -D http/daserver daserver1 
   It will delete SPN "http/daserver" for computer "daserver1" 
setspn -F -S http/daserver daserver1 
   It will register SPN "http/daserver" for computer "daserver1"
    if no such SPN exists in the forest
setspn -U -S http/daserver dauser 
   It will register SPN "http/daserver" for user account "dauser" 
    if no such SPN exists in the domain
setspn -T * -T bar -X
   It will report all duplicate registration of SPNs in this domain and bar
setspn -T bar -F -Q */daserver
   It will find all SPNs of the form */daserver registered in the forest to
    which bar belongs

```

### Usage (stderr):
```Batchfile
FindDomainForAccount: Call to DsGetDcNameWithAccountW failed with return value 0x0000054B
Could not find account help

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: setspn.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


