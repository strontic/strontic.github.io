---
title: dcdiag.exe | Active Directory Domain Services / Lightweight Directory Services diagnosis utility
excerpt: What is dcdiag.exe?
---

# dcdiag.exe 

* File Path: `C:\Windows\SysWOW64\dcdiag.exe`
* Description: Active Directory Domain Services / Lightweight Directory Services diagnosis utility

## Hashes

Type | Hash
-- | --
MD5 | `CA1502D2B3342A4F8890FC8A120E4B32`
SHA1 | `5A1623C5C2D48E5019D2539DCB2B2B8450F98DF7`
SHA256 | `DBEFECE2B296A91054C674EC3F9246879D02E1D76AC56EB2DBA803EE2E9D971D`
SHA384 | `807A1465739EC846B34514651F88DD723D16D44121AE3EE7A252C87A2042D7E31852851F5309C28325921E1E6A8A9233`
SHA512 | `C6B0C78E93EB67C2FF94F09E95F02D2851D8DA3243CE64DAAAA69AA8CE25AB030AB00409FE232051DE2C81D1471F431548E556A3B23EB47166B8C6FCE9DFBF30`
SSDEEP | `6144:NSqTJfoS39xraJenrUT19gcIsiAfCW/hXDRTZgOL2ftP5wSolD6AWL1AzaHqkLWF:NSnvHd3R4Z5foIp3qKfePAv9r/H2`

## Runtime Data

### Usage (stdout):
```cmhg

 Directory Server Diagnosis

dcdiag.exe /s:<Directory Server>[:<LDAP Port>] [/u:<Domain>\<Username>
/p:*|<Password>|""] 
           [/hqv] [/n:<Naming Context>] [/f:<Log>] [/x:XMLLog.xml]
           [/skip:<Test>] [/test:<Test>]
   /h: Display this help screen

   /s: Use <Directory Server> as Home Server. Ignored for DcPromo and
       RegisterInDns tests which can only be run locally.
   /n: Use <Naming Context> as the Naming Context to test
       Domains may be specified in Netbios, DNS or DN form.
   /u: Use domain\username credentials for binding.
       Must also use the /p option

   /p: Use <Password> as the password.  Must also use the /u option
   /a: Test all the servers in this site
   /e: Test all the servers in the entire enterprise.  Overrides /a
   /q: Quiet - Only print error messages
   /v: Verbose - Print extended information
   /i: ignore - ignores superfluous error messages.
   /c: Comprehensive, runs all tests, including non-default tests but excluding
       DcPromo and RegisterInDNS. Can use with /skip
   /fix: fix - Make safe repairs.
   /f: Redirect all output to a file <Log> seperately
   /x:<XMLLog.xml> Redirect xml output to <XMLLog.xml>. Currently works with
/test:dns option only
   /xsl:<xslfile.xsl or xsltfile.xslt> Adds the processing instructions that
references specified stylesheet. Works with /test:dns /x:<XMLLog.xml> option
only

   /test:<TestName> - Test only this test.  Required tests will still
                      be run.  Do not mix with /skip.

   /skip:<TestName> - Skip the named test.  Required tests will still
                      be run.  Do not mix with /test.

   The list of known tests:

	Advertising  
             Checks whether each DSA is advertising itself, and whether it is
            advertising itself as having the capabilities of a DSA. 

	CheckSDRefDom  
             This test checks that all application directory partitions have
            appropriate security descriptor reference domains. 

	CheckSecurityError  
             Locates security errors (or those possibly security related) and
            performs the initial diagnosis of the problem. Optional Arguments:
            /ReplSource:<Source DC> to target a specific source, regardless of
            it's error status.  Need not be a current partner. 
	  * Test is not run by default, i.e. it must be requested explicitly

	Connectivity  
             Tests whether DSAs are DNS registered, pingeable, and have
            LDAP/RPC connectivity. 
	  * Test cannot be skipped
	  * Test is applicable to AD/LDS

	CrossRefValidation  
             This test looks for cross-refs that are in some way invalid. 
	  * Test is applicable to AD/LDS

	CutoffServers  
             Check for servers that won't receive replications because its
            partners are down 
	  * Test is not run by default, i.e. it must be requested explicitly
	  * Test is applicable to AD/LDS

	DcPromo  
             Tests the existing DNS infrastructure for promotion to domain
            controller. If the infrastructure is sufficient, the computer can
            be promoted to domain controller in a domain specified in
            <Active_Directory_Domain_DNS_Name>. Reports whether any
            modifications to the existing DNS infrastructure are required.
            Required argument: /DnsDomain:<Active_Directory_Domain_DNS_Name>
            One of the following arguments is required: /NewForest /NewTree
            /ChildDomain /ReplicaDC If NewTree is specified, then the
            ForestRoot argument is required:
            /ForestRoot:<Forest_Root_Domain_DNS_Name> 

	DNS  
             This test checks the health of DNS settings for the whole
            enterprise. Sub tests can be run individually using the switches
            below. By default, all tests except external name resolution are
            run)         /DnsBasic            (basic tests, can't be skipped)
                  /DnsForwarders            (forwarders and root hints tests)
                  /DnsDelegation            (delegations tests)
            /DnsDynamicUpdate            (dynamic update tests)
            /DnsRecordRegistration            (records registration tests)
               /DnsResolveExtName            (external name resolution test)
                 /DnsAll            (includes all tests above)
            /DnsInternetName:          <internet name> (for test
            /DnsResolveExtName)         (default is www.microsoft.com) 
	  * Test is not run by default, i.e. it must be requested explicitly

	FrsEvent  
             This test checks to see if there are any operation errors in the
            file replication system (FRS).  Failing replication of the SYSVOL
            share, can cause Policy problems.  

	DFSREvent  
             This test checks to see if there are any operation errors in the
            DFS. 

	SysVolCheck  
             This test checks that the SYSVOL is ready. 

	LocatorCheck  
             Checks that global role-holders are known, can be located, and are
            responding. 

	Intersite  
             Checks for failures that would prevent or temporarily hold up
            intersite replication. 

	KccEvent  
             This test checks that the Knowledge Consistency Checker is
            completing without errors.  
	  * Test is applicable to AD/LDS

	KnowsOfRoleHolders  
             Check whether the DSA thinks it knows the role holders, and prints
            these roles out in verbose mode. 

	MachineAccount  
             Check to see if the Machine Account has the proper information. Use
            /RecreateMachineAccount to attempt a repair if the local machine
            account is missing. Use /FixMachineAccount if the machine account
            flags are incorrect. 

	NCSecDesc  
             Checks that the security descriptosrs on the naming context heads
            have appropriate permissions for replication.  

	NetLogons  
             Checks that the appropriate logon priviledges allow replication to
            proceed. 

	ObjectsReplicated  
             Check that Machine Account (AD only) and DSA objects have
            replicated. Use /objectdn:<dn> with /n:<nc> to specify an
            additional object to check. 
	  * Test is applicable to AD/LDS

	OutboundSecureChannels  
             See if we have secure channels from all of the DC's in the domain
            the domains specified by /testdomain:. /nositerestriction will
            prevent the test from being limited to the DC's in the site. 
	  * Test is not run by default, i.e. it must be requested explicitly

	RegisterInDNS  
             Tests whether this directory server can register the directory
            Server Locator DNS records. These records must be present in DNS in
            order for other computers to locate this directory server for the
            <Active_Directory_Domain_DNS_Name> domain. Reports whether any
            modifications to the existing DNS infrastructure are required.
            Required argument: /DnsDomain:<Active_Directory_Domain_DNS_Name> 

	Replications  
             Checks for timely replication between directory servers. 
	  * Test is applicable to AD/LDS

	RidManager  
             Check to see if RID master is accessable and to see if it contains
            the proper information. 

	Services  
             Check to see if appropriate supporting services are running. 
	  * Test is applicable to AD/LDS

	SystemLog  
             This test checks that the system is running without errors.  
	  * Test is applicable to AD/LDS

	Topology  
             Checks that the generated topology is fully connected for all DSAs.
             
	  * Test is not run by default, i.e. it must be requested explicitly
	  * Test is applicable to AD/LDS

	VerifyEnterpriseReferences  
             This test verifys that certain system references are intact for the
            FRS and Replication infrastructure across all objects in the
            enterprise on each DSA.  
	  * Test is not run by default, i.e. it must be requested explicitly

	VerifyReferences  
             This test verifys that certain system references are intact for the
            FRS and Replication infrastructure.  

	VerifyReplicas  
             This test verifys that all application directory partitions are
            fully instantiated on all replica servers. 
	  * Test is not run by default, i.e. it must be requested explicitly
	  * Test is applicable to AD/LDS


	All tests except DcPromo and RegisterInDNS must be run on computers
	after they have been promoted to directory server.

	Note: Text (Naming Context names, server names, etc) with
International or
	Unicode characters will only display correctly if appropriate fonts
and
	language support are loaded

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SysWOW64\dcdiag.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dcdiag.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\dsmgmt.exe](dsmgmt.exe-6222DD5B0F8120806673AB634E5844FB.md) | 41
[C:\Windows\SysWOW64\repadmin.exe](repadmin.exe-D79A33E972B365D254CD6B9718DCB213.md) | 35




MIT License. Copyright (c) 2020-2021 Strontic.


