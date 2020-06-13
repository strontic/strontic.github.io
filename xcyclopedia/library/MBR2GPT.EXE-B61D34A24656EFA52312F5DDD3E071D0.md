
# MBR2GPT.EXE 

* File Path: `C:\WINDOWS\system32\MBR2GPT.EXE`
* Description: 
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B61D34A24656EFA52312F5DDD3E071D0`
SHA1 | `89F6C169C124F0C0CD6D746B08989571A1C539DF`
SHA256 | `AE0F3C0A1592D68CF7FE5DC2FDC9D5499AD63DBAA3AF8482809A9163F5EEA2E6`
SHA384 | `710AE5714A5F0E012158AE6D7A628C88AA14FFC0AE31C3B4A1EABE09BD8C88526BC3E75931A793F2A1BD0A6F7B9AD954`
SHA512 | `2538FB5773E45D950000B0C82E657829B524D3C2810C4E351D6D215B67BB2033C6F111F21D51811F3C631A2AE61C546CEFD005FE60739743DA117F16F20A7BE1`
SSDEEP | `12288:gEPjkp44aaCdEHeZPFqpjgfQ0/K+hhJbngfIWco0FM4P6B0thmKa:7PjklHCPF60WcoOjS0mK`

## Runtime Data

### Usage (stdout):
```Batchfile

Converts a disk from MBR to GPT partitioning without modifying or deleting data on the disk.

MBR2GPT.exe /validate|convert [/disk:<diskNumber>] [/logs:<logDirectory>] [/map:<source>=<destination>] [/allowFullOS]

Where:

 /validate
         - Validates that the selected disk can be converted
           without performing the actual conversion.

 /convert
         - Validates that the selected disk can be converted
           and performs the actual conversion.

 /disk:<diskNumber>
         - Specifies the disk number of the disk to be processed.
           If not specified, the system disk is processed.

 /logs:<logDirectory>
         - Specifies the directory for logging. By default logs
           are created in the %windir% directory.

 /map:<source>=<destination>
         - Specifies the GPT partition type to be used for a
           given MBR partition type not recognized by Windows.
           Multiple /map switches are allowed.

 /allowFullOS
         - Allows the tool to be used from the full Windows
           environment. By default, this tool can only be used
           from the Windows Preinstallation Environment.


```

### Usage (stderr):
```Batchfile
Invalid argument: -help

Invalid arguments


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 



MIT License. Copyright (c) 2020 Strontic.


