
# w3wp.exe 

* File Path: `C:\Windows\SysWOW64\inetsrv\w3wp.exe`
* Description: IIS Worker Process
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `A93EC9C3999C4F798B270A4B5C5300A1`
SHA1 | `F39A39456B8D962A553BFC759CF420979F7D3FAB`
SHA256 | `3BD48EECD731F843B4416C46C254D2EFB78A5F77105C341FC8FD888956F1FB64`
SHA384 | `08BABA95B8E85E997088A2603E3481E281D1A29BF44925EA6C4245A09FCA75567D0A3E33CEE28930B19A2E4E8A93E1FC`
SHA512 | `B582C92561A79C769F0DEC2B91A50B73128588A93F67D539131AAC59354A9BB3487AF4974E4BFAA89C41761BF79C237C5E7037C02ECDDF28DF2995AFCB981862`
SSDEEP | `384:JI3JPj561Qknfpw2Xw78QZgp9IbnUiSkHFqWSuYN:JAJPEmuhwH8+eAUiSklY`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: C:\Windows\SysWOW64\inetsrv\w3wp.exe -s <site id> | -h [application host file]  
                           -w <optional root web.config file>  
                           -in <optional instance name>  
 
	-debug 
		 This option launches a worker process using the default 
		 application host config file.  By default, it will use 
		 site id 1. 
 
	-s <site id> 
		 Optional parameter to use a siteinformation from the provided 
		 site id. 
 
	or 
 
	-h [Application host config filename] 
		 Launches a worker process using the specified application host 
		 config file. 
 
	-in <Instance Name> 
		 Optional instance name to use.  Defaults to 'HWC-<PID>' 
 
	-w <Root web config filename> 
		 Optional root web config file to use. 

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: w3wp.exe.mui
* Product Name: Internet Information Services
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


