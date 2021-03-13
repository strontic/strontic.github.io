---
title: tpmvscmgr.exe | TPM Virtual Smartcard Setup Utility
excerpt: What is tpmvscmgr.exe?
---

# tpmvscmgr.exe 

* File Path: `C:\WINDOWS\system32\tpmvscmgr.exe`
* Description: TPM Virtual Smartcard Setup Utility

## Hashes

Type | Hash
-- | --
MD5 | `34EDCD35E248CED00FDD42967E6F033C`
SHA1 | `2EAC3A95F919F1F10CD9027D27627E543F0753AF`
SHA256 | `C31A0574845887A49371B1A26520768E32C3E46644E6E9FC8D3443A0537C9AB5`
SHA384 | `1218190FF0D623F5F41A7C9AB5B4C98179FF03F8B0D6F3E645F65A2403F8FE6F1811B39093764272458AC247396A92E7`
SHA512 | `601B87ABDE366C0F4807947C5FB3F2B8DB62E03EB35605397962B662B922A8322BDFB18409F5CF33010A0C9902884728D91CDA5BD65E241D8546A4E8084EFD40`
SSDEEP | `3072:uGBdmn6NHZM10co7T5Ooikw3+RCe2HaF1iaGdlSd9SpXx:uGBdk6NHrwQQTaF1tSp`

## Runtime Data

### Usage (stderr):
```cmhg
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

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## tpmvscmgr

The tpmvscmgr command-line tool allows users with Administrative credentials to create and delete TPM virtual smart cards on a computer.

### Syntax

```
tpmvscmgr create [/name] [/adminkey DEFAULT | PROMPT | RANDOM] [/PIN DEFAULT | PROMPT] [/PUK DEFAULT | PROMPT] [/generate] [/machine] [/?]
```

```
tpmvscmgr destroy [/instance <instanceID>] [/?]
```

#### Create parameters

The **Create** command sets up new virtual smart cards on the user's system. It also returns the instance ID of the newly-created card for later reference, if deletion is required. The instance ID is in the format **ROOT\SMARTCARDREADER\000n** where **n** starts from 0 and is increased by 1 each time you create a new virtual smart card.

| Parameter | Description |
|--|--|
| /name | Required. Indicates the name of the new virtual smart card. |
| /adminkey | Indicates the desired administrator key that can be used to reset the PIN of the card if the user forgets the PIN. This can include:<ul><li>**DEFAULT** - Specifies the default value of *010203040506070801020304050607080102030405060708*.</li><li>**PROMPT** - Prompts the user to enter a value for the administrator key.</li><li>**RANDOM** - Results in a random setting for the administrator key for a card that is not returned to the user. This creates a card that might not be manageable by using smart card management tools. When using the RANDOM option, the administrator key must be entered as 48 hexadecimal characters.</li></ul> |
| /PIN | Indicates desired user PIN value.<ul><li>**DEFAULT** - Specifies the default PIN of 12345678.</li><li>**PROMPT** - Prompts the user to enter a PIN at the command line. The PIN must be a minimum of eight characters, and it can contain numerals, characters, and special characters.</li></ul> |
| /PUK | Indicates the desired PIN Unlock Key (PUK) value. The PUK value must be a minimum of eight characters, and it can contain numerals, characters, and special characters. If the parameter is omitted, the card is created without a PUK. The options include:<ul><li>**DEFAULT** - Specifies the default PUK of *12345678*.</li><li>**PROMPT** - Prompts to the user to enter a PUK at the command line.</li></ul> |
| /generate | Generates the files in storage that are necessary for the virtual smart card to function. If you don't use the **/generate** parameter, it's like you created the card without the underlying file system. A card without a file system can be managed only by a smart card management system such as Microsoft Configuration Manager. |
| /machine | Allows you to specify the name of a remote computer on which the virtual smart card can be created. This can be used in a domain environment only, and it relies on DCOM. For the command to succeed in creating a virtual smart card on a different computer, the user running this command must be a member in the local administrators group on the remote computer. |
| /? | Displays Help for this command. |

#### Destroy parameters

The **Destroy** command securely deletes a virtual smart card from the user's computer.

> [!WARNING]
> If a virtual smart card is deleted, it cannot be recovered.

| Parameter | Description |
|--|--|
| /instance | Specifies the instance ID of the virtual smart card to be removed. The instanceID was generated as output by tpmvscmgr.exe when the card was created. The **/instance** parameter is a required field for the **Destroy** command. |
| /? | Displays help at the command prompt. |

##### Remarks

- For alphanumeric inputs, the full 127 character ASCII set is allowed.

### Examples

To create a virtual smart card that can be later managed by a smart card management tool launched from another computer, type:

```
tpmvscmgr.exe create /name VirtualSmartCardForCorpAccess /AdminKey DEFAULT /PIN PROMPT
```

Alternatively, instead of using a default administrator key, you can create an administrator key at the command line. The following command shows how to create an administrator key.

```
tpmvscmgr.exe create /name VirtualSmartCardForCorpAccess /AdminKey PROMPT /PIN PROMPT
```

To create an unmanaged virtual smart card that can be used to enroll certificates, type:

```
tpmvscmgr.exe create /name VirtualSmartCardForCorpAccess /AdminKey RANDOM /PIN PROMPT /generate
```

A virtual smart card is created with a randomized administrator key. The key is automatically discarded after the card is created. This means that if the user forgets the PIN or wants to the change the PIN, the user needs to delete the card and create it again.

To delete the card, type:

```
tpmvscmgr.exe destroy /instance <instance ID>
```

Where `<instanceID>` is the value printed on the screen when the user created the card. Specifically, for the first card created, the instance ID is *ROOT\SMARTCARDREADER\0000*.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


