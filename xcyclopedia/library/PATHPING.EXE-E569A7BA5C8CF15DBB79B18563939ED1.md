
# PATHPING.EXE 
* File Path: `C:\WINDOWS\system32\PATHPING.EXE`
* Description: TCP/IP PathPing Command
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `E569A7BA5C8CF15DBB79B18563939ED1`
SHA1 | `CFC5C1ED1D916F92CA0276BDB4C1E2C5138AEA19`
SHA256 | `9BF3289456E40A0F8BC5C4B1920F764BB5A45C19BC92D2B4D348FD64EE367460`
SHA384 | `CAB13EF2FA92703CADE531A55C21FC7F8A1290ECCC2B328E40BE7E7FF4F022AE247CF7CB6C53C86E1FEB8CECEB409603`
SHA415 | `79B03E63AD213B257FE2B4191720FD63E2ED79B100FDF7A719F87D75F889FB9A569497D640F83BFE1D2EF0A356EBB037B9FEC1A474517900D685A20C7F18DE5B`
SSDEEP | `384:ihhn9RQsXowY4m7r68bd2JqLWb5ztmTL8SNgfWUAW:oYNHdkB94TL8J`

## Runtime Data
### Usage (stdout):
```Batchfile

Usage: pathping [-g host-list] [-h maximum_hops] [-i address] [-n] 
                [-p period] [-q num_queries] [-w timeout] 
                [-4] [-6] target_name

Options:
    -g host-list     Loose source route along host-list.
    -h maximum_hops  Maximum number of hops to search for target.
    -i address       Use the specified source address. 
    -n               Do not resolve addresses to hostnames.
    -p period        Wait period milliseconds between pings.
    -q num_queries   Number of queries per hop.
    -w timeout       Wait timeout milliseconds for each reply.
    -4               Force using IPv4.
    -6               Force using IPv6.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pathping.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


