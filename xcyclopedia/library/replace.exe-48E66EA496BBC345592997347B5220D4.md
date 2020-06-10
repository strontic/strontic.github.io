
# replace.exe 
* File Path: `C:\Windows\SysWOW64\replace.exe`
* Description: Replace File Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `48E66EA496BBC345592997347B5220D4`
SHA1 | `20D17BBEA61B1F98CE4BAEF5E57DDDD0AC1E4947`
SHA256 | `E6FC8FA07A57A0D5AF992B49C67EBF65CE7297D7BE8EEBCE645EE78041580897`
SHA384 | `3EE8ED7B371AF93F234A82802A37515799F8340B5161E09F8F4192768328AD1DAF753146B16B10E90A33D81789EBC89B`
SHA415 | `36D3BA2CF14A27BA6037D9E238E4A60A1ED211DDDEF9BFB9D657C384EC150484175DEC39F6DDE404BFFF0EFDB53C91394393C8D89F0BE011A05A020C82FF144F`
SSDEEP | `384:tvp8Vc0mTVLYq6lDRP5QeXXgsDg7rF9KKdlWFh/WoR4:tRuc/VkdNRPevUg9p8T`

## Runtime Data
### Usage (stdout):
```Batchfile
Replaces files.

REPLACE [drive1:][path1]filename [drive2:][path2] [/A] [/P] [/R] [/W]
REPLACE [drive1:][path1]filename [drive2:][path2] [/P] [/R] [/S] [/W] [/U]

  [drive1:][path1]filename Specifies the source file or files.
  [drive2:][path2]         Specifies the directory where files are to be
                           replaced.
  /A                       Adds new files to destination directory. Cannot
                           use with /S or /U switches.
  /P                       Prompts for confirmation before replacing a file or
                           adding a source file.
  /R                       Replaces read-only files as well as unprotected
                           files.
  /S                       Replaces files in all subdirectories of the
                           destination directory. Cannot use with the /A
                           switch.
  /W                       Waits for you to insert a disk before beginning.
  /U                       Replaces (updates) only files that are older than
                           source files. Cannot use with the /A switch.

```

### Usage (stderr):
```Batchfile
Invalid switch - -help

```

### Child Processes:
RdpSa.exe

## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: REPLACE.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


