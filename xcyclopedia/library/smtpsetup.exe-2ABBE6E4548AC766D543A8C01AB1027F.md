---
title: smtpsetup.exe | SMTP Setup
---

# smtpsetup.exe 

* File Path: `C:\Windows\system32\inetsrv\smtpsetup.exe`
* Description: SMTP Setup

## Hashes

Type | Hash
-- | --
MD5 | `2ABBE6E4548AC766D543A8C01AB1027F`
SHA1 | `5A889D21B35F7D3DD0C28B350E09A77A05DE2606`
SHA256 | `7EF026867E6A6CED14F07E5DDAE6827E7101B1037FCD37252341B03AB1B79EA3`
SHA384 | `B502E44D32E15D7549898D14DF77127A3F6EE18CEDD32AC9F3E45815F5FE5C938EB5997DEBCA8D8C402CE821CF83C91F`
SHA512 | `282BB5A8BA4CA44E381D2A7248A81AE31547483990E513D94AAB192C3C9E7B1CB3A0C834BA7307F112280DED280ECA46FDC80FAFFC26B711C017901B273EE359`
SSDEEP | `768:ILLGnj9BNRTlE3ici4q81Rz1G1daowB73WOXeK7mjVlPfbp8S8dzL5+izz:IunHNXf4Z1Rz1Yaowjpmh1pK1Ntz`

## Runtime Data

### Usage (stdout):
```cmhg

Description: smtpsetup.exe runs the installation and uninstallation of SMTP
components.

Usage:
smtpsetup [/uninstall | /install] <component-name> [/inf <inf-file-name>]
          [/debug]

Options:

    /uninstall       Uninstall the named component.
    /install         Install the named component.
    <component-name> The component to install or uninstall. Possible values 
                     are Common, Service, and Admin.
    /inf             Specify INF file name.
    <inf-file-name>  The path to the INF file.
                     Default is "smtp.inf"
    /debug           Enable debugging output.


```

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: smtpsetup.exe.mui
* Product Name: Internet Information Services
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


