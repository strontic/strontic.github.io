---
title: OSPPC.DLL | Office Software Licensing Client Dll
excerpt: What is OSPPC.DLL?
---

# OSPPC.DLL 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\vfs\ProgramFilesCommonX64\Microsoft Shared\OfficeSoftwareProtectionPlatform\OSPPC.DLL`
* Description: Office Software Licensing Client Dll

## Hashes

Type | Hash
-- | --
MD5 | `2B26EB559943B3E47CACD3099B6AEC93`
SHA1 | `70C1F5A5AB23B9A5CB25957676B72DB856618932`
SHA256 | `2D6514AFDA6287FE1B26C28245381C0E3D0E9FF38EF621E37DAA242D60CAD9A5`
SHA384 | `8B1980299D99724330363D25B01A537C31E006C92C0E17BCDAF29741A28791F9218DE14BAABDDE0DCBED0BE1903A6CE9`
SHA512 | `4F880DBCA2630681FC62BF70D2A5AD00816C6C3A7F15C3CCE8F3B95329C7B3C35E504409D2CB0D7696B087EB89FE77339AFD6F982079D7DA2800E7E10959601A`
SSDEEP | `3072:xfC2hnw2CLW78A6BCUS67DEw9V3uozxNiE1jMMR6vmR2reBrdQpm:xhnV4WnULPEw9V3F4vmkw`
IMP | `687D4737D41F6DBE69EC38F7C8F75354`
PESHA1 | `52F345EB55F9AA5AA260F017035F5DCA28143FD2`
PE256 | `9B659CF0CB22B058D3C021FB78D98044A94635D98B371FACB142908ECEEABA8B`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`SLCallServer` | 1 | Exported Function
`SLLoadApplicationPolicies` | 41 | Exported Function
`SLOpen` | 42 | Exported Function
`SLpAuthenticateGenuineTicketResponse` | 2 | Exported Function
`SLpBeginGenuineTicketTransaction` | 3 | Exported Function
`SLpDepositTokenActivationResponse` | 4 | Exported Function
`SLPersistApplicationPolicies` | 43 | Exported Function
`SLPersistRTSPayloadOverride` | 44 | Exported Function
`SLpGenerateTokenActivationChallenge` | 5 | Exported Function
`SLpGetGenuineBlob` | 6 | Exported Function
`SLpGetGenuineLocal` | 7 | Exported Function
`SLpGetLicenseAcquisitionInfo` | 8 | Exported Function
`SLIsGenuineLocalEx` | 40 | Exported Function
`SLpGetMachineUGUID` | 10 | Exported Function
`SLpGetTokenActivationGrantInfo` | 11 | Exported Function
`SLpVLActivateProduct` | 12 | Exported Function
`SLReArm` | 45 | Exported Function
`SLRegisterEvent` | 46 | Exported Function
`SLRegisterPlugin` | 47 | Exported Function
`SLSetAuthenticationData` | 48 | Exported Function
`SLSetCurrentProductKey` | 49 | Exported Function
`SLSetGenuineInformation` | 50 | Exported Function
`SLUninstallLicense` | 51 | Exported Function
`SLUninstallProofOfPurchase` | 52 | Exported Function
`SLUnloadApplicationPolicies` | 53 | Exported Function
`SLpGetMSPidInformation` | 9 | Exported Function
`SLUnregisterEvent` | 54 | Exported Function
`SLInstallProofOfPurchaseEx` | 39 | Exported Function
`SLInstallLicense` | 37 | Exported Function
`SLClose` | 13 | Exported Function
`SLConsumeRight` | 14 | Exported Function
`SLDepositMigrationBlob` | 15 | Exported Function
`SLDepositOfflineConfirmationId` | 16 | Exported Function
`SLFireEvent` | 17 | Exported Function
`SLGatherMigrationBlob` | 18 | Exported Function
`SLGenerateOfflineInstallationId` | 19 | Exported Function
`SLGetApplicationInformation` | 20 | Exported Function
`SLGetApplicationPolicy` | 21 | Exported Function
`SLGetAuthenticationResult` | 22 | Exported Function
`SLGetEncryptedPIDEx` | 23 | Exported Function
`SLInstallProofOfPurchase` | 38 | Exported Function
`SLGetGenuineInformation` | 24 | Exported Function
`SLGetLicense` | 26 | Exported Function
`SLGetLicenseFileId` | 27 | Exported Function
`SLGetLicenseInformation` | 28 | Exported Function
`SLGetLicensingStatusInformation` | 29 | Exported Function
`SLGetPKeyId` | 30 | Exported Function
`SLGetPKeyInformation` | 31 | Exported Function
`SLGetPolicyInformation` | 32 | Exported Function
`SLGetPolicyInformationDWORD` | 33 | Exported Function
`SLGetProductSkuInformation` | 34 | Exported Function
`SLGetServiceInformation` | 36 | Exported Function
`SLGetSLIDList` | 35 | Exported Function
`SLGetInstalledProductKeyIds` | 25 | Exported Function
`SLUnregisterPlugin` | 55 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `6119CC93000100000066`
* Thumbprint: `19F8F76F4655074509769C20349FFAECCECD217D`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: osppc.dll
* Product Name: Microsoft Office
* Company Name: Microsoft Corporation
* File Version: 15.0.0169.500 (win7sp1_gdr_oob_osppv2(oobla).120705-1649)
* Product Version: 15.0.0169.500
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/2d6514afda6287fe1b26c28245381c0e3d0e9ff38ef621e37daa242d60cad9a5/detection/

## Possible Misuse

*The following table contains possible examples of `OSPPC.DLL` being misused. While `OSPPC.DLL` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"value": "osppc.dll",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [invisimole](https://github.com/eset/malware-ioc/blob/master/invisimole/README.adoc) | `osppc.dll` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


