---
title: tpmvscmgr.exe | TPM Virtual Smartcard Setup Utility
excerpt: What is tpmvscmgr.exe?
---

# tpmvscmgr.exe 

* File Path: `C:\windows\system32\tpmvscmgr.exe`
* Description: TPM Virtual Smartcard Setup Utility

## Hashes

Type | Hash
-- | --
MD5 | `48430DD3D6BA660E3A4CE684E6CE2D42`
SHA1 | `62C35E2712EB0E1B8536C5B8DFE999EDD2057B8A`
SHA256 | `7191BA350F924CD2C059F0244A2A933656D19A66E99E05D079D7E95BD2634B92`
SHA384 | `7532208BD545331E076833FF1B3D5B425D8126AEFF71DABCBFA316AF135E6BBCC05F51CD6AE30B174E822175B6EFDEBD`
SHA512 | `C56A5ACC93C7AD4761EBE55EFF8D8487CC7F18DAE177E820DF9D772F8434F7C7531E73569F296E91ACC6E0FD289D9E4C14C4648C9FFAC101EE2624DEA050FFDB`
SSDEEP | `3072:xoBTadO6xP1DJXTEsasx6kAfaep9Rmo5gb+P/d5wd/rXBC:xoBoF1DJXTEsXxpASK7XJd5mrX`

## Signature

* Status: The file C:\windows\system32\tpmvscmgr.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: TpmVscMgr.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.00 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
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



MIT License. Copyright (c) 2020 Strontic.


