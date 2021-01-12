---
title: computerhardwareids.exe | ComputerHardwareIds is a tool to derive the computer hardware ids from SMBIOS information.
excerpt: What is computerhardwareids.exe?
---

# computerhardwareids.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\computerhardwareids.exe`
* Description: ComputerHardwareIds is a tool to derive the computer hardware ids from SMBIOS information.

## Hashes

Type | Hash
-- | --
MD5 | `F72CADFA334092C45E6B1DD408C79E29`
SHA1 | `FF57BDEAD4448A2A0E1DAB35F5576670928FA27D`
SHA256 | `0EA5B7DCB056B288EA365E0EAC2FBC6F9C5B2DAB6CA722B4FCE747A78249D4E6`
SHA384 | `78FFE307127CA319DDFDC9DB898E263959C31C74B3065223262D3E0974121242DBEA015C705803A9989633C6592952A6`
SHA512 | `6BA7E0558D9C8F09D916636432D9F2DC14644D5701C3D2125639C98E134448B439D59144388BA41827DD17AFA9B7ACD8647CCA8F046F802B6C7DEF1A6B638480`
SSDEEP | `768:ZC+rrlxPGT1iFYBllWxWC1FFECVQVdu/dGCp1X:dLPYe4jsW+FFEFduFGCL`
IMP | `26284274DD19BD6814E0A94AE4E6B717`
PESHA1 | `AF0018163EF984C70837E6EB7E5C7E242C2BA530`
PE256 | `922615BA740ADA8BE8D3F13C97FC8493E1A0619F636ABC5748FA0C382F4D1C49`

## Runtime Data

### Usage (stdout):
```cmhg
NAME
  ComputerHardwareIds - Outputs the HardwareIds for the computer

SYNOPSIS
  ComputerHardwareIds.exe [/mfg] [/product] [/family] [/ven] [/ver] [/major]
    [/minor] [/sku] [/enclosure] [/bb_mfg] [/bb_product] [/verbose] [/?]

DESCRIPTION
  Outputs the HardwareIds for the computer. When executed without any command
  line arguments the HardwareIds are generated using data in the system
  BIOS. Optional arguments allow the generation of HardwareIds based on
  strings specified on the command line. When optional arguments are specified
  the BIOS values on the local computer are not used when generating the
  HardwareID values.

OPTIONS

  Argument  BIOS Field                    Meaning
  -----------------------------------------------------------------------------
  /ven      "BIOS vendor string"          Specifies the BIOS vendor string for
                                          a given system. If not specified the
                                          value is assumed to be NULL.

  /ver      "BIOS version string"         Specifies the BIOS version string for
                                          a given system. If not specified the
                                          value is assumed to be NULL.

  /major    "System BIOS Major Release"   Specifies the BIOS major release
                                          as a string representation of
                                          an int. If not specified the value is
                                          assumed to be '0'.

  /minor    "System BIOS Minor Release"   Specifies the BIOS minor release
                                          as a string representation of
                                          an int. If not specified the value is
                                          assumed to be '0'.

  /mfg      "System Manufacturer string"  Specifies the System Manufacturer
                                          string for a given system. If not
                                          specified the value is assumed to be
                                          NULL.

  /family   "System Family string"        Specifies the System Family string
                                          for a given system. If not specified
                                          the value is assumed to be NULL.

  /product  "System ProductName string"   Specifies the ProductName string for
                                          a given system. If not specified the
                                          value is assumed to be NULL.

  /enclosure "Enclosure type number"      Specifies the number for the
                                          Enclosure type for the system.  This
                                          number is the Byte value from the
                                          Sytem Enclosure or Chassis Type list
                                          in the SMBIOS specification.  This
                                          value cannot be 0.

  /bb_mfg "Baseboard Manufacturer string" Specifies the Baseboard Manufacturer
                                          string for a given system. If not
                                          specified the value is assumed to be
                                          NULL.

  /bb_product "Baseboard Product string"  Specifies the ProductName string for
                                          a given baseboard. If not specified the
                                          value is assumed to be NULL.

  /sku      "SKU Number string"           Specifies the SKU Number string
                                          for the system. If not specified
                                          the value is assumed to be NULL.

  /verbose  "true or false"               Specifies whether to print more
                                          information than just the GUIDs. If
                                          not specified verbose output is
                                          assumed.

  /?                                      List of the command line options and
                                          usage.
  -----------------------------------------------------------------------------

  Up to fifteen HardwareIds will be generated depending on the following:
  * The BIOS fields available on the local system when no arguments are
    specified.
  * The command line arguments specified.

  Each of the following HardwareIds will be generated if the indicated BIOS
  fields or arguments are available:

  HardwareId 1 : Manufacturer + Family + Product Name + SKU Number + BIOS Vendor
                     + BIOS Version + BIOS Major Release + BIOS Minor Release
      [required]   /ven, /ver, /mfg, /product and /sku
      [optional]   /major, /minor, and /family

  HardwareId 2 : Manufacturer + Family + Product Name + BIOS Vendor
                     + BIOS Version + BIOS Major Release + BIOS Minor Release
      [required]   /ven, /ver, /mfg, and /product
      [optional]   /major, /minor, and /family

  HardwareId 3 : Manufacturer + Product Name + BIOS Vendor
                     + BIOS Version + BIOS Major Release + BIOS Minor Release
      [required]   /ven, /ver, /mfg, and /product
      [optional]   /major and /minor

  HardwareId 4 : Manufacturer + Family + ProductName + SKU Number + Baseboard Manufacturer + Baseboard Product
      [required]   /mfg, /product, /sku, /bb_mfg, and /bb_product
      [optional]   /family

  HardwareId 5 : Manufacturer + Family + ProductName + SKU Number
      [required]   /mfg, /product, and /sku
      [optional]   /family

  HardwareId 6 : Manufacturer + Family + ProductName
      [required]   /mfg, and /product
      [optional]   /family

  HardwareId 7 : Manufacturer + SKU Number + Baseboard Manufacturer + Baseboard Product
      [required]   /mfg, /sku, /bb_mfg, and /bb_product

  HardwareId 8 : Manufacturer + SKU Number
      [required]   /mfg and /sku

  HardwareId 9 : Manufacturer + ProductName + Baseboard Manufacturer + Baseboard Product
      [required]   /mfg, /product, /bb_mfg, and /bb_product

  HardwareId 10 : Manufacturer + ProductName
      [required]   /mfg and /product

  HardwareId 11 : Manufacturer + Family + Baseboard Manufacturer + Baseboard Product
      [required]   /mfg, /family, /bb_mfg, and /bb_product

  HardwareId 12 : Manufacturer + Family
      [required]   /mfg and /family

  HardwareId 13 : Manufacturer + Enclosure Type
      [required]   /mfg and /enclosure

  HardwareId 14: Manufacturer + Baseboard Manufacturer + Baseboard Product
      [required]   /mfg, /bb_mfg, and /bb_product

  HardwareId 15: Manufacturer
      [required]   /mfg

  Refer to the System Management (SMBIOS) Specification for additional
  details on these BIOS fields.

  BIOS Field Name                  Structure Name (Type)              Offset
  -----------------------------------------------------------------------------
  Baseboard Manufacturer           Baseboard Information (Type 2)     04h

  Baseboard Product                Baseboard Information (Type 2)     05h

  System Manufacturer              System Information (Type 1)        04h

  System Family                    System Information (Type 1)        1Ah

  System Product Name              System Information (Type 1)        05h

  SKU Number                       System Information (Type 1)        19h

  BIOS Vendor                      BIOS Information (Type 0)          04h

  BIOS Version                     BIOS Information (Type 0)          05h

  System BIOS Major Release        BIOS Information (Type 0)          14h

  System BIOS Minor Release        BIOS Information (Type 0)          15h

  Enclosure type                   System Enclosure (Type 3)          05h
  -----------------------------------------------------------------------------

EXAMPLES

  Generating HardwareIds from the BIOS:

  ComputerHardwareIds.exe

  Generating HardwareIds from command line arguments:

  ComputerHardwareIds.exe /ven "Contoso Ltd." /ver "0.158" /major "12"
    /minor "9" /mfg "Contoso" /family "Q Workstation" /product "3C273"
    /enclosure "6"

C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\computerhardwareids.exe version
  10.0.19041.1

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\computerhardwareids.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ComputerHardwareIds.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a





MIT License. Copyright (c) 2020 Strontic.


