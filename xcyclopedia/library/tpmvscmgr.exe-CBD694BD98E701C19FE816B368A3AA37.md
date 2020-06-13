
# tpmvscmgr.exe 

* File Path: `C:\Windows\system32\tpmvscmgr.exe`
* Description: TPM Virtual Smartcard Setup Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `CBD694BD98E701C19FE816B368A3AA37`
SHA1 | `9D6D721386BB0A95374146D5F95BB1399BFBBD83`
SHA256 | `61F2F6757DBB57213E7391841CF342BCA2CF0BFEB904A9BB273FB1D9AAA7BEB6`
SHA384 | `0275C04164F39591611478B4BEA5867FD00F30020F1FEA10385946C57A1DC93F4CB12D39FFE4D1DA19F970F6CF5435FE`
SHA512 | `499EB95320228CC2D65D209C3DAE23F2C27A4BE680F2838887676BA2E86CE028D5DD4F06DE5A08332FB82847ACADC48680FEBB8F1E3ECCF7790D8FF4CA42BFA5`
SSDEEP | `3072:OHyb47+equxzJc7z40/VrJBac8+ZTAb90p:OHyb4qeLoVd40`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TpmVscMgr.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.00 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# tpmvscmgr

The Tpmvscmgr command-line tool allows users with Administrative credentials to create and delete TPM virtual smart cards on a computer.

## Syntax

```
Tpmvscmgr create [/name] [/AdminKey DEFAULT | PROMPT | RANDOM] [/PIN DEFAULT | PROMPT] [/PUK DEFAULT | PROMPT] [/generate] [/machine] [/?]
```
```
Tpmvscmgr destroy [/instance <instance ID>] [/?]
```

#### Parameters for Create command

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

#### Parameters for Destroy command

The Destroy command securely deletes a virtual smart card from the user's computer.

> [!WARNING]
> When a virtual smart card is deleted, it cannot be recovered.

|Parameter|Description|
|---------|-----------|
|/instance|Specifies the instance ID of the virtual smart card to be removed. The instanceID was generated as output by Tpmvscmgr.exe when the card was created. The /instance parameter is a required field for the Destroy command.|
|/?|Displays Help for this command.|

## Remarks

Membership in the **Administrators** group (or equivalent) on the target computer is the minimum required to run all the parameters of this command.

For alphanumeric inputs, the full 127 character ASCII set is allowed.

## Examples

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

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


