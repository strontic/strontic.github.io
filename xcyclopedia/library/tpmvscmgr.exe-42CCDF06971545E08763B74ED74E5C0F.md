﻿---
title: tpmvscmgr.exe | TPM Virtual Smartcard Setup Utility
---

# tpmvscmgr.exe 

* File Path: `C:\windows\system32\tpmvscmgr.exe`
* Description: TPM Virtual Smartcard Setup Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `42CCDF06971545E08763B74ED74E5C0F`
SHA1 | `0F83DB9B2CCA397F7D3B7C60374E4F7A173B9578`
SHA256 | `93BAC4D5013074DBE590BEDED6CF4A9CFF601AC0DACFAAFA79D8CFB698FE7B4C`
SHA384 | `1E19B3AD6FC2625B4FC1AAACEB970C56F804769BC66ED18352B5FCDF4091851F0182F5B38AEEA4B4AAEF7C7CB8089B99`
SHA512 | `7AA40899E945FF69E7568D6FF97E032BE0E7DC88756CAAEB76C16D42661111FC4632F9CEB96A3FC41C3321A956637E26EF8D42E55809166AE6A2BA03D1249672`
SSDEEP | `3072:K9qC82ZNmaPEhdt/yFvYH9K6hr277WvvJia8xDUPeO35:K9XV2hh9eGvB6O`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TpmVscMgr.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.00 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## tpmvscmgr

The Tpmvscmgr command-line tool allows users with Administrative credentials to create and delete TPM virtual smart cards on a computer.

### Syntax

```
Tpmvscmgr create [/name] [/AdminKey DEFAULT | PROMPT | RANDOM] [/PIN DEFAULT | PROMPT] [/PUK DEFAULT | PROMPT] [/generate] [/machine] [/?]
```
```
Tpmvscmgr destroy [/instance <instance ID>] [/?]
```

##### Parameters for Create command

The Create command sets up new virtual smart cards on the user's system. It returns the instance ID of the newly created card for later reference if deletion is required. The instance ID is in the format **ROOT\SMARTCARDREADER\000n** where **n** starts from 0 and is increased by 1 each time you create a new virtual smart card.

|Parameter|Description|
|---------|-----------|
|/name|Required. Indicates the name of the new virtual smart card.|
|/AdminKey|Indicates the desired administrator key that can be used to reset the PIN of the card if the user forgets the PIN.</br>**DEFAULT** Specifies the default value of 010203040506070801020304050607080102030405060708.</br>**PROMPT** Prompts the user to enter a value for the administrator key.</br>**RANDOM** Results in a random setting for the administrator key for a card that is not returned to the user. This creates a card that might not be manageable by using smart card management tools. When generated with RANDOM, the administrator key must be entered as 48 hexadecimal characters.|
|/PIN|Indicates desired user PIN value.</br>**DEFAULT** Specifies the default PIN of 12345678.</br>**PROMPT** Prompts the user to enter a PIN at the command line. The PIN must be a minimum of eight characters, and it can contain numerals, characters, and special characters.|
|/PUK|Indicates the desired PIN Unlock Key (PUK) value. The PUK value must be a minimum of eight characters, and it can contain numerals, characters, and special characters. If the parameter is omitted, the card is created without a PUK.</br>**DEFAULT** Specifies the default PUK of 12345678.</br>**PROMPT** Prompts to the user to enter a PUK at the command line.|
|/generate|Generates the files in storage that are necessary for the virtual smart card to function. If the /generate parameter is omitted, it is equivalent to creating a card without this file system. A card without a file system can be managed only by a smart card management system such as Microsoft Configuration Manager.|
|/machine|Allows you to specify the name of a remote computer on which the virtual smart card can be created. This can be used in a domain environment only, and it relies on DCOM. For the command to succeed in creating a virtual smart card on a different computer, the user running this command must be a member in the local administrators group on the remote computer.|
|/?|Displays Help for this command.|

##### Parameters for Destroy command

The Destroy command securely deletes a virtual smart card from the user's computer.

> [!WARNING]
> When a virtual smart card is deleted, it cannot be recovered.

|Parameter|Description|
|---------|-----------|
|/instance|Specifies the instance ID of the virtual smart card to be removed. The instanceID was generated as output by Tpmvscmgr.exe when the card was created. The /instance parameter is a required field for the Destroy command.|
|/?|Displays Help for this command.|

### Remarks

Membership in the **Administrators** group (or equivalent) on the target computer is the minimum required to run all the parameters of this command.

For alphanumeric inputs, the full 127 character ASCII set is allowed.

### Examples

The following command shows how to create a virtual smart card that can be later managed by a smart card management tool launched from another computer.
```
tpmvscmgr.exe create /name VirtualSmartCardForCorpAccess /AdminKey DEFAULT /PIN PROMPT
```
Alternatively, instead of using a default administrator key, you can create an administrator key at the command line. The following command shows how to create an administrator key.
```
tpmvscmgr.exe create /name VirtualSmartCardForCorpAccess /AdminKey PROMPT /PIN PROMPT
```
The following command will create the unmanaged virtual smart card that can be used to enroll certificates.
```
tpmvscmgr.exe create /name VirtualSmartCardForCorpAccess /AdminKey RANDOM /PIN PROMPT /generate
```
The following command will create a virtual smart card with a randomized administrator key. The key is automatically discarded after the cardis created. This means that if the user forgets the PIN or wants to the change the PIN, the user needs to delete the card and create it again. To delete the card, the user can run the following command.
```
tpmvscmgr.exe destroy /instance <instance ID>
```
where \<instance ID> is the value printed on the screen when the user created the card. Specifically, for the first card created, the instance ID is ROOT\SMARTCARDREADER\0000.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.

