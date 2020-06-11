
# tpmvscmgr.exe 

* File Path: `C:\WINDOWS\system32\tpmvscmgr.exe`
* Description: TPM Virtual Smartcard Setup Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `34EDCD35E248CED00FDD42967E6F033C`
SHA1 | `2EAC3A95F919F1F10CD9027D27627E543F0753AF`
SHA256 | `C31A0574845887A49371B1A26520768E32C3E46644E6E9FC8D3443A0537C9AB5`
SHA384 | `1218190FF0D623F5F41A7C9AB5B4C98179FF03F8B0D6F3E645F65A2403F8FE6F1811B39093764272458AC247396A92E7`
SHA415 | `601B87ABDE366C0F4807947C5FB3F2B8DB62E03EB35605397962B662B922A8322BDFB18409F5CF33010A0C9902884728D91CDA5BD65E241D8546A4E8084EFD40`
SSDEEP | `3072:uGBdmn6NHZM10co7T5Ooikw3+RCe2HaF1iaGdlSd9SpXx:uGBdk6NHrwQQTaF1tSp`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile
Unknown action: /help
TpmVscMgr.exe 
 
 Commands: 
	create 
		[/quiet] 
		/name <name> 
		/adminkey 'PROMPT'|'DEFAULT'|'RANDOM' 
		[/puk 'PROMPT'|'DEFAULT'] 
		/pin 'PROMPT'|'DEFAULT' 
		[/generate] 
		[/machine <machine name>] 
		[/pinpolicy [policy options]] 
		    policy options: 
			minlen <minimum PIN length> 
			maxlen <maximum PIN length> 
			uppercase 'ALLOWED'|'DISALLOWED'|'REQUIRED' 
			lowercase 'ALLOWED'|'DISALLOWED'|'REQUIRED' 
			digits 'ALLOWED'|'DISALLOWED'|'REQUIRED' 
			specialchars 'ALLOWED'|'DISALLOWED'|'REQUIRED' 
		[/attestation 'AIK_AND_CERT'|'AIK_ONLY'] 
 
	destroy 
		[/quiet] 
		/instance <device instance ID> 
		[/machine <machine name>] 
 
 Legend: 
		'PROMPT' => prompt for parameter 
		'DEFAULT' => default value for parameter 
		'RANDOM' => generate a random value 
		'ALLOWED' => these characters are allowed 
		'DISALLOWED' => these characters are not 
		    allowed 
		'REQUIRED' => at least one such character 
		    is required 
		'AIK_AND_CERT' => Creates an AIK and obtains
		    an AIK certificate from the cloud CA 
		'AIK_ONLY' => Creates an AIK but 
		    does not obtain an AIK certificate 
 
 Note: 
		The generate command formats the TPM 
		virtual smart card so that it can be used 
		to enroll for certificates. If this option 
		is not specified, a card management 
		system/tool will need to be used to format 
		the card before first use. 
 
 Note: 
		/pinpolicy may only be used in conjunction 
		with /pin prompt. 
 
 Note: 
		The default PIN policy options are as 
		follows: 
		    minlen 8 
		    maxlen 127 
		    uppercase allowed 
		    lowercase allowed 
		    digits allowed 
		    specialchars allowed 

		The lower and upper bounds on PIN length 
		are 4 and 127, respectively. When using 
		/pinpolicy, PIN characters must be 
		printable ASCII characters. 
 
 Note: 
		If '/attestation AIK_AND_CERT' is specified, it
		is possible that VSC creation will fail if
		there is no network connectivity. 
 Examples: 
    Create a TPM virtual smart card with default value for 
    PIN and a random admin key with no attestation: 

	TpmVscMgr create /name MyVSC /pin default /adminkey random /generate 

    Create a TPM virtual smart card with default value for 
    admin key and a specified PIN policy and attestation method: 

	TpmVscMgr create /name MyVSC /pin prompt /pinpolicy minlen 4 maxlen 8 
	    /adminkey default /attestation AIK_AND_CERT /generate 

    Destroy a TPM virtual smart card using the instance ID 
    that was returned when the card was created: 

	TpmVscMgr destroy /instance root\smartcardreader\0000

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TpmVscMgr.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.00 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


